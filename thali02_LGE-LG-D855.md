#### Test 83268893a5a5a53_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 15:44:36.589  6522  6522 D DocsApplication: Installing DEX configuration.
08-30 15:44:36.608  6522  6522 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-30 15:44:36.612  6522  6522 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2dccee9c com.google.android.apps.docs}
08-30 15:44:36.632  6522  6522 D TAG     : onCreate()
08-30 15:44:36.658  6522  6522 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 15:44:37.191   330   413 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 15:44:37.195  3221  6551 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 15:44:37.471  1815  4754 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-30 15:44:37.640  1815  4754 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 15:44:37.715  1815  4754 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-30 15:44:37.787  6552  6552 D AndroidRuntime: 
08-30 15:44:37.787  6552  6552 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 15:44:37.790  6552  6552 D AndroidRuntime: CheckJNI is OFF
08-30 15:44:37.923  6552  6552 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 15:44:37.928  1034  1574 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 15:44:37.961  1940  3989 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 15:44:37.966  1034  1574 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 15:44:37.968  1034  1574 D ActivityManager: setTaskToReturnTo : TaskRecord{26268269 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 15:44:37.968  1034  1574 D ActivityManager: setTaskToReturnTo : TaskRecord{26268269 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 15:44:37.969  1034  1574 D WindowStateEx: AppWindowTokenEx init.. 
08-30 15:44:37.970   341   347 E GBMv2   : DFP En is all cleared set to be enabled
08-30 15:44:38.043  1034  1574 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6587 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 15:44:38.045  6552  6552 D AndroidRuntime: Shutting down VM
08-30 15:44:38.091  1940  3989 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 15:44:38.091  1940  3989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{112432d8 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 15:44:38.092  1940  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 15:44:38.092  1940  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ef7a631 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 15:44:38.145  6587  6587 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 15:44:38.223  6587  6587 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 15:44:38.230  6587  6587 I LibraryLoader: Loading: webviewchromium
08-30 15:44:38.233  6587  6587 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3688-3691)
08-30 15:44:38.233  6587  6587 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:44:38.246  6587  6587 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {159a3646}
08-30 15:44:38.247  6587  6587 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:44:38.247  6587  6587 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 15:44:38.256  6587  6587 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 15:44:38.256  6587  6587 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:44:38.265  6587  6587 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 15:44:38.266  6587  6587 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-30 15:44:38.266  6587  6587 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 15:44:38.271   314  2149 V AudioPolicyService: registerClient() client 0xb101af00, uid 10118
,08-30 15:44:38.285  1034  1096 D BluetoothManagerService: Message: 20
,08-30 15:44:38.285  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1121a3ab:true
08-30 15:44:38.294  6587  6587 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:44:38.294  6587  6587 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:44:38.294  6587  6587 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:44:38.294  6587  6587 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:44:38.294  6587  6587 I Adreno-EGL: Remote Branch: 
08-30 15:44:38.294  6587  6587 I Adreno-EGL: Local Patches: 
08-30 15:44:38.294  6587  6587 I Adreno-EGL: Reconstruct Branch: 
08-30 15:44:38.352  6522  6522 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:44:38.352  6522  6522 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:44:38.357  6587  6616 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-30 15:44:38.358  6587  6587 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 15:44:38.372  6587  6587 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:44:38.375  6587  6587 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 15:44:38.378  6587  6587 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 15:44:38.380  6587  6587 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 15:44:38.380  6587  6587 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 15:44:38.391  6587  6587 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 15:44:38.397  6587  6587 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 15:44:38.397  6587  6587 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:44:38.435  6587  6630 D OpenGLRenderer: Render dirty regions requested: true
08-30 15:44:38.435  6587  6630 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 15:44:38.445  6587  6630 D OpenGLRenderer: Enabling debug mode 0
,08-30 15:44:38.454  6587  6587 D Atlas   : Validating map...
08-30 15:44:38.458  1034  1957 D SplitWindow: check instance of lgWin Window{2b80c54d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 15:44:38.495  6085  6085 I LockScreenSettings: New app installed broadcast received ..
,08-30 15:44:38.497  6085  6085 I LockScreenSettings: Number of installed packages  1
08-30 15:44:38.498  6587  6628 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:44:38.498  6587  6628 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:44:38.517  6522  6522 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-30 15:44:38.552  1034  1884 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:44:38.585  6587  6587 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@345669cd time:104044
,08-30 15:44:38.601  1034  1921 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6646 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 15:44:38.604  1034  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +515ms (total +633ms)
08-30 15:44:38.605  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{57b4ee u0 com.test.thalitest/.MainActivity t6} time:104063
,08-30 15:44:38.667  6646  6646 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-30 15:44:38.667  6646  6646 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-30 15:44:38.705  1034  1992 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6667 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 15:44:38.707  1034  1992 I ActivityManager: Killing 5752:com.google.android.gm/u0a64 (adj 15): empty #17
08-30 15:44:38.731  6587  6587 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 15:44:38.816  1034  1957 W libprocessgroup: failed to open /acct/uid_10064/pid_5752/cgroup.procs: No such file or directory
08-30 15:44:38.840  6587  6684 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-30 15:44:38.853  6587  6684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 15:44:38.853  6587  6684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 15:44:38.853  6587  6684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 15:44:38.853  6587  6684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 15:44:38.853  6587  6684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 15:44:38.853  6587  6684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de47501 added. We now have 1 listener(s)
08-30 15:44:38.858  1034  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:44:38.861  6587  6684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 15:44:38.862  6587  6684 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:44:38.863  6587  6684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:44:38.863  6587  6684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 15:44:38.871  6587  6684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f49d94 added. We now have 1 listener(s)
08-30 15:44:38.871  6587  6684 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:44:38.876  1034  1404 D WifiService: New client listening to asynchronous messages
08-30 15:44:38.879  6587  6684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:44:38.879  6587  6684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 15:44:38.879  6587  6684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 15:44:38.879  6587  6684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 15:44:38.879  6587  6684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 15:44:38.885  6587  6684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:38.886  1034  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:44:38.886  6587  6684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 15:44:38.894  6587  6684 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 15:44:38.895  6587  6684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:38.895  6587  6684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:38.895  6587  6684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:38.895  6587  6684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:38.895  6587  6684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:38.895  6587  6684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:38.895  6587  6684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:38.895  6587  6684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:38.895  6587  6684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 15:44:38.895  6587  6684 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:44:38.896  6587  6684 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 15:44:38.897  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:38.898  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:38.909  6667  6667 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-30 15:44:38.933  6667  6667 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 15:44:38.933  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-30 15:44:38.934  6587  6628 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 15:44:38.934  6587  6628 I chromium: 
,08-30 15:44:38.960  6390  6390 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-30 15:44:38.960  1034  1885 I ActivityManager: Killing 5599:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 15:44:38.977  5576  5576 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-30 15:44:38.978  5576  5576 W System.err: android.os.DeadObjectException
08-30 15:44:38.979  5576  5576 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 15:44:38.979  5576  5576 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 15:44:38.979  5576  5576 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 15:44:38.979  5576  5576 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 15:44:38.979  5576  5576 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 15:44:38.979  5576  5576 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 15:44:38.979  5576  5576 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:44:38.979  5576  5576 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:44:38.979  5576  5576 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:44:38.979  5576  5576 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:44:38.979  5576  5576 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:38.979  5576  5576 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:38.979  5576  5576 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:44:38.979  5576  5576 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:44:38.979  5576  5576 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 15:44:38.980  5576  5576 W System.err: android.os.DeadObjectException
08-30 15:44:38.980  5576  5576 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 15:44:38.980  5576  5576 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 15:44:38.980  5576  5576 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 15:44:38.980  5576  5576 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 15:44:38.980  5576  5576 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 15:44:38.980  5576  5576 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 15:44:38.980  5576  5576 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:44:38.980  5576  5576 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:44:38.980  5576  5576 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:44:38.980  5576  5576 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:44:38.980  5576  5576 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:38.980  5576  5576 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:38.980  5576  5576 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:44:38.980  5576  5576 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:44:38.981  5576  5576 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 15:44:38.982  5576  5576 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 15:44:39.010  6587  6587 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 15:44:39.098  6587  6587 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 15:44:39.098  6587  6587 I chromium: 
,08-30 15:44:39.244  1034  1921 W libprocessgroup: failed to open /acct/uid_1000/pid_5599/cgroup.procs: No such file or directory
08-30 15:44:39.244  1034  1921 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 15:44:39.250  5576  5576 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 15:44:39.250  5576  5576 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 15:44:39.305  1034  1575 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6690 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 15:44:39.306  5576  5576 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 15:44:39.362   341   349 E GBMv2   : DFP En is all cleared set to be enabled
08-30 15:44:39.362   341   349 E GBMv2   : Set value is all cleared set the max
08-30 15:44:39.362   341   349 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 15:44:39.392  6690  6690 D UEI.SmartControl: Quickset Services start...
08-30 15:44:39.397  6690  6690 I UEI.SmartControl: Manufacture = LGE
08-30 15:44:39.397  6690  6690 D UEI.SmartControl: Id = LGNevo
,08-30 15:44:39.400  6690  6690 D UEI.SmartControl: File observer start...
08-30 15:44:39.401  6690  6690 E UEI.SmartControl: IR Port is disabled: false
08-30 15:44:39.401  6690  6690 D UEI.SmartControl: Starting file observer...
08-30 15:44:39.403  6690  6690 D UEI.SmartControl: Extracting JNI libs...
08-30 15:44:39.404  6690  6690 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 15:44:39.501  6690  6690 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 15:44:39.501  6690  6690 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 15:44:39.501  6690  6690 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 15:44:39.538  6690  6690 I UEI.SmartControl: --- Selecting new region: 6
,08-30 15:44:39.541  6690  6690 I UEI.SmartControl: Model = LG-D855
08-30 15:44:39.543  6690  6690 D UEI.SmartControl: QS Service created
08-30 15:44:39.560  6690  6690 I UEI.SmartControl: Service initServices...
,08-30 15:44:39.565  6690  6690 D UEI.SmartControl: QS start get config
08-30 15:44:39.614  6690  6690 D UEI.SmartControl: Loading JNI Libs...
,08-30 15:44:39.900  2789  2789 I MusicWidget: mDelayedStopHandler : unbind
08-30 15:44:39.906  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,08-30 15:44:39.907  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-30 15:44:39.907  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-30 15:44:39.912  2131  2131 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-30 15:44:39.915  2131  2131 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-30 15:44:39.916  6587  6687 W jxcore-log: Initializing JXcore engine
08-30 15:44:39.916  6587  6687 W jxcore-log: JXcore engine is ready
08-30 15:44:39.916  2131  2131 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-30 15:44:39.920  2131  2131 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-30 15:44:39.920  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-30 15:44:39.932  1034  1574 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@38198f7com.lge.music.MediaPlaybackService$5@d39364
,08-30 15:44:39.933  2131  2131 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-30 15:44:39.934  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.935  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.942  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.943  2131  2131 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@203370d2
,08-30 15:44:39.943  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.944  2131  2131 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-30 15:44:39.944  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.945  2131  2131 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-30 15:44:39.945  2131  2131 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-30 15:44:39.945  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.946  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.951  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.952  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.952  2131  2131 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 15:44:39.953  2131  2131 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-30 15:44:39.956  2131  2131 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-30 15:44:39.956  2131  2131 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-30 15:44:39.956  2131  2131 V MediaPlayer[Native]: reset
08-30 15:44:39.962  2131  2131 V MediaPlayer[Native]: setListener
08-30 15:44:39.962  2131  2131 V MediaPlayer[Native]: disconnect
08-30 15:44:39.962  2131  2131 V MediaPlayer[Native]: destructor
08-30 15:44:39.963   314  2148 V AudioFlinger: releasing 16 from 2131 for -1
08-30 15:44:39.963   314  2148 V AudioFlinger:  decremented refcount to 0
08-30 15:44:39.963   314  2148 V AudioFlinger: purging stale effects
08-30 15:44:39.959  6687  6687 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9276]" dev="sockfs" ino=9276 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 15:44:39.963  2131  2131 V MediaPlayer[Native]: disconnect
08-30 15:44:39.959  6687  6687 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 15:44:39.959  6687  6687 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9503]" dev="sockfs" ino=9503 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 15:44:39.959  6687  6687 W Thread-757: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 15:44:39.959  6687  6687 W Thread-757: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31955]" dev="sockfs" ino=31955 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 15:44:39.964  2131  2131 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-30 15:44:39.970  2131  2131 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-30 15:44:39.970  2131  2131 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-30 15:44:39.973  2131  2131 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-30 15:44:39.974  6587  6687 W jxcore-log: Starting JXcore engine
08-30 15:44:39.974  2131  2131 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-30 15:44:39.974  2131  2131 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-30 15:44:39.975  2131  2131 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 878078413
08-30 15:44:39.976  2131  2131 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 878078413
,08-30 15:44:39.984  2131  2131 I SmartShareClient: [SmartShareManagerClient] terminate service: 2131/MediaPlaybackService/721967240
08-30 15:44:39.988  2131  2131 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-30 15:44:39.988  2131  2131 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3e95b282
08-30 15:44:39.992  2131  2131 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-30 15:44:39.993  2131  2131 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-30 15:44:39.993  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-30 15:44:39.994  2131  2131 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,08-30 15:44:39.998  1034  1575 I ActivityManager: Killing 5576:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 15:44:40.001  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
08-30 15:44:40.060  6587  6687 W jxcore-log: Platform android
08-30 15:44:40.060  6587  6687 W jxcore-log: 
,08-30 15:44:40.060  6587  6687 W jxcore-log: Process ARCH arm
08-30 15:44:40.060  6587  6687 W jxcore-log: 
08-30 15:44:40.069  6690  6690 I UEI.SmartControl: Supports setup maps: true
08-30 15:44:40.074  6690  6690 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 15:44:40.074  6690  6690 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 15:44:40.074  6690  6690 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 15:44:40.074  6690  6690 I UEI.SmartControl: ### init IR Blaster...
08-30 15:44:40.079  6690  6690 D serial_port: Configuring serial port
08-30 15:44:40.081  1034  2031 W libprocessgroup: failed to open /acct/uid_10112/pid_5576/cgroup.procs: No such file or directory
08-30 15:44:40.088  6690  6690 E UEI.SmartControl: UEIBLaster setting for 616
,08-30 15:44:40.088  6690  6690 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 15:44:40.090  6690  6690 I UEI.SmartControl: configuring settings for MAXQ616
08-30 15:44:40.090  6690  6690 I UEI.SmartControl: Get version...
08-30 15:44:40.108  6690  6713 D UEI.SmartControl: serial port data available: 21
,08-30 15:44:40.136  6690  6690 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 15:44:40.137  6690  6690 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 15:44:40.137  6690  6690 I UEI.SmartControl: QS saving settings...
08-30 15:44:40.139  6690  6690 D UEI.SmartControl: IR Blaster version: 25672567
08-30 15:44:40.157  6690  6713 D UEI.SmartControl: serial port data available: 4
,08-30 15:44:40.196  6690  6717 I UEI.SmartControl: Device manager: loading config....
08-30 15:44:40.197  6690  6717 D UEI.SmartControl: ----------- loading internal config...
,08-30 15:44:40.208  6690  6690 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 15:44:40.214  6690  6690 E UEI.SmartControl: Services init done
,08-30 15:44:40.215  6690  6690 D UEI.SmartControl: QS Service init finished
08-30 15:44:40.215  6690  6690 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 15:44:40.215  6690  6690 D UEI.SmartControl: QS Service version code: 201091
08-30 15:44:40.216  6690  6690 D UEI.SmartControl: Service requested: Control
08-30 15:44:40.222  6690  6690 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 15:44:40.223  6690  6690 D UEI.SmartControl: Service.onUnbind: IControl
08-30 15:44:40.223  6690  6717 E UEI.SmartControl: Loading SETTINGS...
08-30 15:44:40.224  6690  6690 D UEI.SmartControl: Service.onDestroy
08-30 15:44:40.224  6690  6690 D UEI.SmartControl: Lock is in USE false
08-30 15:44:40.224  6690  6690 D UEI.SmartControl: unbind internal service
08-30 15:44:40.226  6690  6690 D serial_port: close(fd = 25)
08-30 15:44:40.229  6690  6690 I UEI.SmartControl: Serial port is closed.
08-30 15:44:40.229  6690  6690 I UEI.SmartControl: Serial port is closed.
08-30 15:44:40.230  6690  6690 D UEI.SmartControl: Blaster closed
08-30 15:44:40.230  6690  6690 D UEI.SmartControl: Shut down QS...
08-30 15:44:40.230  6690  6690 D UEI.SmartControl: Stopping QS lib
08-30 15:44:40.230  6690  6716 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 15:44:40.230  6690  6716 D UEI.SmartControl: -----service ready thread exits
08-30 15:44:40.231  6690  6690 D UEI.SmartControl: QS lib stop result = true
08-30 15:44:40.231  6690  6690 D UEI.SmartControl: Stopped QS lib
,08-30 15:44:40.231  6690  6690 D UEI.SmartControl: Stopped file observer...
08-30 15:44:40.231  6690  6690 D UEI.SmartControl: QS shutdown complete
08-30 15:44:40.234  6690  6690 D UEI.SmartControl: QS Service created
08-30 15:44:40.240  6690  6717 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 15:44:40.247  6587  6687 I jxcore-log: JXcore Cordova bridge is ready!
08-30 15:44:40.247  6587  6687 I jxcore-log: 
08-30 15:44:40.247  6587  6687 W jxcore-log: JXcore engine is started
,08-30 15:44:40.253  6690  6690 I UEI.SmartControl: Service initServices...
08-30 15:44:40.253  6690  6690 D UEI.SmartControl: QS start get config
08-30 15:44:40.254  6587  6684 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 15:44:40.257  6587  6587 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 15:44:40.540  6690  6690 I UEI.SmartControl: Supports setup maps: true
,08-30 15:44:40.543  6690  6690 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 15:44:40.543  6690  6690 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 15:44:40.543  6690  6690 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 15:44:40.543  6690  6690 I UEI.SmartControl: ### init IR Blaster...
08-30 15:44:40.547  6690  6690 D serial_port: Configuring serial port
08-30 15:44:40.547  6690  6690 E UEI.SmartControl: UEIBLaster setting for 616
08-30 15:44:40.547  6690  6690 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 15:44:40.547  6690  6690 I UEI.SmartControl: configuring settings for MAXQ616
08-30 15:44:40.547  6690  6690 I UEI.SmartControl: Get version...
08-30 15:44:40.570  6690  6723 D UEI.SmartControl: serial port data available: 21
,08-30 15:44:40.601  6690  6690 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 15:44:40.601  6690  6690 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 15:44:40.601  6690  6690 I UEI.SmartControl: QS saving settings...
08-30 15:44:40.602  6690  6690 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 15:44:40.630  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 6709
08-30 15:44:40.630  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 6710
08-30 15:44:40.631  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 6712
,08-30 15:44:40.632  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 6714
08-30 15:44:40.633  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 6720
08-30 15:44:40.634  6690  6723 D UEI.SmartControl: serial port data available: 4
08-30 15:44:40.661  6690  6690 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 15:44:40.665  6690  6690 E UEI.SmartControl: Services init done
08-30 15:44:40.665  6690  6690 D UEI.SmartControl: QS Service init finished
08-30 15:44:40.665  6690  6690 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 15:44:40.665  6690  6690 D UEI.SmartControl: QS Service version code: 201091
08-30 15:44:40.666  6690  6690 D UEI.SmartControl: Service requested: Control
08-30 15:44:40.667  1034  1575 I ActivityManager: Killing 5794:com.google.android.talk/u0a72 (adj 15): empty #17
08-30 15:44:40.683  6690  6729 I UEI.SmartControl: Device manager: loading config....
08-30 15:44:40.683  6690  6729 D UEI.SmartControl: ----------- loading internal config...
08-30 15:44:40.685  6690  6729 E UEI.SmartControl: Loading SETTINGS...
,08-30 15:44:40.688  6690  6729 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 15:44:40.703  6690  6728 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 15:44:40.703  6690  6728 D UEI.SmartControl: -----service ready thread exits
,08-30 15:44:40.752  1034  2031 W libprocessgroup: failed to open /acct/uid_10072/pid_5794/cgroup.procs: No such file or directory
08-30 15:44:40.762  6690  6690 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@203370d2 that was originally bound here
08-30 15:44:40.762  6690  6690 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@203370d2 that was originally bound here
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:44:40.762  6690  6690 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:44:40.762  6690  6690 D UEI.SmartControl: Internal service binding...
,08-30 15:44:41.224  6690  6719 D UEI.SmartControl: Internal timer expired: 2
,08-30 15:44:42.435  6522  6522 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-30 15:44:42.443  1034  1992 I ActivityManager: Killing 6214:com.android.calendar/u0a13 (adj 15): empty #17
08-30 15:44:42.504  1034  1575 W libprocessgroup: failed to open /acct/uid_10013/pid_6214/cgroup.procs: No such file or directory
,08-30 15:44:43.426  6522  6624 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 15:44:44.378  6690  6701 E UEI.SmartControl: file observer is disposed!
,08-30 15:44:45.660  6690  6730 D UEI.SmartControl: Internal timer expired: 3
08-30 15:44:45.660  6690  6730 D UEI.SmartControl: unbind internal service
,08-30 15:44:45.671  6690  6690 D UEI.SmartControl: Service.onUnbind: IControl
08-30 15:44:45.671  6690  6690 D UEI.SmartControl: Service.onDestroy
08-30 15:44:45.671  6690  6690 D UEI.SmartControl: Lock is in USE false
08-30 15:44:45.671  6690  6690 D UEI.SmartControl: unbind internal service
08-30 15:44:45.672  6690  6690 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@ebcad15
08-30 15:44:45.673  6690  6690 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 15:44:45.673  6690  6690 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 15:44:45.673  6690  6690 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 15:44:45.673  6690  6690 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 15:44:45.673  6690  6690 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 15:44:45.673  6690  6690 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 15:44:45.673  6690  6690 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 15:44:45.674  6690  6690 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 15:44:45.674  6690  6690 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:44:45.674  6690  6690 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:44:45.674  6690  6690 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:44:45.674  6690  6690 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:44:45.674  6690  6690 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:44:45.674  6690  6690 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:44:45.674  6690  6690 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:44:45.674  6690  6690 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@ebcad15
08-30 15:44:45.678  6690  6727 D serial_port: close(fd = 24)
,08-30 15:44:45.688  6690  6727 I UEI.SmartControl: Serial port is closed.
08-30 15:44:45.690  6690  6690 I UEI.SmartControl: Serial port is closed.
08-30 15:44:45.690  6690  6690 I UEI.SmartControl: Serial port is closed.
08-30 15:44:45.690  6690  6690 D UEI.SmartControl: Blaster closed
08-30 15:44:45.690  6690  6690 D UEI.SmartControl: Shut down QS...
08-30 15:44:45.690  6690  6690 D UEI.SmartControl: Stopping QS lib
08-30 15:44:45.690  6690  6690 D UEI.SmartControl: QS lib stop result = true
08-30 15:44:45.690  6690  6690 D UEI.SmartControl: Stopped QS lib
08-30 15:44:45.690  6690  6690 D UEI.SmartControl: QS shutdown complete
,08-30 15:44:50.002  2131  2131 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19992
,08-30 15:44:50.770  1034  1092 I ActivityManager: Waited long enough for: ServiceRecord{5c9c351 u0 com.google.android.gms/.wearable.service.WearableService}
,08-30 15:44:51.403  1034  1379 V AlarmManager: RTC_WAKEUP set : Alarm{2ec3ed44 type 0 when 1472564691245 com.android.vending} when 1472564691245
,08-30 15:44:51.578  1034  1751 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:44:51.593  4490  6754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-30 15:44:51.746  6045  6045 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 15:44:53.453  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 15:44:53.453  6587  6687 I jxcore-log: 
08-30 15:44:53.455  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 15:44:53.455  6587  6687 I jxcore-log: 
,08-30 15:44:53.463  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:53.463  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:53.463  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:53.463  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:53.463  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:53.463  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:53.463  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:53.463  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:53.466  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:53.469  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 15:44:53.469  6587  6687 I jxcore-log: 
,08-30 15:44:53.471  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 15:44:53.471  6587  6687 I jxcore-log: 
08-30 15:44:53.977  6587  6687 D executeNativeTests: Running unit tests
,08-30 15:44:54.061  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:44:54.061  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 added. We now have 2 listener(s)
,08-30 15:44:54.062  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:44:54.067  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:44:54.068  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:44:54.068  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:44:54.068  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:44:54.068  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 added. We now have 2 listener(s)
08-30 15:44:54.068  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:44:54.068  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:44:54.073  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:54.078  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:54.078  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.078  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.078  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:54.078  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:54.078  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.078  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:54.078  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:44:54.079  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.079  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:44:54.080  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.082  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:54.084  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:44:54.085  6587  6687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:44:54.085  6587  6687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:44:54.086  6587  6687 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 15:44:54.089  6587  6687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
,08-30 15:44:54.089  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-30 15:44:54.089  6587  6687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:44:54.089  6587  6687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-30 15:44:54.090  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:44:54.090  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:44:54.090  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:44:54.091  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-30 15:44:54.091  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:44:54.091  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:44:54.091  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 15:44:54.091  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 removed from the list
08-30 15:44:54.091  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.091  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 removed from the list
08-30 15:44:54.092  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.092  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.092  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.092  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.093  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.093  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.093  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.093  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.095  6587  6687 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 15:44:54.096  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.096  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.096  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.096  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.096  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.096  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.096  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
,08-30 15:44:54.096  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.096  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.096  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.096  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.096  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.096  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.096  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.097  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.097  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.097  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:44:54.097  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.103  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 15:44:54.103  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:44:54.103  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAll,OutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:44:54.104  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:44:54.104  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.104  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.104  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.104  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.104  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.104  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.104  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.104  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.105  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.105  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.105  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.105  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.105  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.105  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.106  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.106  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.106  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.106  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.106  6587  6687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:44:54.107  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:54.109  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:54.109  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.109  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.109  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:54.109  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:54.109  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.109  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:54.109  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:54.110  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.110  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:44:54.112  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.113  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.114  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:44:54.114  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:44:54.114  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:44:54.114  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:54.114  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:44:54.117  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:44:54.117  1034  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:44:54.121  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:44:54.124  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 15:44:54.125  6587  6687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 15:44:54.126  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:44:54.127  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:54.128  6587  6687 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:44:54.128  6587  6687 I io.jxcore.node.ConnectionHelper: start: OK
08-30 15:44:54.130  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.130  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.130  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.130  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.131  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.131  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:54.131  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.131  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.131  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.131  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.131  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.131  6587  6687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:44:54.201  1034  1885 I art     : Explicit concurrent mark sweep GC freed 23393(1199KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.499ms total 69.116ms
08-30 15:44:54.203  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:54.204  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:54.204  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.204  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.204  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:54.204  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:54.204  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.204  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:54.204  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:54.205  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.205  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:44:54.206  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:54.207  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.207  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:44:54.207  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:44:54.207  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:44:54.207  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:54.207  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:44:54.210  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:44:54.210  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:54.211  6587  6687 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:44:54.211  6587  6687 I io.jxcore.node.ConnectionHelper: start: OK
08-30 15:44:54.213  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.213  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.213  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.213  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.213  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.213  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:54.213  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.213  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.213  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.213  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.213  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.214  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.214  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.214  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.214  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.216  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.216  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.216  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.216  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thalipr,oject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.216  6587  6687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:44:54.218  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:44:54.226  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:54.226  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.226  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.226  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:54.226  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:44:54.226  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.226  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:54.226  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:54.226  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.227  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:44:54.227  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:44:54.227  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:44:54.227  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:44:54.227  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:54.227  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:44:54.229  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.230  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.232  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:44:54.232  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:54.233  6587  6687 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:44:54.233  6587  6687 I io.jxcore.node.ConnectionHelper: start: OK
08-30 15:44:54.233  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.233  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.233  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.234  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.234  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.234  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.234  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.234  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probab,ly already removed
08-30 15:44:54.234  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:44:54.234  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.234  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.234  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.234  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.234  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.234  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.234  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.235  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.235  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.235  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.235  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.235  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.235  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.236  6587  6687 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 15:44:54.236  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.236  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.236  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.236  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.236  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.236  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.236  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.236  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.236  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.236  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.236  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.236  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.236  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.237  6587  6687 D ,org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.239  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.239  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.239  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.239  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.239  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.239  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.240  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 15:44:54.240  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.240  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.240  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.241  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.241  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.241  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.241  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.241  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.241  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.241  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.241  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.241  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.241  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.241  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.241  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.242  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.242  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.242  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.242  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.242  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.242  6587  6687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 15:44:54.243  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.243  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.243  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.243  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.243  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.243  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.243  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.243  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.243  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.243  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.243  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.243  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.243  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.243  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.244  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.244  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.244  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.244  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.244  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.244  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.245  6587  6687 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 15:44:54.245  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.245  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.245  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.245  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.245  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.245  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.245  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.245  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.245  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.245  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.245  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.245  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.245  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.245  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.247  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.247  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.248  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.248  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.248  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.248  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.248  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:44:54.249  6587  6687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:44:54.249  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:44:54.249  6587  6687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:44:54.249  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:44:54.249  6587  6687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:44:54.249  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.249  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.249  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.249  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.249  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.249  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.249  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.249  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.249  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.249  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.249  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.249  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.250  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.250  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.253  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.253  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.256  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.256  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.256  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.256  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.257  6587  6687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:54.257  6587  6687 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:44:54.257  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 15:44:54.260  6587  6687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:54.260  6587  6687 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:44:54.261  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:44:54.262  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:44:54.262  6587  6687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 15:44:54.262  6587  6687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:44:54.262  6587  6687 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 15:44:54.262  6587  6687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:54.262  6587  6687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:44:54.263  6587  6687 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 15:44:54.263  6587  6687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:54.263  6587  6687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:44:54.263  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 15:44:54.265  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 15:44:54.266  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 15:44:54.266  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 15:44:54.267  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 15:44:54.267  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 15:44:54.267  6587  6687 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 15:44:54.267  6587  6687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:44:54.267  6587  6687 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-30 15:44:54.268  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.268  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.268  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.268  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.268  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.268  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.268  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 15:44:54.270  6587  6785 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-30 15:44:54.271  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.271  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.271  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.271  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.271  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.271  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.271  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.271  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.273  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.273  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.273  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.273  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.273  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.273  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.274  6587  6687 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 15:44:54.274  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.274  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.274  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.274  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.274  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.274  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.274  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.274  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.274  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.274  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.274  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.274  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.274  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.274  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.275  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.275  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.275  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.276  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.276  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.276  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.276  6587  6687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 15:44:54.276  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.276  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.276  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.279  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.279  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.279  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.279  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.279  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.279  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.279  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.279  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.279  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.279  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.279  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.283  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.283  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.285  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.285  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.285  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.285  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.286  6587  6687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 15:44:54.286  6587  6687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 15:44:54.286  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:44:54.286  6587  6687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 15:44:54.286  6587  6687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:44:54.286  6587  6687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 15:44:54.286  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:44:54.286  6587  6687 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 15:44:54.286  6587  6687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:44:54.286  6587  6687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:44:54.286  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:44:54.286  6587  6687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 15:44:54.291  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.291  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.291  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.291  6587  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-30 15:44:54.291  6587  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821)
08-30 15:44:54.291  6587  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
08-30 15:44:54.293  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.293  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.293  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.293  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.293  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.293  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.293  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.293  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.293  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.293  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.293  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.294  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.294  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.294  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.294  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.294  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.294  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.295  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.295  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.295  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.295  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.295  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.295  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.295  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.295  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.295  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.295  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.295  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.295  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.295  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.295  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.295  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.295  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.295  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.295  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.296  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.296  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.296  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.296  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.296  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.296  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.296  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.296  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.296  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.296  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.296  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.297  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.297  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.297  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.297  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.297  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.297  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.299  6587  6687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 15:44:54.299  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:54.299  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 15:44:54.300  6587  6687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 15:44:54.300  6587  6687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 15:44:54.300  6587  6587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 15:44:54.300  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 15:44:54.300  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:44:54.301  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.301  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 15:44:54.301  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 15:44:54.301  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 15:44:54.301  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.301  6587  6687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 15:44:54.301  6587  6587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 15:44:54.301  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.301  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.301  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:44:54.301  6587  6687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:44:54.301  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:44:54.303  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 15:44:54.303  6587  6787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 15:44:54.304  6587  6787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 15:44:54.305  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:44:54.305  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:44:54.305  6587  6687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:44:54.306  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.306  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.308  6587  6687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:44:54.309  6587  6587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:54.309  6587  6587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:44:54.309  6587  6587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 15:44:54.310  6587  6587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:44:54.310  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.310  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.310  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.310  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.310  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.310  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.310  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.311  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.311  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.311  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.311  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.311  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.311  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.311  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.311  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.311  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.311  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.311  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.311  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.312  6587  6687 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 15:44:54.312  6587  6687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 15:44:54.312  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:44:54.313  6587  6687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:44:54.313  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.313  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.313  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.314  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.315  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.315  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.317  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.317  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.318  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.318  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.318  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.319  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.319  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.319  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.323  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.323  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.323  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.323  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.326  1034  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:44:54.328  1034  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:44:54.333  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:44:54.334  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.334  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.334  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.334  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.335  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.335  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.335  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.335  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.335  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.335  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.335  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.335  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.335  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.335  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.339  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.339  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.339  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.339  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
,08-30 15:44:54.341  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:44:54.342  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:44:54.342  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:44:54.342  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:44:54.342  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.342  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.342  6587  6687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17468991 not in the list
08-30 15:44:54.342  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.342  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.342  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:44:54.342  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.343  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.343  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:44:54.343  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:44:54.344  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:44:54.344  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:44:54.344  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:44:54.345  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e18f0f6 not in the list
08-30 15:44:54.348  6587  6687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-30 15:44:54.348  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:44:54.349  6587  6687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 15:44:54.349  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:44:54.349  6587  6687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 15:44:54.349  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:44:54.353  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 15:44:54.353  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 15:44:54.354  6587  6687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-30 15:44:54.354  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 15:44:54.354  6587  6687 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 15:44:54.354  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 15:44:54.354  6587  6687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 15:44:54.354  6587  6687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 15:44:54.355  6587  6687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 15:44:54.355  6587  6687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 15:44:54.356  6587  6687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 15:44:54.356  6587  6687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 15:44:54.356  6587  6687 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 15:44:54.356  6587  6687 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 15:44:54.358  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:44:54.358  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26f953ef added. We now have 2 listener(s)
08-30 15:44:54.358  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:44:54.359  6587  6687 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 15:44:54.361  1034  1575 D WifiServiceImplEx: setWifiEnabled: true pid=6587, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:44:54.363  1034  1575 D WifiService: setWifiEnabled: true pid=6587, uid=10118
08-30 15:44:54.363  1034  1575 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:44:54.365  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:44:54.365  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2995befc added. We now have 3 listener(s)
08-30 15:44:54.365  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:44:54.371  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:44:54.371  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7db4985 added. We now have 4 listener(s)
08-30 15:44:54.371  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:44:54.373  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:44:54.373  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa303da added. We now have 5 listener(s)
08-30 15:44:54.373  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:44:54.378  6587  6785 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-30 15:44:54.379  6587  6785 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-30 15:44:54.379  1034  1957 D WifiServiceImplEx: setWifiEnabled: false pid=6587, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:44:54.379  1034  1957 D WifiService: setWifiEnabled: false pid=6587, uid=10118
08-30 15:44:54.379  1034  1957 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:44:54.392  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:44:54.392  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:44:54.392  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-30 15:44:54.393  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:44:54.393  1034  1391 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 15:44:54.393  1034  1921 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@f44b05e mBinding = false
,08-30 15:44:54.394  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 15:44:54.395  1034  1391 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 15:44:54.396  1034  1391 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 15:44:54.398  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 15:44:54.398  1034  1391 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 15:44:54.398  1034  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:44:54.398  1034  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:44:54.399  1034  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:44:54.399  1034  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:44:54.406  1034  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 15:44:54.406  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:44:54.406  2736  2736 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:44:54.406  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.407  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.407  1034  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:44:54.407  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:44:54.408  1034  1391 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:44:54.409  1034  2858 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.409   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:44:54.412  1034  1096 D BluetoothManagerService: Message: 2
08-30 15:44:54.413  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:44:54.415  1034  1096 D BluetoothManagerService: Sending off request.
08-30 15:44:54.416  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:44:54.417  3897  4020 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 15:44:54.417  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:44:54.418  3897  3978 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 15:44:54.418  3897  3978 D BluetoothAdapterProperties: Setting state to 13
08-30 15:44:54.418  3897  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 15:44:54.420  3897  3978 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 15:44:54.420  3897  3978 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 15:44:54.421  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-30 15:44:54.428  3897  3982 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:44:54.428  3897  3978 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 15:44:54.429  1034  1096 D BluetoothManagerService: Message: 60
08-30 15:44:54.429  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 15:44:54.429  3897  4289 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:44:54.429  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 15:44:54.429  3897  4287 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 15:44:54.429  3897  4287 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:44:54.429  3897  4287 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 15:44:54.429  3897  4287 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 15:44:54.429  3897  4287 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 15:44:54.429  3897  4287 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 15:44:54.429  3897  4287 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 15:44:54.429  3897  4287 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 15:44:54.430  3897  3978 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 15:44:54.431  3897  4331 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:44:54.431  3897  4326 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:44:54.432  3897  4329 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:44:54.433  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 15:44:54.433  3897  4085 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 15:44:54.435  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 15:44:54.435  3897  4085 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 15:44:54.435  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.435  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:44:54.435  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.435  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.435  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:54.435  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:54.435  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.435  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:54.435  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:54.436  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.436  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.436  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:44:54.439  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.441  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.444  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.444  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:54.444  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.444  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.444  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:54.444  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:54.444  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.444  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:44:54.444  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:54.444  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.445  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:44:54.445  1034  1408 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 15:44:54.445  1034  1408 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 15:44:54.447  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.447  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:54.447  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.447  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.447  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:54.447  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:54.447  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:54.447  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:54.447  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:54.448  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.448  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:44:54.459  1034  1574 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-30 15:44:54.459  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.459  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.459  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 15:44:54.459  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.459  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-30 15:44:54.483  1034  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6805 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 15:44:54.486  1034  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:54.486  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:54.487  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:54.487  1034  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:54.488  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:54.488  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:54.489  1034  1391 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 15:44:54.489  1034  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:54.490  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:54.490  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:54.490  1034  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.490  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.491  1034  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@20624c54
,08-30 15:44:54.491  1034  1390 D LGWifiP2pService: P2pDisablingState
08-30 15:44:54.492  1034  1390 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.492  1034  1390 D LGWifiP2pService: p2p socket connection lost
08-30 15:44:54.492  1034  1390 D LGWifiP2pService: P2pDisabledState
08-30 15:44:54.493  3897  3897 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:54.493  3897  3897 D BluetoothMapService: STATE_TURNING_OFF
08-30 15:44:54.494  3897  3897 V BtOppService: Receiver DISABLED_ACTION 
08-30 15:44:54.494  3897  3897 V BluetoothMapService: Handler(): got msg=4
08-30 15:44:54.494  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:54.494  3897  3897 D BluetoothMapService: MAP Service closeService in
08-30 15:44:54.494  3897  3897 D BluetoothMapMasInstance: MAP Service shutdown
08-30 15:44:54.494  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:44:54.494  3897  3897 V BluetoothMapService: MAP Service closeService out
08-30 15:44:54.495  3897  3897 I BtOppRfcommListener: stopping Accept Thread
08-30 15:44:54.495  3897  3897 V BtOppRfcommListener: close mBtServerSocket
08-30 15:44:54.495  3897  3897 V BtOppRfcommListener: waiting for thread to terminate
08-30 15:44:54.495  3897  4326 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 15:44:54.495  3897  3897 V BtOppRfcommListener: done waiting for thread to terminate
08-30 15:44:54.495  1034  1408 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 15:44:54.495  1034  1408 D DSQN    : disableDataServiceNotify
08-30 15:44:54.496  1034  1408 D DSQN    : stop dsqn bin
08-30 15:44:54.496  1034  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 15:44:54.496  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.496  1034  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.496   309  6821 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 15:44:54.497  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 15:44:54.497  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:44:54.498  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.498  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:54.498  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.498  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.498  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:54.498  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:54.498  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:54.498  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:54.498  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:44:54.498  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 15:44:54.498  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:44:54.499  2736  2736 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:44:54.499  1034  1391 D W,ifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:44:54.499  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:44:54.499  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.500  1034  1391 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:44:54.500  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:44:54.500   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:44:54.501  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.510  1034  1408 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 15:44:54.510  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:54.510  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:44:54.511  1034  1408 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:44:54.511  1034  1408 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 15:44:54.512  1034  1408 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 15:44:54.512  1034  1408 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 15:44:54.512  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 15:44:54.516  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 15:44:54.516  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.516  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.517  1034  2856 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 15:44:54.538  1034  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6824 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 15:44:54.539  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 15:44:54.541  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 15:44:54.542  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:54.542  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:54.542  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:44:54.542  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 15:44:54.544  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:54.544  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:44:54.544  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:44:54.545  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 15:44:54.545  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-30 15:44:54.545  1034  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.545  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 15:44:54.545  1034  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:54.546  1940  1940 D WfdsService: WifiP2pState is changed : false
08-30 15:44:54.546  1940  2291 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 15:44:54.546  1940  2291 D WfdsService: Set the WFDS Monitor: false
08-30 15:44:54.546  1940  2291 D WfdsMonitor: WFDS Monitor is stopped
08-30 15:44:54.546  1940  2291 D WfdsService: STATE : WfdsDisabledState - enter
08-30 15:44:54.546  3897  3897 V BtOppService: onDestroy
08-30 15:44:54.547  1940  2293 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 15:44:54.547  1940  2772 D CtrlSupplicant: Received on exit socket, terminate
08-30 15:44:54.547  1940  2772 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 15:44:54.547  1940  2772 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 15:44:54.547  1034  1391 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 15:44:54.547  1940  2772 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 15:44:54.547  1940  2291 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 15:44:54.547  1034  1408 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:54.547  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:44:54.547  1034  1391 D WifiNative-p2p0: TERMINATE: returned true
08-30 15:44:54.548  1034  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:44:54.548  1034  1391 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:44:54.548  1034  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:44:54.550  3897  3897 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 15:44:54.550  1034  1408 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:54.550  1034  1408 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:54.550  1034  1408 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 15:44:54.551  1034  1408 D NetworkManagementService: Removing idletimer
08-30 15:44:54.551  1034  1391 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:54.551  1034  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:44:54.552  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:54.552  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:44:54.552  1034  1408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:54.553  1034  1408 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 15:44:54.555  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 15:44:54.555  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:54.555  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:54.555  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:44:54.556  1034  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 15:44:54.557  1034  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 15:44:54.557  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 15:44:54.557  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:54.557  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:54.557  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 15:44:54.557  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:44:54.557  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:44:54.557  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:44:54.558  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:44:54.558  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:44:54.558  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:44:54.559  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 15:44:54.560  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:44:54.560  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 15:44:54.560  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 15:44:54.563  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:54.563  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled -, will return stored value
08-30 15:44:54.563  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:54.563  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.563  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.563  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:54.563  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:54.563  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:54.563  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:54.563  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:44:54.565  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.565  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:44:54.567  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.567  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:54.567  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:54.567  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:54.567  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:44:54.567  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:54.567  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:54.567  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:54.567  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:44:54.568  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:54.568  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:44:54.582  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:54.582  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:54.583  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:54.588  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 15:44:54.588  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:54.588  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:44:54.596  6824  6824 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:44:54.597  6824  6824 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 15:44:54.597  6824  6824 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:44:54.597  6824  6824 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 15:44:54.599  6824  6824 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 15:44:54.599  6824  6824 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:44:54.603  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:44:54.603  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:54.604  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:44:54.619  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:44:54.620  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:54.620  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:54.621  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:54.638  6805  6805 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-30 15:44:54.638  6805  6805 W LG Account v2.2: No ProfileInfo entries
08-30 15:44:54.639  6805  6805 I LG Account v2.2: isEnabled: false
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]Country: EU
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]Operator: OPEN
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]Ranking support: false
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]Comfort support: false
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]Accessory: true
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]Health device: true
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]Extra Pedometer: false
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]Blood glucose device: false
08-30 15:44:54.639  6805  6805 I Feature : [Lifetracker]Device Number: 3
08-30 15:44:54.642  2736  2736 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 15:44:54.642  2736  2736 I wpa_supplicant: monitor socket send errors count : 1
08-30 15:44:54.642  2736  2736 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-2\x00 that cannot receive messages
08-30 15:44:54.643  1034  2771 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 15:44:54.643  1034  2771 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 15:44:54.650  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:44:54.672  1034  2858 D DhcpStateMachine: StoppedState
08-30 15:44:54.672  1034  2858 D DhcpStateMachine: StoppedState{ when=-173ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:44:54.692  2736  2736 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:44:54.693  1034  2771 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 15:44:54.693  1034  2771 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:44:54.693  1034  2771 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:44:54.693  1034  2771 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 15:44:54.694  1034  1391 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120139
,08-30 15:44:54.694  1034  1391 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120139
08-30 15:44:54.694  2736  2736 W wpa_supplicant: USIM:  scard_deinit function
08-30 15:44:54.694  1034  1096 D Tethering: InitialState.processMessage what=4
08-30 15:44:54.695  1034  2771 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:44:54.695  1034  2771 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:44:54.695  1034  1391 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=120140  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 15:44:54.695  1034  1391 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=120140  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 15:44:54.704  1034  1993 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6843 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 15:44:54.705  1034  1993 I ActivityManager: Killing 6170:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 15:44:54.742  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:44:54.743  1034  1391 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 15:44:54.743  1034  1391 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 15:44:54.745  1034  1050 W libprocessgroup: failed to open /acct/uid_10014/pid_6170/cgroup.procs: No such file or directory
,08-30 15:44:54.746  1034  1391 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:54.747  1034  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 15:44:54.810  6587  6587 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:44:54.817  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:44:54.824  2736  2736 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 15:44:54.825  1034  2771 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 15:44:54.825  1034  2771 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 15:44:54.825  1034  2771 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 15:44:54.828  1034  1391 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-30 15:44:54.835  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-30 15:44:54.836  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:44:54.842  1034  1751 I ActivityManager: Killing 6291:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 15:44:54.859  6824  6824 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 15:44:54.918  1034  1939 W libprocessgroup: failed to open /acct/uid_10004/pid_6291/cgroup.procs: No such file or directory
,08-30 15:44:54.937  1940  1940 D WfdsService: Supplicant Connection state is changed : false
,08-30 15:44:54.937  1940  2291 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 15:44:54.938  1034  1391 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 15:44:54.939  1940  2291 D WfdsService: Set the WFDS Monitor: false
,08-30 15:44:54.939  1034  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:44:54.939  1034  1391 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:44:54.939  1034  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:44:54.939  1940  2291 D WfdsMonitor: WFDS Monitor is stopped
08-30 15:44:54.946  3897  3897 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:44:54.946  3897  3897 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:54.947  3897  3897 V BluetoothPbapReceiver: ***********state = 13
08-30 15:44:54.947  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 15:44:54.948  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 15:44:54.948  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 15:44:54.948  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:54.951  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 15:44:54.951  3897  3897 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 15:44:54.952  2471  2471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:54.954  3897  3897 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:54.954  3897  3897 V BluetoothPbapService: state: 13
08-30 15:44:54.954  3897  3897 V BluetoothPbapService: Pbap Service closeService in
,08-30 15:44:54.957  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.958  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:54.962  3897  3897 V BluetoothPbapService: successfully stopped pbap service
08-30 15:44:54.962  3897  3897 V BluetoothPbapService: Pbap Service closeService out
08-30 15:44:54.962  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:44:54.963  3897  3897 V BluetoothPbapService: Pbap Service onDestroy
08-30 15:44:54.963  3897  3897 V BluetoothPbapService: Pbap Service closeService in
08-30 15:44:54.963  3897  3897 V BluetoothPbapService: Pbap Service closeService out
08-30 15:44:54.963  3897  3897 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 15:44:54.972  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:44:55.008  6824  6824 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 15:44:55.008  6824  6824 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:44:55.018  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:44:55.028  1034  1096 D BluetoothManagerService: Message: 20
08-30 15:44:55.028  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ea699f8:true
,08-30 15:44:55.040  1034  1096 D BluetoothManagerService: Message: 30
,08-30 15:44:55.045  1034  1096 D BluetoothManagerService: Message: 30
08-30 15:44:55.048  6824  6824 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 15:44:55.050  6824  6824 D BluetoothMap: Create BluetoothMap proxy object
08-30 15:44:55.051  1034  1096 D BluetoothManagerService: Message: 30
08-30 15:44:55.055  1034  1096 D BluetoothManagerService: Message: 30
,08-30 15:44:55.057  6824  6824 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 15:44:55.058  6824  6824 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 15:44:55.074  6824  6824 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 15:44:55.079  6824  6824 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 15:44:55.094  6824  6824 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:44:55.108  6824  6824 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 15:44:55.113  6824  6824 D BluetoothInputDevice: Proxy object connected
,08-30 15:44:55.115  6824  6824 D HidProfile: Bluetooth service connected
08-30 15:44:55.117  6824  6824 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:44:55.118  6824  6824 D PanProfile: Bluetooth service connected
08-30 15:44:55.119  6824  6824 D BluetoothMap: Proxy object connected
08-30 15:44:55.121  6824  6824 D MapProfile: Bluetooth service connected
08-30 15:44:55.121  6824  6824 D BluetoothMap: getConnectedDevices()
08-30 15:44:55.122  6824  6824 D BluetoothMap: Bluetooth is Not enabled
,08-30 15:44:55.123  6824  6824 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 15:44:55.129  6824  6824 D BluetoothPermissionRequest: onReceive
08-30 15:44:55.132  6824  6824 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 15:44:55.145  1034  1049 I ActivityManager: Killing 6432:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-30 15:44:55.147  6824  6824 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 15:44:55.204  3897  3897 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-30 15:44:55.204  3897  3897 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-30 15:44:55.207  3897  3897 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 15:44:55.208  1034  1993 W libprocessgroup: failed to open /acct/uid_10008/pid_6432/cgroup.procs: No such file or directory
08-30 15:44:55.311  1034  1049 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6877 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 15:44:55.333  3897  3897 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:55.333  3897  3897 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 15:44:55.335  3897  3897 V BluetoothFtpService: Ftp Service onStartCommand
08-30 15:44:55.335  3897  3897 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:55.335  3897  3897 V BluetoothFtpService: Ftp Service closeService
08-30 15:44:55.335  3897  3897 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 15:44:55.336   345   345 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 462us total 32.757ms
08-30 15:44:55.354  3897  3897 V BluetoothFtpService: successfully stopped ftp service
,08-30 15:44:55.357  3897  3897 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:44:55.357  3897  3897 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:44:55.357  3897  3897 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:44:55.357  3897  3897 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:55.357  3897  3897 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 15:44:55.357  3897  3897 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 15:44:55.359  3897  3897 V BluetoothFtpService: Ftp Service onDestroy
08-30 15:44:55.359  3897  3897 V BluetoothFtpService: Ftp Service closeService
08-30 15:44:55.360   345   345 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 23.280ms
08-30 15:44:55.382   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 21.131ms
,08-30 15:44:55.432  1034  1993 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6898 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 15:44:55.438  3897  3982 D bt_hci_bdroid: cleanup
08-30 15:44:55.438  3897  4087 I bt_lpm  : LPM is already off!!!
08-30 15:44:55.438  3897  4085 W bt-btif : ag scb idx 1 not allocated
08-30 15:44:55.438  3897  4085 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:44:55.438  3897  4085 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:44:55.439  3897  4085 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:44:55.439  3897  4085 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 15:44:55.439  3897  4085 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 15:44:55.439  3897  4257 I bt_userial_mct: exiting userial_read_thread
08-30 15:44:55.439  3897  4257 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 15:44:55.439  3897  3982 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 15:44:55.439  3897  4087 I bt_vendor: hw_epilog_process
08-30 15:44:55.440  3897  3982 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 15:44:55.440  3897  3982 D bt_userial_mct: userial_close
08-30 15:44:55.440  3897  3982 E bt_userial_mct: pthread_join() FAILED result:3
08-30 15:44:55.440  3897  3982 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 15:44:55.442  3897  3897 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:55.442  3897  3897 V BluetoothSapService: state: 13
08-30 15:44:55.442  3897  3897 V BluetoothSapService: Stopping SAP server process
,08-30 15:44:55.444  3897  3897 V BluetoothSapService: Sap Service closeSapService in
08-30 15:44:55.444  3897  3897 V BluetoothSapService: Close listen Socket : 
08-30 15:44:55.445  3897  3897 V BluetoothSapService: Close rfcomm Socket : 
08-30 15:44:55.445  3897  3897 V BluetoothSapService: Close sapd  Socket : 
08-30 15:44:55.445  3897  3897 V BluetoothSapService: Sap Service closeSapService out
08-30 15:44:55.446  3897  3897 V BluetoothSapService: Sap Service onDestroy
08-30 15:44:55.446  3897  3897 V BluetoothSapService: Sap Service closeSapService in
08-30 15:44:55.446  3897  3897 V BluetoothSapService: Close listen Socket : 
,08-30 15:44:55.446  3897  3897 V BluetoothSapService: Close rfcomm Socket : 
08-30 15:44:55.446  3897  3897 V BluetoothSapService: Close sapd  Socket : 
08-30 15:44:55.446  3897  3897 V BluetoothSapService: Sap Service closeSapService out
,08-30 15:44:55.469  6877  6877 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 15:44:55.493  6877  6877 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 15:44:55.501  6898  6898 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 15:44:55.519  1034  1751 I ActivityManager: Killing 5965:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 15:44:55.529  3897  3982 D bt_hci_bdroid: set_power 0
,08-30 15:44:55.529  3897  3982 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 15:44:55.529  3897  3982 I bt_vendor: bluetooth satus is on
08-30 15:44:55.529  3897  3982 I bt_vendor: bt-vendor : resetting BT status
08-30 15:44:55.529  3897  3982 I bt_vendor: Starting hciattach daemon
08-30 15:44:55.529  3897  3982 I bt_vendor: try to set false
08-30 15:44:55.530  3897  3982 I bt_vendor: Starting hciattach daemon
08-30 15:44:55.530  3897  3982 I bt_vendor: try to set false
08-30 15:44:55.531  3897  3982 I bt_vendor: cleanup
08-30 15:44:55.531  3897  4085 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 15:44:55.532  3897  3982 I GKI_LINUX: GKI_exit_task 0 done
08-30 15:44:55.532  3897  3982 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 15:44:55.533  3897  3978 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 15:44:55.534  6877  6877 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 15:44:55.535  6877  6877 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 15:44:55.535  6877  6877 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 15:44:55.536  6877  6877 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 15:44:55.536  6877  6877 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 15:44:55.538  6877  6877 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-30 15:44:55.545  6877  6877 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-30 15:44:55.565  1034  1575 W libprocessgroup: failed to open /acct/uid_10011/pid_5965/cgroup.procs: No such file or directory
08-30 15:44:55.566  3897  3897 D HeadsetService: Received stop request...Stopping profile...
,08-30 15:44:55.571  3897  3897 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 15:44:55.571  3897  3897 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:44:55.571  3897  4008 D HeadsetStateMachine: Exit Disconnected: -1
08-30 15:44:55.571  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f56a007
08-30 15:44:55.572  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-30 15:44:55.572  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 15:44:55.573  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 15:44:55.573  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 15:44:55.574  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 15:44:55.574  3897  3897 D A2dpService: Received stop request...Stopping profile...
08-30 15:44:55.575  3897  4064 D A2dpStateMachine: Exit Disconnected: -1
08-30 15:44:55.575  3897  3897 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 15:44:55.576  3897  3978 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 15:44:55.577  3897  3897 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 15:44:55.577  3897  3897 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:44:55.578  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f56a007
,08-30 15:44:55.581  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-30 15:44:55.581  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 15:44:55.582  3897  3897 D HidService: Received stop request...Stopping profile...
08-30 15:44:55.582  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f56a007
08-30 15:44:55.584  6824  6824 D BluetoothInputDevice: Proxy object disconnected
08-30 15:44:55.584  3897  3897 D HeadsetStateMachine: Unbinding service...
08-30 15:44:55.584  6824  6824 D HidProfile: Bluetooth service disconnected
08-30 15:44:55.585  3897  3897 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:44:55.585  3897  3897 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:44:55.586  3897  3897 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:44:55.586  3897  3897 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:44:55.586  3897  3897 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 15:44:55.586  3897  3897 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:44:55.586  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:44:55.586  3897  3897 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 15:44:55.587  3897  3897 D HealthService: Received stop request...Stopping profile...
08-30 15:44:55.587  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f56a007
08-30 15:44:55.589  3897  3897 D PanService: Received stop request...Stopping profile...
,08-30 15:44:55.591  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f56a007
08-30 15:44:55.593  3897  3897 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 15:44:55.593  6824  6824 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 15:44:55.593  6824  6824 D PanProfile: Bluetooth service disconnected
08-30 15:44:55.593  3897  3897 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 15:44:55.593  3897  3897 D BtGatt.GattService: stop()
08-30 15:44:55.593  3897  3897 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 15:44:55.594  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:44:55.594  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f56a007
08-30 15:44:55.595  3897  3897 D BluetoothMapService: Received stop request...Stopping profile...
08-30 15:44:55.595  3897  3897 D BluetoothMapService: stop()
08-30 15:44:55.596  3897  3897 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 15:44:55.596  3897  3897 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 15:44:55.597  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f56a007
08-30 15:44:55.598  3897  3897 I BluetoothA2dpServiceJni: cleanupNative
08-30 15:44:55.598  3897  4065 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 15:44:55.598  6824  6824 D BluetoothMap: Proxy object disconnected
08-30 15:44:55.598  6824  6824 D MapProfile: Bluetooth service disconnected
08-30 15:44:55.598  3897  3897 I GKI_LINUX: GKI_exit_task 2 done
08-30 15:44:55.598  3897  3897 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 15:44:55.599  3897  3897 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 15:44:55.599  3897  3897 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 15:44:55.599  3897  3897 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 15:44:55.599  3897  3897 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:44:55.599  3897  3897 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:44:55.600  3897  3897 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:44:55.600  3897  3897 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 15:44:55.601  3897  3897 V BluetoothMapService: Handler(): got msg=4
08-30 15:44:55.601  3897  3897 D BluetoothMapService: MAP Service closeService in
08-30 15:44:55.601  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:44:55.601  3897  3897 V BluetoothMapService: MAP Service closeService out
08-30 15:44:55.601  3897  3978 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 15:44:55.602  3897  3978 D BluetoothAdapterProperties: Setting state to 10
08-30 15:44:55.602  3897  3978 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 15:44:55.602  3897  3897 D BluetoothMapService: cleanup()
08-30 15:44:55.602  3897  3897 D BluetoothMapService: MAP Service closeService in
08-30 15:44:55.602  1034  1096 D BluetoothManagerService: Message: 60
08-30 15:44:55.602  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:44:55.602  3897  3897 V BluetoothMapService: MAP Service closeService out
08-30 15:44:55.602  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 15:44:55.602  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 15:44:55.603  3897  3978 I BluetoothAdapterState: Entering OffState
08-30 15:44:55.603  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 15:44:55.604  6824  6840 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:44:55.605  1850  4018 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:44:55.606  6824  6839 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:44:55.607  1850  2453 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:44:55.607  6824  6840 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:44:55.608  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:44:55.608  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:44:55.608  6824  6839 D BluetoothPan: onBluetoothStateChange on: false
08-30 15:44:55.609  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 15:44:55.609  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 15:44:55.612  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 15:44:55.612  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 15:44:55.613  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@f44b05e mBinding = false
08-30 15:44:55.613  1034  1096 D BluetoothManagerService: Sending unbind request.
08-30 15:44:55.615  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 15:44:55.616  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:55.616  1940  2124 D LGBluetoothAPIService: Message: 2
08-30 15:44:55.617  1940  2124 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3efae116 mBinding = false
08-30 15:44:55.617  1940  2124 D LGBluetoothAPIService: Sending unbind request.
08-30 15:44:55.618  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:44:55.618  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:55.619  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:55.624  6824  6824 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 15:44:55.625  3897  3982 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 15:44:55.625  6824  6824 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 15:44:55.625  6824  6824 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 15:44:55.629  3897  3897 I GKI_LINUX: GKI_exit_task 1 done
08-30 15:44:55.629  3897  3897 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 15:44:55.630  3897  3897 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 15:44:55.630  3897  3897 I art     : --- WEIRD: removing null entry 246
08-30 15:44:55.630  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:44:55.630  3897  3897 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 15:44:55.630  3897  3897 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 15:44:55.631  6824  6824 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 15:44:55.632  1602  1602 D BluetoothAdapter: 1005674367: getState() :  mService = null. Returning STATE_OFF
08-30 15:44:55.632  1602  1602 D BluetoothAdapter: 1005674367: getState() :  mService = null. Returning STATE_OFF
08-30 15:44:55.633  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:44:55.633  6877  6877 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-30 15:44:55.637  3897  3897 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 15:44:55.640  3897  3897 I art     : System.exit called, status: 0
08-30 15:44:55.640  3897  3897 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 15:44:55.641  6877  6877 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 15:44:55.642  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:44:55.642  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:44:55.642  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:44:55.651  6824  6824 D DockEventReceiver: finishStartingService: stopping service
08-30 15:44:55.652  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:44:55.658  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:44:55.664  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:44:55.666   314  2149 V AudioFlinger: 3897 died, releasing its sessions
08-30 15:44:55.666   314  2149 V AudioFlinger:  pid 1850 @ 0
08-30 15:44:55.666   314  2149 V AudioFlinger:  pid 3459 @ 1
,08-30 15:44:55.666   314  2149 V AudioFlinger:  pid 3459 @ 2
08-30 15:44:55.666  6824  6824 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 15:44:55.666  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:44:55.731  1034  2029 I ActivityManager: Process com.android.bluetooth (pid 3897) has died
,08-30 15:44:55.732  1034  2029 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 15:44:55.743  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:44:55.749  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:44:55.752  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:44:55.763  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:44:55.763  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:44:55.763  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:44:55.772  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:44:55.779  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:44:55.782  6824  6824 D BluetoothPermissionRequest: onReceive
,08-30 15:44:55.785  6824  6824 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 15:44:55.786  6824  6824 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 15:44:55.788  6824  6824 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 15:44:55.836  1034  1957 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6929 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-30 15:44:55.851  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:44:55.852  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:44:55.855  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:44:55.912  1034  1921 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6946 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 15:44:55.937  6929  6929 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 15:44:55.937  6929  6929 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:44:55.938  6929  6929 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 15:44:55.938  6929  6929 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 15:44:55.957  6929  6929 D BluetoothAdapterApp: Loading JNI Library
,08-30 15:44:55.985  6929  6929 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2dccee9c Instance Count = 1
,08-30 15:44:55.991  6929  6929 D BluetoothAdapterApp: onCreate
,08-30 15:44:56.010  6929  6929 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 15:44:56.010  6929  6929 D ProfileConfigQcom: Adding HeadsetService
08-30 15:44:56.011  6929  6929 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 15:44:56.011  6929  6929 D ProfileConfigQcom: Adding A2dpService
08-30 15:44:56.011  6929  6929 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 15:44:56.011  6929  6929 D ProfileConfigQcom: Adding HidService
08-30 15:44:56.011  6929  6929 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 15:44:56.011  6929  6929 D ProfileConfigQcom: Adding HealthService
08-30 15:44:56.012  6929  6929 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 15:44:56.012  6929  6929 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 15:44:56.013  6929  6929 D ProfileConfigQcom: Adding PanService
08-30 15:44:56.013  6929  6929 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 15:44:56.013  6929  6929 D ProfileConfigQcom: Adding GattService
08-30 15:44:56.013  6929  6929 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 15:44:56.013  6929  6929 D ProfileConfigQcom: Adding BluetoothMapService
08-30 15:44:56.013  6929  6929 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 15:44:56.015  6929  6929 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 15:44:56.019  6824  6824 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 15:44:56.021  6929  6929 V LGMDMManagerInternal: Create singleton instance
08-30 15:44:56.024  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:44:56.027  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:44:56.032  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:44:56.050  6946  6966 W FormManager: Network not available. Please check & try again.
,08-30 15:44:56.056  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-30 15:44:56.056  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:44:56.056  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:44:56.057  6824  6824 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 15:44:56.057  6946  6967 V FormManager: Network unavailable.
08-30 15:44:56.058  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 15:44:56.059  6946  6967 V FormManager: Network unavailable.
08-30 15:44:56.075  6824  6824 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:44:56.075  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 15:44:56.075  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:44:56.075  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:44:56.075  6824  6824 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:44:56.075  6824  6824 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 15:44:56.076  1034  2031 I ActivityManager: Killing 5988:com.android.contacts/u0a19 (adj 15): empty #17
08-30 15:44:56.105  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-30 15:44:56.106  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 15:44:56.106  1034  1049 W libprocessgroup: failed to open /acct/uid_10019/pid_5988/cgroup.procs: No such file or directory
08-30 15:44:56.107  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:44:56.108  6929  6929 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:56.109  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:44:56.110  6929  6929 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:44:56.111  6929  6929 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:44:56.111  6929  6929 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:44:56.112  6929  6929 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:44:56.112  6929  6929 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 15:44:56.113  4333  6970 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:44:56.115  4333  6971 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:44:56.115  4333  6971 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:44:56.118  6898  6898 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 15:44:56.124  6843  6843 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 15:44:56.125  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:44:56.125  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:44:56.126  6946  6974 W FormManager: Network not available. Please check & try again.
08-30 15:44:56.129  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 15:44:56.131  6946  6975 V FormManager: Network unavailable.
,08-30 15:44:56.133  6946  6975 V FormManager: Network unavailable.
,08-30 15:44:56.138  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:44:56.139  1034  1921 I ActivityManager: Killing 6487:com.lge.email/u0a23 (adj 15): empty #17
08-30 15:44:56.169  1034  1574 W libprocessgroup: failed to open /acct/uid_10023/pid_6487/cgroup.procs: No such file or directory
,08-30 15:44:56.190  6877  6877 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 15:44:56.191  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 15:44:56.192  6877  6877 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 15:44:56.232  6877  6877 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 15:44:56.232  6877  6877 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:44:56.242  6877  6877 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 15:44:56.243  6877  6877 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 15:44:56.243  6877  6877 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 15:44:56.243  6877  6877 V SoundPool: doLoad: loading sample sampleID=1
08-30 15:44:56.243  6877  6877 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 15:44:56.250  6877  6877 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 15:44:56.251  6877  6978 V SoundPool: Start decode
08-30 15:44:56.251  6877  6978 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 15:44:56.252  6690  6690 D UEI.SmartControl: QS Service created
08-30 15:44:56.253   314  1402 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 15:44:56.253   314  1402 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 15:44:56.253   314  1402 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 15:44:56.253   314  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 15:44:56.254  6877  6877 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 15:44:56.254   314  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 15:44:56.254   314  1402 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 15:44:56.254   314  1402 V MediaPlayerService: player type = 3
08-30 15:44:56.254   314  1402 V AwesomePlayer: AwesomePlayer create()
08-30 15:44:56.254  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 15:44:56.255   314  1402 V AwesomePlayer: reset_l() 
08-30 15:44:56.255   314  1402 V AwesomePlayer: cancelPlayerEvents
,08-30 15:44:56.256   314  1402 V AwesomePlayer: setAudioSink() 
08-30 15:44:56.256   314  1402 V AwesomePlayer: reset_l() 
08-30 15:44:56.256   314  1402 V AudioCache: notify(0xb1432bc0, 8, 0, 0)
08-30 15:44:56.256   314  1402 V AudioCache: ignored
08-30 15:44:56.256   314  1402 V AwesomePlayer: cancelPlayerEvents
08-30 15:44:56.256   314  1402 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 15:44:56.256   314  1402 V AwesomePlayer: setDataSource_l dataSource
08-30 15:44:56.256   314  1402 V LGParserOSAL: SniffLGParser start
08-30 15:44:56.256   314  1402 V LGParserOSAL: MainType:5, SubType=0
08-30 15:44:56.256   314  1402 V LGParserOSAL: #### check Mime : application/ogg
08-30 15:44:56.257   314  1402 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 15:44:56.257   314  1402 E MediaExtractor: Use LGExtractor :application/ogg 
,08-30 15:44:56.265  6877  6877 V LGMDMManager: Create singleton instance
08-30 15:44:56.276  6690  6690 I UEI.SmartControl: Service initServices...
08-30 15:44:56.276  6690  6690 D UEI.SmartControl: QS start get config
,08-30 15:44:56.307   314  1402 V LGParserOSAL: supported mime: application/ogg
08-30 15:44:56.308   314  1402 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 15:44:56.308   314  1402 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 15:44:56.308   314  1402 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 15:44:56.308   314  1402 V AwesomePlayer: AudioTrack Setting
08-30 15:44:56.308   314  1402 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 15:44:56.308   314  1402 V AwesomePlayer: setAudioSource() 
08-30 15:44:56.308   314  1402 V MediaPlayerService: prepare
08-30 15:44:56.308   314  1402 V AwesomePlayer: prepareAsync_l() 
08-30 15:44:56.308   314  1402 V MediaPlayerService: wait for prepare
08-30 15:44:56.308   314  6979 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 15:44:56.308   314  6979 V AwesomePlayer: initAudioDecoder() 
08-30 15:44:56.309   314  6979 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 15:44:56.309   314  6979 V AudioSystem: isOffloadSupported()
08-30 15:44:56.309   314  6979 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 15:44:56.309   314  6979 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 15:44:56.309   314  6979 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 15:44:56.309   314  6979 V AwesomePlayer: getUseOffload() = 0 
08-30 15:44:56.309   314  6979 V OMXCodec: OMXCodec::Create
08-30 15:44:56.309   314  6979 V OMXCodec: findMatchingCodecs()
08-30 15:44:56.309   314  6979 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 15:44:56.309   314  6979 V OMXCodec: matchingCodecs.size()=1
08-30 15:44:56.309   314  6979 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 15:44:56.311   314  6979 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 15:44:56.311   314  6979 V LGCodecAdapter: LG Codec Adapter start
08-30 15:44:56.311   314  6979 V OMXCodec: OMXCodec Createtor
08-30 15:44:56.311   314  6979 V OMXCodec: setComponentRole
08-30 15:44:56.311   314  6979 V OMXCodec: configureCodec protected=0
08-30 15:44:56.311   314  6979 V LGCodecAdapter: called getLGCodecSpecificData
08-30 15:44:56.311   314  6979 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 15:44:56.311   314  6979 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 15:44:56.311   314  6979 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 15:44:56.311   314  6979 V LGCodecOSAL: Not support LGCodec
08-30 15:44:56.311   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 15:44:56.311   314  6979 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 15:44:56.311   314  6979 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 15:44:56.311   314  6979 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 15:44:56.312   314  6979 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 15:44:56.312   314  6979 V AudioSystem: isOffloadSupported()
08-30 15:44:56.312   314  6979 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 15:44:56.312   314  6979 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 15:44:56.312   314  6979 V OMXCodec: init()
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 15:44:56.312   314  6979 V OMXCodec: allocateBuffers
08-30 15:44:56.312   314  6979 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-30 15:44:56.312   314  6979 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-30 15:44:56.312   314  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c9420 on output port
08-30 15:44:56.312   314  6979 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 15:44:56.312   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 15:44:56.313   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 15:44:56.313   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 15:44:56.313   314  6979 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 15:44:56.313   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 15:44:56.313   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 15:44:56.313   31,4  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 15:44:56.313   314  6979 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 15:44:56.313   314  6979 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 15:44:56.313   314  6979 V AudioCache: notify(0xb1432bc0, 5, 0, 0)
08-30 15:44:56.313   314  6979 V AudioCache: ignored
08-30 15:44:56.313   314  6979 V AudioCache: notify(0xb1432bc0, 1, 0, 0)
08-30 15:44:56.313   314  6979 V AudioCache: prepared
08-30 15:44:56.313   314  1402 V AudioCache: wait - success
08-30 15:44:56.313   314  1402 V MediaPlayerService: start
08-30 15:44:56.313   314  1402 V AwesomePlayer: play_l() 
08-30 15:44:56.313   314  1402 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 15:44:56.313   314  1402 V AwesomePlayer: createAudioPlayer_l
08-30 15:44:56.313   314  1402 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 15:44:56.313   314  1402 V AwesomePlayer: startAudioPlayer_l() 
08-30 15:44:56.313   314  1402 D AudioPlayer: start of Playback, useOffload 0
08-30 15:44:56.313   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 15:44:56.313   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044840480
08-30 15:44:56.316   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:44:56.317   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 15:44:56.317   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 15:44:56.317   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 15:44:56.317   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 15:44:56.317   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 15:44:56.317   314  6981 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 15:44:56.317   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 15:44:56.318   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-30 15:44:56.318   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-30 15:44:56.318   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 15:44:56.318   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on output port
08-30 15:44:56.318   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 15:44:56.318   314  6981 V OMXCod,ec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 15:44:56.319  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 15:44:56.319  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 15:44:56.320   314  1402 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 15:44:56.321   314  1402 V AudioCache: notify(0xb1432bc0, 6, 0, 0)
08-30 15:44:56.321   314  1402 V AudioCache: ignored
08-30 15:44:56.322   314  1402 V MediaPlayerService: wait for playback complete
08-30 15:44:56.322   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.322   314  6982 V AudioCache: memcpy(0xaf006000, 0xb0404000, 4096)
08-30 15:44:56.324  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7613
08-30 15:44:56.325   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.325   314  6982 V AudioCache: memcpy(0xaf007000, 0xb0404000, 4096)
08-30 15:44:56.325   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.325   314  6982 V AudioCache: memcpy(0xaf008000, 0xb0404000, 4096)
08-30 15:44:56.325   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.325   314  6982 V AudioCache: memcpy(0xaf009000, 0xb0404000, 4096)
08-30 15:44:56.326   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.326   314  6982 V AudioCache: memcpy(0xaf00a000, 0xb0404000, 4096)
08-30 15:44:56.326   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.326   314  6982 V AudioCache: memcpy(0xaf00b000, 0xb0404000, 4096)
08-30 15:44:56.326   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.326   314  6982 V AudioCache: memcpy(0xaf00c000, 0xb0404000, 4096)
08-30 15:44:56.327   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.327   314  6982 V AudioCache: memcpy(0xaf00d000, 0xb0404000, 4096)
08-30 15:44:56.327   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.327   314  6982 V AudioCache: memcpy(0xaf00e000, 0xb0404000, 4096)
08-30 15:44:56.328   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.328   314  6982 V AudioCache: memcpy(0xaf00f000, 0xb0404000, 4096)
08-30 15:44:56.328   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.328   314  6982 V AudioCache: memcpy(0xaf010000, 0xb0404000, 4096)
08-30 15:44:56.329   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.329   314  6982 V AudioCache: memcpy(0xaf011000, 0xb0404000, 4096)
08-30 15:44:56.330   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.330   314  6982 V AudioCache: memcpy(0xaf012000, 0xb0404000, 4096)
08-30 15:44:56.330   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.330   314  6982 V AudioCache: memcpy(0xaf013000, 0xb0404000, 4096)
08-30 15:44:56.331   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.331   314  6982 V AudioCache: memcpy(0xaf014000, 0xb0404000, 4096)
08-30 15:44:56.331   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.331   314  6982 V AudioCache: memcpy(0xaf015000, 0xb0404000, 4096)
08-30 15:44:56.332   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.332   314  6982 V AudioCache: memcpy(0xaf016000, 0xb0404000, 4096)
08-30 15:44:56.332   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.332   314  6982 V AudioCache: memcpy(0xaf017000, 0xb0404000, 4096)
08-30 15:44:56.333   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.333   314  6982 V AudioCache: memcpy(0xaf018000, 0xb0404000, 4096)
08-30 15:44:56.333   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.333   314  6982 V AudioCache: memcpy(0xaf019000, 0xb0404000, 4096)
08-30 15:44:56.334   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.334   314  6982 V AudioCache: memcpy(0xaf01a000, 0xb0404000, 4096)
08-30 15:44:56.334   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.334   314  6982 V AudioCache: memcpy(0xaf01b000, 0xb0404000, 4096)
08-30 15:44:56.335   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.335   314  6982 V AudioCache: memcpy(0xaf01c000, 0xb0404000, 4096)
08-30 15:44:56.335   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.335   314  6982 V AudioCache: memcpy(0xaf01d000, 0xb0404000, 4096)
08-30 15:44:56.336   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.336   314  6982 V AudioCache: memcpy(0xaf01e000, 0xb0404000, 4096)
08-30 15:44:56.336   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.336   314  6982 V AudioCache: memcpy(0xaf01f000, 0xb0404000, 4096)
08-30 15:44:56.337   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.337   314  6982 V AudioCache: memcpy(0xaf020000, 0xb0404000, 4096)
08-30 15:44:56.337   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.337   314  6982 V AudioCache: memcpy(0xaf021000, 0xb0404000, 4096)
08-30 15:44:56.338   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.338   314  6982 V AudioCache: memcpy(0xaf022000, 0xb0404000, 4096)
08-30 15:44:56.338   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.339   314  6982 V AudioCache: memcpy(0xaf023000, 0xb0404000, 4096)
08-30 15:44:56.339   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.339   314  6982 V AudioCache: memcpy(0xaf024000, 0xb0404000, 4096)
08-30 15:44:56.340   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.340   314  6982 V AudioCache: memcpy(0xaf025000, 0xb0404000, 4096)
08-30 15:44:56.340   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.340   314  6982 V AudioCache: memcpy(0xaf026000, 0xb0404000, 4096)
08-30 15:44:56.341   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.341   314  6982 V AudioCache: memcpy(0xaf027000, 0xb0404000, 4096)
08-30 15:44:56.341   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.341   314  6982 V AudioCache: memcpy(0xaf028000, 0xb0404000, 4096)
08-30 15:44:56.342   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.342   314  6982 V AudioCache: memcpy(0xaf029000, 0xb0404000, 4096)
08-30 15:44:56.342   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.342   314  6982 V AudioCache: memcpy(0xaf02a000, 0xb0404000, 4096)
08-30 15:44:56.343   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.343   314  6982 V AudioCache: memcpy(0xaf02b000, 0xb0404000, 4096)
08-30 15:44:56.343   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.343   314  6982 V AudioCache: memcpy(0xaf02c000, 0xb0404000, 4096)
08-30 15:44:56.344   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.344   314  6982 V AudioCache: memcpy(0xaf02d000, 0xb0404000, 4096)
08-30 15:44:56.344   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.344   314  6982 V AudioCache: memcpy(0xaf02e000, 0xb0404000, 4096)
08-30 15:44:56.345   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.345   314  6982 V AudioCache: memcpy(0xaf02f000, 0xb0404000, 4096)
08-30 15:44:56.345   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.345   314  6982 V AudioCache: memcpy(0xaf030000, 0xb0404000, 4096)
08-30 15:44:56.346   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.346   314  6982 V AudioCache: memcpy(0xaf031000, 0xb0404000, 4096)
08-30 15:44:56.346   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.346   314  6982 V AudioCache: memcpy(0xaf032000, 0xb0404000, 4096)
08-30 15:44:56.347   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.347   314  6982 V AudioCache: memcpy(0xaf033000, 0xb0404000, 4096)
08-30 15:44:56.347   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.347   314  6982 V AudioCache: memcpy(0xaf034000, 0xb0404000, 4096)
08-30 15:44:56.347   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.347   314  6982 V AudioCache: memcpy(0xaf035000, 0xb0404000, 4096)
08-30 15:44:56.348   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.348   314  6982 V AudioCache: memcpy(0xaf036000, 0xb0404000, 4096)
08-30 15:44:56.348   314  6982 V AudioCache: write(0xb0404000, 4096)
08-30 15:44:56.348   314  6982 V AudioCache: memcpy(0xaf037000, 0xb0404000, 4096)
08-30 15:44:56.349   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 15:44:56.349   314  6982 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 15:44:56.349   314  6982 V AwesomePlayer: postAudioEOS() 
08-30 15:44:56.349   314  6982 V AudioCache: write(0xb0404000, 280)
08-30 15:44:56.349   314  6982 V AudioCache: memcpy(0xaf038000, 0xb0404000, 280)
08-30 15:44:56.350   314  6979 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 15:44:56.350   314  6979 V AwesomePlayer: onStreamDone
08-30 15:44:56.350   314  6979 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 15:44:56.350   314  6979 V AudioCache: notify(0xb1432bc0, 2, 0, 0)
08-30 15:44:56.350   314  6979 V AudioCache: playback complete
08-30 15:44:56.350   314  6979 V AwesomePlayer: pause_l() 
,08-30 15:44:56.350   314  6979 V AudioCache: notify(0xb1432bc0, 7, 0, 0)
,08-30 15:44:56.350   314  1402 V AudioCache: wait - success
08-30 15:44:56.350   314  6979 V AudioCache: ignored
08-30 15:44:56.350   314  1402 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 15:44:56.350   314  6979 V AwesomePlayer: cancelPlayerEvents
08-30 15:44:56.350   314  6979 D AudioPlayer: Pause Playback at 1068125
08-30 15:44:56.351   314  1402 V AwesomePlayer: reset_l() 
08-30 15:44:56.351   314  1402 V AudioCache: notify(0xb1432bc0, 8, 0, 0)
08-30 15:44:56.351   314  1402 V AudioCache: ignored
08-30 15:44:56.351   314  1402 V AwesomePlayer: cancelPlayerEvents
08-30 15:44:56.351   314  1402 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 15:44:56.351   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 15:44:56.351   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 15:44:56.351   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 15:44:56.351   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 1
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-30 15:44:56.351   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 15:44:56.352   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-30 15:44:56.352   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:44:56.352   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 15:44:56.352   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 15:44:56.352   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 15:44:56.352   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 15:44:56.352   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 15:44:56.352   314  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 15:44:56.352   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 15:44:56.352   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 15:44:56.352   314  1402 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 15:44:56.352   314  1402 ,V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 15:44:56.353   314  1402 D AudioPlayer: AudioPlayer releasing audio source
08-30 15:44:56.353   314  1402 D AudioPlayer: AudioPlayer done releasing audio source
08-30 15:44:56.353   314  1402 V AwesomePlayer: reset_l() 
08-30 15:44:56.353   314  1402 V AwesomePlayer: cancelPlayerEvents
08-30 15:44:56.353   314  1402 V AwesomePlayer: ~AwesomePlayer call
08-30 15:44:56.353   314  1402 V AwesomePlayer: reset_l() 
08-30 15:44:56.353   314  1402 V AwesomePlayer: cancelPlayerEvents
08-30 15:44:56.353  6877  6978 V SoundPool: close(31)
08-30 15:44:56.353  6877  6978 V SoundPool: pointer = 0x9ffe0000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 15:44:56.556  6690  6690 I UEI.SmartControl: Supports setup maps: true
08-30 15:44:56.559  6690  6690 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 15:44:56.559  6690  6690 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 15:44:56.559  6690  6690 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 15:44:56.559  6690  6690 I UEI.SmartControl: ### init IR Blaster...
,08-30 15:44:56.562  6690  6690 D serial_port: Configuring serial port
08-30 15:44:56.563  6690  6690 E UEI.SmartControl: UEIBLaster setting for 616
,08-30 15:44:56.563  6690  6690 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 15:44:56.563  6690  6690 I UEI.SmartControl: configuring settings for MAXQ616
08-30 15:44:56.563  6690  6690 I UEI.SmartControl: Get version...
08-30 15:44:56.581  6690  6983 D UEI.SmartControl: serial port data available: 21
,08-30 15:44:56.608  6690  6690 D UEI.SmartControl: MAXQ616 A2-X4 software.,
,08-30 15:44:56.608  6690  6690 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 15:44:56.608  6690  6690 I UEI.SmartControl: QS saving settings...
08-30 15:44:56.614  6690  6690 D UEI.SmartControl: IR Blaster version: 25672567
08-30 15:44:56.631  6690  6983 D UEI.SmartControl: serial port data available: 4
,08-30 15:44:56.663  6690  6989 I UEI.SmartControl: Device manager: loading config....
,08-30 15:44:56.664  6690  6989 D UEI.SmartControl: ----------- loading internal config...
,08-30 15:44:56.665  6690  6690 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 15:44:56.669  6690  6690 E UEI.SmartControl: Services init done
08-30 15:44:56.669  6690  6690 D UEI.SmartControl: QS Service init finished
08-30 15:44:56.670  6690  6690 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 15:44:56.671  6690  6690 D UEI.SmartControl: QS Service version code: 201091
08-30 15:44:56.672  6690  6690 D UEI.SmartControl: Service requested: Control
08-30 15:44:56.677  6690  6989 E UEI.SmartControl: Loading SETTINGS...
08-30 15:44:56.677  6690  6690 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 15:44:56.683  6877  6877 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-30 15:44:56.683  6690  6690 D UEI.SmartControl: Internal service binding...
,08-30 15:44:56.686  6690  6705 I UEI.SmartControl: ------ IControl API: 11
08-30 15:44:56.686  6690  6705 D UEI.SmartControl: File observer start...
08-30 15:44:56.687  6690  6705 E UEI.SmartControl: IR Port is disabled: false
,08-30 15:44:56.687  6690  6705 D UEI.SmartControl: Starting file observer...
08-30 15:44:56.688  6690  6705 I UEI.SmartControl: Registering callback...
08-30 15:44:56.691  6690  6706 I UEI.SmartControl: ------ IControl API: 19
,08-30 15:44:56.692  6690  6706 I UEI.SmartControl: Registering Services Ready callback...
,08-30 15:44:56.696  6690  6989 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 15:44:56.723  6690  6988 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 15:44:56.723  6690  6988 D UEI.SmartControl: -----service ready thread exits
,08-30 15:44:56.724  6877  6893 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 15:44:56.725  6877  6976 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 15:44:56.726  6877  6976 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-30 15:44:56.727  6877  6877 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 15:44:56.727  6877  6877 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 15:44:56.728  6690  6705 I UEI.SmartControl: ------ IControl API: 8
08-30 15:44:56.730  6877  6877 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 15:44:56.731  6877  6877 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 15:44:56.732  6877  6877 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 15:44:56.733  6877  6877 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 15:44:56.735  6877  6877 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 15:44:56.737  6877  6877 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-30 15:44:56.742  6877  6877 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-30 15:44:56.746  6877  6877 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 15:44:56.748  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 15:44:56.750  6877  6877 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 15:44:56.751  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 15:44:56.753  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-30 15:44:56.754  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 15:44:56.755  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 15:44:56.757  6877  6877 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472564696756]
08-30 15:44:56.761  6877  6877 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 15:44:56.763  1034  1884 I ActivityManager: Killing 6023:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 15:44:56.792  6877  6991 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 15:44:56.834  1034  1751 W libprocessgroup: failed to open /acct/uid_10027/pid_6023/cgroup.procs: No such file or directory
,08-30 15:44:56.853  6877  6877 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 15:44:56.854  6877  6877 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 15:44:56.855  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-30 15:44:56.856  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 15:44:56.857  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 15:44:56.858  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 15:44:56.858  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 15:44:56.876  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 15:44:57.474  1034  1993 D WifiServiceImplEx: setWifiEnabled: true pid=6587, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 15:44:57.476  1034  1993 D WifiService: setWifiEnabled: true pid=6587, uid=10118
,08-30 15:44:57.476  1034  1993 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:44:57.506  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:44:57.506  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:44:57.507  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-30 15:44:57.510  1034  1391 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 15:44:57.510  1034  1391 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 15:44:57.514  1034  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 15:44:57.514  1034  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 15:44:57.514  1034  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 15:44:57.514  1034  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 15:44:57.514  1034  1391 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 15:44:57.514  1034  1391 E WifiHW  : unknown target_country: EU , set to default
08-30 15:44:57.514  1034  1391 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 15:44:57.515  1034  1391 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 15:44:57.515  1034  1391 I WifiUtil: gEnableBmps=1
08-30 15:44:57.551  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:44:57.558  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-30 15:44:57.568  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:57.571  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:57.574  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:57.579  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:57.579  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-30 15:44:57.588  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:44:57.593  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:57.594  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 15:44:57.597  6390  6424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 15:44:57.609  5692  5692 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 15:44:57.618  5692  5692 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 15:44:57.636  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:44:57.685  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:44:57.725  1034  1921 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6999 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 15:44:57.734  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 15:44:57.781  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 15:44:57.800  6999  6999 I AppUp4:AppBoxCP: onCreate
08-30 15:44:57.801  6999  6999 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 15:44:57.811  6999  6999 I AppUp4:DB:  setFingerPrint start
,08-30 15:44:57.811  6999  6999 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 15:44:57.819  6999  6999 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 15:44:57.819  6999  6999 I AppUp4:DB:  SDK version = 21
,08-30 15:44:57.819  6999  6999 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-30 15:44:57.822  6999  6999 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 15:44:57.823  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 15:44:57.823  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:57.826  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:44:57.826  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 15:44:57.833  6999  6999 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 15:44:57.883  6999  6999 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:44:57.883  6999  6999 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:44:57.893  6999  6999 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@159a3646
,08-30 15:44:57.893  6999  6999 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:44:57.893  6999  6999 D AppUp4:CustFacade: isPhone : true
08-30 15:44:57.894  6999  6999 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:44:57.894  6999  6999 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-30 15:44:57.895  6999  6999 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 15:44:57.896  6999  7033 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 15:44:57.896  6999  7033 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 15:44:57.896  6999  7033 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-30 15:44:57.899  1034  1049 I ActivityManager: Killing 6522:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-30 15:44:57.999  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:58.000  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:44:58.001  1034  1050 W libprocessgroup: failed to open /acct/uid_10061/pid_6522/cgroup.procs: No such file or directory
,08-30 15:44:58.006  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:44:58.018  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:44:58.030  4333  7036 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 15:44:58.038  4333  7037 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:58.038  4333  7037 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 15:44:58.095  1034  1574 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7043 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 15:44:58.169  7043  7043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 15:44:58.170  7043  7043 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:44:58.172  7043  7043 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 15:44:58.172  7043  7043 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 15:44:58.251  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 15:44:58.258  1034  1096 D Tethering: InitialState.processMessage what=4
08-30 15:44:58.262   309   893 D SoftapController: Softap fwReload - Ok
08-30 15:44:58.262  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:44:58.265  1034  1391 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (744ms)
,08-30 15:44:58.268   309   893 D CommandListener: Setting iface cfg
08-30 15:44:58.268   309   893 D CommandListener: Trying to bring down wlan0
08-30 15:44:58.269   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:44:58.273  1034  1391 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 15:44:58.276  1034  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:44:58.276  1034  1391 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:44:58.276  1034  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:44:58.269  7062  7062 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:44:58.269  7062  7062 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:44:58.283  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:58.284  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 15:44:58.286  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:58.287  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:44:58.289  1034  1391 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 15:44:58.289  1034  1391 D WifiMonitor: connecting to supplicant
08-30 15:44:58.291  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 15:44:58.297  7043  7043 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 15:44:58.312  7043  7043 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 15:44:58.322  7062  7062 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 15:44:58.345  7062  7062 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 15:44:58.346  7062  7062 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 15:44:58.353  7043  7043 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:44:58.386  7043  7043 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 15:44:58.386  7043  7043 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:44:58.421  7062  7062 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 15:44:58.464  7062  7062 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 15:44:58.470  7062  7062 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 15:44:58.471  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-30 15:44:58.472  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 15:44:58.472  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 15:44:58.472  1034  7067 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 15:44:58.472  1034  7067 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 15:44:58.473  1034  1391 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 15:44:58.473  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:58.474  1034  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:58.474  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:58.475  1034  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:58.475  1034  1391 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 15:44:58.475  1034  1391 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 15:44:58.476  7062  7062 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 15:44:58.476  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 15:44:58.476  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 15:44:58.476  1034  7067 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 15:44:58.476  1034  7067 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 15:44:58.476  1034  1391 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 15:44:58.476  1034  1391 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 15:44:58.476  1034  1391 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 15:44:58.477  1034  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:44:58.477  1034  1391 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:44:58.477  1034  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:44:58.477  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:58.478  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:44:58.478  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:58.478  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:58.478  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:44:58.481  1034  1391 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 15:44:58.482  1034  1391 D WifiNative-wlan0: SET update_config 1: returned true
08-30 15:44:58.482  1034  1391 D WifiConfigStore: Loading config and enabling all networks 
08-30 15:44:58.482  1034  1391 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 15:44:58.482  1034  1391 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 15:44:58.483  1940  1940 D WfdService: Waiting for WifiP2p enabling
08-30 15:44:58.485  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:58.487  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 15:44:58.487  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 15:44:58.489  1034  1391 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 15:44:58.489  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:58.489  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:58.489  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:58.489  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:58.489  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:58.489  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:58.489  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:58.489  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:58.489  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:44:58.489  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:58.489  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:44:58.490  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:58.490  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:44:58.490  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:44:58.490  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:44:58.490  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:44:58.490  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:44:58.490  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:44:58.490  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:44:58.490  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:44:58.490  6587  6587 W org.thal,iproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:44:58.490  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:44:58.499  1034  1391 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-30 15:44:58.499  1034  1391 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 15:44:58.500  1034  1391 D WifiStateMachine: enableVerboseLogging : level 2
08-30 15:44:58.500  1034  1391 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 15:44:58.500  1034  1391 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 15:44:58.500  1034  1391 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 15:44:58.501  1034  1391 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 15:44:58.501  1034  1391 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 15:44:58.502  1034  1391 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 15:44:58.502  1034  1391 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 15:44:58.502  1034  1391 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 15:44:58.502  1034  1391 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 15:44:58.503  1034  1391 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 15:44:58.503  1034  1391 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 15:44:58.503  1034  1391 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 15:44:58.503  1034  1391 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 15:44:58.503  1034  1391 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 15:44:58.504  1034  1391 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 15:44:58.504  1034  1391 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 15:44:58.504  1034  1391 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 15:44:58.504  1034  1391 D WifiNative-HAL: Setting external_sim to 1
08-30 15:44:58.504  1034  1391 D WifiNative-wlan0: doBoolean: SET external_sim 1
,08-30 15:44:58.505  1940  1940 D WfdsService: Supplicant Connection state is changed : true
08-30 15:44:58.505  1940  2291 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 15:44:58.505  1940  2291 D WfdsService: Set the WFDS Monitor: true
08-30 15:44:58.505  1940  2291 D WfdsMonitor: WfdsMonitorThread create
08-30 15:44:58.505  1034  1391 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 15:44:58.505  1034  1391 I WifiNative-HAL: startHal
08-30 15:44:58.505  1034  1391 D wifi    : setting scan oui 0xaf794140
08-30 15:44:58.505  1940  2291 D WfdsMonitor: WFDS Monitor is created and started
08-30 15:44:58.505  1940  2291 D WfdsService: WiFi: Supplicant connection re-established
08-30 15:44:58.505  1034  1391 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 15:44:58.505  1034  1391 I WifiNative-HAL: startHal
08-30 15:44:58.505  1034  1391 D wifi    : setting scan oui 0xaf794140
08-30 15:44:58.506  1034  1391 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 15:44:58.506  1940  7068 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 15:44:58.506  1940  7068 E CtrlSupplicant: Succeed to open control connection
08-30 15:44:58.506  1940  7068 E CtrlSupplicant: Succeed to open monitor connection
08-30 15:44:58.507  1034  1391 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 15:44:58.507  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 15:44:58.507  1940  7068 D WfdsMonitor: Supplicant connection established
08-30 15:44:58.507  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 15:44:58.507  1940  2291 D WfdsService: Connected to the supplicant for wfds
08-30 15:44:58.507  1034  1391 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 15:44:58.508  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 15:44:58.508  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 15:44:58.508  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 15:44:58.508  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 15:44:58.508  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 15:44:58.508  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 15:44:58.508  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 15:44:58.508  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 15:44:58.509  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 15:44:58.509  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 15:44:58.509  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 15:44:58.509  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 15:44:58.509  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 15:44:58.509  7062  7062 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 15:44:58.509  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 15:44:58.510  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 15:44:58.510  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 15:44:58.510  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 15:44:58.511  1034  1391 E WifiNative: : [123,955,293 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 15:44:58.511  1034  1391 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 15:44:58.511  1034  1391 D WifiNative-wlan0: RECONNECT: returned true
08-30 15:44:58.511  1034  1391 D WifiNative-wlan0: doString: [STATUS]
08-30 15:44:58.512  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 15:44:58.512  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SS,ID=
08-30 15:44:58.512  1034  1391 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 15:44:58.513  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:44:58.514  1034  1391 D WifiNative-wlan0: SET ps 1: returned true
,08-30 15:44:58.514  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.516  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 15:44:58.516  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-30 15:44:58.516   309   893 D CommandListener: Setting iface cfg
08-30 15:44:58.516   309   893 D CommandListener: Trying to bring up p2p0
08-30 15:44:58.516  1034  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.516  1034  1555 I WifiNative-HAL: startHal
08-30 15:44:58.516  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf794140
08-30 15:44:58.516  1034  1555 D wifi    : failed to get capabilities : -3
08-30 15:44:58.516  1034  1555 E WifiScanningService: could not get scan capabilities
08-30 15:44:58.516  1034  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 15:44:58.516  1034  1390 D LGWifiP2pService: P2pEnablingState
08-30 15:44:58.516  1034  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.516  1034  1390 D LGWifiP2pService: P2p socket connection successful
08-30 15:44:58.516  1034  1390 D LGWifiP2pService: P2pEnabledState
08-30 15:44:58.517  1034  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 15:44:58.517  1034  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.517  1034  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 15:44:58.517  1034  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 15:44:58.517  1034  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 15:44:58.518  1034  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-30 15:44:58.518  1034  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 15:44:58.518  1034  1390 D LGWifiP2pService: before postfix = G3
08-30 15:44:58.518  1034  1390 D WifiServerServiceExt: postfix byte check : 2
08-30 15:44:58.518  1034  1390 D LGWifiP2pService: after postfix = G3
08-30 15:44:58.518  1034  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 15:44:58.518  1034  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 15:44:58.518  1034  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 15:44:58.519  1034  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 15:44:58.519  1034  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 15:44:58.519  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 15:44:58.519  1034  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 15:44:58.519  1940  1940 D WfdsService: WifiP2pState is changed : true
08-30 15:44:58.519  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 15:44:58.519  1940  2291 D WfdsService: Receive the WFDS_ENABLE Method
08-30 15:44:58.519  1034  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 15:44:58.519  1940  2291 D WfdsService: Set the WFDS Monitor: true
08-30 15:44:58.519  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-30 15:44:58.519  1940  2291 D WfdsService: Connected to the supplicant for wfds
08-30 15:44:58.519  1940  2291 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 15:44:58.520  7062  7062 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 15:44:58.520  1940  2291 D WfdsService: selectPreferredScanChannel [36]
08-30 15:44:58.520  1940  2291 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 15:44:58.520  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 15:44:58.520  1034  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30, 15:44:58.520  1034  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 15:44:58.520  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 15:44:58.520  1034  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 15:44:58.521  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 15:44:58.521  1940  1940 D WfdsService: isConnected: false
08-30 15:44:58.521  1034  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 15:44:58.522  1034  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 15:44:58.522  1034  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 15:44:58.522  1034  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 15:44:58.523  1034  1391 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 15:44:58.523  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 15:44:58.523  1034  1391 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 15:44:58.524  1034  1391 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 15:44:58.524  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 15:44:58.524  1940  1940 D WfdsService: Update P2p Interface State: 3
08-30 15:44:58.524  1034  1391 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 15:44:58.524  1034  1391 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 15:44:58.525  1034  1391 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 15:44:58.525  1034  1391 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 15:44:58.525  1034  1391 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-30 15:44:58.530  7062  7062 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 15:44:58.531  1034  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 15:44:58.531  1034  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 15:44:58.531  1034  1390 D LGWifiP2pService: InactiveState
08-30 15:44:58.531  1034  1390 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.531  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.531  1034  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 15:44:58.531  1034  1391 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 15:44:58.532  1034  1391 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 15:44:58.532  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 15:44:58.532  1034  1391 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 15:44:58.532  1034  1391 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 15:44:58.532  7062  7062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-30 15:44:58.532  1034  7067 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:44:58.532  1034  7067 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:44:58.532  1034  7067 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:44:58.532  1034  7067 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:44:58.533  1940  7068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:44:58.533  7062  7062 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 15:44:58.533  7062  7062 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 15:44:58.533  7062  7062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.533  1034  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 15:44:58.533  1034  7067 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:44:58.533  1034  7067 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.533  1034  7067 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.533  1034  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.533  1034  7067 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.533  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:44:58.533  1034  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.533  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.534  7062  7062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.534  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.534  1034  1390 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.534  1034  7067 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:44:58.534  1034  7067 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.534  1034  7067 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.534  1034  7067 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.534  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.534  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.534  1034  1390 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.534  7043  7043 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 15:44:58.534  1034  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.534  1940  2291 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 15:44:58.534  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.534  1034  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.534  1940  7068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:44:58.534  1940  7068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:44:58.534  1034  1034 E WifiServerServiceExt: No p2p device connected
08-30 15:44:58.534  1034  1391 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 15:44:58.535  1034  1391 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 15:44:58.535  1034  1391 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 15:44:58.535  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 15:44:58.536  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 15:44:58.536  7062  7062 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:44:58.536  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:44:58.536  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:44:58.536  1034  7067 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:44:58.536  1034  7067 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:44:58.537  7062  7062 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 15:44:58.537  7062  7062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.537  1034  7067 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:44:58.537  1034  7067 E WifiMonitor: WifiMonitor:p,2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.537  1034  7067 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.537  1034  1391 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 15:44:58.537  1034  7067 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.537  7062  7062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.537  1034  7067 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:44:58.537  1034  7067 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.537  1034  1391 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:44:58.538  1034  7067 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.538  1034  7067 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:44:58.538  1034  1391 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:44:58.538  1940  7068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:44:58.538  1940  7068 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:44:58.538  1034  1391 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:44:58.538  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 15:44:58.538  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 15:44:58.538  7062  7062 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:44:58.539  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 15:44:58.539  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:44:58.539  1034  7067 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:44:58.539  1034  7067 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:44:58.539  1034  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.539  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:58.539  1034  1391 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 15:44:58.539  1034  1391 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 15:44:58.539  1034  1391 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 15:44:58.539  1034  1391 D WifiNative-wlan0: doBoolean: SCAN
08-30 15:44:58.540  1034  1391 D WifiNative-wlan0: SCAN: returned false
,08-30 15:44:58.540  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=123985  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:44:58.541  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=123986  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:44:58.541  1034  1391 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-30 15:44:58.542  1034  1391 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:44:58.542  1034  1391 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:44:58.542  1034  1391 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:44:58.543  1034  1391 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:44:58.543  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:58.543  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:58.543  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:58.543  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:58.543  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 15:44:58.544  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:44:58.544  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 15:44:58.544  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:58.561  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 15:44:58.561  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:58.562  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 15:44:58.563  7043  7043 I HubEmail: JNI_OnLoad()
08-30 15:44:58.563  7043  7043 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 15:44:58.563  7043  7043 I HubEmail: registerNatives()
08-30 15:44:58.563  7043  7043 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 15:44:58.563  7043  7043 I HubEmail: registerNativeMethods()
08-30 15:44:58.563  7043  7043 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 15:44:58.563  7043  7043 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-30 15:44:58.568  6946  7071 W FormManager: Network not available. Please check & try again.
08-30 15:44:58.606  1034  1957 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7074 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 15:44:58.610  6946  7072 V FormManager: Network unavailable.
08-30 15:44:58.611  7043  7073 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:58.613  6946  7072 V FormManager: Network unavailable.
08-30 15:44:58.620  1034  1884 I ActivityManager: Killing 6085:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-30 15:44:58.707  1034  1751 W libprocessgroup: failed to open /acct/uid_10080/pid_6085/cgroup.procs: No such file or directory
,08-30 15:44:58.804  7074  7074 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:44:58.804  7074  7074 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:44:58.808  7074  7074 D PhoneMonitor: Register our PhoneStateListener
,08-30 15:44:58.832  7074  7074 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 15:44:58.837  7074  7074 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 15:44:58.860  7074  7074 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-30 15:44:58.863  7074  7074 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 15:44:58.864  7074  7074 D TelephonyAutoProfiling: [parse] Load xml
,08-30 15:44:58.871  7074  7074 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 15:44:58.871  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 15:44:58.871  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 15:44:58.871  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 15:44:58.871  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 15:44:58.871  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
,08-30 15:44:58.871  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 15:44:58.872  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 15:44:58.872  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 15:44:58.872  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 15:44:58.872  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 15:44:58.872  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 15:44:58.872  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 15:44:58.872  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 15:44:58.872  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 15:44:58.872  7074  7074 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 15:44:58.873  7074  7074 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-30 15:44:58.883  7074  7074 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 15:44:58.905  1034  1575 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7093 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 15:44:58.907  1034  1575 I ActivityManager: Killing 6103:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 15:44:58.953  1034  1993 W libprocessgroup: failed to open /acct/uid_10097/pid_6103/cgroup.procs: No such file or directory
,08-30 15:44:59.098  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-30 15:44:59.098  1034  7067 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 15:44:59.098  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 15:44:59.098  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-30 15:44:59.098  1034  7067 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 15:44:59.098  7062  7062 E wpa_supplicant: USIM:  scard_init function
08-30 15:44:59.099  1034  1391 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 15:44:59.099  1034  1391 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 15:44:59.100  7062  7062 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 15:44:59.100  1034  1391 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 15:44:59.100  1034  1391 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 15:44:59.100  1034  1391 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-30 15:44:59.105  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 15:44:59.106  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 15:44:59.120  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=124565  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 15:44:59.131  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.131  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:59.133  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:44:59.142  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.142  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.142  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 15:44:59.184  1034  1050 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7114 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-30 15:44:59.185  1034  1050 I ActivityManager: Killing 6646:com.lge.eula/1000 (adj 15): empty #17
,08-30 15:44:59.222  7062  7062 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 15:44:59.224  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 15:44:59.225  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 15:44:59.225  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,08-30 15:44:59.225  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 15:44:59.225  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:44:59.225  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:44:59.233  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:44:59.233  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:44:59.233  7062  7062 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:44:59.233  7062  7062 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:44:59.233  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=124678  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 15:44:59.234  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 15:44:59.234  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:44:59.234  1034  7067 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:44:59.234  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 15:44:59.234  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:44:59.234  1034  7067 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 15:44:59.236  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:44:59.236  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:44:59.237  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.237  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:59.239  1034  1992 W libprocessgroup: failed to open /acct/uid_1000/pid_6646/cgroup.procs: No such file or directory
08-30 15:44:59.240  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:59.240  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.240  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.240  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 15:44:59.242  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124687  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 15:44:59.243  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124688  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 15:44:59.244  1034  1391 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124689
08-30 15:44:59.245  1034  1391 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124690
08-30 15:44:59.246  1034  1391 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124690
,08-30 15:44:59.246  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124691
08-30 15:44:59.247  1034  1391 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124691
08-30 15:44:59.247  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 15:44:59.247  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=124692  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 15:44:59.254  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=124698  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 15:44:59.255  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=124699  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 15:44:59.255  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.255  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.256  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 15:44:59.257  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=124702  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 15:44:59.259  1034  1391 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=124704
08-30 15:44:59.260  1034  1391 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=124705
08-30 15:44:59.260  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.260  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:59.260  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.261  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.261  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 15:44:59.261  1034  1391 D WifiNative-wlan0: doString: [STATUS]
08-30 15:44:59.261  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:44:59.261  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 15:44:59.262  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:44:59.262  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-30 15:44:59.264  1034  1391 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 15:44:59.264  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:59.266  1034  1391 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 15:44:59.268  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.268  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:59.269  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:59.271  1034  1391 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 15:44:59.271  1034  1391 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 15:44:59.275  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.275  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.275  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-30 15:44:59.280  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.280  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.280  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 15:44:59.284  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.284  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:59.285  1034  1391 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 15:44:59.285  1034  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:44:59.285  1034  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:44:59.285  1034  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:44:59.285  1034  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:44:59.286  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:59.286  1034  1408 D ConnectivityService: Got NetworkAgent Messenger
08-30 15:44:59.286  1034  1408 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 15:44:59.286  1034  1408 D ConnectivityService: NetworkAgent connected
08-30 15:44:59.288  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.288  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:59.289  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:44:59.291  1034  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:44:59.291  1034  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:44:59.292  1034  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:44:59.292  1034  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:44:59.292  1034  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:44:59.296  1034  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:44:59.298   309   893 D CommandListener: Setting iface cfg
08-30 15:44:59.301  1034  1391 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 15:44:59.301  1034  7138 D DhcpStateMachine: StoppedState
08-30 15:44:59.301  1034  7138 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.301  1034  7138 D DhcpStateMachine: WaitBeforeStartState
08-30 15:44:59.302  1034  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=124746  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 15:44:59.302  1034  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=124747  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:44:59.303  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=124747  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:44:59.304  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:44:59.304  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 15:44:59.305  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:59.305  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,08-30 15:44:59.306  1034  1391 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:59.306  1034  1391 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:59.307  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:59.307  1034  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:44:59.309  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:44:59.309  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 15:44:59.310  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:44:59.310  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 15:44:59.311  1034  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=124755  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:44:59.312  1034  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=124756  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:44:59.312  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=124757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:44:59.314  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:79403] from screen [on:0 period:-609083214] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 15:44:59.315  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-609083213] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 15:44:59.315  1034  1391 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 15:44:59.318  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:59.320  1034  1408 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 15:44:59.320  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.321  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.321  1034  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.322  1034  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.322  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.323  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.323  1034  1408 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 15:44:59.324  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=116,0,0
08-30 15:44:59.324  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=116,0,0
08-30 15:44:59.325  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 15:44:59.325  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 15:44:59.326  1034  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
,08-30 15:44:59.326  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 15:44:59.326  1034  1391 D WifiNative-wlan0: SET ps 0: returned true
08-30 15:44:59.326  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 15:44:59.327  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 15:44:59.327  1034  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 15:44:59.327  1034  1391 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 15:44:59.327  1034  1391 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 15:44:59.327  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f79fba9 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.327  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f79fba9 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.327  1034  1391 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 15:44:59.327  1034  7138 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.327  1034  7138 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 15:44:59.329   309   893 D CommandListener: Setting iface cfg
08-30 15:44:59.329   309   893 D CommandListener: Trying to bring up wlan0
08-30 15:44:59.330  1034  1391 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 15:44:59.380  1034  1921 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7139 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:44:59.381  1034  1921 I ActivityManager: Killing 6667:com.lge.bnr/1000 (adj 15): empty #17
,08-30 15:44:59.422  1034  1939 W libprocessgroup: failed to open /acct/uid_1000/pid_6667/cgroup.procs: No such file or directory
,08-30 15:44:59.430  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.431  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:44:59.431  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.431  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 15:44:59.432  1034  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.432  1034  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.433  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.434  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:44:59.434  1034  1408 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 15:44:59.435  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 15:44:59.435  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 15:44:59.435  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.436  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.436  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:44:59.436  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-30 15:44:59.437  1034  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:44:59.437  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 15:44:59.437  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 15:44:59.438  1034  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 15:44:59.438  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:44:59.454  1034  1391 D WifiNative-wlan0: SET ps 1: returned true
,08-30 15:44:59.455  1034  1408 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 15:44:59.455  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 15:44:59.456  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 15:44:59.456  1034  1391 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 15:44:59.457  7139  7139 I art     : Almond Protected OAT
08-30 15:44:59.457  1034  1408 D ConnectivityService: ignoring duplicate network state non-change
08-30 15:44:59.460  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.460  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:59.462  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:59.463  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.463  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.463  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 15:44:59.467  1034  1408 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 15:44:59.468  1034  1408 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 15:44:59.470  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.470  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.470  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 15:44:59.472  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 15:44:59.473  1034  1391 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 15:44:59.475  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 15:44:59.479  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.479  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.479  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-30 15:44:59.484  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.484  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:44:59.485  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:59.487  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 15:44:59.490  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.490  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 15:44:59.490  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:44:59.492  1034  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.492  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.492  1034  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.495  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.495  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:44:59.495  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 15:44:59.503  1034  1408 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 15:44:59.503  1034  1408 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 15:44:59.504  1034  1408 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 15:44:59.505   309   893 E Netd    : netlink response contains error (File exists)
,08-30 15:44:59.505  1034  1408 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 15:44:59.506  1034  1408 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 15:44:59.506  1034  1408 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 15:44:59.506  1034  1408 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 15:44:59.510  1034  1408 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 15:44:59.510  1034  1408 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 15:44:59.510  1034  1408 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 15:44:59.510  1034  7135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.510  1034  7135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 15:44:59.510  1034  7135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:44:59.510  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:44:59.510  1034  7135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 15:44:59.511  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 15:44:59.511  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:59.513  1034  1408 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 15:44:59.513  1034  1408 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:44:59.513  1034  1408 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:44:59.513  1034  1408 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 15:44:59.513  1034  1408 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:59.513  1034  1408 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 15:44:59.513  1034  1408 D ConnectivityService: currentScore = 0, newScore = 20
08-30 15:44:59.513  1034  1408 D ConnectivityService:    accepting network in place of null
08-30 15:44:59.513  1034  1408 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:59.513  1034  1391 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:59.513  1034  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:44:59.514   309  7159 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 15:44:59.514  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:59.514  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZW,APP&VZW800 Specifier: <-1>]
08-30 15:44:59.514  1034  1408 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 15:44:59.515  1034  1408 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 15:44:59.515  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:44:59.515  1034  1408 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:44:59.515  1034  1408 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 15:44:59.515  1034  1408 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 15:44:59.516  1034  1408 D ConnectivityService: validation of new default Network = false
08-30 15:44:59.516  1034  1408 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 15:44:59.516  1034  1408 D DSQN    : enableDataServiceNotify 
08-30 15:44:59.516  1034  1408 D DSQN    : start dsqn bin
08-30 15:44:59.517  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 15:44:59.518  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:44:59.518  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:44:59.518  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:44:59.524  1034  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 15:44:59.519  7160  7160 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:44:59.519  7160  7160 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:44:59.525  1034  1408 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 15:44:59.525  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:44:59.525  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:44:59.525  1034  1408 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 15:44:59.528  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:44:59.532  1034  7138 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 15:44:59.532  7139  7139 D WeatherApplication: removeAccount
08-30 15:44:59.532  1034  7138 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 15:44:59.532  1034  7138 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 15:44:59.536  7139  7139 D WeatherApplication: Account.length = 0
08-30 15:44:59.537  7139  7139 E WeatherApplication: OPERATOR:OPEN
,08-30 15:44:59.529  7162  7162 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:44:59.529  7162  7162 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:44:59.540  7160  7160 E DSQN    : DSQN ssw
08-30 15:44:59.542  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:44:59
08-30 15:44:59.543  7162  7162 I dhcpcd  : version 5.5.6 starting
08-30 15:44:59.545  7162  7162 E dhcpcd  : get_duid: m
08-30 15:44:59.545  7162  7162 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 15:44:59.545  7162  7162 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 15:44:59.546  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 15:44:59.547  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:44:59.548  1034  1391 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:44:59.548  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:44:59.548  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:44:59.548  1034  1391 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:44:59.549  1034  1391 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:44:59.549  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:44:59.549  1034  1391 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:44:59.550  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-30 15:44:59.551  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 15:44:59.563  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:44:59.563  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:44:59.564  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:44:59.567  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 15:44:59.567  1815  7165 I CheckinService: active receiver: enabled
08-30 15:44:59.568  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:44:59.568  7139  7139 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 15:44:59.576  1815  7165 I CheckinService: Preparing to send checkin request
,08-30 15:44:59.577  1815  7165 I EventLogService: Accumulating logs since 1472564631585
08-30 15:44:59.593  7162  7162 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 15:44:59.593  7162  7162 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-30 15:44:59.593  7162  7162 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 15:44:59.593  7162  7162 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 15:44:59.593  7162  7162 D dhcpcd  : wlan0: sending REQUEST (xid 0x2f4a4b1b), next in 4.14 seconds
08-30 15:44:59.595  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 15:44:59.595  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:44:59
08-30 15:44:59.631  1034  1992 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7174 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 15:44:59.632  1034  1992 I ActivityManager: Killing 2131:com.lge.music/u0a34 (adj 15): empty #17
08-30 15:44:59.643   314  2149 V AudioFlinger: 2131 died, releasing its sessions
08-30 15:44:59.643   314  2149 V AudioFlinger:  pid 1850 @ 0
08-30 15:44:59.643   314  2149 V AudioFlinger:  pid 3459 @ 1
08-30 15:44:59.643   314  2149 V AudioFlinger:  pid 3459 @ 2
,08-30 15:44:59.672  1034  1050 W libprocessgroup: failed to open /acct/uid_10034/pid_2131/cgroup.procs: No such file or directory
08-30 15:44:59.672  1815  7165 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 15:44:59.760  1034  1957 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7191 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 15:44:59.776   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 268us total 15.435ms
,08-30 15:44:59.789   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 263us total 12.339ms,
,08-30 15:44:59.801   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 228us total 10.823ms
,08-30 15:44:59.809   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 15:44:59.809   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 15:44:59.809   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 15:44:59.809  7174  7209 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 15:44:59.813   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 15:44:59.813   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 15:44:59.813   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 15:44:59.814  7174  7209 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 15:44:59.817   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 15:44:59.817   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 15:44:59.817   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 15:44:59.818  7174  7211 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 15:44:59.821   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 15:44:59.821   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 15:44:59.821   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 15:44:59.823  7174  7211 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 15:44:59.826  7191  7191 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 15:44:59.826  7191  7191 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 15:44:59.850  7191  7191 I MultiDex: VM with version 2.1.0 has multidex support
08-30 15:44:59.850  7191  7191 I MultiDex: install
08-30 15:44:59.850  7191  7191 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 15:44:59.858  7191  7191 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 15:45:00.045  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 15:45:00.045  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 15:45:00.045  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 15:45:00.045  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-30 15:45:00.046  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-30 15:45:00.046  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-30 15:45:00.046  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-30 15:45:00.046  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 15:45:00.060  7174  7174 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 15:45:00.070  7174  7174 I LibraryLoader: Loading: webviewchromium
08-30 15:45:00.091  7174  7174 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 5528-5550)
08-30 15:45:00.092  7174  7174 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 15:45:00.107  7174  7174 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f6cd5c9}
08-30 15:45:00.110  7174  7174 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 15:45:00.112  7174  7174 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 15:45:00.121  7191  7207 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:45:00.122  7191  7207 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:45:00.126  7174  7174 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 15:45:00.127  7174  7174 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:45:00.139   314  2148 V AudioPolicyService: registerClient() client 0xb102fd80, uid 10093
,08-30 15:45:00.142  7174  7237 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 15:45:00.145  7174  7174 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 15:45:00.146  7174  7174 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 15:45:00.146  7174  7174 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 15:45:00.174  7174  7174 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:45:00.174  7174  7174 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:45:00.174  7174  7174 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:45:00.174  7174  7174 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:45:00.174  7174  7174 I Adreno-EGL: Remote Branch: 
08-30 15:45:00.174  7174  7174 I Adreno-EGL: Local Patches: 
08-30 15:45:00.174  7174  7174 I Adreno-EGL: Reconstruct Branch: 
,08-30 15:45:00.266  7245  7245 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 15:45:00.309  7245  7245 I dex2oat : dex2oat took 42.896ms (threads: 4)
,08-30 15:45:00.318  7191  7207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:45:00.318  7191  7207 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:45:00.318  7191  7207 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:45:00.318  7191  7207 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:45:00.318  7191  7207 I Adreno-EGL: Remote Branch: 
08-30 15:45:00.318  7191  7207 I Adreno-EGL: Local Patches: 
08-30 15:45:00.318  7191  7207 I Adreno-EGL: Reconstruct Branch: 
08-30 15:45:00.416  1034  2031 I art     : Explicit concurrent mark sweep GC freed 99178(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.438ms total 148.710ms
08-30 15:45:00.418  7174  7174 I NSApplication: Starting up...
,08-30 15:45:00.433  7191  7207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:45:00.433  7191  7207 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:45:00.433  7191  7207 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:45:00.433  7191  7207 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:45:00.433  7191  7207 I Adreno-EGL: Remote Branch: 
08-30 15:45:00.433  7191  7207 I Adreno-EGL: Local Patches: 
08-30 15:45:00.433  7191  7207 I Adreno-EGL: Reconstruct Branch: 
,08-30 15:45:00.458   309  7159 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 15:45:00.476  1034  2029 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7257 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 15:45:00.477  1034  2029 I ActivityManager: Killing 6045:com.android.vending/u0a44 (adj 15): empty #17
,08-30 15:45:00.526  1034  1408 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 15:45:00.532  1034  1574 W libprocessgroup: failed to open /acct/uid_10044/pid_6045/cgroup.procs: No such file or directory
08-30 15:45:00.535  1034  1885 D WifiServiceImplEx: setWifiEnabled: false pid=6587, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:45:00.535  1034  1885 D WifiService: setWifiEnabled: false pid=6587, uid=10118
08-30 15:45:00.535  1034  1885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:45:00.545  1034  1391 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 15:45:00.545  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 15:45:00.545  1034  1391 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 15:45:00.546  1034  1391 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 15:45:00.546  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:45:00.546  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 15:45:00.546  1034  1391 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 15:45:00.546  1034  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:45:00.546  1034  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:45:00.546  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:45:00.546  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-30 15:45:00.547  1034  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:45:00.547  1034  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:45:00.552  1034  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:45:00.552  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:45:00.552  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:45:00.552  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:00.552  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:00.553  1034  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:45:00.553  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:45:00.553  1034  1391 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:45:00.553   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:45:00.564  7191  7207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:45:00.564  7191  7207 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:45:00.564  7191  7207 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:45:00.564  7191  7207 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:45:00.564  7191  7207 I Adreno-EGL: Remote Branch: 
08-30 15:45:00.564  7191  7207 I Adreno-EGL: Local Patches: 
08-30 15:45:00.564  7191  7207 I Adreno-EGL: Reconstruct Branch: 
,08-30 15:45:00.573  7257  7257 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:45:00.576  1034  1408 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 15:45:00.576  1034  1408 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-30 15:45:00.577  1034  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:00.579  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 15:45:00.579  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:00.580  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:00.580  1034  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@20624c54
08-30 15:45:00.580  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:00.580  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:00.580  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:00.581  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:00.581  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 15:45:00.581  1034  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:00.582  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:00.582  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:00.582  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:00.582  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:45:00.582  1034  1391 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 15:45:00.582  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:45:00.585  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 15:45:00.586  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:00.586  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:00.586  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:45:00.586  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 15:45:00.586  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-30 15:45:00.586  1034  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:00.586  1034  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:00.586  1034  1390 D LGWifiP2pService: P2pDisablingState
08-30 15:45:00.586  1034  1390 D LGWifiP2pService: P2pDisablingState{ when=-7ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:00.586  1034  1390 D LGWifiP2pService: p2p socket connection lost
08-30 15:45:00.587  1034  1390 D LGWifiP2pService: P2pDisabledState
08-30 15:45:00.588  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 15:45:00.588  1940  1940 D WfdsService: WifiP2pState is changed : false
08-30 15:45:00.588  1940  2291 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 15:45:00.588  1940  2291 D WfdsService: Set the WFDS Monitor: false
08-30 15:45:00.589  1940  2291 D WfdsMonitor: WFDS Monitor is stopped
,08-30 15:45:00.589  1940  2291 D WfdsService: STATE : WfdsDisabledState - enter
,08-30 15:45:00.589  1940  7068 D CtrlSupplicant: Received on exit socket, terminate
08-30 15:45:00.589  1940  7068 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 15:45:00.589  1940  7068 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 15:45:00.589  1940  7068 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 15:45:00.589  1940  2293 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 15:45:00.589  1940  2291 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 15:45:00.593  1034  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 15:45:00.593  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:00.593  1034  1390 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:00.593  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:45:00.594  7062  7062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:45:00.594  1034  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:45:00.594  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:45:00.594  1034  1391 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:45:00.595  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:00.605  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:00.605  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:00.607  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:00.621  1034  1408 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 15:45:00.621   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:45:00.621  1034  1408 D DSQN    : disableDataServiceNotify
08-30 15:45:00.621  1034  1408 D DSQN    : stop dsqn bin
08-30 15:45:00.622  1034  1391 D WifiNative-p2p0: doBoolean: TERMINATE
,08-30 15:45:00.623  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 15:45:00.624  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:00.624  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:00.625  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:45:00.625  1034  1391 D WifiNative-p2p0: TERMINATE: returned true
,08-30 15:45:00.625  1034  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:45:00.625  1034  1391 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:45:00.625  1034  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:45:00.626  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 15:45:00.628  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 15:45:00.628  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:00.628  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 15:45:00.628  1034  1408 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 15:45:00.628  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:45:00.628  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 15:45:00.628  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:00.628  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:45:00.629  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:45:00.629  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:45:00.629  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:00.629  1034  1408 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:45:00.629  1034  1408 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 15:45:00.629  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:00.629  6587  6587 V io.jxc,ore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:00.629  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:45:00.629  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:45:00.629  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 15:45:00.629  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:00.630  1034  1408 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 15:45:00.630  1034  1408 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 15:45:00.630  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:45:00.630  1034  1408 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:00.630  1034  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 15:45:00.630  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:45:00.633  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:00.633  1034  1408 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:00.633  1034  1408 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:00.633  1034  1408 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:00.634  1034  1408 D NetworkManagementService: Removing idletimer
08-30 15:45:00.634  1034  1408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:00.634  1034  1408 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 15:45:00.634  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:00.634  1034  1391 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 15:45:00.634  1034  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:45:00.634  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 15:45:00.634  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:45:00.634  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:45:00.634  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:45:00.634  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:45:00.636  1034  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 15:45:00.636  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 15:45:00.637  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:45:00.637  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,08-30 15:45:00.637  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 15:45:00.642  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:45:00.661  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:45:00.661  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:00.662  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:45:00.674  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:45:00.674  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:00.675  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:00.743   309  7289 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 15:45:00.743  7062  7062 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 15:45:00.743  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 15:45:00.743  1815  7165 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-30 15:45:00.743  7062  7062 I wpa_supplicant: monitor socket send errors count : 1
08-30 15:45:00.743  7062  7062 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-4\x00 that cannot receive messages
,08-30 15:45:00.746  1034  7067 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 15:45:00.746  1034  7067 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 15:45:00.753  1815  7165 I CheckinService: active receiver: disabled
,08-30 15:45:00.783  7062  7062 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:45:00.783  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-30 15:45:00.784  7062  7062 W wpa_supplicant: USIM:  scard_deinit function
08-30 15:45:00.784  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:45:00.784  1034  7067 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:45:00.784  1034  7067 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 15:45:00.784  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:45:00.784  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:45:00.785  1034  1391 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=126230
08-30 15:45:00.785  1034  1096 D Tethering: InitialState.processMessage what=4
08-30 15:45:00.786  1034  1391 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=126230
08-30 15:45:00.786  1034  1391 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=126231  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 15:45:00.787  1034  1391 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=126232  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 15:45:00.787  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:45:00.788  1034  1391 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:00.788  1034  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:00.862  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 15:45:00.865  6390  6424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 15:45:00.878  7062  7062 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 15:45:00.881  1034  7067 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-30 15:45:00.881  1034  7067 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 15:45:00.881  1034  7067 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 15:45:00.882  1034  1391 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-30 15:45:00.896  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:00.911  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 15:45:00.911  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:00.911  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:45:00.911  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 15:45:00.914  6999  6999 I AppUp4:CustModeStarterReceiver: onReceive
08-30 15:45:00.918  6999  6999 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@159a3646
08-30 15:45:00.918  6999  6999 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:45:00.918  6999  6999 D AppUp4:CustFacade: isPhone : true
08-30 15:45:00.918  6999  6999 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:45:00.919  6999  6999 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 15:45:00.925  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:00.925  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:45:00.927  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:45:00.934  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:00.939  4333  7297 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:45:00.954  7043  7043 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 15:45:00.957  4333  7298 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:00.957  4333  7298 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:45:00.977  7043  7302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:45:00.981  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 15:45:00.981  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:00.981  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 15:45:00.985  1940  1940 D WfdsService: Supplicant Connection state is changed : false
08-30 15:45:00.986  1940  2291 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 15:45:00.986  1940  2291 D WfdsService: Set the WFDS Monitor: false
08-30 15:45:00.986  1940  2291 D WfdsMonitor: WFDS Monitor is stopped
08-30 15:45:00.986  1034  1391 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 15:45:00.986  1034  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:45:00.986  1034  1391 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:45:00.986  1034  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:45:00.988  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 15:45:00.988  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:45:00.992  7074  7074 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 15:45:00.992  7074  7074 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 15:45:00.992  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 15:45:00.992  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 15:45:00.993  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 15:45:00.993  2471  2471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:00.995  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:45:00.995  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:00.995  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:00.995  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:00.995  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:00.995  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:45:00.995  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:00.995  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:00.995  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:00.996  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:45:00.996  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:00.996  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:00.996  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:00.996  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:00.996  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:45:00.996  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:00.996  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:00.996  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:01.010  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:45:1
08-30 15:45:01.010  1034  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=802113030, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-30 15:45:01.014  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 15:45:01.014  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:45:01.015  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:45:01.015  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-30 15:45:01.015  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@190e7534
08-30 15:45:01.015  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 15:45:01.016  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:45:01.016  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 15:45:01.016  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 15:45:01.016  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:45:1
08-30 15:45:01.018  6946  7303 W FormManager: Network not available. Please check & try again.
08-30 15:45:01.021  6946  7305 V FormManager: Network unavailable.
08-30 15:45:01.028  6946  7305 V FormManager: Network unavailable.
,08-30 15:45:01.044  2604  2604 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 15:45:01.063  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 15:45:01.063  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:45:01.063  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:45:01.063  6824  6824 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-30 15:45:01.065  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 15:45:01.067  6824  6824 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:45:01.067  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 15:45:01.067  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:45:01.067  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:45:01.068  6824  6824 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:45:01.068  6824  6824 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 15:45:01.081  6946  7307 W FormManager: Network not available. Please check & try again.
,08-30 15:45:01.083  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:01.085  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 15:45:01.086  6946  7308 V FormManager: Network unavailable.
08-30 15:45:01.088  6946  7308 V FormManager: Network unavailable.
08-30 15:45:01.092  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:45:01.106  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:45:01.109  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:45:01.113  6946  7310 W FormManager: Network not available. Please check & try again.
08-30 15:45:01.115  6946  7311 V FormManager: Network unavailable.
08-30 15:45:01.115  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.121  6946  7311 V FormManager: Network unavailable.
08-30 15:45:01.123  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:45:01.124  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:45:01.125  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:45:01.127  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:01.132  4333  7312 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:45:01.133  4333  7313 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:45:01.133  4333  7313 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:45:01.155  1034  1049 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7314 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 15:45:01.256  7314  7314 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 15:45:01.256  7314  7314 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 15:45:01.265  7314  7314 V [BNRBootReceiver]: Boot Receiver Return
08-30 15:45:01.265  7314  7314 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 15:45:01.272  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:45:01.285  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.296  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:45:01.313  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.314  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION,
,08-30 15:45:01.315  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 15:45:01.322  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 15:45:01.327  6824  6824 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-30 15:45:01.334  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:45:01.348  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.360  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.372  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.372  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:45:01.377  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:45:01.382  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.399  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.414  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.424  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.424  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:01.426  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 15:45:01.429  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.437  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.445  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.452  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.452  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:01.452  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 15:45:01.459  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:45:01.472  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.479  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:45:01.486  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.486  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:45:01.487  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:01.501  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:45:01.510  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.518  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.525  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:45:01.526  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:01.526  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:01.530  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.536  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.542  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.559  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.560  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:45:01.562  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:01.570  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.582  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.590  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.598  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.598  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:45:01.603  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:01.608  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.615  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.622  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.628  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.628  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:45:01.629  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:01.632  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.636  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 15:45:01.644  1034  1404 D WifiService: New client listening to asynchronous messages
,08-30 15:45:01.645  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:01.648  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:45:01.654  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.662  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.662  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:01.663  6877  6877 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 15:45:01.663  6690  6990 D UEI.SmartControl: Internal timer expired: 4
08-30 15:45:01.663  6690  6990 D UEI.SmartControl: unbind internal service
08-30 15:45:01.664  6877  6877 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 15:45:01.665  6877  6877 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 15:45:01.670  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.673  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 15:45:01.674  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:01.677  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.683  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.690  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:45:01.691  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:01.692  6877  6877 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 15:45:01.692  6877  6877 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 15:45:01.693  6877  6877 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 15:45:01.695  1034  1574 I ActivityManager: Killing 6805:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-30 15:45:01.763  6690  6985 D serial_port: close(fd = 24)
,08-30 15:45:01.769  6690  6985 I UEI.SmartControl: Serial port is closed.
08-30 15:45:01.828  1034  1920 W libprocessgroup: failed to open /acct/uid_10037/pid_6805/cgroup.procs: No such file or directory
,08-30 15:45:01.837  2186  2186 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 15:45:01.850  2186  2186 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 15:45:01.851  2186  2186 D c       : Getting all permits...
08-30 15:45:01.851  2186  2186 D a       : Opening database...
08-30 15:45:01.856  2186  2186 D a       : Opening database auth.proximity.permit_store...
08-30 15:45:01.857  2186  2186 D a       : Closing database...
08-30 15:45:01.873  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.877  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:45:01.877  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:45:01.877  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:45:01.880  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.890  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.896  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.897  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:01.898  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 15:45:01.905  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.908  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:45:01.908  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:45:01.908  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:01.912  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.918  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:45:01.924  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.924  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:01.925  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 15:45:01.929  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:01.932  6843  6843 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:45:01.932  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:45:01.932  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:01.936  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:01.943  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.950  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:01.951  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:01.953  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 15:45:01.962  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:01.967  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:45:01.974  6946  7347 W FormManager: Network not available. Please check & try again.
08-30 15:45:01.976  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:01.982  6946  7348 V FormManager: Network unavailable.
,08-30 15:45:01.986  6946  7348 V FormManager: Network unavailable.
08-30 15:45:01.995  2186  2186 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 15:45:02.014  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:45:02.014  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 15:45:02.016  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:02.018  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:02.025  4333  7349 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 15:45:02.026  6843  6843 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 15:45:02.026  6843  6843 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:45:02.027  6843  6843 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:02.030  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:45:02.032  4333  7350 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:45:02.033  4333  7350 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:45:02.037  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:02.037  6946  7352 W FormManager: Network not available. Please check & try again.
08-30 15:45:02.044  6946  7353 V FormManager: Network unavailable.
,08-30 15:45:02.051  6946  7353 V FormManager: Network unavailable.
08-30 15:45:02.113  1034  1575 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7354 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-30 15:45:02.233  7354  7354 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-30 15:45:02.238  7354  7354 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@a4f6c2b
08-30 15:45:02.239  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=802113030 [*alarm*], flags=0x0
08-30 15:45:02.242  1034  1049 I ActivityManager: Killing 6898:com.lge.settings.easy/1000 (adj 15): empty #17
08-30 15:45:02.321  1034  1391 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-609080207] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 15:45:02.322  1034  1391 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-609080206] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 15:45:02.323  1034  1884 W libprocessgroup: failed to open /acct/uid_1000/pid_6898/cgroup.procs: No such file or directory
,08-30 15:45:02.517  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:02.526  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-30 15:45:02.535  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:02.537  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:02.543  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 15:45:02.544  6390  6424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 15:45:02.552  5692  5692 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 15:45:02.568  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:02.583  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 15:45:02.583  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:02.584  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:45:02.584  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 15:45:02.587  6999  6999 I AppUp4:CustModeStarterReceiver: onReceive
08-30 15:45:02.590  6999  6999 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@159a3646
08-30 15:45:02.590  6999  6999 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:45:02.590  6999  6999 D AppUp4:CustFacade: isPhone : true
08-30 15:45:02.591  6999  6999 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:45:02.591  6999  6999 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-30 15:45:02.597  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:02.597  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:45:02.598  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:02.600  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:02.603  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:45:02.611  7043  7043 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 15:45:02.629  4333  7385 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 15:45:02.632  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:02.639  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 15:45:02.639  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:02.640  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 15:45:02.640  3459  3459 D PhoneState: setPdpRejectCasuse : false
08-30 15:45:02.642  7074  7074 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 15:45:02.642  7074  7074 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 15:45:02.654  4333  7386 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:02.655  4333  7386 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 15:45:02.659  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:45:2
08-30 15:45:02.664  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 15:45:02.664  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:45:02.666  7043  7387 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:02.666  6946  7391 W FormManager: Network not available. Please check & try again.
08-30 15:45:02.667  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:45:02.667  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-30 15:45:02.667  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@190e7534
,08-30 15:45:02.670  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-30 15:45:02.670  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:45:02.670  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 15:45:02.670  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 15:45:02.670  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:45:2
08-30 15:45:02.687  6946  7393 V FormManager: Network unavailable.
08-30 15:45:02.689  6946  7393 V FormManager: Network unavailable.
,08-30 15:45:03.546  1034  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:45:03.547  1034  1575 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 15:45:03.575  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:45:03.575  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:45:03.575  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-30 15:45:03.576  1034  1096 D BluetoothManagerService: Message: 1
08-30 15:45:03.576  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 15:45:03.601  1034  1096 D BluetoothManagerService: Message: 20
08-30 15:45:03.601  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ef95fee:true
,08-30 15:45:03.605  6929  6929 D BluetoothAdapterState: make
08-30 15:45:03.610  6929  6929 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 15:45:03.610  6929  6929 I bluedroid-qcom: init
08-30 15:45:03.612  6929  7401 I BluetoothAdapterState: Entering OffState
08-30 15:45:03.612  6929  6929 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 15:45:03.612  6929  6929 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 15:45:03.612  6929  6929 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 15:45:03.612  6929  6929 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 15:45:03.612  6929  6929 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 15:45:03.615  6929  6929 I bluedroid-qcom: get_profile_interface socket
08-30 15:45:03.615  6929  6929 I bluedroid-qcom: get_profile_interface map_client
08-30 15:45:03.609  7404  7404 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:03.609  7404  7404 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:45:03.619  7404  7404 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 15:45:03.619  7404  7404 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 15:45:03.619  7404  7404 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 15:45:03.622  6929  7405 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 15:45:03.624  6929  7405 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 15:45:03.627  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 15:45:03.627  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 15:45:03.627  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 15:45:03.627  1034  1096 D BluetoothManagerService: Message: 40
08-30 15:45:03.627  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,08-30 15:45:03.630  6929  6945 I bluedroid-qcom: config_hci_snoop_log
08-30 15:45:03.631  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:03.632  7404  7404 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 15:45:03.639  7404  7404 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 15:45:03.639  7404  7404 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 15:45:03.643  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 15:45:03.643  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 15:45:03.653  6929  7405 D BluetoothAdapterProperties: Name is: G3
,08-30 15:45:03.654  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:03.655  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:03.657  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:03.660  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:03.660  6929  7401 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 15:45:03.661  6929  7401 D BluetoothAdapterProperties: Setting state to 11
08-30 15:45:03.661  6929  7401 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 15:45:03.661  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-30 15:45:03.661  1034  1096 D BluetoothManagerService: Message: 60
08-30 15:45:03.661  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 15:45:03.662  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 15:45:03.662  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 15:45:03.663  6390  6424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 15:45:03.663  6929  7401 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 15:45:03.668  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:03.671  5692  5692 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 15:45:03.672  6929  7401 D BluetoothBondStateMachine: make
08-30 15:45:03.674  6929  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:03.674  6929  7401 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 15:45:03.674  6929  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:03.674  6929  7401 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 15:45:03.675  6929  7401 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 15:45:03.676  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-30 15:45:03.677  6929  7417 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 15:45:03.677  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:03.679  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:45:03.681  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:45:03.683  6824  6824 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 15:45:03.685  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:03.688  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:03.690  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:03.692  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:03.694  6929  7401 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:45:03.700  6929  6929 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:45:03.701  6929  6929 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:03.701  6929  6929 V BluetoothPbapReceiver: ***********state = 11
08-30 15:45:03.711  6929  6929 D HeadsetService: Received start request. Starting profile...
08-30 15:45:03.711  6929  6929 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:45:03.712  6929  6929 D LGBluetoothHfpAdapter: Version 1.6
08-30 15:45:03.714  6929  6929 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 15:45:03.716  6929  6929 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:45:03.716  6929  6929 D HeadsetStateMachine: make
,08-30 15:45:03.723  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:45:03.725  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:03.727  6929  7401 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:45:03.753  6929  6929 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:45:03.754  6929  6929 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:45:03.765  7162  7162 D dhcpcd  : wlan0: sending REQUEST (xid 0x2f4a4b1b), next in 8.89 seconds
08-30 15:45:03.766  7162  7162 E dhcpcd  : wlan0: send_raw_packet: m
08-30 15:45:03.766  7162  7162 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason FAIL
08-30 15:45:03.769  1034  1751 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7421 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 15:45:03.772  6929  6929 D HeadsetStateMachine: max_hf_connections = 1
08-30 15:45:03.772  6929  6929 I bluedroid-qcom: get_profile_interface handsfree
08-30 15:45:03.774  5692  5692 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 15:45:03.774  6929  6929 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 15:45:03.775   314  1402 V AudioPolicyService: registerClient() client 0xb102fe60, uid 1002
08-30 15:45:03.775   314  2149 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 15:45:03.775   314  2149 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:45:03.775   314  2149 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:45:03.775  6929  6929 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 15:45:03.776   314  2148 V AudioFlinger: registerClient() client 0xb55815e0, pid 6929
08-30 15:45:03.776  6929  6929 V ToneGenerator: Create Track: 0xb4928080
08-30 15:45:03.776  6929  6929 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 15:45:03.776  6929  6929 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 15:45:03.776   314  1403 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 15:45:03.776   314  1403 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 15:45:03.776   314  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:45:03.776   314  1403 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:45:03.776  6929  6929 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 15:45:03.776   314  2149 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 15:45:03.777   314  2148 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 15:45:03.777   314  2148 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 15:45:03.777   314  2148 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:45:03.777   314  2148 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:45:03.777  6929  6929 V AudioSystem: getLatency() output 2, latency 50
08-30 15:45:03.777  6929  6929 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 15:45:03.777  6929  6929 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 15:45:03.777  6929  6929 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 15:45:03.777   314  2149 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 15:45:03.777   314  2149 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 15:45:03.777   314  2149 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 15:45:03.777   314  2149 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 15:45:03.777   314  2149 V AudioFlinger: createTrack() lSessionId: 20
08-30 15:45:03.778   314  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:03.778   314  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:03.778  1850  2453 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:03.778  1850  2453 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:03.778  1034  1993 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:03.778  1034  1993 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:03.778   314  1396 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:03.778   314  1396 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:03.779  6929  6944 V Aud,ioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:03.779  6929  6944 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 15:45:03.779  1034  1921 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:03.779  6929  6944 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:03.779  6929  6944 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 15:45:03.779  1034  1921 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:03.779  1602  2119 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:03.779  1602  2119 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:03.779  1602  2119 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:03.779  1602  2119 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:03.780  1850  2453 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:03.780  1850  2453 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:03.780  3459  3475 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:03.780  3459  3475 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:03.780  3459  3475 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:03.780  3459  3475 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:03.780  6929  6929 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 15:45:03.780   314  1402 V AudioFlinger: acquiring 20 from 6929, for 6929
08-30 15:45:03.780   314  1402 V AudioFlinger:  added new entry for 20
08-30 15:45:03.780  6929  6929 V ToneGenerator: ToneGenerator INIT OK, time: 129239
08-30 15:45:03.780  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
,08-30 15:45:03.781  6929  7420 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 15:45:03.781  6929  7420 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:45:03.781  6929  7420 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:45:03.782  6929  7420 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 15:45:03.783   314  2149 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6929
08-30 15:45:03.783   314  2149 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 15:45:03.783   314  2149 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 15:45:03.783   314  2149 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 15:45:03.783   314  2149 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 15:45:03.783   314  2149 V voice   : voice_set_parameters: exit with code(0)
08-30 15:45:03.783   314  2149 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 15:45:03.783   314  2149 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 15:45:03.783   314  2149 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 15:45:03.783   314  2149 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 15:45:03.783   314  2149 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 15:45:03.783   314  2149 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 15:45:03.784  6929  7420 V ToneGenerator: ToneGenerator destructor
08-30 15:45:03.784  6929  7420 V ToneGenerator: stopTone
08-30 15:45:03.784  6929  7420 V ToneGenerator: Delete Track: 0xb4928080
08-30 15:45:03.785  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:03.785  6929  6929 D HeadsetStateMachine: Proxy object connected
08-30 15:45:03.785  6929  6929 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 15:45:03.785  6929  6929 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 15:45:03.788  6929  6929 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:45:03.790  6929  6929 D A2dpService: Received start request. Starting profile...
08-30 15:45:03.790  6929  6929 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 15:45:03.791  6929  7420 V AudioTrack: ~AudioTrack, releasing session id from 6929 on behalf of 6929
08-30 15:45:03.792   314  1403 V AudioFlinger: releasing 20 from 6929 for 6929
08-30 15:45:03.792   314  1403 V AudioFlinger:  decremented refcount to 0
08-30 15:45:03.792   314  1403 V AudioFlinger: purging stale effects
08-30 15:45:03.792   314  1403 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 15:45:03.792   314  1403 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 15:45:03.792  6929  6929 V Avrcp   : make
08-30 15:45:03.792   314  1258 V AudioPolicyService: AudioCommandThread() waking up
08-30 15:45:03.792   314  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 15:45:03.792   314  1258 V AudioPolicyManager: releaseOutput() 2
08-30 15:45:03.792   314  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 15:45:03.792   314  1403 V AudioFlinger: PlaybackThread::Track destructor
08-30 15:45:03.792   314  1403 V AudioFlinger: removeClient_l() pid 6929, calling pid 314
08-30 15:45:03.793  6929  6929 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 15:45:03.793  6929  6929 I bluedroid-qcom: get_profile_interface avrcp
08-30 15:45:03.793  6929  7401 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:45:03.800  6929  7401 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:45:03.804  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:03.805  6929  6929 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 15:45:03.808  6929  6929 E AudioManager: No RCC entry present to update
08-30 15:45:03.808  6929  6929 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 15:45:03.810  6929  6929 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 15:45:03.810  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 15:45:03.810  6929  6929 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 15:45:03.814  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 15:45:03.815  6929  7401 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:45:03.872  6929  7401 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:45:03.876  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 15:45:03.876  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:03.876  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:45:03.876  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 15:45:03.878  6929  7401 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:45:03.884  6999  6999 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 15:45:03.888  6929  7401 V LGMDMManager: Create singleton instance
,08-30 15:45:03.890  6929  7401 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 15:45:03.891  6999  6999 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@159a3646
08-30 15:45:03.891  6999  6999 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:45:03.891  6999  6999 D AppUp4:CustFacade: isPhone : true
08-30 15:45:03.892  6999  6999 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:45:03.893  6999  6999 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 15:45:03.900  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:03.900  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 15:45:03.902  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:03.905  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:03.909  4333  7453 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:45:03.911  7043  7043 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 15:45:03.917  4333  7454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:03.917  4333  7454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 15:45:03.918  1034  1575 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:45:03.918  1034  1575 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:45:03.930  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 15:45:03.930  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:45:03.931  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 15:45:03.933  6946  7457 W FormManager: Network not available. Please check & try again.
08-30 15:45:03.935  7074  7074 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 15:45:03.935  7074  7074 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 15:45:03.935  7043  7455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:03.941  1034  7138 D NetUtils: dhcp_do_request failed : wlan0 (new)
08-30 15:45:03.942  6946  7458 V FormManager: Network unavailable.
08-30 15:45:03.942  1034  7138 V LgDhcpStateMachineHelper: [getKeyforDhcp] getBSSID, getSSID is null 
08-30 15:45:03.942  1034  7138 E DhcpStateMachine: DHCP failed on wlan0: DHCP result was failed
,08-30 15:45:03.944  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:45:3
08-30 15:45:03.946  6946  7458 V FormManager: Network unavailable.
08-30 15:45:03.946  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 15:45:03.946  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:45:03.947  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:45:03.947  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-30 15:45:03.947  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@190e7534
08-30 15:45:03.948  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 15:45:03.948  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:45:03.948  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 15:45:03.948  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 15:45:03.948  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:45:3
08-30 15:45:03.951  7421  7421 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 15:45:03.952  7421  7421 W LG Account v2.2: No ProfileInfo entries
08-30 15:45:03.952  7421  7421 I LG Account v2.2: isEnabled: false
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]Country: EU
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]Operator: OPEN
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]Ranking support: false
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]Comfort support: false
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]Accessory: true
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]Health device: true
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]Extra Pedometer: false
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]Blood glucose device: false
08-30 15:45:03.952  7421  7421 I Feature : [Lifetracker]Device Number: 3
08-30 15:45:03.971  6824  6824 D BluetoothPermissionRequest: onReceive
,08-30 15:45:03.972  1034  1993 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 15:45:03.974  6390  6390 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 15:45:03.975  6390  6424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 15:45:03.977  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 15:45:03.980  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 15:45:03.981  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 15:45:03.981  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 15:45:03.981  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 15:45:03.981  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:45:03.981  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 15:45:03.981  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 15:45:03.981  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 15:45:03.981  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:45:03.981  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 15:45:03.982  6824  6824 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:45:03.982  6929  6929 I BluetoothA2dpServiceJni: classInitNative
08-30 15:45:03.982  6929  6929 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:45:03.982  6929  6929 D A2dpStateMachine: make
08-30 15:45:03.983  6929  6929 I bluedroid-qcom: get_profile_interface a2dp
,08-30 15:45:03.983  6929  7463 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 15:45:03.985  6929  6929 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:45:03.985  6929  6929 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 15:45:03.987  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:03.987  6929  7462 D A2dpStateMachine: Enter Disconnected: -2
08-30 15:45:03.987  6929  7420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 15:45:03.988  6929  7420 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 15:45:03.988  6929  6929 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 15:45:03.988  6929  7420 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 15:45:03.989  6929  6929 D HidService: Received start request. Starting profile...
08-30 15:45:03.989  6929  6929 I bluedroid-qcom: get_profile_interface hidhost
08-30 15:45:03.990  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:03.990  6929  6929 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 15:45:03.991  6929  6929 D HealthService: Received start request. Starting profile...
08-30 15:45:03.993  6929  6929 I bluedroid-qcom: get_profile_interface health
08-30 15:45:03.993  6929  6929 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 15:45:03.993  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:03.994  6929  6929 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 15:45:03.995  6929  6929 D PanService: Received start request. Starting profile...
08-30 15:45:03.995  6929  6929 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 15:45:03.995  6929  6929 I bluedroid-qcom: get_profile_interface pan
08-30 15:45:03.996  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:04.001  6929  6929 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 15:45:04.001  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:04.002  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 15:45:04.002  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:04.002  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:45:04.002  6999  6999 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 15:45:04.002  6929  6929 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 15:45:04.003  6999  6999 I AppUp4:CustModeStarterReceiver: onReceive
08-30 15:45:04.005  6999  6999 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@159a3646
08-30 15:45:04.005  6999  6999 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:45:04.005  6999  6999 D AppUp4:CustFacade: isPhone : true
,08-30 15:45:04.007  6929  6929 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 15:45:04.007  6999  6999 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:45:04.007  6999  6999 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-30 15:45:04.010  6929  6929 D BtGatt.GattService: Received start request. Starting profile...
08-30 15:45:04.010  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:04.010  6929  6929 D BtGatt.GattService: start()
08-30 15:45:04.010  6929  6929 I bluedroid-qcom: get_profile_interface gatt
08-30 15:45:04.010  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:45:04.010  6929  6929 D BtGatt.AdvertiseManager: advertise manager created
08-30 15:45:04.011  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:04.013  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:04.015  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:04.015  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:04.016  6929  6929 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 15:45:04.016  6929  6929 V BluetoothMapService: BluetoothMapBinder()
08-30 15:45:04.017  4333  7470 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 15:45:04.017  6929  6929 D BluetoothMapService: Received start request. Starting profile...
08-30 15:45:04.017  6929  6929 D BluetoothMapService: start()
08-30 15:45:04.020  6929  6929 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 15:45:04.020  6929  6929 D BluetoothMapEmailAppObserver: createReceiver()
08-30 15:45:04.021  6929  6929 D BluetoothMapEmailAppObserver: initObservers()
08-30 15:45:04.021  6929  6929 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 15:45:04.021  7043  7043 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 15:45:04.022  4333  7471 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:04.022  4333  7471 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:45:04.027  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:04.030  6929  6929 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 15:45:04.033  6929  6929 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:45:04.036  3459  3459 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 15:45:04.036  3459  3459 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:04.036  3459  3459 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 15:45:04.037  6929  6929 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:45:04.037  6929  6929 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 15:45:04.039  6929  6929 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:45:04.039  7074  7074 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 15:45:04.040  7074  7074 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 15:45:04.041  6929  6929 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 15:45:04.042  6929  6929 V BluetoothMapService: Handler(): got msg=1
,08-30 15:45:04.044  6929  7401 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 15:45:04.044  6929  7401 I bluedroid-qcom: enable
08-30 15:45:04.044  6929  7477 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 15:45:04.044  6929  7401 I bt_hci_bdroid: init
08-30 15:45:04.045  6929  7401 I bt_vendor: bt-vendor : init
08-30 15:45:04.045  6929  7401 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 15:45:04.045  6929  7401 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 15:45:04.045  6929  7401 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 15:45:04.045  6929  7401 D bt_userial_mct: userial_init
08-30 15:45:04.045  6929  7477 I bt-btu  : btu_task pending for preload complete event
,08-30 15:45:04.045  6946  7473 W FormManager: Network not available. Please check & try again.
08-30 15:45:04.046  6929  7401 D bt_hci_bdroid: set_power 1
08-30 15:45:04.046  6929  7401 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 15:45:04.046  6929  7401 I bt_vendor: Starting hciattach daemon
08-30 15:45:04.046  6929  7401 I bt_vendor: try to set true
08-30 15:45:04.039  7480  7480 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:04.048  6929  6929 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.039  7480  7480 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:04.050  7139  7139 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:45:4
08-30 15:45:04.050  7139  7139 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 15:45:04.051  7139  7139 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:45:04.051  7139  7139 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:45:04.051  7139  7139 D WeatherAncestor: connectivity changed - connection : true
08-30 15:45:04.051  7139  7139 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@190e7534
08-30 15:45:04.052  7139  7139 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 15:45:04.052  7139  7139 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:45:04.052  7139  7139 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 15:45:04.052  7139  7139 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 15:45:04.052  7139  7139 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:45:4
08-30 15:45:04.053  6929  6929 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:45:04.053  6929  6929 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:45:04.054  6929  6929 V BluetoothSapReceiver: SapReceiver onReceive 
,08-30 15:45:04.054  6929  6929 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.054  6946  7474 V FormManager: Network unavailable.
08-30 15:45:04.054  6929  6929 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-30 15:45:04.057  7043  7475 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:04.061  6946  7474 V FormManager: Network unavailable.
08-30 15:45:04.061  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
08-30 15:45:04.097  1034  1049 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7486 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 15:45:04.118  7498  7498 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 15:45:04.128  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 15:45:04.140  7486  7486 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 15:45:04.144  1034  7138 V LgDhcpStateMachineHelper: [getKeyforDhcp] getBSSID, getSSID is null 
08-30 15:45:04.144  1034  7138 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 15:45:04.144  1034  7138 D DhcpStateMachine: StoppedState
08-30 15:45:04.145  1034  7138 D DhcpStateMachine: StoppedState{ when=-3s591ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:04.145  1034  7138 D DhcpStateMachine: StoppedState{ when=-3s550ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:04.146  1034  1391 E WifiStateMachine:  InitialState CMD_POST_DHCP_ACTION 2 0 FAIL 
08-30 15:45:04.147  1034  1391 E WifiStateMachine:  DefaultState CMD_POST_DHCP_ACTION 2 0 FAIL 
08-30 15:45:04.148  1034  1391 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
08-30 15:45:04.149  1034  1391 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 15:45:04.151  7507  7507 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-30 15:45:04.151  1034  1957 I ActivityManager: Killing 7314:com.lge.bnr/1000 (adj 15): empty #17
08-30 15:45:04.158  7508  7508 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 15:45:04.168  7509  7509 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-30 15:45:04.176  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 15:45:04.199  7512  7512 I libmdmdetect: ESOC framework not supported
08-30 15:45:04.199  7512  7512 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 15:45:04.204  1034  1574 W libprocessgroup: failed to open /acct/uid_1000/pid_7314/cgroup.procs: No such file or directory
,08-30 15:45:04.208  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{16b044 type 2 when 129625 com.google.android.gms} when 129625
08-30 15:45:04.211  7512  7512 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 15:45:04.211  7512  7512 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 15:45:04.211  7512  7512 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 15:45:04.211  7512  7512 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 15:45:04.211  7512  7512 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 15:45:04.211  7512  7512 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 15:45:04.211  7512  7512 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 15:45:04.214   309  7515 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 15:45:04.215  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 15:45:04.218  6877  6877 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 15:45:04.218  6877  6877 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7613
08-30 15:45:04.256  7512  7513 E QC-QMI  : qmi_client [7512] 14: failed to locate client data
,08-30 15:45:04.257   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-30 15:45:04.258   481   481 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-30 15:45:04.307  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 15:45:04.325  7517  7517 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 15:45:04.398  6929  7401 I bt_vendor: bluetooth satus is on
,08-30 15:45:04.398  6929  7401 D bt_hci_bdroid: preload
08-30 15:45:04.398  6929  7479 D bt_userial_mct: userial_open(port:0)
08-30 15:45:04.398  6929  7479 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 15:45:04.402  6929  7479 I bt_vendor: Done intiailizing UART
,08-30 15:45:04.407  6929  7479 I bt_vendor: Done intiailizing UART
08-30 15:45:04.407  6929  7479 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 15:45:04.409  6929  7479 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 15:45:04.409  6929  7477 I bt-btu  : btu_task received preload complete event
08-30 15:45:04.409  6929  7520 D bt_userial_mct: Entering userial_read_thread()
08-30 15:45:04.411  6929  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 15:45:04.411  6929  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-30 15:45:04.423  6929  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 15:45:04.434  6929  7477 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 15:45:04.435  6929  7477 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 15:45:04.435  6929  7477 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 15:45:04.435  6929  7477 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 15:45:04.435  6929  7477 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 15:45:04.435  6929  7477 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 15:45:04.435  6929  7477 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 15:45:04.487  6929  7477 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 15:45:04.489  6929  7477 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ee061 
08-30 15:45:04.489  6929  7477 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ee061 
,08-30 15:45:04.505  6929  7405 E bt-btif : Calling BTA_HhEnable
08-30 15:45:04.505  6929  7477 W bt-l2cap: btif_storage_get_adapter_property service_mask
08-30 15:45:04.505  6929  7405 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 15:45:04.505  6929  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 15:45:04.505  6929  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 15:45:04.505  6929  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 15:45:04.505  6929  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 15:45:04.506  6929  7405 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 15:45:04.507  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 15:45:04.508  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-30 15:45:04.509  6929  7405 D BluetoothAdapterProperties: Name is: G3
08-30 15:45:04.512  6929  7405 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:45:04.512  6929  7405 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:45:04.512  6929  7405 D bt_hci_bdroid: postload
08-30 15:45:04.513  6929  7479 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:45:04.513  6929  7477 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 15:45:04.514  6929  7405 D bte_conf: Device ID record 1 : primary
,08-30 15:45:04.514  6929  7405 D bte_conf:   vendorId            = 00c4
08-30 15:45:04.514  6929  7405 D bte_conf:   vendorIdSource      = 0001
08-30 15:45:04.514  6929  7405 D bte_conf:   product             = 13a1
08-30 15:45:04.514  6929  7405 D bte_conf:   version             = 1000
08-30 15:45:04.514  6929  7405 D bte_conf:   clientExecutableURL = 
08-30 15:45:04.514  6929  7405 D bte_conf:   serviceDescription  = 
08-30 15:45:04.514  6929  7405 D bte_conf:   documentationURL    = 
08-30 15:45:04.514  6929  7405 D bte_conf: bte_load_did_conf no section named DID2.
08-30 15:45:04.516  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:04.517  6929  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:04.517  6929  7477 W bt-smp  : Plain text(LSB ~ MSB) = 73 13 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:04.517  6929  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 52 df 18 1b a0 e8 a2 5d 7a 88 ab c8 f2 11 dc 
08-30 15:45:04.517  6929  7477 W bt-btm  : Stopping oneshot timer
08-30 15:45:04.517  6929  7479 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:45:04.519  6929  7479 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:45:04.519  6929  7479 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:45:04.509  7524  7524 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:04.509  7524  7524 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:04.519  6929  7405 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 15:45:04.521  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:04.525  6929  7479 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:45:04.525  6929  7401 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 15:45:04.525  6929  7401 D BluetoothAdapterProperties: ScanMode =  20
08-30 15:45:04.525  6929  7401 D BluetoothAdapterProperties: State =  11
08-30 15:45:04.525  6929  7401 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 15:45:04.526  6929  7401 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 15:45:04.526  6929  7401 D BluetoothAdapterProperties: Setting state to 12
08-30 15:45:04.526  6929  7401 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 15:45:04.526  6929  7405 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 15:45:04.527  6929  7401 I BluetoothAdapterState: Entering On State
08-30 15:45:04.528  6929  7520 E bt_mct  : hci lib postload completed
08-30 15:45:04.530  6929  7401 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 15:45:04.530  6929  7401 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 15:45:04.530  6929  7401 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 15:45:04.531  6929  7401 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 15:45:04.531  1034  1096 D BluetoothManagerService: Message: 60
08-30 15:45:04.531  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 15:45:04.531  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 15:45:04.532  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:45:04.537  6824  6840 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 15:45:04.542  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 15:45:04.545  6929  7405 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:45:04.545  6929  7405 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 15:45:04.550  6824  6824 D BluetoothMap: Proxy object connected
08-30 15:45:04.550  6824  6824 D MapProfile: Bluetooth service connected
08-30 15:45:04.550  6824  6824 D BluetoothMap: getConnectedDevices()
,08-30 15:45:04.552  6929  6944 V BluetoothMapService: getConnectedDevices()
08-30 15:45:04.552  1850  4018 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:45:04.555  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 15:45:04.556  6824  6840 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 15:45:04.558  6929  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:04.558  6929  7477 W bt-smp  : Plain text(LSB ~ MSB) = 67 d7 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:04.558  6929  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f 1e 18 14 7e 85 3d fe e7 ab c5 1a 4c ad 47 a0 
08-30 15:45:04.558  6929  7477 W bt-btm  : Stopping oneshot timer
08-30 15:45:04.561  6824  6824 D BluetoothInputDevice: Proxy object connected
08-30 15:45:04.562  6824  6824 D HidProfile: Bluetooth service connected
08-30 15:45:04.562  1850  3555 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:45:04.566  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 15:45:04.566  6824  6840 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 15:45:04.568  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:45:04.569  1034  1034 D BluetoothHeadset: Proxy object connected
08-30 15:45:04.570  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:45:04.571  6824  6839 D BluetoothPan: onBluetoothStateChange on: true
08-30 15:45:04.571  6824  6839 D BluetoothPan: onBluetoothStateChange call bindService
08-30 15:45:04.575  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,08-30 15:45:04.575  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 15:45:04.575  6929  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:04.576  6929  7477 W bt-smp  : Plain text(LSB ~ MSB) = 1a 3e 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:04.576  6929  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = 18 76 3c 80 7d e8 18 33 fb 5f 6c 24 63 99 e9 c9 
08-30 15:45:04.576  6929  7477 W bt-btm  : Stopping oneshot timer
08-30 15:45:04.578  6929  7401 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 15:45:04.578  1034  1034 D BluetoothA2dp: Proxy object connected
08-30 15:45:04.582  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{b5881e0 type 2 when 130026 com.google.android.gms} when 130026
08-30 15:45:04.583  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.583  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:45:04.584  1940  2124 D LGBluetoothAPIService: Message: 1
08-30 15:45:04.584  1940  2124 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 15:45:04.589  6929  6929 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.590  6929  6929 D BluetoothMapService: STATE_ON
08-30 15:45:04.590  6929  6929 V BluetoothMapService: Handler(): got msg=1
,08-30 15:45:04.593  6929  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:04.593  6929  7477 W bt-smp  : Plain text(LSB ~ MSB) = 1f b7 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:04.593  6929  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = 01 96 fc c1 04 56 17 65 3c bd ea f5 d6 05 94 d2 
08-30 15:45:04.593  6929  7477 W bt-btm  : Stopping oneshot timer
08-30 15:45:04.593  6587  6587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 15:45:04.595  6929  6929 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 15:45:04.597  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:04.597  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:04.597  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:04.597  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:04.597  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:04.597  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:04.597  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:04.597  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:04.597  7530  7530 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 15:45:04.600  1940  2124 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 15:45:04.602  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 15:45:04.602  1034  1096 D BluetoothManagerService: Message: 40
08-30 15:45:04.602  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 15:45:04.603  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:04.608  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:04.608  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:04.608  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:04.608  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:04.608  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:04.608  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:04.608  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:04.608  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:04.609  6929  7477 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:04.609  6929  7477 W bt-smp  : Plain text(LSB ~ MSB) = 34 88 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:04.609  6929  7477 W bt-smp  : Encrypted text(LSB ~ MSB) = 99 55 31 41 54 7c c0 39 aa 04 23 34 77 81 b3 12 
08-30 15:45:04.609  6929  7477 W bt-btm  : Stopping oneshot timer
08-30 15:45:04.610  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:04.612  6824  6824 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 15:45:04.616  1034  1096 D BluetoothManagerService: Message: 30
08-30 15:45:04.618  6929  7532 D BluetoothMapMasInstance: MAS initSocket()
08-30 15:45:04.618  6929  7532 D BluetoothMapMasInstance:   masId = 00
08-30 15:45:04.618  6929  7532 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 15:45:04.618  6929  7532 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 15:45:04.618  6929  7532 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 15:45:04.620  1034  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:04.622  6929  7532 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:45:04.626  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:04.626  6929  6929 V BluetoothPbapService: Pbap Service onCreate
08-30 15:45:04.626  6929  6929 V BluetoothPbapService: Starting PBAP service
,08-30 15:45:04.628  6929  7405 D BluetoothAdapterProperties: Scan Mode:21
08-30 15:45:04.628  6929  7405 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-30 15:45:04.629  6929  6929 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 15:45:04.629  6929  6929 V BluetoothPbapService: Pbap Service onBind
08-30 15:45:04.630  6929  7532 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 15:45:04.630  6929  7532 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 15:45:04.630  6929  7532 D BluetoothMapMasInstance: Accepting socket connection...
08-30 15:45:04.632  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:04.633  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:04.638  6824  6824 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 15:45:04.639  6929  6929 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.640  6929  6929 V BluetoothPbapService: state: 12
08-30 15:45:04.640  1034  1096 D BluetoothManagerService: Message: 30
,08-30 15:45:04.644  6929  6929 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 15:45:04.645  6929  6929 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 15:45:04.646  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 15:45:04.646  6929  6929 V BluetoothPbapService: Handler(): got msg=1
08-30 15:45:04.647  1940  2124 D LGBluetoothAPIService: Message: 100
08-30 15:45:04.647  6929  6929 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 15:45:04.647  1940  2124 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 15:45:04.648  6824  6824 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:45:04.648  6824  6824 D PanProfile: Bluetooth service connected
08-30 15:45:04.650  6824  6824 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 15:45:04.650  6929  7538 V BluetoothPbapService: Pbap Service initSocket
08-30 15:45:04.651  1034  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:04.652  6824  6824 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 15:45:04.659  6929  7538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:45:04.661  6824  6824 D BluetoothPbap: Proxy object connected
08-30 15:45:04.661  6929  6929 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:45:04.661  6929  6929 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.661  6929  6929 V BluetoothPbapReceiver: ***********state = 12
08-30 15:45:04.662  6824  6824 D PbapServerProfile: Bluetooth service connected
08-30 15:45:04.663  6824  6824 D BluetoothA2dp: Proxy object connected
08-30 15:45:04.663  6824  6824 D A2dpProfile: Bluetooth service connected
08-30 15:45:04.663  6929  7538 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 15:45:04.664  6929  7538 V BluetoothPbapService: Succeed to create listening socket 
08-30 15:45:04.664  6929  7538 V BluetoothPbapService: Accepting socket connection...
,08-30 15:45:04.665  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:45:04.666  2186  2186 D c       : Getting all permits...
08-30 15:45:04.666  2186  2186 D a       : Opening database...
08-30 15:45:04.666  6824  6824 D BluetoothHeadset: Proxy object connected
08-30 15:45:04.668  6824  6824 D HeadsetProfile: Bluetooth service connected
08-30 15:45:04.671  2186  2186 D a       : Opening database auth.proximity.permit_store...
08-30 15:45:04.671  2186  2186 D a       : Closing database...
08-30 15:45:04.682  6824  6824 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:45:04.698  6824  6824 D BluetoothPermissionRequest: onReceive
,08-30 15:45:04.702  6824  6824 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 15:45:04.705  6824  6824 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:45:04.710  6929  6929 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-30 15:45:04.712  6929  6929 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 15:45:04.721  6929  6929 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 15:45:04.752  6929  6929 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 15:45:04.752  6929  6929 V BtOppService: onCreate
,08-30 15:45:04.757  6929  6929 V BluetoothOppNotification: send message
08-30 15:45:04.760  6929  6929 V BtOppService: Starting RfcommListener
08-30 15:45:04.768  6929  6929 D BluetoothOppPreference: Dumping Names:  
08-30 15:45:04.769  6929  6929 D BluetoothOppPreference: {}
08-30 15:45:04.769  6929  6929 D BluetoothOppPreference: Dumping Channels:  
08-30 15:45:04.769  6929  6929 D BluetoothOppPreference: {}
08-30 15:45:04.769  6929  6929 V BtOppService: onStartCommand
,08-30 15:45:04.775  6929  7547 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 15:45:04.776  6929  7544 V BtOppService: Deleted complete outbound shares, number =  0
08-30 15:45:04.776  6929  7547 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 15:45:04.778  6929  6929 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.779  6929  6929 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 15:45:04.780  6929  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27d4eca9 on behalf of 
08-30 15:45:04.780  6929  7544 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 15:45:04.781  6929  7544 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 15:45:04.782  6929  6929 V BluetoothOppNotification: new notify threadi!
,08-30 15:45:04.783  6929  6929 V BluetoothOppNotification: send delay message
08-30 15:45:04.786  6929  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 15:45:04.786  6929  6929 V BtOppService: start RfcommListener
08-30 15:45:04.789  6929  6929 V BtOppService: RfcommListener started
08-30 15:45:04.790  6929  6929 V BtOppService: ContentObserver received notification
08-30 15:45:04.790  6929  6929 V BtOppService: ContentObserver received notification
08-30 15:45:04.791  6929  7544 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@97a722e on behalf of 
08-30 15:45:04.791  6929  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1580d1cf on behalf of 
08-30 15:45:04.791  6929  7549 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 15:45:04.792  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:04.793  6929  7549 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:45:04.793  6929  7547 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 15:45:04.793  6929  7547 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 15:45:04.795  6929  7549 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-30 15:45:04.796  6929  7549 V BtOppRfcommListener: Started RFCOMM listener....
08-30 15:45:04.796  6929  7549 I BtOppRfcommListener: Accept thread started.
08-30 15:45:04.796  6929  7549 V BtOppRfcommListener: Accepting connection...
08-30 15:45:04.796  6929  7548 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 15:45:04.807  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:04.807  6929  6929 V BluetoothFtpService: Ftp Service onCreate
08-30 15:45:04.807  6929  6929 I BluetoothFtpService: Ftp Service onCreate
08-30 15:45:04.808  6929  6929 V BluetoothFtpService: Ftp Service onStartCommand
08-30 15:45:04.808  6929  6929 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.808  6929  6929 V BluetoothFtpService: Starting Listening on sockets
08-30 15:45:04.808  6929  6929 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:45:04.808  6929  6929 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:45:04.809  6929  6929 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:45:04.809  6929  6929 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.809  6929  6929 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 15:45:04.809  6929  6929 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 15:45:04.812  6929  6929 V BluetoothFtpService: Handler(): got msg=1
,08-30 15:45:04.815  6929  6929 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 15:45:04.815  6929  6929 V BluetoothFtpService: Ftp Service initSocket
08-30 15:45:04.818  1034  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:04.819  6929  6929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:45:04.828  6929  6929 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-30 15:45:04.828  6929  6929 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-30 15:45:04.833  6929  7551 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 15:45:04.837  7174  7212 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-30 15:45:04.846  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:04.846  6929  6929 V BluetoothSapService: Sap Service onCreate
,08-30 15:45:04.849  6929  6929 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:04.849  6929  6929 V BluetoothSapService: state: 12
08-30 15:45:04.849  6929  6929 V BluetoothSapService: Starting SAP server process
08-30 15:45:04.852  6929  6929 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 15:45:04.849  7553  7553 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:04.849  7553  7553 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:04.854  6929  7554 V BluetoothSapService: Sap Service initRfcommSocket
08-30 15:45:04.855  1034  1751 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:04.856  6929  7554 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:45:04.862  6929  7554 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
08-30 15:45:04.862  6929  7554 V BluetoothSapService: Succeed to create listening socket 
08-30 15:45:04.862  6929  7554 V BluetoothSapService: Accepting socket connection...
,08-30 15:45:04.867  7553  7553 V BT_SAP  : Event pipe created
08-30 15:45:04.867  7553  7553 V BT_SAP  : create_server_socket qcom.sap.server
08-30 15:45:04.867  7553  7553 V BT_SAP  : created socket fd 6
08-30 15:45:04.964  1034  1049 I art     : Explicit concurrent mark sweep GC freed 93289(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.014ms total 167.056ms
08-30 15:45:04.965  6929  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@208dcd48 on behalf of 
08-30 15:45:04.965  6929  7547 V BluetoothOppNotification: update too frequent, put in queue
,08-30 15:45:04.967  6929  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 15:45:04.968  6929  7547 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-30 15:45:04.971  6929  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e9c87e1 on behalf of 
08-30 15:45:04.973  6929  7548 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 15:45:04.974  6929  7548 V BluetoothOppNotification: outbound notification was removed.
08-30 15:45:04.975  6929  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 15:45:04.976  6929  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33129906 on behalf of 
08-30 15:45:04.976  6929  7548 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 15:45:04.978  6929  7548 V BluetoothOppNotification: inbound notification was removed.
,08-30 15:45:04.978  6929  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 15:45:04.982  6929  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a2f2bc7 on behalf of 
08-30 15:45:05.356  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{127d4428 type 2 when 130786 com.google.android.gms} when 130786
,08-30 15:45:05.464   309  7159 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 15:45:05.476  1034  7135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: errno 64 (Machine is not on the network)
08-30 15:45:05.477  1034  7135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s847ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:05.477  1034  7135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s847ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:05.477  1034  7135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 15:45:05.591  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:05.591  1034  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:45:05.629  1034  1391 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 15:45:05.630  1034  1391 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 15:45:05.755  1034  1049 I ActivityManager: Killing 6843:com.lge.sync/1000 (adj 15): empty #17
,08-30 15:45:05.781  1034  1404 D WifiService: Client connection lost with reason: 4
,08-30 15:45:05.785  6929  6929 V BluetoothOppNotification: new notify threadi!
08-30 15:45:05.785  6929  6929 V BluetoothOppNotification: send delay message
08-30 15:45:05.787  6929  7565 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 15:45:05.788  6929  7565 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@185675f4 on behalf of 
08-30 15:45:05.789  6929  7565 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 15:45:05.790  6929  7565 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 15:45:05.791  6929  7565 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2378c11d on behalf of 
08-30 15:45:05.792  6929  7565 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 15:45:05.795  6929  7565 V BluetoothOppNotification: outbound notification was removed.
08-30 15:45:05.795  6929  7565 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 15:45:05.797  6929  7565 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1eaf3f92 on behalf of 
08-30 15:45:05.798  6929  7565 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 15:45:05.800  6929  7565 V BluetoothOppNotification: inbound notification was removed.
08-30 15:45:05.800  6929  7565 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 15:45:05.801  6929  7565 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32e8bd63 on behalf of 
08-30 15:45:05.805  1034  1993 W libprocessgroup: failed to open /acct/uid_1000/pid_6843/cgroup.procs: No such file or directory
,08-30 15:45:05.863  1034  2029 I ActivityManager: Killing 7354:com.lge.clock/u0a10 (adj 15): empty #17
,08-30 15:45:05.895  1034  1751 W libprocessgroup: failed to open /acct/uid_10010/pid_7354/cgroup.procs: No such file or directory
,08-30 15:45:06.594  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:45:06.595  1034  2031 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@290a6541 mBinding = false
,08-30 15:45:06.628  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:45:06.628  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:45:06.628  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-30 15:45:06.629  1034  1096 D BluetoothManagerService: Message: 2
08-30 15:45:06.630  1034  1096 D BluetoothManagerService: Sending off request.
08-30 15:45:06.631  6929  6944 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 15:45:06.632  6929  7401 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 15:45:06.632  6929  7401 D BluetoothAdapterProperties: Setting state to 13
08-30 15:45:06.632  6929  7401 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 15:45:06.632  6929  7401 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 15:45:06.633  6929  7401 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 15:45:06.634  6929  7405 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:45:06.636  6929  7401 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-30 15:45:06.641  6929  7401 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 15:45:06.644  6929  7532 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 15:45:06.644  6929  7532 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:45:06.644  6929  7532 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 15:45:06.644  6929  7532 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 15:45:06.644  6929  7532 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 15:45:06.644  6929  7532 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 15:45:06.644  6929  7532 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 15:45:06.644  6929  7532 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 15:45:06.644  6929  7538 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:45:06.644  6929  7549 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:45:06.645  6929  7551 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:45:06.645  6929  7554 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:45:06.645  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 15:45:06.645  6929  7477 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 15:45:06.658  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 15:45:06.658  6929  7477 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-30 15:45:06.666  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:45:06.666  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:06.666  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:06.666  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:06.666  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:06.666  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:45:06.666  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:06.666  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:06.666  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:06.668  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:45:06.668  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:06.670  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:45:06.670  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:06.670  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:06.670  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:06.670  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:06.670  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:45:06.670  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:06.670  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:06.670  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:06.675  6587  6587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:45:06.675  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:06.677  1034  1096 D BluetoothManagerService: Message: 60
08-30 15:45:06.677  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 15:45:06.677  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 15:45:06.680  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:06.682  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 15:45:06.688  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:06.691  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:06.693  6929  6929 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:06.693  6929  6929 D BluetoothMapService: STATE_TURNING_OFF
08-30 15:45:06.693  6929  6929 V BluetoothMapService: Handler(): got msg=4
08-30 15:45:06.693  6929  6929 D BluetoothMapService: MAP Service closeService in
08-30 15:45:06.693  6929  6929 D BluetoothMapMasInstance: MAP Service shutdown
08-30 15:45:06.694  6929  6929 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:45:06.694  6929  6929 V BluetoothMapService: MAP Service closeService out
08-30 15:45:06.695  6929  6929 V BtOppService: Receiver DISABLED_ACTION 
08-30 15:45:06.695  6929  6929 I BtOppRfcommListener: stopping Accept Thread
08-30 15:45:06.695  6929  6929 V BtOppRfcommListener: close mBtServerSocket
,08-30 15:45:06.697  6929  7549 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 15:45:06.698  6929  6929 V BtOppRfcommListener: waiting for thread to terminate
08-30 15:45:06.699  6929  6929 V BtOppRfcommListener: done waiting for thread to terminate
08-30 15:45:06.702  6824  6824 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 15:45:06.710  6824  6824 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 15:45:06.714  6929  6929 V BtOppService: onDestroy
08-30 15:45:06.716  6929  6929 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 15:45:06.721  6929  6929 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:45:06.721  6929  6929 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:06.721  6929  6929 V BluetoothPbapReceiver: ***********state = 13
08-30 15:45:06.725  6929  6929 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-30 15:45:06.728  6929  6929 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:45:06.729  6929  6929 V BluetoothPbapService: state: 13
,08-30 15:45:06.729  6929  6929 V BluetoothPbapService: Pbap Service closeService in
08-30 15:45:06.732  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:45:06.733  6929  6929 V BluetoothPbapService: successfully stopped pbap service
08-30 15:45:06.734  6929  6929 V BluetoothPbapService: Pbap Service closeService out
08-30 15:45:06.735  6929  6929 V BluetoothPbapService: Pbap Service onDestroy
08-30 15:45:06.735  6929  6929 V BluetoothPbapService: Pbap Service closeService in
08-30 15:45:06.735  6929  6929 V BluetoothPbapService: Pbap Service closeService out
08-30 15:45:06.735  6929  6929 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 15:45:06.753  6824  6824 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:45:06.765  6824  6824 D BluetoothPbap: Proxy object disconnected
08-30 15:45:06.765  6824  6824 D PbapServerProfile: Bluetooth service disconnected
08-30 15:45:06.772  6824  6824 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 15:45:06.780  6824  6824 D BluetoothPermissionRequest: onReceive
08-30 15:45:06.780  6824  6824 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 15:45:06.786  6824  6824 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 15:45:06.790  6929  6929 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 15:45:06.790  6929  6929 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 15:45:06.791  6929  6929 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 15:45:06.795  6929  6929 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:06.795  6929  6929 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 15:45:06.796  6929  6929 V BluetoothFtpService: Ftp Service onStartCommand
08-30 15:45:06.796  6929  6929 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:06.796  6929  6929 V BluetoothFtpService: Ftp Service closeService
08-30 15:45:06.797  6929  6929 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-30 15:45:06.798  6929  6929 V BluetoothFtpService: successfully stopped ftp service
08-30 15:45:06.799  6929  6929 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:45:06.799  6929  6929 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:45:06.799  6929  6929 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:45:06.799  6929  6929 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:06.799  6929  6929 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 15:45:06.799  6929  6929 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 15:45:06.800  6929  6929 V BluetoothFtpService: Ftp Service onDestroy
08-30 15:45:06.800  6929  6929 V BluetoothFtpService: Ftp Service closeService
,08-30 15:45:06.804  6929  6929 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:06.804  6929  6929 V BluetoothSapService: state: 13
08-30 15:45:06.804  6929  6929 V BluetoothSapService: Stopping SAP server process
08-30 15:45:06.805  6929  6929 V BluetoothSapService: Sap Service closeSapService in
08-30 15:45:06.805  6929  6929 V BluetoothSapService: Close listen Socket : 
08-30 15:45:06.805  6929  6929 V BluetoothSapService: Close rfcomm Socket : 
08-30 15:45:06.806  6929  6929 V BluetoothSapService: Close sapd  Socket : 
08-30 15:45:06.809  6929  6929 V BluetoothSapService: Sap Service closeSapService out
08-30 15:45:06.809  6929  6929 V BluetoothSapService: Sap Service onDestroy
08-30 15:45:06.809  6929  6929 V BluetoothSapService: Sap Service closeSapService in
08-30 15:45:06.809  6929  6929 V BluetoothSapService: Close listen Socket : 
08-30 15:45:06.809  6929  6929 V BluetoothSapService: Close rfcomm Socket : 
08-30 15:45:06.809  6929  6929 V BluetoothSapService: Close sapd  Socket : 
08-30 15:45:06.809  6929  6929 V BluetoothSapService: Sap Service closeSapService out
08-30 15:45:06.820  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3f2ab827 type 2 when 132261 com.google.android.gms} when 132261
,08-30 15:45:06.825   309  7587 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 15:45:06.826  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 15:45:07.564  6929  7405 D bt_hci_bdroid: cleanup
,08-30 15:45:07.573  6929  7520 I bt_userial_mct: exiting userial_read_thread
08-30 15:45:07.573  6929  7520 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 15:45:07.573  6929  7479 I bt_lpm  : LPM is already off!!!
08-30 15:45:07.574  6929  7477 W bt-btif : ag scb idx 1 not allocated
08-30 15:45:07.574  6929  7477 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:45:07.574  6929  7477 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:45:07.574  6929  7477 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 15:45:07.575  6929  7405 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 15:45:07.575  6929  7479 I bt_vendor: hw_epilog_process
08-30 15:45:07.576  6929  7405 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 15:45:07.576  6929  7405 D bt_userial_mct: userial_close
08-30 15:45:07.576  6929  7405 E bt_userial_mct: pthread_join() FAILED result:3
08-30 15:45:07.576  6929  7405 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 15:45:07.582  6929  7405 D bt_hci_bdroid: set_power 0
08-30 15:45:07.582  6929  7405 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 15:45:07.582  6929  7405 I bt_vendor: bluetooth satus is on
08-30 15:45:07.582  6929  7405 I bt_vendor: bt-vendor : resetting BT status
08-30 15:45:07.582  6929  7405 I bt_vendor: Starting hciattach daemon
08-30 15:45:07.582  6929  7405 I bt_vendor: try to set false
,08-30 15:45:07.585  6929  7405 I bt_vendor: Starting hciattach daemon
08-30 15:45:07.585  6929  7405 I bt_vendor: try to set false
,08-30 15:45:07.592  6929  7405 I bt_vendor: cleanup
08-30 15:45:07.593  6929  7477 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 15:45:07.593  6929  7405 I GKI_LINUX: GKI_exit_task 0 done
08-30 15:45:07.593  6929  7405 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 15:45:07.594  6929  7401 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 15:45:07.599  6929  6929 D HeadsetService: Received stop request...Stopping profile...
,08-30 15:45:07.603  6929  6929 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 15:45:07.603  6929  6929 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:45:07.603  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:07.604  6929  7420 D HeadsetStateMachine: Exit Disconnected: -1
08-30 15:45:07.609  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 15:45:07.609  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 15:45:07.609  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 15:45:07.610  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-30 15:45:07.610  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 15:45:07.615  6929  7401 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 15:45:07.615  6929  6929 D A2dpService: Received stop request...Stopping profile...
08-30 15:45:07.616  6929  7462 D A2dpStateMachine: Exit Disconnected: -1
08-30 15:45:07.617  6929  6929 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 15:45:07.619  6929  6929 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 15:45:07.619  6929  6929 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:45:07.619  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:07.621  6929  6929 D HidService: Received stop request...Stopping profile...
08-30 15:45:07.621  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:07.623  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-30 15:45:07.623  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-30 15:45:07.627  6929  6929 D HealthService: Received stop request...Stopping profile...
08-30 15:45:07.627  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:07.629  6929  6929 D PanService: Received stop request...Stopping profile...
08-30 15:45:07.630  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:07.632  6929  6929 D HeadsetStateMachine: Unbinding service...
08-30 15:45:07.633  6929  6929 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:45:07.633  6929  6929 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:45:07.633  6929  6929 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:45:07.633  6929  6929 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:45:07.633  6929  6929 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 15:45:07.633  6929  6929 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:45:07.633  6929  6929 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 15:45:07.633  6929  6929 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 15:45:07.635  6929  6929 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 15:45:07.635  6929  6929 D BtGatt.GattService: stop()
08-30 15:45:07.636  6929  6929 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 15:45:07.639  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:07.640  6929  6929 D BluetoothMapService: Received stop request...Stopping profile...
08-30 15:45:07.640  6929  6929 D BluetoothMapService: stop()
08-30 15:45:07.641  6929  6929 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 15:45:07.641  6929  6929 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 15:45:07.641  6929  6929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@190e7534
08-30 15:45:07.643  6929  6929 I BluetoothA2dpServiceJni: cleanupNative
08-30 15:45:07.643  6929  7463 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 15:45:07.643  6929  6929 I GKI_LINUX: GKI_exit_task 2 done
08-30 15:45:07.643  6929  6929 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 15:45:07.644  6929  6929 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 15:45:07.644  6929  6929 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 15:45:07.644  6929  6929 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 15:45:07.644  6929  6929 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:45:07.644  6929  6929 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:45:07.644  6929  6929 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:45:07.644  6929  6929 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 15:45:07.647  6929  6929 V BluetoothMapService: Handler(): got msg=4
08-30 15:45:07.647  6929  6929 D BluetoothMapService: MAP Service closeService in
08-30 15:45:07.647  6929  6929 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:45:07.647  6929  6929 V BluetoothMapService: MAP Service closeService out
,08-30 15:45:07.651  6929  7401 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 15:45:07.652  6929  7401 D BluetoothAdapterProperties: Setting state to 10
08-30 15:45:07.652  6929  7401 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 15:45:07.652  6929  6929 D BluetoothMapService: cleanup()
08-30 15:45:07.652  6929  6929 D BluetoothMapService: MAP Service closeService in
08-30 15:45:07.652  6929  6929 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:45:07.652  6929  6929 V BluetoothMapService: MAP Service closeService out
08-30 15:45:07.653  1034  1096 D BluetoothManagerService: Message: 60
08-30 15:45:07.653  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 15:45:07.653  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 15:45:07.654  6929  7401 I BluetoothAdapterState: Entering OffState
08-30 15:45:07.654  1850  3556 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:45:07.655  6824  7528 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:45:07.655  1850  3555 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:45:07.656  6824  7528 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:45:07.657  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:45:07.657  6824  7528 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:45:07.658  6824  7528 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:45:07.658  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:45:07.658  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:45:07.659  6824  7528 D BluetoothPan: onBluetoothStateChange on: false
08-30 15:45:07.659  6824  7528 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 15:45:07.666  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 15:45:07.666  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 15:45:07.669  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 15:45:07.669  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 15:45:07.669  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@290a6541 mBinding = false
08-30 15:45:07.670  1034  1096 D BluetoothManagerService: Sending unbind request.
08-30 15:45:07.675  6929  7405 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 15:45:07.677  6929  6929 I GKI_LINUX: GKI_exit_task 1 done
08-30 15:45:07.677  6929  6929 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 15:45:07.678  6929  6929 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 15:45:07.678  6929  6929 I art     : --- WEIRD: removing null entry 248
08-30 15:45:07.678  6929  6929 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 15:45:07.679  6929  6929 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 15:45:07.680  6929  6929 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 15:45:07.681  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 15:45:07.682  6929  6929 I art     : System.exit called, status: 0
08-30 15:45:07.682  6929  6929 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 15:45:07.702   314  2149 V AudioFlinger: 6929 died, releasing its sessions
08-30 15:45:07.702   314  2149 V AudioFlinger:  pid 1850 @ 0
08-30 15:45:07.702   314  2149 V AudioFlinger:  pid 3459 @ 1
08-30 15:45:07.702   314  2149 V AudioFlinger:  pid 3459 @ 2
,08-30 15:45:07.707  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-30 15:45:07.707  1940  2124 D LGBluetoothAPIService: Message: 101
08-30 15:45:07.707  1940  2124 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 15:45:07.707  1940  2124 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-30 15:45:07.707  1940  2124 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-30 15:45:07.709  6824  6824 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 15:45:07.741  1034  1884 I ActivityManager: Process com.android.bluetooth (pid 6929) has died
08-30 15:45:07.742  1034  1884 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-30 15:45:07.742  1034  1884 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 13999ms
,08-30 15:45:07.749  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:07.750  1940  2124 D LGBluetoothAPIService: Message: 2
08-30 15:45:07.750  1940  2124 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 15:45:07.750  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:45:07.753  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:07.755  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:07.755  6824  6824 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 15:45:07.755  6824  6824 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-30 15:45:07.759  6824  6824 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 15:45:07.761  1602  1602 D BluetoothAdapter: 1005674367: getState() :  mService = null. Returning STATE_OFF
08-30 15:45:07.761  1602  1602 D BluetoothAdapter: 1005674367: getState() :  mService = null. Returning STATE_OFF
08-30 15:45:07.821  1034  1050 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7617 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 15:45:07.824  6824  6824 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:45:07.900  7617  7617 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 15:45:07.901  7617  7617 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 15:45:07.902  7617  7617 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-30 15:45:07.902  7617  7617 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:45:07.923  7617  7617 D BluetoothAdapterApp: Loading JNI Library
,08-30 15:45:07.960  7617  7617 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2dccee9c Instance Count = 1
,08-30 15:45:07.967  7617  7617 D BluetoothAdapterApp: onCreate
,08-30 15:45:07.993  7617  7617 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-30 15:45:07.994  7617  7617 D ProfileConfigQcom: Adding HeadsetService
08-30 15:45:07.994  7617  7617 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 15:45:07.994  7617  7617 D ProfileConfigQcom: Adding A2dpService
08-30 15:45:07.994  7617  7617 D ProfileConfigQcom: [BTUI] HidService is supported
,08-30 15:45:07.995  7617  7617 D ProfileConfigQcom: Adding HidService
08-30 15:45:07.995  7617  7617 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 15:45:07.995  7617  7617 D ProfileConfigQcom: Adding HealthService
,08-30 15:45:07.995  7617  7617 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 15:45:07.997  7617  7617 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 15:45:07.997  7617  7617 D ProfileConfigQcom: Adding PanService
,08-30 15:45:07.997  7617  7617 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 15:45:07.997  7617  7617 D ProfileConfigQcom: Adding GattService
08-30 15:45:07.998  7617  7617 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 15:45:07.998  7617  7617 D ProfileConfigQcom: Adding BluetoothMapService
,08-30 15:45:07.998  7617  7617 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 15:45:07.999  7617  7617 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:45:08.000  7617  7617 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:45:08.001  7617  7617 V BluetoothPbapReceiver: ***********state = 10
,08-30 15:45:08.003  7617  7617 V LGMDMManagerInternal: Create singleton instance
08-30 15:45:08.119  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:45:08.123  6824  6824 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 15:45:08.125  7617  7617 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 15:45:08.126  7617  7617 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 15:45:08.127  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 15:45:08.128  1940  2124 D LGBluetoothAPIService: Message: 100
08-30 15:45:08.128  1940  2124 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 15:45:08.148  6824  6824 D BluetoothPermissionRequest: onReceive
,08-30 15:45:08.153  6824  6824 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 15:45:08.153  6824  6824 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 15:45:08.155  6824  6824 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:45:08.161  7617  7617 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-30 15:45:08.166  7617  7617 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:45:08.170  7617  7617 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:45:08.170  7617  7617 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:45:08.171  7617  7617 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:45:08.172  7617  7617 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:08.172  7617  7617 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 15:45:08.180  7486  7486 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 15:45:09.632  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 15:45:09.658  1034  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 15:45:09.707  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:09.708  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:45:09.752  1034  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7646 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 15:45:09.756  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{114aa0be type 2 when 135168 com.google.android.gms} when 135168
08-30 15:45:09.759  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 15:45:09.760  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 15:45:09.778  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 15:45:09.788  1034  1034 D administrator: Handling package changes for user 0
08-30 15:45:09.805  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 15:45:09.839  7646  7646 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 15:45:09.897  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 15:45:09.898  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 15:45:09.925  7646  7646 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:45:09.925  7646  7646 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:45:09.956  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 15:45:09.962  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 15:45:09.970  2471  2471 V GmsNetworkLocationProvi: DISABLE
08-30 15:45:09.970  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 15:45:10.005  1034  1091 D LocationProviderProxy: applying state to connected service
08-30 15:45:10.006  2471  2471 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 15:45:10.035  7646  7689 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 15:45:10.035  7646  7689 I Babel   : MmsConfig.loadMmsSettings
08-30 15:45:10.040  7646  7689 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 15:45:10.040  7646  7689 I Babel   : MmsConfig.loadFromDatabase
,08-30 15:45:10.056  7646  7689 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 15:45:10.056  7646  7689 I Babel   : MmsConfig.loadFromResources
,08-30 15:45:10.057  7646  7689 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 15:45:10.058  7646  7689 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 15:45:10.070  7646  7646 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:45:10.082  7646  7688 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 15:45:10.084  7646  7688 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 15:45:10.086  7646  7688 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 15:45:10.097  7646  7688 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 15:45:10.098  1815  7693 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 15:45:10.098  1815  7693 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 15:45:10.100  7646  7688 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 15:45:10.102  7646  7688 W AudioCapabilities: Unsupported mime audio/evrc
08-30 15:45:10.108  6999  6999 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 15:45:10.115  6999  6999 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@159a3646
08-30 15:45:10.116  6999  6999 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:45:10.116  6999  6999 D AppUp4:CustFacade: isPhone : true
08-30 15:45:10.116  6999  6999 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:45:10.116  6999  6999 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 15:45:10.128  7646  7688 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 15:45:10.128  1815  4754 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 15:45:10.134  7646  7688 W VideoCapabilities: Unsupported mime video/divx
08-30 15:45:10.136  7646  7688 W VideoCapabilities: Unsupported mime video/divx311
08-30 15:45:10.137  7646  7688 W VideoCapabilities: Unsupported mime video/divx4
08-30 15:45:10.141  7646  7688 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 15:45:10.154  7646  7688 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 15:45:10.158  7646  7688 W AudioCapabilities: Unsupported mime audio/eac3
08-30 15:45:10.159  7646  7688 W AudioCapabilities: Unsupported mime audio/ac3
08-30 15:45:10.160  7646  7688 W AudioCapabilities: Unsupported mime audio/g726
08-30 15:45:10.161  7646  7688 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 15:45:10.162  7646  7688 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 15:45:10.163  7646  7688 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 15:45:10.164  7646  7688 W VideoCapabilities: Unsupported mime video/theora
08-30 15:45:10.166  7646  7688 W VideoCapabilities: Unsupported mime video/mjpg
,08-30 15:45:10.167  1034  1574 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7697 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-30 15:45:10.214  1034  1921 I ActivityManager: Killing 7043:com.lge.email/u0a23 (adj 15): empty #17
,08-30 15:45:10.214  7697  7697 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:45:10.214  7697  7697 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:45:10.215  7697  7697 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-30 15:45:10.215  7697  7697 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 15:45:10.216  7697  7697 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 15:45:10.272  1034  1920 W libprocessgroup: failed to open /acct/uid_10023/pid_7043/cgroup.procs: No such file or directory
,08-30 15:45:10.303  7697  7697 I SystemConfig: BUILD Country: EU
,08-30 15:45:10.303  7697  7697 I SystemConfig: BUILD Operator: OPEN
,08-30 15:45:10.346  1034  1939 I ActivityManager: Killing 6946:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 15:45:10.506  1034  1884 W libprocessgroup: failed to open /acct/uid_10026/pid_6946/cgroup.procs: No such file or directory
,08-30 15:45:10.527  7697  7715 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-30 15:45:10.528  7697  7715 I SystemConfig: existFile = false
08-30 15:45:10.528  7697  7715 I SystemConfig: canReadFile = false
08-30 15:45:10.528  7697  7715 I SystemConfig: systemFeature RCS result false
08-30 15:45:10.528  7697  7715 D SystemConfig: refreshRcsSupport() :false
08-30 15:45:10.572  1034  1939 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7720 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 15:45:10.638  7720  7720 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:45:10.638  7720  7720 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 15:45:10.638  7720  7720 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 15:45:10.639  7720  7720 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 15:45:10.641  1034  1408 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-30 15:45:10.784  7720  7720 I AppConfig: Total System Memory = 2995761152
,08-30 15:45:10.795  7720  7720 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 15:45:10.882  1034  1885 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7739 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:45:10.885  1034  1885 I ActivityManager: Killing 6390:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 15:45:10.923  1034  1575 W libprocessgroup: failed to open /acct/uid_1000/pid_6390/cgroup.procs: No such file or directory
,08-30 15:45:11.153  7739  7739 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 15:45:11.263  7739  7739 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 15:45:11.263  7739  7739 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:45:11.332  7739  7739 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 15:45:11.353  7739  7739 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 15:45:11.354  7739  7739 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 15:45:11.371  7739  7739 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 15:45:11.371  7739  7739 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 15:45:11.392  1034  1751 I ActivityManager: Killing 7074:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 15:45:11.425  1034  1957 W libprocessgroup: failed to open /acct/uid_10046/pid_7074/cgroup.procs: No such file or directory
,08-30 15:45:11.429  3534  3550 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-30 15:45:11.430  3534  3550 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@dcf238a on behalf of 7739
08-30 15:45:11.434  4607  7779 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-30 15:45:11.484  1034  1885 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7780 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 15:45:11.516   345   345 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 471us total 28.436ms
,08-30 15:45:11.539   345   345 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 458us total 21.944ms
,08-30 15:45:11.560   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 19.656ms
,08-30 15:45:11.577  7739  7739 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 15:45:11.596  7739  7739 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 15:45:11.606  7780  7780 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-30 15:45:11.629  7780  7780 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 15:45:11.629  7780  7780 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-30 15:45:11.629  7780  7780 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 15:45:11.629  7780  7780 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 15:45:11.629  7780  7780 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 15:45:11.629  7780  7780 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-30 15:45:11.640   309  7811 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 15:45:11.641  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 15:45:11.645  1034  2029 I ActivityManager: Killing 7093:com.android.chrome/u0a57 (adj 15): empty #17
08-30 15:45:11.684  1034  1939 W libprocessgroup: failed to open /acct/uid_10057/pid_7093/cgroup.procs: No such file or directory
,08-30 15:45:11.844  1034  1939 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:45:11.869  4607  7779 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 435 ms] updated apps [took 435 ms] 
,08-30 15:45:12.766  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:45:12.774  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24fdcee8 added. We now have 6 listener(s)
08-30 15:45:12.774  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:12.777  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:12.777  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48bf901 added. We now have 7 listener(s)
08-30 15:45:12.777  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:12.778  6587  6687 I System.out: IsBluetoothEnabled
08-30 15:45:12.779  1034  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:12.779  1034  1992 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 15:45:12.780  1034  1096 D BluetoothManagerService: Message: 2
08-30 15:45:12.783  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:12.785  1034  1751 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:12.785  1034  1751 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 15:45:12.798  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:45:12.798  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-30 15:45:12.798  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-30 15:45:12.801  1034  1096 D BluetoothManagerService: Message: 1
08-30 15:45:12.801  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 15:45:12.826  1034  1096 D BluetoothManagerService: Message: 20
08-30 15:45:12.826  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29542da8:true
,08-30 15:45:12.830  7617  7617 D BluetoothAdapterState: make
08-30 15:45:12.835  7617  7617 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 15:45:12.835  7617  7617 I bluedroid-qcom: init
08-30 15:45:12.836  7617  7825 I BluetoothAdapterState: Entering OffState
08-30 15:45:12.837  7617  7617 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 15:45:12.837  7617  7617 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 15:45:12.837  7617  7617 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 15:45:12.837  7617  7617 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 15:45:12.837  7617  7617 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 15:45:12.839  7617  7617 I bluedroid-qcom: get_profile_interface socket
08-30 15:45:12.839  7617  7617 I bluedroid-qcom: get_profile_interface map_client
,08-30 15:45:12.843  7617  7829 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 15:45:12.839  7828  7828 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:12.848  7617  7829 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 15:45:12.839  7828  7828 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:12.857  7828  7828 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 15:45:12.857  7828  7828 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 15:45:12.857  7828  7828 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 15:45:12.863  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 15:45:12.863  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 15:45:12.864  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 15:45:12.864  1034  1096 D BluetoothManagerService: Message: 40
08-30 15:45:12.864  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 15:45:12.865  7617  7633 I bluedroid-qcom: config_hci_snoop_log
08-30 15:45:12.866  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 15:45:12.866  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 15:45:12.867  7828  7828 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 15:45:12.869  7617  7829 D BluetoothAdapterProperties: Name is: G3
,08-30 15:45:12.877  7828  7828 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 15:45:12.877  7828  7828 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 15:45:12.879  7617  7825 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 15:45:12.880  7617  7825 D BluetoothAdapterProperties: Setting state to 11
08-30 15:45:12.880  7617  7825 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 15:45:12.881  1034  1096 D BluetoothManagerService: Message: 60
08-30 15:45:12.881  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 15:45:12.881  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 15:45:12.882  7617  7825 I LGBluetoothServiceJni: classInitNative: succeeds
,08-30 15:45:12.892  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:12.892  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:45:12.898  6824  6824 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-30 15:45:12.903  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:12.907  7617  7617 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:45:12.907  7617  7617 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:12.907  7617  7617 V BluetoothPbapReceiver: ***********state = 11
08-30 15:45:12.917  7617  7825 D BluetoothBondStateMachine: make
,08-30 15:45:12.924  7617  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:12.924  7617  7825 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 15:45:12.925  7617  7825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:12.925  7617  7825 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 15:45:12.925  7617  7838 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 15:45:12.926  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:45:12.927  7617  7825 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 15:45:12.934  7617  7825 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:45:12.952  7617  7617 D HeadsetService: Received start request. Starting profile...
08-30 15:45:12.952  7617  7617 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:45:12.953  7617  7617 D LGBluetoothHfpAdapter: Version 1.6
08-30 15:45:12.956  7617  7617 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 15:45:12.957  7617  7617 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:45:12.957  7617  7617 D HeadsetStateMachine: make
,08-30 15:45:12.964  7617  7825 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:45:12.972  6824  6824 D BluetoothPermissionRequest: onReceive
,08-30 15:45:12.975  7617  7825 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:45:12.979  6824  6824 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:45:12.989  7617  7825 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:45:13.000  7617  7617 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:45:13.000  7617  7617 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:45:13.001  7617  7825 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:45:13.006  7617  7617 D HeadsetStateMachine: max_hf_connections = 1
08-30 15:45:13.006  7617  7617 I bluedroid-qcom: get_profile_interface handsfree
08-30 15:45:13.008  7617  7617 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 15:45:13.009   314  2149 V AudioPolicyService: registerClient() client 0xb102fb20, uid 1002
08-30 15:45:13.010   314  1403 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 15:45:13.010   314  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:45:13.010   314  1403 V AudioPolicyManagerEx: getOutput() returns output 2
,08-30 15:45:13.010  7617  7617 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 15:45:13.011   314   314 V AudioFlinger: registerClient() client 0xb5581568, pid 7617
08-30 15:45:13.011   314  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:13.011   314  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:13.011  1602  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:13.011  1602  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:13.012   314  1396 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:13.012   314  1396 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:13.012  3459  3474 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:13.012  3459  3474 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:13.012  7617  7632 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:13.012  1602  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:13.012  1602  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:13.012  3459  3475 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:13.012  3459  3475 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:13.012  1850  3555 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:13.011  1034  1574 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:45:13.012  1850  3555 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:13.012  1034  1574 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:45:13.012  1850  3555 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:13.012  1850  3555 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:13.012  1034  1574 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:13.012  1034  1574 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:45:13.013  7617  7632 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 15:45:13.014  7617  7632 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:45:13.014  7617  7632 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 15:45:13.014  7617  7617 V ToneGenerator: Create Track: 0xb4928a80
08-30 15:45:13.014  7617  7617 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 15:45:13.014  7617  7617 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 15:45:13.015   314  1402 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 15:45:13.015   314  1402 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 15:45:13.016   314  1402 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:45:13.016   314  1402 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:45:13.017   314  2149 I AudioFlinger: isAudioPlaybackHookOn() false
,08-30 15:45:13.017   314  1403 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 15:45:13.017   314  1403 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 15:45:13.017   314  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:45:13.017   314  1403 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:45:13.018  7617  7617 V AudioSystem: getLatency() output 2, latency 50
08-30 15:45:13.018  7617  7617 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 15:45:13.018  7617  7617 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 15:45:13.018   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 15:45:13.018   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 15:45:13.018   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 15:45:13.018   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 15:45:13.018   314   314 V AudioFlinger: createTrack() lSessionId: 21
08-30 15:45:13.020  7617  7617 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 15:45:13.020  7617  7825 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:45:13.020   314   314 V AudioFlinger: acquiring 21 from 7617, for 7617
08-30 15:45:13.020   314   314 V AudioFlinger:  added new entry for 21
08-30 15:45:13.021  7617  7617 V ToneGenerator: ToneGenerator INIT OK, time: 138479
08-30 15:45:13.021  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:13.022  7617  7841 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 15:45:13.024  7617  7841 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:45:13.024  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:13.024  7617  7841 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:45:13.024  7617  7841 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 15:45:13.025   314  2148 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7617
08-30 15:45:13.026  7617  7617 D A2dpService: Received start request. Starting profile...
08-30 15:45:13.026   314  2148 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
,08-30 15:45:13.026   314  2148 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 15:45:13.026   314  2148 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 15:45:13.026   314  2148 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 15:45:13.026   314  2148 V voice   : voice_set_parameters: exit with code(0)
08-30 15:45:13.026   314  2148 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 15:45:13.026   314  2148 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 15:45:13.026   314  2148 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 15:45:13.026   314  2148 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 15:45:13.027   314  2148 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 15:45:13.027   314  2148 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 15:45:13.027  7617  7617 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 15:45:13.027  7617  7841 V ToneGenerator: ToneGenerator destructor
08-30 15:45:13.027  7617  7841 V ToneGenerator: stopTone
08-30 15:45:13.027  7617  7841 V ToneGenerator: Delete Track: 0xb4928a80
08-30 15:45:13.028  7617  7617 V Avrcp   : make
08-30 15:45:13.029  7617  7617 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 15:45:13.029  7617  7617 I bluedroid-qcom: get_profile_interface avrcp
08-30 15:45:13.030  7617  7841 V AudioTrack: ~AudioTrack, releasing session id from 7617 on behalf of 7617
08-30 15:45:13.030   314  2149 V AudioFlinger: releasing 21 from 7617 for 7617
08-30 15:45:13.030   314  2149 V AudioFlinger:  decremented refcount to 0
08-30 15:45:13.030   314  2149 V AudioFlinger: purging stale effects
08-30 15:45:13.031   314  2149 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 15:45:13.031   314  2149 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 15:45:13.032   314  1258 V AudioPolicyService: AudioCommandThread() waking up
,08-30 15:45:13.032   314  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 15:45:13.032   314  1258 V AudioPolicyManager: releaseOutput() 2
08-30 15:45:13.032   314  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 15:45:13.032   314  2149 V AudioFlinger: PlaybackThread::Track destructor
08-30 15:45:13.032   314  2149 V AudioFlinger: removeClient_l() pid 7617, calling pid 314
08-30 15:45:13.035  7617  7825 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:45:13.047  7617  7617 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 15:45:13.049  7617  7617 E AudioManager: No RCC entry present to update
,08-30 15:45:13.049  7617  7617 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 15:45:13.052  7617  7825 V LGMDMManager: Create singleton instance
08-30 15:45:13.053  7617  7617 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 15:45:13.055  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 15:45:13.055  7617  7617 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 15:45:13.055  7617  7825 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 15:45:13.061  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 15:45:13.204  1034  1992 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:45:13.204  1034  1992 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:45:13.348  1034  1993 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 15:45:13.375  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 15:45:13.394  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-30 15:45:13.396  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 15:45:13.397  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 15:45:13.398  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 15:45:13.400  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:45:13.400  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 15:45:13.400  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 15:45:13.400  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 15:45:13.400  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:45:13.401  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 15:45:13.403  7617  7617 I BluetoothA2dpServiceJni: classInitNative
08-30 15:45:13.403  7617  7617 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:45:13.403  7617  7617 D A2dpStateMachine: make
08-30 15:45:13.406  7617  7617 I bluedroid-qcom: get_profile_interface a2dp
08-30 15:45:13.406  7617  7859 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 15:45:13.409  7617  7617 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:45:13.410  7617  7617 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 15:45:13.411  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:13.414  7617  7617 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 15:45:13.418  7617  7858 D A2dpStateMachine: Enter Disconnected: -2
08-30 15:45:13.421  7617  7617 D HidService: Received start request. Starting profile...
08-30 15:45:13.421  7617  7617 I bluedroid-qcom: get_profile_interface hidhost
08-30 15:45:13.421  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:13.422  7617  7617 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 15:45:13.424  7617  7617 D HealthService: Received start request. Starting profile...
08-30 15:45:13.427  7617  7617 I bluedroid-qcom: get_profile_interface health
,08-30 15:45:13.428  7617  7617 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 15:45:13.428  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:13.428  7617  7617 D HeadsetStateMachine: Proxy object connected
08-30 15:45:13.429  7617  7617 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 15:45:13.429  7617  7617 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 15:45:13.432  7617  7617 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 15:45:13.434  7617  7617 D PanService: Received start request. Starting profile...
08-30 15:45:13.434  7617  7617 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 15:45:13.434  7617  7617 I bluedroid-qcom: get_profile_interface pan
08-30 15:45:13.441  7617  7617 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 15:45:13.441  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
,08-30 15:45:13.447  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:45:13.448  7617  7841 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 15:45:13.448  7617  7617 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 15:45:13.449  7617  7841 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 15:45:13.449  7617  7841 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 15:45:13.455  7617  7617 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:45:13.455  7617  7617 D BtGatt.GattService: Received start request. Starting profile...
08-30 15:45:13.455  7617  7617 D BtGatt.GattService: start()
08-30 15:45:13.455  7617  7617 I bluedroid-qcom: get_profile_interface gatt
08-30 15:45:13.456  7617  7617 D BtGatt.AdvertiseManager: advertise manager created
08-30 15:45:13.462  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:13.464  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:13.464  7617  7617 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 15:45:13.465  7617  7617 V BluetoothMapService: BluetoothMapBinder()
08-30 15:45:13.466  7617  7617 D BluetoothMapService: Received start request. Starting profile...
08-30 15:45:13.466  7617  7617 D BluetoothMapService: start()
,08-30 15:45:13.469  7617  7617 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 15:45:13.470  7617  7617 D BluetoothMapEmailAppObserver: createReceiver()
08-30 15:45:13.471  7617  7617 D BluetoothMapEmailAppObserver: initObservers()
08-30 15:45:13.471  7617  7617 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 15:45:13.480  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
,08-30 15:45:13.484  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:45:13.486  7617  7617 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:13.490  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:45:13.493  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 15:45:13.494  7617  7617 V PanService: [BTUI] SIM Extra State :ABSENT
,08-30 15:45:13.498  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:45:13.501  7617  7617 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 15:45:13.502  7617  7617 V BluetoothMapService: Handler(): got msg=1
,08-30 15:45:13.503  7617  7617 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 15:45:13.503  7617  7617 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:45:13.503  7617  7617 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:45:13.503  7617  7617 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:13.503  7617  7617 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-30 15:45:13.503  7617  7825 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 15:45:13.503  7617  7825 I bluedroid-qcom: enable
08-30 15:45:13.504  7617  7866 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 15:45:13.506  7617  7825 I bt_hci_bdroid: init
,08-30 15:45:13.513  7617  7825 I bt_vendor: bt-vendor : init
08-30 15:45:13.513  7617  7825 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 15:45:13.513  7617  7825 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 15:45:13.513  7617  7825 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 15:45:13.513  7617  7825 D bt_userial_mct: userial_init
08-30 15:45:13.513  7617  7866 I bt-btu  : btu_task pending for preload complete event
08-30 15:45:13.514  7617  7825 D bt_hci_bdroid: set_power 1
08-30 15:45:13.514  7617  7825 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 15:45:13.514  7617  7825 I bt_vendor: Starting hciattach daemon
08-30 15:45:13.514  7617  7825 I bt_vendor: try to set true
08-30 15:45:13.509  7869  7869 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:13.509  7869  7869 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:13.539  7870  7870 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 15:45:13.629  7876  7876 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 15:45:13.643  7877  7877 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 15:45:13.670  7879  7879 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 15:45:13.683  7880  7880 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 15:45:13.708  7881  7881 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 15:45:13.722  7882  7882 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 15:45:13.750  7884  7884 I libmdmdetect: ESOC framework not supported
08-30 15:45:13.751  7884  7884 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 15:45:13.759  7884  7884 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-30 15:45:13.759  7884  7884 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-30 15:45:13.759  7884  7884 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-30 15:45:13.759  7884  7884 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-30 15:45:13.759  7884  7884 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 15:45:13.759  7884  7884 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-30 15:45:13.759  7884  7884 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 15:45:13.799  7884  7885 E QC-QMI  : qmi_client [7884] 15: failed to locate client data
08-30 15:45:13.802   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-30 15:45:13.802   481   481 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-30 15:45:13.832  7886  7886 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 15:45:13.856  7887  7887 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 15:45:13.916  7617  7825 I bt_vendor: bluetooth satus is on
,08-30 15:45:13.916  7617  7825 D bt_hci_bdroid: preload
,08-30 15:45:13.916  7617  7868 D bt_userial_mct: userial_open(port:0)
,08-30 15:45:13.916  7617  7868 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 15:45:13.922  7617  7868 I bt_vendor: Done intiailizing UART
,08-30 15:45:13.926  7617  7868 I bt_vendor: Done intiailizing UART
,08-30 15:45:13.926  7617  7868 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-30 15:45:13.927  7617  7868 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 15:45:13.927  7617  7866 I bt-btu  : btu_task received preload complete event
,08-30 15:45:13.929  7617  7866 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-30 15:45:13.929  7617  7866 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-30 15:45:13.929  7617  7889 D bt_userial_mct: Entering userial_read_thread()
,08-30 15:45:13.936  7617  7866 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-30 15:45:13.946  7617  7866 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 15:45:13.946  7617  7866 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 15:45:13.946  7617  7866 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 15:45:13.946  7617  7866 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 15:45:13.947  7617  7866 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 15:45:13.947  7617  7866 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 15:45:13.947  7617  7866 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 15:45:13.948  7617  7866 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 15:45:13.948  7617  7866 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 15:45:13.948  7617  7866 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 15:45:13.948  7617  7866 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 15:45:13.948  7617  7866 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 15:45:13.948  7617  7866 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 15:45:13.948  7617  7866 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 15:45:13.948  7617  7866 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 15:45:13.948  7617  7866 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 15:45:14.035  7617  7866 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-30 15:45:14.035  7617  7866 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ee061 
,08-30 15:45:14.035  7617  7866 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ee061 
,08-30 15:45:14.076  7617  7829 E bt-btif : Calling BTA_HhEnable
08-30 15:45:14.076  7617  7829 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 15:45:14.077  7617  7829 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 15:45:14.084  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 15:45:14.085  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 15:45:14.085  7617  7829 D BluetoothAdapterProperties: Name is: G3
08-30 15:45:14.088  7617  7829 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:45:14.088  7617  7829 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:45:14.088  7617  7829 D bt_hci_bdroid: postload
08-30 15:45:14.090  7617  7829 D bte_conf: Device ID record 1 : primary
08-30 15:45:14.090  7617  7829 D bte_conf:   vendorId            = 00c4
08-30 15:45:14.090  7617  7829 D bte_conf:   vendorIdSource      = 0001
08-30 15:45:14.090  7617  7829 D bte_conf:   product             = 13a1
08-30 15:45:14.090  7617  7829 D bte_conf:   version             = 1000
08-30 15:45:14.090  7617  7829 D bte_conf:   clientExecutableURL = 
08-30 15:45:14.090  7617  7829 D bte_conf:   serviceDescription  = 
08-30 15:45:14.091  7617  7829 D bte_conf:   documentationURL    = 
,08-30 15:45:14.097  7617  7868 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:45:14.097  7617  7829 D bte_conf: bte_load_did_conf no section named DID2.
08-30 15:45:14.099  7894  7894 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:14.104  7617  7825 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 15:45:14.105  7617  7825 D BluetoothAdapterProperties: ScanMode =  20
08-30 15:45:14.105  7617  7825 D BluetoothAdapterProperties: State =  11
08-30 15:45:14.105  7617  7825 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 15:45:14.106  7617  7825 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 15:45:14.106  7617  7825 D BluetoothAdapterProperties: Setting state to 12
08-30 15:45:14.106  7617  7825 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 15:45:14.109  7617  7829 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 15:45:14.109  7894  7894 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:14.121  1034  1096 D BluetoothManagerService: Message: 60
08-30 15:45:14.122  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 15:45:14.122  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 15:45:14.123  7617  7825 I BluetoothAdapterState: Entering On State
08-30 15:45:14.148  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:14.148  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:14.148  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:14.148  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:14.148  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:14.148  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:14.148  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:14.148  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:45:14.156  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:45:14.157  7617  7825 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 15:45:14.157  7617  7825 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 15:45:14.157  7617  7825 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 15:45:14.160  7617  7825 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-30 15:45:14.173  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:45:14.175  7617  7825 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 15:45:14.176  7617  7829 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:45:14.176  7617  7829 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 15:45:14.192  1850  1850 D BluetoothHeadset: Proxy object connected
,08-30 15:45:14.196  7617  7866 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 15:45:14.196  7617  7866 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 15:45:14.196  7617  7866 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 15:45:14.196  7617  7866 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 15:45:14.196  7617  7866 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 15:45:14.196  7617  7866 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 15:45:14.196  7617  7829 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 15:45:14.197  7617  7868 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:45:14.217  7899  7899 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 15:45:14.223  7617  7868 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:45:14.223  6824  7528 D BluetoothMap: onBluetoothStateChange: up=true
08-30 15:45:14.226  7617  7889 E bt_mct  : hci lib postload completed
08-30 15:45:14.228  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:45:14.230  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 15:45:14.230  6824  7528 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 15:45:14.234  7617  7866 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:14.234  7617  7866 W bt-smp  : Plain text(LSB ~ MSB) = a9 db 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:14.234  7617  7866 W bt-smp  : Encrypted text(LSB ~ MSB) = e4 98 55 ed b0 f0 23 19 65 d6 fa 68 a2 89 4c c9 
08-30 15:45:14.234  7617  7866 W bt-btm  : Stopping oneshot timer
,08-30 15:45:14.237  1850  3555 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:45:14.239  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 15:45:14.240  6824  6839 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:45:14.245  6824  6840 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 15:45:14.248  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:45:14.248  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:45:14.249  1034  1034 D BluetoothHeadset: Proxy object connected
,08-30 15:45:14.249  6824  7528 D BluetoothPan: onBluetoothStateChange on: true
08-30 15:45:14.249  6824  7528 D BluetoothPan: onBluetoothStateChange call bindService
08-30 15:45:14.253  6824  6824 D BluetoothMap: Proxy object connected
08-30 15:45:14.253  6824  6824 D MapProfile: Bluetooth service connected
08-30 15:45:14.253  6824  6824 D BluetoothMap: getConnectedDevices()
,08-30 15:45:14.257  7617  7632 V BluetoothMapService: getConnectedDevices()
08-30 15:45:14.257  6824  6839 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:45:14.259  1034  1034 D BluetoothA2dp: Proxy object connected
08-30 15:45:14.259  6824  6824 D BluetoothInputDevice: Proxy object connected
08-30 15:45:14.259  6824  6824 D HidProfile: Bluetooth service connected
08-30 15:45:14.261  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 15:45:14.261  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 15:45:14.262  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:14.263  1940  2124 D LGBluetoothAPIService: Message: 1
08-30 15:45:14.263  1940  2124 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 15:45:14.263  1940  2124 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-30 15:45:14.263  1940  2124 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 15:45:14.266  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:45:14.266  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 15:45:14.267  1034  1096 D BluetoothManagerService: Message: 40
08-30 15:45:14.267  6824  6824 D BluetoothHeadset: Proxy object connected
08-30 15:45:14.267  6824  6824 D HeadsetProfile: Bluetooth service connected
08-30 15:45:14.269  7617  7617 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:14.269  7617  7617 D BluetoothMapService: STATE_ON
08-30 15:45:14.269  7617  7617 V BluetoothMapService: Handler(): got msg=1
08-30 15:45:14.270  7617  7617 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 15:45:14.271  7617  7866 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:14.271  7617  7866 W bt-smp  : Plain text(LSB ~ MSB) = a7 7b 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:14.271  7617  7866 W bt-smp  : Encrypted text(LSB ~ MSB) = 14 3e c8 63 ab 11 4a ac 9c 83 ec 0a b5 37 aa 53 
08-30 15:45:14.271  7617  7866 W bt-btm  : Stopping oneshot timer
08-30 15:45:14.273  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:14.274  6824  6824 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:45:14.274  6824  6824 D PanProfile: Bluetooth service connected
08-30 15:45:14.275  6824  6824 D BluetoothA2dp: Proxy object connected
08-30 15:45:14.275  6824  6824 D A2dpProfile: Bluetooth service connected
08-30 15:45:14.279  6824  6824 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 15:45:14.281  7617  7866 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:14.281  7617  7866 W bt-smp  : Plain text(LSB ~ MSB) = 76 bd 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:14.281  7617  7866 W bt-smp  : Encrypted text(LSB ~ MSB) = dd 1c 11 80 a3 7f cc 7f 66 e0 6e 86 9b bf 70 70 
08-30 15:45:14.281  7617  7866 W bt-btm  : Stopping oneshot timer
,08-30 15:45:14.282  6824  6824 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 15:45:14.282  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:14.282  7617  7617 V BluetoothPbapService: Pbap Service onCreate
,08-30 15:45:14.282  7617  7617 V BluetoothPbapService: Starting PBAP service
08-30 15:45:14.285  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 15:45:14.286  7617  7617 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 15:45:14.286  7617  7617 V BluetoothPbapService: Pbap Service onBind
08-30 15:45:14.288  7617  7617 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:14.288  7617  7617 V BluetoothPbapService: state: 12
08-30 15:45:14.288  7617  7617 V BluetoothPbapService: Handler(): got msg=1
08-30 15:45:14.288  7617  7617 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 15:45:14.289  7617  7866 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:14.289  7617  7866 W bt-smp  : Plain text(LSB ~ MSB) = 40 62 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:14.289  7617  7866 W bt-smp  : Encrypted text(LSB ~ MSB) = 59 19 db 21 7a 43 e2 04 be c8 d0 79 8b 6c 00 a9 
08-30 15:45:14.289  7617  7866 W bt-btm  : Stopping oneshot timer
08-30 15:45:14.289  7617  7917 V BluetoothPbapService: Pbap Service initSocket
08-30 15:45:14.291  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:14.291  7617  7617 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:45:14.291  7617  7617 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:14.291  7617  7617 V BluetoothPbapReceiver: ***********state = 12
08-30 15:45:14.293  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:45:14.294  2186  2186 D c       : Getting all permits...
08-30 15:45:14.294  2186  2186 D a       : Opening database...
08-30 15:45:14.296  2186  2186 D a       : Opening database auth.proximity.permit_store...
08-30 15:45:14.297  2186  2186 D a       : Closing database...
08-30 15:45:14.297  7617  7915 D BluetoothMapMasInstance: MAS initSocket()
08-30 15:45:14.298  7617  7866 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:45:14.298  7617  7866 W bt-smp  : Plain text(LSB ~ MSB) = 55 c2 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:45:14.298  7617  7866 W bt-smp  : Encrypted text(LSB ~ MSB) = 60 d6 ab 3c 08 97 a7 be b2 8e 29 4f 52 da 61 4e 
08-30 15:45:14.298  7617  7866 W bt-btm  : Stopping oneshot timer
08-30 15:45:14.299  7617  7915 D BluetoothMapMasInstance:   masId = 00
08-30 15:45:14.299  7617  7915 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 15:45:14.299  7617  7915 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 15:45:14.299  7617  7915 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 15:45:14.299  1034  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:45:14.305  7617  7915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:45:14.305  7617  7917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:45:14.306  7617  7915 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 15:45:14.306  7617  7915 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 15:45:14.306  7617  7915 D BluetoothMapMasInstance: Accepting socket connection...
08-30 15:45:14.307  7617  7829 D BluetoothAdapterProperties: Scan Mode:21
08-30 15:45:14.307  7617  7829 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 15:45:14.311  7617  7917 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 15:45:14.312  7617  7917 V BluetoothPbapService: Succeed to create listening socket 
08-30 15:45:14.312  7617  7917 V BluetoothPbapService: Accepting socket connection...
08-30 15:45:14.312  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:14.313  6824  6824 D DockEventReceiver: finishStartingService: stopping service
08-30 15:45:14.313  6824  6824 D BluetoothPbap: Proxy object connected
08-30 15:45:14.313  6824  6824 D PbapServerProfile: Bluetooth service connected
08-30 15:45:14.317  6824  6824 D BluetoothPermissionRequest: onReceive
,08-30 15:45:14.320  6824  6824 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 15:45:14.321  6824  6824 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:45:14.324  7617  7617 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 15:45:14.325  7617  7617 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 15:45:14.330  7617  7617 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 15:45:14.342  7617  7617 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 15:45:14.342  7617  7617 V BtOppService: onCreate
,08-30 15:45:14.345  7617  7617 V BluetoothOppNotification: send message
08-30 15:45:14.347  7617  7617 V BtOppService: Starting RfcommListener
08-30 15:45:14.349  7617  7617 D BluetoothOppPreference: Dumping Names:  
08-30 15:45:14.349  7617  7617 D BluetoothOppPreference: {}
08-30 15:45:14.350  7617  7617 D BluetoothOppPreference: Dumping Channels:  
08-30 15:45:14.350  7617  7617 D BluetoothOppPreference: {}
08-30 15:45:14.350  7617  7617 V BtOppService: onStartCommand
08-30 15:45:14.351  7617  7927 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 15:45:14.354  7617  7617 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:14.354  7617  7617 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 15:45:14.360  7617  7924 V BtOppService: Deleted complete outbound shares, number =  0
08-30 15:45:14.361  7617  7927 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 15:45:14.363  7617  7927 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27d4eca9 on behalf of 
08-30 15:45:14.363  7617  7927 V BluetoothOppNotification: update too frequent, put in queue
08-30 15:45:14.364  7617  7924 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 15:45:14.364  7617  7924 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 15:45:14.364  7617  7927 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 15:45:14.364  7617  7927 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 15:45:14.365  7617  7924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@97a722e on behalf of 
08-30 15:45:14.368  7617  7927 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1580d1cf on behalf of 
08-30 15:45:14.368  7617  7927 V BluetoothOppNotification: update too frequent, put in queue
08-30 15:45:14.369  7617  7927 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 15:45:14.432  1034  1050 I art     : Explicit concurrent mark sweep GC freed 27631(1361KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.468ms total 76.106ms
,08-30 15:45:14.435  7617  7617 V BluetoothOppNotification: new notify threadi!
08-30 15:45:14.436  7617  7617 V BluetoothOppNotification: send delay message
08-30 15:45:14.436  7617  7929 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 15:45:14.437  7617  7617 V BtOppService: start RfcommListener
08-30 15:45:14.437  7617  7929 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ce0975c on behalf of 
08-30 15:45:14.438  7617  7929 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 15:45:14.439  7617  7929 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 15:45:14.441  7617  7929 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6e6aa65 on behalf of 
08-30 15:45:14.442  7617  7929 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 15:45:14.443  7617  7929 V BluetoothOppNotification: outbound notification was removed.
08-30 15:45:14.443  7617  7929 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 15:45:14.444  7617  7929 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@273f833a on behalf of 
,08-30 15:45:14.445  7617  7617 V BtOppService: RfcommListener started
08-30 15:45:14.445  7617  7930 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 15:45:14.445  7617  7617 V BtOppService: ContentObserver received notification
08-30 15:45:14.446  7617  7617 V BtOppService: ContentObserver received notification
08-30 15:45:14.446  7617  7931 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 15:45:14.446  7617  7931 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 15:45:14.447  1034  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:14.447  7617  7930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:45:14.448  7617  7930 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-30 15:45:14.448  7617  7931 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8e2bbeb on behalf of 
08-30 15:45:14.449  7617  7930 V BtOppRfcommListener: Started RFCOMM listener....
08-30 15:45:14.449  7617  7931 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 15:45:14.449  7617  7930 I BtOppRfcommListener: Accept thread started.
08-30 15:45:14.449  7617  7930 V BtOppRfcommListener: Accepting connection...
08-30 15:45:14.449  7617  7929 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 15:45:14.451  7617  7929 V BluetoothOppNotification: inbound notification was removed.
08-30 15:45:14.451  7617  7929 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 15:45:14.451  7617  7929 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@208dcd48 on behalf of 
08-30 15:45:14.470  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:14.470  7617  7617 V BluetoothFtpService: Ftp Service onCreate
08-30 15:45:14.470  7617  7617 I BluetoothFtpService: Ftp Service onCreate
08-30 15:45:14.471  7617  7617 V BluetoothFtpService: Ftp Service onStartCommand
08-30 15:45:14.471  7617  7617 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:14.471  7617  7617 V BluetoothFtpService: Starting Listening on sockets
08-30 15:45:14.471  7617  7617 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:45:14.471  7617  7617 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:45:14.471  7617  7617 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:45:14.471  7617  7617 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:14.471  7617  7617 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 15:45:14.472  7617  7617 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-30 15:45:14.479  7617  7617 V BluetoothFtpService: Handler(): got msg=1
08-30 15:45:14.479  7617  7617 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 15:45:14.479  7617  7617 V BluetoothFtpService: Ftp Service initSocket
08-30 15:45:14.485  1034  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:14.485  7617  7617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:45:14.488  7617  7617 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-30 15:45:14.489  7617  7617 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 15:45:14.490  7617  7932 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 15:45:14.504  7617  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d15ef5d
08-30 15:45:14.504  7617  7617 V BluetoothSapService: Sap Service onCreate
08-30 15:45:14.506  7617  7617 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:45:14.506  7617  7617 V BluetoothSapService: state: 12
08-30 15:45:14.507  7617  7617 V BluetoothSapService: Starting SAP server process
,08-30 15:45:14.509  7617  7617 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 15:45:14.499  7933  7933 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:14.499  7933  7933 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:45:14.512  7617  7934 V BluetoothSapService: Sap Service initRfcommSocket
08-30 15:45:14.513  1034  1939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:14.514  7617  7934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:45:14.516  7617  7934 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 15:45:14.517  7617  7934 V BluetoothSapService: Succeed to create listening socket 
08-30 15:45:14.517  7617  7934 V BluetoothSapService: Accepting socket connection...
08-30 15:45:14.523  7933  7933 V BT_SAP  : Event pipe created
08-30 15:45:14.523  7933  7933 V BT_SAP  : create_server_socket qcom.sap.server
08-30 15:45:14.524  7933  7933 V BT_SAP  : created socket fd 6
,08-30 15:45:14.817  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7901
,08-30 15:45:14.827  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:14.827  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:14.827  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:14.827  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:45:14.827  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:14.827  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:14.827  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:14.827  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:14.829  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:14.831  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:14.831  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d3d83a6 added. We now have 8 listener(s)
08-30 15:45:14.831  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:14.834  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7902
08-30 15:45:14.835  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7913
08-30 15:45:14.835  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7920
08-30 15:45:14.836  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7941
,08-30 15:45:14.840  1034  1575 D WifiServiceImplEx: setWifiEnabled: false pid=6587, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:45:14.841  1034  1575 D WifiService: setWifiEnabled: false pid=6587, uid=10118
08-30 15:45:14.841  1034  1575 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:45:14.842  7646  7672 W art     : Suspending all threads took: 20.476ms
08-30 15:45:14.846  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:14.848  1034  2029 D WifiServiceImplEx: setWifiEnabled: true pid=6587, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:45:14.849  1034  2029 D WifiService: setWifiEnabled: true pid=6587, uid=10118
08-30 15:45:14.849  1034  2029 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:45:14.860  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:45:14.860  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:45:14.860  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-30 15:45:14.863  1034  1391 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 15:45:14.863  1034  1391 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-30 15:45:14.866  1034  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-30 15:45:14.866  1034  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-30 15:45:14.866  1034  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-30 15:45:14.866  1034  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-30 15:45:14.866  1034  1391 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 15:45:14.866  1034  1391 E WifiHW  : unknown target_country: EU , set to default
08-30 15:45:14.866  1034  1391 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 15:45:14.866  1034  1391 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 15:45:14.866  1034  1391 I WifiUtil: gEnableBmps=1
,08-30 15:45:15.442  7617  7617 V BluetoothOppNotification: new notify threadi!
,08-30 15:45:15.443  7617  7617 V BluetoothOppNotification: send delay message
,08-30 15:45:15.462   309   893 D SoftapController: Softap fwReload - Ok
,08-30 15:45:15.466  1034  1391 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (594ms)
08-30 15:45:15.467   309   893 D CommandListener: Setting iface cfg
08-30 15:45:15.468   309   893 D CommandListener: Trying to bring down wlan0
08-30 15:45:15.468   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:45:15.483  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:45:15.483  1034  1096 D Tethering: InitialState.processMessage what=4
,08-30 15:45:15.496  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 15:45:15.500  1034  1391 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 15:45:15.509  7955  7955 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:15.520  1034  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:45:15.520  1034  1391 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:45:15.520  1034  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:45:15.519  7955  7955 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:45:15.539  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:45:15.552  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 15:45:15.578  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-30 15:45:15.579  1034  1391 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 15:45:15.579  1034  1391 D WifiMonitor: connecting to supplicant
08-30 15:45:15.580  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:15.586  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 15:45:15.586  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:45:15.586  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:45:15.586  6824  6824 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 15:45:15.586  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 15:45:15.587  6824  6824 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:45:15.587  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 15:45:15.587  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:45:15.587  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:45:15.587  6824  6824 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:45:15.587  6824  6824 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 15:45:15.589  7955  7955 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 15:45:15.591  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 15:45:15.591  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:45:15.591  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:45:15.591  6824  6824 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 15:45:15.592  7617  7953 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 15:45:15.593  7617  7953 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2378c11d on behalf of 
08-30 15:45:15.598  7617  7953 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 15:45:15.602  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 15:45:15.602  7617  7953 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 15:45:15.603  6824  6824 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:45:15.603  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 15:45:15.603  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:45:15.603  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:45:15.603  6824  6824 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:45:15.603  6824  6824 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 15:45:15.605  7617  7953 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1eaf3f92 on behalf of 
08-30 15:45:15.607  7617  7953 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 15:45:15.611  7617  7953 V BluetoothOppNotification: outbound notification was removed.
08-30 15:45:15.611  7617  7953 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 15:45:15.612  7617  7953 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32e8bd63 on behalf of 
08-30 15:45:15.613  7617  7953 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 15:45:15.614  7617  7953 V BluetoothOppNotification: inbound notification was removed.
08-30 15:45:15.614  7617  7953 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 15:45:15.615  7617  7953 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@345efd60 on behalf of 
08-30 15:45:15.640  7955  7955 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 15:45:15.640  7955  7955 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-30 15:45:15.651  1034  1575 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7973 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 15:45:15.734  7955  7955 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 15:45:15.753  1034  1939 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7994 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 15:45:15.758  7973  7992 W FormManager: Network not available. Please check & try again.
08-30 15:45:15.774  7955  7955 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 15:45:15.774  7973  7993 V FormManager: Network unavailable.
,08-30 15:45:15.777  7973  7993 V FormManager: Network unavailable.
08-30 15:45:15.779  7955  7955 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 15:45:15.781  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 15:45:15.781  1034  8012 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 15:45:15.781  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 15:45:15.781  1034  8012 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 15:45:15.782  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 15:45:15.782  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 15:45:15.782  7955  7955 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 15:45:15.782  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 15:45:15.783  1034  1391 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 15:45:15.783  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:15.784  1034  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:15.784  1034  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:15.785  1034  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:15.785  1034  1391 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 15:45:15.785  1034  1391 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 15:45:15.786  1034  1391 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 15:45:15.786  1034  1391 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 15:45:15.786  1034  1391 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 15:45:15.786  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 15:45:15.786  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-30 15:45:15.787  1034  8012 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 15:45:15.787  1034  8012 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 15:45:15.787  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:15.787  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:15.787  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:15.787  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:15.788  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:45:15.788  1034  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:45:15.788  1034  1391 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:45:15.788  1034  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:45:15.789  1940  1940 D WfdService: Waiting for WifiP2p enabling
08-30 15:45:15.790  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 15:45:15.791  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:15.791  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 15:45:15.792  1034  1391 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 15:45:15.792  1034  1391 D WifiNative-wlan0: SET update_config 1: returned true
08-30 15:45:15.792  1034  1391 D WifiConfigStore: Loading config and enabling all networks 
08-30 15:45:15.792  1034  1391 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 15:45:15.793  1034  1391 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 15:45:15.795  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:15.795  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:15.795  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:15.795  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:15.795  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:15.795  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:15.795  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:15.795  6587  6587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:15.797  6587  6587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:15.800  1034  1391 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 15:45:15.809  1034  1391 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 15:45:15.810  1034  1391 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 15:45:15.811  1034  1391 D WifiStateMachine: enableVerboseLogging : level 2
08-30 15:45:15.811  1034  1391 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 15:45:15.811  1034  1391 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 15:45:15.811  1034  1391 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 15:45:15.812  1034  1391 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 15:45:15.812  1034  1391 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 15:45:15.812  1034  1391 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 15:45:15.812  1034  1391 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 15:45:15.813  1034  1391 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 15:45:15.813  1034  1391 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 15:45:15.813  1034  1939 I ActivityManager: Killing 7114:com.lge.drmservice/u0a62 (adj 15): empty #17
08-30 15:45:15.813  1034  1391 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 15:45:15.814  1034  1391 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 15:45:15.814  1034  1391 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 15:45:15.814  1034  1391 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 15:45:15.814  1034  1391 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 15:45:15.840  7994  7994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:45:15.855  1034  1391 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 15:45:15.855  1034  1391 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-30 15:45:15.855  1034  1391 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 15:45:15.855  1034  1391 D WifiNative-HAL: Setting external_sim to 1
08-30 15:45:15.855  1034  1391 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 15:45:15.856  1940  1940 D WfdsService: Supplicant Connection state is changed : true
08-30 15:45:15.856  1940  2291 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 15:45:15.856  1034  1391 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 15:45:15.856  1940  2291 D WfdsService: Set the WFDS Monitor: true
08-30 15:45:15.856  1034  1391 I WifiNative-HAL: startHal
08-30 15:45:15.856  1940  2291 D WfdsMonitor: WfdsMonitorThread create
08-30 15:45:15.856  1034  1391 D wifi    : setting scan oui 0xaf794140
08-30 15:45:15.857  7646  7646 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:15.857  1940  2291 D WfdsMonitor: WFDS Monitor is created and started
08-30 15:45:15.857  1940  2291 D WfdsService: WiFi: Supplicant connection re-established
08-30 15:45:15.857  1034  1391 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 15:45:15.857  1034  1391 I WifiNative-HAL: startHal
08-30 15:45:15.857  1034  1391 D wifi    : setting scan oui 0xaf794140
08-30 15:45:15.857  1034  1391 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 15:45:15.857  1940  8015 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 15:45:15.857  1034  1391 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 15:45:15.858  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 15:45:15.858  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 15:45:15.858  1940  8015 E CtrlSupplicant: Succeed to open control connection
08-30 15:45:15.858  1034  1391 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 15:45:15.858  1940  8015 E CtrlSupplicant: Succeed to open monitor connection
08-30 15:45:15.858  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 15:45:15.858  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 15:45:15.858  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 15:45:15.859  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 15:45:15.859  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 15:45:15.859  1940  8015 D WfdsMonitor: Supplicant connection established
08-30 15:45:15.859  1940  2291 D WfdsService: Connected to the supplicant for wfds
08-30 15:45:15.859  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 15:45:15.859  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 15:45:15.859  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 15:45:15.859  1034  1920 W libprocessgroup: failed to open /acct/uid_10062/pid_7114/cgroup.procs: No such file or directory
08-30 15:45:15.859  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 15:45:15.859  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 15:45:15.859  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 15:45:15.859  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 15:45:15.860  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 15:45:15.860  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 15:45:15.860  7955  7955 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 15:45:15.860  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 15:45:15.860  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 15:45:15.860  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 15:45:15.861  1034  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: retu,rned true
08-30 15:45:15.862  1034  1391 E WifiNative: : [141,306,543 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 15:45:15.862  1034  1391 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 15:45:15.862  1034  1391 D WifiNative-wlan0: RECONNECT: returned true
08-30 15:45:15.862  1034  1391 D WifiNative-wlan0: doString: [STATUS]
08-30 15:45:15.863  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 15:45:15.863  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 15:45:15.863  1034  1391 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 15:45:15.863  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:45:15.864  1034  1391 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:45:15.864  1034  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.865  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:15.865   309   893 D CommandListener: Setting iface cfg
08-30 15:45:15.866   309   893 D CommandListener: Trying to bring up p2p0
08-30 15:45:15.866  1034  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 15:45:15.866  1034  1390 D LGWifiP2pService: P2pEnablingState
08-30 15:45:15.866  1034  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.866  1034  1390 D LGWifiP2pService: P2p socket connection successful
08-30 15:45:15.866  1034  1390 D LGWifiP2pService: P2pEnabledState
08-30 15:45:15.866  1034  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 15:45:15.866  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 15:45:15.867  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-30 15:45:15.867  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.867  1034  1555 I WifiNative-HAL: startHal
08-30 15:45:15.867  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf794140
08-30 15:45:15.867  1034  1555 D wifi    : failed to get capabilities : -3
08-30 15:45:15.867  1034  1555 E WifiScanningService: could not get scan capabilities
,08-30 15:45:15.867  1034  1391 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 15:45:15.868  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 15:45:15.868  1940  1940 D WfdsService: WifiP2pState is changed : true
08-30 15:45:15.868  1940  2291 D WfdsService: Receive the WFDS_ENABLE Method
08-30 15:45:15.868  1940  2291 D WfdsService: Set the WFDS Monitor: true
,08-30 15:45:15.868  1940  2291 D WfdsService: Connected to the supplicant for wfds
08-30 15:45:15.868  1940  2291 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 15:45:15.868  7955  7955 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,08-30 15:45:15.868  1940  2291 D WfdsService: selectPreferredScanChannel [36]
08-30 15:45:15.869  1940  2291 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 15:45:15.869  1034  1391 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 15:45:15.869  1034  1391 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 15:45:15.869  1034  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 15:45:15.870  1034  1391 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 15:45:15.870  1034  1556 D RttService: DefaultState got{ when=-4ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.870  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=141315  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:45:15.871  1034  1957 I ActivityManager: Killing 7139:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 15:45:15.872  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 15:45:15.872  1034  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 15:45:15.872  1034  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 15:45:15.872  1940  1940 D WfdsService: isConnected: false
08-30 15:45:15.872  1034  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-30 15:45:15.872  1034  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 15:45:15.872  1034  1390 D LGWifiP2pService: before postfix = G3
08-30 15:45:15.873  1034  1390 D WifiServerServiceExt: postfix byte check : 2
08-30 15:45:15.873  1034  1390 D LGWifiP2pService: after postfix = G3
08-30 15:45:15.873  1034  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 15:45:15.873  1034  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 15:45:15.873  1034  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 15:45:15.873  1034  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 15:45:15.873  1034  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 15:45:15.874  1034  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 15:45:15.874  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 15:45:15.874  1034  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 15:45:15.875  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-30 15:45:15.875  1034  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 15:45:15.877  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:45:15.877  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:15.877  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:15.877  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:15.877  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:15.877  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:45:15.877  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:45:15.877  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:45:15.878  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:45:15.883  6587  6687 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 15:45:15.884  6587  6687 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 15:45:15.887  6587  6687 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@24c6f3b8 Bundle[{}]
08-30 15:45:15.888  6587  6687 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 15:45:15.888  6587  6687 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 15:45:15.888  6587  6687 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 15:45:15.889  6587  6687 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 15:45:15.890  6587  6687 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 15:45:15.890  6587  6687 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 15:45:15.895  6587  6687 I System.out: Running OutgoingSocketThread
,08-30 15:45:15.898  6587  8016 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
08-30 15:45:15.900  6587  8016 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58349
08-30 15:45:15.900  6587  8016 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 15:45:15.915  1034  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 15:45:15.915  1034  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 15:45:15.916  1034  1751 W libprocessgroup: failed to open /acct/uid_10085/pid_7139/cgroup.procs: No such file or directory
08-30 15:45:15.916  1034  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
,08-30 15:45:15.916  1034  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 15:45:15.916  1034  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 15:45:15.916  1034  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 15:45:15.917  1034  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 15:45:15.917  1034  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-30 15:45:15.923  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=141368  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:45:15.923  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 15:45:15.923  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 15:45:15.924  1940  1940 D WfdsService: Update P2p Interface State: 3
08-30 15:45:15.925  1034  1391 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 15:45:15.926  1034  1391 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 15:45:15.926  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:15.926  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:15.927  1034  1391 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 15:45:15.927  1034  1391 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 15:45:15.928  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:15.928  7955  7955 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 15:45:15.928  1034  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 15:45:15.928  1034  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-30 15:45:15.929  1034  1391 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 15:45:15.930  1034  1391 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 15:45:15.934  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:15.934  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:15.934  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 15:45:15.934  1034  1391 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 15:45:15.934  1034  1391 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 15:45:15.935  1034  1390 D LGWifiP2pService: InactiveState
08-30 15:45:15.935  7955  7955 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 15:45:15.935  1034  1390 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.935  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.935  1034  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 15:45:15.936  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 15:45:15.936  1034  1391 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 15:45:15.936  7955  7955 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:45:15.938  7955  7955 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 15:45:15.938  7955  7955 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.938  1034  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 15:45:15.938  1034  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.938  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.939  1034  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.939  7955  7955 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.940  1034  8012 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:45:15.940  1034  8012 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-30 15:45:15.941  1034  8012 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:45:15.942  1034  8012 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:45:15.942  1940  8015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:45:15.942  1034  8012 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:45:15.942  1940  8015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:45:15.942  1034  8012 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.942  1940  8015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:45:15.942  1034  8012 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.942  1034  8012 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.942  1034  8012 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:45:15.942  1034  8012 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.942  1034  8012 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.943  1034  8012 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.943  1034  1391 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 15:45:15.944  1034  1391 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 15:45:15.944  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 15:45:15.944  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 15:45:15.945  7955  7955 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:45:15.945  1034  1390 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.946  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.946  1034  1390 D LGWifiP2pService: DefaultState{ when=-11ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.946  7955  7955 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 15:45:15.947  1940  2291 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 15:45:15.947  7955  7955 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.947  1034  1390 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.947  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.947  1034  1390 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.947  1034  1390 D LGWifiP2pService: InactiveState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.947  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.947  1034  1390 D LGWifiP2pService: DefaultState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.948  7955  7955 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.948  1034  1034 E WifiServerServiceExt: No p2p device connected
08-30 15:45:15.949  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:45:15.949  1940  8015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type,=WORLD]
08-30 15:45:15.949  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:45:15.949  1940  8015 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:45:15.949  1034  8012 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:45:15.949  1034  8012 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:45:15.949  1034  8012 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:45:15.949  1034  8012 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.949  1034  8012 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.949  1034  1391 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 15:45:15.949  1034  8012 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.950  1034  8012 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:45:15.950  1034  8012 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.950  1034  8012 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.950  1034  8012 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:45:15.950  1034  1391 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:45:15.951  1034  1391 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:45:15.951  1034  1391 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:45:15.951  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 15:45:15.952  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 15:45:15.952  1034  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.952  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:15.952  7955  7955 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:45:15.952  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 15:45:15.952  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:45:15.952  1034  8012 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:45:15.952  1034  8012 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:45:15.953  1034  1391 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 15:45:15.953  1034  1391 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-30 15:45:15.954  1034  1391 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 15:45:15.954  1034  1391 D WifiNative-wlan0: doBoolean: SCAN
08-30 15:45:15.954  1034  1391 D WifiNative-wlan0: SCAN: returned false
08-30 15:45:15.955  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=141400  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:45:15.956  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=141401  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:45:15.957  1034  1391 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:45:15.958  1034  1391 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:45:15.959  1034  1391 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:45:15.960  1034  1391 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:45:15.961  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:15.961  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:15.961  1034  1391 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:45:15.961  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 15:45:15.961  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:15.961  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:15.962  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:15.965  7994  7994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:15.965  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:45:15.965  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 15:45:15.967  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:45:15.967  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-30 15:45:15.968  7973  8019 W FormManager: Network not available. Please check & try again.
08-30 15:45:15.971  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 15:45:15.974  7973  8020 V FormManager: Network unavailable.
08-30 15:45:15.977  7973  8020 V FormManager: Network unavailable.
,08-30 15:45:15.980  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:45:15.993  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:45:15.993  4333  4333 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:45:15.995  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:45:15.996  4333  4333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:45:15.999  4333  8021 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:45:16.002  4333  8022 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:45:16.002  4333  8022 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:45:16.054  1034  1049 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8023 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 15:45:16.180  8023  8023 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 15:45:16.180  8023  8023 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 15:45:16.193  8023  8023 V [BNRBootReceiver]: Boot Receiver Return
08-30 15:45:16.194  8023  8023 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 15:45:16.265  1034  1751 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8044 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 15:45:16.268  1034  1751 I ActivityManager: Killing 7174:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-30 15:45:16.378  1034  1992 W libprocessgroup: failed to open /acct/uid_10093/pid_7174/cgroup.procs: No such file or directory
,08-30 15:45:16.408  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 15:45:16.408  1034  8012 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 15:45:16.408  7955  7955 E wpa_supplicant: USIM:  scard_init function
08-30 15:45:16.408  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 15:45:16.409  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-30 15:45:16.409  1034  8012 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 15:45:16.409  7955  7955 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-30 15:45:16.411  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,08-30 15:45:16.411  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 15:45:16.417  1034  1391 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 15:45:16.418  1034  1391 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 15:45:16.419  1034  1391 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 15:45:16.421  1034  1391 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 15:45:16.422  1034  1391 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 15:45:16.433  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=141878  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 15:45:16.434  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=141879  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 15:45:16.438  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.438  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.439  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 15:45:16.439  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:45:16.439  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 15:45:16.440  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:16.440  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:16.442  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.451  8044  8044 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 15:45:16.473  8044  8044 D PluginManager: init()
,08-30 15:45:16.526  7955  7955 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 15:45:16.526  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 15:45:16.528  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 15:45:16.528  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 15:45:16.529  1034  1391 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
,08-30 15:45:16.530  1034  1391 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:16.530  1034  1391 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:16.530  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 15:45:16.531  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:16.531  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 15:45:16.532  1034  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:45:16.532  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:45:16.532  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:45:16.532  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=141977  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 15:45:16.533  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=141977  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 15:45:16.533  1034  1391 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141978
08-30 15:45:16.534  1034  1391 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141978
08-30 15:45:16.534  1034  1391 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141979
08-30 15:45:16.534  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141979
08-30 15:45:16.535  1034  1391 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141980
08-30 15:45:16.535  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=141980  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 15:45:16.543  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=141988  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 15:45:16.544  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.545  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.545  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 15:45:16.545  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:16.545  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:16.546  7955  7955 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:45:16.546  7955  7955 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 15:45:16.550  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:45:16.552  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:45:16.552  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:45:16.552  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 15:45:16.552  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:45:16.552  1034  8012 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:45:16.553  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 15:45:16.553  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:45:16.553  1034  8012 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:45:16.553  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:45:16.553  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:45:16.554  1034  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=141999  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 15:45:16.555  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.555  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:45:16.555  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 15:45:16.555  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:45:16.555  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 15:45:16.555  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:45:16.555  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 15:45:16.558  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:16.558  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:16.560  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.562  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=142007  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 15:45:16.563  1034  1391 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142007
08-30 15:45:16.563  1034  1391 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142008
08-30 15:45:16.564  1034  1391 D WifiNative-wlan0: doString: [STATUS]
08-30 15:45:16.564  1034  8012 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:45:16.564  1034  8012 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:45:16.566  1034  1391 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 15:45:16.567  1034  1391 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 15:45:16.575  1034  1391 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 15:45:16.575  1034  1391 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 15:45:16.579  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:16.579  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:16.580  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:45:16.580  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.580  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 15:45:16.581  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.584  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.584  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.584  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 15:45:16.588  1034  1391 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 15:45:16.589  1034  1408 D ConnectivityService: Got NetworkAgent Messenger
08-30 15:45:16.589  1034  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:45:16.589  1034  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:45:16.589  1034  1408 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 15:45:16.589  1034  1408 D ConnectivityService: NetworkAgent connected
08-30 15:45:16.590  1034  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:45:16.590  1034  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 15:45:16.595  1034  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:45:16.596  1034  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:45:16.596  1034  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:45:16.596  1034  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:45:16.596  1034  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:45:16.601  1034  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:45:16.602  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:16.602  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 15:45:16.603  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.604   309   893 D CommandListener: Setting iface cfg
08-30 15:45:16.607  1034  1391 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 15:45:16.607  1034  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=142052  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:45:16.608  1034  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=142053  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:45:16.608  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=142053  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:45:16.609  1034  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=142054  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:45:16.609  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:45:16.610  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 15:45:16.610  1034  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=142054  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:45:16.610  1034  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=142055  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:45:16.611  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14289] from screen [on:0 period:-609065917] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 15:45:16.612  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-609065916] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 15:45:16.612  1034  1391 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 15:45:16.612  1034  8062 D DhcpStateMachine: StoppedState
,08-30 15:45:16.612  1034  8062 D DhcpStateMachine: StoppedState{ when=-5ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:16.613  1034  8062 D DhcpStateMachine: WaitBeforeStartState
08-30 15:45:16.617  1034  1408 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-30 15:45:16.618  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:16.618  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:16.619  1034  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:16.619  1034  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:16.619  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:16.620  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:45:16.620  1034  1408 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 15:45:16.622  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:45:16.622  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 15:45:16.623  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:45:16.623  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 15:45:16.623  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.624  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
08-30 15:45:16.624  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
08-30 15:45:16.624  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 15:45:16.625  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 15:45:16.625  1034  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 15:45:16.625  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 0
,08-30 15:45:16.626  1034  1391 D WifiNative-wlan0: SET ps 0: returned true
08-30 15:45:16.626  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 15:45:16.627  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 15:45:16.627  1034  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 15:45:16.628  1034  1391 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 15:45:16.628  1034  1391 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 15:45:16.628  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c71f509 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:16.628  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c71f509 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:16.628  1034  8062 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:16.628  1034  8062 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 15:45:16.628  1034  1391 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 15:45:16.629   309   893 D CommandListener: Setting iface cfg
08-30 15:45:16.630   309   893 D CommandListener: Trying to bring up wlan0
08-30 15:45:16.630  1034  1391 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 15:45:16.631  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-30 15:45:16.632  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-30 15:45:16.632  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:45:16.632  1034  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:16.632  1034  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:16.632  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:45:16.632  1034  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:45:16.632  1034  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 15:45:16.633  7955  7955 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 15:45:16.633  1034  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 15:45:16.633  1034  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:45:16.658  1034  1391 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:45:16.660  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:16.661  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:16.661  1034  1408 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-30 15:45:16.664  1034  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:16.666  1034  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:16.667  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:16.668  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:16.669  1034  1408 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 15:45:16.670  1034  1391 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 15:45:16.671  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 15:45:16.671  1034  1391 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 15:45:16.672  1034  1408 D ConnectivityService: ignoring duplicate network state non-change
08-30 15:45:16.677  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:16.677  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:16.679  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:45:16.682  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.682  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.682  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 15:45:16.686  1034  1408 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 15:45:16.687  1034  1408 D ConnectivityService: Adding iface wlan0 to network 102
08-30 15:45:16.690  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.690  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.690  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-30 15:45:16.693  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 15:45:16.697  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.697  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.697  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 15:45:16.698  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 15:45:16.698  1034  1391 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 15:45:16.700  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-30 15:45:16.705  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:45:16.705  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:45:16.705  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 15:45:16.706  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:16.706  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:45:16.708  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.708  1034  1408 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 15:45:16.708  1034  1408 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 15:45:16.709  1034  1408 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 15:45:16.710   309   893 E Netd    : netlink response contains error (File exists)
08-30 15:45:16.710  1034  1408 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 15:45:16.710  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:16.711  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 15:45:16.711  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.711  1034  1408 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 15:45:16.711  1034  1408 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 15:45:16.711  1034  1408 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 15:45:16.712  1034  1408 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 15:45:16.712  1034  1408 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 15:45:16.712  1034  1408 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 15:45:16.712  1034  1408 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 15:45:16.712  1034  1408 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:45:16.712  1034  1408 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:45:16.712  1034  1408 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 15:45:16.712  1034  1408 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:16.713  1034  1408 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 15:45:16.713  1034  1408 D ConnectivityService: currentScore = 0, newScore = 20
08-30 15:45:16.713  1034  1408 D ConnectivityService:    accepting network in place of null
08-30 15:45:16.713  1034  1408 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:16.714  1034  8061 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:16.714  1034  8061 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 15:45:16.714  1034  8061 D NetworkMonitor ,NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:45:16.714  1034  8061 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 15:45:16.715  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:16.716  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:45:16.716  1034  1391 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:16.716  1034  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 15:45:16.718  1034  1408 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 15:45:16.718  1034  1408 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 15:45:16.718  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:45:16.719   309  8072 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 15:45:16.720  1034  1408 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:45:16.720  1034  1408 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 15:45:16.721  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 15:45:16.721  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:45:16.721  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:45:16.721  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:45:16.724  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:45:16.724  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 15:45:16.724  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.725  1034  1408 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 15:45:16.727  1034  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 15:45:16.727  1034  1408 D ConnectivityService: validation of new default Network = false
08-30 15:45:16.728  1034  1408 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 15:45:16.728  1034  1408 D DSQN    : enableDataServiceNotify 
08-30 15:45:16.728  1034  1408 D DSQN    : start dsqn bin
,08-30 15:45:16.735  1034  1408 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 15:45:16.735  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:16.735  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:45:16.735  1034  1408 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:45:16.736  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:45:16.729  8073  8073 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:16.729  8073  8073 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:16.748  8073  8073 E DSQN    : DSQN ssw
,08-30 15:45:16.751  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 15:45:16.752  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.753  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.770   309  8072 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 15:45:16.807   309  8072 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 15:45:16.830  1034  8062 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 15:45:16.832  1034  8062 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 15:45:16.832  1034  8062 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 15:45:16.836   309   892 D LGDataListener: argv[0]=dsqncommand
08-30 15:45:16.836   309   892 D LGDataListener: argv[1]=wlan0
08-30 15:45:16.836   309   892 D LGDataListener: argv[2]=1
08-30 15:45:16.836   309   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 15:45:16.837  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 15:45:16.837  1034  1094 D DSQN    : start to monitor internet connection
08-30 15:45:16.829  8078  8078 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:16.829  8078  8078 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:45:16.861  1034  8061 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 13:45:16 GMT], X-Android-Received-Millis=[1472564716861], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472564716834]}
08-30 15:45:16.862  1034  8061 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 15:45:16.862  1034  8061 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 15:45:16.862  1034  1408 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 15:45:16.862  1034  1408 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 15:45:16.862  1034  1408 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:45:16.862  1034  1408 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:45:16.862  1034  1408 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 15:45:16.862  1034  1408 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 15:45:16.862  1034  1408 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 15:45:16.862  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:16.863  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 15:45:16.863  1034  1408 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:45:16.863  1034  1408 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:16.864  1034  1408 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 15:45:16.864  8078  8078 I dhcpcd  : version 5.5.6 starting
08-30 15:45:16.864  1034  1391 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:16.864  1034  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:45:16.865  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:45:16.866  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:16.866  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:45:16.866  8078  8078 E dhcpcd  : get_duid: m
08-30 15:45:16.866  8078  8078 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 15:45:16.866  8078  8078 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-30 15:45:16.888  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:45:16.889  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.890  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:45:16.896  6587  6687 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
08-30 15:45:16.896  6587  6687 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
08-30 15:45:16.899  6587  6687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
08-30 15:45:16.900  6587  6687 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 15:45:16.900  6587  6687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
08-30 15:45:16.902  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:16.902  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39b1d1e7 added. We now have 2 listener(s)
08-30 15:45:16.902  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:16.904  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:16.904  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:16.904  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:16.904  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:16.904  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e54f194 added. We now have 9 listener(s)
08-30 15:45:16.905  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:16.905  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:45:16.907  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:45:16.910  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:16.910  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:16.910  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:16.910  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:16.910  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:16.910  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:16.910  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:45:16.910  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:45:16.911  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:16.911  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:45:16.912  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:16.912  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ae3432 added. We now have 3 listener(s)
08-30 15:45:16.912  1034  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:16.913  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:16.915  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:16.915  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:16.916  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:16.916  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:16.916  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:16.916  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbfa583 added. We now have 10 listener(s)
08-30 15:45:16.916  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:16.916  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:45:16.916  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:16.916  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:45:16.918  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:16.918  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.918  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:16.918  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:16.918  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39b1d1e7 removed from the list
08-30 15:45:16.918  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:16.918  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e54f194 removed from the list
08-30 15:45:16.918  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:16.918  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.918  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.918  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.919  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:16.919  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:16.919  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:16.919  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e54f194 not in the list
08-30 15:45:16.919  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.919  6587  6687 D org.thaliproject.p2p.btconnec,torlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:45:16.920  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:16.920  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:16.920  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:16.920  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbfa583 removed from the list
08-30 15:45:16.920  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:16.920  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.920  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.920  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:16.920  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ae3432 removed from the list
08-30 15:45:16.920  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:16.920  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f599300 added. We now have 2 listener(s)
08-30 15:45:16.921  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:16.923  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:16.923  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:16.923  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:16.923  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:16.923  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15edc739 added. We now have 9 listener(s)
08-30 15:45:16.923  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:16.923  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:45:16.925  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:16.927  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:16.927  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:16.927  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:16.927  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:16.927  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:16.927  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:16.927  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:45:16.927  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:45:16.928  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChang,ed: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:16.928  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:45:16.928  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:16.928  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@204d16df added. We now have 3 listener(s)
08-30 15:45:16.929  1034  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:16.930  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:16.930  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:16.931  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:16.931  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:16.931  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:16.931  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:16.931  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d44df2c added. We now have 10 listener(s)
08-30 15:45:16.931  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:16.931  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:45:16.931  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:45:16.931  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:45:16.931  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:16.931  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 15:45:16.934  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:45:16.934  1034  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:16.938  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:45:16.938  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 15:45:16.939  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:45:16.940  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:16.940  6587  6687 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:45:16.941  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:16.941  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:45:16.941  8078  8078 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 15:45:16.942  8078  8078 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 15:45:16.942  8078  8078 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 15:45:16.942  8078  8078 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 15:45:16.942  8078  8078 D dhcpcd  : wlan0: sending REQUEST (xid 0xb561cb42), next in 4.42 seconds
08-30 15:45:16.942  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:45:16.942  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:16.942  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:45:16.942  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:16.942  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.942  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:16.942  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:16.942  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f599300 removed from the list
08-30 15:45:16.942  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:45:16.942  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15edc739 removed from the list
08-30 15:45:16.942  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:16.942  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.943  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.943  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.943  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:16.943  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:16.943  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:16.943  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15edc739 not in the list
08-30 15:45:16.943  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:45:16.943  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:45:16.944  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:16.944  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:45:16.944  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:45:16.944  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:16.944  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:16.944  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d44df2c removed from the list
08-30 15:45:16.944  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:16.944  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.945  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.945  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:16.945  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@204d16df removed from the list
08-30 15:45:16.945  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:16.945  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151641fb added. We now have 2 listener(s)
08-30 15:45:16.946  1034  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:16.949  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:16.949  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:16.949  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:16.949  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:16.949  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b6c218 added. We now have 9 listener(s)
,08-30 15:45:16.949  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:45:16.949  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:45:16.951  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:16.953  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:16.953  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:16.953  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:16.953  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:16.953  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:16.953  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:16.953  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:45:16.953  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:45:16.954  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:16.954  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:45:16.955  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:16.955  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc42256 added. We now have 3 listener(s)
08-30 15:45:16.955  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:16.956  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:16.958  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:16.958  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:16.958  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:16.958  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:16.958  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:16.959  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d7d02d7 added. We now have 10 listener(s)
08-30 15:45:16.959  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:16.959  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:45:16.959  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:45:16.959  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:45:16.959  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:45:16.959,  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:16.959  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:45:16.962  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:45:16.962  1034  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:45:16.965  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-30 15:45:16.966  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:45:16.967  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:45:16.968  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:16.970  6587  6687 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:45:16.970  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:45:16.970  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:16.970  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:45:16.970  8078  8078 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 15:45:16.970  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:16.970  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.970  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:16.970  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:16.970  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151641fb removed from the list
08-30 15:45:16.970  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:16.970  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b6c218 removed from the list
08-30 15:45:16.970  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:45:16.970  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.971  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.971  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.971  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:16.971  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:16.971  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:16.971  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b6c218 not in the list
,08-30 15:45:16.971  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.971  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.972  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:16.972  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:45:16.972  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:45:16.972  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:16.972  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-30 15:45:16.972  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d7d02d7 removed from the list
08-30 15:45:16.972  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:16.972  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:16.972  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:16.973  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:16.973  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc42256 removed from the list
08-30 15:45:16.973  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:16.973  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1780de2 added. We now have 2 listener(s)
08-30 15:45:16.973  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:45:16.975  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:16.975  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:16.975  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:16.975  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:16.975  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1324f573 added. We now have 9 listener(s)
08-30 15:45:16.975  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:16.976  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:45:16.980  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:16.985  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:16.985  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:16.985  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:16.985  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:16.985  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:16.985  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:16.985  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:45:16.985  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:45:16.987  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:16.987  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:45:16.987  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:16.987  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2271f0a9 added. We now have 3 listener(s)
08-30 15:45:16.988  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:16.989  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:45:16.990  8044  8044 W ExternalStrings: load override strings
08-30 15:45:16.990  8044  8044 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:45:16.990  8044  8044 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:45:16.991  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:16.991  8044  8044 D StatusProvider: onCreate
08-30 15:45:16.994  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:16.994  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:16.994  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:16.994  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:16.995  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d8d262e added. We now have 10 listener(s)
08-30 15:45:16.995  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:16.995  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:45:16.995  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:45:16.995  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:45:16.995  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:16.995  6587  6687 I org.th,aliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:45:16.998  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:45:16.998  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:17.001  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:45:17.001  8078  8078 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 15:45:17.001  8078  8078 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 15:45:17.002  8078  8078 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 15:45:17.002  8078  8078 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 15:45:17.003  8078  8078 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 15:45:17.003  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 15:45:17.003  8078  8078 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 15:45:17.003  8078  8078 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 15:45:17.003  8078  8078 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 15:45:17.004  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:45:17.004  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:17.005  6587  6687 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:45:17.006  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:45:17.006  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:17.006  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:45:17.007  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:17.007  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:17.007  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:17.007  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:17.007  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1780de2 removed from the list
08-30 15:45:17.007  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:17.007  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1324f573 removed from the list
08-30 15:45:17.007  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:17.007  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:17.007  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:17.007  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:17.008  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:17.008  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:17.008  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:17.008  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1324f573 not in the list
08-30 15:45:17.008  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.blu,etooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:17.008  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:17.009  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:17.009  6587  6687 D BluetoothLeScanner: could not find callback wrapper
08-30 15:45:17.009  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:45:17.009  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:17.009  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:17.009  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d8d262e removed from the list
08-30 15:45:17.009  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:17.009  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:17.009  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:17.009  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:17.009  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2271f0a9 removed from the list
08-30 15:45:17.010  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:17.010  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@284fee65 added. We now have 2 listener(s)
08-30 15:45:17.011  1034  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:17.013  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:17.013  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:17.013  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:17.013  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:17.013  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9773a added. We now have 9 listener(s)
08-30 15:45:17.013  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:45:17.016  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:45:17.018  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:45:17.023  6587  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:45:17.023  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:45:17.023  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:45:17.023  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:45:17.023  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:45:17.023  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:17.023  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:45:17.023  6587  6687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:45:17.024  6587  6687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:45:17.024  6587  6687 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:45:17.025  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:45:17.025  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1eae148 added. We now have 3 listener(s)
08-30 15:45:17.026  1034  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:45:17.027  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:17.028  6587  6587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:45:17.030  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:45:17.030  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:45:17.030  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:45:17.030  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:45:17.030  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27560be1 added. We now have 10 listener(s)
08-30 15:45:17.030  6587  6687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:45:17.030  6587  6687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:45:17.030  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:45:17.030  6587  6687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:45:17.031  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:17.031  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:17.031  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:45:17.031  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:17.031  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@284fee65 removed from the list
08-30 15:45:17.031  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:17.031  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9773a removed from the list
08-30 15:45:17.031  6587  6687 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:45:17.031  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:17.031  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:17.031  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:17.032  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:17.032  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:17.032  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:17.032  6587  6687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9773a not in the list
08-30 15:45:17.032  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:17.032  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:17.033  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:45:17.033  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:45:17.033  6587  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:45:17.033  6587  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27560be1 removed from the list
08-30 15:45:17.033  6587  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:45:17.033  6587  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:45:17.033  6587  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:45:17.033  6587  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:45:17.033  6587  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1eae148 removed from the list
08-30 15:45:17.034  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 15:45:17.034  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 15:45:17.034  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 15:45:17.034  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:45:17.034  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 15:45:17.034  6587  6687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:45:17.042  8044  8044 V Signer  : override build config not found
08-30 15:45:17.042  8044  8044 D Signer  : value of property debug is false
08-30 15:45:17.044  6587  8089 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
08-30 15:45:17.044  6587  8089 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
08-30 15:45:17.045  6587  8089 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 15:45:17.046  6587  8091 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
08-30 15:45:17.046  6587  8091 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
08-30 15:45:17.046  6587  8091 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 15:45:17.048  6587  6687 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 15:45:17.048  6587  6687 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 15:45:17.048  6587  6687 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 15:45:17.048  6587  6687 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 15:45:17.048  6587  6687 D com.test.thalitest.ThaliTestRunner: Total duration: 22989 ms
08-30 15:45:17.049  6587  6687 I jxcore-log: *Native tests were executed*
08-30 15:45:17.049  6587  6687 I jxcore-log: 
08-30 15:45:17.049  6587  6687 I jxcore-log: Total number of executed tests:  80
08-30 15:45:17.049  6587  6687 I jxcore-log: 
08-30 15:45:17.049  6587  6687 I jxcore-log: Number of passed tests:  80
08-30 15:45:17.049  6587  6687 I jxcore-log: 
08-30 15:45:17.049  6587  6687 I jxcore-log: Number of failed tests:  0
08-30 15:45:17.049  6587  6687 I jxcore-log: 
08-30 15:45:17.049  6587  6687 I jxcore-log: Number of ignored tests:  0
08-30 15:45:17.049  6587  6687 I jxcore-log: 
08-30 15:45:17.050  6587  6687 I jxcore-log: Total duration:  22989
08-30 15:45:17.050  6587  6687 I jxcore-log: 
08-30 15:45:17.050  6587  6687 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 15:45:17.050  6587  6687 I jxcore-log: 
08-30 15:45:17.052  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.052  6587  6687 I jxcore-log: 
,08-30 15:45:17.055  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.055  6587  6687 I jxcore-log: 
08-30 15:45:17.056  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.056  6587  6687 I jxcore-log: 
08-30 15:45:17.057  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.057  6587  6687 I jxcore-log: 
08-30 15:45:17.058  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.058  6587  6687 I jxcore-log: 
08-30 15:45:17.059  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.059  6587  6687 I jxcore-log: 
08-30 15:45:17.061  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:45:17.061  6587  6687 I jxcore-log: 
08-30 15:45:17.061  6587  6587 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 15:45:17.063  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.063  6587  6687 I jxcore-log: 
08-30 15:45:17.063  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:45:17.063  6587  6687 I jxcore-log: 
08-30 15:45:17.064  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.064  6587  6687 I jxcore-log: 
08-30 15:45:17.064  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.064  6587  6687 I jxcore-log: 
08-30 15:45:17.065  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:45:17.065  6587  6687 I jxcore-log: 
08-30 15:45:17.066  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:45:17.066  6587  6687 I jxcore-log: 
08-30 15:45:17.066  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:45:17.066  6587  6687 I jxcore-log: 
08-30 15:45:17.067  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.067  6587  6687 I jxcore-log: 
08-30 15:45:17.067  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.067  6587  6687 I jxcore-log: 
08-30 15:45:17.068  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.068  6587  6687 I jxcore-log: 
08-30 15:45:17.068  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.068  6587  6687 I jxcore-log: 
08-30 15:45:17.069  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.069  6587  6687 I jxcore-log: 
08-30 15:45:17.069  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.069  6587  6687 I jxcore-log: 
08-30 15:45:17.070  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.070  6587  6687 I jxcore-log: 
08-30 15:45:17.071  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:45:17.071  6587  6687 I jxcore-log: 
,08-30 15:45:17.076  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:45:17.076  6587  6687 I jxcore-log: 
08-30 15:45:17.077  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:45:17.077  6587  6687 I jxcore-log: 
08-30 15:45:17.077  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.077  6587  6687 I jxcore-log: 
08-30 15:45:17.078  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.078  6587  6687 I jxcore-log: 
08-30 15:45:17.078  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.078  6587  6687 I jxcore-log: 
,08-30 15:45:17.078  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.078  6587  6687 I jxcore-log: 
08-30 15:45:17.079  6587  6687 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:45:17.079  6587  6687 I jxcore-log: 
08-30 15:45:17.087  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-30 15:45:17.087  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 15:45:17.087  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 15:45:17.087  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 15:45:17.087  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 15:45:17.087  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 15:45:17.088  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 15:45:17.088  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 15:45:17.088  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 15:45:17.088  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 15:45:17.088  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 15:45:17.088  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 15:45:17.089  8044  8044 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-30 15:45:17.098  8044  8044 V LGMDMManager: Create singleton instance
08-30 15:45:17.145  8044  8044 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-30 15:45:17.183  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:45:17.189  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:45:17.197  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:17.197  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:45:17.202  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:45:17.204  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:17.208  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:45:17.213  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:17.215  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 15:45:17.217  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:45:17.220  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:17.224  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:17.224  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:17.225  6877  6877 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:45:17.227  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 15:45:17.229  6824  6824 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 15:45:17.230  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:17.230  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:45:17.234  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:45:17.238  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:17.241  1034  8062 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 15:45:17.242  1034  8062 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 15:45:17.243  1034  8062 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 15:45:17.243  1034  8062 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 15:45:17.243  1034  8062 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 15:45:17.243  1034  8062 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 15:45:17.243  1034  8062 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 15:45:17.243  1034  8062 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 15:45:17.243  1034  8062 D DhcpStateMachine: RunningState
08-30 15:45:17.244  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:17.244  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:17.245  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:17.247  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 15:45:17.247  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:45:17.247  6824  6824 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:45:17.247  6824  6824 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 15:45:17.248  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 15:45:17.249  6824  6824 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:45:17.249  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 15:45:17.249  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:45:17.249  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:45:17.249  6824  6824 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:45:17.249  6824  6824 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 15:45:17.249  6824  6824 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 15:45:17.251  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:17.252  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 15:45:17.256  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:45:17.261  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:17.266  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:45:17.266  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:45:17.266  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:17.311  8099  8099 D AndroidRuntime: 
08-30 15:45:17.311  8099  8099 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 15:45:17.313  8099  8099 D AndroidRuntime: CheckJNI is OFF
08-30 15:45:17.356  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:45:17.357  8044  8108 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 15:45:17.358  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:45:17.372  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:17.385  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:45:17.395  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:17.396  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:17.396  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:17.398  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:45:17.399  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:45:17.407  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:17.414  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:17.422  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:17.422  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:17.422  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 15:45:17.425  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:17.426  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:45:17.431  8099  8099 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-30 15:45:17.432  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:45:17.436  1034  1379 V AlarmManager: RTC_WAKEUP set : Alarm{1fe6e817 type 0 when 1472564710743 com.google.android.gms} when 1472564710743
08-30 15:45:17.437  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{8d20404 type 2 when 142879 com.google.android.gms} when 142879
,08-30 15:45:17.437  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 15:45:17.438  1034  1092 I ActivityManager: Killing 6587:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-30 15:45:17.438  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:17.468  1034  1884 I WindowState: WIN DEATH: Window{2b80c54d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 15:45:17.469  1034  1404 D WifiService: Client connection lost with reason: 4
,08-30 15:45:17.474  1034  1884 D InputDispatcher: Window went away: Window{2b80c54d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 15:45:17.549  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{57b4ee u0 com.test.thalitest/.MainActivity t6}
,08-30 15:45:17.604   341   347 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 15:45:17.618  1034  1993 W ActivityManager: Spurious death for ProcessRecord{1dbd1ded 6587:com.test.thalitest/u0a118}, curProc for 6587: null
08-30 15:45:17.619  1034  1102 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-30 15:45:17.626  1034  1102 I ActivityManager:   Force finishing activity ActivityRecord{57b4ee u0 com.test.thalitest/.MainActivity t6 f}
08-30 15:45:17.626  1034  1102 W ActivityManager: Duplicate finish request for ActivityRecord{57b4ee u0 com.test.thalitest/.MainActivity t6 f}
,08-30 15:45:17.682  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-30 15:45:17.689  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 15:45:17.691  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 15:45:17.715  3843  3843 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 15:45:17.715  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-30 15:45:17.716  7617  7617 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 15:45:17.717  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 15:45:17.723  4490  4490 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 15:45:17.723  4490  4490 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 15:45:17.723  4490  4490 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 15:45:17.723  4490  4490 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 15:45:17.723  4490  4490 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:45:17.723  4490  4490 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:45:17.723  4490  4490 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:45:17.724  4490  4490 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:45:17.724  4490  4490 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:45:17.724  4490  4490 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:45:17.724  4490  4490 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:45:17.724  4490  4490 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:45:17.738  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 15:45:17.740  2032  2123 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 15:45:17.740  4607  4607 I art     : Explicit concurrent mark sweep GC freed 8188(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 622us total 94.913ms
,08-30 15:45:17.742  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:17.749  1034  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 15:45:17.744  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:17.752  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 15:45:17.756  2471  2595 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 15:45:17.768  1034  2031 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:45:17.770  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-30 15:45:17.798  1903  1903 D ActionManagerService: notifyUserLog: 1000003
08-30 15:45:17.799  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-30 15:45:17.803  3843  4484 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 15:45:17.809  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 15:45:17.810  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 15:45:17.810  1602  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 15:45:17.810  1602  1662 D KeyguardModel: createShortcutInfo...
08-30 15:45:17.810  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{136f746d co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 15:45:17.811  1940  3989 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 15:45:17.811  1940  3989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{353bf8a2 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 15:45:17.811  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 15:45:17.818  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:17.818  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 15:45:17.821  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 15:45:17.827  1602  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 15:45:17.827  1602  1662 D KeyguardModel: createShortcutInfo...
08-30 15:45:17.828  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 15:45:17.833  1903  1903 D ActionManagerService: notifyUserLog: 1000004
08-30 15:45:17.833  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 15:45:17.833  3843  4484 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 15:45:17.835  3843  3858 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-30 15:45:17.839  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 15:45:17.839  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , display: false
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , animation: false }
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , display: false
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , animation: false }
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , display: false
08-30 15:45:17.841  2032  2032 I GBoardWebViewUtils: , animation: false }
08-30 15:45:17.846  1034  1034 D administrator: Handling package changes for user 0
08-30 15:45:17.849  2032  8132 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-30 15:45:17.854  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-30 15:45:17.854  1867  1867 D SplitUIService: removed split : 
08-30 15:45:17.859  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 15:45:17.859  1602  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:45:17.859  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 15:45:17.861  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 15:45:17.863  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:45:17.863  1602  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 15:45:17.865  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:17.869  1602  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 15:45:17.869  1602  1662 D KeyguardModel: createShortcutInfo...
08-30 15:45:17.871  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 15:45:17.872  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 15:45:17.873  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:17.878  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 15:45:17.878  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:45:17.880  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:45:17.880  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:45:17.881  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:45:17.881  1602  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-30 15:45:17.882  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:17.882  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:17.882  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:17.884  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-30 15:45:17.884  1867  1867 I SplitUIService: split app #11
08-30 15:45:17.885  1602  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 15:45:17.885  1602  1662 D KeyguardModel: createShortcutInfo...
08-30 15:45:17.888  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:17.889  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:45:17.890  1602  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:45:17.890  1602  1662 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 15:45:17.890  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 15:45:17.890  1602  1662 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 15:45:17.892  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:45:17.892  1602  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 15:45:17.892  1034  1391 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:17.893  1034  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:17.893  1034  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 15:45:17.893  1034  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:17.893  1034  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:17.893  1034  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:45:17.894  1602  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 15:45:17.894  1602  1662 D KeyguardModel: createShortcutInfo...
08-30 15:45:17.894  1034  1408 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 15:45:17.894  1034  1408 D ConnectivityService: identical MTU - not setting
08-30 15:45:17.894  1034  1408 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 15:45:17.894  1034  1408 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 15:45:17.894  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:45:17.894  1034  1408 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:45:17.895  1034  1408 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:45:17.895  1602  2069 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 15:45:17.897  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-30 15:45:17.897  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 15:45:17.900  1602  1662 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 15:45:17.900  1602  1662 D KeyguardModel: createShortcutInfo...
08-30 15:45:17.901  1602  1662 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 15:45:17.901  1602  1662 D KeyguardModel: createShortcutInfo...
08-30 15:45:17.902  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:45:17.902  1602  1662 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 15:45:17.905  1602  1662 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 15:45:17.905  1602  1662 D KeyguardModel: createShortcutInfo...
08-30 15:45:17.906  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:45:17.906  1602  1662 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 15:45:17.907  1602  1662 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 15:45:17.907  1602  1662 D KeyguardModel: createShortcutInfo...
08-30 15:45:17.908  1602  1662 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:45:17.908  1602  1662 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 15:45:17.909  1602  1662 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 15:45:17.909  1602  1662 D KeyguardModel: createShortcutInfo...
,08-30 15:45:17.916  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:45:17.935  1034  1049 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:45:17.936  7617  7617 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 15:45:17.938  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-30 15:45:17.938  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 15:45:17.961  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:17.970  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 15:45:17.985  1034  1574 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:45:17.986  2032  2046 I art     : Background partial concurrent mark sweep GC freed 7029(320KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 5.853ms total 24.449ms
08-30 15:45:17.986  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:17.987  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:17.987  6877  6877 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:45:17.990  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:17.990  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:45:18.003  7994  7994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 15:45:18.008  8044  8108 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:45:18.009  8044  8108 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:45:18.009  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 15:45:18.009  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 15:45:18.009  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 15:45:18.010  1034  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-30 15:45:18.013  7994  7994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:18.015  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:45:18.020  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:18.034  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:18.034  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:45:18.034  6877  6877 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 15:45:18.035  6877  6877 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 15:45:18.035  6877  6877 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 15:45:18.040  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 15:45:18.043  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:45:18.043  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:45:18.044  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:45:18.045  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 15:45:18.046  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 15:45:18.047  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,08-30 15:45:18.048  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 15:45:18.050  7994  7994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 15:45:18.050  7994  7994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:45:18.053  6824  6824 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:45:18.057  1034  1102 I art     : Explicit concurrent mark sweep GC freed 80996(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.515ms total 346.539ms
08-30 15:45:18.064  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 15:45:18.065  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:45:18.065  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{184bbc08 u0 com.lge.launcher2/.Launcher t5} time:143523
,08-30 15:45:18.075  2032  2168 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 15:45:18.075  2032  2168 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 15:45:18.076  6824  6824 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:45:18.079  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 15:45:18.079  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 15:45:18.079  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:45:18.083  6877  6877 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:45:18.083  6877  6877 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:45:18.084  6877  6877 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 15:45:18.085  6877  6877 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 15:45:18.085  6877  6877 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 15:45:18.086  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 15:45:18.087  2604  2604 D [Concierge]Service: onStartCommand(). Type : 8
08-30 15:45:18.087  2604  2604 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 15:45:18.089  2604  2604 D [Concierge]Service: Update widget ID : 11
08-30 15:45:18.090  2032  2032 D [Concierge]WidgetView: change position of spinner
08-30 15:45:18.094  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1472564718094
08-30 15:45:18.094  2604  2604 D [Concierge]Service: onStartCommand(). Type : 0
,08-30 15:45:18.095  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:45:18.096  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:45:18.097  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:45:18.098  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:45:18.099  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:45:18.104  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:45:18.106  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 681654181
08-30 15:45:18.107  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 15:45:18.107  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 15:45:18.109  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2381ab25
08-30 15:45:18.110  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 15:45:18.111  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 15:45:18.111  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 15:45:18.114  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:45:18.118  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 15:45:18.118  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 15:45:18.118  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 15:45:18.121  1034  1992 I ActivityManager: Killing 7191:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 15:45:18.147  8044  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-30 15:45:18.161  8099  8099 D AndroidRuntime: Shutting down VM
,08-30 15:45:18.186  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 15:45:18.191  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 15:45:18.205  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472564602534, New one : 1472564718094
08-30 15:45:18.205  2032  2032 D [Concierge]WidgetView: Unregister all receivers
,08-30 15:45:18.205  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 15:45:18.206  1034  1575 W libprocessgroup: failed to open /acct/uid_10005/pid_7191/cgroup.procs: No such file or directory
08-30 15:45:18.242  8044  8108 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-30 15:45:18.254  8044  8108 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-30 15:45:18.254  8044  8108 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-30 15:45:18.256  8044  8108 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-30 15:45:18.257  8044  8108 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 15:45:18.258  8044  8108 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 15:45:18.265  8044  8108 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-30 15:45:18.267  8044  8108 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-30 15:45:18.278  1034  1102 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8143 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 15:45:18.280  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:45:18.282  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-30 15:45:18.286  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 15:45:18.288  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 15:45:18.288  8044  8044 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 15:45:18.290   309  8151 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 15:45:18.291   309  8151 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 15:45:18.291  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 15:45:18.292  8044  8109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:45:18.294  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 15:45:18.295  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 15:45:18.304  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:45:18.306  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 15:45:18.307  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 15:45:18.316  2186  2186 I ConfigService: onCreate
08-30 15:45:18.317  2186  2186 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 15:45:18.320  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-30 15:45:18.336  2186  2186 I ConfigService: onBind returning update interface
08-30 15:45:18.339  2186  2186 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 15:45:18.339  2186  2186 I ConfigService: onBind returning config service
,08-30 15:45:18.339   309  8151 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-30 15:45:18.347  2186  2186 I ConfigService: onDestroy
,08-30 15:45:18.361  1815  8165 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 15:45:18.363  1815  8158 I CheckinService: active receiver: enabled
,08-30 15:45:18.373  1815  8158 I CheckinService: Preparing to send checkin request
08-30 15:45:18.373  1815  8158 I EventLogService: Accumulating logs since 1472564699577
08-30 15:45:18.377  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 15:45:18.388  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-30 15:45:18.388  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 15:45:18.398  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 15:45:18.416  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1f394fb6 time:143875
08-30 15:45:18.416  5889  8172 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 15:45:18.429  1815  8174 I PeopleContactsSync: CP2 sync disabled
,08-30 15:45:18.434  1815  4754 I Icing   : doRemovePackageData com.test.thalitest
,08-30 15:45:18.453  6999  6999 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 15:45:18.457  1034  2029 I ActivityManager: Killing 7646:com.google.android.talk/u0a72 (adj 15): empty #17
08-30 15:45:18.492  1815  3984 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/EventLogService.xml to backup file /data/data/com.google.android.gms/shared_prefs/EventLogService.xml.bak
,08-30 15:45:18.559  1034  1921 W libprocessgroup: failed to open /acct/uid_10072/pid_7646/cgroup.procs: No such file or directory

```
