#### Test 82894682a24f9af_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 17:37:14.053  1817  3732 I art     : Explicit concurrent mark sweep GC freed 26018(1782KB) AllocSpace objects, 19(300KB) LOS objects, 51% free, 29MB/61MB, paused 2.466ms total 61.619ms
08-26 17:37:14.086  4560  6641 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 252 ms] updated apps [took 252 ms] 
08-26 17:37:14.154  6645  6645 D DocsApplication: Installing DEX configuration.
08-26 17:37:14.170  6645  6645 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 17:37:14.174  6645  6645 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{19da19ca com.google.android.apps.docs}
08-26 17:37:14.189  6645  6645 D TAG     : onCreate()
08-26 17:37:14.205  6645  6645 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 17:37:14.821   330   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-26 17:37:14.825  3224  6668 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-26 17:37:15.098  1817  4749 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-26 17:37:15.143  6669  6669 D AndroidRuntime: 
08-26 17:37:15.143  6669  6669 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 17:37:15.145  6669  6669 D AndroidRuntime: CheckJNI is OFF
08-26 17:37:15.196  1817  4749 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-26 17:37:15.248  6669  6669 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 17:37:15.251  1817  4749 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
--------- beginning of system
08-26 17:37:15.253  1035  1956 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 17:37:15.260  1941  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 17:37:15.263  1035  1956 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 17:37:15.264  1035  1956 D ActivityManager: setTaskToReturnTo : TaskRecord{3b58ca8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 17:37:15.264  1035  1956 D ActivityManager: setTaskToReturnTo : TaskRecord{3b58ca8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 17:37:15.264  1035  1956 D WindowStateEx: AppWindowTokenEx init.. 
08-26 17:37:15.265   338   346 E GBMv2   : DFP En is all cleared set to be enabled
08-26 17:37:15.308  1035  1956 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6695 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 17:37:15.311  6669  6669 D AndroidRuntime: Shutting down VM
08-26 17:37:15.360  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 17:37:15.361  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{28ea1f66 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 17:37:15.362  1941  2937 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 17:37:15.363  1941  2937 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3024a2a7 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 17:37:15.374  6645  6645 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:15.374  6645  6645 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 17:37:15.414  6695  6695 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 17:37:15.469  6695  6695 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-26 17:37:15.474  6695  6695 I LibraryLoader: Loading: webviewchromium
08-26 17:37:15.476  6695  6695 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3516-3518)
08-26 17:37:15.476  6695  6695 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 17:37:15.497  6695  6695 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d9dd804}
08-26 17:37:15.500  6695  6695 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 17:37:15.501  6695  6695 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 17:37:15.523  6695  6695 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 17:37:15.524  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 17:37:15.535  6695  6695 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 17:37:15.535  6695  6695 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-26 17:37:15.536  6695  6695 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-26 17:37:15.537   313  1383 V AudioPolicyService: registerClient() client 0xb1025f60, uid 10118
,08-26 17:37:15.542  1035  1099 D BluetoothManagerService: Message: 20
08-26 17:37:15.542  1035  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1086d3e:true
08-26 17:37:15.549  6159  6159 I LockScreenSettings: New app installed broadcast received ..
08-26 17:37:15.551  6159  6159 I LockScreenSettings: Number of installed packages  1
08-26 17:37:15.555  6695  6695 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 17:37:15.555  6695  6695 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 17:37:15.555  6695  6695 I Adreno-EGL: Build Date: 12/12/14 금
08-26 17:37:15.555  6695  6695 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 17:37:15.555  6695  6695 I Adreno-EGL: Remote Branch: 
08-26 17:37:15.555  6695  6695 I Adreno-EGL: Local Patches: 
08-26 17:37:15.555  6695  6695 I Adreno-EGL: Reconstruct Branch: 
,08-26 17:37:15.560  6645  6645 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-26 17:37:15.607  1035  1990 V SIM_STK : Menu title from STK is T-Mobile
,08-26 17:37:15.648  1035  1896 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6742 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 17:37:15.666  6695  6729 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 17:37:15.670  6695  6695 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 17:37:15.689  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 17:37:15.693  6695  6695 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 17:37:15.696  6695  6695 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 17:37:15.699  6695  6695 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 17:37:15.699  6695  6695 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-26 17:37:15.717  6695  6695 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-26 17:37:15.726  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 17:37:15.726  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 17:37:15.735  6742  6742 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 17:37:15.735  6742  6742 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-26 17:37:15.783  1035  1962 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6769 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 17:37:15.786  1035  1962 I ActivityManager: Killing 5841:com.google.android.gm/u0a64 (adj 15): empty #17
08-26 17:37:15.799  6695  6763 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:15.799  6695  6763 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 17:37:15.847  1035  1990 W libprocessgroup: failed to open /acct/uid_10064/pid_5841/cgroup.procs: No such file or directory
08-26 17:37:15.848  6695  6786 D OpenGLRenderer: Render dirty regions requested: true
08-26 17:37:15.848  6695  6786 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 17:37:15.854  6695  6786 D OpenGLRenderer: Enabling debug mode 0
08-26 17:37:15.858  1035  1092 W ActivityManager: Activity pause timeout for ActivityRecord{171843c1 u0 com.test.thalitest/.MainActivity t6}
,08-26 17:37:15.863  6695  6695 D Atlas   : Validating map...
08-26 17:37:15.868  1035  2032 D SplitWindow: check instance of lgWin Window{245eb6a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 17:37:15.906  6769  6769 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-26 17:37:15.944  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 17:37:15.945  6769  6769 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-26 17:37:15.949  1035  1100 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +592ms (total +684ms)
08-26 17:37:15.950  1035  1100 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{171843c1 u0 com.test.thalitest/.MainActivity t6} time:103992
08-26 17:37:15.953  6695  6695 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3797cea3 time:103996
08-26 17:37:15.974  1035  2032 I ActivityManager: Killing 5886:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 17:37:16.054  6695  6695 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 17:37:16.054  6695  6695 I chromium: 
,08-26 17:37:16.090  1035  1896 W libprocessgroup: failed to open /acct/uid_10072/pid_5886/cgroup.procs: No such file or directory
,08-26 17:37:16.111  6695  6695 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 17:37:16.171  6695  6763 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 17:37:16.171  6695  6763 I chromium: 
,08-26 17:37:16.307  6695  6793 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-26 17:37:16.320  6695  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 17:37:16.320  6695  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 17:37:16.320  6695  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 17:37:16.320  6695  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 17:37:16.320  6695  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 17:37:16.320  6695  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f2e1f7 added. We now have 1 listener(s)
08-26 17:37:16.326  1035  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 17:37:16.331  6695  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-26 17:37:16.334  6695  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:16.337  6695  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:16.338  6695  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 17:37:16.355  6695  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44a4f82 added. We now have 1 listener(s)
,08-26 17:37:16.356  6695  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:16.360  1035  1545 D WifiService: New client listening to asynchronous messages
08-26 17:37:16.364  6695  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:16.364  6695  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 17:37:16.364  6695  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 17:37:16.365  6695  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 17:37:16.365  6695  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 17:37:16.369  6695  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:16.370  1035  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:16.372  6695  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-26 17:37:16.391  6695  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-26 17:37:16.391  6695  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:16.391  6695  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:16.391  6695  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:16.391  6695  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:16.391  6695  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:16.391  6695  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:16.391  6695  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:16.391  6695  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:16.392  6695  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 17:37:16.392  6695  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:16.393  6695  6793 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 17:37:16.395  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:16.397  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:16.432  6695  6695 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 17:37:16.808   338   348 E GBMv2   : DFP En is all cleared set to be enabled
08-26 17:37:16.809   338   348 E GBMv2   : Set value is all cleared set the max
08-26 17:37:16.809   338   348 I GBMv2   : DFP Enabled. Ignore VFP set
,08-26 17:37:17.438  6695  6799 W jxcore-log: Initializing JXcore engine
,08-26 17:37:17.439  6695  6799 W jxcore-log: JXcore engine is ready
,08-26 17:37:17.516  6799  6799 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8363]" dev="sockfs" ino=8363 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-26 17:37:17.516  6799  6799 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 17:37:17.516  6799  6799 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8498]" dev="sockfs" ino=8498 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 17:37:17.516  6799  6799 W Thread-757: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-26 17:37:17.516  6799  6799 W Thread-757: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31208]" dev="sockfs" ino=31208 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-26 17:37:17.534  6695  6799 W jxcore-log: Starting JXcore engine
,08-26 17:37:17.625  6695  6799 W jxcore-log: Platform android
08-26 17:37:17.625  6695  6799 W jxcore-log: 
08-26 17:37:17.625  6695  6799 W jxcore-log: Process ARCH arm
08-26 17:37:17.625  6695  6799 W jxcore-log: 
,08-26 17:37:17.833  6695  6799 I jxcore-log: JXcore Cordova bridge is ready!
08-26 17:37:17.833  6695  6799 I jxcore-log: 
08-26 17:37:17.834  6695  6799 W jxcore-log: JXcore engine is started
,08-26 17:37:17.843  6695  6793 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 17:37:17.845  6695  6695 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 17:37:18.018  2793  2793 I MusicWidget: mDelayedStopHandler : unbind
,08-26 17:37:18.023  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 17:37:18.023  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 17:37:18.023  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-26 17:37:18.025  2172  2172 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 17:37:18.025  2172  2172 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 17:37:18.025  2172  2172 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-26 17:37:18.026  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 17:37:18.026  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-26 17:37:18.027  1035  1956 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@7e8a05dcom.lge.music.MediaPlaybackService$5@23d6cdd2
08-26 17:37:18.028  2172  2172 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 17:37:18.028  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.029  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.029  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.029  2172  2172 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@34227070
08-26 17:37:18.030  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.030  2172  2172 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 17:37:18.030  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.030  2172  2172 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 17:37:18.031  2172  2172 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 17:37:18.031  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.031  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.032  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.032  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.032  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 17:37:18.033  2172  2172 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 17:37:18.034  2172  2172 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 17:37:18.034  2172  2172 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 17:37:18.034  2172  2172 V MediaPlayer[Native]: reset
,08-26 17:37:18.040  2172  2172 V MediaPlayer[Native]: setListener
08-26 17:37:18.040  2172  2172 V MediaPlayer[Native]: disconnect
08-26 17:37:18.040  2172  2172 V MediaPlayer[Native]: destructor
08-26 17:37:18.040   313   313 V AudioFlinger: releasing 18 from 2172 for -1
08-26 17:37:18.040   313   313 V AudioFlinger:  decremented refcount to 0
08-26 17:37:18.040   313   313 V AudioFlinger: purging stale effects
08-26 17:37:18.040  2172  2172 V MediaPlayer[Native]: disconnect
08-26 17:37:18.041  2172  2172 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-26 17:37:18.042  2172  2172 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 17:37:18.042  2172  2172 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 17:37:18.043  2172  2172 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
,08-26 17:37:18.043  2172  2172 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 17:37:18.043  2172  2172 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 17:37:18.043  2172  2172 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 932695715
08-26 17:37:18.043  2172  2172 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 932695715
08-26 17:37:18.050  2172  2172 I SmartShareClient: [SmartShareManagerClient] terminate service: 2172/MediaPlaybackService/661129366
08-26 17:37:18.052  2172  2172 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 17:37:18.052  2172  2172 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@21aad5a0
08-26 17:37:18.054  2172  2172 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 17:37:18.054  2172  2172 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-26 17:37:18.055  2172  2172 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 17:37:18.055  2172  2172 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-26 17:37:18.056  1035  1932 I ActivityManager: Killing 5687:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-26 17:37:18.057  2172  2172 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
,08-26 17:37:18.068  5663  5663 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-26 17:37:18.068  5663  5663 W System.err: android.os.DeadObjectException
08-26 17:37:18.068  5663  5663 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 17:37:18.068  5663  5663 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 17:37:18.068  5663  5663 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 17:37:18.068  5663  5663 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 17:37:18.068  5663  5663 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 17:37:18.068  5663  5663 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 17:37:18.068  5663  5663 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 17:37:18.068  5663  5663 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 17:37:18.068  5663  5663 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 17:37:18.068  5663  5663 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 17:37:18.068  5663  5663 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:18.069  5663  5663 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:18.069  5663  5663 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 17:37:18.069  5663  5663 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 17:37:18.069  5663  5663 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 17:37:18.069  5663  5663 W System.err: android.os.DeadObjectException
08-26 17:37:18.069  5663  5663 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 17:37:18.069  5663  5663 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 17:37:18.069  5663  5663 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,08-26 17:37:18.069  5663  5663 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 17:37:18.069  5663  5663 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-26 17:37:18.069  5663  5663 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 17:37:18.069  5663  5663 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 17:37:18.069  5663  5663 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 17:37:18.069  5663  5663 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 17:37:18.069  5663  5663 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 17:37:18.069  5663  5663 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:18.069  5663  5663 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:18.069  5663  5663 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 17:37:18.069  5663  5663 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 17:37:18.069  5663  5663 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 17:37:18.069  5663  5663 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 17:37:18.298  1035  1785 W libprocessgroup: failed to open /acct/uid_1000/pid_5687/cgroup.procs: No such file or directory
08-26 17:37:18.298  1035  1785 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 17:37:18.317  5663  5663 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 17:37:18.347  5663  5663 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 17:37:18.419  1035  1921 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6808 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 17:37:18.419  5663  5663 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 17:37:18.485  6808  6808 D UEI.SmartControl: Quickset Services start...
,08-26 17:37:18.488  6808  6808 I UEI.SmartControl: Manufacture = LGE
,08-26 17:37:18.488  6808  6808 D UEI.SmartControl: Id = LGNevo
08-26 17:37:18.489  6808  6808 D UEI.SmartControl: File observer start...
08-26 17:37:18.490  6808  6808 E UEI.SmartControl: IR Port is disabled: false
08-26 17:37:18.490  6808  6808 D UEI.SmartControl: Starting file observer...
08-26 17:37:18.490  6808  6808 D UEI.SmartControl: Extracting JNI libs...
08-26 17:37:18.490  6808  6808 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 17:37:18.591  6808  6808 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 17:37:18.591  6808  6808 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 17:37:18.592  6808  6808 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 17:37:18.630  6808  6808 I UEI.SmartControl: --- Selecting new region: 6,
,08-26 17:37:18.633  6808  6808 I UEI.SmartControl: Model = LG-D855
,08-26 17:37:18.635  6808  6808 D UEI.SmartControl: QS Service created
08-26 17:37:18.651  6808  6808 I UEI.SmartControl: Service initServices...,
,08-26 17:37:18.656  6808  6808 D UEI.SmartControl: QS start get config
,08-26 17:37:18.701  6808  6808 D UEI.SmartControl: Loading JNI Libs...
,08-26 17:37:19.060  6808  6808 I UEI.SmartControl: Supports setup maps: true
08-26 17:37:19.063  6808  6808 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 17:37:19.063  6808  6808 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 17:37:19.063  6808  6808 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 17:37:19.063  6808  6808 I UEI.SmartControl: ### init IR Blaster...
08-26 17:37:19.068  6808  6808 D serial_port: Configuring serial port
08-26 17:37:19.071  6808  6808 E UEI.SmartControl: UEIBLaster setting for 616
08-26 17:37:19.071  6808  6808 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 17:37:19.072  6808  6808 I UEI.SmartControl: configuring settings for MAXQ616
08-26 17:37:19.072  6808  6808 I UEI.SmartControl: Get version...
08-26 17:37:19.088  6808  6834 D UEI.SmartControl: serial port data available: 21
,08-26 17:37:19.114  6808  6808 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 17:37:19.114  6808  6808 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 17:37:19.114  6808  6808 I UEI.SmartControl: QS saving settings...
08-26 17:37:19.115  6808  6808 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 17:37:19.131  6808  6834 D UEI.SmartControl: serial port data available: 4
,08-26 17:37:19.166  6808  6808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 17:37:19.170  6808  6808 E UEI.SmartControl: Services init done
,08-26 17:37:19.170  6808  6808 D UEI.SmartControl: QS Service init finished
08-26 17:37:19.171  6808  6838 I UEI.SmartControl: Device manager: loading config....
08-26 17:37:19.172  6808  6838 D UEI.SmartControl: ----------- loading internal config...
08-26 17:37:19.173  6808  6808 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 17:37:19.173  6808  6808 D UEI.SmartControl: QS Service version code: 201091
08-26 17:37:19.178  6808  6808 D UEI.SmartControl: Service requested: Control
08-26 17:37:19.186  6808  6838 E UEI.SmartControl: Loading SETTINGS...
,08-26 17:37:19.190  6808  6808 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 17:37:19.193  5663  5663 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 17:37:19.195  1035  1962 I ActivityManager: Killing 5663:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 17:37:19.196  6808  6824 I UEI.SmartControl: ------ IControl API: 11
08-26 17:37:19.197  6808  6824 I UEI.SmartControl: Registering callback...
08-26 17:37:19.200  6808  6838 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 17:37:19.204  6808  6837 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 17:37:19.204  6808  6837 D UEI.SmartControl: -----service ready thread exits
08-26 17:37:19.311  1035  1896 W libprocessgroup: failed to open /acct/uid_10112/pid_5663/cgroup.procs: No such file or directory
,08-26 17:37:19.313  6808  6808 D UEI.SmartControl: Internal service binding...
,08-26 17:37:19.489  6645  6645 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-26 17:37:19.490  1035  1995 I ActivityManager: Killing 6298:com.android.calendar/u0a13 (adj 15): empty #17
,08-26 17:37:19.741  1035  1050 W libprocessgroup: failed to open /acct/uid_10013/pid_6298/cgroup.procs: No such file or directory
,08-26 17:37:20.455  6645  6712 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 17:37:23.288  1817  6545 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 17:37:23.293   309  6846 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-26 17:37:23.294   309  6846 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-26 17:37:23.294   309  6846 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-26 17:37:23.549  1817  1817 I ConfigFetchService: fetch service done; releasing wakelock
,08-26 17:37:23.555  1817  1817 I ConfigFetchService: stopping self
,08-26 17:37:23.561  2208  2208 I ConfigService: onDestroy
08-26 17:37:24.139  6808  6836 D serial_port: close(fd = 25)
,08-26 17:37:24.147  6808  6836 I UEI.SmartControl: Serial port is closed.
08-26 17:37:24.165  6808  6839 D UEI.SmartControl: Internal timer expired: 1
08-26 17:37:24.165  6808  6839 D UEI.SmartControl: unbind internal service
,08-26 17:37:24.177  6808  6808 D UEI.SmartControl: Service.onUnbind: IControl
,08-26 17:37:24.182  6808  6808 D UEI.SmartControl: Service.onDestroy
,08-26 17:37:24.182  6808  6808 D UEI.SmartControl: Lock is in USE false
,08-26 17:37:24.182  6808  6808 D UEI.SmartControl: unbind internal service
,08-26 17:37:24.182  6808  6808 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@34227070
08-26 17:37:24.183  6808  6808 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-26 17:37:24.183  6808  6808 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 17:37:24.183  6808  6808 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
,08-26 17:37:24.183  6808  6808 W System.err: ,	at com.uei.control.Service.c(Unknown Source)
08-26 17:37:24.183  6808  6808 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source),
08-26 17:37:24.183  6808  6808 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
,08-26 17:37:24.183  6808  6808 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,08-26 17:37:24.183  6808  6808 W System.err: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 17:37:24.184  6808  6808 W System.err: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:24.184  6808  6808 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 17:37:24.184  6808  6808 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 17:37:24.184  6808  6808 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:24.184  6808  6808 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:24.184  6808  6808 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 17:37:24.184  6808  6808 W System.err: ,	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 17:37:24.184  6808  6808 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@34227070
08-26 17:37:24.184  6808  6808 I UEI.SmartControl: Serial port is closed.
08-26 17:37:24.184  6808  6808 I UEI.SmartControl: Serial port is closed.
08-26 17:37:24.184  6808  6808 D UEI.SmartControl: Blaster closed
08-26 17:37:24.185  6808  6808 D UEI.SmartControl: Shut down QS...
08-26 17:37:24.185  6808  6808 D UEI.SmartControl: Stopping QS lib
08-26 17:37:24.185  6808  6808 D UEI.SmartControl: QS lib stop result = true
08-26 17:37:24.185  6808  6808 D UEI.SmartControl: Stopped QS lib
08-26 17:37:24.188  6808  6808 D UEI.SmartControl: Stopped file observer...
08-26 17:37:24.188  6808  6808 D UEI.SmartControl: QS shutdown complete
,08-26 17:37:27.651  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 17:37:27.651  6695  6799 I jxcore-log: 
,08-26 17:37:27.654  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 17:37:27.654  6695  6799 I jxcore-log: 
08-26 17:37:27.659  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:27.659  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:27.659  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:27.659  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:27.659  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:27.659  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:27.659  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:27.659  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:27.662  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:27.664  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 17:37:27.664  6695  6799 I jxcore-log: 
,08-26 17:37:27.666  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 17:37:27.666  6695  6799 I jxcore-log: 
,08-26 17:37:28.068  2172  2172 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
,08-26 17:37:28.169  6695  6799 D executeNativeTests: Running unit tests
,08-26 17:37:28.251  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:28.251  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 added. We now have 2 listener(s)
,08-26 17:37:28.252  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 17:37:28.254  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:28.254  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:28.254  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:28.254  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:28.254  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 added. We now have 2 listener(s)
08-26 17:37:28.254  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 17:37:28.254  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 17:37:28.256  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:28.260  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 17:37:28.260  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.260  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.260  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-26 17:37:28.260  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:28.260  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:28.260  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:28.260  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:28.260  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:28.261  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:28.262  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:28.263  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.265  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 17:37:28.267  6695  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 17:37:28.267  6695  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 17:37:28.269  6695  6799 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
08-26 17:37:28.270  6695  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-26 17:37:28.270  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 17:37:28.270  6695  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:28.270  6695  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 17:37:28.270  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.271  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.271  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:28.272  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.272  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.272  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:28.272  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 17:37:28.272  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 removed from the list
08-26 17:37:28.272  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.272  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 removed from the list
,08-26 17:37:28.272  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.272  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.273  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.273  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:28.274  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.274  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.274  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:28.274  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
,08-26 17:37:28.277  6695  6799 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
08-26 17:37:28.277  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:28.277  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.277  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.278  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:28.278  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.278  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:28.278  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.278  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.278  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
,08-26 17:37:28.278  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.278  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:28.278  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.278  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.278  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:28.279  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.279  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:28.279  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.279  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 17:37:28.284  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 17:37:28.285  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 17:37:28.285  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-26 17:37:28.285  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 17:37:28.285  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 17:37:28.285  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 17:37:28.285  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 17:37:28.285  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:28.285  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.285  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.286  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.286  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.286  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.286  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list,
08-26 17:37:28.286  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.286  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.286  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.286  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.286  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.286  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:28.286  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.287  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.287  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.287  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.287  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.288  6695  6799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 17:37:28.289  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:28.291  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:28.291  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.291  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.291  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:28.291  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:28.291  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:28.291  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:28.291  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:28.292  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:28.292  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:28.293  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.294  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.294  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:28.294  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 17:37:28.295  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:28.295  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:28.295  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:28.297  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 17:37:28.297  1035  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:28.301  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 17:37:28.304  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 17:37:28.306  6695  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
08-26 17:37:28.307  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:28.307  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:28.308  6695  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 17:37:28.308  6695  6799 I io.jxcore.node.ConnectionHelper: start: OK
08-26 17:37:28.310  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:28.311  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.311  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.311  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.311  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.311  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:28.311  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
,08-26 17:37:28.311  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.311  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.311  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.311  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.311  6695  6799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 17:37:28.313  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:28.315  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 17:37:28.315  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.315  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.315  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:28.315  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:28.315  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:28.315  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:28.315  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:28.316  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-26 17:37:28.316  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:28.317  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.318  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.318  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:28.318  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 17:37:28.318  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:28.318  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:28.318  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:28.321  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:28.321  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:28.322  6695  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 17:37:28.322  6695  6799 I io.jxcore.node.ConnectionHelper: start: OK,
08-26 17:37:28.323  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.323  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.323  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.323  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.323  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.323  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:28.323  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.323  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.323  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.323  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.323  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.324  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:28.324  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.324  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.324  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.325  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.325  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.325  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:28.325  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.326  6695  6799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 17:37:28.327  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:28.329  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:28.329  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.329  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.329  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:28.329  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:28.329  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:28.329  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:28.329  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:28.330  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:28.330  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:28.331  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.331  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:28.332  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:28.332  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:28.332  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:28.332  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:28.332  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.335  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 17:37:28.335  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:28.336  6695  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 17:37:28.336  6695  6799 I io.jxcore.node.ConnectionHelper: start: OK
08-26 17:37:28.336  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.336  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.336  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.337  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.337  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.337  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.337  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.337  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.337  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:28.337  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.337  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.337  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.337  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.337  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.338  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.338  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:28.339  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.339  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.340  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.340  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.340  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.340  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.341  6695  6799 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 17:37:28.341  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.341  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.341  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.341  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.341  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.342  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.342  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.342  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.342  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.342  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.342  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.342  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.342  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.342  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.342  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.342  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.343  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.343  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.343  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.343  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.344  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 17:37:28.344  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.344  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: N,OT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.344  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.344  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.344  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.344  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.344  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.344  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.344  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.345  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.345  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.345  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.345  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.345  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.345  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.345  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.345  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.346  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.346  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.346  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.346  6695  6799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 17:37:28.347  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.347  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.347  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.347  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.347  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.347  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.347  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.347  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.347  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.347  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.347  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.347  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.347  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.347  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.348  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.348  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.348  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.348  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.348  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.348  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.349  6695  6799 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 17:37:28.349  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.349  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.349  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.357  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.357  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.357  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.357  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.357  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.357  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.357  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.357  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.357  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.357  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.357  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.359  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.360  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.360  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.361  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.361  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.361  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.362  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 17:37:28.364  6695  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 17:37:28.364  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 17:37:28.364  6695  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:28.365  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 17:37:28.365  6695  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 17:37:28.365  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.365  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.365  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.365  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.366  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.366  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.367  1035  1092 I ActivityManager: Waited long enough for: ServiceRecord{2e940530 u0 com.google.android.gms/.wearable.service.WearableService}
08-26 17:37:28.368  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.368  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.368  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.368  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.369  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.369  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.369  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.369  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.370  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.370  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.371  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.371  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.371  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.371  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.374  6695  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 17:37:28.374  6695  6799 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 17:37:28.374  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 17:37:28.379  6695  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 17:37:28.379  6695  6799 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 17:37:28.379  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 17:37:28.379  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 17:37:28.379  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 17:37:28.379  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 17:37:28.379  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 17:37:28.380  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 17:37:28.381  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 17:37:28.381  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 17:37:28.381  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 17:37:28.381  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 17:37:28.381  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 17:37:28.381  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 17:37:28.382  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 17:37:28.382  6695  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 17:37:28.382  6695  6799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 17:37:28.383  6695  6799 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 17:37:28.383  6695  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 17:37:28.383  6695  6799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 17:37:28.383  6695  6799 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 17:37:28.383  6695  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 17:37:28.383  6695  6799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 17:37:28.383  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 17:37:28.385  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 17:37:28.386  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 17:37:28.386  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 17:37:28.387  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 17:37:28.387  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 17:37:28.387  6695  6799 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 17:37:28.387  6695  6799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 17:37:28.388  6695  6799 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 17:37:28.388  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.388  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.388  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.388  6695  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-26 17:37:28.388  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.388  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.388  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.389  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 17:37:28.389  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.390  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.390  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.390  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.390  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.390  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.390  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.390  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.391  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.391  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.392  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.392  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.392  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.392  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.392  6695  6854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-26 17:37:28.392  6695  6854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821)
08-26 17:37:28.393  6695  6854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
08-26 17:37:28.393  6695  6799 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 17:37:28.393  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.394  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.394  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.394  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.394  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.394  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.394  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.394  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.394  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.395  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.395  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.395  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.395  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.395  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.397  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.397  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.398  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.398  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.398  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.399  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.400  6695  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 17:37:28.401  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.401  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.402  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.402  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.402  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.402  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.402  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.402  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.402  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.402  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.402  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.402  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.402  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.402  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.404  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.404  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.405  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.405  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.405  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.405  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.406  6695  6799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 17:37:28.406  6695  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 17:37:28.407  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 17:37:28.408  6695  6799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 17:37:28.408  6695  6799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 17:37:28.408  6695  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 17:37:28.408  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 17:37:28.409  6695  6799 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 17:37:28.409  6695  6799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 17:37:28.409  6695  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 17:37:28.409  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 17:37:28.409  6695  6799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 17:37:28.409  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.410  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.410  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.410  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.410  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.410  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.410  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.410  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.410  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.410  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.411  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.411  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.411  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.411  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.412  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.413  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.413  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.413  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.413  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.413  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.414  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.414  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.414  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.414  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.414  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.414  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.414  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.414  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.414  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.415  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.415  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.415  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.415  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.415  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.415  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.415  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.415  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.415  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.415  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.415  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.415  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.415  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.416  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.416  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.416  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.416  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.416  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.416  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.416  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.416  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.417  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:28.417  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.417  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.417  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.417  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.420  6695  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 17:37:28.420  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:28.421  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 17:37:28.422  6695  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 17:37:28.423  6695  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 17:37:28.423  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 17:37:28.423  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 17:37:28.424  6695  6695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 17:37:28.425  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.425  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 17:37:28.426  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 17:37:28.426  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 17:37:28.426  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.426  6695  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 17:37:28.426  6695  6695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 17:37:28.426  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.426  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.426  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:28.426  6695  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:28.427  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:28.428  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 17:37:28.428  6695  6855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 17:37:28.429  6695  6855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 17:37:28.429  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:28.429  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:28.429  6695  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 17:37:28.429  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.429  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.430  6695  6799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:28.431  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.431  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:28.431  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:28.431  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.431  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.431  6695  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 17:37:28.431  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.431  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.431  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:28.431  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.431  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.431  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.431  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.431  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.431  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.431  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.431  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.431  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.431  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.433  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.433  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.433  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.433  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.435  6695  6799 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 17:37:28.435  6695  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 17:37:28.435  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 17:37:28.437  6695  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:28.438  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.438  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.438  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.439  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.439  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.439  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.439  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.439  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.439  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.439  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.439  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.439  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.439  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.439  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.440  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.440  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.441  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.441  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.442  1035  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:28.443  1035  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:28.444  1035  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:28.445  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.445  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.445  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.445  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.445  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.445  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.445  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.445  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.445  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.445  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.445  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.445  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.445  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.445  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.448  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.448  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:28.448  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.448  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.451  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:28.451  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:28.451  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:28.451  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:28.451  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.451  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.453  6695  6799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21ecd07 not in the list
08-26 17:37:28.453  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:28.453  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.454  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:28.454  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.454  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.454  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:28.454  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:28.455  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:28.455  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:28.455  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:28.455  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ff9e34 not in the list
08-26 17:37:28.457  6695  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 17:37:28.457  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-26 17:37:28.458  6695  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 17:37:28.458  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 17:37:28.458  6695  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-26 17:37:28.458  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 17:37:28.462  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 17:37:28.462  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-26 17:37:28.465  6695  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 17:37:28.465  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 17:37:28.466  6695  6799 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-26 17:37:28.466  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 17:37:28.466  6695  6799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 17:37:28.466  6695  6799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-26 17:37:28.467  6695  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 17:37:28.468  6695  6799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 17:37:28.469  6695  6799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-26 17:37:28.469  6695  6799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 17:37:28.469  6695  6799 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 17:37:28.469  6695  6799 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing,
08-26 17:37:28.470  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:28.470  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@862c215 added. We now have 2 listener(s)
08-26 17:37:28.470  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-26 17:37:28.472  6695  6799 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 17:37:28.475  1035  1962 D WifiServiceImplEx: setWifiEnabled: true pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 17:37:28.476  1035  1962 D WifiService: setWifiEnabled: true pid=6695, uid=10118
08-26 17:37:28.476  1035  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 17:37:28.479  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:28.479  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a6d392a added. We now have 3 listener(s)
08-26 17:37:28.479  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:28.484  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:28.484  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2868531b added. We now have 4 listener(s)
08-26 17:37:28.484  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:28.492  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:28.492  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f9fccb8 added. We now have 5 listener(s)
08-26 17:37:28.492  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:28.495  1035  1896 D WifiServiceImplEx: setWifiEnabled: false pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 17:37:28.496  1035  1896 D WifiService: setWifiEnabled: false pid=6695, uid=10118
08-26 17:37:28.496  1035  1896 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 17:37:28.501  6695  6853 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-26 17:37:28.501  6695  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-26 17:37:28.509  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 17:37:28.510  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 17:37:28.510  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-26 17:37:28.512  1035  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 17:37:28.513  1035  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:28.513  1035  2016 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2f9964f1 mBinding = false
08-26 17:37:28.513  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 17:37:28.513  1035  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 17:37:28.514  1035  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 17:37:28.514  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 17:37:28.514  1035  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 17:37:28.514  1035  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 17:37:28.514  1035  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 17:37:28.515  1035  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 17:37:28.515  1035  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 17:37:28.522  1035  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 17:37:28.523  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.523  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.523  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 17:37:28.523  2700  2700 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 17:37:28.524  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 17:37:28.524  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 17:37:28.524  1035  1540 D WifiNative-wlan0: SET ps 1: returned true
08-26 17:37:28.525  1035  2860 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.529   309   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 17:37:28.529  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 17:37:28.533  1035  1099 D BluetoothManagerService: Message: 2
08-26 17:37:28.533  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 17:37:28.534  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 17:37:28.534  1035  1099 D BluetoothManagerService: Sending off request.
08-26 17:37:28.535  3865  3979 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 17:37:28.536  3865  3948 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 17:37:28.536  3865  3948 D BluetoothAdapterProperties: Setting state to 13
08-26 17:37:28.536  3865  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 17:37:28.537  3865  3948 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 17:37:28.537  3865  3948 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 17:37:28.538  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:28.541  1035  1099 D BluetoothManagerService: Message: 60
08-26 17:37:28.541  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 17:37:28.541  1035  1099 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 17:37:28.543  3865  3952 D BluetoothAdapterProperties: Scan Mode:20
08-26 17:37:28.544  3865  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 17:37:28.545  3865  4179 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:28.545  3865  3948 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 17:37:28.545  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,08-26 17:37:28.548  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 17:37:28.548  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:28.549  3865  4053 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 17:37:28.550  3865  4239 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 17:37:28.551  3865  4241 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:28.552  3865  4237 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:28.552  3865  3865 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:28.553  3865  3865 D BluetoothMapService: STATE_TURNING_OFF
08-26 17:37:28.553  3865  3865 V BtOppService: Receiver DISABLED_ACTION 
08-26 17:37:28.553  3865  3865 V BluetoothMapService: Handler(): got msg=4
08-26 17:37:28.553  3865  3865 D BluetoothMapService: MAP Service closeService in
08-26 17:37:28.553  3865  3865 D BluetoothMapMasInstance: MAP Service shutdown
08-26 17:37:28.554  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.555  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:28.555  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.555  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.555  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:28.555  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:28.555  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:28.555  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:28.555  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:28.558  3865  4177 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 17:37:28.558  3865  4177 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:28.558  3865  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 17:37:28.558  3865  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 17:37:28.558  3865  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 17:37:28.558  3865  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 17:37:28.558  3865  4177 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 17:37:28.558  3865  4177 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 17:37:28.559  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.559  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:28.559  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:28.560  3865  3865 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 17:37:28.560  3865  3865 V BluetoothMapService: MAP Service closeService out
08-26 17:37:28.560  3865  3865 I BtOppRfcommListener: stopping Accept Thread
08-26 17:37:28.561  3865  3865 V BtOppRfcommListener: close mBtServerSocket
08-26 17:37:28.562  3865  4237 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 17:37:28.562  3865  3865 V BtOppRfcommListener: waiting for thread to terminate
08-26 17:37:28.562  3865  3865 V BtOppRfcom,mListener: done waiting for thread to terminate
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 17:37:28.563  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 17:37:28.563  3865  4053 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-26 17:37:28.570  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.578  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:28.582  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.582  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:28.582  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.582  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.582  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:28.582  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:28.582  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:28.582  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:28.582  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:28.583  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.583  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:28.584  1035  1648 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-26 17:37:28.585  1035  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.585  1035  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.585  1035  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 17:37:28.586  1035  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.586  1035  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 17:37:28.587  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 17:37:28.588  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.588  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-26 17:37:28.601  1035  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6866 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 17:37:28.602  3865  3865 V BtOppService: onDestroy
,08-26 17:37:28.607  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.607  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:28.607  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.607  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.607  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:28.607  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:28.607  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:28.607  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:28.607  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:28.608  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.608  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:28.610  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.610  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:28.610  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.610  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.610  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:28.610  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:28.610  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:28.610  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:28.610  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:28.610  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.610  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:28.640  1035  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 17:37:28.640  1035  1546 D DSQN    : disableDataServiceNotify
08-26 17:37:28.640  1035  1546 D DSQN    : stop dsqn bin
08-26 17:37:28.641   309  6890 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-26 17:37:28.641  1035  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 17:37:28.641  1035  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-26 17:37:28.645  1035  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6886 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-26 17:37:28.646  1035  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 17:37:28.646  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:28.646  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:28.647  1035  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:28.647  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 17:37:28.647  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 17:37:28.648  1035  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 17:37:28.648  1035  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 17:37:28.648  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 17:37:28.648  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:28.648  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 17:37:28.648  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:28.649  1035  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:28.649  1035  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:28.649  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:28.649  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 17:37:28.650  1035  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.650  1035  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.650  1035  2850 D Net,workMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 17:37:28.652  1035  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:28.652  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:28.652  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:28.653  1035  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:28.653  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:28.654  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:28.654  1035  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 17:37:28.655  1035  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:28.655  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:28.655  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:28.656  1035  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:28.656  1035  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:28.656  1035  1538 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.656  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.656  1035  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@51acc42
08-26 17:37:28.656  1035  1538 D LGWifiP2pService: P2pDisablingState
08-26 17:37:28.657  1035  1538 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.657  1035  1538 D LGWifiP2pService: p2p socket connection lost
08-26 17:37:28.657  1035  1538 D LGWifiP2pService: P2pDisabledState
08-26 17:37:28.649  1035  1546 D NetworkManagementService: Removing idletimer
08-26 17:37:28.657  1035  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:28.658  1035  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 17:37:28.659  1035  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 17:37:28.659  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.659  1035  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.659  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 17:37:28.659  2700  2700 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 17:37:28.660  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 17:37:28.660  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 17:37:28.660  1035  1540 D WifiNative-wlan0: SET ps 1: returned true
08-26 17:37:28.660   309   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 17:37:28.664  1035  1540 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 17:37:28.667  1035  1540 D WifiNative-p2p0: TERMINATE: returned true
08-26 17:37:28.668  1035  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 17:37:28.668  1035  1540 E WifiStateMachine: useWiFiOffloading() : false
08-26 17:37:28.668  1035  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 17:37:28.673  1035  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 17:37:28.675  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 17:37:28.676  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 17:37:28.676  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 17:37:28.676  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 17:37:28.676  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 17:37:28.676  1035  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 17:37:28.676  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 17:37:28.676  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 17:37:28.676  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 17:37:28.678  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 17:37:28.679  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-26 17:37:28.680  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:28.680  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:28.680  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 17:37:28.681  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 17:37:28.682  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:28.682  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:28.682  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 17:37:28.682  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 17:37:28.682  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-26 17:37:28.682  1035  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.682  1035  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.684  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 17:37:28.684  1941  1941 D WfdsService: WifiP2pState is changed : false
08-26 17:37:28.684  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 17:37:28.684  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:28.684  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:28.684  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 17:37:28.684  1941  2242 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 17:37:28.684  1941  2242 D WfdsService: Set the WFDS Monitor: false
08-26 17:37:28.685  1941  2242 D WfdsMonitor: WFDS Monitor is stopped
08-26 17:37:28.685  1941  2242 D WfdsService: STATE : WfdsDisabledState - enter
08-26 17:37:28.685  1941  2758 D CtrlSupplicant: Received on exit socket, terminate
08-26 17:37:28.685  1941  2758 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 17:37:28.685  1941  2758 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 17:37:28.685  1941  2758 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 17:37:28.686  1941  2247 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 17:37:28.686  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 17:37:28.686  1941  2242 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 17:37:28.686  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.686  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:28.686  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.686  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.686  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:28.686  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:28.686  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
0,8-26 17:37:28.686  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:28.686  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:28.686  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.686  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:28.688  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.688  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:28.688  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:28.688  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:28.688  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:28.688  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:28.688  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:28.688  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:28.688  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:28.688  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 17:37:28.688  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:28.688  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 17:37:28.690  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:28.690  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:28.705  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 17:37:28.706  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:28.706  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:28.718  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 17:37:28.719  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:28.719  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:28.719  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:28.719  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:28.720  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:28.721  1035  1932 I art     : Explicit concurrent mark sweep GC freed 40103(1992KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.077ms total 151.195ms
08-26 17:37:28.723  3865  3865 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 17:37:28.732  1035  2860 D DhcpStateMachine: StoppedState
,08-26 17:37:28.733  1035  2860 D DhcpStateMachine: StoppedState{ when=-73ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:28.733  1035  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 17:37:28.734  1035  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 17:37:28.740  6866  6866 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 17:37:28.740  6866  6866 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-26 17:37:28.740  6866  6866 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 17:37:28.740  6866  6866 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-26 17:37:28.741  6866  6866 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 17:37:28.742  6866  6866 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 17:37:28.743  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:28.743  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:28.744  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 17:37:28.746  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 17:37:28.746  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:28.747  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:28.748  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:28.761  2700  2700 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 17:37:28.761  2700  2700 I wpa_supplicant: monitor socket send errors count : 1
08-26 17:37:28.761  2700  2700 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
,08-26 17:37:28.762  1035  2755 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 17:37:28.762  1035  2755 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 17:37:28.775  6886  6886 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-26 17:37:28.775  6886  6886 W LG Account v2.2: No ProfileInfo entries
08-26 17:37:28.775  6886  6886 I LG Account v2.2: isEnabled: false
08-26 17:37:28.775  6886  6886 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 17:37:28.775  6886  6886 I Feature : [Lifetracker]Country: EU
08-26 17:37:28.775  6886  6886 I Feature : [Lifetracker]Operator: OPEN
08-26 17:37:28.775  6886  6886 I Feature : [Lifetracker]Ranking support: false
08-26 17:37:28.776  6886  6886 I Feature : [Lifetracker]Comfort support: false
08-26 17:37:28.776  6886  6886 I Feature : [Lifetracker]Accessory: true
08-26 17:37:28.776  6886  6886 I Feature : [Lifetracker]Health device: true
08-26 17:37:28.776  6886  6886 I Feature : [Lifetracker]Extra Pedometer: false
08-26 17:37:28.776  6886  6886 I Feature : [Lifetracker]Blood glucose device: false
08-26 17:37:28.776  6886  6886 I Feature : [Lifetracker]Device Number: 3
08-26 17:37:28.783  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:28.799  2700  2700 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 17:37:28.799  1035  2755 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 17:37:28.799  1035  2755 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 17:37:28.799  1035  2755 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 17:37:28.799  2700  2700 W wpa_supplicant: USIM:  scard_deinit function
08-26 17:37:28.800  1035  2755 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 17:37:28.800  1035  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116829
08-26 17:37:28.800  1035  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116830
,08-26 17:37:28.800  1035  2755 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:28.800  1035  2755 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 17:37:28.801  1035  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116830  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 17:37:28.801  1035  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116831  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 17:37:28.801  1035  1099 D Tethering: InitialState.processMessage what=4
08-26 17:37:28.807  1035  1576 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6906 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 17:37:28.808  1035  1576 I ActivityManager: Killing 6255:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-26 17:37:28.848  1035  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 17:37:28.849  2700  2700 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 17:37:28.849  1035  2755 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 17:37:28.849  1035  2755 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 17:37:28.850  1035  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-26 17:37:28.850  1035  2755 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 17:37:28.851  1035  1386 V AlarmManager: RTC_WAKEUP set : Alarm{11bc31f3 type 0 when 1472225848814 com.android.vending} when 1472225848814
08-26 17:37:28.851  1035  1050 W libprocessgroup: failed to open /acct/uid_10014/pid_6255/cgroup.procs: No such file or directory
08-26 17:37:28.885  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 17:37:28.889  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 17:37:28.890  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:28.899  1035  1932 V SIM_STK : Menu title from STK is T-Mobile
,08-26 17:37:28.927  6866  6866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 17:37:28.931  6695  6695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 17:37:28.933  3865  3865 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 17:37:28.934  3865  3865 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:28.934  3865  3865 V BluetoothPbapReceiver: ***********state = 13
08-26 17:37:28.935  3865  3865 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 17:37:28.937  3865  3865 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:28.937  3865  3865 V BluetoothPbapService: state: 13
08-26 17:37:28.937  3865  3865 V BluetoothPbapService: Pbap Service closeService in
08-26 17:37:28.939  3865  3865 V BluetoothPbapService: successfully stopped pbap service
08-26 17:37:28.939  3865  3865 V BluetoothPbapService: Pbap Service closeService out
,08-26 17:37:28.939  3865  3865 V BluetoothPbapService: Pbap Service onDestroy
08-26 17:37:28.940  3865  3865 V BluetoothPbapService: Pbap Service closeService in
08-26 17:37:28.940  3865  3865 V BluetoothPbapService: Pbap Service closeService out
08-26 17:37:28.940  3865  3865 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 17:37:28.941  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:28.942  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 17:37:28.951  1035  1540 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 17:37:28.951  1035  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 17:37:28.951  1035  1540 E WifiStateMachine: useWiFiOffloading() : false
08-26 17:37:28.951  1035  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 17:37:28.951  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-26 17:37:28.952  1941  2242 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 17:37:28.952  1941  2242 D WfdsService: Set the WFDS Monitor: false
08-26 17:37:28.952  1941  2242 D WfdsMonitor: WFDS Monitor is stopped
08-26 17:37:28.953  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-26 17:37:28.953  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:28.953  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 17:37:28.954  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 17:37:28.954  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 17:37:28.956  2479  2479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:28.957  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.958  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:28.984  6866  6866 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 17:37:28.984  6866  6866 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 17:37:28.994  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:29.002  1035  1099 D BluetoothManagerService: Message: 20
08-26 17:37:29.002  1035  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@968ecae:true
,08-26 17:37:29.013  1035  1099 D BluetoothManagerService: Message: 30
08-26 17:37:29.018  1035  1099 D BluetoothManagerService: Message: 30
,08-26 17:37:29.021  6866  6866 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 17:37:29.022  6866  6866 D BluetoothMap: Create BluetoothMap proxy object
08-26 17:37:29.023  1035  1099 D BluetoothManagerService: Message: 30
08-26 17:37:29.027  1035  1099 D BluetoothManagerService: Message: 30
08-26 17:37:29.030  6866  6866 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 17:37:29.031  6866  6866 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-26 17:37:29.048  6866  6866 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-26 17:37:29.052  6866  6866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-26 17:37:29.063  6866  6866 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:29.076  6866  6866 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 17:37:29.079  6866  6866 D BluetoothInputDevice: Proxy object connected
08-26 17:37:29.080  6866  6866 D HidProfile: Bluetooth service connected
08-26 17:37:29.081  6866  6866 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 17:37:29.081  6866  6866 D PanProfile: Bluetooth service connected
08-26 17:37:29.082  6866  6866 D BluetoothMap: Proxy object connected
08-26 17:37:29.082  6866  6866 D MapProfile: Bluetooth service connected
08-26 17:37:29.082  6866  6866 D BluetoothMap: getConnectedDevices()
08-26 17:37:29.083  6866  6866 D BluetoothMap: Bluetooth is Not enabled
08-26 17:37:29.084  6866  6866 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 17:37:29.085  6866  6866 D BluetoothPermissionRequest: onReceive
08-26 17:37:29.089  6866  6866 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 17:37:29.090  6120  6120 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-26 17:37:29.094  1035  1956 I ActivityManager: Killing 6363:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 17:37:29.122  1035  1962 W libprocessgroup: failed to open /acct/uid_10004/pid_6363/cgroup.procs: No such file or directory
,08-26 17:37:29.131  1035  1956 I ActivityManager: Killing 6564:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-26 17:37:29.133  6866  6866 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 17:37:29.155  1035  1540 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
,08-26 17:37:29.156  1035  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-26 17:37:29.181  3865  3865 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 17:37:29.181  3865  3865 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-26 17:37:29.182  3865  3865 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 17:37:29.183  1035  2016 W libprocessgroup: failed to open /acct/uid_10008/pid_6564/cgroup.procs: No such file or directory
08-26 17:37:29.266  1035  1896 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6935 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 17:37:29.281  3865  3865 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:29.281  3865  3865 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 17:37:29.284  3865  3865 V BluetoothFtpService: Ftp Service onStartCommand
,08-26 17:37:29.286  3865  3865 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:29.287  3865  3865 V BluetoothFtpService: Ftp Service closeService
08-26 17:37:29.287  3865  3865 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 17:37:29.288   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 21.700ms
08-26 17:37:29.291  3865  3865 V BluetoothFtpService: successfully stopped ftp service
08-26 17:37:29.291  3865  3865 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 17:37:29.292  3865  3865 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 17:37:29.292  3865  3865 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 17:37:29.292  3865  3865 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:29.292  3865  3865 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 17:37:29.292  3865  3865 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 17:37:29.296  3865  3865 V BluetoothFtpService: Ftp Service onDestroy
08-26 17:37:29.296  3865  3865 V BluetoothFtpService: Ftp Service closeService
,08-26 17:37:29.306   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 367us total 17.014ms
08-26 17:37:29.321   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 291us total 14.450ms
,08-26 17:37:29.363  1035  1785 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6952 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 17:37:29.372  3865  3865 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:29.372  3865  3865 V BluetoothSapService: state: 13
08-26 17:37:29.372  3865  3865 V BluetoothSapService: Stopping SAP server process
08-26 17:37:29.374  3865  3865 V BluetoothSapService: Sap Service closeSapService in
08-26 17:37:29.374  3865  3865 V BluetoothSapService: Close listen Socket : 
08-26 17:37:29.374  3865  3865 V BluetoothSapService: Close rfcomm Socket : 
08-26 17:37:29.374  3865  3865 V BluetoothSapService: Close sapd  Socket : 
08-26 17:37:29.377  3865  3865 V BluetoothSapService: Sap Service closeSapService out
08-26 17:37:29.377  3865  3865 V BluetoothSapService: Sap Service onDestroy
08-26 17:37:29.377  3865  3865 V BluetoothSapService: Sap Service closeSapService in
08-26 17:37:29.378  3865  3865 V BluetoothSapService: Close listen Socket : 
08-26 17:37:29.378  3865  3865 V BluetoothSapService: Close rfcomm Socket : 
08-26 17:37:29.378  3865  3865 V BluetoothSapService: Close sapd  Socket : 
08-26 17:37:29.379  3865  3865 V BluetoothSapService: Sap Service closeSapService out
08-26 17:37:29.396  6935  6935 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 17:37:29.417  6935  6935 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-26 17:37:29.427  6952  6952 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 17:37:29.442  1035  1962 I ActivityManager: Killing 6049:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-26 17:37:29.443  6935  6935 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 17:37:29.443  6935  6935 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 17:37:29.443  6935  6935 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 17:37:29.444  6935  6935 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 17:37:29.444  6935  6935 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 17:37:29.445  6935  6935 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 17:37:29.449  6935  6935 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 17:37:29.497  1035  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_6049/cgroup.procs: No such file or directory
,08-26 17:37:29.510  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 17:37:29.518  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:29.550  6935  6935 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 17:37:29.553  6935  6935 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 17:37:29.557  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:29.558  6935  6935 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 17:37:29.562  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 17:37:29.562  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 17:37:29.562  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:29.565  3865  4053 W bt-btif : ag scb idx 1 not allocated
08-26 17:37:29.565  3865  3952 D bt_hci_bdroid: cleanup
08-26 17:37:29.565  3865  4053 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:29.565  3865  4053 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:29.566  3865  4162 I bt_userial_mct: exiting userial_read_thread
08-26 17:37:29.566  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:29.566  3865  4162 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 17:37:29.566  3865  4053 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:29.566  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:29.566  3865  4053 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:29.566  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:29.566  3865  4053 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:29.566  3865  4053 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:29.566  3865  4053 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:29.566  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 17:37:29.566  3865  3952 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 17:37:29.566  3865  4053 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 17:37:29.566  3865  4055 I bt_lpm  : LPM is already off!!!
08-26 17:37:29.566  3865  4055 I bt_vendor: hw_epilog_process
08-26 17:37:29.567  3865  3952 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 17:37:29.567  3865  3952 D bt_userial_mct: userial_close
08-26 17:37:29.567  3865  3952 E bt_userial_mct: pthread_join() FAILED result:3
08-26 17:37:29.567  3865  3952 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 17:37:29.573  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:29.584  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 17:37:29.584  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 17:37:29.586  6935  6935 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 17:37:29.589  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:29.595  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 17:37:29.595  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 17:37:29.595  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:29.598  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:29.606  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:29.616  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:29.617  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 17:37:29.621  6935  6935 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 17:37:29.658  3865  3952 D bt_hci_bdroid: set_power 0
08-26 17:37:29.658  3865  3952 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 17:37:29.658  3865  3952 I bt_vendor: bluetooth satus is on
08-26 17:37:29.658  3865  3952 I bt_vendor: bt-vendor : resetting BT status
08-26 17:37:29.658  3865  3952 I bt_vendor: Starting hciattach daemon
08-26 17:37:29.658  3865  3952 I bt_vendor: try to set false
,08-26 17:37:29.660  3865  3952 I bt_vendor: Starting hciattach daemon
08-26 17:37:29.660  3865  3952 I bt_vendor: try to set false
08-26 17:37:29.660  3865  3952 I bt_vendor: cleanup
08-26 17:37:29.663  3865  4053 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 17:37:29.667  3865  3952 I GKI_LINUX: GKI_exit_task 0 done
08-26 17:37:29.667  3865  3952 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 17:37:29.669  3865  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 17:37:29.707  1035  1956 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6976 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 17:37:29.712  3865  3865 D HeadsetService: Received stop request...Stopping profile...
08-26 17:37:29.713  3865  3865 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 17:37:29.713  3865  3865 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 17:37:29.713  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b1e61ed
08-26 17:37:29.714  3865  3978 D HeadsetStateMachine: Exit Disconnected: -1
08-26 17:37:29.719  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:29.719  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 17:37:29.719  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:29.720  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:29.720  1852  1852 D BluetoothHeadset: Proxy object disconnected
,08-26 17:37:29.722  3865  3865 D A2dpService: Received stop request...Stopping profile...
08-26 17:37:29.722  3865  4035 D A2dpStateMachine: Exit Disconnected: -1
08-26 17:37:29.723  3865  3865 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 17:37:29.726  3865  3865 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 17:37:29.726  3865  3865 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 17:37:29.726  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b1e61ed
08-26 17:37:29.727  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-26 17:37:29.727  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 17:37:29.729  3865  3865 D HidService: Received stop request...Stopping profile...
08-26 17:37:29.729  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b1e61ed
08-26 17:37:29.730  3865  3948 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 17:37:29.731  3865  3865 D HeadsetStateMachine: Unbinding service...
08-26 17:37:29.732  3865  3865 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,08-26 17:37:29.732  3865  3865 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 17:37:29.732  3865  3865 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 17:37:29.732  3865  3865 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 17:37:29.732  6866  6866 D BluetoothInputDevice: Proxy object disconnected
,08-26 17:37:29.732  3865  3865 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 17:37:29.732  3865  3865 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 17:37:29.732  3865  3865 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 17:37:29.732  6866  6866 D HidProfile: Bluetooth service disconnected
08-26 17:37:29.733  3865  3865 D HealthService: Received stop request...Stopping profile...
08-26 17:37:29.733  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b1e61ed
08-26 17:37:29.737  3865  3865 D PanService: Received stop request...Stopping profile...
08-26 17:37:29.738  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b1e61ed
08-26 17:37:29.739  6866  6866 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 17:37:29.739  6866  6866 D PanProfile: Bluetooth service disconnected
08-26 17:37:29.739  3865  3865 I BluetoothA2dpServiceJni: cleanupNative
08-26 17:37:29.739  3865  4036 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 17:37:29.740  3865  3865 I GKI_LINUX: GKI_exit_task 2 done
08-26 17:37:29.740  3865  3865 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 17:37:29.740  3865  3865 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:29.740  3865  3865 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 17:37:29.740  3865  3865 D BtGatt.GattService: stop()
08-26 17:37:29.740  3865  3865 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 17:37:29.741  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b1e61ed
08-26 17:37:29.742  3865  3865 D BluetoothMapService: Received stop request...Stopping profile...
08-26 17:37:29.742  3865  3865 D BluetoothMapService: stop()
08-26 17:37:29.743  3865  3865 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 17:37:29.743  3865  3865 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 17:37:29.743  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b1e61ed
08-26 17:37:29.744  6866  6866 D BluetoothMap: Proxy object disconnected
08-26 17:37:29.744  6866  6866 D MapProfile: Bluetooth service disconnected
08-26 17:37:29.744  3865  3865 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 17:37:29.744  3865  3865 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 17:37:29.745  3865  3865 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 17:37:29.745  3865  3865 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 17:37:29.745  3865  3865 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 17:37:29.745  3865  3865 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 17:37:29.745  3865  3865 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 17:37:29.746  3865  3865 V BluetoothMapService: Handler(): got msg=4
08-26 17:37:29.746  3865  3865 D BluetoothMapService: MAP Service closeService in
08-26 17:37:29.746  3865  3865 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 17:37:29.746  3865  3865 V BluetoothMapService: MAP Service closeService out
08-26 17:37:29.746  3865  3865 D BluetoothMapService: cleanup()
08-26 17:37:29.746  3865  3865 D BluetoothMapService: MAP Service closeService in
08-26 17:37:29.746  3865  3865 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 17:37:29.747  3865  3865 V BluetoothMapService: MAP Service closeService out
08-26 17:37:29.747  3865  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 17:37:29.747  3865  3948 D BluetoothAdapterProperties: Setting state to 10
08-26 17:37:29.747  3865  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 17:37:29.747  1035  1099 D BluetoothManagerService: Message: 60
08-26 17:37:29.748  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 17:37:29.748  1035  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 17:37:29.748  3865  3948 I BluetoothAdapterState: Entering OffState
08-26 17:37:29.748  1852  3981 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:29.749  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:29.749  6866  6885 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 17:37:29.750  6866  6883 D BluetoothMap: onBluetoothStateChange: up=false
08-26 17:37:29.751  1035  1099 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:29.751  6866  6885 D BluetoothPan: onBluetoothStateChange on: false
08-26 17:37:29.751  1035  1099 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 17:37:29.752  1852  2460 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:29.752  6866  6883 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 17:37:29.753  1035  1099 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 17:37:29.753  1035  1099 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 17:37:29.756  1035  1099 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 17:37:29.756  1035  1099 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 17:37:29.756  1035  1099 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2f9964f1 mBinding = false
08-26 17:37:29.756  1035  1099 D BluetoothManagerService: Sending unbind request.
08-26 17:37:29.759  1035  1099 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 17:37:29.765  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:29.765  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 17:37:29.766  3865  3952 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 17:37:29.767  3865  3865 I GKI_LINUX: GKI_exit_task 1 done
08-26 17:37:29.767  3865  3865 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 17:37:29.767  1941  2103 D LGBluetoothAPIService: Message: 2
08-26 17:37:29.767  3865  3865 I BluetoothServiceJni: cleanupNative: return from cleanup,
08-26 17:37:29.767  1941  2103 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1d525354 mBinding = false
08-26 17:37:29.768  3865  3865 I art     : --- WEIRD: removing null entry 246
08-26 17:37:29.768  1941  2103 D LGBluetoothAPIService: Sending unbind request.
08-26 17:37:29.768  3865  3865 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 17:37:29.768  3865  3865 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-26 17:37:29.773  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:29.774  3865  3865 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 17:37:29.774  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:29.775  6866  6866 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 17:37:29.775  1604  1604 D BluetoothAdapter: 86988828: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:29.775  1604  1604 D BluetoothAdapter: 86988828: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:29.776  6866  6866 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 17:37:29.776  6866  6866 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 17:37:29.776  3865  3865 I art     : System.exit called, status: 0
08-26 17:37:29.776  3865  3865 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 17:37:29.788  6866  6866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 17:37:29.794  6866  6866 D DockEventReceiver: finishStartingService: stopping service
08-26 17:37:29.804   313  1383 V AudioFlinger: 3865 died, releasing its sessions
08-26 17:37:29.804   313  1383 V AudioFlinger:  pid 1852 @ 0
08-26 17:37:29.804   313  1383 V AudioFlinger:  pid 3480 @ 1
08-26 17:37:29.804   313  1383 V AudioFlinger:  pid 3480 @ 2
,08-26 17:37:29.806  6866  6866 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 17:37:29.838  1035  1932 I ActivityManager: Process com.android.bluetooth (pid 3865) has died
08-26 17:37:29.838  1035  1932 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-26 17:37:29.849  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:29.865  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 17:37:29.882  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:29.894  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:29.896  6976  7002 W FormManager: Network not available. Please check & try again.
,08-26 17:37:29.899  6866  6866 D BluetoothPermissionRequest: onReceive
08-26 17:37:29.901  6866  6866 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 17:37:29.902  6866  6866 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 17:37:29.903  6866  6866 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 17:37:29.962  1035  1050 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7005 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 17:37:29.971  6976  7003 V FormManager: Network unavailable.
08-26 17:37:29.976  6976  7003 V FormManager: Network unavailable.
,08-26 17:37:29.991  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 17:37:29.992  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-26 17:37:29.992  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 17:37:29.992  6866  6866 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 17:37:29.993  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 17:37:30.004  6866  6866 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 17:37:30.004  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-26 17:37:30.004  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 17:37:30.004  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 17:37:30.004  6866  6866 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 17:37:30.005  6866  6866 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-26 17:37:30.006  1035  2032 I ActivityManager: Killing 6072:com.android.contacts/u0a19 (adj 15): empty #17
08-26 17:37:30.043  4457  7024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 17:37:30.065  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 17:37:30.065  1035  1050 W libprocessgroup: failed to open /acct/uid_10019/pid_6072/cgroup.procs: No such file or directory
08-26 17:37:30.065  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 17:37:30.067  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 17:37:30.096  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 17:37:30.103  7005  7005 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 17:37:30.104  7005  7005 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 17:37:30.104  7005  7005 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 17:37:30.105  7005  7005 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 17:37:30.109  6906  6906 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 17:37:30.109  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 17:37:30.109  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:30.109  4296  7030 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 17:37:30.112  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:30.116  4296  7031 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 17:37:30.116  4296  7031 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 17:37:30.121  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 17:37:30.126  6976  7033 W FormManager: Network not available. Please check & try again.
08-26 17:37:30.140  6976  7034 V FormManager: Network unavailable.
,08-26 17:37:30.142  7005  7005 D BluetoothAdapterApp: Loading JNI Library
08-26 17:37:30.143  6976  7034 V FormManager: Network unavailable.
08-26 17:37:30.144  6935  6935 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 17:37:30.145  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 17:37:30.145  6935  6935 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 17:37:30.178  7005  7005 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@19da19ca Instance Count = 1
,08-26 17:37:30.183  7005  7005 D BluetoothAdapterApp: onCreate
08-26 17:37:30.188  6935  6935 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:30.188  6935  6935 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 17:37:30.195  6935  6935 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-26 17:37:30.196  6935  6935 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 17:37:30.196  6935  6935 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 17:37:30.196  6935  6935 V SoundPool: doLoad: loading sample sampleID=1
08-26 17:37:30.197  6935  6935 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 17:37:30.198  6935  7038 V SoundPool: Start decode
08-26 17:37:30.198  6935  7038 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 17:37:30.199   313   313 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 17:37:30.199   313   313 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 17:37:30.199   313   313 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 17:37:30.199   313   313 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 17:37:30.199   313   313 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 17:37:30.199   313   313 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 17:37:30.199   313   313 V MediaPlayerService: player type = 3
08-26 17:37:30.199   313   313 V AwesomePlayer: AwesomePlayer create()
08-26 17:37:30.200   313   313 V AwesomePlayer: reset_l() 
08-26 17:37:30.200   313   313 V AwesomePlayer: cancelPlayerEvents
08-26 17:37:30.200   313   313 V AwesomePlayer: setAudioSink() 
08-26 17:37:30.200   313   313 V AwesomePlayer: reset_l() 
08-26 17:37:30.200   313   313 V AudioCache: notify(0xb5474780, 8, 0, 0)
08-26 17:37:30.200   313   313 V AudioCache: ignored
08-26 17:37:30.200   313   313 V AwesomePlayer: cancelPlayerEvents
08-26 17:37:30.200   313   313 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 17:37:30.200   313   313 V AwesomePlayer: setDataSource_l dataSource
08-26 17:37:30.200   313   313 V LGParserOSAL: SniffLGParser start
08-26 17:37:30.200   313   313 V LGParserOSAL: MainType:5, SubType=0
08-26 17:37:30.200   313   313 V LGParserOSAL: #### check Mime : application/ogg
08-26 17:37:30.200   313   313 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 17:37:30.200   313   313 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 17:37:30.201  6808  6808 D UEI.SmartControl: QS Service created
08-26 17:37:30.205  7005  7005 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 17:37:30.205  7005  7005 D ProfileConfigQcom: Adding HeadsetService
08-26 17:37:30.205  7005  7005 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 17:37:30.206  7005  7005 D ProfileConfigQcom: Adding A2dpService
08-26 17:37:30.206  7005  7005 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 17:37:30.206  7005  7005 D ProfileConfigQcom: Adding HidService
08-26 17:37:30.206  7005  7005 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 17:37:30.206  7005  7005 D ProfileConfigQcom: Adding HealthService
08-26 17:37:30.207  7005  7005 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 17:37:30.207  7005  7005 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 17:37:30.208  7005  7005 D ProfileConfigQcom: Adding PanService
08-26 17:37:30.208  7005  7005 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 17:37:30.208  7005  7005 D ProfileConfigQcom: Adding GattService
08-26 17:37:30.208  7005  7005 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 17:37:30.208  7005  7005 D ProfileConfigQcom: Adding BluetoothMapService
08-26 17:37:30.209  7005  7005 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 17:37:30.210  7005  7005 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-26 17:37:30.214  6866  6866 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 17:37:30.216  7005  7005 V LGMDMManagerInternal: Create singleton instance
08-26 17:37:30.218  6935  6935 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 17:37:30.219  6935  6935 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 17:37:30.220  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 17:37:30.233  6935  6935 V LGMDMManager: Create singleton instance
08-26 17:37:30.238  6808  6808 I UEI.SmartControl: Service initServices...
08-26 17:37:30.238  6808  6808 D UEI.SmartControl: QS start get config
08-26 17:37:30.241   313   313 V LGParserOSAL: supported mime: application/ogg
08-26 17:37:30.241   313   313 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 17:37:30.241   313   313 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 17:37:30.241   313   313 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 17:37:30.241   313   313 V AwesomePlayer: AudioTrack Setting
08-26 17:37:30.241   313   313 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 17:37:30.241   313   313 V AwesomePlayer: setAudioSource() 
08-26 17:37:30.241   313   313 V MediaPlayerService: prepare
08-26 17:37:30.241   313   313 V AwesomePlayer: prepareAsync_l() 
08-26 17:37:30.242   313   313 V MediaPlayerService: wait for prepare
08-26 17:37:30.242   313  7040 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 17:37:30.242   313  7040 V AwesomePlayer: initAudioDecoder() 
08-26 17:37:30.242   313  7040 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 17:37:30.242   313  7040 V AudioSystem: isOffloadSupported()
08-26 17:37:30.242   313  7040 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 17:37:30.242   313  7040 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 17:37:30.242   313  7040 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 17:37:30.242   313  7040 V AwesomePlayer: getUseOffload() = 0 
08-26 17:37:30.242   313  7040 V OMXCodec: OMXCodec::Create
08-26 17:37:30.242   313  7040 V OMXCodec: findMatchingCodecs()
08-26 17:37:30.242   313  7040 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 17:37:30.242   313  7040 V OMXCodec: matchingCodecs.size()=1
08-26 17:37:30.242   313  7040 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-26 17:37:30.244   313  7040 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 17:37:30.244   313  7040 V LGCodecAdapter: LG Codec Adapter start
08-26 17:37:30.244   313  7040 V OMXCodec: OMXCodec Createtor
08-26 17:37:30.244   313  7040 V OMXCodec: setComponentRole
08-26 17:37:30.244   313  7040 V OMXCodec: configureCodec protected=0
08-26 17:37:30.244   313  7040 V LGCodecAdapter: called getLGCodecSpecificData
08-26 17:37:30.244   313  7040 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 17:37:30.244   313  7040 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 17:37:30.244   313  7040 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 17:37:30.244   313  7040 V LGCodecOSAL: Not support LGCodec
08-26 17:37:30.244   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 17:37:30.244   313  7040 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 17:37:30.244   313  7040 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 17:37:30.244   313  7040 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 17:37:30.244   313  7040 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 17:37:30.244   313  7040 V AudioSystem: isOffloadSupported()
08-26 17:37:30.244   313  7040 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 17:37:30.244   313  7040 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 17:37:30.244   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 17:37:30.244   313  7040 V OMXCodec: init()
08-26 17:37:30.244   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 17:37:30.244   313  7040 V OMXCodec: allocateBuffers
08-26 17:37:30.244   313  7040 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 17:37:30.244   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 17:37:30.244   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-26 17:37:30.245   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-26 17:37:30.245   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
08-26 17:37:30.245   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd060 on input port
08-26 17:37:30.245   313  7040 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 17:37:30.245   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 17:37:30.245   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd150 on output port
08-26 17:37:30.245   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd240 on output port
08-26 17:37:30.245   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd420 on output port
08-26 17:37:30.245   313  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd510 on output port
08-26 17:37:30.245   313  7040 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 17:37:30.248   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 17:37:30.248   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 17:37:30.248   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 17:37:30.248   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 17:37:30.248   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 17:37:30.248   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-26 17:37:30.248   313  7040 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 17:37:30.248   313  7040 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 17:37:30.248   313  7040 V AudioCache: notify(0xb5474780, 5, 0, 0)
08-26 17:37:30.248   313  7040 V AudioCache: ignored
08-26 17:37:30.248   313  7040 V AudioCache: notify(0xb5474780, 1, 0, 0)
08-26 17:37:30.248   313  7040 V AudioCache: prepared
08-26 17:37:30.248   313   313 V AudioCache: wait - success
08-26 17:37:30.248   313   313 V MediaPlayerService: start
08-26 17:37:30.248   313   313 V AwesomePlayer: play_l() 
08-26 17:37:30.248   313   313 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 17:37:30.248   313   313 V AwesomePlayer: createAudioPlayer_l
08-26 17:37:30.248   313   313 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 17:37:30.248   313   313 V AwesomePlayer: startAudioPlayer_l() 
08-26 17:37:30.248   313   313 D AudioPlayer: start of Playback, useOffload 0
08-26 17:37:30.248   313   313 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 17:37:30.248   313   313 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 17:37:30.257   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 17:37:30.257   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 17:37:30.257   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790608
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790848
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044791328
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044791568
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 17:37:30.259   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 17:37:30.260   313  7042 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 17:37:30.260   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 17:37:30.260   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd420 on output port
08-26 17:37:30.260   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd240 on output port
08-26 17:37:30.260   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd150 on output port
08-26 17:37:30.260   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd8d0 on output port
08-26 17:37:30.260   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 17:37:30.260   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 17:37:30.261   313   313 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 17:37:30.262   313   313 V AudioCache: notify(0xb5474780, 6, 0, 0)
08-26 17:37:30.262   313   313 V AudioCache: ignored
08-26 17:37:30.262   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.262   313  7043 V AudioCache: memcpy(0xac300000, 0xb16df000, 4096)
08-26 17:37:30.262   313   313 V MediaPlayerService: wait for playback complete
08-26 17:37:30.263   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.263   313  7043 V AudioCache: memcpy(0xac301000, 0xb16df000, 4096)
08-26 17:37:30.263   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.263   313  7043 V AudioCache: memcpy(0xac302000, 0xb16df000, 4096)
08-26 17:37:30.264   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.265   313  7043 V AudioCache: memcpy(0xac303000, 0xb16df000, 4096)
08-26 17:37:30.265   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.265   313  7043 V AudioCache: memcpy(0xac304000, 0xb16df000, 4096)
08-26 17:37:30.265   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.265   313  7043 V AudioCache: memcpy(0xac305000, 0xb16df000, 4096)
08-26 17:37:30.265   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.265   313  7043 V AudioCache: memcpy(0xac306000, 0xb16df000, 4096)
08-26 17:37:30.266   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.266   313  7043 V AudioCache: memcpy(0xac307000, 0xb16df000, 4096)
08-26 17:37:30.266   313  7043 V AudioCache,: write(0xb16df000, 4096)
08-26 17:37:30.266   313  7043 V AudioCache: memcpy(0xac308000, 0xb16df000, 4096)
08-26 17:37:30.267   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.267   313  7043 V AudioCache: memcpy(0xac309000, 0xb16df000, 4096)
08-26 17:37:30.268   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.268   313  7043 V AudioCache: memcpy(0xac30a000, 0xb16df000, 4096)
08-26 17:37:30.268   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.268   313  7043 V AudioCache: memcpy(0xac30b000, 0xb16df000, 4096)
08-26 17:37:30.269   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.269   313  7043 V AudioCache: memcpy(0xac30c000, 0xb16df000, 4096)
08-26 17:37:30.270   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.270   313  7043 V AudioCache: memcpy(0xac30d000, 0xb16df000, 4096)
08-26 17:37:30.270   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.270   313  7043 V AudioCache: memcpy(0xac30e000, 0xb16df000, 4096)
08-26 17:37:30.271   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.271   313  7043 V AudioCache: memcpy(0xac30f000, 0xb16df000, 4096)
08-26 17:37:30.271   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.271   313  7043 V AudioCache: memcpy(0xac310000, 0xb16df000, 4096)
08-26 17:37:30.272   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.272   313  7043 V AudioCache: memcpy(0xac311000, 0xb16df000, 4096)
08-26 17:37:30.273   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.273   313  7043 V AudioCache: memcpy(0xac312000, 0xb16df000, 4096)
08-26 17:37:30.273   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.273   313  7043 V AudioCache: memcpy(0xac313000, 0xb16df000, 4096)
08-26 17:37:30.274   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.274   313  7043 V AudioCache: memcpy(0xac314000, 0xb16df000, 4096)
08-26 17:37:30.275   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.275   313  7043 V AudioCache: memcpy(0xac315000, 0xb16df000, 4096)
08-26 17:37:30.275   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.275   313  7043 V AudioCache: memcpy(0xac316000, 0xb16df000, 4096)
08-26 17:37:30.276   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.276   313  7043 V AudioCache: memcpy(0xac317000, 0xb16df000, 4096)
08-26 17:37:30.276   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.276   313  7043 V AudioCache: memcpy(0xac318000, 0xb16df000, 4096)
08-26 17:37:30.277   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.277   313  7043 V AudioCache: memcpy(0xac319000, 0xb16df000, 4096)
08-26 17:37:30.278   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.278   313  7043 V AudioCache: memcpy(0xac31a000, 0xb16df000, 4096)
08-26 17:37:30.278   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.278   313  7043 V AudioCache: memcpy(0xac31b000, 0xb16df000, 4096)
08-26 17:37:30.279   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.279   313  7043 V AudioCache: memcpy(0xac31c000, 0xb16df000, 4096)
08-26 17:37:30.280   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.280   313  7043 V AudioCache: memcpy(0xac31d000, 0xb16df000, 4096)
08-26 17:37:30.280   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.280   313  7043 V AudioCache: memcpy(0xac31e000, 0xb16df000, 4096)
,08-26 17:37:30.281   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.281   313  7043 V AudioCache: memcpy(0xac31f000, 0xb16df000, 4096)
08-26 17:37:30.281   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.281   313  7043 V AudioCache: memcpy(0xac320000, 0xb16df000, 4096)
08-26 17:37:30.282   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.282   313  7043 V AudioCache: memcpy(0xac321000, 0xb16df000, 4096)
08-26 17:37:30.282   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.282   313  7043 V AudioCache: memcpy(0xac322000, 0xb16df000, 4096)
08-26 17:37:30.283   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.283   313  7043 V AudioCache: memcpy(0xac323000, 0xb16df000, 4096)
08-26 17:37:30.283   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.283   313  7043 V AudioCache: memcpy(0xac324000, 0xb16df000, 4096)
08-26 17:37:30.284   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.284   313  7043 V AudioCache: memcpy(0xac325000, 0xb16df000, 4096)
08-26 17:37:30.284  7005  7005 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:30.284   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.284   313  7043 V AudioCache: memcpy(0xac326000, 0xb16df000, 4096)
08-26 17:37:30.286  7005  7005 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 17:37:30.286   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.286   313  7043 V AudioCache: memcpy(0xac327000, 0xb16df000, 4096)
08-26 17:37:30.286  7005  7005 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 17:37:30.286  7005  7005 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 17:37:30.287   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.287   313  7043 V AudioCache: memcpy(0xac328000, 0xb16df000, 4096)
08-26 17:37:30.287  7005  7005 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:30.287  7005  7005 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 17:37:30.287   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.287   313  7043 V AudioCache: memcpy(0xac329000, 0xb16df000, 4096)
08-26 17:37:30.288   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.288   313  7043 V AudioCache: memcpy(0xac32a000, 0xb16df000, 4096)
08-26 17:37:30.289   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.289   313  7043 V AudioCache: memcpy(0xac32b000, 0xb16df000, 4096)
08-26 17:37:30.289   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.289   313  7043 V AudioCache: memcpy(0xac32c000, 0xb16df000, 4096)
08-26 17:37:30.290   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.290   313  7043 V AudioCache: memcpy(0xac32d000, 0xb16df000, 4096)
08-26 17:37:30.290   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.290   313  7043 V AudioCache: memcpy(0xac32e000, 0xb16df000, 4096)
08-26 17:37:30.291   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.291   313  7043 V AudioCache: memcpy(0xac32f000, 0xb16df000, 4096)
08-26 17:37:30.291   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.291   313  7043 V AudioCache: memcpy(0xac330000, 0xb16df000, 4096)
08-26 17:37:30.292   313  7043 V AudioCache: write(0xb16df000, 4096)
08-26 17:37:30.292   313  7043 V AudioCache: memcpy(0xac331000, 0xb16df000, 4096)
08-26 17:37:30.292   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-26 17:37:30.292   313  7043 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 17:37:30.292   313  7043 V AwesomePlayer: postAudioEOS() 
08-26 17:37:30.292   313  7043 V AudioCache: write(0xb16df000, 280)
08-26 17:37:30.292   313  7043 V AudioCache: memcpy(0xac332000, 0xb16df000, 280)
08-26 17:37:30.292  6952  6952 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 17:37:30.295   313  7040 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 17:37:30.295   313  7040 V AwesomePlayer: onStreamDone
08-26 17:37:30.295   313  7040 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 17:37:30.295   313  7040 V AudioCache: notify(0xb5474780, 2, 0, 0)
08-26 17:37:30.295   313  7040 V AudioCache: playback complete
08-26 17:37:30.295   313  7040 V AwesomePlayer: pause_l() 
08-26 17:37:30.295   313  7040 V AudioCache: notify(0xb5474780, 7, 0, 0)
08-26 17:37:30.295   313  7040 V AudioCache: ignored
08-26 17:37:30.295   313  7040 V AwesomePlayer: cancelPlayerEvents
,08-26 17:37:30.296   313  7040 D AudioPlayer: Pause Playback at 1068125
08-26 17:37:30.296   313   313 V AudioCache: wait - success
08-26 17:37:30.296   313   313 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 17:37:30.296   313   313 V AwesomePlayer: reset_l() 
08-26 17:37:30.296   313   313 V AudioCache: notify(0xb5474780, 8, 0, 0)
08-26 17:37:30.296   313   313 V AudioCache: ignored
08-26 17:37:30.296   313   313 V AwesomePlayer: cancelPlayerEvents
08-26 17:37:30.296   313   313 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 17:37:30.296   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 17:37:30.296   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 17:37:30.296   313   313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 17:37:30.296   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd060 on port 0
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd8d0 on port 1
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd150 on port 1
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd240 on port 1
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd420 on port 1
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:30.297   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 17:37:30.297   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 17:37:30.297   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 17:37:30.298   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 17:37:30.298   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 17:37:30.298   313  7042 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 17:37:30.298   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 17:37:30.298   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 17:37:30.298   313   313 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 17:37:30.298   313   313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 17:37:30.298   313   313 D AudioPlayer: Audi,oPlayer releasing audio source
08-26 17:37:30.298   313   313 D AudioPlayer: AudioPlayer done releasing audio source
08-26 17:37:30.298   313   313 V AwesomePlayer: reset_l() 
08-26 17:37:30.298   313   313 V AwesomePlayer: cancelPlayerEvents
08-26 17:37:30.298   313   313 V AwesomePlayer: ~AwesomePlayer call
08-26 17:37:30.299   313   313 V AwesomePlayer: reset_l() 
08-26 17:37:30.299   313   313 V AwesomePlayer: cancelPlayerEvents
08-26 17:37:30.299  6935  7038 V SoundPool: close(31)
08-26 17:37:30.299  6935  7038 V SoundPool: pointer = 0x9fe58000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 17:37:30.306  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 17:37:30.307  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-26 17:37:30.309  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8158,
08-26 17:37:30.486  6808  6808 I UEI.SmartControl: Supports setup maps: true
,08-26 17:37:30.489  6808  6808 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 17:37:30.489  6808  6808 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-26 17:37:30.489  6808  6808 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 17:37:30.489  6808  6808 I UEI.SmartControl: ### init IR Blaster...
,08-26 17:37:30.493  6808  6808 D serial_port: Configuring serial port
08-26 17:37:30.493  6808  6808 E UEI.SmartControl: UEIBLaster setting for 616
08-26 17:37:30.493  6808  6808 I UEI.SmartControl: Setting serial record hearder size = 2
,08-26 17:37:30.493  6808  6808 I UEI.SmartControl: configuring settings for MAXQ616
08-26 17:37:30.493  6808  6808 I UEI.SmartControl: Get version...
08-26 17:37:30.512  6808  7045 D UEI.SmartControl: serial port data available: 21
,08-26 17:37:30.538  6808  6808 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 17:37:30.538  6808  6808 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-26 17:37:30.538  6808  6808 I UEI.SmartControl: QS saving settings...
,08-26 17:37:30.540  6808  6808 D UEI.SmartControl: IR Blaster version: 25672567
08-26 17:37:30.557  6808  7045 D UEI.SmartControl: serial port data available: 4
,08-26 17:37:30.588  6808  7051 I UEI.SmartControl: Device manager: loading config....
,08-26 17:37:30.591  6808  7051 D UEI.SmartControl: ----------- loading internal config...
08-26 17:37:30.593  6808  6808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 17:37:30.595  6808  6808 E UEI.SmartControl: Services init done
08-26 17:37:30.595  6808  6808 D UEI.SmartControl: QS Service init finished
08-26 17:37:30.597  6808  6808 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 17:37:30.597  6808  6808 D UEI.SmartControl: QS Service version code: 201091
08-26 17:37:30.598  6808  6808 D UEI.SmartControl: Service requested: Control
08-26 17:37:30.602  6808  7051 E UEI.SmartControl: Loading SETTINGS...
,08-26 17:37:30.603  6808  6808 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 17:37:30.606  6935  6935 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 17:37:30.608  6808  6823 I UEI.SmartControl: ------ IControl API: 11
08-26 17:37:30.608  6808  6808 D UEI.SmartControl: Internal service binding...
08-26 17:37:30.608  6808  6823 D UEI.SmartControl: File observer start...
08-26 17:37:30.609  6808  6823 E UEI.SmartControl: IR Port is disabled: false
08-26 17:37:30.610  6808  6823 D UEI.SmartControl: Starting file observer...
08-26 17:37:30.610  6808  6823 I UEI.SmartControl: Registering callback...
08-26 17:37:30.611  6808  6824 I UEI.SmartControl: ------ IControl API: 19
08-26 17:37:30.612  6808  6824 I UEI.SmartControl: Registering Services Ready callback...
08-26 17:37:30.614  6808  7051 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 17:37:30.626  6808  7050 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 17:37:30.628  6935  6951 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 17:37:30.628  6808  7050 D UEI.SmartControl: -----service ready thread exits
08-26 17:37:30.630  6935  7036 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 17:37:30.630  6935  7036 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-26 17:37:30.631  6935  6935 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 17:37:30.632  6935  6935 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 17:37:30.633  6808  6823 I UEI.SmartControl: ------ IControl API: 8
08-26 17:37:30.635  6935  6935 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 17:37:30.636  6935  6935 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 17:37:30.636  6935  6935 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 17:37:30.636  6935  6935 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 17:37:30.638  6935  6935 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 17:37:30.638  6935  6935 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 17:37:30.640  6935  6935 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 17:37:30.645  6935  6935 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 17:37:30.646  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-26 17:37:30.647  6935  6935 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 17:37:30.647  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 17:37:30.649  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 17:37:30.650  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 17:37:30.651  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 17:37:30.652  6935  6935 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472225850651]
08-26 17:37:30.657  6935  6935 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-26 17:37:30.661  1035  1990 I ActivityManager: Killing 6095:com.android.gallery3d/u0a27 (adj 15): empty #17
08-26 17:37:30.689  6935  7053 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 17:37:30.734  1035  1990 I ActivityManager: Killing 6610:com.lge.email/u0a23 (adj 15): empty #18
,08-26 17:37:30.792  1035  1050 W libprocessgroup: failed to open /acct/uid_10027/pid_6095/cgroup.procs: No such file or directory
,08-26 17:37:30.799  1035  1932 W libprocessgroup: failed to open /acct/uid_10023/pid_6610/cgroup.procs: No such file or directory
08-26 17:37:30.809  6935  6935 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-26 17:37:30.812  6935  6935 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-26 17:37:30.813  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 17:37:30.813  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-26 17:37:30.813  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 17:37:30.814  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 17:37:30.814  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 17:37:30.826  6935  6935 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 17:37:31.564  1035  1956 D WifiServiceImplEx: setWifiEnabled: true pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 17:37:31.566  1035  1956 D WifiService: setWifiEnabled: true pid=6695, uid=10118
,08-26 17:37:31.566  1035  1956 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 17:37:31.595  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 17:37:31.595  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 17:37:31.595  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-26 17:37:31.599  1035  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-26 17:37:31.599  1035  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-26 17:37:31.602  1035  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-26 17:37:31.602  1035  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-26 17:37:31.602  1035  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 17:37:31.602  1035  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 17:37:31.602  1035  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 17:37:31.602  1035  1540 E WifiHW  : unknown target_country: EU , set to default
,08-26 17:37:31.602  1035  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
,08-26 17:37:31.602  1035  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-26 17:37:31.602  1035  1540 I WifiUtil: gEnableBmps=1,
,08-26 17:37:31.653  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:31.683  1035  1099 D Tethering: MasterInitialState.processMessage what=3
08-26 17:37:31.693  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:31.696  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:31.699  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:31.702  1035  1099 D Tethering: MasterInitialState.processMessage what=3
08-26 17:37:31.710  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:31.714  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:31.714  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:31.716  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 17:37:31.720  6502  6539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 17:37:31.728  5795  5795 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 17:37:31.736  5795  5795 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 17:37:31.761  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:31.801  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:31.835  1035  1956 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7073 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-26 17:37:31.841  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:31.841  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 17:37:31.909  7073  7073 I AppUp4:AppBoxCP: onCreate
08-26 17:37:31.910  7073  7073 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 17:37:31.922  7073  7073 I AppUp4:DB:  setFingerPrint start
08-26 17:37:31.922  7073  7073 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 17:37:31.931  7073  7073 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-26 17:37:31.931  7073  7073 I AppUp4:DB:  SDK version = 21
08-26 17:37:31.931  7073  7073 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-26 17:37:31.933  7073  7073 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-26 17:37:31.934  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 17:37:31.934  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:31.937  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 17:37:31.937  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 17:37:31.944  7073  7073 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 17:37:31.986  7073  7073 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:31.986  7073  7073 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 17:37:31.996  7073  7073 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d9dd804
08-26 17:37:31.996  7073  7073 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 17:37:31.996  7073  7073 D AppUp4:CustFacade: isPhone : true
08-26 17:37:31.996  7073  7073 D AppUp4:CustModeStarterReceiver: begin check event
08-26 17:37:31.997  7073  7073 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 17:37:31.997  7073  7073 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-26 17:37:31.998  7073  7094 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 17:37:31.998  7073  7094 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-26 17:37:31.999  7073  7094 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-26 17:37:32.001  1035  1787 I ActivityManager: Killing 6645:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-26 17:37:32.041  1035  1932 W libprocessgroup: failed to open /acct/uid_10061/pid_6645/cgroup.procs: No such file or directory
,08-26 17:37:32.045  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:32.045  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 17:37:32.047  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:32.051  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:32.058  4296  7097 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 17:37:32.065  4296  7098 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:32.066  4296  7098 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 17:37:32.145  1035  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7102 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 17:37:32.223  7102  7102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 17:37:32.223  7102  7102 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 17:37:32.225  7102  7102 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-26 17:37:32.226  7102  7102 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 17:37:32.325  7102  7102 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 17:37:32.357  7102  7102 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 17:37:32.360   309   894 D SoftapController: Softap fwReload - Ok
08-26 17:37:32.361  1035  1540 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (753ms)
08-26 17:37:32.364   309   894 D CommandListener: Setting iface cfg
08-26 17:37:32.364   309   894 D CommandListener: Trying to bring down wlan0
08-26 17:37:32.364   309   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 17:37:32.366  1035  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 17:37:32.368  1035  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 17:37:32.368  1035  1540 E WifiStateMachine: useWiFiOffloading() : false
08-26 17:37:32.368  1035  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 17:37:32.369  1035  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 17:37:32.369  1035  1099 D Tethering: InitialState.processMessage what=4
08-26 17:37:32.370  1035  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 17:37:32.366  7128  7128 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:32.366  7128  7128 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 17:37:32.380  1035  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 17:37:32.380  1035  1540 D WifiMonitor: connecting to supplicant
08-26 17:37:32.383  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 17:37:32.386  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:32.387  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 17:37:32.389  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:32.390  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:32.404  7128  7128 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 17:37:32.424  7102  7102 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 17:37:32.439  7128  7128 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 17:37:32.439  7128  7128 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 17:37:32.459  7102  7102 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:32.459  7102  7102 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 17:37:32.512  7128  7128 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 17:37:32.560  7128  7128 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 17:37:32.567  7128  7128 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 17:37:32.569  1035  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 17:37:32.569  1035  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 17:37:32.570  1035  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 17:37:32.571  1035  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 17:37:32.572  1035  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:32.573  1035  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:32.573  7128  7128 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 17:37:32.574  1035  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 17:37:32.574  1035  7137 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 17:37:32.574  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 17:37:32.574  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 17:37:32.574  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,08-26 17:37:32.574  1035  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 17:37:32.574  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 17:37:32.574  1035  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 17:37:32.574  1035  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 17:37:32.574  1035  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 17:37:32.575  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 17:37:32.575  1035  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 17:37:32.576  1035  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 17:37:32.576  1035  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 17:37:32.583  1035  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 17:37:32.583  1035  1540 E WifiStateMachine: useWiFiOffloading() : false
08-26 17:37:32.583  1035  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 17:37:32.584  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:32.585  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:32.585  1035  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 17:37:32.585  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:32.585  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:32.586  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 17:37:32.586  1035  1540 D WifiNative-wlan0: SET update_config 1: returned true
08-26 17:37:32.586  1035  1540 D WifiConfigStore: Loading config and enabling all networks 
08-26 17:37:32.586  1035  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 17:37:32.587  1035  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-26 17:37:32.589  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-26 17:37:32.590  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:32.593  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:32.593  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:32.593  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:32.593  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:32.593  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:32.593  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:32.593  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:32.593  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:32.593  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:32.593  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:32.594  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:32.594  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 17:37:32.594  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 17:37:32.598  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:32.598  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:32.598  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:32.598  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:32.598  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:32.598  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:32.598  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:32.598  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:32.598  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:32.598  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:32.598  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:32.605  1035  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-26 17:37:32.618  6976  7141 W FormManager: Network not available. Please check & try again.
,08-26 17:37:32.622  3480  3480 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 17:37:32.622  3480  3480 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:32.622  1035  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 17:37:32.622  3480  3480 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 17:37:32.623  1035  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 17:37:32.630  7102  7102 I HubEmail: JNI_OnLoad()
08-26 17:37:32.630  7102  7102 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 17:37:32.630  7102  7102 I HubEmail: registerNatives()
08-26 17:37:32.631  7102  7102 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 17:37:32.631  7102  7102 I HubEmail: registerNativeMethods()
08-26 17:37:32.631  7102  7102 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-26 17:37:32.631  7102  7102 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-26 17:37:32.676  1035  1896 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7144 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 17:37:32.680  1035  1540 D WifiStateMachine: enableVerboseLogging : level 2
08-26 17:37:32.680  1035  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 17:37:32.680  1035  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 17:37:32.680  1035  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 17:37:32.681  1035  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 17:37:32.681  1035  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 17:37:32.682  1035  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 17:37:32.682  1035  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 17:37:32.682  1035  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 17:37:32.682  1035  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 17:37:32.683  1035  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 17:37:32.683  1035  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 17:37:32.683  1035  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 17:37:32.683  1035  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 17:37:32.684  1035  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 17:37:32.684  6976  7142 V FormManager: Network unavailable.
08-26 17:37:32.684  1035  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 17:37:32.684  1035  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 17:37:32.685  1035  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 17:37:32.685  1035  1540 D WifiNative-HAL: Setting external_sim to 1
08-26 17:37:32.685  1035  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
,08-26 17:37:32.685  1035  1540 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 17:37:32.685  1035  1540 I WifiNative-HAL: startHal
08-26 17:37:32.685  1035  1540 D wifi    : setting scan oui 0x953fa360
08-26 17:37:32.685  1035  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 17:37:32.686  1035  1540 I WifiNative-HAL: startHal
08-26 17:37:32.686  1035  1540 D wifi    : setting scan oui 0x953fa360
08-26 17:37:32.686  1035  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 17:37:32.686  1941  1941 D WfdsService: Supplicant Connection state is changed : true
,08-26 17:37:32.686  1035  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 17:37:32.686  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 17:37:32.687  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 17:37:32.687  1941  2242 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 17:37:32.687  1941  2242 D WfdsService: Set the WFDS Monitor: true
08-26 17:37:32.687  1941  2242 D WfdsMonitor: WfdsMonitorThread create
08-26 17:37:32.687  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,08-26 17:37:32.687  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 17:37:32.688  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 17:37:32.688  1941  2242 D WfdsMonitor: WFDS Monitor is created and started
08-26 17:37:32.688  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-26 17:37:32.688  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 17:37:32.688  1941  2242 D WfdsService: WiFi: Supplicant connection re-established
08-26 17:37:32.688  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 17:37:32.689  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 17:37:32.689  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 17:37:32.689  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-26 17:37:32.689  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 17:37:32.689  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 17:37:32.689  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 17:37:32.690  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 17:37:32.690  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 17:37:32.690  7128  7128 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 17:37:32.690  1941  7153 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-26 17:37:32.691  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 17:37:32.691  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 17:37:32.691  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 17:37:32.691  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 17:37:32.691  1941  7153 E CtrlSupplicant: Succeed to open control connection
08-26 17:37:32.692  1941  7153 E CtrlSupplicant: Succeed to open monitor connection
08-26 17:37:32.692  1035  1540 E WifiNative: : [120,721,129 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
,08-26 17:37:32.692  1035  1540 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 17:37:32.693  1941  7153 D WfdsMonitor: Supplicant connection established
08-26 17:37:32.693  1941  2242 D WfdsService: Connected to the supplicant for wfds
08-26 17:37:32.694  1035  1540 D WifiNative-wlan0: RECONNECT: returned true
08-26 17:37:32.694  1035  1540 D WifiNative-wlan0: doString: [STATUS]
08-26 17:37:32.695  7102  7143 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:32.696  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,08-26 17:37:32.696  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 17:37:32.697  1035  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 17:37:32.697  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 17:37:32.698  1035  1540 D WifiNative-wlan0: SET ps 1: returned true,
08-26 17:37:32.699  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.702   309   894 D CommandListener: Setting iface cfg
08-26 17:37:32.702   309   894 D CommandListener: Trying to bring up p2p0,
08-26 17:37:32.703  1035  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 17:37:32.703  1035  1538 D LGWifiP2pService: P2pEnablingState
08-26 17:37:32.703  1035  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:32.703  1035  1538 D LGWifiP2pService: P2p socket connection successful
08-26 17:37:32.703  1035  1538 D LGWifiP2pService: P2pEnabledState
08-26 17:37:32.706  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 17:37:32.706  1035  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.706  1035  1035 D RttService: SCAN_AVAILABLE : 3
,08-26 17:37:32.706  1035  1557 I WifiNative-HAL: startHal
08-26 17:37:32.706  1035  1557 D wifi    : getting scan capabilities on interface[1] = 0x953fa360
08-26 17:37:32.706  1035  1557 D wifi    : failed to get capabilities : -3
08-26 17:37:32.706  1035  1557 E WifiScanningService: could not get scan capabilities
08-26 17:37:32.706  1035  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:32.706  1035  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 17:37:32.708  1035  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-26 17:37:32.709  1035  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 17:37:32.709  1035  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
,08-26 17:37:32.709  1035  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 17:37:32.710  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=120739  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 17:37:32.712  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 17:37:32.712  1035  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 17:37:32.712  1941  1941 D WfdsService: WifiP2pState is changed : true
08-26 17:37:32.713  1941  2242 D WfdsService: Receive the WFDS_ENABLE Method
08-26 17:37:32.713  1941  2242 D WfdsService: Set the WFDS Monitor: true
08-26 17:37:32.713  1941  2242 D WfdsService: Connected to the supplicant for wfds
08-26 17:37:32.713  1941  2242 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 17:37:32.713  7128  7128 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 17:37:32.713  1035  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 17:37:32.713  1941  2242 D WfdsService: selectPreferredScanChannel [36]
08-26 17:37:32.713  1941  2242 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 17:37:32.713  1035  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 17:37:32.714  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=120743  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 17:37:32.714  1035  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-26 17:37:32.714  1035  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 17:37:32.714  1035  1538 D LGWifiP2pService: before postfix = G3
08-26 17:37:32.714  1035  1538 D WifiServerServiceExt: postfix byte check : 2
08-26 17:37:32.714  1035  1538 D LGWifiP2pService: after postfix = G3
08-26 17:37:32.714  1035  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 17:37:32.714  1035  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 17:37:32.714  1035  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 17:37:32.714  1035  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 17:37:32.715  1035  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 17:37:32.715  1035  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 17:37:32.715  1035  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 17:37:32.715  1035  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 17:37:32.715  1035  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 17:37:32.716  1035  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 17:37:32.716  1035  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 17:37:32.716  7128  7128 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 17:37:32.717  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 17:37:32.718  1941  1941 D WfdsService: isConnected: false
08-26 17:37:32.718  1035  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 17:37:32.718  1035  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 17:37:32.718  1035  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-26 17:37:32.718  1035  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 17:37:32.719  1035  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 17:37:32.719  1035  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 17:37:32.719  1035  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 17:37:32.719  7128  7128 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 17:37:32.720  1035  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 17:37:32.720  1035  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
,08-26 17:37:32.720  1035  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 17:37:32.720  1035  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 17:37:32.721  1035  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 17:37:32.721  1035  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-26 17:37:32.721  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:32.721  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:32.721  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 17:37:32.722  1035  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 17:37:32.722  1035  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 17:37:32.722  1035  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS],
08-26 17:37:32.722  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 17:37:32.722  1035  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 17:37:32.722  1035  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 17:37:32.725  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:32.725  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 17:37:32.727  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 17:37:32.728  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 17:37:32.728  1941  1941 D WfdsService: Update P2p Interface State: 3
08-26 17:37:32.730  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:32.732  1035  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-26 17:37:32.732  1035  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 17:37:32.733  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 17:37:32.733  7128  7128 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-26 17:37:32.734  7128  7128 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 17:37:32.734  7128  7128 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.735  1035  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 17:37:32.735  7128  7128 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.735  1035  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 17:37:32.736  1035  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 17:37:32.736  1941  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:32.736  1941  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:32.736  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 17:37:32.736  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:32.736  1035  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:32.736  1035  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:32.736  1035  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 17:37:32.736  1035  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:32.736  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 17:37:32.736  1035  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.736  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 17:37:32.736  7128  7128 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 17:37:32.737  1035  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.737  1035  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.737  1035  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:32.737  1035  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.738  1035  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.738  1035  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.738  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 17:37:32.738  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 17:37:32.738  1035  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 17:37:32.738  1035  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-26 17:37:32.739  1035  1538 D LGWifiP2pService: InactiveState
08-26 17:37:32.739  1035  1538 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.739  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.739  1035  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 17:37:32.740  1035  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 17:37:32.740  1035  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 17:37:32.740  1035  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 17:37:32.740  1035  1540 D WifiNative-wlan0: doBoolean: SCAN
08-26 17:37:32.741  1035  1540 D WifiNative-wlan0: SCAN: returned false
08-26 17:37:32.741  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=120770  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 17:37:32.742  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 17:37:32.743  7128  7128 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:32.743  1035  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 17:37:32.743  1035  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:32.743  1035  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:32.743  1035  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:32.743  1941  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 17:37:32.743  7128  7128 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 17:37:32.743  7128  7128 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.744  1035  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:32.744  1035  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.744  1035  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.744  1035  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.744  7128  7128 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.744  1035  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 17:37:32.744  1035  1538 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.745  1035  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.745  1035  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.Sta,teMachine$SmHandler }
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.745  1035  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.746  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.746  1035  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:32.746  1941  2242 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 17:37:32.746  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:32.746  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:32.746  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 17:37:32.746  1035  1035 E WifiServerServiceExt: No p2p device connected
08-26 17:37:32.747  1941  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:32.747  6976  7142 V FormManager: Network unavailable.
08-26 17:37:32.747  1941  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:32.747  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=120777  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 17:37:32.748  1035  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-26 17:37:32.748  1035  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 17:37:32.749  1035  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 17:37:32.749  1035  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 17:37:32.749  1035  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 17:37:32.751  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:32.751  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:32.753  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:32.753  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 17:37:32.753  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:32.754  1035  1921 I ActivityManager: Killing 6159:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-26 17:37:32.770  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:32.770  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 17:37:32.770  1035  1576 W libprocessgroup: failed to open /acct/uid_10080/pid_6159/cgroup.procs: No such file or directory
,08-26 17:37:32.828  7144  7144 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:32.828  7144  7144 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 17:37:32.830  7144  7144 D PhoneMonitor: Register our PhoneStateListener
08-26 17:37:32.845  7144  7144 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 17:37:32.847  7144  7144 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 17:37:32.866  7144  7144 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-26 17:37:32.868  7144  7144 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-26 17:37:32.870  7144  7144 D TelephonyAutoProfiling: [parse] Load xml
,08-26 17:37:32.876  7144  7144 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 17:37:32.876  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 17:37:32.876  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 17:37:32.877  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 17:37:32.877  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 17:37:32.877  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 17:37:32.877  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 17:37:32.877  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 17:37:32.877  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 17:37:32.877  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-26 17:37:32.878  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 17:37:32.878  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 17:37:32.878  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 17:37:32.878  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 17:37:32.878  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 17:37:32.878  7144  7144 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 17:37:32.878  7144  7144 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-26 17:37:32.888  7144  7144 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-26 17:37:32.917  1035  1648 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7165 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 17:37:32.918  1035  1648 I ActivityManager: Killing 6188:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-26 17:37:32.978  1035  1990 W libprocessgroup: failed to open /acct/uid_10097/pid_6188/cgroup.procs: No such file or directory
,08-26 17:37:33.185  1035  1990 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7186 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-26 17:37:33.189  1035  1990 I ActivityManager: Killing 6742:com.lge.eula/1000 (adj 15): empty #17
08-26 17:37:33.210  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 17:37:33.210  1035  7137 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-26 17:37:33.210  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 17:37:33.210  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-26 17:37:33.210  1035  7137 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 17:37:33.211  7128  7128 E wpa_supplicant: USIM:  scard_init function
08-26 17:37:33.211  1035  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 17:37:33.212  1035  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 17:37:33.212  1035  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 17:37:33.213  1035  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 17:37:33.213  1035  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 17:37:33.213  7128  7128 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 17:37:33.213  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 17:37:33.214  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 17:37:33.238  1035  1785 W libprocessgroup: failed to open /acct/uid_1000/pid_6742/cgroup.procs: No such file or directory
,08-26 17:37:33.244  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121274  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 17:37:33.246  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121275  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 17:37:33.248  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:33.248  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:33.249  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.250  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.250  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.250  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-26 17:37:33.252  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:33.252  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 17:37:33.333  7128  7128 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 17:37:33.338  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,08-26 17:37:33.338  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 17:37:33.339  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 17:37:33.339  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 17:37:33.340  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:33.340  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 17:37:33.346  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=121375  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 17:37:33.348  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=121377  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 17:37:33.349  1035  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121378
08-26 17:37:33.349  1035  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121379
08-26 17:37:33.352  7128  7128 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 17:37:33.352  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:33.352  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 17:37:33.352  7128  7128 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 17:37:33.352  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 17:37:33.352  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 17:37:33.352  1035  7137 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 17:37:33.353  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 17:37:33.353  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 17:37:33.353  1035  7137 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 17:37:33.353  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:33.353  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 17:37:33.354  1035  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121379
08-26 17:37:33.355  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121384
08-26 17:37:33.355  1035  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121385
08-26 17:37:33.358  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121388  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 17:37:33.381  1035  1896 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7203 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 17:37:33.382  1035  1896 I ActivityManager: Killing 6769:com.lge.bnr/1000 (adj 15): empty #17
,08-26 17:37:33.440  1035  1099 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 17:37:33.441  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6769/cgroup.procs: No such file or directory
08-26 17:37:33.443  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 17:37:33.456  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:33.456  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 17:37:33.459  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.460  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.461  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.461  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 17:37:33.465  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.466  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.466  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 17:37:33.469  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:33.469  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-26 17:37:33.472  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=121502  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 17:37:33.473  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=121503  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 17:37:33.474  1035  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121503
08-26 17:37:33.474  1035  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121504
08-26 17:37:33.475  1035  1540 D WifiNative-wlan0: doString: [STATUS]
08-26 17:37:33.476  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:33.476  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 17:37:33.476  1035  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-26 17:37:33.478  1035  1540 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 17:37:33.481  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:33.481  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:33.483  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 17:37:33.489  1035  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 17:37:33.489  1035  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 17:37:33.494  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.495  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.495  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 17:37:33.495  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.495  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.495  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-26 17:37:33.501  1035  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 17:37:33.502  1035  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 17:37:33.502  1035  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 17:37:33.502  1035  1546 D ConnectivityService: Got NetworkAgent Messenger
08-26 17:37:33.502  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 17:37:33.502  1035  1546 D ConnectivityService: NetworkAgent connected
08-26 17:37:33.502  1035  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 17:37:33.503  1035  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 17:37:33.506  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:33.506  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:33.507  1035  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 17:37:33.507  1035  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 17:37:33.507  1035  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 17:37:33.507  1035  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 17:37:33.507  1035  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 17:37:33.508  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.510  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:33.510  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:33.512  1035  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 17:37:33.513  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.514   309   894 D CommandListener: Setting iface cfg
08-26 17:37:33.520  1035  1540 E WifiStateMachine: Start Dhcp Watchdog 2
08-26 17:37:33.520  1035  7221 D DhcpStateMachine: StoppedState
08-26 17:37:33.520  1035  7221 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:33.520  1035  7221 D DhcpStateMachine: WaitBeforeStartState
08-26 17:37:33.521  1035  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121550  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:33.521  1035  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121550  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:33.522  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121551  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:33.522  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:33.522  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:33.523  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 17:37:33.523  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:33.523  1035  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:33.524  1035  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:33.524  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-26 17:37:33.525  1035  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:33.525  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:33.525  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 17:37:33.525  1035  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=121555  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:33.526  1035  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=121555  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:33.527  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=121556  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:33.528  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:75888] from screen [on:0 period:-947929000] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 17:37:33.530  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-947928999] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 17:37:33.530  1035  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 17:37:33.531  7203  7203 I art     : Almond Protected OAT
08-26 17:37:33.533  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.535  1035  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 17:37:33.536  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:33.536  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 17:37:33.537  1035  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:33.537  1035  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:33.538  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:33.538  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:33.539  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 17:37:33.539  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=100,0,0
08-26 17:37:33.540  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=100,0,0
08-26 17:37:33.540  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 17:37:33.540  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 17:37:33.540  1035  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 17:37:33.540  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 17:37:33.541  1035  1540 D WifiNative-wlan0: SET ps 0: returned true
08-26 17:37:33.541  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 17:37:33.541  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 17:37:33.542  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 17:37:33.542  1035  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 17:37:33.542  1035  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 17:37:33.542  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@55bde7 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:33.542  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@55bde7 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:33.542  1035  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 17:37:33.542  1035  7221 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:33.542  1035  7221 D DhcpStateMachine: DHCP Start wake lock is acquired.,
,08-26 17:37:33.543   309   894 D CommandListener: Setting iface cfg
08-26 17:37:33.543   309   894 D CommandListener: Trying to bring up wlan0
,08-26 17:37:33.544  1035  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 17:37:33.545  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:33.545  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 17:37:33.547  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:33.548  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 17:37:33.549  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 17:37:33.549  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 17:37:33.550  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:33.550  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:33.550  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 17:37:33.550  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 17:37:33.551  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 17:37:33.551  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 17:37:33.551  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 17:37:33.551  1035  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 17:37:33.552  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 17:37:33.570  1035  1540 D WifiNative-wlan0: SET ps 1: returned true
08-26 17:37:33.570  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-26 17:37:33.571  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns,
,08-26 17:37:33.571  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:33.571  1035  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 17:37:33.572  1035  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:33.572  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:33.573  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 17:37:33.574  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 17:37:33.574  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 17:37:33.574  1035  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-26 17:37:33.576  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 17:37:33.576  1035  1546 D ConnectivityService: ignoring duplicate network state non-change
08-26 17:37:33.579  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-26 17:37:33.579  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:33.580  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:33.580  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.580  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 17:37:33.581  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming,
08-26 17:37:33.585  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.585  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:33.585  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 17:37:33.586  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 17:37:33.586  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 17:37:33.587  1035  1546 D ConnectivityService: Adding iface wlan0 to network 101
08-26 17:37:33.588  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-26 17:37:33.591  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.591  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.591  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 17:37:33.593  1035  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 17:37:33.594  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 17:37:33.600  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.600  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:33.601  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 17:37:33.602  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:33.602  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:33.604  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.606  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:33.607  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 17:37:33.607  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.612  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:33.612  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 17:37:33.612  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 17:37:33.620  1035  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 17:37:33.621  1035  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 17:37:33.621  1035  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 17:37:33.622   309   894 E Netd    : netlink response contains error (File exists)
08-26 17:37:33.622  1035  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 17:37:33.623  1035  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 17:37:33.623  1035  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 17:37:33.623  1035  1546 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-26 17:37:33.624  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 17:37:33.624  1035  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 17:37:33.624  1035  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 17:37:33.625  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:33.625  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 17:37:33.625  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:33.625  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 17:37:33.627  1035  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 17:37:33.627  1035  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:33.627  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:33.627  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 17:37:33.627  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:33.627  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
,08-26 17:37:33.627  1035  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-26 17:37:33.627  1035  1546 D ConnectivityService:    accepting network in place of null
08-26 17:37:33.627  1035  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:33.628   309  7231 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 17:37:33.629  1035  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:33.629  1035  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:33.630  1035  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 17:37:33.630  1035  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 17:37:33.630  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 17:37:33.632  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:33.632  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 17:37:33.632  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 17:37:33.633  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 17:37:33.633  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 17:37:33.633  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 17:37:33.634  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:33.634  1035  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 17:37:33.634  1035  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 17:37:33.635  1035  1546 D ConnectivityService: validation of new default Network = false
08-26 17:37:33.635  1035  1546 D ConnectivityService: Default network via Wi,-Fi connected. start DSQN
08-26 17:37:33.635  1035  1546 D DSQN    : enableDataServiceNotify 
08-26 17:37:33.635  1035  1546 D DSQN    : start dsqn bin
,08-26 17:37:33.643  1035  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 17:37:33.643  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:33.643  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:33.643  1035  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:33.643  7203  7203 D WeatherApplication: removeAccount
08-26 17:37:33.644  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 17:37:33.644  7203  7203 D WeatherApplication: Account.length = 0
08-26 17:37:33.645  7203  7203 E WeatherApplication: OPERATOR:OPEN
08-26 17:37:33.646  1035  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 17:37:33.636  7232  7232 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:33.636  7232  7232 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:33.657  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:33.658  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:33.658  1035  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:33.658  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:33
08-26 17:37:33.659  7232  7232 E DSQN    : DSQN ssw
08-26 17:37:33.669  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 17:37:33.669  1035  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 17:37:33.669  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
08-26 17:37:33.670  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-26 17:37:33.670  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 17:37:33.670  1035  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 17:37:33.671  1035  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 17:37:33.671  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.671  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 17:37:33.671  1035  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 17:37:33.672  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.673  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 17:37:33.675  7203  7203 D WeatherAncestor: connectivity changed - connection : true
08-26 17:37:33.676  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-26 17:37:33.680  1817  7236 I CheckinService: active receiver: enabled
,08-26 17:37:33.688   309  7231 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-26 17:37:33.690  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 17:37:33.690  1817  7236 I CheckinService: Preparing to send checkin request
08-26 17:37:33.690  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 17:37:33.691  1817  7236 I EventLogService: Accumulating logs since 1472225789776
08-26 17:37:33.691  7203  7203 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-26 17:37:33.704  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-26 17:37:33.704  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:33
,08-26 17:37:33.727   309  7231 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 17:37:33.745  1035  7221 D DhcpStateMachine: DHCPV4 request on wlan0
,08-26 17:37:33.746  1035  7221 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 17:37:33.746  1035  7221 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 17:37:33.753  1035  1787 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7239 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 17:37:33.754  1817  7236 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-26 17:37:33.746  7242  7242 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:33.746  7242  7242 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:33.755  1035  1787 I ActivityManager: Killing 2172:com.lge.music/u0a34 (adj 15): empty #17
08-26 17:37:33.762  7242  7242 I dhcpcd  : version 5.5.6 starting
,08-26 17:37:33.764  7242  7242 E dhcpcd  : get_duid: m
08-26 17:37:33.764  7242  7242 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 17:37:33.764  7242  7242 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-26 17:37:33.768   309   893 D LGDataListener: argv[0]=dsqncommand
08-26 17:37:33.768   309   893 D LGDataListener: argv[1]=wlan0
08-26 17:37:33.768   309   893 D LGDataListener: argv[2]=1
08-26 17:37:33.768   309   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 17:37:33.775  1035  1096 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 17:37:33.775  1035  1096 D DSQN    : start to monitor internet connection
08-26 17:37:33.779   313  1383 V AudioFlinger: 2172 died, releasing its sessions
,08-26 17:37:33.779   313  1383 V AudioFlinger:  pid 1852 @ 0
08-26 17:37:33.779   313  1383 V AudioFlinger:  pid 3480 @ 1
08-26 17:37:33.779   313  1383 V AudioFlinger:  pid 3480 @ 2
08-26 17:37:33.808  1035  1962 W libprocessgroup: failed to open /acct/uid_10034/pid_2172/cgroup.procs: No such file or directory
,08-26 17:37:33.811  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 15:37:33 GMT], X-Android-Received-Millis=[1472225853811], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472225853767]}
08-26 17:37:33.811  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 17:37:33.811  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 17:37:33.811  1035  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 17:37:33.811  1035  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 17:37:33.811  1035  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:33.812  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:33.812  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 17:37:33.812  1035  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 17:37:33.812  1035  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 17:37:33.812  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:33.812  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:33.812  1035  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:33.812  1035  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:33.812  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 17:37:33.813  1035  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:33.813  1035  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:33.813  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 17:37:33.813  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:33.814  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-26 17:37:33.829  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 17:37:33.830  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:33.831  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 17:37:33.838  7242  7242 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 17:37:33.838  7242  7242 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 17:37:33.838  7242  7242 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 17:37:33.838  7242  7242 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 17:37:33.838  7242  7242 D dhcpcd  : wlan0: sending REQUEST (xid 0x3b76bd54), next in 3.83 seconds
08-26 17:37:33.867  7242  7242 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 17:37:33.879   278   374 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 17:37:33.879   278   374 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 17:37:33.879   278   374 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 17:37:33.880  7239  7267 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 17:37:33.881  7242  7242 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 17:37:33.881  7242  7242 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 17:37:33.881  7242  7242 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 17:37:33.881  7242  7242 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 17:37:33.881  7242  7242 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 17:37:33.882  7242  7242 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 17:37:33.882   278   374 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 17:37:33.882   278   374 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 17:37:33.882   278   374 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 17:37:33.882  7242  7242 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 17:37:33.882  7242  7242 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 17:37:33.882  7239  7267 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 17:37:33.890   278   374 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 17:37:33.890   278   374 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 17:37:33.890   278   374 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 17:37:33.890  7239  7270 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 17:37:33.892   278   374 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 17:37:33.892   278   374 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 17:37:33.892   278   374 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 17:37:33.893  7239  7270 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 17:37:33.918  1035  2032 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7276 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-26 17:37:33.938   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 19.293ms
,08-26 17:37:33.955   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 357us total 16.795ms
,08-26 17:37:33.965  7276  7276 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 17:37:33.965  7276  7276 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 17:37:33.970   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 284us total 13.798ms
,08-26 17:37:33.989  7276  7276 I MultiDex: VM with version 2.1.0 has multidex support
08-26 17:37:33.989  7276  7276 I MultiDex: install
08-26 17:37:33.989  7276  7276 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 17:37:33.997  7276  7276 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-26 17:37:34.123  7239  7239 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 17:37:34.136  7239  7239 I LibraryLoader: Loading: webviewchromium
,08-26 17:37:34.149  7239  7239 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 2178-2191)
08-26 17:37:34.149  7239  7239 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 17:37:34.156  1035  7221 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 17:37:34.158  1035  7221 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 17:37:34.158  1035  7221 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 17:37:34.159  1035  7221 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 17:37:34.159  1035  7221 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 17:37:34.159  1035  7221 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 17:37:34.159  1035  7221 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 17:37:34.159  1035  7221 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 17:37:34.160  1035  7221 D DhcpStateMachine: RunningState
08-26 17:37:34.163  7239  7239 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {38ceb1ff}
,08-26 17:37:34.167  7239  7239 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 17:37:34.168  7239  7239 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 17:37:34.180  7239  7239 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 17:37:34.181  7239  7239 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 17:37:34.193   313  2164 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10093
,08-26 17:37:34.194  7239  7329 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 17:37:34.201  7239  7239 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-26 17:37:34.203  7239  7239 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-26 17:37:34.204  7239  7239 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-26 17:37:34.220  7239  7239 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 17:37:34.220  7239  7239 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 17:37:34.220  7239  7239 I Adreno-EGL: Build Date: 12/12/14 금
08-26 17:37:34.220  7239  7239 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 17:37:34.220  7239  7239 I Adreno-EGL: Remote Branch: 
08-26 17:37:34.220  7239  7239 I Adreno-EGL: Local Patches: 
08-26 17:37:34.220  7239  7239 I Adreno-EGL: Reconstruct Branch: 
,08-26 17:37:34.305  7239  7239 I NSApplication: Starting up...
,08-26 17:37:34.308  7337  7337 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-26 17:37:34.356  7337  7337 I dex2oat : dex2oat took 48.471ms (threads: 4)
,08-26 17:37:34.360  1035  1051 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7351 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 17:37:34.360  1035  1051 I ActivityManager: Killing 6120:com.android.vending/u0a44 (adj 15): empty #17
08-26 17:37:34.367  7276  7294 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 17:37:34.367  7276  7294 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 17:37:34.367  7276  7294 I Adreno-EGL: Build Date: 12/12/14 금
08-26 17:37:34.367  7276  7294 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 17:37:34.367  7276  7294 I Adreno-EGL: Remote Branch: 
08-26 17:37:34.367  7276  7294 I Adreno-EGL: Local Patches: 
08-26 17:37:34.367  7276  7294 I Adreno-EGL: Reconstruct Branch: 
08-26 17:37:34.455  7276  7294 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 17:37:34.455  7276  7294 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 17:37:34.455  7276  7294 I Adreno-EGL: Build Date: 12/12/14 금
08-26 17:37:34.455  7276  7294 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 17:37:34.455  7276  7294 I Adreno-EGL: Remote Branch: 
08-26 17:37:34.455  7276  7294 I Adreno-EGL: Local Patches: 
08-26 17:37:34.455  7276  7294 I Adreno-EGL: Reconstruct Branch: 
,08-26 17:37:34.467  1035  1576 W libprocessgroup: failed to open /acct/uid_10044/pid_6120/cgroup.procs: No such file or directory
,08-26 17:37:34.499  7351  7351 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 17:37:34.601  1035  1956 D WifiServiceImplEx: setWifiEnabled: false pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 17:37:34.602  1035  1956 D WifiService: setWifiEnabled: false pid=6695, uid=10118
08-26 17:37:34.602  1035  1956 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 17:37:34.616  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 17:37:34.616  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 17:37:34.616  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 17:37:34.618  1035  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 17:37:34.619  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-26 17:37:34.619  1035  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 17:37:34.620  1035  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 17:37:34.621  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 17:37:34.621  1035  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 17:37:34.621  1035  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 17:37:34.621  1035  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 17:37:34.624  1035  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 17:37:34.624  1035  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 17:37:34.633  1035  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 17:37:34.634  1035  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:34.634  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.634  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 17:37:34.635  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 17:37:34.636  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 17:37:34.636  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 17:37:34.637  1035  1540 D WifiNative-wlan0: SET ps 1: returned true
08-26 17:37:34.638  1035  7221 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.642   309   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 17:37:34.643  1035  1995 I art     : Explicit concurrent mark sweep GC freed 86920(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.528ms total 80.558ms
08-26 17:37:34.644  1035  1546 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 17:37:34.663  7276  7294 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 17:37:34.663  7276  7294 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 17:37:34.663  7276  7294 I Adreno-EGL: Build Date: 12/12/14 금
08-26 17:37:34.663  7276  7294 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 17:37:34.663  7276  7294 I Adreno-EGL: Remote Branch: 
08-26 17:37:34.663  7276  7294 I Adreno-EGL: Local Patches: 
08-26 17:37:34.663  7276  7294 I Adreno-EGL: Reconstruct Branch: 
,08-26 17:37:34.668  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 17:37:34.668  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-26 17:37:34.670  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 17:37:34.679  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:34.679  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 17:37:34.682  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:34.682  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:34.682  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 17:37:34.682  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 17:37:34.683  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:34.683  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.683  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.683  1035  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@51acc42
08-26 17:37:34.683  1035  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:34.683  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:34.683  1035  1538 D LGWifiP2pService: P2pDisablingState
08-26 17:37:34.683  1035  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.683  1035  1538 D LGWifiP2pService: p2p socket connection lost
08-26 17:37:34.683  1035  1538 D LGWifiP2pService: P2pDisabledState
08-26 17:37:34.683  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:34.683  1035  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:34.684  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:34.684  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:34.684  1035  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 17:37:34.684  1035  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 17:37:34.684  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 17:37:34.684  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.684  1035  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.684  7128  7128 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 17:37:34.685  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 17:37:34.687  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:34.687  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:34.687  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 17:37:34.687  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 17:37:34.687  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-26 17:37:34.687  1035  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.687  1035  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.688  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 17:37:34.688  1941  1941 D WfdsService: WifiP2pState is changed : false
08-26 17:37:34.688  1941  2242 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 17:37:34.688  1941  2242 D WfdsService: Set the WFDS Monitor,: false
08-26 17:37:34.689  1941  2242 D WfdsMonitor: WFDS Monitor is stopped
08-26 17:37:34.689  1941  2242 D WfdsService: STATE : WfdsDisabledState - enter
08-26 17:37:34.689  1941  7153 D CtrlSupplicant: Received on exit socket, terminate
08-26 17:37:34.689  1941  7153 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 17:37:34.689  1941  2247 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 17:37:34.689  1941  7153 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 17:37:34.689  1941  7153 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 17:37:34.689  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 17:37:34.689  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 17:37:34.689  1941  2242 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 17:37:34.689  1035  1540 D WifiNative-wlan0: SET ps 1: returned true
08-26 17:37:34.705   309   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 17:37:34.705  1035  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 17:37:34.705  1035  1546 D DSQN    : disableDataServiceNotify
08-26 17:37:34.705  1035  1546 D DSQN    : stop dsqn bin
,08-26 17:37:34.706  1035  1540 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 17:37:34.707  1035  1540 D WifiNative-p2p0: TERMINATE: returned true
08-26 17:37:34.707  1035  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 17:37:34.707  1035  1540 E WifiStateMachine: useWiFiOffloading() : false
08-26 17:37:34.707  1035  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 17:37:34.708  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-26 17:37:34.709  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:34.709  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:34.710  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 17:37:34.710  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:34.710  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:34.710  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 17:37:34.711  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:34.711  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:34.711  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:34.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:34.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:34.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:34.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:34.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:34.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:34.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:34.711  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:34.711  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:34.711  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 17:37:34.712  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:34.712  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 17:37:34.712  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:34.712  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:34.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:34.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:34.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:34.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bl,uetooth enabled: false
08-26 17:37:34.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:34.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:34.712  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:34.712  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:34.712  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:34.713  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 17:37:34.713  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:34.713  1035  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 17:37:34.713  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:34.713  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:34.714  1035  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:34.714  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:34.714  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 17:37:34.714  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 17:37:34.714  1035  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 17:37:34.714  1035  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 17:37:34.714  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 17:37:34.714  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.714  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.714  1035  7220 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 17:37:34.714  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:34.714  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 17:37:34.715  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 17:37:34.715  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:34.715  1035  1537, V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 17:37:34.716  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:34.716  1035  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:34.716  1035  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:34.716  1035  1546 D NetworkManagementService: Removing idletimer
08-26 17:37:34.716  1035  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:34.717  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:34.717  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 17:37:34.717  1035  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:34.717  1035  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:34.718  1035  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 17:37:34.719  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 17:37:34.719  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 17:37:34.720  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 17:37:34.720  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 17:37:34.720  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 17:37:34.720  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 17:37:34.720  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 17:37:34.721  1035  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-26 17:37:34.748  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 17:37:34.749  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:34.749  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 17:37:34.761  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 17:37:34.762  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:34.763  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:34.778  7128  7128 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 17:37:34.778  7128  7128 I wpa_supplicant: monitor socket send errors count : 1
08-26 17:37:34.778  7128  7128 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-26 17:37:34.779  1035  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 17:37:34.779  1035  7137 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-26 17:37:34.800  7128  7128 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 17:37:34.800  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 17:37:34.800  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 17:37:34.800  1035  7137 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 17:37:34.800  1035  7137 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 17:37:34.801  7128  7128 W wpa_supplicant: USIM:  scard_deinit function
08-26 17:37:34.802  1035  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122831
08-26 17:37:34.802  1035  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122831
08-26 17:37:34.802  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:34.802  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 17:37:34.802  1035  1099 D Tethering: InitialState.processMessage what=4
08-26 17:37:34.803  1035  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=122832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 17:37:34.803  1035  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 17:37:34.803  1035  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=122832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 17:37:34.803  1035  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:34.804  1035  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:34.820  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 17:37:34.821  6502  6539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 17:37:34.829  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:34.837  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-26 17:37:34.837  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:34.838  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 17:37:34.838  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 17:37:34.839  7073  7073 I AppUp4:CustModeStarterReceiver: onReceive
08-26 17:37:34.842  7073  7073 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d9dd804
08-26 17:37:34.842  7073  7073 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 17:37:34.842  7073  7073 D AppUp4:CustFacade: isPhone : true
08-26 17:37:34.842  7073  7073 D AppUp4:CustModeStarterReceiver: begin check event
08-26 17:37:34.843  1035  7221 D DhcpStateMachine: StoppedState
08-26 17:37:34.843  1035  7221 D DhcpStateMachine: StoppedState{ when=-153ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:34.843  7073  7073 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 17:37:34.843  1035  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 17:37:34.844  1035  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 17:37:34.845  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:34.845  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 17:37:34.846  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:34.848  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:34.851  4296  7389 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 17:37:34.853  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 17:37:34.854  4296  7390 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:34.854  4296  7390 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 17:37:34.866  3480  3480 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 17:37:34.866  3480  3480 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:34.866  3480  3480 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 17:37:34.870  7144  7144 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 17:37:34.870  7144  7144 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 17:37:34.871  7102  7392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:34.873  6976  7395 W FormManager: Network not available. Please check & try again.
08-26 17:37:34.882  6976  7396 V FormManager: Network unavailable.
08-26 17:37:34.883  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:34
,08-26 17:37:34.886  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 17:37:34.887  6976  7396 V FormManager: Network unavailable.
08-26 17:37:34.886  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
08-26 17:37:34.890  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 17:37:34.890  7203  7203 D WeatherAncestor: connectivity changed - connection : true
08-26 17:37:34.890  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38141822
08-26 17:37:34.891  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 17:37:34.891  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 17:37:34.891  7203  7203 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 17:37:34.891  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 17:37:34.891  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:34
08-26 17:37:34.909  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 17:37:34.909  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 17:37:34.909  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 17:37:34.909  6866  6866 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 17:37:34.910  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-26 17:37:34.911  6866  6866 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 17:37:34.911  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 17:37:34.911  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 17:37:34.911  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 17:37:34.911  6866  6866 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 17:37:34.911  6866  6866 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 17:37:34.916  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:34.919  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:34.923  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:34.928  6976  7401 W FormManager: Network not available. Please check & try again.
08-26 17:37:34.928  7128  7128 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 17:37:34.928  1035  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 17:37:34.928  1035  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 17:37:34.928  1035  7137 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 17:37:34.929  1035  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-26 17:37:34.934  6976  7402 V FormManager: Network unavailable.
,08-26 17:37:34.937  6976  7402 V FormManager: Network unavailable.
08-26 17:37:34.939  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:34.942  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:34.946  6976  7403 W FormManager: Network not available. Please check & try again.
,08-26 17:37:34.949  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:34.951  6976  7404 V FormManager: Network unavailable.
08-26 17:37:34.953  6976  7404 V FormManager: Network unavailable.
08-26 17:37:34.959  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 17:37:34.959  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 17:37:34.960  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:34.962  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:34.965  4296  7405 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 17:37:34.966  7276  7294 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:34.967  7276  7294 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 17:37:34.967  4296  7406 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 17:37:34.967  4296  7406 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 17:37:34.997  1035  2032 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7407 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 17:37:35.006   309  7423 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 17:37:35.006  1817  7236 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-26 17:37:35.006  1035  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 17:37:35.012  1817  7236 I CheckinService: active receiver: disabled
,08-26 17:37:35.030  1035  1540 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 17:37:35.030  1035  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 17:37:35.030  1035  1540 E WifiStateMachine: useWiFiOffloading() : false
08-26 17:37:35.030  1035  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 17:37:35.030  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-26 17:37:35.030  1941  2242 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 17:37:35.030  1941  2242 D WfdsService: Set the WFDS Monitor: false
08-26 17:37:35.030  1941  2242 D WfdsMonitor: WFDS Monitor is stopped
,08-26 17:37:35.031  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 17:37:35.031  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 17:37:35.031  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 17:37:35.032  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:35.032  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:35.033  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 17:37:35.033  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:35.033  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:35.033  2479  2479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:35.059  7407  7407 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 17:37:35.059  7407  7407 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 17:37:35.068  7407  7407 V [BNRBootReceiver]: Boot Receiver Return
08-26 17:37:35.069  7407  7407 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 17:37:35.078  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 17:37:35.085  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.092  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.109  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 17:37:35.109  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:35.113  6935  6935 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 17:37:35.117  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.128  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.135  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.143  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.144  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 17:37:35.146  6935  6935 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 17:37:35.149  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 17:37:35.153  6866  6866 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 17:37:35.157  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 17:37:35.167  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.177  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 17:37:35.188  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.189  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:35.190  6935  6935 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 17:37:35.198  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.210  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.223  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 17:37:35.237  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.238  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:35.239  6935  6935 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 17:37:35.250  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.268  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.283  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.297  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 17:37:35.298  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:35.299  6935  6935 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 17:37:35.305  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.320  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.332  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.343  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.344  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:35.345  6935  6935 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 17:37:35.351  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.365  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.373  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.385  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.386  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 17:37:35.387  6935  6935 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 17:37:35.399  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 17:37:35.426  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.449  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.470  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 17:37:35.481  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:35.490  6935  6935 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 17:37:35.503  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.517  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.526  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.538  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.538  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 17:37:35.539  6935  6935 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 17:37:35.543  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.548  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 17:37:35.558  1035  1545 D WifiService: New client listening to asynchronous messages
,08-26 17:37:35.559  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:35.566  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.576  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.585  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.586  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:35.587  6935  6935 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-26 17:37:35.589  6808  7052 D UEI.SmartControl: Internal timer expired: 2
08-26 17:37:35.589  6808  7052 D UEI.SmartControl: unbind internal service
08-26 17:37:35.591  6935  6935 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 17:37:35.591  6935  6935 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 17:37:35.599  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.608  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 17:37:35.610  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:35.614  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.625  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.636  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 17:37:35.636  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:35.637  6935  6935 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 17:37:35.639  6935  6935 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 17:37:35.640  6935  6935 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 17:37:35.643  1035  1050 I ActivityManager: Killing 6886:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-26 17:37:35.680  1035  1995 W libprocessgroup: failed to open /acct/uid_10037/pid_6886/cgroup.procs: No such file or directory
,08-26 17:37:35.686  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 17:37:35.695  2208  2208 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 17:37:35.697  2208  2208 D c       : Getting all permits...
08-26 17:37:35.697  2208  2208 D a       : Opening database...
08-26 17:37:35.699  6808  7046 D serial_port: close(fd = 24)
08-26 17:37:35.704  6808  7046 I UEI.SmartControl: Serial port is closed.
08-26 17:37:35.705  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-26 17:37:35.707  2208  2208 D a       : Closing database...
08-26 17:37:35.718  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 17:37:35.724  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 17:37:35.724  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 17:37:35.724  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:35.728  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.735  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.743  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.743  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 17:37:35.745  6935  6935 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 17:37:35.750  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.754  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 17:37:35.754  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 17:37:35.754  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:35.758  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.768  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 17:37:35.778  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.778  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 17:37:35.782  6935  6935 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 17:37:35.788  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:35.795  6906  6906 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 17:37:35.795  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 17:37:35.795  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 17:37:35.803  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:35.812  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.819  6935  6935 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:35.819  6935  6935 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:35.822  6935  6935 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 17:37:35.831  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:35.836  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:35.845  6976  7437 W FormManager: Network not available. Please check & try again.
08-26 17:37:35.847  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.847  6976  7438 V FormManager: Network unavailable.
08-26 17:37:35.854  6976  7438 V FormManager: Network unavailable.
,08-26 17:37:35.864  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-26 17:37:35.881  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 17:37:35.882  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 17:37:35.883  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 17:37:35.889  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:35.895  4296  7439 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 17:37:35.899  6906  6906 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 17:37:35.899  6906  6906 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 17:37:35.899  6906  6906 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:35.901  4296  7440 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 17:37:35.901  4296  7440 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 17:37:35.906  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:35.914  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:35.921  6976  7442 W FormManager: Network not available. Please check & try again.
,08-26 17:37:35.935  6976  7443 V FormManager: Network unavailable.
,08-26 17:37:35.940  6976  7443 V FormManager: Network unavailable.
,08-26 17:37:36.538  1035  1540 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-947925990] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 17:37:36.541  1035  1540 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-947925988] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 17:37:36.636  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:36.651  1035  1099 D Tethering: MasterInitialState.processMessage what=3
08-26 17:37:36.655  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:36.658  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:36.665  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:36.668  5795  5795 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 17:37:36.672  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 17:37:36.674  6502  6539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 17:37:36.701  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:36.721  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 17:37:36.721  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:36.721  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 17:37:36.721  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 17:37:36.728  7073  7073 I AppUp4:CustModeStarterReceiver: onReceive
08-26 17:37:36.731  7073  7073 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d9dd804
08-26 17:37:36.732  7073  7073 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 17:37:36.732  7073  7073 D AppUp4:CustFacade: isPhone : true
08-26 17:37:36.732  7073  7073 D AppUp4:CustModeStarterReceiver: begin check event
08-26 17:37:36.732  7073  7073 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 17:37:36.737  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:36.737  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 17:37:36.741  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:36.744  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:36.752  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 17:37:36.774  4296  7457 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 17:37:36.782  7102  7456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:36.793  4296  7458 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:36.794  4296  7458 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 17:37:36.804  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:36.809  6976  7459 W FormManager: Network not available. Please check & try again.
,08-26 17:37:36.816  3480  3480 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 17:37:36.816  3480  3480 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:36.816  3480  3480 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 17:37:36.817  3480  3480 D PhoneState: setPdpRejectCasuse : false
08-26 17:37:36.821  7144  7144 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 17:37:36.821  7144  7144 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 17:37:36.822  6976  7460 V FormManager: Network unavailable.
08-26 17:37:36.829  6976  7460 V FormManager: Network unavailable.
08-26 17:37:36.834  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:36
,08-26 17:37:36.838  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-26 17:37:36.838  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
,08-26 17:37:36.839  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 17:37:36.839  7203  7203 D WeatherAncestor: connectivity changed - connection : true
08-26 17:37:36.839  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38141822
,08-26 17:37:36.840  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 17:37:36.840  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 17:37:36.840  7203  7203 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 17:37:36.840  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-26 17:37:36.840  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:36
,08-26 17:37:37.619  1035  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:37.620  1035  1648 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 17:37:37.642  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 17:37:37.642  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 17:37:37.642  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 17:37:37.644  1035  1099 D BluetoothManagerService: Message: 1
08-26 17:37:37.644  1035  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 17:37:37.669  1035  1099 D BluetoothManagerService: Message: 20
08-26 17:37:37.669  1035  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e6f29a7:true
,08-26 17:37:37.673  7005  7005 D BluetoothAdapterState: make
08-26 17:37:37.678  7005  7005 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 17:37:37.678  7005  7005 I bluedroid-qcom: init
08-26 17:37:37.679  7005  7489 I BluetoothAdapterState: Entering OffState
08-26 17:37:37.680  7005  7005 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 17:37:37.680  7005  7005 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 17:37:37.680  7005  7005 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 17:37:37.680  7005  7005 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 17:37:37.680  7005  7005 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 17:37:37.682  7005  7005 I bluedroid-qcom: get_profile_interface socket
08-26 17:37:37.682  7005  7005 I bluedroid-qcom: get_profile_interface map_client
,08-26 17:37:37.686  7005  7493 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 17:37:37.686  7492  7492 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:37.691  7005  7493 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 17:37:37.686  7492  7492 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:37.699  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 17:37:37.699  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-26 17:37:37.704  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 17:37:37.704  1035  1099 D BluetoothManagerService: Message: 40
08-26 17:37:37.704  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 17:37:37.705  7005  7020 I bluedroid-qcom: config_hci_snoop_log
08-26 17:37:37.708  7492  7492 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 17:37:37.708  7492  7492 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 17:37:37.708  7492  7492 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 17:37:37.709  1035  1099 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 17:37:37.709  1035  1099 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 17:37:37.711  7492  7492 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-26 17:37:37.716  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:37.718  7492  7492 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 17:37:37.718  7492  7492 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 17:37:37.729  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:37.731  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:37.734  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:37.745  7005  7489 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON,
,08-26 17:37:37.748  1035  1099 D Tethering: MasterInitialState.processMessage what=3
08-26 17:37:37.748  1035  1099 D Tethering: MasterInitialState.processMessage what=3
08-26 17:37:37.749  7005  7493 D BluetoothAdapterProperties: Name is: G3
08-26 17:37:37.749  7005  7489 D BluetoothAdapterProperties: Setting state to 11
08-26 17:37:37.750  7005  7489 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 17:37:37.751  1035  1099 D BluetoothManagerService: Message: 60
08-26 17:37:37.751  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 17:37:37.751  1035  1099 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 17:37:37.752  7005  7489 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 17:37:37.762  7005  7489 D BluetoothBondStateMachine: make
,08-26 17:37:37.766  7005  7489 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:37.767  7005  7489 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 17:37:37.767  7005  7489 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:37.767  7005  7489 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 17:37:37.774  7005  7494 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 17:37:37.774  7005  7489 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 17:37:37.778  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:37.778  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 17:37:37.784  6866  6866 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 17:37:37.785  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:37.789  5795  5795 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 17:37:37.789  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:37.793  7005  7489 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:37.795  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:37.798  7005  7005 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 17:37:37.799  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:37.799  7005  7005 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:37.799  7005  7005 V BluetoothPbapReceiver: ***********state = 11
08-26 17:37:37.803  7005  7005 D HeadsetService: Received start request. Starting profile...
08-26 17:37:37.803  7005  7005 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 17:37:37.803  7005  7005 D LGBluetoothHfpAdapter: Version 1.6
08-26 17:37:37.803  7005  7489 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:37.806  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:37.806  7005  7005 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 17:37:37.807  7005  7005 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 17:37:37.807  7005  7005 D HeadsetStateMachine: make
08-26 17:37:37.793  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 17:37:37.812  6502  6539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 17:37:37.814  7005  7489 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:37.816  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:37.847  7005  7005 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:37.847  7005  7005 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 17:37:37.859  1035  1921 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7513 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-26 17:37:37.864  7005  7005 D HeadsetStateMachine: max_hf_connections = 1
08-26 17:37:37.864  7005  7005 I bluedroid-qcom: get_profile_interface handsfree
,08-26 17:37:37.866  7005  7005 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 17:37:37.867   313   313 V AudioPolicyService: registerClient() client 0xb558a2e0, uid 1002
08-26 17:37:37.867   313  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 17:37:37.867   313  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 17:37:37.867   313  1383 V AudioPolicyManagerEx: getOutput() returns output 2
,08-26 17:37:37.867  7005  7005 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 17:37:37.868   313  2164 V AudioFlinger: registerClient() client 0xb1433130, pid 7005
08-26 17:37:37.869   313  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:37.869   313  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 17:37:37.869  7005  7022 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:37.869  7005  7022 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 17:37:37.869  3480  3497 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:37.869  3480  3497 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 17:37:37.869  1035  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:37.869  1035  1051 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 17:37:37.869   313  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:37.869  7005  7005 V ToneGenerator: Create Track: 0xb4928a80
08-26 17:37:37.869   313  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 17:37:37.869  7005  7005 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 17:37:37.869  7005  7005 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 17:37:37.869  1604  2105 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:37.869  1604  2105 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 17:37:37.869   313  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 17:37:37.870   313  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 17:37:37.870  1852  3981 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:37.870   313  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 17:37:37.870  1852  3981 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 17:37:37.870   313  1382 V AudioPolicyManagerEx: getOutput() returns output 2
,08-26 17:37:37.870  1852  3981 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:37.870  1852  3981 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 17:37:37.870  1035  1932 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:37.870  1035  1932 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 17:37:37.870   313  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 17:37:37.870   313  2164 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 17:37:37.870   313  2164 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 17:37:37.870   313  2164 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 17:37:37.870   313  2164 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 17:37:37.870  7005  7005 V AudioSystem: getLatency() output 2, latency 50
08-26 17:37:37.870  7005  7005 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 17:37:37.870  7005  7005 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 17:37:37.871  1604  2105 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:37.871  1604  2105 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 17:37:37.871  3480  3496 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:37.871  3480  3496 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-26 17:37:37.871   313  2165 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 17:37:37.871  7005  7507 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:37.871   313  2165 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 17:37:37.871   313  2165 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 17:37:37.871  7005  7507 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 17:37:37.871   313  2165 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 17:37:37.871   313  2165 V AudioFlinger: createTrack() lSessionId: 22
08-26 17:37:37.872  5795  5795 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 17:37:37.872  7005  7489 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:37.872  7005  7005 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 17:37:37.872   313  1383 V AudioFlinger: acquiring 22 from 7005, for 7005
08-26 17:37:37.872   313  1383 V AudioFlinger:  added new entry for 22
08-26 17:37:37.873  7005  7005 V ToneGenerator: ToneGenerator INIT OK, time: 125915
08-26 17:37:37.873  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:37.874  7005  7511 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 17:37:37.874  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:37.875  7005  7511 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 17:37:37.875  7005  7511 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 17:37:37.876  7005  7511 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 17:37:37.876   313  2164 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7005
08-26 17:37:37.878  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:37.879   313  2164 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 17:37:37.879   313  2164 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 17:37:37.879   313  2164 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 17:37:37.879   313  2164 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 17:37:37.879   313  2164 V voice   : voice_set_parameters: exit with code(0)
08-26 17:37:37.879   313  2164 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 17:37:37.879   313  2164 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 17:37:37.879   313  2164 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 17:37:37.879   313  2164 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 17:37:37.879   313  2164 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 17:37:37.879   313  2164 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 17:37:37.879  7005  7511 V ToneGenerator: ToneGenerator destructor
08-26 17:37:37.879  7005  7511 V ToneGenerator: stopTone
08-26 17:37:37.879  7005  7511 V ToneGenerator: Delete Track: 0xb4928a80
08-26 17:37:37.879  7005  7005 D A2dpService: Received start request. Starting profile...
08-26 17:37:37.880  7005  7005 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 17:37:37.881  7005  7511 V AudioTrack: ~AudioTrack, releasing session id from 7005 on behalf of 7005
08-26 17:37:37.881   313  2165 V AudioFlinger: releasing 22 from 7005 for 7005
08-26 17:37:37.881   313  2165 V AudioFlinger:  decremented refcount to 0
08-26 17:37:37.881   313  2165 V AudioFlinger: purging stale effects
08-26 17:37:37.881   313  216,5 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 17:37:37.881   313  2165 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 17:37:37.881   313  1119 V AudioPolicyService: AudioCommandThread() waking up
08-26 17:37:37.881  7005  7005 V Avrcp   : make
08-26 17:37:37.881   313  1119 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 17:37:37.881   313  1119 V AudioPolicyManager: releaseOutput() 2
08-26 17:37:37.881   313  1119 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 17:37:37.881   313  2165 V AudioFlinger: PlaybackThread::Track destructor
08-26 17:37:37.881   313  2165 V AudioFlinger: removeClient_l() pid 7005, calling pid 313
08-26 17:37:37.882  7005  7005 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 17:37:37.882  7005  7005 I bluedroid-qcom: get_profile_interface avrcp
08-26 17:37:37.884  7005  7489 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:37.892  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:37.893  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:37.896  7005  7489 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:37.897  7005  7005 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 17:37:37.899  7005  7005 E AudioManager: No RCC entry present to update
08-26 17:37:37.899  7005  7005 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 17:37:37.902  7005  7005 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 17:37:37.903  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 17:37:37.903  7005  7005 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 17:37:37.903  7005  7489 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:37.905  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:37.911  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-26 17:37:37.923  7005  7489 V LGMDMManager: Create singleton instance
08-26 17:37:37.924  7005  7489 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 17:37:37.956  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 17:37:37.956  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:37.956  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-26 17:37:37.956  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 17:37:37.959  7073  7073 I AppUp4:CustModeStarterReceiver: onReceive
08-26 17:37:37.963  7073  7073 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d9dd804
08-26 17:37:37.963  7073  7073 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 17:37:37.963  7073  7073 D AppUp4:CustFacade: isPhone : true
08-26 17:37:37.963  7073  7073 D AppUp4:CustModeStarterReceiver: begin check event
08-26 17:37:37.963  7073  7073 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 17:37:37.967  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:37.967  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 17:37:37.969  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 17:37:37.977  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:37.988  4296  7534 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 17:37:37.988  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 17:37:37.992  4296  7535 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:37.993  4296  7535 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 17:37:38.006  1035  1787 V SIM_STK : Menu title from STK is T-Mobile
08-26 17:37:38.006  1035  1787 V SIM_STK : Menu title from STK is T-Mobile
,08-26 17:37:38.022  7102  7536 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:38.026  6976  7539 W FormManager: Network not available. Please check & try again.
08-26 17:37:38.028  6976  7540 V FormManager: Network unavailable.
08-26 17:37:38.029  3480  3480 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 17:37:38.029  3480  3480 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:38.029  3480  3480 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 17:37:38.032  7144  7144 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 17:37:38.032  6976  7540 V FormManager: Network unavailable.
08-26 17:37:38.032  7144  7144 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 17:37:38.045  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:38
,08-26 17:37:38.045  7513  7513 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 17:37:38.046  7513  7513 W LG Account v2.2: No ProfileInfo entries
08-26 17:37:38.046  7513  7513 I LG Account v2.2: isEnabled: false
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]Country: EU
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]Operator: OPEN
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]Ranking support: false
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]Comfort support: false
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]Accessory: true
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]Health device: true
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]Extra Pedometer: false
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]Blood glucose device: false
08-26 17:37:38.046  7513  7513 I Feature : [Lifetracker]Device Number: 3
08-26 17:37:38.047  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 17:37:38.047  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
08-26 17:37:38.050  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 17:37:38.050  7203  7203 D WeatherAncestor: connectivity changed - connection : true
08-26 17:37:38.050  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38141822
08-26 17:37:38.051  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 17:37:38.051  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 17:37:38.051  7203  7203 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 17:37:38.051  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 17:37:38.051  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:38
08-26 17:37:38.056  6866  6866 D BluetoothPermissionRequest: onReceive
08-26 17:37:38.062  6866  6866 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 17:37:38.076  6502  6502 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 17:37:38.080  6502  6539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 17:37:38.091  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 17:37:38.091  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:38.098  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 17:37:38.101  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 17:37:38.102  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 17:37:38.102  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 17:37:38.102  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 17:37:38.102  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 17:37:38.102  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 17:37:38.102  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 17:37:38.102  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 17:37:38.102  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 17:37:38.102  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 17:37:38.103  7005  7005 I BluetoothA2dpServiceJni: classInitNative
08-26 17:37:38.103  7005  7005 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 17:37:38.103  7005  7005 D A2dpStateMachine: make
08-26 17:37:38.104  7005  7005 I bluedroid-qcom: get_profile_interface a2dp
08-26 17:37:38.105  7005  7545 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-26 17:37:38.106  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 17:37:38.106  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:38.106  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 17:37:38.106  7073  7073 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 17:37:38.107  7005  7005 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 17:37:38.107  7005  7005 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 17:37:38.108  7073  7073 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 17:37:38.108  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:38.108  7005  7005 D HeadsetStateMachine: Proxy object connected
08-26 17:37:38.109  7005  7544 D A2dpStateMachine: Enter Disconnected: -2
08-26 17:37:38.109  7005  7005 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 17:37:38.109  7005  7005 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 17:37:38.110  7005  7005 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 17:37:38.112  7005  7005 D HidService: Received start request. Starting profile...
08-26 17:37:38.112  7005  7005 I bluedroid-qcom: get_profile_interface hidhost
08-26 17:37:38.112  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:38.112  7073  7073 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d9dd804
08-26 17:37:38.112  7073  7073 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 17:37:38.112  7073  7073 D AppUp4:CustFacade: isPhone : true
08-26 17:37:38.113  7073  7073 D AppUp4:CustModeStarterReceiver: begin check event
08-26 17:37:38.113  7073  7073 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 17:37:38.115  7005  7005 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 17:37:38.116  7005  7005 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 17:37:38.116  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:38.117  7005  7005 D HealthService: Received start request. Starting profile...
08-26 17:37:38.117  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 17:37:38.119  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:38.120  7005  7005 I bluedroid-qcom: get_profile_interface health
08-26 17:37:38.120  7005  7005 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 17:37:38.120  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:38.121  7005  7005 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 17:37:38.121  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:38.121  7005  7511 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 17:37:38.122  7005  7005 D PanService: Received start request. Starting profile...
08-26 17:37:38.122  7005  7005 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 17:37:38.122  7005  7005 I bluedroid-qcom: get_profile_interface pan
08-26 17:37:38.122  7005  7511 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 17:37:38.123  7005  7511 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 17:37:38.125  4296  7549 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 17:37:38.128  4296  7550 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:38.128  4296  7550 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 17:37:38.129  7005  7005 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 17:37:38.129  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
,08-26 17:37:38.131  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 17:37:38.131  7005  7005 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 17:37:38.142  7005  7005 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:38.142  7005  7005 D BtGatt.GattService: Received start request. Starting profile...
08-26 17:37:38.142  7005  7005 D BtGatt.GattService: start()
08-26 17:37:38.142  7005  7005 I bluedroid-qcom: get_profile_interface gatt
08-26 17:37:38.143  7005  7005 D BtGatt.AdvertiseManager: advertise manager created
,08-26 17:37:38.146  7102  7552 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:38.149  3480  3480 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 17:37:38.149  3480  3480 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:38.150  3480  3480 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 17:37:38.151  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:38.152  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:38.152  7005  7005 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 17:37:38.153  7005  7005 V BluetoothMapService: BluetoothMapBinder()
08-26 17:37:38.153  7005  7005 D BluetoothMapService: Received start request. Starting profile...
08-26 17:37:38.153  7005  7005 D BluetoothMapService: start()
08-26 17:37:38.154  6976  7556 W FormManager: Network not available. Please check & try again.
08-26 17:37:38.156  7144  7144 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 17:37:38.156  7144  7144 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 17:37:38.160  7005  7005 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 17:37:38.160  7005  7005 D BluetoothMapEmailAppObserver: createReceiver()
08-26 17:37:38.163  7005  7005 D BluetoothMapEmailAppObserver: initObservers()
08-26 17:37:38.163  7005  7005 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 17:37:38.170  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:38
08-26 17:37:38.170  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
,08-26 17:37:38.173  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 17:37:38.173  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
08-26 17:37:38.173  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 17:37:38.173  7203  7203 D WeatherAncestor: connectivity changed - connection : true
08-26 17:37:38.174  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38141822
08-26 17:37:38.174  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 17:37:38.174  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 17:37:38.174  6976  7557 V FormManager: Network unavailable.
08-26 17:37:38.174  7203  7203 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 17:37:38.174  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 17:37:38.175  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:37:38
08-26 17:37:38.175  7005  7005 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 17:37:38.178  7005  7005 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 17:37:38.182  7005  7005 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 17:37:38.182  7005  7005 V PanService: [BTUI] SIM Extra State :ABSENT
,08-26 17:37:38.185  6976  7557 V FormManager: Network unavailable.
08-26 17:37:38.185  7005  7005 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 17:37:38.188  7005  7005 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 17:37:38.188  7005  7005 V BluetoothMapService: Handler(): got msg=1
08-26 17:37:38.189  7005  7489 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 17:37:38.189  7005  7489 I bluedroid-qcom: enable
08-26 17:37:38.189  7005  7489 I bt_hci_bdroid: init
08-26 17:37:38.190  7005  7559 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 17:37:38.190  7005  7559 I bt-btu  : btu_task pending for preload complete event
08-26 17:37:38.191  7005  7489 I bt_vendor: bt-vendor : init
08-26 17:37:38.191  7005  7489 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 17:37:38.191  7005  7489 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 17:37:38.191  7005  7489 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 17:37:38.191  7005  7489 D bt_userial_mct: userial_init
08-26 17:37:38.191  7005  7489 D bt_hci_bdroid: set_power 1
,08-26 17:37:38.191  7005  7489 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 17:37:38.191  7005  7489 I bt_vendor: Starting hciattach daemon
08-26 17:37:38.191  7005  7489 I bt_vendor: try to set true
08-26 17:37:38.193  7005  7005 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:38.186  7562  7562 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:38.186  7562  7562 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:38.199  7005  7005 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 17:37:38.199  7005  7005 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 17:37:38.199  7005  7005 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 17:37:38.199  7005  7005 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:38.200  7005  7005 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-26 17:37:38.211  7563  7563 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
08-26 17:37:38.288  7569  7569 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 17:37:38.310  7570  7570 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 17:37:38.348  7572  7572 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 17:37:38.371  7573  7573 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 17:37:38.384  7574  7574 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 17:37:38.404  7575  7575 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 17:37:38.436  7577  7577 I libmdmdetect: ESOC framework not supported
08-26 17:37:38.439  7577  7577 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 17:37:38.451  7577  7577 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-26 17:37:38.451  7577  7577 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 17:37:38.451  7577  7577 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 17:37:38.451  7577  7577 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 17:37:38.451  7577  7577 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 17:37:38.451  7577  7577 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-26 17:37:38.451  7577  7577 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings,
08-26 17:37:38.500  7577  7578 E QC-QMI  : qmi_client [7577] 14: failed to locate client data
08-26 17:37:38.501   453   453 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-26 17:37:38.501   453   453 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-26 17:37:38.544  7582  7582 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 17:37:38.571  7586  7586 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 17:37:38.593  7005  7489 I bt_vendor: bluetooth satus is on
08-26 17:37:38.593  7005  7489 D bt_hci_bdroid: preload
08-26 17:37:38.593  7005  7561 D bt_userial_mct: userial_open(port:0)
08-26 17:37:38.593  7005  7561 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 17:37:38.597  7005  7561 I bt_vendor: Done intiailizing UART
08-26 17:37:38.598  7005  7561 I bt_vendor: Done intiailizing UART
08-26 17:37:38.598  7005  7561 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 17:37:38.598  7005  7561 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 17:37:38.598  7005  7588 D bt_userial_mct: Entering userial_read_thread()
08-26 17:37:38.598  7005  7559 I bt-btu  : btu_task received preload complete event
08-26 17:37:38.599  7005  7559 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 17:37:38.599  7005  7559 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 17:37:38.602  7005  7559 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 17:37:38.605  7005  7559 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 17:37:38.606  7005  7559 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 17:37:38.677  7005  7559 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 17:37:38.677  7005  7559 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0164061 
,08-26 17:37:38.677  7005  7559 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0164061 
,08-26 17:37:38.710  7005  7493 E bt-btif : Calling BTA_HhEnable
,08-26 17:37:38.710  7005  7493 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-26 17:37:38.710  7005  7493 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 17:37:38.710  7005  7559 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-26 17:37:38.710  7005  7559 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 17:37:38.710  7005  7559 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 17:37:38.711  7005  7559 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 17:37:38.711  7005  7559 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 17:37:38.719  7005  7493 D BluetoothAdapterProperties: Name is: G3
,08-26 17:37:38.721  7005  7493 D BluetoothAdapterProperties: Scan Mode:20,
08-26 17:37:38.721  7005  7493 D BluetoothAdapterProperties: Discoverable Timeout:120,
08-26 17:37:38.721  7005  7493 D bt_hci_bdroid: postload
,08-26 17:37:38.721  7005  7561 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 17:37:38.722  7005  7493 D bte_conf: Device ID record 1 : primary
,08-26 17:37:38.722  7005  7493 D bte_conf:   vendorId            = 00c4
,08-26 17:37:38.722  7005  7493 D bte_conf:   vendorIdSource      = 0001
08-26 17:37:38.722  7005  7493 D bte_conf:   product             = 13a1
08-26 17:37:38.722  7005  7493 D bte_conf:   version             = 1000
,08-26 17:37:38.722  7005  7493 D bte_conf:   clientExecutableURL = ,
08-26 17:37:38.722  7005  7493 D bte_conf:   serviceDescription  = 
08-26 17:37:38.722  7005  7493 D bte_conf:   documentationURL    = 
08-26 17:37:38.722  7005  7493 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 17:37:38.726  7005  7489 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 17:37:38.726  7005  7489 D BluetoothAdapterProperties: ScanMode =  20
08-26 17:37:38.726  7005  7489 D BluetoothAdapterProperties: State =  11
08-26 17:37:38.726  7005  7489 D BluetoothAdapterProperties: mDiscoverableTimeout = 120,
08-26 17:37:38.726  7005  7489 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 17:37:38.726  7005  7489 D BluetoothAdapterProperties: Setting state to 12
08-26 17:37:38.726  7005  7489 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 17:37:38.727  7005  7493 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 17:37:38.726  7590  7590 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:38.726  7590  7590 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:38.738  7005  7489 I BluetoothAdapterState: Entering On State
,08-26 17:37:38.740  7005  7559 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 17:37:38.741  7005  7561 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 17:37:38.742  1035  1099 D BluetoothManagerService: Message: 60
08-26 17:37:38.742  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 17:37:38.742  1035  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 17:37:38.745  7005  7561 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 17:37:38.745  7005  7561 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 17:37:38.745  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 17:37:38.745  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 17:37:38.747  7005  7561 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 17:37:38.748  1852  2460 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:38.749  7005  7493 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 17:37:38.749  7005  7493 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 17:37:38.749  7005  7493 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 17:37:38.750  7005  7489 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 17:37:38.750  7005  7588 E bt_mct  : hci lib postload completed
08-26 17:37:38.750  7005  7489 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 17:37:38.751  7005  7489 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 17:37:38.752  7005  7489 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-26 17:37:38.756  7005  7559 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:38.756  7005  7559 W bt-smp  : Plain text(LSB ~ MSB) = b7 be 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:38.756  7005  7559 W bt-smp  : Encrypted text(LSB ~ MSB) = 3f 3d f0 e3 d0 23 70 82 c3 30 85 50 f6 47 c7 1e 
08-26 17:37:38.756  7005  7559 W bt-btm  : Stopping oneshot timer
08-26 17:37:38.758  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:38.758  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:38.758  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:38.758  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:38.758  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:38.758  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:38.758  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:38.758  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:38.763  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:38.770  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:38.770  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:38.770  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:38.770  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:38.770  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:38.770  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:38.770  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:38.770  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:38.773  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:38.776  1852  1852 D BluetoothHeadset: Proxy object connected
,08-26 17:37:38.779  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:38.783  1852  1852 D BluetoothHeadset: Proxy object connected
08-26 17:37:38.787  6866  6883 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 17:37:38.788  7005  7559 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:38.788  7005  7559 W bt-smp  : Plain text(LSB ~ MSB) = 8e 61 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:38.788  7005  7559 W bt-smp  : Encrypted text(LSB ~ MSB) = 03 e9 9b 60 3c 08 46 ff a5 0c 1f 0d 10 4c ea 47 
08-26 17:37:38.788  7005  7559 W bt-btm  : Stopping oneshot timer
,08-26 17:37:38.790  7005  7489 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 17:37:38.798  6866  6885 D BluetoothMap: onBluetoothStateChange: up=true
08-26 17:37:38.799  6866  6866 D BluetoothInputDevice: Proxy object connected
08-26 17:37:38.799  6866  6866 D HidProfile: Bluetooth service connected
08-26 17:37:38.803  1035  1099 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 17:37:38.804  1035  1035 D BluetoothHeadset: Proxy object connected
08-26 17:37:38.807  6866  6866 D BluetoothMap: Proxy object connected
08-26 17:37:38.807  6866  6883 D BluetoothPan: onBluetoothStateChange on: true
08-26 17:37:38.807  6866  6883 D BluetoothPan: onBluetoothStateChange call bindService
08-26 17:37:38.808  6866  6866 D MapProfile: Bluetooth service connected
08-26 17:37:38.808  6866  6866 D BluetoothMap: getConnectedDevices()
08-26 17:37:38.809  7005  7020 V BluetoothMapService: getConnectedDevices()
08-26 17:37:38.810  7595  7595 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 17:37:38.811  7005  7559 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:38.811  7005  7559 W bt-smp  : Plain text(LSB ~ MSB) = cf d5 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:38.811  7005  7559 W bt-smp  : Encrypted text(LSB ~ MSB) = db 54 98 b2 d3 0f 81 d8 a6 6e 71 37 b1 cb ae 0c 
08-26 17:37:38.811  7005  7559 W bt-btm  : Stopping oneshot timer
08-26 17:37:38.813  1035  1099 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 17:37:38.814  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:38.815  1035  1035 D BluetoothA2dp: Proxy object connected
,08-26 17:37:38.819  6866  6866 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 17:37:38.819  6866  6866 D PanProfile: Bluetooth service connected
08-26 17:37:38.820  1852  1852 D BluetoothHeadset: Proxy object connected
08-26 17:37:38.821  6866  7378 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 17:37:38.823  1035  1099 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 17:37:38.823  1035  1099 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 17:37:38.824  7005  7559 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:38.824  7005  7559 W bt-smp  : Plain text(LSB ~ MSB) = fb 30 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:38.824  7005  7559 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e d8 77 f1 c5 20 b1 d0 dd 75 56 0e 44 23 28 11 
08-26 17:37:38.824  7005  7559 W bt-btm  : Stopping oneshot timer
08-26 17:37:38.824  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:38.825  1941  2103 D LGBluetoothAPIService: Message: 1
08-26 17:37:38.825  1941  2103 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 17:37:38.828  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-26 17:37:38.829  6695  6695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 17:37:38.832  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:38.835  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:38.838  1941  2103 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 17:37:38.838  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 17:37:38.838  1035  1099 D BluetoothManagerService: Message: 40
08-26 17:37:38.838  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-26 17:37:38.840  6866  6866 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 17:37:38.841  7005  7559 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:38.841  7005  7559 W bt-smp  : Plain text(LSB ~ MSB) = f3 33 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:38.841  7005  7559 W bt-smp  : Encrypted text(LSB ~ MSB) = 65 18 8a 79 72 f1 2a 9f c8 79 6f 21 e6 59 9a 50 
08-26 17:37:38.841  7005  7559 W bt-btm  : Stopping oneshot timer
08-26 17:37:38.842  7005  7005 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:38.842  1035  1099 D BluetoothManagerService: Message: 30
08-26 17:37:38.842  7005  7005 D BluetoothMapService: STATE_ON
08-26 17:37:38.842  7005  7005 V BluetoothMapService: Handler(): got msg=1
08-26 17:37:38.843  7005  7005 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 17:37:38.845  6866  6866 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 17:37:38.847  7005  7608 D BluetoothMapMasInstance: MAS initSocket()
08-26 17:37:38.848  7005  7005 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 17:37:38.848  1035  1099 D BluetoothManagerService: Message: 30
08-26 17:37:38.848  7005  7005 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 17:37:38.849  7005  7608 D BluetoothMapMasInstance:   masId = 00
08-26 17:37:38.849  7005  7608 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 17:37:38.849  7005  7608 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 17:37:38.849  7005  7608 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 17:37:38.851  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 17:37:38.851  1941  2103 D LGBluetoothAPIService: Message: 100
,08-26 17:37:38.851  1941  2103 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 17:37:38.852  1035  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:38.853  7005  7608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:38.853  6866  6866 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 17:37:38.854  7005  7608 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 17:37:38.855  7005  7608 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 17:37:38.855  7005  7608 D BluetoothMapMasInstance: Accepting socket connection...
08-26 17:37:38.855  7005  7493 D BluetoothAdapterProperties: Scan Mode:21
08-26 17:37:38.855  7005  7493 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 17:37:38.858  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:38.860  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:38.860  6866  6866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 17:37:38.862  6866  6866 D BluetoothA2dp: Proxy object connected
08-26 17:37:38.863  6866  6866 D A2dpProfile: Bluetooth service connected
08-26 17:37:38.866  6866  6866 D BluetoothHeadset: Proxy object connected
08-26 17:37:38.866  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:38.866  7005  7005 V BluetoothPbapService: Pbap Service onCreate
08-26 17:37:38.866  7005  7005 V BluetoothPbapService: Starting PBAP service
08-26 17:37:38.867  6866  6866 D HeadsetProfile: Bluetooth service connected
08-26 17:37:38.867  7005  7005 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 17:37:38.868  7005  7005 V BluetoothPbapService: Pbap Service onBind
08-26 17:37:38.869  7005  7005 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:38.869  7005  7005 V BluetoothPbapService: state: 12
08-26 17:37:38.869  7005  7005 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 17:37:38.869  7005  7005 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:38.869  7005  7005 V BluetoothPbapReceiver: ***********state = 12
,08-26 17:37:38.870  7005  7005 V BluetoothPbapService: Handler(): got msg=1
,08-26 17:37:38.871  7005  7005 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 17:37:38.872  7005  7611 V BluetoothPbapService: Pbap Service initSocket
08-26 17:37:38.872  1035  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:38.873  7005  7611 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:38.874  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:38.874  2208  2208 D c       : Getting all permits...
08-26 17:37:38.874  2208  2208 D a       : Opening database...
08-26 17:37:38.875  6866  6866 D DockEventReceiver: finishStartingService: stopping service
08-26 17:37:38.875  7005  7611 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 17:37:38.875  7005  7611 V BluetoothPbapService: Succeed to create listening socket 
08-26 17:37:38.875  7005  7611 V BluetoothPbapService: Accepting socket connection...
08-26 17:37:38.876  6866  6866 D BluetoothPbap: Proxy object connected
08-26 17:37:38.876  6866  6866 D PbapServerProfile: Bluetooth service connected
08-26 17:37:38.878  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-26 17:37:38.879  2208  2208 D a       : Closing database...
08-26 17:37:38.887  6866  6866 D BluetoothPermissionRequest: onReceive
08-26 17:37:38.888  6866  6866 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 17:37:38.890  6866  6866 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 17:37:38.892  7005  7005 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 17:37:38.893  7005  7005 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 17:37:38.898  7005  7005 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-26 17:37:38.906  7239  7271 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-26 17:37:38.915  7005  7005 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 17:37:38.916  7005  7005 V BtOppService: onCreate
,08-26 17:37:38.920  7005  7005 V BluetoothOppNotification: send message
08-26 17:37:38.923  7005  7005 V BtOppService: Starting RfcommListener
08-26 17:37:38.928  7005  7005 D BluetoothOppPreference: Dumping Names:  
08-26 17:37:38.928  7005  7005 D BluetoothOppPreference: {}
08-26 17:37:38.928  7005  7005 D BluetoothOppPreference: Dumping Channels:  
08-26 17:37:38.928  7005  7005 D BluetoothOppPreference: {}
08-26 17:37:38.929  7005  7005 V BtOppService: onStartCommand
08-26 17:37:38.932  7005  7621 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-26 17:37:38.933  7005  7005 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:38.933  7005  7005 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 17:37:38.936  7005  7005 V BluetoothOppNotification: new notify threadi!
08-26 17:37:38.937  7005  7005 V BluetoothOppNotification: send delay message
08-26 17:37:38.938  7005  7621 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 17:37:38.938  7005  7618 V BtOppService: Deleted complete outbound shares, number =  0
08-26 17:37:38.938  7005  7005 V BtOppService: start RfcommListener
08-26 17:37:38.940  7005  7618 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 17:37:38.940  7005  7618 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 17:37:38.942  7005  7005 V BtOppService: RfcommListener started
08-26 17:37:38.942  7005  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 17:37:38.942  7005  7618 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b0d1bdf on behalf of 
08-26 17:37:38.944  7005  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@308d002c on behalf of 
08-26 17:37:38.945  7005  7623 V BtOppRfcommListener: Starting RFCOMM listener....
,08-26 17:37:38.948  7005  7622 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 17:37:38.949  7005  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 17:37:38.950  7005  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@301eaaf5 on behalf of 
08-26 17:37:38.951  7005  7622 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 17:37:38.952  7005  7622 V BluetoothOppNotification: outbound notification was removed.
08-26 17:37:38.952  7005  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 17:37:38.954  7005  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a3a08a on behalf of 
08-26 17:37:38.954  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:38.954  7005  7622 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 17:37:38.955  7005  7623 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:38.956  7005  7623 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 17:37:38.956  7005  7623 V BtOppRfcommListener: Started RFCOMM listener....
08-26 17:37:38.957  7005  7623 I BtOppRfcommListener: Accept thread started.
08-26 17:37:38.957  7005  7623 V BtOppRfcommListener: Accepting connection...
08-26 17:37:38.957  7005  7621 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c5196fb on behalf of 
08-26 17:37:38.958  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:38.958  7005  7005 V BluetoothFtpService: Ftp Service onCreate
08-26 17:37:38.958  7005  7005 I BluetoothFtpService: Ftp Service onCreate
08-26 17:37:38.959  7005  7005 V BluetoothFtpService: Ftp Service onStartCommand
08-26 17:37:38.959  7005  7005 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:38.959  7005  7005 V BluetoothFtpService: Starting Listening on sockets
08-26 17:37:38.959  7005  7005 V BtOppService: ContentObserver received notification
08-26 17:37:38.959  7005  7005 V BtOppService: ContentObserver received notification
08-26 17:37:38.960  7005  7005 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 17:37:38.960  7005  7005 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 17:37:38.960  7005  7005 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 17:37:38.960  7005  7005 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:38.960  7005  7005 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
,08-26 17:37:38.960  7005  7005 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 17:37:38.961  7005  7622 V BluetoothOppNotification: inbound notification was removed.
08-26 17:37:38.961  7005  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 17:37:38.963  7005  7005 V BluetoothFtpService: Handler(): got msg=1
08-26 17:37:38.963  7005  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6fc0171 on behalf of 
08-26 17:37:38.964  7005  7005 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 17:37:38.964  7005  7005 V BluetoothFtpService: Ftp Service initSocket
08-26 17:37:38.965  7005  7621 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 17:37:38.965  7005  7621 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 17:37:38.966  1035  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:38.967  7005  7005 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:38.968  7005  7005 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-26 17:37:38.968  7005  7005 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 17:37:38.970  7005  7624 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 17:37:38.970  7005  7621 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10233b56 on behalf of 
08-26 17:37:38.971  7005  7621 V BluetoothOppNotification: update too frequent, put in queue
,08-26 17:37:38.973  7005  7621 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-26 17:37:38.984  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:38.984  7005  7005 V BluetoothSapService: Sap Service onCreate
,08-26 17:37:38.986  7005  7005 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:38.986  7005  7005 V BluetoothSapService: state: 12
08-26 17:37:38.986  7005  7005 V BluetoothSapService: Starting SAP server process
08-26 17:37:38.987  7005  7005 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 17:37:38.986  7625  7625 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:38.986  7625  7625 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:38.990  7005  7626 V BluetoothSapService: Sap Service initRfcommSocket
08-26 17:37:38.991  1035  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:38.992  7005  7626 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:38.994  7005  7626 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 17:37:38.994  7005  7626 V BluetoothSapService: Succeed to create listening socket 
08-26 17:37:38.994  7005  7626 V BluetoothSapService: Accepting socket connection...
08-26 17:37:39.000  7625  7625 V BT_SAP  : Event pipe created
08-26 17:37:39.000  7625  7625 V BT_SAP  : create_server_socket qcom.sap.server
08-26 17:37:39.000  7625  7625 V BT_SAP  : created socket fd 6
,08-26 17:37:39.688  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:39.688  1035  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:39.711  1035  1540 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 17:37:39.713  1035  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 17:37:39.841  1035  1995 I ActivityManager: Killing 7407:com.lge.bnr/1000 (adj 15): empty #17
,08-26 17:37:39.873  1035  1787 W libprocessgroup: failed to open /acct/uid_1000/pid_7407/cgroup.procs: No such file or directory
,08-26 17:37:39.940  7005  7005 V BluetoothOppNotification: new notify threadi!
,08-26 17:37:39.941  7005  7005 V BluetoothOppNotification: send delay message
,08-26 17:37:39.953  7005  7636 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 17:37:39.956  7005  7636 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b2fb6e2 on behalf of 
08-26 17:37:39.960  7005  7636 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-26 17:37:39.963  7005  7636 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 17:37:39.965  7005  7636 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11d5ea73 on behalf of 
08-26 17:37:39.966  7005  7636 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 17:37:39.968  7005  7636 V BluetoothOppNotification: outbound notification was removed.
08-26 17:37:39.968  7005  7636 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 17:37:39.969  7005  7636 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d760d30 on behalf of 
08-26 17:37:39.970  7005  7636 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 17:37:39.972  7005  7636 V BluetoothOppNotification: inbound notification was removed.
08-26 17:37:39.973  7005  7636 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-26 17:37:39.976  7005  7636 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16686da9 on behalf of 
08-26 17:37:39.996  1035  1995 I ActivityManager: Killing 6808:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 17:37:40.018  6935  6935 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 17:37:40.019  6935  6935 W System.err: android.os.DeadObjectException
08-26 17:37:40.019  6935  6935 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 17:37:40.019  6935  6935 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 17:37:40.019  6935  6935 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 17:37:40.019  6935  6935 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 17:37:40.019  6935  6935 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 17:37:40.019  6935  6935 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 17:37:40.019  6935  6935 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 17:37:40.019  6935  6935 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 17:37:40.019  6935  6935 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 17:37:40.019  6935  6935 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 17:37:40.019  6935  6935 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:40.019  6935  6935 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:40.019  6935  6935 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 17:37:40.020  6935  6935 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 17:37:40.020  6935  6935 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 17:37:40.020  6935  6935 W System.err: android.os.DeadObjectException
08-26 17:37:40.020  6935  6935 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 17:37:40.020  6935  6935 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 17:37:40.020  6935  6935 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 17:37:40.020  6935  6935 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 17:37:40.020  6935  6935 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 17:37:40.020  6935  6935 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 17:37:40.020  6935  6935 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 17:37:40.021  6935  6935 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 17:37:40.021  6935  6935 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 17:37:40.021  6935  6935 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 17:37:40.021  6935  6935 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:40.021  6935  6935 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:40.021  6935  6935 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 17:37:40.021  6935  6935 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 17:37:40.021  6935  6935 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 17:37:40.021  6935  6935 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-26 17:37:40.055  1035  1787 W libprocessgroup: failed to open /acct/uid_1000/pid_6808/cgroup.procs: No such file or directory
,08-26 17:37:40.060  1035  1787 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-26 17:37:40.065  6935  6935 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 17:37:40.065  6935  6935 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 17:37:40.123  1035  1648 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7638 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 17:37:40.157  6935  6935 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 17:37:40.223  7638  7638 D UEI.SmartControl: Quickset Services start...
,08-26 17:37:40.229  7638  7638 I UEI.SmartControl: Manufacture = LGE
,08-26 17:37:40.229  7638  7638 D UEI.SmartControl: Id = LGNevo
,08-26 17:37:40.230  7638  7638 D UEI.SmartControl: File observer start...
,08-26 17:37:40.231  7638  7638 E UEI.SmartControl: IR Port is disabled: false
08-26 17:37:40.231  7638  7638 D UEI.SmartControl: Starting file observer...
08-26 17:37:40.232  7638  7638 D UEI.SmartControl: Extracting JNI libs...
08-26 17:37:40.232  7638  7638 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 17:37:40.328  7638  7638 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 17:37:40.328  7638  7638 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-26 17:37:40.328  7638  7638 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 17:37:40.369  7638  7638 I UEI.SmartControl: --- Selecting new region: 6,
,08-26 17:37:40.371  7638  7638 I UEI.SmartControl: Model = LG-D855
08-26 17:37:40.373  7638  7638 D UEI.SmartControl: QS Service created
08-26 17:37:40.389  7638  7638 I UEI.SmartControl: Service initServices...
08-26 17:37:40.394  7638  7638 D UEI.SmartControl: QS start get config
,08-26 17:37:40.441  7638  7638 D UEI.SmartControl: Loading JNI Libs...
,08-26 17:37:40.661  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 17:37:40.661  1035  1956 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3f59485e mBinding = false
,08-26 17:37:40.678  1035  1099 D BluetoothManagerService: Message: 2
08-26 17:37:40.679  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 17:37:40.679  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 17:37:40.679  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 17:37:40.680  1035  1099 D BluetoothManagerService: Sending off request.
08-26 17:37:40.683  7005  7607 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-26 17:37:40.685  7005  7489 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 17:37:40.685  7005  7489 D BluetoothAdapterProperties: Setting state to 13
08-26 17:37:40.685  7005  7489 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 17:37:40.686  7005  7489 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 17:37:40.686  7005  7489 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 17:37:40.689  7005  7493 D BluetoothAdapterProperties: Scan Mode:20
08-26 17:37:40.689  1035  1099 D BluetoothManagerService: Message: 60
08-26 17:37:40.689  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 17:37:40.689  1035  1099 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 17:37:40.690  7005  7489 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 17:37:40.691  7005  7611 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:40.692  7005  7608 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 17:37:40.692  7005  7608 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:40.692  7005  7608 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 17:37:40.692  7005  7608 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 17:37:40.692  7005  7608 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 17:37:40.692  7005  7608 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 17:37:40.692  7005  7608 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 17:37:40.692  7005  7608 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 17:37:40.693  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 17:37:40.693  7005  7559 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 17:37:40.694  7005  7623 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:40.695  7005  7624 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:40.695  7005  7626 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:40.695  7005  7489 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 17:37:40.697  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 17:37:40.69,7  7005  7559 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-26 17:37:40.706  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:40.707  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 17:37:40.709  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:40.709  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:40.709  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:40.709  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:40.709  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:40.709  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:40.709  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:40.709  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:40.709  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:40.711  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:40.711  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:40.713  7005  7005 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:40.713  7005  7005 D BluetoothMapService: STATE_TURNING_OFF
08-26 17:37:40.713  6866  6866 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-26 17:37:40.713  7005  7005 V BtOppService: Receiver DISABLED_ACTION 
08-26 17:37:40.713  7005  7005 V BluetoothMapService: Handler(): got msg=4
08-26 17:37:40.713  7005  7005 D BluetoothMapService: MAP Service closeService in
08-26 17:37:40.713  7005  7005 D BluetoothMapMasInstance: MAP Service shutdown
08-26 17:37:40.713  7005  7005 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 17:37:40.713  7005  7005 V BluetoothMapService: MAP Service closeService out
08-26 17:37:40.713  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:40.714  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:40.714  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:40.714  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:40.714  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:40.714  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:40.714  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:40.714  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:40.714  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:40.714  7005  7005 I BtOppRfcommListener: stopping Accept Thread
08-26 17:37:40.714  7005  7005 V BtOppRfcommListener: close mBtServerSocket
08-26 17:37:40.714  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:40.714  7005  7005 V BtOppRfcommListener: waiting for thread to terminate
08-26 17:37:40.714  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:40.715  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:40.715  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: N,o relevant state changes
08-26 17:37:40.715  7005  7623 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 17:37:40.716  7005  7005 V BtOppRfcommListener: done waiting for thread to terminate
08-26 17:37:40.717  7005  7005 V BtOppService: onDestroy
08-26 17:37:40.718  6866  6866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 17:37:40.718  7005  7005 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 17:37:40.724  7005  7005 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 17:37:40.724  7005  7005 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:40.724  7005  7005 V BluetoothPbapReceiver: ***********state = 13
08-26 17:37:40.726  7005  7005 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 17:37:40.729  7005  7005 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:40.729  7005  7005 V BluetoothPbapService: state: 13
08-26 17:37:40.729  7005  7005 V BluetoothPbapService: Pbap Service closeService in
08-26 17:37:40.729  6866  6866 D DockEventReceiver: finishStartingService: stopping service
08-26 17:37:40.730  7005  7005 V BluetoothPbapService: successfully stopped pbap service
08-26 17:37:40.730  7005  7005 V BluetoothPbapService: Pbap Service closeService out
08-26 17:37:40.730  7005  7005 V BluetoothPbapService: Pbap Service onDestroy
08-26 17:37:40.730  7005  7005 V BluetoothPbapService: Pbap Service closeService in
08-26 17:37:40.730  7005  7005 V BluetoothPbapService: Pbap Service closeService out
08-26 17:37:40.730  7005  7005 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 17:37:40.730  6866  6866 D BluetoothPbap: Proxy object disconnected
08-26 17:37:40.730  6866  6866 D PbapServerProfile: Bluetooth service disconnected
08-26 17:37:40.732  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:40.740  6866  6866 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 17:37:40.745  6866  6866 D BluetoothPermissionRequest: onReceive
08-26 17:37:40.745  6866  6866 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 17:37:40.749  6866  6866 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 17:37:40.752  7005  7005 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 17:37:40.752  7005  7005 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-26 17:37:40.755  7005  7005 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 17:37:40.758  7005  7005 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:40.758  7005  7005 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 17:37:40.759  7005  7005 V BluetoothFtpService: Ftp Service onStartCommand
08-26 17:37:40.759  7005  7005 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:40.759  7005  7005 V BluetoothFtpService: Ftp Service closeService
08-26 17:37:40.759  7005  7005 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 17:37:40.764  7638  7638 I UEI.SmartControl: Supports setup maps: true
08-26 17:37:40.764  7005  7005 V BluetoothFtpService: successfully stopped ftp service
08-26 17:37:40.765  7005  7005 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 17:37:40.765  7005  7005 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 17:37:40.765  7005  7005 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 17:37:40.765  7005  7005 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:40.766  7005  7005 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 17:37:40.766  7005  7005 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 17:37:40.770  7638  7638 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 17:37:40.771  7638  7638 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 17:37:40.771  7005  7005 V BluetoothFtpService: Ftp Service onDestroy
08-26 17:37:40.771  7005  7005 V BluetoothFtpService: Ftp Service closeService
08-26 17:37:40.771  7638  7638 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 17:37:40.771  7638  7638 I UEI.SmartControl: ### init IR Blaster...
08-26 17:37:40.772  7005  7005 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:40.772  7005  7005 V BluetoothSapService: state: 13
08-26 17:37:40.772  7005  7005 V BluetoothSapService: Stopping SAP server process
08-26 17:37:40.775  7638  7638 D serial_port: Configuring serial port
08-26 17:37:40.777  7005  7005 V BluetoothSapService: Sap Service closeSapService in
08-26 17:37:40.777  7005  7005 V BluetoothSapService: Close listen Socket : 
08-26 17:37:40.778  7005  7005 V BluetoothSapService: Close rfcomm Socket : 
08-26 17:37:40.779  7005  7005 V BluetoothSapService: Close sapd  Socket : 
08-26 17:37:40.780  7638  7638 E UEI.SmartControl: UEIBLaster setting for 616
08-26 17:37:40.780  7638  7638 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 17:37:40.780  7005  7005 V BluetoothSapService: Sap Service closeSapService out
08-26 17:37:40.780  7638  7638 I UEI.SmartControl: configuring settings for MAXQ616
08-26 17:37:40.780  7638  7638 I UEI.SmartControl: Get version...
08-26 17:37:40.781  7005  7005 V BluetoothSapService: Sap Service onDestroy
08-26 17:37:40.781  7005  7005 V BluetoothSapService: Sap Service closeSapService in
08-26 17:37:40.781  7005  7005 V BluetoothSapService: Close listen Socket : 
08-26 17:37:40.781  7005  7005 V BluetoothSapService: Close rfcomm Socket : 
08-26 17:37:40.781  7005  7005 V BluetoothSapService: Close sapd  Socket : 
08-26 17:37:40.781  7005  7005 V BluetoothSapService: Sap Service closeSapService out
,08-26 17:37:40.797  7638  7673 D UEI.SmartControl: serial port data available: 21
,08-26 17:37:40.826  7638  7638 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 17:37:40.826  7638  7638 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 17:37:40.827  7638  7638 I UEI.SmartControl: QS saving settings...
,08-26 17:37:40.830  7638  7638 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 17:37:40.848  7638  7673 D UEI.SmartControl: serial port data available: 4
,08-26 17:37:40.890  7638  7679 I UEI.SmartControl: Device manager: loading config....
,08-26 17:37:40.891  7638  7679 D UEI.SmartControl: ----------- loading internal config...
,08-26 17:37:40.894  7638  7638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 17:37:40.900  7638  7638 E UEI.SmartControl: Services init done
08-26 17:37:40.900  7638  7638 D UEI.SmartControl: QS Service init finished
08-26 17:37:40.902  7638  7638 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 17:37:40.902  7638  7638 D UEI.SmartControl: QS Service version code: 201091
08-26 17:37:40.903  7638  7638 D UEI.SmartControl: Service requested: Control
08-26 17:37:40.905  7638  7679 E UEI.SmartControl: Loading SETTINGS...
,08-26 17:37:40.910  7638  7638 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 17:37:40.913  6935  6935 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 17:37:40.914  1035  1648 I ActivityManager: Killing 6935:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 17:37:40.916  7638  7653 I UEI.SmartControl: ------ IControl API: 11
08-26 17:37:40.918  7638  7653 I UEI.SmartControl: Registering callback...
08-26 17:37:40.923  7638  7679 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 17:37:40.946  7638  7678 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 17:37:40.946  7638  7678 D UEI.SmartControl: -----service ready thread exits
,08-26 17:37:40.958  1035  1785 W libprocessgroup: failed to open /acct/uid_10112/pid_6935/cgroup.procs: No such file or directory
,08-26 17:37:40.960  7638  7638 D UEI.SmartControl: Internal service binding...
,08-26 17:37:41.611  7005  7493 D bt_hci_bdroid: cleanup
,08-26 17:37:41.619  7005  7561 I bt_lpm  : LPM is already off!!!
08-26 17:37:41.619  7005  7588 I bt_userial_mct: exiting userial_read_thread
08-26 17:37:41.619  7005  7588 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 17:37:41.620  7005  7559 W bt-btif : ag scb idx 1 not allocated
08-26 17:37:41.620  7005  7559 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 17:37:41.620  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:41.620  7005  7559 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:41.620  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:41.620  7005  7559 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:41.620  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:41.620  7005  7559 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 17:37:41.621  7005  7559 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:41.621  7005  7559 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 17:37:41.624  7005  7493 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 17:37:41.624  7005  7561 I bt_vendor: hw_epilog_process
08-26 17:37:41.626  7005  7493 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 17:37:41.626  7005  7493 D bt_userial_mct: userial_close
08-26 17:37:41.626  7005  7493 E bt_userial_mct: pthread_join() FAILED result:3
08-26 17:37:41.626  7005  7493 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 17:37:41.638  7005  7493 D bt_hci_bdroid: set_power 0
,08-26 17:37:41.643  7005  7493 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 17:37:41.643  7005  7493 I bt_vendor: bluetooth satus is on
08-26 17:37:41.643  7005  7493 I bt_vendor: bt-vendor : resetting BT status
08-26 17:37:41.643  7005  7493 I bt_vendor: Starting hciattach daemon
08-26 17:37:41.643  7005  7493 I bt_vendor: try to set false
08-26 17:37:41.646  7005  7493 I bt_vendor: Starting hciattach daemon
08-26 17:37:41.646  7005  7493 I bt_vendor: try to set false
08-26 17:37:41.647  7005  7493 I bt_vendor: cleanup
08-26 17:37:41.648  7005  7559 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 17:37:41.648  7005  7493 I GKI_LINUX: GKI_exit_task 0 done
08-26 17:37:41.648  7005  7493 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 17:37:41.650  7005  7489 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 17:37:41.659  7005  7005 D HeadsetService: Received stop request...Stopping profile...
08-26 17:37:41.662  7005  7005 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 17:37:41.662  7005  7005 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 17:37:41.665  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:41.667  7005  7511 D HeadsetStateMachine: Exit Disconnected: -1
08-26 17:37:41.668  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:41.668  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 17:37:41.669  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:41.669  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:41.669  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:41.669  7005  7489 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 17:37:41.671  7005  7005 D A2dpService: Received stop request...Stopping profile...
08-26 17:37:41.673  7005  7544 D A2dpStateMachine: Exit Disconnected: -1
08-26 17:37:41.674  7005  7005 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-26 17:37:41.677  7005  7005 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 17:37:41.677  7005  7005 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 17:37:41.678  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:41.680  7005  7005 D HidService: Received stop request...Stopping profile...
08-26 17:37:41.680  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:41.681  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-26 17:37:41.681  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 17:37:41.682  7005  7005 D HealthService: Received stop request...Stopping profile...
08-26 17:37:41.683  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:41.685  7005  7005 D PanService: Received stop request...Stopping profile...
08-26 17:37:41.686  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
,08-26 17:37:41.689  7005  7005 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:41.690  7005  7005 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 17:37:41.690  7005  7005 D BtGatt.GattService: stop()
08-26 17:37:41.690  7005  7005 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 17:37:41.691  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:41.693  7005  7005 D BluetoothMapService: Received stop request...Stopping profile...
08-26 17:37:41.693  7005  7005 D BluetoothMapService: stop()
08-26 17:37:41.694  7005  7005 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 17:37:41.694  7005  7005 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 17:37:41.695  7005  7005 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38141822
08-26 17:37:41.696  7005  7005 D HeadsetStateMachine: Unbinding service...
08-26 17:37:41.697  7005  7005 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 17:37:41.697  7005  7005 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 17:37:41.697  7005  7005 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 17:37:41.697  7005  7005 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 17:37:41.698  7005  7005 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 17:37:41.698  7005  7005 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 17:37:41.698  7005  7005 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 17:37:41.698  7005  7005 I BluetoothA2dpServiceJni: cleanupNative
08-26 17:37:41.700  7005  7545 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 17:37:41.702  7005  7005 I GKI_LINUX: GKI_exit_task 2 done
08-26 17:37:41.702  7005  7005 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 17:37:41.704  7005  7005 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 17:37:41.704  7005  7005 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 17:37:41.704  7005  7005 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 17:37:41.704  7005  7005 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 17:37:41.704  7005  7005 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 17:37:41.704  7005  7005 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 17:37:41.705  7005  7005 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 17:37:41.707  7005  7005 V BluetoothMapService: Handler(): got msg=4
08-26 17:37:41.707  7005  7005 D BluetoothMapService: MAP Service closeService in
08-26 17:37:41.707  7005  7005 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 17:37:41.707  7005  7005 V BluetoothMapService: MAP Service closeService out
08-26 17:37:41.709  7005  7489 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 17:37:41.709  7005  7489 D BluetoothAdapterProperties: Setting state to 10
08-26 17:37:41.709  7005  7489 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 17:37:41.709  7005  7005 D BluetoothMapService: cleanup()
08-26 17:37:41.709  7005  7005 D BluetoothMapService: MAP Service closeService in
08-26 17:37:41.709  7005  7005 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 17:37:41.709  7005  7005 V BluetoothMapService: MAP Service closeService out
08-26 17:37:41.711  1035  1099 D BluetoothManagerService: Message: 60
08-26 17:37:41.712  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 17:37:41.712  1035  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-26 17:37:41.716  7005  7489 I BluetoothAdapterState: Entering OffState
08-26 17:37:41.716  1852  3982 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:41.717  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:41.718  6866  6885 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 17:37:41.719  6866  6885 D BluetoothMap: onBluetoothStateChange: up=false
08-26 17:37:41.719  1035  1099 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:41.719  6866  6885 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 17:37:41.720  6866  6885 D BluetoothPan: onBluetoothStateChange on: false
08-26 17:37:41.720  6866  6885 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:41.721  1035  1099 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 17:37:41.721  1852  2457 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:41.722  6866  6885 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 17:37:41.723  1035  1099 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 17:37:41.723  1035  1099 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 17:37:41.725  1035  1099 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 17:37:41.725  1035  1099 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 17:37:41.725  1035  1099 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3f59485e mBinding = false
,08-26 17:37:41.728  1035  1099 D BluetoothManagerService: Sending unbind request.
08-26 17:37:41.733  7005  7493 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 17:37:41.733  7005  7005 I GKI_LINUX: GKI_exit_task 1 done
08-26 17:37:41.734  7005  7005 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 17:37:41.734  7005  7005 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 17:37:41.734  7005  7005 I art     : --- WEIRD: removing null entry 248
08-26 17:37:41.734  7005  7005 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 17:37:41.734  7005  7005 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 17:37:41.735  7005  7005 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 17:37:41.736  1035  1099 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-26 17:37:41.741  7005  7005 I art     : System.exit called, status: 0
08-26 17:37:41.741  7005  7005 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 17:37:41.761   313  2164 V AudioFlinger: 7005 died, releasing its sessions
08-26 17:37:41.761   313  2164 V AudioFlinger:  pid 1852 @ 0
08-26 17:37:41.761   313  2164 V AudioFlinger:  pid 3480 @ 1
08-26 17:37:41.761   313  2164 V AudioFlinger:  pid 3480 @ 2
,08-26 17:37:41.764  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-26 17:37:41.764  1941  2103 D LGBluetoothAPIService: Message: 101
08-26 17:37:41.765  1941  2103 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-26 17:37:41.765  1941  2103 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-26 17:37:41.765  1941  2103 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-26 17:37:41.766  6866  6866 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 17:37:41.817  1035  1990 I ActivityManager: Process com.android.bluetooth (pid 7005) has died
08-26 17:37:41.818  1035  1990 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-26 17:37:41.818  1035  1990 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-26 17:37:41.824  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 17:37:41.825  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:41.825  1941  2103 D LGBluetoothAPIService: Message: 2
08-26 17:37:41.825  1941  2103 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-26 17:37:41.827  6866  6866 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 17:37:41.827  6866  6866 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 17:37:41.830  1604  1604 D BluetoothAdapter: 86988828: getState() :  mService = null. Returning STATE_OFF
,08-26 17:37:41.830  1604  1604 D BluetoothAdapter: 86988828: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:41.833  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:41.838  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:41.949  1035  2032 I art     : Explicit concurrent mark sweep GC freed 92982(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.977ms total 120.741ms
,08-26 17:37:41.952  6866  6866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 17:37:41.986  1035  1956 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7710 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 17:37:41.988  6866  6866 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:42.075  7710  7710 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 17:37:42.076  7710  7710 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 17:37:42.076  7710  7710 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-26 17:37:42.077  7710  7710 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 17:37:42.099  7710  7710 D BluetoothAdapterApp: Loading JNI Library
,08-26 17:37:42.138  7710  7710 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@19da19ca Instance Count = 1
,08-26 17:37:42.145  7710  7710 D BluetoothAdapterApp: onCreate
08-26 17:37:42.170  7710  7710 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-26 17:37:42.171  7710  7710 D ProfileConfigQcom: Adding HeadsetService
,08-26 17:37:42.171  7710  7710 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 17:37:42.171  7710  7710 D ProfileConfigQcom: Adding A2dpService
08-26 17:37:42.171  7710  7710 D ProfileConfigQcom: [BTUI] HidService is supported
,08-26 17:37:42.171  7710  7710 D ProfileConfigQcom: Adding HidService
08-26 17:37:42.172  7710  7710 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-26 17:37:42.172  7710  7710 D ProfileConfigQcom: Adding HealthService
08-26 17:37:42.172  7710  7710 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 17:37:42.173  7710  7710 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 17:37:42.173  7710  7710 D ProfileConfigQcom: Adding PanService
08-26 17:37:42.174  7710  7710 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 17:37:42.174  7710  7710 D ProfileConfigQcom: Adding GattService
08-26 17:37:42.174  7710  7710 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 17:37:42.174  7710  7710 D ProfileConfigQcom: Adding BluetoothMapService
08-26 17:37:42.175  7710  7710 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 17:37:42.175  7710  7710 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 17:37:42.177  7710  7710 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:42.177  7710  7710 V BluetoothPbapReceiver: ***********state = 10
08-26 17:37:42.179  7710  7710 V LGMDMManagerInternal: Create singleton instance
,08-26 17:37:42.265  7710  7710 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-26 17:37:42.265  7710  7710 D LGBluetoothAPIServer: [BTUI] onBind()
,08-26 17:37:42.268  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:42.272  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 17:37:42.273  1941  2103 D LGBluetoothAPIService: Message: 100
,08-26 17:37:42.273  1941  2103 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 17:37:42.276  6866  6866 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 17:37:42.304  6866  6866 D BluetoothPermissionRequest: onReceive
,08-26 17:37:42.307  6866  6866 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 17:37:42.307  6866  6866 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 17:37:42.310  6866  6866 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 17:37:42.317  7710  7710 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 17:37:42.324  7710  7710 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:42.330  7710  7710 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 17:37:42.330  7710  7710 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 17:37:42.330  7710  7710 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 17:37:42.332  7710  7710 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:42.332  7710  7710 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 17:37:42.336  6952  6952 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 17:37:43.680  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:43.680  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:43.758  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 17:37:43.777  1035  1456 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 17:37:43.860  1035  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7738 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 17:37:43.873  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 17:37:43.873  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-26 17:37:43.875  1035  1035 D administrator: Handling package changes for user 0
08-26 17:37:43.921  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 17:37:43.944  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 17:37:43.959  7738  7738 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 17:37:43.999  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-26 17:37:43.999  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 17:37:44.036  7738  7738 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:44.036  7738  7738 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 17:37:44.048  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 17:37:44.052  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 17:37:44.059  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 17:37:44.060  2479  2479 V GmsNetworkLocationProvi: DISABLE
08-26 17:37:44.094  1035  1091 D LocationProviderProxy: applying state to connected service
,08-26 17:37:44.097  2479  2479 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-26 17:37:44.153  7738  7783 I Babel   : MmsConfig: mnc/mcc: 0/0
08-26 17:37:44.153  7738  7783 I Babel   : MmsConfig.loadMmsSettings
08-26 17:37:44.159  7738  7783 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 17:37:44.159  7738  7783 I Babel   : MmsConfig.loadFromDatabase
,08-26 17:37:44.179  7738  7783 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 17:37:44.179  7738  7783 I Babel   : MmsConfig.loadFromResources
08-26 17:37:44.181  7738  7783 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 17:37:44.182  7738  7783 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 17:37:44.183  7738  7738 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:44.183  7738  7781 W AudioCapabilities: Unsupported mime audio/evrc
08-26 17:37:44.184  7738  7781 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 17:37:44.185  7738  7781 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 17:37:44.191  7738  7781 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-26 17:37:44.192  7738  7781 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 17:37:44.193  7738  7781 W AudioCapabilities: Unsupported mime audio/evrc
08-26 17:37:44.200  7738  7781 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 17:37:44.204  7738  7781 W VideoCapabilities: Unsupported mime video/divx
08-26 17:37:44.210  1817  7785 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 17:37:44.210  1817  7785 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-26 17:37:44.214  7738  7781 W VideoCapabilities: Unsupported mime video/divx311
08-26 17:37:44.214  7073  7073 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 17:37:44.217  7073  7073 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d9dd804
08-26 17:37:44.217  7073  7073 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 17:37:44.217  7073  7073 D AppUp4:CustFacade: isPhone : true
08-26 17:37:44.218  7073  7073 D AppUp4:CustModeStarterReceiver: begin check event
08-26 17:37:44.218  7073  7073 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 17:37:44.221  7738  7781 W VideoCapabilities: Unsupported mime video/divx4
08-26 17:37:44.223  1817  4749 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-26 17:37:44.234  7738  7781 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 17:37:44.246  7738  7781 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 17:37:44.250  7738  7781 W AudioCapabilities: Unsupported mime audio/eac3
08-26 17:37:44.251  7738  7781 W AudioCapabilities: Unsupported mime audio/ac3
08-26 17:37:44.258  7738  7781 W AudioCapabilities: Unsupported mime audio/g726
,08-26 17:37:44.259  1035  1787 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7788 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-26 17:37:44.264  1035  1648 I ActivityManager: Killing 6906:com.lge.sync/1000 (adj 15): empty #17
08-26 17:37:44.265  7738  7781 W AudioCapabilities: Unsupported mime audio/wma-voice
08-26 17:37:44.266  7738  7781 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 17:37:44.266  7738  7781 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 17:37:44.268  7738  7781 W VideoCapabilities: Unsupported mime video/theora
08-26 17:37:44.269  7738  7781 W VideoCapabilities: Unsupported mime video/mjpg
08-26 17:37:44.280  1035  1545 D WifiService: Client connection lost with reason: 4
,08-26 17:37:44.340  1035  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6906/cgroup.procs: No such file or directory
,08-26 17:37:44.379  7788  7788 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 17:37:44.379  7788  7788 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 17:37:44.379  7788  7788 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 17:37:44.381  7788  7788 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 17:37:44.381  7788  7788 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-26 17:37:44.456  7788  7788 I SystemConfig: BUILD Country: EU
08-26 17:37:44.456  7788  7788 I SystemConfig: BUILD Operator: OPEN
,08-26 17:37:44.503  1035  1990 I ActivityManager: Killing 7102:com.lge.email/u0a23 (adj 15): empty #17
,08-26 17:37:44.651  1035  2016 W libprocessgroup: failed to open /acct/uid_10023/pid_7102/cgroup.procs: No such file or directory
,08-26 17:37:44.714  1035  1990 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7815 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 17:37:44.721  7788  7807 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 17:37:44.721  7788  7807 I SystemConfig: existFile = false
08-26 17:37:44.722  7788  7807 I SystemConfig: canReadFile = false
08-26 17:37:44.722  7788  7807 I SystemConfig: systemFeature RCS result false
08-26 17:37:44.722  7788  7807 D SystemConfig: refreshRcsSupport() :false
08-26 17:37:44.728  1035  1546 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-26 17:37:44.795  7815  7815 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 17:37:44.795  7815  7815 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 17:37:44.796  7815  7815 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 17:37:44.796  7815  7815 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 17:37:44.914  7815  7815 I AppConfig: Total System Memory = 2995761152
,08-26 17:37:44.925  7815  7815 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-26 17:37:45.036  1035  1785 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7835 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 17:37:45.037  1035  1785 I ActivityManager: Killing 6976:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-26 17:37:45.118  1035  2032 W libprocessgroup: failed to open /acct/uid_10026/pid_6976/cgroup.procs: No such file or directory
,08-26 17:37:45.279  7835  7835 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 17:37:45.336  7835  7835 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:45.336  7835  7835 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 17:37:45.386  7835  7835 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 17:37:45.405  7835  7835 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 17:37:45.407  7835  7835 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 17:37:45.423  7835  7835 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 17:37:45.423  7835  7835 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 17:37:45.443  1035  2032 I ActivityManager: Killing 6502:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-26 17:37:45.552  1035  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_6502/cgroup.procs: No such file or directory
,08-26 17:37:45.579  4560  7871 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-26 17:37:45.605  1035  1932 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7873 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 17:37:45.614  2841  7259 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-26 17:37:45.615  2841  7259 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@608bfe8 on behalf of 7835
08-26 17:37:45.633  7835  7835 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 17:37:45.646  7835  7835 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 17:37:45.683  7873  7873 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 17:37:45.708  7873  7873 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-26 17:37:45.708  7873  7873 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-26 17:37:45.708  7873  7873 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 17:37:45.708  7873  7873 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,08-26 17:37:45.708  7873  7873 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-26 17:37:45.708  7873  7873 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-26 17:37:45.727  1035  1995 I ActivityManager: Killing 7144:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-26 17:37:45.810  1035  2016 W libprocessgroup: failed to open /acct/uid_10046/pid_7144/cgroup.procs: No such file or directory
,08-26 17:37:45.892  7638  7680 D UEI.SmartControl: Internal timer expired: 1
,08-26 17:37:45.893  7638  7680 D UEI.SmartControl: unbind internal service
,08-26 17:37:45.903  7638  7638 D UEI.SmartControl: Service.onUnbind: IControl
08-26 17:37:45.904  7638  7638 D UEI.SmartControl: Service.onDestroy
08-26 17:37:45.904  7638  7638 D UEI.SmartControl: Lock is in USE false
08-26 17:37:45.905  7638  7638 D UEI.SmartControl: unbind internal service
08-26 17:37:45.906  7638  7638 D serial_port: close(fd = 25)
08-26 17:37:45.911  7638  7638 I UEI.SmartControl: Serial port is closed.
08-26 17:37:45.911  7638  7638 I UEI.SmartControl: Serial port is closed.
,08-26 17:37:45.914  7638  7638 D UEI.SmartControl: Blaster closed
,08-26 17:37:45.915  7638  7638 D UEI.SmartControl: Shut down QS...
08-26 17:37:45.915  7638  7638 D UEI.SmartControl: Stopping QS lib
08-26 17:37:45.916  7638  7638 D UEI.SmartControl: QS lib stop result = true
08-26 17:37:45.916  7638  7638 D UEI.SmartControl: Stopped QS lib
08-26 17:37:45.919  7638  7638 D UEI.SmartControl: Stopped file observer...
08-26 17:37:45.919  7638  7638 D UEI.SmartControl: QS shutdown complete
08-26 17:37:46.070  1035  1956 V SIM_STK : Menu title from STK is T-Mobile
,08-26 17:37:46.093  4560  7871 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 515 ms] updated apps [took 514 ms] 
,08-26 17:37:46.695  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:46.696  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29fdbdf6 added. We now have 6 listener(s)
,08-26 17:37:46.696  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:46.709  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:46.710  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@132f05f7 added. We now have 7 listener(s)
08-26 17:37:46.710  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:46.711  6695  6799 I System.out: IsBluetoothEnabled
08-26 17:37:46.712  1035  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:46.712  1035  1995 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-26 17:37:46.713  1035  1099 D BluetoothManagerService: Message: 2
08-26 17:37:46.716  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:46.717  1035  1648 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:46.717  1035  1648 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 17:37:46.737  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-26 17:37:46.740  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 17:37:46.740  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-26 17:37:46.741  1035  1099 D BluetoothManagerService: Message: 1
08-26 17:37:46.741  1035  1099 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 17:37:46.766  1035  1099 D BluetoothManagerService: Message: 20
08-26 17:37:46.766  1035  1099 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@290d428c:true
,08-26 17:37:46.770  7710  7710 D BluetoothAdapterState: make
08-26 17:37:46.774  7710  7710 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 17:37:46.775  7710  7710 I bluedroid-qcom: init
08-26 17:37:46.776  7710  7917 I BluetoothAdapterState: Entering OffState
08-26 17:37:46.776  7710  7710 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 17:37:46.776  7710  7710 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 17:37:46.776  7710  7710 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 17:37:46.777  7710  7710 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 17:37:46.777  7710  7710 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 17:37:46.778  7710  7710 I bluedroid-qcom: get_profile_interface socket
08-26 17:37:46.778  7710  7710 I bluedroid-qcom: get_profile_interface map_client
,08-26 17:37:46.782  7710  7921 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 17:37:46.776  7920  7920 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:46.776  7920  7920 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:46.796  7920  7920 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 17:37:46.796  7920  7920 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 17:37:46.796  7920  7920 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 17:37:46.807  7920  7920 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 17:37:46.816  7920  7920 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 17:37:46.816  7920  7920 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-26 17:37:46.822  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 17:37:46.822  1035  1099 D BluetoothManagerService: Message: 40
08-26 17:37:46.822  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 17:37:46.823  7710  7727 I bluedroid-qcom: config_hci_snoop_log
08-26 17:37:46.824  1035  1099 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 17:37:46.824  1035  1099 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 17:37:46.825  7710  7921 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 17:37:46.827  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 17:37:46.827  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 17:37:46.827  7710  7921 D BluetoothAdapterProperties: Name is: G3
08-26 17:37:46.832  7710  7917 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 17:37:46.833  7710  7917 D BluetoothAdapterProperties: Setting state to 11
08-26 17:37:46.833  7710  7917 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-26 17:37:46.836  1035  1099 D BluetoothManagerService: Message: 60
08-26 17:37:46.836  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 17:37:46.837  1035  1099 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 17:37:46.840  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:46.841  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 17:37:46.844  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:46.846  6866  6866 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-26 17:37:46.861  7710  7917 I LGBluetoothServiceJni: classInitNative: succeeds
,08-26 17:37:46.870  7710  7710 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 17:37:46.870  7710  7710 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:46.871  7710  7710 V BluetoothPbapReceiver: ***********state = 11
08-26 17:37:46.873  7710  7917 D BluetoothBondStateMachine: make
,08-26 17:37:46.875  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:46.879  7710  7936 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 17:37:46.879  7710  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:46.879  7710  7917 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 17:37:46.879  7710  7917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:46.879  7710  7917 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 17:37:46.880  7710  7917 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 17:37:46.890  6866  6866 D BluetoothPermissionRequest: onReceive
08-26 17:37:46.890  7710  7917 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 17:37:46.897  6866  6866 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 17:37:46.902  7710  7710 D HeadsetService: Received start request. Starting profile...
08-26 17:37:46.902  7710  7710 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 17:37:46.903  7710  7710 D LGBluetoothHfpAdapter: Version 1.6
08-26 17:37:46.906  7710  7710 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 17:37:46.907  7710  7710 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 17:37:46.908  7710  7710 D HeadsetStateMachine: make
08-26 17:37:46.909  7710  7917 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:46.920  7710  7917 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 17:37:46.925  7710  7917 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:46.929  7710  7917 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:46.933  7710  7917 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 17:37:46.936  7710  7710 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:46.936  7710  7710 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 17:37:46.937  7710  7917 E BluetoothAdapterService: File transfer profiles supported!!
08-26 17:37:46.941  7710  7710 D HeadsetStateMachine: max_hf_connections = 1
08-26 17:37:46.941  7710  7710 I bluedroid-qcom: get_profile_interface handsfree
08-26 17:37:46.944  7710  7710 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 17:37:46.944   313  1382 V AudioPolicyService: registerClient() client 0xb1025e00, uid 1002
08-26 17:37:46.944   313  2165 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 17:37:46.945   313  2165 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 17:37:46.945   313  2165 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 17:37:46.945  7710  7710 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 17:37:46.945   313  2164 V AudioFlinger: registerClient() client 0xb14330a0, pid 7710
08-26 17:37:46.945   313  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:46.945   313  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-26 17:37:46.946  1035  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-26 17:37:46.946  1035  1051 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 17:37:46.946  1604  2105 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:46.946  1604  2105 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 17:37:46.946  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:46.946  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 17:37:46.946  3480  3497 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:46.946  3480  3497 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 17:37:46.946   313  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:46.946  7710  7726 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 17:37:46.946   313  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 17:37:46.946  7710  7726 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 17:37:46.947  1035  1787 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:46.947  1035  1787 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 17:37:46.947  7710  7727 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:46.947  7710  7727 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 17:37:46.947  7710  7710 V ToneGenerator: Create Track: 0xb4928a80
08-26 17:37:46.947  7710  7710 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 17:37:46.947  7710  7710 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 17:37:46.947   313  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 17:37:46.947  3480  3496 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:46.947   313  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 17:37:46.947   313  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 17:37:46.947  3480  3496 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 17:37:46.947   313  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 17:37:46.947  1852  3982 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:46.947  1852  3982 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 17:37:46.947  1604  1627 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 17:37:46.947  1604  1627 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 17:37:46.947   313  1382 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 17:37:46.948   313  2165 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 17:37:46.948   313  2165 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 17:37:46.948   313  2165 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 17:37:46.948   313  2165 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 17:37:46.948  7710  7710 V AudioSystem: getLatency() output 2, latency 50
08-26 17:37:46.948  7710  7710 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 17:37:46.948  7710  7710 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 17:37:46.948   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 17:37:46.948   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 17:37:46.948   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 17:37:46.949   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 17:37:46.949   313   3,13 V AudioFlinger: createTrack() lSessionId: 23
08-26 17:37:46.952  7710  7710 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 17:37:46.952   313   313 V AudioFlinger: acquiring 23 from 7710, for 7710
08-26 17:37:46.952   313   313 V AudioFlinger:  added new entry for 23
08-26 17:37:46.952  7710  7710 V ToneGenerator: ToneGenerator INIT OK, time: 134995
08-26 17:37:46.952  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:46.953  7710  7939 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 17:37:46.953  7710  7939 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 17:37:46.953  7710  7939 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 17:37:46.953  7710  7939 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 17:37:46.953   313  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7710
08-26 17:37:46.954   313  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 17:37:46.954   313  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 17:37:46.954   313  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 17:37:46.954   313  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 17:37:46.954   313  1383 V voice   : voice_set_parameters: exit with code(0)
08-26 17:37:46.954   313  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 17:37:46.954   313  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 17:37:46.954   313  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 17:37:46.954   313  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 17:37:46.954   313  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 17:37:46.954   313  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 17:37:46.954  7710  7939 V ToneGenerator: ToneGenerator destructor
08-26 17:37:46.954  7710  7939 V ToneGenerator: stopTone
08-26 17:37:46.954  7710  7939 V ToneGenerator: Delete Track: 0xb4928a80
08-26 17:37:46.954  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:46.954  7710  7917 V LGMDMManager: Create singleton instance
08-26 17:37:46.957  7710  7939 V AudioTrack: ~AudioTrack, releasing session id from 7710 on behalf of 7710
08-26 17:37:46.957   313  2164 V AudioFlinger: releasing 23 from 7710 for 7710
08-26 17:37:46.957   313  2164 V AudioFlinger:  decremented refcount to 0
08-26 17:37:46.957   313  2164 V AudioFlinger: purging stale effects
08-26 17:37:46.957  1035  1995 W Process : Unable to open /proc/7943/status
08-26 17:37:46.957   313  2164 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 17:37:46.957   313  2164 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 17:37:46.957   313  2164 V AudioFlinger: PlaybackThread::Track destructor
08-26 17:37:46.957   313  2164 V AudioFlinger: removeClient_l() pid 7710, calling pid 313
08-26 17:37:46.957   313  1119 V AudioPolicyService: AudioCommandThread() waking up
08-26 17:37:46.957   313  1119 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 17:37:46.957   313  1119 V AudioPolicyManager: releaseOutput() 2
08-26 17:37:46.957   313  1119 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 17:37:46.958  7710  7710 D A2dpService: Received start request. Starting profile...
08-26 17:37:46.958  7710  7917 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 17:37:46.959  7710  7710 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 17:37:46.959  7710  7710 V Avrcp   : make
08-26 17:37:46.960  7710  7710 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 17:37:46.960  7710  7710 I bluedroid-qcom: get_profile_interface avrcp
08-26 17:37:46.968  7710  7710 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 17:37:46.969  7710  7710 E AudioManager: No RCC entry present to update
08-26 17:37:46.969  7710  7710 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 17:37:46.972  7710  7710 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 17:37:46.974  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 17:37:46.974  7710  7710 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 17:37:46.977  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 17:37:47.114  1035  1932 V SIM_STK : Menu title from STK is T-Mobile
08-26 17:37:47.114  1035  1932 V SIM_STK : Menu title from STK is T-Mobile
,08-26 17:37:47.233  1035  1896 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 17:37:47.244  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 17:37:47.249  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 17:37:47.250  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 17:37:47.250  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 17:37:47.250  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 17:37:47.250  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 17:37:47.250  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 17:37:47.250  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 17:37:47.250  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 17:37:47.250  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 17:37:47.250  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 17:37:47.251  7710  7710 I BluetoothA2dpServiceJni: classInitNative
08-26 17:37:47.251  7710  7710 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 17:37:47.251  7710  7710 D A2dpStateMachine: make
,08-26 17:37:47.256  7710  7710 I bluedroid-qcom: get_profile_interface a2dp
08-26 17:37:47.256  7710  7950 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 17:37:47.261  7710  7710 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 17:37:47.261  7710  7710 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 17:37:47.264  7710  7949 D A2dpStateMachine: Enter Disconnected: -2
08-26 17:37:47.264  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:47.267  7710  7710 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 17:37:47.269  7710  7710 D HidService: Received start request. Starting profile...
08-26 17:37:47.269  7710  7710 I bluedroid-qcom: get_profile_interface hidhost
08-26 17:37:47.270  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:47.270  7710  7710 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 17:37:47.272  7710  7710 D HealthService: Received start request. Starting profile...
08-26 17:37:47.273  7710  7710 I bluedroid-qcom: get_profile_interface health
08-26 17:37:47.273  7710  7710 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 17:37:47.273  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:47.274  7710  7710 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 17:37:47.276  7710  7710 D PanService: Received start request. Starting profile...
08-26 17:37:47.276  7710  7710 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 17:37:47.276  7710  7710 I bluedroid-qcom: get_profile_interface pan
08-26 17:37:47.282  7710  7710 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 17:37:47.282  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
,08-26 17:37:47.283  7710  7710 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-26 17:37:47.289  7710  7710 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:47.290  7710  7710 D BtGatt.GattService: Received start request. Starting profile...
08-26 17:37:47.290  7710  7710 D BtGatt.GattService: start()
08-26 17:37:47.290  7710  7710 I bluedroid-qcom: get_profile_interface gatt
08-26 17:37:47.290  7710  7710 D BtGatt.AdvertiseManager: advertise manager created
08-26 17:37:47.295  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
,08-26 17:37:47.297  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:47.297  7710  7710 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 17:37:47.298  7710  7710 V BluetoothMapService: BluetoothMapBinder()
08-26 17:37:47.299  7710  7710 D BluetoothMapService: Received start request. Starting profile...
08-26 17:37:47.299  7710  7710 D BluetoothMapService: start()
08-26 17:37:47.303  7710  7710 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 17:37:47.303  7710  7710 D BluetoothMapEmailAppObserver: createReceiver()
08-26 17:37:47.304  7710  7710 D BluetoothMapEmailAppObserver: initObservers()
08-26 17:37:47.304  7710  7710 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 17:37:47.314  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:47.314  7710  7710 D HeadsetStateMachine: Proxy object connected
08-26 17:37:47.315  7710  7710 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 17:37:47.315  7710  7710 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-26 17:37:47.321  7710  7710 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 17:37:47.321  7710  7939 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 17:37:47.323  7710  7939 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 17:37:47.323  7710  7939 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 17:37:47.323  7710  7710 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:47.330  7710  7710 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 17:37:47.335  7710  7710 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 17:37:47.339  7710  7710 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 17:37:47.339  7710  7710 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 17:37:47.343  7710  7710 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 17:37:47.347  7710  7710 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 17:37:47.348  7710  7710 V BluetoothMapService: Handler(): got msg=1
08-26 17:37:47.349  7710  7710 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 17:37:47.349  7710  7710 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 17:37:47.349  7710  7710 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 17:37:47.349  7710  7710 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:47.349  7710  7917 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 17:37:47.349  7710  7710 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 17:37:47.349  7710  7917 I bluedroid-qcom: enable
08-26 17:37:47.350  7710  7957 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 17:37:47.350  7710  7957 I bt-btu  : btu_task pending for preload complete event
08-26 17:37:47.350  7710  7917 I bt_hci_bdroid: init
08-26 17:37:47.353  7710  7917 I bt_vendor: bt-vendor : init
08-26 17:37:47.354  7710  7917 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 17:37:47.354  7710  7917 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 17:37:47.354  7710  7917 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 17:37:47.354  7710  7917 D bt_userial_mct: userial_init
08-26 17:37:47.355  7710  7917 D bt_hci_bdroid: set_power 1
08-26 17:37:47.355  7710  7917 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 17:37:47.355  7710  7917 I bt_vendor: Starting hciattach daemon
08-26 17:37:47.355  7710  7917 I bt_vendor: try to set true
08-26 17:37:47.356  7960  7960 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:47.356  7960  7960 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 17:37:47.408  7961  7961 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 17:37:47.515  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{bad43a2 type 2 when 135541 com.google.android.gms} when 135541
,08-26 17:37:47.527   309  7969 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 17:37:47.528  1035  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 17:37:47.537  7967  7967 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-26 17:37:47.551  7970  7970 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 17:37:47.588  7973  7973 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 17:37:47.591  1035  1956 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7972 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-26 17:37:47.610  7982  7982 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 17:37:47.622  7994  7994 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-26 17:37:47.625   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 479us total 35.943ms
,08-26 17:37:47.637  7996  7996 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 17:37:47.648   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 461us total 21.976ms
08-26 17:37:47.659  7999  7999 I libmdmdetect: ESOC framework not supported
08-26 17:37:47.660  7999  7999 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 17:37:47.663  7972  7972 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 17:37:47.670   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 713us total 20.622ms
,08-26 17:37:47.670  7999  7999 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 17:37:47.670  7999  7999 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 17:37:47.670  7999  7999 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 17:37:47.670  7999  7999 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 17:37:47.670  7999  7999 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 17:37:47.670  7999  7999 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 17:37:47.670  7999  7999 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 17:37:47.687  7972  7972 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 17:37:47.705  7999  8001 E QC-QMI  : qmi_client [7999] 15: failed to locate client data
,08-26 17:37:47.707   453   453 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-26 17:37:47.707   453   453 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-26 17:37:47.718  7972  7972 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 17:37:47.719  7972  7972 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 17:37:47.719  7972  7972 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 17:37:47.720  7972  7972 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 17:37:47.720  7972  7972 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-26 17:37:47.722  7972  7972 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-26 17:37:47.727  7972  7972 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-26 17:37:47.733  7972  7972 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-26 17:37:47.734  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8158
08-26 17:37:47.736  7972  7972 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 17:37:47.738  7972  7972 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 17:37:47.739  7972  7972 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-26 17:37:47.740  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-26 17:37:47.740  7972  7972 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 17:37:47.754  8003  8003 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 17:37:47.771  7972  7972 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 17:37:47.772  7972  7972 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 17:37:47.778  7972  7972 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 17:37:47.780  7972  7972 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 17:37:47.780  7972  7972 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 17:37:47.780  7972  7972 V SoundPool: doLoad: loading sample sampleID=1
08-26 17:37:47.780  7972  8007 V SoundPool: Start decode
08-26 17:37:47.780  7972  8007 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 17:37:47.781   313  2164 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 17:37:47.781   313  2164 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 17:37:47.781   313  2164 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 17:37:47.781   313  2164 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 17:37:47.781   313  2164 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 17:37:47.781   313  2164 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 17:37:47.781   313  2164 V MediaPlayerService: player type = 3
08-26 17:37:47.781   313  2164 V AwesomePlayer: AwesomePlayer create()
08-26 17:37:47.781  8004  8004 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-26 17:37:47.781   313  2164 V AwesomePlayer: reset_l() 
08-26 17:37:47.781   313  2164 V AwesomePlayer: cancelPlayerEvents
08-26 17:37:47.781   313  2164 V AwesomePlayer: setAudioSink() 
08-26 17:37:47.781   313  2164 V AwesomePlayer: reset_l() 
08-26 17:37:47.782   313  2164 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-26 17:37:47.782   313  2164 V AudioCache: ignored
08-26 17:37:47.782   313  2164 V AwesomePlayer: cancelPlayerEvents
,08-26 17:37:47.782   313  2164 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 17:37:47.782   313  2164 V AwesomePlayer: setDataSource_l dataSource
08-26 17:37:47.782   313  2164 V LGParserOSAL: SniffLGParser start
08-26 17:37:47.782   313  2164 V LGParserOSAL: MainType:5, SubType=0
08-26 17:37:47.782   313  2164 V LGParserOSAL: #### check Mime : application/ogg
08-26 17:37:47.782   313  2164 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 17:37:47.782   313  2164 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 17:37:47.785  7972  7972 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 17:37:47.791  7638  7638 D UEI.SmartControl: QS Service created
08-26 17:37:47.793  7972  7972 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 17:37:47.796  7972  7972 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-26 17:37:47.798  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 17:37:47.808  7638  7638 I UEI.SmartControl: Service initServices...
08-26 17:37:47.808  7638  7638 D UEI.SmartControl: QS start get config
,08-26 17:37:47.812  7710  7917 I bt_vendor: bluetooth satus is on
08-26 17:37:47.812  7710  7917 D bt_hci_bdroid: preload
08-26 17:37:47.812  7710  7959 D bt_userial_mct: userial_open(port:0)
08-26 17:37:47.812  7710  7959 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 17:37:47.815  7710  7959 I bt_vendor: Done intiailizing UART
08-26 17:37:47.816  7710  7959 I bt_vendor: Done intiailizing UART
08-26 17:37:47.816  7710  7959 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 17:37:47.816  7710  7959 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 17:37:47.816  7710  7957 I bt-btu  : btu_task received preload complete event
08-26 17:37:47.816  7710  7957 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 17:37:47.816  7710  7957 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 17:37:47.817  7972  7972 V LGMDMManager: Create singleton instance
08-26 17:37:47.818  7710  7957 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 17:37:47.819  7710  8009 D bt_userial_mct: Entering userial_read_thread()
,08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 17:37:47.820  7710  7957 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 17:37:47.825   313  2164 V LGParserOSAL: supported mime: application/ogg
08-26 17:37:47.825   313  2164 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 17:37:47.825   313  2164 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 17:37:47.825   313  2164 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 17:37:47.825   313  2164 V AwesomePlayer: AudioTrack Setting
08-26 17:37:47.825   313  2164 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 17:37:47.825   313  2164 V AwesomePlayer: setAudioSource() 
08-26 17:37:47.825   313  2164 V MediaPlayerService: prepare
08-26 17:37:47.825   313  2164 V AwesomePlayer: prepareAsync_l() 
08-26 17:37:47.825   313  2164 V MediaPlayerService: wait for prepare
08-26 17:37:47.826   313  8010 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 17:37:47.826   313  8010 V AwesomePlayer: initAudioDecoder() 
08-26 17:37:47.826   313  8010 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 17:37:47.826   313  8010 V AudioSystem: isOffloadSupported()
08-26 17:37:47.826   313  8010 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 17:37:47.826   313  8010 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 17:37:47.826   313  8010 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 17:37:47.826   313  8010 V AwesomePlayer: getUseOffload() = 0 
,08-26 17:37:47.826   313  8010 V OMXCodec: OMXCodec::Create
08-26 17:37:47.826   313  8010 V OMXCodec: findMatchingCodecs()
08-26 17:37:47.826   313  8010 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 17:37:47.826   313  8010 V OMXCodec: matchingCodecs.size()=1
08-26 17:37:47.826   313  8010 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 17:37:47.827   313  8010 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 17:37:47.827   313  8010 V LGCodecAdapter: LG Codec Adapter start
08-26 17:37:47.827   313  8010 V OMXCodec: OMXCodec Createtor
08-26 17:37:47.827   313  8010 V OMXCodec: setComponentRole
08-26 17:37:47.827   313  8010 V OMXCodec: configureCodec protected=0
08-26 17:37:47.827   313  8010 V LGCodecAdapter: called getLGCodecSpecificData
08-26 17:37:47.827   313  8010 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 17:37:47.827   313  8010 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 17:37:47.827   313  8010 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 17:37:47.827   313  8010 V LGCodecOSAL: Not support LGCodec
08-26 17:37:47.827   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 17:37:47.827   313  8010 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 17:37:47.827   313  8010 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 17:37:47.827   313  8010 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 17:37:47.827   313  8010 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 17:37:47.827   313  8010 V AudioSystem: isOffloadSupported()
08-26 17:37:47.828   313  8010 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 17:37:47.828   313  8010 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 17:37:47.828   313  8010 V OMXCodec: init()
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 17:37:47.828   313  8010 V OMXCodec: allocateBuffers
08-26 17:37:47.828   313  8010 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-26 17:37:47.828   313  8010 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-26 17:37:47.828   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd060 on output port
08-26 17:37:47.829   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd150 on output port
08-26 17:37:47.829   313  8010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd1f0 on output port
08-26 17:37:47.829   313  8010 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 17:37:47.829   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 17:37:47.829   313  8012 V OMXCodec: [OMX.google.vorbis.d,ecoder] Now Idle.
08-26 17:37:47.829   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 17:37:47.829   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 17:37:47.829   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 17:37:47.829   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 17:37:47.837   313  8010 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 17:37:47.837   313  8010 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 17:37:47.837   313  8010 V AudioCache: notify(0xb5474940, 5, 0, 0)
08-26 17:37:47.837   313  8010 V AudioCache: ignored
08-26 17:37:47.837   313  8010 V AudioCache: notify(0xb5474940, 1, 0, 0)
08-26 17:37:47.837   313  8010 V AudioCache: prepared
08-26 17:37:47.837   313  2164 V AudioCache: wait - success
08-26 17:37:47.837   313  2164 V MediaPlayerService: start
08-26 17:37:47.837   313  2164 V AwesomePlayer: play_l() 
08-26 17:37:47.837   313  2164 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 17:37:47.837   313  2164 V AwesomePlayer: createAudioPlayer_l
08-26 17:37:47.838   313  2164 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 17:37:47.838   313  2164 V AwesomePlayer: startAudioPlayer_l() 
08-26 17:37:47.838   313  2164 D AudioPlayer: start of Playback, useOffload 0
08-26 17:37:47.838   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 17:37:47.838   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 17:37:47.840   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 17:37:47.840   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 17:37:47.840   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 17:37:47.840   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 17:37:47.840   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 17:37:47.840   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790368
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790608
,08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790768
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,08-26 17:37:47.841   313  8012 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd150 on output port
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd060 on output port
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-26 17:37:47.841   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd740 on output port
08-26 17:37:47.842   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 17:37:47.842   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,08-26 17:37:47.844   313  2164 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 17:37:47.844   313  2164 V AudioCache: notify(0xb5474940, 6, 0, 0)
08-26 17:37:47.844   313  2164 V AudioCache: ignored
08-26 17:37:47.844   313  2164 V MediaPlayerService: wait for playback complete
08-26 17:37:47.845   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.845   313  8013 V AudioCache: memcpy(0xac100000, 0xb14b4000, 4096)
08-26 17:37:47.846   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.846   313  8013 V AudioCache: memcpy(0xac101000, 0xb14b4000, 4096)
08-26 17:37:47.846   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.847   313  8013 V AudioCache: memcpy(0xac102000, 0xb14b4000, 4096)
08-26 17:37:47.847   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.847   313  8013 V AudioCache: memcpy(0xac103000, 0xb14b4000, 4096)
08-26 17:37:47.848   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.848   313  8013 V AudioCache: memcpy(0xac104000, 0xb14b4000, 4096)
08-26 17:37:47.854   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.854   313  8013 V AudioCache: memcpy(0xac105000, 0xb14b4000, 4096)
08-26 17:37:47.854   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.854   313  8013 V AudioCache: memcpy(0xac106000, 0xb14b4000, 4096)
08-26 17:37:47.854   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.854   313  8013 V AudioCache: memcpy(0xac107000, 0xb14b4000, 4096)
08-26 17:37:47.854   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.854   313  8013 V AudioCache: memcpy(0xac108000, 0xb14b4000, 4096)
08-26 17:37:47.855   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.855   313  8013 V AudioCache: memcpy(0xac109000, 0xb14b4000, 4096)
08-26 17:37:47.855   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.855   313  8013 V AudioCache: memcpy(0xac10a000, 0xb14b4000, 4096)
08-26 17:37:47.855   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.855   313  8013 V AudioCache: memcpy(0xac10b000, 0xb14b4000, 4096)
08-26 17:37:47.856   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.857   313  8013 V AudioCache: memcpy(0xac10c000, 0xb14b4000, 4096)
08-26 17:37:47.857   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.857   313  8013 V AudioCache: memcpy(0xac10d000, 0xb14b4000, 4096)
08-26 17:37:47.858   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.858   313  8013 V AudioCache: memcpy(0xac10e000, 0xb14b4000, 4096)
,08-26 17:37:47.859   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.859   313  8013 V AudioCache: memcpy(0xac10f000, 0xb14b4000, 4096)
08-26 17:37:47.859   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.859   313  8013 V AudioCache: memcpy(0xac110000, 0xb14b4000, 4096)
08-26 17:37:47.860   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.860   313  8013 V AudioCache: memcpy(0xac111000, 0xb14b4000, 4096)
08-26 17:37:47.861   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.861   313  8013 V AudioCache: memcpy(0xac112000, 0xb14b4000, 4096)
08-26 17:37:47.862   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.862   313  8013 V AudioCache: memcpy(0xac113000, 0xb14b4000, 4096)
08-26 17:37:47.862   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.862   313  8013 V AudioCache: memcpy(0xac114000, 0xb14b4000, 4096)
08-26 17:37:47.863   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.863   313  8013 V AudioCache: memcpy(0xac115000, 0xb14b4000, 4096)
08-26 17:37:47.864   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.864   313  8013 V AudioCache: memcpy(0xac116000, 0xb14b4000, 4096)
08-26 17:37:47.865   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.865   313  8013 V AudioCache: memcpy(0xac117000, 0xb14b4000, 4096)
08-26 17:37:47.865   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.865   313  8013 V AudioCache: memcpy(0xac118000, 0xb14b4000, 4096)
08-26 17:37:47.866   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.866   313  8013 V AudioCache: memcpy(0xac119000, 0xb14b4000, 4096)
08-26 17:37:47.867   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.867   313  8013 V AudioCache: memcpy(0xac11a000, 0xb14b4000, 4096)
08-26 17:37:47.868   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.868   313  8013 V AudioCache: memcpy(0xac11b000, 0xb14b4000, 4096)
08-26 17:37:47.868  7710  7957 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 17:37:47.868  7710  7957 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0164061 
08-26 17:37:47.868  7710  7957 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0164061 
08-26 17:37:47.869   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.869   313  8013 V AudioCache: memcpy(0xac11c000, 0xb14b4000, 4096)
08-26 17:37:47.869   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.869   313  8013 V AudioCache: memcpy(0xac11d000, 0xb14b4000, 4096)
08-26 17:37:47.870   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.870   313  8013 V AudioCache: memcpy(0xac11e000, 0xb14b4000, 4096)
,08-26 17:37:47.871   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.871   313  8013 V AudioCache: memcpy(0xac11f000, 0xb14b4000, 4096)
08-26 17:37:47.871   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.871   313  8013 V AudioCache: memcpy(0xac120000, 0xb14b4000, 4096)
08-26 17:37:47.872   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.872   313  8013 V AudioCache: memcpy(0xac121000, 0xb14b4000, 4096)
08-26 17:37:47.872   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.872   313  8013 V AudioCache: memcpy(0xac122000, 0xb14b4000, 4096)
08-26 17:37:47.873   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.873   313  8013 V AudioCache: memcpy(0xac123000, 0xb14b4000, 4096)
08-26 17:37:47.873   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.873   313  8013 V AudioCache: memcpy(0xac124000, 0xb14b4000, 4096)
08-26 17:37:47.874   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.874   313  8013 V AudioCache: memcpy(0xac125000, 0xb14b4000, 4096)
08-26 17:37:47.874   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.874   313  8013 V AudioCache: memcpy(0xac126000, 0xb14b4000, 4096)
08-26 17:37:47.874   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.874   313  8013 V AudioCache: memcpy(0xac127000, 0xb14b4000, 4096)
08-26 17:37:47.876   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.876   313  8013 V AudioCache: memcpy(0xac128000, 0xb14b4000, 4096)
08-26 17:37:47.876   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.876   313  8013 V AudioCache: memcpy(0xac129000, 0xb14b4000, 4096)
08-26 17:37:47.876   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.876   313  8013 V AudioCache: memcpy(0xac12a000, 0xb14b4000, 4096)
08-26 17:37:47.876   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.876   313  8013 V AudioCache: memcpy(0xac12b000, 0xb14b4000, 4096)
08-26 17:37:47.878   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.878   313  8013 V AudioCache: memcpy(0xac12c000, 0xb14b4000, 4096)
08-26 17:37:47.878   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.878   313  8013 V AudioCache: memcpy(0xac12d000, 0xb14b4000, 4096)
08-26 17:37:47.878   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.878   313  8013 V AudioCache: memcpy(0xac12e000, 0xb14b4000, 4096)
08-26 17:37:47.878   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.878   313  8013 V AudioCache: memcpy(0xac12f000, 0xb14b4000, 4096)
08-26 17:37:47.879   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.879   313  8013 V AudioCache: memcpy(0xac130000, 0xb14b4000, 4096)
,08-26 17:37:47.879   313  8013 V AudioCache: write(0xb14b4000, 4096)
08-26 17:37:47.879   313  8013 V AudioCache: memcpy(0xac131000, 0xb14b4000, 4096)
08-26 17:37:47.879   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 17:37:47.879   313  8013 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 17:37:47.879   313  8013 V AwesomePlayer: postAudioEOS() 
08-26 17:37:47.879   313  8013 V AudioCache: write(0xb14b4000, 280)
08-26 17:37:47.879   313  8013 V AudioCache: memcpy(0xac132000, 0xb14b4000, 280)
08-26 17:37:47.881   313  8010 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 17:37:47.881   313  8010 V AwesomePlayer: onStreamDone
08-26 17:37:47.881   313  8010 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 17:37:47.881   313  8010 V AudioCache: notify(0xb5474940, 2, 0, 0)
08-26 17:37:47.881   313  8010 V AudioCache: playback complete
08-26 17:37:47.881   313  8010 V AwesomePlayer: pause_l() 
08-26 17:37:47.881   313  8010 V AudioCache: notify(0xb5474940, 7, 0, 0)
08-26 17:37:47.881   313  8010 V AudioCache: ignored
08-26 17:37:47.881   313  8010 V AwesomePlayer: cancelPlayerEvents
08-26 17:37:47.881   313  8010 D AudioPlayer: Pause Playback at 1068125
08-26 17:37:47.881   313  2164 V AudioCache: wait - success
08-26 17:37:47.881   313  2164 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 17:37:47.882   313  2164 V AwesomePlayer: reset_l() 
08-26 17:37:47.882   313  2164 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-26 17:37:47.882   313  2164 V AudioCache: ignored
08-26 17:37:47.882   313  2164 V AwesomePlayer: cancelPlayerEvents
,08-26 17:37:47.882   313  2164 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 17:37:47.882   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 17:37:47.882   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 17:37:47.882   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 17:37:47.882   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 17:37:47.882   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd740 on port 1
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd060 on port 1
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd150 on port 1
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 17:37:47.883   313  8012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 17:37:47.883   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 17:37:47.883   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 17:37:47.883   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 17:37:47.884   313  2164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 17:37:47.885   313  2164 D AudioPlayer: AudioPlayer releasing audio source
08-26 17:37:47.885   313  2164 D AudioPlayer: AudioPlayer done releasing audio source
08-26 17:37:47.885   313  2164 V AwesomePlayer: reset_l() 
08-26 17:37:47.885   313  2164 V AwesomePlayer: cancelPlayerEvents
08-26 17:37:47.885   313  2164 V AwesomePlayer: ~AwesomePlayer call
08-26 17:37:47.885  7710  7921 E bt-btif : Calling BTA_HhEnable
08-26 17:37:47.885   313  2164 V AwesomePlayer: reset_l() 
08-26 17:37:47.885  7710  7921 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 17:37:47.885   313  2164 V AwesomePlayer: cancelPlayerEvents
08-26 17:37:47.885  7710  7921 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 17:37:,47.885  7972  8007 V SoundPool: close(31)
08-26 17:37:47.886  7972  8007 V SoundPool: pointer = 0x9fe58000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 17:37:47.886  7710  7957 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 17:37:47.886  7710  7957 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 17:37:47.886  7710  7957 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 17:37:47.886  7710  7957 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 17:37:47.886  7710  7957 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 17:37:47.887  7710  7921 D BluetoothAdapterProperties: Name is: G3
08-26 17:37:47.887  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 17:37:47.887  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 17:37:47.888  7710  7921 D BluetoothAdapterProperties: Scan Mode:20
08-26 17:37:47.888  7710  7921 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 17:37:47.888  7710  7921 D bt_hci_bdroid: postload
08-26 17:37:47.889  7710  7959 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 17:37:47.889  7710  7921 D bte_conf: Device ID record 1 : primary
08-26 17:37:47.889  7710  7921 D bte_conf:   vendorId            = 00c4
08-26 17:37:47.889  7710  7921 D bte_conf:   vendorIdSource      = 0001
08-26 17:37:47.889  7710  7921 D bte_conf:   product             = 13a1
08-26 17:37:47.889  7710  7921 D bte_conf:   version             = 1000
,08-26 17:37:47.889  7710  7921 D bte_conf:   clientExecutableURL = 
08-26 17:37:47.889  7710  7921 D bte_conf:   serviceDescription  = 
08-26 17:37:47.889  7710  7921 D bte_conf:   documentationURL    = 
08-26 17:37:47.889  7710  7921 D bte_conf: bte_load_did_conf no section named DID2.
08-26 17:37:47.889  7710  7957 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 17:37:47.890  7710  7959 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 17:37:47.892  7710  7959 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 17:37:47.892  7710  7959 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 17:37:47.893  7710  7917 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 17:37:47.893  7710  7917 D BluetoothAdapterProperties: ScanMode =  20
08-26 17:37:47.893  7710  7917 D BluetoothAdapterProperties: State =  11
08-26 17:37:47.893  7710  7917 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,08-26 17:37:47.894  7710  7917 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 17:37:47.894  7710  7917 D BluetoothAdapterProperties: Setting state to 12
08-26 17:37:47.894  7710  7917 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 17:37:47.895  1035  1099 D BluetoothManagerService: Message: 60
,08-26 17:37:47.895  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 17:37:47.895  1035  1099 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 17:37:47.895  7710  7917 I BluetoothAdapterState: Entering On State
08-26 17:37:47.896  7710  7921 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 17:37:47.897  7710  7921 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 17:37:47.886  8015  8015 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:47.886  8015  8015 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:47.900  7710  7959 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 17:37:47.900  7710  7959 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 17:37:47.902  7710  7917 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 17:37:47.902  7710  7917 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 17:37:47.902  7710  7917 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 17:37:47.903  7710  7917 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 17:37:47.903  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 17:37:47.904  7710  8009 E bt_mct  : hci lib postload completed
,08-26 17:37:47.909  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:47.909  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:47.909  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:47.909  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:47.909  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:47.909  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:47.909  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:47.909  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:47.910  7710  7957 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:47.910  7710  7957 W bt-smp  : Plain text(LSB ~ MSB) = b0 a3 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:47.910  7710  7957 W bt-smp  : Encrypted text(LSB ~ MSB) = 0f 37 9d 1f 23 9f b2 74 76 b3 f7 9f ba 93 ee 8e 
08-26 17:37:47.910  7710  7957 W bt-btm  : Stopping oneshot timer
08-26 17:37:47.915  7710  7921 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 17:37:47.915  7710  7921 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 17:37:47.918  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:47.920  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:47.920  1852  1852 D BluetoothHeadset: Proxy object connected
08-26 17:37:47.921  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 17:37:47.922  1852  1852 D BluetoothHeadset: Proxy object connected
08-26 17:37:47.922  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 17:37:47.924  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8612
08-26 17:37:47.925  6866  6885 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 17:37:47.928  6866  6883 D BluetoothMap: onBluetoothStateChange: up=true
08-26 17:37:47.929  6866  6866 D BluetoothInputDevice: Proxy object connected
08-26 17:37:47.929  6866  6866 D HidProfile: Bluetooth service connected
08-26 17:37:47.931  1035  1099 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:47.931  6866  6866 D BluetoothMap: Proxy object connected
,08-26 17:37:47.931  6866  6866 D MapProfile: Bluetooth service connected
08-26 17:37:47.931  6866  6866 D BluetoothMap: getConnectedDevices()
08-26 17:37:47.931  6866  7378 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 17:37:47.931  1035  1035 D BluetoothHeadset: Proxy object connected
08-26 17:37:47.932  7710  7942 V BluetoothMapService: getConnectedDevices()
08-26 17:37:47.933  6866  6885 D BluetoothPan: onBluetoothStateChange on: true
08-26 17:37:47.933  6866  6885 D BluetoothPan: onBluetoothStateChange call bindService
08-26 17:37:47.933  6866  6866 D BluetoothA2dp: Proxy object connected
08-26 17:37:47.933  6866  6866 D A2dpProfile: Bluetooth service connected
08-26 17:37:47.935  6866  6866 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 17:37:47.935  6866  6866 D PanProfile: Bluetooth service connected
08-26 17:37:47.935  6866  6883 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:47.936  1035  1099 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 17:37:47.936  6866  6866 D BluetoothHeadset: Proxy object connected
08-26 17:37:47.936  6866  6866 D HeadsetProfile: Bluetooth service connected
08-26 17:37:47.936  1035  1035 D BluetoothA2dp: Proxy object connected
,08-26 17:37:47.937  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:47.937  7710  7957 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:47.937  7710  7957 W bt-smp  : Plain text(LSB ~ MSB) = 68 ed 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:47.937  7710  7957 W bt-smp  : Encrypted text(LSB ~ MSB) = 49 39 22 8e 05 6f ac f1 06 b7 92 02 98 6e 83 af 
08-26 17:37:47.937  7710  7957 W bt-btm  : Stopping oneshot timer
08-26 17:37:47.938  1852  1852 D BluetoothHeadset: Proxy object connected
,08-26 17:37:47.939  6866  7378 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 17:37:47.942  1035  1099 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 17:37:47.942  1035  1099 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 17:37:47.943  8020  8020 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 17:37:47.943  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 17:37:47.945  7710  7917 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 17:37:47.946  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:47.946  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 17:37:47.946  1941  2103 D LGBluetoothAPIService: Message: 1
08-26 17:37:47.946  1941  2103 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 17:37:47.946  1941  2103 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-26 17:37:47.946  1941  2103 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 17:37:47.948  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:47.949  7710  7710 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:47.950  7710  7710 D BluetoothMapService: STATE_ON
,08-26 17:37:47.950  1035  1099 D BluetoothManagerService: Message: 40
08-26 17:37:47.950  1035  1099 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 17:37:47.951  6866  6866 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 17:37:47.952  6866  6866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 17:37:47.953  7710  7957 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:47.953  7710  7957 W bt-smp  : Plain text(LSB ~ MSB) = 18 b4 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:47.953  7710  7957 W bt-smp  : Encrypted text(LSB ~ MSB) = 20 12 e6 b1 38 2a 10 62 4b 81 b6 33 3f e6 65 64 
08-26 17:37:47.954  7710  7957 W bt-btm  : Stopping oneshot timer
08-26 17:37:47.958  6866  6866 D DockEventReceiver: finishStartingService: stopping service
08-26 17:37:47.960  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:47.961  7710  7710 V BluetoothPbapService: Pbap Service onCreate
08-26 17:37:47.961  7710  7710 V BluetoothPbapService: Starting PBAP service
08-26 17:37:47.961  7710  7710 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 17:37:47.961  7710  7710 V BluetoothPbapService: Pbap Service onBind
08-26 17:37:47.962  7710  7710 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:47.962  7710  7710 V BluetoothPbapService: state: 12
08-26 17:37:47.962  7710  7710 V BluetoothMapService: Handler(): got msg=1
,08-26 17:37:47.963  7710  7957 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:47.963  7710  7957 W bt-smp  : Plain text(LSB ~ MSB) = b5 19 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:47.963  7710  7957 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 24 e1 9f 92 f6 e0 4f 14 00 80 c3 9a 13 a3 44 
08-26 17:37:47.963  7710  7957 W bt-btm  : Stopping oneshot timer
08-26 17:37:47.963  7710  7710 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 17:37:47.963  7710  7710 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 17:37:47.963  7710  7710 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:47.963  7710  7710 V BluetoothPbapReceiver: ***********state = 12
08-26 17:37:47.964  7710  8022 D BluetoothMapMasInstance: MAS initSocket()
08-26 17:37:47.964  6866  6866 D BluetoothPbap: Proxy object connected
08-26 17:37:47.964  6866  6866 D PbapServerProfile: Bluetooth service connected
08-26 17:37:47.964  7710  7710 V BluetoothPbapService: Handler(): got msg=1
08-26 17:37:47.964  7710  8022 D BluetoothMapMasInstance:   masId = 00
08-26 17:37:47.964  7710  8022 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 17:37:47.964  7710  8022 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 17:37:47.964  7710  8022 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 17:37:47.964  7710  7710 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 17:37:47.965  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:47.966  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:47.966  2208  2208 D c       : Getting all permits...
08-26 17:37:47.966  2208  2208 D a       : Opening database...
08-26 17:37:47.969  7710  8022 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:47.970  7710  8022 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 17:37:47.970  7710  8022 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 17:37:47.970  7710  7921 D BluetoothAdapterProperties: Scan Mode:21
08-26 17:37:47.970  7710  8022 D BluetoothMapMasInstance: Accepting socket connection...
08-26 17:37:47.970  7710  7921 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 17:37:47.971  7710  7957 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 17:37:47.971  7710  7957 W bt-smp  : Plain text(LSB ~ MSB) = 8a 8e 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 17:37:47.971  7710  7957 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 ec 67 57 c6 40 6e 90 2d 95 cb 27 eb 8c 90 18 
08-26 17:37:47.971  7710  7957 W bt-btm  : Stopping oneshot timer
08-26 17:37:47.971  7710  8023 V BluetoothPbapService: Pbap Service initSocket
08-26 17:37:47.971  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-26 17:37:47.971  1035  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:47.972  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:47.973  2208  2208 D a       : Closing database...
08-26 17:37:47.974  7710  8023 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:47.979  7710  8023 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 17:37:47.979  7710  8023 V BluetoothPbapService: Succeed to create listening socket 
08-26 17:37:47.979  7710  8023 V BluetoothPbapService: Accepting socket connection...
08-26 17:37:47.981  6866  6866 D BluetoothPermissionRequest: onReceive
08-26 17:37:47.982  6866  6866 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 17:37:47.983  6866  6866 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 17:37:47.989  7710  7710 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-26 17:37:47.990  7710  7710 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 17:37:47.995  7710  7710 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-26 17:37:48.015  7710  7710 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 17:37:48.015  7710  7710 V BtOppService: onCreate
,08-26 17:37:48.082  1035  1785 I art     : Explicit concurrent mark sweep GC freed 24469(1210KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.300ms total 65.285ms
,08-26 17:37:48.084  7710  7710 V BluetoothOppNotification: send message
08-26 17:37:48.090  7710  7710 V BtOppService: Starting RfcommListener
08-26 17:37:48.093  7710  8026 V BtOppService: Deleted complete outbound shares, number =  0
08-26 17:37:48.096  7710  8026 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 17:37:48.097  7710  8026 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 17:37:48.098  7710  8026 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27605a7e on behalf of 
,08-26 17:37:48.099  7710  7710 D BluetoothOppPreference: Dumping Names:  
08-26 17:37:48.099  7710  7710 D BluetoothOppPreference: {}
08-26 17:37:48.099  7710  7710 D BluetoothOppPreference: Dumping Channels:  
08-26 17:37:48.099  7710  7710 D BluetoothOppPreference: {}
08-26 17:37:48.100  7710  7710 V BtOppService: onStartCommand
,08-26 17:37:48.101  7710  8029 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 17:37:48.102  7710  8029 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 17:37:48.104  7710  8029 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@308d002c on behalf of 
08-26 17:37:48.104  7710  7710 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:48.104  7710  7710 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 17:37:48.107  7710  7710 V BluetoothOppNotification: new notify threadi!
08-26 17:37:48.107  7710  7710 V BluetoothOppNotification: send delay message
08-26 17:37:48.108  7710  7710 V BtOppService: start RfcommListener
08-26 17:37:48.110  7710  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 17:37:48.110  7710  7710 V BtOppService: RfcommListener started
08-26 17:37:48.111  7710  7710 V BtOppService: ContentObserver received notification
08-26 17:37:48.111  7710  7710 V BtOppService: ContentObserver received notification
08-26 17:37:48.115  7710  8031 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 17:37:48.115  1035  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 17:37:48.116  7710  8031 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:48.116  7710  8031 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 17:37:48.116  7710  8031 V BtOppRfcommListener: Started RFCOMM listener....
08-26 17:37:48.116  7710  8031 I BtOppRfcommListener: Accept thread started.
08-26 17:37:48.116  7710  8031 V BtOppRfcommListener: Accepting connection...
08-26 17:37:48.121  7710  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@301eaaf5 on behalf of 
08-26 17:37:48.123  7710  8030 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 17:37:48.125  7710  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 17:37:48.126  7710  8029 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 17:37:48.126  7710  8029 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 17:37:48.126  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:48.126  7710  7710 V BluetoothFtpService: Ftp Service onCreate
08-26 17:37:48.126  7710  7710 I BluetoothFtpService: Ftp Service onCreate
08-26 17:37:48.127  7710  7710 V BluetoothFtpService: Ftp Service onStartCommand
08-26 17:37:48.127  7710  7710 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:48.127  7710  7710 V BluetoothFtpService: Starting Listening on sockets
08-26 17:37:48.127  7710  7710 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 17:37:48.127  7710  7710 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 17:37:48.127  7710  7710 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 17:37:48.127  7710  7710 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:48.127  7710  7710 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 17:37:48.127  7710  7710 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 17:37:48.129  7710  7710 V BluetoothFtpService: Handler(): got msg=1
,08-26 17:37:48.130  7710  7710 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 17:37:48.130  7710  7710 V BluetoothFtpService: Ftp Service initSocket
,08-26 17:37:48.131  7710  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c5196fb on behalf of 
08-26 17:37:48.132  7710  8030 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 17:37:48.132  7710  8029 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bdff318 on behalf of 
08-26 17:37:48.133  7710  8029 V BluetoothOppNotification: update too frequent, put in queue
08-26 17:37:48.138  7710  8030 V BluetoothOppNotification: outbound notification was removed.
08-26 17:37:48.138  7710  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 17:37:48.138  7710  8029 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 17:37:48.138  1035  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:48.139  7710  7710 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:48.141  7710  7710 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-26 17:37:48.141  7710  7710 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-26 17:37:48.148  7710  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6fc0171 on behalf of 
08-26 17:37:48.149  7710  8030 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 17:37:48.152  7710  8030 V BluetoothOppNotification: inbound notification was removed.
08-26 17:37:48.152  7710  8030 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 17:37:48.153  7710  8032 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-26 17:37:48.153  7710  8030 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10233b56 on behalf of 
08-26 17:37:48.163  7710  7710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c34d2b3
08-26 17:37:48.163  7710  7710 V BluetoothSapService: Sap Service onCreate
08-26 17:37:48.165  7710  7710 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:48.165  7710  7710 V BluetoothSapService: state: 12
,08-26 17:37:48.165  7710  7710 V BluetoothSapService: Starting SAP server process
,08-26 17:37:48.166  7710  7710 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 17:37:48.167  7710  8034 V BluetoothSapService: Sap Service initRfcommSocket
,08-26 17:37:48.156  8033  8033 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:48.168  1035  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:48.156  8033  8033 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:48.169  7710  8034 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:48.170  7710  8034 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 17:37:48.170  7710  8034 V BluetoothSapService: Succeed to create listening socket 
08-26 17:37:48.170  7710  8034 V BluetoothSapService: Accepting socket connection...
08-26 17:37:48.180  8033  8033 V BT_SAP  : Event pipe created
08-26 17:37:48.180  8033  8033 V BT_SAP  : create_server_socket qcom.sap.server
08-26 17:37:48.180  8033  8033 V BT_SAP  : created socket fd 6
,08-26 17:37:48.204  7638  7638 I UEI.SmartControl: Supports setup maps: true
,08-26 17:37:48.210  7638  7638 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 17:37:48.210  7638  7638 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 17:37:48.210  7638  7638 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 17:37:48.210  7638  7638 I UEI.SmartControl: ### init IR Blaster...
08-26 17:37:48.214  7638  7638 D serial_port: Configuring serial port
08-26 17:37:48.214  7638  7638 E UEI.SmartControl: UEIBLaster setting for 616
08-26 17:37:48.214  7638  7638 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 17:37:48.214  7638  7638 I UEI.SmartControl: configuring settings for MAXQ616
08-26 17:37:48.215  7638  7638 I UEI.SmartControl: Get version...
08-26 17:37:48.233  7638  8035 D UEI.SmartControl: serial port data available: 21
,08-26 17:37:48.259  7638  7638 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 17:37:48.259  7638  7638 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 17:37:48.260  7638  7638 I UEI.SmartControl: QS saving settings...
,08-26 17:37:48.262  7638  7638 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 17:37:48.279  7638  8035 D UEI.SmartControl: serial port data available: 4
,08-26 17:37:48.308  7638  8038 I UEI.SmartControl: Device manager: loading config....
,08-26 17:37:48.313  7638  7638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 17:37:48.314  7638  8038 D UEI.SmartControl: ----------- loading internal config...
08-26 17:37:48.315  7638  7638 E UEI.SmartControl: Services init done
08-26 17:37:48.315  7638  7638 D UEI.SmartControl: QS Service init finished
08-26 17:37:48.317  7638  7638 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 17:37:48.317  7638  7638 D UEI.SmartControl: QS Service version code: 201091
08-26 17:37:48.319  7638  7638 D UEI.SmartControl: Service requested: Control
08-26 17:37:48.320  7638  8038 E UEI.SmartControl: Loading SETTINGS...
08-26 17:37:48.324  7638  7638 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 17:37:48.326  7638  8038 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 17:37:48.328  7638  7638 D UEI.SmartControl: Internal service binding...
08-26 17:37:48.329  7972  7972 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 17:37:48.332  7638  7654 I UEI.SmartControl: ------ IControl API: 11
08-26 17:37:48.332  7638  7654 D UEI.SmartControl: File observer start...
08-26 17:37:48.333  7638  7654 E UEI.SmartControl: IR Port is disabled: false
08-26 17:37:48.334  7638  7654 D UEI.SmartControl: Starting file observer...
08-26 17:37:48.334  7638  7654 I UEI.SmartControl: Registering callback...
08-26 17:37:48.336  7638  7653 I UEI.SmartControl: ------ IControl API: 19
08-26 17:37:48.338  7638  7653 I UEI.SmartControl: Registering Services Ready callback...
08-26 17:37:48.339  7638  7653 I UEI.SmartControl: Notify client services are ready...
08-26 17:37:48.340  7972  7989 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 17:37:48.341  7972  8005 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 17:37:48.341  7972  8005 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 17:37:48.342  7972  7972 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 17:37:48.343  7972  7972 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-26 17:37:48.344  7638  7654 I UEI.SmartControl: ------ IControl API: 8
,08-26 17:37:48.347  7638  8037 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 17:37:48.347  7972  7995 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 17:37:48.348  7638  8037 D UEI.SmartControl: -----service ready thread exits
08-26 17:37:48.348  7972  8005 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 17:37:48.348  7972  7972 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 17:37:48.348  7972  8005 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 17:37:48.349  7972  7972 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 17:37:48.350  7972  7972 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 17:37:48.351  7972  7972 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 17:37:48.352  7972  7972 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 17:37:48.353  7972  7972 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 17:37:48.356  7972  7972 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-26 17:37:48.360  7972  7972 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-26 17:37:48.361  7972  7972 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 17:37:48.363  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 17:37:48.365  7972  7972 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 17:37:48.366  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 17:37:48.368  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 17:37:48.371  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-26 17:37:48.372  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,08-26 17:37:48.375  7972  7972 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472225868373]
08-26 17:37:48.378  7972  7972 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 17:37:48.382  1035  1576 I ActivityManager: Killing 7165:com.android.chrome/u0a57 (adj 15): empty #17
08-26 17:37:48.417  7972  8040 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 17:37:48.439  1035  1995 W libprocessgroup: failed to open /acct/uid_10057/pid_7165/cgroup.procs: No such file or directory
,08-26 17:37:48.447  7972  7972 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-26 17:37:48.448  7972  7972 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 17:37:48.449  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 17:37:48.449  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 17:37:48.449  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 17:37:48.450  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 17:37:48.450  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 17:37:48.460  7972  7972 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 17:37:48.776  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:48.776  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:48.776  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:48.776  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:48.776  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:48.776  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:48.776  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:48.776  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:48.790  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:48.791  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:48.792  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12e0fc64 added. We now have 8 listener(s)
08-26 17:37:48.792  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:48.795  1035  1648 D WifiServiceImplEx: setWifiEnabled: false pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 17:37:48.795  1035  1648 D WifiService: setWifiEnabled: false pid=6695, uid=10118
08-26 17:37:48.795  1035  1648 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 17:37:48.805  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:48.807  1035  1932 D WifiServiceImplEx: setWifiEnabled: true pid=6695, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 17:37:48.808  1035  1932 D WifiService: setWifiEnabled: true pid=6695, uid=10118
08-26 17:37:48.808  1035  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 17:37:48.825  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 17:37:48.825  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 17:37:48.825  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-26 17:37:48.829  1035  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 17:37:48.829  1035  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 17:37:48.832  1035  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 17:37:48.832  1035  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 17:37:48.832  1035  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 17:37:48.832  1035  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 17:37:48.832  1035  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 17:37:48.832  1035  1540 E WifiHW  : unknown target_country: EU , set to default
08-26 17:37:48.832  1035  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 17:37:48.832  1035  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 17:37:48.832  1035  1540 I WifiUtil: gEnableBmps=1
08-26 17:37:49.109  7710  7710 V BluetoothOppNotification: new notify threadi!
08-26 17:37:49.109  7710  7710 V BluetoothOppNotification: send delay message
,08-26 17:37:49.138  7710  8053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 17:37:49.148  7710  8053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b2fb6e2 on behalf of 
08-26 17:37:49.149  7710  8053 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 17:37:49.150  7710  8053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-26 17:37:49.152  7710  8053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11d5ea73 on behalf of 
,08-26 17:37:49.153  7710  8053 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 17:37:49.155  7710  8053 V BluetoothOppNotification: outbound notification was removed.
,08-26 17:37:49.155  7710  8053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-26 17:37:49.156  7710  8053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d760d30 on behalf of 
08-26 17:37:49.156  7710  8053 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 17:37:49.157  7710  8053 V BluetoothOppNotification: inbound notification was removed.
08-26 17:37:49.157  7710  8053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 17:37:49.159  7710  8053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16686da9 on behalf of 
08-26 17:37:49.534   309   894 D SoftapController: Softap fwReload - Ok
,08-26 17:37:49.546  1035  1540 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (710ms)
08-26 17:37:49.557   309   894 D CommandListener: Setting iface cfg
08-26 17:37:49.557   309   894 D CommandListener: Trying to bring down wlan0
,08-26 17:37:49.561   309   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 17:37:49.577  1035  1099 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 17:37:49.584  1035  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 17:37:49.586  8061  8061 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 17:37:49.596  8061  8061 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:49.603  1035  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 17:37:49.603  1035  1540 E WifiStateMachine: useWiFiOffloading() : false
08-26 17:37:49.603  1035  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 17:37:49.619  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-26 17:37:49.629  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:49.630  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 17:37:49.643  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:49.646  1035  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 17:37:49.646  1035  1540 D WifiMonitor: connecting to supplicant
08-26 17:37:49.652  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 17:37:49.652  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 17:37:49.652  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 17:37:49.652  6866  6866 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 17:37:49.653  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 17:37:49.654  6866  6866 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 17:37:49.655  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 17:37:49.655  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 17:37:49.655  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 17:37:49.655  6866  6866 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 17:37:49.655  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 17:37:49.656  6866  6866 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 17:37:49.660  8061  8061 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 17:37:49.695  8061  8061 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 17:37:49.695  8061  8061 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 17:37:49.698  1035  1099 D Tethering: InitialState.processMessage what=4
,08-26 17:37:49.700  1035  1990 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8079 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-26 17:37:49.703  1035  1099 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 17:37:49.756  8061  8061 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 17:37:49.813  1035  1787 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8101 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 17:37:49.817  8079  8099 W FormManager: Network not available. Please check & try again.
08-26 17:37:49.824  8061  8061 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-26 17:37:49.824  8079  8100 V FormManager: Network unavailable.
08-26 17:37:49.828  8079  8100 V FormManager: Network unavailable.
08-26 17:37:49.831  8061  8061 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-26 17:37:49.833  1035  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 17:37:49.834  1035  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 17:37:49.834  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 17:37:49.834  1035  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 17:37:49.834  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 17:37:49.835  1035  8118 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 17:37:49.835  1035  8118 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 17:37:49.835  1035  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 17:37:49.836  1035  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:49.836  1035  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:49.837  1035  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:49.838  1035  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:49.838  1035  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 17:37:49.838  1035  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 17:37:49.839  1035  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 17:37:49.839  1035  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 17:37:49.839  1035  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 17:37:49.840  1035  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 17:37:49.840  1035  1540 E WifiStateMachine: useWiFiOffloading() : false
08-26 17:37:49.840  1035  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 17:37:49.840  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:49.840  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:49.840  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:49.841  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:49.841  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 17:37:49.843  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:49.844  1941  1941 D WfdService: Waiting for WifiP2p enabling
,08-26 17:37:49.845  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 17:37:49.845  1035  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 17:37:49.846  1035  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 17:37:49.846  1035  1540 D WifiNative-wlan0: SET update_config 1: returned true
,08-26 17:37:49.846  1035  1540 D WifiConfigStore: Loading config and enabling all networks 
08-26 17:37:49.846  1035  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 17:37:49.847  1035  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 17:37:49.848  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:49.848  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:49.848  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:49.848  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:49.848  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:49.848  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:49.848  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:49.848  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:49.850  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:49.854  1035  1785 I ActivityManager: Killing 7186:com.lge.drmservice/u0a62 (adj 15): empty #17
08-26 17:37:49.855  1035  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-26 17:37:49.865  1035  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-26 17:37:49.865  1035  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 17:37:49.885  1035  1050 W libprocessgroup: failed to open /acct/uid_10062/pid_7186/cgroup.procs: No such file or directory
08-26 17:37:49.885  1035  1540 D WifiStateMachine: enableVerboseLogging : level 2
08-26 17:37:49.885  1035  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 17:37:49.886  1035  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 17:37:49.886  1035  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 17:37:49.886  1035  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 17:37:49.886  1035  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 17:37:49.887  1035  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 17:37:49.887  1035  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 17:37:49.888  1035  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 17:37:49.888  1035  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 17:37:49.888  1035  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 17:37:49.888  1035  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 17:37:49.889  1035  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 17:37:49.889  1035  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 17:37:49.889  1035  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 17:37:49.890  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-26 17:37:49.891  1035  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 17:37:49.891  1035  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 17:37:49.891  1941  2242 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 17:37:49.891  1941  2242 D WfdsService: Set the WFDS Monitor: true
08-26 17:37:49.891  1941  2242 D WfdsMonitor: WfdsMonitorThread create
08-26 17:37:49.891  1035  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 17:37:49.891  1035  1540 D WifiNative-HAL: Setting external_sim to 1
08-26 17:37:49.891  7738  7738 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:49.891  1035  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 17:37:49.891  1941  2242 D WfdsMonitor: WFDS Monitor is created and started
08-26 17:37:49.891  1941  2242 D WfdsService: WiFi: Supplicant connection re-established
08-26 17:37:49.892  1035  1540 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 17:37:49.892  1035  1540 I WifiNative-HAL: startHal
08-26 17:37:49.892  1035  1540 D wifi    : setting scan oui 0x953fa360
08-26 17:37:49.892  1035  1540 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 17:37:49.892  1035  1540 I WifiNative-HAL: startHal
08-26 17:37:49.892  1035  1540 D wifi    : setting scan oui 0x953fa360
08-26 17:37:49.893  1035  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 17:37:49.893  1035  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 17:37:49.893  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 17:37:49.893  1941  8120 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 17:37:49.894  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 17:37:49.894  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 17:37:49.894  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 17:37:49.894  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 17:37:49.895  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 17:37:49.895  1941  8120 E CtrlSupplicant: Succeed to open control connection
08-26 17:37:49.895  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 17:37:49.895  8061  8061 I wpa_supplicant: wpa_driver_nl802,11_ext_driver_cmd RXFILTER-REMOVE 3
08-26 17:37:49.895  1941  8120 E CtrlSupplicant: Succeed to open monitor connection
08-26 17:37:49.895  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 17:37:49.895  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 17:37:49.896  1941  8120 D WfdsMonitor: Supplicant connection established
08-26 17:37:49.896  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 17:37:49.896  1941  2242 D WfdsService: Connected to the supplicant for wfds
08-26 17:37:49.896  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 17:37:49.896  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 17:37:49.897  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 17:37:49.898  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 17:37:49.898  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 17:37:49.899  8061  8061 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-26 17:37:49.899  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 17:37:49.899  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 17:37:49.900  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 17:37:49.900  1035  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 17:37:49.903  1035  1540 E WifiNative: : [137,930,544 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 17:37:49.903  1035  1540 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 17:37:49.904  1035  1540 D WifiNative-wlan0: RECONNECT: returned true
,08-26 17:37:49.904  1035  1540 D WifiNative-wlan0: doString: [STATUS]
08-26 17:37:49.905  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 17:37:49.905  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 17:37:49.905  1035  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 17:37:49.906  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 17:37:49.907  1035  1540 D WifiNative-wlan0: SET ps 1: returned true
08-26 17:37:49.907  1035  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.908  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 17:37:49.908  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-26 17:37:49.909  1035  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 17:37:49.909  1035  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.909  1035  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.909  1035  1557 I WifiNative-HAL: startHal
08-26 17:37:49.909  1035  1557 D wifi    : getting scan capabilities on interface[1] = 0x953fa360
08-26 17:37:49.909  1035  1557 D wifi    : failed to get capabilities : -3
08-26 17:37:49.909  1035  1557 E WifiScanningService: could not get scan capabilities
,08-26 17:37:49.909  1035  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 17:37:49.910   309   894 D CommandListener: Setting iface cfg
08-26 17:37:49.910   309   894 D CommandListener: Trying to bring up p2p0
08-26 17:37:49.910  1035  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 17:37:49.910  1035  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 17:37:49.910  1035  1538 D LGWifiP2pService: P2pEnablingState
08-26 17:37:49.910  1035  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.910  1035  1538 D LGWifiP2pService: P2p socket connection successful
08-26 17:37:49.910  1035  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 17:37:49.910  1035  1538 D LGWifiP2pService: P2pEnabledState
08-26 17:37:49.910  1035  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 17:37:49.911  1035  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 17:37:49.911  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 17:37:49.911  1941  1941 D WfdsService: WifiP2pState is changed : true
08-26 17:37:49.912  1941  2242 D WfdsService: Receive the WFDS_ENABLE Method
08-26 17:37:49.912  1941  2242 D WfdsService: Set the WFDS Monitor: true
08-26 17:37:49.912  1941  2242 D WfdsService: Connected to the supplicant for wfds
08-26 17:37:49.912  1941  2242 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 17:37:49.912  8061  8061 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 17:37:49.912  1941  2242 D WfdsService: selectPreferredScanChannel [36]
08-26 17:37:49.912  1941  2242 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 17:37:49.913  1035  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 17:37:49.913  1035  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 17:37:49.913  1035  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 17:37:49.914  8061  8061 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-26 17:37:49.914  1035  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 17:37:49.915  1035  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 17:37:49.915  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 17:37:49.915  1035  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 17:37:49.916  1035  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 17:37:49.916  1941  1941 D WfdsService: isConnected: false
08-26 17:37:49.916  1035  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 17:37:49.916  1035  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-26 17:37:49.916  1035  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 17:37:49.917  1035  1538 D LGWifiP2pService: before postfix = G3
08-26 17:37:49.917  1035  1538 D WifiServerServiceExt: postfix byte check : 2
08-26 17:37:49.917  1035  1538 D LGWifiP2pService: after postfix = G3
08-26 17:37:49.917  1035  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 17:37:49.917  1035  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 17:37:49.917  1035  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 17:37:49.918  1035  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 17:37:49.918  1035  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 17:37:49.918  8061  8061 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 17:37:49.918  1035  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 17:37:49.919  1035  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 17:37:49.919  1035  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 17:37:49.919  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 17:37:49.921  1035  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 17:37:49.921  1035  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 17:37:49.922  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 17:37:49.922  8061  8061 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:49.923  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 17:37:49.923  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:49.923  1035  8118 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:49.923  1035  8118 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:49.923  8061  8061 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 17:37:49.923  8061  8061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.924  8061  8061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 17:37:49.926  1941  8120 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:49.926  1941  8120 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:49.928  1035  8118 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:49.928  1035  8118 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.928  1035  8118 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.928  1035  8118 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.928  1035  8118 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:49.928  1035  8118 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.928  1035  8118 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.928  1035  8118 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.929  1035  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 17:37:49.929  1035  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 17:37:49.929  1035  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 17:37:49.930  1035  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 17:37:49.930  1035  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 17:37:49.930  1035  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-26 17:37:49.930  1035  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 17:37:49.930  1035  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 17:37:49.931  1035  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 17:37:49.931  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 17:37:49.931  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 17:37:49.931  8061  8061 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 17:37:49.932  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 17:37:49.932  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 17:37:49.932  1035  8118 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 17:37:49.932  1035  8118 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 17:37:49.932  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 17:37:49.932  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 17:37:49.932  1941  1941 D WfdsService: Update P2p Interface State: 3
08-26 17:37:49.932  1035  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 17:37:49.933  1035  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 17:37:49.933  1035  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 17:37:49.933  1035  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 17:37:49.933  1035  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 17:37:49.933  1035  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 17:37:49.934  1035  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 17:37:49.934  1035  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 17:37:49.934  1035  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 17:37:49.934  1035  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 17:37:49.943  8101  8101 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:49.945  1035  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 17:37:49.945  1035  1538 D LGWifiP2pS,ervice: sending p2p persistent groups changed broadcast
08-26 17:37:49.946  1035  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 17:37:49.946  1035  1540 D WifiNative-wlan0: doBoolean: SCAN
,08-26 17:37:49.946  1035  1540 D WifiNative-wlan0: SCAN: returned false
08-26 17:37:49.947  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137976  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 17:37:49.949  1035  1538 D LGWifiP2pService: InactiveState
08-26 17:37:49.949  1035  1538 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.949  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.949  1035  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 17:37:49.949  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:49.950  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 17:37:49.950  8061  8061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:49.951  8061  8061 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 17:37:49.951  1035  8118 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 17:37:49.951  1035  8118 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:49.951  8061  8061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.951  1035  8118 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:49.951  1035  8118 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 17:37:49.951  1035  8118 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:49.951  1035  8118 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.952  1035  8118 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.952  1035  8118 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.952  1035  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 17:37:49.952  1035  1538 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.952  8061  8061 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.952  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.952  1035  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.952  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.952  1035  1538 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.952  1035  1538 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.952  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.952  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137982  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 17:37:49.952  1035  1538 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.953  1035  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.953  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.ut,il.StateMachine$SmHandler }
08-26 17:37:49.953  1035  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.953  1941  8120 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 17:37:49.953  1035  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.953  1941  8120 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:49.953  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.953  1035  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 17:37:49.953  1941  8120 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:49.953  1035  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:49.953  1035  1035 E WifiServerServiceExt: No p2p device connected
08-26 17:37:49.953  1035  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 17:37:49.953  1035  8118 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 17:37:49.954  1035  8118 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.954  1035  8118 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 17:37:49.954  1035  8118 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 17:37:49.954  1035  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 17:37:49.954  1035  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 17:37:49.955  1941  2242 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 17:37:49.956  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:49.957  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:49.958  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:49.959  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:49.959  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:49.959  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 17:37:49.961  1035  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-26 17:37:49.962  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-26 17:37:49.962  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-26 17:37:49.966  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:49.968  1035  1990 I ActivityManager: Killing 7203:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 17:37:50.064  1035  1576 W libprocessgroup: failed to open /acct/uid_10085/pid_7203/cgroup.procs: No such file or directory
,08-26 17:37:50.101  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-26 17:37:50.101  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-26 17:37:50.101  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-26 17:37:50.101  6866  6866 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 17:37:50.102  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-26 17:37:50.104  6866  6866 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-26 17:37:50.104  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-26 17:37:50.104  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-26 17:37:50.104  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 17:37:50.104  6866  6866 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 17:37:50.105  6866  6866 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-26 17:37:50.123  8101  8101 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 17:37:50.133  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:50.148  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 17:37:50.157  8079  8124 W FormManager: Network not available. Please check & try again.
08-26 17:37:50.161  8079  8125 V FormManager: Network unavailable.
,08-26 17:37:50.166  8079  8125 V FormManager: Network unavailable.
08-26 17:37:50.178  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 17:37:50.179  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 17:37:50.183  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:50.186  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 17:37:50.194  4296  8126 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 17:37:50.196  4296  8127 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 17:37:50.197  4296  8127 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 17:37:50.243  1035  1050 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8128 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 17:37:50.381  8128  8128 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 17:37:50.382  8128  8128 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-26 17:37:50.391  8128  8128 V [BNRBootReceiver]: Boot Receiver Return
08-26 17:37:50.391  8128  8128 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 17:37:50.473  1035  1051 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8149 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 17:37:50.475  8061  8061 E wpa_supplicant: USIM:  scard_init function
08-26 17:37:50.477  8061  8061 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 17:37:50.481  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 17:37:50.481  1035  8118 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 17:37:50.481  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 17:37:50.481  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-26 17:37:50.481  1035  8118 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 17:37:50.481  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 17:37:50.481  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 17:37:50.483  1035  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 17:37:50.483  1035  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 17:37:50.484  1035  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 17:37:50.484  1035  1051 I ActivityManager: Killing 7239:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-26 17:37:50.485  1035  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 17:37:50.486  1035  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 17:37:50.599  8061  8061 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 17:37:50.611  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 17:37:50.611  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 17:37:50.611  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 17:37:50.611  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 17:37:50.611  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:50.611  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 17:37:50.620  8061  8061 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 17:37:50.620  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:50.620  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 17:37:50.620  8061  8061 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 17:37:50.620  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 17:37:50.620  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 17:37:50.620  1035  8118 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 17:37:50.620  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 17:37:50.620  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 17:37:50.621  1035  8118 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 17:37:50.621  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:50.621  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 17:37:50.753  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138782  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 17:37:50.774  1035  1099 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
,08-26 17:37:50.778  1035  2032 W libprocessgroup: failed to open /acct/uid_10093/pid_7239/cgroup.procs: No such file or directory
08-26 17:37:50.784  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138814  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 17:37:50.785  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138814  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 17:37:50.786  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138815  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-26 17:37:50.795  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:50.795  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:50.796  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.796  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.796  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 17:37:50.797  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:50.800  1035  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138830
08-26 17:37:50.801  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.801  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.801  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 17:37:50.801  1035  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138831
08-26 17:37:50.802  1035  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138831
08-26 17:37:50.803  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138832
08-26 17:37:50.804  1035  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138833
08-26 17:37:50.805  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138834  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 17:37:50.806  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138836  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 17:37:50.807  1035  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138836  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 17:37:50.808  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138838  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 17:37:50.809  1035  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138838
08-26 17:37:50.809  1035  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138839
,08-26 17:37:50.810  1035  1540 D WifiNative-wlan0: doString: [STATUS]
08-26 17:37:50.811  1035  8118 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 17:37:50.811  1035  8118 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 17:37:50.812  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.812  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.812  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 17:37:50.814  1035  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 17:37:50.816  1035  1540 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 17:37:50.818  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.819  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.819  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 17:37:50.820  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:50.820  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:50.821  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:50.825  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:50.825  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 17:37:50.828  1035  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 17:37:50.828  1035  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 17:37:50.830  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:50.831  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:50.831  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:50.841  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 17:37:50.845  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.845  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.846  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 17:37:50.846  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.846  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.846  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 17:37:50.848  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:50.848  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:50.850  1035  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 17:37:50.850  1035  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 17:37:50.850  1035  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 17:37:50.851  1035  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 17:37:50.851  1035  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 17:37:50.851  1035  1546 D ConnectivityService: Got NetworkAgent Messenger
08-26 17:37:50.851  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 17:37:50.851  1035  1546 D ConnectivityService: NetworkAgent connected
08-26 17:37:50.853  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 17:37:50.855  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:50.855  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:50.856  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:50.858  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:50.858  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:50.858  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:50.858  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:50.858  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:50.858  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:50.858  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:50.858  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:50.859  1035  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 17:37:50.859  1035  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 17:37:50.859  1035  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 17:37:50.859  1035  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 17:37:50.859  1035  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 17:37:50.860  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:50.864  1035  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 17:37:50.865  6695  6799 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 17:37:50.866   309   894 D CommandListener: Setting iface cfg
08-26 17:37:50.866  6695  6799 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 17:37:50.868  6695  6799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8d1c346 Bundle[{}]
08-26 17:37:50.869  1035  1540 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 17:37:50.869  1035  8176 D DhcpStateMachine: StoppedState
08-26 17:37:50.869  1035  8176 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:50.869  1035  8176 D DhcpStateMachine: WaitBeforeStartState
08-26 17:37:50.869  1035  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138898  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:50.869  6695  6799 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 17:37:50.869  6695  6799 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 17:37:50.869  1035  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138899  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:50.870  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138899  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:50.871  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:50.871  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-26 17:37:50.872  6695  6799 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 17:37:50.873  6695  6799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 17:37:50.873  6695  6799 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 17:37:50.874  6695  6799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 17:37:50.876  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:50.876  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:50.877  1035  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:50.877  1035  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:50.878  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:50.878  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 17:37:50.878  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:50.878  1035  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 17:37:50.879  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:50.879  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 17:37:50.880  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:50.880  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 17:37:50.880  1035  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138910  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:50.881  1035  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138910  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:50.881  6695  6799 I System.out: Running OutgoingSocketThread
08-26 17:37:50.881  1035  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138911  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 17:37:50.883  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14341] from screen [on:0 period:-947911645] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 17:37:50.883  8149  8149 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 17:37:50.883  6695  8181 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
08-26 17:37:50.884  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-947911645] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 17:37:50.884  1035  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 17:37:50.885  6695  8181 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44304
08-26 17:37:50.885  6695  8181 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 17:37:50.888  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:50.890  1035  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 17:37:50.890  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:50.891  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:50.891  1035  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:50.892  1035  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:50.892  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:50.892  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 17:37:50.893  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 17:37:50.894  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
08-26 17:37:50.894  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
08-26 17:37:50.894  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 17:37:50.894  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 17:37:50.895  1035  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 17:37:50.896  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 17:37:50.896  1035  1540 D WifiNative-wlan0: SET ps 0: returned true
08-26 17:37:50.896  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 17:37:50.896  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 17:37:50.898  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 17:37:50.898  1035  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 17:37:50.898  1035  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 17:37:50.899  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d1884f8 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:50.899  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d1884f8 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:50.899  1035  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 17:37:50.899  1035  8176 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:50.899  1035  8176 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-26 17:37:50.901   309   894 D CommandListener: Setting iface cfg
08-26 17:37:50.901   309   894 D CommandListener: Trying to bring up wlan0
08-26 17:37:50.902  1035  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 17:37:50.903  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:50.903  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 17:37:50.904  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 17:37:50.904  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 17:37:50.904  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 17:37:50.905  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 17:37:50.905  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 17:37:50.905  1035  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:50.905  1035  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:50.905  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 17:37:50.905  1035  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 17:37:50.906  1035  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 17:37:50.906  8061  8061 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 17:37:50.906  1035  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 17:37:50.906  1035  1540 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 17:37:50.912  8149  8149 D PluginManager: init()
,08-26 17:37:50.923  1035  1540 D WifiNative-wlan0: SET ps 1: returned true
08-26 17:37:50.924  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:50.924  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:50.925  1035  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:50.925  1035  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:50.925  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:50.926  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:50.926  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 17:37:50.926  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 17:37:50.927  1035  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 17:37:50.927  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 17:37:50.927  1035  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 17:37:50.928  1035  1546 D ConnectivityService: ignoring duplicate network state non-change
,08-26 17:37:50.931  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:50.931  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:50.933  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:50.933  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.934  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.934  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 17:37:50.938  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.938  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.938  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 17:37:50.939  1035  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 17:37:50.939  1035  1546 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 17:37:50.944  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-26 17:37:50.944  1035  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 17:37:50.947  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 17:37:50.950  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.950  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:50.951  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 17:37:50.955  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 17:37:50.961  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.961  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:50.961  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 17:37:50.963  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:50.963  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 17:37:50.964  1035  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 17:37:50.964  1035  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 17:37:50.965  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 17:37:50.966  1035  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 17:37:50.967  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 17:37:50.967  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 17:37:50.967   309   894 E Netd    : netlink response contains error (File exists)
08-26 17:37:50.967  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:50.968  1035  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 17:37:50.969  1035  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 17:37:50.969  1035  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 17:37:50.969  1035  1546 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 17:37:50.970  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:50.970  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 17:37:50.971  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:50.972  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 17:37:50.972  1035  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 17:37:50.972  1035  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 17:37:50.973  1035  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:50.973  1035  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 17:37:50.973  1035  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:50.973  1035  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 17:37:50.974  1035  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 17:37:50.974  1035  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:50.974  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:50.974  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 17:37:50.974  1035  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:50.974  1035  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 17:37:50.974  1035  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-26 17:37:50.974  1035  1546 D ConnectivityService:    accepting network in place of null
08-26 17:37:50.974  1035  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 17:37:50.975  1035  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:50.975  1035  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:50.975  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:50.975  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 17:37:50.975   309  8187 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 17:37:50.976  1035  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 17:37:50.976  1035  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 17:37:50.976  1035  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 17:37:50.976   309  8187 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-26 17:37:50.977  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 17:37:50.977   309  8187 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
08-26 17:37:50.977  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 17:37:50.977  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 17:37:50.977  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 17:37:50.978   309  8187 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
,08-26 17:37:50.980  1035  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 17:37:50.981  1035  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-26 17:37:50.986  1035  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:50.986  1035  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 17:37:50.987  1035  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 17:37:50.988  1035  1546 D ConnectivityService: validation of new default Network = false
,08-26 17:37:50.988  1035  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 17:37:50.988  1035  1546 D DSQN    : enableDataServiceNotify 
08-26 17:37:50.988  1035  1546 D DSQN    : start dsqn bin
08-26 17:37:50.994  1035  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 17:37:50.994  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:50.994  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:50.994  1035  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-26 17:37:50.996  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 17:37:50.986  8188  8188 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:50.986  8188  8188 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:50.999  1035  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 17:37:51.011  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 17:37:51.011  8188  8188 E DSQN    : DSQN ssw
,08-26 17:37:51.011  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 17:37:51.012  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 17:37:51.104  1035  8176 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 17:37:51.106  1035  8176 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 17:37:51.106  1035  8176 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-26 17:37:51.106  8192  8192 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:51.106  8192  8192 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 17:37:51.132  8192  8192 I dhcpcd  : version 5.5.6 starting
08-26 17:37:51.134  8192  8192 E dhcpcd  : get_duid: m
08-26 17:37:51.134  8192  8192 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 17:37:51.134  8192  8192 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-26 17:37:51.219  8192  8192 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 17:37:51.219  8192  8192 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 17:37:51.219  8192  8192 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 17:37:51.219  8192  8192 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-26 17:37:51.219  8192  8192 D dhcpcd  : wlan0: sending REQUEST (xid 0x89a32814), next in 3.76 seconds
,08-26 17:37:51.258  8149  8149 W ExternalStrings: load override strings
08-26 17:37:51.258  8149  8149 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 17:37:51.258  8149  8149 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 17:37:51.260  8149  8149 D StatusProvider: onCreate
,08-26 17:37:51.281  8192  8192 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 17:37:51.304  8149  8149 V Signer  : override build config not found
,08-26 17:37:51.304  8149  8149 D Signer  : value of property debug is false
,08-26 17:37:51.308  8192  8192 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-26 17:37:51.308  8192  8192 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-26 17:37:51.308  8192  8192 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 17:37:51.309  8192  8192 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 17:37:51.309  8192  8192 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 17:37:51.310  8192  8192 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 17:37:51.310  8192  8192 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-26 17:37:51.310  8192  8192 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 17:37:51.336  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-26 17:37:51.337  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-26 17:37:51.337  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 17:37:51.337  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 17:37:51.337  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 17:37:51.338  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 17:37:51.338  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 17:37:51.338  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 17:37:51.338  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 17:37:51.338  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-26 17:37:51.338  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 17:37:51.339  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 17:37:51.339  8149  8149 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-26 17:37:51.370  8149  8149 V LGMDMManager: Create singleton instance
,08-26 17:37:51.447  8149  8149 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-26 17:37:51.508  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 17:37:51.508  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 17:37:51.512  1035  8176 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 17:37:51.513  1035  8176 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 17:37:51.513  1035  8176 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 17:37:51.514  1035  8176 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 17:37:51.514  1035  8176 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 17:37:51.514  1035  8176 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 17:37:51.514  1035  8176 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 17:37:51.514  1035  8176 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 17:37:51.514  1035  8176 D DhcpStateMachine: RunningState
08-26 17:37:51.520  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:51.528  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:51.538  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:51.540  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 17:37:51.552  7972  7972 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 17:37:51.554  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 17:37:51.557  6866  6866 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 17:37:51.560  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 17:37:51.560  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 17:37:51.560  6866  6866 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 17:37:51.560  6866  6866 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 17:37:51.561  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 17:37:51.561  6866  6866 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 17:37:51.561  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 17:37:51.561  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 17:37:51.562  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 17:37:51.562  6866  6866 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 17:37:51.562  6866  6866 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 17:37:51.562  6866  6866 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 17:37:51.565  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:51.565  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 17:37:51.571  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:51.578  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:51.585  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 17:37:51.586  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.587  7972  7972 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 17:37:51.591  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:51.592  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 17:37:51.602  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 17:37:51.609  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 17:37:51.615  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:51.616  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.616  7972  7972 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 17:37:51.715  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:51.716  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 17:37:51.723  8149  8223 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-26 17:37:51.729  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:51.733  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 17:37:51.738  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:51.738  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.738  7972  7972 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 17:37:51.742  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:51.742  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 17:37:51.748  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:51.754  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:51.759  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:51.759  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.760  7972  7972 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 17:37:51.763  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 17:37:51.764  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 17:37:51.769  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 17:37:51.773  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 17:37:51.778  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:51.778  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.778  7972  7972 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 17:37:51.782  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:51.782  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 17:37:51.789  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:51.793  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:51.798  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:51.798  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.799  7972  7972 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 17:37:51.805  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 17:37:51.806  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 17:37:51.816  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:51.836  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:51.841  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:51.841  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.848  7972  7972 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 17:37:51.854  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:51.855  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 17:37:51.868  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 17:37:51.873  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 17:37:51.881  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 17:37:51.883  6695  6799 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
08-26 17:37:51.883  6695  6799 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
08-26 17:37:51.887  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.888  7972  7972 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 17:37:51.889  6695  6799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
,08-26 17:37:51.890  6695  6799 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 17:37:51.890  6695  6799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
08-26 17:37:51.894  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:51.894  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 17:37:51.895  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:51.895  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@300a1ecd added. We now have 2 listener(s)
,08-26 17:37:51.897  1035  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:51.899  8101  8101 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 17:37:51.900  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:51.900  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:51.900  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:51.900  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:51.900  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@293fc382 added. We now have 9 listener(s)
08-26 17:37:51.901  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:51.901  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:51.903  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:51.903  8101  8101 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 17:37:51.907  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 17:37:51.908  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:51.908  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:51.908  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:51.908  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:51.908  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:51.908  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:51.908  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:51.908  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:51.910  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:51.910  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:51.910  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:51.910  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e37ad0 added. We now have 3 listener(s)
08-26 17:37:51.911  1035  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:51.912  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:51.914  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:51.914  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:51.914  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:51.914  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:51.914  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:51.914  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b26dac9 added. We now have 10 listener(s)
08-26 17:37:51.914  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:51.914  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:51.914  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:51.914  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:51.914  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:51.914  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.914  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:51.914  6695  6799 I org.thaliproject.p2p.btconnectorlib,.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:51.914  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@300a1ecd removed from the list
08-26 17:37:51.914  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:51.915  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@293fc382 removed from the list
08-26 17:37:51.915  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:51.915  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.915  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.915  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.916  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:51.916  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:51.916  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:51.916  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@293fc382 not in the list
08-26 17:37:51.916  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.916  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.917  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:51.917  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:51.917  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:51.917  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b26dac9 removed from the list
08-26 17:37:51.917  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:51.917  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.917  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.917  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:51.917  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e37ad0 removed from the list
,08-26 17:37:51.918  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:51.918  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26aa95ce added. We now have 2 listener(s)
08-26 17:37:51.918  1035  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:51.921  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:51.921  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:51.921  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:51.922  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:51.922  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b9abcef added. We now have 9 listener(s)
08-26 17:37:51.922  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:51.922  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:51.922  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:51.925  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:51.928  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:51.928  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:51.928  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:51.928  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:51.928  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:51.928  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:51.928  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:51.928  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:51.930  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:51.930  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:51.930  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:51.930  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29395a85 added. We now have 3 listener(s)
08-26 17:37:51.931  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:51.932  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:51.932  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.932  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:51.933  7972  7972 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 17:37:51.933  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:51.933  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:51.933  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:51.933  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:51.933  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ede40da added. We now have 10 listener(s)
08-26 17:37:51.933  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:51.933  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:51.933  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:51.934  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:51.934  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:51.934  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:51.934  7972  7972 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 17:37:51.934  7972  7972 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 17:37:51.934  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:51.936  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 17:37:51.939  1035  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 17:37:51.941  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 17:37:51.941  8149  8224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 17:37:51.944  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 17:37:51.945  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 17:37:51.947  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:51.947  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:51.947  8101  8101 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 17:37:51.948  8101  8101 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 17:37:51.949  6695  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 17:37:51.949  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:51.949  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:51.952  6866  6866 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 17:37:51.952  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:51.953  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:51.953  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:51.953  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:51.953  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.953  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:51.953  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:51.953  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26aa95ce removed from the list
08-26 17:37:51.953  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:51.953  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b9abcef removed from the list
08-26 17:37:51.953  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:51.953  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.954  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.954  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.955  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:51.955  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:51.955  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:51.955  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b9abcef not in the list
08-26 17:37:51.955  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.955  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.956  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:51.958  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:51.958  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:51.958  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:51.958  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:51.958  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ede40da removed from the list
08-26 17:37:51.958  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:51.958  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.958  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 1,7:37:51.958  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:51.958  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29395a85 removed from the list
08-26 17:37:51.959  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:51.959  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3a1a01 added. We now have 2 listener(s)
08-26 17:37:51.959  1035  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:51.961  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:51.961  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:51.961  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:51.961  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:51.961  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66f90a6 added. We now have 9 listener(s)
08-26 17:37:51.962  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:51.962  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:51.964  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:51.965  6866  6866 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 17:37:51.969  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:51.969  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:51.969  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:51.969  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:51.969  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:51.969  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:51.969  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:51.969  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:51.973  7972  7972 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 17:37:51.973  7972  7972 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 17:37:51.973  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:51.973  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:51.973  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:51.974  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29ae4694 added. We now have 3 listener(s)
08-26 17:37:51.974  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:51.974  7972  7972 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 17:37:51.975  7972  7972 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 17:37:51.975  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:51.975  7972  7972 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 17:37:51.977  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:51.977  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:51.977  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:51.977  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:51.977  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d553d added. We now have 10 listener(s)
08-26 17:37:51.977  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:51.978  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 17:37:51.978  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:51.978  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:51.978  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:51.978  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:51.979  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:51.980  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:51.980  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:51.981  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 17:37:51.982  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:51.982  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:51.983  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:51.984  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:51.985  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 17:37:51.986  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 17:37:51.986  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:51.988  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:51.988  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:51.988  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:51.989  6695  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 17:37:51.989  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:51.989  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:51.989  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:51.989  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:51.989  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.989  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:51.989  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:51.989  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeLis,tener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3a1a01 removed from the list
08-26 17:37:51.989  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:51.989  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66f90a6 removed from the list
08-26 17:37:51.989  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:51.989  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.990  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-26 17:37:51.991  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:51.991  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.991  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.993  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:51.993  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:51.993  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:51.993  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66f90a6 not in the list
08-26 17:37:51.993  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.993  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.993  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:51.994  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:51.995  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:51.995  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:51.995  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:51.995  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:51.995  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d553d removed from the list
08-26 17:37:51.995  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:51.995  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:51.995  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:51.995  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:51.995  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29ae4694 removed from the list
08-26 17:37:51.995  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:51.995  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:51.995  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f733800 added. We now have 2 listener(s)
08-26 17:37:51.996  1035  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:51.997  8149  8223 D LgDataFeature: LgDataFeature() Constructor: none
08-26 17:37:51.998  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:51.998  8149  8223 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 17:37:51.998  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, ser,vice record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:51.998  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:51.998  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:51.998  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f1f0839 added. We now have 9 listener(s)
08-26 17:37:51.998  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:51.998  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 17:37:52.000  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:52.001  1035  2032 I ActivityManager: Killing 7276:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-26 17:37:52.118  8149  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-26 17:37:52.123  1035  1785 W libprocessgroup: failed to open /acct/uid_10005/pid_7276/cgroup.procs: No such file or directory
08-26 17:37:52.126  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:52.132  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:52.132  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:52.132  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:52.132  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:52.132  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:52.132  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:52.132  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:52.132  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:52.135  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:52.136  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:52.136  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:52.137  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89abfdf added. We now have 3 listener(s)
08-26 17:37:52.137  1035  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:52.139  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:52.144  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:52.144  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:52.144  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:52.145  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:52.145  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:52.145  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d3d42c added. We now have 10 listener(s)
08-26 17:37:52.145  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.145  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:52.145  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:52.146  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:52.146  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:52.146  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:52.150  8149  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-26 17:37:52.153  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 17:37:52.154  1035  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:52.161  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 17:37:52.162  8149  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 17:37:52.163  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 17:37:52.163  8149  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-26 17:37:52.164  8149  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 17:37:52.165  8149  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
,08-26 17:37:52.165  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:52.165  8149  8223 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 17:37:52.166  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:52.169  6695  6799 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 17:37:52.171  8149  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-26 17:37:52.171  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:52.171  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:52.171  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:52.172  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:52.172  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.172  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:52.172  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.172  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f733800 removed from the list
08-26 17:37:52.173  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.173  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f1f0839 removed from the list
08-26 17:37:52.173  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:52.173  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.173  8149  8223 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-26 17:37:52.173  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.173  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.175  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.175  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.175  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.175  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f1f0839 not in the list
,08-26 17:37:52.175  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.175  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.177  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.178  6695  6799 D BluetoothLeScanner: could not find callback wrapper
08-26 17:37:52.178  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 17:37:52.178  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:52.178  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.178  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d3d42c removed from the list
08-26 17:37:52.178  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:52.178  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.178  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.178  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.178  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89abfdf removed from the list
,08-26 17:37:52.179  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:52.179  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f157afb added. We now have 2 listener(s)
,08-26 17:37:52.179  1035  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 17:37:52.182  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:52.182  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:52.182  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:52.182  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:52.182  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c00718 added. We now have 9 listener(s)
08-26 17:37:52.182  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.183  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-26 17:37:52.186  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:52.190  6695  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:52.190  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-26 17:37:52.190  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 17:37:52.190  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:52.190  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:52.190  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:52.190  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:52.190  6695  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
08-26 17:37:52.192  6695  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:52.192  6695  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:52.192  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:52.192  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14136f56 added. We now have 3 listener(s)
,08-26 17:37:52.193  1035  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 17:37:52.195  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 17:37:52.195  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:52.195  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:52.196  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:52.196  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ab6cbd7 added. We now have 10 listener(s)
,08-26 17:37:52.196  6695  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.196  6695  6799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:52.196  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:52.196  6695  6799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:52.196  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:52.196  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.196  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:52.196  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.197  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f157afb removed from the list
08-26 17:37:52.197  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:52.197  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c00718 removed from the list
08-26 17:37:52.197  6695  6799 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:52.197  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.198  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:52.198  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.201  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.201  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-26 17:37:52.201  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.201  6695  6799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c00718 not in the list
,08-26 17:37:52.201  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.201  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.201  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:52.202  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.202  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.202  6695  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:52.202  6695  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ab6cbd7 removed from the list
08-26 17:37:52.202  6695  6799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:52.202  6695  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:52.203  6695  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.203  6695  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.203  6695  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14136f56 removed from the list
08-26 17:37:52.204  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 17:37:52.204  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 17:37:52.204  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 17:37:52.204  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 17:37:52.204  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 17:37:52.205  6695  6799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:52.216  6695  8245 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
,08-26 17:37:52.216  6695  8245 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
08-26 17:37:52.216  6695  8245 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 17:37:52.219  6695  8246 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
,08-26 17:37:52.220  6695  8246 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
08-26 17:37:52.220  6695  8246 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 17:37:52.222  6695  6799 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 17:37:52.222  6695  6799 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-26 17:37:52.222  6695  6799 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 17:37:52.222  6695  6799 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 17:37:52.222  6695  6799 D com.test.thalitest.ThaliTestRunner: Total duration: 23973 ms
08-26 17:37:52.224  6695  6799 I jxcore-log: *Native tests were executed*
08-26 17:37:52.224  6695  6799 I jxcore-log: 
,08-26 17:37:52.224  6695  6799 I jxcore-log: Total number of executed tests:  80
08-26 17:37:52.224  6695  6799 I jxcore-log: 
08-26 17:37:52.224  6695  6799 I jxcore-log: Number of passed tests:  80
08-26 17:37:52.224  6695  6799 I jxcore-log: 
08-26 17:37:52.224  6695  6799 I jxcore-log: Number of failed tests:  0
08-26 17:37:52.224  6695  6799 I jxcore-log: 
,08-26 17:37:52.224  6695  6799 I jxcore-log: Number of ignored tests:  0
08-26 17:37:52.224  6695  6799 I jxcore-log: 
08-26 17:37:52.225  6695  6799 I jxcore-log: Total duration:  23973
08-26 17:37:52.225  6695  6799 I jxcore-log: 
08-26 17:37:52.225  6695  6799 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 17:37:52.225  6695  6799 I jxcore-log: 
,08-26 17:37:52.238  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.238  6695  6799 I jxcore-log: 
,08-26 17:37:52.241  6695  6695 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 17:37:52.242  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.242  6695  6799 I jxcore-log: 
08-26 17:37:52.243  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.243  6695  6799 I jxcore-log: 
08-26 17:37:52.244  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.244  6695  6799 I jxcore-log: 
08-26 17:37:52.245  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.245  6695  6799 I jxcore-log: 
08-26 17:37:52.247  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.247  6695  6799 I jxcore-log: 
08-26 17:37:52.250  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.250  6695  6799 I jxcore-log: 
08-26 17:37:52.252  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.252  6695  6799 I jxcore-log: 
08-26 17:37:52.253  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.253  6695  6799 I jxcore-log: 
08-26 17:37:52.254  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.254  6695  6799 I jxcore-log: 
08-26 17:37:52.255  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.255  6695  6799 I jxcore-log: 
08-26 17:37:52.256  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 17:37:52.256  6695  6799 I jxcore-log: 
,08-26 17:37:52.257  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.257  6695  6799 I jxcore-log: 
08-26 17:37:52.258  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.258  6695  6799 I jxcore-log: 
08-26 17:37:52.259  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.259  6695  6799 I jxcore-log: 
08-26 17:37:52.260  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.260  6695  6799 I jxcore-log: 
08-26 17:37:52.261  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.261  6695  6799 I jxcore-log: 
08-26 17:37:52.261  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.261  6695  6799 I jxcore-log: 
08-26 17:37:52.262  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.262  6695  6799 I jxcore-log: 
08-26 17:37:52.263  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.263  6695  6799 I jxcore-log: 
08-26 17:37:52.264  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.264  6695  6799 I jxcore-log: 
08-26 17:37:52.265  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.265  6695  6799 I jxcore-log: 
08-26 17:37:52.265  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.265  6695  6799 I jxcore-log: 
08-26 17:37:52.266  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.266  6695  6799 I jxcore-log: 
08-26 17:37:52.267  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.267  6695  6799 I jxcore-log: 
08-26 17:37:52.268  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.268  6695  6799 I jxcore-log: 
08-26 17:37:52.269  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.269  6695  6799 I jxcore-log: 
,08-26 17:37:52.270  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.270  6695  6799 I jxcore-log: 
08-26 17:37:52.270  6695  6799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.270  6695  6799 I jxcore-log: 
08-26 17:37:52.546  8249  8249 D AndroidRuntime: 
08-26 17:37:52.546  8249  8249 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 17:37:52.553  8249  8249 D AndroidRuntime: CheckJNI is OFF
08-26 17:37:52.750  1035  1540 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:52.750  1035  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:52.751  1035  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:52.751  1035  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:52.751  1035  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 17:37:52.752  1035  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 17:37:52.756  1035  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
,08-26 17:37:52.756  1035  1546 D ConnectivityService: identical MTU - not setting
08-26 17:37:52.756  1035  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 17:37:52.756  1035  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 17:37:52.756  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:52.757  1035  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:52.757  8249  8249 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 17:37:52.758  1035  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 17:37:52.759  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 17:37:52.767  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-26 17:37:52.768  1035  1092 I ActivityManager: Killing 6695:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-26 17:37:52.808  1035  1545 D WifiService: Client connection lost with reason: 4
08-26 17:37:52.808  1035  1896 I WindowState: WIN DEATH: Window{245eb6a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 17:37:52.815  1035  1896 D InputDispatcher: Window went away: Window{245eb6a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 17:37:52.889  1035  1092 I ActivityManager:   Force finishing activity ActivityRecord{171843c1 u0 com.test.thalitest/.MainActivity t6}
,08-26 17:37:52.927   338   346 E GBMv2   : DFP En is all cleared set to be enabled
,08-26 17:37:52.932  1035  1051 W ActivityManager: Spurious death for ProcessRecord{2f304122 6695:com.test.thalitest/u0a118}, curProc for 6695: null
08-26 17:37:52.944  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-26 17:37:52.946  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-26 17:37:52.948  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 17:37:52.949  1941  2937 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-26 17:37:52.949  1941  2937 D SplitWindowPolicy: topRunningActivity=ActivityInfo{76ec243 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 17:37:52.950  2033  2106 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-26 17:37:52.951  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 17:37:52.951  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2c2b50c0 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 17:37:52.955  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 17:37:52.958  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-26 17:37:52.958  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-26 17:37:52.960  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-26 17:37:52.961  3803  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-26 17:37:52.962  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 17:37:53.010  1035  1092 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8269 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 17:37:53.018  1035  1120 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-26 17:37:53.056  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-26 17:37:53.058  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-26 17:37:53.059  3803  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 17:37:53.063  1035  1456 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 17:37:53.068  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-26 17:37:53.087  7710  7710 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-26 17:37:53.087  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 17:37:53.087  3803  3803 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-26 17:37:53.088  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-26 17:37:53.091  3803  3818 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 17:37:53.124  4560  4560 I art     : Explicit concurrent mark sweep GC freed 8194(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 673us total 54.628ms
,08-26 17:37:53.131  4457  4457 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 17:37:53.131  2479  2632 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 17:37:53.131  4457  4457 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 17:37:53.131  4457  4457 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 17:37:53.132  4457  4457 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 17:37:53.132  4457  4457 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 17:37:53.132  4457  4457 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 17:37:53.132  4457  4457 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 17:37:53.132  4457  4457 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 17:37:53.132  4457  4457 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:53.132  4457  4457 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:53.132  4457  4457 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 17:37:53.132  4457  4457 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 17:37:53.139  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , display: false
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , animation: false }
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , display: false
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , animation: false }
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , create_time: 1472216588858
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , display: false
08-26 17:37:53.143  2033  2033 I GBoardWebViewUtils: , animation: false }
08-26 17:37:53.149  1604  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 17:37:53.149  1604  1662 D KeyguardModel: createShortcutInfo...
08-26 17:37:53.153  2033  8295 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-26 17:37:53.155  1604  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 17:37:53.155  1604  1662 D KeyguardModel: createShortcutInfo...
08-26 17:37:53.161  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-26 17:37:53.163  1035  1576 V SIM_STK : Menu title from STK is T-Mobile
,08-26 17:37:53.170  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 17:37:53.170  1604  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 17:37:53.171  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 17:37:53.171  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 17:37:53.171  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 17:37:53.171  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 17:37:53.174  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 17:37:53.174  1604  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 17:37:53.182  1604  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 17:37:53.182  1604  1662 D KeyguardModel: createShortcutInfo...
,08-26 17:37:53.186  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-26 17:37:53.193  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 17:37:53.193  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 17:37:53.194  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 17:37:53.194  1604  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-26 17:37:53.198  1604  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 17:37:53.198  1604  1662 D KeyguardModel: createShortcutInfo...
08-26 17:37:53.206  1604  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 17:37:53.206  1604  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 17:37:53.206  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 17:37:53.206  1604  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 17:37:53.208  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 17:37:53.208  1604  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-26 17:37:53.209  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-26 17:37:53.209  1869  1869 D SplitUIService: removed split : 
08-26 17:37:53.215  1604  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 17:37:53.215  1604  1662 D KeyguardModel: createShortcutInfo...
08-26 17:37:53.218  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-26 17:37:53.218  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 17:37:53.219  1035  2016 V SIM_STK : Menu title from STK is T-Mobile
08-26 17:37:53.219  1035  2016 V SIM_STK : Menu title from STK is T-Mobile
08-26 17:37:53.220  1604  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 17:37:53.221  1604  1662 D KeyguardModel: createShortcutInfo...
,08-26 17:37:53.227  1604  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 17:37:53.227  1604  1662 D KeyguardModel: createShortcutInfo...
08-26 17:37:53.231  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 17:37:53.231  1604  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 17:37:53.233  1604  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 17:37:53.233  1604  1662 D KeyguardModel: createShortcutInfo...
08-26 17:37:53.236  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 17:37:53.236  1604  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-26 17:37:53.239  1604  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 17:37:53.239  1604  1662 D KeyguardModel: createShortcutInfo...
08-26 17:37:53.242  1604  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 17:37:53.242  1604  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 17:37:53.243  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-26 17:37:53.243  1869  1869 I SplitUIService: split app #11
08-26 17:37:53.244  1604  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 17:37:53.244  1604  1662 D KeyguardModel: createShortcutInfo...
08-26 17:37:53.255  1035  1035 D administrator: Handling package changes for user 0
08-26 17:37:53.258  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 17:37:53.260  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-26 17:37:53.275  1035  1990 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
,08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 17:37:53.275  7710  7710 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 17:37:53.285  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-26 17:37:53.285  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 17:37:53.288  1035  1962 V SIM_STK : Menu title from STK is T-Mobile
08-26 17:37:53.299  8269  8269 I art     : Almond Protected OAT
,08-26 17:37:53.310  7638  8039 D UEI.SmartControl: Internal timer expired: 2
08-26 17:37:53.310  7638  8039 D UEI.SmartControl: unbind internal service
08-26 17:37:53.342  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-26 17:37:53.344  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 17:37:53.346  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 17:37:53.347  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 17:37:53.348  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 17:37:53.349  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 17:37:53.353  8269  8269 D WeatherApplication: removeAccount
08-26 17:37:53.354  8269  8269 D WeatherApplication: Account.length = 0
08-26 17:37:53.354  8269  8269 E WeatherApplication: OPERATOR:OPEN
08-26 17:37:53.357  8269  8269 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 17:37:53
08-26 17:37:53.363  8269  8269 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 17:37:53.363  8269  8269 D Weather.Utils: 2 : All the weather widget is gone.
,08-26 17:37:53.364   330   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-26 17:37:53.364  3224  8300 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-26 17:37:53.366  1035  1100 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3f7f60fa u0 com.lge.launcher2/.Launcher t5} time:141408
08-26 17:37:53.374  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 17:37:53.375  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 17:37:53.378  2033  2158 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 17:37:53.378  2033  2158 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-26 17:37:53.378  8269  8269 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 17:37:53.386  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 17:37:53.386  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 17:37:53.386  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 17:37:53.388  8269  8269 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 17:37:53.388  8269  8269 D Weather.Utils: 2 : All the weather widget is gone.
08-26 17:37:53.388  8269  8269 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 17:37:53
,08-26 17:37:53.389  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-26 17:37:53.390  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 17:37:53.390  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 17:37:53.391  1035  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 17:37:53.392  8149  8149 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-26 17:37:53.398  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-26 17:37:53.399  2623  2623 D [Concierge]Service: onStartCommand(). Type : 8
08-26 17:37:53.399  2623  2623 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 17:37:53.399  2623  2623 D [Concierge]Service: Update widget ID : 11
,08-26 17:37:53.401  2033  2033 D [Concierge]WidgetView: change position of spinner
08-26 17:37:53.402  2623  2623 D [Concierge]Service: onStartCommand(). Type : 0
08-26 17:37:53.403  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1472225873403
08-26 17:37:53.409  1035  1785 I ActivityManager: Killing 7738:com.google.android.talk/u0a72 (adj 15): empty #17
08-26 17:37:53.441  1035  1120 I art     : Explicit concurrent mark sweep GC freed 80330(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.454ms total 285.234ms
,08-26 17:37:53.456  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 17:37:53.462  8249  8249 D AndroidRuntime: Shutting down VM
08-26 17:37:53.463  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-26 17:37:53.498  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-26 17:37:53.498  1035  2016 W libprocessgroup: failed to open /acct/uid_10072/pid_7738/cgroup.procs: No such file or directory
,08-26 17:37:53.505  2208  2208 I ConfigService: onCreate
08-26 17:37:53.505  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-26 17:37:53.507  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-26 17:37:53.508  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1033680074
08-26 17:37:53.509  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-26 17:37:53.509  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 17:37:53.510  2208  2208 I ConfigService: onBind returning update interface
08-26 17:37:53.510  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 17:37:53.510  2208  2208 I ConfigService: onBind returning config service
,08-26 17:37:53.511  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@b700ad8
08-26 17:37:53.512  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 17:37:53.513  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 17:37:53.513  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 17:37:53.517  2208  2208 I ConfigService: onDestroy
08-26 17:37:53.518  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 17:37:53.518  7638  8036 D serial_port: close(fd = 24)
08-26 17:37:53.518  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 17:37:53.518  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 17:37:53.519  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472225760389, New one : 1472225873403
08-26 17:37:53.519  2033  2033 D [Concierge]WidgetView: Unregister all receivers
08-26 17:37:53.519  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 17:37:53.520  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 17:37:53.520  1817  8306 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-26 17:37:53.521  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 17:37:53.523  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 17:37:53.524  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-26 17:37:53.525  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-26 17:37:53.526  7638  8036 I UEI.SmartControl: Serial port is closed.
08-26 17:37:53.527  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 17:37:53.528  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 17:37:53.529  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 17:37:53.529  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 17:37:53.540  5975  8311 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-26 17:37:53.554  7073  7073 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-26 17:37:53.560  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-26 17:37:53.568  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 17:37:53.568  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-26 17:37:53.568  1817  8313 I PeopleContactsSync: CP2 sync disabled
08-26 17:37:53.569  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 17:37:53.577  2354  8314 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-26 17:37:53.590  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4e4af4 time:141633
,08-26 17:37:53.597  1035  1050 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8316 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-26 17:37:53.604  1817  4749 I Icing   : doRemovePackageData com.test.thalitest
,08-26 17:37:53.609  1817  8312 W GmsApplication: Using Auth Proxy for data requests.
08-26 17:37:53.613  1817  8312 W GmsApplication: Using Auth Proxy for data requests.
,08-26 17:37:53.634  8316  8316 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 17:37:53.634  8316  8316 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 17:37:53.635  8316  8316 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 17:37:53.635  8316  8316 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 17:37:53.656  2208  2347 I art     : Explicit concurrent mark sweep GC freed 6125(367KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 529us total 23.700ms
,08-26 17:37:53.706  1035  1120 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8334 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 17:37:53.709  8316  8316 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-26 17:37:53.719  8316  8316 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 17:37:53.747  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-26 17:37:53.751  1035  1921 I ActivityManager: Killing 7815:com.android.gallery3d/u0a27 (adj 15): empty #17
08-26 17:37:53.755  8316  8316 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 17:37:53.786  2033  2940 I GBoardtInterface: onReloaded()

```
