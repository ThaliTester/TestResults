#### Test 846390997f1f1fd_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-09 14:24:24.990  1035  2113 V SIM_STK : Menu title from STK is T-Mobile
--------- beginning of system
09-09 14:24:24.993  1035  1050 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6529 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 14:24:25.090  4632  6525 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 155 ms] updated apps [took 155 ms] 
09-09 14:24:25.282  6529  6529 D DocsApplication: Installing DEX configuration.
09-09 14:24:25.307  6529  6529 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-09 14:24:25.312  6529  6529 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1c4d9940 com.google.android.apps.docs}
09-09 14:24:25.330  6529  6529 D TAG     : onCreate()
09-09 14:24:25.355  6529  6529 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,09-09 14:24:26.099  1839  4765 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-09 14:24:26.154  1839  4765 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-09 14:24:26.212  1839  4765 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
09-09 14:24:26.241  6556  6556 D AndroidRuntime: 
09-09 14:24:26.241  6556  6556 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 14:24:26.244  6556  6556 D AndroidRuntime: CheckJNI is OFF
09-09 14:24:26.378  6556  6556 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 14:24:26.383  1035  1051 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 14:24:26.407  1967  1983 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-09 14:24:26.410  1035  1051 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-09 14:24:26.412  1035  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{365f1324 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 14:24:26.412  1035  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{365f1324 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 14:24:26.413  1035  1051 D WindowStateEx: AppWindowTokenEx init.. 
09-09 14:24:26.414   344   357 E GBMv2   : DFP En is all cleared set to be enabled
09-09 14:24:26.470  1035  1051 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6588 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 14:24:26.471  6556  6556 D AndroidRuntime: Shutting down VM
09-09 14:24:26.516  1967  4011 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-09 14:24:26.516  1967  4011 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ebe2abc co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 14:24:26.517  1967  1982 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-09 14:24:26.517  1967  1982 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2165aa45 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 14:24:26.578  6588  6588 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-09 14:24:26.645  6588  6588 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-09 14:24:26.653  6588  6588 I LibraryLoader: Loading: webviewchromium
09-09 14:24:26.656  6588  6588 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4083-4087)
09-09 14:24:26.656  6588  6588 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:24:26.671  6588  6588 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1badebca}
,09-09 14:24:26.672  6588  6588 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:24:26.672  6588  6588 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 14:24:26.688  6588  6588 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 14:24:26.689  6588  6588 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 14:24:26.703   316   316 V AudioPolicyService: registerClient() client 0xb0410560, uid 10118
,09-09 14:24:26.703  6588  6588 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-09 14:24:26.704  6588  6588 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-09 14:24:26.704  6588  6588 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-09 14:24:26.706  1035  1117 D BluetoothManagerService: Message: 20
09-09 14:24:26.706  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1309f68e:true
09-09 14:24:26.715  6588  6588 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:24:26.715  6588  6588 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:24:26.715  6588  6588 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:24:26.715  6588  6588 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:24:26.715  6588  6588 I Adreno-EGL: Remote Branch: 
09-09 14:24:26.715  6588  6588 I Adreno-EGL: Local Patches: 
09-09 14:24:26.715  6588  6588 I Adreno-EGL: Reconstruct Branch: 
09-09 14:24:26.792  6588  6620 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-09 14:24:26.795  6588  6588 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-09 14:24:26.819  6588  6588 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 14:24:26.824  6588  6588 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 14:24:26.827  6588  6588 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-09 14:24:26.830  6588  6588 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-09 14:24:26.830  6588  6588 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-09 14:24:26.845  6588  6588 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-09 14:24:26.851  6588  6588 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 14:24:26.851  6588  6588 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 14:24:26.878  6588  6632 D OpenGLRenderer: Render dirty regions requested: true
09-09 14:24:26.878  6588  6632 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 14:24:26.884  6588  6632 D OpenGLRenderer: Enabling debug mode 0
,09-09 14:24:26.894  6588  6588 D Atlas   : Validating map...
09-09 14:24:26.899  1035  1984 D SplitWindow: check instance of lgWin Window{3b1291d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 14:24:26.937  6588  6630 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:26.937  6588  6630 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:24:27.033  6529  6529 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:27.033  6529  6529 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:24:27.044  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +530ms (total +630ms)
09-09 14:24:27.045  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10284e8d u0 com.test.thalitest/.MainActivity t6} time:104476
09-09 14:24:27.047  6588  6588 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@14deed21 time:104478
09-09 14:24:27.151  6588  6588 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 14:24:27.191  6588  6588 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-09 14:24:27.191  6588  6588 I chromium: 
,09-09 14:24:27.228  6588  6630 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-09 14:24:27.228  6588  6630 I chromium: 
,09-09 14:24:27.241  6164  6164 I LockScreenSettings: New app installed broadcast received ..
,09-09 14:24:27.246  6164  6164 I LockScreenSettings: Number of installed packages  1
09-09 14:24:27.256  6529  6529 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-09 14:24:27.302  1035  2030 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:24:27.363  1035  1986 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6660 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 14:24:27.368  6588  6659 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
09-09 14:24:27.376  6588  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 14:24:27.376  6588  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 14:24:27.376  6588  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 14:24:27.376  6588  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 14:24:27.376  6588  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 14:24:27.376  6588  6659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a615815 added. We now have 1 listener(s)
09-09 14:24:27.381  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:24:27.383  6588  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-09 14:24:27.385  6588  6659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:24:27.386  6588  6659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:24:27.387  6588  6659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 14:24:27.395  6588  6659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc7dab8 added. We now have 1 listener(s)
09-09 14:24:27.395  6588  6659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:24:27.399  1035  1543 D WifiService: New client listening to asynchronous messages
09-09 14:24:27.403  6588  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:24:27.403  6588  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 14:24:27.403  6588  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2,
09-09 14:24:27.404  6588  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 14:24:27.404  6588  6659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 14:24:27.406  6588  6659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:27.407  1035  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:24:27.408  6588  6659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-09 14:24:27.411  6660  6660 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-09 14:24:27.411  6660  6660 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
09-09 14:24:27.416  6588  6659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 14:24:27.417  6588  6659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:27.417  6588  6659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:27.417  6588  6659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:27.417  6588  6659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:27.417  6588  6659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:27.417  6588  6659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:27.417  6588  6659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:27.417  6588  6659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:27.417  6588  6659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 14:24:27.417  6588  6659 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:24:27.417  6588  6659 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 14:24:27.418  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:27.420  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:27.448  6588  6588 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 14:24:27.455  1035  1731 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6681 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-09 14:24:27.456  1035  1731 I ActivityManager: Killing 5848:com.google.android.gm/u0a64 (adj 15): empty #17
09-09 14:24:27.570  1035  1575 W libprocessgroup: failed to open /acct/uid_10064/pid_5848/cgroup.procs: No such file or directory
,09-09 14:24:27.653  6681  6681 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-09 14:24:27.674  6681  6681 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-09 14:24:27.682  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-09 14:24:27.713  6396  6396 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,09-09 14:24:27.713  1035  1051 I ActivityManager: Killing 5892:com.google.android.talk/u0a72 (adj 15): empty #17
09-09 14:24:27.825  1035  2009 W libprocessgroup: failed to open /acct/uid_10072/pid_5892/cgroup.procs: No such file or directory
,09-09 14:24:28.308   344   360 E GBMv2   : DFP En is all cleared set to be enabled
09-09 14:24:28.309   344   360 E GBMv2   : Set value is all cleared set the max
,09-09 14:24:28.309   344   360 I GBMv2   : DFP Enabled. Ignore VFP set
09-09 14:24:28.379  6588  6680 W jxcore-log: Initializing JXcore engine
,09-09 14:24:28.379  6588  6680 W jxcore-log: JXcore engine is ready
,09-09 14:24:28.412  6680  6680 W Thread-747: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8408]" dev="sockfs" ino=8408 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-09 14:24:28.412  6680  6680 W Thread-747: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-09 14:24:28.412  6680  6680 W Thread-747: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7591]" dev="sockfs" ino=7591 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-09 14:24:28.412  6680  6680 W Thread-747: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-09 14:24:28.412  6680  6680 W Thread-747: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30688]" dev="sockfs" ino=30688 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-09 14:24:28.430  6588  6680 W jxcore-log: Starting JXcore engine
09-09 14:24:28.503  6588  6680 W jxcore-log: Platform android
09-09 14:24:28.503  6588  6680 W jxcore-log: 
09-09 14:24:28.503  6588  6680 W jxcore-log: Process ARCH arm
09-09 14:24:28.503  6588  6680 W jxcore-log: 
,09-09 14:24:28.694  6588  6680 I jxcore-log: JXcore Cordova bridge is ready!
09-09 14:24:28.694  6588  6680 I jxcore-log: 
09-09 14:24:28.695  6588  6680 W jxcore-log: JXcore engine is started
,09-09 14:24:28.700  6588  6659 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 14:24:28.702  6588  6588 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 14:24:29.102  2795  2795 I MusicWidget: mDelayedStopHandler : unbind
,09-09 14:24:29.107  2167  2167 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,09-09 14:24:29.108  2167  2167 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
,09-09 14:24:29.116  2167  2167 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-09 14:24:29.119  2167  2167 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-09 14:24:29.120  2167  2167 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-09 14:24:29.120  2167  2167 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-09 14:24:29.121  2167  2167 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-09 14:24:29.122  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-09 14:24:29.123  1035  1984 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2318cf2bcom.lge.music.MediaPlaybackService$5@26f17f88
09-09 14:24:29.124  2167  2167 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-09 14:24:29.124  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 14:24:29.125  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 14:24:29.126  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 14:24:29.127  2167  2167 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@7a6fa96
09-09 14:24:29.127  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 14:24:29.127  2167  2167 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-09 14:24:29.128  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 14:24:29.128  2167  2167 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-09 14:24:29.128  2167  2167 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-09 14:24:29.128  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-09 14:24:29.132  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 14:24:29.132  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 14:24:29.133  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 14:24:29.134  2167  2167 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 14:24:29.135  2167  2167 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-09 14:24:29.136  2167  2167 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-09 14:24:29.136  2167  2167 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-09 14:24:29.136  2167  2167 V MediaPlayer[Native]: reset
09-09 14:24:29.143  2167  2167 V MediaPlayer[Native]: setListener
09-09 14:24:29.143  2167  2167 V MediaPlayer[Native]: disconnect
09-09 14:24:29.143  2167  2167 V MediaPlayer[Native]: destructor
09-09 14:24:29.143   316   316 V AudioFlinger: releasing 18 from 2167 for -1
09-09 14:24:29.143   316   316 V AudioFlinger:  decremented refcount to 0
09-09 14:24:29.143   316   316 V AudioFlinger: purging stale effects
09-09 14:24:29.143  2167  2167 V MediaPlayer[Native]: disconnect
,09-09 14:24:29.149  2167  2167 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-09 14:24:29.150  2167  2167 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-09 14:24:29.151  2167  2167 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-09 14:24:29.152  2167  2167 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-09 14:24:29.152  2167  2167 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-09 14:24:29.152  2167  2167 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-09 14:24:29.152  2167  2167 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 350154017
09-09 14:24:29.153  2167  2167 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 350154017
09-09 14:24:29.160  2167  2167 I SmartShareClient: [SmartShareManagerClient] terminate service: 2167/MediaPlaybackService/236128620
09-09 14:24:29.164  2167  2167 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-09 14:24:29.164  2167  2167 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@17b13546
,09-09 14:24:29.168  2167  2167 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-09 14:24:29.168  2167  2167 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-09 14:24:29.169  2167  2167 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-09 14:24:29.170  2167  2167 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-09 14:24:29.172  1035  1965 I ActivityManager: Killing 5682:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-09 14:24:29.173  2167  2167 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
09-09 14:24:29.191  5602  5602 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-09 14:24:29.192  5602  5602 W System.err: android.os.DeadObjectException
09-09 14:24:29.192  5602  5602 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 14:24:29.192  5602  5602 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 14:24:29.192  5602  5602 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 14:24:29.192  5602  5602 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-09 14:24:29.192  5602  5602 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 14:24:29.192  5602  5602 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 14:24:29.192  5602  5602 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:24:29.192  5602  5602 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:24:29.192  5602  5602 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:24:29.192  5602  5602 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:24:29.192  5602  5602 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:29.192  5602  5602 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:24:29.192  5602  5602 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:24:29.192  5602  5602 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:24:29.193  5602  5602 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 14:24:29.193  5602  5602 W System.err: android.os.DeadObjectException
09-09 14:24:29.193  5602  5602 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 14:24:29.193  5602  5602 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 14:24:29.193  5602  5602 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 14:24:29.193  5602  5602 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-09 14:24:29.193  5602  5602 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 14:24:29.193  5602  5602 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 14:24:29.193  5602  5602 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:24:29.193  5602  5602 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:24:29.193  5602  5602 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:24:29.193  5602  5602 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,09-09 14:24:29.193  5602  5602 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:29.193  5602  5602 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:24:29.193  5602  5602 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:24:29.194  5602  5602 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704),
09-09 14:24:29.194  5602  5602 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 14:24:29.194  5602  5602 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-09 14:24:29.382  1035  1965 E libprocessgroup: failed to kill 1 processes for processgroup 5682
,09-09 14:24:29.619  1035  1731 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-09 14:24:29.626  5602  5602 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-09 14:24:29.627  5602  5602 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 14:24:29.698  1035  1051 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6713 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 14:24:29.713  5602  5602 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 14:24:29.773  6713  6713 D UEI.SmartControl: Quickset Services start...
09-09 14:24:29.775  6713  6713 I UEI.SmartControl: Manufacture = LGE
09-09 14:24:29.775  6713  6713 D UEI.SmartControl: Id = LGNevo
09-09 14:24:29.776  6713  6713 D UEI.SmartControl: File observer start...
09-09 14:24:29.777  6713  6713 E UEI.SmartControl: IR Port is disabled: false
09-09 14:24:29.777  6713  6713 D UEI.SmartControl: Starting file observer...
09-09 14:24:29.777  6713  6713 D UEI.SmartControl: Extracting JNI libs...
09-09 14:24:29.777  6713  6713 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-09 14:24:29.852  6713  6713 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 14:24:29.852  6713  6713 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-09 14:24:29.852  6713  6713 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-09 14:24:29.883  6713  6713 I UEI.SmartControl: --- Selecting new region: 6
,09-09 14:24:29.885  6713  6713 I UEI.SmartControl: Model = LG-D855
,09-09 14:24:29.887  6713  6713 D UEI.SmartControl: QS Service created
09-09 14:24:29.924  6713  6713 I UEI.SmartControl: Service initServices...
09-09 14:24:29.930  6713  6713 D UEI.SmartControl: QS start get config
,09-09 14:24:30.003  6713  6713 D UEI.SmartControl: Loading JNI Libs...
,09-09 14:24:30.355  6713  6713 I UEI.SmartControl: Supports setup maps: true
,09-09 14:24:30.362  6713  6713 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 14:24:30.362  6713  6713 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 14:24:30.362  6713  6713 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 14:24:30.362  6713  6713 I UEI.SmartControl: ### init IR Blaster...
09-09 14:24:30.368  6713  6713 D serial_port: Configuring serial port
09-09 14:24:30.378  6713  6713 E UEI.SmartControl: UEIBLaster setting for 616
09-09 14:24:30.378  6713  6713 I UEI.SmartControl: Setting serial record hearder size = 2
,09-09 14:24:30.379  6713  6713 I UEI.SmartControl: configuring settings for MAXQ616
09-09 14:24:30.380  6713  6713 I UEI.SmartControl: Get version...
09-09 14:24:30.398  6713  6736 D UEI.SmartControl: serial port data available: 21
,09-09 14:24:30.432  6713  6713 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 14:24:30.432  6713  6713 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 14:24:30.433  6713  6713 I UEI.SmartControl: QS saving settings...
09-09 14:24:30.435  6713  6713 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 14:24:30.456  6713  6736 D UEI.SmartControl: serial port data available: 4
,09-09 14:24:30.486  6713  6713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-09 14:24:30.488  6713  6713 E UEI.SmartControl: Services init done
09-09 14:24:30.499  6713  6742 I UEI.SmartControl: Device manager: loading config....
09-09 14:24:30.499  6713  6742 D UEI.SmartControl: ----------- loading internal config...
09-09 14:24:30.503  6713  6713 D UEI.SmartControl: QS Service init finished
09-09 14:24:30.504  6713  6713 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 14:24:30.504  6713  6713 D UEI.SmartControl: QS Service version code: 201091
09-09 14:24:30.505  6713  6713 D UEI.SmartControl: Service requested: Control
,09-09 14:24:30.509  6713  6742 E UEI.SmartControl: Loading SETTINGS...
09-09 14:24:30.512  6713  6713 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 14:24:30.517  1035  1705 I ActivityManager: Killing 5602:com.lge.qremote/u0a112 (adj 15): empty #17
09-09 14:24:30.524  6713  6742 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-09 14:24:30.534  6713  6741 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-09 14:24:30.534  6713  6741 D UEI.SmartControl: -----service ready thread exits
09-09 14:24:30.630  1035  2075 W libprocessgroup: failed to open /acct/uid_10112/pid_5602/cgroup.procs: No such file or directory
,09-09 14:24:30.636  6713  6713 D UEI.SmartControl: Internal service binding...
09-09 14:24:31.290  6529  6529 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
09-09 14:24:31.291  1035  1984 I ActivityManager: Killing 5232:com.android.calendar/u0a13 (adj 15): empty #17
,09-09 14:24:31.514  1035  1986 W libprocessgroup: failed to open /acct/uid_10013/pid_5232/cgroup.procs: No such file or directory
,09-09 14:24:32.128  6529  6641 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-09 14:24:34.266  1839  6450 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-09 14:24:34.272   309  6780 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 14:24:34.272   309  6780 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
,09-09 14:24:34.272   309  6780 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-09 14:24:35.486  6713  6743 D UEI.SmartControl: Internal timer expired: 1
09-09 14:24:35.486  6713  6743 D UEI.SmartControl: unbind internal service
,09-09 14:24:35.500  6713  6713 D UEI.SmartControl: Service.onUnbind: IControl
,09-09 14:24:35.501  6713  6713 D UEI.SmartControl: Service.onDestroy
09-09 14:24:35.501  6713  6713 D UEI.SmartControl: Lock is in USE false
09-09 14:24:35.501  6713  6713 D UEI.SmartControl: unbind internal service
09-09 14:24:35.501  6713  6713 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@7a6fa96
09-09 14:24:35.502  6713  6713 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-09 14:24:35.502  6713  6713 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-09 14:24:35.502  6713  6713 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-09 14:24:35.502  6713  6713 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-09 14:24:35.502  6713  6713 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-09 14:24:35.502  6713  6713 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-09 14:24:35.502  6713  6713 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-09 14:24:35.502  6713  6713 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-09 14:24:35.502  6713  6713 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:35.502  6713  6713 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:24:35.502  6713  6713 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:24:35.502  6713  6713 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:35.502  6713  6713 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:24:35.502  6713  6713 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:24:35.502  6713  6713 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:24:35.502  6713  6713 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@7a6fa96
09-09 14:24:35.504  6713  6713 D serial_port: close(fd = 25)
,09-09 14:24:35.549  6713  6713 I UEI.SmartControl: Serial port is closed.
09-09 14:24:35.549  6713  6713 I UEI.SmartControl: Serial port is closed.
09-09 14:24:35.550  6713  6713 D UEI.SmartControl: Blaster closed
,09-09 14:24:35.553  6713  6713 D UEI.SmartControl: Shut down QS...
,09-09 14:24:35.553  6713  6713 D UEI.SmartControl: Stopping QS lib
,09-09 14:24:35.553  6713  6713 D UEI.SmartControl: QS lib stop result = true
09-09 14:24:35.553  6713  6713 D UEI.SmartControl: Stopped QS lib
09-09 14:24:35.554  6713  6713 D UEI.SmartControl: Stopped file observer...
09-09 14:24:35.554  6713  6713 D UEI.SmartControl: QS shutdown complete
,09-09 14:24:37.522  1839  1839 I ConfigFetchService: fetch service done; releasing wakelock
,09-09 14:24:37.527  1839  1839 I ConfigFetchService: stopping self
,09-09 14:24:37.537  2219  2219 I ConfigService: onDestroy
,09-09 14:24:38.710  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 14:24:38.710  6588  6680 I jxcore-log: 
,09-09 14:24:38.713  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 14:24:38.713  6588  6680 I jxcore-log: 
,09-09 14:24:38.718  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:38.718  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:38.718  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:38.718  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:38.718  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:38.718  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:38.718  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:38.718  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:38.720  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:38.723  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 14:24:38.723  6588  6680 I jxcore-log: 
,09-09 14:24:38.725  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 14:24:38.725  6588  6680 I jxcore-log: 
,09-09 14:24:39.184  2167  2167 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
,09-09 14:24:39.239  6588  6680 D executeNativeTests: Running unit tests
,09-09 14:24:39.322  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 14:24:39.322  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 added. We now have 2 listener(s)
,09-09 14:24:39.323  1035  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:24:39.325  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-09 14:24:39.325  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:24:39.325  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:24:39.325  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:24:39.325  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a added. We now have 2 listener(s)
,09-09 14:24:39.325  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:24:39.325  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 14:24:39.328  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-09 14:24:39.330  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 14:24:39.330  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:39.330  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,09-09 14:24:39.330  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:39.330  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:39.330  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:39.330  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:39.330  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:39.331  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:24:39.331  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:24:39.332  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:39.333  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:39.336  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
,09-09 14:24:39.338  6588  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 14:24:39.338  6588  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,09-09 14:24:39.340  6588  6680 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 14:24:39.340  6588  6680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 14:24:39.340  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 14:24:39.340  6588  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-09 14:24:39.341  6588  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:24:39.341  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.342  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-09 14:24:39.342  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 14:24:39.342  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.343  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.343  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:39.343  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:24:39.343  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 removed from the list,
09-09 14:24:39.343  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.343  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a removed from the list
09-09 14:24:39.343  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.343  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:24:39.343  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.343  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.344  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.344  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.344  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:39.344  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.346  6588  6680 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 14:24:39.346  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.346  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 14:24:39.346  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.346  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.346  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.346  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.346  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list,
09-09 14:24:39.347  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.347  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.347  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.347  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:24:39.347  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.347  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.347  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.347  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.347  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-09 14:24:39.347  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.347  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
,09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 14:24:39.353  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-09 14:24:39.354  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 14:24:39.354  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 14:24:39.354  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 14:24:39.354  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.354  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 14:24:39.354  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.354  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.354  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.354  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.355  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list,
09-09 14:24:39.355  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.355  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.355  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.355  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.355  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 14:24:39.355  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.355  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.355  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.355  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:24:39.355  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.355  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.356  6588  6680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:24:39.357  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:39.359  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:39.359  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
09-09 14:24:39.359  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:39.359  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:39.359  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:39.359  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:39.359  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:39.359  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:39.360  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:39.360  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-09 14:24:39.361  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:39.361  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:24:39.361  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:24:39.361  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 14:24:39.361  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:39.361  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 14:24:39.363  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 14:24:39.365  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:24:39.366  1035  1965 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:39.369  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:24:39.372  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:24:39.374  6588  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
09-09 14:24:39.375  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:24:39.375  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:39.376  6588  6680 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:24:39.376  6588  6680 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 14:24:39.379  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.379  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.379  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.379  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.379  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:24:39.379  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:39.379  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.379  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.379  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
,09-09 14:24:39.379  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.379  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.380  6588  6680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:24:39.381  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:39.383  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,09-09 14:24:39.383  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:39.383  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:39.383  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:39.383  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:39.383  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:39.383  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:39.383  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:39.384  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:39.384  1035  1098 I ActivityManager: Waited long enough for: ServiceRecord{28c9aa8a u0 com.google.android.gms/.wearable.service.WearableService},
09-09 14:24:39.384  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:24:39.385  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 14:24:39.386  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:39.386  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:24:39.386  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:24:39.386  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 14:24:39.386  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:39.386  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:24:39.389  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:24:39.389  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:39.390  6588  6680 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-09 14:24:39.390  6588  6680 I io.jxcore.node.ConnectionHelper: start: OK
09-09 14:24:39.391  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.391  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.391  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.391  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 14:24:39.391  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.391  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:39.391  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.391  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:39.392  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.392  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.392  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.392  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.392  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 14:24:39.392  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.392  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.394  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.394  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.394  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 14:24:39.394  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.394  6588  6680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 14:24:39.396  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-09 14:24:39.397  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:39.397  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:39.397  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:39.397  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:39.397  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:39.397  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:39.397  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,09-09 14:24:39.397  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:39.398  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:39.398  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:24:39.399  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:39.400  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 14:24:39.400  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:24:39.400  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:24:39.400  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:39.400  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:39.400  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:24:39.403  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:24:39.403  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 14:24:39.404  6588  6680 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:24:39.404  6588  6680 I io.jxcore.node.ConnectionHelper: start: OK
09-09 14:24:39.404  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:24:39.404  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.404  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.405  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.405  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-09 14:24:39.405  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.405  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.405  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:24:39.405  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:24:39.405  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.405  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 14:24:39.405  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.405  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.405  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.405  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-09 14:24:39.405  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.406  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.406  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:24:39.406  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.406  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.406  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.406  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.407  6588  6680 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 14:24:39.407  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.407  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.407  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.407  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.407  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.407  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.407  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.407  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.407  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.407  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.407  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.407  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.407  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.407  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.408  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.408  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.408  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.408  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.408  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.409  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.409  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 14:24:39.409  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.409  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.409  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: ,The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.410  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.410  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.410  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.410  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.410  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.410  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.410  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.410  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.410  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.410  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.410  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.411  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.411  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.411  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.411  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.411  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.411  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.411  6588  6680 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 14:24:39.412  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.412  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.412  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.412  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.412  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.412  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.412  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.412  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.412  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.412  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.412  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.412  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.412  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.412  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.413  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.413  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.413  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.413  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.413  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.413  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.414  6588  6680 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 14:24:39.414  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.414  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.414  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.414  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.414  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.414  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.414  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.414  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.414  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.414  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.414  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.414  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.414  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.414  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.415  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.415  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.416  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.416  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.416  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.416  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.416  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 14:24:39.416  6588  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:24:39.416  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:24:39.416  6588  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:24:39.416  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 14:24:39.416  6588  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:24:39.416  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.417  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.417  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.417  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.417  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.417  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.417  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.417  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.417  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.417  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.417  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.417  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.417  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.417  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.418  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.418  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.419  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.419  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.419  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.419  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.419  6588  6680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:39.419  6588  6680 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 14:24:39.419  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 14:24:39.421  6588  6680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:39.421  6588  6680 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 14:24:39.421  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 14:24:39.422  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 14:24:39.422  6588  6680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 14:24:39.422  6588  6680 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:24:39.422  6588  6680 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 14:24:39.422  6588  6680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:39.422  6588  6680 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:24:39.422  6588  6680 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 14:24:39.422  6588  6680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:39.422  6588  6680 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:24:39.422  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 14:24:39.424  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 14:24:39.425  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 14:24:39.425  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 14:24:39.426  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 14:24:39.426  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 14:24:39.426  6588  6680 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 14:24:39.426  6588  6680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:24:39.426  6588  6680 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 14:24:39.426  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.426  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.426  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.426  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.426  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.426  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.427  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 14:24:39.427  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.427  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.427  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.427  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.427  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.427  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.427  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.427  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.428  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.428  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.429  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.429  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.429  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.429  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.430  6588  6787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 811
09-09 14:24:39.430  6588  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 811)
09-09 14:24:39.431  6588  6680 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 14:24:39.431  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.431  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.431  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.431  6588  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 811)
09-09 14:24:39.432  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.432  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.432  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.432  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.432  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.432  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.432  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.432  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.432  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.432  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.432  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.433  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.433  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.433  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.433  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.433  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.433  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.434  6588  6680 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 14:24:39.436  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.436  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.436  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.436  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.436  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.436  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.436  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.436  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 14:24:39.436  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.436  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.436  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.436  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.436  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.436  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.437  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.437  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.437  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.437  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.437  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.437  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.438  6588  6680 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 14:24:39.438  6588  6680 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 14:24:39.438  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:24:39.438  6588  6680 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 14:24:39.439  6588  6680 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 14:24:39.439  6588  6680 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 14:24:39.439  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:24:39.439  6588  6680 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 14:24:39.439  6588  6680 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 14:24:39.439  6588  6680 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 14:24:39.439  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:24:39.439  6588  6680 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 14:24:39.439  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.439  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.439  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.440  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.440  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.440  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.440  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.440  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.440  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.440  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.440  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.440  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.440  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.440  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.440  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.440  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.441  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.441  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.441  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.441  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.441  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.441  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.441  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.441  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.441  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.441  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.441  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.441  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.441  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.441  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.442  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.442  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.442  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.442  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.442  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.442  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.442  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.442  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.442  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.442  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.442  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.442  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.442  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.442  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.442  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.442  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.442  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.442  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.442  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.443  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.443  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.444  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.444  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.444  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.444  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.445  6588  6680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 14:24:39.445  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:39.445  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 14:24:39.446  6588  6680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 14:24:39.446  6588  6680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 14:24:39.446  6588  6588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 14:24:39.446  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 14:24:39.446  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:24:39.447  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.448  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 14:24:39.448  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 14:24:39.448  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 14:24:39.448  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.448  6588  6680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 14:24:39.448  6588  6588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 14:24:39.448  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.448  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.448  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:24:39.448  6588  6680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:24:39.448  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:24:39.449  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:24:39.449  6588  6788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 14:24:39.449  6588  6788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 14:24:39.450  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:24:39.451  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:24:39.451  6588  6680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:24:39.451  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.451  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.451  6588  6680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:24:39.452  6588  6588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:39.452  6588  6588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:24:39.452  6588  6588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 14:24:39.452  6588  6588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:24:39.452  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.452  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.452  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.452  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.452  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.452  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.452  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.452  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.452  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.452  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.452  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.452  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.452  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.452  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.452  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.453  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.453  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.453  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.453  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.453  6588  6680 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 14:24:39.454  6588  6680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 14:24:39.454  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:24:39.455  6588  6680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:24:39.455  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.455  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.455  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.455  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.455  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.455  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.455  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.455  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.455  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.455  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.455  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.455  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.455  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.455  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.456  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.456  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.456  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.456  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.457  1035  2076 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:39.458  1035  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:39.459  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:39.459  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.459  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.459  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.460  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.460  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.460  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.460  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.460  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.460  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.460  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.460  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.460  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.460  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.460  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.461  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.461  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.461  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.461  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.461  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:24:39.461  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:24:39.461  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:24:39.462  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:24:39.462  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.462  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.462  6588  6680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22c67fa5 not in the list
09-09 14:24:39.462  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.462  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.462  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:24:39.462  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.462  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.462  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:24:39.462  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:24:39.463  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:24:39.463  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:24:39.463  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:24:39.463  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2806cf7a not in the list
09-09 14:24:39.464  6588  6680 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 14:24:39.464  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:24:39.464  6588  6680 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 14:24:39.464  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:24:39.464  6588  6680 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 14:24:39.464  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:24:39.465  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 14:24:39.465  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 14:24:39.466  6588  6680 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 14:24:39.466  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 14:24:39.466  6588  6680 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 14:24:39.466  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 14:24:39.466  6588  6680 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 14:24:39.466  6588  6680 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 14:24:39.467  6588  6680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 14:24:39.467  6588  6680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 14:24:39.467  6588  6680 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 14:24:39.467  6588  6680 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 14:24:39.467  6588  6680 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 14:24:39.467  6588  6680 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 14:24:39.468  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:24:39.468  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20ff5ca3 added. We now have 2 listener(s)
09-09 14:24:39.468  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:39.470  6588  6680 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 14:24:39.470  1035  1966 D WifiServiceImplEx: setWifiEnabled: true pid=6588, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:24:39.471  1035  1966 D WifiService: setWifiEnabled: true pid=6588, uid=10118
09-09 14:24:39.471  1035  1966 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:24:39.471  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:24:39.472  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24064ba0 added. We now have 3 listener(s)
09-09 14:24:39.472  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:39.474  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:24:39.474  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f792359 added. We now have 4 listener(s)
09-09 14:24:39.474  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:39.475  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:24:39.475  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f2f5b1e added. We now have 5 listener(s)
09-09 14:24:39.476  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:24:39.477  1035  2075 D WifiServiceImplEx: setWifiEnabled: false pid=6588, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:24:39.477  1035  2075 D WifiService: setWifiEnabled: false pid=6588, uid=10118
09-09 14:24:39.477  1035  2075 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:24:39.487  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:24:39.487  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:24:39.487  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-09 14:24:39.488  1035  2113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:39.488  1035  2113 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3c866bd mBinding = false
09-09 14:24:39.489  1035  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:39.489  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:39.490  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:39.490  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:39.491  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:39.491  1035  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 14:24:39.491  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:24:39.491  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:24:39.492  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:24:39.492  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-09 14:24:39.499  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:24:39.499  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:24:39.499  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-09 14:24:39.499  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:24:39.499  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:24:39.499  2728  2728 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:24:39.499  1035  1117 D BluetoothManagerService: Message: 2
09-09 14:24:39.500  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:24:39.500  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:24:39.500  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:24:39.500  1035  1117 D BluetoothManagerService: Sending off request.
09-09 14:24:39.500   309   895 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:24:39.500  1035  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.501  3920  3940 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-09 14:24:39.501  3920  4000 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 14:24:39.502  3920  4000 D BluetoothAdapterProperties: Setting state to 13
09-09 14:24:39.502  3920  4000 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 14:24:39.502  3920  4000 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 14:24:39.502  3920  4000 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 14:24:39.504  1035  2866 D DhcpStateMachine: RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.506  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.507  3920  4003 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:24:39.507  3920  4000 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 14:24:39.509  3920  4295 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:39.509  3920  4000 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 14:24:39.509  3920  4317 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:39.511  3920  4275 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 14:24:39.511  3920  4275 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:39.511  3920  4275 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 14:24:39.511  3920  4275 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 14:24:39.511  3920  4275 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 14:24:39.511  3920  4275 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 14:24:39.511  3920  4275 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 14:24:39.511  3920  4275 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 14:24:39.511  3920  4276 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:39.512  3920  4297 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:39.512  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 14:24:39.513  3920  4094 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-09 14:24:39.514  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:39.514  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:24:39.514  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:39.514  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:39.514  3920  4094 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:24:39.514  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:24:39.514  3920  4094 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:39.515  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:39.515  3920  4094 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:24:39.515  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 14:24:39.515  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 14:24:39.515  3920  4094 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 14:24:39.516  1035  1117 D BluetoothManagerService: Message: 60
09-09 14:24:39.516  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 14:24:39.533  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-09 14:24:39.534  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:39.534  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:39.534  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:39.534  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:39.534  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:39.534  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:39.534  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:39.534  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:24:39.534  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:39.535  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:39.535  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:24:39.537  1035  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 14:24:39.538  1035  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-09 14:24:39.585  1035  1098 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6800 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-09 14:24:39.586  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:39.586  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:24:39.589  1035  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 14:24:39.589  1035  1544 D DSQN    : disableDataServiceNotify
09-09 14:24:39.589  3920  3920 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:39.589  1035  1544 D DSQN    : stop dsqn bin
09-09 14:24:39.589  3920  3920 D BluetoothMapService: STATE_TURNING_OFF
09-09 14:24:39.589  3920  3920 V BtOppService: Receiver DISABLED_ACTION 
09-09 14:24:39.589  3920  3920 V BluetoothMapService: Handler(): got msg=4
09-09 14:24:39.589  3920  3920 D BluetoothMapService: MAP Service closeService in
09-09 14:24:39.590  3920  3920 D BluetoothMapMasInstance: MAP Service shutdown
09-09 14:24:39.590  3920  3920 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:24:39.590  3920  3920 V BluetoothMapService: MAP Service closeService out
09-09 14:24:39.590  3920  3920 I BtOppRfcommListener: stopping Accept Thread
09-09 14:24:39.590  3920  3920 V BtOppRfcommListener: close mBtServerSocket
09-09 14:24:39.590  3920  3920 V BtOppRfcommListener: waiting for thread to terminate
09-09 14:24:39.590  3920  4295 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 14:24:39.591  3920  3920 V BtOppRfcommListener: done waiting for thread to terminate
09-09 14:24:39.592  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:39.592  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:39.592  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:39.592  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:39.592  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:39.592  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:39.592  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:39.592  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:39.592  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:39.592  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:39.592  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:39.594  1035  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 14:24:39.594  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:39.594  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:24:39.595  1035  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:24:39.595  1035  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 14:24:39.595  1035  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.595  1035  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util,.StateMachine$SmHandler }
09-09 14:24:39.595  1035  2862 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 14:24:39.596  1035  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 14:24:39.596  1035  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 14:24:39.596  1601  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 14:24:39.596  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-09 14:24:39.638  1035  1098 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6819 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 14:24:39.639  1035  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:39.639  3920  3920 V BtOppService: onDestroy
09-09 14:24:39.639  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:24:39.640  1035  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:39.640  1035  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:39.640  1035  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:39.641  1035  1544 D NetworkManagementService: Removing idletimer
09-09 14:24:39.641  1035  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:39.641  1035  1544 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 14:24:39.642  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-09 14:24:39.642  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:39.642  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:39.642  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:24:39.642  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 14:24:39.642  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 14:24:39.642  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:24:39.642  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:24:39.643  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:24:39.643  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:24:39.643  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:24:39.643  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:24:39.643  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 14:24:39.643  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 14:24:39.644  1878  1878 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:39.644  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:24:39.645  1967  1967 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 14:24:39.645  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.645  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.646  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:39.646  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTI,ES 0 0
09-09 14:24:39.646  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:39.646  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:39.646  1035  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@120ed78
09-09 14:24:39.647  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:39.647  1035  1537 D LGWifiP2pService: P2pDisablingState
09-09 14:24:39.647  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:39.647  1035  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.647  1035  1537 D LGWifiP2pService: p2p socket connection lost
09-09 14:24:39.647  1035  1537 D LGWifiP2pService: P2pDisabledState
09-09 14:24:39.647  1035  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 14:24:39.647  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:39.648  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:39.648  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:39.648  1035  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:39.650  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-09 14:24:39.650  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:39.650  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:39.650  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:24:39.650  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 14:24:39.650  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-09 14:24:39.650  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.650  1035  1557 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.651  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 14:24:39.651  1967  1967 D WfdsService: WifiP2pState is changed : false
09-09 14:24:39.651  1967  2387 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 14:24:39.651  1967  2387 D WfdsService: Set the WFDS Monitor: false
,09-09 14:24:39.652  1967  2387 D WfdsMonitor: WFDS Monitor is stopped
09-09 14:24:39.652  1967  2387 D WfdsService: STATE : WfdsDisabledState - enter
09-09 14:24:39.652  1967  2760 D CtrlSupplicant: Received on exit socket, terminate
09-09 14:24:39.652  1967  2760 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 14:24:39.652  1967  2760 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 14:24:39.652  1967  2760 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 14:24:39.652  1967  2388 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 14:24:39.652  1967  2387 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 14:24:39.652  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:24:39.653  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 14:24:39.653  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:24:39.653  2728  2728 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:24:39.653  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.653  1035  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.653  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:24:39.653  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:24:39.654  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:24:39.654   309   895 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:24:39.657  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-09 14:24:39.658  1035  1538 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 14:24:39.659  1035  1538 D WifiNative-p2p0: TERMINATE: returned true
09-09 14:24:39.659  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:24:39.659  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:24:39.659  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:24:39.659  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:39.659  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:39.659  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:24:39.660  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 14:24:39.662  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:39.662  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:39.663  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:24:39.665  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 14:24:39.665  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:39.665  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:39.665  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:39.665  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:39.665  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:39.665  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:39.665  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:39.665  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:39.665  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:39.666  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:39.666  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:39.670  1035  1731 I art     : Explicit concurrent mark sweep GC freed 26209(1366KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.950ms total 151.020ms
09-09 14:24:39.674  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:24:39.674  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,09-09 14:24:39.682  3920  3920 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 14:24:39.682  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:24:39.686  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:39.686  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:24:39.686  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:39.686  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:39.686  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-09 14:24:39.686  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:39.686  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:39.686  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:39.686  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:39.686  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:39.686  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:39.686  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:24:39.688  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:39.690  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:39.707  1035  2866 D DhcpStateMachine: StoppedState
09-09 14:24:39.707  1035  2866 D DhcpStateMachine: StoppedState{ when=-54ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:39.709  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 14:24:39.709  1035  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 14:24:39.729  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:24:39.730  6819  6819 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:24:39.730  6819  6819 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 14:24:39.730  6819  6819 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:24:39.730  6819  6819 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-09 14:24:39.730  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:39.731  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:39.731  6819  6819 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 14:24:39.732  6819  6819 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 14:24:39.747  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 14:24:39.758  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:39.759  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:39.759  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:39.759  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:39.760  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:39.761  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 14:24:39.761  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:39.762  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:24:39.764  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:39.771  6800  6800 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-09 14:24:39.771  6800  6800 W LG Account v2.2: No ProfileInfo entries
09-09 14:24:39.772  6800  6800 I LG Account v2.2: isEnabled: false
09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]Country: EU
09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]Operator: OPEN
09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]Ranking support: false
09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]Comfort support: false
09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]Accessory: true
,09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]Health device: true
09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]Extra Pedometer: false
09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]Blood glucose device: false
09-09 14:24:39.772  6800  6800 I Feature : [Lifetracker]Device Number: 3
09-09 14:24:39.779  2728  2728 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 14:24:39.779  2728  2728 I wpa_supplicant: monitor socket send errors count : 1
09-09 14:24:39.780  2728  2728 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1967-2\x00 that cannot receive messages
09-09 14:24:39.780  1035  2758 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 14:24:39.780  1035  2758 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 14:24:39.781  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:39.816  1035  1966 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6839 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 14:24:39.817  1035  1966 I ActivityManager: Killing 5944:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-09 14:24:39.820  2728  2728 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:24:39.820  2728  2728 W wpa_supplicant: USIM:  scard_deinit function
09-09 14:24:39.821  1035  2758 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 14:24:39.821  1035  2758 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:24:39.821  1035  2758 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:24:39.822  1035  2758 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 14:24:39.822  1035  2758 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:24:39.822  1035  2758 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:24:39.822  1035  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117241
09-09 14:24:39.823  1035  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117241
09-09 14:24:39.823  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117241  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 14:24:39.823  1035  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117241  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 14:24:39.824  1035  1117 D Tethering: InitialState.processMessage what=4
09-09 14:24:39.825  6819  6819 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:24:39.860  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 14:24:39.861  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:39.861  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:39.864  1035  2009 W libprocessgroup: failed to open /acct/uid_10014/pid_5944/cgroup.procs: No such file or directory
09-09 14:24:39.867  3920  3920 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:24:39.868  3920  3920 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:39.868  3920  3920 V BluetoothPbapReceiver: ***********state = 13
09-09 14:24:39.869  1035  1117 D BluetoothManagerService: Message: 20
09-09 14:24:39.869  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c61455f:true
09-09 14:24:39.869  3920  3920 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 14:24:39.870  3920  3920 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:39.870  3920  3920 V BluetoothPbapService: state: 13
09-09 14:24:39.870  3920  3920 V BluetoothPbapService: Pbap Service closeService in
09-09 14:24:39.872  2219  2219 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:39.878  3920  3920 V BluetoothPbapService: successfully stopped pbap service
09-09 14:24:39.879  3920  3920 V BluetoothPbapService: Pbap Service closeService out
09-09 14:24:39.879  3920  3920 V BluetoothPbapService: Pbap Service onDestroy
09-09 14:24:39.879  3920  3920 V BluetoothPbapService: Pbap Service closeService in
09-09 14:24:39.879  3920  3920 V BluetoothPbapService: Pbap Service closeService out
09-09 14:24:39.879  3920  3920 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 14:24:39.887  1035  1117 D BluetoothManagerService: Message: 30
,09-09 14:24:39.893  1035  1117 D BluetoothManagerService: Message: 30
09-09 14:24:39.896  6819  6819 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 14:24:39.898  6819  6819 D BluetoothMap: Create BluetoothMap proxy object
,09-09 14:24:39.899  1035  1117 D BluetoothManagerService: Message: 30
09-09 14:24:39.904  1035  1117 D BluetoothManagerService: Message: 30
09-09 14:24:39.906  6819  6819 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-09 14:24:39.907  6819  6819 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-09 14:24:39.909  2728  2728 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 14:24:39.909  1035  2758 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 14:24:39.910  1035  2758 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 14:24:39.910  1035  2758 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 14:24:39.911  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-09 14:24:39.919  1035  1398 V AlarmManager: RTC_WAKEUP set : Alarm{18f9a0e5 type 0 when 1473423879913 com.android.vending} when 1473423879913
09-09 14:24:39.929  6819  6819 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-09 14:24:39.933  6819  6819 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-09 14:24:39.943  6839  6839 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 14:24:39.950  6819  6819 D DockEventReceiver: finishStartingService: stopping service
09-09 14:24:39.952  6588  6588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 14:24:39.959  6839  6839 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-09 14:24:39.960  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:39.961  6819  6819 D BluetoothInputDevice: Proxy object connected
09-09 14:24:39.962  6819  6819 D HidProfile: Bluetooth service connected
09-09 14:24:39.963  6819  6819 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 14:24:39.963  6819  6819 D PanProfile: Bluetooth service connected
09-09 14:24:39.964  6819  6819 D BluetoothMap: Proxy object connected
09-09 14:24:39.965  6819  6819 D MapProfile: Bluetooth service connected
09-09 14:24:39.965  6819  6819 D BluetoothMap: getConnectedDevices()
09-09 14:24:39.966  6819  6819 D BluetoothMap: Bluetooth is Not enabled
09-09 14:24:39.966  6819  6819 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 14:24:39.979  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:40.001  1035  1731 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:24:40.013  1035  1538 D WifiOffDelayIfNotUsed: stopMonitoring
,09-09 14:24:40.013  1967  1967 D WfdsService: Supplicant Connection state is changed : false
09-09 14:24:40.013  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:24:40.013  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:24:40.013  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:24:40.013  1967  2387 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,09-09 14:24:40.013  1967  2387 D WfdsService: Set the WFDS Monitor: false
09-09 14:24:40.013  1967  2387 D WfdsMonitor: WFDS Monitor is stopped
09-09 14:24:40.015  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 14:24:40.016  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:40.017  6819  6819 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:40.017  6819  6819 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 14:24:40.017  1035  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 14:24:40.018  1035  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 14:24:40.018  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 14:24:40.019  2465  2465 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:40.020  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:40.022  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:40.035  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:40.036  6819  6819 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 14:24:40.040  6819  6819 D BluetoothPermissionRequest: onReceive
09-09 14:24:40.043  6819  6819 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 14:24:40.050  1035  1051 I ActivityManager: Killing 6292:com.android.defcontainer/u0a4 (adj 15): empty #17
09-09 14:24:40.053  6819  6819 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:24:40.092  3920  3920 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-09 14:24:40.093  3920  3920 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-09 14:24:40.093  3920  3920 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-09 14:24:40.100  1035  1984 W libprocessgroup: failed to open /acct/uid_10004/pid_6292/cgroup.procs: No such file or directory
09-09 14:24:40.190  1035  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6867 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 14:24:40.194  3920  3920 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:40.195  3920  3920 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 14:24:40.196  3920  3920 V BluetoothFtpService: Ftp Service onStartCommand
09-09 14:24:40.196  3920  3920 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:40.197  3920  3920 V BluetoothFtpService: Ftp Service closeService
09-09 14:24:40.197  3920  3920 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 14:24:40.199  3920  3920 V BluetoothFtpService: successfully stopped ftp service
09-09 14:24:40.199  3920  3920 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:24:40.199  3920  3920 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:24:40.199  3920  3920 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:24:40.199  3920  3920 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:40.199  3920  3920 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-09 14:24:40.200  3920  3920 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 14:24:40.201  3920  3920 V BluetoothFtpService: Ftp Service onDestroy
09-09 14:24:40.201  3920  3920 V BluetoothFtpService: Ftp Service closeService
09-09 14:24:40.219  6126  6126 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-09 14:24:40.257  1035  2113 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6885 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 14:24:40.264  3920  3920 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:40.264  3920  3920 V BluetoothSapService: state: 13
09-09 14:24:40.264  3920  3920 V BluetoothSapService: Stopping SAP server process
09-09 14:24:40.265  1035  2009 I ActivityManager: Killing 6457:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-09 14:24:40.266  3920  3920 V BluetoothSapService: Sap Service closeSapService in
09-09 14:24:40.266  3920  3920 V BluetoothSapService: Close listen Socket : 
09-09 14:24:40.266  3920  3920 V BluetoothSapService: Close rfcomm Socket : 
09-09 14:24:40.267  3920  3920 V BluetoothSapService: Close sapd  Socket : 
09-09 14:24:40.290  6867  6867 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 14:24:40.330  3920  3920 V BluetoothSapService: Sap Service closeSapService out
09-09 14:24:40.330  1035  1575 W libprocessgroup: failed to open /acct/uid_10008/pid_6457/cgroup.procs: No such file or directory
,09-09 14:24:40.330  3920  3920 V BluetoothSapService: Sap Service onDestroy
09-09 14:24:40.330  3920  3920 V BluetoothSapService: Sap Service closeSapService in
09-09 14:24:40.330  3920  3920 V BluetoothSapService: Close listen Socket : 
09-09 14:24:40.330  3920  3920 V BluetoothSapService: Close rfcomm Socket : 
09-09 14:24:40.330  3920  3920 V BluetoothSapService: Close sapd  Socket : 
09-09 14:24:40.339  3920  3920 V BluetoothSapService: Sap Service closeSapService out
09-09 14:24:40.341  6867  6867 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-09 14:24:40.356  6885  6885 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 14:24:40.373  1035  1947 I ActivityManager: Killing 6056:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-09 14:24:40.400  6867  6867 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-09 14:24:40.400  6867  6867 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-09 14:24:40.401  6867  6867 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-09 14:24:40.401  6867  6867 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-09 14:24:40.401  6867  6867 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-09 14:24:40.403  6867  6867 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-09 14:24:40.412  6867  6867 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-09 14:24:40.421  1035  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_6056/cgroup.procs: No such file or directory
09-09 14:24:40.439  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:24:40.446  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 14:24:40.464  6867  6867 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:24:40.467  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:40.469  6867  6867 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-09 14:24:40.472  6839  6839 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 14:24:40.472  6839  6839 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:24:40.472  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:40.473  6867  6867 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-09 14:24:40.475  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:40.482  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:40.492  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:24:40.493  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:40.494  6867  6867 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 14:24:40.498  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:40.501  6839  6839 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 14:24:40.501  6839  6839 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:24:40.501  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:40.504  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:40.512  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:40.517  3920  4094 W bt-btif : ag scb idx 1 not allocated
09-09 14:24:40.517  3920  4003 D bt_hci_bdroid: cleanup
09-09 14:24:40.517  3920  4094 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:40.517  3920  4094 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:24:40.518  3920  4094 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 14:24:40.518  3920  4096 I bt_lpm  : LPM is already off!!!
09-09 14:24:40.518  3920  4261 I bt_userial_mct: exiting userial_read_thread
09-09 14:24:40.518  3920  4261 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 14:24:40.518  3920  4003 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 14:24:40.519  3920  4096 I bt_vendor: hw_epilog_process
09-09 14:24:40.519  3920  4003 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 14:24:40.519  3920  4003 D bt_userial_mct: userial_close
09-09 14:24:40.519  3920  4003 E bt_userial_mct: pthread_join() FAILED result:3
09-09 14:24:40.519  3920  4003 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 14:24:40.523  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:40.524  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:40.526  6867  6867 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 14:24:40.558  3920  4003 D bt_hci_bdroid: set_power 0
09-09 14:24:40.559  3920  4003 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 14:24:40.559  3920  4003 I bt_vendor: bluetooth satus is on
09-09 14:24:40.559  3920  4003 I bt_vendor: bt-vendor : resetting BT status
09-09 14:24:40.559  3920  4003 I bt_vendor: Starting hciattach daemon
09-09 14:24:40.559  3920  4003 I bt_vendor: try to set false
,09-09 14:24:40.561  3920  4003 I bt_vendor: Starting hciattach daemon
09-09 14:24:40.561  3920  4003 I bt_vendor: try to set false
09-09 14:24:40.562  3920  4003 I bt_vendor: cleanup
09-09 14:24:40.564  3920  4094 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 14:24:40.565  3920  4003 I GKI_LINUX: GKI_exit_task 0 done
09-09 14:24:40.565  3920  4003 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 14:24:40.567  3920  4000 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 14:24:40.590  1035  2113 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6909 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-09 14:24:40.596  3920  3920 D HeadsetService: Received stop request...Stopping profile...
09-09 14:24:40.599  3920  3920 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 14:24:40.599  3920  3920 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:24:40.599  3920  3920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f21213b
09-09 14:24:40.599  3920  4027 D HeadsetStateMachine: Exit Disconnected: -1
09-09 14:24:40.602  1878  1878 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:40.603  1878  1878 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:40.603  1878  1878 D BluetoothHeadset: Proxy object disconnected
,09-09 14:24:40.604  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:40.605  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 14:24:40.607  3920  3920 D A2dpService: Received stop request...Stopping profile...
09-09 14:24:40.607  3920  4058 D A2dpStateMachine: Exit Disconnected: -1
09-09 14:24:40.609  3920  3920 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-09 14:24:40.611  3920  4000 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 14:24:40.612  3920  3920 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 14:24:40.612  3920  3920 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:24:40.612  3920  3920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f21213b
09-09 14:24:40.612  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-09 14:24:40.612  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 14:24:40.614  3920  3920 D HidService: Received stop request...Stopping profile...
09-09 14:24:40.614  3920  3920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f21213b
09-09 14:24:40.615  3920  3920 D HeadsetStateMachine: Unbinding service...
09-09 14:24:40.616   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 461us total 26.689ms
09-09 14:24:40.629  3920  3920 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:24:40.629  3920  3920 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:24:40.629  3920  3920 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:24:40.629  3920  3920 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:24:40.629  3920  3920 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 14:24:40.629  3920  3920 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:24:40.629  3920  3920 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-09 14:24:40.630  6819  6819 D BluetoothInputDevice: Proxy object disconnected
09-09 14:24:40.630  6819  6819 D HidProfile: Bluetooth service disconnected
09-09 14:24:40.631  3920  3920 D HealthService: Received stop request...Stopping profile...
09-09 14:24:40.631  3920  3920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f21213b
09-09 14:24:40.633  3920  3920 D PanService: Received stop request...Stopping profile...
09-09 14:24:40.633  3920  3920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f21213b
09-09 14:24:40.634  3920  3920 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:24:40.635  3920  3920 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 14:24:40.635  3920  3920 D BtGatt.GattService: stop()
09-09 14:24:40.635  3920  3920 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 14:24:40.636  3920  3920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f21213b
09-09 14:24:40.637  3920  3920 D BluetoothMapService: Received stop request...Stopping profile...
09-09 14:24:40.637  3920  3920 D BluetoothMapService: stop()
09-09 14:24:40.637  3920  3920 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 14:24:40.637  3920  3920 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 14:24:40.638  3920  3920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f21213b
09-09 14:24:40.638   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 20.315ms
09-09 14:24:40.639  3920  3920 I BluetoothA2dpServiceJni: cleanupNative
09-09 14:24:40.639  3920  4059 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 14:24:40.640  3920  3920 I GKI_LINUX: GKI_exit_task 2 done
09-09 14:24:40.640  3920  3920 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 14:24:40.640  3920  3920 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 14:24:40.640  3920  3920 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 14:24:40.640  3920  3920 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 14:24:40.641  3920  3920 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:24:40.641  3920  3920 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:24:40.641  3920  3920 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 14:24:40.641  3920  3920 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 14:24:40.643  3920  3920 V BluetoothMapService: Handler(): got msg=4
09-09 14:24:40.643  3920  3920 D BluetoothMapService: MAP Service closeService in
09-09 14:24:40.643  3920  3920 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:24:40.643  3920  3920 V BluetoothMapService: MAP Service closeService out
09-09 14:24:40.644  3920  4000 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 14:24:40.644  3920  4000 D BluetoothAdapterProperties: Setting state to 10
09-09 14:24:40.644  3920  4000 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 14:24:40.644  3920  3920 D BluetoothMapService: cleanup()
09-09 14:24:40.644  3920  3920 D BluetoothMapService: MAP Service closeService in
09-09 14:24:40.644  3920  3920 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:24:40.644  3920  3920 V BluetoothMapService: MAP Service closeService out
09-09 14:24:40.645  3920  4000 I BluetoothAdapterState: Entering OffState
09-09 14:24:40.647  1035  1117 D BluetoothManagerService: Message: 60
09-09 14:24:40.648  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 14:24:40.648  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-09 14:24:40.648  1878  2528 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:40.649  6819  6819 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 14:24:40.649  6819  6819 D PanProfile: Bluetooth service disconnected
09-09 14:24:40.649  6819  6819 D BluetoothMap: Proxy object disconnected
09-09 14:24:40.649  6819  6819 D MapProfile: Bluetooth service disconnected
09-09 14:24:40.650  6819  6834 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 14:24:40.650  1878  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:40.651  6819  6835 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:24:40.651  1878  2662 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:40.651  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:40.652  6819  6834 D BluetoothPan: onBluetoothStateChange on: false
09-09 14:24:40.652  6819  6835 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:24:40.653  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:24:40.653  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 14:24:40.654  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-09 14:24:40.656  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 14:24:40.656  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 14:24:40.656  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3c866bd mBinding = false
09-09 14:24:40.656  1035  1117 D BluetoothManagerService: Sending unbind request.
09-09 14:24:40.659   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 19.450ms
09-09 14:24:40.666  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-09 14:24:40.666  3920  4003 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-09 14:24:40.667  3920  3920 I GKI_LINUX: GKI_exit_task 1 done
09-09 14:24:40.667  3920  3920 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 14:24:40.667  3920  3920 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 14:24:40.667  3920  3920 I art     : --- WEIRD: removing null entry 246
09-09 14:24:40.667  3920  3920 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-09 14:24:40.667  3920  3920 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 14:24:40.669  3920  3920 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,09-09 14:24:40.672  3920  3920 I art     : System.exit called, status: 0
09-09 14:24:40.674  3920  3920 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 14:24:40.676  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:40.676  1967  2259 D LGBluetoothAPIService: Message: 2
09-09 14:24:40.676  1967  2259 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2888b59a mBinding = false
09-09 14:24:40.676  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:24:40.676  1967  2259 D LGBluetoothAPIService: Sending unbind request.
09-09 14:24:40.677  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:40.678  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:40.678  6819  6819 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 14:24:40.679  6819  6819 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 14:24:40.679  6819  6819 D LGBluetoothEventManager: [BTUI] clear device connection state
09-09 14:24:40.681  1601  1601 D BluetoothAdapter: 7800429: getState() :  mService = null. Returning STATE_OFF
09-09 14:24:40.681  1601  1601 D BluetoothAdapter: 7800429: getState() :  mService = null. Returning STATE_OFF
09-09 14:24:40.689  6819  6819 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:24:40.692   316  4033 V AudioFlinger: 3920 died, releasing its sessions
09-09 14:24:40.692   316  4033 V AudioFlinger:  pid 1878 @ 0
09-09 14:24:40.693   316  4033 V AudioFlinger:  pid 3435 @ 1
09-09 14:24:40.693   316  4033 V AudioFlinger:  pid 3435 @ 2
09-09 14:24:40.695  6819  6819 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-09 14:24:40.719  1035  2076 I ActivityManager: Process com.android.bluetooth (pid 3920) has died
09-09 14:24:40.720  1035  2076 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-09 14:24:40.788  1035  2030 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6934 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-09 14:24:40.791  6819  6819 D DockEventReceiver: finishStartingService: stopping service
09-09 14:24:40.802  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:24:40.807  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 14:24:40.814  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:40.830  6909  6951 W FormManager: Network not available. Please check & try again.
,09-09 14:24:40.834  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 14:24:40.834  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:24:40.834  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:24:40.834  6819  6819 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 14:24:40.835  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-09 14:24:40.847  6819  6819 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:24:40.847  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 14:24:40.848  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:24:40.849  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:24:40.849  6819  6819 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:24:40.849  6819  6819 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 14:24:40.853  6909  6954 V FormManager: Network unavailable.
09-09 14:24:40.858  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:24:40.858  6909  6954 V FormManager: Network unavailable.
09-09 14:24:40.858  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 14:24:40.862  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:40.864  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:40.870  6934  6934 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-09 14:24:40.870  6934  6934 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 14:24:40.871  6839  6839 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 14:24:40.871  6839  6839 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:24:40.871  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:24:40.873  4351  6961 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:24:40.873  6934  6934 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-09 14:24:40.874  6934  6934 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 14:24:40.874  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 14:24:40.879  4351  6962 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:24:40.879  4351  6962 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:24:40.891  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:24:40.893  6909  6963 W FormManager: Network not available. Please check & try again.
09-09 14:24:40.894  4522  6958 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
09-09 14:24:40.895  6934  6934 D BluetoothAdapterApp: Loading JNI Library
09-09 14:24:40.900  6909  6964 V FormManager: Network unavailable.
09-09 14:24:40.909  6909  6964 V FormManager: Network unavailable.
09-09 14:24:40.910  6867  6867 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 14:24:40.913  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 14:24:40.914  6867  6867 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-09 14:24:40.915  1035  1575 I ActivityManager: Killing 6078:com.android.contacts/u0a19 (adj 15): empty #17
,09-09 14:24:40.931  6934  6934 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1c4d9940 Instance Count = 1
09-09 14:24:40.957  6867  6867 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 14:24:40.957  6867  6867 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:24:40.964  6867  6867 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-09 14:24:40.964  6867  6867 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-09 14:24:40.964  6867  6867 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
09-09 14:24:40.964  6867  6867 V SoundPool: doLoad: loading sample sampleID=1
09-09 14:24:40.965  6867  6867 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 14:24:40.965  6867  6970 V SoundPool: Start decode
09-09 14:24:40.965  6867  6970 V MediaPlayer[Native]: decode(32, 10857164, 17813)
09-09 14:24:40.966   316  4033 V MediaPlayerService: decode(23, 10857164, 17813)
09-09 14:24:40.966   316  4033 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-09 14:24:40.966   316  4033 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-09 14:24:40.966   316  4033 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-09 14:24:40.966   316  4033 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-09 14:24:40.966   316  4033 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-09 14:24:40.966   316  4033 V MediaPlayerService: player type = 3
09-09 14:24:40.966   316  4033 V AwesomePlayer: AwesomePlayer create()
09-09 14:24:40.967   316  4033 V AwesomePlayer: reset_l() 
09-09 14:24:40.967   316  4033 V AwesomePlayer: cancelPlayerEvents
09-09 14:24:40.967   316  4033 V AwesomePlayer: setAudioSink() 
09-09 14:24:40.967   316  4033 V AwesomePlayer: reset_l() 
09-09 14:24:40.967   316  4033 V AudioCache: notify(0xb5474700, 8, 0, 0)
09-09 14:24:40.967   316  4033 V AudioCache: ignored
09-09 14:24:40.967   316  4033 V AwesomePlayer: cancelPlayerEvents
09-09 14:24:40.967   316  4033 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-09 14:24:40.967   316  4033 V AwesomePlayer: setDataSource_l dataSource
09-09 14:24:40.967   316  4033 V LGParserOSAL: SniffLGParser start
,09-09 14:24:40.967   316  4033 V LGParserOSAL: MainType:5, SubType=0
09-09 14:24:40.967   316  4033 V LGParserOSAL: #### check Mime : application/ogg
09-09 14:24:40.967   316  4033 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-09 14:24:40.967   316  4033 E MediaExtractor: Use LGExtractor :application/ogg 
,09-09 14:24:40.998   316  4033 V LGParserOSAL: supported mime: application/ogg
09-09 14:24:40.998   316  4033 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-09 14:24:40.998   316  4033 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-09 14:24:40.998   316  4033 V AwesomePlayer: mBitrate = -1 bits/sec
09-09 14:24:40.998   316  4033 V AwesomePlayer: AudioTrack Setting
09-09 14:24:40.998   316  4033 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-09 14:24:40.998   316  4033 V AwesomePlayer: setAudioSource() 
09-09 14:24:40.998   316  4033 V MediaPlayerService: prepare
,09-09 14:24:40.998   316  4033 V AwesomePlayer: prepareAsync_l() 
09-09 14:24:40.999   316  4033 V MediaPlayerService: wait for prepare
09-09 14:24:40.999   316  6972 V AwesomePlayer: onPrepareAsyncEvent() 
09-09 14:24:40.999   316  6972 V AwesomePlayer: initAudioDecoder() 
09-09 14:24:40.999   316  6972 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 14:24:40.999   316  6972 V AudioSystem: isOffloadSupported()
09-09 14:24:40.999   316  6972 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 14:24:40.999   316  6972 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 14:24:40.999   316  6972 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 14:24:40.999   316  6972 V AwesomePlayer: getUseOffload() = 0 
09-09 14:24:40.999   316  6972 V OMXCodec: OMXCodec::Create
09-09 14:24:40.999   316  6972 V OMXCodec: findMatchingCodecs()
09-09 14:24:40.999   316  6972 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-09 14:24:40.999   316  6972 V OMXCodec: matchingCodecs.size()=1
09-09 14:24:40.999   316  6972 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-09 14:24:41.000   316  6972 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-09 14:24:41.000   316  6972 V LGCodecAdapter: LG Codec Adapter start
09-09 14:24:41.000   316  6972 V OMXCodec: OMXCodec Createtor
09-09 14:24:41.000   316  6972 V OMXCodec: setComponentRole
09-09 14:24:41.001   316  6972 V OMXCodec: configureCodec protected=0
09-09 14:24:41.001   316  6972 V LGCodecAdapter: called getLGCodecSpecificData
09-09 14:24:41.001   316  6972 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-09 14:24:41.001   316  6972 V LGCodecOSAL: Called LGconfigureCodecMETA
09-09 14:24:41.001   316  6972 V LGCodecOSAL: Called LGconfigureCodecMSG
09-09 14:24:41.001   316  6972 V LGCodecOSAL: Not support LGCodec
09-09 14:24:41.001   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 14:24:41.001   316  6972 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-09 14:24:41.001   316  6972 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-09 14:24:41.001   316  6972 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-09 14:24:41.001   316  6972 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 14:24:41.001   316  6972 V AudioSystem: isOffloadSupported()
09-09 14:24:41.001   316  6972 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 14:24:41.001   316  6972 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 14:24:41.001   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-09 14:24:41.001   316  6972 V OMXCodec: init()
09-09 14:24:41.001   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
,09-09 14:24:41.001   316  6972 V OMXCodec: allocateBuffers
09-09 14:24:41.001   316  6972 V OMXCodec: allocateBuffersOnPort portIndex=0
09-09 14:24:41.001   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-09 14:24:41.002   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
09-09 14:24:41.002   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on input port
09-09 14:24:41.002   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on input port
09-09 14:24:41.002   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on input port
09-09 14:24:41.002   316  6972 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 14:24:41.002   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 14:24:41.002   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
09-09 14:24:41.002   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
09-09 14:24:41.002   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fe70 on output port
09-09 14:24:41.002   316  6972 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040ff60 on output port
09-09 14:24:41.002   316  6972 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 14:24:41.002   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 14:24:41.002   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 14:24:41.002   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-09 14:24:41.002   316  6972 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 14:24:41.002   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-09 14:24:41.002   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-09 14:24:41.002   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-09 14:24:41.002   316  6972 V OMXCodec: init() mAsyncCompletion wait free! 
09-09 14:24:41.002   316  6972 V AwesomePlayer: finishAsyncPrepare_l() 
09-09 14:24:41.002   316  6972 V AudioCache: notify(0xb5474700, 5, 0, 0)
09-09 14:24:41.002   316  6972 V AudioCache: ignored
09-09 14:24:41.002   316  6972 V AudioCache: notify(0xb5474700, 1, 0, 0)
09-09 14:24:41.002   316  6972 V AudioCache: prepared
09-09 14:24:41.002   316  4033 V AudioCache: wait - success
09-09 14:24:41.002   316  4033 V MediaPlayerService: start
09-09 14:24:41.002   316  4033 V AwesomePlayer: play_l() 
09-09 14:24:41.002   316  4033 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-09 14:24:41.002   316  4033 V AwesomePlayer: createAudioPlayer_l
09-09 14:24:41.002   316  4033 V AwesomePlayer: seekAudioIfNecessary_l() 
09-09 14:24:41.002   316  4033 V AwesomePlayer: startAudioPlayer_l() 
09-09 14:24:41.002   316  4033 D AudioPlayer: start of Playback, useOffload 0
09-09 14:24:41.002   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 14:24:41.002   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 14:24:41.004   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-09 14:24:41.004   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-09 14:24:41.004   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-09 14:24:41.004   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-09 14:24:41.004   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-09 14:24:41.004   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048736
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbi,s.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048896
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049456
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049696
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-09 14:24:41.005   316  6974 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fe70 on output port
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-09 14:24:41.005   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-09 14:24:41.005   316  4033 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-09 14:24:41.006   316  4033 V AudioCache: notify(0xb5474700, 6, 0, 0)
09-09 14:24:41.006   316  4033 V AudioCache: ignored
09-09 14:24:41.006   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.006   316  6975 V AudioCache: memcpy(0xac200000, 0xb57ec000, 4096)
09-09 14:24:41.006   316  4033 V MediaPlayerService: wait for playback complete
09-09 14:24:41.007   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.007   316  6975 V AudioCache: memcpy(0xac201000, 0xb57ec000, 4096)
09-09 14:24:41.007   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.007   316  6975 V AudioCache: memcpy(0xac202000, 0xb57ec000, 4096)
09-09 14:24:41.007   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.007   316  6975 V AudioCache: memcpy(0xac203000, 0xb57ec000, 4096)
,09-09 14:24:41.008   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.008   316  6975 V AudioCache: memcpy(0xac204000, 0xb57ec000, 4096)
09-09 14:24:41.008   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.008   316  6975 V AudioCache: memcpy(0xac205000, 0xb57ec000, 4096)
09-09 14:24:41.009   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.009   316  6975 V AudioCache: memcpy(0xac206000, 0xb57ec000, 4096)
09-09 14:24:41.009   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.009   316  6975 V AudioCache: memcpy(0xac207000, 0xb57ec000, 4096)
09-09 14:24:41.009   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.009   316  6975 V AudioCache: memcpy(0xac208000, 0xb57ec000, 4096)
09-09 14:24:41.010   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.010   316  6975 V AudioCache: memcpy(0xac209000, 0xb57ec000, 4096)
09-09 14:24:41.010   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.010   316  6975 V AudioCache: memcpy(0xac20a000, 0xb57ec000, 4096)
09-09 14:24:41.010   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.010   316  6975 V AudioCache: memcpy(0xac20b000, 0xb57ec000, 4096)
09-09 14:24:41.011   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.011   316  6975 V AudioCache: memcpy(0xac20c000, 0xb57ec000, 4096)
09-09 14:24:41.011   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.011   316  6975 V AudioCache: memcpy(0xac20d000, 0xb57ec000, 4096)
09-09 14:24:41.011   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.011   316  6975 V AudioCache: memcpy(0xac20e000, 0xb57ec000, 4096)
09-09 14:24:41.012   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.012   316  6975 V AudioCache: memcpy(0xac20f000, 0xb57ec000, 4096)
09-09 14:24:41.012   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.012   316  6975 V AudioCache: memcpy(0xac210000, 0xb57ec000, 4096)
09-09 14:24:41.012   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.012   316  6975 V AudioCache: memcpy(0xac211000, 0xb57ec000, 4096)
09-09 14:24:41.013   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.013   316  6975 V AudioCache: memcpy(0xac212000, 0xb57ec000, 4096)
09-09 14:24:41.013   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.013   316  6975 V AudioCache: memcpy(0xac213000, 0xb57ec000, 4096)
09-09 14:24:41.013   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.013   316  6975 V AudioCache: memcpy(0xac214000, 0xb57ec000, 4096)
09-09 14:24:41.014   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.014   316  6975 V AudioCache: memcpy(0xac215000, 0xb57ec000, 4096)
09-09 14:24:41.014   316  6975 V AudioCache: write(0xb57ec000, 4096)
,09-09 14:24:41.014   316  6975 V AudioCache: memcpy(0xac216000, 0xb57ec000, 4096)
09-09 14:24:41.014   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.014   316  6975 V AudioCache: memcpy(0xac217000, 0xb57ec000, 4096)
09-09 14:24:41.015   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.015   316  6975 V AudioCache: memcpy(0xac218000, 0xb57ec000, 4096)
09-09 14:24:41.015   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.015   316  6975 V AudioCache: memcpy(0xac219000, 0xb57ec000, 4096)
09-09 14:24:41.015   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.015   316  6975 V AudioCache: memcpy(0xac21a000, 0xb57ec000, 4096)
09-09 14:24:41.016   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.016   316  6975 V AudioCache: memcpy(0xac21b000, 0xb57ec000, 4096)
09-09 14:24:41.016   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.016   316  6975 V AudioCache: memcpy(0xac21c000, 0xb57ec000, 4096)
09-09 14:24:41.016   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.016   316  6975 V AudioCache: memcpy(0xac21d000, 0xb57ec000, 4096)
09-09 14:24:41.017   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.017   316  6975 V AudioCache: memcpy(0xac21e000, 0xb57ec000, 4096)
09-09 14:24:41.017   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.017   316  6975 V AudioCache: memcpy(0xac21f000, 0xb57ec000, 4096)
09-09 14:24:41.018   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.018   316  6975 V AudioCache: memcpy(0xac220000, 0xb57ec000, 4096)
09-09 14:24:41.018   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.018   316  6975 V AudioCache: memcpy(0xac221000, 0xb57ec000, 4096)
09-09 14:24:41.019   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.019   316  6975 V AudioCache: memcpy(0xac222000, 0xb57ec000, 4096)
09-09 14:24:41.020  1035  2030 W libprocessgroup: failed to open /acct/uid_10019/pid_6078/cgroup.procs: No such file or directory
09-09 14:24:41.024  6934  6934 D BluetoothAdapterApp: onCreate
09-09 14:24:41.026  6713  6713 D UEI.SmartControl: QS Service created
09-09 14:24:41.029  6867  6867 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-09 14:24:41.029   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.029   316  6975 V AudioCache: memcpy(0xac223000, 0xb57ec000, 4096)
09-09 14:24:41.031   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.031   316  6975 V AudioCache: memcpy(0xac224000, 0xb57ec000, 4096)
09-09 14:24:41.031   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.031   316  6975 V AudioCache: memcpy(0xac225000, 0xb57ec000, 4096)
09-09 14:24:41.031   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.031   316  6975 V AudioCache: memcpy(0xac226000, 0xb57ec000, 4096)
09-09 14:24:41.031   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.032   316  6975 V AudioCache: memcpy(0xac227000, 0xb57ec000, 4096)
09-09 14:24:41.032   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.032   316  6975 V AudioCache: memcpy(0xac228000, 0xb57ec000, 4096)
09-09 14:24:41.032   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.032   316  6975 V AudioCache: memcpy(0xac229000, 0xb57ec000, 4096)
09-09 14:24:41.032   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.032   316  6975 V AudioCache: memcpy(0xac22a000, 0xb57ec000, 4096)
09-09 14:24:41.033   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.033   316  6975 V AudioCache: memcpy(0xac22b000, 0xb57ec000, 4096)
09-09 14:24:41.033   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.033   316  6975 V AudioCache: memcpy(0xac22c000, 0xb57ec000, 4096)
09-09 14:24:41.033   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.033   316  6975 V AudioCache: memcpy(0xac22d000, 0xb57ec000, 4096)
09-09 14:24:41.033   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.033   316  6975 V AudioCache: memcpy(0xac22e000, 0xb57ec000, 4096)
09-09 14:24:41.033  6713  6713 I UEI.SmartControl: Service initServices...
09-09 14:24:41.033   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.033   316  6975 V AudioCache: memcpy(0xac22f000, 0xb57ec000, 4096)
09-09 14:24:41.033  6713  6713 D UEI.SmartControl: QS start get config
09-09 14:24:41.034   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.034   316  6975 V AudioCache: memcpy(0xac230000, 0xb57ec000, 4096)
09-09 14:24:41.034   316  6975 V AudioCache: write(0xb57ec000, 4096)
09-09 14:24:41.034   316  6975 V AudioCache: memcpy(0xac231000, 0xb57ec000, 4096)
09-09 14:24:41.034   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-09 14:24:41.034   316  6975 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 14:24:41.034   316  6975 V AwesomePlayer: postAudioEOS() 
09-09 14:24:41.034   316  6975 V AudioCache: write(0xb57ec000, 280)
09-09 14:24:41.034   316  6975 V AudioCache: memcpy(0xac232000, 0xb57ec000, 280)
09-09 14:24:41.034  6867  6867 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 14:24:41.035  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 14:24:41.036   316  6972 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-09 14:24:41.036   316  6972 V AwesomePlayer: onStreamDone
09-09 14:24:41.036   316  6972 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-09 14:24:41.036   316  6972 V AudioCache: notify(0xb5474700, 2, 0, 0)
09-09 14:24:41.036   316  6972 V AudioCache: playback complete
09-09 14:24:41.036   316  6972 V AwesomePlayer: pause_l() 
09-09 14:24:41.036   316  6972 V AudioCache: notify(0xb5474700, 7, 0, 0)
09-09 14:24:41.036   316  6972 V AudioCache: ignored
09-09 14:24:41.036   316  6972 V AwesomePlayer: cancelPlayerEvents
09-09 14:24:41.036   316  4033 V AudioCache: wait - success
09-09 14:24:41.036   316  4033 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-09 14:24:41.036   316  6972 D AudioPlayer: Pause Playback at 1068125
09-09 14:24:41.037   316  4033 V AwesomePlayer: reset_l() 
09-09 14:24:41.037   316  4033 V AudioCache: notify(0xb5474700, 8, 0, 0)
09-09 14:24:41.037   316  4033 V AudioCache: ignored
09-09 14:24:41.037   316  4033 V AwesomePlayer: cancelPlayerEvents
09-09 14:24:41.037   316  4033 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-09 14:24:41.037   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-09 14:24:41.037   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-09 14:24:41.037   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-09 14:24:41.037   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 0
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 0
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 0
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fc40 on port 1
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fe70 on port 1
09-09 14:24:41.038   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:24:41.039   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-09 14:24:41.039   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 14:24:41.039   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 14:24:41.039   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-09 14:24:41.039   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-09 14:24:41.039   316  6974 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-09 14:24:41.039   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 14:24:41.039   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-09 14:24:41.039   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-09 14:24:41.040   316  4033 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,09-09 14:24:41.040   316  4033 D AudioPlayer: AudioPlayer releasing audio source
09-09 14:24:41.040   316  4033 D AudioPlayer: AudioPlayer done releasing audio source
09-09 14:24:41.040   316  4033 V AwesomePlayer: reset_l() 
09-09 14:24:41.040   316  4033 V AwesomePlayer: cancelPlayerEvents
09-09 14:24:41.040   316  4033 V AwesomePlayer: ~AwesomePlayer call
09-09 14:24:41.040   316  4033 V AwesomePlayer: reset_l() 
09-09 14:24:41.040   316  4033 V AwesomePlayer: cancelPlayerEvents
09-09 14:24:41.040  6867  6970 V SoundPool: close(32)
09-09 14:24:41.040  6867  6970 V SoundPool: pointer = 0x9ffe6000, size = 205080, sampleRate = 48000, numChannels = 2
09-09 14:24:41.041  6867  6867 V LGMDMManager: Create singleton instance
09-09 14:24:41.048  6934  6934 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-09 14:24:41.048  6934  6934 D ProfileConfigQcom: Adding HeadsetService
09-09 14:24:41.048  6934  6934 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-09 14:24:41.048  6934  6934 D ProfileConfigQcom: Adding A2dpService
09-09 14:24:41.049  6934  6934 D ProfileConfigQcom: [BTUI] HidService is supported
09-09 14:24:41.049  6934  6934 D ProfileConfigQcom: Adding HidService
09-09 14:24:41.049  6934  6934 D ProfileConfigQcom: [BTUI] HealthService is supported
09-09 14:24:41.050  6934  6934 D ProfileConfigQcom: Adding HealthService
09-09 14:24:41.050  6934  6934 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 14:24:41.051  6934  6934 D ProfileConfigQcom: [BTUI] PanService is supported
09-09 14:24:41.051  6934  6934 D ProfileConfigQcom: Adding PanService
09-09 14:24:41.051  6934  6934 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 14:24:41.051  6934  6934 D ProfileConfigQcom: Adding GattService
09-09 14:24:41.052  6934  6934 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-09 14:24:41.052  6934  6934 D ProfileConfigQcom: Adding BluetoothMapService
09-09 14:24:41.052  6934  6934 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-09 14:24:41.054  6934  6934 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:24:41.055  6934  6934 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:41.055  6934  6934 V BluetoothPbapReceiver: ***********state = 10
09-09 14:24:41.057  6934  6934 V LGMDMManagerInternal: Create singleton instance
09-09 14:24:41.096  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 14:24:41.097  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-09 14:24:41.099  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9086
09-09 14:24:41.140  2219  2219 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:41.147  6819  6819 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 14:24:41.163  6819  6819 D BluetoothPermissionRequest: onReceive
,09-09 14:24:41.167  6819  6819 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-09 14:24:41.167  6819  6819 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 14:24:41.171  6819  6819 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:24:41.180  6934  6934 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-09 14:24:41.185  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:41.188  6934  6934 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:24:41.189  6934  6934 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:24:41.189  6934  6934 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:24:41.190  6934  6934 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:41.190  6934  6934 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-09 14:24:41.200  6885  6885 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-09 14:24:41.291  6713  6713 I UEI.SmartControl: Supports setup maps: true
,09-09 14:24:41.294  6713  6713 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 14:24:41.294  6713  6713 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 14:24:41.294  6713  6713 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 14:24:41.294  6713  6713 I UEI.SmartControl: ### init IR Blaster...
09-09 14:24:41.297  6713  6713 D serial_port: Configuring serial port
09-09 14:24:41.298  6713  6713 E UEI.SmartControl: UEIBLaster setting for 616
09-09 14:24:41.298  6713  6713 I UEI.SmartControl: Setting serial record hearder size = 2
,09-09 14:24:41.298  6713  6713 I UEI.SmartControl: configuring settings for MAXQ616
09-09 14:24:41.298  6713  6713 I UEI.SmartControl: Get version...
09-09 14:24:41.316  6713  6979 D UEI.SmartControl: serial port data available: 21
,09-09 14:24:41.343  6713  6713 D UEI.SmartControl: MAXQ616 A2-X4 software.,
09-09 14:24:41.343  6713  6713 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 14:24:41.343  6713  6713 I UEI.SmartControl: QS saving settings...
,09-09 14:24:41.348  6713  6713 D UEI.SmartControl: IR Blaster version: 25672567
09-09 14:24:41.365  6713  6979 D UEI.SmartControl: serial port data available: 4
,09-09 14:24:41.395  6713  6985 I UEI.SmartControl: Device manager: loading config....
,09-09 14:24:41.396  6713  6985 D UEI.SmartControl: ----------- loading internal config...
09-09 14:24:41.397  6713  6713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 14:24:41.401  6713  6713 E UEI.SmartControl: Services init done
09-09 14:24:41.402  6713  6713 D UEI.SmartControl: QS Service init finished
,09-09 14:24:41.405  6713  6713 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 14:24:41.406  6713  6713 D UEI.SmartControl: QS Service version code: 201091
09-09 14:24:41.409  6713  6713 D UEI.SmartControl: Service requested: Control
09-09 14:24:41.411  6713  6985 E UEI.SmartControl: Loading SETTINGS...
,09-09 14:24:41.415  6713  6713 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 14:24:41.419  6867  6867 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 14:24:41.419  6713  6713 D UEI.SmartControl: Internal service binding...
09-09 14:24:41.421  6713  6728 I UEI.SmartControl: ------ IControl API: 11
09-09 14:24:41.421  6713  6728 D UEI.SmartControl: File observer start...
09-09 14:24:41.422  6713  6728 E UEI.SmartControl: IR Port is disabled: false
09-09 14:24:41.422  6713  6728 D UEI.SmartControl: Starting file observer...
09-09 14:24:41.423  6713  6985 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 14:24:41.423  6713  6728 I UEI.SmartControl: Registering callback...
09-09 14:24:41.424  6713  6729 I UEI.SmartControl: ------ IControl API: 19
09-09 14:24:41.426  6713  6729 I UEI.SmartControl: Registering Services Ready callback...
09-09 14:24:41.434  6713  6984 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 14:24:41.434  6713  6984 D UEI.SmartControl: -----service ready thread exits
09-09 14:24:41.435  6867  6882 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 14:24:41.435  6867  6968 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 14:24:41.435  6867  6968 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,09-09 14:24:41.436  6867  6867 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-09 14:24:41.436  6867  6867 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-09 14:24:41.437  6713  6728 I UEI.SmartControl: ------ IControl API: 8
09-09 14:24:41.439  6867  6867 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-09 14:24:41.439  6867  6867 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-09 14:24:41.439  6867  6867 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-09 14:24:41.440  6867  6867 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-09 14:24:41.441  6867  6867 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-09 14:24:41.441  6867  6867 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-09 14:24:41.444  6867  6867 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-09 14:24:41.447  6867  6867 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-09 14:24:41.448  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 14:24:41.449  6867  6867 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 14:24:41.450  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 14:24:41.451  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 14:24:41.453  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-09 14:24:41.453  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-09 14:24:41.454  6867  6867 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473423881454]
09-09 14:24:41.457  6867  6867 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-09 14:24:41.462  1035  2075 I ActivityManager: Killing 6102:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-09 14:24:41.482  6867  6987 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-09 14:24:41.549  1035  2075 I ActivityManager: Killing 6492:com.lge.email/u0a23 (adj 15): empty #18
,09-09 14:24:41.615  1035  2009 W libprocessgroup: failed to open /acct/uid_10023/pid_6492/cgroup.procs: No such file or directory
,09-09 14:24:41.619  1035  1050 W libprocessgroup: failed to open /acct/uid_10027/pid_6102/cgroup.procs: No such file or directory
09-09 14:24:41.620  6867  6867 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-09 14:24:41.622  6867  6867 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 14:24:41.623  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-09 14:24:41.623  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-09 14:24:41.625  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-09 14:24:41.626  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-09 14:24:41.627  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-09 14:24:41.636  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-09 14:24:42.643  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:42.651  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:42.656  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-09 14:24:42.679  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:42.684  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:42.684  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-09 14:24:42.690  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:42.695  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:42.699  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:42.702  1035  2009 D WifiServiceImplEx: setWifiEnabled: true pid=6588, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:24:42.703  1035  2009 D WifiService: setWifiEnabled: true pid=6588, uid=10118
09-09 14:24:42.703  1035  2009 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:24:42.706  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 14:24:42.717  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:24:42.718  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:24:42.718  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-09 14:24:42.721  1035  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 14:24:42.721  1035  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 14:24:42.724  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-09 14:24:42.724  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 14:24:42.724  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 14:24:42.724  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 14:24:42.724  1035  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 14:24:42.724  1035  1538 E WifiHW  : unknown target_country: EU , set to default
09-09 14:24:42.724  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 14:24:42.724  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-09 14:24:42.724  1035  1538 I WifiUtil: gEnableBmps=1
09-09 14:24:42.733  5789  5789 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 14:24:42.741  5789  5789 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-09 14:24:42.744  6396  6434 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 14:24:42.768  2219  2219 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:42.802  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:42.857  1035  1051 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7009 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 14:24:42.866  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:42.866  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 14:24:42.927  7009  7009 I AppUp4:AppBoxCP: onCreate
,09-09 14:24:42.929  7009  7009 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-09 14:24:42.938  7009  7009 I AppUp4:DB:  setFingerPrint start
09-09 14:24:42.939  7009  7009 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-09 14:24:42.947  7009  7009 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-09 14:24:42.947  7009  7009 I AppUp4:DB:  SDK version = 21
09-09 14:24:42.947  7009  7009 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 14:24:42.949  7009  7009 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 14:24:42.950  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:24:42.951  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:42.953  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:24:42.953  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 14:24:42.965  7009  7009 I AppUp4:CustModeStarterReceiver: onReceive
09-09 14:24:43.010  7009  7009 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:43.010  7009  7009 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:24:43.021  7009  7009 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1badebca
09-09 14:24:43.021  7009  7009 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:24:43.022  7009  7009 D AppUp4:CustFacade: isPhone : true
09-09 14:24:43.022  7009  7009 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:24:43.023  7009  7009 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 14:24:43.023  7009  7009 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 14:24:43.024  7009  7028 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 14:24:43.024  7009  7028 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 14:24:43.025  7009  7028 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 14:24:43.029  1035  1050 I ActivityManager: Killing 6529:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-09 14:24:43.092  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:43.093  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 14:24:43.094  1035  1965 W libprocessgroup: failed to open /acct/uid_10061/pid_6529/cgroup.procs: No such file or directory
09-09 14:24:43.103  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:43.109  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:24:43.125  4351  7034 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 14:24:43.129  4351  7035 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:43.130  4351  7035 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:24:43.165  1035  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7036 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 14:24:43.247  7036  7036 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 14:24:43.247  7036  7036 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 14:24:43.251  7036  7036 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 14:24:43.251  7036  7036 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 14:24:43.355  7036  7036 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 14:24:43.374  7036  7036 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-09 14:24:43.413  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 14:24:43.421   309   895 D SoftapController: Softap fwReload - Ok
,09-09 14:24:43.423  1035  1538 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (694ms)
09-09 14:24:43.426   309   895 D CommandListener: Setting iface cfg
09-09 14:24:43.426   309   895 D CommandListener: Trying to bring down wlan0
09-09 14:24:43.428  1035  1117 D Tethering: InitialState.processMessage what=4
09-09 14:24:43.430  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:24:43.431   309   895 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:24:43.436  1035  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 14:24:43.439  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:24:43.439  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:24:43.439  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:24:43.432  7065  7065 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:43.446  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:43.432  7065  7065 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:43.449  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-09 14:24:43.462  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:43.463  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:43.464  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 14:24:43.464  1035  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 14:24:43.464  1035  1538 D WifiMonitor: connecting to supplicant
,09-09 14:24:43.487  7065  7065 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 14:24:43.516  7036  7036 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 14:24:43.521  7065  7065 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 14:24:43.521  7065  7065 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 14:24:43.550  7036  7036 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:43.550  7036  7036 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:24:43.594  7065  7065 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 14:24:43.637  7065  7065 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 14:24:43.648  7036  7036 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 14:24:43.650  7065  7065 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-09 14:24:43.652  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-09 14:24:43.652  1035  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-09 14:24:43.652  1035  7081 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 14:24:43.652  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-09 14:24:43.653  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-09 14:24:43.653  1035  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 14:24:43.654  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:43.654  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:43.654  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:43.655  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:43.655  1035  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 14:24:43.655  1035  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 14:24:43.656  1035  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 14:24:43.657  1035  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 14:24:43.657  1035  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-09 14:24:43.657  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : ,
09-09 14:24:43.657  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:24:43.657  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 14:24:43.657  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:43.658  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
09-09 14:24:43.658  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
09-09 14:24:43.658  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:24:43.658  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:24:43.659  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=],
09-09 14:24:43.659  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,09-09 14:24:43.660  7065  7065 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 14:24:43.660  1035  1538 D WifiNative-wlan0: doBoolean: SET update_config 1,
09-09 14:24:43.660  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,09-09 14:24:43.660  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED ,
09-09 14:24:43.660  1035  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,09-09 14:24:43.660  1035  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 14:24:43.660  1035  1538 D WifiNative-wlan0: SET update_config 1: returned true,
09-09 14:24:43.660  1035  1538 D WifiConfigStore: Loading config and enabling all networks 
,09-09 14:24:43.660  1035  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,09-09 14:24:43.660  1035  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	,NG700	any	
09-09 14:24:43.661  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming,
09-09 14:24:43.663  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,09-09 14:24:43.663  1035  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 14:24:43.665  1035  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-09 14:24:43.670  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:43.670  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:43.670  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:43.670  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:43.670  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:24:43.670  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:43.670  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:43.672  1035  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 14:24:43.672  1035  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 14:24:43.672  1967  1967 D WfdService: Waiting for WifiP2p enabling
09-09 14:24:43.673  1035  1538 D WifiStateMachine: enableVerboseLogging : level 2
,09-09 14:24:43.673  1035  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 14:24:43.673  1035  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 14:24:43.674  1035  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 14:24:43.674  1035  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 14:24:43.674  1035  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 14:24:43.674  1035  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true,
09-09 14:24:43.674  1035  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 14:24:43.674  1035  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 14:24:43.674  1035  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 14:24:43.675  1035  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 14:24:43.675  1035  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,09-09 14:24:43.675  1035  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 14:24:43.675  1035  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 14:24:43.675  1035  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 14:24:43.681  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 14:24:43.681  1035  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-09 14:24:43.681  1035  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 14:24:43.681  1035  1538 D WifiNative-HAL: Setting external_sim to 1
09-09 14:24:43.681  1035  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 14:24:43.682  1035  1538 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 14:24:43.682  1035  1538 I WifiNative-HAL: startHal
09-09 14:24:43.682  1035  1538 D wifi    : setting scan oui 0xaf504360
09-09 14:24:43.682  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 14:24:43.682  1035  1538 I WifiNative-HAL: startHal
09-09 14:24:43.682  1035  1538 D wifi    : setting scan oui 0xaf504360
09-09 14:24:43.683  1035  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 14:24:43.683  1035  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 14:24:43.683  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 14:24:43.683  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 14:24:43.684  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 14:24:43.684  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 14:24:43.684  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 14:24:43.685  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 14:24:43.685  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 14:24:43.685  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 14:24:43.685  1967  1967 D WfdsService: Supplicant Connection state is changed : true
09-09 14:24:43.685  1967  2387 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 14:24:43.685  1967  2387 D WfdsService: Set the WFDS Monitor: true
09-09 14:24:43.685  1967  2387 D WfdsMonitor: WfdsMonitorThread create
09-09 14:24:43.685  1967  2387 D WfdsMonitor: WFDS Monitor is created and started
09-09 14:24:43.685  1967  2387 D WfdsService: WiFi: Supplicant connection re-established
09-09 14:24:43.685  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 14:24:43.686  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 14:24:43.686  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 14:24:43.686  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 14:24:43.686  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 14:24:43.686  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 14:24:43.686  1967  7082 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 14:24:43.687  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 14:24:43.687  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 14:24:43.687  7065  7065 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 14:24:43.687  1967  7082 E CtrlSupplicant: Succeed to open control connection
09-09 14:24:43.687  1967  7082 E CtrlSupplicant: Succeed to open monitor connection
09-09 14:24:43.687  1967  7082 D WfdsMonitor: Supplicant connection established
09-09 14:24:43.688  1967  2387 D WfdsService: Connected to the supplicant for wfds
09-09 14:24:43.689  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 14:24:43.689  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 14:24:43.689  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 14:24:43.689  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 14:24:43.690  1035  1538 E WifiNative: : [121,107,881 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 14:24:43.690  1035  1538 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 14:24:43.692  1035  1538 D WifiNative-wlan0: RECONNECT: returned true
09-09 14:24:43.692  1035  1538 D WifiNative-wlan0: doString: [STATUS]
09-09 14:24:43.692  1035  7081 D WifiMonito,r: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,09-09 14:24:43.692  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 14:24:43.692  1035  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 14:24:43.692  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:24:43.693  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:24:43.693  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.694  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 14:24:43.695  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-09 14:24:43.695  1035  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.695   309   895 D CommandListener: Setting iface cfg
09-09 14:24:43.695   309   895 D CommandListener: Trying to bring up p2p0
09-09 14:24:43.695  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.695  1035  1556 I WifiNative-HAL: startHal
09-09 14:24:43.695  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf504360
,09-09 14:24:43.695  1035  1556 D wifi    : failed to get capabilities : -3
09-09 14:24:43.695  1035  1556 E WifiScanningService: could not get scan capabilities
09-09 14:24:43.695  1035  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 14:24:43.695  1035  1537 D LGWifiP2pService: P2pEnablingState
09-09 14:24:43.695  1035  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.695  1035  1537 D LGWifiP2pService: P2p socket connection successful
09-09 14:24:43.695  1035  1537 D LGWifiP2pService: P2pEnabledState
09-09 14:24:43.696  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 14:24:43.696  1035  1537 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 14:24:43.697  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 14:24:43.697  1967  1967 D WfdsService: WifiP2pState is changed : true
09-09 14:24:43.697  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 14:24:43.697  1967  2387 D WfdsService: Receive the WFDS_ENABLE Method
09-09 14:24:43.697  1967  2387 D WfdsService: Set the WFDS Monitor: true
09-09 14:24:43.697  1967  2387 D WfdsService: Connected to the supplicant for wfds
,09-09 14:24:43.697  1967  2387 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 14:24:43.697  7065  7065 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 14:24:43.698  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 14:24:43.698  1967  2387 D WfdsService: selectPreferredScanChannel [36]
09-09 14:24:43.698  1967  2387 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 14:24:43.698  1035  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 14:24:43.699  1035  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 14:24:43.699  1035  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 14:24:43.699  1967  1967 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 14:24:43.699  1035  1537 D WifiNative-p2p0: SET device_name G3: returned true
09-09 14:24:43.699  1035  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 14:24:43.699  1035  1537 D LGWifiP2pService: before postfix = G3
09-09 14:24:43.699  1035  1537 D WifiServerServiceExt: postfix byte check : 2
09-09 14:24:43.699  1035  1537 D LGWifiP2pService: after postfix = G3
09-09 14:24:43.699  1035  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-09 14:24:43.700  1967  1967 D WfdsService: isConnected: false
09-09 14:24:43.700  1035  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 14:24:43.700  1035  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-09 14:24:43.700  1035  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 14:24:43.700  1035  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 14:24:43.700  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 14:24:43.700  1035  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 14:24:43.700  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 14:24:43.700  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121119  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:24:43.701  1035  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 14:24:43.701  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress
09-09 14:24:43.701  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-09 14:24:43.703  1035  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 14:24:43.703  1035  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 14:24:43.703  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121122  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:24:43.704  1035  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 14:24:43.704  1035  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 14:24:43.704  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 14:24:43.704  1035  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 14:24:43.704  1035  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 14:24:43.705  1035  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 14:24:43.705  1035  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-09 14:24:43.705  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:43.705  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:43.705  1035  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 14:24:43.706  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:24:43.707  1967  1967 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 14:24:43.707  1967  1967 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 14:24:43.707  1967  1967 D WfdsService: Update P2p Interface State: 3
09-09 14:24:43.708  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:43.708  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:43.708  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 14:24:43.710  1035  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 14:24:43.710  1035  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 14:24:43.714  7036  7036 I HubEmail: JNI_OnLoad()
09-09 14:24:43.715  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 14:24:43.715  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:43.715  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 14:24:43.714  7036  7036 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 14:24:43.715  7036  7036 I HubEmail: registerNatives()
09-09 14:24:43.715  7036  7036 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 14:24:43.715  7036  7036 I HubEmail: registerNativeMethods()
09-09 14:24:43.715  7036  7036 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 14:24:43.716  7065  7065 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 14:24:43.716  1035  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 14:24:43.717  1035  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 14:24:43.717  7036  7036 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-09 14:24:43.717  1035  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 14:24:43.719  1035  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,09-09 14:24:43.719  1035  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 14:24:43.719  1035  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 14:24:43.720  7065  7065 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 14:24:43.721  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 14:24:43.722  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 14:24:43.723  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 14:24:43.723  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 14:24:43.723  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 14:24:43.724  7065  7065 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:24:43.724  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:24:43.724  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:24:43.724  1035  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:24:43.724  1035  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:24:43.724  7065  7065 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 14:24:43.724  7065  7065 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.725  7065  7065 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.725  1035  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 14:24:43.726  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:24:43.726  1035  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:24:43.726  1035  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.726  1035  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.726  1035  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.726  1035  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:24:43.726  1035  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.726  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:24:43.726  1035  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-09 14:24:43.726  1035  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.726  1967  7082 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:24:43.726  1967  7082 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:24:43.727  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:24:43.727  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 14:24:43.727  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 14:24:43.727  7065  7065 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:24:43.727  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 14:24:43.727  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:24:43.727  1035  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:24:43.727  1035  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:24:43.728  1035  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 14:24:43.728  1035  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 14:24:43.728  1035  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 14:24:43.728  1035  1538 D WifiNative-wlan0: doBoolean: SCAN
09-09 14:24:43.729  1035  1538 D WifiNative-wlan0: SCAN: returned false
09-09 14:24:43.729  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=121147  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:24:43.762  1035  1731 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7088 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-09 14:24:43.763  1035  1537 D LGWifiP2pService: InactiveState
09-09 14:24:43.763  1035  1537 D LGWifiP2pService: InactiveState{ when=-59ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.763  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-59ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.763  1035  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 14:24:43.764  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 14:24:43.765  7065  7065 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-09 14:24:43.765  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=121183  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:24:43.765  7065  7065 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 14:24:43.765  1035  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:24:43.766  7065  7065 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.766  1035  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:24:43.766  1035  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:24:43.766  7065  7065 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.766  1035  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:24:43.766  1035  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 14:24:43.767  1035  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: InactiveState{ when=-41ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-41ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1035  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:24:43.767  1035  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1035  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:24:43.767  1035  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:24:43.767  1035  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:24:43.767  1035  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1035  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.767  1035  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1035  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1035  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.767  1035  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.767  1035  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1967  7082 D WfdsMonitor: Event [CTRL-E,VENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.767  1967  7082 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:24:43.767  1967  7082 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:24:43.767  1035  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.768  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.768  1035  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:43.768  1035  1035 E WifiServerServiceExt: No p2p device connected
09-09 14:24:43.769  1967  2387 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 14:24:43.769  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:43.769  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:43.769  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 14:24:43.769  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:43.770  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:43.771  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:24:43.771  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 14:24:43.772  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:43.772  6909  7084 W FormManager: Network not available. Please check & try again.
,09-09 14:24:43.774  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:24:43.774  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-09 14:24:43.779  6909  7085 V FormManager: Network unavailable.
09-09 14:24:43.781  7036  7087 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:43.784  6909  7085 V FormManager: Network unavailable.
09-09 14:24:43.790  1035  1986 I ActivityManager: Killing 6164:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-09 14:24:43.834  1035  1947 W libprocessgroup: failed to open /acct/uid_10080/pid_6164/cgroup.procs: No such file or directory
09-09 14:24:43.927  7088  7088 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:43.927  7088  7088 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:24:43.932  7088  7088 D PhoneMonitor: Register our PhoneStateListener
09-09 14:24:43.954  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 14:24:43.956  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-09 14:24:43.980  7088  7088 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 14:24:43.984  7088  7088 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,09-09 14:24:43.985  7088  7088 D TelephonyAutoProfiling: [parse] Load xml
09-09 14:24:43.990  7088  7088 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-09 14:24:43.991  7088  7088 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-09 14:24:43.991  7088  7088 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-09 14:24:44.002  7088  7088 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 14:24:44.018  1035  1705 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7108 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 14:24:44.018  1035  1705 I ActivityManager: Killing 6194:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-09 14:24:44.052  1035  1051 W libprocessgroup: failed to open /acct/uid_10097/pid_6194/cgroup.procs: No such file or directory
,09-09 14:24:44.257  1035  1051 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7126 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-09 14:24:44.258  1035  1051 I ActivityManager: Killing 6660:com.lge.eula/1000 (adj 15): empty #17
,09-09 14:24:44.264  7065  7065 E wpa_supplicant: USIM:  scard_init function
09-09 14:24:44.265  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 14:24:44.265  1035  7081 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 14:24:44.265  7065  7065 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-09 14:24:44.265  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 14:24:44.265  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-09 14:24:44.265  1035  7081 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 14:24:44.267  1035  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 14:24:44.268  1035  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 14:24:44.268  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 14:24:44.269  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-09 14:24:44.270  1035  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 14:24:44.271  1035  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 14:24:44.271  1035  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-09 14:24:44.320  1035  2113 W libprocessgroup: failed to open /acct/uid_1000/pid_6660/cgroup.procs: No such file or directory
,09-09 14:24:44.328  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121746  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 14:24:44.330  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121749  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 14:24:44.334  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:24:44.334  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.334  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 14:24:44.337  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:44.337  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:44.338  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:24:44.338  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 14:24:44.340  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.386  7065  7065 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 14:24:44.386  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 14:24:44.386  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 14:24:44.387  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 14:24:44.387  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 14:24:44.387  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:24:44.387  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:24:44.389  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=121807  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 14:24:44.389  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=121808  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 14:24:44.390  1035  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121808
09-09 14:24:44.390  1035  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121809
09-09 14:24:44.391  1035  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121809
09-09 14:24:44.391  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121809
09-09 14:24:44.391  1035  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121810
09-09 14:24:44.392  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121810  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 14:24:44.435  1035  1966 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7143 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 14:24:44.436  1035  1966 I ActivityManager: Killing 6681:com.lge.bnr/1000 (adj 15): empty #17
,09-09 14:24:44.448  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-09 14:24:44.448  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:24:44.448  7065  7065 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:24:44.449  7065  7065 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:24:44.449  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 14:24:44.449  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:24:44.449  1035  7081 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:24:44.450  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-09 14:24:44.450  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:24:44.451  1035  7081 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:24:44.451  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:24:44.452  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-09 14:24:44.502  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 14:24:44.504  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:44.504  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:44.506  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.508  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.509  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.509  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 14:24:44.521  1035  1984 W libprocessgroup: failed to open /acct/uid_1000/pid_6681/cgroup.procs: No such file or directory
,09-09 14:24:44.527  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121945  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-09 14:24:44.534  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.534  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.534  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 14:24:44.534  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:24:44.535  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 14:24:44.535  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=121953  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 14:24:44.535  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:44.535  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:44.536  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=121954  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 14:24:44.536  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.538  1035  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121956
09-09 14:24:44.539  1035  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121957
09-09 14:24:44.540  1035  1538 D WifiNative-wlan0: doString: [STATUS]
09-09 14:24:44.541  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:24:44.541  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:24:44.542  1035  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 14:24:44.547  1035  1538 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 14:24:44.558  7143  7143 I art     : Almond Protected OAT
,09-09 14:24:44.568  1035  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 14:24:44.568  1035  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-09 14:24:44.571  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:44.571  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 14:24:44.572  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.572  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.572  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 14:24:44.572  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.581  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.581  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.581  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 14:24:44.584  1035  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 14:24:44.584  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:24:44.584  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:24:44.584  1035  1544 D ConnectivityService: Got NetworkAgent Messenger
09-09 14:24:44.584  1035  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 14:24:44.584  1035  1544 D ConnectivityService: NetworkAgent connected
09-09 14:24:44.584  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:24:44.584  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-09 14:24:44.589  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:24:44.590  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:24:44.590  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:24:44.590  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:24:44.590  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 14:24:44.593  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:44.593  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:44.594  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.594  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:24:44.596   309   895 D CommandListener: Setting iface cfg
,09-09 14:24:44.598  1035  1538 E WifiStateMachine: Start Dhcp Watchdog 2
09-09 14:24:44.598  1035  7161 D DhcpStateMachine: StoppedState
09-09 14:24:44.598  1035  7161 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:44.599  1035  7161 D DhcpStateMachine: WaitBeforeStartState
09-09 14:24:44.599  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122017  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:24:44.599  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122017  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:24:44.600  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122018  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:24:44.600  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:44.600  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:44.601  1035  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:44.601  1035  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:44.601  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:44.602  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:44.603  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:24:44.603  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 14:24:44.604  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:24:44.604  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 14:24:44.604  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122023  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:24:44.605  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122023  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:24:44.605  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122023  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:24:44.606  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:76082] from screen [on:0 period:250102078] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 14:24:44.607  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:250102079] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 14:24:44.607  1035  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 14:24:44.611  1035  1544 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-09 14:24:44.611  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:44.611  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:44.612  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:44.612  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:44.612  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:44.613  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:44.613  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=121,0,0
09-09 14:24:44.614  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=121,0,0
09-09 14:24:44.614  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 14:24:44.614  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 14:24:44.614  1035  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 14:24:44.614  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.614  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 14:24:44.614  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 14:24:44.615  1035  1538 D WifiNative-wlan0: SET ps 0: returned true
09-09 14:24:44.615  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 14:24:44.615  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 14:24:44.615  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 14:24:44.615  1035  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 14:24:44.615  1035  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 14:24:44.615  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@75cb2f7 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:44.615  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@75cb2f7 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:44.615  1035  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 14:24:44.615  1035  7161 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:44.615  1035  7161 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 14:24:44.616   309   895 D CommandListener: Setting iface cfg
09-09 14:24:44.617   309   895 D CommandListener: Trying to bring up wlan0
09-09 14:24:44.617  1035  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 14:24:44.618  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:24:44.618  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-09 14:24:44.619  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION,
09-09 14:24:44.619  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 14:24:44.619  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-09 14:24:44.620  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:44.620  7143  7143 D WeatherApplication: removeAccount
09-09 14:24:44.620  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-09 14:24:44.621  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:44.621  7143  7143 D WeatherApplication: Account.length = 0
,09-09 14:24:44.621  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:44.621  7143  7143 E WeatherApplication: OPERATOR:OPEN
09-09 14:24:44.622  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0,
09-09 14:24:44.622  1035  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 14:24:44.622  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 14:24:44.623  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4,
09-09 14:24:44.623  1035  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:44.624  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:24:44.625  7143  7143 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:44
09-09 14:24:44.625  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:24:44.626  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-09 14:24:44.626  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:24:44.626  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,09-09 14:24:44.626  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 14:24:44.626  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,09-09 14:24:44.626  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:24:44.628  7143  7143 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 14:24:44.628  7143  7143 D Weather.Utils: 2 : All the weather widget is gone.
,09-09 14:24:44.630  7143  7143 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-09 14:24:44.632  7143  7143 D WeatherAncestor: connectivity changed - connection : true
,09-09 14:24:44.633  7143  7143 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-09 14:24:44.641  7143  7143 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:24:44.641  7143  7143 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:24:44.642  7143  7143 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-09 14:24:44.647  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:44.647  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:24:44.647  1035  1537 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:24:44.649  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:24:44.650  1035  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 14:24:44.650  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 14:24:44.650  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 14:24:44.650  1035  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 14:24:44.651  1035  1544 D ConnectivityService: ignoring duplicate network state non-change
09-09 14:24:44.653  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:44.653  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:44.655  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.655  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.655  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 14:24:44.656  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.657  1035  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 14:24:44.657  1035  1544 D ConnectivityService: Adding iface wlan0 to network 101
09-09 14:24:44.663  7143  7143 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:24:44.663  7143  7143 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:44
,09-09 14:24:44.666  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.666  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.666  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 14:24:44.669  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 14:24:44.671  1967  1967 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 14:24:44.673  1035  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 14:24:44.675  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.675  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.675  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 14:24:44.677  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:44.678  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 14:24:44.680  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.680  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 14:24:44.684  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:44.684  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 14:24:44.684  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.685  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.685  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:44.685  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 14:24:44.689  1035  1544 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 14:24:44.690  1035  1544 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-09 14:24:44.690  1035  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:24:44.691  1035  1544 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 14:24:44.691  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:24:44.691  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:24:44.692   309   895 E Netd    : netlink response contains error (File exists)
09-09 14:24:44.692  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-09 14:24:44.692  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:24:44.692  1035  1544 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 14:24:44.692  1035  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:24:44.693  1035  1544 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 14:24:44.693  1035  1544 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-09 14:24:44.693  1035  1544 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-09 14:24:44.703  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:44.704  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,09-09 14:24:44.704  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.744  1035  1986 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7165 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 14:24:44.746  1035  1986 I ActivityManager: Killing 2167:com.lge.music/u0a34 (adj 15): empty #17
,09-09 14:24:44.763   316  1384 V AudioFlinger: 2167 died, releasing its sessions
09-09 14:24:44.763   316  1384 V AudioFlinger:  pid 1878 @ 0
09-09 14:24:44.763   316  1384 V AudioFlinger:  pid 3435 @ 1
09-09 14:24:44.763   316  1384 V AudioFlinger:  pid 3435 @ 2
,09-09 14:24:44.817  1035  7161 D DhcpStateMachine: DHCPV4 request on wlan0
,09-09 14:24:44.817  1035  7161 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 14:24:44.817  1035  7161 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 14:24:44.812  7182  7182 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:44.812  7182  7182 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:44.837  7182  7182 I dhcpcd  : version 5.5.6 starting
09-09 14:24:44.839  7182  7182 E dhcpcd  : get_duid: m
09-09 14:24:44.839  7182  7182 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 14:24:44.839  7182  7182 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-09 14:24:44.850  1035  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 14:24:44.851  1035  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 14:24:44.851  1035  1575 W libprocessgroup: failed to open /acct/uid_10034/pid_2167/cgroup.procs: No such file or directory
09-09 14:24:44.851  1035  1544 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 14:24:44.851  1035  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 14:24:44.851  1035  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:24:44.852  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:44.852  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 14:24:44.852  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:44.852  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 14:24:44.855  1035  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,09-09 14:24:44.855  1035  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 14:24:44.856  1035  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:44.856  1035  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 14:24:44.856  1035  1544 D ConnectivityService: currentScore = 0, newScore = 20
09-09 14:24:44.856  1035  1544 D ConnectivityService:    accepting network in place of null
09-09 14:24:44.856  1035  1544 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:44.857  1878  1878 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:44.858  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:24:44.859  1035  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:44.859  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:24:44.860  1035  1544 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 14:24:44.861  1035  1544 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 14:24:44.861  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:24:44.862   309  7186 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 14:24:44.869  1035  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:44.875  1035  1544 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 14:24:44.877  1035  1544 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 14:24:44.881  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 14:24:44.881  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:24:44.881  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,09-09 14:24:44.881  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:24:44.888  1035  1544 D ConnectivityService: validation of new default Network = false
09-09 14:24:44.888  1035  1544 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 14:24:44.888  1035  1544 D DSQN    : enableDataServiceNotify 
09-09 14:24:44.888  1035  1544 D DSQN    : start dsqn bin
,09-09 14:24:44.897  1035  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 14:24:44.897  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:44.897  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:24:44.897  1035  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:24:44.892  7190  7190 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:44.892  7190  7190 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:44.900  1601  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 14:24:44.918  7190  7190 E DSQN    : DSQN ssw
,09-09 14:24:44.924  1035  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 14:24:44.926  1839  7193 I CheckinService: active receiver: enabled
09-09 14:24:44.929  7182  7182 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 14:24:44.929  7182  7182 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 14:24:44.929  7182  7182 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 14:24:44.929  7182  7182 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 14:24:44.929  7182  7182 D dhcpcd  : wlan0: sending REQUEST (xid 0x7baaf832), next in 4.94 seconds
,09-09 14:24:44.949  1839  7193 I CheckinService: Preparing to send checkin request
09-09 14:24:44.949  1839  7193 I EventLogService: Accumulating logs since 1473423820745
09-09 14:24:44.957  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:24:44.958  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.959  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:44.979  7182  7182 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-09 14:24:44.996  1839  7193 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-09 14:24:45.004  7182  7182 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 14:24:45.004  7182  7182 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-09 14:24:45.005  7182  7182 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 14:24:45.005  7182  7182 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 14:24:45.005  7182  7182 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 14:24:45.005  7182  7182 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 14:24:45.005  7182  7182 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 14:24:45.005  7182  7182 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-09 14:24:45.020   278   384 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 14:24:45.020   278   384 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 14:24:45.020   278   384 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 14:24:45.020   309  7186 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-09 14:24:45.021  7165  7199 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 14:24:45.023   278   384 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-09 14:24:45.023   278   384 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 14:24:45.023   278   384 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 14:24:45.023  7165  7199 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 14:24:45.038   278   384 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-09 14:24:45.038   278   384 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-09 14:24:45.038   278   384 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 14:24:45.040  7165  7206 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 14:24:45.043   278   384 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 14:24:45.043   278   384 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 14:24:45.043   278   384 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 14:24:45.043  7165  7206 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 14:24:45.057   309  7186 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-09 14:24:45.079  1035  2009 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7213 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-09 14:24:45.089   309   894 D LGDataListener: argv[0]=dsqncommand
09-09 14:24:45.089   309   894 D LGDataListener: argv[1]=wlan0
09-09 14:24:45.089   309   894 D LGDataListener: argv[2]=1
09-09 14:24:45.090   309   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 14:24:45.090  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 14:24:45.090  1035  1115 D DSQN    : start to monitor internet connection
,09-09 14:24:45.117  7213  7213 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 14:24:45.117  7213  7213 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 14:24:45.124  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 12:24:45 GMT], X-Android-Received-Millis=[1473423885123], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473423885089]}
09-09 14:24:45.124  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 14:24:45.124  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 14:24:45.124  1035  1544 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-09 14:24:45.124  1035  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 14:24:45.124  1035  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:24:45.124  1035  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:24:45.124  1035  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 14:24:45.124  1035  1544 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-09 14:24:45.124  1035  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 14:24:45.124  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:45.124  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:24:45.125  1035  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:24:45.125  1035  1544 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:45.125  1035  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:45.125  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:24:45.125  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 14:24:45.126  1601  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 14:24:45.126  1878  1878 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:45.126  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:24:45.139  7213  7213 I MultiDex: VM with version 2.1.0 has multidex support
09-09 14:24:45.139  7213  7213 I MultiDex: install
09-09 14:24:45.139  7213  7213 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-09 14:24:45.141  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:24:45.142  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:45.142  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:24:45.147  7213  7213 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-09 14:24:45.220  1035  7161 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-09 14:24:45.221  1035  7161 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 14:24:45.221  1035  7161 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 14:24:45.221  1035  7161 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,09-09 14:24:45.221  1035  7161 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 14:24:45.221  1035  7161 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 14:24:45.221  1035  7161 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 14:24:45.221  1035  7161 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 14:24:45.221  1035  7161 D DhcpStateMachine: RunningState
09-09 14:24:45.265  7165  7165 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 14:24:45.299  7165  7165 I LibraryLoader: Loading: webviewchromium
,09-09 14:24:45.304  7165  7165 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 2728-2735)
09-09 14:24:45.305  7165  7165 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:24:45.312  7165  7165 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d9c3a5d}
,09-09 14:24:45.315  7165  7165 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:24:45.315  7165  7165 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 14:24:45.327  7165  7165 I BrowserStartupController: Initializing chromium process, renderers=0
,09-09 14:24:45.329  7165  7165 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 14:24:45.347  7165  7165 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-09 14:24:45.358  7165  7165 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-09 14:24:45.359  7165  7165 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-09 14:24:45.364   316  1383 V AudioPolicyService: registerClient() client 0xb1021b40, uid 10093
,09-09 14:24:45.367  7165  7264 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 14:24:45.376  7165  7165 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:24:45.376  7165  7165 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:24:45.376  7165  7165 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:24:45.376  7165  7165 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:24:45.376  7165  7165 I Adreno-EGL: Remote Branch: 
09-09 14:24:45.376  7165  7165 I Adreno-EGL: Local Patches: 
09-09 14:24:45.376  7165  7165 I Adreno-EGL: Reconstruct Branch: 
,09-09 14:24:45.449  7165  7165 I NSApplication: Starting up...
,09-09 14:24:45.494  1035  1051 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7278 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-09 14:24:45.494  1035  1051 I ActivityManager: Killing 6126:com.android.vending/u0a44 (adj 15): empty #17
09-09 14:24:45.527  7277  7277 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 14:24:45.562  1035  1986 W libprocessgroup: failed to open /acct/uid_10044/pid_6126/cgroup.procs: No such file or directory
,09-09 14:24:45.604  7278  7278 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 14:24:45.609  7277  7277 I dex2oat : dex2oat took 81.650ms (threads: 4)
,09-09 14:24:45.625  7213  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:24:45.625  7213  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:24:45.625  7213  7235 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:24:45.625  7213  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:24:45.625  7213  7235 I Adreno-EGL: Remote Branch: 
09-09 14:24:45.625  7213  7235 I Adreno-EGL: Local Patches: 
09-09 14:24:45.625  7213  7235 I Adreno-EGL: Reconstruct Branch: 
,09-09 14:24:45.723  1035  1705 D WifiServiceImplEx: setWifiEnabled: false pid=6588, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:24:45.723  1035  1705 D WifiService: setWifiEnabled: false pid=6588, uid=10118
,09-09 14:24:45.723  1035  1705 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:24:45.740  1035  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:45.740  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:24:45.740  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:24:45.740  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:45.740  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-09 14:24:45.741  1035  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:45.741  1035  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:45.741  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 14:24:45.741  1035  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 14:24:45.741  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:24:45.742  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:24:45.742  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:24:45.742  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-09 14:24:45.750  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:24:45.750  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:24:45.750  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:24:45.750  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.750  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.750  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:24:45.750  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:24:45.750  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:24:45.750  1035  7161 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.751   309   895 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:24:45.773  1035  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 14:24:45.774  1035  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-09 14:24:45.775  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-09 14:24:45.776  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:45.776  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:45.778  1967  1967 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 14:24:45.779  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:45.779  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:24:45.779  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:45.779  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-09 14:24:45.779  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:45.779  1035  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 14:24:45.779  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:24:45.789  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:45.789  1035  1537 D LGWifiP2pService: InactiveState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.789  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.790  1035  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@120ed78
09-09 14:24:45.791  1035  1537 D LGWifiP2pService: P2pDisablingState
,09-09 14:24:45.791  1035  1537 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.791  1035  1537 D LGWifiP2pService: p2p socket connection lost
09-09 14:24:45.791  1035  1537 D LGWifiP2pService: P2pDisabledState
09-09 14:24:45.792  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-09 14:24:45.792  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:45.792  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:45.792  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:24:45.792  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 14:24:45.792  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-09 14:24:45.793  1035  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.793  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.793  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 14:24:45.793  1967  1967 D WfdsService: WifiP2pState is changed : false
09-09 14:24:45.793  1967  2387 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 14:24:45.793  1967  2387 D WfdsService: Set the WFDS Monitor: false
09-09 14:24:45.794  1035  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 14:24:45.794  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:24:45.794  1967  2387 D WfdsMonitor: WFDS Monitor is stopped
09-09 14:24:45.794  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.794  1967  2387 D WfdsService: STATE : WfdsDisabledState - enter
09-09 14:24:45.794  1035  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.794  7065  7065 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:24:45.794  1967  2388 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 14:24:45.795  1967  7082 D CtrlSupplicant: Received on exit socket, terminate
09-09 14:24:45.795  1967  7082 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 14:24:45.795  1967  7082 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 14:24:45.795  1967  7082 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 14:24:45.795  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:24:45.795  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:24:45.795  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:24:45.795  1967  2387 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 14:24:45.808  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:45.808  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 14:24:45.811  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:45.818   309   895 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:24:45.818  1035  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 14:24:45.818  1035  1544 D DSQN    : disableDataServiceNotify
09-09 14:24:45.818  1035  1544 D DSQN    : stop dsqn bin
09-09 14:24:45.819  1035  1538 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 14:24:45.821  1035  1035 D WifiHS20: hidePasspointNotification off =false
,09-09 14:24:45.821  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:45.821  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:45.821  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:24:45.821  1035  1538 D WifiNative-p2p0: TERMINATE: returned true
09-09 14:24:45.821  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:24:45.821  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:24:45.821  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:24:45.823  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 14:24:45.823  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 14:24:45.824  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:45.824  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:45.824  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:45.824  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:45.824  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:45.824  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:45.824  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:45.824  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:45.824  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:45.824  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:45.824  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:45.824  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:24:45.824  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 14:24:45.825  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:45.825  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:45.825  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:45.825  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:45.825  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:45.825  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:45.825  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:45.825  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:45.825  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:24:45.825  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:45.825  6588  6588 D io.jxcore.node.JXcoreExtension: ,notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:45.826  1035  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 14:24:45.826  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:45.827  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:24:45.827  1035  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:24:45.827  1035  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 14:24:45.827  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.827  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.827  1035  7160 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 14:24:45.828  1035  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 14:24:45.828  1035  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 14:24:45.828  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:24:45.828  1601  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 14:24:45.829  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 14:24:45.829  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:24:45.830  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:45.831  7213  7235 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:45.831  7213  7235 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 14:24:45.831  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:45.832  1035  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:45.832  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-09 14:24:45.834  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 14:24:45.834  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 14:24:45.834  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:24:45.834  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:24:45.834  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:24:45.836  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 14:24:45.836  1035  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:45.836  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:24:45.836  1035  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:45.836  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:24:45.836  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:24:45.836  1035  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:45.836  1035  1544 D NetworkManagementService: Removing idletimer
09-09 14:24:45.836  1035  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:45.836  1035  1544 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 14:24:45.837  1035  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:45.837  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:24:45.837  1035  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 14:24:45.837  1878  1878 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:24:45.837  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:24:45.864  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:24:45.865  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:24:45.865  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:24:45.882  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:24:45.883  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:45.883  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:45.897  1035  1544 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 14:24:45.901  1035  2009 I art     : Explicit concurrent mark sweep GC freed 117296(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.359ms total 199.800ms
09-09 14:24:45.950  7065  7065 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 14:24:45.950  7065  7065 I wpa_supplicant: monitor socket send errors count : 1
09-09 14:24:45.950  7065  7065 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1967-4\x00 that cannot receive messages
09-09 14:24:45.952  1035  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 14:24:45.952  1035  7081 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-09 14:24:45.955  1035  7161 D DhcpStateMachine: StoppedState
09-09 14:24:45.956  1035  7161 D DhcpStateMachine: StoppedState{ when=-161ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:24:45.957  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 14:24:45.958  1035  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 14:24:45.973  7065  7065 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:24:45.975  7065  7065 W wpa_supplicant: USIM:  scard_deinit function
09-09 14:24:45.975  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-09 14:24:45.975  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:24:45.975  1035  7081 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:24:45.975  1035  7081 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 14:24:45.976  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:24:45.976  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:24:45.976  1035  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123394
09-09 14:24:45.976  1035  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123394
,09-09 14:24:45.976  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=123395  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 14:24:45.977  1035  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=123395  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 14:24:45.977  1035  1117 D Tethering: InitialState.processMessage what=4
09-09 14:24:45.981  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:24:45.982  1035  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:45.983  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:24:45.985  7213  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:24:45.985  7213  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:24:45.985  7213  7235 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:24:45.985  7213  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:24:45.985  7213  7235 I Adreno-EGL: Remote Branch: 
09-09 14:24:45.985  7213  7235 I Adreno-EGL: Local Patches: 
09-09 14:24:45.985  7213  7235 I Adreno-EGL: Reconstruct Branch: 
09-09 14:24:46.069  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 14:24:46.072  7213  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:24:46.072  7213  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:24:46.072  7213  7235 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:24:46.072  7213  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:24:46.072  7213  7235 I Adreno-EGL: Remote Branch: 
09-09 14:24:46.072  7213  7235 I Adreno-EGL: Local Patches: 
09-09 14:24:46.072  7213  7235 I Adreno-EGL: Reconstruct Branch: 
09-09 14:24:46.074  6396  6434 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 14:24:46.096  2219  2219 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:46.104  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:24:46.104  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:46.105  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:24:46.105  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 14:24:46.106  7009  7009 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 14:24:46.109  7009  7009 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1badebca
09-09 14:24:46.109  7009  7009 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:24:46.109  7009  7009 D AppUp4:CustFacade: isPhone : true
09-09 14:24:46.110  7009  7009 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:24:46.111  7009  7009 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 14:24:46.115  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:46.115  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:24:46.116  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:46.118  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:46.119  7065  7065 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 14:24:46.124  1035  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 14:24:46.124  1035  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 14:24:46.124  1035  7081 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 14:24:46.125  1035  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
09-09 14:24:46.129  7036  7036 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 14:24:46.132  4351  7315 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:24:46.132  1035  1538 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 14:24:46.132  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:24:46.132  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:24:46.132  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 14:24:46.136  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:24:46.137  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:46.137  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:46.137  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:46.137  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:46.137  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:46.137  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:46.137  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:46.137  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:46.137  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:46.137  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 14:24:46.137  4351  7316 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:46.137  1035  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 14:24:46.137  1035  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 14:24:46.137  4351  7316 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:24:46.143  1967  1967 D WfdsService: Supplicant Connection state is changed : false
09-09 14:24:46.143  1967  2387 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 14:24:46.143  1967  2387 D WfdsService: Set the WFDS Monitor: false
09-09 14:24:46.143  1967  2387 D WfdsMonitor: WFDS Monitor is stopped
09-09 14:24:46.143  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 14:24:46.143  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:46.143  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:46.143  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:46.143  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:46.143  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:46.143  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:46.143  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:46.143  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:46.143  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:46.144  2465  2465 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:46.152  7036  7317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:24:46.158  6909  7321 W FormManager: Network not available. Please check & try again.
,09-09 14:24:46.164  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 14:24:46.164  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:46.164  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 14:24:46.167  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 14:24:46.167  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 14:24:46.174   309  7326 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 14:24:46.174  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 14:24:46.174  1839  7193 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,09-09 14:24:46.182  7143  7143 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:46
,09-09 14:24:46.182  6909  7322 V FormManager: Network unavailable.
09-09 14:24:46.184  7143  7143 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 14:24:46.184  7143  7143 D Weather.Utils: 2 : All the weather widget is gone.
09-09 14:24:46.184  7143  7143 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 14:24:46.185  7143  7143 D WeatherAncestor: connectivity changed - connection : true
09-09 14:24:46.185  7143  7143 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17dd5058
09-09 14:24:46.185  7143  7143 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:24:46.185  7143  7143 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:24:46.185  7143  7143 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 14:24:46.185  7143  7143 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:24:46.186  7143  7143 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:46
09-09 14:24:46.187  6909  7322 V FormManager: Network unavailable.
09-09 14:24:46.188  1839  7193 I CheckinService: active receiver: disabled
,09-09 14:24:46.215  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-09 14:24:46.215  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:24:46.215  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:24:46.215  6819  6819 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 14:24:46.215  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 14:24:46.216  6819  6819 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:24:46.216  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 14:24:46.216  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:24:46.216  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:24:46.216  6819  6819 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:24:46.216  6819  6819 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-09 14:24:46.224  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:46.227  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 14:24:46.232  6909  7328 W FormManager: Network not available. Please check & try again.
09-09 14:24:46.233  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:46.239  6909  7329 V FormManager: Network unavailable.
,09-09 14:24:46.241  6909  7329 V FormManager: Network unavailable.
09-09 14:24:46.253  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:24:46.258  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 14:24:46.262  6909  7331 W FormManager: Network not available. Please check & try again.
09-09 14:24:46.264  6909  7332 V FormManager: Network unavailable.
,09-09 14:24:46.265  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:46.270  6909  7332 V FormManager: Network unavailable.
09-09 14:24:46.279  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:24:46.279  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:24:46.281  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:24:46.283  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:46.286  4351  7333 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:24:46.290  4351  7334 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:24:46.290  4351  7334 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:24:46.315  1035  1986 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7335 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-09 14:24:46.331   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 312us total 14.347ms
,09-09 14:24:46.344   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 253us total 12.953ms
,09-09 14:24:46.356   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 255us total 11.780ms
,09-09 14:24:46.397  6713  6986 D UEI.SmartControl: Internal timer expired: 2
09-09 14:24:46.397  6713  6986 D UEI.SmartControl: unbind internal service
,09-09 14:24:46.418  7335  7335 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 14:24:46.418  7335  7335 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 14:24:46.424  7335  7335 V [BNRBootReceiver]: Boot Receiver Return
09-09 14:24:46.424  7335  7335 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 14:24:46.426  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:46.432  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.442  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:24:46.458  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:46.459  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 14:24:46.462  6867  6867 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:24:46.465  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:46.472  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.484  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:24:46.497  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:46.498  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:46.500  6867  6867 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:24:46.504  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-09 14:24:46.509  6819  6819 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 14:24:46.514  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 14:24:46.530  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.534  6713  6983 D serial_port: close(fd = 24)
09-09 14:24:46.539  6713  6983 I UEI.SmartControl: Serial port is closed.
09-09 14:24:46.541  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:46.556  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:24:46.556  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:46.558  6867  6867 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:24:46.563  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:46.571  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.581  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:46.590  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:24:46.591  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:46.592  6867  6867 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:24:46.596  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:46.608  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.621  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:46.635  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:24:46.636  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:46.637  6867  6867 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:24:46.644  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:46.656  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.666  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:46.677  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:46.678  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:46.679  6867  6867 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:24:46.685  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:46.698  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.701  1035  1398 V AlarmManager: ELAPSED_WAKEUP set : Alarm{16d9c5c7 type 2 when 124117 com.google.android.gms} when 124117
,09-09 14:24:46.710  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:46.718  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:46.719  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:46.719  6867  6867 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:24:46.732  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 14:24:46.753  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.763  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:46.771  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:46.771  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:46.776  6867  6867 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:24:46.780  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 14:24:46.793  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.802  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:24:46.811  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:46.812  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:46.814  6867  6867 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:24:46.820  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:46.825  6839  6839 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 14:24:46.837  1035  1543 D WifiService: New client listening to asynchronous messages
,09-09 14:24:46.838  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:46.844  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.852  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:24:46.870  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:46.870  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:46.873  6867  6867 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 14:24:46.875  6867  6867 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 14:24:46.876  6867  6867 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-09 14:24:46.884  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:46.892  6839  6839 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 14:24:46.895  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:46.900  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:46.908  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:46.917  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:46.917  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 14:24:46.918  6867  6867 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-09 14:24:46.919  6867  6867 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-09 14:24:46.920  6867  6867 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 14:24:46.925  1035  2030 I ActivityManager: Killing 6800:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-09 14:24:47.019  1035  2075 W libprocessgroup: failed to open /acct/uid_10037/pid_6800/cgroup.procs: No such file or directory
,09-09 14:24:47.033  2219  2219 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-09 14:24:47.051  2219  2219 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-09 14:24:47.053  2219  2219 D c       : Getting all permits...
09-09 14:24:47.053  2219  2219 D a       : Opening database...
09-09 14:24:47.063  2219  2219 D a       : Opening database auth.proximity.permit_store...
09-09 14:24:47.065  2219  2219 D a       : Closing database...
,09-09 14:24:47.081  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 14:24:47.084  6839  6839 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 14:24:47.084  6839  6839 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:24:47.084  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:47.089  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:24:47.095  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:24:47.107  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:47.107  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:47.109  6867  6867 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:24:47.117  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:47.121  6839  6839 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 14:24:47.122  6839  6839 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-09 14:24:47.122  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:47.126  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:24:47.132  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:47.140  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:47.140  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 14:24:47.142  6867  6867 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 14:24:47.146  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:24:47.150  6839  6839 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 14:24:47.151  6839  6839 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:24:47.151  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:47.155  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:24:47.164  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:24:47.171  6867  6867 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:24:47.171  6867  6867 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:24:47.173  6867  6867 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:24:47.182  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:47.186  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 14:24:47.194  6909  7360 W FormManager: Network not available. Please check & try again.
09-09 14:24:47.196  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:47.206  6909  7361 V FormManager: Network unavailable.
,09-09 14:24:47.210  6909  7361 V FormManager: Network unavailable.
09-09 14:24:47.218  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:24:47.219  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 14:24:47.224  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:47.226  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:47.236  4351  7362 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 14:24:47.238  4351  7363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:24:47.244  6839  6839 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 14:24:47.244  6839  6839 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:24:47.244  6839  6839 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:24:47.244  4351  7363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:24:47.254  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 14:24:47.259  6909  7365 W FormManager: Network not available. Please check & try again.
09-09 14:24:47.263  6909  7366 V FormManager: Network unavailable.
09-09 14:24:47.264  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:24:47.270  6909  7366 V FormManager: Network unavailable.
,09-09 14:24:47.283  2219  2219 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-09 14:24:47.302   309  7368 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-09 14:24:47.303  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-09 14:24:47.303  6867  6867 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-09 14:24:47.303  6867  6867 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9086
,09-09 14:24:47.613  1035  1538 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:250105085] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 14:24:47.615  1035  1538 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:250105087] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 14:24:47.872  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:47.877  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-09 14:24:47.878  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:47.887  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:47.891  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:47.899  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 14:24:47.904  6396  6434 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 14:24:47.945  5789  5789 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 14:24:47.959  2219  2219 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:47.977  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:24:47.977  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:47.978  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:24:47.978  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 14:24:47.982  7009  7009 I AppUp4:CustModeStarterReceiver: onReceive
09-09 14:24:47.986  7009  7009 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1badebca
09-09 14:24:47.986  7009  7009 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:24:47.986  7009  7009 D AppUp4:CustFacade: isPhone : true
09-09 14:24:47.987  7009  7009 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:24:47.987  7009  7009 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 14:24:47.992  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:47.992  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:24:47.993  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:24:47.999  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:48.007  7036  7036 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 14:24:48.027  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 14:24:48.027  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:48.027  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = true
09-09 14:24:48.028  3435  3435 D PhoneState: setPdpRejectCasuse : false
,09-09 14:24:48.039  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 14:24:48.039  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-09 14:24:48.044  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:48.052  4351  7389 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:24:48.053  4351  7394 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:48.053  4351  7394 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 14:24:48.059  6909  7390 W FormManager: Network not available. Please check & try again.
09-09 14:24:48.064  7143  7143 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:48
,09-09 14:24:48.068  7036  7395 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:24:48.069  7143  7143 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 14:24:48.069  7143  7143 D Weather.Utils: 2 : All the weather widget is gone.
09-09 14:24:48.070  7143  7143 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 14:24:48.070  7143  7143 D WeatherAncestor: connectivity changed - connection : true
09-09 14:24:48.070  7143  7143 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17dd5058
09-09 14:24:48.071  7143  7143 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:24:48.071  7143  7143 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:24:48.071  7143  7143 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 14:24:48.071  7143  7143 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:24:48.071  7143  7143 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:48
09-09 14:24:48.076  6909  7391 V FormManager: Network unavailable.
,09-09 14:24:48.085  6909  7391 V FormManager: Network unavailable.
,09-09 14:24:48.742  1035  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:48.743  1035  1947 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-09 14:24:48.772  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:24:48.773  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:24:48.773  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-09 14:24:48.776  1035  1117 D BluetoothManagerService: Message: 1
09-09 14:24:48.776  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-09 14:24:48.803  1035  1117 D BluetoothManagerService: Message: 20
09-09 14:24:48.803  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22cd58d:true
,09-09 14:24:48.807  6934  6934 D BluetoothAdapterState: make
09-09 14:24:48.812  6934  6934 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 14:24:48.812  6934  6934 I bluedroid-qcom: init
09-09 14:24:48.813  6934  7408 I BluetoothAdapterState: Entering OffState
09-09 14:24:48.813  6934  6934 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 14:24:48.814  6934  6934 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 14:24:48.814  6934  6934 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 14:24:48.814  6934  6934 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 14:24:48.814  6934  6934 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 14:24:48.816  6934  6934 I bluedroid-qcom: get_profile_interface socket
09-09 14:24:48.816  6934  6934 I bluedroid-qcom: get_profile_interface map_client
,09-09 14:24:48.821  6934  7412 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 14:24:48.823  6934  7412 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 14:24:48.812  7411  7411 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:48.812  7411  7411 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:48.833  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:48.837  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:48.842  7411  7411 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-09 14:24:48.842  7411  7411 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-09 14:24:48.842  7411  7411 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-09 14:24:48.843  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-09 14:24:48.844  7411  7411 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 14:24:48.849  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:48.853  7411  7411 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-09 14:24:48.853  7411  7411 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-09 14:24:48.856  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:48.873  6934  7412 D BluetoothAdapterProperties: Name is: G3
,09-09 14:24:48.876  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-09 14:24:48.883  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:48.885  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:48.887  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 14:24:48.888  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 14:24:48.889  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-09 14:24:48.889  1035  1117 D BluetoothManagerService: Message: 40
09-09 14:24:48.889  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 14:24:48.890  6934  6953 I bluedroid-qcom: config_hci_snoop_log
09-09 14:24:48.892  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 14:24:48.892  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-09 14:24:48.897  6934  7408 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-09 14:24:48.898  6934  7408 D BluetoothAdapterProperties: Setting state to 11
09-09 14:24:48.898  6934  7408 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-09 14:24:48.905  6934  7408 I LGBluetoothServiceJni: classInitNative: succeeds
09-09 14:24:48.913  1035  1117 D BluetoothManagerService: Message: 60
09-09 14:24:48.913  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,09-09 14:24:48.914  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,09-09 14:24:48.916  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:48.918  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-09 14:24:48.919  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:48.922  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:48.924  6819  6819 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 14:24:48.925  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 14:24:48.926  6396  6434 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 14:24:48.930  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:48.931  6934  7408 D BluetoothBondStateMachine: make
09-09 14:24:48.933  6934  6934 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:24:48.934  6934  6934 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:48.934  6934  6934 V BluetoothPbapReceiver: ***********state = 11
09-09 14:24:48.934  5789  5789 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-09 14:24:48.936  6934  7408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:48.936  6934  7408 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 14:24:48.936  6934  7408 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:48.936  6934  7408 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-09 14:24:48.937  6934  7428 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 14:24:48.937  6934  7408 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 14:24:48.941  6934  7408 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 14:24:48.950  2219  2219 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:24:48.950  5789  5789 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-09 14:24:48.957  6934  7408 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 14:24:48.959  6934  6934 D HeadsetService: Received start request. Starting profile...
09-09 14:24:48.960  6934  6934 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:24:48.960  6934  6934 D LGBluetoothHfpAdapter: Version 1.6
09-09 14:24:48.961  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:48.963  6934  6934 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 14:24:48.964  6934  6934 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:24:48.965  6934  6934 D HeadsetStateMachine: make
09-09 14:24:48.998  1035  2113 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7431 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-09 14:24:49.004  6934  6934 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:49.005  6934  6934 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:24:49.012  6934  7408 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:24:49.013  6934  6934 D HeadsetStateMachine: max_hf_connections = 1
09-09 14:24:49.013  6934  6934 I bluedroid-qcom: get_profile_interface handsfree
09-09 14:24:49.016  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:49.017  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:24:49.018  2219  2219 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:49.019  6934  6934 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-09 14:24:49.019  6934  7408 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 14:24:49.020   316  1384 V AudioPolicyService: registerClient() client 0xb558a900, uid 1002
09-09 14:24:49.021   316  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 14:24:49.021   316  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:24:49.021   316  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:24:49.021  6934  6934 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 14:24:49.021   316   316 V AudioFlinger: registerClient() client 0xb101fb68, pid 6934
09-09 14:24:49.022   316  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:49.022   316  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:49.022  6934  6934 V ToneGenerator: Create Track: 0xb4928a80
09-09 14:24:49.022  6934  6934 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 14:24:49.022  6934  6934 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-09 14:24:49.022  6934  6952 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:49.022  6934  6952 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 14:24:49.022   316  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 14:24:49.022   316  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 14:24:49.022   316  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:24:49.022   316  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:24:49.023  1035  2009 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:49.023  1035  2009 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:49.023   316  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:49.023   316  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:49.023  1878  2528 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:49.023  1878  2528 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:49.023  6934  6952 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:49.023  1035  2030 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:49.023  1035  2030 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:49.023  6934  6952 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-09 14:24:49.023  1601  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:49.023  1601  1618 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:49.023  1601  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:49.023  1601  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:49.024  3435  3450 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:49.024  3435  3450 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:49.024  1878  2662 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:49.024  3435  3450 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:49.024  1878  2662 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:49.024  3435  3450 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:49.024   316  4033 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 14:24:49.024   316  4033 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 14:24:49.024   316  4033 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 14:24:49.024   31,6  4033 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:24:49.024   316  4033 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:24:49.025  6934  6934 V AudioSystem: getLatency() output 2, latency 50
09-09 14:24:49.025  6934  6934 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 14:24:49.025  6934  6934 V AudioTrack: createTrack_l() output 2 afLatency 50
09-09 14:24:49.025   316  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 14:24:49.025   316  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 14:24:49.025   316  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 14:24:49.025   316  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 14:24:49.025   316  1383 V AudioFlinger: createTrack() lSessionId: 22
09-09 14:24:49.027  6934  6934 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 14:24:49.027   316  1384 V AudioFlinger: acquiring 22 from 6934, for 6934
09-09 14:24:49.027   316  1384 V AudioFlinger:  added new entry for 22
09-09 14:24:49.029  6934  6934 V ToneGenerator: ToneGenerator INIT OK, time: 126461
09-09 14:24:49.029  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:49.030  6934  7430 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 14:24:49.030  6934  7430 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:24:49.031  6934  7408 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 14:24:49.031  6934  7430 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:24:49.031  6934  7430 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-09 14:24:49.032  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:49.033  6934  6934 D A2dpService: Received start request. Starting profile...
09-09 14:24:49.034  6934  6934 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 14:24:49.035  6934  6934 V Avrcp   : make
09-09 14:24:49.035  6934  7408 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:24:49.035  6934  6934 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 14:24:49.035  6934  6934 I bluedroid-qcom: get_profile_interface avrcp
09-09 14:24:49.035   316  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6934
09-09 14:24:49.036   316  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 14:24:49.036   316  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 14:24:49.036   316  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 14:24:49.036   316  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 14:24:49.036   316  1383 V voice   : voice_set_parameters: exit with code(0)
09-09 14:24:49.036   316  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 14:24:49.036   316  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 14:24:49.036   316  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 14:24:49.036   316  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 14:24:49.036   316  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 14:24:49.036   316  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 14:24:49.037  6934  7430 V ToneGenerator: ToneGenerator destructor
09-09 14:24:49.037  6934  7430 V ToneGenerator: stopTone
09-09 14:24:49.037  6934  7430 V ToneGenerator: Delete Track: 0xb4928a80
09-09 14:24:49.037  6934  7430 V AudioTrack: ~AudioTrack, releasing session id from 6934 on behalf of 6934
09-09 14:24:49.037   316  7449 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 14:24:49.037   316  7449 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-09 14:24:49.037   316  7449 V AudioFlinger: PlaybackThread::Track destructor
09-09 14:24:49.037   316  7449 V AudioFlinger: removeClient_l() pid 6934, calling pid 316
09-09 14:24:49.037   316   316 V AudioFlinger: releasing 22 from 6934 for 6934
09-09 14:24:49.037   316   316 V AudioFlinger:  decremented refcount to 0
09-09 14:24:49.037   316   316 V AudioFlinger: purging stale effects
09-09 14:24:49.037   316  1272 V AudioPolicyService: AudioCommandThread() waking up
09-09 14:24:49.037   316  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
09-09 14:24:49.037   316  1272 V AudioPolicyManager: releaseOutput() 2
09-09 14:24:49.037   316  1272 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 14:24:49.042  6934  7408 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:24:49.043  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:24:49.043  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:49.043  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:24:49.043  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 14:24:49.048  6934  6934 V AudioManager: registerRemoteController: size of Media player list: 0
09-09 14:24:49.050  6934  6934 E AudioManager: No RCC entry present to update
09-09 14:24:49.050  6934  6934 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 14:24:49.053  6934  6934 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-09 14:24:49.054  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 14:24:49.054  6934  6934 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-09 14:24:49.058  7009  7009 I AppUp4:CustModeStarterReceiver: onReceive
09-09 14:24:49.060  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 14:24:49.063  6934  7408 V LGMDMManager: Create singleton instance
09-09 14:24:49.067  6934  7408 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 14:24:49.067  7009  7009 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1badebca
09-09 14:24:49.067  7009  7009 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:24:49.067  7009  7009 D AppUp4:CustFacade: isPhone : true
09-09 14:24:49.113  7009  7009 D AppUp4:CustModeStarterReceiver: begin check event
,09-09 14:24:49.114  7009  7009 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 14:24:49.122  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:49.122  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:24:49.127  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:49.134  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:24:49.145  4351  7454 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:24:49.149  7036  7036 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 14:24:49.156  4351  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:49.156  4351  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:24:49.166  7036  7456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:24:49.172  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 14:24:49.172  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:49.172  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 14:24:49.173  1035  1947 V SIM_STK : Menu title from STK is T-Mobile
09-09 14:24:49.173  1035  1947 V SIM_STK : Menu title from STK is T-Mobile
09-09 14:24:49.175  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 14:24:49.175  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 14:24:49.189  6909  7459 W FormManager: Network not available. Please check & try again.
09-09 14:24:49.190  6909  7460 V FormManager: Network unavailable.
,09-09 14:24:49.191  7143  7143 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:49
09-09 14:24:49.192  6909  7460 V FormManager: Network unavailable.
09-09 14:24:49.193  7143  7143 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 14:24:49.193  7143  7143 D Weather.Utils: 2 : All the weather widget is gone.
09-09 14:24:49.193  7143  7143 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 14:24:49.193  7143  7143 D WeatherAncestor: connectivity changed - connection : true
09-09 14:24:49.193  7143  7143 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17dd5058
09-09 14:24:49.194  7143  7143 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:24:49.194  7143  7143 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:24:49.194  7143  7143 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 14:24:49.194  7143  7143 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:24:49.194  7143  7143 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:49
09-09 14:24:49.202  7431  7431 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-09 14:24:49.202  7431  7431 W LG Account v2.2: No ProfileInfo entries
09-09 14:24:49.202  7431  7431 I LG Account v2.2: isEnabled: false
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]Country: EU
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]Operator: OPEN
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]Ranking support: false
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]Comfort support: false
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]Accessory: true
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]Health device: true
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]Extra Pedometer: false
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]Blood glucose device: false
09-09 14:24:49.203  7431  7431 I Feature : [Lifetracker]Device Number: 3
09-09 14:24:49.217  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 14:24:49.218  6819  6819 D BluetoothPermissionRequest: onReceive
09-09 14:24:49.219  6396  6434 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 14:24:49.225  1035  1965 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-09 14:24:49.229  6819  6819 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:24:49.230  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-09 14:24:49.232  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 14:24:49.233  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 14:24:49.233  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,09-09 14:24:49.233  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 14:24:49.233  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:24:49.233  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 14:24:49.233  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 14:24:49.233  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 14:24:49.233  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:24:49.233  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 14:24:49.233  6934  6934 I BluetoothA2dpServiceJni: classInitNative
09-09 14:24:49.233  6934  6934 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:24:49.234  6934  6934 D A2dpStateMachine: make
09-09 14:24:49.235  6934  6934 I bluedroid-qcom: get_profile_interface a2dp
09-09 14:24:49.235  6934  7465 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 14:24:49.237  6934  6934 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:24:49.237  6934  6934 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 14:24:49.238  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:49.238  6934  6934 D HeadsetStateMachine: Proxy object connected
09-09 14:24:49.238  6934  7464 D A2dpStateMachine: Enter Disconnected: -2
09-09 14:24:49.238  6934  6934 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-09 14:24:49.238  6934  6934 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-09 14:24:49.240  6934  6934 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 14:24:49.241  6934  6934 D HidService: Received start request. Starting profile...
09-09 14:24:49.241  6934  6934 I bluedroid-qcom: get_profile_interface hidhost
09-09 14:24:49.241  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:49.241  6934  6934 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 14:24:49.242  2219  2219 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:24:49.243  6934  6934 D HealthService: Received start request. Starting profile...
09-09 14:24:49.244  6934  6934 I bluedroid-qcom: get_profile_interface health
09-09 14:24:49.245  6934  6934 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-09 14:24:49.245  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:49.247  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:49.248  6934  7430 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 14:24:49.248  6934  6934 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 14:24:49.248  6934  7430 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 14:24:49.249  6934  7430 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 14:24:49.250  6934  6934 D PanService: Received start request. Starting profile...
09-09 14:24:49.250  6934  6934 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 14:24:49.250  6934  6934 I bluedroid-qcom: get_profile_interface pan
09-09 14:24:49.253  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:24:49.253  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:49.253  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:24:49.253  7009  7009 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 14:24:49.255  7009  7009 I AppUp4:CustModeStarterReceiver: onReceive
09-09 14:24:49.257  6934  6934 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-09 14:24:49.257  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:49.258  6934  6934 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 14:24:49.260  7009  7009 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1badebca
,09-09 14:24:49.261  7009  7009 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:24:49.261  7009  7009 D AppUp4:CustFacade: isPhone : true
09-09 14:24:49.261  7009  7009 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:24:49.261  7009  7009 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 14:24:49.262  6934  6934 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:24:49.262  6934  6934 D BtGatt.GattService: Received start request. Starting profile...
09-09 14:24:49.262  6934  6934 D BtGatt.GattService: start()
09-09 14:24:49.262  6934  6934 I bluedroid-qcom: get_profile_interface gatt
09-09 14:24:49.263  6934  6934 D BtGatt.AdvertiseManager: advertise manager created
09-09 14:24:49.265  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:49.265  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 14:24:49.267  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:24:49.268  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:24:49.270  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:49.271  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:49.272  6934  6934 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-09 14:24:49.273  6934  6934 V BluetoothMapService: BluetoothMapBinder()
09-09 14:24:49.273  6934  6934 D BluetoothMapService: Received start request. Starting profile...
09-09 14:24:49.273  6934  6934 D BluetoothMapService: start()
09-09 14:24:49.274  4351  7472 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:24:49.277  7036  7036 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 14:24:49.277  6934  6934 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-09 14:24:49.278  6934  6934 D BluetoothMapEmailAppObserver: createReceiver()
09-09 14:24:49.280  4351  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:49.280  6934  6934 D BluetoothMapEmailAppObserver: initObservers()
09-09 14:24:49.280  4351  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:24:49.280  6934  6934 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-09 14:24:49.291  7036  7474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:24:49.294  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
,09-09 14:24:49.298  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:49.299  3435  3435 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-09 14:24:49.299  3435  3435 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:24:49.299  3435  3435 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 14:24:49.301  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:49.304  6909  7477 W FormManager: Network not available. Please check & try again.
09-09 14:24:49.305  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:49.306  6934  6934 V PanService: [BTUI] SIM Extra State :ABSENT
,09-09 14:24:49.309  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:49.311  7088  7088 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 14:24:49.311  7088  7088 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 14:24:49.312  6934  6934 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 14:24:49.312  6934  6934 V BluetoothMapService: Handler(): got msg=1
09-09 14:24:49.314  6934  7408 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 14:24:49.314  6934  7408 I bluedroid-qcom: enable
09-09 14:24:49.314  6934  7479 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 14:24:49.314  6934  7479 I bt-btu  : btu_task pending for preload complete event
09-09 14:24:49.314  6934  7408 I bt_hci_bdroid: init
09-09 14:24:49.316  6934  7408 I bt_vendor: bt-vendor : init
09-09 14:24:49.316  6934  7408 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 14:24:49.316  6934  7408 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 14:24:49.316  6934  7408 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 14:24:49.316  6934  7408 D bt_userial_mct: userial_init
09-09 14:24:49.317  6934  7408 D bt_hci_bdroid: set_power 1
09-09 14:24:49.317  6934  7408 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 14:24:49.317  6934  7408 I bt_vendor: Starting hciattach daemon
09-09 14:24:49.317  6934  7408 I bt_vendor: try to set true
09-09 14:24:49.318  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:49.312  7482  7482 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:49.312  7482  7482 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:24:49.322  6909  7478 V FormManager: Network unavailable.
09-09 14:24:49.324  6934  6934 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:24:49.324  6934  6934 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:24:49.324  6934  6934 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:24:49.324  6934  6934 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:49.324  6934  6934 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 14:24:49.325  6909  7478 V FormManager: Network unavailable.
09-09 14:24:49.329  7143  7143 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:49
09-09 14:24:49.331  7143  7143 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 14:24:49.331  7143  7143 D Weather.Utils: 2 : All the weather widget is gone.
09-09 14:24:49.332  7143  7143 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 14:24:49.332  7143  7143 D WeatherAncestor: connectivity changed - connection : true
09-09 14:24:49.332  7143  7143 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17dd5058
09-09 14:24:49.333  7143  7143 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:24:49.333  7143  7143 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:24:49.333  7143  7143 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 14:24:49.333  7143  7143 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:24:49.333  7143  7143 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:24:49
,09-09 14:24:49.344  7483  7483 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-09 14:24:49.406  7489  7489 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 14:24:49.421  7490  7490 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 14:24:49.461  7493  7493 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 14:24:49.472  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-09 14:24:49.484  7495  7495 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 14:24:49.496  7496  7496 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-09 14:24:49.519  7498  7498 I libmdmdetect: ESOC framework not supported
09-09 14:24:49.520  7498  7498 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-09 14:24:49.527  7498  7498 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-09 14:24:49.527  7498  7498 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-09 14:24:49.527  7498  7498 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-09 14:24:49.527  7498  7498 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-09 14:24:49.527  7498  7498 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-09 14:24:49.527  7498  7498 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 14:24:49.527  7498  7498 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-09 14:24:49.569  7498  7499 E QC-QMI  : qmi_client [7498] 14: failed to locate client data
,09-09 14:24:49.571   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-09 14:24:49.571   467   467 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-09 14:24:49.596  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 14:24:49.616  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 14:24:49.670  6934  7408 I bt_vendor: bluetooth satus is on
,09-09 14:24:49.670  6934  7408 D bt_hci_bdroid: preload
09-09 14:24:49.670  6934  7481 D bt_userial_mct: userial_open(port:0)
09-09 14:24:49.670  6934  7481 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-09 14:24:49.674  6934  7481 I bt_vendor: Done intiailizing UART
09-09 14:24:49.675  6934  7481 I bt_vendor: Done intiailizing UART
09-09 14:24:49.675  6934  7481 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 14:24:49.675  6934  7481 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 14:24:49.675  6934  7506 D bt_userial_mct: Entering userial_read_thread()
09-09 14:24:49.676  6934  7479 I bt-btu  : btu_task received preload complete event
09-09 14:24:49.676  6934  7479 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-09 14:24:49.676  6934  7479 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 14:24:49.678  6934  7479 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-09 14:24:49.685  6934  7479 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 14:24:49.685  6934  7479 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 14:24:49.685  6934  7479 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 14:24:49.685  6934  7479 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 14:24:49.685  6934  7479 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 14:24:49.685  6934  7479 I         : BTE_InitTraceLevels -- TRC_A2D
,09-09 14:24:49.685  6934  7479 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 14:24:49.686  6934  7479 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 14:24:49.686  6934  7479 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-09 14:24:49.686  6934  7479 I         : BTE_InitTraceLevels -- TRC_GAP
,09-09 14:24:49.686  6934  7479 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 14:24:49.686  6934  7479 I         : BTE_InitTraceLevels -- TRC_SDP
,09-09 14:24:49.686  6934  7479 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 14:24:49.686  6934  7479 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 14:24:49.686  6934  7479 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 14:24:49.686  6934  7479 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 14:24:49.791  6934  7479 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
09-09 14:24:49.791  6934  7479 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f4061 ,
09-09 14:24:49.791  6934  7479 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f4061 ,
,09-09 14:24:49.833  6934  7412 E bt-btif : Calling BTA_HhEnable
09-09 14:24:49.833  6934  7412 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-09 14:24:49.833  6934  7412 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-09 14:24:49.838  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 14:24:49.838  6934  7412 D BluetoothAdapterProperties: Name is: G3
09-09 14:24:49.840  6934  7412 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:24:49.840  6934  7412 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:24:49.840  6934  7412 D bt_hci_bdroid: postload
09-09 14:24:49.842  6934  7412 D bte_conf: Device ID record 1 : primary
09-09 14:24:49.842  6934  7412 D bte_conf:   vendorId            = 00c4
09-09 14:24:49.842  6934  7412 D bte_conf:   vendorIdSource      = 0001
09-09 14:24:49.842  6934  7412 D bte_conf:   product             = 13a1
09-09 14:24:49.842  6934  7412 D bte_conf:   version             = 1000
09-09 14:24:49.842  6934  7412 D bte_conf:   clientExecutableURL = 
09-09 14:24:49.842  6934  7412 D bte_conf:   serviceDescription  = 
09-09 14:24:49.842  6934  7412 D bte_conf:   documentationURL    = 
09-09 14:24:49.842  6934  7481 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:24:49.842  6934  7412 D bte_conf: bte_load_did_conf no section named DID2.
09-09 14:24:49.845  6934  7481 D bt_hci_bdroid: Used up Tx Cmd credits
,09-09 14:24:49.852  6934  7408 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 14:24:49.852  6934  7408 D BluetoothAdapterProperties: ScanMode =  20
09-09 14:24:49.852  6934  7408 D BluetoothAdapterProperties: State =  11
09-09 14:24:49.852  6934  7408 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 14:24:49.852  6934  7408 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 14:24:49.853  6934  7412 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 14:24:49.842  7514  7514 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:49.856  6934  7408 D BluetoothAdapterProperties: Setting state to 12
09-09 14:24:49.856  6934  7408 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 14:24:49.856  1035  1117 D BluetoothManagerService: Message: 60
09-09 14:24:49.856  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 14:24:49.857  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-09 14:24:49.857  6934  7506 E bt_mct  : hci lib postload completed
,09-09 14:24:49.852  7514  7514 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:49.866  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:49.871  6934  7408 I BluetoothAdapterState: Entering On State
,09-09 14:24:49.875  1878  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:24:49.887  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:49.887  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:49.887  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:49.887  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:49.887  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:49.887  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:49.887  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:49.887  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:24:49.893  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 14:24:49.895  6934  7412 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:24:49.895  6934  7412 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 14:24:49.899  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:24:49.909  6934  7408 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 14:24:49.909  6934  7408 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 14:24:49.910  6934  7408 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-09 14:24:49.910  6934  7408 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-09 14:24:49.917  1878  1878 D BluetoothHeadset: Proxy object connected
,09-09 14:24:49.922  6934  7408 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-09 14:24:49.931  6934  7479 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-09 14:24:49.931  6934  7479 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 14:24:49.931  6934  7479 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-09 14:24:49.933  6934  7479 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-09 14:24:49.933  6934  7479 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-09 14:24:49.933  6934  7479 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 14:24:49.933  6934  7412 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 14:24:49.939  6819  6931 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 14:24:49.941  1878  2662 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:24:49.942  6934  7479 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:24:49.942  6934  7479 W bt-smp  : Plain text(LSB ~ MSB) = 57 5f 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:24:49.942  6934  7479 W bt-smp  : Encrypted text(LSB ~ MSB) = 14 e7 84 14 0f 8b 28 ff 84 49 e5 89 df 36 ac 4f 
09-09 14:24:49.942  6934  7479 W bt-btm  : Stopping oneshot timer
09-09 14:24:49.945  1878  1878 D BluetoothHeadset: Proxy object connected
09-09 14:24:49.947  6819  6834 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 14:24:49.955  1878  2528 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:24:49.956  6819  6819 D BluetoothMap: Proxy object connected
,09-09 14:24:49.956  6819  6819 D MapProfile: Bluetooth service connected
09-09 14:24:49.956  6819  6819 D BluetoothMap: getConnectedDevices()
09-09 14:24:49.960  1878  1878 D BluetoothHeadset: Proxy object connected
09-09 14:24:49.960  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:24:49.961  1035  1035 D BluetoothHeadset: Proxy object connected
09-09 14:24:49.962  6934  7451 V BluetoothMapService: getConnectedDevices()
09-09 14:24:49.963  6819  6931 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:24:49.963  6819  6931 D BluetoothPan: onBluetoothStateChange call bindService
09-09 14:24:49.968  6819  6834 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 14:24:49.971  6934  7479 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-09 14:24:49.971  6934  7479 W bt-smp  : Plain text(LSB ~ MSB) = 19 02 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-09 14:24:49.971  6934  7479 W bt-smp  : Encrypted text(LSB ~ MSB) = 7b 9b 2c 17 42 df 63 fc 0b 4e 37 25 8b df 3d e0 
09-09 14:24:49.972  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 14:24:49.973  6934  7479 W bt-btm  : Stopping oneshot timer
09-09 14:24:49.973  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 14:24:49.973  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-09 14:24:49.974  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:24:49.975  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:24:49.978  1967  2259 D LGBluetoothAPIService: Message: 1
09-09 14:24:49.978  1967  2259 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-09 14:24:49.981  6588  6588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 14:24:49.983  6819  6819 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 14:24:49.985  1035  1035 D BluetoothA2dp: Proxy object connected
09-09 14:24:49.988  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:49.988  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:49.988  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:49.988  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:49.988  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:49.988  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:49.988  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:49.988  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:49.992  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:49.994  7534  7534 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-09 14:24:49.995  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:49.996  6934  6934 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:49.996  6934  6934 D BluetoothMapService: STATE_ON
,09-09 14:24:49.998  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,09-09 14:24:49.998  1967  2259 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-09 14:24:49.998  6934  7479 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:24:49.999  6934  7479 W bt-smp  : Plain text(LSB ~ MSB) = 48 ad 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:24:49.999  6934  7479 W bt-smp  : Encrypted text(LSB ~ MSB) = b3 35 25 39 0e 82 a7 a0 4d b2 68 35 a1 80 e7 5d 
09-09 14:24:49.999  6934  7479 W bt-btm  : Stopping oneshot timer
09-09 14:24:50.000  6819  6819 D PanProfile: Bluetooth service connected
09-09 14:24:50.000  1035  1117 D BluetoothManagerService: Message: 40
09-09 14:24:50.000  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 14:24:50.001  6934  6934 D LGBluetoothAPIServer: [BTUI] onCreate()
09-09 14:24:50.002  6934  6934 D LGBluetoothAPIServer: [BTUI] onBind()
09-09 14:24:50.003  6934  6934 V BluetoothMapService: Handler(): got msg=1
09-09 14:24:50.003  1967  1967 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 14:24:50.003  1967  2259 D LGBluetoothAPIService: Message: 100
09-09 14:24:50.003  1967  2259 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-09 14:24:50.003  6934  6934 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-09 14:24:50.005  6934  7537 D BluetoothMapMasInstance: MAS initSocket()
09-09 14:24:50.006  6934  7537 D BluetoothMapMasInstance:   masId = 00
09-09 14:24:50.006  6934  7537 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 14:24:50.006  6934  7537 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 14:24:50.006  6934  7537 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 14:24:50.006  6819  6819 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 14:24:50.008  1035  1965 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:50.010  6934  7537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:50.011  1035  1117 D BluetoothManagerService: Message: 30
09-09 14:24:50.011  6934  7479 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:24:50.011  6934  7479 W bt-smp  : Plain text(LSB ~ MSB) = db 3d 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:24:50.011  6934  7479 W bt-smp  : Encrypted text(LSB ~ MSB) = 25 4f 1f ef fe 2d 58 aa 24 da 40 e5 34 39 c5 60 
09-09 14:24:50.011  6934  7479 W bt-btm  : Stopping oneshot timer
,09-09 14:24:50.017  6819  6819 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 14:24:50.022  1035  1117 D BluetoothManagerService: Message: 30
09-09 14:24:50.022  6934  7537 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-09 14:24:50.023  6934  7537 V BluetoothMapMasInstance: Succeed to create listening socket 
,09-09 14:24:50.023  6934  7537 D BluetoothMapMasInstance: Accepting socket connection...
09-09 14:24:50.025  6934  7479 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:24:50.026  6934  7479 W bt-smp  : Plain text(LSB ~ MSB) = 5f 27 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:24:50.026  6934  7479 W bt-smp  : Encrypted text(LSB ~ MSB) = 96 d8 87 ab 27 11 2c 3d 2f ec 80 99 9f c7 16 c1 
09-09 14:24:50.026  6934  7479 W bt-btm  : Stopping oneshot timer
09-09 14:24:50.026  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:50.026  6934  6934 V BluetoothPbapService: Pbap Service onCreate
09-09 14:24:50.026  6934  6934 V BluetoothPbapService: Starting PBAP service
09-09 14:24:50.027  6934  7412 D BluetoothAdapterProperties: Scan Mode:21
09-09 14:24:50.027  6934  7412 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 14:24:50.028  6934  6934 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 14:24:50.028  6934  6934 V BluetoothPbapService: Pbap Service onBind
09-09 14:24:50.030  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:50.032  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:50.035  6934  6934 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:50.035  6934  6934 V BluetoothPbapService: state: 12
09-09 14:24:50.035  6934  6934 V BluetoothPbapService: Handler(): got msg=1
09-09 14:24:50.037  6934  6934 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 14:24:50.038  6934  7538 V BluetoothPbapService: Pbap Service initSocket
09-09 14:24:50.039  1035  1966 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:50.040  6934  7538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:50.040  6819  6819 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-09 14:24:50.044  6934  7538 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 14:24:50.044  6934  7538 V BluetoothPbapService: Succeed to create listening socket 
09-09 14:24:50.044  6934  7538 V BluetoothPbapService: Accepting socket connection...
09-09 14:24:50.046  6819  6819 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:24:50.050  6819  6819 D BluetoothInputDevice: Proxy object connected
09-09 14:24:50.050  6819  6819 D HidProfile: Bluetooth service connected
09-09 14:24:50.051  6934  6934 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:24:50.051  6934  6934 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:50.051  6934  6934 V BluetoothPbapReceiver: ***********state = 12
,09-09 14:24:50.053  6819  6819 D BluetoothA2dp: Proxy object connected
09-09 14:24:50.054  6819  6819 D A2dpProfile: Bluetooth service connected
09-09 14:24:50.055  2219  2219 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:24:50.055  2219  2219 D c       : Getting all permits...
09-09 14:24:50.055  2219  2219 D a       : Opening database...
09-09 14:24:50.055  6819  6819 D BluetoothHeadset: Proxy object connected
09-09 14:24:50.056  7165  7202 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-09 14:24:50.056  6819  6819 D HeadsetProfile: Bluetooth service connected
09-09 14:24:50.058  6819  6819 D BluetoothPbap: Proxy object connected
09-09 14:24:50.058  6819  6819 D PbapServerProfile: Bluetooth service connected
09-09 14:24:50.059  2219  2219 D a       : Opening database auth.proximity.permit_store...
09-09 14:24:50.060  2219  2219 D a       : Closing database...
09-09 14:24:50.068  6819  6819 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:24:50.074  6819  6819 D BluetoothPermissionRequest: onReceive
09-09 14:24:50.076  6819  6819 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 14:24:50.077  6819  6819 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:24:50.080  6934  6934 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-09 14:24:50.081  6934  6934 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-09 14:24:50.087  6934  6934 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-09 14:24:50.109  6934  6934 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 14:24:50.110  6934  6934 V BtOppService: onCreate
,09-09 14:24:50.115  6934  6934 V BluetoothOppNotification: send message
09-09 14:24:50.119  6934  6934 V BtOppService: Starting RfcommListener
09-09 14:24:50.126  6934  6934 D BluetoothOppPreference: Dumping Names:  
,09-09 14:24:50.126  6934  6934 D BluetoothOppPreference: {}
09-09 14:24:50.126  6934  6934 D BluetoothOppPreference: Dumping Channels:  
09-09 14:24:50.126  6934  6934 D BluetoothOppPreference: {}
09-09 14:24:50.127  6934  6934 V BtOppService: onStartCommand
09-09 14:24:50.132  6934  7548 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 14:24:50.132  6934  7545 V BtOppService: Deleted complete outbound shares, number =  0
09-09 14:24:50.134  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:50.135  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 14:24:50.135  6934  7545 V BtOppService: Deleted complete inbound failed shares, number = 0
09-09 14:24:50.137  6934  7545 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 14:24:50.137  6934  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 14:24:50.139  6934  6934 V BluetoothOppNotification: new notify threadi!
,09-09 14:24:50.141  6934  7545 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@302a2b3d on behalf of 
09-09 14:24:50.141  6934  6934 V BluetoothOppNotification: send delay message
09-09 14:24:50.143  6934  6934 V BtOppService: start RfcommListener
09-09 14:24:50.143  6934  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 14:24:50.145  6934  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@94f2f32 on behalf of 
09-09 14:24:50.148  6934  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9c48483 on behalf of 
09-09 14:24:50.149  6934  6934 V BtOppService: RfcommListener started
09-09 14:24:50.150  6934  6934 V BtOppService: ContentObserver received notification
09-09 14:24:50.150  6934  6934 V BtOppService: ContentObserver received notification
09-09 14:24:50.150  6934  7549 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-09 14:24:50.153  6934  7548 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 14:24:50.155  6934  7550 V BtOppRfcommListener: Starting RFCOMM listener....
,09-09 14:24:50.156  1035  2076 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:50.156  6934  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 14:24:50.157  6934  7550 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:50.158  6934  7550 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-09 14:24:50.158  6934  7550 V BtOppRfcommListener: Started RFCOMM listener....
09-09 14:24:50.158  6934  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 14:24:50.159  6934  7550 I BtOppRfcommListener: Accept thread started.
09-09 14:24:50.159  6934  7550 V BtOppRfcommListener: Accepting connection...
09-09 14:24:50.160  6934  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@95e8600 on behalf of 
09-09 14:24:50.161  6934  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e133e39 on behalf of 
09-09 14:24:50.162  6934  7549 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 14:24:50.164  6934  7549 V BluetoothOppNotification: outbound notification was removed.
,09-09 14:24:50.164  6934  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 14:24:50.164  6934  7548 V BluetoothOppNotification: update too frequent, put in queue
09-09 14:24:50.167  6934  7548 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-09 14:24:50.167  6934  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@143d0c7e on behalf of 
09-09 14:24:50.168  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:50.168  6934  6934 V BluetoothFtpService: Ftp Service onCreate
09-09 14:24:50.168  6934  6934 I BluetoothFtpService: Ftp Service onCreate
09-09 14:24:50.168  6934  7549 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 14:24:50.168  6934  6934 V BluetoothFtpService: Ftp Service onStartCommand
09-09 14:24:50.169  6934  6934 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:50.169  6934  6934 V BluetoothFtpService: Starting Listening on sockets
09-09 14:24:50.169  6934  6934 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:24:50.169  6934  6934 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:24:50.169  6934  6934 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:24:50.169  6934  6934 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:50.169  6934  6934 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 14:24:50.169  6934  6934 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 14:24:50.170  6934  7549 V BluetoothOppNotification: inbound notification was removed.
09-09 14:24:50.170  6934  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 14:24:50.172  6934  6934 V BluetoothFtpService: Handler(): got msg=1
09-09 14:24:50.172  6934  6934 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-09 14:24:50.172  6934  6934 V BluetoothFtpService: Ftp Service initSocket
,09-09 14:24:50.175  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:50.176  6934  6934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:24:50.179  6934  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e26022c on behalf of 
,09-09 14:24:50.181  6934  6934 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
,09-09 14:24:50.181  6934  6934 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-09 14:24:50.183  6934  7551 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-09 14:24:50.197  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:50.197  6934  6934 V BluetoothSapService: Sap Service onCreate
09-09 14:24:50.200  6934  6934 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:50.200  6934  6934 V BluetoothSapService: state: 12
09-09 14:24:50.200  6934  6934 V BluetoothSapService: Starting SAP server process
,09-09 14:24:50.192  7552  7552 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:24:50.203  6934  6934 V BluetoothSapService: SAP Service startRfcommListenerThread
09-09 14:24:50.192  7552  7552 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:24:50.205  6934  7553 V BluetoothSapService: Sap Service initRfcommSocket
09-09 14:24:50.205  1035  1965 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:50.206  6934  7553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:50.207  6934  7553 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-09 14:24:50.207  6934  7553 V BluetoothSapService: Succeed to create listening socket 
09-09 14:24:50.207  6934  7553 V BluetoothSapService: Accepting socket connection...
09-09 14:24:50.218  7552  7552 V BT_SAP  : Event pipe created
09-09 14:24:50.218  7552  7552 V BT_SAP  : create_server_socket qcom.sap.server
09-09 14:24:50.219  7552  7552 V BT_SAP  : created socket fd 6
,09-09 14:24:50.796  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:24:50.796  1035  1537 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:24:50.827  1035  1538 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-09 14:24:50.833  1035  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-09 14:24:51.076  1035  2075 I ActivityManager: Killing 7335:com.lge.bnr/1000 (adj 15): empty #17
,09-09 14:24:51.111  1035  1965 W libprocessgroup: failed to open /acct/uid_1000/pid_7335/cgroup.procs: No such file or directory
,09-09 14:24:51.143  6934  6934 V BluetoothOppNotification: new notify threadi!
,09-09 14:24:51.144  6934  6934 V BluetoothOppNotification: send delay message
,09-09 14:24:51.164  1035  1947 I ActivityManager: Killing 6839:com.lge.sync/1000 (adj 15): empty #17
,09-09 14:24:51.174  6934  7563 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-09 14:24:51.187  1035  1543 D WifiService: Client connection lost with reason: 4
,09-09 14:24:51.192  6934  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7071518 on behalf of 
09-09 14:24:51.192  6934  7563 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 14:24:51.194  6934  7563 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 14:24:51.195  6934  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f017b71 on behalf of 
09-09 14:24:51.195  6934  7563 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 14:24:51.197  6934  7563 V BluetoothOppNotification: outbound notification was removed.
09-09 14:24:51.197  6934  7563 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 14:24:51.198  6934  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a42d56 on behalf of 
09-09 14:24:51.200  6934  7563 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-09 14:24:51.204  6934  7563 V BluetoothOppNotification: inbound notification was removed.
,09-09 14:24:51.204  6934  7563 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-09 14:24:51.206  6934  7563 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f3bb1d7 on behalf of 
,09-09 14:24:51.209  1035  1731 W libprocessgroup: failed to open /acct/uid_1000/pid_6839/cgroup.procs: No such file or directory
,09-09 14:24:51.793  1035  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:24:51.793  1035  2009 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@409f229 mBinding = false
,09-09 14:24:51.834  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:24:51.834  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:24:51.835  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-09 14:24:51.838  1035  1117 D BluetoothManagerService: Message: 2
,09-09 14:24:51.839  1035  1117 D BluetoothManagerService: Sending off request.
09-09 14:24:51.840  6934  6952 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-09 14:24:51.841  6934  7408 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,09-09 14:24:51.841  6934  7408 D BluetoothAdapterProperties: Setting state to 13
09-09 14:24:51.841  6934  7408 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 14:24:51.842  6934  7408 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 14:24:51.842  6934  7408 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 14:24:51.844  6934  7412 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:24:51.846  6934  7408 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 14:24:51.847  6934  7537 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 14:24:51.847  6934  7537 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:51.847  6934  7537 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 14:24:51.847  6934  7537 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 14:24:51.847  6934  7537 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 14:24:51.847  6934  7537 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 14:24:51.847  6934  7537 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 14:24:51.847  6934  7537 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,09-09 14:24:51.853  6934  7538 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:51.854  6934  7550 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:51.855  6934  7551 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:51.855  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 14:24:51.855  6934  7479 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-09 14:24:51.857  6934  7408 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:24:51.860  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 14:24:51.861  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 14:24:51.861  6934  7479 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 14:24:51.865  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:51.865  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:51.865  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:51.865  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:51.865  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:51.865  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:51.865  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:51.865  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:51.865  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:24:51.875  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:51.875  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:51.880  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:51.880  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:51.880  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:51.880  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:51.880  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:51.880  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:24:51.880  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:51.880  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:51.880  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:24:51.884  6588  6588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:24:51.884  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:51.886  1035  1117 D BluetoothManagerService: Message: 60
09-09 14:24:51.886  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 14:24:51.886  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-09 14:24:51.888  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:51.890  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-09 14:24:51.899  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:51.901  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:51.901  6934  6934 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:51.902  6934  6934 D BluetoothMapService: STATE_TURNING_OFF
09-09 14:24:51.902  6934  6934 V BluetoothMapService: Handler(): got msg=4
09-09 14:24:51.902  6934  6934 D BluetoothMapService: MAP Service closeService in
09-09 14:24:51.902  6934  6934 D BluetoothMapMasInstance: MAP Service shutdown
09-09 14:24:51.902  6934  6934 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:24:51.902  6934  6934 V BluetoothMapService: MAP Service closeService out
09-09 14:24:51.903  6934  6934 V BtOppService: Receiver DISABLED_ACTION 
09-09 14:24:51.903  6934  6934 I BtOppRfcommListener: stopping Accept Thread
09-09 14:24:51.903  6934  6934 V BtOppRfcommListener: close mBtServerSocket
09-09 14:24:51.904  6934  7550 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 14:24:51.907  6934  6934 V BtOppRfcommListener: waiting for thread to terminate
09-09 14:24:51.907  6934  6934 V BtOppRfcommListener: done waiting for thread to terminate
09-09 14:24:51.914  6819  6819 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-09 14:24:51.919  6934  7553 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:24:51.923  6819  6819 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:24:51.926  6934  6934 V BtOppService: onDestroy
09-09 14:24:51.928  6934  6934 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-09 14:24:51.933  6934  6934 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:24:51.933  6934  6934 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:51.933  6934  6934 V BluetoothPbapReceiver: ***********state = 13
09-09 14:24:51.936  6934  6934 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 14:24:51.937  6934  6934 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:51.937  6934  6934 V BluetoothPbapService: state: 13
09-09 14:24:51.937  6934  6934 V BluetoothPbapService: Pbap Service closeService in
09-09 14:24:51.941  2219  2219 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:51.944  6934  6934 V BluetoothPbapService: successfully stopped pbap service
09-09 14:24:51.944  6934  6934 V BluetoothPbapService: Pbap Service closeService out
,09-09 14:24:51.947  6934  6934 V BluetoothPbapService: Pbap Service onDestroy
09-09 14:24:51.947  6934  6934 V BluetoothPbapService: Pbap Service closeService in
,09-09 14:24:51.947  6934  6934 V BluetoothPbapService: Pbap Service closeService out
09-09 14:24:51.947  6934  6934 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 14:24:51.967  6819  6819 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:24:51.970  6819  6819 D BluetoothPbap: Proxy object disconnected
09-09 14:24:51.970  6819  6819 D PbapServerProfile: Bluetooth service disconnected
09-09 14:24:51.978  6819  6819 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 14:24:51.985  6819  6819 D BluetoothPermissionRequest: onReceive
09-09 14:24:51.985  6819  6819 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 14:24:51.990  6819  6819 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:24:51.994  6934  6934 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-09 14:24:51.994  6934  6934 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-09 14:24:51.994  6934  6934 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-09 14:24:51.999  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:51.999  6934  6934 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 14:24:52.000  6934  6934 V BluetoothFtpService: Ftp Service onStartCommand
09-09 14:24:52.000  6934  6934 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:52.001  6934  6934 V BluetoothFtpService: Ftp Service closeService
09-09 14:24:52.001  6934  6934 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 14:24:52.002  6934  6934 V BluetoothFtpService: successfully stopped ftp service
09-09 14:24:52.002  6934  6934 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:24:52.002  6934  6934 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:24:52.002  6934  6934 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:24:52.002  6934  6934 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:52.003  6934  6934 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-09 14:24:52.003  6934  6934 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 14:24:52.004  6934  6934 V BluetoothFtpService: Ftp Service onDestroy
09-09 14:24:52.004  6934  6934 V BluetoothFtpService: Ftp Service closeService
09-09 14:24:52.007  6934  6934 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:24:52.007  6934  6934 V BluetoothSapService: state: 13
,09-09 14:24:52.007  6934  6934 V BluetoothSapService: Stopping SAP server process
,09-09 14:24:52.009  6934  6934 V BluetoothSapService: Sap Service closeSapService in
,09-09 14:24:52.009  6934  6934 V BluetoothSapService: Close listen Socket : 
,09-09 14:24:52.009  6934  6934 V BluetoothSapService: Close rfcomm Socket : 
,09-09 14:24:52.009  6934  6934 V BluetoothSapService: Close sapd  Socket : 
,09-09 14:24:52.012  6934  6934 V BluetoothSapService: Sap Service closeSapService out,
,09-09 14:24:52.012  6934  6934 V BluetoothSapService: Sap Service onDestroy
09-09 14:24:52.012  6934  6934 V BluetoothSapService: Sap Service closeSapService in
09-09 14:24:52.012  6934  6934 V BluetoothSapService: Close listen Socket : 
09-09 14:24:52.012  6934  6934 V BluetoothSapService: Close rfcomm Socket : 
,09-09 14:24:52.012  6934  6934 V BluetoothSapService: Close sapd  Socket : 
09-09 14:24:52.013  6934  6934 V BluetoothSapService: Sap Service closeSapService out
09-09 14:24:52.763  6934  7412 D bt_hci_bdroid: cleanup
,09-09 14:24:52.781  6934  7481 I bt_lpm  : LPM is already off!!!
09-09 14:24:52.782  6934  7506 I bt_userial_mct: exiting userial_read_thread
09-09 14:24:52.782  6934  7506 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 14:24:52.782  6934  7479 W bt-btif : ag scb idx 1 not allocated
09-09 14:24:52.782  6934  7479 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:24:52.783  6934  7479 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:24:52.783  6934  7479 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 14:24:52.784  6934  7412 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 14:24:52.784  6934  7481 I bt_vendor: hw_epilog_process
09-09 14:24:52.784  6934  7412 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 14:24:52.784  6934  7412 D bt_userial_mct: userial_close
09-09 14:24:52.784  6934  7412 E bt_userial_mct: pthread_join() FAILED result:3
09-09 14:24:52.784  6934  7412 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 14:24:52.789  6934  7412 D bt_hci_bdroid: set_power 0
09-09 14:24:52.789  6934  7412 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 14:24:52.789  6934  7412 I bt_vendor: bluetooth satus is on
09-09 14:24:52.789  6934  7412 I bt_vendor: bt-vendor : resetting BT status
09-09 14:24:52.789  6934  7412 I bt_vendor: Starting hciattach daemon
09-09 14:24:52.789  6934  7412 I bt_vendor: try to set false
09-09 14:24:52.790  6934  7412 I bt_vendor: Starting hciattach daemon
09-09 14:24:52.790  6934  7412 I bt_vendor: try to set false
,09-09 14:24:52.795  6934  7412 I bt_vendor: cleanup
09-09 14:24:52.798  6934  7479 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 14:24:52.798  6934  7412 I GKI_LINUX: GKI_exit_task 0 done
09-09 14:24:52.798  6934  7412 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 14:24:52.800  6934  7408 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 14:24:52.803  6934  6934 D HeadsetService: Received stop request...Stopping profile...
,09-09 14:24:52.807  6934  6934 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 14:24:52.807  6934  6934 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:24:52.807  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:52.807  6934  7430 D HeadsetStateMachine: Exit Disconnected: -1
09-09 14:24:52.810  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:52.810  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 14:24:52.817  6934  6934 D A2dpService: Received stop request...Stopping profile...
,09-09 14:24:52.819  6934  7464 D A2dpStateMachine: Exit Disconnected: -1
09-09 14:24:52.820  1878  1878 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:52.821  1878  1878 D BluetoothHeadset: Proxy object disconnected
09-09 14:24:52.823  6934  7408 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 14:24:52.823  6934  6934 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-09 14:24:52.825  6934  6934 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 14:24:52.825  6934  6934 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:24:52.825  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:52.826  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-09 14:24:52.826  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 14:24:52.829  6934  6934 D HeadsetStateMachine: Unbinding service...
,09-09 14:24:52.833  6934  6934 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:24:52.833  6934  6934 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:24:52.833  6934  6934 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:24:52.833  6934  6934 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:24:52.833  6934  6934 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 14:24:52.833  6934  6934 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:24:52.833  6934  6934 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 14:24:52.835  6934  6934 D HidService: Received stop request...Stopping profile...
09-09 14:24:52.835  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:52.837  6934  6934 D HealthService: Received stop request...Stopping profile...
09-09 14:24:52.837  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:52.839  6934  6934 D PanService: Received stop request...Stopping profile...
09-09 14:24:52.840  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:52.841  6934  6934 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 14:24:52.844  6934  6934 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 14:24:52.844  6934  6934 D BtGatt.GattService: stop()
09-09 14:24:52.844  6934  6934 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 14:24:52.845  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:52.847  6934  6934 D BluetoothMapService: Received stop request...Stopping profile...
09-09 14:24:52.847  6934  6934 D BluetoothMapService: stop()
09-09 14:24:52.848  6934  6934 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 14:24:52.848  6934  6934 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 14:24:52.849  6934  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17dd5058
09-09 14:24:52.850  6934  6934 I BluetoothA2dpServiceJni: cleanupNative
09-09 14:24:52.850  6934  7465 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 14:24:52.851  6934  6934 I GKI_LINUX: GKI_exit_task 2 done
09-09 14:24:52.851  6934  6934 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 14:24:52.851  6934  6934 V BluetoothMapService: Handler(): got msg=4
09-09 14:24:52.851  6934  6934 D BluetoothMapService: MAP Service closeService in
09-09 14:24:52.851  6934  6934 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:24:52.851  6934  6934 V BluetoothMapService: MAP Service closeService out
09-09 14:24:52.852  6934  7408 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 14:24:52.852  6934  7408 D BluetoothAdapterProperties: Setting state to 10
09-09 14:24:52.852  6934  7408 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-09 14:24:52.856  1035  1117 D BluetoothManagerService: Message: 60
09-09 14:24:52.856  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 14:24:52.856  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-09 14:24:52.857  6934  7408 I BluetoothAdapterState: Entering OffState
09-09 14:24:52.858  1878  1893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:52.859  6819  6834 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:52.861  6934  6934 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 14:24:52.861  6934  6934 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 14:24:52.863  6819  6834 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 14:24:52.864  1878  2528 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 14:24:52.867  6819  6834 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:24:52.867  6934  6934 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 14:24:52.868  6934  6934 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:24:52.868  6934  6934 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:24:52.869  6934  6934 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 14:24:52.869  6934  6934 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 14:24:52.872  6934  6934 D BluetoothMapService: cleanup()
09-09 14:24:52.872  6934  6934 D BluetoothMapService: MAP Service closeService in
09-09 14:24:52.872  6934  6934 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:24:52.872  6934  6934 V BluetoothMapService: MAP Service closeService out
09-09 14:24:52.873  1878  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:52.874  6819  6834 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:24:52.874  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:24:52.874  6819  6834 D BluetoothPan: onBluetoothStateChange on: false
09-09 14:24:52.875  6819  6834 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:24:52.875  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 14:24:52.878  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 14:24:52.879  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-09 14:24:52.881  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 14:24:52.881  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 14:24:52.881  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@409f229 mBinding = false
09-09 14:24:52.882  1035  1117 D BluetoothManagerService: Sending unbind request.
09-09 14:24:52.887  6934  7412 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 14:24:52.889  6934  6934 I GKI_LINUX: GKI_exit_task 1 done
09-09 14:24:52.889  6934  6934 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 14:24:52.889  6934  6934 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 14:24:52.890  6934  6934 I art     : --- WEIRD: removing null entry 248
09-09 14:24:52.890  6934  6934 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-09 14:24:52.890  6934  6934 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 14:24:52.891  6934  6934 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-09 14:24:52.892  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-09 14:24:52.894  6934  6934 I art     : System.exit called, status: 0
09-09 14:24:52.894  6934  6934 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 14:24:52.916   316  7449 V AudioFlinger: 6934 died, releasing its sessions
09-09 14:24:52.916   316  7449 V AudioFlinger:  pid 1878 @ 0
09-09 14:24:52.916   316  7449 V AudioFlinger:  pid 3435 @ 1
09-09 14:24:52.916   316  7449 V AudioFlinger:  pid 3435 @ 2
,09-09 14:24:52.924  1967  1967 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,09-09 14:24:52.925  1967  2259 D LGBluetoothAPIService: Message: 101
09-09 14:24:52.925  1967  2259 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-09 14:24:52.926  1967  2259 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-09 14:24:52.926  1967  2259 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-09 14:24:52.927  6819  6819 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-09 14:24:53.059  1035  1984 I ActivityManager: Process com.android.bluetooth (pid 6934) has died
09-09 14:24:53.059  1035  1984 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-09 14:24:53.060  1035  1984 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-09 14:24:53.072  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:53.074  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:24:53.076  1967  2259 D LGBluetoothAPIService: Message: 2
,09-09 14:24:53.076  1967  2259 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-09 14:24:53.082  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:53.083  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:53.083  6819  6819 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 14:24:53.083  6819  6819 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-09 14:24:53.086  6819  6819 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:24:53.092  1601  1601 D BluetoothAdapter: 7800429: getState() :  mService = null. Returning STATE_OFF
09-09 14:24:53.092  1601  1601 D BluetoothAdapter: 7800429: getState() :  mService = null. Returning STATE_OFF
,09-09 14:24:53.134  1035  2009 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7610 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-09 14:24:53.136  6819  6819 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:24:53.335  1035  1965 I art     : Explicit concurrent mark sweep GC freed 77404(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.393ms total 156.595ms
,09-09 14:24:53.359  7610  7610 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-09 14:24:53.361  7610  7610 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:24:53.362  7610  7610 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-09 14:24:53.363  7610  7610 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 14:24:53.385  7610  7610 D BluetoothAdapterApp: Loading JNI Library
,09-09 14:24:53.414  7610  7610 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1c4d9940 Instance Count = 1
,09-09 14:24:53.418  7610  7610 D BluetoothAdapterApp: onCreate
,09-09 14:24:53.437  7610  7610 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-09 14:24:53.437  7610  7610 D ProfileConfigQcom: Adding HeadsetService
09-09 14:24:53.437  7610  7610 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-09 14:24:53.437  7610  7610 D ProfileConfigQcom: Adding A2dpService
09-09 14:24:53.437  7610  7610 D ProfileConfigQcom: [BTUI] HidService is supported
,09-09 14:24:53.437  7610  7610 D ProfileConfigQcom: Adding HidService
,09-09 14:24:53.438  7610  7610 D ProfileConfigQcom: [BTUI] HealthService is supported
09-09 14:24:53.438  7610  7610 D ProfileConfigQcom: Adding HealthService
09-09 14:24:53.438  7610  7610 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 14:24:53.439  7610  7610 D ProfileConfigQcom: [BTUI] PanService is supported
09-09 14:24:53.439  7610  7610 D ProfileConfigQcom: Adding PanService
09-09 14:24:53.439  7610  7610 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 14:24:53.439  7610  7610 D ProfileConfigQcom: Adding GattService
09-09 14:24:53.440  7610  7610 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-09 14:24:53.440  7610  7610 D ProfileConfigQcom: Adding BluetoothMapService
09-09 14:24:53.440  7610  7610 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-09 14:24:53.441  7610  7610 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:24:53.442  7610  7610 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:53.442  7610  7610 V BluetoothPbapReceiver: ***********state = 10
09-09 14:24:53.443  7610  7610 V LGMDMManagerInternal: Create singleton instance
09-09 14:24:53.506  2219  2219 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:53.516  6819  6819 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 14:24:53.522  7610  7610 D LGBluetoothAPIServer: [BTUI] onCreate()
09-09 14:24:53.522  7610  7610 D LGBluetoothAPIServer: [BTUI] onBind()
,09-09 14:24:53.527  1967  1967 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 14:24:53.527  1967  2259 D LGBluetoothAPIService: Message: 100
09-09 14:24:53.527  1967  2259 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,09-09 14:24:53.531  6819  6819 D BluetoothPermissionRequest: onReceive
09-09 14:24:53.533  6819  6819 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 14:24:53.533  6819  6819 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 14:24:53.537  6819  6819 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 14:24:53.545  7610  7610 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-09 14:24:53.549  7610  7610 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:24:53.551  7610  7610 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-09 14:24:53.552  7610  7610 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-09 14:24:53.552  7610  7610 V BluetoothSapReceiver: SapReceiver onReceive 
,09-09 14:24:53.553  7610  7610 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:24:53.553  7610  7610 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-09 14:24:53.558  6885  6885 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings,
09-09 14:24:54.901  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop,
,09-09 14:24:54.901  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:24:55.038  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-09 14:24:55.043  1035  1461 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 14:24:55.071  2089  2089 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 14:24:55.145  1035  1035 D administrator: Handling package changes for user 0
,09-09 14:24:55.170  1035  1098 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7639 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 14:24:55.185  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 14:24:55.187  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-09 14:24:55.207  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-09 14:24:55.255  7639  7639 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 14:24:55.292  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-09 14:24:55.292  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 14:24:55.345  7639  7639 D LgDataFeature: LgDataFeature() Constructor: none,
09-09 14:24:55.345  7639  7639 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:24:55.356  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 14:24:55.361  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-09 14:24:55.370  2089  2089 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 14:24:55.371  2465  2465 V GmsNetworkLocationProvi: DISABLE
09-09 14:24:55.403  1035  1097 D LocationProviderProxy: applying state to connected service
09-09 14:24:55.404  2465  2465 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-09 14:24:55.470  7639  7683 I Babel   : MmsConfig: mnc/mcc: 0/0
09-09 14:24:55.470  7639  7683 I Babel   : MmsConfig.loadMmsSettings
09-09 14:24:55.481  7639  7683 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-09 14:24:55.481  7639  7683 I Babel   : MmsConfig.loadFromDatabase
,09-09 14:24:55.497  7639  7683 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-09 14:24:55.497  7639  7683 I Babel   : MmsConfig.loadFromResources
09-09 14:24:55.499  7639  7683 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 14:24:55.500  7639  7683 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-09 14:24:55.517  7639  7639 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:24:55.548  1839  7686 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-09 14:24:55.549  1839  7686 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-09 14:24:55.557  7009  7009 I AppUp4:CustModeStarterReceiver: onReceive
09-09 14:24:55.558  7639  7682 W AudioCapabilities: Unsupported mime audio/evrc
09-09 14:24:55.563  7639  7682 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 14:24:55.564  7009  7009 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1badebca
09-09 14:24:55.564  7009  7009 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:24:55.564  7009  7009 D AppUp4:CustFacade: isPhone : true
09-09 14:24:55.565  7009  7009 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:24:55.565  7009  7009 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-09 14:24:55.568  7639  7682 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 14:24:55.570  1839  4765 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-09 14:24:55.581  7639  7682 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-09 14:24:55.582  7639  7682 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 14:24:55.582  7639  7682 W AudioCapabilities: Unsupported mime audio/evrc
09-09 14:24:55.589  7639  7682 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-09 14:24:55.591  7639  7682 W VideoCapabilities: Unsupported mime video/divx
09-09 14:24:55.592  7639  7682 W VideoCapabilities: Unsupported mime video/divx311
,09-09 14:24:55.593  7639  7682 W VideoCapabilities: Unsupported mime video/divx4
09-09 14:24:55.597  7639  7682 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-09 14:24:55.608  7639  7682 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 14:24:55.611  1035  2076 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7689 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-09 14:24:55.615  7639  7682 W AudioCapabilities: Unsupported mime audio/eac3
09-09 14:24:55.615  1035  2076 I ActivityManager: Killing 6713:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-09 14:24:55.619  7639  7682 W AudioCapabilities: Unsupported mime audio/ac3
09-09 14:24:55.623  7639  7682 W AudioCapabilities: Unsupported mime audio/g726
09-09 14:24:55.623  7639  7682 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 14:24:55.626  7639  7682 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 14:24:55.627  7639  7682 W AudioCapabilities: Unsupported mime audio/adpcm
,09-09 14:24:55.628  7639  7682 W VideoCapabilities: Unsupported mime video/theora
09-09 14:24:55.629  7639  7682 W VideoCapabilities: Unsupported mime video/mjpg
09-09 14:24:55.690  6867  6867 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-09 14:24:55.691  6867  6867 W System.err: android.os.DeadObjectException
09-09 14:24:55.691  6867  6867 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 14:24:55.691  6867  6867 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 14:24:55.692  6867  6867 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 14:24:55.692  6867  6867 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-09 14:24:55.692  6867  6867 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 14:24:55.692  6867  6867 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 14:24:55.692  6867  6867 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:24:55.692  6867  6867 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:24:55.692  6867  6867 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:24:55.692  6867  6867 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:24:55.692  6867  6867 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:55.693  6867  6867 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:24:55.693  6867  6867 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:24:55.693  6867  6867 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:24:55.693  6867  6867 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 14:24:55.694  1035  2030 W libprocessgroup: failed to open /acct/uid_1000/pid_6713/cgroup.procs: No such file or directory
09-09 14:24:55.694  6867  6867 W System.err: android.os.DeadObjectException
09-09 14:24:55.694  1035  2030 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-09 14:24:55.694  6867  6867 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 14:24:55.694  6867  6867 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 14:24:55.695  6867  6867 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 14:24:55.695  6867  6867 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-09 14:24:55.695  6867  6867 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 14:24:55.695  6867  6867 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 14:24:55.695  6867  6867 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:24:55.695  6867  6867 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:24:55.695  6867  6867 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:24:55.695  6867  6867 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:24:55.695  6867  6867 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:55.695  6867  6867 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:24:55.696  6867  6867 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:24:55.696  6867  6867 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:24:55.696  6867  6867 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 14:,24:55.697  6867  6867 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-09 14:24:55.699  6867  6867 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-09 14:24:55.699  6867  6867 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 14:24:55.731  7689  7689 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:24:55.731  7689  7689 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:24:55.732  7689  7689 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 14:24:55.733  7689  7689 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 14:24:55.733  7689  7689 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-09 14:24:55.771  1035  1965 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7706 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 14:24:55.772  6867  6867 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 14:24:55.831  7706  7706 D UEI.SmartControl: Quickset Services start...
09-09 14:24:55.833  7706  7706 I UEI.SmartControl: Manufacture = LGE
09-09 14:24:55.833  7706  7706 D UEI.SmartControl: Id = LGNevo
09-09 14:24:55.834  7689  7689 I SystemConfig: BUILD Country: EU
09-09 14:24:55.834  7689  7689 I SystemConfig: BUILD Operator: OPEN
,09-09 14:24:55.837  7706  7706 D UEI.SmartControl: File observer start...
09-09 14:24:55.837  7706  7706 E UEI.SmartControl: IR Port is disabled: false
09-09 14:24:55.838  7706  7706 D UEI.SmartControl: Starting file observer...
09-09 14:24:55.838  7706  7706 D UEI.SmartControl: Extracting JNI libs...
09-09 14:24:55.838  7706  7706 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 14:24:55.877  1035  1705 I ActivityManager: Killing 6867:com.lge.qremote/u0a112 (adj 15): empty #17
,09-09 14:24:55.920  7706  7706 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-09 14:24:55.921  7706  7706 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 14:24:55.921  7706  7706 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-09 14:24:55.956  7706  7706 I UEI.SmartControl: --- Selecting new region: 6
,09-09 14:24:55.958  7706  7706 I UEI.SmartControl: Model = LG-D855
09-09 14:24:55.960  7706  7706 D UEI.SmartControl: QS Service created
09-09 14:24:55.983  1035  1984 W libprocessgroup: failed to open /acct/uid_10112/pid_6867/cgroup.procs: No such file or directory
,09-09 14:24:55.999  7689  7726 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-09 14:24:55.999  7689  7726 I SystemConfig: existFile = false
09-09 14:24:55.999  7689  7726 I SystemConfig: canReadFile = false
09-09 14:24:55.999  7689  7726 I SystemConfig: systemFeature RCS result false
09-09 14:24:55.999  7689  7726 D SystemConfig: refreshRcsSupport() :false
,09-09 14:24:56.024  7706  7706 I UEI.SmartControl: Service initServices...
,09-09 14:24:56.029  7706  7706 D UEI.SmartControl: QS start get config
09-09 14:24:56.050  1035  2113 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7728 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-09 14:24:56.081  7706  7706 D UEI.SmartControl: Loading JNI Libs...
,09-09 14:24:56.115  7728  7728 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
09-09 14:24:56.115  7728  7728 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 14:24:56.116  7728  7728 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 14:24:56.116  7728  7728 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 14:24:56.223  7728  7728 I AppConfig: Total System Memory = 2995761152
,09-09 14:24:56.235  7728  7728 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-09 14:24:56.325  1035  1705 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7754 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 14:24:56.326  1035  1705 I ActivityManager: Killing 7036:com.lge.email/u0a23 (adj 15): empty #17
,09-09 14:24:56.401  7706  7706 I UEI.SmartControl: Supports setup maps: true
,09-09 14:24:56.404  7706  7706 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 14:24:56.404  7706  7706 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 14:24:56.404  7706  7706 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 14:24:56.405  7706  7706 I UEI.SmartControl: ### init IR Blaster...
09-09 14:24:56.409  7706  7706 D serial_port: Configuring serial port
09-09 14:24:56.410  1035  1947 W libprocessgroup: failed to open /acct/uid_10023/pid_7036/cgroup.procs: No such file or directory
,09-09 14:24:56.424  7706  7706 E UEI.SmartControl: UEIBLaster setting for 616
09-09 14:24:56.424  7706  7706 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 14:24:56.426  7706  7706 I UEI.SmartControl: configuring settings for MAXQ616
09-09 14:24:56.426  7706  7706 I UEI.SmartControl: Get version...
,09-09 14:24:56.444  7706  7773 D UEI.SmartControl: serial port data available: 21
,09-09 14:24:56.473  7706  7706 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-09 14:24:56.473  7706  7706 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 14:24:56.474  7706  7706 I UEI.SmartControl: QS saving settings...
09-09 14:24:56.475  7706  7706 D UEI.SmartControl: IR Blaster version: 25672567
09-09 14:24:56.491  7706  7773 D UEI.SmartControl: serial port data available: 4
,09-09 14:24:56.523  7706  7779 I UEI.SmartControl: Device manager: loading config....
,09-09 14:24:56.528  7706  7779 D UEI.SmartControl: ----------- loading internal config...
09-09 14:24:56.530  7706  7706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 14:24:56.541  7706  7706 E UEI.SmartControl: Services init done
09-09 14:24:56.541  7706  7706 D UEI.SmartControl: QS Service init finished
09-09 14:24:56.542  7706  7706 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 14:24:56.543  7706  7706 D UEI.SmartControl: QS Service version code: 201091
,09-09 14:24:56.545  7706  7706 D UEI.SmartControl: Service requested: Control
09-09 14:24:56.549  7706  7779 E UEI.SmartControl: Loading SETTINGS...
09-09 14:24:56.551  7706  7706 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 14:24:56.552  7706  7706 D UEI.SmartControl: Service.onUnbind: IControl
09-09 14:24:56.553  7706  7706 D UEI.SmartControl: Service.onDestroy
09-09 14:24:56.553  7706  7706 D UEI.SmartControl: Lock is in USE false
09-09 14:24:56.553  7706  7706 D UEI.SmartControl: unbind internal service
09-09 14:24:56.554  7706  7706 D serial_port: close(fd = 25)
09-09 14:24:56.556  7706  7777 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 14:24:56.556  7706  7777 D UEI.SmartControl: -----service ready thread exits
09-09 14:24:56.561  7706  7706 I UEI.SmartControl: Serial port is closed.
09-09 14:24:56.562  7706  7706 I UEI.SmartControl: Serial port is closed.
09-09 14:24:56.562  7706  7706 D UEI.SmartControl: Blaster closed
09-09 14:24:56.563  7706  7706 D UEI.SmartControl: Shut down QS...
09-09 14:24:56.563  7706  7706 D UEI.SmartControl: Stopping QS lib
09-09 14:24:56.563  7706  7706 D UEI.SmartControl: QS lib stop result = true
09-09 14:24:56.563  7706  7706 D UEI.SmartControl: Stopped QS lib
09-09 14:24:56.564  7706  7706 D UEI.SmartControl: Stopped file observer...
09-09 14:24:56.564  7706  7706 D UEI.SmartControl: QS shutdown complete
09-09 14:24:56.565  7706  7706 D UEI.SmartControl: QS Service created
,09-09 14:24:56.572  7706  7779 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 14:24:56.583  7706  7706 I UEI.SmartControl: Service initServices...
,09-09 14:24:56.583  7706  7706 D UEI.SmartControl: QS start get config
09-09 14:24:56.635  7754  7754 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-09 14:24:56.731  7754  7754 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:56.731  7754  7754 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:24:56.775  7754  7754 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-09 14:24:56.793  7754  7754 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 14:24:56.794  7754  7754 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 14:24:56.808  7754  7754 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-09 14:24:56.808  7754  7754 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-09 14:24:56.824  1035  1731 I ActivityManager: Killing 6909:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-09 14:24:56.878  7706  7706 I UEI.SmartControl: Supports setup maps: true
,09-09 14:24:56.884  7706  7706 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 14:24:56.884  7706  7706 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 14:24:56.884  7706  7706 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 14:24:56.884  7706  7706 I UEI.SmartControl: ### init IR Blaster...
09-09 14:24:56.889  7706  7706 D serial_port: Configuring serial port
09-09 14:24:56.889  7706  7706 E UEI.SmartControl: UEIBLaster setting for 616
09-09 14:24:56.889  7706  7706 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 14:24:56.889  7706  7706 I UEI.SmartControl: configuring settings for MAXQ616
09-09 14:24:56.889  7706  7706 I UEI.SmartControl: Get version...
09-09 14:24:56.894  1035  2009 W libprocessgroup: failed to open /acct/uid_10026/pid_6909/cgroup.procs: No such file or directory
,09-09 14:24:56.905  3484  3500 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-09 14:24:56.908  3484  3500 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2e3e13ce on behalf of 7754
,09-09 14:24:56.908  7706  7800 D UEI.SmartControl: serial port data available: 21
09-09 14:24:56.914  4632  7801 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-09 14:24:56.936  7706  7706 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 14:24:56.936  7706  7706 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 14:24:56.936  7706  7706 I UEI.SmartControl: QS saving settings...
09-09 14:24:56.938  7706  7706 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 14:24:56.952  7706  7800 D UEI.SmartControl: serial port data available: 4
,09-09 14:24:56.973  1035  2030 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7803 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-09 14:24:56.980  7706  7813 I UEI.SmartControl: Device manager: loading config....
09-09 14:24:56.980  7706  7813 D UEI.SmartControl: ----------- loading internal config...
09-09 14:24:56.989  7706  7706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-09 14:24:56.993  7706  7706 E UEI.SmartControl: Services init done
09-09 14:24:56.993  7706  7706 D UEI.SmartControl: QS Service init finished
09-09 14:24:56.995  7706  7706 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 14:24:56.995  7706  7706 D UEI.SmartControl: QS Service version code: 201091
09-09 14:24:56.995  7706  7706 D UEI.SmartControl: Service requested: Control
09-09 14:24:56.999  7754  7754 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-09 14:24:57.003  7706  7813 E UEI.SmartControl: Loading SETTINGS...
,09-09 14:24:57.006  7706  7706 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 14:24:57.013  7706  7706 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@7a6fa96 that was originally bound here
09-09 14:24:57.013  7706  7706 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@7a6fa96 that was originally bound here
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:24:57.013  7706  7706 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:24:57.014  7706  7813 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 14:24:57.014  7706  7706 D UEI.SmartControl: Internal service binding...
09-09 14:24:57.022  7754  7754 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-09 14:24:57.025  1035  1965 I ActivityManager: Killing 6396:com.wsandroid.suite.lge/1000 (adj 15): empty #17
09-09 14:24:57.034  7706  7812 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-09 14:24:57.034  7706  7812 D UEI.SmartControl: -----service ready thread exits
,09-09 14:24:57.063  1035  1575 W libprocessgroup: failed to open /acct/uid_1000/pid_6396/cgroup.procs: No such file or directory
,09-09 14:24:57.107  7803  7803 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-09 14:24:57.132  7803  7803 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-09 14:24:57.132  7803  7803 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-09 14:24:57.132  7803  7803 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-09 14:24:57.132  7803  7803 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-09 14:24:57.132  7803  7803 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-09 14:24:57.132  7803  7803 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-09 14:24:57.160  1035  1705 I ActivityManager: Killing 7088:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-09 14:24:57.199  1035  1984 W libprocessgroup: failed to open /acct/uid_10046/pid_7088/cgroup.procs: No such file or directory
,09-09 14:24:57.325  1035  1575 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:24:57.349  4632  7801 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 434 ms] updated apps [took 434 ms] 
,09-09 14:24:57.553  7706  7783 D UEI.SmartControl: Internal timer expired: 2
,09-09 14:24:57.925  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:24:57.925  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@201481cc added. We now have 6 listener(s)
,09-09 14:24:57.926  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:24:57.960  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:24:57.960  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@180f9c15 added. We now have 7 listener(s)
09-09 14:24:57.960  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:24:57.965  6588  6680 I System.out: IsBluetoothEnabled
09-09 14:24:57.966  1035  1705 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:57.966  1035  1705 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-09 14:24:57.967  1035  1117 D BluetoothManagerService: Message: 2
09-09 14:24:57.979  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:57.982  1035  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:57.982  1035  1947 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-09 14:24:58.002  1035  1117 D BluetoothManagerService: Message: 1
09-09 14:24:58.002  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-09 14:24:58.007  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:24:58.007  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:24:58.007  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-09 14:24:58.037  1035  1117 D BluetoothManagerService: Message: 20
09-09 14:24:58.037  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4cd68e1:true
,09-09 14:24:58.041  7610  7610 D BluetoothAdapterState: make
09-09 14:24:58.046  7610  7610 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 14:24:58.046  7610  7610 I bluedroid-qcom: init
09-09 14:24:58.047  7610  7839 I BluetoothAdapterState: Entering OffState
09-09 14:24:58.047  7610  7610 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 14:24:58.047  7610  7610 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 14:24:58.047  7610  7610 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 14:24:58.048  7610  7610 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 14:24:58.048  7610  7610 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 14:24:58.049  7610  7610 I bluedroid-qcom: get_profile_interface socket
09-09 14:24:58.049  7610  7610 I bluedroid-qcom: get_profile_interface map_client
,09-09 14:24:58.053  7610  7843 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 14:24:58.042  7842  7842 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:58.042  7842  7842 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:58.065  7842  7842 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-09 14:24:58.065  7842  7842 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-09 14:24:58.065  7842  7842 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-09 14:24:58.069  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-09 14:24:58.069  1035  1117 D BluetoothManagerService: Message: 40
09-09 14:24:58.069  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 14:24:58.070  7610  7627 I bluedroid-qcom: config_hci_snoop_log
09-09 14:24:58.071  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 14:24:58.071  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-09 14:24:58.075  7610  7843 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 14:24:58.076  7842  7842 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 14:24:58.078  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 14:24:58.078  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,09-09 14:24:58.082  7610  7843 D BluetoothAdapterProperties: Name is: G3
09-09 14:24:58.092  7610  7839 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-09 14:24:58.093  7610  7839 D BluetoothAdapterProperties: Setting state to 11
09-09 14:24:58.093  7610  7839 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 14:24:58.094  1035  1117 D BluetoothManagerService: Message: 60
09-09 14:24:58.094  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-09 14:24:58.094  7842  7842 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-09 14:24:58.094  7842  7842 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-09 14:24:58.094  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-09 14:24:58.095  7610  7839 I LGBluetoothServiceJni: classInitNative: succeeds
09-09 14:24:58.099  7610  7839 D BluetoothBondStateMachine: make
09-09 14:24:58.104  7610  7839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
,09-09 14:24:58.104  7610  7859 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 14:24:58.104  7610  7839 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 14:24:58.105  7610  7839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:58.105  7610  7839 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-09 14:24:58.106  7610  7839 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 14:24:58.110  7610  7839 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:24:58.118  7610  7610 D HeadsetService: Received start request. Starting profile...
,09-09 14:24:58.119  7610  7610 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:24:58.119  7610  7610 D LGBluetoothHfpAdapter: Version 1.6
09-09 14:24:58.124  7610  7610 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 14:24:58.125  7610  7610 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:24:58.125  7610  7610 D HeadsetStateMachine: make
09-09 14:24:58.128  7610  7839 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:24:58.134  7610  7839 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:24:58.134  1035  1098 W ProcessCpuTracker: Skipping unknown process pid 7842
09-09 14:24:58.139  7610  7839 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 14:24:58.145  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:58.145  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:24:58.150  7610  7839 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:24:58.150  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:58.151  6819  6819 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 14:24:58.160  7610  7839 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 14:24:58.166  7610  7610 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:24:58.166  7610  7610 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 14:24:58.171  7610  7610 D HeadsetStateMachine: max_hf_connections = 1
09-09 14:24:58.172  7610  7610 I bluedroid-qcom: get_profile_interface handsfree
,09-09 14:24:58.172  7610  7839 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:24:58.175  7610  7610 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-09 14:24:58.175   316   316 V AudioPolicyService: registerClient() client 0xb1021b60, uid 1002
09-09 14:24:58.175   316  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 14:24:58.175   316  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:24:58.175   316  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:24:58.176  7610  7610 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,09-09 14:24:58.176   316  7449 V AudioFlinger: registerClient() client 0xb5581628, pid 7610
09-09 14:24:58.177   316  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:58.177   316  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:58.177  7610  7610 V ToneGenerator: Create Track: 0xb4928a80
09-09 14:24:58.177  7610  7610 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 14:24:58.177  7610  7610 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-09 14:24:58.177  1035  1966 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:58.177  1035  1966 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:58.177   316  4033 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 14:24:58.177   316  4033 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 14:24:58.177   316  4033 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:24:58.177   316  4033 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:24:58.177  7610  7610 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 14:24:58.178   316  7449 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 14:24:58.178  1878  1893 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:58.178  1878  1893 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:58.178   316  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:58.178   316  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:58.178  1035  1966 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:58.178  1035  1966 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:58.178  1601  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:58.178  1601  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:58.178  3435  3450 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:58.178  3435  3450 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:24:58.179  7610  7863 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:24:58.179  7610  7863 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 14:24:58.179  7610  7863 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:58.179  7610  7863 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-09 14:24:58.179  1601  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:58.179  1601  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:58.179  1878  2662 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:58.179  1878  2662 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:58.179  3435  3450 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:24:58.179  3435  3450 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:24:58.179   316  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 14:24:58.179   316  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 14:24:58.179   316  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:24:58.179   316  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:24:58.179  7610  7610 V AudioSystem: getLatency() output 2, latency 50
09-09 14:24:58.179  7610  7610 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 14:24:58.179  7610  7610 V AudioTrack: createTrack_l() output 2 afLatency 50
09-0,9 14:24:58.180   316  4033 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 14:24:58.180   316  4033 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 14:24:58.180   316  4033 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 14:24:58.180   316  4033 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 14:24:58.180   316  4033 V AudioFlinger: createTrack() lSessionId: 23
09-09 14:24:58.181  7610  7610 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 14:24:58.181   316  4033 V AudioFlinger: acquiring 23 from 7610, for 7610
09-09 14:24:58.181   316  4033 V AudioFlinger:  added new entry for 23
09-09 14:24:58.181  7610  7610 V ToneGenerator: ToneGenerator INIT OK, time: 135613
09-09 14:24:58.181  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:58.182  7610  7861 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 14:24:58.182  7610  7861 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:24:58.182  7610  7861 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:24:58.182  7610  7861 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-09 14:24:58.182   316  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7610
09-09 14:24:58.183  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:58.183   316  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 14:24:58.183   316  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 14:24:58.183   316  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 14:24:58.183   316  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 14:24:58.183   316  1383 V voice   : voice_set_parameters: exit with code(0)
09-09 14:24:58.183   316  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 14:24:58.183   316  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 14:24:58.183   316  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 14:24:58.183   316  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 14:24:58.183   316  1383 V audio_hw_primary: adev_set_parameters: exit with code(0),
09-09 14:24:58.183   316  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 14:24:58.184  7610  7861 V ToneGenerator: ToneGenerator destructor
09-09 14:24:58.184  7610  7861 V ToneGenerator: stopTone
09-09 14:24:58.184  7610  7861 V ToneGenerator: Delete Track: 0xb4928a80
09-09 14:24:58.184  7610  7861 V AudioTrack: ~AudioTrack, releasing session id from 7610 on behalf of 7610
,09-09 14:24:58.184   316   316 V AudioFlinger: releasing 23 from 7610 for 7610
09-09 14:24:58.184   316  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 14:24:58.184   316   316 V AudioFlinger:  decremented refcount to 0
09-09 14:24:58.184   316   316 V AudioFlinger: purging stale effects
09-09 14:24:58.184   316  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-09 14:24:58.184   316  1272 V AudioPolicyService: AudioCommandThread() waking up
,09-09 14:24:58.185   316  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
09-09 14:24:58.185   316  1272 V AudioPolicyManager: releaseOutput() 2
09-09 14:24:58.185   316  1272 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 14:24:58.185   316  1384 V AudioFlinger: PlaybackThread::Track destructor
09-09 14:24:58.186   316  1384 V AudioFlinger: removeClient_l() pid 7610, calling pid 316
09-09 14:24:58.186  7610  7610 D A2dpService: Received start request. Starting profile...
,09-09 14:24:58.186  7610  7610 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 14:24:58.187  7610  7610 V Avrcp   : make
09-09 14:24:58.188  7610  7610 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 14:24:58.188  7610  7610 I bluedroid-qcom: get_profile_interface avrcp
09-09 14:24:58.188  1035  2030 W Process : Unable to open /proc/7864/status
09-09 14:24:58.204  7610  7610 V AudioManager: registerRemoteController: size of Media player list: 0
,09-09 14:24:58.205  7610  7610 E AudioManager: No RCC entry present to update
09-09 14:24:58.205  7610  7610 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 14:24:58.209  7610  7839 V LGMDMManager: Create singleton instance
09-09 14:24:58.209  7610  7610 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-09 14:24:58.210  7610  7839 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 14:24:58.211  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 14:24:58.211  7610  7610 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-09 14:24:58.214  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 14:24:58.322  1035  2076 V SIM_STK : Menu title from STK is T-Mobile
09-09 14:24:58.322  1035  2076 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:24:58.445  1035  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-09 14:24:58.454  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 14:24:58.459  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-09 14:24:58.460  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 14:24:58.461  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 14:24:58.461  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 14:24:58.461  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:24:58.461  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 14:24:58.462  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 14:24:58.464  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 14:24:58.464  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:24:58.464  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 14:24:58.465  7610  7610 I BluetoothA2dpServiceJni: classInitNative
,09-09 14:24:58.466  7610  7610 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:24:58.466  7610  7610 D A2dpStateMachine: make
09-09 14:24:58.467  7610  7610 I bluedroid-qcom: get_profile_interface a2dp
09-09 14:24:58.468  7610  7871 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 14:24:58.470  7610  7610 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,09-09 14:24:58.470  7610  7610 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 14:24:58.471  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:58.472  7610  7610 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 14:24:58.472  7610  7870 D A2dpStateMachine: Enter Disconnected: -2
09-09 14:24:58.474  7610  7610 D HidService: Received start request. Starting profile...
09-09 14:24:58.474  7610  7610 I bluedroid-qcom: get_profile_interface hidhost
09-09 14:24:58.474  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:58.474  7610  7610 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 14:24:58.476  7610  7610 D HealthService: Received start request. Starting profile...
,09-09 14:24:58.481  7610  7610 I bluedroid-qcom: get_profile_interface health
,09-09 14:24:58.481  7610  7610 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,09-09 14:24:58.481  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
,09-09 14:24:58.483  7610  7610 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 14:24:58.487  7610  7610 D PanService: Received start request. Starting profile...
,09-09 14:24:58.487  7610  7610 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 14:24:58.487  7610  7610 I bluedroid-qcom: get_profile_interface pan,
09-09 14:24:58.503  7610  7610 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,09-09 14:24:58.503  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
,09-09 14:24:58.504  7610  7610 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-09 14:24:58.504  7610  7610 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED,
,09-09 14:24:58.504  7610  7610 V BluetoothPbapReceiver: ***********state = 11
,09-09 14:24:58.508  7610  7610 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 14:24:58.512  2219  2219 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:24:58.516  7610  7610 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:24:58.517  7610  7610 D BtGatt.GattService: Received start request. Starting profile...
09-09 14:24:58.517  7610  7610 D BtGatt.GattService: start()
09-09 14:24:58.517  7610  7610 I bluedroid-qcom: get_profile_interface gatt
09-09 14:24:58.518  7610  7610 D BtGatt.AdvertiseManager: advertise manager created
,09-09 14:24:58.526  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:58.526  7610  7610 D HeadsetStateMachine: Proxy object connected
09-09 14:24:58.527  7610  7610 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-09 14:24:58.527  7610  7610 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-09 14:24:58.531  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
,09-09 14:24:58.531  7610  7610 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-09 14:24:58.533  7610  7610 V BluetoothMapService: BluetoothMapBinder()
09-09 14:24:58.534  7610  7610 D BluetoothMapService: Received start request. Starting profile...
09-09 14:24:58.534  7610  7610 D BluetoothMapService: start()
09-09 14:24:58.538  6819  6819 D BluetoothPermissionRequest: onReceive
09-09 14:24:58.538  7610  7610 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-09 14:24:58.538  7610  7610 D BluetoothMapEmailAppObserver: createReceiver()
09-09 14:24:58.540  7610  7610 D BluetoothMapEmailAppObserver: initObservers()
09-09 14:24:58.540  7610  7610 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-09 14:24:58.544  6819  6819 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 14:24:58.552  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:58.556  7610  7610 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:58.556  7610  7861 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 14:24:58.557  7610  7861 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 14:24:58.557  7610  7861 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-09 14:24:58.560  7610  7610 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:58.563  7610  7610 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:58.566  7610  7610 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:58.569  7610  7610 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:24:58.569  7610  7610 V PanService: [BTUI] SIM Extra State :ABSENT
,09-09 14:24:58.573  7610  7610 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 14:24:58.574  7610  7610 V BluetoothMapService: Handler(): got msg=1
09-09 14:24:58.575  7610  7839 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 14:24:58.575  7610  7839 I bluedroid-qcom: enable
09-09 14:24:58.575  7610  7839 I bt_hci_bdroid: init
09-09 14:24:58.576  7610  7839 I bt_vendor: bt-vendor : init
09-09 14:24:58.576  7610  7839 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 14:24:58.577  7610  7839 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 14:24:58.577  7610  7839 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 14:24:58.577  7610  7839 D bt_userial_mct: userial_init
09-09 14:24:58.579  7610  7839 D bt_hci_bdroid: set_power 1
09-09 14:24:58.579  7610  7839 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 14:24:58.579  7610  7839 I bt_vendor: Starting hciattach daemon
09-09 14:24:58.579  7610  7839 I bt_vendor: try to set true
09-09 14:24:58.572  7885  7885 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:24:58.572  7885  7885 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:58.586  7610  7610 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:58.577  7610  7882 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 14:24:58.587  7610  7882 I bt-btu  : btu_task pending for preload complete event
09-09 14:24:58.590  7610  7610 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:24:58.590  7610  7610 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:24:58.590  7610  7610 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:24:58.590  7610  7610 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:58.591  7610  7610 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 14:24:58.605  7886  7886 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-09 14:24:58.732  7901  7901 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 14:24:58.753  7903  7903 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 14:24:58.784  7906  7906 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 14:24:58.814  7907  7907 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-09 14:24:58.844  7908  7908 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 14:24:58.861  7909  7909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-09 14:24:58.891  7915  7915 I libmdmdetect: ESOC framework not supported
,09-09 14:24:58.894  7915  7915 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-09 14:24:58.906  7915  7915 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-09 14:24:58.906  7915  7915 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-09 14:24:58.906  7915  7915 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,09-09 14:24:58.906  7915  7915 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-09 14:24:58.907  7915  7915 D bthci_qcomm_common: [BTUI]     LE: Class 2
,09-09 14:24:58.907  7915  7915 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 14:24:58.907  7915  7915 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-09 14:24:58.957  7915  7916 E QC-QMI  : qmi_client [7915] 15: failed to locate client data
09-09 14:24:58.958   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-09 14:24:58.958   467   467 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-09 14:24:58.998  7920  7920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 14:24:59.013  7924  7924 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 14:24:59.032  7610  7839 I bt_vendor: bluetooth satus is on
09-09 14:24:59.032  7610  7839 D bt_hci_bdroid: preload
,09-09 14:24:59.034  7610  7884 D bt_userial_mct: userial_open(port:0)
09-09 14:24:59.034  7610  7884 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-09 14:24:59.038  7610  7884 I bt_vendor: Done intiailizing UART
09-09 14:24:59.039  7610  7884 I bt_vendor: Done intiailizing UART
09-09 14:24:59.039  7610  7884 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 14:24:59.039  7610  7884 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 14:24:59.039  7610  7882 I bt-btu  : btu_task received preload complete event
09-09 14:24:59.040  7610  7882 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-09 14:24:59.040  7610  7882 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 14:24:59.042  7610  7882 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-09 14:24:59.044  7610  7926 D bt_userial_mct: Entering userial_read_thread()
,09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_GAP
,09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 14:24:59.049  7610  7882 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 14:24:59.109  7610  7882 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-09 14:24:59.109  7610  7882 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f4061 
09-09 14:24:59.109  7610  7882 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f4061 
,09-09 14:24:59.136  7610  7843 E bt-btif : Calling BTA_HhEnable
09-09 14:24:59.136  7610  7843 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-09 14:24:59.136  7610  7843 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-09 14:24:59.141  7610  7882 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-09 14:24:59.141  7610  7882 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 14:24:59.141  7610  7882 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,09-09 14:24:59.142  7610  7882 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,09-09 14:24:59.142  7610  7882 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-09 14:24:59.144  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 14:24:59.145  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 14:24:59.145  7610  7843 D BluetoothAdapterProperties: Name is: G3
09-09 14:24:59.148  7610  7843 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:24:59.148  7610  7843 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:24:59.148  7610  7843 D bt_hci_bdroid: postload
09-09 14:24:59.149  7610  7884 D bt_hci_bdroid: Used up Tx Cmd credits
,09-09 14:24:59.155  7610  7884 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:24:59.157  7610  7882 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 14:24:59.159  7610  7884 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:24:59.160  7610  7843 D bte_conf: Device ID record 1 : primary
09-09 14:24:59.160  7610  7843 D bte_conf:   vendorId            = 00c4
09-09 14:24:59.160  7610  7843 D bte_conf:   vendorIdSource      = 0001
09-09 14:24:59.160  7610  7843 D bte_conf:   product             = 13a1
09-09 14:24:59.160  7610  7843 D bte_conf:   version             = 1000
09-09 14:24:59.160  7610  7843 D bte_conf:   clientExecutableURL = 
09-09 14:24:59.160  7610  7843 D bte_conf:   serviceDescription  = 
09-09 14:24:59.160  7610  7843 D bte_conf:   documentationURL    = 
09-09 14:24:59.160  7610  7843 D bte_conf: bte_load_did_conf no section named DID2.
09-09 14:24:59.163  7610  7839 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 14:24:59.164  7610  7839 D BluetoothAdapterProperties: ScanMode =  20
09-09 14:24:59.164  7610  7839 D BluetoothAdapterProperties: State =  11
09-09 14:24:59.164  7610  7839 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 14:24:59.164  7610  7839 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 14:24:59.164  7610  7839 D BluetoothAdapterProperties: Setting state to 12
09-09 14:24:59.164  7610  7839 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 14:24:59.165  7610  7843 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 14:24:59.165  7610  7843 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 14:24:59.172  7928  7928 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:59.172  7928  7928 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:24:59.189  1035  1117 D BluetoothManagerService: Message: 60
09-09 14:24:59.189  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 14:24:59.189  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-09 14:24:59.190  7610  7882 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:24:59.190  7610  7882 W bt-smp  : Plain text(LSB ~ MSB) = c8 00 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:24:59.190  7610  7882 W bt-smp  : Encrypted text(LSB ~ MSB) = f0 a1 06 79 d6 40 ea 47 02 78 87 26 f1 b8 00 a7 
09-09 14:24:59.190  7610  7884 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:24:59.190  7610  7882 W bt-btm  : Stopping oneshot timer
09-09 14:24:59.193  7610  7926 E bt_mct  : hci lib postload completed
,09-09 14:24:59.204  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:24:59.204  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:24:59.204  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:24:59.204  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:24:59.204  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:24:59.204  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:24:59.204  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:24:59.204  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:24:59.209  7610  7839 I BluetoothAdapterState: Entering On State
,09-09 14:24:59.211  1878  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:24:59.219  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:24:59.228  7610  7882 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:24:59.228  7610  7882 W bt-smp  : Plain text(LSB ~ MSB) = eb ad 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:24:59.228  7610  7882 W bt-smp  : Encrypted text(LSB ~ MSB) = 08 ee 73 49 3d 87 44 12 9e 8d 27 96 dd 51 ec a4 
,09-09 14:24:59.230  7610  7882 W bt-btm  : Stopping oneshot timer
09-09 14:24:59.233  7610  7839 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 14:24:59.234  7610  7839 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 14:24:59.234  7610  7839 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-09 14:24:59.237  7610  7839 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-09 14:24:59.248  1878  1878 D BluetoothHeadset: Proxy object connected
,09-09 14:24:59.251  6819  6834 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:24:59.267  7610  7839 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-09 14:24:59.269  7610  7882 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:24:59.269  7610  7882 W bt-smp  : Plain text(LSB ~ MSB) = 0c 58 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:24:59.269  7610  7882 W bt-smp  : Encrypted text(LSB ~ MSB) = 9e 74 f3 2b ea 84 f3 0e 2c 4d 0a ab a8 39 72 95 
09-09 14:24:59.269  7610  7882 W bt-btm  : Stopping oneshot timer
09-09 14:24:59.270  6819  6931 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 14:24:59.283  1878  2662 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:24:59.294  1878  1878 D BluetoothHeadset: Proxy object connected
,09-09 14:24:59.296  7610  7882 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:24:59.296  7610  7882 W bt-smp  : Plain text(LSB ~ MSB) = d6 36 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:24:59.297  7610  7882 W bt-smp  : Encrypted text(LSB ~ MSB) = 4e 32 e6 bc c5 af a4 b2 df 93 15 f5 42 8d f1 41 
09-09 14:24:59.297  7610  7882 W bt-btm  : Stopping oneshot timer
,09-09 14:24:59.303  6819  6835 D BluetoothMap: onBluetoothStateChange: up=true
09-09 14:24:59.307  6819  6819 D BluetoothHeadset: Proxy object connected
09-09 14:24:59.307  6819  6819 D HeadsetProfile: Bluetooth service connected
09-09 14:24:59.311  1878  1893 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:24:59.319  7933  7933 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-09 14:24:59.319  1878  1878 D BluetoothHeadset: Proxy object connected
09-09 14:24:59.320  6819  6931 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 14:24:59.320  6819  6819 D BluetoothMap: Proxy object connected
09-09 14:24:59.320  6819  6819 D MapProfile: Bluetooth service connected
09-09 14:24:59.320  6819  6819 D BluetoothMap: getConnectedDevices()
,09-09 14:24:59.321  7610  7863 V BluetoothMapService: getConnectedDevices()
09-09 14:24:59.322  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:24:59.323  1035  1035 D BluetoothHeadset: Proxy object connected
09-09 14:24:59.325  7610  7882 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-09 14:24:59.325  7610  7882 W bt-smp  : Plain text(LSB ~ MSB) = cd 69 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:24:59.325  7610  7882 W bt-smp  : Encrypted text(LSB ~ MSB) = 46 22 44 a0 26 01 9f b0 b8 79 ad 0c 6d a7 9d 9f 
09-09 14:24:59.325  7610  7882 W bt-btm  : Stopping oneshot timer
09-09 14:24:59.325  6819  6834 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:24:59.325  6819  6834 D BluetoothPan: onBluetoothStateChange call bindService
09-09 14:24:59.325  6819  6819 D BluetoothA2dp: Proxy object connected
09-09 14:24:59.325  6819  6819 D A2dpProfile: Bluetooth service connected
,09-09 14:24:59.330  6819  6819 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 14:24:59.330  6819  6819 D PanProfile: Bluetooth service connected
09-09 14:24:59.330  6819  6835 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 14:24:59.333  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 14:24:59.333  6819  6819 D BluetoothInputDevice: Proxy object connected
09-09 14:24:59.333  6819  6819 D HidProfile: Bluetooth service connected
09-09 14:24:59.334  1035  1035 D BluetoothA2dp: Proxy object connected
09-09 14:24:59.335  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 14:24:59.335  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-09 14:24:59.338  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:59.338  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,09-09 14:24:59.338  1035  1117 D BluetoothManagerService: Message: 40
09-09 14:24:59.338  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 14:24:59.339  1967  2259 D LGBluetoothAPIService: Message: 1
09-09 14:24:59.339  1967  2259 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-09 14:24:59.339  1967  2259 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-09 14:24:59.339  1967  2259 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-09 14:24:59.341  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:24:59.344  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:24:59.348  7610  7610 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:59.348  7610  7610 D BluetoothMapService: STATE_ON
09-09 14:24:59.348  7610  7610 V BluetoothMapService: Handler(): got msg=1
09-09 14:24:59.350  7610  7610 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,09-09 14:24:59.356  6819  6819 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-09 14:24:59.358  7610  7952 D BluetoothMapMasInstance: MAS initSocket()
09-09 14:24:59.358  6819  6819 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:24:59.359  7610  7952 D BluetoothMapMasInstance:   masId = 00
09-09 14:24:59.359  7610  7952 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 14:24:59.359  7610  7952 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 14:24:59.359  7610  7952 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 14:24:59.366  6819  6819 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:24:59.369  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:59.370  7610  7610 V BluetoothPbapService: Pbap Service onCreate
09-09 14:24:59.370  7610  7610 V BluetoothPbapService: Starting PBAP service
09-09 14:24:59.371  7610  7610 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 14:24:59.372  7610  7610 V BluetoothPbapService: Pbap Service onBind
09-09 14:24:59.374  7610  7610 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:59.374  7610  7610 V BluetoothPbapService: state: 12
09-09 14:24:59.375  1035  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:59.376  7610  7610 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:24:59.376  7610  7610 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:59.376  7610  7610 V BluetoothPbapReceiver: ***********state = 12
09-09 14:24:59.377  6819  6819 D BluetoothPbap: Proxy object connected
09-09 14:24:59.377  6819  6819 D PbapServerProfile: Bluetooth service connected
09-09 14:24:59.378  7610  7610 V BluetoothPbapService: Handler(): got msg=1
09-09 14:24:59.380  7610  7952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:59.380  7610  7610 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 14:24:59.380  2219  2219 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:24:59.381  7610  7952 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
,09-09 14:24:59.381  7610  7954 V BluetoothPbapService: Pbap Service initSocket
09-09 14:24:59.381  2219  2219 D c       : Getting all permits...
09-09 14:24:59.381  2219  2219 D a       : Opening database...
09-09 14:24:59.381  1035  2113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:59.381  7610  7952 V BluetoothMapMasInstance: Succeed to create listening socket 
09-09 14:24:59.382  7610  7952 D BluetoothMapMasInstance: Accepting socket connection...
09-09 14:24:59.382  7610  7954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:59.383  7610  7954 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 14:24:59.383  7610  7954 V BluetoothPbapService: Succeed to create listening socket 
09-09 14:24:59.383  7610  7954 V BluetoothPbapService: Accepting socket connection...
09-09 14:24:59.386  2219  2219 D a       : Opening database auth.proximity.permit_store...
09-09 14:24:59.387  2219  2219 D a       : Closing database...
09-09 14:24:59.389  7610  7843 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:24:59.389  7610  7843 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 14:24:59.392  7610  7843 D BluetoothAdapterProperties: Scan Mode:21
09-09 14:24:59.392  7610  7843 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 14:24:59.395  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:24:59.401  6819  6819 D BluetoothPermissionRequest: onReceive
,09-09 14:24:59.403  6819  6819 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 14:24:59.404  6819  6819 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:24:59.407  7610  7610 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-09 14:24:59.408  7610  7610 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-09 14:24:59.413  7610  7610 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-09 14:24:59.427  7610  7610 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 14:24:59.427  7610  7610 V BtOppService: onCreate
,09-09 14:24:59.432  7610  7610 V BluetoothOppNotification: send message
09-09 14:24:59.435  7610  7610 V BtOppService: Starting RfcommListener
09-09 14:24:59.440  7610  7610 D BluetoothOppPreference: Dumping Names:  
,09-09 14:24:59.440  7610  7610 D BluetoothOppPreference: {}
,09-09 14:24:59.440  7610  7610 D BluetoothOppPreference: Dumping Channels:  
09-09 14:24:59.440  7610  7610 D BluetoothOppPreference: {}
09-09 14:24:59.441  7610  7610 V BtOppService: onStartCommand
09-09 14:24:59.444  7610  7610 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:59.445  7610  7610 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 14:24:59.446  7610  7961 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 14:24:59.448  7610  7610 V BluetoothOppNotification: new notify threadi!
09-09 14:24:59.449  7610  7610 V BluetoothOppNotification: send delay message
09-09 14:24:59.449  7610  7610 V BtOppService: start RfcommListener
09-09 14:24:59.451  7610  7610 V BtOppService: RfcommListener started
09-09 14:24:59.453  7610  7963 V BtOppRfcommListener: Starting RFCOMM listener....
09-09 14:24:59.454  1035  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:24:59.456  7610  7963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:59.457  7610  7963 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-09 14:24:59.458  7610  7963 V BtOppRfcommListener: Started RFCOMM listener....
09-09 14:24:59.458  7610  7963 I BtOppRfcommListener: Accept thread started.
09-09 14:24:59.458  7610  7963 V BtOppRfcommListener: Accepting connection...
09-09 14:24:59.459  7610  7958 V BtOppService: Deleted complete outbound shares, number =  0
09-09 14:24:59.459  7610  7962 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 14:24:59.459  7610  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 14:24:59.462  7610  7962 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@302a2b3d on behalf of 
09-09 14:24:59.463  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:59.463  7610  7610 V BluetoothFtpService: Ftp Service onCreate
09-09 14:24:59.463  7610  7610 I BluetoothFtpService: Ftp Service onCreate
09-09 14:24:59.463  7610  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@94f2f32 on behalf of 
09-09 14:24:59.463  7610  7610 V BluetoothFtpService: Ftp Service onStartCommand
09-09 14:24:59.463  7610  7958 V BtOppService: Deleted complete inbound failed shares, number = 0
09-09 14:24:59.463  7610  7610 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:59.464  7610  7610 V BluetoothFtpService: Starting Listening on sockets
09-09 14:24:59.464  7610  7610 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:24:59.464  7610  7610 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:24:59.464  7610  7610 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:24:59.464  7610  7610 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:59.464  7610  7610 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 14:24:59.464  7610  7610 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 14:24:59.465  7610  7962 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 14:24:59.465  7610  7958 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 14:24:59.466  7610  7961 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 14:24:59.469  7610  7962 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-09 14:24:59.473  7610  7958 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@95e8600 on behalf of 
09-09 14:24:59.473  7610  7962 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e133e39 on behalf of 
09-09 14:24:59.474  7610  7962 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 14:24:59.475  7610  7962 V BluetoothOppNotification: outbound notification was removed.
09-09 14:24:59.475  7610  7962 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 14:24:59.477  7610  7962 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@143d0c7e on behalf of 
09-09 14:24:59.478  7610  7962 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 14:24:59.479  7610  7962 V BluetoothOppNotification: inbound notification was removed.
09-09 14:24:59.479  7610  7962 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 14:24:59.481  7610  7962 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f40e5df on behalf of 
,09-09 14:24:59.578  1035  1984 I art     : Explicit concurrent mark sweep GC freed 25287(1245KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.943ms total 111.808ms
,09-09 14:24:59.579  7610  7610 V BtOppService: ContentObserver received notification
09-09 14:24:59.579  7610  7610 V BtOppService: ContentObserver received notification
09-09 14:24:59.579  7610  7610 V BluetoothFtpService: Handler(): got msg=1
09-09 14:24:59.580  7610  7610 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-09 14:24:59.580  7610  7610 V BluetoothFtpService: Ftp Service initSocket
09-09 14:24:59.581  7610  7964 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 14:24:59.582  1035  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:59.582  7610  7964 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 14:24:59.583  7610  7610 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:59.583  7610  7610 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-09 14:24:59.584  7610  7610 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-09 14:24:59.586  7610  7965 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-09 14:24:59.587  7610  7964 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e26022c on behalf of 
09-09 14:24:59.588  7610  7964 V BluetoothOppNotification: update too frequent, put in queue
09-09 14:24:59.590  7610  7964 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 14:24:59.597  7610  7610 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c635b1
09-09 14:24:59.597  7610  7610 V BluetoothSapService: Sap Service onCreate
,09-09 14:24:59.592  7966  7966 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:59.592  7966  7966 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:24:59.598  7610  7610 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:24:59.598  7610  7610 V BluetoothSapService: state: 12
09-09 14:24:59.598  7610  7610 V BluetoothSapService: Starting SAP server process
09-09 14:24:59.600  7610  7610 V BluetoothSapService: SAP Service startRfcommListenerThread
09-09 14:24:59.601  7610  7967 V BluetoothSapService: Sap Service initRfcommSocket
09-09 14:24:59.601  1035  2076 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:24:59.603  7610  7967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:24:59.603  7610  7967 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-09 14:24:59.604  7610  7967 V BluetoothSapService: Succeed to create listening socket 
09-09 14:24:59.604  7610  7967 V BluetoothSapService: Accepting socket connection...
09-09 14:24:59.611  7966  7966 V BT_SAP  : Event pipe created
09-09 14:24:59.611  7966  7966 V BT_SAP  : create_server_socket qcom.sap.server
09-09 14:24:59.611  7966  7966 V BT_SAP  : created socket fd 6
,09-09 14:25:00.041  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-09 14:25:00.042  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-09 14:25:00.042  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-09 14:25:00.042  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,09-09 14:25:00.055  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
09-09 14:25:00.055  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
09-09 14:25:00.056  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
09-09 14:25:00.057  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
09-09 14:25:00.061  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:25:00.061  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:00.061  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:25:00.061  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:25:00.061  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:00.061  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:00.061  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:00.061  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:25:00.064  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:25:00.067  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:00.067  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d720b2a added. We now have 8 listener(s)
09-09 14:25:00.067  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:00.071  1035  1966 D WifiServiceImplEx: setWifiEnabled: false pid=6588, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:25:00.072  1035  1966 D WifiService: setWifiEnabled: false pid=6588, uid=10118
09-09 14:25:00.072  1035  1966 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:25:00.079  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:25:00.083  1035  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6588, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:25:00.084  1035  1051 D WifiService: setWifiEnabled: true pid=6588, uid=10118
09-09 14:25:00.084  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:25:00.099  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:25:00.099  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:25:00.099  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-09 14:25:00.103  1035  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-09 14:25:00.103  1035  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-09 14:25:00.106  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-09 14:25:00.106  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-09 14:25:00.106  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-09 14:25:00.106  1035  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 14:25:00.106  1035  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 14:25:00.106  1035  1538 E WifiHW  : unknown target_country: EU , set to default
09-09 14:25:00.106  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 14:25:00.106  1035  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,09-09 14:25:00.107  1035  1538 I WifiUtil: gEnableBmps=1,
09-09 14:25:00.451  7610  7610 V BluetoothOppNotification: new notify threadi!
09-09 14:25:00.452  7610  7610 V BluetoothOppNotification: send delay message
,09-09 14:25:00.472  7610  7980 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 14:25:00.474  7610  7980 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7071518 on behalf of 
09-09 14:25:00.475  7610  7980 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 14:25:00.476  7610  7980 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 14:25:00.477  7610  7980 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f017b71 on behalf of 
09-09 14:25:00.478  7610  7980 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-09 14:25:00.482  7610  7980 V BluetoothOppNotification: outbound notification was removed.
,09-09 14:25:00.482  7610  7980 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 14:25:00.484  7610  7980 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a42d56 on behalf of 
09-09 14:25:00.484  7610  7980 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-09 14:25:00.487  7610  7980 V BluetoothOppNotification: inbound notification was removed.
09-09 14:25:00.487  7610  7980 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 14:25:00.489  7610  7980 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f3bb1d7 on behalf of 
09-09 14:25:00.788   309   895 D SoftapController: Softap fwReload - Ok
,09-09 14:25:00.809  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:25:00.809  1035  1117 D Tethering: InitialState.processMessage what=4
,09-09 14:25:00.813  1035  1538 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (703ms)
09-09 14:25:00.817   309   895 D CommandListener: Setting iface cfg
09-09 14:25:00.817   309   895 D CommandListener: Trying to bring down wlan0
09-09 14:25:00.826   309   895 D CommandListener: Clearing all IP addresses on wlan0
,09-09 14:25:00.835  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:25:00.844  1035  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-09 14:25:00.842  7988  7988 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:25:00.852  7988  7988 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:25:00.862  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:25:00.862  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:25:00.862  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:25:00.871  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:00.876  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-09 14:25:00.878  1035  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 14:25:00.878  1035  1538 D WifiMonitor: connecting to supplicant
09-09 14:25:00.883  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 14:25:00.883  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:25:00.884  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:25:00.884  6819  6819 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 14:25:00.894  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:00.894  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 14:25:00.895  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-09 14:25:00.897  6819  6819 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:25:00.897  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 14:25:00.898  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:25:00.898  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:25:00.898  6819  6819 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:25:00.898  6819  6819 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 14:25:00.901  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 14:25:00.901  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:25:00.901  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:25:00.901  6819  6819 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 14:25:00.901  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 14:25:00.902  6819  6819 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:25:00.902  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 14:25:00.902  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:25:00.902  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:25:00.902  6819  6819 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:25:00.903  6819  6819 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 14:25:00.904  7988  7988 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 14:25:00.923  7706  7718 E UEI.SmartControl: file observer is disposed!
,09-09 14:25:00.940  7988  7988 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 14:25:00.940  7988  7988 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 14:25:00.953  1035  2030 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8006 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-09 14:25:01.051  7988  7988 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 14:25:01.056  1035  1966 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8028 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 14:25:01.059  8006  8026 W FormManager: Network not available. Please check & try again.
09-09 14:25:01.063  8006  8027 V FormManager: Network unavailable.
,09-09 14:25:01.067  8006  8027 V FormManager: Network unavailable.
,09-09 14:25:01.082  7988  7988 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-09 14:25:01.085  1035  1705 I ActivityManager: Killing 7108:com.android.chrome/u0a57 (adj 15): empty #17
09-09 14:25:01.087  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-09 14:25:01.089  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-09 14:25:01.090  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-09 14:25:01.090  1035  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-09 14:25:01.090  1035  8046 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 14:25:01.090  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-09 14:25:01.090  1035  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 14:25:01.091  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 14:25:01.091  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 14:25:01.091  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:25:01.091  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:25:01.091  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 14:25:01.091  1035  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:25:01.092  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 14:25:01.092  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 14:25:01.092  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:25:01.092  1035  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 14:25:01.092  1035  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 14:25:01.092  1035  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 14:25:01.092  1035  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 14:25:01.092  1035  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 14:25:01.093  1035  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 14:25:01.093  1035  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 14:25:01.105  8028  8028 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:25:01.115  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:25:01.115  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:01.115  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:25:01.115  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:01.115  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:01.115  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:01.115  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:01.115  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:25:01.116  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:25:01.120  6588  6680 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 14:25:01.120  6588  6680 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 14:25:01.122  6588  6680 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3ba1a59c Bundle[{}]
09-09 14:25:01.122  6588  6680 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 14:25:01.123  6588  6680 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 14:25:01.123  6588  6680 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 14:25:01.124  6588  6680 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 14:25:01.124  6588  6680 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 14:25:01.124  6588  6680 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 14:25:01.128  6588  6680 I System.out: Running OutgoingSocketThread
,09-09 14:25:01.131  6588  8049 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 841)
09-09 14:25:01.132  6588  8049 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42938
09-09 14:25:01.132  6588  8049 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 14:25:01.193  1035  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:25:01.193  1035  1538 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:25:01.193  1035  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:25:01.193  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.194  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.194  1035  1575 W libprocessgroup: failed to open /acct/uid_10057/pid_7108/cgroup.procs: No such file or directory
09-09 14:25:01.194  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.195  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.195  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-09 14:25:01.201  1035  1575 I ActivityManager: Killing 7126:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-09 14:25:01.271  1035  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 14:25:01.272  1035  1538 D WifiNative-wlan0: SET update_config 1: returned true
09-09 14:25:01.273  1035  1538 D WifiConfigStore: Loading config and enabling all networks 
09-09 14:25:01.273  1035  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 14:25:01.274  1035  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-09 14:25:01.277  1967  1967 D WfdService: Waiting for WifiP2p enabling
09-09 14:25:01.282  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:01.292  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:25:01.292  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:01.292  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:25:01.292  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:01.292  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:01.292  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:01.292  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:01.292  6588  6588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:25:01.293  1035  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-09 14:25:01.295  1035  2076 W libprocessgroup: failed to open /acct/uid_10062/pid_7126/cgroup.procs: No such file or directory
09-09 14:25:01.299  6588  6588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:25:01.299  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 14:25:01.301  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 14:25:01.302  1035  1542 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,09-09 14:25:01.309  1035  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 14:25:01.309  1035  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 14:25:01.310  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:01.313  1035  1538 D WifiStateMachine: enableVerboseLogging : level 2
09-09 14:25:01.313  1035  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 14:25:01.314  1035  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 14:25:01.314  1035  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 14:25:01.314  1035  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 14:25:01.314  1035  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 14:25:01.315  1035  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 14:25:01.315  1035  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 14:25:01.315  1035  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
,09-09 14:25:01.315  1035  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 14:25:01.316  1035  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 14:25:01.316  1035  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 14:25:01.316  1035  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 14:25:01.316  1035  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 14:25:01.317  1035  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 14:25:01.319  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 14:25:01.319  1035  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-09 14:25:01.319  1035  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 14:25:01.319  1035  1538 D WifiNative-HAL: Setting external_sim to 1
09-09 14:25:01.319  1035  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 14:25:01.319  1967  1967 D WfdsService: Supplicant Connection state is changed : true
09-09 14:25:01.320  1967  2387 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 14:25:01.320  1967  2387 D WfdsService: Set the WFDS Monitor: true
09-09 14:25:01.320  1967  2387 D WfdsMonitor: WfdsMonitorThread create
09-09 14:25:01.320  1967  2387 D WfdsMonitor: WFDS Monitor is created and started
09-09 14:25:01.320  1967  2387 D WfdsService: WiFi: Supplicant connection re-established
09-09 14:25:01.320  7639  7639 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.320  1035  1538 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 14:25:01.320  1035  1538 I WifiNative-HAL: startHal
,09-09 14:25:01.320  1035  1538 D wifi    : setting scan oui 0xaf504360
09-09 14:25:01.321  1035  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 14:25:01.321  1967  8050 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 14:25:01.321  1035  1538 I WifiNative-HAL: startHal
09-09 14:25:01.321  1035  1538 D wifi    : setting scan oui 0xaf504360
09-09 14:25:01.321  1035  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 14:25:01.321  1967  8050 E CtrlSupplicant: Succeed to open control connection
09-09 14:25:01.322  1967  8050 E CtrlSupplicant: Succeed to open monitor connection
09-09 14:25:01.322  1967  8050 D WfdsMonitor: Supplicant connection established
09-09 14:25:01.322  1967  2387 D WfdsService: Connected to the supplicant for wfds
09-09 14:25:01.322  1035  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 14:25:01.322  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 14:25:01.322  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 14:25:01.323  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 14:25:01.323  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 14:25:01.323  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 14:25:01.323  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 14:25:01.323  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 14:25:01.323  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 14:25:01.324  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 14:25:01.324  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 14:25:01.324  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 14:25:01.324  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,09-09 14:25:01.324  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 14:25:01.324  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 14:25:01.325  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 14:25:01.325  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 14:25:01.325  7988  7988 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,09-09 14:25:01.325  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 14:25:01.325  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 14:25:01.325  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 14:25:01.326  1035  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 14:25:01.327  1035  1538 E WifiNative: : [138,744,573 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 14:25:01.327  1035  1538 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 14:25:01.327  1035  1538 D WifiNative-wlan0: RECONNECT: returned true
09-09 14:25:01.327  1035  1538 D WifiNative-wlan0: doString: [STATUS]
,09-09 14:25:01.328  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 14:25:01.328  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 14:25:01.329  1035  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 14:25:01.329  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:25:01.329  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:25:01.330  1035  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:25:01.333   309   895 D CommandListener: Setting iface cfg
09-09 14:25:01.333   309   895 D CommandListener: Trying to bring up p2p0
09-09 14:25:01.333  8028  8028 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:25:01.334  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 14:25:01.334  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.334  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 14:25:01.334  1035  1556 I WifiNative-HAL: startHal
09-09 14:25:01.334  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf504360
09-09 14:25:01.334  1035  1556 D wifi    : failed to get capabilities : -3
09-09 14:25:01.334  1035  1556 E WifiScanningService: could not get scan capabilities
09-09 14:25:01.334  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-09 14:25:01.334  1035  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.334  1035  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 14:25:01.335  1035  1537 D LGWifiP2pService: P2pEnablingState
09-09 14:25:01.335  1035  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 14:25:01.335  1035  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.335  1035  1537 D LGWifiP2pService: P2p socket connection successful
09-09 14:25:01.335  1035  1537 D LGWifiP2pService: P2pEnabledState
09-09 14:25:01.335  1035  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 14:25:01.335  1035  1537 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 14:25:01.335  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 14:25:01.335  1035  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 14:25:01.336  1035  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 14:25:01.336  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=138754  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:25:01.336  1035  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 14:25:01.336  1035  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 14:25:01.337  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 14:25:01.337  1035  1537 D WifiNative-p2p0: SET device_name G3: returned true
09-09 14:25:01.337  1035  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 14:25:01.337  1967  1967 D WfdsService: WifiP2pState is changed : true
09-09 14:25:01.337  1035  1537 D LGWifiP2pService: before postfix = G3
09-09 14:25:01.337  1035  1537 D WifiServerServiceExt: postfix byte check : 2
09-09 14:25:01.337  1035  1537 D LGWifiP2pService: after postfix = G3
09-09 14:25:01.337  1035  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-09 14:25:01.337  1967  2387 D WfdsService: Receive the WFDS_ENABLE Method
09-09 14:25:01.337  1967  2387 D WfdsService: Set the WFDS Monitor: true
09-09 14:25:01.337  1967  2387 D WfdsService: Connected to the supplicant for wfds
09-09 14:25:01.337  1967  2387 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 14:25:01.337  7988  7988 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 14:25:01.337  1035  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 14:25:01.337  1035  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-09 14:25:01.338  1967  2387 D WfdsService: selectPreferredScanChannel [36]
09-09 14:25:01.338  1967  2387 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 14:25:01.338  1035  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 14:25:01.338  1035  1537 D WifiNa,tive-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 14:25:01.338  1035  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 14:25:01.339  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 14:25:01.339  1035  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 14:25:01.339  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress
09-09 14:25:01.339  1035  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-09 14:25:01.340  1035  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 14:25:01.340  1035  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 14:25:01.340  1967  1967 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 14:25:01.340  1967  1967 D WfdsService: isConnected: false
09-09 14:25:01.340  1035  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 14:25:01.340  1035  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 14:25:01.341  1035  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 14:25:01.341  1035  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 14:25:01.341  1035  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 14:25:01.341  1035  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-09 14:25:01.344  1967  1967 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 14:25:01.344  1967  1967 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 14:25:01.344  1967  1967 D WfdsService: Update P2p Interface State: 3
09-09 14:25:01.345  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:01.345  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:25:01.347  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:01.348  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=138764  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:25:01.349  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.349  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.349  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 14:25:01.349  1035  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 14:25:01.349  1035  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 14:25:01.350  1035  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 14:25:01.350  1035  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 14:25:01.351  7988  7988 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 14:25:01.351  1035  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 14:25:01.351  1035  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 14:25:01.351  1035  1537 D LGWifiP2pService: InactiveState
09-09 14:25:01.351  1035  1537 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.352  1035  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 14:25:01.352  1035  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 14:25:01.353  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.353  1035  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 14:25:01.353  1035  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 14:25:01.353  7988  7988 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 14:25:01.353  1035  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 14:25:01.353  1035  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 14:25:01.354  1035  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.354  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.354  1035  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.354  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 14:25:01.354  1035  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.354  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:25:01.354  1035  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.354  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:25:01.354  1035  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.354  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.354  1035  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.354  1035  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.355  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.355  1035  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.355  7988  7988 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 14:25:01.355  1967  8050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:25:01.355  1035  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:25:01.355  1035  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:25:01.355  1035  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:25:01.355  1035  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:25:01.355  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.356  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 14:25:01.356  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 14:25:01.356  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.356  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 14:25:01.357  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 14:25:01.357  1035  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:25:01.357  1967  8050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:25:01.357  1035  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.357  1967  8050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:25:01.357  1035  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.357  1035  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.357  1035  1035 E WifiServerServiceExt: No p2p device connected
09-09 14:25:01.357  1035  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:25:01.357  1035  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.357  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 14:25:01.358  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:25:01.358  1967  2387 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 14:25:01.358  1035  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.358  1035  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.358  1035  8046 D WifiMonitor: Event, [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:25:01.358  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:25:01.358  1035  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:25:01.358  1035  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:25:01.359  7988  7988 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 14:25:01.359  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.359  1035  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 14:25:01.359  1035  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:25:01.360  1035  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.360  1035  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.360  1035  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.360  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.360  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.360  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:01.360  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:01.360  1967  8050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:25:01.360  1035  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:25:01.360  1035  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.360  1967  8050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:25:01.360  1035  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.360  1035  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:25:01.361  1035  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:25:01.361  1035  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:25:01.362  1035  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:25:01.362  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 14:25:01.362  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 14:25:01.362  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:25:01.362  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 14:25:01.362  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:25:01.362  1035  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:25:01.362  1035  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:25:01.363  1035  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 14:25:01.363  1035  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 14:25:01.363  1035  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 14:25:01.363  1035  1538 D WifiNative-wlan0: doBoolean: SCAN
09-09 14:25:01.368  8006  8052 W FormManager: Network not available. Please check & try again.
09-09 14:25:01.369  1035  1538 D WifiNative-wlan0: SCAN: returned false
09-09 14:25:01.369  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=138787  SSID:  BSSID: 00:00:00:0,0:00:00 nid: -1 state: SCANNING
09-09 14:25:01.375  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=138793  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:25:01.375  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:01.375  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:25:01.376  1035  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:25:01.376  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:01.377  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.377  1035  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:25:01.377  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.377  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 14:25:01.377  1035  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:25:01.378  1035  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:25:01.378  1035  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:25:01.378  8006  8053 V FormManager: Network unavailable.
09-09 14:25:01.380  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:25:01.380  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:25:01.380  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:25:01.380  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 14:25:01.381  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:25:01.381  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 14:25:01.382  8006  8053 V FormManager: Network unavailable.
09-09 14:25:01.382  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:25:01.385  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:25:01.391  4351  8054 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:25:01.394  4351  8055 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:25:01.394  4351  8055 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 14:25:01.459  1035  1731 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8056 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-09 14:25:01.479   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 27.789ms
,09-09 14:25:01.499   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 422us total 19.426ms
,09-09 14:25:01.517   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 381us total 16.968ms
,09-09 14:25:01.544  8056  8056 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 14:25:01.544  8056  8056 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-09 14:25:01.550  8056  8056 V [BNRBootReceiver]: Boot Receiver Return
09-09 14:25:01.551  8056  8056 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-09 14:25:01.607  1035  1050 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8074 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 14:25:01.609  1035  1050 I ActivityManager: Killing 7143:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-09 14:25:01.681  1035  1984 W libprocessgroup: failed to open /acct/uid_10085/pid_7143/cgroup.procs: No such file or directory
,09-09 14:25:01.717  8074  8074 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 14:25:01.733  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 14:25:01.733  1035  8046 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 14:25:01.733  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 14:25:01.734  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
09-09 14:25:01.734  1035  8046 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,09-09 14:25:01.734  7988  7988 E wpa_supplicant: USIM:  scard_init function
09-09 14:25:01.735  7988  7988 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-09 14:25:01.737  1035  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 14:25:01.738  1035  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 14:25:01.739  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 14:25:01.739  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-09 14:25:01.739  1035  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 14:25:01.740  1035  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 14:25:01.740  1035  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 14:25:01.744  8074  8074 D PluginManager: init()
09-09 14:25:01.752  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=139170  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-09 14:25:01.756  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=139174  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-09 14:25:01.756  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:01.756  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:25:01.757  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 14:25:01.757  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:25:01.757  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 14:25:01.757  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:01.757  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:25:01.759  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:01.987  7706  7815 D UEI.SmartControl: Internal timer expired: 3
09-09 14:25:01.987  7706  7815 D UEI.SmartControl: unbind internal service
,09-09 14:25:01.994  7706  7706 D UEI.SmartControl: Service.onUnbind: IControl
09-09 14:25:01.995  7706  7706 D UEI.SmartControl: Service.onDestroy
09-09 14:25:01.996  7706  7706 D UEI.SmartControl: Lock is in USE false
,09-09 14:25:01.996  7706  7706 D UEI.SmartControl: unbind internal service
09-09 14:25:01.996  7706  7706 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3b3ce9e9
09-09 14:25:01.997  7706  7706 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-09 14:25:01.997  7706  7706 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-09 14:25:01.997  7706  7706 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-09 14:25:01.997  7706  7706 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-09 14:25:01.997  7706  7706 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-09 14:25:01.998  7706  7706 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-09 14:25:01.998  7706  7706 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-09 14:25:01.998  7706  7706 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-09 14:25:01.998  7706  7706 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:01.998  7706  7706 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:25:02.000  7706  7706 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:25:02.000  7706  7706 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:25:02.000  7706  7706 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:25:02.000  7706  7706 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:25:02.000  7706  7706 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:25:02.000  7706  7706 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3b3ce9e9
09-09 14:25:02.000  7706  7706 D serial_port: close(fd = 24)
09-09 14:25:02.004  7706  7706 I UEI.SmartControl: Serial port is closed.
09-09 14:25:02.004  7706  7706 I UEI.SmartControl: Serial port is closed.
09-09 14:25:02.004  7706  7706 D UEI.SmartControl: Blaster closed
09-09 14:25:02.004  7706  7706 D UEI.SmartControl: Shut down QS...
09-09 14:25:02.004  7706  7706 D UEI.SmartControl: Stopping QS lib
09-09 14:25:02.004  7706  7706 D UEI.SmartControl: QS lib stop result = true
09-09 14:25:02.004  7706  7706 D UEI.SmartControl: Stopped QS lib
09-09 14:25:02.004  7706  7706 D UEI.SmartControl: QS shutdown complete
,09-09 14:25:02.095  7988  7988 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 14:25:02.095  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 14:25:02.095  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 14:25:02.095  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,09-09 14:25:02.095  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 14:25:02.096  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 14:25:02.097  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=139515  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 14:25:02.097  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=139515  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 14:25:02.097  1035  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139516
09-09 14:25:02.097  1035  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139516
09-09 14:25:02.098  1035  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139516
09-09 14:25:02.098  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139516
09-09 14:25:02.100  1035  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139516
,09-09 14:25:02.101  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:25:02.101  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 14:25:02.101  1035  1538 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:25:02.101  1035  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:25:02.101  1035  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:25:02.102  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:25:02.102  1035  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:25:02.103  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:25:02.103  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:25:02.104  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139522  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 14:25:02.105  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139523  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 14:25:02.108  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.108  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.108  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 14:25:02.108  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.108  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.108  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 14:25:02.108  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:25:02.108  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 14:25:02.109  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:02.109  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:25:02.115  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.116  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:02.116  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 14:25:02.117  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.129  6588  6680 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 842)
09-09 14:25:02.130  6588  6680 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 842)
,09-09 14:25:02.132  6588  6680 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 847)
09-09 14:25:02.132  6588  6680 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 14:25:02.132  6588  6680 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 848)
09-09 14:25:02.134  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.134  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@571bd1b added. We now have 2 listener(s)
09-09 14:25:02.134  1035  2076 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.136  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:25:02.136  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.136  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.136  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.136  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16edeeb8 added. We now have 9 listener(s)
09-09 14:25:02.136  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:02.136  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:25:02.138  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:02.140  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:02.140  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:02.140  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:25:02.140  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:02.140  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:02.140  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:02.140  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:02.140  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:25:02.141  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:25:02.141  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:25:02.142  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.142  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.143  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.143  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d7daff6 added. We now have 3 listener(s)
09-09 14:25:02.143  1035  1705 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.144  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:25:02.144  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.144  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.144  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.144  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28650ff7 added. We now have 10 listener(s)
09-09 14:25:02.144  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:02.144  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:25:02.144  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:02.144  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:02.145  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.145  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.145  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:02.145  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.145  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@571bd1b removed from the list
09-09 14:25:02.145  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.145  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16edeeb8 removed from the list
09-09 14:25:02.145  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:25:02.145  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.145  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.145  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.147  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: ,stopAdvertising
09-09 14:25:02.147  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.147  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.147  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16edeeb8 not in the list
09-09 14:25:02.147  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.147  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.148  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.148  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:02.148  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.148  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28650ff7 removed from the list
09-09 14:25:02.148  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.148  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.148  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.148  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.148  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d7daff6 removed from the list
09-09 14:25:02.149  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.149  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def3e64 added. We now have 2 listener(s)
09-09 14:25:02.149  1035  1731 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.151  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:25:02.151  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.151  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.151  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.151  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@393838cd added. We now have 9 listener(s)
,09-09 14:25:02.151  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:02.151  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:25:02.153  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:25:02.158  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:02.158  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:02.158  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:25:02.158  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:02.158  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:02.158  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:02.158  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:02.158  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:25:02.158  8074  8074 W ExternalStrings: load override strings
09-09 14:25:02.158  8074  8074 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:25:02.158  8074  8074 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:25:02.159  7988  7988 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:25:02.159  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:25:02.159  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:25:02.159  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:25:02.160  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 14:25:02.161  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:25:02.161  1035  8046 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:25:02.161  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22,:99:3e completed [id=0 id_str=]]
09-09 14:25:02.161  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:25:02.161  1035  8046 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:25:02.161  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:25:02.161  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:25:02.161  1035  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=139578  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 14:25:02.161  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:25:02.161  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=139580  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 14:25:02.161  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:25:02.162  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.162  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29d0b493 added. We now have 3 listener(s)
09-09 14:25:02.162  1035  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139580
09-09 14:25:02.162  1035  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139580
09-09 14:25:02.162  1035  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.162  1035  1538 D WifiNative-wlan0: doString: [STATUS]
09-09 14:25:02.163  1035  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:25:02.163  1035  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:25:02.163  1035  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 14:25:02.163  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.163  1035  1538 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 14:25:02.165  8074  8074 D StatusProvider: onCreate
09-09 14:25:02.165  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-09 14:25:02.165  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.165  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.165  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.165  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2193dcd0 added. We now have 10 listener(s)
09-09 14:25:02.165  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:02.166  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:02.166  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:25:02.166  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:25:02.166  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:02.166  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:25:02.167  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.169  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:25:02.171  1035  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.171  1035  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 14:25:02.171  1035  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-09 14:25:02.173  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:02.173  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:25:02.174  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.174  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.174  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 14:25:02.174  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.176  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.176  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.176  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-09 14:25:02.180  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:25:02.180  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 14:25:02.181  1035  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 14:25:02.181  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:25:02.181  1035  1544 D ConnectivityService: Got NetworkAgent Messenger
09-09 14:25:02.182  1035  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 14:25:02.182  1035  1544 D ConnectivityService: NetworkAgent connected
09-09 14:25:02.182  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:25:02.182  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:25:02.182  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:25:02.182  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 14:25:02.182  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:02.183  6588  6680 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:25:02.183  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:02.183  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:02.185  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:25:02.185  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:02.185  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:02.185  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.185  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.185  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:02.185  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.185  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@def3e64 removed from the list
09-09 14:25:02.185  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.185  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@393838c,d removed from the list
09-09 14:25:02.185  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:25:02.185  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.186  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.186  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.186  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:02.186  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.186  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.186  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@393838cd not in the list
09-09 14:25:02.186  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.186  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.187  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:25:02.187  1035  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:25:02.187  1035  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:25:02.188  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.188  1035  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:25:02.188  1035  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 14:25:02.188  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:25:02.188  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:25:02.188  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:02.188  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.188  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2193dcd0 removed from the list
09-09 14:25:02.188  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.188  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.188  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.189  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.189  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29d0b493 removed from the list
09-09 14:25:02.189  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.189  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4806ef added. We now have 2 listener(s)
09-09 14:25:02.189  1035  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.191  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:25:02.191  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.191  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.191  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.191  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a1f5fc added. We now have 9 listener(s)
09-09 14:25:02.191  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:02.191  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:25:02.193  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:02.195  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:02.195  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:02.195  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:25:02.195  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:02.195  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:02.195  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:02.195  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:02.195  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:25:02.198  1035  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:25:02.199   309   895 D CommandListener: Setting iface cfg
09-09 14:25:02.201  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:02.202  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:25:02.202  1035  1538 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 14:25:02.203  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139621  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:25:02.203  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139621  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:25:02.204  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139622  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:25:02.204  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:25:02.205  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 14:25:02.205  1035  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=139624  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:25:02.206  1035  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=139624  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:25:02.206  1035  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=139624  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:25:02.207  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:25:02.207  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:25:02.207  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.207  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dbb92da added. We now have 3 listener(s)
09-09 14:25:02.207  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14591] from screen [on:0 period:250119679] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 14:25:02.207  1035  1965 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.208  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.208  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.208  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:250119680] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 14:25:02.208  1035  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 14:25:02.210  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:25:02.210  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.210  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.210  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.210  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.210  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e38230b added. We now have 10 listener(s)
09-09 14:25:02.210  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:02.210  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:02.211  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:02.211  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:25:02.211  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:25:02.211  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:02.211  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:25:02.212  1035  8099 D DhcpStateMachine: StoppedState
09-09 14:25:02.213  1035  8099 D DhcpStateMachine: StoppedState{ when=-11ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:02.213  1035  8099 D DhcpStateMachine: WaitBeforeStartState
09-09 14:25:02.213  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:25:02.213  1035  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.215  1035  1544 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-09 14:25:02.215  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:25:02.215  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:25:02.216  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 14:25:02.216  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:25:02.216  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:25:02.216  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:25:02.216  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:25:02.217  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:02.217  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:25:02.217  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:25:02.217  1035  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 14:25:02.217  6588  6680 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:25:02.218  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:25:02.218  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:02.218  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:02.218  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.218  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.218  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:02.218  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.218  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4806ef removed from the list
09-09 14:25:02.218  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.218  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a1f5fc removed from the list
09-09 14:25:02.218  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:25:02.218  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.218  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:25:02.218  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 14:25:02.219  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.219  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.219  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:02.220  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:25:02.220  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.220  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.220  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 14:25:02.220  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a1f5fc not in the list
09-09 14:25:02.220  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.220  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.220  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.220  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
09-09 14:25:02.220  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:25:02.220  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:25:02.220  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:02.220  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.220  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e38230b removed from the list
09-09 14:25:02.221  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.221  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.221  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.221  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.221  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
09-09 14:25:02.221  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dbb92da removed from the list
09-09 14:25:02.221  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 14:25:02.221  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 14:25:02.221  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 14:25:02.221  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 14:25:02.221  1035  1538 D WifiNative-wlan0: SET ps 0: returned true
09-09 14:25:02.221  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 14:25:02.221  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 14:25:02.221  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 14:25:02.222  1035  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 14:25:02.222  1035  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 14:25:02.222  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34aee99 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:02.222  1035  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 14:25:02.222  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34aee99 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:02.222  1035  8099 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:02.222  1035  8099 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 14:25:02.222   309   895 D CommandListener: Setting iface cfg
09-09 14:25:02.222   309   895 D CommandListener: Trying to bring up wlan0
09-09 14:25:02.223  1035  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 14:25:02.223  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-09 14:25:02.223  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-09 14:25:02.223  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:25:02.224  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:25:02.224  1035  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:02.224  1035  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:02.224  1035  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:25:02.224  1035  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 14:25:02.224  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 14:25:02.224  1035  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 14:25:02.224  1035  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:25:02.225  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.225  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad002a6 added. We now have 2 listener(s)
09-09 14:25:02.225  1035  1965 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.226  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:25:02.227  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.227  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.227  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.227  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dc3e4e7 added. We now have 9 listener(s)
09-09 14:25:02.227  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:25:02.227  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:25:02.230  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:02.230  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.231  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:02.231  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:02.231  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:25:02.231  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:02.231  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:02.231  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:02.231  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:02.231  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:25:02.232  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:25:02.232  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:25:02.232  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.232  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@915ef3d added. We now have 3 listener(s)
09-09 14:25:02.233  1035  1705 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.234  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.234  8074  8074 V Signer  : override build config not found
09-09 14:25:02.234  8074  8074 D Signer  : value of property debug is false
09-09 14:25:02.235  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:25:02.235  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.235  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.235  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.235  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1369a332 added. We now have 10 listener(s)
09-09 14:25:02.235  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:02.235  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:02.235  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:25:02.235  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:25:02.235  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:02.235  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:25:02.236  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.237  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:25:02.237  1035  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.239  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:25:02.240  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 14:25:02.241  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:25:02.241  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:02.242  6588  6680 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:25:02.243  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:25:02.243  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:02.243  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:02.243  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.243  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.243  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:02.243  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.243  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad002a6 removed from the list
09-09 14:25:02.243  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.243  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dc3e4e7 removed from the list
09-09 14:25:02.243  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:25:02.243  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.245  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.245  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.245  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:02.245  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.245  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.245  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dc3e4e7 not in the list
09-09 14:25:02.245  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.245  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.246  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.246  6588  6680 D BluetoothLeScanner: could not find callback wrapper
09-09 14:25:02.246  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:25:02.246  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:02.246  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.246  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1369a332 removed from the list
09-09 14:25:02.246  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.246  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.246  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.246  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.246  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@915ef3d removed from the list
09-09 14:25:02.247  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.247  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f74239 added. We now have 2 listener(s)
09-09 14:25:02.247  1035  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.248  1035  1538 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:25:02.248  1035  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 14:25:02.249  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:02.249  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:02.249  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:02.250  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:02.250  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:02.251  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:02.251  1035  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 14:25:02.252  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:25:02.252  1035  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 14:25:02.252  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.252  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.252  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.252  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@178ac07e added. We now have 9 listener(s)
09-09 14:25:02.252  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:02.252  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:25:02.252  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 14:25:02.252  1035  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 14:25:02.252  1035  1544 D ConnectivityService: ignoring duplicate network state non-change
09-09 14:25:02.253  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:25:02.256  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.256  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.256  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 14:25:02.257  1035  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 14:25:02.257  1035  1544 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 14:25:02.259  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:02.259  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:25:02.259  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.260  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.260  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 14:25:02.260  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.261  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:02.261  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:25:02.263  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.263  1967  1967 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 14:25:02.265  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 14:25:02.266  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.266  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.266  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 14:25:02.266  6588  6680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:25:02.266  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:25:02.266  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:25:02.266  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:25:02.266  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:25:02.266  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:25:02.266  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:25:02.266  6588  6680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:25:02.270  6588  6680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:25:02.270  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 14:25:02.270  6588  6680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:25:02.270  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:25:02.270  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4cd62c added. We now have 3 listener(s)
,09-09 14:25:02.271  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.273  6588  6588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:25:02.275  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.275  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:25:02.275  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 14:25:02.276  1035  2113 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:25:02.278  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:25:02.278  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:25:02.278  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:25:02.278  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:25:02.278  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f00c8f5 added. We now have 10 listener(s)
09-09 14:25:02.279  6588  6680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:25:02.279  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-09 14:25:02.279  6588  6680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:25:02.279  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:02.279  6588  6680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:25:02.279  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.279  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.279  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-09 14:25:02.279  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:25:02.279  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.279  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f74239 removed from the list
09-09 14:25:02.279  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.279  1035  1544 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 14:25:02.279  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@178ac07e removed from the list
09-09 14:25:02.279  6588  6680 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:25:02.279  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-09 14:25:02.279  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blue,toothManager: release: 1 listener(s) left
09-09 14:25:02.279  1035  1544 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 14:25:02.280  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-09 14:25:02.280  1035  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 14:25:02.280  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-09 14:25:02.280  1035  1544 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-09 14:25:02.280  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-09 14:25:02.280  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-09 14:25:02.280  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-09 14:25:02.280   309   895 E Netd    : netlink response contains error (File exists)
09-09 14:25:02.281  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.281  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.281  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-09 14:25:02.281  1035  1544 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-09 14:25:02.281  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-09 14:25:02.281  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
,09-09 14:25:02.281  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-09 14:25:02.281  1035  1544 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 14:25:02.281  1035  1544 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-09 14:25:02.281  8074  8074 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-09 14:25:02.281  1035  1544 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 14:25:02.282  1035  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 14:25:02.282  1035  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 14:25:02.282  1035  1544 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 14:25:02.282  1035  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 14:25:02.282  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:02.282  1035  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 14:25:02.282  1035  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:25:02.282  1035  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 14:25:02.282  1035  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:02.282  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 14:25:02.282  1035  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 14:25:02.282  1035  1544 D ConnectivityService: currentScore = 0, newScore = 20
,09-09 14:25:02.282  1035  1544 D ConnectivityService:    accepting network in place of null
09-09 14:25:02.282  1035  1544 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:02.282  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.283  1035  8094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:25:02.283  1035  8094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 14:25:02.283  1035  8094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:25:02.283  1035  8094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 14:25:02.284  1878  1878 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:02.284  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:25:02.285   309  8105 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 14:25:02.285  1035  1544 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,09-09 14:25:02.285  1035  1544 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 14:25:02.285  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:25:02.285  1035  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:25:02.285  1035  1544 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 14:25:02.285  1035  1544 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 14:25:02.287  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:25:02.287  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 14:25:02.287  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.287  1035  1544 D ConnectivityService: validation of new default Network = false
09-09 14:25:02.287  1035  1544 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 14:25:02.287  1035  1544 D DSQN    : enableDataServiceNotify 
09-09 14:25:02.287  1035  1544 D DSQN    : start dsqn bin
09-09 14:25:02.289  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:02.289  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.289  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.289  6588  6680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@178ac07e not in the list
09-09 14:25:02.289  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:25:02.289  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.293  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 14:25:02.293  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:25:02.293  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:25:02.293  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:25:02.294  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:25:02.294  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:25:02.294  6588  6680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:25:02.294  6588  6680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f00c8f5 removed from the list
09-09 14:25:02.294  6588  6680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:25:02.294  6588  6680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probab,ly already removed
09-09 14:25:02.294  6588  6680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:25:02.294  6588  6680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:25:02.294  6588  6680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f4cd62c removed from the list
09-09 14:25:02.294  1035  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 14:25:02.294  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:02.294  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:25:02.294  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 14:25:02.295  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 14:25:02.295  1035  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:25:02.295  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 14:25:02.295  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:25:02.295  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 14:25:02.295  6588  6680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 14:25:02.296  1601  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 14:25:02.282  8106  8106 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:25:02.282  8106  8106 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:25:02.303  1035  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 14:25:02.306  8074  8074 V LGMDMManager: Create singleton instance
09-09 14:25:02.308  8106  8106 E DSQN    : DSQN ssw
09-09 14:25:02.309  6588  8108 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 855, name: My test thread name)
,09-09 14:25:02.309  6588  8108 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 855, thread name: My test thread name)
09-09 14:25:02.310  6588  8108 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 855, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 14:25:02.313  6588  8111 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 857, name: My test thread name)
09-09 14:25:02.313  6588  8111 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 857, thread name: My test thread name)
09-09 14:25:02.313  6588  8111 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 857, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 14:25:02.314  6588  6680 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 14:25:02.314  6588  6680 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 14:25:02.314  6588  6680 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 14:25:02.314  6588  6680 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 14:25:02.314  6588  6680 D com.test.thalitest.ThaliTestRunner: Total duration: 22995 ms
09-09 14:25:02.315  1035  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:02.315  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:25:02.315  6588  6680 I jxcore-log: *Native tests were executed*
09-09 14:25:02.315  6588  6680 I jxcore-log: 
09-09 14:25:02.315  6588  6680 I jxcore-log: Total number of executed tests:  80
09-09 14:25:02.315  6588  6680 I jxcore-log: 
09-09 14:25:02.315  6588  6680 I jxcore-log: Number of passed tests:  80
09-09 14:25:02.315  6588  6680 I jxcore-log: 
09-09 14:25:02.316  6588  6680 I jxcore-log: Number of failed tests:  0
09-09 14:25:02.316  6588  6680 I jxcore-log: 
09-09 14:25:02.316  6588  6680 I jxcore-log: Number of ignored tests:  0
09-09 14:25:02.316  6588  6680 I jxcore-log: 
09-09 14:25:02.316  6588  6680 I jxcore-log: Total duration:  22995
09-09 14:25:02.316  6588  6680 I jxcore-log: 
09-09 14:25:02.316  6588  6680 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 14:25:02.316  6588  6680 I jxcore-log: 
09-09 14:25:02.318  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:02.318  6588  6680 I jxcore-log: 
09-09 14:25:02.320  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:02.320  6588  6680 I jxcore-log: 
09-09 14:25:02.321  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:02.321  6588  6680 I jxcore-log: 
09-09 14:25:02.322  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:02.322  6588  6680 I jxcore-log: 
,09-09 14:25:02.322  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:25:02.322  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:02.322  6588  6680 I jxcore-log: 
09-09 14:25:02.323  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.323  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.324  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:25:02.324  6588  6680 I jxcore-log: 
09-09 14:25:02.325  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.325  6588  6680 I jxcore-log: 
09-09 14:25:02.327  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.327  6588  6680 I jxcore-log: 
09-09 14:25:02.327  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.327  6588  6680 I jxcore-log: 
09-09 14:25:02.328  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:25:02.328  6588  6680 I jxcore-log: 
09-09 14:25:02.329  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.329  6588  6680 I jxcore-log: 
09-09 14:25:02.329  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.329  6588  6680 I jxcore-log: 
09-09 14:25:02.330  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.330  6588  6680 I jxcore-log: 
09-09 14:25:02.331  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.331  6588  6680 I jxcore-log: 
09-09 14:25:02.331  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.331  6588  6680 I jxcore-log: 
09-09 14:25:02.331  6588  6588 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 14:25:02.332  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.332  6588  6680 I jxcore-log: 
09-09 14:25:02.332  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.332  6588  6680 I jxcore-log: 
09-09 14:25:02.333  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.333  6588  6680 I jxcore-log: 
09-09 14:25:02.333  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.333  6588  6680 I jxcore-log: 
09-09 14:25:02.333  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:25:02.333  6588  6680 I jxcore-log: 
09-09 14:25:02.334  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.334  6588  6680 I jxcore-log: 
09-09 14:25:02.334  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.334  6588  6680 I jxcore-log: 
09-09 14:25:02.335  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.335  6588  6680 I jxcore-log: 
09-09 14:25:02.335  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.335  6588  6680 I jxcore-log: 
09-09 14:25:02.336  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.336  6588  6680 I jxcore-log: 
09-09 14:25:02.336  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.336  6588  6680 I jxcore-log: 
09-09 14:25:02.337  6588  6680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:25:02.337  6588  6680 I jxcore-log: 
09-09 14:25:02.342   309  8105 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-09 14:25:02.350  8074  8074 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
09-09 14:25:02.385  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 14:25:02.385  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:25:02.394  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:25:02.397  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:25:02.401   309  8105 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-09 14:25:02.423  1035  8099 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 14:25:02.424  1035  8099 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 14:25:02.424  1035  8099 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-09 14:25:02.431  8119  8119 I dhcpcd  : version 5.5.6 starting
09-09 14:25:02.432  8119  8119 E dhcpcd  : get_duid: m
09-09 14:25:02.432  8119  8119 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 14:25:02.432  8119  8119 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-09 14:25:02.412  8119  8119 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:25:02.412  8119  8119 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:25:02.440   309   894 D LGDataListener: argv[0]=dsqncommand
09-09 14:25:02.440   309   894 D LGDataListener: argv[1]=wlan0
09-09 14:25:02.440   309   894 D LGDataListener: argv[2]=1
09-09 14:25:02.440   309   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 14:25:02.449  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 14:25:02.449  1035  1115 D DSQN    : start to monitor internet connection
09-09 14:25:02.458  1035  8094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 12:25:02 GMT], X-Android-Received-Millis=[1473423902457], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473423902424]}
,09-09 14:25:02.458  1035  8094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 14:25:02.458  1035  8094 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 14:25:02.459  1035  1544 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 14:25:02.459  1035  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 14:25:02.459  1035  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:25:02.459  1035  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:25:02.459  1035  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,09-09 14:25:02.459  1035  1544 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 14:25:02.459  1035  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 14:25:02.459  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:02.459  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:25:02.459  1035  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:25:02.460  1035  1544 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:02.460  1035  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 14:25:02.461  1601  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 14:25:02.461  1035  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:02.461  1035  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:25:02.461  1878  1878 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:02.461  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:25:02.488  1035  1966 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8127 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-09 14:25:02.489  1035  1966 I ActivityManager: Killing 7165:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-09 14:25:02.496  8119  8119 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 14:25:02.496  8119  8119 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 14:25:02.496  8119  8119 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 14:25:02.496  8119  8119 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 14:25:02.496  8119  8119 D dhcpcd  : wlan0: sending REQUEST (xid 0x9817f572), next in 4.19 seconds
09-09 14:25:02.527  8119  8119 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-09 14:25:02.578  8119  8119 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 14:25:02.578  8119  8119 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-09 14:25:02.579  8119  8119 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 14:25:02.579  8119  8119 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 14:25:02.579  8119  8119 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 14:25:02.579  8119  8119 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 14:25:02.580  8119  8119 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 14:25:02.580  8119  8119 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-09 14:25:02.593  8074  8113 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 14:25:02.604  1035  2009 W libprocessgroup: failed to open /acct/uid_10093/pid_7165/cgroup.procs: No such file or directory
09-09 14:25:02.620  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 14:25:02.621  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.622  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:25:02.629  8127  8127 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:25:02.650  8127  8127 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-09 14:25:02.685  8117  8117 D AndroidRuntime: 
09-09 14:25:02.685  8117  8117 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 14:25:02.689  8117  8117 D AndroidRuntime: CheckJNI is OFF
09-09 14:25:02.692  8127  8127 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-09 14:25:02.692  8127  8127 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-09 14:25:02.692  8127  8127 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-09 14:25:02.692  8127  8127 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-09 14:25:02.693  8127  8127 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-09 14:25:02.694  8127  8127 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-09 14:25:02.710  8127  8127 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-09 14:25:02.716  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:25:02.717  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:02.730  8127  8127 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:25:02.732  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:02.732  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:25:02.734  8127  8127 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-09 14:25:02.736  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:25:02.736  8127  8127 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-09 14:25:02.739  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:02.742  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:25:02.742  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:02.743  8127  8127 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 14:25:02.745  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 14:25:02.747  6819  6819 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 14:25:02.748  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:02.749  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:25:02.753  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:25:02.759  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:02.762  8074  8113 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:25:02.762  8074  8113 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 14:25:02.763  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:25:02.763  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:02.763  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:25:02.767  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 14:25:02.767  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:25:02.767  6819  6819 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:25:02.767  6819  6819 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 14:25:02.768  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 14:25:02.770  6819  6819 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:25:02.770  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 14:25:02.770  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:25:02.770  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:25:02.770  6819  6819 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:25:02.771  6819  6819 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 14:25:02.771  6819  6819 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 14:25:02.773  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:02.773  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:25:02.778  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:25:02.782  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:02.786  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:25:02.787  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:02.787  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:25:02.788  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:02.788  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:25:02.794  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:25:02.799  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:02.808  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:25:02.808  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:02.808  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:25:02.810  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:02.810  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:25:02.815  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:25:02.818  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:02.822  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:25:02.822  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:02.822  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:25:02.824  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:02.824  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 14:25:02.825  1035  8099 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-09 14:25:02.828  1035  8099 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 14:25:02.829  1035  8099 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 14:25:02.829  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:25:02.829  1035  8099 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 14:25:02.829  1035  8099 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 14:25:02.829  1035  8099 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 14:25:02.829  1035  8099 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 14:25:02.829  1035  8099 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 14:25:02.829  1035  8099 D DhcpStateMachine: RunningState
09-09 14:25:02.832  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:02.836  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:25:02.836  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:02.836  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:25:02.843  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:02.843  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 14:25:02.853  8074  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-09 14:25:02.853  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:25:02.855  8117  8117 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 14:25:02.857  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:02.863  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:25:02.863  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:02.867  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:25:02.870  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:02.870  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:25:02.871  1035  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-09 14:25:02.871  1035  1098 I ActivityManager: Killing 6588:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-09 14:25:02.912  1035  1947 I WindowState: WIN DEATH: Window{3b1291d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 14:25:02.913  1035  1543 D WifiService: Client connection lost with reason: 4
,09-09 14:25:02.919  1035  1947 D InputDispatcher: Window went away: Window{3b1291d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 14:25:02.929  8074  8113 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-09 14:25:02.937  8074  8113 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-09 14:25:02.938  8074  8113 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-09 14:25:02.938  8074  8113 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-09 14:25:02.939  8074  8113 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-09 14:25:02.939  8074  8113 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,09-09 14:25:02.941  8074  8113 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-09 14:25:02.943  8074  8113 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-09 14:25:03.085  1035  1098 I ActivityManager:   Force finishing activity ActivityRecord{10284e8d u0 com.test.thalitest/.MainActivity t6}
,09-09 14:25:03.124   344   357 E GBMv2   : DFP En is all cleared set to be enabled
,09-09 14:25:03.129  1035  1966 W ActivityManager: Spurious death for ProcessRecord{ffb111a 6588:com.test.thalitest/u0a118}, curProc for 6588: null
,09-09 14:25:03.130  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-09 14:25:03.139  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{10284e8d u0 com.test.thalitest/.MainActivity t6 f}
09-09 14:25:03.140  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{10284e8d u0 com.test.thalitest/.MainActivity t6 f}
,09-09 14:25:03.187  2031  2031 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,09-09 14:25:03.188  7610  7610 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-09 14:25:03.188  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 14:25:03.189  2465  2600 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 14:25:03.191  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-09 14:25:03.193  3868  3868 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-09 14:25:03.197  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:25:03.208  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:03.222  1035  1461 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 14:25:03.230  4632  4632 I art     : Explicit concurrent mark sweep GC freed 8186(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 550us total 77.180ms
,09-09 14:25:03.257  2089  2089 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-09 14:25:03.261  2089  2089 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-09 14:25:03.266  2089  2089 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-09 14:25:03.268  2089  2192 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,09-09 14:25:03.271  1967  1983 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-09 14:25:03.272  1967  1983 D SplitWindowPolicy: topRunningActivity=ActivityInfo{213ba5c1 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-09 14:25:03.273  1967  4011 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-09 14:25:03.273  1967  4011 D SplitWindowPolicy: topRunningActivity=ActivityInfo{72c9166 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-09 14:25:03.283  4522  4522 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-09 14:25:03.285  4522  4522 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-09 14:25:03.285  4522  4522 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-09 14:25:03.285  4522  4522 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-09 14:25:03.285  4522  4522 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:25:03.285  4522  4522 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:25:03.285  4522  4522 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:25:03.285  4522  4522 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:25:03.285  4522  4522 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:25:03.285  4522  4522 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:25:03.286  4522  4522 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:25:03.286  4522  4522 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-09 14:25:03.308  2089  2089 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-09 14:25:03.310  1929  1929 D ActionManagerService: notifyUserLog: 1000003
09-09 14:25:03.310  3868  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-09 14:25:03.314  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-09 14:25:03.317  2089  2089 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-09 14:25:03.318  1601  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 14:25:03.318  1601  1655 D KeyguardModel: createShortcutInfo...
09-09 14:25:03.321  2089  2089 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-09 14:25:03.324  2089  2089 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-09 14:25:03.329  1601  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 14:25:03.329  1601  1655 D KeyguardModel: createShortcutInfo...
09-09 14:25:03.335  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 14:25:03.335  1601  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:25:03.335  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 14:25:03.337  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 14:25:03.339  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:25:03.339  1601  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 14:25:03.339  1929  1929 D ActionManagerService: notifyUserLog: 1000004
,09-09 14:25:03.340  3868  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004),
09-09 14:25:03.340  2089  2089 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-09 14:25:03.343  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-09 14:25:03.345  1601  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 14:25:03.345  1601  1655 D KeyguardModel: createShortcutInfo...
09-09 14:25:03.352  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 14:25:03.352  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:25:03.353  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:25:03.353  1601  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 14:25:03.355  1601  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 14:25:03.355  1601  1655 D KeyguardModel: createShortcutInfo...
09-09 14:25:03.356  1035  1965 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:25:03.359  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-09 14:25:03.362  1601  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:25:03.362  1601  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 14:25:03.363  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 14:25:03.363  1601  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 14:25:03.366  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
09-09 14:25:03.366  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
09-09 14:25:03.367  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:25:03.367  1601  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 14:25:03.368  3868  3884 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , create_time: 1430832262123
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , expire_time: 0
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , display: false
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , animation: false }
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , create_time: 1430832262287
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , expire_time: 0
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , display: false
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , animation: false }
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , create_time: 1473420113195
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , expire_time: 0
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , display: false
09-09 14:25:03.371  2089  2089 I GBoardWebViewUtils: , animation: false }
,09-09 14:25:03.373  1601  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 14:25:03.373  1601  1655 D KeyguardModel: createShortcutInfo...
09-09 14:25:03.380  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:25:03.380  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:03.381  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:25:03.396  1035  1035 D administrator: Handling package changes for user 0
,09-09 14:25:03.429  2089  8200 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-09 14:25:03.440  2089  2089 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 14:25:03.441  2089  2089 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,09-09 14:25:03.443  1035  1984 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-09 14:25:03.444  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 14:25:03.444  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 14:25:03.444  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 14:25:03.444  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 14:25:03.444  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 14:25:03.444  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:25:03.444  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 14:25:03.444  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 14:25:03.444  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 14:25:03.445  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:25:03.445  7610  7610 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 14:25:03.446  1035  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
09-09 14:25:03.446  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-09 14:25:03.446  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 14:25:03.452  1895  1895 D SplitUIManager: split_name #11 / not available #0
09-09 14:25:03.453  1895  1895 D SplitUIService: removed split : 
09-09 14:25:03.456  1601  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 14:25:03.456  1601  1655 D KeyguardModel: createShortcutInfo...
,09-09 14:25:03.458  1601  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 14:25:03.458  1601  1655 D KeyguardModel: createShortcutInfo...
09-09 14:25:03.459  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:25:03.459  1601  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 14:25:03.460  1601  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 14:25:03.460  1601  1655 D KeyguardModel: createShortcutInfo...
09-09 14:25:03.462  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:25:03.462  1601  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 14:25:03.467  1601  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 14:25:03.467  1601  1655 D KeyguardModel: createShortcutInfo...
09-09 14:25:03.470  1601  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:25:03.470  1601  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-09 14:25:03.474  1601  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 14:25:03.474  1601  1655 D KeyguardModel: createShortcutInfo...
09-09 14:25:03.475  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.489  8028  8028 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 14:25:03.497  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:25:03.498  2089  2104 I art     : Background sticky concurrent mark sweep GC freed 2489(140KB) AllocSpace objects, 3(176KB) LOS objects, 0% free, 80MB/80MB, paused 6ms total 14.484ms
09-09 14:25:03.498  1895  1895 D SplitUIManager: split_name #11 / not available #0
09-09 14:25:03.498  1895  1895 I SplitUIService: split app #11
09-09 14:25:03.501  8028  8028 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:25:03.506  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:25:03.507  2089  2089 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-09 14:25:03.511  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-09 14:25:03.511  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 14:25:03.511  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 14:25:03.512  1035  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-09 14:25:03.517  1601  1601 D KeyguardModel: handleShortcutListChanged...
09-09 14:25:03.517  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 14:25:03.518  1035  1984 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:25:03.540  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:25:03.545  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:25:03.546  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:03.546  8127  8127 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 14:25:03.547  8127  8127 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 14:25:03.547  8127  8127 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 14:25:03.549  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.549  8074  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:25:03.552  8028  8028 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 14:25:03.554  8028  8028 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:25:03.556  6819  6819 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:25:03.561  6819  6819 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:25:03.565  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:25:03.566  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:25:03.566  8127  8127 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-09 14:25:03.566  8127  8127 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-09 14:25:03.567  8127  8127 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 14:25:03.568  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.597  2089  2089 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-09 14:25:03.600  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:25:03.601  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-09 14:25:03.602  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-09 14:25:03.603  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-09 14:25:03.604  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-09 14:25:03.618  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5af1e11 u0 com.lge.launcher2/.Launcher t5} time:141049
,09-09 14:25:03.626  2089  2089 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-09 14:25:03.626  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:25:03.635  2089  2314 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-09 14:25:03.635  2089  2314 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-09 14:25:03.637  8127  8127 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-09 14:25:03.637  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 14:25:03.637  8127  8127 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-09 14:25:03.640  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-09 14:25:03.641  2089  2089 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 14:25:03.641  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:25:03.648  2089  2089 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,09-09 14:25:03.649  2669  2669 D [Concierge]Service: onStartCommand(). Type : 8
09-09 14:25:03.649  2669  2669 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-09 14:25:03.650  2669  2669 D [Concierge]Service: Update widget ID : 11
09-09 14:25:03.651  2089  2089 D [Concierge]WidgetView: change position of spinner
09-09 14:25:03.652  2669  2669 D [Concierge]Service: onStartCommand(). Type : 0
09-09 14:25:03.652  2089  2089 I [Concierge]WidgetView: initWebView(). Time : 1473423903652
09-09 14:25:03.661  8127  8127 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:25:03.661  8127  8127 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:25:03.665  8127  8127 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-09 14:25:03.666  8127  8127 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
09-09 14:25:03.666  8127  8127 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
09-09 14:25:03.666  8127  8127 V SoundPool: doLoad: loading sample sampleID=1
09-09 14:25:03.666  8127  8210 V SoundPool: Start decode
09-09 14:25:03.666  8127  8210 V MediaPlayer[Native]: decode(30, 10857164, 17813)
09-09 14:25:03.667  2089  2089 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 217032569
09-09 14:25:03.667  2089  2089 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-09 14:25:03.667  2089  2089 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 14:25:03.668   316   316 V MediaPlayerService: decode(23, 10857164, 17813)
09-09 14:25:03.669   316   316 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-09 14:25:03.669   316   316 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-09 14:25:03.669   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-09 14:25:03.669   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-09 14:25:03.669   316   316 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-09 14:25:03.669   316   316 V MediaPlayerService: player type = 3
09-09 14:25:03.669   316   316 V AwesomePlayer: AwesomePlayer create()
09-09 14:25:03.669   316   316 V AwesomePlayer: reset_l() 
09-09 14:25:03.669   316   316 V AwesomePlayer: cancelPlayerEvents
09-09 14:25:03.669   316   316 V AwesomePlayer: setAudioSink() 
09-09 14:25:03.669   316   316 V AwesomePlayer: reset_l() 
09-09 14:25:03.669   316   316 V AudioCache: notify(0xb5474a00, 8, 0, 0)
09-09 14:25:03.669   316   316 V AudioCache: ignored
09-09 14:25:03.669   316   316 V AwesomePlayer: cancelPlayerEvents
09-09 14:25:03.669   316   316 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-09 14:25:03.669   316   316 V AwesomePlayer: setDataSource_l dataSource
09-09 14:25:03.669   316   316 V LGParserOSAL: SniffLGParser start
09-09 14:25:03.669   316   316 V LGParserOSAL: MainType:5, SubType=0
09-09 14:25:03.669   316   316 V LGParserOSAL: #### check Mime : application/ogg
09-09 14:25:03.669   316   316 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-09 14:25:03.669   316   316 E MediaExtractor: Use LGExtractor :application/ogg 
09-09 14:25:03.670  2089  2089 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@29f523e
09-09 14:25:03.670  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-09 14:25:03.671  2089  2089 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 14:25:03.671  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:25:03.675  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:25:03.677  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-09 14:25:03.677  1035  1123 I art     : Explicit concurrent mark sweep GC freed 84150(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 2.149ms total 306.680ms
09-09 14:25:03.677  2089  2089 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-09 14:25:03.677  2089  2089 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-09 14:25:03.678  2089  2089 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473423790519, New one : 1473,423903652
09-09 14:25:03.678  2089  2089 D [Concierge]WidgetView: Unregister all receivers
09-09 14:25:03.678  2089  2089 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-09 14:25:03.679  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:25:03.683  8127  8127 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 14:25:03.683  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-09 14:25:03.684  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-09 14:25:03.684  8127  8127 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-09 14:25:03.685  7706  7706 D UEI.SmartControl: QS Service created
09-09 14:25:03.685  8127  8127 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 14:25:03.685  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 14:25:03.685  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-09 14:25:03.686  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-09 14:25:03.687  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-09 14:25:03.691  8127  8127 V LGMDMManager: Create singleton instance
09-09 14:25:03.691  7706  7706 I UEI.SmartControl: Service initServices...
09-09 14:25:03.691  7706  7706 D UEI.SmartControl: QS start get config
09-09 14:25:03.699  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:25:03.699  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-09 14:25:03.711   316   316 V LGParserOSAL: supported mime: application/ogg
09-09 14:25:03.711   316   316 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-09 14:25:03.711   316   316 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-09 14:25:03.711   316   316 V AwesomePlayer: mBitrate = -1 bits/sec
09-09 14:25:03.711   316   316 V AwesomePlayer: AudioTrack Setting
09-09 14:25:03.711   316   316 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-09 14:25:03.711   316   316 V AwesomePlayer: setAudioSource() 
09-09 14:25:03.711   316   316 V MediaPlayerService: prepare
09-09 14:25:03.711   316   316 V AwesomePlayer: prepareAsync_l() 
09-09 14:25:03.711   316   316 V MediaPlayerService: wait for prepare
09-09 14:25:03.712   316  8211 V AwesomePlayer: onPrepareAsyncEvent() 
09-09 14:25:03.712   316  8211 V AwesomePlayer: initAudioDecoder() 
09-09 14:25:03.712   316  8211 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 14:25:03.712   316  8211 V AudioSystem: isOffloadSupported()
09-09 14:25:03.712   316  8211 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 14:25:03.712   316  8211 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 14:25:03.712   316  8211 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 14:25:03.712   316  8211 V AwesomePlayer: getUseOffload() = 0 
09-09 14:25:03.712   316  8211 V OMXCodec: OMXCodec::Create
09-09 14:25:03.712   316  8211 V OMXCodec: findMatchingCodecs()
09-09 14:25:03.712   316  8211 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-09 14:25:03.712   316  8211 V OMXCodec: matchingCodecs.size()=1
09-09 14:25:03.712   316  8211 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-09 14:25:03.715   316  8211 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-09 14:25:03.715   316  8211 V LGCodecAdapter: LG Codec Adapter start
09-09 14:25:03.715   316  8211 V OMXCodec: OMXCodec Createtor
09-09 14:25:03.715   316  8211 V OMXCodec: setComponentRole
09-09 14:25:03.716   316  8211 V OMXCodec: configureCodec protected=0
09-09 14:25:03.716   316  8211 V LGCodecAdapter: called getLGCodecSpecificData
09-09 14:25:03.716   316  8211 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-09 14:25:03.716   316  8211 V LGCodecOSAL: Called LGconfigureCodecMETA
09-09 14:25:03.716   316  8211 V LGCodecOSAL: Called LGconfigureCodecMSG
09-09 14:25:03.716   316  8211 V LGCodecOSAL: Not support LGCodec
09-09 14:25:03.716   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 14:25:03.716   316  8211 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-09 14:25:03.716   316  8211 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-09 14:25:03.716   316  8211 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-09 14:25:03.716   316  8211 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 14:25:03.716   316  8211 V AudioSystem: isOffloadSupported()
09-09 14:25:03.716   316  8211 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 14:25:03.716   316  8211 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 14:25:03.716   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-09 14:25:03.716   316  8211 V OMXCodec: init()
09-09 14:25:03.719   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-09 14:25:03.719   316  8211 V OMXCodec: allocateBuffers
09-09 14:25:03.719   316  8211 V OMXCodec: allocateBuffersOnPort portIndex=0
09-09 14:25:03.719   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-09 14:25:03.719   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-09 14:25:03.719   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-09 14:25:03.720   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-09 14:25:03.720   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
09-09 14:25:03.720   316  8211 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 14:25:03.720   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 14:25:03.720   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-09 14:25:03.720   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
09-09 14:25:03.720   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc060 on output port
09-09 14:25:03.720   316  8211 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc0b0 on output port
09-09 14:25:03.720   316  8211 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 14:25:03.720   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 14:25:03.720   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 14:25:03.720   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-09 14:25:03.720   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-09 14:25:03.720   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-09 14:25:03.720   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
09-09 14:25:03.725   316  8211 V OMXCodec: init() mAsyncCompletion wait free! 
09-09 14:25:03.726   316  8211 V AwesomePlayer: finishAsyncPrepare_l() 
09-09 14:25:03.726   316  8211 V AudioCache: notify(0xb5474a00, 5, 0, 0)
09-09 14:25:03.726   316  8211 V AudioCache: ignored
09-09 14:25:03.726   316  8211 V AudioCache: notify(0xb5474a00, 1, 0, 0)
09-09 14:25:03.726   316  8211 V AudioCache: prepared
,09-09 14:25:03.732   316   316 V AudioCache: wait - success
09-09 14:25:03.732   316   316 V MediaPlayerService: start
,09-09 14:25:03.732   316   316 V AwesomePlayer: play_l() 
09-09 14:25:03.732   316   316 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-09 14:25:03.732   316   316 V AwesomePlayer: createAudioPlayer_l
09-09 14:25:03.732   316   316 V AwesomePlayer: seekAudioIfNecessary_l() 
09-09 14:25:03.732   316   316 V AwesomePlayer: startAudioPlayer_l() 
09-09 14:25:03.732   316   316 D AudioPlayer: start of Playback, useOffload 0
09-09 14:25:03.732   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 14:25:03.732   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044786272
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044786352
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-09 14:25:03.734   316  8213 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc060 on output port
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-09 14:25:03.734   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-09 14:25:03.735   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-09 14:25:03.735   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-09 14:25:03.735   316   316 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-09 14:25:03.738   316   316 V AudioCache: notify(0xb5474a00, 6, 0, 0)
09-09 14:25:03.738   316   316 V AudioCache: ignored
09-09 14:25:03.738   316   316 V MediaPlayerService: wait for playback complete
09-09 14:25:03.739   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.739   316  8214 V AudioCache: memcpy(0xac102000, 0xb1507000, 4096)
09-09 14:25:03.740   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.740   316  8214 V AudioCache: memcpy(0xac103000, 0xb1507000, 4096)
09-09 14:25:03.741   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.741   316  8214 V AudioCache: memcpy(0xac104000, 0xb1507000, 4096)
09-09 14:25:03.741   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.741   316  8214 V AudioCache: memcpy(0xac105000, 0xb1507000, 4096)
09-09 14:25:03.741   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.741   316  8214 V AudioCache: memcpy(0xac106000, 0xb1507000, 4096)
09-09 14:25:03.742   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.742   316  8214 V AudioCache: memcpy(0xac107000, 0xb1507000, 4096)
09-09 14:25:03.742   3,16  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.742   316  8214 V AudioCache: memcpy(0xac108000, 0xb1507000, 4096)
,09-09 14:25:03.742   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.742   316  8214 V AudioCache: memcpy(0xac109000, 0xb1507000, 4096)
09-09 14:25:03.743   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.743   316  8214 V AudioCache: memcpy(0xac10a000, 0xb1507000, 4096)
09-09 14:25:03.743   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.743   316  8214 V AudioCache: memcpy(0xac10b000, 0xb1507000, 4096)
09-09 14:25:03.744   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.744   316  8214 V AudioCache: memcpy(0xac10c000, 0xb1507000, 4096)
09-09 14:25:03.745   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.745   316  8214 V AudioCache: memcpy(0xac10d000, 0xb1507000, 4096)
09-09 14:25:03.745   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.745   316  8214 V AudioCache: memcpy(0xac10e000, 0xb1507000, 4096)
09-09 14:25:03.745  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 14:25:03.745   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.745   316  8214 V AudioCache: memcpy(0xac10f000, 0xb1507000, 4096)
09-09 14:25:03.746   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.746   316  8214 V AudioCache: memcpy(0xac110000, 0xb1507000, 4096)
09-09 14:25:03.746   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.746   316  8214 V AudioCache: memcpy(0xac111000, 0xb1507000, 4096)
09-09 14:25:03.746   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.746   316  8214 V AudioCache: memcpy(0xac112000, 0xb1507000, 4096)
09-09 14:25:03.747   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.747   316  8214 V AudioCache: memcpy(0xac113000, 0xb1507000, 4096)
09-09 14:25:03.747   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.747   316  8214 V AudioCache: memcpy(0xac114000, 0xb1507000, 4096)
09-09 14:25:03.747   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.747   316  8214 V AudioCache: memcpy(0xac115000, 0xb1507000, 4096)
09-09 14:25:03.748   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.748   316  8214 V AudioCache: memcpy(0xac116000, 0xb1507000, 4096)
09-09 14:25:03.748   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.748   316  8214 V AudioCache: memcpy(0xac117000, 0xb1507000, 4096)
09-09 14:25:03.759   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.759   316  8214 V AudioCache: memcpy(0xac118000, 0xb1507000, 4096)
09-09 14:25:03.760   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.760   316  8214 V AudioCache: memcpy(0xac119000, 0xb1507000, 4096)
09-09 14:25:03.760   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.760   316  8214 V AudioCache: memcpy(0xac11a000, 0xb1507000, 4096)
09-09 14:25:03.761   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.761   316  8214 V AudioCache: memcpy(0xac11b000, 0xb1507000, 4096)
09-09 14:25:03.761   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.761   316  8214 V AudioCache: memcpy(0xac11c000, 0xb1507000, 4096)
09-09 14:25:03.761   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.761   316  8214 V AudioCache: memcpy(0xac11d000, 0xb1507000, 4096)
09-09 14:25:03.762   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.762   316  8214 V AudioCache: memcpy(0xac11e000, 0xb1507000, 4096)
09-09 14:25:03.762   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.762   316  8214 V AudioCache: memcpy(0xac11f000, 0xb1507000, 4096)
09-09 14:25:03.762   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.762   316  8214 V AudioCache: memcpy(0xac120000, 0xb1507000, 4096)
09-09 14:25:03.763   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.763   316  8214 V AudioCache: memcpy(0xac121000, 0xb1507000, 4096)
09-09 14:25:03.763   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.763   316  8214 V AudioCache: memcpy(0xac122000, 0xb1507000, 4096)
09-09 14:,25:03.763   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.763   316  8214 V AudioCache: memcpy(0xac123000, 0xb1507000, 4096)
09-09 14:25:03.764   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.764   316  8214 V AudioCache: memcpy(0xac124000, 0xb1507000, 4096)
09-09 14:25:03.764   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.764   316  8214 V AudioCache: memcpy(0xac125000, 0xb1507000, 4096)
,09-09 14:25:03.764   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.764   316  8214 V AudioCache: memcpy(0xac126000, 0xb1507000, 4096)
09-09 14:25:03.765   316  8214 V AudioCache: write(0xb1507000, 4096)
,09-09 14:25:03.765   316  8214 V AudioCache: memcpy(0xac127000, 0xb1507000, 4096)
09-09 14:25:03.765   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.765   316  8214 V AudioCache: memcpy(0xac128000, 0xb1507000, 4096)
09-09 14:25:03.765   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.765   316  8214 V AudioCache: memcpy(0xac129000, 0xb1507000, 4096)
09-09 14:25:03.766   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.766   316  8214 V AudioCache: memcpy(0xac12a000, 0xb1507000, 4096)
09-09 14:25:03.766   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.766   316  8214 V AudioCache: memcpy(0xac12b000, 0xb1507000, 4096)
09-09 14:25:03.766   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.766   316  8214 V AudioCache: memcpy(0xac12c000, 0xb1507000, 4096)
09-09 14:25:03.767   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.767   316  8214 V AudioCache: memcpy(0xac12d000, 0xb1507000, 4096)
09-09 14:25:03.767   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.767   316  8214 V AudioCache: memcpy(0xac12e000, 0xb1507000, 4096)
,09-09 14:25:03.767   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.767   316  8214 V AudioCache: memcpy(0xac12f000, 0xb1507000, 4096)
09-09 14:25:03.768   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.768   316  8214 V AudioCache: memcpy(0xac130000, 0xb1507000, 4096)
09-09 14:25:03.768   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-09 14:25:03.768   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.768   316  8214 V AudioCache: memcpy(0xac131000, 0xb1507000, 4096)
09-09 14:25:03.768   316  8214 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 14:25:03.768   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.768   316  8214 V AudioCache: memcpy(0xac132000, 0xb1507000, 4096)
09-09 14:25:03.768   316  8214 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 14:25:03.768   316  8214 V AudioCache: write(0xb1507000, 4096)
09-09 14:25:03.768   316  8214 V AudioCache: memcpy(0xac133000, 0xb1507000, 4096)
09-09 14:25:03.768   316  8214 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 14:25:03.768   316  8214 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 14:25:03.768   316  8214 V AwesomePlayer: postAudioEOS() 
09-09 14:25:03.768   316  8214 V AudioCache: write(0xb1507000, 280)
09-09 14:25:03.768   316  8214 V AudioCache: memcpy(0xac134000, 0xb1507000, 280)
09-09 14:25:03.770   316  8211 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-09 14:25:03.770   316  8211 V AwesomePlayer: onStreamDone
09-09 14:25:03.770   316  8211 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-09 14:25:03.770   316  8211 V AudioCache: notify(0xb5474a00, 2, 0, 0)
09-09 14:25:03.770   316  8211 V AudioCache: playback complete
09-09 14:25:03.770   316  8211 V AwesomePlayer: pause_l() 
09-09 14:25:03.770   316  8211 V AudioCache: notify(0xb5474a00, 7, 0, 0)
09-09 14:25:03.770   316  8211 V AudioCache: ignored
09-09 14:25:03.770   316  8211 V AwesomePlayer: cancelPlayerEvents
09-09 14:25:03.770   316   316 V AudioCache: wait - success
09-09 14:25:03.770   316   316 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-09 14:25:03.770   316  8211 D AudioPlayer: Pause Playback at 1068125
09-09 14:25:03.770   316   316 V AwesomePlayer: reset_l() 
09-09 14:25:03.770   316   316 V AudioCache: notify(0xb5474a00, 8, 0, 0)
09-09 14:25:03.770   316   316 V AudioCache: ignored
09-09 14:25:03.770   316   316 V AwesomePlayer: cancelPlayerEvents
09-09 14:25:03.770   316   316 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-09 14:25:03.770   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-09 14:25:03.770   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-09 14:25:03.770   316   316 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-09 14:25:03.770   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 14:25:03.770  1035  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-09 14:25:03.770   316  8213 V OM,XCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
09-09 14:25:03.770   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-09 14:25:03.771  1035  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bc060 on port 1
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-09 14:25:03.771   316  8213 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-09 14:25:03.771  1035  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:03.771  1035  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:03.772  1035  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:03.772  1035  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:25:03.772  1035  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-09 14:25:03.772  1035  1544 D ConnectivityService: identical MTU - not setting
09-09 14:25:03.773  1035  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 14:25:03.773  1035  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 14:25:03.773   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 14:25:03.773   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-09 14:25:03.773  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:25:03.773  1035  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:25:03.773   316   316 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-09 14:25:03.773  1035  1544 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:25:03.773   316   316 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-09 14:25:03.774   316   316 D AudioPlayer: AudioPlayer releasing audio source
09-09 14:25:03.774   316   316 D AudioPlayer: AudioPlayer done releasing audio source
09-09 14:25:03.774   316   316 V AwesomePlayer: reset_l() 
09-09 14:25:03.774   316   316 V AwesomePlayer: cancelPlayerEvents
09-09 14:25:03.774   316   316 V AwesomePlayer: ~AwesomePlayer call
09-09 14:25:03.774  1601  1811 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 14:25:03.774   316   316 V Awesome,Player: reset_l() 
09-09 14:25:03.774   316   316 V AwesomePlayer: cancelPlayerEvents
09-09 14:25:03.774  8127  8210 V SoundPool: close(30)
09-09 14:25:03.774  8127  8210 V SoundPool: pointer = 0x9ffe6000, size = 205080, sampleRate = 48000, numChannels = 2
09-09 14:25:03.781  2089  2089 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 14:25:03.787  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 14:25:03.788  2089  2089 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-09 14:25:03.788  2089  2089 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-09 14:25:03.789  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-09 14:25:03.790  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2222
09-09 14:25:03.790  2089  2089 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 14:25:03.793  2089  2089 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:25:03.793  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.794  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.796  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.798  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.801  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.805  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.807  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:25:03.810  8074  8074 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-09 14:25:03.810  2089  2089 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3abb923a time:141241
09-09 14:25:03.812  1839  1839 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-09 14:25:03.818  2219  2219 I ConfigService: onCreate
09-09 14:25:03.818  2219  2219 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-09 14:25:03.821  1839  1839 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-09 14:25:03.822  2219  2219 I ConfigService: onBind returning update interface
09-09 14:25:03.823  2219  2219 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-09 14:25:03.823  2219  2219 I ConfigService: onBind returning config service
09-09 14:25:03.839  2219  2219 I ConfigService: onDestroy
,09-09 14:25:03.843  1839  8216 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-09 14:25:03.843  8117  8117 D AndroidRuntime: Shutting down VM
09-09 14:25:03.865  1839  8223 I PeopleContactsSync: CP2 sync disabled
,09-09 14:25:03.868  1839  4765 I Icing   : doRemovePackageData com.test.thalitest
09-09 14:25:03.870  5987  8222 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-09 14:25:03.882  1839  8221 W GmsApplication: Using Auth Proxy for data requests.
,09-09 14:25:03.887  1839  8221 W GmsApplication: Using Auth Proxy for data requests.
09-09 14:25:03.895  7009  7009 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-09 14:25:03.905  2202  8225 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 14:25:03.935  1035  1984 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8227 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 14:25:03.974  2219  2236 I art     : Explicit concurrent mark sweep GC freed 6137(368KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 595us total 15.917ms
,09-09 14:25:03.980  8227  8227 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:25:03.980  8227  8227 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:25:03.982  8227  8227 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 14:25:03.982  8227  8227 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 14:25:04.007  2089  2089 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-09 14:25:04.033  8227  8227 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 14:25:04.042  8227  8227 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-09 14:25:04.044  2089  2950 I GBoardtInterface: onReloaded()
,09-09 14:25:04.047  2089  2089 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-09 14:25:04.048  3868  3884 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 14:25:04.055  3868  3883 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 14:25:04.068  8227  8227 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 14:25:04.074  7706  7706 I UEI.SmartControl: Supports setup maps: true
09-09 14:25:04.076  7706  7706 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 14:25:04.076  7706  7706 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 14:25:04.076  7706  7706 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 14:25:04.076  7706  7706 I UEI.SmartControl: ### init IR Blaster...
09-09 14:25:04.079  7706  7706 D serial_port: Configuring serial port
09-09 14:25:04.080  7706  7706 E UEI.SmartControl: UEIBLaster setting for 616
09-09 14:25:04.080  7706  7706 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 14:25:04.080  7706  7706 I UEI.SmartControl: configuring settings for MAXQ616
09-09 14:25:04.080  7706  7706 I UEI.SmartControl: Get version...
09-09 14:25:04.082  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8247 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-09 14:25:04.089  1929  1929 D ActionManagerService: notifyUserLog: 1000001
09-09 14:25:04.090  3868  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 14:25:04.090  3868  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 14:25:04.092  1929  1929 D ActionManagerService: notifyUserLog: 1000001
09-09 14:25:04.093  3868  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 14:25:04.093  3868  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 14:25:04.093  3868  4514 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-09 14:25:04.093  3868  4514 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-09 14:25:04.094  3868  3884 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-09 14:25:04.096  2089  2089 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-09 14:25:04.096  2089  2089 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-09 14:25:04.097  7706  8249 D UEI.SmartControl: serial port data available: 21
09-09 14:25:04.098  2089  2089 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-09 14:25:04.098  2089  2089 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 14:25:04.099  2089  2089 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-09 14:25:04.099  2089  2089 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,09-09 14:25:04.109  8227  8227 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 14:25:04.109  8227  8227 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 14:25:04.123  7706  7706 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 14:25:04.123  7706  7706 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 14:25:04.123  7706  7706 I UEI.SmartControl: QS saving settings...
,09-09 14:25:04.139  7706  7706 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 14:25:04.155  7706  8249 D UEI.SmartControl: serial port data available: 4
,09-09 14:25:04.163  8227  8227 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-09 14:25:04.168  7728  7728 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
09-09 14:25:04.169  1035  1947 I ActivityManager: Killing 7213:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-09 14:25:04.182  7706  8273 I UEI.SmartControl: Device manager: loading config....
09-09 14:25:04.182  7706  7706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 14:25:04.182  7706  8273 D UEI.SmartControl: ----------- loading internal config...
,09-09 14:25:04.185  7706  8273 E UEI.SmartControl: Loading SETTINGS...
09-09 14:25:04.185  7706  8273 W FileUtils: Failed to chmod(/data/data/com.uei.lg.quicksetsdk.maxq616/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
09-09 14:25:04.185  7706  8273 W System.err: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/data: open failed: EROFS (Read-only file system)
09-09 14:25:04.186  7706  8273 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 14:25:04.186  7706  8273 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,09-09 14:25:04.186  7706  8273 W System.err: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
09-09 14:25:04.186  7706  8273 W System.err: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
09-09 14:25:04.186  7706  8273 W System.err: 	at com.uei.control.core.f.e(Unknown Source)
09-09 14:25:04.186  7706  8273 W System.err: 	at com.uei.control.core.f.l(Unknown Source)
09-09 14:25:04.186  7706  8273 W System.err: 	at com.uei.control.core.f.c(Unknown Source)
09-09 14:25:04.186  7706  8273 W System.err: 	at com.uei.control.i.run(Unknown Source)
09-09 14:25:04.186  7706  8273 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:04.186  7706  8273 W System.err: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:04.186  7706  8273 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:04.186  7706  8273 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 14:25:04.186  7706  8273 W System.err: 	... 7 more
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/data: open failed: EROFS (Read-only file system)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.e(Unknown Source)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.l(Unknown Source)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.c(Unknown Source)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at com.uei.control.i.run(Unknown Source)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	... 7 more
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/data: open failed: EROFS (Read-only file system)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.e(Unknown Source)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.l(Unknown Source)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.c(Unknown Source)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at com.uei.control.i.run(Unknown Source)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.,java:442)
09-09 14:25:04.186  7706  8273 E UEI.SmartControl: 	... 7 more
09-09 14:25:04.188  7706  8273 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 14:25:04.188  7706  8273 W System.err: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_assets/brands.xml: open failed: EROFS (Read-only file system)
09-09 14:25:04.188  7706  8273 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 14:25:04.188  7706  8273 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:04.188  7706  8273 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:25:04.188  7706  8273 W System.err: 	at com.uei.control.core.f.d(Unknown Source)
09-09 14:25:04.188  7706  8273 W System.err: 	at com.uei.control.core.f.c(Unknown Source)
09-09 14:25:04.188  7706  8273 W System.err: 	at com.uei.control.i.run(Unknown Source)
09-09 14:25:04.188  7706  8273 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:04.188  7706  8273 W System.err: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:04.188  7706  8273 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:04.188  7706  8273 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 14:25:04.188  7706  8273 W System.err: 	... 5 more
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_assets/brands.xml: open failed: EROFS (Read-only file system)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.d(Unknown Source)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.c(Unknown Source)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at com.uei.control.i.run(Unknown Source)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	... 5 more
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_assets/brands.xml: open failed: EROFS (Read-only file system)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.d(Unknown Source)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at com.uei.control.core.f.c(Unknown Source)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at com.uei.control.i.run(Unknown Source)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 14:25:04.189  7706  8273 E UEI.SmartControl: 	... 5 more
09-09 14:25:04.201  7706  8272 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 14:25:04.201  7706  8272 D UEI.SmartControl: -----service ready thread exits
,09-09 14:25:04.252  1035  1705 W libprocessgroup: failed to open /acct/uid_10005/pid_7213/cgroup.procs: No such file or directory
09-09 14:25:04.252  2031  2031 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-09 14:25:04.252  2031  2031 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...

```
