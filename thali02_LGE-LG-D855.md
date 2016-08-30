#### Test 83243049e1001da_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 12:37:41.511  6558  6558 D DocsApplication: Installing DEX configuration.
08-30 12:37:41.530  6558  6558 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-30 12:37:41.534  6558  6558 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3870d019 com.google.android.apps.docs}
08-30 12:37:41.557  6558  6558 D TAG     : onCreate()
08-30 12:37:41.588  6558  6558 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 12:37:42.120   340   430 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 12:37:42.122  3238  6584 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 12:37:42.380  1820  4775 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-30 12:37:42.472  1820  4775 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 12:37:42.564  1820  4775 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-30 12:37:42.638  6586  6586 D AndroidRuntime: 
08-30 12:37:42.638  6586  6586 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 12:37:42.642  6586  6586 D AndroidRuntime: CheckJNI is OFF
08-30 12:37:42.778  6558  6558 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:37:42.778  6558  6558 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 12:37:42.866  6586  6586 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 12:37:42.876  1036  1578 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 12:37:42.889  1945  2560 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 12:37:42.893  1036  1578 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 12:37:42.894  1036  1578 D ActivityManager: setTaskToReturnTo : TaskRecord{177c947 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 12:37:42.894  1036  1578 D ActivityManager: setTaskToReturnTo : TaskRecord{177c947 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 12:37:42.895  1036  1578 D WindowStateEx: AppWindowTokenEx init.. 
08-30 12:37:42.896   346   363 E GBMv2   : DFP En is all cleared set to be enabled
08-30 12:37:42.923  1036  1578 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6615 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 12:37:42.925  6586  6586 D AndroidRuntime: Shutting down VM
08-30 12:37:42.940  6110  6110 I LockScreenSettings: New app installed broadcast received ..
08-30 12:37:42.947  6110  6110 I LockScreenSettings: Number of installed packages  1
08-30 12:37:42.959  6558  6558 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-30 12:37:42.995  1945  2560 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 12:37:42.995  1945  2560 D SplitWindowPolicy: topRunningActivity=ActivityInfo{22567be5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 12:37:42.996  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 12:37:42.996  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{30b0b6ba co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 12:37:43.020  1036  1999 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:37:43.082  1036  1618 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6641 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 12:37:43.088  6615  6615 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-30 12:37:43.147  6641  6641 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-30 12:37:43.147  6641  6641 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-30 12:37:43.171  6615  6615 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 12:37:43.195  1036  1578 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6658 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-30 12:37:43.196  1036  1578 I ActivityManager: Killing 5462:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-30 12:37:43.232  1036  1052 W libprocessgroup: failed to open /acct/uid_10005/pid_5462/cgroup.procs: No such file or directory
,08-30 12:37:43.244  6615  6615 I LibraryLoader: Loading: webviewchromium
,08-30 12:37:43.247  6615  6615 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4333-4337)
08-30 12:37:43.248  6615  6615 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:37:43.272  6615  6615 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f0e03db}
,08-30 12:37:43.273  6615  6615 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:37:43.273  6615  6615 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:37:43.282  6615  6615 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 12:37:43.283  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:43.299  6615  6615 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 12:37:43.299  6615  6615 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 12:37:43.300   328  1784 V AudioPolicyService: registerClient() client 0xb0410620, uid 10118
08-30 12:37:43.300  6615  6615 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 12:37:43.305  1036  1118 D BluetoothManagerService: Message: 20
08-30 12:37:43.305  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7007a6a:true
08-30 12:37:43.318  6615  6615 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:37:43.318  6615  6615 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:37:43.318  6615  6615 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:37:43.318  6615  6615 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:37:43.318  6615  6615 I Adreno-EGL: Remote Branch: 
08-30 12:37:43.318  6615  6615 I Adreno-EGL: Local Patches: 
08-30 12:37:43.318  6615  6615 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:37:43.325  6658  6658 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-30 12:37:43.348  6658  6658 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 12:37:43.351  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-30 12:37:43.380  6615  6687 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 12:37:43.384  6615  6615 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 12:37:43.393  6431  6431 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-30 12:37:43.396  1036  1999 I ActivityManager: Killing 5850:com.google.android.talk/u0a72 (adj 15): empty #17
08-30 12:37:43.404  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:43.409  6615  6615 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 12:37:43.412  6615  6615 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 12:37:43.415  6615  6615 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 12:37:43.415  6615  6615 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-30 12:37:43.428  6615  6615 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 12:37:43.443  1036  1051 W libprocessgroup: failed to open /acct/uid_10072/pid_5850/cgroup.procs: No such file or directory
,08-30 12:37:43.447  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:37:43.447  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:43.488  6615  6700 D OpenGLRenderer: Render dirty regions requested: true
08-30 12:37:43.489  6615  6700 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 12:37:43.494  6615  6700 D OpenGLRenderer: Enabling debug mode 0
08-30 12:37:43.495  1036  1103 W ActivityManager: Activity pause timeout for ActivityRecord{133e8574 u0 com.test.thalitest/.MainActivity t6}
,08-30 12:37:43.507  6615  6615 D Atlas   : Validating map...
,08-30 12:37:43.515  1036  2054 D SplitWindow: check instance of lgWin Window{20a65ec3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:37:43.562  6615  6698 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:37:43.562  6615  6698 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:37:43.643  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +649ms (total +747ms)
08-30 12:37:43.644  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{133e8574 u0 com.test.thalitest/.MainActivity t6} time:104734
,08-30 12:37:43.646  6615  6615 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6aff866 time:104736
08-30 12:37:43.775  6615  6615 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 12:37:43.775  6615  6615 I chromium: 
,08-30 12:37:43.818  6615  6615 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:37:43.976  6615  6716 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435155968
,08-30 12:37:43.993  6615  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:37:43.993  6615  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:37:43.993  6615  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:37:43.993  6615  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:37:43.993  6615  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 12:37:43.993  6615  6716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c40704a added. We now have 1 listener(s)
08-30 12:37:44.002  1036  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:37:44.005  6615  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-30 12:37:44.008  6615  6716 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:37:44.010  6615  6716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:37:44.010  6615  6716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 12:37:44.018  6615  6716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72be431 added. We now have 1 listener(s)
08-30 12:37:44.018  6615  6716 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:37:44.023  1036  1547 D WifiService: New client listening to asynchronous messages
08-30 12:37:44.027  6615  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:37:44.028  6615  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 12:37:44.028  6615  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:37:44.028  6615  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:37:44.028  6615  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 12:37:44.034  6615  6716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:37:44.034  1036  1618 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:37:44.036  6615  6716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 12:37:44.046  6615  6716 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 12:37:44.047  6615  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:37:44.047  6615  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:37:44.047  6615  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:37:44.047  6615  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:37:44.047  6615  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:37:44.047  6615  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:44.047  6615  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:37:44.047  6615  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:37:44.047  6615  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:37:44.047  6615  6716 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:37:44.050  6615  6716 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:37:44.051  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:37:44.054  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:37:44.086  6615  6698 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 12:37:44.086  6615  6698 I chromium: 
,08-30 12:37:44.182  6615  6615 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 12:37:44.694   346   365 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 12:37:44.694   346   365 E GBMv2   : Set value is all cleared set the max
08-30 12:37:44.694   346   365 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 12:37:45.013  6615  6719 W jxcore-log: Initializing JXcore engine
08-30 12:37:45.013  6615  6719 W jxcore-log: JXcore engine is ready
,08-30 12:37:45.040  6719  6719 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9885]" dev="sockfs" ino=9885 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 12:37:45.040  6719  6719 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 12:37:45.040  6719  6719 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10000]" dev="sockfs" ino=10000 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 12:37:45.040  6719  6719 W Thread-757: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 12:37:45.040  6719  6719 W Thread-757: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31174]" dev="sockfs" ino=31174 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 12:37:45.064  6615  6719 W jxcore-log: Starting JXcore engine
,08-30 12:37:45.142  6615  6719 W jxcore-log: Platform android
08-30 12:37:45.142  6615  6719 W jxcore-log: 
08-30 12:37:45.142  6615  6719 W jxcore-log: Process ARCH arm
08-30 12:37:45.142  6615  6719 W jxcore-log: 
,08-30 12:37:45.340  6615  6719 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:37:45.340  6615  6719 I jxcore-log: 
08-30 12:37:45.341  6615  6719 W jxcore-log: JXcore engine is started
,08-30 12:37:45.352  6615  6716 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 12:37:45.359  6615  6615 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:37:45.383  2804  2804 I MusicWidget: mDelayedStopHandler : unbind
,08-30 12:37:45.392  2128  2128 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-30 12:37:45.392  2128  2128 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-30 12:37:45.392  2128  2128 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-30 12:37:45.403  2128  2128 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-30 12:37:45.404  2128  2128 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-30 12:37:45.404  2128  2128 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,08-30 12:37:45.409  2128  2128 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-30 12:37:45.410  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-30 12:37:45.411  1036  1999 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@15f685a8com.lge.music.MediaPlaybackService$5@3ea048c1
08-30 12:37:45.411  2128  2128 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-30 12:37:45.411  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:37:45.421  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 12:37:45.424  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:37:45.430  2128  2128 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1b5f02b7
08-30 12:37:45.431  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:37:45.433  2128  2128 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-30 12:37:45.434  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 12:37:45.438  2128  2128 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-30 12:37:45.438  2128  2128 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-30 12:37:45.439  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:37:45.439  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:37:45.450  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 12:37:45.453  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:37:45.454  2128  2128 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 12:37:45.462  2128  2128 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,08-30 12:37:45.467  2128  2128 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-30 12:37:45.467  2128  2128 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-30 12:37:45.468  2128  2128 V MediaPlayer[Native]: reset
08-30 12:37:45.482  2128  2128 V MediaPlayer[Native]: setListener
08-30 12:37:45.482  2128  2128 V MediaPlayer[Native]: disconnect
08-30 12:37:45.482  2128  2128 V MediaPlayer[Native]: destructor
08-30 12:37:45.482   328  1784 V AudioFlinger: releasing 18 from 2128 for -1
08-30 12:37:45.482   328  1784 V AudioFlinger:  decremented refcount to 0
08-30 12:37:45.483   328  1784 V AudioFlinger: purging stale effects
,08-30 12:37:45.483  2128  2128 V MediaPlayer[Native]: disconnect
08-30 12:37:45.485  2128  2128 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-30 12:37:45.486  2128  2128 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-30 12:37:45.487  2128  2128 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-30 12:37:45.488  2128  2128 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-30 12:37:45.488  2128  2128 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-30 12:37:45.488  2128  2128 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-30 12:37:45.488  2128  2128 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 112195686
08-30 12:37:45.488  2128  2128 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 112195686
08-30 12:37:45.495  2128  2128 I SmartShareClient: [SmartShareManagerClient] terminate service: 2128/MediaPlaybackService/733304021
08-30 12:37:45.499  2128  2128 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-30 12:37:45.499  2128  2128 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3b8007a7
,08-30 12:37:45.511  2128  2128 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-30 12:37:45.512  2128  2128 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-30 12:37:45.513  2128  2128 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-30 12:37:45.513  2128  2128 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-30 12:37:45.514  1036  1890 I ActivityManager: Killing 5652:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-30 12:37:45.518  2128  2128 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
,08-30 12:37:45.532  5631  5631 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-30 12:37:45.532  5631  5631 W System.err: android.os.DeadObjectException
,08-30 12:37:45.532  5631  5631 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:37:45.532  5631  5631 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-30 12:37:45.532  5631  5631 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,08-30 12:37:45.532  5631  5631 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 12:37:45.532  5631  5631 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 12:37:45.532  5631  5631 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:37:45.532  5631  5631 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:37:45.532  5631  5631 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:37:45.532  5631  5631 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:37:45.532  5631  5631 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:37:45.532  5631  5631 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:37:45.532  5631  5631 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:37:45.532  5631  5631 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:37:45.532  5631  5631 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:37:45.533  5631  5631 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 12:37:45.538  5631  5631 W System.err: android.os.DeadObjectException
08-30 12:37:45.539  5631  5631 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:37:45.539  5631  5631 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 12:37:45.539  5631  5631 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 12:37:45.539  5631  5631 W System.err: 	,at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 12:37:45.540  5631  5631 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-30 12:37:45.540  5631  5631 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:37:45.540  5631  5631 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-30 12:37:45.540  5631  5631 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:37:45.540  5631  5631 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:37:45.540  5631  5631 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:37:45.540  5631  5631 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-30 12:37:45.540  5631  5631 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:37:45.540  5631  5631 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-30 12:37:45.540  5631  5631 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 12:37:45.540  5631  5631 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 12:37:45.541  5631  5631 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 12:37:45.722  1036  1890 E libprocessgroup: failed to kill 1 processes for processgroup 5652
,08-30 12:37:45.892  1036  2045 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 12:37:45.903  5631  5631 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 12:37:45.903  5631  5631 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 12:37:45.952  1036  1618 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6720 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:37:45.956  5631  5631 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 12:37:46.020  6720  6720 D UEI.SmartControl: Quickset Services start...
08-30 12:37:46.022  6720  6720 I UEI.SmartControl: Manufacture = LGE
08-30 12:37:46.022  6720  6720 D UEI.SmartControl: Id = LGNevo
08-30 12:37:46.023  6720  6720 D UEI.SmartControl: File observer start...
08-30 12:37:46.023  6720  6720 E UEI.SmartControl: IR Port is disabled: false
08-30 12:37:46.023  6720  6720 D UEI.SmartControl: Starting file observer...
08-30 12:37:46.024  6720  6720 D UEI.SmartControl: Extracting JNI libs...
08-30 12:37:46.024  6720  6720 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-30 12:37:46.098  6720  6720 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-30 12:37:46.098  6720  6720 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 12:37:46.098  6720  6720 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 12:37:46.134  6720  6720 I UEI.SmartControl: --- Selecting new region: 6
08-30 12:37:46.136  6720  6720 I UEI.SmartControl: Model = LG-D855
,08-30 12:37:46.138  6720  6720 D UEI.SmartControl: QS Service created
08-30 12:37:46.166  6720  6720 I UEI.SmartControl: Service initServices...
,08-30 12:37:46.173  6720  6720 D UEI.SmartControl: QS start get config
,08-30 12:37:46.231  6720  6720 D UEI.SmartControl: Loading JNI Libs...
,08-30 12:37:46.586  6720  6720 I UEI.SmartControl: Supports setup maps: true
,08-30 12:37:46.604  6720  6720 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 12:37:46.604  6720  6720 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 12:37:46.604  6720  6720 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-30 12:37:46.605  6720  6720 I UEI.SmartControl: ### init IR Blaster...
,08-30 12:37:46.613  6720  6720 D serial_port: Configuring serial port
08-30 12:37:46.625  6720  6720 E UEI.SmartControl: UEIBLaster setting for 616
08-30 12:37:46.626  6720  6720 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 12:37:46.627  6720  6720 I UEI.SmartControl: configuring settings for MAXQ616
08-30 12:37:46.627  6720  6720 I UEI.SmartControl: Get version...
,08-30 12:37:46.646  6720  6743 D UEI.SmartControl: serial port data available: 21
,08-30 12:37:46.675  6720  6720 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 12:37:46.675  6720  6720 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 12:37:46.675  6720  6720 I UEI.SmartControl: QS saving settings...
08-30 12:37:46.676  6720  6720 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 12:37:46.693  6720  6743 D UEI.SmartControl: serial port data available: 4
,08-30 12:37:46.729  6720  6746 I UEI.SmartControl: Device manager: loading config....
,08-30 12:37:46.732  6720  6746 D UEI.SmartControl: ----------- loading internal config...
,08-30 12:37:46.732  6720  6720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 12:37:46.735  6720  6720 E UEI.SmartControl: Services init done
08-30 12:37:46.735  6720  6720 D UEI.SmartControl: QS Service init finished
08-30 12:37:46.737  6720  6720 D UEI.SmartControl: QS Service version name: 2.1.91
,08-30 12:37:46.737  6720  6720 D UEI.SmartControl: QS Service version code: 201091
08-30 12:37:46.739  6720  6720 D UEI.SmartControl: Service requested: Control
08-30 12:37:46.747  6720  6746 E UEI.SmartControl: Loading SETTINGS...
08-30 12:37:46.749  6720  6720 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 12:37:46.754  5631  5631 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 12:37:46.755  6720  6736 I UEI.SmartControl: ------ IControl API: 11
08-30 12:37:46.755  1036  1927 I ActivityManager: Killing 5631:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 12:37:46.757  6720  6736 I UEI.SmartControl: Registering callback...
08-30 12:37:46.760  6720  6746 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 12:37:46.767  6720  6745 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 12:37:46.767  6720  6745 D UEI.SmartControl: -----service ready thread exits
,08-30 12:37:46.821  1036  1890 W libprocessgroup: failed to open /acct/uid_10112/pid_5631/cgroup.procs: No such file or directory
,08-30 12:37:46.824  6720  6720 D UEI.SmartControl: Internal service binding...
08-30 12:37:46.892  6558  6558 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-30 12:37:46.896  1036  1998 I ActivityManager: Killing 6258:com.android.calendar/u0a13 (adj 15): empty #17
,08-30 12:37:46.971  1036  1578 W libprocessgroup: failed to open /acct/uid_10013/pid_6258/cgroup.procs: No such file or directory
,08-30 12:37:47.848  6558  6608 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 12:37:51.730  6720  6747 D UEI.SmartControl: Internal timer expired: 1
,08-30 12:37:51.730  6720  6747 D UEI.SmartControl: unbind internal service
,08-30 12:37:51.742  6720  6720 D UEI.SmartControl: Service.onUnbind: IControl
08-30 12:37:51.745  6720  6720 D UEI.SmartControl: Service.onDestroy
08-30 12:37:51.746  6720  6720 D UEI.SmartControl: Lock is in USE false
08-30 12:37:51.746  6720  6720 D UEI.SmartControl: unbind internal service
08-30 12:37:51.746  6720  6720 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1b5f02b7
08-30 12:37:51.747  6720  6720 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 12:37:51.747  6720  6720 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 12:37:51.747  6720  6720 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 12:37:51.747  6720  6720 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 12:37:51.748  6720  6720 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
,08-30 12:37:51.748  6720  6720 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
,08-30 12:37:51.748  6720  6720 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,08-30 12:37:51.748  6720  6720 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
,08-30 12:37:51.748  6720  6720 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102),
08-30 12:37:51.748  6720  6720 W System.err: 	,at android.os.Looper.loop(Looper.java:135)
08-30 12:37:51.748  6720  6720 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:37:51.748  6720  6720 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:37:51.748  6720  6720 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:37:51.748  6720  6720 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:37:51.749  6720  6720 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:37:51.749  6720  6720 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1b5f02b7
,08-30 12:37:51.762  6720  6720 D serial_port: close(fd = 25)
08-30 12:37:51.764  6720  6720 I UEI.SmartControl: Serial port is closed.
08-30 12:37:51.764  6720  6720 I UEI.SmartControl: Serial port is closed.
08-30 12:37:51.765  6720  6720 D UEI.SmartControl: Blaster closed
08-30 12:37:51.765  6720  6720 D UEI.SmartControl: Shut down QS...
08-30 12:37:51.765  6720  6720 D UEI.SmartControl: Stopping QS lib
08-30 12:37:51.765  6720  6720 D UEI.SmartControl: QS lib stop result = true
08-30 12:37:51.765  6720  6720 D UEI.SmartControl: Stopped QS lib
,08-30 12:37:51.766  6720  6720 D UEI.SmartControl: Stopped file observer...
08-30 12:37:51.766  6720  6720 D UEI.SmartControl: QS shutdown complete
,08-30 12:37:55.526  2128  2128 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
,08-30 12:37:55.760  1036  1103 I ActivityManager: Waited long enough for: ServiceRecord{1cb52f05 u0 com.google.android.gms/.wearable.service.WearableService}
,08-30 12:37:59.669  6615  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:37:59.669  6615  6719 I jxcore-log: 
,08-30 12:37:59.672  6615  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:37:59.672  6615  6719 I jxcore-log: 
08-30 12:37:59.678  6615  6719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:37:59.678  6615  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:37:59.678  6615  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:37:59.678  6615  6719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:37:59.678  6615  6719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:37:59.678  6615  6719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:59.678  6615  6719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:37:59.678  6615  6719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:37:59.681  6615  6719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:59.684  6615  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:37:59.684  6615  6719 I jxcore-log: 
08-30 12:37:59.686  6615  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:37:59.686  6615  6719 I jxcore-log: 
,08-30 12:38:00.033  6615  6719 I jxcore-log: Running unit tests
08-30 12:38:00.033  6615  6719 I jxcore-log: 
,08-30 12:38:00.033  6615  6719 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 12:38:00.034  6615  6719 I jxcore-log: Failed to execute UT.
08-30 12:38:00.034  6615  6719 I jxcore-log: 
08-30 12:38:00.035  6615  6719 I jxcore-log: Unit Test app is loaded
08-30 12:38:00.035  6615  6719 I jxcore-log: 
08-30 12:38:00.040  6615  6719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:38:00.040  6615  6719 I jxcore-log: 
08-30 12:38:00.044  6615  6719 I jxcore-log: My device name is: LGE-LG-D855
08-30 12:38:00.044  6615  6719 I jxcore-log: 
08-30 12:38:00.045  6615  6719 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 12:38:00.045  6615  6719 I jxcore-log: 
08-30 12:38:00.049  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 12:38:00.049  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 12:38:00.049  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 12:38:00.050  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,08-30 12:38:00.055  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,08-30 12:38:00.055  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,08-30 12:38:00.055  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
,08-30 12:38:00.056  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 12:38:00.061  6615  6615 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 12:38:02.439  1036  1425 D PowerManagerServiceEx: acquireWakeLockInternal: lock=437006446, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-30 12:38:02.460  1036  1425 V AlarmManager: RTC_WAKEUP set : Alarm{199a1f9c type 0 when 1472553476176 com.android.vending} when 1472553476176
,08-30 12:38:02.499  2669  2669 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 12:38:02.535  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=437006446 [*alarm*], flags=0x0
,08-30 12:38:02.562  4512  6781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-30 12:38:02.581  6615  6719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 12:38:02.581  6615  6719 I jxcore-log: 
,08-30 12:38:02.592  1036  1890 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:38:02.745  6072  6072 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 12:38:03.041  6615  6719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 12:38:03.041  6615  6719 I jxcore-log: 
,08-30 12:38:03.064  6615  6719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 12:38:03.064  6615  6719 I jxcore-log: 
,08-30 12:38:04.435  6615  6719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 12:38:04.435  6615  6719 I jxcore-log: 
,08-30 12:38:04.671  6615  6719 I jxcore-log: ERROR runTests: 
08-30 12:38:04.671  6615  6719 I jxcore-log: 
,08-30 12:38:04.674  6615  6719 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:38:04.674  6615  6719 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 12:38:04.676  6615  6719 I jxcore-log: WARN testUtils: logCallback not set!
08-30 12:38:04.676  6615  6719 I jxcore-log: 
08-30 12:38:04.685  6615  6719 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _functionName: 'loadFile',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _lineNumber: '26',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _columnNumber: '11',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 12:38:04.685  6615  6719 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _functionName: '',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _lineNumber: '38',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _columnNumber: '7',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 12:38:04.685  6615  6719 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _functionName: '',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _lineNumber: '35',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _columnNumber: '3',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 12:38:04.685  6615  6719 I jxcore-log:   { _fileName: 'module.js',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _lineNumber: '621',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _columnNumber: '8',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 12:38:04.685  6615  6719 I jxcore-log:   { _fileName: 'module.js',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _lineNumber: '651',
08-30 12:38:04.685  6615  6719 I jxcore-log:     _columnNumber: '1',
08-30 12:38:04.685  6615  6719 I jxcore-log:    
08-30 12:38:04.686  6615  6719 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 12:38:04.686  6615  6719 I jxcore-log: 
08-30 12:38:04.686  6615  6719 E jxcore-log: Error: 
08-30 12:38:04.686  6615  6719 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:38:04.686  6615  6719 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 12:38:04.686  6615  6719 E jxcore-log: 
,08-30 12:38:05.011  6806  6806 D AndroidRuntime: 
08-30 12:38:05.011  6806  6806 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 12:38:05.015  6806  6806 D AndroidRuntime: CheckJNI is OFF
,08-30 12:38:05.213  6806  6806 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 12:38:05.231  1036  1103 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-30 12:38:05.232  1036  1103 I ActivityManager: Killing 6615:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-30 12:38:05.307  1036  1890 I WindowState: WIN DEATH: Window{20a65ec3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 12:38:05.308  1036  1547 D WifiService: Client connection lost with reason: 4
,08-30 12:38:05.322  1036  1890 D InputDispatcher: Window went away: Window{20a65ec3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:38:05.451  1036  1103 I ActivityManager:   Force finishing activity ActivityRecord{133e8574 u0 com.test.thalitest/.MainActivity t6}
,08-30 12:38:05.483   346   363 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 12:38:05.495  1036  1052 W ActivityManager: Spurious death for ProcessRecord{2ae92da5 6615:com.test.thalitest/u0a118}, curProc for 6615: null
,08-30 12:38:05.498  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-30 12:38:05.499  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{133e8574 u0 com.test.thalitest/.MainActivity t6 f}
08-30 12:38:05.499  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{133e8574 u0 com.test.thalitest/.MainActivity t6 f}
,08-30 12:38:05.547  4616  4616 I art     : Explicit concurrent mark sweep GC freed 485(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 584us total 38.408ms
,08-30 12:38:05.559  2036  2036 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 12:38:05.560  2036  2036 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-30 12:38:05.562  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-30 12:38:05.564  2036  2146 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 12:38:05.565  1945  2560 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 12:38:05.565  1945  2560 D SplitWindowPolicy: topRunningActivity=ActivityInfo{20c6a96b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 12:38:05.566  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 12:38:05.567  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ff6ecc8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 12:38:05.570  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 12:38:05.571  1909  1909 D ActionManagerService: notifyUserLog: 1000003
08-30 12:38:05.573  2036  2036 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 12:38:05.573  2036  2036 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 12:38:05.575  2036  2036 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 12:38:05.578  1909  1909 D ActionManagerService: notifyUserLog: 1000004
08-30 12:38:05.579  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-30 12:38:05.580  3805  4503 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 12:38:05.580  3805  4503 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 12:38:05.581  3805  3821 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:38:05.586  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 12:38:05.596  3861  3861 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 12:38:05.596  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 12:38:05.596  2000  2000 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-30 12:38:05.601  3805  3805 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 12:38:05.602  1036  1471 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 12:38:05.605  2495  2600 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 12:38:05.623  1036  1101 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , display: false
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , animation: false }
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , display: false
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , animation: false }
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , display: false
08-30 12:38:05.658  2036  2036 I GBoardWebViewUtils: , animation: false }
,08-30 12:38:05.659  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 12:38:05.675  1606  1667 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 12:38:05.675  1606  1667 D KeyguardModel: createShortcutInfo...
08-30 12:38:05.678  1606  1667 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 12:38:05.678  1606  1667 D KeyguardModel: createShortcutInfo...
,08-30 12:38:05.685  1606  1667 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 12:38:05.685  1606  1667 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:38:05.685  1606  1667 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 12:38:05.687  1606  1667 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 12:38:05.689  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 12:38:05.692  2036  6831 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 12:38:05.692  1606  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:05.692  1606  1667 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-30 12:38:05.695  4512  4512 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 12:38:05.695  4512  4512 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 12:38:05.695  4512  4512 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 12:38:05.695  4512  4512 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 12:38:05.695  4512  4512 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:38:05.695  4512  4512 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:38:05.695  4512  4512 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:38:05.695  4512  4512 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:38:05.695  4512  4512 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:38:05.695  4512  4512 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:38:05.696  4512  4512 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:38:05.696  4512  4512 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:38:05.699  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-30 12:38:05.699  1606  1667 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 12:38:05.700  1606  1667 D KeyguardModel: createShortcutInfo...
08-30 12:38:05.700  1872  1872 D SplitUIService: removed split : 
08-30 12:38:05.702  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 12:38:05.703  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 12:38:05.703  1606  1667 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 12:38:05.703  1606  1667 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:38:05.713  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 12:38:05.715  1606  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:05.715  1606  1667 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-30 12:38:05.716  1036  2054 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:38:05.719  1820  1820 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 12:38:05.720  1606  1667 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 12:38:05.720  1606  1667 D KeyguardModel: createShortcutInfo...
08-30 12:38:05.728  1606  1667 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:38:05.728  1606  1667 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 12:38:05.728  1606  1667 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 12:38:05.728  1606  1667 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 12:38:05.729  1606  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:05.729  1606  1667 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 12:38:05.738  1606  1667 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 12:38:05.738  1606  1667 D KeyguardModel: createShortcutInfo...
08-30 12:38:05.756  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-30 12:38:05.756  1872  1872 I SplitUIService: split app #11
08-30 12:38:05.757  1036  1036 I art     : Explicit concurrent mark sweep GC freed 30230(1956KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.058ms total 234.705ms
08-30 12:38:05.757  1036  1963 I art     : WaitForGcToComplete blocked for 34.695ms for cause Explicit
,08-30 12:38:05.766  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 12:38:05.792  1036  2035 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:38:05.792  1036  2035 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:38:05.862  1036  1036 D administrator: Handling package changes for user 0
,08-30 12:38:05.881  1036  1927 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:38:05.882  1036  1963 I art     : Explicit concurrent mark sweep GC freed 5273(345KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.417ms total 121.207ms
08-30 12:38:05.883  1036  1124 I art     : WaitForGcToComplete blocked for 312.247ms for cause Explicit
08-30 12:38:05.888  1036  1926 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 12:38:05.889  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 12:38:05.889  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 12:38:05.889  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 12:38:05.889  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 12:38:05.889  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 12:38:05.889  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:38:05.890  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 12:38:05.890  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 12:38:05.890  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 12:38:05.890  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:38:05.890  3861  3861 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 12:38:05.894  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-30 12:38:05.894  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 12:38:05.903  2192  2192 I ConfigService: onCreate
08-30 12:38:05.903  2192  2192 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 12:38:05.906  1606  1667 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 12:38:05.906  1606  1667 D KeyguardModel: createShortcutInfo...
08-30 12:38:05.907  2192  2192 I ConfigService: onBind returning update interface
08-30 12:38:05.912  1606  1667 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 12:38:05.912  1606  1667 D KeyguardModel: createShortcutInfo...
08-30 12:38:05.913  1606  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:05.913  1606  1667 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 12:38:05.914  1606  1667 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 12:38:05.914  1606  1667 D KeyguardModel: createShortcutInfo...
08-30 12:38:05.915  1606  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:05.915  1606  1667 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-30 12:38:05.919  1606  1667 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 12:38:05.919  1606  1667 D KeyguardModel: createShortcutInfo...
08-30 12:38:05.921  1606  1667 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:38:05.921  1606  1667 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 12:38:05.922  1820  1820 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 12:38:05.923  2192  2192 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 12:38:05.923  2192  2192 I ConfigService: onBind returning config service
08-30 12:38:05.929  1606  1667 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 12:38:05.929  1606  1667 D KeyguardModel: createShortcutInfo...
,08-30 12:38:05.931  1820  1820 I ConfigFetchService: service connected
08-30 12:38:05.933  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-30 12:38:05.933  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 12:38:05.939  2192  2192 I ConfigService: onDestroy
08-30 12:38:05.954  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-30 12:38:05.951  1820  6838 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 12:38:05.959  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:38:05.961  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 12:38:05.962  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 12:38:05.963  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 12:38:05.964  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-30 12:38:05.980  2036  2036 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 12:38:05.986  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 12:38:05.986  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:38:05.986  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d4d5f09 u0 com.lge.launcher2/.Launcher t5} time:127076
08-30 12:38:05.990  2036  2279 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 12:38:05.990  2036  2279 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 12:38:05.997  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 12:38:05.997  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 12:38:05.997  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 12:38:05.999  1036  1581 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-30 12:38:06.000  5935  6844 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 12:38:06.001  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 12:38:06.002  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 12:38:06.002  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:38:06.009  2036  2036 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 12:38:06.011  2669  2669 D [Concierge]Service: onStartCommand(). Type : 8
08-30 12:38:06.011  2669  2669 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-30 12:38:06.013  2669  2669 D [Concierge]Service: Update widget ID : 11
08-30 12:38:06.013  1820  6848 I PeopleContactsSync: CP2 sync disabled
08-30 12:38:06.014  2036  2036 D [Concierge]WidgetView: change position of spinner
08-30 12:38:06.015  2036  2036 I [Concierge]WidgetView: initWebView(). Time : 1472553486015
08-30 12:38:06.015  2669  2669 D [Concierge]Service: onStartCommand(). Type : 0
08-30 12:38:06.019  1820  4775 I Icing   : doRemovePackageData com.test.thalitest
08-30 12:38:06.029  1820  6846 W GmsApplication: Using Auth Proxy for data requests.
,08-30 12:38:06.034  1820  6846 W GmsApplication: Using Auth Proxy for data requests.
08-30 12:38:06.054   340   430 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-30 12:38:06.055  3238  6850 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 12:38:06.056  2036  2036 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 591254494
08-30 12:38:06.057  6002  6002 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-30 12:38:06.057  2036  2036 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 12:38:06.057  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 12:38:06.060  2036  2036 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2a501e12
08-30 12:38:06.060  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 12:38:06.061  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 12:38:06.061  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:38:06.065  6523  6523 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-30 12:38:06.066  2343  6851 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 12:38:06.067  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 12:38:06.068  2036  2036 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 12:38:06.068  2036  2036 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-30 12:38:06.069  2036  2036 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472553387398, New one : 1472553486015
08-30 12:38:06.069  2036  2036 D [Concierge]WidgetView: Unregister all receivers
08-30 12:38:06.070  2036  2036 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 12:38:06.070  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:38:06.071  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 12:38:06.073  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 12:38:06.074  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 12:38:06.075  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 12:38:06.077  2000  2000 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 12:38:06.077  2000  2000 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-30 12:38:06.077  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 12:38:06.078  2000  2000 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 12:38:06.080  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:38:06.080  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 12:38:06.086  6431  6431 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 12:38:06.087  1036  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:38:06.096  1036  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 12:38:06.106  1036  1051 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6854 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 12:38:06.117  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 12:38:06.124  2036  2036 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 12:38:06.125  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 12:38:06.130  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 12:38:06.134  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 12:38:06.141  1036  1124 I art     : Explicit concurrent mark sweep GC freed 7501(383KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 12.540ms total 255.319ms
08-30 12:38:06.153  2036  2036 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2f1d898b time:127243
,08-30 12:38:06.184  6854  6854 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 12:38:06.184  6854  6854 W LG Account v2.2: No ProfileInfo entries
,08-30 12:38:06.184  6854  6854 I LG Account v2.2: isEnabled: false
08-30 12:38:06.184  6854  6854 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,08-30 12:38:06.184  6854  6854 I Feature : [Lifetracker]Country: EU
08-30 12:38:06.184  6854  6854 I Feature : [Lifetracker]Operator: OPEN
08-30 12:38:06.184  6854  6854 I Feature : [Lifetracker]Ranking support: false
08-30 12:38:06.184  6854  6854 I Feature : [Lifetracker]Comfort support: false
08-30 12:38:06.185  6854  6854 I Feature : [Lifetracker]Accessory: true
08-30 12:38:06.185  6854  6854 I Feature : [Lifetracker]Health device: true
08-30 12:38:06.185  6854  6854 I Feature : [Lifetracker]Extra Pedometer: false
08-30 12:38:06.185  6854  6854 I Feature : [Lifetracker]Blood glucose device: false
08-30 12:38:06.185  6854  6854 I Feature : [Lifetracker]Device Number: 3
08-30 12:38:06.185  6854  6854 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-30 12:38:06.207  6806  6806 D AndroidRuntime: Shutting down VM
,08-30 12:38:06.214  1036  1927 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6873 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:38:06.215  1036  1927 I ActivityManager: Killing 6211:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 12:38:06.277  2036  2036 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 12:38:06.310  1036  1890 W libprocessgroup: failed to open /acct/uid_10014/pid_6211/cgroup.procs: No such file or directory
,08-30 12:38:06.311  2036  2960 I GBoardtInterface: onReloaded()
08-30 12:38:06.316  2036  2036 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 12:38:06.317  3805  4501 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:38:06.319  3805  3821 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:38:06.324  1909  1909 D ActionManagerService: notifyUserLog: 1000001
,08-30 12:38:06.325  3805  4503 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 12:38:06.325  3805  4503 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-30 12:38:06.326  6873  6873 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:38:06.326  6873  6873 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 12:38:06.326  6873  6873 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:38:06.327  6873  6873 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 12:38:06.327  6873  6873 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:38:06.328  6873  6873 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 12:38:06.328  1909  1909 D ActionManagerService: notifyUserLog: 1000001
08-30 12:38:06.329  3805  4503 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 12:38:06.329  3805  4503 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 12:38:06.329  3805  4503 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 12:38:06.329  3805  4503 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 12:38:06.329  3805  4501 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:38:06.331  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 12:38:06.331  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 12:38:06.333  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 12:38:06.333  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 12:38:06.335  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 12:38:06.335  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 12:38:06.401  6873  6873 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-30 12:38:06.408  6873  6873 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-30 12:38:06.408  6873  6873 D HideNavigationAppsReceiver: replacing : false
08-30 12:38:06.410  6873  6873 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-30 12:38:06.411  6873  6873 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-30 12:38:06.411  6873  6873 D ButtonCombinationReceiver: replacing : false
,08-30 12:38:06.416  1036  1889 I ActivityManager: Killing 6321:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 12:38:06.503  1036  1124 W ActivityManager: Application dead when creating service ServiceRecord{3f630efd u0 com.android.defcontainer/.DefaultContainerService}
08-30 12:38:06.503  1036  1124 W libprocessgroup: failed to open /acct/uid_10004/pid_6321/cgroup.procs: No such file or directory
08-30 12:38:06.503  1036  1124 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 1000ms
,08-30 12:38:06.506  1036  1124 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 4000ms
08-30 12:38:06.506  1036  1052 W ActivityManager: Spurious death for ProcessRecord{6ca7f2 0:com.android.defcontainer/u0a4}, curProc for 6321: null
08-30 12:38:06.515  4616  6894 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 12:38:06.543  1036  1926 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6895 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:38:06.557  1036  1578 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:38:06.564  4616  6894 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
08-30 12:38:06.568  4616  6894 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-30 12:38:06.568  4616  6894 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4616
08-30 12:38:06.568  4616  6894 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at csx.d(PG:186)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at cun.g(PG:594)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at cuy.ub(PG:301)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:38:06.568  4616  6894 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:38:06.576  4616  6894 I Process : Sending signal. PID: 4616 SIG: 9
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: Can't write: system_app_crash
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:38:06.579  1036  6912 E DropBoxManagerService: 	... 5 more

```
