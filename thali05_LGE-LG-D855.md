#### Test 757892686f45c73_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-26 15:20:55.458  6523  6523 D DocsApplication: Installing DEX configuration.
07-26 15:20:55.476  6523  6523 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-26 15:20:55.480  6523  6523 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3a44e660 com.google.android.apps.docs}
07-26 15:20:55.499  6523  6523 D TAG     : onCreate()
,07-26 15:20:55.521  6523  6523 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
--------- beginning of system
07-26 15:20:55.676  1040  1982 I ActivityManager: Killing 5810:com.google.android.talk/u0a72 (adj 15): empty #17
07-26 15:20:55.797  1040  1921 W libprocessgroup: failed to open /acct/uid_10072/pid_5810/cgroup.procs: No such file or directory
07-26 15:20:55.827  6554  6554 D AndroidRuntime: 
07-26 15:20:55.827  6554  6554 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-26 15:20:55.830  6554  6554 D AndroidRuntime: CheckJNI is OFF
07-26 15:20:55.985  6554  6554 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-26 15:20:55.991  1040  1983 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-26 15:20:56.002  1948  1963 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-26 15:20:56.005  1040  1983 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-26 15:20:56.007  1040  1983 D ActivityManager: setTaskToReturnTo : TaskRecord{2a7700bd #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-26 15:20:56.007  1040  1983 D ActivityManager: setTaskToReturnTo : TaskRecord{2a7700bd #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-26 15:20:56.008  1040  1983 D WindowStateEx: AppWindowTokenEx init.. 
07-26 15:20:56.008   352   379 E GBMv2   : DFP En is all cleared set to be enabled
07-26 15:20:56.032  1040  1983 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6570 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-26 15:20:56.033  6554  6554 D AndroidRuntime: Shutting down VM
07-26 15:20:56.067  1948  1963 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-26 15:20:56.068  1948  1963 D SplitWindowPolicy: topRunningActivity=ActivityInfo{194961dc co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-26 15:20:56.069  1948  3974 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-26 15:20:56.069  1948  3974 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2c37e2e5 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-26 15:20:56.101  3220  6587 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-26 15:20:56.101   339   418 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-26 15:20:56.106  6570  6570 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-26 15:20:56.216  6570  6570 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-26 15:20:56.230  6570  6570 I LibraryLoader: Loading: webviewchromium
07-26 15:20:56.233  6570  6570 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3815-3819)
,07-26 15:20:56.234  6570  6570 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:56.251  6570  6570 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33edcfea}
,07-26 15:20:56.253  6570  6570 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:56.253  6570  6570 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-26 15:20:56.264  6570  6570 I BrowserStartupController: Initializing chromium process, renderers=0
,07-26 15:20:56.265  6570  6570 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:56.276   329  2188 V AudioPolicyService: registerClient() client 0xb558a620, uid 10118
07-26 15:20:56.276  6570  6570 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,07-26 15:20:56.276  6570  6570 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-26 15:20:56.277  6570  6570 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-26 15:20:56.282  1040  1122 D BluetoothManagerService: Message: 20
07-26 15:20:56.282  1040  1122 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e5eadac:true
07-26 15:20:56.291  6570  6570 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-26 15:20:56.291  6570  6570 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-26 15:20:56.291  6570  6570 I Adreno-EGL: Build Date: 12/12/14 금
07-26 15:20:56.291  6570  6570 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-26 15:20:56.291  6570  6570 I Adreno-EGL: Remote Branch: 
07-26 15:20:56.291  6570  6570 I Adreno-EGL: Local Patches: 
07-26 15:20:56.291  6570  6570 I Adreno-EGL: Reconstruct Branch: 
07-26 15:20:56.314  1823  4784 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,07-26 15:20:56.348  1823  4784 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,07-26 15:20:56.364  6570  6600 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,07-26 15:20:56.366  6570  6570 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-26 15:20:56.385  6570  6570 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:56.389  6570  6570 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-26 15:20:56.392  6570  6570 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-26 15:20:56.395  6570  6570 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-26 15:20:56.395  6570  6570 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,07-26 15:20:56.410  6570  6570 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-26 15:20:56.415  6570  6570 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:56.415  6570  6570 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:56.438  1823  4784 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,07-26 15:20:56.444  6570  6612 D OpenGLRenderer: Render dirty regions requested: true
07-26 15:20:56.444  6570  6612 I OpenGLRenderer: Initialized EGL, version 1.4
07-26 15:20:56.450  6570  6612 D OpenGLRenderer: Enabling debug mode 0
,07-26 15:20:56.477  6570  6570 D Atlas   : Validating map...
,07-26 15:20:56.480  1040  1055 D SplitWindow: check instance of lgWin Window{155ac786 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-26 15:20:56.517  6570  6610 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:20:56.517  6570  6610 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:20:56.627  1040  1123 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +560ms (total +618ms)
,07-26 15:20:56.630  1040  1123 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{261316b2 u0 com.test.thalitest/.MainActivity t40} time:134215
07-26 15:20:56.638  6570  6570 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1b8a9fc1 time:134224
07-26 15:20:56.742  6570  6570 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-26 15:20:56.742  6570  6570 I chromium: 
,07-26 15:20:56.787  6570  6570 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-26 15:20:56.822  6570  6610 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-26 15:20:56.822  6570  6610 I chromium: 
,07-26 15:20:56.882  6523  6523 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:20:56.882  6523  6523 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:20:56.909  6570  6628 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,07-26 15:20:56.919  6570  6628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 15:20:56.919  6570  6628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:20:56.919  6570  6628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:20:56.919  6570  6628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:20:56.919  6570  6628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-26 15:20:56.920  6570  6628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89c88b5 added. We now have 1 listener(s)
07-26 15:20:56.924  1040  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:20:56.927  6570  6628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,07-26 15:20:56.929  6570  6628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:20:56.930  6570  6628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:56.931  6570  6628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-26 15:20:56.938  6570  6628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3276bbd8 added. We now have 1 listener(s)
07-26 15:20:56.938  6570  6628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:20:56.942  1040  1473 D WifiService: New client listening to asynchronous messages
07-26 15:20:56.945  6570  6628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:56.945  6570  6628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-26 15:20:56.945  6570  6628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:20:56.946  6570  6628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-26 15:20:56.948  6570  6628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:56.949  1040  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:20:56.949  6570  6628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-26 15:20:56.959  6570  6628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:20:56.959  6570  6628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:56.959  6570  6628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:56.959  6570  6628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:56.959  6570  6628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:56.959  6570  6628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:56.959  6570  6628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:56.959  6570  6628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:56.959  6570  6628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:56.960  6570  6628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-26 15:20:56.960  6570  6628 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:56.961  6570  6628 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 15:20:56.962  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:56.964  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:56.991  6570  6570 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-26 15:20:57.079  6125  6125 I LockScreenSettings: New app installed broadcast received ..
07-26 15:20:57.084  6125  6125 I LockScreenSettings: Number of installed packages  1
07-26 15:20:57.103  6523  6523 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-26 15:20:57.142  1040  1055 V SIM_STK : Menu title from STK is T-Mobile
07-26 15:20:57.194  1040  1947 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6650 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-26 15:20:57.259   352   381 E GBMv2   : DFP En is all cleared set to be enabled
07-26 15:20:57.259   352   381 E GBMv2   : Set value is all cleared set the max
07-26 15:20:57.260   352   381 I GBMv2   : DFP Enabled. Ignore VFP set
07-26 15:20:57.284  6650  6650 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-26 15:20:57.284  6650  6650 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
07-26 15:20:57.344  1040  2037 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6669 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-26 15:20:57.345  1040  2037 I ActivityManager: Killing 5455:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-26 15:20:57.435  1040  1056 W libprocessgroup: failed to open /acct/uid_10005/pid_5455/cgroup.procs: No such file or directory
07-26 15:20:57.496  6669  6669 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-26 15:20:57.518  6669  6669 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-26 15:20:57.520  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-26 15:20:57.556  1040  1055 I ActivityManager: Killing 5655:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-26 15:20:57.574  5628  5628 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-26 15:20:57.575  5628  5628 W System.err: android.os.DeadObjectException
07-26 15:20:57.575  5628  5628 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-26 15:20:57.575  5628  5628 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-26 15:20:57.575  5628  5628 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-26 15:20:57.575  5628  5628 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-26 15:20:57.575  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-26 15:20:57.575  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-26 15:20:57.575  5628  5628 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:57.575  5628  5628 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:57.575  5628  5628 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:20:57.575  5628  5628 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-26 15:20:57.575  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.575  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:20:57.575  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-26 15:20:57.575  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-26 15:20:57.576  5628  5628 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-26 15:20:57.576  5628  5628 W System.err: android.os.DeadObjectException
07-26 15:20:57.576  5628  5628 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-26 15:20:57.576  5628  5628 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-26 15:20:57.576  5628  5628 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-26 15:20:57.576  5628  5628 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-26 15:20:57.576  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-26 15:20:57.577  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-26 15:20:57.577  5628  5628 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:57.577  5628  5628 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:57.577  5628  5628 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:20:57.577  5628  5628 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-26 15:20:57.577  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:57.577  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:20:57.577  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-26 15:20:57.577  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-26 15:20:57.577  5628  5628 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-26 15:20:57.577  5628  5628 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-26 15:20:57.619  6570  6636 W jxcore-log: Initializing JXcore engine
07-26 15:20:57.619  6570  6636 W jxcore-log: JXcore engine is ready
07-26 15:20:57.661  6636  6636 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9648]" dev="sockfs" ino=9648 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-26 15:20:57.661  6636  6636 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-26 15:20:57.661  6636  6636 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9730]" dev="sockfs" ino=9730 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-26 15:20:57.661  6636  6636 W Thread-757: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-26 15:20:57.661  6636  6636 W Thread-757: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32954]" dev="sockfs" ino=32954 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-26 15:20:57.677  6570  6636 W jxcore-log: Starting JXcore engine
07-26 15:20:57.737  1040  1643 W libprocessgroup: failed to open /acct/uid_1000/pid_5655/cgroup.procs: No such file or directory
07-26 15:20:57.737  1040  1643 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-26 15:20:57.742  5628  5628 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-26 15:20:57.743  5628  5628 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-26 15:20:57.759  6570  6636 W jxcore-log: Platform android
07-26 15:20:57.759  6570  6636 W jxcore-log: 
07-26 15:20:57.759  6570  6636 W jxcore-log: Process ARCH arm
07-26 15:20:57.759  6570  6636 W jxcore-log: 
,07-26 15:20:57.792  1040  1902 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6691 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-26 15:20:57.793  5628  5628 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-26 15:20:57.918  6691  6691 D UEI.SmartControl: Quickset Services start...
,07-26 15:20:57.920  6691  6691 I UEI.SmartControl: Manufacture = LGE
07-26 15:20:57.920  6691  6691 D UEI.SmartControl: Id = LGNevo
07-26 15:20:57.922  6691  6691 D UEI.SmartControl: File observer start...
07-26 15:20:57.922  6691  6691 E UEI.SmartControl: IR Port is disabled: false
07-26 15:20:57.923  6691  6691 D UEI.SmartControl: Starting file observer...
07-26 15:20:57.923  6691  6691 D UEI.SmartControl: Extracting JNI libs...
07-26 15:20:57.923  6691  6691 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-26 15:20:57.943  6570  6636 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:20:57.943  6570  6636 I jxcore-log: 
07-26 15:20:57.943  6570  6636 W jxcore-log: JXcore engine is started
,07-26 15:20:57.950  6570  6628 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-26 15:20:57.953  6570  6570 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-26 15:20:58.021  6691  6691 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-26 15:20:58.021  6691  6691 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-26 15:20:58.021  6691  6691 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-26 15:20:58.055  6691  6691 I UEI.SmartControl: --- Selecting new region: 6
07-26 15:20:58.056  6691  6691 I UEI.SmartControl: Model = LG-D855
,07-26 15:20:58.058  6691  6691 D UEI.SmartControl: QS Service created
07-26 15:20:58.072  6691  6691 I UEI.SmartControl: Service initServices...
,07-26 15:20:58.077  6691  6691 D UEI.SmartControl: QS start get config
07-26 15:20:58.130  6691  6691 D UEI.SmartControl: Loading JNI Libs...
,07-26 15:20:58.175  2179  2179 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,07-26 15:20:58.175  2179  2179 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,07-26 15:20:58.376  6691  6691 I UEI.SmartControl: Supports setup maps: true
07-26 15:20:58.379  6691  6691 D UEI.SmartControl: QS start statue = true Error code = 0
07-26 15:20:58.379  6691  6691 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-26 15:20:58.379  6691  6691 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-26 15:20:58.379  6691  6691 I UEI.SmartControl: ### init IR Blaster...
,07-26 15:20:58.386  6691  6691 D serial_port: Configuring serial port
07-26 15:20:58.389  6691  6691 E UEI.SmartControl: UEIBLaster setting for 616
07-26 15:20:58.389  6691  6691 I UEI.SmartControl: Setting serial record hearder size = 2
07-26 15:20:58.389  6691  6691 I UEI.SmartControl: configuring settings for MAXQ616
07-26 15:20:58.390  6691  6691 I UEI.SmartControl: Get version...
07-26 15:20:58.404  6691  6712 D UEI.SmartControl: serial port data available: 21
,07-26 15:20:58.432  6691  6691 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-26 15:20:58.432  6691  6691 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-26 15:20:58.432  6691  6691 I UEI.SmartControl: QS saving settings...
07-26 15:20:58.433  6691  6691 D UEI.SmartControl: IR Blaster version: 25672567
,07-26 15:20:58.450  6691  6712 D UEI.SmartControl: serial port data available: 4
,07-26 15:20:58.496  6691  6691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-26 15:20:58.498  6691  6691 E UEI.SmartControl: Services init done
07-26 15:20:58.498  6691  6691 D UEI.SmartControl: QS Service init finished
07-26 15:20:58.499  6691  6715 I UEI.SmartControl: Device manager: loading config....
07-26 15:20:58.499  6691  6715 D UEI.SmartControl: ----------- loading internal config...
07-26 15:20:58.505  6691  6691 D UEI.SmartControl: QS Service version name: 2.1.91
07-26 15:20:58.505  6691  6691 D UEI.SmartControl: QS Service version code: 201091
07-26 15:20:58.507  6691  6691 D UEI.SmartControl: Service requested: Control
07-26 15:20:58.509  6691  6715 E UEI.SmartControl: Loading SETTINGS...
,07-26 15:20:58.513  6691  6691 D UEI.SmartControl: Request IControl service: devices are loaded...
07-26 15:20:58.516  1040  1056 I ActivityManager: Killing 5628:com.lge.qremote/u0a112 (adj 15): empty #17
07-26 15:20:58.521  6691  6715 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-26 15:20:58.537  6691  6714 I UEI.SmartControl: Notify AllClients services are ready: 0
07-26 15:20:58.538  6691  6714 D UEI.SmartControl: -----service ready thread exits
,07-26 15:20:58.609  6691  6691 D UEI.SmartControl: Internal service binding...
,07-26 15:20:58.612  1040  1983 W libprocessgroup: failed to open /acct/uid_10112/pid_5628/cgroup.procs: No such file or directory
,07-26 15:21:00.002  1040  1384 D PowerManagerServiceEx: acquireWakeLockInternal: lock=186887661, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,07-26 15:21:00.039  4491  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,07-26 15:21:00.049  1607  1607 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-26 15:21:00.049  1607  1607 I KeyguardUpdateMonitor: called onTimeUpdated()
07-26 15:21:00.049  1607  1607 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-26 15:21:00.049  1607  1607 I [SystemUI]Clock: called onTimeUpdated()
07-26 15:21:00.057  1607  1607 I LgeClockWidgetControlView: called onTimeUpdated()
07-26 15:21:00.057  1607  1607 I [SystemUI]DateView: called onTimeUpdated()
,07-26 15:21:00.057  1607  1607 I [SystemUI]DateView: called onTimeUpdated()
07-26 15:21:00.058  1607  1607 D KeyguardUpdateMonitor: handleTimeUpdate
07-26 15:21:00.095  2623  2623 D [Concierge]Service: onStartCommand(). Type : 9
,07-26 15:21:00.111  1040  1040 D PowerManagerServiceEx: releaseWakeLockInternal: lock=186887661 [*alarm*], flags=0x0
07-26 15:21:01.016  6523  6523 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-26 15:21:01.017  1040  2051 I ActivityManager: Killing 6245:com.android.calendar/u0a13 (adj 15): empty #17
,07-26 15:21:01.095  1040  1055 W libprocessgroup: failed to open /acct/uid_10013/pid_6245/cgroup.procs: No such file or directory
,07-26 15:21:01.965  6523  6630 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-26 15:21:03.485  6691  6716 D UEI.SmartControl: Internal timer expired: 1
,07-26 15:21:03.485  6691  6716 D UEI.SmartControl: unbind internal service
,07-26 15:21:03.495  6691  6691 D UEI.SmartControl: Service.onUnbind: IControl
07-26 15:21:03.496  6691  6691 D UEI.SmartControl: Service.onDestroy
07-26 15:21:03.496  6691  6691 D UEI.SmartControl: Lock is in USE false
07-26 15:21:03.496  6691  6691 D UEI.SmartControl: unbind internal service
07-26 15:21:03.496  6691  6691 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2ed100b6
07-26 15:21:03.497  6691  6691 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-26 15:21:03.497  6691  6691 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-26 15:21:03.497  6691  6691 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-26 15:21:03.497  6691  6691 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-26 15:21:03.497  6691  6691 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-26 15:21:03.497  6691  6691 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-26 15:21:03.497  6691  6691 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-26 15:21:03.497  6691  6691 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-26 15:21:03.497  6691  6691 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:03.497  6691  6691 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:21:03.497  6691  6691 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-26 15:21:03.497  6691  6691 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:03.497  6691  6691 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:03.497  6691  6691 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-26 15:21:03.497  6691  6691 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-26 15:21:03.497  6691  6691 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2ed100b6
07-26 15:21:03.514  6691  6713 D serial_port: close(fd = 25)
,07-26 15:21:03.521  6691  6713 I UEI.SmartControl: Serial port is closed.
07-26 15:21:03.522  6691  6691 I UEI.SmartControl: Serial port is closed.
07-26 15:21:03.522  6691  6691 I UEI.SmartControl: Serial port is closed.
07-26 15:21:03.522  6691  6691 D UEI.SmartControl: Blaster closed
07-26 15:21:03.522  6691  6691 D UEI.SmartControl: Shut down QS...
07-26 15:21:03.522  6691  6691 D UEI.SmartControl: Stopping QS lib
07-26 15:21:03.522  6691  6691 D UEI.SmartControl: QS lib stop result = true
07-26 15:21:03.522  6691  6691 D UEI.SmartControl: Stopped QS lib
07-26 15:21:03.523  6691  6691 D UEI.SmartControl: Stopped file observer...
07-26 15:21:03.523  6691  6691 D UEI.SmartControl: QS shutdown complete
07-26 15:21:04.540  1823  6443 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-26 15:21:04.547   325  6744 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-26 15:21:04.547   325  6744 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-26 15:21:04.547   325  6744 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-26 15:21:05.382  1823  1823 I ConfigFetchService: fetch service done; releasing wakelock
,07-26 15:21:05.383  1823  1823 I ConfigFetchService: stopping self
,07-26 15:21:05.388  2218  2218 I ConfigService: onDestroy
,07-26 15:21:08.341  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-26 15:21:08.341  6570  6636 I jxcore-log: 
07-26 15:21:08.344  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-26 15:21:08.344  6570  6636 I jxcore-log: 
,07-26 15:21:08.350  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:08.350  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:08.350  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:08.350  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:08.350  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:08.350  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:08.350  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:08.350  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:08.353  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:08.356  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-26 15:21:08.356  6570  6636 I jxcore-log: 
,07-26 15:21:08.358  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-26 15:21:08.358  6570  6636 I jxcore-log: 
07-26 15:21:08.692  6570  6636 D ExecuteNativeTests: Running unit tests
,07-26 15:21:08.775  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:08.775  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 added. We now have 2 listener(s)
,07-26 15:21:08.776  1040  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:08.778  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:08.778  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:08.778  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:08.778  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:08.778  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 added. We now have 2 listener(s)
07-26 15:21:08.779  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:08.779  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:21:08.781  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:08.785  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:08.785  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:08.785  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:08.785  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:08.785  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:08.785  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:08.785  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:08.785  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:08.786  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:08.786  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:08.789  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-26 15:21:08.790  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:08.792  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:08.794  6570  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:21:08.794  6570  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:21:08.796  6570  6636 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-26 15:21:08.797  6570  6636 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 15:21:08.797  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:21:08.797  6570  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:21:08.797  6570  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:21:08.798  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.798  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.799  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.799  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.799  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.799  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:08.799  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:08.800  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 removed from the list
07-26 15:21:08.800  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.800  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 removed from the list
07-26 15:21:08.800  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.800  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.800  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.800  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:08.801  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.801  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.801  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.801  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.804  6570  6636 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-26 15:21:08.804  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.805  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.805  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.805  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.805  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.805  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.805  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.805  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.805  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.805  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.805  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.805  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.805  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.805  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:08.808  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.808  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.808  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.808  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-26 15:21:08.813  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-26 15:21:08.814  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:21:08.814  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-26 15:21:08.814  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-26 15:21:08.814  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-26 15:21:08.814  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.814  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.814  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.814  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.814  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.814  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.814  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.814  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.814  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.814  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.814  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.814  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.814  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.814  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.815  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.815  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.815  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.815  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.815  6570  6636 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:21:08.816  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:2,1:08.818  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:08.818  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:08.818  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:08.818  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:08.818  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:08.818  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:08.818  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:08.818  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:21:08.822  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:08.822  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:08.823  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:08.823  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:08.824  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:08.824  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:08.824  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:21:08.824  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:08.827  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:21:08.827  1040  1643 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:08.832  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-26 15:21:08.838  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:21:08.840  6570  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:21:08.841  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:21:08.842  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:08.843  6570  6636 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:08.843  6570  6636 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:21:08.846  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:21:08.846  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.846  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.846  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.846  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.846  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:08.846  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.846  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.846  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.846  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.846  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.847  6570  6636 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:21:08.849  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:08.851  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:08.851  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:08.851  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:08.851  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:08.851  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:08.851  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:08.851  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:08.851  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:08.852  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:08.852  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:08.852  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:08.852  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:08.852  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:08.852  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:21:08.855  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:08.856  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:08.859  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:21:08.859  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:08.860  6570  6636 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:08.860  6570  6636 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:21:08.862  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.862  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.862  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.862  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.862  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.862  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:08.862  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.862  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.862  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.862  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.862  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.862  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.862  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.863  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.863  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.864  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.864  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.864  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.864  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.865  6570  6636 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:21:08.866  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:08.869  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:08.869  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:08.869  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:08.869  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:08.869  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:08.869  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSI,D name: f4:f2:6d:22:99:3e
07-26 15:21:08.869  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:08.869  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:21:08.872  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:08.872  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:08.872  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:08.872  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:08.872  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:08.872  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:21:08.875  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:08.877  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:21:08.877  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:08.877  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:08.878  6570  6636 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:08.878  6570  6636 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:21:08.878  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.878  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.878  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.879  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.879  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.879  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.879  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.879  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.879  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:08.879  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.879  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.880  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.880  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.880  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.880  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.880  6570,  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:08.883  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.883  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.883  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.883  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.883  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.883  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.884  6570  6636 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-26 15:21:08.884  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.884  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.884  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.884  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.884  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.884  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.884  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.884  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.885  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.885  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.885  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.885  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.885  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.885  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.885  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.886  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.886  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.886  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.886  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.886  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.887  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:21:08.887  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.887  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, dis,covery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.887  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.887  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.887  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.887  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.887  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.887  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.887  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.887  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.887  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.887  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.887  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.887  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.888  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.889  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.889  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.889  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.889  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.889  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.890  6570  6636 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-26 15:21:08.890  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.890  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.890  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.890  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.890  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.890  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.890  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.890  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.890  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSetti,ngs: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.890  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.890  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.890  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.890  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.890  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.891  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.891  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.891  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.891  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.891  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.891  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.892  6570  6636 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-26 15:21:08.892  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.892  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.892  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.893  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.893  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.893  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.893  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.893  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.893  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.893  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.894  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.894  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.894  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.894  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.896  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.896  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.900  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.900  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.900  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.900  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.901  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:21:08.901  6570  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:21:08.901  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:21:08.902  6570  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:21:08.902  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:21:08.902  6570  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:21:08.902  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.902  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.902  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.903  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.903  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.903  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.903  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.903  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.903  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.903  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.903  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.903  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.903  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.903  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.905  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.905  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.905  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.905  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.905  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.905  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.906  6570  6636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:08.906  6570  6636 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 15:21:08.906  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:21:08.908  6570  6636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:08.908  6570  6636 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-26 15:21:08.909  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:21:08.910  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-26 15:21:08.910  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:21:08.910  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-26 15:21:08.910  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-26 15:21:08.910  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:21:08.910  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-26 15:21:08.910  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-26 15:21:08.910  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-26 15:21:08.910  6570  6636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-26 15:21:08.910  6570  6636 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:21:08.910  6570  6636 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-26 15:21:08.910  6570  6636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:08.910  6570  6636 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:21:08.910  6570  6636 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-26 15:21:08.910  6570  6636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:08.910  6570  6636 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:21:08.910  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-26 15:21:08.912  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-26 15:21:08.913  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-26 15:21:08.913  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-26 15:21:08.914  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-26 15:21:08.914  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,07-26 15:21:08.914  6570  6636 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-26 15:21:08.914  6570  6636 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:08.914  6570  6636 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-26 15:21:08.914  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.915  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.915  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.915  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.915  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.915  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.920  6570  6745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
07-26 15:21:08.922  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-26 15:21:08.922  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.922  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.922  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.922  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.922  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.922  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.922  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.922  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.924  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.924  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.924  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.924  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.924  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.924  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.927  6570  6746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
07-26 15:21:08.927  6570  6636 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-26 15:21:08.932  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.932  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.932  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.932  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.932  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.932  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.932  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.932  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.932  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.932  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.932  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.932  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.932  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.932  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.933  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.933  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.934  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.934  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.934  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.934  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.935  6570  6636 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-26 15:21:08.936  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.936  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.936  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.936  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.936  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.936  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.936  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.936  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.936  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.937  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.937  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.937  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.937  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.937  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.941  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.941  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.941  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.941  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.941  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.941  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.942  6570  6636 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-26 15:21:08.943  6570  6636 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-26 15:21:08.943  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:21:08.943  6570  6636 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-26 15:21:08.943  6570  6636 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-26 15:21:08.943  6570  6636 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-26 15:21:08.943  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:21:08.943  6570  6636 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-26 15:21:08.943  6570  6636 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-26 15:21:08.944  6570  6636 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 15:21:08.944  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:21:08.944  6570  6636 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-26 15:21:08.944  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.944  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.944  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.947  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.947  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.947  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.947  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.947  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.947  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.951  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.951  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.951  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.951  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.952  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.954  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.954  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:21:08.962  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.962  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.962  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.962  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.965  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.965  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.965  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.965  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.965  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.965  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.965  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.965  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.965  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.965  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.965  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.965  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.966  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.966  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.966  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.966  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.966  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.966  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.966  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.966  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.966  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.966  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.966  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.966  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListene,r: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.966  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.966  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.966  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.966  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.966  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.967  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.967  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.968  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.968  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.968  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.968  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.970  6570  6636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 15:21:08.970  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:08.971  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-26 15:21:08.971  6570  6636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 15:21:08.971  6570  6636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 15:21:08.972  6570  6570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-26 15:21:08.972  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-26 15:21:08.972  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 15:21:08.973  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.974  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-26 15:21:08.974  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 15:21:08.974  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 15:21:08.974  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:08.976  6570  6753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 15:21:08.976  6570  6753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 15:21:08.978  6570  6636 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 15:21:08.979  6570  6570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 15:21:08.979  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.979  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.979  6570  6570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 15:21:08.979  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 15:21:08.979  6570  6636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:21:08.979  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 15:21:08.980  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-26 15:21:08.980  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:08.980  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:08.980  6570  6636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 15:21:08.980  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.980  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.981  6570  6636 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:21:08.981  6570  6570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:21:08.981  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.982  6570  6570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:21:08.982  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.982  6570  6570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:21:08.982  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.982  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.982  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.982  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.982  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.982  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not ,in the list
07-26 15:21:08.982  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.982  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.982  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.982  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.982  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.982  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.982  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.983  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.983  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.983  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.983  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.984  6570  6636 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-26 15:21:08.985  6570  6636 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 15:21:08.985  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:21:08.985  6570  6636 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:21:08.985  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.985  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.985  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.986  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.986  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.986  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.986  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.986  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.986  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.986  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.986  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.986  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.986  6570  6636 W org.thaliproject,.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.986  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.987  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.987  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.987  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.987  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.988  1040  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:08.989  1040  1786 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:08.992  1040  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:08.993  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.993  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.993  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.993  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.993  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.993  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.993  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.993  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.993  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.993  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.993  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.993  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.993  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.993  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.994  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.994  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.994  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.994  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.995  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:08.995  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:08.995  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:08.995  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:08.995  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.995  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.995  6570  6636 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34145b76 not in the list
07-26 15:21:08.995  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.995  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.995  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:08.995  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.995  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.995  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:08.995  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:08.996  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:08.996  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:08.996  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:08.996  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13cd1577 not in the list
07-26 15:21:08.997  6570  6636 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-26 15:21:08.997  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:21:08.997  6570  6636 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-26 15:21:08.997  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:21:08.998  6570  6636 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-26 15:21:08.998  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:21:08.999  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:21:08.999  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-26 15:21:09.000  6570  6636 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-26 15:21:09.000  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:21:09.000  6570  6636 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-26 15:21:09.000  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:21:09.000  6570  6636 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-26 15:21:09.000  6570  6636 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-26 15:21:09.001  6570  6636 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-26 15:21:09.001  6570  6636 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-26 15:21:09.002  6570  6636 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-26 15:21:09.002  6570  6636 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-26 15:21:09.002  6570  6636 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-26 15:21:09.002  6570  6636 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-26 15:21:09.003  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:09.003  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@243cbd7c added. We now have 2 listener(s)
07-26 15:21:09.003  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:09.006  6570  6636 D BluetoothAdapter: enable(): BT is already enabled..!
07-26 15:21:09.007  1040  1643 D WifiServiceImplEx: setWifiEnabled: true pid=6570, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-26 15:21:09.008  1040  1643 D WifiService: setWifiEnabled: true pid=6570, uid=10118
07-26 15:21:09.008  1040  1643 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:21:09.009  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:09.009  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3980a605 added. We now have 3 listener(s)
07-26 15:21:09.009  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:09.014  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:09.014  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b3a665a added. We now have 4 listener(s)
07-26 15:21:09.014  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:09.016  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:09.016  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26a9308b added. We now have 5 listener(s)
07-26 15:21:09.016  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:09.020  1040  1982 D WifiServiceImplEx: setWifiEnabled: false pid=6570, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-26 15:21:09.020  1040  1982 D WifiService: setWifiEnabled: false pid=6570, uid=10118
07-26 15:21:09.020  1040  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:21:09.023  6570  6745 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
07-26 15:21:09.023  6570  6745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:09.024  3878  3894 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:09.024  3878  4063 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
07-26 15:21:09.024  3878  3894 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=84 mFd=82
07-26 15:21:09.038  1040  1056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:09.038  1040  1056 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3c3fddb3 mBinding = false
07-26 15:21:09.038  1040  1415 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:09.039  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:09.040  1040  1040 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-26 15:21:09.039  1040  1415 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:09.041  1040  1415 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:09.041  1040  1040 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-26 15:21:09.041  1040  1040 D Ulp_jni : JNI:system_update. Event-4
07-26 15:21:09.041  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:09.041  1040  1415 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-26 15:21:09.041  1040  1415 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:09.041  1040  1415 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-26 15:21:09.042  1040  1415 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-26 15:21:09.042  1040  1415 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-26 15:21:09.049  1040  1122 D BluetoothManagerService: Message: 2
07-26 15:21:09.050  1040  1415 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-26 15:21:09.050  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-26 15:21:09.050  1040  1122 D BluetoothManagerService: Sending off request.
07-26 15:21:09.050  2751  2751 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-26 15:21:09.051  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-26 15:21:09.051  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 1
07-26 15:21:09.052  1040  1396 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.052  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.052  3878  3895 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-26 15:21:09.052  1040  1415 D WifiNative-wlan0: SET ps 1: returned true
07-26 15:21:09.052  3878  3958 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-26 15:21:09.052  3878  3958 D BluetoothAdapterProperties: Setting state to 13
07-26 15:21:09.052  3878  3958 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-26 15:21:09.053   325   898 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:21:09.060  1040  1040 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-26 15:21:09.060  1040  2864 D DhcpStateMachine: RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.060  1040  1040 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-26 15:21:09.060  1040  1040 D Ulp_jni : JNI:system_update. Event-4
07-26 15:21:09.061  3878  3958 D BluetoothAdapterProperties: onBluetoothDisable()
07-26 15:21:09.061  3878  3958 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-26 15:21:09.062  1040  1122 D BluetoothManagerService: Message: 60
07-26 15:21:09.062  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-26 15:21:09.062  1040  1122 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,07-26 15:21:09.067  1948  1948 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:09.067  1607  1607 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-26 15:21:09.068  3878  3878 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:09.068  3878  3878 D BluetoothMapService: STATE_TURNING_OFF
07-26 15:21:09.068  3878  3878 V BluetoothMapService: Handler(): got msg=4
07-26 15:21:09.068  3878  3878 D BluetoothMapService: MAP Service closeService in
07-26 15:21:09.068  3878  3878 D BluetoothMapMasInstance: MAP Service shutdown
07-26 15:21:09.069  3878  4266 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-26 15:21:09.069  3878  4266 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:09.069  3878  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-26 15:21:09.069  3878  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-26 15:21:09.069  3878  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-26 15:21:09.069  3878  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-26 15:21:09.069  3878  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-26 15:21:09.069  3878  4266 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-26 15:21:09.069  3878  3878 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-26 15:21:09.069  3878  3878 V BluetoothMapService: MAP Service closeService out
07-26 15:21:09.071  3878  3878 V BtOppService: Receiver DISABLED_ACTION 
07-26 15:21:09.071  3878  3878 I BtOppRfcommListener: stopping Accept Thread
07-26 15:21:09.071  3878  3878 V BtOppRfcommListener: close mBtServerSocket
07-26 15:21:09.071  3878  3878 V BtOppRfcommListener: waiting for thread to terminate
07-26 15:21:09.071  3878  4322 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:09.071  3878  4322 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-26 15:21:09.072  3878  3878 V BtOppRfcommListener: done waiting for thread to terminate
07-26 15:21:09.084  1040  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-26 15:21:09.084  1040  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,07-26 15:21:09.086  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.086  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:09.086  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.086  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.086  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:09.086  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:09.086  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.086  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:09.086  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:09.087  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.087  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.110  1040  1109 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6764 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-26 15:21:09.112  1040  1415 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:09.112  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:09.112  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:09.113  1040  1415 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:09.113  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:09.113  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:09.114  1040  1415 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-26 15:21:09.115  1040  1396 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.115  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.115  1040  1396 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1aa2ee98
07-26 15:21:09.115  1040  1040 D WifiHS20: hidePasspointNotification off =false
07-26 15:21:09.116  3878  3878 V BtOppService: onDestroy
07-26 15:21:09.117  1948  1948 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-26 15:21:09.118  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:09.118  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:09.118  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-26 15:21:09.119  1040  1040 D WifiHS20: hidePasspointNotification off =false
07-26 15:21:09.119  1040  1415 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:09.120  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:09.120  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:09.124  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:09.124  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:09.124  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,07-26 15:21:09.125  1040  1040 D WifiScanningService: SCAN_AVAILABLE : 1
07-26 15:21:09.126  1040  1040 D RttService: SCAN_AVAILABLE : 1
07-26 15:21:09.126  1040  1562 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.126  1040  1561 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.128  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:09.128  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:09.128  1040  1396 D LGWifiP2pService: P2pDisablingState
07-26 15:21:09.128  1040  1396 D LGWifiP2pService: P2pDisablingState{ when=-14ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.128  1040  1396 D LGWifiP2pService: p2p socket connection lost
07-26 15:21:09.128  1040  1396 D LGWifiP2pService: P2pDisabledState
07-26 15:21:09.129  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:09.129  1040  1415 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-26 15:21:09.129  1040  1396 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.129  1040  1396 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.129  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-26 15:21:09.130  2751  2751 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-26 15:21:09.130  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-26 15:21:09.130  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 1
07-26 15:21:09.130  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-26 15:21:09.130  1948  1948 D WfdsService: WifiP2pState is changed : false
07-26 15:21:09.130  1948  2270 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-26 15:21:09.130  1948  2270 D WfdsService: Set the WFDS Monitor: false
07-26 15:21:09.131  1948  2270 D WfdsMonitor: WFDS Monitor is stopped
07-26 15:21:09.131  1948  2270 D WfdsService: STATE : WfdsDisabledState - enter
07-26 15:21:09.131  1948  2790 D CtrlSupplicant: Received on exit socket, terminate
07-26 15:21:09.131  1948  2790 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-26 15:21:09.131  1948  2790 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-26 15:21:09.131  1948  2790 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-26 15:21:09.131  1040  1415 D WifiNative-wlan0: SET ps 1: returned true
07-26 15:21:09.132  1948  2279 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-26 15:21:09.132  1948  2270 W WfdsService: DefaultState - msg [9445378] is not handled
07-26 15:21:09.133  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:09.133  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:09.134  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:09.135   325   898 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:21:09.135  1040  1477 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-26 15:21:09.135  1040  1477 D DSQN    : disableDataServiceNotify
07-26 15:21:09.135  1040  1477 D DSQN    : stop dsqn bin
07-26 15:21:09.136  1040  1415 D WifiNative-p2p0: doBoolean: TERMINATE
0,7-26 15:21:09.138  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:09.138  1040  1040 D WifiHS20: hidePasspointNotification off =false
07-26 15:21:09.138  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:09.138  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:09.138  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,07-26 15:21:09.139  1040  1415 D WifiNative-p2p0: TERMINATE: returned true
07-26 15:21:09.140  1040  1415 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-26 15:21:09.140  1040  1415 E WifiStateMachine: useWiFiOffloading() : false
07-26 15:21:09.140  1040  1415 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-26 15:21:09.144  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-26 15:21:09.144  1040  1040 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-26 15:21:09.145  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:09.145  1040  1040 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-26 15:21:09.146  1040  1477 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-26 15:21:09.147  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:09.147  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-26 15:21:09.147  1040  1477 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:09.147  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.147  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:09.147  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.147  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.147  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:09.147  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:09.147  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:09.147  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:09.147  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:09.147  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.148  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:09.148  1040  1477 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-26 15:21:09.148  1040  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.148  1040  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.148  1040  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-26 15:21:09.148  1607  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-26 15:21:09.148  1040  1477 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
,07-26 15:21:09.148  1040  1477 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-26 15:21:09.148  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:09.149  1040  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:09.149  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:09.149  1040  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:09.149  1040  1477 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:09.149  1040  1477 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:09.149  1040  1477 D NetworkManagementService: Removing idletimer
07-26 15:21:09.150  1040  1415 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:09.150  1040  1415 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:09.150  1040  1395 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-26 15:21:09.150  1040  1395 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-26 15:21:09.152  1858  1858 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:09.152  1040  1040 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-26 15:21:09.152  1040  1477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:09.152  1040  1040 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-26 15:21:09.152  1040  1040 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-26 15:21:09.152  1040  1477 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-26 15:21:09.153  1858  1858 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-26 15:21:09.153  1040  1040 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-26 15:21:09.153  1040  1040 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-26 15:21:09.153  1040  1040 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-26 15:21:09.153  1040  1040 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-26 15:21:09.153  1040  1040 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,07-26 15:21:09.166  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-26 15:21:09.166  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:09.166  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-26 15:21:09.167  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-26 15:21:09.180  1607  1607 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-26 15:21:09.181  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:09.181  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-26 15:21:09.193  1607  1607 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-26 15:21:09.194  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:09.194  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:09.225  1040  1875 I art     : Explicit concurrent mark sweep GC freed 37315(1843KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.298ms total 174.718ms
,07-26 15:21:09.226  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:09.227  3878  3963 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:21:09.227  3878  3958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-26 15:21:09.227  3878  4323 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:09.227  3878  3958 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-26 15:21:09.228  3878  4268 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:09.228  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-26 15:21:09.228  3878  4063 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-26 15:21:09.229  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-26 15:21:09.229  3878  4063 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-26 15:21:09.229  3878  4326 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:09.230  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.230  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:09.230  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.230  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.230  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:09.230  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:09.230  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:09.230  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:09.230  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:09.230  6570  6745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
07-26 15:21:09.230  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.230  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:09.230  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:09.232  6570  6570 V io.jxcore.node.ConnectivityMo,nitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.232  3878  3878 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-26 15:21:09.233  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.237  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.237  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:09.237  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.237  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.237  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:09.237  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:09.237  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:09.237  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:09.237  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:09.238  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.242  2751  2751 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-26 15:21:09.244  2751  2751 I wpa_supplicant: monitor socket send errors count : 1
07-26 15:21:09.244  2751  2751 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1948-2\x00 that cannot receive messages
07-26 15:21:09.245  1040  2788 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-26 15:21:09.245  1040  2788 D WifiMonitor: Dropping event because (p2p0) is stopped
07-26 15:21:09.249  6764  6764 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:09.249  6764  6764 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-26 15:21:09.249  6764  6764 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-26 15:21:09.250  6764  6764 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,07-26 15:21:09.251  6764  6764 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-26 15:21:09.251  6764  6764 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-26 15:21:09.265  1040  1982 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6783 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-26 15:21:09.267  1040  2864 D DhcpStateMachine: StoppedState
07-26 15:21:09.267  1040  2864 D DhcpStateMachine: StoppedState{ when=-136ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:09.268  1040  1415 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-26 15:21:09.269  1040  1415 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,07-26 15:21:09.325  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-26 15:21:09.334  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-26 15:21:09.335  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,07-26 15:21:09.336  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:09.337  3878  3878 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-26 15:21:09.337  3878  3878 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:09.338  3878  3878 V BluetoothPbapReceiver: ***********state = 13
07-26 15:21:09.338  1040  2018 I ActivityManager: Killing 6201:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-26 15:21:09.339  1040  1122 D BluetoothManagerService: Message: 20
07-26 15:21:09.339  1040  1122 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f6994a5:true
07-26 15:21:09.339  3878  3878 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-26 15:21:09.369  3878  3878 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:09.369  3878  3878 V BluetoothPbapService: state: 13
07-26 15:21:09.369  3878  3878 V BluetoothPbapService: Pbap Service closeService in
,07-26 15:21:09.369  1040  1580 W libprocessgroup: failed to open /acct/uid_10014/pid_6201/cgroup.procs: No such file or directory
07-26 15:21:09.379  3878  3878 V BluetoothPbapService: successfully stopped pbap service
07-26 15:21:09.379  3878  3878 V BluetoothPbapService: Pbap Service closeService out
,07-26 15:21:09.379  1040  1122 D BluetoothManagerService: Message: 30
07-26 15:21:09.379  3878  3878 V BluetoothPbapService: Pbap Service onDestroy
07-26 15:21:09.379  3878  3878 V BluetoothPbapService: Pbap Service closeService in
07-26 15:21:09.379  3878  3878 V BluetoothPbapService: Pbap Service closeService out
07-26 15:21:09.380  3878  3878 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-26 15:21:09.382  2218  2218 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:09.385  2751  2751 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-26 15:21:09.386  2751  2751 W wpa_supplicant: USIM:  scard_deinit function
07-26 15:21:09.387  1040  2788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-26 15:21:09.387  1040  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-26 15:21:09.387  1040  2788 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-26 15:21:09.388  1040  2788 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-26 15:21:09.388  1040  2788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:09.388  1040  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-26 15:21:09.389  1040  1415 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=146963
07-26 15:21:09.389  1040  1122 D BluetoothManagerService: Message: 30
07-26 15:21:09.390  1040  1415 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=146964
07-26 15:21:09.391  1040  1415 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=146965  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-26 15:21:09.392  1040  1415 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=146966  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-26 15:21:09.394  1040  1122 D Tethering: InitialState.processMessage what=4
,07-26 15:21:09.438  1040  2018 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6803 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
07-26 15:21:09.440  1040  1122 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-26 15:21:09.442  6764  6764 D LocalBluetoothProfileManager: Adding local MAP profile
07-26 15:21:09.443  1040  1415 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:09.443  1040  1415 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:09.449  6764  6764 D BluetoothMap: Create BluetoothMap proxy object
07-26 15:21:09.449  1040  1122 D BluetoothManagerService: Message: 30
,07-26 15:21:09.456  1040  1122 D BluetoothManagerService: Message: 30
07-26 15:21:09.458  6764  6764 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-26 15:21:09.459  6764  6764 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-26 15:21:09.476  6764  6764 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-26 15:21:09.481  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-26 15:21:09.496  6764  6764 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:09.505  2751  2751 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-26 15:21:09.506  1040  2788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-26 15:21:09.507  1040  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-26 15:21:09.507  1040  2788 D WifiMonitor: Disconnecting from the supplicant, no more events
07-26 15:21:09.509  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:09.510  1040  1415 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
07-26 15:21:09.514  1948  1948 D WfdsService: Supplicant Connection state is changed : false
07-26 15:21:09.514  1948  2270 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-26 15:21:09.514  1948  2270 D WfdsService: Set the WFDS Monitor: false
07-26 15:21:09.514  1948  2270 D WfdsMonitor: WFDS Monitor is stopped
07-26 15:21:09.520  1040  1415 D WifiOffDelayIfNotUsed: stopMonitoring
07-26 15:21:09.520  1040  1415 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-26 15:21:09.520  1040  1415 E WifiStateMachine: useWiFiOffloading() : false
07-26 15:21:09.520  1040  1415 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-26 15:21:09.521  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:09.522  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-26 15:21:09.523  2487  2487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:09.525  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:09.526  1040  1040 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-26 15:21:09.526  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.527  1040  1449 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-26 15:21:09.527  1040  1449 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-26 15:21:09.530  6803  6803 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-26 15:21:09.531  6803  6803 W LG Account v2.2: No ProfileInfo entries
07-26 15:21:09.531  6803  6803 I LG Account v2.2: isEnabled: false
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]Country: EU
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]Operator: OPEN
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]Ranking support: false
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]Comfort support: false
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]Accessory: true
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]Health device: true
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]Extra Pedometer: false
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]Blood glucose device: false
07-26 15:21:09.531  6803  6803 I Feature : [Lifetracker]Device Number: 3
07-26 15:21:09.534  1040  1643 I ActivityManager: Killing 2179:com.lge.music/u0a34 (adj 15): empty #17
07-26 15:21:09.543  6764  6764 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:09.543  6764  6764 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:09.545   329  1402 V AudioFlinger: 2179 died, releasing its sessions
,07-26 15:21:09.545   329  1402 V AudioFlinger:  pid 1858 @ 0
07-26 15:21:09.545   329  1402 V AudioFlinger:  pid 3318 @ 1
07-26 15:21:09.545   329  1402 V AudioFlinger:  pid 3318 @ 2
07-26 15:21:09.550  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:09.550  6764  6764 D BluetoothInputDevice: Proxy object connected
07-26 15:21:09.551  6764  6764 D HidProfile: Bluetooth service connected
07-26 15:21:09.552  6764  6764 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:09.552  6764  6764 D PanProfile: Bluetooth service connected
07-26 15:21:09.552  6764  6764 D BluetoothMap: Proxy object connected
07-26 15:21:09.553  6764  6764 D MapProfile: Bluetooth service connected
07-26 15:21:09.553  6764  6764 D BluetoothMap: getConnectedDevices()
07-26 15:21:09.553  6764  6764 D BluetoothMap: Bluetooth is Not enabled
07-26 15:21:09.553  6764  6764 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-26 15:21:09.566  1040  1983 W libprocessgroup: failed to open /acct/uid_10034/pid_2179/cgroup.procs: No such file or directory
,07-26 15:21:09.573  6764  6764 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-26 15:21:09.576  6764  6764 D BluetoothPermissionRequest: onReceive
07-26 15:21:09.577  6764  6764 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-26 15:21:09.587  6764  6764 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-26 15:21:09.588  1040  1875 I ActivityManager: Killing 6449:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-26 15:21:09.698  3878  3878 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-26 15:21:09.699  3878  3878 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,07-26 15:21:09.700  1040  1786 W libprocessgroup: failed to open /acct/uid_10008/pid_6449/cgroup.procs: No such file or directory
07-26 15:21:09.700  3878  3878 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-26 15:21:09.702  1040  1109 I ActivityManager: Waited long enough for: ServiceRecord{1dbbeb20 u0 com.google.android.gms/.wearable.service.WearableService}
07-26 15:21:09.802  1040  1983 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6830 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-26 15:21:09.805  3878  3878 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:09.805  3878  3878 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-26 15:21:09.807  3878  3878 V BluetoothFtpService: Ftp Service onStartCommand
07-26 15:21:09.808  3878  3878 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:09.808  3878  3878 V BluetoothFtpService: Ftp Service closeService
07-26 15:21:09.808  3878  3878 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-26 15:21:09.811  3878  3878 V BluetoothFtpService: successfully stopped ftp service
07-26 15:21:09.811  3878  3878 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-26 15:21:09.811  3878  3878 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-26 15:21:09.811  3878  3878 V BluetoothSapReceiver: SapReceiver onReceive 
07-26 15:21:09.811  3878  3878 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:09.811  3878  3878 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-26 15:21:09.811  3878  3878 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-26 15:21:09.813  3878  3878 V BluetoothFtpService: Ftp Service onDestroy
07-26 15:21:09.813  3878  3878 V BluetoothFtpService: Ftp Service closeService
07-26 15:21:09.825   356   356 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 20.715ms
,07-26 15:21:09.844   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 376us total 18.223ms
,07-26 15:21:09.861   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 16.618ms
,07-26 15:21:09.907  1040  1875 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6850 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-26 15:21:09.921  3878  3878 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:09.921  3878  3878 V BluetoothSapService: state: 13
07-26 15:21:09.922  3878  3878 V BluetoothSapService: Stopping SAP server process
07-26 15:21:09.923  3878  3878 V BluetoothSapService: Sap Service closeSapService in
07-26 15:21:09.923  3878  3878 V BluetoothSapService: Close listen Socket : 
07-26 15:21:09.924  3878  3878 V BluetoothSapService: Close rfcomm Socket : 
07-26 15:21:09.924  3878  3878 V BluetoothSapService: Close sapd  Socket : 
07-26 15:21:09.925  3878  3878 V BluetoothSapService: Sap Service closeSapService out
07-26 15:21:09.926  3878  3878 V BluetoothSapService: Sap Service onDestroy
07-26 15:21:09.926  3878  3878 V BluetoothSapService: Sap Service closeSapService in
07-26 15:21:09.926  3878  3878 V BluetoothSapService: Close listen Socket : 
07-26 15:21:09.926  3878  3878 V BluetoothSapService: Close rfcomm Socket : 
07-26 15:21:09.926  3878  3878 V BluetoothSapService: Close sapd  Socket : 
07-26 15:21:09.927  3878  3878 V BluetoothSapService: Sap Service closeSapService out
07-26 15:21:09.944  6830  6830 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-26 15:21:09.970  6830  6830 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,07-26 15:21:09.977  6850  6850 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-26 15:21:09.992  1040  1055 I ActivityManager: Killing 5993:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-26 15:21:10.007  6830  6830 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,07-26 15:21:10.007  6830  6830 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-26 15:21:10.008  6830  6830 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-26 15:21:10.009  6830  6830 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-26 15:21:10.009  6830  6830 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-26 15:21:10.011  6830  6830 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-26 15:21:10.016  6830  6830 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-26 15:21:10.027  1040  1947 W libprocessgroup: failed to open /acct/uid_10011/pid_5993/cgroup.procs: No such file or directory
,07-26 15:21:10.039  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:10.042  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:10.065  6830  6830 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-26 15:21:10.070  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:10.071  6830  6830 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-26 15:21:10.077  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-26 15:21:10.077  6830  6830 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-26 15:21:10.077  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-26 15:21:10.077  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:10.086  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:10.097  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:10.108  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:10.109  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:10.111  6830  6830 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-26 15:21:10.117  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:10.125  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-26 15:21:10.125  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-26 15:21:10.125  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-26 15:21:10.132  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:10.142  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:10.153  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-26 15:21:10.154  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:10.156  6830  6830 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-26 15:21:10.229  1040  1982 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6870 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-26 15:21:10.232  3878  3963 D bt_hci_bdroid: cleanup
07-26 15:21:10.233  3878  4065 I bt_lpm  : LPM is already off!!!
07-26 15:21:10.233  3878  4255 I bt_userial_mct: exiting userial_read_thread
07-26 15:21:10.233  3878  4255 D bt_userial_mct: Leaving userial_evt_read_thread()
07-26 15:21:10.233  3878  4063 W bt-btif : ag scb idx 1 not allocated
07-26 15:21:10.233  3878  4063 E bt-btif : BTA AG is already disabled, ignoring ...
07-26 15:21:10.233  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-26 15:21:10.233  3878  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:10.233  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:10.233  3878  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:10.234  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:10.234  3878  3963 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-26 15:21:10.235  3878  4065 I bt_vendor: hw_epilog_process
07-26 15:21:10.235  3878  3963 D bt_hci_bdroid: cleanup Finalizing cleanup
07-26 15:21:10.235  3878  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:10.235  3878  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-26 15:21:10.235  3878  3963 D bt_userial_mct: userial_close
07-26 15:21:10.235  3878  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:10.235  3878  4063 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-26 15:21:10.235  3878  3963 E bt_userial_mct: pthread_join() FAILED result:3
07-26 15:21:10.235  3878  3963 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,07-26 15:21:10.304  3878  3963 D bt_hci_bdroid: set_power 0,
,07-26 15:21:10.305  3878  3963 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-26 15:21:10.305  3878  3963 I bt_vendor: bluetooth satus is on
07-26 15:21:10.305  3878  3963 I bt_vendor: bt-vendor : resetting BT status
07-26 15:21:10.305  3878  3963 I bt_vendor: Starting hciattach daemon
07-26 15:21:10.305  3878  3963 I bt_vendor: try to set false
07-26 15:21:10.306  3878  3963 I bt_vendor: Starting hciattach daemon
07-26 15:21:10.306  3878  3963 I bt_vendor: try to set false
07-26 15:21:10.306  3878  3963 I bt_vendor: cleanup
07-26 15:21:10.308  3878  4063 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-26 15:21:10.308  3878  3963 I GKI_LINUX: GKI_exit_task 0 done
07-26 15:21:10.308  3878  3963 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-26 15:21:10.310  3878  3958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-26 15:21:10.314  3878  3878 D HeadsetService: Received stop request...Stopping profile...
07-26 15:21:10.315  3878  3878 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-26 15:21:10.316  3878  3878 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:21:10.316  3878  3878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9702db
07-26 15:21:10.316  3878  3995 D HeadsetStateMachine: Exit Disconnected: -1
07-26 15:21:10.318  1858  1858 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:10.318  1040  1040 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:10.318  1040  1040 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-26 15:21:10.318  1858  1858 D BluetoothHeadset: Proxy object disconnected
,07-26 15:21:10.318  1858  1858 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:10.319  3878  3878 D A2dpService: Received stop request...Stopping profile...
07-26 15:21:10.319  3878  4053 D A2dpStateMachine: Exit Disconnected: -1
07-26 15:21:10.322  3878  3878 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-26 15:21:10.326  3878  3878 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-26 15:21:10.326  3878  3878 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:21:10.327  3878  3878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9702db
07-26 15:21:10.328  1040  1040 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:10.328  1040  1040 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-26 15:21:10.330  3878  3878 D HidService: Received stop request...Stopping profile...
07-26 15:21:10.330  3878  3878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9702db
07-26 15:21:10.332  3878  3958 D BluetoothAdapterState: Stopping profile services that were post enabled
07-26 15:21:10.332  3878  3878 D HeadsetStateMachine: Unbinding service...
07-26 15:21:10.333  6764  6764 D BluetoothInputDevice: Proxy object disconnected
,07-26 15:21:10.333  6764  6764 D HidProfile: Bluetooth service disconnected
07-26 15:21:10.335  3878  3878 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-26 15:21:10.335  3878  3878 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,07-26 15:21:10.335  3878  3878 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-26 15:21:10.335  3878  3878 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-26 15:21:10.335  3878  3878 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 15:21:10.335  3878  3878 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:21:10.335  3878  3878 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-26 15:21:10.337  3878  3878 D HealthService: Received stop request...Stopping profile...
07-26 15:21:10.337  3878  3878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9702db
07-26 15:21:10.339  3878  3878 D PanService: Received stop request...Stopping profile...
07-26 15:21:10.340  3878  3878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9702db
07-26 15:21:10.341  3878  3878 I BluetoothA2dpServiceJni: cleanupNative
07-26 15:21:10.341  6764  6764 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-26 15:21:10.341  6764  6764 D PanProfile: Bluetooth service disconnected
07-26 15:21:10.341  3878  4054 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,07-26 15:21:10.341  3878  3878 I GKI_LINUX: GKI_exit_task 2 done
07-26 15:21:10.341  3878  3878 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-26 15:21:10.342  3878  3878 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:21:10.342  3878  3878 D BtGatt.GattService: Received stop request...Stopping profile...
07-26 15:21:10.343  3878  3878 D BtGatt.GattService: stop()
07-26 15:21:10.343  3878  3878 D BtGatt.AdvertiseManager: advertise clients cleared
07-26 15:21:10.344  3878  3878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9702db
07-26 15:21:10.345  3878  3878 D BluetoothMapService: Received stop request...Stopping profile...
07-26 15:21:10.345  3878  3878 D BluetoothMapService: stop()
07-26 15:21:10.346  3878  3878 D BluetoothMapEmailAppObserver: deinitObservers()
07-26 15:21:10.346  3878  3878 D BluetoothMapEmailAppObserver: removeReceiver()
07-26 15:21:10.346  3878  3878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9702db
07-26 15:21:10.347  6764  6764 D BluetoothMap: Proxy object disconnected
07-26 15:21:10.347  6764  6764 D MapProfile: Bluetooth service disconnected
07-26 15:21:10.348  3878  3878 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-26 15:21:10.348  3878  3878 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-26 15:21:10.348  3878  3878 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:21:10.348  3878  3878 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:21:10.348  3878  3878 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:21:10.348  3878  3878 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-26 15:21:10.348  3878  3878 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-26 15:21:10.350  3878  3878 V BluetoothMapService: Handler(): got msg=4
,07-26 15:21:10.350  3878  3878 D BluetoothMapService: MAP Service closeService in
07-26 15:21:10.350  3878  3878 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-26 15:21:10.350  3878  3878 V BluetoothMapService: MAP Service closeService out
07-26 15:21:10.350  3878  3878 D BluetoothMapService: cleanup()
07-26 15:21:10.350  3878  3878 D BluetoothMapService: MAP Service closeService in
07-26 15:21:10.350  3878  3878 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-26 15:21:10.350  3878  3878 V BluetoothMapService: MAP Service closeService out
07-26 15:21:10.350  3878  3958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,07-26 15:21:10.351  3878  3958 D BluetoothAdapterProperties: Setting state to 10
07-26 15:21:10.351  3878  3958 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-26 15:21:10.351  1040  1122 D BluetoothManagerService: Message: 60
07-26 15:21:10.351  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-26 15:21:10.351  1040  1122 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-26 15:21:10.351  3878  3958 I BluetoothAdapterState: Entering OffState
07-26 15:21:10.351  6764  6781 D BluetoothPan: onBluetoothStateChange on: false
07-26 15:21:10.353  1040  1122 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-26 15:21:10.353  1858  1873 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:10.353  1858  2447 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:10.354  1858  1874 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-26 15:21:10.355  1040  1122 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:10.355  6764  6782 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:21:10.356  6764  6781 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:21:10.356  6764  6782 D BluetoothMap: onBluetoothStateChange: up=false
07-26 15:21:10.358  1040  1122 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-26 15:21:10.358  1040  1122 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-26 15:21:10.360  1040  1122 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-26 15:21:10.360  1040  1122 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-26 15:21:10.361  1040  1122 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3c3fddb3 mBinding = false
07-26 15:21:10.361  1040  1122 D BluetoothManagerService: Sending unbind request.
07-26 15:21:10.364  1040  1122 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-26 15:21:10.373  3878  3963 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-26 15:21:10.375  3878  3878 I GKI_LINUX: GKI_exit_task 1 done
07-26 15:21:10.375  3878  3878 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-26 15:21:10.376  3878  3878 I BluetoothServiceJni: cleanupNative: return from cleanup
07-26 15:21:10.376  3878  3878 I art     : --- WEIRD: removing null entry 246
07-26 15:21:10.376  3878  3878 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-26 15:21:10.376  3878  3878 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-26 15:21:10.378  3878  3878 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-26 15:21:10.380  3878  3878 I art     : System.exit called, status: 0
07-26 15:21:10.380  3878  3878 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-26 15:21:10.384  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:10.384  1948  1948 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:10.384  1948  2109 D LGBluetoothAPIService: Message: 2
07-26 15:21:10.385  1948  2109 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3d0b91ba mBinding = false
07-26 15:21:10.385  1948  2109 D LGBluetoothAPIService: Sending unbind request.
,07-26 15:21:10.388  1607  1607 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-26 15:21:10.391  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:10.393  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:10.396  6764  6764 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-26 15:21:10.398  1607  1607 D BluetoothAdapter: 350497474: getState() :  mService = null. Returning STATE_OFF
07-26 15:21:10.398  1607  1607 D BluetoothAdapter: 350497474: getState() :  mService = null. Returning STATE_OFF
,07-26 15:21:10.403   329  2189 V AudioFlinger: 3878 died, releasing its sessions
07-26 15:21:10.403   329  2189 V AudioFlinger:  pid 1858 @ 0
07-26 15:21:10.403   329  2189 V AudioFlinger:  pid 3318 @ 1
07-26 15:21:10.404   329  2189 V AudioFlinger:  pid 3318 @ 2
07-26 15:21:10.405  6764  6764 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-26 15:21:10.405  6764  6764 D LGBluetoothEventManager: [BTUI] clear device connection state
07-26 15:21:10.407  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-26 15:21:10.505  1040  1983 I ActivityManager: Process com.android.bluetooth (pid 3878) has died
07-26 15:21:10.505  1040  1983 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,07-26 15:21:10.517  6870  6891 W FormManager: Network not available. Please check & try again.
07-26 15:21:10.528  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:10.547  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:10.547  6764  6764 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-26 15:21:10.608  1040  1946 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6900 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-26 15:21:10.613  6764  6764 D DockEventReceiver: finishStartingService: stopping service
07-26 15:21:10.630  6870  6896 V FormManager: Network unavailable.
,07-26 15:21:10.645  6870  6896 V FormManager: Network unavailable.
,07-26 15:21:10.647  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-26 15:21:10.648  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-26 15:21:10.648  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-26 15:21:10.648  6764  6764 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-26 15:21:10.649  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-26 15:21:10.661  6764  6764 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-26 15:21:10.661  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-26 15:21:10.661  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-26 15:21:10.661  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-26 15:21:10.661  6764  6764 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-26 15:21:10.661  6764  6764 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-26 15:21:10.666  1040  1946 I ActivityManager: Killing 6016:com.android.contacts/u0a19 (adj 15): empty #17
,07-26 15:21:10.751  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-26 15:21:10.752  1040  1947 W libprocessgroup: failed to open /acct/uid_10019/pid_6016/cgroup.procs: No such file or directory
07-26 15:21:10.754  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-26 15:21:10.760  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-26 15:21:10.783  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-26 15:21:10.795  4331  6920 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-26 15:21:10.796  4331  6921 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-26 15:21:10.801  6783  6783 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,07-26 15:21:10.801  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-26 15:21:10.801  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:10.805  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:10.805  4331  6921 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-26 15:21:10.807  6900  6900 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-26 15:21:10.808  6900  6900 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-26 15:21:10.808  6900  6900 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-26 15:21:10.809  6900  6900 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-26 15:21:10.812  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-26 15:21:10.824  6870  6923 W FormManager: Network not available. Please check & try again.
07-26 15:21:10.830  6870  6924 V FormManager: Network unavailable.
,07-26 15:21:10.832  6900  6900 D BluetoothAdapterApp: Loading JNI Library
07-26 15:21:10.839  6830  6830 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-26 15:21:10.841  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-26 15:21:10.842  6870  6924 V FormManager: Network unavailable.
07-26 15:21:10.843  6830  6830 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,07-26 15:21:10.869  6900  6900 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3a44e660 Instance Count = 1
,07-26 15:21:10.874  6900  6900 D BluetoothAdapterApp: onCreate
07-26 15:21:10.895  6830  6830 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:10.896  6830  6830 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:10.902  6900  6900 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-26 15:21:10.903  6900  6900 D ProfileConfigQcom: Adding HeadsetService
07-26 15:21:10.903  6830  6830 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-26 15:21:10.904  6900  6900 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-26 15:21:10.904  6900  6900 D ProfileConfigQcom: Adding A2dpService
07-26 15:21:10.905  6830  6830 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-26 15:21:10.905  6830  6830 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-26 15:21:10.905  6830  6830 V SoundPool: doLoad: loading sample sampleID=1
07-26 15:21:10.905  6900  6900 D ProfileConfigQcom: [BTUI] HidService is supported
07-26 15:21:10.905  6900  6900 D ProfileConfigQcom: Adding HidService
07-26 15:21:10.907  6830  6830 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-26 15:21:10.907  6900  6900 D ProfileConfigQcom: [BTUI] HealthService is supported
07-26 15:21:10.907  6900  6900 D ProfileConfigQcom: Adding HealthService
07-26 15:21:10.908  6830  6928 V SoundPool: Start decode
07-26 15:21:10.908  6830  6928 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-26 15:21:10.909   329  1402 V MediaPlayerService: decode(22, 10857164, 17813)
07-26 15:21:10.909   329  1402 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-26 15:21:10.909   329  1402 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-26 15:21:10.909   329  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-26 15:21:10.909   329  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-26 15:21:10.909   329  1402 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-26 15:21:10.909   329  1402 V MediaPlayerService: player type = 3
07-26 15:21:10.909   329  1402 V AwesomePlayer: AwesomePlayer create()
07-26 15:21:10.909   329  1402 V AwesomePlayer: reset_l() 
,07-26 15:21:10.910   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:10.910   329  1402 V AwesomePlayer: setAudioSink() 
07-26 15:21:10.910   329  1402 V AwesomePlayer: reset_l() 
07-26 15:21:10.910   329  1402 V AudioCache: notify(0xb16a6840, 8, 0, 0)
07-26 15:21:10.910   329  1402 V AudioCache: ignored
07-26 15:21:10.910   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:10.910   329  1402 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
07-26 15:21:10.910   329  1402 V AwesomePlayer: setDataSource_l dataSource
07-26 15:21:10.910   329  1402 V LGParserOSAL: SniffLGParser start
07-26 15:21:10.910   329  1402 V LGParserOSAL: MainType:5, SubType=0
07-26 15:21:10.910   329  1402 V LGParserOSAL: #### check Mime : application/ogg
07-26 15:21:10.910   329  1402 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-26 15:21:10.910   329  1402 E MediaExtractor: Use LGExtractor :application/ogg 
07-26 15:21:10.914  6691  6691 D UEI.SmartControl: QS Service created
07-26 15:21:10.915  6900  6900 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-26 15:21:10.917  6900  6900 D ProfileConfigQcom: [BTUI] PanService is supported
07-26 15:21:10.917  6900  6900 D ProfileConfigQcom: Adding PanService
07-26 15:21:10.917  6900  6900 D ProfileConfigQcom: [BTUI] GattService is supported
07-26 15:21:10.918  6900  6900 D ProfileConfigQcom: Adding GattService
07-26 15:21:10.918  6900  6900 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-26 15:21:10.919  6900  6900 D ProfileConfigQcom: Adding BluetoothMapService
07-26 15:21:10.919  6900  6900 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-26 15:21:10.920  6900  6900 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-26 15:21:10.921  6900  6900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:10.922  6900  6900 V BluetoothPbapReceiver: ***********state = 10
07-26 15:21:10.924  6900  6900 V LGMDMManagerInternal: Create singleton instance
07-26 15:21:10.928  6830  6830 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-26 15:21:10.934  6830  6830 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-26 15:21:10.936  6691  6691 I UEI.SmartControl: Service initServices...
07-26 15:21:10.937  6691  6691 D UEI.SmartControl: QS start get config
07-26 15:21:10.938  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,07-26 15:21:10.958   329  1402 V LGParserOSAL: supported mime: application/ogg
07-26 15:21:10.958   329  1402 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-26 15:21:10.958   329  1402 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-26 15:21:10.958   329  1402 V AwesomePlayer: mBitrate = -1 bits/sec
07-26 15:21:10.958   329  1402 V AwesomePlayer: AudioTrack Setting
07-26 15:21:10.958   329  1402 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-26 15:21:10.958   329  1402 V AwesomePlayer: setAudioSource() 
07-26 15:21:10.958   329  1402 V MediaPlayerService: prepare
07-26 15:21:10.958   329  1402 V AwesomePlayer: prepareAsync_l() 
07-26 15:21:10.959   329  1402 V MediaPlayerService: wait for prepare
07-26 15:21:10.959   329  6929 V AwesomePlayer: onPrepareAsyncEvent() 
07-26 15:21:10.959   329  6929 V AwesomePlayer: initAudioDecoder() 
07-26 15:21:10.959   329  6929 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-26 15:21:10.959   329  6929 V AudioSystem: isOffloadSupported()
07-26 15:21:10.959   329  6929 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-26 15:21:10.959   329  6929 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-26 15:21:10.959   329  6929 I AudioFlinger: isAudioPlaybackHookOn() false
07-26 15:21:10.959   329  6929 V AwesomePlayer: getUseOffload() = 0 
07-26 15:21:10.959   329  6929 V OMXCodec: OMXCodec::Create
07-26 15:21:10.959   329  6929 V OMXCodec: findMatchingCodecs()
07-26 15:21:10.959   329  6929 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-26 15:21:10.959   329  6929 V OMXCodec: matchingCodecs.size()=1
07-26 15:21:10.959   329  6929 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-26 15:21:10.961   329  6929 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-26 15:21:10.961   329  6929 V LGCodecAdapter: LG Codec Adapter start
07-26 15:21:10.961   329  6929 V OMXCodec: OMXCodec Createtor
07-26 15:21:10.961   329  6929 V OMXCodec: setComponentRole
07-26 15:21:10.961   329  6929 V OMXCodec: configureCodec protected=0
07-26 15:21:10.961   329  6929 V LGCodecAdapter: called getLGCodecSpecificData
07-26 15:21:10.961   329  6929 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-26 15:21:10.961   329  6929 V LGCodecOSAL: Called LGconfigureCodecMETA
07-26 15:21:10.962   329  6929 V LGCodecOSAL: Called LGconfigureCodecMSG
07-26 15:21:10.962   329  6929 V LGCodecOSAL: Not support LGCodec
07-26 15:21:10.962   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-26 15:21:10.962   329  6929 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-26 15:21:10.962   329  6929 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-26 15:21:10.962   329  6929 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-26 15:21:10.962   329  6929 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-26 15:21:10.962   329  6929 V AudioSystem: isOffloadSupported()
07-26 15:21:10.962   329  6929 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-26 15:21:10.962   329  6929 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-26 15:21:10.962   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-26 15:21:10.962   329  6929 V OMXCodec: init()
07-26 15:21:10.962   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
07-26 15:21:10.962   329  6929 V OMXCodec: allocateBuffers
07-26 15:21:10.962   329  6929 V OMXCodec: allocateBuffersOnPort portIndex=0
07-26 15:21:10.962   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-26 15:21:10.962   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
07-26 15:21:10.962   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
07-26 15:21:10.962   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
07-26 15:21:10.962   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
07-26 15:21:10.962   329  6929 V OMXCodec: allocateBuffersOnPort portIndex=1
07-26 15:21:10.962   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-26 15:21:10.963   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
07-26 15:21:10.963   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-26 15:21:10.963   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-26 15:21:10.963   329  6929 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
07-26 15:21:10.963   329  6929 V OMXCodec: init() mAsyncCompletion wait!!! 
07-26 15:21:10.963   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-26 15:21:10.963   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-26 15:21:10.963   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-26 15:21:10.963   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-26 15:21:10.963   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-26 15:21:10.963   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-26 15:21:10.963   329  6929 V OMXCodec: init() mAsyncCompletion wait free! 
07-26 15:21:10.963   329  6929 V AwesomePlayer: finishAsyncPrepare_l() 
07-26 15:21:10.963   329  6929 V AudioCache: notify(0xb16a6840, 5, 0, 0)
07-26 15:21:10.963   329  6929 V AudioCache: ignored
07-26 15:21:10.963   329  6929 V AudioCache: notify(0xb16a6840, 1, 0, 0)
07-26 15:21:10.963   329  6929 V AudioCache: prepared
07-26 15:21:10.963   329  1402 V AudioCache: wait - success
07-26 15:21:10.963   329  1402 V MediaPlayerService: start
07-26 15:21:10.963   329  1402 V AwesomePlayer: play_l() 
07-26 15:21:10.963   329  1402 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-26 15:21:10.963   329  1402 V AwesomePlayer: createAudioPlayer_l
07-26 15:21:10.963   329  1402 V AwesomePlayer: seekAudioIfNecessary_l() 
07-26 15:21:10.963   329  1402 V AwesomePlayer: startAudioPlayer_l() 
,07-26 15:21:10.963  6830  6830 V LGMDMManager: Create singleton instance
07-26 15:21:10.963   329  1402 D AudioPlayer: start of Playback, useOffload 0
07-26 15:21:10.964   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-26 15:21:10.964   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-26 15:21:10.966   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-26 15:21:10.967   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-26 15:21:10.967   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-26 15:21:10.967   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-26 15:21:10.967   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-26 15:21:10.967   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,07-26 15:21:10.967   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
07-26 15:21:10.967   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-26 15:21:10.967   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
07-26 15:21:10.967   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-26 15:21:10.968   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
07-26 15:21:10.968   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-26 15:21:10.968   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
07-26 15:21:10.968   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-26 15:21:10.968   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-26 15:21:10.968   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,07-26 15:21:10.968   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-26 15:21:10.968   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-26 15:21:10.968   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-26 15:21:10.968   329  6931 V OMXCodec: allocateBuffersOnPort portIndex=1
07-26 15:21:10.969   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-26 15:21:10.969   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-26 15:21:10.969   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-26 15:21:10.969   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
07-26 15:21:10.969   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f1f0 on output port
,07-26 15:21:10.969   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-26 15:21:10.969   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-26 15:21:10.971   329  1402 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-26 15:21:10.971   329  1402 V AudioCache: notify(0xb16a6840, 6, 0, 0)
,07-26 15:21:10.971   329  1402 V AudioCache: ignored
,07-26 15:21:10.972   329  1402 V MediaPlayerService: wait for playback complete
07-26 15:21:10.975   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.975   329  6932 V AudioCache: memcpy(0xb0556000, 0xb16e0000, 4096)
07-26 15:21:10.985   329  6932 V AudioCache: write(0xb16e0000, 4096)
,07-26 15:21:10.985   329  6932 V AudioCache: memcpy(0xb0557000, 0xb16e0000, 4096)
07-26 15:21:10.986   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.986   329  6932 V AudioCache: memcpy(0xb0558000, 0xb16e0000, 4096)
07-26 15:21:10.987   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.987   329  6932 V AudioCache: memcpy(0xb0559000, 0xb16e0000, 4096)
07-26 15:21:10.987   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.987   329  6932 V AudioCache: memcpy(0xb055a000, 0xb16e0000, 4096)
07-26 15:21:10.988   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.988   329  6932 V AudioCache: memcpy(0xb055b000, 0xb16e0000, 4096)
07-26 15:21:10.989   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.989   329  6932 V AudioCache: memcpy(0xb055c000, 0xb16e0000, 4096)
07-26 15:21:10.989   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.989   329  6932 V AudioCache: memcpy(0xb055d000, 0xb16e0000, 4096)
07-26 15:21:10.990   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.990   329  6932 V AudioCache: memcpy(0xb055e000, 0xb16e0000, 4096)
07-26 15:21:10.991   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.991   329  6932 V AudioCache: memcpy(0xb055f000, 0xb16e0000, 4096)
07-26 15:21:10.992   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.992   329  6932 V AudioCache: memcpy(0xb0560000, 0xb16e0000, 4096)
07-26 15:21:10.992   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.992   329  6932 V AudioCache: memcpy(0xb0561000, 0xb16e0000, 4096)
07-26 15:21:10.993   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.993   329  6932 V AudioCache: memcpy(0xb0562000, 0xb16e0000, 4096)
07-26 15:21:10.994   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.994   329  6932 V AudioCache: memcpy(0xb0563000, 0xb16e0000, 4096)
07-26 15:21:10.995   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.995   329  6932 V AudioCache: memcpy(0xb0564000, 0xb16e0000, 4096)
07-26 15:21:10.995   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.995   329  6932 V AudioCache: memcpy(0xb0565000, 0xb16e0000, 4096)
07-26 15:21:10.996   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.996   329  6932 V AudioCache: memcpy(0xb0566000, 0xb16e0000, 4096)
07-26 15:21:10.997   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.997   329  6932 V AudioCache: memcpy(0xb0567000, 0xb16e0000, 4096)
07-26 15:21:10.997   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.997   329  6932 V AudioCache: memcpy(0xb0568000, 0xb16e0000, 4096)
07-26 15:21:10.998   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.998   329  6932 V AudioCache: memcpy(0xb0569000, 0xb16e0000, 4096)
07-26 15:21:10.999   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.999   329  6932 V AudioCache: memcpy(0xb056a000, 0xb16e0000, 4096)
07-26 15:21:10.999   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:10.999   329  6932 V AudioCache: memcpy(0xb056b000, 0xb16e0000, 4096)
07-26 15:21:11.000   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.000   329  6932 V AudioCache: memcpy(0xb056c000, 0xb16e0000, 4096)
07-26 15:21:11.001   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.001   329  6932 V AudioCache: memcpy(0xb056d000, 0xb16e0000, 4096)
07-26 15:21:11.001   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.001   329  6932 V AudioCache: memcpy(0xb056e000, 0xb16e0000, 4096)
07-26 15:21:11.002   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.002   329  6932 V AudioCache: memcpy(0xb056f000, 0xb16e0000, 4096)
07-26 15:21:11.002   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.002   329  6932 V AudioCache: memcpy(0xb0570000, 0xb16e0000, 4096)
07-26 15:21:11.003   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.003   329  6932 V AudioCache: memcpy(0xb0571000, 0xb16e0000, 4096)
07-26 15:21:11.003   329  6932 V Au,dioCache: write(0xb16e0000, 4096)
07-26 15:21:11.003   329  6932 V AudioCache: memcpy(0xb0572000, 0xb16e0000, 4096)
07-26 15:21:11.004   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.004   329  6932 V AudioCache: memcpy(0xb0573000, 0xb16e0000, 4096)
07-26 15:21:11.004   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.004   329  6932 V AudioCache: memcpy(0xb0574000, 0xb16e0000, 4096)
07-26 15:21:11.006   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.006   329  6932 V AudioCache: memcpy(0xb0575000, 0xb16e0000, 4096)
07-26 15:21:11.006   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.006   329  6932 V AudioCache: memcpy(0xb0576000, 0xb16e0000, 4096)
07-26 15:21:11.006   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.006   329  6932 V AudioCache: memcpy(0xb0577000, 0xb16e0000, 4096)
07-26 15:21:11.006   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.006   329  6932 V AudioCache: memcpy(0xb0578000, 0xb16e0000, 4096)
07-26 15:21:11.008   329  6932 V AudioCache: write(0xb16e0000, 4096)
,07-26 15:21:11.008   329  6932 V AudioCache: memcpy(0xb0579000, 0xb16e0000, 4096)
07-26 15:21:11.008   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.008   329  6932 V AudioCache: memcpy(0xb057a000, 0xb16e0000, 4096)
07-26 15:21:11.009   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.009   329  6932 V AudioCache: memcpy(0xb057b000, 0xb16e0000, 4096)
07-26 15:21:11.009   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.009   329  6932 V AudioCache: memcpy(0xb057c000, 0xb16e0000, 4096)
07-26 15:21:11.009   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.009   329  6932 V AudioCache: memcpy(0xb057d000, 0xb16e0000, 4096)
,07-26 15:21:11.010   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.010   329  6932 V AudioCache: memcpy(0xb057e000, 0xb16e0000, 4096)
07-26 15:21:11.011   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.011   329  6932 V AudioCache: memcpy(0xb057f000, 0xb16e0000, 4096)
07-26 15:21:11.012   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.012   329  6932 V AudioCache: memcpy(0xb0580000, 0xb16e0000, 4096)
07-26 15:21:11.012   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.012   329  6932 V AudioCache: memcpy(0xb0581000, 0xb16e0000, 4096)
07-26 15:21:11.013   329  6932 V AudioCache: write(0xb16e0000, 4096)
,07-26 15:21:11.013   329  6932 V AudioCache: memcpy(0xb0582000, 0xb16e0000, 4096)
07-26 15:21:11.014   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.014   329  6932 V AudioCache: memcpy(0xb0583000, 0xb16e0000, 4096)
07-26 15:21:11.015   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.015   329  6932 V AudioCache: memcpy(0xb0584000, 0xb16e0000, 4096)
07-26 15:21:11.015   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.015   329  6932 V AudioCache: memcpy(0xb0585000, 0xb16e0000, 4096)
07-26 15:21:11.016   329  6932 V AudioCache: write(0xb16e0000, 4096)
07-26 15:21:11.016   329  6932 V AudioCache: memcpy(0xb0586000, 0xb16e0000, 4096)
07-26 15:21:11.017   329  6932 V AudioCache: write(0xb16e0000, 4096),
07-26 15:21:11.017   329  6932 V AudioCache: memcpy(0xb0587000, 0xb16e0000, 4096)
07-26 15:21:11.017   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-26 15:21:11.017   329  6932 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-26 15:21:11.017   329  6932 V AwesomePlayer: postAudioEOS() 
07-26 15:21:11.017   329  6932 V AudioCache: write(0xb16e0000, 280)
,07-26 15:21:11.017   329  6932 V AudioCache: memcpy(0xb0588000, 0xb16e0000, 280)
07-26 15:21:11.024   329  6929 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-26 15:21:11.024   329  6929 V AwesomePlayer: onStreamDone
07-26 15:21:11.024   329  6929 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-26 15:21:11.024   329  6929 V AudioCache: notify(0xb16a6840, 2, 0, 0)
07-26 15:21:11.024   329  6929 V AudioCache: playback complete
07-26 15:21:11.024   329  6929 V AwesomePlayer: pause_l() 
07-26 15:21:11.024   329  6929 V AudioCache: notify(0xb16a6840, 7, 0, 0)
07-26 15:21:11.024   329  6929 V AudioCache: ignored
07-26 15:21:11.024   329  6929 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:11.024   329  1402 V AudioCache: wait - success
,07-26 15:21:11.024   329  1402 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-26 15:21:11.025   329  6929 D AudioPlayer: Pause Playback at 1068125
07-26 15:21:11.025   329  1402 V AwesomePlayer: reset_l() 
07-26 15:21:11.025   329  1402 V AudioCache: notify(0xb16a6840, 8, 0, 0)
07-26 15:21:11.025   329  1402 V AudioCache: ignored
07-26 15:21:11.025   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:11.025   329  1402 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,07-26 15:21:11.025   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-26 15:21:11.025   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-26 15:21:11.025   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-26 15:21:11.025   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3,
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-26 15:21:11.026   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f1f0 on port 1
,07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-26 15:21:11.027   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-26 15:21:11.027   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-26 15:21:11.027   329  6931 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-26 15:21:11.027   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-26 15:21:11.027   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-26 15:21:11.027   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-26 15:21:11.029   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-26 15:21:11.029   329  1402 D AudioPlayer: AudioPlayer releasing audio source
07-26 15:21:11.029   329  1402 D AudioPlayer: AudioPlayer done releasing audio source
,07-26 15:21:11.029   329  1402 V AwesomePlayer: reset_l() 
07-26 15:21:11.029   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:11.029   329  1402 V AwesomePlayer: ~AwesomePlayer call
07-26 15:21:11.030   329  1402 V AwesomePlayer: reset_l() 
07-26 15:21:11.030   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:11.031  6830  6928 V SoundPool: close(31)
07-26 15:21:11.031  6830  6928 V SoundPool: pointer = 0x9fe5b000, size = 205080, sampleRate = 48000, numChannels = 2
07-26 15:21:11.035  2218  2218 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:11.045  6764  6764 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-26 15:21:11.047  6764  6764 D BluetoothPermissionRequest: onReceive
07-26 15:21:11.049  6764  6764 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-26 15:21:11.050  6764  6764 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-26 15:21:11.051  6764  6764 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-26 15:21:11.054  6900  6900 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,07-26 15:21:11.057  6900  6900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:11.059  6900  6900 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-26 15:21:11.060  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-26 15:21:11.060  6900  6900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-26 15:21:11.060  6900  6900 V BluetoothSapReceiver: SapReceiver onReceive 
07-26 15:21:11.060  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-26 15:21:11.061  6900  6900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:11.061  6900  6900 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-26 15:21:11.062  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8188
07-26 15:21:11.067  6850  6850 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,07-26 15:21:11.234  6691  6691 I UEI.SmartControl: Supports setup maps: true
,07-26 15:21:11.237  6691  6691 D UEI.SmartControl: QS start statue = true Error code = 0
07-26 15:21:11.237  6691  6691 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-26 15:21:11.237  6691  6691 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-26 15:21:11.237  6691  6691 I UEI.SmartControl: ### init IR Blaster...
07-26 15:21:11.241  6691  6691 D serial_port: Configuring serial port
07-26 15:21:11.241  6691  6691 E UEI.SmartControl: UEIBLaster setting for 616
07-26 15:21:11.241  6691  6691 I UEI.SmartControl: Setting serial record hearder size = 2
07-26 15:21:11.241  6691  6691 I UEI.SmartControl: configuring settings for MAXQ616
07-26 15:21:11.241  6691  6691 I UEI.SmartControl: Get version...
07-26 15:21:11.260  6691  6934 D UEI.SmartControl: serial port data available: 21
,07-26 15:21:11.286  6691  6691 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-26 15:21:11.286  6691  6691 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-26 15:21:11.286  6691  6691 I UEI.SmartControl: QS saving settings...
07-26 15:21:11.289  6691  6691 D UEI.SmartControl: IR Blaster version: 25672567
,07-26 15:21:11.306  6691  6934 D UEI.SmartControl: serial port data available: 4
,07-26 15:21:11.337  6691  6940 I UEI.SmartControl: Device manager: loading config....
07-26 15:21:11.339  6691  6691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-26 15:21:11.341  6691  6940 D UEI.SmartControl: ----------- loading internal config...
07-26 15:21:11.341  6691  6691 E UEI.SmartControl: Services init done
07-26 15:21:11.341  6691  6691 D UEI.SmartControl: QS Service init finished
07-26 15:21:11.343  6691  6691 D UEI.SmartControl: QS Service version name: 2.1.91
07-26 15:21:11.343  6691  6691 D UEI.SmartControl: QS Service version code: 201091
07-26 15:21:11.344  6691  6691 D UEI.SmartControl: Service requested: Control
07-26 15:21:11.349  6691  6691 D UEI.SmartControl: Request IControl service: devices are loaded...
07-26 15:21:11.350  6691  6940 E UEI.SmartControl: Loading SETTINGS...
,07-26 15:21:11.354  6830  6830 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-26 15:21:11.355  6691  6691 D UEI.SmartControl: Internal service binding...
07-26 15:21:11.356  6691  6706 I UEI.SmartControl: ------ IControl API: 11
07-26 15:21:11.356  6691  6706 D UEI.SmartControl: File observer start...
07-26 15:21:11.357  6691  6706 E UEI.SmartControl: IR Port is disabled: false
07-26 15:21:11.357  6691  6706 D UEI.SmartControl: Starting file observer...
07-26 15:21:11.358  6691  6706 I UEI.SmartControl: Registering callback...
07-26 15:21:11.359  6691  6707 I UEI.SmartControl: ------ IControl API: 19
07-26 15:21:11.360  6691  6707 I UEI.SmartControl: Registering Services Ready callback...
07-26 15:21:11.360  6691  6940 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-26 15:21:11.375  6691  6939 I UEI.SmartControl: Notify AllClients services are ready: 0
07-26 15:21:11.375  6691  6939 D UEI.SmartControl: -----service ready thread exits
,07-26 15:21:11.381  6830  6845 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-26 15:21:11.381  6830  6926 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-26 15:21:11.382  6830  6926 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-26 15:21:11.382  6830  6830 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-26 15:21:11.383  6830  6830 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-26 15:21:11.383  6691  6706 I UEI.SmartControl: ------ IControl API: 8
07-26 15:21:11.385  6830  6830 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-26 15:21:11.385  6830  6830 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-26 15:21:11.386  6830  6830 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-26 15:21:11.386  6830  6830 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-26 15:21:11.387  6830  6830 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-26 15:21:11.388  6830  6830 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-26 15:21:11.390  6830  6830 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,07-26 15:21:11.393  6830  6830 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-26 15:21:11.394  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-26 15:21:11.395  6830  6830 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-26 15:21:11.395  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-26 15:21:11.396  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-26 15:21:11.397  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-26 15:21:11.398  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-26 15:21:11.399  6830  6830 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469539271398]
07-26 15:21:11.401  6830  6830 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-26 15:21:11.405  1040  1055 I ActivityManager: Killing 6046:com.android.gallery3d/u0a27 (adj 15): empty #17
,07-26 15:21:11.426  6830  6945 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-26 15:21:11.444  1040  1055 I ActivityManager: Killing 6490:com.lge.email/u0a23 (adj 15): empty #18
,07-26 15:21:11.475  1040  1902 W libprocessgroup: failed to open /acct/uid_10027/pid_6046/cgroup.procs: No such file or directory
,07-26 15:21:11.480  1040  1875 W libprocessgroup: failed to open /acct/uid_10023/pid_6490/cgroup.procs: No such file or directory
07-26 15:21:11.489  6830  6830 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-26 15:21:11.491  6830  6830 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-26 15:21:11.492  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-26 15:21:11.493  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-26 15:21:11.494  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,07-26 15:21:11.500  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-26 15:21:11.501  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-26 15:21:11.513  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-26 15:21:12.152  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:12.167  1040  1122 D Tethering: MasterInitialState.processMessage what=3
07-26 15:21:12.189  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:12.194  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:12.194  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:12.197  1040  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:12.201  1040  1122 D Tethering: MasterInitialState.processMessage what=3
,07-26 15:21:12.213  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:12.216  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:12.218  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-26 15:21:12.221  6381  6420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-26 15:21:12.233  1040  1947 D WifiServiceImplEx: setWifiEnabled: true pid=6570, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-26 15:21:12.233  1040  1947 D WifiService: setWifiEnabled: true pid=6570, uid=10118
07-26 15:21:12.234  1040  1947 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:21:12.239  5253  5253 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-26 15:21:12.247  1040  1415 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-26 15:21:12.247  1040  1415 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,07-26 15:21:12.250  1040  1040 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-26 15:21:12.251  1040  1040 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-26 15:21:12.251  1040  1040 D Ulp_jni : JNI:system_update. Event-4
07-26 15:21:12.251  1040  1415 E WifiUtil: wfc_util_ffile_check_copy(): pid[1040] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-26 15:21:12.251  1040  1415 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-26 15:21:12.251  1040  1415 E WifiUtil: wfc_util_ffile_check_copy(): pid[1040] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-26 15:21:12.251  1040  1415 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-26 15:21:12.251  1040  1415 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-26 15:21:12.251  1040  1415 E WifiHW  : unknown target_country: EU , set to default
07-26 15:21:12.251  1040  1415 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-26 15:21:12.252  1040  1415 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-26 15:21:12.252  1040  1415 I WifiUtil: gEnableBmps=1
,07-26 15:21:12.266  5253  5253 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-26 15:21:12.280  2218  2218 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:12.315  1040  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:12.339  1040  2018 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6950 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-26 15:21:12.363  1040  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:12.363  1040  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:12.451  6950  6950 I AppUp4:AppBoxCP: onCreate
07-26 15:21:12.452  6950  6950 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-26 15:21:12.466  6950  6950 I AppUp4:DB:  setFingerPrint start
,07-26 15:21:12.466  6950  6950 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,07-26 15:21:12.476  6950  6950 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,07-26 15:21:12.476  6950  6950 I AppUp4:DB:  SDK version = 21
07-26 15:21:12.476  6950  6950 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-26 15:21:12.478  6950  6950 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-26 15:21:12.480  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-26 15:21:12.480  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:12.483  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-26 15:21:12.483  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-26 15:21:12.490  6950  6950 I AppUp4:CustModeStarterReceiver: onReceive
,07-26 15:21:12.535  6950  6950 D LgDataFeature: LgDataFeature() Constructor: none
,07-26 15:21:12.535  6950  6950 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:12.545  6950  6950 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33edcfea
07-26 15:21:12.545  6950  6950 D AppUp4:CustFacade: isCustomizationCompleted : false
07-26 15:21:12.545  6950  6950 D AppUp4:CustFacade: isPhone : true
07-26 15:21:12.546  6950  6950 D AppUp4:CustModeStarterReceiver: begin check event
07-26 15:21:12.547  6950  6950 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-26 15:21:12.547  6950  6950 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-26 15:21:12.548  6950  6983 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-26 15:21:12.548  6950  6983 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-26 15:21:12.548  6950  6983 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-26 15:21:12.551  1040  1786 I ActivityManager: Killing 6086:com.android.vending/u0a44 (adj 15): empty #17
07-26 15:21:12.613  1040  2037 W libprocessgroup: failed to open /acct/uid_10044/pid_6086/cgroup.procs: No such file or directory
,07-26 15:21:12.616  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:12.617  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-26 15:21:12.621  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:12.623  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:12.631  4331  6988 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-26 15:21:12.638  4331  6989 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:12.639  4331  6989 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-26 15:21:12.697  1040  1056 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6990 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-26 15:21:12.767  6990  6990 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:12.767  6990  6990 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-26 15:21:12.769  6990  6990 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-26 15:21:12.769  6990  6990 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-26 15:21:12.869  6990  6990 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-26 15:21:12.886  6990  6990 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-26 15:21:12.932  6990  6990 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 15:21:12.989  6990  6990 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:12.989  6990  6990 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:13.029  1040  1122 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-26 15:21:13.032  1040  1122 D Tethering: InitialState.processMessage what=4
07-26 15:21:13.045   325   898 D SoftapController: Softap fwReload - Ok
07-26 15:21:13.046  1040  1415 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (791ms)
,07-26 15:21:13.050  1040  1122 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-26 15:21:13.051   325   898 D CommandListener: Setting iface cfg
07-26 15:21:13.051   325   898 D CommandListener: Trying to bring down wlan0
07-26 15:21:13.055   325   898 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:21:13.058  1040  1415 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-26 15:21:13.065  1040  1415 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-26 15:21:13.065  1040  1415 E WifiStateMachine: useWiFiOffloading() : false
07-26 15:21:13.065  1040  1415 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-26 15:21:13.061  7017  7017 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:13.061  7017  7017 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:13.066  1040  1415 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-26 15:21:13.066  1040  1415 D WifiMonitor: connecting to supplicant
07-26 15:21:13.069  1040  1040 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-26 15:21:13.072  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:13.073  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-26 15:21:13.075  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:13.078  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:13.089  7017  7017 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-26 15:21:13.120  7017  7017 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-26 15:21:13.120  7017  7017 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-26 15:21:13.157  6990  6990 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-26 15:21:13.186  3318  3318 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,07-26 15:21:13.186  3318  3318 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:13.186  3318  3318 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-26 15:21:13.204  7017  7017 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:13.276  1040  1055 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7029 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-26 15:21:13.284  7017  7017 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-26 15:21:13.288  6870  7028 V FormManager: Network unavailable.
07-26 15:21:13.289  6990  6990 I HubEmail: JNI_OnLoad()
07-26 15:21:13.289  6990  6990 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-26 15:21:13.289  6990  6990 I HubEmail: registerNatives()
07-26 15:21:13.289  6990  6990 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-26 15:21:13.289  6990  6990 I HubEmail: registerNativeMethods()
07-26 15:21:13.289  6990  6990 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-26 15:21:13.290  6990  6990 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,07-26 15:21:13.296  6870  7028 V FormManager: Network unavailable.
07-26 15:21:13.296  6870  7027 W FormManager: Network not available. Please check & try again.
,07-26 15:21:13.303  7017  7017 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-26 15:21:13.305  6990  7044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:13.306  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-26 15:21:13.306  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-26 15:21:13.306  1040  7047 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-26 15:21:13.306  1040  7047 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-26 15:21:13.306  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-26 15:21:13.307  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-26 15:21:13.307  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-26 15:21:13.308  1040  1415 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-26 15:21:13.308  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:13.309  1040  1415 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:13.309  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:13.310  1040  1415 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:13.310  1040  1415 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-26 15:21:13.310  1040  1415 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-26 15:21:13.311  1040  1415 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-26 15:21:13.311  1040  1415 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-26 15:21:13.311  1040  1415 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,07-26 15:21:13.312  1040  1415 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-26 15:21:13.312  1040  1415 E WifiStateMachine: useWiFiOffloading() : false
07-26 15:21:13.312  1040  1415 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-26 15:21:13.312  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:13.312  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:13.312  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:13.312  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:13.312  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-26 15:21:13.313  1040  1415 D WifiNative-wlan0: doBoolean: SET update_config 1
07-26 15:21:13.313  1040  1415 D WifiNative-wlan0: SET update_config 1: returned true
07-26 15:21:13.313  1040  1415 D WifiConfigStore: Loading config and enabling all networks 
07-26 15:21:13.314  1040  1415 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-26 15:21:13.314  1040  1415 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-26 15:21:13.316  1040  1040 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-26 15:21:13.317  1040  1055 I ActivityManager: Killing 6328:com.android.defcontainer/u0a4 (adj 15): empty #17
07-26 15:21:13.318  1040  1449 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-26 15:21:13.319  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:13.319  1948  1948 D WfdService: Waiting for WifiP2p enabling
07-26 15:21:13.319  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:13.319  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:13.319  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:13.319  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:13.319  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:13.319  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:13.319  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:13.319  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:13.319  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:13.319  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:13.319  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:13.320  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:13.321  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:13.321  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:13.321  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - i,s Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:13.321  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:13.321  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:13.321  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:13.321  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:13.321  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:13.321  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:13.321  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:13.325  1040  1415 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,07-26 15:21:13.333  1040  1415 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-26 15:21:13.334  1040  1415 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-26 15:21:13.375  1040  1415 D WifiStateMachine: enableVerboseLogging : level 2
07-26 15:21:13.375  1040  1415 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-26 15:21:13.375  1040  1921 W libprocessgroup: failed to open /acct/uid_10004/pid_6328/cgroup.procs: No such file or directory
07-26 15:21:13.376  1040  1415 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-26 15:21:13.376  1040  1415 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-26 15:21:13.378  1040  1415 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-26 15:21:13.378  1040  1415 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-26 15:21:13.379  1040  1415 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-26 15:21:13.379  1040  1415 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,07-26 15:21:13.381  1040  1415 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-26 15:21:13.382  1040  1415 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-26 15:21:13.383  1040  1415 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-26 15:21:13.383  1040  1415 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-26 15:21:13.384  1040  1415 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-26 15:21:13.384  1040  1415 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,07-26 15:21:13.385  1040  1415 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,07-26 15:21:13.386  1948  1948 D WfdsService: Supplicant Connection state is changed : true
07-26 15:21:13.387  1948  2270 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-26 15:21:13.387  1948  2270 D WfdsService: Set the WFDS Monitor: true
07-26 15:21:13.387  1948  2270 D WfdsMonitor: WfdsMonitorThread create
07-26 15:21:13.387  1948  2270 D WfdsMonitor: WFDS Monitor is created and started
07-26 15:21:13.387  1948  2270 D WfdsService: WiFi: Supplicant connection re-established
07-26 15:21:13.387  1040  1415 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 15:21:13.387  1040  1415 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-26 15:21:13.388  1040  1415 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-26 15:21:13.388  1040  1415 D WifiNative-HAL: Setting external_sim to 1
07-26 15:21:13.388  1040  1415 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-26 15:21:13.388  1040  1415 D WifiNative-wlan0: SET external_sim 1: returned true
07-26 15:21:13.388  1040  1415 I WifiNative-HAL: startHal
07-26 15:21:13.388  1040  1415 D wifi    : setting scan oui 0xaf6f2440
07-26 15:21:13.389  1040  1415 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 15:21:13.389  1040  1415 I WifiNative-HAL: startHal
07-26 15:21:13.389  1040  1415 D wifi    : setting scan oui 0xaf6f2440
07-26 15:21:13.389  1040  1415 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-26 15:21:13.389  1948  7049 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-26 15:21:13.390  1040  1415 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-26 15:21:13.390  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-26 15:21:13.390  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-26 15:21:13.390  1948  7049 E CtrlSupplicant: Succeed to open control connection
07-26 15:21:13.391  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-26 15:21:13.391  1948  7049 E CtrlSupplicant: Succeed to open monitor connection
07-26 15:21:13.391  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-26 15:21:13.392  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,07-26 15:21:13.392  1948  7049 D WfdsMonitor: Supplicant connection established
07-26 15:21:13.392  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-26 15:21:13.392  1948  2270 D WfdsService: Connected to the supplicant for wfds
07-26 15:21:13.392  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-26 15:21:13.393  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-26 15:21:13.394  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-26 15:21:13.394  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-26 15:21:13.394  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-26 15:21:13.394  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-26 15:21:13.394  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,07-26 15:21:13.394  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-26 15:21:13.395  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-26 15:21:13.395  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-26 15:21:13.395  7017  7017 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-26 15:21:13.395  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-26 15:21:13.395  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-26 15:21:13.396  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-26 15:21:13.396  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-26 15:21:13.397  1040  1415 E WifiNative: : [150,970,542 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-26 15:21:13.397  1040  1415 D WifiNative-wlan0: doBoolean: RECONNECT
,07-26 15:21:13.397  1040  1415 D WifiNative-wlan0: RECONNECT: returned true
07-26 15:21:13.397  1040  1415 D WifiNative-wlan0: doString: [STATUS]
07-26 15:21:13.398  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-26 15:21:13.398  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-26 15:21:13.399  1040  1415 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-26 15:21:13.399  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 1
07-26 15:21:13.399  1040  1415 D WifiNative-wlan0: SET ps 1: returned true
,07-26 15:21:13.400  1040  1396 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler },
07-26 15:21:13.401  1040  1040 D WifiScanningService: SCAN_AVAILABLE : 3
07-26 15:21:13.401  1040  1040 D RttService: SCAN_AVAILABLE : 3
07-26 15:21:13.401  1040  1561 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.402  1040  1561 I WifiNative-HAL: startHal
07-26 15:21:13.402  1040  1561 D wifi    : getting scan capabilities on interface[1] = 0xaf6f2440
07-26 15:21:13.402  1040  1561 D wifi    : failed to get capabilities : -3
07-26 15:21:13.402  1040  1561 E WifiScanningService: could not get scan capabilities
07-26 15:21:13.402  1040  1562 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.402   325   898 D CommandListener: Setting iface cfg
07-26 15:21:13.402   325   898 D CommandListener: Trying to bring up p2p0
07-26 15:21:13.403  1040  1415 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-26 15:21:13.403  1040  1396 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-26 15:21:13.403  1040  1396 D LGWifiP2pService: P2pEnablingState
07-26 15:21:13.403  1040  1396 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.403  1040  1415 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-26 15:21:13.403  1040  1396 D LGWifiP2pService: P2p socket connection successful
07-26 15:21:13.404  1040  1396 D LGWifiP2pService: P2pEnabledState
07-26 15:21:13.404  1040  1415 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-26 15:21:13.404  1040  1415 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-26 15:21:13.405  1040  1415 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-26 15:21:13.405  1040  1415 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-26 15:21:13.406  1040  1415 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-26 15:21:13.406  1040  1415 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1,
07-26 15:21:13.406  7017  7017 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-26 15:21:13.407  1040  1415 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-26 15:21:13.408  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-26 15:21:13.408  1040  1415 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-26 15:21:13.408  1948  1948 D WfdsService: WifiP2pState is changed : true
07-26 15:21:13.408  1040  1415 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,07-26 15:21:13.408  1040  1415 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-26 15:21:13.408  7017  7017 E wpa_supplicant: disconnect_rssi_lvl: -100
07-26 15:21:13.408  1948  2270 D WfdsService: Receive the WFDS_ENABLE Method
07-26 15:21:13.408  1948  2270 D WfdsService: Set the WFDS Monitor: true
07-26 15:21:13.409  1948  2270 D WfdsService: Connected to the supplicant for wfds
07-26 15:21:13.409  1948  2270 D WfdsJNI : doCommand: WFDS_SET TRUE
,07-26 15:21:13.409  7017  7017 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-26 15:21:13.409  1948  2270 D WfdsService: selectPreferredScanChannel [36]
07-26 15:21:13.409  1948  2270 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-26 15:21:13.410  1040  1415 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-26 15:21:13.411  1040  1415 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
07-26 15:21:13.411  1040  1415 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
,07-26 15:21:13.411  1040  1396 D LGWifiP2pService: sending p2p connection changed broadcast
07-26 15:21:13.411  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,07-26 15:21:13.412  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-26 15:21:13.413  7017  7017 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:13.413  7017  7017 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-26 15:21:13.414  7017  7017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.414  1040  1415 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-26 15:21:13.414  7017  7017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.415  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-26 15:21:13.415  1040  1415 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,07-26 15:21:13.415  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:13.415  1040  7047 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:13.415  1040  7047 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:13.415  1040  1415 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-26 15:21:13.416  1948  7049 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:13.416  1040  1415 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-26 15:21:13.416  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-26 15:21:13.416  1948  7049 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:13.416  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-26 15:21:13.416  1040  7047 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:13.416  7017  7017 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-26 15:21:13.416  1040  7047 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.416  1040  7047 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.416  1040  7047 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.417  1040  7047 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:13.417  1040  7047 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.417  1040  7047 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.417  1040  7047 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.417  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-26 15:21:13.417  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-26 15:21:13.417  1040  1415 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-26 15:21:13.417  1040  1415 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-26 15:21:13.417  1040  7047 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-26 15:21:13.417  1040  7047 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-26 15:21:13.418  1040  1415 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-26 15:21:13.418  1040  1415 D WifiNative-wlan0: doBoolean: SCAN
07-26 15:21:13.418  1948  1948 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-26 15:21:13.419  1040  1415 D WifiNative-wlan0: SCAN: returned false
07-26 15:21:13.419  1948  1948 D WfdsService: isConnected: false
07-26 15:21:13.419  1040  1396 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-26 15:21:13.419  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=150993  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-26 15:21:13.420  1040  1396 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-26 15:21:13.420  1040  1396 D WifiNative-p2p0: doBoolean: SET device_name G3
07-26 15:21:13.420  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=150994  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-26 15:21:13.420  1040  1396 D WifiNative-p2p0: SET device_name G3: returned true
07-26 15:21:13.420  1040  1396 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-26 15:21:13.420  1040  1396 D LGWifiP2pService: before postfix = G3
07-26 15:21:13.420  1040  1396 D WifiServerServiceExt: postfix byte check : 2
07-26 15:21:13.421  1040  1396 D LGWifiP2pService: after postfix = G3
07-26 15:21:,13.421  1040  1396 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-26 15:21:13.421  1040  1415 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:13.421  1040  1396 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-26 15:21:13.421  1040  1396 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-26 15:21:13.421  1040  1415 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:13.422  1040  1396 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-26 15:21:13.422  1040  1396 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-26 15:21:13.422  1040  1415 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:13.422  1040  1415 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:13.422  1040  1396 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-26 15:21:13.422  1040  1396 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-26 15:21:13.423  1040  1415 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:13.423  1040  1396 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-26 15:21:13.423  1040  1396 D WifiNative-HAL: p2pGetDeviceAddress
07-26 15:21:13.423  1040  1396 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-26 15:21:13.426  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:13.426  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-26 15:21:13.427  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:13.427  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:13.427  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-26 15:21:13.427  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:13.428  1040  1396 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-26 15:21:13.428  1040  1396 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-26 15:21:13.429  1040  1396 D WifiNative-p2p0: P2P_FLUSH: returned true
07-26 15:21:13.429  1040  1396 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-26 15:21:13.429  1040  1396 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-26 15:21:13.429  1040  1396 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-26 15:21:13.429  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:13.429  1040  1040 D WifiServerServiceExt: setSupplicantStateSCANNING
07-26 15:21:13.430  1040  1396 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-26 15:21:13.430  1040  1396 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-26 15:21:13.431  1948  1948 I WfdStateTracker: handleP2pThisDeviceChanged
07-26 15:21:13.431  1948  1948 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-26 15:21:13.431  1948  1948 D WfdsService: Update P2p Interface State: 3
07-26 15:21:13.439  1040  1396 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-26 15:21:13.439  1040  1396 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-26 15:21:13.439  1040  1396 D LGWifiP2pService: InactiveState
07-26 15:21:13.439  1040  1396 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.439  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.439  1040  1396 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-26 15:21:13.440  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-26 15:21:13.440  7017  7017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:13.440  1040  7047 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-26 15:21:13.441  1040  7047 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:13.441  1040  7047 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:13.441  1040  7047 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:13.441  1948  7049 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-26 15:21:13.441  7017  7017 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-26 15:21:13.441  7017  7017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.441  1948  7049 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:13.441  1040  1396 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-26 15:21:13.441  1040  1396 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.441  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util,.StateMachine$SmHandler }
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.442  7017  7017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.442  1948  7049 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.442  1040  1396 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.443  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.443  1040  1396 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:13.443  1040  7047 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:13.443  1040  7047 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.443  1040  7047 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.443  1040  7047 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.443  1040  7047 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:13.443  1040  7047 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.443  1040  7047 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.443  1040  7047 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:13.444  1948  2270 W WfdsService: DefaultState - msg [9441285] is not handled
07-26 15:21:13.444  1040  1040 E WifiServerServiceExt: No p2p device connected
,07-26 15:21:13.465  7029  7029 D LgDataFeature: LgDataFeature() Constructor: none
,07-26 15:21:13.465  7029  7029 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:13.469  7029  7029 D PhoneMonitor: Register our PhoneStateListener
,07-26 15:21:13.480  7029  7029 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-26 15:21:13.482  7029  7029 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-26 15:21:13.505  7029  7029 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-26 15:21:13.507  7029  7029 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,07-26 15:21:13.509  7029  7029 D TelephonyAutoProfiling: [parse] Load xml
07-26 15:21:13.515  7029  7029 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-26 15:21:13.515  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-26 15:21:13.515  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-26 15:21:13.515  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
,07-26 15:21:13.515  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-26 15:21:13.515  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
,07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-26 15:21:13.516  7029  7029 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-26 15:21:13.517  7029  7029 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,07-26 15:21:13.529  7029  7029 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-26 15:21:13.535  1040  1643 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7052 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-26 15:21:13.535  1040  1643 I ActivityManager: Killing 6125:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,07-26 15:21:13.597  1040  1055 W libprocessgroup: failed to open /acct/uid_10080/pid_6125/cgroup.procs: No such file or directory
,07-26 15:21:13.800  1040  1055 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7073 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,07-26 15:21:13.803  1040  1055 I ActivityManager: Killing 6523:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,07-26 15:21:13.856  1040  1921 W libprocessgroup: failed to open /acct/uid_10061/pid_6523/cgroup.procs: No such file or directory
,07-26 15:21:13.985  1040  1982 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7090 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-26 15:21:13.987  1040  1982 I ActivityManager: Killing 6154:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-26 15:21:13.993  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-26 15:21:13.993  1040  7047 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-26 15:21:13.993  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-26 15:21:13.993  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
07-26 15:21:13.994  1040  7047 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-26 15:21:13.994  7017  7017 E wpa_supplicant: USIM:  scard_init function
07-26 15:21:13.996  7017  7017 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-26 15:21:13.997  1040  1415 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
07-26 15:21:13.997  1040  1415 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
07-26 15:21:13.998  1040  1415 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
07-26 15:21:13.998  1040  1415 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
07-26 15:21:13.998  1040  1415 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-26 15:21:13.998  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-26 15:21:13.998  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,07-26 15:21:14.046  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=151620  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-26 15:21:14.048  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.048  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:14.050  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.050  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.050  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.050  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-26 15:21:14.051  1040  1056 W libprocessgroup: failed to open /acct/uid_10097/pid_6154/cgroup.procs: No such file or directory
07-26 15:21:14.052  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=151626  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-26 15:21:14.062  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:21:14.062  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.062  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-26 15:21:14.062  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:14.063  1040  1040 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-26 15:21:14.071  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.071  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:14.072  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.086  7090  7090 I art     : Almond Protected OAT
,07-26 15:21:14.114  7017  7017 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-26 15:21:14.116  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-26 15:21:14.117  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-26 15:21:14.117  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-26 15:21:14.117  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-26 15:21:14.117  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:14.117  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-26 15:21:14.118  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=151692  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-26 15:21:14.118  1040  1122 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-26 15:21:14.118  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=151692  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-26 15:21:14.119  1040  1415 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=151693
07-26 15:21:14.119  1040  1415 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=151693
07-26 15:21:14.120  1040  1415 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=151694
07-26 15:21:14.120  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=151694
07-26 15:21:14.121  1040  1415 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=151695
07-26 15:21:14.121  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=151695  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-26 15:21:14.123  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=151697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-26 15:21:14.125  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:14.125  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:14.127  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.127  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.127  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.127  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,07-26 15:21:14.130  1040  1396 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.130  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.130  1040  1396 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.132  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.132  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.132  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-26 15:21:14.135  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:14.135  1040  1040 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-26 15:21:14.136  1040  1415 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:14.136  1040  1415 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:14.137  1040  1415 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:14.137  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:14.137  1040  1415 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:14.138  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:14.138  1040  1040 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-26 15:21:14.141  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:14.141  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,07-26 15:21:14.141  7017  7017 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-26 15:21:14.141  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-26 15:21:14.141  7017  7017 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-26 15:21:14.141  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-26 15:21:14.141  1040  7047 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-26 15:21:14.142  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-26 15:21:14.142  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-26 15:21:14.142  1040  1415 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-26 15:21:14.143  1040  1415 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
07-26 15:21:14.143  1040  1415 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-26 15:21:14.143  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-26 15:21:14.144  1040  1415 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-26 15:21:14.145  1040  7047 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-26 15:21:14.145  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:14.145  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-26 15:21:14.147  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=151720  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-26 15:21:14.147  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=151721  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-26 15:21:14.148  1040  1415 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=151722
07-26 15:21:14.148  1040  1415 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=151722
07-26 15:21:14.149  1040  1415 D WifiNative-wlan0: doString: [STATUS]
07-26 15:21:14.149  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:14.149  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-26 15:21:14.150  1040  1415 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-26 15:21:14.151  1040  1415 I WifiServiceExtension: setVHTCapabilityType  : false
07-26 15:21:14.153  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.153  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-26 15:21:14.154  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.158  1040  1415 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-26 15:21:14.159  1040  1415 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-26 15:21:14.162  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.162  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.162  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-26 15:21:14.166  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.166  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:21:14.166  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-26 15:21:14.172  1040  1415 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-26 15:21:14.172  1040  1415 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:14.172  1040  1415 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-26 15:21:14.173  1040  1477 D ConnectivityService: Got NetworkAgent Messenger
07-26 15:21:14.173  1040  1415 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-26 15:21:14.173  1040  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-26 15:21:14.173  1040  1415 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-26 15:21:14.173  1040  1477 D ConnectivityService: NetworkAgent connected
07-26 15:21:14.175  7090  7090 D WeatherApplication: removeAccount
07-26 15:21:14.175  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.175  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:14.176  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.177  1040  1415 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-26 15:21:14.177  1040  1415 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:14.177  1040  1415 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,07-26 15:21:14.178  1040  1415 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-26 15:21:14.178  1040  1415 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-26 15:21:14.179  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.179  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:14.180  7090  7090 D WeatherApplication: Account.length = 0
07-26 15:21:14.180  7090  7090 E WeatherApplication: OPERATOR:OPEN
07-26 15:21:14.181  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.182  1040  1415 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-26 15:21:14.184   325   898 D CommandListener: Setting iface cfg
07-26 15:21:14.186  7090  7090 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:14
07-26 15:21:14.187  1040  1415 E WifiStateMachine: Start Dhcp Watchdog 2
07-26 15:21:14.187  1040  7112 D DhcpStateMachine: StoppedState
07-26 15:21:14.187  1040  7112 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.187  1040  7112 D DhcpStateMachine: WaitBeforeStartState
07-26 15:21:14.187  1040  1415 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=151761  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:14.187  1040  1415 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=151761  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:14.188  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=151762  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:14.188  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:14.189  1040  1040 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,07-26 15:21:14.189  1040  1415 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=151763  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:14.189  1040  1415 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=151763  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:14.190  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=151764  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:14.190  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:105318] from screen [on:0 period:660458958] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-26 15:21:14.191  7090  7090 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-26 15:21:14.191  7090  7090 D Weather.Utils: 2 : All the weather widget is gone.
07-26 15:21:14.191  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:660458959] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-26 15:21:14.191  1040  1415 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-26 15:21:14.192  7090  7090 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-26 15:21:14.195  1040  1477 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-26 15:21:14.195  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:14.195  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:14.195  1040  1415 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:14.195  1040  1415 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:14.196  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:14.196  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:14.196  7090  7090 D WeatherAncestor: connectivity changed - connection : true
07-26 15:21:14.196  1040  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-26 15:21:14.196  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=170,0,0
07-26 15:21:14.197  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.197  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=170,0,0
07-26 15:21:14.197  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-26 15:21:14.197  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-26 15:21:14.197  7090  7090 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-26 15:21:14.197  1040  1415 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-26 15:21:14.197  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 0
07-26 15:21:14.197  1040  1415 D WifiNative-wlan0: SET ps 0: returned true
07-26 15:21:14.197  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-26 15:21:14.198  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-26 15:21:14.198  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-26 15:21:14.198  1040  1415 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-26 15:21:14.198  1040  1415 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-26 15:21:14.198  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36835254 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.198  1040  1415 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:,22:99:3e"NG700"
07-26 15:21:14.198  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36835254 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.198  1040  7112 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.198  1040  7112 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-26 15:21:14.199   325   898 D CommandListener: Setting iface cfg
07-26 15:21:14.199   325   898 D CommandListener: Trying to bring up wlan0
,07-26 15:21:14.200  1040  1415 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-26 15:21:14.201  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
07-26 15:21:14.201  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:14.201  1040  1040 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-26 15:21:14.201  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
07-26 15:21:14.201  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-26 15:21:14.201  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-26 15:21:14.201  1040  1396 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.201  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.202  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-26 15:21:14.202  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-26 15:21:14.202  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:14.202  1040  1040 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-26 15:21:14.202  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-26 15:21:14.202  1040  1415 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-26 15:21:14.202  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 1
07-26 15:21:14.208  7090  7090 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-26 15:21:14.208  7090  7090 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-26 15:21:14.209  7090  7090 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,07-26 15:21:14.223  1040  1415 D WifiNative-wlan0: SET ps 1: returned true
07-26 15:21:14.224  1040  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-26 15:21:14.224  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:14.224  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-26 15:21:14.225  1040  1415 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:14.225  1040  1415 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:14.227  7090  7090 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-26 15:21:14.228  7090  7090 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:14
07-26 15:21:14.228  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:14.228  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:14.229  1040  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-26 15:21:14.230  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-26 15:21:14.231  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-26 15:21:14.231  1040  1415 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-26 15:21:14.231  1040  1477 D ConnectivityService: ignoring duplicate network state non-change
07-26 15:21:14.281  1040  2018 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7116 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-26 15:21:14.282  1040  2018 I ActivityManager: Killing 6650:com.lge.eula/1000 (adj 15): empty #17
,07-26 15:21:14.337  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.337  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-26 15:21:14.340  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.340  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.340  1040  2051 W libprocessgroup: failed to open /acct/uid_1000/pid_6650/cgroup.procs: No such file or directory
07-26 15:21:14.340  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-26 15:21:14.342  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.351  1040  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-26 15:21:14.352  1040  1477 D ConnectivityService: Adding iface wlan0 to network 101
07-26 15:21:14.368  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.368  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.368  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,07-26 15:21:14.374  1040  1040 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-26 15:21:14.375  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.376  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:14.377  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.379  1948  1948 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-26 15:21:14.382  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.382  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.383  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-26 15:21:14.384  1040  1415 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-26 15:21:14.385  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.385  1607  1607 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-26 15:21:14.385  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.386  1040  1040 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-26 15:21:14.391  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.391  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:21:14.392  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-26 15:21:14.397  1040  1477 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-26 15:21:14.398  1040  1477 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-26 15:21:14.399  1040  1477 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-26 15:21:14.400   325   898 E Netd    : netlink response contains error (File exists)
07-26 15:21:14.400  1040  1477 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-26 15:21:14.401  1040  1477 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-26 15:21:14.401  1040  1477 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-26 15:21:14.401  1040  1477 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
07-26 15:21:14.403  1040  1477 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-26 15:21:14.403  1040  1477 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-26 15:21:14.403  1040  1477 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,07-26 15:21:14.403  1040  1477 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-26 15:21:14.403  1040  1477 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:14.403  1040  1477 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:14.403  1040  1477 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-26 15:21:14.403  1040  1477 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:14.403  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.403  1040  1477 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-26 15:21:14.403  1040  1477 D ConnectivityService: currentScore = 0, newScore = 20
07-26 15:21:14.403  1040  1477 D ConnectivityService:    accepting network in place of null
07-26 15:21:14.403  1607  1607 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-26 15:21:14.403  1040  1477 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:14.404  1040  1415 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:14.404  1040  1415 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:14.404  1040  7107 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.404  1040  7107 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-26 15:21:14.404  1040  7107 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.404  1040  7107 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-26 15:21:14.405  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.406  1858  1858 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:14.407  1858  1858 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-26 15:21:14.407  1040  7112 D DhcpStateMachine: DHCPV4 request on wlan0
07-26 15:21:14.407  1040  1477 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-26 15:21:14.407  1040 , 1477 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-26 15:21:14.407  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:14.408   325  7136 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-26 15:21:14.408  1040  7112 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-26 15:21:14.408  1040  7112 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-26 15:21:14.409  1040  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:14.409  1040  1477 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-26 15:21:14.410  1040  1477 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-26 15:21:14.412  1040  1477 D ConnectivityService: validation of new default Network = false
07-26 15:21:14.412  1040  1477 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-26 15:21:14.412  1040  1477 D DSQN    : enableDataServiceNotify 
07-26 15:21:14.412  1040  1477 D DSQN    : start dsqn bin
07-26 15:21:14.401  7137  7137 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:14.401  7137  7137 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:14.413  1040  1040 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-26 15:21:14.413  1040  1040 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-26 15:21:14.413  1040  1040 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-26 15:21:14.413  1040  1040 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-26 15:21:14.419  1040  1477 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,07-26 15:21:14.419  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 15:21:14.420  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:14.420  1040  1477 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:14.421  7137  7137 I dhcpcd  : version 5.5.6 starting
,07-26 15:21:14.421  1607  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-26 15:21:14.422  7137  7137 E dhcpcd  : get_duid: m
07-26 15:21:14.422  7137  7137 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-26 15:21:14.422  7137  7137 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-26 15:21:14.411  7138  7138 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:14.411  7138  7138 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-26 15:21:14.440  7138  7138 E DSQN    : DSQN ssw
07-26 15:21:14.451  1040  1395 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,07-26 15:21:14.467  1823  7145 I CheckinService: active receiver: enabled
07-26 15:21:14.469  1607  1607 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-26 15:21:14.470  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.470  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:14.474  1823  7145 I CheckinService: Preparing to send checkin request
07-26 15:21:14.474  1823  7145 I EventLogService: Accumulating logs since 1469539179223
07-26 15:21:14.476  7137  7137 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-26 15:21:14.476  7137  7137 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-26 15:21:14.476  7137  7137 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-26 15:21:14.476  7137  7137 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-26 15:21:14.476  7137  7137 D dhcpcd  : wlan0: sending REQUEST (xid 0x87fc7732), next in 4.53 seconds
,07-26 15:21:14.497   278   341 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-26 15:21:14.497   278   341 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,07-26 15:21:14.497   278   341 W Vold    : Returning OperationFailed - no handler for errno 0
07-26 15:21:14.498  7116  7152 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-26 15:21:14.499   278   341 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-26 15:21:14.499   278   341 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-26 15:21:14.499   278   341 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:14.500  7116  7152 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-26 15:21:14.503   278   341 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-26 15:21:14.503   278   341 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-26 15:21:14.503   278   341 W Vold    : Returning OperationFailed - no handler for errno 0
07-26 15:21:14.503  7116  7154 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-26 15:21:14.505   278   341 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-26 15:21:14.505   278   341 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-26 15:21:14.505   278   341 W Vold    : Returning OperationFailed - no handler for errno 0
07-26 15:21:14.506  7116  7154 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-26 15:21:14.506  1823  7145 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-26 15:21:14.528  7137  7137 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
07-26 15:21:14.544  7137  7137 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-26 15:21:14.544  7137  7137 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,07-26 15:21:14.545  7137  7137 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-26 15:21:14.545  7137  7137 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-26 15:21:14.545  7137  7137 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-26 15:21:14.545  7137  7137 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-26 15:21:14.545  7137  7137 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-26 15:21:14.545  7137  7137 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,07-26 15:21:14.598  1040  2051 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7175 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-26 15:21:14.608   356   356 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 203us total 10.165ms
07-26 15:21:14.618   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 9.552ms
,07-26 15:21:14.628   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 9.361ms
,07-26 15:21:14.660  7175  7175 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-26 15:21:14.660  7175  7175 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-26 15:21:14.681  7116  7116 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-26 15:21:14.684  7175  7175 I MultiDex: VM with version 2.1.0 has multidex support
07-26 15:21:14.684  7175  7175 I MultiDex: install
07-26 15:21:14.684  7175  7175 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-26 15:21:14.687  7116  7116 I LibraryLoader: Loading: webviewchromium
07-26 15:21:14.689  7116  7116 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2272-2274)
07-26 15:21:14.689  7116  7116 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:21:14.692  7175  7175 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-26 15:21:14.694  7116  7116 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c6076fd}
07-26 15:21:14.695  7116  7116 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:21:14.695  7116  7116 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-26 15:21:14.708  7116  7116 I BrowserStartupController: Initializing chromium process, renderers=0
,07-26 15:21:14.710  7116  7116 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:21:14.720   329  2189 V AudioPolicyService: registerClient() client 0xb101bce0, uid 10093
07-26 15:21:14.721  7116  7116 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-26 15:21:14.721  7116  7116 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-26 15:21:14.721  7116  7214 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-26 15:21:14.724  7116  7116 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
07-26 15:21:14.736  7116  7116 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-26 15:21:14.736  7116  7116 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-26 15:21:14.736  7116  7116 I Adreno-EGL: Build Date: 12/12/14 금
07-26 15:21:14.736  7116  7116 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-26 15:21:14.736  7116  7116 I Adreno-EGL: Remote Branch: 
07-26 15:21:14.736  7116  7116 I Adreno-EGL: Local Patches: 
07-26 15:21:14.736  7116  7116 I Adreno-EGL: Reconstruct Branch: 
,07-26 15:21:14.813  1040  7112 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-26 15:21:14.814  1040  7112 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-26 15:21:14.815  1040  7112 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-26 15:21:14.815  1040  7112 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-26 15:21:14.815  1040  7112 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-26 15:21:14.815  1040  7112 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-26 15:21:14.815  1040  7112 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-26 15:21:14.815  1040  7112 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-26 15:21:14.815  1040  7112 D DhcpStateMachine: RunningState
07-26 15:21:14.843  7116  7116 I NSApplication: Starting up...
,07-26 15:21:14.914  1040  1983 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7228 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-26 15:21:14.916  1040  1983 I ActivityManager: Killing 6669:com.lge.bnr/1000 (adj 15): empty #17
,07-26 15:21:15.060  1040  2051 W libprocessgroup: failed to open /acct/uid_1000/pid_6669/cgroup.procs: No such file or directory
,07-26 15:21:15.109  7228  7228 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-26 15:21:15.136  7175  7196 D LgDataFeature: LgDataFeature() Constructor: none
,07-26 15:21:15.137  7175  7196 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:15.211  7245  7245 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-26 15:21:15.248  1040  1921 D WifiServiceImplEx: setWifiEnabled: false pid=6570, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-26 15:21:15.248  1040  1921 D WifiService: setWifiEnabled: false pid=6570, uid=10118
07-26 15:21:15.248  1040  1921 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:21:15.258  1040  1415 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:15.258  1040  1040 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-26 15:21:15.258  1040  1040 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-26 15:21:15.258  1040  1040 D Ulp_jni : JNI:system_update. Event-4
07-26 15:21:15.258  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:15.259  1040  1415 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:15.259  1040  1415 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:15.260  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-26 15:21:15.260  1040  1415 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-26 15:21:15.260  1040  1415 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:15.260  1040  1415 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-26 15:21:15.260  1040  1415 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-26 15:21:15.260  1040  1415 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-26 15:21:15.266  1040  1415 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-26 15:21:15.266  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-26 15:21:15.266  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.266  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.266  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-26 15:21:15.266  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-26 15:21:15.266  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 1
07-26 15:21:15.267  1040  1415 D WifiNative-wlan0: SET ps 1: returned true
07-26 15:21:15.267  1040  7112 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.268   325   898 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:21:15.277  7245  7245 I dex2oat : dex2oat took 65.210ms (threads: 4)
,07-26 15:21:15.290  1040  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-26 15:21:15.290  1040  1477 D ConnectivityService: ignoring duplicate network state non-change
07-26 15:21:15.290  1040  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
07-26 15:21:15.290  1040  1040 D WifiHS20: hidePasspointNotification off =false
07-26 15:21:15.291  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:15.291  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:15.292  1948  1948 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-26 15:21:15.292  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:15.292  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:15.292  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-26 15:21:15.293  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.293  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.293  1040  1396 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1aa2ee98
07-26 15:21:15.293  1040  1415 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:15.293  1040  1396 D LGWifiP2pService: P2pDisablingState
07-26 15:21:15.293  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:15.293  1040  1396 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.293  1040  1396 D LGWifiP2pService: p2p socket connection lost
07-26 15:21:15.293  1040  1396 D LGWifiP2pService: P2pDisabledState
07-26 15:21:15.294  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:15.295  1040  1040 D WifiHS20: hidePasspointNotification off =false
,07-26 15:21:15.296  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:15.296  1040  1415 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:15.296  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:15.297  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:15.297  1040  1415 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-26 15:21:15.297  1040  1415 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,07-26 15:21:15.301  1040  1396 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.301  1040  1396 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.301  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-26 15:21:15.303  7017  7017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-26 15:21:15.303  7175  7196 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-26 15:21:15.303  7175  7196 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-26 15:21:15.303  7175  7196 I Adreno-EGL: Build Date: 12/12/14 금
07-26 15:21:15.303  7175  7196 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-26 15:21:15.303  7175  7196 I Adreno-EGL: Remote Branch: 
07-26 15:21:15.303  7175  7196 I Adreno-EGL: Local Patches: 
07-26 15:21:15.303  7175  7196 I Adreno-EGL: Reconstruct Branch: 
,07-26 15:21:15.303  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-26 15:21:15.303  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 1
07-26 15:21:15.304  1040  1415 D WifiNative-wlan0: SET ps 1: returned true
07-26 15:21:15.313  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:15.313  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:15.313  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-26 15:21:15.313  1040  1040 D WifiScanningService: SCAN_AVAILABLE : 1
07-26 15:21:15.313  1040  1040 D RttService: SCAN_AVAILABLE : 1
07-26 15:21:15.314  1040  1561 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.314  1040  1562 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.314  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-26 15:21:15.314  1948  1948 D WfdsService: WifiP2pState is changed : false
07-26 15:21:15.314  1948  2270 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-26 15:21:15.314  1948  2270 D WfdsService: Set the WFDS Monitor: false
07-26 15:21:15.316  1948  2270 D WfdsMonitor: WFDS Monitor is stopped
07-26 15:21:15.316  1948  2270 D WfdsService: STATE : WfdsDisabledState - enter
07-26 15:21:15.316  1948  7049 D CtrlSupplicant: Received on exit socket, terminate
07-26 15:21:15.316  1948  7049 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-26 15:21:15.316  1948  7049 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-26 15:21:15.316  1948  7049 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-26 15:21:15.316  1948  2279 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-26 15:21:15.318  1948  2270 W WfdsService: DefaultState - msg [9445378] is not handled
,07-26 15:21:15.328   325   898 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:21:15.328  1040  1477 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-26 15:21:15.328  1040  1477 D DSQN    : disableDataServiceNotify
07-26 15:21:15.328  1040  1477 D DSQN    : stop dsqn bin
07-26 15:21:15.329  1040  1415 D WifiNative-p2p0: doBoolean: TERMINATE
07-26 15:21:15.330  1040  1415 D WifiNative-p2p0: TERMINATE: returned true
07-26 15:21:15.330  1040  1040 D WifiHS20: hidePasspointNotification off =false
07-26 15:21:15.330  1040  1415 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-26 15:21:15.330  1040  1415 E WifiStateMachine: useWiFiOffloading() : false
07-26 15:21:15.330  1040  1415 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-26 15:21:15.331  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:15.331  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:15.331  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:15.331  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:15.331  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-26 15:21:15.331  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:15.333  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-26 15:21:15.333  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:15.334  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-26 15:21:15.335  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:15.335  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:15.335  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:15.335  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:15.335  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:15.335  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:15.335  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:15.335  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:15.335  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:15.335  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:15.335  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:15.335  1040  1040 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-26 15:21:15.335  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:15.336  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:15.336  1040  1040 D WifiServe,rServiceExt: setSupplicantStateDISCONNECTED
07-26 15:21:15.336  1040  1477 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-26 15:21:15.336  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:15.336  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:15.337  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:15.337  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:15.337  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:15.337  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:15.337  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:15.337  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:15.337  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:15.337  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:15.337  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:15.337  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:15.337  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:15.337  1040  1477 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:15.337  1040  1477 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-26 15:21:15.337  1607  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-26 15:21:15.338  1040  1477 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-26 15:21:15.338  1040  1477 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-26 15:21:15.338  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:15.338  1040  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:15.338  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:15.338  1040  1040 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-26 15:21:15.338  1040  1040 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-26 15:21:15.338  1040  1040 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAva,ilable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-26 15:21:15.338  1040  1040 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-26 15:21:15.339  1040  1395 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-26 15:21:15.339  1040  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:15.339  1040  1477 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:15.339  1040  1477 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:15.340  1040  1477 D NetworkManagementService: Removing idletimer
07-26 15:21:15.340  1040  1477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:15.340  1040  1415 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:15.340  1040  1415 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:15.340  1858  1858 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:15.340  1858  1858 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-26 15:21:15.341  1040  1040 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-26 15:21:15.341  1040  1040 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-26 15:21:15.341  1040  1040 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-26 15:21:15.341  1040  1040 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-26 15:21:15.342  1040  1395 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-26 15:21:15.350  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:15.365  1607  1607 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-26 15:21:15.366  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:15.366  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:15.379  1040  1875 I art     : Explicit concurrent mark sweep GC freed 86138(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.865ms total 186.502ms
,07-26 15:21:15.386  1607  1607 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-26 15:21:15.386  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:15.387  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:15.408  7175  7196 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-26 15:21:15.408  7175  7196 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-26 15:21:15.408  7175  7196 I Adreno-EGL: Build Date: 12/12/14 금
07-26 15:21:15.408  7175  7196 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-26 15:21:15.408  7175  7196 I Adreno-EGL: Remote Branch: 
07-26 15:21:15.408  7175  7196 I Adreno-EGL: Local Patches: 
07-26 15:21:15.408  7175  7196 I Adreno-EGL: Reconstruct Branch: 
,07-26 15:21:15.419  7017  7017 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-26 15:21:15.419  7017  7017 I wpa_supplicant: monitor socket send errors count : 1
07-26 15:21:15.419  7017  7017 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1948-4\x00 that cannot receive messages
07-26 15:21:15.419  1040  7047 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-26 15:21:15.419  1040  7047 D WifiMonitor: Dropping event because (p2p0) is stopped
,07-26 15:21:15.420  1040  1477 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
07-26 15:21:15.440  7017  7017 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-26 15:21:15.440  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-26 15:21:15.440  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-26 15:21:15.440  1040  7047 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-26 15:21:15.440  1040  7047 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-26 15:21:15.441  7017  7017 W wpa_supplicant: USIM:  scard_deinit function
07-26 15:21:15.441  1040  1415 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153015
07-26 15:21:15.441  1040  1415 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153015
07-26 15:21:15.441  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:15.441  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-26 15:21:15.441  1040  1415 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=153015  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,07-26 15:21:15.442  1040  1415 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=153016  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-26 15:21:15.442  1040  1122 D Tethering: InitialState.processMessage what=4
07-26 15:21:15.443  1040  1122 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-26 15:21:15.444  1040  1415 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:15.445  1040  1415 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:15.453  7175  7196 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-26 15:21:15.453  7175  7196 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-26 15:21:15.453  7175  7196 I Adreno-EGL: Build Date: 12/12/14 금
07-26 15:21:15.453  7175  7196 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-26 15:21:15.453  7175  7196 I Adreno-EGL: Remote Branch: 
07-26 15:21:15.453  7175  7196 I Adreno-EGL: Local Patches: 
07-26 15:21:15.453  7175  7196 I Adreno-EGL: Reconstruct Branch: 
07-26 15:21:15.474  1040  7112 D DhcpStateMachine: StoppedState
07-26 15:21:15.474  1040  7112 D DhcpStateMachine: StoppedState{ when=-169ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:15.475  1040  1415 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-26 15:21:15.475  1040  1415 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,07-26 15:21:15.516  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-26 15:21:15.517  6381  6420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-26 15:21:15.532  2218  2218 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:15.539  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-26 15:21:15.539  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:15.539  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-26 15:21:15.539  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-26 15:21:15.541  6950  6950 I AppUp4:CustModeStarterReceiver: onReceive
07-26 15:21:15.543  6950  6950 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33edcfea
,07-26 15:21:15.543  6950  6950 D AppUp4:CustFacade: isCustomizationCompleted : false
07-26 15:21:15.543  6950  6950 D AppUp4:CustFacade: isPhone : true
07-26 15:21:15.544  6950  6950 D AppUp4:CustModeStarterReceiver: begin check event
07-26 15:21:15.544  6950  6950 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,07-26 15:21:15.547  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:15.547  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-26 15:21:15.549  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:15.550  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:15.553  4331  7266 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-26 15:21:15.555  7017  7017 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-26 15:21:15.557  1040  7047 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-26 15:21:15.557  1040  7047 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
07-26 15:21:15.557  1040  7047 D WifiMonitor: Disconnecting from the supplicant, no more events
07-26 15:21:15.558  1040  1415 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
07-26 15:21:15.561  6990  6990 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-26 15:21:15.560  4331  7267 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:15.563  4331  7267 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-26 15:21:15.579  6990  7270 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:21:15.583  3318  3318 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-26 15:21:15.583  3318  3318 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:15.583  3318  3318 I LgeMiscReceiver: networkInfo.isConnected() = false
07-26 15:21:15.589  7029  7029 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-26 15:21:15.589  7029  7029 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-26 15:21:15.598  7090  7090 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:15
,07-26 15:21:15.600  6870  7273 W FormManager: Network not available. Please check & try again.
,07-26 15:21:15.600  6870  7275 V FormManager: Network unavailable.
07-26 15:21:15.601  7090  7090 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-26 15:21:15.601  7090  7090 D Weather.Utils: 2 : All the weather widget is gone.
07-26 15:21:15.601  7090  7090 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-26 15:21:15.602  6870  7275 V FormManager: Network unavailable.
07-26 15:21:15.603  7090  7090 D WeatherAncestor: connectivity changed - connection : true
07-26 15:21:15.604  7090  7090 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@158d2178
07-26 15:21:15.606  7090  7090 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-26 15:21:15.606  7090  7090 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-26 15:21:15.606  7090  7090 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-26 15:21:15.606  7090  7090 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-26 15:21:15.606  7090  7090 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:15
07-26 15:21:15.629  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-26 15:21:15.629  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-26 15:21:15.630  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-26 15:21:15.630  6764  6764 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-26 15:21:15.631  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-26 15:21:15.632  6764  6764 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-26 15:21:15.632  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-26 15:21:15.632  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-26 15:21:15.632  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-26 15:21:15.632  6764  6764 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-26 15:21:15.632  6764  6764 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-26 15:21:15.639  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:15.643  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:15.649  6870  7277 W FormManager: Network not available. Please check & try again.
07-26 15:21:15.649  6870  7278 V FormManager: Network unavailable.
07-26 15:21:15.651  6870  7278 V FormManager: Network unavailable.
,07-26 15:21:15.653  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:15.657   325  7280 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-26 15:21:15.657  1040  1120 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-26 15:21:15.659  1948  1948 D WfdsService: Supplicant Connection state is changed : false
07-26 15:21:15.659  1948  2270 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-26 15:21:15.659  1948  2270 D WfdsService: Set the WFDS Monitor: false
07-26 15:21:15.659  1948  2270 D WfdsMonitor: WFDS Monitor is stopped
07-26 15:21:15.660  1040  1415 D WifiOffDelayIfNotUsed: stopMonitoring
07-26 15:21:15.660  1040  1415 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-26 15:21:15.660  1040  1415 E WifiStateMachine: useWiFiOffloading() : false
07-26 15:21:15.660  1040  1415 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-26 15:21:15.661  1823  7145 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-26 15:21:15.663  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-26 15:21:15.663  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:15.664  2487  2487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:15.664  1040  1040 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-26 15:21:15.664  1040  1449 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-26 15:21:15.664  1040  1449 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,07-26 15:21:15.669  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:15.669  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:15.669  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:15.669  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:15.669  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:15.669  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:15.669  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:15.669  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:15.669  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:15.669  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:15.670  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:15.670  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:15.670  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:15.670  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:15.670  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:15.670  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:15.670  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:15.670  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:15.671  1823  7145 I CheckinService: active receiver: disabled
,07-26 15:21:15.690  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:15.692  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:15.696  6870  7282 W FormManager: Network not available. Please check & try again.
07-26 15:21:15.698  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-26 15:21:15.701  6870  7283 V FormManager: Network unavailable.
07-26 15:21:15.703  6870  7283 V FormManager: Network unavailable.
07-26 15:21:15.712  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-26 15:21:15.712  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-26 15:21:15.713  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-26 15:21:15.715  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:15.721  4331  7284 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-26 15:21:15.723  4331  7285 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-26 15:21:15.724  4331  7285 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-26 15:21:15.780  1040  2051 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7286 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-26 15:21:15.902  7286  7286 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-26 15:21:15.902  7286  7286 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-26 15:21:15.911  7286  7286 V [BNRBootReceiver]: Boot Receiver Return
,07-26 15:21:15.912  7286  7286 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-26 15:21:15.918  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:15.934  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:15.940  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:15.954  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:15.954  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:15.956  6830  6830 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-26 15:21:15.961  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-26 15:21:15.965  6764  6764 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-26 15:21:15.970  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:15.981  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:15.987  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:15.997  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-26 15:21:15.998  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.000  6830  6830 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-26 15:21:16.007  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:16.020  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.027  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.039  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:16.040  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:16.041  6830  6830 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-26 15:21:16.050  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:16.068  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.083  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.101  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-26 15:21:16.102  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:16.103  6830  6830 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-26 15:21:16.115  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:16.130  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.139  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.148  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-26 15:21:16.148  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:16.149  6830  6830 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-26 15:21:16.155  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:16.166  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.173  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-26 15:21:16.183  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:16.184  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:16.185  6830  6830 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-26 15:21:16.192  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:16.201  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.210  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.219  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:16.219  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:16.221  6830  6830 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-26 15:21:16.236  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:16.259  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.270  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.283  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-26 15:21:16.283  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:16.290  6830  6830 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-26 15:21:16.300  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:16.317  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.328  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.338  6691  6941 D UEI.SmartControl: Internal timer expired: 2
07-26 15:21:16.339  6691  6941 D UEI.SmartControl: unbind internal service
,07-26 15:21:16.341  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:16.342  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:16.344  6830  6830 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-26 15:21:16.354  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:16.363  6691  6935 D serial_port: close(fd = 24)
07-26 15:21:16.365  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-26 15:21:16.370  6691  6935 I UEI.SmartControl: Serial port is closed.
07-26 15:21:16.382  1040  1473 D WifiService: New client listening to asynchronous messages
07-26 15:21:16.384  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-26 15:21:16.392  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.402  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.416  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-26 15:21:16.417  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.419  6830  6830 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-26 15:21:16.421  6830  6830 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-26 15:21:16.422  6830  6830 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-26 15:21:16.434  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:16.442  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-26 15:21:16.445  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:16.454  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.480  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.494  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:16.494  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.495  6830  6830 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,07-26 15:21:16.496  6830  6830 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-26 15:21:16.496  6830  6830 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-26 15:21:16.501  1040  2051 I ActivityManager: Killing 6803:com.lge.lifetracker/u0a37 (adj 15): empty #17
07-26 15:21:16.532  1040  1983 W libprocessgroup: failed to open /acct/uid_10037/pid_6803/cgroup.procs: No such file or directory
,07-26 15:21:16.537  2218  2218 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-26 15:21:16.552  2218  2218 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-26 15:21:16.554  2218  2218 D c       : Getting all permits...
07-26 15:21:16.554  2218  2218 D a       : Opening database...
,07-26 15:21:16.558  2218  2218 D a       : Opening database auth.proximity.permit_store...
07-26 15:21:16.559  2218  2218 D a       : Closing database...
07-26 15:21:16.572  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:16.577  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,07-26 15:21:16.577  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-26 15:21:16.577  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:16.581  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.588  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.597  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:16.597  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.601  6830  6830 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-26 15:21:16.606  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:16.611  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-26 15:21:16.612  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-26 15:21:16.612  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-26 15:21:16.619  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.630  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.641  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:16.642  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.644  6830  6830 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-26 15:21:16.649  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:16.655  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-26 15:21:16.655  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false,
07-26 15:21:16.656  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-26 15:21:16.660  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.667  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.675  6830  6830 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:16.675  6830  6830 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.677  6830  6830 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-26 15:21:16.689  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-26 15:21:16.694  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:16.700  6870  7311 W FormManager: Network not available. Please check & try again.
,07-26 15:21:16.706  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.715  6870  7312 V FormManager: Network unavailable.
,07-26 15:21:16.726  6870  7312 V FormManager: Network unavailable.
07-26 15:21:16.730  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-26 15:21:16.730  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-26 15:21:16.733  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:16.736  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:16.749  6783  6783 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-26 15:21:16.749  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-26 15:21:16.749  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-26 15:21:16.752  4331  7313 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-26 15:21:16.756  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:16.757  4331  7314 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-26 15:21:16.757  4331  7314 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-26 15:21:16.768  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:16.768  6870  7316 W FormManager: Network not available. Please check & try again.
07-26 15:21:16.776  6870  7317 V FormManager: Network unavailable.
,07-26 15:21:16.784  6870  7317 V FormManager: Network unavailable.
07-26 15:21:16.794  2218  2218 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-26 15:21:17.197  1040  1415 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:660461965] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
,07-26 15:21:17.200  1040  1415 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:660461967] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-26 15:21:17.411  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:17.432  1040  1384 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7324 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-26 15:21:17.433  1040  1384 V AlarmManager: RTC_WAKEUP set : Alarm{18d4d549 type 0 when 1469539270092 com.android.vending} when 1469539270092
,07-26 15:21:17.440  1040  1122 D Tethering: MasterInitialState.processMessage what=3
07-26 15:21:17.444  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:17.444  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:17.449  1040  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:17.489  6830  6830 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
07-26 15:21:17.489  6830  6830 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8188
,07-26 15:21:17.510  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-26 15:21:17.539  6381  6420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-26 15:21:17.550  5253  5253 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-26 15:21:17.569  1040  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.595  2218  2218 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:17.604  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-26 15:21:17.604  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:17.604  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-26 15:21:17.604  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-26 15:21:17.606  6950  6950 I AppUp4:CustModeStarterReceiver: onReceive
07-26 15:21:17.609  6950  6950 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33edcfea
07-26 15:21:17.609  6950  6950 D AppUp4:CustFacade: isCustomizationCompleted : false
07-26 15:21:17.609  6950  6950 D AppUp4:CustFacade: isPhone : true
07-26 15:21:17.609  6950  6950 D AppUp4:CustModeStarterReceiver: begin check event
07-26 15:21:17.610  6950  6950 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-26 15:21:17.613  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:17.613  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-26 15:21:17.615  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:17.617  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:17.626  6990  6990 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-26 15:21:17.638  4331  7360 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-26 15:21:17.648  4331  7363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:17.648  4331  7363 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-26 15:21:17.653  3318  3318 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-26 15:21:17.653  3318  3318 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:17.653  3318  3318 I LgeMiscReceiver: networkInfo.isConnected() = true
07-26 15:21:17.653  3318  3318 D PhoneState: setPdpRejectCasuse : false
07-26 15:21:17.654  6990  7362 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:17.657  7029  7029 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-26 15:21:17.657  7029  7029 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-26 15:21:17.661  6870  7366 W FormManager: Network not available. Please check & try again.
07-26 15:21:17.662  6870  7367 V FormManager: Network unavailable.
07-26 15:21:17.669  7090  7090 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:17
07-26 15:21:17.671  7090  7090 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-26 15:21:17.671  7090  7090 D Weather.Utils: 2 : All the weather widget is gone.
,07-26 15:21:17.672  7090  7090 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-26 15:21:17.672  7090  7090 D WeatherAncestor: connectivity changed - connection : true
07-26 15:21:17.672  7090  7090 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@158d2178
07-26 15:21:17.672  6870  7367 V FormManager: Network unavailable.
07-26 15:21:17.673  7090  7090 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-26 15:21:17.673  7090  7090 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-26 15:21:17.673  7090  7090 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-26 15:21:17.673  7090  7090 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-26 15:21:17.673  7090  7090 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:17
07-26 15:21:17.703  7324  7324 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-26 15:21:17.798  7324  7324 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:17.798  7324  7324 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:17.869  7324  7324 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-26 15:21:17.890  7324  7324 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-26 15:21:17.891  7324  7324 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-26 15:21:17.907  7324  7324 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,07-26 15:21:17.908  7324  7324 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-26 15:21:17.945  3419  4500 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-26 15:21:17.946  3419  4500 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2efe4dee on behalf of 7324
,07-26 15:21:17.957  7324  7324 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-26 15:21:17.984  7324  7324 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-26 15:21:18.019  1040  2018 V SIM_STK : Menu title from STK is T-Mobile
,07-26 15:21:18.259  7324  7324 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-26 15:21:18.259  1040  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:18.260  1040  2018 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-26 15:21:18.266  1040  1875 I ActivityManager: Killing 6850:com.lge.settings.easy/1000 (adj 15): empty #17
,07-26 15:21:18.287  1040  1040 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-26 15:21:18.287  1040  1040 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-26 15:21:18.287  1040  1040 D Ulp_jni : JNI:system_update. Event-4
07-26 15:21:18.287  1040  1122 D BluetoothManagerService: Message: 1
07-26 15:21:18.288  1040  1122 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,07-26 15:21:18.338  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:18.357  1040  1786 W libprocessgroup: failed to open /acct/uid_1000/pid_6850/cgroup.procs: No such file or directory
,07-26 15:21:18.380  1040  1122 D Tethering: MasterInitialState.processMessage what=3
,07-26 15:21:18.385  1040  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.386  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.388  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:18.391  1040  1106 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.392  1040  1122 D Tethering: MasterInitialState.processMessage what=3
07-26 15:21:18.392  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:18.393  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-26 15:21:18.401  6381  6420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-26 15:21:18.405  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:18.406  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:18.413  5253  5253 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-26 15:21:18.415  1040  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:18.415  1040  1106 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:18.416  1040  1122 D BluetoothManagerService: Message: 20
07-26 15:21:18.417  1040  1122 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30ffb175:true
,07-26 15:21:18.419  6900  6900 D BluetoothAdapterState: make
07-26 15:21:18.421  5253  5253 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-26 15:21:18.424  6900  6900 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-26 15:21:18.425  6900  7393 I BluetoothAdapterState: Entering OffState
07-26 15:21:18.426  6900  6900 I bluedroid-qcom: init
07-26 15:21:18.427  6900  6900 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-26 15:21:18.428  6900  6900 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-26 15:21:18.428  6900  6900 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-26 15:21:18.428  6900  6900 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-26 15:21:18.428  6900  6900 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-26 15:21:18.428  6900  6900 I bluedroid-qcom: get_profile_interface socket
07-26 15:21:18.429  6900  7396 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-26 15:21:18.421  7397  7397 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:18.421  7397  7397 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:18.433  6900  6900 I bluedroid-qcom: get_profile_interface map_client
07-26 15:21:18.436  6900  7396 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-26 15:21:18.437  1040  1040 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-26 15:21:18.438  1040  1040 D BluetoothManagerService: Stored Bluetooth name: G3
07-26 15:21:18.438  2218  2218 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.439  7397  7397 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-26 15:21:18.439  7397  7397 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-26 15:21:18.439  7397  7397 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-26 15:21:18.440  6900  7396 D BluetoothAdapterProperties: Name is: G3
07-26 15:21:18.442  7397  7397 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,07-26 15:21:18.450  7397  7397 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-26 15:21:18.450  7397  7397 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-26 15:21:18.452  1040  1040 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-26 15:21:18.452  1040  1122 D BluetoothManagerService: Message: 40
07-26 15:21:18.452  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-26 15:21:18.453  6900  6917 I bluedroid-qcom: config_hci_snoop_log
07-26 15:21:18.455  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-26 15:21:18.455  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.455  1040  1122 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-26 15:21:18.455  1040  1122 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-26 15:21:18.457  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-26 15:21:18.457  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-26 15:21:18.459  6950  6950 I AppUp4:CustModeStarterReceiver: onReceive
07-26 15:21:18.461  6900  7393 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-26 15:21:18.462  6900  7393 D BluetoothAdapterProperties: Setting state to 11
07-26 15:21:18.462  6900  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-26 15:21:18.463  1040  1122 D BluetoothManagerService: Message: 60
07-26 15:21:18.463  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-26 15:21:18.463  1040  1122 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-26 15:21:18.463  6900  7393 I LGBluetoothServiceJni: classInitNative: succeeds
07-26 15:21:18.464  1948  1948 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:18.467  6764  6764 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-26 15:21:18.467  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:18.468  6950  6950 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33edcfea
07-26 15:21:18.468  6950  6950 D AppUp4:CustFacade: isCustomizationCompleted : false
07-26 15:21:18.468  6950  6950 D AppUp4:CustFacade: isPhone : true
07-26 15:21:18.469  1607  1607 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-26 15:21:18.469  6950  6950 D AppUp4:CustModeStarterReceiver: begin check event
07-26 15:21:18.469  6950  6950 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-26 15:21:18.470  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:18.475  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.475  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-26 15:21:18.477  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:18.479  6900  6900 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-26 15:21:18.479  6900  6900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:18.479  6900  6900 V BluetoothPbapReceiver: ***********state = 11
07-26 15:21:18.483  6900  7393 D BluetoothBondStateMachine: make
,07-26 15:21:18.484  2218  2218 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:18.486  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:18.487  6900  7393 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.487  6900  7393 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-26 15:21:18.487  6900  7393 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.487  6900  7393 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-26 15:21:18.488  6900  7393 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-26 15:21:18.488  6900  7402 I BluetoothBondStateMachine: StableState(): Entering Off State
07-26 15:21:18.493  6900  7393 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:18.537  1040  1786 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7404 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:18.544  6900  6900 D HeadsetService: Received start request. Starting profile...
07-26 15:21:18.545  6900  7393 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:18.545  6900  6900 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-26 15:21:18.545  6900  6900 D LGBluetoothHfpAdapter: Version 1.6
07-26 15:21:18.548  6900  6900 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-26 15:21:18.550  6900  6900 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-26 15:21:18.550  6900  7393 E BluetoothAdapterService: File transfer profiles supported!!
,07-26 15:21:18.550  6900  6900 D HeadsetStateMachine: make
07-26 15:21:18.557  6900  7393 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:18.563  6900  7393 E BluetoothAdapterService: File transfer profiles supported!!
,07-26 15:21:18.563  6990  6990 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-26 15:21:18.567  4331  7422 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-26 15:21:18.573  6900  7393 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:18.575  4331  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.576  4331  7423 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-26 15:21:18.582  6900  7393 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:18.590  6990  7424 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:18.592  6900  6900 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:18.592  6900  6900 D LgDataFeature: LgDataFeature() Constructor Done, null
07-26 15:21:18.597  3318  3318 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-26 15:21:18.597  3318  3318 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.597  3318  3318 I LgeMiscReceiver: networkInfo.isConnected() = false
07-26 15:21:18.597  6900  6900 D HeadsetStateMachine: max_hf_connections = 1
07-26 15:21:18.597  6900  6900 I bluedroid-qcom: get_profile_interface handsfree
07-26 15:21:18.599  7029  7029 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-26 15:21:18.599  7029  7029 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-26 15:21:18.600  6900  6900 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-26 15:21:18.601  6900  7393 V LGMDMManager: Create singleton instance
,07-26 15:21:18.602   329  1403 V AudioPolicyService: registerClient() client 0xb558a860, uid 1002
07-26 15:21:18.603   329  1402 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-26 15:21:18.603   329  1402 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-26 15:21:18.603   329  1402 V AudioPolicyManagerEx: getOutput() returns output 2
07-26 15:21:18.603  6900  6900 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,07-26 15:21:18.605   329  2189 V AudioFlinger: registerClient() client 0xb55815f8, pid 6900
07-26 15:21:18.608  6900  6900 V ToneGenerator: Create Track: 0xb4928a80
07-26 15:21:18.608  6900  6900 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-26 15:21:18.608  6900  6900 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-26 15:21:18.608   329  1397 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:18.608   329   329 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-26 15:21:18.608   329  1397 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:18.608   329   329 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-26 15:21:18.608   329   329 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-26 15:21:18.608   329   329 V AudioPolicyManagerEx: getOutput() returns output 2
07-26 15:21:18.608  6900  6900 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-26 15:21:18.609   329  2189 I AudioFlinger: isAudioPlaybackHookOn() false
07-26 15:21:18.609   329  2188 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-26 15:21:18.609   329  2188 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-26 15:21:18.609   329  2188 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-26 15:21:18.609   329  2188 V AudioPolicyManagerEx: getOutput() returns output 2
07-26 15:21:18.611  1607  2087 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:18.611  1607  2087 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:18.611  3318  3334 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:18.611  3318  3334 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:18.611  6900  6918 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:18.611  6900  6918 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-26 15:21:18.611  1858  1873 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:18.611  1858  1873 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:18.611   329  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:18.611   329  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:18.611  1040  1921 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:18.611  1040  1921 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:18.611  1040  1921 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:18.611  1040  1921 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:18.611  6900  6900 V AudioSystem: getLatency() output 2, latency 50
07-26 15:21:18.611  6900  6900 V AudioSystem: getFrameCount() output 2, frameCount 960
07-26 15:21:18.611  6900  6900 V AudioTrack: createTrack_l() output 2 afLatency 50
07-26 15:21:18.612   329   329 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
,07-26 15:21:18.612   329   329 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-26 15:21:18.612   329   329 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-26 15:21:18.612   329   329 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-26 15:21:18.612   329   329 V AudioFlinger: createTrack() lSessionId: 20
07-26 15:21:18.615  1858  1874 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:18.615  1858  1874 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:18.615  3318  3333 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:18.615  3318  3333 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:18.616  6900  7393 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-26 15:21:18.616  1607  1628 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:18.616  1607  1628 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:18.616  6900  6917 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:18.616  6900  6917 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-26 15:21:18.617  6900  6900 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-26 15:21:18.618   329   329 V AudioFlinger: acquiring 20 from 6900, for 6900
07-26 15:21:18.618   329   329 V AudioFlinger:  added new entry for 20
07-26 15:21:18.618  6900  6900 V ToneGenerator: ToneGenerator INIT OK, time: 156203
07-26 15:21:18.618  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.619  6900  7420 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-26 15:21:18.619  6900  7420 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-26 15:21:18.619  6900  7420 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-26 15:21:18.619  6900  7420 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-26 15:21:18.620   329  1402 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6900
07-26 15:21:18.620   329  1402 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-26 15:21:18.620   329  1402 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-26 15:21:18.620   329  1402 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-26 15:21:18.620   329  1402 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-26 15:21:18.620   329  1402 V voice   : voice_set_parameters: exit with code(0)
07-26 15:21:18.620   329  1402 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-26 15:21:18.620   329  1402 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-26 15:21:18.620   329  1402 V msm8974_platform: platform_set_parameters: exit with code(0)
07-26 15:21:18.620   329  1402 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-26 15:21:18.620   329  1402 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-26 15:21:18.620   329  1402 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-26 15:21:18.621  7090  7090 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:18
07-26 15:21:18.621  6900  7420 V ToneGenerator: ToneGenerator destructor
07-26 15:21:18.621  6900  7420 V ToneGenerator: stopTone
07-26 15:21:18.621  6900  7420 V ToneGenerator: Delete Track: 0xb4928a80
07-26 15:21:18.621  6900  7420 V AudioTrack: ~AudioTrack, releasing session id from 6900 on behalf of 6900
07-26 15:21:18.621   329   329 V AudioFlinger: releasing 20 from 6900 for 6900
07-26 15:21:18.621   329   329 V AudioFlinger:  decremented refcount to 0
07-26 15:21:18.621   329  , 329 V AudioFlinger: purging stale effects
07-26 15:21:18.621  1040  1580 W Process : Unable to open /proc/7429/status
07-26 15:21:18.621   329   329 V AudioPolicyService: AudioCommandThread() adding release output 2
07-26 15:21:18.621   329   329 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-26 15:21:18.621   329   329 V AudioFlinger: PlaybackThread::Track destructor
07-26 15:21:18.621   329  1270 V AudioPolicyService: AudioCommandThread() waking up
07-26 15:21:18.621   329   329 V AudioFlinger: removeClient_l() pid 6900, calling pid 329
07-26 15:21:18.621   329  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
07-26 15:21:18.621   329  1270 V AudioPolicyManager: releaseOutput() 2
07-26 15:21:18.621   329  1270 V AudioPolicyService: AudioCommandThread() going to sleep
07-26 15:21:18.622  7090  7090 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-26 15:21:18.622  7090  7090 D Weather.Utils: 2 : All the weather widget is gone.
07-26 15:21:18.622  7090  7090 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-26 15:21:18.623  7090  7090 D WeatherAncestor: connectivity changed - connection : true
07-26 15:21:18.623  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.623  7090  7090 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@158d2178
07-26 15:21:18.624  7090  7090 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-26 15:21:18.624  7090  7090 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-26 15:21:18.624  7090  7090 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-26 15:21:18.624  7090  7090 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-26 15:21:18.624  7090  7090 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:18
07-26 15:21:18.625  6900  6900 D A2dpService: Received start request. Starting profile...
07-26 15:21:18.625  6900  6900 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-26 15:21:18.626  6900  6900 V Avrcp   : make
07-26 15:21:18.627  6900  6900 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-26 15:21:18.627  6900  6900 I bluedroid-qcom: get_profile_interface avrcp
07-26 15:21:18.626  6870  7427 W FormManager: Network not available. Please check & try again.
07-26 15:21:18.635  6900  6900 V AudioManager: registerRemoteController: size of Media player list: 0
07-26 15:21:18.637  6900  6900 E AudioManager: No RCC entry present to update
07-26 15:21:18.637  6900  6900 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-26 15:21:18.637  6870  7428 V FormManager: Network unavailable.
07-26 15:21:18.639  6870  7428 V FormManager: Network unavailable.
07-26 15:21:18.640  6900  6900 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-26 15:21:18.641  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-26 15:21:18.641  6900  6900 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-26 15:21:18.644  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,07-26 15:21:18.703  7404  7404 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-26 15:21:18.704  7404  7404 W LG Account v2.2: No ProfileInfo entries
07-26 15:21:18.704  7404  7404 I LG Account v2.2: isEnabled: false
07-26 15:21:18.704  6381  6381 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-26 15:21:18.707  6381  6420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-26 15:21:18.709  7404  7404 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-26 15:21:18.709  7404  7404 I Feature : [Lifetracker]Country: EU
07-26 15:21:18.709  7404  7404 I Feature : [Lifetracker]Operator: OPEN
07-26 15:21:18.710  7404  7404 I Feature : [Lifetracker]Ranking support: false
07-26 15:21:18.710  7404  7404 I Feature : [Lifetracker]Comfort support: false
07-26 15:21:18.710  7404  7404 I Feature : [Lifetracker]Accessory: true
07-26 15:21:18.710  7404  7404 I Feature : [Lifetracker]Health device: true
07-26 15:21:18.710  7404  7404 I Feature : [Lifetracker]Extra Pedometer: false
07-26 15:21:18.710  7404  7404 I Feature : [Lifetracker]Blood glucose device: false
07-26 15:21:18.710  7404  7404 I Feature : [Lifetracker]Device Number: 3
07-26 15:21:18.733  6764  6764 D BluetoothPermissionRequest: onReceive
,07-26 15:21:18.738  6764  6764 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-26 15:21:18.744  1040  1875 V SIM_STK : Menu title from STK is T-Mobile
07-26 15:21:18.744  1040  1875 V SIM_STK : Menu title from STK is T-Mobile
07-26 15:21:18.746  2218  2218 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:18.762  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,07-26 15:21:18.762  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.762  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-26 15:21:18.763  6950  6950 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-26 15:21:18.765  6950  6950 I AppUp4:CustModeStarterReceiver: onReceive
07-26 15:21:18.768  6950  6950 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33edcfea
07-26 15:21:18.768  6950  6950 D AppUp4:CustFacade: isCustomizationCompleted : false
07-26 15:21:18.768  6950  6950 D AppUp4:CustFacade: isPhone : true
07-26 15:21:18.769  6950  6950 D AppUp4:CustModeStarterReceiver: begin check event
07-26 15:21:18.769  6950  6950 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-26 15:21:18.772  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.772  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-26 15:21:18.774  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-26 15:21:18.777  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:18.785  6990  6990 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-26 15:21:18.786  4331  7434 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-26 15:21:18.791  4331  7435 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.791  4331  7435 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-26 15:21:18.800  1040  1875 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-26 15:21:18.804  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-26 15:21:18.806  6990  7436 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:18.807  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-26 15:21:18.808  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-26 15:21:18.808  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-26 15:21:18.808  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-26 15:21:18.808  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-26 15:21:18.808  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-26 15:21:18.808  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-26 15:21:18.808  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-26 15:21:18.808  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-26 15:21:18.808  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-26 15:21:18.808  6900  6900 I BluetoothA2dpServiceJni: classInitNative
07-26 15:21:18.808  6900  6900 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:21:18.808  6900  6900 D A2dpStateMachine: make
07-26 15:21:18.810  6900  6900 I bluedroid-qcom: get_profile_interface a2dp
07-26 15:21:18.810  6900  7442 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,07-26 15:21:18.816  3318  3318 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-26 15:21:18.816  3318  3318 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:18.816  3318  3318 I LgeMiscReceiver: networkInfo.isConnected() = false
07-26 15:21:18.816  6900  6900 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:21:18.816  6900  6900 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-26 15:21:18.816  6870  7438 W FormManager: Network not available. Please check & try again.
07-26 15:21:18.818  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.818  6900  7440 D A2dpStateMachine: Enter Disconnected: -2
07-26 15:21:18.819  6900  6900 I BluetoothHidServiceJni: classInitNative: succeeds
07-26 15:21:18.821  6900  6900 D HidService: Received start request. Starting profile...
07-26 15:21:18.821  6900  6900 I bluedroid-qcom: get_profile_interface hidhost
07-26 15:21:18.821  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.821  7029  7029 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-26 15:21:18.821  7029  7029 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-26 15:21:18.821  6900  6900 I BluetoothHealthServiceJni: classInitNative: succeeds
07-26 15:21:18.823  6900  6900 D HealthService: Received start request. Starting profile...
07-26 15:21:18.825  6900  6900 I bluedroid-qcom: get_profile_interface health
07-26 15:21:18.825  6870  7439 V FormManager: Network unavailable.
,07-26 15:21:18.825  6900  6900 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-26 15:21:18.825  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.826  6900  6900 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-26 15:21:18.827  6900  6900 D PanService: Received start request. Starting profile...
07-26 15:21:18.827  6900  6900 D BluetoothPanServiceJni: initializeNative(L110): pan
07-26 15:21:18.827  6900  6900 I bluedroid-qcom: get_profile_interface pan
07-26 15:21:18.833  6870  7439 V FormManager: Network unavailable.
07-26 15:21:18.834  6900  6900 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-26 15:21:18.835  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.835  6900  6900 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-26 15:21:18.839  6900  6900 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:21:18.839  6900  6900 D BtGatt.GattService: Received start request. Starting profile...
07-26 15:21:18.839  6900  6900 D BtGatt.GattService: start()
07-26 15:21:18.839  6900  6900 I bluedroid-qcom: get_profile_interface gatt
07-26 15:21:18.839  6900  6900 D BtGatt.AdvertiseManager: advertise manager created
,07-26 15:21:18.843  7090  7090 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:18
07-26 15:21:18.844  7090  7090 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-26 15:21:18.844  7090  7090 D Weather.Utils: 2 : All the weather widget is gone.
07-26 15:21:18.844  7090  7090 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-26 15:21:18.844  7090  7090 D WeatherAncestor: connectivity changed - connection : true
07-26 15:21:18.844  7090  7090 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@158d2178
07-26 15:21:18.845  7090  7090 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-26 15:21:18.845  7090  7090 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-26 15:21:18.845  7090  7090 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-26 15:21:18.845  7090  7090 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-26 15:21:18.845  7090  7090 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:18
07-26 15:21:18.851  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
,07-26 15:21:18.852  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.852  6900  6900 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-26 15:21:18.854  6900  6900 V BluetoothMapService: BluetoothMapBinder()
07-26 15:21:18.855  6900  6900 D BluetoothMapService: Received start request. Starting profile...
07-26 15:21:18.855  6900  6900 D BluetoothMapService: start()
07-26 15:21:18.862  6900  6900 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-26 15:21:18.862  6900  6900 D BluetoothMapEmailAppObserver: createReceiver()
,07-26 15:21:18.863  6900  6900 D BluetoothMapEmailAppObserver: initObservers()
,07-26 15:21:18.863  6900  6900 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-26 15:21:18.874  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:18.875  6900  6900 D HeadsetStateMachine: Proxy object connected
07-26 15:21:18.875  6900  6900 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-26 15:21:18.876  6900  6900 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,07-26 15:21:18.880  6900  6900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-26 15:21:18.882  6900  7420 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-26 15:21:18.882  6900  7420 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-26 15:21:18.882  6900  7420 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-26 15:21:18.886  6900  6900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-26 15:21:18.889  6900  6900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-26 15:21:18.896  6900  6900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-26 15:21:18.899  6900  6900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-26 15:21:18.900  6900  6900 V PanService: [BTUI] SIM Extra State :ABSENT
07-26 15:21:18.903  6900  6900 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-26 15:21:18.903  6900  6900 V BluetoothMapService: Handler(): got msg=1
07-26 15:21:18.903  6900  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-26 15:21:18.904  6900  7393 I bluedroid-qcom: enable
07-26 15:21:18.904  6900  7449 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-26 15:21:18.904  6900  7449 I bt-btu  : btu_task pending for preload complete event
,07-26 15:21:18.905  6900  7393 I bt_hci_bdroid: init
07-26 15:21:18.906  6900  7393 I bt_vendor: bt-vendor : init
07-26 15:21:18.906  6900  7393 I bt_vendor: bt-vendor : get_bt_soc_type
07-26 15:21:18.906  6900  7393 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-26 15:21:18.906  6900  7393 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-26 15:21:18.906  6900  7393 D bt_userial_mct: userial_init
07-26 15:21:18.906  6900  6900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:18.908  6900  7393 D bt_hci_bdroid: set_power 1
07-26 15:21:18.908  6900  7393 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-26 15:21:18.908  6900  7393 I bt_vendor: Starting hciattach daemon
07-26 15:21:18.908  6900  7393 I bt_vendor: try to set true
07-26 15:21:18.911  6900  6900 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-26 15:21:18.911  6900  6900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-26 15:21:18.911  6900  6900 V BluetoothSapReceiver: SapReceiver onReceive 
07-26 15:21:18.911  6900  6900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:18.911  6900  6900 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-26 15:21:18.901  7452  7452 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:18.901  7452  7452 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:18.935  7453  7453 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-26 15:21:18.961  1040  1921 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7456 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-26 15:21:19.022  7477  7477 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-26 15:21:19.032  7456  7456 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-26 15:21:19.036  7478  7478 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-26 15:21:19.051  1040  1921 I ActivityManager: Killing 7286:com.lge.bnr/1000 (adj 15): empty #17
,07-26 15:21:19.068  7480  7480 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,07-26 15:21:19.079  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-26 15:21:19.093  7482  7482 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-26 15:21:19.109  7483  7483 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-26 15:21:19.135  7485  7485 I libmdmdetect: ESOC framework not supported
07-26 15:21:19.136  1040  1946 W libprocessgroup: failed to open /acct/uid_1000/pid_7286/cgroup.procs: No such file or directory
07-26 15:21:19.137  7485  7485 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-26 15:21:19.145  7485  7485 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,07-26 15:21:19.145  7485  7485 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-26 15:21:19.145  7485  7485 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-26 15:21:19.145  7485  7485 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-26 15:21:19.145  7485  7485 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-26 15:21:19.145  7485  7485 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-26 15:21:19.145  7485  7485 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-26 15:21:19.184  7485  7486 E QC-QMI  : qmi_client [7485] 14: failed to locate client data
07-26 15:21:19.184   464   464 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-26 15:21:19.185   464   464 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,07-26 15:21:19.228  7487  7487 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-26 15:21:19.243  7488  7488 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-26 15:21:19.260  6900  7393 I bt_vendor: bluetooth satus is on
07-26 15:21:19.260  6900  7393 D bt_hci_bdroid: preload
07-26 15:21:19.260  6900  7451 D bt_userial_mct: userial_open(port:0)
07-26 15:21:19.260  6900  7451 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-26 15:21:19.267  6900  7451 I bt_vendor: Done intiailizing UART
07-26 15:21:19.270  6900  7451 I bt_vendor: Done intiailizing UART
07-26 15:21:19.270  6900  7451 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-26 15:21:19.271  6900  7451 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-26 15:21:19.271  6900  7490 D bt_userial_mct: Entering userial_read_thread()
07-26 15:21:19.271  6900  7449 I bt-btu  : btu_task received preload complete event
07-26 15:21:19.272  6900  7449 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-26 15:21:19.273  6900  7449 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-26 15:21:19.276  6900  7449 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_HCI
,07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_AVDT
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_AVRC
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_A2D
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_BNEP
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_BTM
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_GAP
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_PAN
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_SDP
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_GATT
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_SMP
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-26 15:21:19.281  6900  7449 I         : BTE_InitTraceLevels -- TRC_BTIF
07-26 15:21:19.339  6900  7449 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-26 15:21:19.339  6900  7449 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0167061 
07-26 15:21:19.339  6900  7449 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0167061 
,07-26 15:21:19.356  6900  7396 E bt-btif : Calling BTA_HhEnable,
07-26 15:21:19.356  6900  7396 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-26 15:21:19.357  6900  7396 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-26 15:21:19.358  6900  7449 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-26 15:21:19.358  6900  7449 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-26 15:21:19.358  6900  7449 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-26 15:21:19.358  6900  7449 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-26 15:21:19.358  6900  7449 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-26 15:21:19.359  1040  1040 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-26 15:21:19.360  6900  7396 D BluetoothAdapterProperties: Name is: G3
07-26 15:21:19.361  6900  7396 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:21:19.361  6900  7396 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:19.362  6900  7396 D bt_hci_bdroid: postload
07-26 15:21:19.363  6900  7451 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:19.360  1040  1040 D BluetoothManagerService: Stored Bluetooth name: G3
07-26 15:21:19.363  6900  7449 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-26 15:21:19.364  6900  7396 D bte_conf: Device ID record 1 : primary
07-26 15:21:19.364  6900  7396 D bte_conf:   vendorId            = 00c4
07-26 15:21:19.364  6900  7396 D bte_conf:   vendorIdSource      = 0001
,07-26 15:21:19.364  6900  7396 D bte_conf:   product             = 13a1
07-26 15:21:19.364  6900  7396 D bte_conf:   version             = 1000
07-26 15:21:19.364  6900  7396 D bte_conf:   clientExecutableURL = 
07-26 15:21:19.364  6900  7396 D bte_conf:   serviceDescription  = 
07-26 15:21:19.364  6900  7396 D bte_conf:   documentationURL    = 
07-26 15:21:19.364  6900  7396 D bte_conf: bte_load_did_conf no section named DID2.
07-26 15:21:19.364  6900  7451 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:19.364  6900  7451 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:19.368  6900  7451 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:19.368  6900  7451 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:19.369  6900  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-26 15:21:19.369  6900  7393 D BluetoothAdapterProperties: ScanMode =  20
07-26 15:21:19.369  6900  7393 D BluetoothAdapterProperties: State =  11
07-26 15:21:19.369  6900  7393 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-26 15:21:19.370  6900  7393 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-26 15:21:19.370  6900  7393 D BluetoothAdapterProperties: Setting state to 12
07-26 15:21:19.370  6900  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-26 15:21:19.370  6900  7396 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-26 15:21:19.371  6900  7396 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-26 15:21:19.372  6900  7451 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:19.373  6900  7490 E bt_mct  : hci lib postload completed
07-26 15:21:19.361  7495  7495 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:19.361  7495  7495 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:19.375  1040  1122 D BluetoothManagerService: Message: 60
07-26 15:21:19.375  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,07-26 15:21:19.375  1040  1122 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-26 15:21:19.379  6900  7393 I BluetoothAdapterState: Entering On State
07-26 15:21:19.381  6900  7449 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:19.381  6900  7449 W bt-smp  : Plain text(LSB ~ MSB) = e5 00 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:19.381  6900  7449 W bt-smp  : Encrypted text(LSB ~ MSB) = 2f 2f 25 62 b3 93 3c b8 83 ea db 95 b9 d3 17 99 
07-26 15:21:19.381  6900  7449 W bt-btm  : Stopping oneshot timer
07-26 15:21:19.382  6900  7393 D LGBluetoothServiceAdapter: [BTUI] OnState
07-26 15:21:19.382  6900  7393 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-26 15:21:19.382  6900  7393 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-26 15:21:19.383  6900  7393 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-26 15:21:19.383  6764  6892 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:21:19.383  6764  6892 D BluetoothPan: onBluetoothStateChange call bindService
,07-26 15:21:19.389  1040  1122 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:21:19.403  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:19.403  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:19.403  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:19.403  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:19.403  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:19.403  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:19.403  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:19.403  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:19.403  1040  1040 D BluetoothA2dp: Proxy object connected
07-26 15:21:19.404  1858  1874 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:19.406  6764  6764 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:19.406  6764  6764 D PanProfile: Bluetooth service connected
07-26 15:21:19.408  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:19.411  6900  7449 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:19.411  6900  7449 W bt-smp  : Plain text(LSB ~ MSB) = 15 6b 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:19.411  6900  7449 W bt-smp  : Encrypted text(LSB ~ MSB) = df 06 ba bd 50 53 e1 26 da 9b ff ad 72 13 74 63 
07-26 15:21:19.411  6900  7449 W bt-btm  : Stopping oneshot timer
07-26 15:21:19.414   325  7136 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-26 15:21:19.414   325  7136 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
07-26 15:21:19.414   325  7136 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
07-26 15:21:19.416  1040  7107 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-26 15:21:19.416  1858  1873 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-26 15:21:19.416  1040  7107 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s78ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:19.416  1040  7107 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s78ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:19.416  1040  7107 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-26 15:21:19.416  1858  1858 D BluetoothHeadset: Proxy object connected
,07-26 15:21:19.417  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:19.417  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:19.417  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:19.417  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:19.417  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:19.417  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,07-26 15:21:19.417  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:19.417  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:19.421  1040  1120 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-26 15:21:19.421  1858  1858 D BluetoothHeadset: Proxy object connected
07-26 15:21:19.422  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:19.422  1858  1874 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:19.425  1858  1858 D BluetoothHeadset: Proxy object connected
07-26 15:21:19.425  1040  1122 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:19.426  1040  1040 D BluetoothHeadset: Proxy object connected
07-26 15:21:19.426  6764  6782 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:21:19.426  6900  7449 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:19.426  6900  7449 W bt-smp  : Plain text(LSB ~ MSB) = b4 80 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:19.426  6900  7449 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e 6b 55 51 03 5b 6d d8 ce a6 18 15 f6 f7 50 97 
07-26 15:21:19.426  6900  7449 W bt-btm  : Stopping oneshot timer
07-26 15:21:19.428  6900  7393 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-26 15:21:19.431  6764  6892 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-26 15:21:19.435  6764  6892 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:21:19.436  6900  7449 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:19.436  6900  7449 W bt-smp  : Plain text(LSB ~ MSB) = f7 bb 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:19.436  6900  7449 W bt-smp  : Encrypted text(LSB ~ MSB) = d0 8e a8 1d 54 1d 1a 03 d1 14 70 30 56 f9 3b 61 
07-26 15:21:19.436  6900  7449 W bt-btm  : Stopping oneshot timer
07-26 15:21:19.437  6764  6764 D BluetoothInputDevice: Proxy object connected
07-26 15:21:19.437  6764  6764 D HidProfile: Bluetooth service connected
07-26 15:21:19.441  6764  6764 D BluetoothMap: Proxy object connected
07-26 15:21:19.441  6764  6764 D MapProfile: Bluetooth service connected
07-26 15:21:19.441  1040  1040 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-26 15:21:19.441  6764  6764 D BluetoothMap: getConnectedDevices()
07-26 15:21:19.441  1040  1122 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-26 15:21:19.441  1040  1122 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-26 15:21:19.445  6900  6917 V BluetoothMapService: getConnectedDevices()
07-26 15:21:19.452  6900  7396 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:19.452  6900  7396 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-26 15:21:19.454  6900  7449 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:19.454  6900  7449 W bt-smp  : Plain text(LSB ~ MSB) = cf 92 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:19.454  6900  7449 W bt-smp  : Encrypted text(LSB ~ MSB) = 2f 7a 20 d8 04 cf b7 72 5b 34 66 4a f1 89 15 ee 
07-26 15:21:19.454  6900  7449 W bt-btm  : Stopping oneshot timer
,07-26 15:21:19.456  1948  1948 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.456  1948  2109 D LGBluetoothAPIService: Message: 1
07-26 15:21:19.456  1948  2109 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-26 15:21:19.457  1607  1607 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-26 15:21:19.460  6900  6900 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.460  6900  6900 D BluetoothMapService: STATE_ON
07-26 15:21:19.463  7506  7506 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-26 15:21:19.464  1948  2109 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-26 15:21:19.466  1040  1122 D BluetoothManagerService: Message: 40
07-26 15:21:19.466  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,07-26 15:21:19.467  6570  6570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:21:19.468  6764  6764 D LocalBluetoothProfileManager: Adding local A2DP profile
07-26 15:21:19.469  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:19.470  1040  1122 D BluetoothManagerService: Message: 30
07-26 15:21:19.470  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:19.472  6764  6764 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-26 15:21:19.475  1040  1122 D BluetoothManagerService: Message: 30
07-26 15:21:19.478  6764  6764 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-26 15:21:19.478  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:19.478  6900  6900 V BluetoothPbapService: Pbap Service onCreate
,07-26 15:21:19.479  6900  6900 V BluetoothPbapService: Starting PBAP service
07-26 15:21:19.479  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-26 15:21:19.480  6900  6900 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-26 15:21:19.480  6900  6900 V BluetoothPbapService: Pbap Service onBind
07-26 15:21:19.483  6764  6764 D BluetoothA2dp: Proxy object connected
07-26 15:21:19.483  6900  6900 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.483  6900  6900 V BluetoothPbapService: state: 12
07-26 15:21:19.483  6900  6900 V BluetoothMapService: Handler(): got msg=1
07-26 15:21:19.484  6764  6764 D A2dpProfile: Bluetooth service connected
07-26 15:21:19.484  6900  6900 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-26 15:21:19.485  6764  6764 D BluetoothHeadset: Proxy object connected
07-26 15:21:19.486  6900  7508 D BluetoothMapMasInstance: MAS initSocket()
07-26 15:21:19.486  6764  6764 D HeadsetProfile: Bluetooth service connected
07-26 15:21:19.486  6900  6900 D LGBluetoothAPIServer: [BTUI] onCreate()
07-26 15:21:19.486  6900  6900 D LGBluetoothAPIServer: [BTUI] onBind()
07-26 15:21:19.487  6900  7508 D BluetoothMapMasInstance:   masId = 00
07-26 15:21:19.487  6900  7508 D BluetoothMapMasInstance:   msgTypes = 0e
07-26 15:21:19.487  6900  7508 D BluetoothMapMasInstance:   masName = SMS/MMS
07-26 15:21:19.487  6900  7508 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-26 15:21:19.487  6900  6900 V BluetoothPbapService: Handler(): got msg=1
07-26 15:21:19.487  6900  6900 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-26 15:21:19.487  1948  1948 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-26 15:21:19.487  1948  2109 D LGBluetoothAPIService: Message: 100
07-26 15:21:19.487  1948  2109 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-26 15:21:19.488  6900  6900 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-26 15:21:19.488  6900  6900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.488  6900  6900 V BluetoothPbapReceiver: ***********state = 12
07-26 15:21:19.488  6900  7509 V BluetoothPbapService: Pbap Service initSocket
07-26 15:21:19.489  1040  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:19.489  1040  1055 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:19.490  6900  7509 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:19.490  6900  7508 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:19.490  2218  2218 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:19.493  2218  2218 D c       : Getting all permits...
07-26 15:21:19.493  2218  2218 D a       : Opening database...
07-26 15:21:19.494  6900  7508 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-26 15:21:19.494  6900  7509 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-26 15:21:19.494  6900  7508 V BluetoothMapMasInstance: Succeed to create listening socket 
07-26 15:21:19.494  6900  7509 V BluetoothPbapService: Succeed to create listening socket 
07-26 15:21:19.494  6900  7508 D BluetoothMapMasInstance: Accepting socket connection...
07-26 15:21:19.494  6900  7509 V BluetoothPbapService: Accepting socket connection...
07-26 15:21:19.494  6900  7396 D BluetoothAdapterProperties: Scan Mode:21
07-26 15:21:19.495  6900  7396 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-26 15:21:19.496  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:19.498  2218  2218 D a       : Opening database auth.proximity.permit_store...
07-26 15:21:19.499  2218  2218 D a       : Closing database...
07-26 15:21:19.499  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:19.499  6764  6764 D DockEventReceiver: finishStartingService: stopping service
07-26 15:21:19.500  6764  6764 D BluetoothPbap: Proxy object connected
07-26 15:21:19.500  6764  6764 D PbapServerProfile: Bluetooth service connected
07-26 15:21:19.508  7116  7153 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-26 15:21:19.510  6764  6764 D BluetoothPermissionRequest: onReceive
07-26 15:21:19.512  6764  6764 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-26 15:21:19.513  6764  6764 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-26 15:21:19.515  6900  6900 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-26 15:21:19.516  6900  6900 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-26 15:21:19.521  6900  6900 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-26 15:21:19.539  6900  6900 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-26 15:21:19.540  6900  6900 V BtOppService: onCreate
,07-26 15:21:19.544  6900  6900 V BluetoothOppNotification: send message
,07-26 15:21:19.548  6900  6900 V BtOppService: Starting RfcommListener
07-26 15:21:19.553  6900  6900 D BluetoothOppPreference: Dumping Names:  
07-26 15:21:19.553  6900  6900 D BluetoothOppPreference: {}
07-26 15:21:19.553  6900  6900 D BluetoothOppPreference: Dumping Channels:  
07-26 15:21:19.553  6900  6900 D BluetoothOppPreference: {}
07-26 15:21:19.554  6900  6900 V BtOppService: onStartCommand
,07-26 15:21:19.560  6900  7519 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-26 15:21:19.560  6900  6900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.561  6900  6900 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-26 15:21:19.563  6900  7516 V BtOppService: Deleted complete outbound shares, number =  0
07-26 15:21:19.567  6900  7519 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-26 15:21:19.567  6900  6900 V BluetoothOppNotification: new notify threadi!
,07-26 15:21:19.568  6900  7516 V BtOppService: Deleted complete inbound failed shares, number = 0
07-26 15:21:19.568  6900  6900 V BluetoothOppNotification: send delay message
07-26 15:21:19.568  6900  7516 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,07-26 15:21:19.569  6900  6900 V BtOppService: start RfcommListener
07-26 15:21:19.570  6900  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-26 15:21:19.572  6900  7516 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a8937dd on behalf of 
07-26 15:21:19.572  6900  7519 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d604f52 on behalf of 
07-26 15:21:19.573  6900  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3598f223 on behalf of 
07-26 15:21:19.575  6900  7520 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-26 15:21:19.576  6900  7519 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-26 15:21:19.577  6900  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-26 15:21:19.578  6900  6900 V BtOppService: RfcommListener started
07-26 15:21:19.578  6900  6900 V BtOppService: ContentObserver received notification
07-26 15:21:19.579  6900  7521 V BtOppRfcommListener: Starting RFCOMM listener....
07-26 15:21:19.580  1040  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:19.580  6900  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15f7f320 on behalf of 
07-26 15:21:19.581  6900  7521 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:19.582  6900  7520 V BluetoothOppNotification: outbound: succ-0  fail-0
07-26 15:21:19.584  6900  7522 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-26 15:21:19.584  6900  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-26 15:21:19.585  6900  7521 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
07-26 15:21:19.586  6900  7521 V BtOppRfcommListener: Started RFCOMM listener....
07-26 15:21:19.586  6900  7521 I BtOppRfcommListener: Accept thread started.
07-26 15:21:19.586  6900  7521 V BtOppRfcommListener: Accepting connection...
07-26 15:21:19.609  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
,07-26 15:21:19.609  6900  6900 V BluetoothFtpService: Ftp Service onCreate
07-26 15:21:19.609  6900  6900 I BluetoothFtpService: Ftp Service onCreate
07-26 15:21:19.610  6900  6900 V BluetoothFtpService: Ftp Service onStartCommand
07-26 15:21:19.610  6900  6900 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.610  6900  6900 V BluetoothFtpService: Starting Listening on sockets
07-26 15:21:19.610  6900  6900 V BtOppService: ContentObserver received notification
07-26 15:21:19.610  6900  6900 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-26 15:21:19.610  6900  6900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-26 15:21:19.610  6900  6900 V BluetoothSapReceiver: SapReceiver onReceive 
07-26 15:21:19.610  6900  6900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.611  6900  6900 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-26 15:21:19.611  6900  6900 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-26 15:21:19.613  6900  6900 V BluetoothFtpService: Handler(): got msg=1
07-26 15:21:19.613  6900  6900 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-26 15:21:19.613  6900  6900 V BluetoothFtpService: Ftp Service initSocket
07-26 15:21:19.616  1040  1055 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:19.617  6900  6900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:19.619  6900  6900 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
07-26 15:21:19.619  6900  6900 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-26 15:21:19.623  6900  7523 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,07-26 15:21:19.635  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:19.635  6900  6900 V BluetoothSapService: Sap Service onCreate
07-26 15:21:19.638  6900  6900 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.638  6900  6900 V BluetoothSapService: state: 12
07-26 15:21:19.638  6900  6900 V BluetoothSapService: Starting SAP server process
,07-26 15:21:19.640  6900  6900 V BluetoothSapService: SAP Service startRfcommListenerThread
07-26 15:21:19.631  7524  7524 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:19.631  7524  7524 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:19.646  6900  7525 V BluetoothSapService: Sap Service initRfcommSocket
07-26 15:21:19.646  1040  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:19.647  6900  7525 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:19.648  6900  7525 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
07-26 15:21:19.648  6900  7525 V BluetoothSapService: Succeed to create listening socket 
07-26 15:21:19.648  6900  7525 V BluetoothSapService: Accepting socket connection...
07-26 15:21:19.670  7524  7524 V BT_SAP  : Event pipe created
07-26 15:21:19.670  7524  7524 V BT_SAP  : create_server_socket qcom.sap.server
07-26 15:21:19.670  7524  7524 V BT_SAP  : created socket fd 6
,07-26 15:21:19.718  1040  1580 I art     : Explicit concurrent mark sweep GC freed 90690(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.171ms total 128.984ms
07-26 15:21:19.720  6900  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d408595 on behalf of 
,07-26 15:21:19.721  6900  7522 V BluetoothOppNotification: update too frequent, put in queue
,07-26 15:21:19.724  6900  7520 V BluetoothOppNotification: outbound notification was removed.
07-26 15:21:19.724  6900  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-26 15:21:19.725  6900  7522 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-26 15:21:19.725  6900  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-26 15:21:19.726  6900  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@336a76aa on behalf of 
07-26 15:21:19.726  6900  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5f8829b on behalf of 
,07-26 15:21:19.727  6900  7522 V BluetoothOppNotification: update too frequent, put in queue
07-26 15:21:19.727  6900  7520 V BluetoothOppNotification: inbound: succ-0  fail-0
07-26 15:21:19.728  6900  7522 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-26 15:21:19.730  6900  7520 V BluetoothOppNotification: inbound notification was removed.
07-26 15:21:19.730  6900  7520 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-26 15:21:19.733  6900  7520 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@217d0638 on behalf of 
,07-26 15:21:20.296  1040  1396 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:21:20.297  1040  1396 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:21:20.336  1040  1415 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-26 15:21:20.337  1040  1415 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-26 15:21:20.539  1040  1983 I ActivityManager: Killing 6783:com.lge.sync/1000 (adj 15): empty #17
,07-26 15:21:20.565  1040  1473 D WifiService: Client connection lost with reason: 4
,07-26 15:21:20.570  6900  6900 V BluetoothOppNotification: new notify threadi!
07-26 15:21:20.570  6900  6900 V BluetoothOppNotification: send delay message
07-26 15:21:20.572  6900  7536 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-26 15:21:20.573  6900  7536 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2170e611 on behalf of 
07-26 15:21:20.574  6900  7536 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-26 15:21:20.575  6900  7536 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-26 15:21:20.576  6900  7536 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25515376 on behalf of 
07-26 15:21:20.576  6900  7536 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-26 15:21:20.581  6900  7536 V BluetoothOppNotification: outbound notification was removed.
07-26 15:21:20.581  6900  7536 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-26 15:21:20.582  6900  7536 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e52ad77 on behalf of 
07-26 15:21:20.583  6900  7536 V BluetoothOppNotification: inbound: succ-0  fail-0
07-26 15:21:20.585  1040  1643 W libprocessgroup: failed to open /acct/uid_1000/pid_6783/cgroup.procs: No such file or directory
07-26 15:21:20.588  6900  7536 V BluetoothOppNotification: inbound notification was removed.
07-26 15:21:20.588  6900  7536 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-26 15:21:20.589  6900  7536 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b184de4 on behalf of 
,07-26 15:21:20.648  1040  1580 I ActivityManager: Killing 6691:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-26 15:21:20.671  6830  6830 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-26 15:21:20.671  6830  6830 W System.err: android.os.DeadObjectException
07-26 15:21:20.672  6830  6830 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-26 15:21:20.672  6830  6830 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-26 15:21:20.672  6830  6830 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-26 15:21:20.672  6830  6830 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-26 15:21:20.672  6830  6830 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-26 15:21:20.672  6830  6830 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-26 15:21:20.672  6830  6830 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:21:20.672  6830  6830 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:21:20.672  6830  6830 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:21:20.672  6830  6830 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-26 15:21:20.672  6830  6830 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:20.672  6830  6830 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:20.672  6830  6830 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-26 15:21:20.672  6830  6830 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-26 15:21:20.672  6830  6830 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-26 15:21:20.673  6830  6830 W System.err: android.os.DeadObjectException
07-26 15:21:20.673  6830  6830 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-26 15:21:20.673  6830  6830 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-26 15:21:20.673  6830  6830 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-26 15:21:20.673  6830  6830 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-26 15:21:20.673  6830  6830 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-26 15:21:20.673  6830  6830 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-26 15:21:20.673  6830  6830 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:21:20.673  6830  6830 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:21:20.673  6830  6830 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:21:20.673  6830  6830 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-26 15:21:20.673  6830  6830 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:20.673  6830  6830 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:20.673  6830  6830 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-26 15:21:20.674  6830  6830 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-26 15:21:20.674  6830  6830 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-26 15:21:20.674  6830  6830 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,07-26 15:21:20.707  1040  1056 W libprocessgroup: failed to open /acct/uid_1000/pid_6691/cgroup.procs: No such file or directory
07-26 15:21:20.708  1040  1056 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-26 15:21:20.715  6830  6830 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-26 15:21:20.715  6830  6830 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-26 15:21:20.768  1040  1643 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7537 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-26 15:21:20.790  6830  6830 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-26 15:21:20.872  7537  7537 D UEI.SmartControl: Quickset Services start...
,07-26 15:21:20.876  7537  7537 I UEI.SmartControl: Manufacture = LGE
,07-26 15:21:20.876  7537  7537 D UEI.SmartControl: Id = LGNevo
,07-26 15:21:20.878  7537  7537 D UEI.SmartControl: File observer start...
,07-26 15:21:20.878  7537  7537 E UEI.SmartControl: IR Port is disabled: false
07-26 15:21:20.879  7537  7537 D UEI.SmartControl: Starting file observer...
,07-26 15:21:20.879  7537  7537 D UEI.SmartControl: Extracting JNI libs...
,07-26 15:21:20.879  7537  7537 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,07-26 15:21:20.977  7537  7537 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-,
07-26 15:21:20.977  7537  7537 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,07-26 15:21:20.977  7537  7537 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-26 15:21:21.016  7537  7537 I UEI.SmartControl: --- Selecting new region: 6
,07-26 15:21:21.019  7537  7537 I UEI.SmartControl: Model = LG-D855
,07-26 15:21:21.021  7537  7537 D UEI.SmartControl: QS Service created
,07-26 15:21:21.038  7537  7537 I UEI.SmartControl: Service initServices...
,07-26 15:21:21.042  7537  7537 D UEI.SmartControl: QS start get config
,07-26 15:21:21.088  7537  7537 D UEI.SmartControl: Loading JNI Libs...
,07-26 15:21:21.289  1040  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-26 15:21:21.290  1040  1982 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@c832bf7 mBinding = false
,07-26 15:21:21.313  1040  1040 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-26 15:21:21.313  1040  1040 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,07-26 15:21:21.317  1040  1040 D Ulp_jni : JNI:system_update. Event-4
07-26 15:21:21.318  1040  1122 D BluetoothManagerService: Message: 2
07-26 15:21:21.319  1040  1122 D BluetoothManagerService: Sending off request.
07-26 15:21:21.320  6900  7498 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-26 15:21:21.321  6900  7393 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-26 15:21:21.321  6900  7393 D BluetoothAdapterProperties: Setting state to 13
07-26 15:21:21.321  6900  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-26 15:21:21.322  6900  7393 D BluetoothAdapterProperties: onBluetoothDisable()
07-26 15:21:21.322  6900  7393 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-26 15:21:21.325  1040  1122 D BluetoothManagerService: Message: 60
07-26 15:21:21.325  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-26 15:21:21.325  1040  1122 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-26 15:21:21.326  6900  7396 D BluetoothAdapterProperties: Scan Mode:20
,07-26 15:21:21.329  6900  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-26 15:21:21.329  6900  7509 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:21.330  6900  7393 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-26 15:21:21.336  6900  7508 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-26 15:21:21.336  6900  7508 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:21.336  6900  7508 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-26 15:21:21.336  6900  7508 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-26 15:21:21.336  6900  7508 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-26 15:21:21.336  6900  7508 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-26 15:21:21.336  6900  7508 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-26 15:21:21.336  6900  7508 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,07-26 15:21:21.336  6900  7521 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:21.337  6900  7523 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:21.337  6900  7525 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:21.338  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-26 15:21:21.338  6900  7449 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-26 15:21:21.339  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-26 15:21:21.339  6900  7449 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,07-26 15:21:21.343  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:21.343  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:21.343  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:21.343  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:21.343  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:21.343  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:21.343  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:21.343  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:21.343  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:21.343  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:21.343  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:21.345  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:21.345  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:21.345  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:21.345  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:21.345  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:21.345  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:21.345  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:21.345  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:21.345  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:21.345  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:21.345  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:21.347  1948  1948 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:21.347  1607  1607 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-26 15:21:21.349  6764  6764 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
07-26 15:21:21.351  6900  6900 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:21.351  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:21.351  6900  6900 D BluetoothMapService: STATE_TURNING_OFF
07-26 15:21:21.351  6900  6900 V BtOppService: Receiver DISABLED_ACTION 
07-26 15:21:21.351  6900  6900 V BluetoothMapService: Handler(): got msg=4
07-26 15:21:21.351  6900  6900 D BluetoothMapService: MAP Service closeService in
07-26 15:21:21.351  6900  6900 D BluetoothMapMasInstance: MAP Service shutdown
07-26 15:21:21.352  6900  6900 D LGBluetooth,MapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-26 15:21:21.352  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:21.353  6900  6900 V BluetoothMapService: MAP Service closeService out
07-26 15:21:21.353  6900  6900 I BtOppRfcommListener: stopping Accept Thread
07-26 15:21:21.353  6900  6900 V BtOppRfcommListener: close mBtServerSocket
07-26 15:21:21.353  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-26 15:21:21.353  6900  7521 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-26 15:21:21.360  6900  6900 V BtOppRfcommListener: waiting for thread to terminate
07-26 15:21:21.361  6900  6900 V BtOppRfcommListener: done waiting for thread to terminate
07-26 15:21:21.361  6900  6900 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-26 15:21:21.361  6900  6900 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:21.361  6900  6900 V BluetoothPbapReceiver: ***********state = 13
07-26 15:21:21.362  6900  6900 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-26 15:21:21.363  6900  6900 V BtOppService: onDestroy
07-26 15:21:21.371  2218  2218 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-26 15:21:21.372  6900  6900 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-26 15:21:21.372  6900  6900 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:21.372  6900  6900 V BluetoothPbapService: state: 13
07-26 15:21:21.372  6900  6900 V BluetoothPbapService: Pbap Service closeService in
07-26 15:21:21.373  6900  6900 V BluetoothPbapService: successfully stopped pbap service
07-26 15:21:21.374  6900  6900 V BluetoothPbapService: Pbap Service closeService out
07-26 15:21:21.375  6764  6764 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:21.376  6764  6764 D BluetoothPbap: Proxy object disconnected
07-26 15:21:21.376  6764  6764 D PbapServerProfile: Bluetooth service disconnected
07-26 15:21:21.380  6900  6900 V BluetoothPbapService: Pbap Service onDestroy
07-26 15:21:21.380  6900  6900 V BluetoothPbapService: Pbap Service closeService in
07-26 15:21:21.380  6900  6900 V BluetoothPbapService: Pbap Service closeService out
07-26 15:21:21.380  6900  6900 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-26 15:21:21.402  7537  7537 I UEI.SmartControl: Supports setup maps: true
,07-26 15:21:21.405  7537  7537 D UEI.SmartControl: QS start statue = true Error code = 0
07-26 15:21:21.405  7537  7537 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-26 15:21:21.405  7537  7537 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-26 15:21:21.406  7537  7537 I UEI.SmartControl: ### init IR Blaster...
07-26 15:21:21.407  6764  6764 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-26 15:21:21.411  7537  7537 D serial_port: Configuring serial port
07-26 15:21:21.411  6764  6764 D BluetoothPermissionRequest: onReceive
07-26 15:21:21.411  6764  6764 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-26 15:21:21.420  6764  6764 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-26 15:21:21.423  7537  7537 E UEI.SmartControl: UEIBLaster setting for 616
07-26 15:21:21.423  7537  7537 I UEI.SmartControl: Setting serial record hearder size = 2
07-26 15:21:21.424  7537  7537 I UEI.SmartControl: configuring settings for MAXQ616
07-26 15:21:21.424  7537  7537 I UEI.SmartControl: Get version...
07-26 15:21:21.427  6900  6900 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-26 15:21:21.427  6900  6900 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-26 15:21:21.428  6900  6900 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-26 15:21:21.432  6900  6900 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:21.432  6900  6900 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,07-26 15:21:21.434  6900  6900 V BluetoothFtpService: Ftp Service onStartCommand
07-26 15:21:21.434  6900  6900 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:21.435  6900  6900 V BluetoothFtpService: Ftp Service closeService
07-26 15:21:21.435  6900  6900 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-26 15:21:21.436  6900  6900 V BluetoothFtpService: successfully stopped ftp service
07-26 15:21:21.436  6900  6900 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-26 15:21:21.437  6900  6900 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-26 15:21:21.437  6900  6900 V BluetoothSapReceiver: SapReceiver onReceive 
07-26 15:21:21.437  6900  6900 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:21.437  6900  6900 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-26 15:21:21.437  6900  6900 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-26 15:21:21.438  6900  6900 V BluetoothFtpService: Ftp Service onDestroy
07-26 15:21:21.438  6900  6900 V BluetoothFtpService: Ftp Service closeService
07-26 15:21:21.441  6900  6900 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:21.441  6900  6900 V BluetoothSapService: state: 13
07-26 15:21:21.441  6900  6900 V BluetoothSapService: Stopping SAP server process
07-26 15:21:21.441  7537  7574 D UEI.SmartControl: serial port data available: 21
07-26 15:21:21.444  6900  6900 V BluetoothSapService: Sap Service closeSapService in
,07-26 15:21:21.444  6900  6900 V BluetoothSapService: Close listen Socket : 
07-26 15:21:21.444  6900  6900 V BluetoothSapService: Close rfcomm Socket : 
07-26 15:21:21.445  6900  6900 V BluetoothSapService: Close sapd  Socket : 
07-26 15:21:21.445  6900  6900 V BluetoothSapService: Sap Service closeSapService out
07-26 15:21:21.445  6900  6900 V BluetoothSapService: Sap Service onDestroy
07-26 15:21:21.445  6900  6900 V BluetoothSapService: Sap Service closeSapService in
07-26 15:21:21.445  6900  6900 V BluetoothSapService: Close listen Socket : 
07-26 15:21:21.445  6900  6900 V BluetoothSapService: Close rfcomm Socket : 
07-26 15:21:21.445  6900  6900 V BluetoothSapService: Close sapd  Socket : 
07-26 15:21:21.446  6900  6900 V BluetoothSapService: Sap Service closeSapService out
07-26 15:21:21.470  7537  7537 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-26 15:21:21.470  7537  7537 I UEI.SmartControl: IR Blaster version: 256702256704300002
,07-26 15:21:21.470  7537  7537 I UEI.SmartControl: QS saving settings...
07-26 15:21:21.472  7537  7537 D UEI.SmartControl: IR Blaster version: 25672567
07-26 15:21:21.489  7537  7574 D UEI.SmartControl: serial port data available: 4
,07-26 15:21:21.532  7537  7577 I UEI.SmartControl: Device manager: loading config....
,07-26 15:21:21.534  7537  7577 D UEI.SmartControl: ----------- loading internal config...
07-26 15:21:21.535  7537  7537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-26 15:21:21.540  7537  7537 E UEI.SmartControl: Services init done
07-26 15:21:21.540  7537  7537 D UEI.SmartControl: QS Service init finished
07-26 15:21:21.542  7537  7537 D UEI.SmartControl: QS Service version name: 2.1.91
07-26 15:21:21.542  7537  7537 D UEI.SmartControl: QS Service version code: 201091
07-26 15:21:21.544  7537  7537 D UEI.SmartControl: Service requested: Control
07-26 15:21:21.555  7537  7577 E UEI.SmartControl: Loading SETTINGS...
07-26 15:21:21.555  7537  7537 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-26 15:21:21.560  6830  6830 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-26 15:21:21.561  7537  7553 I UEI.SmartControl: ------ IControl API: 11
07-26 15:21:21.562  1040  1786 I ActivityManager: Killing 6830:com.lge.qremote/u0a112 (adj 15): empty #17
07-26 15:21:21.565  7537  7553 I UEI.SmartControl: Registering callback...
07-26 15:21:21.580  7537  7577 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-26 15:21:21.608  7537  7576 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-26 15:21:21.608  7537  7576 D UEI.SmartControl: -----service ready thread exits
,07-26 15:21:21.627  1040  1875 W libprocessgroup: failed to open /acct/uid_10112/pid_6830/cgroup.procs: No such file or directory
07-26 15:21:21.628  7537  7537 D UEI.SmartControl: Internal service binding...
,07-26 15:21:22.286  6900  7396 D bt_hci_bdroid: cleanup
,07-26 15:21:22.292  6900  7451 I bt_lpm  : LPM is already off!!!
,07-26 15:21:22.293  6900  7490 I bt_userial_mct: exiting userial_read_thread
,07-26 15:21:22.295  6900  7449 W bt-btif : ag scb idx 1 not allocated
,07-26 15:21:22.295  6900  7449 E bt-btif : BTA AG is already disabled, ignoring ...
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,07-26 15:21:22.295  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019,
,07-26 15:21:22.296  6900  7449 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
07-26 15:21:22.296  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-26 15:21:22.296  6900  7449 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:22.296  6900  7449 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b,
07-26 15:21:22.296  6900  7449 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:22.296  6900  7449 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-26 15:21:22.299  6900  7490 D bt_userial_mct: Leaving userial_evt_read_thread(),
,07-26 15:21:22.300  6900  7396 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-26 15:21:22.301  6900  7451 I bt_vendor: hw_epilog_process
07-26 15:21:22.302  6900  7396 D bt_hci_bdroid: cleanup Finalizing cleanup
07-26 15:21:22.302  6900  7396 D bt_userial_mct: userial_close
07-26 15:21:22.302  6900  7396 E bt_userial_mct: pthread_join() FAILED result:3
07-26 15:21:22.302  6900  7396 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-26 15:21:22.318  6900  7396 D bt_hci_bdroid: set_power 0
07-26 15:21:22.318  6900  7396 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,07-26 15:21:22.336  6900  7396 I bt_vendor: bluetooth satus is on,
07-26 15:21:22.336  6900  7396 I bt_vendor: bt-vendor : resetting BT status
07-26 15:21:22.336  6900  7396 I bt_vendor: Starting hciattach daemon
07-26 15:21:22.336  6900  7396 I bt_vendor: try to set false
07-26 15:21:22.339  6900  7396 I bt_vendor: Starting hciattach daemon
07-26 15:21:22.339  6900  7396 I bt_vendor: try to set false
07-26 15:21:22.340  6900  7396 I bt_vendor: cleanup
07-26 15:21:22.341  6900  7449 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-26 15:21:22.342  6900  7396 I GKI_LINUX: GKI_exit_task 0 done
,07-26 15:21:22.343  6900  7396 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-26 15:21:22.344  6900  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,07-26 15:21:22.354  6900  7393 D BluetoothAdapterState: Stopping profile services that were post enabled
07-26 15:21:22.356  6900  6900 D HeadsetService: Received stop request...Stopping profile...
,07-26 15:21:22.358  6900  6900 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-26 15:21:22.358  6900  6900 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:21:22.358  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:22.359  6900  7420 D HeadsetStateMachine: Exit Disconnected: -1
07-26 15:21:22.363  1040  1040 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:22.363  1040  1040 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-26 15:21:22.363  1858  1858 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:22.364  1858  1858 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:22.364  1858  1858 D BluetoothHeadset: Proxy object disconnected
07-26 15:21:22.365  6900  6900 D A2dpService: Received stop request...Stopping profile...
07-26 15:21:22.365  6900  7440 D A2dpStateMachine: Exit Disconnected: -1
07-26 15:21:22.367  6900  6900 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-26 15:21:22.369  6900  6900 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-26 15:21:22.369  6900  6900 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:21:22.369  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
,07-26 15:21:22.375  1040  1040 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:22.375  1040  1040 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-26 15:21:22.376  6900  6900 D HidService: Received stop request...Stopping profile...
07-26 15:21:22.376  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:22.378  6900  6900 D HealthService: Received stop request...Stopping profile...
07-26 15:21:22.378  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:22.381  6900  6900 D PanService: Received stop request...Stopping profile...
07-26 15:21:22.382  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
,07-26 15:21:22.388  6900  6900 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:21:22.388  6900  6900 D BtGatt.GattService: Received stop request...Stopping profile...
07-26 15:21:22.388  6900  6900 D BtGatt.GattService: stop()
07-26 15:21:22.389  6900  6900 D BtGatt.AdvertiseManager: advertise clients cleared
07-26 15:21:22.390  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
07-26 15:21:22.392  6900  6900 D BluetoothMapService: Received stop request...Stopping profile...
07-26 15:21:22.392  6900  6900 D BluetoothMapService: stop()
07-26 15:21:22.393  6900  6900 D BluetoothMapEmailAppObserver: deinitObservers()
07-26 15:21:22.393  6900  6900 D BluetoothMapEmailAppObserver: removeReceiver()
07-26 15:21:22.394  6900  6900 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@158d2178
,07-26 15:21:22.397  6900  6900 V BluetoothMapService: Handler(): got msg=4
07-26 15:21:22.397  6900  6900 D BluetoothMapService: MAP Service closeService in
07-26 15:21:22.397  6900  6900 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-26 15:21:22.397  6900  6900 V BluetoothMapService: MAP Service closeService out
07-26 15:21:22.398  6900  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-26 15:21:22.398  6900  7393 D BluetoothAdapterProperties: Setting state to 10
07-26 15:21:22.398  6900  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-26 15:21:22.398  1040  1122 D BluetoothManagerService: Message: 60
07-26 15:21:22.398  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-26 15:21:22.399  1040  1122 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
07-26 15:21:22.399  6900  7393 I BluetoothAdapterState: Entering OffState
07-26 15:21:22.399  6764  6892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:22.400  6764  6892 D BluetoothPan: onBluetoothStateChange on: false
07-26 15:21:22.401  1040  1122 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:21:22.401  1858  2447 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:22.403  1858  1873 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:22.404  1858  1874 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:21:22.405  6764  6892 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:21:22.406  1040  1122 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-26 15:21:22.408  6764  6892 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:21:22.409  6900  6900 D HeadsetStateMachine: Unbinding service...
07-26 15:21:22.410  6900  6900 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-26 15:21:22.410  6900  6900 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-26 15:21:22.410  6900  6900 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-26 15:21:22.410  6900  6900 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-26 15:21:22.410  6900  6900 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 15:21:22.410  6900  6900 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:21:22.410  6900  6900 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-26 15:21:22.412  6764  6892 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:21:22.413  6900  6900 I BluetoothA2dpServiceJni: cleanupNative
07-26 15:21:22.414  6900  7442 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-26 15:21:22.415  6900  6900 I GKI_LINUX: GKI_exit_task 2 done
07-26 15:21:22.415  6900  6900 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-26 15:21:22.416  6764  6892 D BluetoothMap: onBluetoothStateChange: up=false
07-26 15:21:22.418  6900  6900 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-26 15:21:22.418  6900  6900 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,07-26 15:21:22.421  1040  1122 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-26 15:21:22.421  1040  1122 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-26 15:21:22.421  6900  6900 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:21:22.422  6900  6900 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:21:22.422  6900  6900 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:21:22.425  6900  6900 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-26 15:21:22.425  6900  6900 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-26 15:21:22.428  1040  1122 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-26 15:21:22.428  1040  1122 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-26 15:21:22.428  1040  1122 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@c832bf7 mBinding = false
07-26 15:21:22.429  1040  1122 D BluetoothManagerService: Sending unbind request.
,07-26 15:21:22.431  6900  6900 D BluetoothMapService: cleanup()
07-26 15:21:22.431  6900  6900 D BluetoothMapService: MAP Service closeService in
07-26 15:21:22.431  6900  6900 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-26 15:21:22.431  6900  6900 V BluetoothMapService: MAP Service closeService out
07-26 15:21:22.437  6900  7396 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-26 15:21:22.438  6900  6900 I GKI_LINUX: GKI_exit_task 1 done
07-26 15:21:22.438  6900  6900 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-26 15:21:22.439  6900  6900 I BluetoothServiceJni: cleanupNative: return from cleanup
07-26 15:21:22.439  6900  6900 I art     : --- WEIRD: removing null entry 248
07-26 15:21:22.439  6900  6900 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
07-26 15:21:22.439  6900  6900 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-26 15:21:22.440  6900  6900 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,07-26 15:21:22.443  1040  1122 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-26 15:21:22.445  6900  6900 I art     : System.exit called, status: 0
07-26 15:21:22.445  6900  6900 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-26 15:21:22.464   329  2189 V AudioFlinger: 6900 died, releasing its sessions
07-26 15:21:22.464   329  2189 V AudioFlinger:  pid 1858 @ 0
07-26 15:21:22.464   329  2189 V AudioFlinger:  pid 3318 @ 1
07-26 15:21:22.464   329  2189 V AudioFlinger:  pid 3318 @ 2
,07-26 15:21:22.468  1948  1948 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
07-26 15:21:22.468  1948  2109 D LGBluetoothAPIService: Message: 101
07-26 15:21:22.468  1948  2109 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
07-26 15:21:22.468  1948  2109 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
07-26 15:21:22.469  1948  2109 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
07-26 15:21:22.470  6764  6764 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-26 15:21:22.481  1040  1580 I ActivityManager: Process com.android.bluetooth (pid 6900) has died
07-26 15:21:22.481  1040  1580 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
07-26 15:21:22.481  1040  1580 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,07-26 15:21:22.488  1948  1948 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:22.488  1948  2109 D LGBluetoothAPIService: Message: 2
07-26 15:21:22.488  1948  2109 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
07-26 15:21:22.489  1607  1607 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-26 15:21:22.496  6764  6764 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-26 15:21:22.496  6764  6764 D LGBluetoothEventManager: [BTUI] clear device connection state
,07-26 15:21:22.497  1607  1607 D BluetoothAdapter: 350497474: getState() :  mService = null. Returning STATE_OFF
07-26 15:21:22.497  1607  1607 D BluetoothAdapter: 350497474: getState() :  mService = null. Returning STATE_OFF
07-26 15:21:22.499  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:22.500  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:22.500  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-26 15:21:22.542  1040  1875 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7608 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-26 15:21:22.546  6764  6764 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:22.587  1040  1384 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1ee9d0c9 type 2 when 160161 com.google.android.gms} when 160161
07-26 15:21:22.591   325  7628 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-26 15:21:22.591  1040  1120 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-26 15:21:22.601  7608  7608 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-26 15:21:22.601  7608  7608 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-26 15:21:22.602  7608  7608 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,07-26 15:21:22.603  7608  7608 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-26 15:21:22.622  7608  7608 D BluetoothAdapterApp: Loading JNI Library
,07-26 15:21:22.659  7608  7608 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3a44e660 Instance Count = 1
,07-26 15:21:22.664  7608  7608 D BluetoothAdapterApp: onCreate
07-26 15:21:22.689  7608  7608 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-26 15:21:22.689  7608  7608 D ProfileConfigQcom: Adding HeadsetService
07-26 15:21:22.689  7608  7608 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-26 15:21:22.690  7608  7608 D ProfileConfigQcom: Adding A2dpService
07-26 15:21:22.690  7608  7608 D ProfileConfigQcom: [BTUI] HidService is supported
,07-26 15:21:22.690  7608  7608 D ProfileConfigQcom: Adding HidService
07-26 15:21:22.690  7608  7608 D ProfileConfigQcom: [BTUI] HealthService is supported
07-26 15:21:22.690  7608  7608 D ProfileConfigQcom: Adding HealthService
07-26 15:21:22.691  7608  7608 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-26 15:21:22.693  7608  7608 D ProfileConfigQcom: [BTUI] PanService is supported
07-26 15:21:22.693  7608  7608 D ProfileConfigQcom: Adding PanService
07-26 15:21:22.694  7608  7608 D ProfileConfigQcom: [BTUI] GattService is supported
07-26 15:21:22.695  7608  7608 D ProfileConfigQcom: Adding GattService
07-26 15:21:22.695  7608  7608 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-26 15:21:22.696  7608  7608 D ProfileConfigQcom: Adding BluetoothMapService
,07-26 15:21:22.697  7608  7608 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-26 15:21:22.699  7608  7608 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-26 15:21:22.701  7608  7608 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:22.702  7608  7608 V BluetoothPbapReceiver: ***********state = 10
07-26 15:21:22.711  7608  7608 V LGMDMManagerInternal: Create singleton instance
07-26 15:21:22.797  2218  2218 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:22.798  6764  6764 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-26 15:21:22.802  7608  7608 D LGBluetoothAPIServer: [BTUI] onCreate()
07-26 15:21:22.803  7608  7608 D LGBluetoothAPIServer: [BTUI] onBind()
07-26 15:21:22.807  1948  1948 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-26 15:21:22.807  1948  2109 D LGBluetoothAPIService: Message: 100
07-26 15:21:22.807  1948  2109 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-26 15:21:22.813  6764  6764 D BluetoothPermissionRequest: onReceive
,07-26 15:21:22.816  6764  6764 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-26 15:21:22.817  6764  6764 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-26 15:21:22.821  6764  6764 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-26 15:21:22.833  7608  7608 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,07-26 15:21:22.843  7608  7608 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:22.849  7608  7608 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-26 15:21:22.850  7608  7608 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-26 15:21:22.851  7608  7608 V BluetoothSapReceiver: SapReceiver onReceive 
07-26 15:21:22.855  7608  7608 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:22.855  7608  7608 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-26 15:21:22.871  7456  7456 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,07-26 15:21:24.326  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:21:24.326  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:24.513  1607  1607 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-26 15:21:24.575  1040  1386 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-26 15:21:24.613  1040  1109 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7640 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-26 15:21:24.619  1607  1607 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-26 15:21:24.620  1607  1607 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-26 15:21:24.659  1040  1040 D administrator: Handling package changes for user 0
07-26 15:21:24.661  2038  2038 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-26 15:21:24.696  2038  2038 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-26 15:21:24.714  7640  7640 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-26 15:21:24.765  1040  1040 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-26 15:21:24.765  1040  1040 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-26 15:21:24.800  7640  7640 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:24.800  7640  7640 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:24.811  1040  1106 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:24.816  1040  1106 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-26 15:21:24.822  2038  2038 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,07-26 15:21:24.823  2487  2487 V GmsNetworkLocationProvi: DISABLE
07-26 15:21:24.856  2487  2487 E GCoreFlp: Bound FusedProviderService with LocationManager
07-26 15:21:24.857  1040  1106 D LocationProviderProxy: applying state to connected service
,07-26 15:21:24.920  7640  7684 I Babel   : MmsConfig: mnc/mcc: 0/0
07-26 15:21:24.920  7640  7684 I Babel   : MmsConfig.loadMmsSettings
,07-26 15:21:24.924  7640  7684 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-26 15:21:24.925  7640  7684 I Babel   : MmsConfig.loadFromDatabase
,07-26 15:21:24.942  7640  7684 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-26 15:21:24.942  7640  7684 I Babel   : MmsConfig.loadFromResources
07-26 15:21:24.944  7640  7684 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-26 15:21:24.944  7640  7684 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-26 15:21:24.944  7640  7682 W AudioCapabilities: Unsupported mime audio/evrc
07-26 15:21:24.945  7640  7682 W AudioCapabilities: Unsupported mime audio/qcelp
07-26 15:21:24.947  7640  7682 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:21:24.951  7640  7640 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:24.955  7640  7682 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-26 15:21:24.956  7640  7682 W AudioCapabilities: Unsupported mime audio/qcelp
07-26 15:21:24.957  7640  7682 W AudioCapabilities: Unsupported mime audio/evrc
07-26 15:21:24.963  7640  7682 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-26 15:21:24.965  7640  7682 W VideoCapabilities: Unsupported mime video/divx
07-26 15:21:24.968  7640  7682 W VideoCapabilities: Unsupported mime video/divx311
07-26 15:21:24.969  7640  7682 W VideoCapabilities: Unsupported mime video/divx4
07-26 15:21:24.974  7640  7682 W VideoCapabilities: Unsupported mime video/mp4v-esdp
07-26 15:21:24.987  1823  7688 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-26 15:21:24.987  1823  7688 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-26 15:21:24.992  6950  6950 I AppUp4:CustModeStarterReceiver: onReceive
07-26 15:21:24.994  7640  7682 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-26 15:21:24.995  1823  4784 I Icing   : updateResources: need to parse e{com.google.android.gms}
07-26 15:21:24.996  6950  6950 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33edcfea
07-26 15:21:24.996  6950  6950 D AppUp4:CustFacade: isCustomizationCompleted : false
07-26 15:21:24.996  6950  6950 D AppUp4:CustFacade: isPhone : true
07-26 15:21:24.997  6950  6950 D AppUp4:CustModeStarterReceiver: begin check event
07-26 15:21:24.997  6950  6950 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-26 15:21:25.006  7640  7682 W AudioCapabilities: Unsupported mime audio/eac3
,07-26 15:21:25.015  7640  7682 W AudioCapabilities: Unsupported mime audio/ac3
07-26 15:21:25.016  7640  7682 W AudioCapabilities: Unsupported mime audio/g726
07-26 15:21:25.018  7640  7682 W AudioCapabilities: Unsupported mime audio/wma-voice
07-26 15:21:25.018  1040  1786 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7690 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-26 15:21:25.024  7640  7682 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-26 15:21:25.026  7640  7682 W AudioCapabilities: Unsupported mime audio/adpcm
07-26 15:21:25.036  7640  7682 W VideoCapabilities: Unsupported mime video/theora
,07-26 15:21:25.037  7640  7682 W VideoCapabilities: Unsupported mime video/mjpg
,07-26 15:21:25.070  7690  7690 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:25.070  7690  7690 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-26 15:21:25.071  7690  7690 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,07-26 15:21:25.072  7690  7690 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-26 15:21:25.073  1040  2018 I ActivityManager: Killing 7324:com.android.vending/u0a44 (adj 15): empty #17
07-26 15:21:25.074  7690  7690 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-26 15:21:25.199  1040  1580 W libprocessgroup: failed to open /acct/uid_10044/pid_7324/cgroup.procs: No such file or directory
,07-26 15:21:25.259  7690  7690 I SystemConfig: BUILD Country: EU
07-26 15:21:25.259  7690  7690 I SystemConfig: BUILD Operator: OPEN
,07-26 15:21:25.333  1040  1786 I ActivityManager: Killing 6990:com.lge.email/u0a23 (adj 15): empty #17
,07-26 15:21:25.500  1040  1983 W libprocessgroup: failed to open /acct/uid_10023/pid_6990/cgroup.procs: No such file or directory
,07-26 15:21:25.546  1040  1786 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7714 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-26 15:21:25.551  7690  7712 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-26 15:21:25.551  7690  7712 I SystemConfig: existFile = false
07-26 15:21:25.551  7690  7712 I SystemConfig: canReadFile = false
07-26 15:21:25.552  7690  7712 I SystemConfig: systemFeature RCS result false
07-26 15:21:25.552  7690  7712 D SystemConfig: refreshRcsSupport() :false
,07-26 15:21:25.596  7714  7714 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:25.596  7714  7714 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-26 15:21:25.596  7714  7714 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-26 15:21:25.596  7714  7714 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-26 15:21:25.695  7714  7714 I AppConfig: Total System Memory = 2995761152
,07-26 15:21:25.703  7714  7714 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-26 15:21:25.795  1040  1056 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7733 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:25.803  1040  1056 I ActivityManager: Killing 6870:com.lge.formmanager/u0a26 (adj 15): empty #17
07-26 15:21:25.831   356   356 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 462us total 38.072ms
,07-26 15:21:25.853   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 21.562ms
,07-26 15:21:25.876   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 20.736ms
,07-26 15:21:25.899  1040  2018 W libprocessgroup: failed to open /acct/uid_10026/pid_6870/cgroup.procs: No such file or directory
07-26 15:21:26.074  7733  7733 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-26 15:21:26.165  7733  7733 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:26.165  7733  7733 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:26.219  7733  7733 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-26 15:21:26.239  7733  7733 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-26 15:21:26.240  7733  7733 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-26 15:21:26.256  7733  7733 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,07-26 15:21:26.256  7733  7733 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-26 15:21:26.287  1040  2018 I ActivityManager: Killing 6381:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,07-26 15:21:26.384  1040  1982 W libprocessgroup: failed to open /acct/uid_1000/pid_6381/cgroup.procs: No such file or directory
,07-26 15:21:26.408  4609  7772 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-26 15:21:26.448  1040  1786 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7774 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:26.465  3419  3438 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,07-26 15:21:26.468  3419  3438 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3219e28f on behalf of 7733
07-26 15:21:26.484  7733  7733 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-26 15:21:26.508  7733  7733 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-26 15:21:26.520  7774  7774 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-26 15:21:26.530  7537  7578 D UEI.SmartControl: Internal timer expired: 1
07-26 15:21:26.531  7537  7578 D UEI.SmartControl: unbind internal service
07-26 15:21:26.532  7537  7537 D UEI.SmartControl: Service.onUnbind: IControl
07-26 15:21:26.532  7537  7537 D UEI.SmartControl: Service.onDestroy
07-26 15:21:26.532  7537  7537 D UEI.SmartControl: Lock is in USE false
07-26 15:21:26.532  7537  7537 D UEI.SmartControl: unbind internal service
07-26 15:21:26.533  7537  7537 D serial_port: close(fd = 25)
07-26 15:21:26.536  7537  7537 I UEI.SmartControl: Serial port is closed.
07-26 15:21:26.536  7537  7537 I UEI.SmartControl: Serial port is closed.
07-26 15:21:26.537  7537  7537 D UEI.SmartControl: Blaster closed
07-26 15:21:26.537  7537  7537 D UEI.SmartControl: Shut down QS...
07-26 15:21:26.537  7537  7537 D UEI.SmartControl: Stopping QS lib
07-26 15:21:26.537  7537  7537 D UEI.SmartControl: QS lib stop result = true
,07-26 15:21:26.537  7537  7537 D UEI.SmartControl: Stopped QS lib
07-26 15:21:26.538  7774  7774 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-26 15:21:26.538  7774  7774 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-26 15:21:26.538  7774  7774 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-26 15:21:26.538  7774  7774 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-26 15:21:26.538  7774  7774 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-26 15:21:26.538  7774  7774 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
07-26 15:21:26.540  7537  7537 D UEI.SmartControl: Stopped file observer...
07-26 15:21:26.540  7537  7537 D UEI.SmartControl: QS shutdown complete
07-26 15:21:26.559  1040  2018 I ActivityManager: Killing 7029:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-26 15:21:26.641  1040  1982 W libprocessgroup: failed to open /acct/uid_10046/pid_7029/cgroup.procs: No such file or directory
,07-26 15:21:26.945  1040  1982 V SIM_STK : Menu title from STK is T-Mobile
,07-26 15:21:26.969  4609  7772 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 557 ms] updated apps [took 557 ms] 
,07-26 15:21:27.341  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:27.341  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@46a9d81 added. We now have 6 listener(s)
,07-26 15:21:27.341  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:27.357  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:27.357  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30288e26 added. We now have 7 listener(s)
07-26 15:21:27.357  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:27.359  6570  6636 I System.out: IsBluetoothEnabled
07-26 15:21:27.360  1040  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:27.360  1040  1921 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
07-26 15:21:27.361  1040  1122 D BluetoothManagerService: Message: 2
,07-26 15:21:27.366  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:27.366  1040  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:27.366  1040  1902 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-26 15:21:27.382  1040  1040 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-26 15:21:27.382  1040  1040 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-26 15:21:27.382  1040  1040 D Ulp_jni : JNI:system_update. Event-4
,07-26 15:21:27.386  1040  1122 D BluetoothManagerService: Message: 1
07-26 15:21:27.386  1040  1122 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,07-26 15:21:27.413  1040  1122 D BluetoothManagerService: Message: 20
07-26 15:21:27.413  1040  1122 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@379cf84d:true
,07-26 15:21:27.417  7608  7608 D BluetoothAdapterState: make
07-26 15:21:27.422  7608  7608 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-26 15:21:27.422  7608  7608 I bluedroid-qcom: init
07-26 15:21:27.423  7608  7810 I BluetoothAdapterState: Entering OffState
07-26 15:21:27.424  7608  7608 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-26 15:21:27.424  7608  7608 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-26 15:21:27.424  7608  7608 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-26 15:21:27.424  7608  7608 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-26 15:21:27.424  7608  7608 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-26 15:21:27.426  7608  7608 I bluedroid-qcom: get_profile_interface socket
07-26 15:21:27.426  7608  7608 I bluedroid-qcom: get_profile_interface map_client
,07-26 15:21:27.431  7608  7814 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-26 15:21:27.434  7608  7814 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-26 15:21:27.431  7813  7813 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:27.431  7813  7813 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:27.443  7813  7813 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-26 15:21:27.443  7813  7813 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-26 15:21:27.443  7813  7813 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,07-26 15:21:27.449  1040  1040 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-26 15:21:27.450  1040  1040 D BluetoothManagerService: Stored Bluetooth name: G3
07-26 15:21:27.451  1040  1040 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-26 15:21:27.451  1040  1122 D BluetoothManagerService: Message: 40
07-26 15:21:27.451  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-26 15:21:27.452  7608  7624 I bluedroid-qcom: config_hci_snoop_log
07-26 15:21:27.453  1040  1122 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-26 15:21:27.453  1040  1122 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-26 15:21:27.454  7813  7813 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-26 15:21:27.457  7608  7814 D BluetoothAdapterProperties: Name is: G3
,07-26 15:21:27.462  7813  7813 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-26 15:21:27.462  7813  7813 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-26 15:21:27.467  7608  7810 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-26 15:21:27.467  7608  7810 D BluetoothAdapterProperties: Setting state to 11
07-26 15:21:27.467  7608  7810 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-26 15:21:27.469  7608  7810 I LGBluetoothServiceJni: classInitNative: succeeds
,07-26 15:21:27.475  1040  1122 D BluetoothManagerService: Message: 60
07-26 15:21:27.475  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-26 15:21:27.475  1040  1122 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-26 15:21:27.479  1948  1948 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:27.480  1607  1607 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-26 15:21:27.483  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:27.487  6764  6764 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-26 15:21:27.507  7608  7608 V BluetoothPbapReceiver: PbapReceiver onReceive 
,07-26 15:21:27.507  7608  7608 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:27.507  7608  7608 V BluetoothPbapReceiver: ***********state = 11
07-26 15:21:27.508  7608  7810 D BluetoothBondStateMachine: make
07-26 15:21:27.512  7608  7810 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:27.512  7608  7810 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-26 15:21:27.512  7608  7810 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:27.512  7608  7810 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-26 15:21:27.513  7608  7827 I BluetoothBondStateMachine: StableState(): Entering Off State
07-26 15:21:27.513  2218  2218 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-26 15:21:27.513  7608  7810 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-26 15:21:27.518  7608  7810 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:27.527  7608  7608 D HeadsetService: Received start request. Starting profile...
07-26 15:21:27.527  6764  6764 D BluetoothPermissionRequest: onReceive
07-26 15:21:27.527  7608  7608 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-26 15:21:27.527  7608  7608 D LGBluetoothHfpAdapter: Version 1.6
,07-26 15:21:27.530  7608  7608 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-26 15:21:27.531  6764  6764 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-26 15:21:27.532  7608  7608 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-26 15:21:27.532  7608  7608 D HeadsetStateMachine: make
07-26 15:21:27.535  7608  7810 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:27.540  7608  7810 E BluetoothAdapterService: File transfer profiles supported!!
,07-26 15:21:27.547  7608  7810 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:27.551  7608  7810 E BluetoothAdapterService: File transfer profiles supported!!
,07-26 15:21:27.555  7608  7810 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:27.559  7608  7810 E BluetoothAdapterService: File transfer profiles supported!!
07-26 15:21:27.569  7608  7608 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:27.569  7608  7608 D LgDataFeature: LgDataFeature() Constructor Done, null
07-26 15:21:27.570  7608  7810 V LGMDMManager: Create singleton instance
07-26 15:21:27.571  7608  7810 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-26 15:21:27.573  7608  7608 D HeadsetStateMachine: max_hf_connections = 1
07-26 15:21:27.573  7608  7608 I bluedroid-qcom: get_profile_interface handsfree
07-26 15:21:27.575  7608  7608 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-26 15:21:27.576   329  2188 V AudioPolicyService: registerClient() client 0xb558aa00, uid 1002
07-26 15:21:27.576   329  1403 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-26 15:21:27.576   329  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-26 15:21:27.576   329  1403 V AudioPolicyManagerEx: getOutput() returns output 2
07-26 15:21:27.576  7608  7608 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-26 15:21:27.577   329  1402 V AudioFlinger: registerClient() client 0xb1019dc0, pid 7608
07-26 15:21:27.577   329  1397 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:27.577   329  1397 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:27.577  1040  1055 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:27.577  1040  1055 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:27.577  7608  7608 V ToneGenerator: Create Track: 0xb4928080
07-26 15:21:27.578  7608  7608 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-26 15:21:27.578  7608  7608 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-26 15:21:27.578  7608  7624 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:27.578  7608  7624 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-26 15:21:27.578   329  1403 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-26 15:21:27.578   329  1403 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-26 15:21:27.578   329  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-26 15:21:27.578   329  1403 V AudioPolicyManagerEx: getOutput() returns output 2
07-26 15:21:27.578  1607  2312 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:27.578  1607  2312 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:27.578   329  1403 I AudioFlinger: isAudioPlaybackHookOn() false
07-26 15:21:27.578   329  2188 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-26 15:21:27.578   329  2188 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-26 15:21:27.578   329  2188 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-26 15:21:27.578   329  2188 V AudioPolicyManagerEx: getOutput() returns output 2
07-26 15:21:27.578  7608  7608 V AudioSystem: getLatency() output 2, latency 50
07-26 15:21:27.578  7608  7608 V AudioSystem: getFrameCount() output 2, frameCount 960
07-26 15:21:27.578  7608  7608 V AudioTrack: createTrack_l() output 2 afLatency 50
07-26 15:21:27.579  1858  1873 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:27.579  1858  1873 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:27.579   329  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-26 15:21:27.579   329  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-26 15:21:27.579   329  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:27.579   329  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:27.579  1607  1628 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:27.579  1607  1628 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:27.579  1040  1580 V AudioSystem: ioConfigChanged() event, 0, ioHandle 4
07-26 15:21:27.579  1858  1874 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:27.579  1040  1580 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:27.579  1858  1874 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:27.579  7608  7624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:27.579  7608  7624 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-26 15:21:27.579   329  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-26 15:21:27.579   329  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-26 15:21:27.579   329  1402 V AudioFlinger: createTrack() lSessionId: 21
07-26 15:21:27.580  3318  3333 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-26 15:21:27.580  3318  3333 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-26 15:21:27.580  3318  3333 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-26 15:21:27.580  3318  3333 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-26 15:21:27.580  7608  7608 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-26 15:21:27.580   329  1402 V AudioFlinger: acquiring 21 from 7608, for 7608
07-26 15:21:27.580   329  1402 V AudioFlinger:  added new entry for 21
07-26 15:21:27.580  7608  7608 V ToneGenerator: ToneGenerator INIT OK, time: 165166
07-26 15:21:27.581  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:27.581  7608  7831 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-26 15:21:27.581  7608  7831 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-26 15:21:27.581  7608  7831 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-26 15:21:27.581  7608  7831 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-26 15:21:27.581   329   329 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7608
07-26 15:21:27.582   329   329 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-26 15:21:27.582   329   329 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-26 15:21:27.582   329   329 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-26 15:21:27.582   329   329 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-26 15:21:27.582   329   329 V voice   : voice_set_parameters: exit with code(0)
07-26 15:21:27.582   329   329 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-26 15:21:27.582   329   329 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-26 15:21:27.582  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:27.582   329   329 V msm8974_platform: platform_set_parameters: exit with code(0)
07-26 15:21:27.582   329   329 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-26 15:21:27.582   329   329 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-26 15:21:27.582   329   329 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-26 15:21:27.582  7608  7831 V ToneGenerator: ToneGenerator destructor
07-26 15:21:27.582  7608  7831 V ToneGenerator: stopTone
07-26 15:21:27.582  7608  7831 V ToneGenerator: Delete Track: 0xb4928080
07-26 15:21:27.583  7608  7831 V AudioTrack: ~AudioTrack, releasing session id from 7608 on behalf of 7608
07-26 15:21:27.583   329  2188 V AudioFlinger: releasing 21 from 7608 for 7608
07-26 15:21:27.583   329  2188 V AudioFlinger:  decremented refcount to 0
07-26 15:21:27.583   329  2188 V AudioFlinger: purging stale effects
07-26 15:21:27.584   329  2188 V AudioPolicyService: AudioCommandThread() adding release output 2
07-26 15:21:27.584   329  2188 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-26 15:21:27.584   329  1270 V AudioPolicyService: AudioCommandThread() waking up
07-26 15:21:27.584   329  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
07-26 15:21:27.584   329  1270 V AudioPolicyManager: releaseOutput() 2
07-26 15:21:27.584   329  1270 V AudioPolicyService: AudioCommandThread() going to sleep
07-26 15:21:27.584   329  2188 V AudioFlinger: PlaybackThread::Track destructor
07-26 15:21:27.584   329  2188 V AudioFlinger: removeClient_l() pid 7608, calling pid 329
07-26 15:21:27.586  7608  7608 D A2dpService: Received start request. Starting profile...
07-26 15:21:27.586  7608  7608 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-26 15:21:27.587  7608  7608 V Avrcp   : make
07-26 15:21:27.587  1040  1055 W Process : Unable to open /proc/7834/status
07-26 15:21:27.588  7608  7608 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-26 15:21:27.588  7608  7608 I bluedroid-qcom: get_profile_interface avrcp
07-26 15:21:27.595  7608  7608 V AudioManager: registerRemoteController: size of Media player list: 0
,07-26 15:21:27.597  7608  7608 E AudioManager: No RCC entry present to update
07-26 15:21:27.597  7608  7608 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-26 15:21:27.600  7608  7608 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-26 15:21:27.601  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-26 15:21:27.601  7608  7608 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-26 15:21:27.604  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-26 15:21:27.706  1040  2018 V SIM_STK : Menu title from STK is T-Mobile
07-26 15:21:27.706  1040  2018 V SIM_STK : Menu title from STK is T-Mobile
,07-26 15:21:27.778  1040  1055 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-26 15:21:27.787  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-26 15:21:27.791  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-26 15:21:27.791  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-26 15:21:27.791  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-26 15:21:27.791  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-26 15:21:27.792  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-26 15:21:27.792  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-26 15:21:27.792  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-26 15:21:27.792  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-26 15:21:27.792  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-26 15:21:27.792  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-26 15:21:27.792  7608  7608 I BluetoothA2dpServiceJni: classInitNative
07-26 15:21:27.792  7608  7608 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:21:27.792  7608  7608 D A2dpStateMachine: make
07-26 15:21:27.796  7608  7608 I bluedroid-qcom: get_profile_interface a2dp
,07-26 15:21:27.798  7608  7838 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,07-26 15:21:27.804  7608  7608 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:21:27.804  7608  7608 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-26 15:21:27.806  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:27.806  7608  7837 D A2dpStateMachine: Enter Disconnected: -2
07-26 15:21:27.807  7608  7608 I BluetoothHidServiceJni: classInitNative: succeeds
07-26 15:21:27.809  7608  7608 D HidService: Received start request. Starting profile...
07-26 15:21:27.809  7608  7608 I bluedroid-qcom: get_profile_interface hidhost
07-26 15:21:27.809  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:27.809  7608  7608 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-26 15:21:27.812  7608  7608 D HealthService: Received start request. Starting profile...
,07-26 15:21:27.815  7608  7608 I bluedroid-qcom: get_profile_interface health
07-26 15:21:27.815  7608  7608 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-26 15:21:27.815  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:27.816  7608  7608 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-26 15:21:27.818  7608  7608 D PanService: Received start request. Starting profile...
07-26 15:21:27.818  7608  7608 D BluetoothPanServiceJni: initializeNative(L110): pan
07-26 15:21:27.818  7608  7608 I bluedroid-qcom: get_profile_interface pan
07-26 15:21:27.826  7608  7608 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-26 15:21:27.826  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
,07-26 15:21:27.827  7608  7608 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,07-26 15:21:27.833  7608  7608 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:21:27.834  7608  7608 D BtGatt.GattService: Received start request. Starting profile...
07-26 15:21:27.834  7608  7608 D BtGatt.GattService: start()
07-26 15:21:27.834  7608  7608 I bluedroid-qcom: get_profile_interface gatt
07-26 15:21:27.834  7608  7608 D BtGatt.AdvertiseManager: advertise manager created
07-26 15:21:27.843  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
,07-26 15:21:27.845  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:27.845  7608  7608 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-26 15:21:27.846  7608  7608 V BluetoothMapService: BluetoothMapBinder()
07-26 15:21:27.847  7608  7608 D BluetoothMapService: Received start request. Starting profile...
07-26 15:21:27.847  7608  7608 D BluetoothMapService: start()
07-26 15:21:27.854  7608  7608 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-26 15:21:27.854  7608  7608 D BluetoothMapEmailAppObserver: createReceiver()
07-26 15:21:27.855  7608  7608 D BluetoothMapEmailAppObserver: initObservers()
07-26 15:21:27.855  7608  7608 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,07-26 15:21:27.865  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:27.865  7608  7608 D HeadsetStateMachine: Proxy object connected
07-26 15:21:27.866  7608  7608 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-26 15:21:27.866  7608  7608 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-26 15:21:27.868  7608  7831 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-26 15:21:27.869  7608  7831 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-26 15:21:27.870  7608  7831 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,07-26 15:21:27.874  7608  7608 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-26 15:21:27.876  7608  7608 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:27.880  7608  7608 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-26 15:21:27.883  7608  7608 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-26 15:21:27.886  7608  7608 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-26 15:21:27.887  7608  7608 V PanService: [BTUI] SIM Extra State :ABSENT
07-26 15:21:27.890  7608  7608 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-26 15:21:27.893  7608  7608 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-26 15:21:27.894  7608  7608 V BluetoothMapService: Handler(): got msg=1
,07-26 15:21:27.898  7608  7608 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-26 15:21:27.898  7608  7608 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-26 15:21:27.899  7608  7608 V BluetoothSapReceiver: SapReceiver onReceive 
07-26 15:21:27.899  7608  7608 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:27.899  7608  7608 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-26 15:21:27.899  7608  7810 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-26 15:21:27.899  7608  7810 I bluedroid-qcom: enable
07-26 15:21:27.900  7608  7848 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-26 15:21:27.900  7608  7848 I bt-btu  : btu_task pending for preload complete event
07-26 15:21:27.901  7608  7810 I bt_hci_bdroid: init
07-26 15:21:27.904  7608  7810 I bt_vendor: bt-vendor : init
07-26 15:21:27.904  7608  7810 I bt_vendor: bt-vendor : get_bt_soc_type
07-26 15:21:27.904  7608  7810 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-26 15:21:27.904  7608  7810 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-26 15:21:27.904  7608  7810 D bt_userial_mct: userial_init
07-26 15:21:27.905  7608  7810 D bt_hci_bdroid: set_power 1
07-26 15:21:27.905  7608  7810 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-26 15:21:27.905  7608  7810 I bt_vendor: Starting hciattach daemon
07-26 15:21:27.905  7608  7810 I bt_vendor: try to set true
07-26 15:21:27.901  7854  7854 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-26 15:21:27.901  7854  7854 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-26 15:21:27.934  7855  7855 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-26 15:21:28.002  7862  7862 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-26 15:21:28.026  7863  7863 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-26 15:21:28.063  7865  7865 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-26 15:21:28.078  7866  7866 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-26 15:21:28.092  7867  7867 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-26 15:21:28.105  7868  7868 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-26 15:21:28.127  7870  7870 I libmdmdetect: ESOC framework not supported
07-26 15:21:28.131  7870  7870 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-26 15:21:28.141  7870  7870 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,07-26 15:21:28.141  7870  7870 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-26 15:21:28.141  7870  7870 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-26 15:21:28.142  7870  7870 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-26 15:21:28.142  7870  7870 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-26 15:21:28.142  7870  7870 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-26 15:21:28.142  7870  7870 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-26 15:21:28.182  7870  7871 E QC-QMI  : qmi_client [7870] 15: failed to locate client data
07-26 15:21:28.183   464   464 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-26 15:21:28.183   464   464 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,07-26 15:21:28.239  7872  7872 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-26 15:21:28.264  7873  7873 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-26 15:21:28.316  7608  7810 I bt_vendor: bluetooth satus is on
,07-26 15:21:28.326  7608  7810 D bt_hci_bdroid: preload
,07-26 15:21:28.327  7608  7853 D bt_userial_mct: userial_open(port:0)
,07-26 15:21:28.327  7608  7853 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-26 15:21:28.331  7608  7853 I bt_vendor: Done intiailizing UART
,07-26 15:21:28.336  7608  7853 I bt_vendor: Done intiailizing UART
07-26 15:21:28.336  7608  7853 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-26 15:21:28.336  7608  7853 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,07-26 15:21:28.347  7608  7848 I bt-btu  : btu_task received preload complete event
,07-26 15:21:28.349  7608  7848 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-26 15:21:28.349  7608  7848 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-26 15:21:28.356  7608  7878 D bt_userial_mct: Entering userial_read_thread()
,07-26 15:21:28.361  7608  7848 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-26 15:21:28.364  7608  7848 I         : BTE_InitTraceLevels -- TRC_HCI
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_AVDT
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_AVRC
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_A2D
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_BNEP
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_BTM
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_GAP
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_PAN
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_SDP
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_GATT
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_SMP
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-26 15:21:28.365  7608  7848 I         : BTE_InitTraceLevels -- TRC_BTIF
07-26 15:21:28.435  7608  7848 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-26 15:21:28.435  7608  7848 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0167061 
07-26 15:21:28.435  7608  7848 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0167061 
,07-26 15:21:28.453  7608  7814 E bt-btif : Calling BTA_HhEnable
07-26 15:21:28.453  7608  7814 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-26 15:21:28.454  7608  7814 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-26 15:21:28.457  7608  7848 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-26 15:21:28.457  7608  7848 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-26 15:21:28.457  7608  7848 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-26 15:21:28.457  7608  7848 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-26 15:21:28.457  7608  7848 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-26 15:21:28.459  1040  1040 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-26 15:21:28.459  1040  1040 D BluetoothManagerService: Stored Bluetooth name: G3
07-26 15:21:28.459  7608  7814 D BluetoothAdapterProperties: Name is: G3
07-26 15:21:28.461  7608  7814 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:21:28.461  7608  7814 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:28.462  7608  7814 D bt_hci_bdroid: postload
07-26 15:21:28.462  7608  7853 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:28.463  7608  7814 D bte_conf: Device ID record 1 : primary
07-26 15:21:28.463  7608  7814 D bte_conf:   vendorId            = 00c4
07-26 15:21:28.463  7608  7814 D bte_conf:   vendorIdSource      = 0001
07-26 15:21:28.463  7608  7814 D bte_conf:   product             = 13a1
07-26 15:21:28.463  7608  7814 D bte_conf:   version             = 1000
07-26 15:21:28.463  7608  7814 D bte_conf:   clientExecutableURL = 
07-26 15:21:28.463  7608  7814 D bte_conf:   serviceDescription  = 
07-26 15:21:28.463  7608  7814 D bte_conf:   documentationURL    = 
07-26 15:21:28.463  7608  7814 D bte_conf: bte_load_did_conf no section named DID2.
07-26 15:21:28.463  7608  7848 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-26 15:21:28.464  7608  7853 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:28.467  7608  7810 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-26 15:21:28.467  7608  7810 D BluetoothAdapterProperties: ScanMode =  20
07-26 15:21:28.467  7608  7810 D BluetoothAdapterProperties: State =  11
07-26 15:21:28.467  7608  7810 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,07-26 15:21:28.472  7608  7810 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-26 15:21:28.461  7880  7880 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:28.475  7608  7810 D BluetoothAdapterProperties: Setting state to 12
07-26 15:21:28.475  7608  7810 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-26 15:21:28.476  7608  7814 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-26 15:21:28.476  7608  7814 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-26 15:21:28.471  7880  7880 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:28.482  7608  7810 I BluetoothAdapterState: Entering On State
,07-26 15:21:28.492  7608  7853 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:28.493  1040  1122 D BluetoothManagerService: Message: 60
07-26 15:21:28.493  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-26 15:21:28.493  1040  1122 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
07-26 15:21:28.501  7608  7848 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:28.501  7608  7848 W bt-smp  : Plain text(LSB ~ MSB) = d2 9d 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:28.501  7608  7848 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 52 3a be 53 5b 89 5e 46 b1 1a 7b bb e2 c9 9e 
,07-26 15:21:28.504  7608  7853 D bt_hci_bdroid: Used up Tx Cmd credits
07-26 15:21:28.504  7608  7848 W bt-btm  : Stopping oneshot timer
07-26 15:21:28.505  7608  7878 E bt_mct  : hci lib postload completed
07-26 15:21:28.508  7608  7810 D LGBluetoothServiceAdapter: [BTUI] OnState
07-26 15:21:28.508  7608  7810 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-26 15:21:28.514  7608  7810 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,07-26 15:21:28.517  7608  7810 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-26 15:21:28.526  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:28.526  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:28.526  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:28.526  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:28.526  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:28.526  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:28.526  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:28.526  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:28.529  7608  7814 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:28.530  7608  7814 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-26 15:21:28.534  7608  7810 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-26 15:21:28.537  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:28.543  7608  7848 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:28.543  7608  7848 W bt-smp  : Plain text(LSB ~ MSB) = 81 27 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:28.543  7608  7848 W bt-smp  : Encrypted text(LSB ~ MSB) = 2f e4 b4 2e ee c3 15 ba b1 cc 38 45 a0 c2 bf 22 
,07-26 15:21:28.546  7608  7848 W bt-btm  : Stopping oneshot timer
07-26 15:21:28.547  6764  6892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:28.555  6764  6781 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:21:28.555  6764  6781 D BluetoothPan: onBluetoothStateChange call bindService
,07-26 15:21:28.568  7608  7848 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:28.568  7608  7848 W bt-smp  : Plain text(LSB ~ MSB) = a7 45 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:28.568  7608  7848 W bt-smp  : Encrypted text(LSB ~ MSB) = 9b 43 87 55 c5 63 a2 20 e8 61 7c 05 f0 e4 f8 26 
07-26 15:21:28.568  7608  7848 W bt-btm  : Stopping oneshot timer
,07-26 15:21:28.572  1040  1122 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:21:28.579  1040  1040 D BluetoothA2dp: Proxy object connected
07-26 15:21:28.589  7608  7848 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:28.589  7608  7848 W bt-smp  : Plain text(LSB ~ MSB) = 35 dc 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:28.589  7608  7848 W bt-smp  : Encrypted text(LSB ~ MSB) = 01 f4 3f a1 da ba a8 f9 d5 e1 99 58 44 58 7a 3f 
07-26 15:21:28.589  7608  7848 W bt-btm  : Stopping oneshot timer
,07-26 15:21:28.594  1858  1873 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:28.602  7885  7885 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,07-26 15:21:28.611  6764  6764 D BluetoothHeadset: Proxy object connected
07-26 15:21:28.611  6764  6764 D HeadsetProfile: Bluetooth service connected
07-26 15:21:28.615  6764  6764 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:28.615  6764  6764 D PanProfile: Bluetooth service connected
07-26 15:21:28.617  1858  2447 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:28.617  1858  1858 D BluetoothHeadset: Proxy object connected
,07-26 15:21:28.622  7608  7848 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-26 15:21:28.622  7608  7848 W bt-smp  : Plain text(LSB ~ MSB) = eb db 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-26 15:21:28.622  7608  7848 W bt-smp  : Encrypted text(LSB ~ MSB) = d5 a8 e3 64 81 c6 c5 ea 9c 45 01 56 09 14 f9 64 
07-26 15:21:28.622  7608  7848 W bt-btm  : Stopping oneshot timer
07-26 15:21:28.626  1858  1858 D BluetoothHeadset: Proxy object connected
07-26 15:21:28.626  1858  1874 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:28.629  1858  1858 D BluetoothHeadset: Proxy object connected
07-26 15:21:28.629  6764  6892 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:21:28.633  1040  1122 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:21:28.635  6764  6782 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:21:28.635  6764  6764 D BluetoothA2dp: Proxy object connected
07-26 15:21:28.635  6764  6764 D A2dpProfile: Bluetooth service connected
07-26 15:21:28.643  6764  6781 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-26 15:21:28.647  6764  6782 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:21:28.648  6764  6764 D BluetoothInputDevice: Proxy object connected
07-26 15:21:28.648  6764  6764 D HidProfile: Bluetooth service connected
07-26 15:21:28.653  1040  1122 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-26 15:21:28.653  1040  1122 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-26 15:21:28.656  1948  1948 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:28.657  1948  2109 D LGBluetoothAPIService: Message: 1
07-26 15:21:28.658  1948  2109 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-26 15:21:28.658  1948  2109 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
07-26 15:21:28.658  1948  2109 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-26 15:21:28.660  1607  1607 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-26 15:21:28.663  6764  6764 D BluetoothMap: Proxy object connected
07-26 15:21:28.663  6764  6764 D MapProfile: Bluetooth service connected
07-26 15:21:28.663  6764  6764 D BluetoothMap: getConnectedDevices()
07-26 15:21:28.665  7608  7625 V BluetoothMapService: getConnectedDevices()
07-26 15:21:28.666  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:28.668  7608  7608 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.668  7608  7608 D BluetoothMapService: STATE_ON
,07-26 15:21:28.673  6764  6764 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-26 15:21:28.674  6764  6764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-26 15:21:28.682  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:28.682  7608  7608 V BluetoothPbapService: Pbap Service onCreate
07-26 15:21:28.682  7608  7608 V BluetoothPbapService: Starting PBAP service
,07-26 15:21:28.685  7608  7608 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-26 15:21:28.685  7608  7608 V BluetoothMapService: Handler(): got msg=1
07-26 15:21:28.685  7608  7608 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-26 15:21:28.686  7608  7608 V BluetoothPbapService: Pbap Service onBind
07-26 15:21:28.686  7608  7608 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.686  7608  7608 V BluetoothPbapService: state: 12
07-26 15:21:28.687  7608  7608 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-26 15:21:28.687  7608  7608 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.687  6764  6764 D DockEventReceiver: finishStartingService: stopping service
07-26 15:21:28.687  7608  7608 V BluetoothPbapReceiver: ***********state = 12
07-26 15:21:28.688  6764  6764 D BluetoothPbap: Proxy object connected
07-26 15:21:28.688  6764  6764 D PbapServerProfile: Bluetooth service connected
07-26 15:21:28.689  7608  7608 V BluetoothPbapService: Handler(): got msg=1
07-26 15:21:28.690  7608  7608 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-26 15:21:28.690  7608  7903 D BluetoothMapMasInstance: MAS initSocket()
07-26 15:21:28.691  7608  7903 D BluetoothMapMasInstance:   masId = 00
07-26 15:21:28.691  7608  7903 D BluetoothMapMasInstance:   msgTypes = 0e
07-26 15:21:28.691  7608  7903 D BluetoothMapMasInstance:   masName = SMS/MMS
07-26 15:21:28.691  7608  7903 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-26 15:21:28.691  2218  2218 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-26 15:21:28.691  2218  2218 D c       : Getting all permits...
07-26 15:21:28.691  2218  2218 D a       : Opening database...
07-26 15:21:28.692  1040  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:28.693  7608  7903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:28.694  7608  7904 V BluetoothPbapService: Pbap Service initSocket
07-26 15:21:28.694  1040  1580 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:28.694  7608  7903 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
,07-26 15:21:28.695  7608  7903 V BluetoothMapMasInstance: Succeed to create listening socket 
07-26 15:21:28.695  7608  7903 D BluetoothMapMasInstance: Accepting socket connection...
07-26 15:21:28.695  2218  2218 D a       : Opening database auth.proximity.permit_store...
07-26 15:21:28.695  2218  2218 D a       : Closing database...
07-26 15:21:28.696  7608  7814 D BluetoothAdapterProperties: Scan Mode:21
07-26 15:21:28.697  7608  7814 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-26 15:21:28.697  7608  7904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:28.699  7608  7904 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-26 15:21:28.699  7608  7904 V BluetoothPbapService: Succeed to create listening socket 
07-26 15:21:28.699  7608  7904 V BluetoothPbapService: Accepting socket connection...
07-26 15:21:28.703  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:28.708  6764  6764 D BluetoothPermissionRequest: onReceive
,07-26 15:21:28.711  6764  6764 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-26 15:21:28.712  6764  6764 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-26 15:21:28.715  7608  7608 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-26 15:21:28.716  7608  7608 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-26 15:21:28.721  7608  7608 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-26 15:21:28.734  7608  7608 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-26 15:21:28.734  7608  7608 V BtOppService: onCreate
,07-26 15:21:28.737  7608  7608 V BluetoothOppNotification: send message
07-26 15:21:28.739  7608  7608 V BtOppService: Starting RfcommListener
07-26 15:21:28.742  7608  7608 D BluetoothOppPreference: Dumping Names:  
07-26 15:21:28.742  7608  7608 D BluetoothOppPreference: {}
07-26 15:21:28.742  7608  7608 D BluetoothOppPreference: Dumping Channels:  
07-26 15:21:28.742  7608  7608 D BluetoothOppPreference: {}
07-26 15:21:28.743  7608  7608 V BtOppService: onStartCommand
07-26 15:21:28.745  7608  7608 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.745  7608  7608 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,07-26 15:21:28.747  7608  7608 V BluetoothOppNotification: new notify threadi!
07-26 15:21:28.748  7608  7608 V BluetoothOppNotification: send delay message
07-26 15:21:28.749  7608  7608 V BtOppService: start RfcommListener
07-26 15:21:28.750  7608  7909 V BtOppService: Deleted complete outbound shares, number =  0
07-26 15:21:28.751  7608  7608 V BtOppService: RfcommListener started
07-26 15:21:28.752  7608  7909 V BtOppService: Deleted complete inbound failed shares, number = 0
,07-26 15:21:28.753  7608  7909 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,07-26 15:21:28.753  7608  7913 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-26 15:21:28.754  7608  7909 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a8937dd on behalf of 
07-26 15:21:28.755  7608  7913 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d604f52 on behalf of 
07-26 15:21:28.755  7608  7912 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,07-26 15:21:28.756  7608  7912 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-26 15:21:28.756  7608  7914 V BtOppRfcommListener: Starting RFCOMM listener....
07-26 15:21:28.757  1040  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:28.757  7608  7914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:28.758  7608  7914 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
07-26 15:21:28.758  7608  7914 V BtOppRfcommListener: Started RFCOMM listener....
07-26 15:21:28.758  7608  7914 I BtOppRfcommListener: Accept thread started.
07-26 15:21:28.758  7608  7914 V BtOppRfcommListener: Accepting connection...
07-26 15:21:28.759  7608  7913 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-26 15:21:28.760  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:28.760  7608  7608 V BluetoothFtpService: Ftp Service onCreate
07-26 15:21:28.760  7608  7608 I BluetoothFtpService: Ftp Service onCreate
07-26 15:21:28.760  7608  7608 V BluetoothFtpService: Ftp Service onStartCommand
07-26 15:21:28.760  7608  7608 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.760  7608  7608 V BluetoothFtpService: Starting Listening on sockets
07-26 15:21:28.761  7608  7608 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-26 15:21:28.761  7608  7608 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-26 15:21:28.761  7608  7608 V BluetoothSapReceiver: SapReceiver onReceive 
07-26 15:21:28.761  7608  7608 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.761  7608  7608 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-26 15:21:28.761  7608  7608 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-26 15:21:28.761  7608  7912 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15f7f320 on behalf of 
07-26 15:21:28.761  7608  7913 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-26 15:21:28.762  7608  7912 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-26 15:21:28.763  7608  7608 V BtOppService: ContentObserver received notification
07-26 15:21:28.763  7608  7608 V BtOppService: ContentObserver received notification
07-26 15:21:28.763  7608  7608 V BluetoothFtpService: Handler(): got msg=1
07-26 15:21:28.763  7608  7608 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-26 15:21:28.763  7608  7608 V BluetoothFtpService: Ftp Service initSocket
07-26 15:21:28.764  7608  7913 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@116674d9 on behalf of 
07-26 15:21:28.765  1040  1580 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:28.765  7608  7608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:28.766  7608  7913 V BluetoothOppNotification: outbound: succ-0  fail-0
07-26 15:21:28.768  7608  7915 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-26 15:21:28.769  7608  7915 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-26 15:21:28.770  7608  7915 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19100e9e on behalf of 
07-26 15:21:28.770  7608  7913 V BluetoothOppNotification: outbound notification was removed.
07-26 15:21:28.770  7608  7913 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-26 15:21:28.770  7608  7915 V BluetoothOppNotification: update too frequent, put in queue
07-26 15:21:28.774  7608  7608 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
07-26 15:21:28.775  7608  7915 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-26 15:21:28.775  7608  7608 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-26 15:21:28.776  7608  7913 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c7e8d7f on behalf of 
07-26 15:21:28.777  7608  7913 V BluetoothOppNotification: inbound: succ-0  fail-0
07-26 15:21:28.780  7608  7916 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,07-26 15:21:28.782  7608  7913 V BluetoothOppNotification: inbound notification was removed.
07-26 15:21:28.782  7608  7913 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-26 15:21:28.783  1040  1040 I art     : Explicit concurrent mark sweep GC freed 27657(1348KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.785ms total 148.063ms
07-26 15:21:28.783  1040  1040 D BluetoothHeadset: Proxy object connected
07-26 15:21:28.786  7608  7608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81a0051
07-26 15:21:28.786  7608  7608 V BluetoothSapService: Sap Service onCreate
07-26 15:21:28.786  1040  1040 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-26 15:21:28.786  1040  1122 D BluetoothManagerService: Message: 40
07-26 15:21:28.786  1040  1122 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-26 15:21:28.787  7608  7608 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.787  7608  7608 V BluetoothSapService: state: 12
07-26 15:21:28.787  7608  7913 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5f8829b on behalf of 
07-26 15:21:28.787  7608  7608 V BluetoothSapService: Starting SAP server process
07-26 15:21:28.789  7608  7608 V BluetoothSapService: SAP Service startRfcommListenerThread
07-26 15:21:28.781  7917  7917 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:28.781  7917  7917 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:28.794  7608  7918 V BluetoothSapService: Sap Service initRfcommSocket
,07-26 15:21:28.794  1040  1786 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-26 15:21:28.795  7608  7918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:28.795  7608  7918 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
07-26 15:21:28.795  7608  7918 V BluetoothSapService: Succeed to create listening socket 
07-26 15:21:28.795  7608  7918 V BluetoothSapService: Accepting socket connection...
07-26 15:21:28.804  7917  7917 V BT_SAP  : Event pipe created
07-26 15:21:28.805  7917  7917 V BT_SAP  : create_server_socket qcom.sap.server
07-26 15:21:28.805  7917  7917 V BT_SAP  : created socket fd 6
,07-26 15:21:29.416  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:29.416  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:29.416  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:29.416  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:29.416  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:29.416  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:29.416  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:29.416  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:29.421  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:29.424  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:29.424  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33f84a67 added. We now have 8 listener(s)
07-26 15:21:29.424  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:29.427  1040  1946 D WifiServiceImplEx: setWifiEnabled: false pid=6570, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-26 15:21:29.427  1040  1946 D WifiService: setWifiEnabled: false pid=6570, uid=10118
07-26 15:21:29.427  1040  1946 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:21:29.432  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:29.437  1040  1902 D WifiServiceImplEx: setWifiEnabled: true pid=6570, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-26 15:21:29.438  1040  1902 D WifiService: setWifiEnabled: true pid=6570, uid=10118
07-26 15:21:29.438  1040  1902 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:21:29.458  1040  1040 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-26 15:21:29.458  1040  1040 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-26 15:21:29.458  1040  1040 D Ulp_jni : JNI:system_update. Event-4
07-26 15:21:29.459  1040  1415 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-26 15:21:29.459  1040  1415 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-26 15:21:29.462  1040  1415 E WifiUtil: wfc_util_ffile_check_copy(): pid[1040] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-26 15:21:29.462  1040  1415 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-26 15:21:29.462  1040  1415 E WifiUtil: wfc_util_ffile_check_copy(): pid[1040] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-26 15:21:29.462  1040  1415 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-26 15:21:29.462  1040  1415 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-26 15:21:29.462  1040  1415 E WifiHW  : unknown target_country: EU , set to default
07-26 15:21:29.462  1040  1415 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-26 15:21:29.462  1040  1415 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-26 15:21:29.463  1040  1415 I WifiUtil: gEnableBmps=1
07-26 15:21:29.750  7608  7608 V BluetoothOppNotification: new notify threadi!
07-26 15:21:29.750  7608  7608 V BluetoothOppNotification: send delay message
,07-26 15:21:29.758  7608  7931 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-26 15:21:29.765  7608  7931 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@217d0638 on behalf of 
07-26 15:21:29.765  7608  7931 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-26 15:21:29.779  7608  7931 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-26 15:21:29.789  7608  7931 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2170e611 on behalf of 
07-26 15:21:29.789  7608  7931 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-26 15:21:29.801  7608  7931 V BluetoothOppNotification: outbound notification was removed.
07-26 15:21:29.802  7608  7931 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-26 15:21:29.815  7608  7931 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25515376 on behalf of 
07-26 15:21:29.815  7608  7931 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-26 15:21:29.838  7608  7931 V BluetoothOppNotification: inbound notification was removed.
07-26 15:21:29.847  7608  7931 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-26 15:21:29.853  7608  7931 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e52ad77 on behalf of 
,07-26 15:21:30.034   325   898 D SoftapController: Softap fwReload - Ok
07-26 15:21:30.038  1040  1415 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (572ms)
07-26 15:21:30.040   325   898 D CommandListener: Setting iface cfg
07-26 15:21:30.040   325   898 D CommandListener: Trying to bring down wlan0
07-26 15:21:30.040   325   898 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:21:30.045  1040  1122 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-26 15:21:30.045  1040  1122 D Tethering: InitialState.processMessage what=4
07-26 15:21:30.050  1040  1415 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-26 15:21:30.051  7945  7945 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:30.051  7945  7945 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-26 15:21:30.082  1040  1122 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-26 15:21:30.086  7945  7945 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-26 15:21:30.101  1040  1415 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-26 15:21:30.101  1040  1415 E WifiStateMachine: useWiFiOffloading() : false
07-26 15:21:30.101  1040  1415 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-26 15:21:30.105  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,07-26 15:21:30.105  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:30.107  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-26 15:21:30.107  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-26 15:21:30.108  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-26 15:21:30.108  6764  6764 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-26 15:21:30.113  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:30.113  1040  1040 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-26 15:21:30.113  1040  1415 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-26 15:21:30.113  1040  1415 D WifiMonitor: connecting to supplicant
07-26 15:21:30.114  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-26 15:21:30.115  6764  6764 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-26 15:21:30.116  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-26 15:21:30.116  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-26 15:21:30.116  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-26 15:21:30.116  6764  6764 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-26 15:21:30.116  6764  6764 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-26 15:21:30.118  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-26 15:21:30.118  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-26 15:21:30.118  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-26 15:21:30.118  6764  6764 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-26 15:21:30.119  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-26 15:21:30.123  7945  7945 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-26 15:21:30.123  7945  7945 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-26 15:21:30.127  6764  6764 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-26 15:21:30.127  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-26 15:21:30.127  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-26 15:21:30.127  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-26 15:21:30.127  6764  6764 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-26 15:21:30.127  6764  6764 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-26 15:21:30.172  1040  1902 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7956 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-26 15:21:30.215  7945  7945 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:30.247  7945  7945 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-26 15:21:30.253  7945  7945 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-26 15:21:30.255  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-26 15:21:30.255  1040  7975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-26 15:21:30.255  1040  7975 D WifiMonitor: Dropping event because (p2p0) is stopped
07-26 15:21:30.255  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-26 15:21:30.256  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-26 15:21:30.257  1040  1415 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-26 15:21:30.257  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:30.258  1040  1415 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:30.258  1040  1384 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3c230c40 type 2 when 167832 com.google.android.gms} when 167832
07-26 15:21:30.259  1040  1415 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:30.259  1040  1415 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:30.260  1040  1415 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-26 15:21:30.260  1040  1415 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-26 15:21:30.260  1040  1415 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-26 15:21:30.260  1040  1415 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
,07-26 15:21:30.261  1040  1415 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,07-26 15:21:30.261  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.262  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.262  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.262  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.262  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-26 15:21:30.262  1040  1415 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-26 15:21:30.262  1040  1415 E WifiStateMachine: useWiFiOffloading() : false
07-26 15:21:30.262  1040  1415 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-26 15:21:30.264  1040  1415 D WifiNative-wlan0: doBoolean: SET update_config 1
07-26 15:21:30.264  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:30.265  1948  1948 D WfdService: Waiting for WifiP2p enabling
07-26 15:21:30.266  7945  7945 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-26 15:21:30.266  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-26 15:21:30.266  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-26 15:21:30.266  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-26 15:21:30.266  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-26 15:21:30.266  1040  7975 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-26 15:21:30.266  1040  7975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-26 15:21:30.267  1040  1415 D WifiNative-wlan0: SET update_config 1: returned true
07-26 15:21:30.267  1040  1415 D WifiConfigStore: Loading config and enabling all networks 
07-26 15:21:30.267  1040  1415 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-26 15:21:30.267  1040  1415 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-26 15:21:30.269  1040  1040 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-26 15:21:30.270  1040  1449 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-26 15:21:30.277  1040  1415 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,07-26 15:21:30.279  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:30.279  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:30.279  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:30.279  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:30.279  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:30.279  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:30.279  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:30.279  6570  6570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:30.282  6570  6570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:30.290  1040  1415 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-26 15:21:30.290  1040  1415 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-26 15:21:30.334  1040  1643 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7980 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-26 15:21:30.337  1040  1415 D WifiStateMachine: enableVerboseLogging : level 2
07-26 15:21:30.337  1040  1415 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-26 15:21:30.338  1040  1415 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-26 15:21:30.338  1040  1415 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-26 15:21:30.338  1040  1415 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-26 15:21:30.338  1040  1415 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-26 15:21:30.339  1040  1415 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-26 15:21:30.339  1040  1415 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-26 15:21:30.339  1040  1415 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-26 15:21:30.339  1040  1415 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-26 15:21:30.340  1040  1415 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-26 15:21:30.340  1040  1415 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-26 15:21:30.340  1040  1415 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-26 15:21:30.340  1040  1415 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-26 15:21:30.341  1040  1415 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-26 15:21:30.341  1040  1415 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 15:21:30.341  1040  1415 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-26 15:21:30.342  1040  1415 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-26 15:21:30.342  1040  1415 D WifiNative-HAL: Setting external_sim to 1
07-26 15:21:30.342  1040  1415 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-26 15:21:30.342  1948  1948 D WfdsService: Supplicant Connection state is changed : true
07-26 15:21:30.342  1040  1415 D WifiNative-wlan0: SET external_sim 1: returned true
07-26 15:21:30.342  1948  2270 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-26 15:21:30.342  1040  1415 I WifiNative-HAL: startHal
07-26 15:21:30.342  1948  2270 D WfdsService: Set the WFDS Monitor: true
07-26 15:21:30.342  1948  2270 D WfdsMonitor: WfdsMonitorThread create
07-26 15:21:30.342  1040  1415 D wifi    : setting scan oui 0xaf6f2440
07-26 15:21:30.343  7640  7640 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.343  1948  2270 D WfdsMonitor: WFDS Monitor is created and started
07-26 15:21:30.343  1948  2270 D WfdsService: WiFi: Supplicant connection re-established
07-26 15:21:30.343  1040  1415 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 15:21:30.343  1040  1415 I WifiNative-HAL: startHal
07-26 15:21:30.343  1040  1415 D wifi    : setting scan oui 0xaf6f2440
07-26 15:21:30.343  1040  1415 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-26 15:21:30.345  1948  7993 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-26 15:21:30.346  1948  7993 E CtrlSupplicant: Succeed to open control connection
07-26 15:21:30.346  1948  7993 E CtrlSupplicant: Succeed to open monitor connection
,07-26 15:21:30.348  7956  7978 W FormManager: Network not available. Please check & try again.
07-26 15:21:30.349  1040  1415 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-26 15:21:30.349  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-26 15:21:30.350  1948  7993 D WfdsMonitor: Supplicant connection established
07-26 15:21:30.350  1948  2270 D WfdsService: Connected to the supplicant for wfds
07-26 15:21:30.350  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-26 15:21:30.353  7956  7979 V FormManager: Network unavailable.
07-26 15:21:30.355  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-26 15:21:30.355  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-26 15:21:30.355  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-26 15:21:30.355  7956  7979 V FormManager: Network unavailable.
07-26 15:21:30.355  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-26 15:21:30.355  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-26 15:21:30.356  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-26 15:21:30.356  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-26 15:21:30.356  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-26 15:21:30.356  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-26 15:21:30.356  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-26 15:21:30.356  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-26 15:21:30.357  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-26 15:21:30.357  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-26 15:21:30.357  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-26 15:21:30.357  7945  7945 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-26 15:21:30.357  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-26 15:21:30.357  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-26 15:21:30.358  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-26 15:21:30.358  1040  1415 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-26 15:21:30.359  1040  1415 E WifiNative: : [167,932,577 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-26 15:21:30.359  1040  1415 D WifiNative-wlan0: doBoolean: RECONNECT
,07-26 15:21:30.363  1040  1415 D WifiNative-wlan0: RECONNECT: returned true
07-26 15:21:30.363  1040  1415 D WifiNative-wlan0: doString: [STATUS]
07-26 15:21:30.364  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-26 15:21:30.364  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-26 15:21:30.365  1040  1415 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-26 15:21:30.365  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 1
07-26 15:21:30.365  1040  1415 D WifiNative-wlan0: SET ps 1: returned true
07-26 15:21:30.365  1040  1396 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.366  1040  1415 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-26 15:21:30.367  1040  1415 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-26 15:21:30.367   325   898 D CommandListener: Setting iface cfg
07-26 15:21:30.367   325   898 D CommandListener: Trying to bring up p2p0
07-26 15:21:30.367  1040  1396 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-26 15:21:30.367  1040  1415 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-26 15:21:30.367  1040  1396 D LGWifiP2pService: P2pEnablingState
07-26 15:21:30.367  1040  1396 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.367  1040  1396 D LGWifiP2pService: P2p socket connection successful
,07-26 15:21:30.367  1040  1396 D LGWifiP2pService: P2pEnabledState
07-26 15:21:30.368  1040  1396 D LGWifiP2pService: sending p2p connection changed broadcast
07-26 15:21:30.368  1040  1415 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-26 15:21:30.368  1040  1396 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-26 15:21:30.368  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=167942  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-26 15:21:30.368  1040  1396 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-26 15:21:30.368  1040  1396 D WifiNative-p2p0: doBoolean: SET device_name G3
07-26 15:21:30.369  1040  1396 D WifiNative-p2p0: SET device_name G3: returned true
07-26 15:21:30.369  1040  1396 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-26 15:21:30.369  1040  1396 D LGWifiP2pService: before postfix = G3
07-26 15:21:30.369  1040  1396 D WifiServerServiceExt: postfix byte check : 2
07-26 15:21:30.369  1040  1396 D LGWifiP2pService: after postfix = G3
07-26 15:21:30.369  1040  1396 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-26 15:21:30.369  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=167943  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-26 15:21:30.369  1040  1396 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-26 15:21:30.369  1040  1396 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-26 15:21:30.369  1040  1396 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-26 15:21:30.369  1040  1396 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-26 15:21:30.369  1040  1415 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-26 15:21:30.370  1040  1396 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-26 15:21:30.370  1040  1396 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-26 15:21:30.370  1040  1415 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-26 15:21:30.370  1040  1396 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-26 15:21:30.370  1040  1396 D WifiNative-HAL: p2pGetDeviceAddress
07-26 15:21:30.370  1040  1396 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-26 15:21:30.370  1040  1415 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-26 15:21:30.370  1040  1415 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-26 15:21:30.370  7945  7945 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-26 15:21:30.370  1040  1396 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-26 15:21:30.370  1040  1396 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-26 15:21:30.371  1040  1396 D WifiNative-p2p0: P2P_FLUSH: returned true
07-26 15:21:30.372  1948  1948 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-26 15:21:30.372  1948  1948 D WfdsService: WifiP2pState is changed : true
07-26 15:21:30.372  1948  2270 D WfdsService: Receive the WFDS_ENABLE Method
07-26 15:21:30.372  1948  2270 D WfdsService: Set the WFDS Monitor: true
07-26 15:21:30.372  1948  2270 D WfdsService: Connected to the supplicant for wfds
07-26 15:21:30.372  1948  2270 D WfdsJNI : doCommand: WFDS_SET TRUE
07-26 15:21:30.372  7945  7945 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-26 15:21:30.372  1948  2270 D WfdsService: selectPreferredScanChannel [36]
07-26 15:21:30.372  1948  2270 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-26 15:21:30.373  1948  1948 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-26 15:21:30.373  1948  1948 D WfdsService: isConnected: false
07-26 15:21:30.374  1040  1396 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-26 15:21:30.374  1040  1040 D WifiScanningService: SCAN_AVAILABLE : 3
07-26 15:21:30.374  1040  1040 D RttService: SCAN_AVAILABLE : 3
07-26 15:21:30.374  1040  1396 D WifiNative-p2p0: P2P_SERVIC,E_FLUSH: returned true
07-26 15:21:30.374  1040  1396 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-26 15:21:30.374  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.374  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.374  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-26 15:21:30.375  1040  1396 D WifiNative-p2p0:    returned OK
07-26 15:21:30.375  1040  1396 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-26 15:21:30.376  1040  1561 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.376  1040  1561 I WifiNative-HAL: startHal
07-26 15:21:30.376  1040  1562 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.376  1040  1396 D WifiNative-p2p0: SAVE_CONFIG: returned false
07-26 15:21:30.376  1040  1396 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-26 15:21:30.377  1040  1561 D wifi    : getting scan capabilities on interface[1] = 0xaf6f2440
07-26 15:21:30.377  1040  1561 D wifi    : failed to get capabilities : -3
07-26 15:21:30.377  1040  1561 E WifiScanningService: could not get scan capabilities
,07-26 15:21:30.380  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:30.380  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:30.381  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:30.382  1948  1948 I WfdStateTracker: handleP2pThisDeviceChanged
07-26 15:21:30.382  1948  1948 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-26 15:21:30.382  1948  1948 D WfdsService: Update P2p Interface State: 3
07-26 15:21:30.385  1040  1415 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-26 15:21:30.385  1040  1396 D LGWifiP2pService: InactiveState
07-26 15:21:30.385  1040  1415 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-26 15:21:30.385  1040  1396 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.385  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.385  1040  1396 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-26 15:21:30.385  1040  1415 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-26 15:21:30.385  1040  1415 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-26 15:21:30.386  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-26 15:21:30.386  7945  7945 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:30.386  1040  7975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-26 15:21:30.387  1040  7975 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:30.387  1040  7975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:30.387  1040  7975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:30.387  7945  7945 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-26 15:21:30.387  7945  7945 E wpa_supplicant: disconnect_rssi_lvl: -100
07-26 15:21:30.387  7945  7945 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.387  1040  1415 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
,07-26 15:21:30.388  1948  7993 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,07-26 15:21:30.388  7945  7945 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.388  1948  7993 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:30.388  1948  7993 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:30.388  1040  1415 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-26 15:21:30.388  1040  1415 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-26 15:21:30.388  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-26 15:21:30.388  1040  1396 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  7975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  7975 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  7975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-26 15:21:30.389  1040  7975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  7975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:30.389  1040  7975 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-26 15:21:30.389  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  7975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.389  1040  7975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  1040 E WifiServerServiceExt: No p2p device connected
,07-26 15:21:30.389  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.389  1040  1396 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.390  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-26 15:21:30.390  7945  7945 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:30.390  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-26 15:21:30.390  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:30.391  1040  7975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,07-26 15:21:30.391  1040  7975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-26 15:21:30.391  7945  7945 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-26 15:21:30.391  1948  2270 W WfdsService: DefaultState - msg [9441285] is not handled
07-26 15:21:30.391  7945  7945 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.391  1948  7993 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:30.391  1040  7975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:30.391  1040  7975 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.391  1040  7975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-26 15:21:30.391  1040  7975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.391  7945  7945 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.392  1948  7993 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:30.392  1040  7975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-26 15:21:30.392  1040  7975 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.392  1040  7975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.392  1040  7975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-26 15:21:30.394  1040  1786 I ActivityManager: Killing 7052:com.android.chrome/u0a57 (adj 15): empty #17
,07-26 15:21:30.396  1040  1415 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-26 15:21:30.396  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.396  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.397  1040  1415 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-26 15:21:30.398  1040  1415 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-26 15:21:30.399  1040  1415 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-26 15:21:30.399  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-26 15:21:30.399  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-26 15:21:30.399  7945  7945 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-26 15:21:30.400  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-26 15:21:30.400  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-26 15:21:30.400  1040  7975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-26 15:21:30.400  1040  7975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-26 15:21:30.400  1040  1415 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-26 15:21:30.400  1040  1415 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-26 15:21:30.401  1040  1415 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-26 15:21:30.401  1040  1415 D WifiNative-wlan0: doBoolean: SCAN
07-26 15:21:30.401  1040  1415 D WifiNative-wlan0: SCAN: returned false
07-26 15:21:30.402  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=167976  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-26 15:21:30.421  7980  7980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-26 15:21:30.437  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:30.438  1040  1643 W libprocessgroup: failed to open /acct/uid_10057/pid_7052/cgroup.procs: No such file or directory
,07-26 15:21:30.441  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=168015  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-26 15:21:30.442  1040  1415 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:30.442  1040  1415 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:30.442  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:30.442  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:30.442  1040  1415 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:30.442  1040  1415 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:30.443  1040  1415 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-26 15:21:30.443  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.443  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.443  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-26 15:21:30.444  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:30.444  1040  1040 D WifiServerServiceExt: setSupplicantStateSCANNING
07-26 15:21:30.444  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:30.447  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:30.448  1040  1055 I ActivityManager: Killing 7073:com.lge.drmservice/u0a62 (adj 15): empty #17
,07-26 15:21:30.473  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:30.473  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:30.473  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:30.473  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:30.473  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:30.473  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:30.473  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:30.473  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:30.477  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:30.485  6570  6636 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-26 15:21:30.486  6570  6636 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-26 15:21:30.490  1040  1946 W libprocessgroup: failed to open /acct/uid_10062/pid_7073/cgroup.procs: No such file or directory
07-26 15:21:30.491  6570  6636 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2adeacbc Bundle[{}]
07-26 15:21:30.493  6570  6636 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 15:21:30.493  6570  6636 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-26 15:21:30.494  6570  6636 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-26 15:21:30.496  6570  6636 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-26 15:21:30.497  6570  6636 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-26 15:21:30.498  6570  6636 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-26 15:21:30.511  6570  6636 I System.out: Running OutgoingSocketThread
,07-26 15:21:30.515  6570  8001 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
,07-26 15:21:30.516  6570  8001 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45752
07-26 15:21:30.516  6570  8001 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
07-26 15:21:30.521   325  8003 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-26 15:21:30.521  1040  1120 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-26 15:21:30.524  7980  7980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-26 15:21:30.529  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:30.533  7956  8005 W FormManager: Network not available. Please check & try again.
07-26 15:21:30.537  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-26 15:21:30.546  7956  8006 V FormManager: Network unavailable.
07-26 15:21:30.553  7956  8006 V FormManager: Network unavailable.
,07-26 15:21:30.557  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-26 15:21:30.558  4331  4331 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-26 15:21:30.563  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:30.567  4331  4331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-26 15:21:30.576  4331  8007 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-26 15:21:30.579  4331  8008 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-26 15:21:30.579  4331  8008 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-26 15:21:30.625  1040  1580 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8009 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-26 15:21:30.740  8009  8009 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-26 15:21:30.740  8009  8009 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-26 15:21:30.749  8009  8009 V [BNRBootReceiver]: Boot Receiver Return
,07-26 15:21:30.751  8009  8009 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-26 15:21:30.828  1040  2051 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8027 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-26 15:21:30.829  1040  2051 I ActivityManager: Killing 7090:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,07-26 15:21:30.837  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-26 15:21:30.837  7945  7945 E wpa_supplicant: USIM:  scard_init function
07-26 15:21:30.837  1040  7975 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-26 15:21:30.838  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-26 15:21:30.838  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
07-26 15:21:30.838  1040  7975 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-26 15:21:30.838  7945  7945 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-26 15:21:30.839  1040  1415 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-26 15:21:30.839  1040  1415 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-26 15:21:30.839  1040  1415 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-26 15:21:30.840  1040  1415 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-26 15:21:30.840  1040  1415 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-26 15:21:30.840  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-26 15:21:30.840  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-26 15:21:30.887  1040  1983 W libprocessgroup: failed to open /acct/uid_10085/pid_7090/cgroup.procs: No such file or directory
,07-26 15:21:30.888  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=168462  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-26 15:21:30.897  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=168471  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-26 15:21:30.897  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:30.897  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:30.898  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.898  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.898  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-26 15:21:30.899  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:30.901  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:30.901  1040  1040 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,07-26 15:21:30.920  8027  8027 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-26 15:21:30.942  8027  8027 D PluginManager: init()
,07-26 15:21:30.964  7945  7945 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-26 15:21:30.964  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-26 15:21:30.964  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-26 15:21:30.964  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-26 15:21:30.964  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-26 15:21:30.965  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=168539  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,07-26 15:21:30.965  1040  1122 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-26 15:21:30.965  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=168539  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-26 15:21:30.966  1040  1415 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:30.966  1040  1415 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:30.967  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:30.967  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-26 15:21:30.967  1040  1415 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:30.968  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:30.968  1040  1040 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-26 15:21:30.968  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:30.969  1040  1415 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-26 15:21:30.969  1040  1415 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168543
07-26 15:21:30.970  1040  1415 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168544
07-26 15:21:30.970  1040  1415 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168544
07-26 15:21:30.970  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168544
07-26 15:21:30.971  1040  1415 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168545
07-26 15:21:30.971  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=168545  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-26 15:21:30.973  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:30.973  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:30.974  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:30.974  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.974  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.974  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-26 15:21:30.975  7945  7945 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-26 15:21:30.976  7945  7945 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-26 15:21:30.976  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=168549  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-26 15:21:30.977  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.977  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.977  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,07-26 15:21:30.977  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:30.978  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-26 15:21:30.978  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:30.978  1040  1040 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-26 15:21:30.978  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-26 15:21:30.979  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-26 15:21:30.979  1040  7975 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-26 15:21:30.979  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-26 15:21:30.979  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-26 15:21:30.979  1040  7975 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-26 15:21:30.979  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:30.979  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-26 15:21:30.980  1040  1415 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=168554  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-26 15:21:30.981  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=168555  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-26 15:21:30.982  1040  1415 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=168556
,07-26 15:21:30.982  1040  1415 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=168556
07-26 15:21:30.983  1040  1415 D WifiNative-wlan0: doString: [STATUS]
07-26 15:21:30.984  1040  7975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-26 15:21:30.984  1040  7975 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-26 15:21:30.984  1040  1415 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-26 15:21:30.986  1040  1415 I WifiServiceExtension: setVHTCapabilityType  : false
07-26 15:21:30.991  1040  1415 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-26 15:21:30.991  1040  1415 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-26 15:21:30.994  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.994  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:30.995  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-26 15:21:30.996  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:30.996  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:30.997  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:31.000  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:31.000  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-26 15:21:31.001  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.001  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.001  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-26 15:21:31.002  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:31.008  1040  1415 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-26 15:21:31.009  1040  1415 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:31.009  1040  1415 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-26 15:21:31.009  1040  1477 D ConnectivityService: Got NetworkAgent Messenger
07-26 15:21:31.009  1040  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-26 15:21:31.009  1040  1477 D ConnectivityService: NetworkAgent connected
07-26 15:21:31.014  1040  1415 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-26 15:21:31.014  1040  1415 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-26 15:21:31.017  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:31.017  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:31.018  1040  1415 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-26 15:21:31.018  1040  1415 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:31.018  1040  1415 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-26 15:21:31.018  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:31.018  1040  1415 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-26 15:21:31.018  1040  1415 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-26 15:21:31.021  1040  1415 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-26 15:21:31.024   325   898 D CommandListener: Setting iface cfg
07-26 15:21:31.027  1040  1415 E WifiStateMachine: Start Dhcp Watchdog 3
07-26 15:21:31.027  1040  8045 D DhcpStateMachine: StoppedState
07-26 15:21:31.027  1040  8045 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:31.027  1040  8045 D DhcpStateMachine: WaitBeforeStartState
07-26 15:21:31.028  1040  1415 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=168601  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:31.028  1040  1415 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=168602  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:31.028  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=168602  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:31.029  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:31.029  1040  1040 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-26 15:21:31.029  1040  1415 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=168603  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:31.030  1040  1415 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=168604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:31.030  1040  1415 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=168604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-26 15:21:31.031  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13830] from screen [on:0 period:660475799] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-26 15:21:31.032  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:660475800] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-26 15:21:31.032  1040  1415 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-26 15:21:31.036  1040  1477 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,07-26 15:21:31.037  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:31.037  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:31.038  1040  1415 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:31.038  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:31.038  1040  1415 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:31.038  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:31.039  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-26 15:21:31.040  1040  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-26 15:21:31.040  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=176,0,0
07-26 15:21:31.040  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=176,0,0
07-26 15:21:31.040  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-26 15:21:31.041  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-26 15:21:31.041  1040  1415 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-26 15:21:31.041  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 0
07-26 15:21:31.041  1040  1415 D WifiNative-wlan0: SET ps 0: returned true
07-26 15:21:31.042  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-26 15:21:31.042  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-26 15:21:31.042  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-26 15:21:31.042  1040  1415 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-26 15:21:31.042  1040  1415 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-26 15:21:31.042  1040  1396 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f8f981b target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:31.042  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f8f981b target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:31.042  1040  1415 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-26 15:21:31.042  1040  8045 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:31.042  1040  8045 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-26 15:21:31.043   325   898 D CommandListener: Setting iface cfg
07-26 15:21:31.043   325   898 D CommandListener: Trying to bring up wlan0
07-26 15:21:31.044  1040  1415 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,07-26 15:21:31.045  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-26 15:21:31.045  1040  1040 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-26 15:21:31.046  1040  1040 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,07-26 15:21:31.046  1040  1040 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-26 15:21:31.046  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
07-26 15:21:31.046  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
07-26 15:21:31.046  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-26 15:21:31.046  1040  1396 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:31.046  1040  1396 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:31.047  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-26 15:21:31.047  1040  1415 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-26 15:21:31.047  1040  1415 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-26 15:21:31.047  7945  7945 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-26 15:21:31.048  1040  1415 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-26 15:21:31.048  1040  1415 D WifiNative-wlan0: doBoolean: SET ps 1
07-26 15:21:31.092  1040  1415 D WifiNative-wlan0: SET ps 1: returned true
,07-26 15:21:31.095  1040  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-26 15:21:31.097  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:31.098  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:31.099  1040  1415 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:31.100  1040  1415 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:31.102  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:31.103  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-26 15:21:31.104  1040  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-26 15:21:31.106  1040  1415 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,07-26 15:21:31.107  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-26 15:21:31.107  1040  1415 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-26 15:21:31.108  1040  1477 D ConnectivityService: ignoring duplicate network state non-change
07-26 15:21:31.112  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:31.112  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-26 15:21:31.113  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:31.118  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.118  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.118  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-26 15:21:31.120  1040  1477 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-26 15:21:31.120  1040  1477 D ConnectivityService: Adding iface wlan0 to network 102
,07-26 15:21:31.130  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.130  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.130  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-26 15:21:31.130  1040  1040 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-26 15:21:31.131  1948  1948 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-26 15:21:31.134  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:31.134  1607  1607 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-26 15:21:31.135  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:31.137  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:31.137  1607  1607 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-26 15:21:31.137  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:31.139  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.139  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.139  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-26 15:21:31.141  1040  1415 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-26 15:21:31.142  1040  1040 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-26 15:21:31.146  1040  1040 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.146  1040  1040 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:31.147  1040  1040 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,07-26 15:21:31.158  1040  1477 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-26 15:21:31.158  1040  1477 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-26 15:21:31.159  1040  1477 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-26 15:21:31.160   325   898 E Netd    : netlink response contains error (File exists)
07-26 15:21:31.160  1607  1607 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:31.160  1040  1477 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-26 15:21:31.161  1607  1607 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-26 15:21:31.161  1040  1477 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-26 15:21:31.161  1040  1477 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
07-26 15:21:31.161  1040  1477 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-26 15:21:31.161  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-26 15:21:31.162  1040  1477 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-26 15:21:31.162  1040  1477 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-26 15:21:31.162  1040  1477 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-26 15:21:31.162  1040  1477 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-26 15:21:31.163  1040  1477 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:31.163  1040  1477 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:31.163  1040  1477 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-26 15:21:31.163  1040  1477 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:31.163  1040  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:31.163  1040  1477 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-26 15:21:31.163  1040  1477 D ConnectivityService: currentScore = 0, newScore = 20
07-26 15:21:31.163  1040  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-26 15:21:31.163  1040  1477 D ConnectivityService:    accepting network in place of null
07-26 15:21:31.163  1040  1477 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:31.163  1040  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:31.163  1040  8044 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-26 15:21:31.164  1040  1415 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:31.164  1040  1415 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:31.165  1858  1858 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:31.165  1858  1858 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specif,ier: <-1>]
07-26 15:21:31.166  1040  1477 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-26 15:21:31.166  1040  1477 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-26 15:21:31.166  1040  1477 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:31.166  1040  1477 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:31.166  1040  1477 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-26 15:21:31.167  1040  1477 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-26 15:21:31.168  1040  1040 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-26 15:21:31.168  1040  1040 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-26 15:21:31.168  1040  1040 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-26 15:21:31.168  1040  1040 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-26 15:21:31.169   325  8049 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-26 15:21:31.169   325  8049 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,07-26 15:21:31.170  1040  1477 D ConnectivityService: validation of new default Network = false
07-26 15:21:31.170  1040  1477 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-26 15:21:31.170  1040  1477 D DSQN    : enableDataServiceNotify 
07-26 15:21:31.170  1040  1477 D DSQN    : start dsqn bin
07-26 15:21:31.178  1040  1477 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-26 15:21:31.178  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:31.178  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:31.178  1040  1395 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-26 15:21:31.178  1040  1477 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:31.179  1607  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-26 15:21:31.171  8050  8050 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:31.171  8050  8050 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:31.190  8050  8050 E DSQN    : DSQN ssw
,07-26 15:21:31.202  1607  1607 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-26 15:21:31.202  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-26 15:21:31.203  1607  1607 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-26 15:21:31.245  1040  8045 D DhcpStateMachine: DHCPV4 request on wlan0
,07-26 15:21:31.246  1040  8045 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,07-26 15:21:31.247  1040  8045 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-26 15:21:31.241  8054  8054 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:31.241  8054  8054 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-26 15:21:31.273  8054  8054 I dhcpcd  : version 5.5.6 starting
,07-26 15:21:31.278  8054  8054 E dhcpcd  : get_duid: m
07-26 15:21:31.278  8054  8054 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-26 15:21:31.278  8054  8054 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-26 15:21:31.324  8027  8027 W ExternalStrings: load override strings
07-26 15:21:31.324  8027  8027 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-26 15:21:31.324  8027  8027 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,07-26 15:21:31.326  8027  8027 D StatusProvider: onCreate
,07-26 15:21:31.363  8027  8027 V Signer  : override build config not found
07-26 15:21:31.363  8027  8027 D Signer  : value of property debug is false
,07-26 15:21:31.372  8054  8054 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-26 15:21:31.372  8054  8054 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-26 15:21:31.372  8054  8054 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-26 15:21:31.372  8054  8054 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-26 15:21:31.372  8054  8054 D dhcpcd  : wlan0: sending REQUEST (xid 0x895ca4fc), next in 4.25 seconds
07-26 15:21:31.386  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
07-26 15:21:31.386  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,07-26 15:21:31.386  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-26 15:21:31.387  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-26 15:21:31.387  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-26 15:21:31.387  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-26 15:21:31.387  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-26 15:21:31.387  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
07-26 15:21:31.387  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-26 15:21:31.388  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-26 15:21:31.388  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-26 15:21:31.388  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
07-26 15:21:31.388  8027  8027 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
07-26 15:21:31.395  8027  8027 V LGMDMManager: Create singleton instance
07-26 15:21:31.410  8054  8054 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-26 15:21:31.431  8027  8027 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,07-26 15:21:31.444  8054  8054 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-26 15:21:31.445  8054  8054 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-26 15:21:31.445  8054  8054 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-26 15:21:31.446  8054  8054 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-26 15:21:31.447  8054  8054 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,07-26 15:21:31.448  8054  8054 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-26 15:21:31.448  8054  8054 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-26 15:21:31.448  8054  8054 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-26 15:21:31.513  6570  6636 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
07-26 15:21:31.513  6570  6636 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 852)
07-26 15:21:31.513  6570  6636 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 852)
07-26 15:21:31.513  6570  6636 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
,07-26 15:21:31.521  6570  6636 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 857)
07-26 15:21:31.521  6570  6636 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 857)
07-26 15:21:31.521  6570  6636 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
07-26 15:21:31.522  6570  6636 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 858)
07-26 15:21:31.525  6570  6636 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 860)
07-26 15:21:31.528  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.528  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a0d4014 added. We now have 2 listener(s)
07-26 15:21:31.528  1040  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.532  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:31.532  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.532  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.532  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:31.532  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a290bd added. We now have 9 listener(s)
07-26 15:21:31.532  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:31.532  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:21:31.538  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:31.542  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:31.542  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:31.542  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:31.542  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:31.542  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:31.542  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.542  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:31.542  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:31.544  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.544  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:31.544  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.544  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37352603 added. We now have 3 listener(s)
07-26 15:21:31.544  1040  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.547  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:31.548  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:31.548  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.548  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.548  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:31.548  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c884980 added. We now have 10 listener(s)
07-26 15:21:31.548  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:31.549  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:31.549  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:31.549  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:31.549  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:31.549  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.549  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:31.549  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:31.549  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a0d4014 removed from the list
07-26 15:21:31.549  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.549  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a290bd removed from the list
07-26 15:21:31.551  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:31.551  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:31.551  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.551  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.551  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.552  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:31.552  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:31.552  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.552  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a290bd not in the list
07-26 15:21:31.552  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.552  6570  6636 D org.thaliproject.p2p.btc,onnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.553  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:31.553  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:31.553  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.553  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c884980 removed from the list
07-26 15:21:31.553  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:31.553  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.553  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.553  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:31.553  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37352603 removed from the list
07-26 15:21:31.554  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.554  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56c7bb9 added. We now have 2 listener(s)
07-26 15:21:31.555  1040  1055 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.557  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:31.557  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.557  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.557  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:31.557  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f93bfe added. We now have 9 listener(s)
07-26 15:21:31.557  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:31.558  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:21:31.560  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:31.566  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:31.566  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:31.566  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:31.566  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:31.566  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:31.566  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.566  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:31.566  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:31.567  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.568  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:31.570  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:31.574  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:31.577  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.577  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e87dac added. We now have 3 listener(s)
07-26 15:21:31.578  1040  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.581  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:31.586  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:31.596  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:31.596  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.596  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.596  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:31.596  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28501a75 added. We now have 10 listener(s)
07-26 15:21:31.596  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:31.596  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:31.596  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:31.596  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:31.596  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 15:21:31.600  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:21:31.603  1040  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.603  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-26 15:21:31.608  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:21:31.608  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:21:31.609  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:31.610  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:21:31.610  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:31.611  6570  6636 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:31.611  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:31.611  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:31.613  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:31.613  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:31.613  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:31.613  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:31.613  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.613  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:31.613  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:31.613  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56c7bb9 removed from the list
07-26 15:21:31.613  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.614  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f93bfe removed from the list
07-26 15:21:31.614  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:31.614  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.614  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.614  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.615  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:31.615  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:31.615  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.615  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f93bfe not in the list
07-26 15:21:31.615  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.615  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.616  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:31.617  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:31.617  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:31.617  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:31.617  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.617  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryM,anagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28501a75 removed from the list
07-26 15:21:31.617  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:31.618  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.618  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.618  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:31.618  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e87dac removed from the list
07-26 15:21:31.619  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.619  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2635c898 added. We now have 2 listener(s)
07-26 15:21:31.650  1040  1055 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8090 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-26 15:21:31.651  1040  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.653  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:31.653  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.653  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.654  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:31.654  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2594e8f1 added. We now have 9 listener(s)
07-26 15:21:31.654  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:31.655  1040  1055 I ActivityManager: Killing 7116:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,07-26 15:21:31.656  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:21:31.758  8027  8077 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-26 15:21:31.853  1040  8045 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-26 15:21:31.857  1040  8045 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,07-26 15:21:31.858  1040  8045 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-26 15:21:31.858  1040  8045 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-26 15:21:31.859  1040  8045 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-26 15:21:31.859  1040  8045 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-26 15:21:31.859  1040  8045 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-26 15:21:31.859  1040  8045 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,07-26 15:21:31.861  1040  8045 D DhcpStateMachine: RunningState
,07-26 15:21:31.886  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:31.886  1040  1983 W libprocessgroup: failed to open /acct/uid_10093/pid_7116/cgroup.procs: No such file or directory
,07-26 15:21:31.893  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:31.893  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:31.893  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:31.893  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:31.893  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:31.893  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.893  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:31.893  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:31.895  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.896  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:31.896  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.896  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c929b57 added. We now have 3 listener(s)
,07-26 15:21:31.907  1040  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-26 15:21:31.913  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:31.916  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:31.916  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.916  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.917  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:31.917  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@120ad644 added. We now have 10 listener(s)
07-26 15:21:31.917  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:31.917  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:21:31.918  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:31.918  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:31.918  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:31.918  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:21:31.922  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:31.929  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:21:31.929  1040  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-26 15:21:31.934  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:21:31.934  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:21:31.937  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-26 15:21:31.939  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:31.941  6570  6636 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:31.941  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:31.941  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:31.941  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:31.941  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:31.941  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.941  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:31.941  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:31.941  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2635c898 removed from the list
07-26 15:21:31.941  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.941  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2594e8f1 removed from the list
07-26 15:21:31.941  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:31.941  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.942  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.942  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.942  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:31.942  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:31.943  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.943  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2594e8f1 not in the list
07-26 15:21:31.943  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.943  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.943  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:31.944  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:31.944  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:31.944  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:31.944  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.944  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@120ad644 removed from the list
07-26 15:21:31.944  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:31.944  6570  6636 W org.thaliproject.p2,p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.944  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.944  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:31.944  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c929b57 removed from the list
07-26 15:21:31.945  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.945  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d3b95f3 added. We now have 2 listener(s)
07-26 15:21:31.945  1040  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.948  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:31.948  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.948  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.948  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:31.948  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@270112b0 added. We now have 9 listener(s)
07-26 15:21:31.948  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:31.949  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:21:31.949  8090  8090 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-26 15:21:31.953  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:31.957  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:31.957  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:31.957  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:31.957  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:31.957  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:31.957  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.957  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:31.957  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:31.958  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.958  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:31.959  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.959  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2beaa0ae added. We now have 3 listener(s)
07-26 15:21:31.959  1040  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.962  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,07-26 15:21:31.962  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.962  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.962  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:31.962  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@246f9e4f added. We now have 10 listener(s)
07-26 15:21:31.962  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:31.962  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:31.962  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:31.962  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:31.962  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:21:31.963  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:31.966  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:21:31.967  1040  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.967  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:31.971  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:21:31.971  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:21:31.973  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:21:31.973  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:31.975  6570  6636 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:31.977  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:31.977  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:31.977  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:21:31.977  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:31.977  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.977  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:31.977  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:31.977  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d3b95f3 removed from the list
07-26 15:21:31.977  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.977  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@270112b0 removed from the list
07-26 15:21:31.977  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:31.977  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.978  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.978  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.979  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:31.979  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:31.979  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.979  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@270112b0 not in the list
07-26 15:21:31.979  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.979  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.980  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:31.981  6570  6636 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:31.981  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:31.981  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:31.981  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:31.981  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@246f9e4f removed from the list
07-26 15:21:31.981  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:31.981  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:31.981  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.981  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:31.981  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2beaa0ae removed from the list
07-26 15:21:31.982  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.982  6570  6636 V org.thaliproject.p2p.btconnectorlib.Connection,ManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ec419ba added. We now have 2 listener(s)
07-26 15:21:31.982  1040  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.985  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:31.985  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.985  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.985  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:31.985  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@931d06b added. We now have 9 listener(s)
07-26 15:21:31.985  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:31.985  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:21:31.988  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:31.993  6570  6636 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:31.993  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:31.993  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:31.993  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:31.993  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:31.993  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.993  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:31.993  6570  6636 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:31.996  6570  6636 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:31.996  6570  6636 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:31.997  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:31.997  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a60f061 added. We now have 3 listener(s)
07-26 15:21:31.997  1040  1056 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-26 15:21:31.999  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:31.999  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-26 15:21:31.999  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:31.999  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:31.999  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:31.999  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a1786 added. We now have 10 listener(s)
07-26 15:21:31.999  6570  6636 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:32.000  6570  6636 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:32.000  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:32.000  6570  6636 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:32.000  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.000  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.000  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:32.000  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.000  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ec419ba removed from the list
07-26 15:21:32.000  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.000  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@931d06b removed from the list
07-26 15:21:32.000  6570  6570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:32.001  6570  6636 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:32.001  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:31.999  8090  8090 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-26 15:21:32.001  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.001  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.002  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.002  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.002  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.002  6570  6636 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@931d06b not in the list
07-26 15:21:32.002  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener ,does not exist in the list - probably already removed
07-26 15:21:32.002  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.003  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.003  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.003  6570  6636 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.003  6570  6636 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a1786 removed from the list
07-26 15:21:32.003  6570  6636 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.003  6570  6636 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.003  6570  6636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.003  6570  6636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.003  6570  6636 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a60f061 removed from the list
07-26 15:21:32.004  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-26 15:21:32.004  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-26 15:21:32.005  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-26 15:21:32.005  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-26 15:21:32.005  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-26 15:21:32.005  6570  6636 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:32.015  6570  8122 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: My test thread name)
07-26 15:21:32.015  6570  8122 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 866, thread name: My test thread name)
07-26 15:21:32.015  6570  8122 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 866, name: My test thread name)
07-26 15:21:32.018  6570  8123 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: My test thread name)
07-26 15:21:32.018  6570  8123 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 868, thread name: My test thread name)
07-26 15:21:32.018  6570  8123 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: My test thread name)
,07-26 15:21:32.020  6570  6636 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 84
07-26 15:21:32.020  6570  6636 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 84
07-26 15:21:32.020  6570  6636 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-26 15:21:32.020  6570  6636 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-26 15:21:32.020  6570  6636 D com.test.thalitest.ThaliTestRunner: Total duration: 23247 ms
07-26 15:21:32.021  6570  6636 I jxcore-log: Total number of executed tests:  84
07-26 15:21:32.021  6570  6636 I jxcore-log: 
07-26 15:21:32.021  6570  6636 I jxcore-log: Number of passed tests:  84
07-26 15:21:32.021  6570  6636 I jxcore-log: 
07-26 15:21:32.021  6570  6636 I jxcore-log: Number of failed tests:  0
07-26 15:21:32.021  6570  6636 I jxcore-log: 
07-26 15:21:32.022  6570  6636 I jxcore-log: Number of ignored tests:  0
07-26 15:21:32.022  6570  6636 I jxcore-log: 
07-26 15:21:32.022  6570  6636 I jxcore-log: Total duration:  23247
07-26 15:21:32.022  6570  6636 I jxcore-log: 
07-26 15:21:32.028  6570  6570 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Unsupported return type."", source: file:///android_asset/www/js/thali_main.js (57)
07-26 15:21:32.029  6570  6570 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-26 15:21:32.030  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.030  6570  6636 I jxcore-log: 
07-26 15:21:32.035  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.035  6570  6636 I jxcore-log: 
07-26 15:21:32.036  1040  1643 I ActivityManager: Killing 7175:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-26 15:21:32.037  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.037  6570  6636 I jxcore-log: 
07-26 15:21:32.038  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.038  6570  6636 I jxcore-log: 
07-26 15:21:32.039  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.039  6570  6636 I jxcore-log: 
07-26 15:21:32.040  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-26 15:21:32.040  6570  6636 I jxcore-log: 
07-26 15:21:32.043  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:21:32.043  6570  6636 I jxcore-log: 
,07-26 15:21:32.046  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.046  6570  6636 I jxcore-log: 
07-26 15:21:32.047  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.047  6570  6636 I jxcore-log: 
07-26 15:21:32.047  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.047  6570  6636 I jxcore-log: 
07-26 15:21:32.048  8090  8090 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-26 15:21:32.049  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.049  6570  6636 I jxcore-log: 
07-26 15:21:32.049  8090  8090 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-26 15:21:32.049  8090  8090 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-26 15:21:32.049  8090  8090 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-26 15:21:32.049  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.049  6570  6636 I jxcore-log: 
07-26 15:21:32.050  8090  8090 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-26 15:21:32.051  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.051  6570  6636 I jxcore-log: 
07-26 15:21:32.051  8090  8090 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-26 15:21:32.052  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.052  6570  6636 I jxcore-log: 
07-26 15:21:32.053  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.053  6570  6636 I jxcore-log: 
07-26 15:21:32.053  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.053  6570  6636 I jxcore-log: 
07-26 15:21:32.054  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.054  6570  6636 I jxcore-log: 
07-26 15:21:32.055  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.055  6570  6636 I jxcore-log: 
07-26 15:21:32.056  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.056  6570  6636 I jxcore-log: 
07-26 15:21:32.056  8090  8090 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-26 15:21:32.057  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.057  6570  6636 I jxcore-log: 
07-26 15:21:32.058  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.058  6570  6636 I jxcore-log: 
07-26 15:,21:32.058  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.058  6570  6636 I jxcore-log: 
07-26 15:21:32.059  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.059  6570  6636 I jxcore-log: 
07-26 15:21:32.060  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.060  6570  6636 I jxcore-log: 
07-26 15:21:32.061  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.061  6570  6636 I jxcore-log: 
07-26 15:21:32.062  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.062  6570  6636 I jxcore-log: 
07-26 15:21:32.062  6570  6636 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.062  6570  6636 I jxcore-log: 
07-26 15:21:32.068  8027  8077 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:32.068  8027  8077 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-26 15:21:32.118  1040  1902 W libprocessgroup: failed to open /acct/uid_10005/pid_7175/cgroup.procs: No such file or directory
07-26 15:21:32.118  6570  6628 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 89ms. Plugin should use CordovaInterface.getThreadPool().
07-26 15:21:32.119  6570  6570 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-26 15:21:32.120  6570  6570 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-26 15:21:32.120  6570  6570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.120  6570  6570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.120  6570  6570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.120  6570  6570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.120  6570  6570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89c88b5 removed from the list
07-26 15:21:32.120  6570  6570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.120  6570  6570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3276bbd8 removed from the list
07-26 15:21:32.120  6570  6570 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:32.120  6570  6570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-26 15:21:32.137   352   379 E GBMv2   : DFP En is all cleared set to be enabled
07-26 15:21:32.141  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.141  1948  1964 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
07-26 15:21:32.141  1948  1964 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3708c861 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,07-26 15:21:32.142  1948  3974 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-26 15:21:32.142  1948  3974 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37d10f86 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-26 15:21:32.157  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:32.170  8090  8090 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-26 15:21:32.171  8090  8090 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-26 15:21:32.172  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:32.173  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:32.176  8090  8090 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-26 15:21:32.181  6570  6570 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-26 15:21:32.184  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-26 15:21:32.185  2038  2038 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-26 15:21:32.185  6570  6570 W ScreenOrientationListener: Removing an inexistent observer!
07-26 15:21:32.187  2038  2038 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
07-26 15:21:32.189  2038  2038 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-26 15:21:32.189  2038  2116 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-26 15:21:32.191  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:32.197  2038  2038 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-26 15:21:32.197  1911  1911 D ActionManagerService: notifyUserLog: 1000003
,07-26 15:21:32.197  3812  4520 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-26 15:21:32.198  2038  2038 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-26 15:21:32.198  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.199  2038  2038 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-26 15:21:32.199  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.200  2038  2038 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-26 15:21:32.201  8090  8090 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-26 15:21:32.206  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-26 15:21:32.211  2038  2038 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
07-26 15:21:32.211  1911  1911 D ActionManagerService: notifyUserLog: 1000004
07-26 15:21:32.212  3812  4520 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-26 15:21:32.212  8027  8077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
07-26 15:21:32.212  3812  3827 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , create_time: 1430832262123
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , expire_time: 0
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , display: false
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , animation: false }
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , create_time: 1430832262287
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , expire_time: 0
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , display: false
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , animation: false }
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , create_time: 1469186101943
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , expire_time: 0
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , display: false
07-26 15:21:32.219  2038  2038 I GBoardWebViewUtils: , animation: false }
07-26 15:21:32.220  6764  6764 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-26 15:21:32.222  1040  1902 D InputDispatcher: Window went away: Window{155ac786 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-26 15:21:32.223  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:32.223  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:32.232  2038  8136 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
07-26 15:21:32.236  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:32.241  8027  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
07-26 15:21:32.250  8027  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,07-26 15:21:32.252  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:32.253  8027  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-26 15:21:32.256  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-26 15:21:32.257  8027  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-26 15:21:32.257  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.257  8090  8090 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-26 15:21:32.257  8027  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
07-26 15:21:32.257  8027  8077 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
07-26 15:21:32.259  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-26 15:21:32.259  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-26 15:21:32.259  6764  6764 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-26 15:21:32.259  6764  6764 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-26 15:21:32.259  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-26 15:21:32.259  2038  2038 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
07-26 15:21:32.259  6764  6764 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-26 15:21:32.260  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-26 15:21:32.260  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-26 15:21:32.260  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-26 15:21:32.260  6764  6764 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-26 15:21:32.260  6764  6764 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-26 15:21:32.260  6764  6764 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-26 15:21:32.262  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:32.262  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:32.266  8027  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
07-26 15:21:32.266  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:32.270  8027  8077 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
07-26 15:21:32.271  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:32.274  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.274  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.274  8090  8090 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-26 15:21:32.276  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:32.276  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:32.280  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:32.285  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:32.287  8128  8128 D AndroidRuntime: 
07-26 15:21:32.287  8128  8128 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-26 15:21:32.289  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.289  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.289  8090  8090 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-26 15:21:32.289  8128  8128 D AndroidRuntime: CheckJNI is OFF
07-26 15:21:32.290  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:32.291  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-26 15:21:32.297  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-26 15:21:32.300  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:32.303  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.304  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.304  8090  8090 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-26 15:21:32.305  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:32.306  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:32.310  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-26 15:21:32.313  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-26 15:21:32.322  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.322  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.323  8090  8090 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-26 15:21:32.328  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:32.329  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:32.337  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:32.342  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:32.346  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.347  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.350  8090  8090 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-26 15:21:32.353  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:32.354  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-26 15:21:32.361  2038  2038 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-26 15:21:32.363  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-26 15:21:32.368  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:32.374  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.375  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.375  8090  8090 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-26 15:21:32.378  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:32.378  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:32.381  7980  7980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-26 15:21:32.384  7980  7980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:32.386  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-26 15:21:32.390  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-26 15:21:32.394  8128  8128 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-26 15:21:32.394  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.395  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.396  8090  8090 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-26 15:21:32.396  8090  8090 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-26 15:21:32.397  8090  8090 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-26 15:21:32.400  1040  1109 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-26 15:21:32.400  1040  1109 I ActivityManager: Killing 6570:com.test.thalitest/u0a118 (adj 11): stop com.test.thalitest
,07-26 15:21:32.402  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:32.402  8027  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-26 15:21:32.437  1040  1473 D WifiService: Client connection lost with reason: 4
,07-26 15:21:32.440  2038  2038 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,07-26 15:21:32.469  2038  2038 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-26 15:21:32.472  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,07-26 15:21:32.474  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-26 15:21:32.476  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-26 15:21:32.478  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-26 15:21:32.486  1040  1415 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:32.486  1040  1415 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:32.487  1040  1415 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:32.487  1040  1415 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-26 15:21:32.487  1040  1415 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:32.488  1040  1415 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-26 15:21:32.488  1040  1477 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
07-26 15:21:32.488  1040  1477 D ConnectivityService: identical MTU - not setting
07-26 15:21:32.488  1040  1477 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-26 15:21:32.488  1040  1477 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-26 15:21:32.489  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:32.489  1040  1477 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:32.489  1040  1477 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:32.489  1607  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-26 15:21:32.516  2038  2038 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-26 15:21:32.516  2038  2240 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-26 15:21:32.516  2038  2038 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-26 15:21:32.517  2038  2240 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,07-26 15:21:32.553  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,07-26 15:21:32.554  2038  2038 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-26 15:21:32.554  2038  2038 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-26 15:21:32.567  2038  2038 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,07-26 15:21:32.628  1040  1946 W ActivityManager: Spurious death for ProcessRecord{3cc7b15c 6570:com.test.thalitest/u0a118}, curProc for 6570: null
07-26 15:21:32.630  7980  7980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-26 15:21:32.635  7980  7980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-26 15:21:32.640  2623  2623 D [Concierge]Service: onStartCommand(). Type : 8
07-26 15:21:32.641  2623  2623 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-26 15:21:32.645  2623  2623 D [Concierge]Service: Update widget ID : 11
,07-26 15:21:32.648  1040  1123 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{21205b10 u0 com.lge.launcher2/.Launcher t39} time:170233
07-26 15:21:32.656  6764  6764 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-26 15:21:32.656  1040  1128 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-26 15:21:32.656  2038  2038 D [Concierge]WidgetView: change position of spinner
,07-26 15:21:32.664  6764  6764 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-26 15:21:32.685  1607  1607 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,07-26 15:21:32.699  2487  2617 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:21:32.699  1040  1386 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-26 15:21:32.702  2001  2001 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-26 15:21:32.703  3812  3812 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
07-26 15:21:32.706  4491  4491 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-26 15:21:32.706  4491  4491 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-26 15:21:32.707  4491  4491 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-26 15:21:32.707  4491  4491 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-26 15:21:32.707  4491  4491 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:21:32.707  4491  4491 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:21:32.707  4491  4491 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-26 15:21:32.707  4491  4491 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-26 15:21:32.707  4491  4491 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:32.707  4491  4491 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:32.707  4491  4491 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-26 15:21:32.707  4491  4491 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-26 15:21:32.708  7608  7608 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-26 15:21:32.708  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-26 15:21:32.709  2038  2038 I [Concierge]WidgetView: initWebView(). Time : 1469539292709
07-26 15:21:32.715  2623  2623 D [Concierge]Service: onStartCommand(). Type : 0
,07-26 15:21:32.729  4609  4609 I art     : Explicit concurrent mark sweep GC freed 8426(478KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 747us total 56.574ms
,07-26 15:21:32.743  1040  1982 V SIM_STK : Menu title from STK is T-Mobile
07-26 15:21:32.755  1040  1106 W InputMethodInfo: Duplicated subtype definition found: , voice
,07-26 15:21:32.782  1040  1040 D administrator: Handling package changes for user 0
,07-26 15:21:32.796  1607  1607 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,07-26 15:21:32.813  1607  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-26 15:21:32.813  1607  1655 D KeyguardModel: createShortcutInfo...
,07-26 15:21:32.813  8090  8090 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-26 15:21:32.813  8090  8090 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.814  8090  8090 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-26 15:21:32.814  8090  8090 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-26 15:21:32.815  8090  8090 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-26 15:21:32.816  1607  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-26 15:21:32.816  1607  1655 D KeyguardModel: createShortcutInfo...
07-26 15:21:32.822  1607  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-26 15:21:32.822  1607  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:32.822  1607  1655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-26 15:21:32.824  1607  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-26 15:21:32.824  1607  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-26 15:21:32.824  1607  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-26 15:21:32.826  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:32.827  2038  2038 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 218078094
07-26 15:21:32.827  1607  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-26 15:21:32.827  1607  1655 D KeyguardModel: createShortcutInfo...
07-26 15:21:32.827  2038  2038 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-26 15:21:32.828  2038  2038 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-26 15:21:32.832  1607  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-26 15:21:32.832  1607  1655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-26 15:21:32.833  2038  2038 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3a984f47
07-26 15:21:32.834  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-26 15:21:32.838  1607  1607 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-26 15:21:32.838  1607  1607 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,07-26 15:21:32.841  1607  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 15:21:32.841  1607  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-26 15:21:32.843  1607  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-26 15:21:32.843  1607  1655 D KeyguardModel: createShortcutInfo...
07-26 15:21:32.844  2038  2038 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-26 15:21:32.845  2038  2038 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-26 15:21:32.858  1607  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-26 15:21:32.858  1607  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-26 15:21:32.858  1607  1655 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-26 15:21:32.858  1607  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-26 15:21:32.860  1607  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 15:21:32.860  1607  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-26 15:21:32.864  1607  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-26 15:21:32.864  1607  1655 D KeyguardModel: createShortcutInfo...
07-26 15:21:32.865  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-26 15:21:32.865  2038  2038 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-26 15:21:32.866  2038  2038 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-26 15:21:32.866  2038  2038 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
07-26 15:21:32.866  2038  2038 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-26 15:21:32.867  2038  2038 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469539150592, New one : 1469539292709
,07-26 15:21:32.867  2038  2038 D [Concierge]WidgetView: Unregister all receivers
07-26 15:21:32.867  2038  2038 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-26 15:21:32.867  2038  2038 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
07-26 15:21:32.867  2038  2038 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-26 15:21:32.869  1876  1876 D SplitUIManager: split_name #11 / not available #0
07-26 15:21:32.869  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-26 15:21:32.869  1876  1876 D SplitUIService: removed split : 
07-26 15:21:32.870  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-26 15:21:32.871  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-26 15:21:32.873  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-26 15:21:32.874  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-26 15:21:32.875  8090  8090 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-26 15:21:32.884  1607  1607 D KeyguardModel: handleShortcutListChanged...
07-26 15:21:32.884  1607  1607 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-26 15:21:32.887  1607  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-26 15:21:32.887  1607  1655 D KeyguardModel: createShortcutInfo...
,07-26 15:21:32.890  8090  8090 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,07-26 15:21:32.895  1607  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-26 15:21:32.895  1607  1655 D KeyguardModel: createShortcutInfo...
07-26 15:21:32.896  1607  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 15:21:32.896  1607  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-26 15:21:32.897  1040  1875 V SIM_STK : Menu title from STK is T-Mobile
07-26 15:21:32.897  1040  1875 V SIM_STK : Menu title from STK is T-Mobile
07-26 15:21:32.897  1607  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-26 15:21:32.897  1607  1655 D KeyguardModel: createShortcutInfo...
07-26 15:21:32.898  1607  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 15:21:32.898  1607  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-26 15:21:32.898  1876  1876 D SplitUIManager: split_name #11 / not available #0
07-26 15:21:32.898  1876  1876 I SplitUIService: split app #11
07-26 15:21:32.899  1607  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-26 15:21:32.899  1607  1655 D KeyguardModel: createShortcutInfo...
07-26 15:21:32.900  1607  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 15:21:32.900  1607  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-26 15:21:32.901  8090  8090 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-26 15:21:32.901  1607  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-26 15:21:32.901  1607  1655 D KeyguardModel: createShortcutInfo...
07-26 15:21:32.902  2038  2038 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-26 15:21:32.902  2038  2038 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-26 15:21:32.911  1040  1946 V SIM_STK : Menu title from STK is T-Mobile
07-26 15:21:32.939  1607  1607 D KeyguardModel: handleShortcutListChanged...
07-26 15:21:32.939  1607  1607 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,07-26 15:21:32.949  1040  1982 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-26 15:21:32.949  7608  7608 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-26 15:21:32.960  2038  2038 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,07-26 15:21:32.968  2038  2038 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-26 15:21:32.968  2038  2038 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
07-26 15:21:32.970  2038  2038 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-26 15:21:32.989  2038  2038 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e65de5a time:170575
,07-26 15:21:33.007  1040  1040 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-26 15:21:33.007  1040  1040 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-26 15:21:33.007  1040  1040 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-26 15:21:33.008  1040  1582 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
07-26 15:21:33.013  8090  8090 D LgDataFeature: LgDataFeature() Constructor: none
07-26 15:21:33.013  8090  8090 D LgDataFeature: LgDataFeature() Constructor Done, null
07-26 15:21:33.025  8090  8090 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,07-26 15:21:33.027  8090  8090 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-26 15:21:33.027  8090  8090 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-26 15:21:33.027  8090  8090 V SoundPool: doLoad: loading sample sampleID=1
07-26 15:21:33.027  8090  8090 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-26 15:21:33.029  8090  8090 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-26 15:21:33.030  8090  8160 V SoundPool: Start decode
07-26 15:21:33.030  8090  8160 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-26 15:21:33.030  7537  7537 D UEI.SmartControl: QS Service created
07-26 15:21:33.030  8090  8090 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-26 15:21:33.030  8090  8090 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-26 15:21:33.034   329  1402 V MediaPlayerService: decode(22, 10857164, 17813)
07-26 15:21:33.034   329  1402 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-26 15:21:33.034   329  1402 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-26 15:21:33.034   329  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-26 15:21:33.034   329  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-26 15:21:33.034   329  1402 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-26 15:21:33.034   329  1402 V MediaPlayerService: player type = 3
07-26 15:21:33.034   329  1402 V AwesomePlayer: AwesomePlayer create()
07-26 15:21:33.035   329  1402 V AwesomePlayer: reset_l() 
07-26 15:21:33.035   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:33.035   329  1402 V AwesomePlayer: setAudioSink() 
07-26 15:21:33.035   329  1402 V AwesomePlayer: reset_l() 
07-26 15:21:33.035   329  1402 V AudioCache: notify(0xb16a69c0, 8, 0, 0)
07-26 15:21:33.035   329  1402 V AudioCache: ignored
07-26 15:21:33.035   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:33.035   329  1402 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
07-26 15:21:33.035   329  1402 V AwesomePlayer: setDataSource_l dataSource
07-26 15:21:33.035   329  1402 V LGParserOSAL: SniffLGParser start
07-26 15:21:33.035   329  1402 V LGParserOSAL: MainType:5, SubType=0
07-26 15:21:33.035   329  1402 V LGParserOSAL: #### check Mime : application/ogg
07-26 15:21:33.035   329  1402 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-26 15:21:33.035   329  1402 E MediaExtractor: Use LGExtractor :application/ogg 
07-26 15:21:33.036  7537  7537 I UEI.SmartControl: Service initServices...
07-26 15:21:33.036  7537  7537 D UEI.SmartControl: QS start get config
07-26 15:21:33.038   339   418 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,07-26 15:21:33.039  3220  8161 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-26 15:21:33.039  8090  8090 V LGMDMManager: Create singleton instance
07-26 15:21:33.065   329  1402 V LGParserOSAL: supported mime: application/ogg
07-26 15:21:33.065   329  1402 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-26 15:21:33.065   329  1402 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-26 15:21:33.065   329  1402 V AwesomePlayer: mBitrate = -1 bits/sec
07-26 15:21:33.065   329  1402 V AwesomePlayer: AudioTrack Setting
07-26 15:21:33.065   329  1402 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-26 15:21:33.065   329  1402 V AwesomePlayer: setAudioSource() 
07-26 15:21:33.065   329  1402 V MediaPlayerService: prepare
07-26 15:21:33.065   329  1402 V AwesomePlayer: prepareAsync_l() 
07-26 15:21:33.065   329  1402 V MediaPlayerService: wait for prepare
07-26 15:21:33.065   329  8162 V AwesomePlayer: onPrepareAsyncEvent() 
07-26 15:21:33.065   329  8162 V AwesomePlayer: initAudioDecoder() 
07-26 15:21:33.065   329  8162 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-26 15:21:33.065   329  8162 V AudioSystem: isOffloadSupported()
07-26 15:21:33.065   329  8162 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-26 15:21:33.065   329  8162 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-26 15:21:33.065   329  8162 I AudioFlinger: isAudioPlaybackHookOn() false
07-26 15:21:33.065   329  8162 V AwesomePlayer: getUseOffload() = 0 
07-26 15:21:33.065   329  8162 V OMXCodec: OMXCodec::Create
07-26 15:21:33.065   329  8162 V OMXCodec: findMatchingCodecs()
07-26 15:21:33.065   329  8162 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-26 15:21:33.065   329  8162 V OMXCodec: matchingCodecs.size()=1
07-26 15:21:33.065   329  8162 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-26 15:21:33.066   329  8162 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-26 15:21:33.066   329  8162 V LGCodecAdapter: LG Codec Adapter start
07-26 15:21:33.066   329  8162 V OMXCodec: OMXCodec Createtor
07-26 15:21:33.066   329  8162 V OMXCodec: setComponentRole
,07-26 15:21:33.066   329  8162 V OMXCodec: configureCodec protected=0
07-26 15:21:33.066   329  8162 V LGCodecAdapter: called getLGCodecSpecificData
07-26 15:21:33.066   329  8162 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-26 15:21:33.066   329  8162 V LGCodecOSAL: Called LGconfigureCodecMETA
07-26 15:21:33.066   329  8162 V LGCodecOSAL: Called LGconfigureCodecMSG
07-26 15:21:33.066   329  8162 V LGCodecOSAL: Not support LGCodec
07-26 15:21:33.066   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-26 15:21:33.066   329  8162 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-26 15:21:33.066   329  8162 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-26 15:21:33.067   329  8162 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-26 15:21:33.067   329  8162 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-26 15:21:33.067   329  8162 V AudioSystem: isOffloadSupported()
,07-26 15:21:33.067   329  8162 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-26 15:21:33.067   329  8162 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-26 15:21:33.067   329  8162 V OMXCodec: init()
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-26 15:21:33.067   329  8162 V OMXCodec: allocateBuffers
07-26 15:21:33.067   329  8162 V OMXCodec: allocateBuffersOnPort portIndex=0
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
07-26 15:21:33.067   329  8162 V OMXCodec: allocateBuffersOnPort portIndex=1
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-26 15:21:33.067   329  8162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
07-26 15:21:33.067   329  8162 V OMXCodec: init() mAsyncCompletion wait!!! 
07-26 15:21:33.074   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-26 15:21:33.074   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-26 15:21:33.074   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-26 15:21:33.074   329  8162 V OMXCodec: init() mAsyncCompletion wait!!! 
07-26 15:21:33.074   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-26 15:21:33.074   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-26 15:21:33.074   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-26 15:21:33.075   329  8162 V OMXCodec: init() mAsyncCompletion wait free! 
07-26 15:21:33.075   329  8162 V AwesomePlayer: finishAsyncPrepare_l() 
07-26 15:21:33.075   329  8162 V AudioCache: notify(0xb16a69c0, 5, 0, 0)
07-26 15:21:33.075   329  8162 V AudioCache: ignored
07-26 15:21:33.075   329  8162 V AudioCache: notify(0xb16a69c0, 1, 0, 0)
07-26 15:21:33.075   329  8162 V AudioCache: prepared
07-26 15:21:33.075   329  1402 V AudioCache: wait - success
07-26 15:21:33.075   329  1402 V MediaPlayerService: start
07-26 15:21:33.075   329  1402 V AwesomePlayer: play_l() 
07-26 15:21:33.075   329  1402 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-26 15:21:33.075   329  1402 V AwesomePlayer: createAudioPlayer_l
07-26 15:21:33.075   329  1402 V AwesomePlayer: seekAudioIfNecessary_l() 
07-26 15:21:33.075   329  1402 V AwesomePlayer: startAudioPlayer_l() 
07-26 15:21:33.075   329  1402 D AudioPlayer: start of Playback, useOffload 0
07-26 15:21:33.075   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-26 15:21:33.075   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-26 15:21:33.076   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-26 15:21:33.076   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-26 15:21:33.076   329  8164 V OMXCodec: [OMX.google.v,orbis.decoder] setState mState=4 , newState=7
07-26 15:21:33.076   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-26 15:21:33.076   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-26 15:21:33.076   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
,07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-26 15:21:33.077   329  8164 V OMXCodec: allocateBuffersOnPort portIndex=1
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb0b0 on output port
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-26 15:21:33.077   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-26 15:21:33.078   329  1402 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-26 15:21:33.078   329  1402 V AudioCache: notify(0xb16a69c0, 6, 0, 0)
07-26 15:21:33.078   329  1402 V AudioCache: ignored
07-26 15:21:33.078   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.078   329  8165 V AudioCache: memcpy(0xb0556000, 0xb16df000, 4096)
07-26 15:21:33.078   329  1402 V MediaPlayerService: wait for playback complete
07-26 15:21:33.082   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.082   329  8165 V AudioCache: memcpy(0xb0557000, 0xb16df000, 4096)
07-26 15:21:33.082   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.082   329  8165 V AudioCache: memcpy(0xb0558000, 0xb16df000, 4096)
07-26 15:21:33.082   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.082   329  8165 V AudioCache: memcpy(0xb0559000, 0xb16df000, 4096)
07-26 15:21:33.083   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.083   329  8165 V AudioCache: memcpy(0xb055a000, 0xb16df000, 4096)
07-26 15:21:33.083   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.083   329  8165 V AudioCache: memcpy(0xb055b000, 0xb16df000, 4096)
07-26 15:21:33.083   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.083   329  8165 V AudioCache: memcpy(0xb055c000, 0xb16df000, 4096)
07-26 15:21:33.083  8090  8090 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-26 15:21:33.084   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.084   329  8165 V AudioCache: memcpy(0xb055d000, 0xb16df000, 4096)
07-26 15:21:33.084  8090  8090 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-26 15:21:33.084   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.084   329  8165 V AudioCache: memcpy(0xb055e000, 0xb16df000, 4096)
07-26 15:21:33.084   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.084   329  8165 V AudioCache: memcpy(0xb055f000, 0xb16df000, 4096)
07-26 15:21:33.084   329  8165 V AudioCache: write(0xb16df000, 4096)
,07-26 15:21:33.084   329  8165 V AudioCache: memcpy(0xb0560000, 0xb16df000, 4096)
07-26 15:21:33.084   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.084   329  8165 V AudioCache: memcpy(0xb0561000, 0xb16df000, 4096)
07-26 15:21:33.085   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.085   329  8165 V AudioCache: memcpy(0xb0562000, 0xb16df000, 4096)
07-26 15:21:33.085   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.085   329  8165 V AudioCache: memcpy(0xb0563000, 0xb16df000, 4096)
07-26 15:21:33.085   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.085  8090  8090 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1302
07-26 15:21:33.085   329  8165 V AudioCache: memcpy(0xb0564000, 0xb16df000, 4096)
07-26 15:21:33.085   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.085   329  8165 V AudioCache: memcpy(0xb0565000, 0xb16df000, 4096)
07-26 15:21:33.086   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.086   329  8165 V AudioCache: memcpy(0xb0566000, 0xb16df000, 4096)
07-26 15:21:33.086   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.086   329  8165 V AudioCache: memcpy(0xb0567000, 0xb16df000, 4096)
07-26 15:21:33.086   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.086   329  8165 V AudioCache: memcpy(0xb0568000, 0xb16df000, 4096)
07-26 15:21:33.086   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.086   329  8165 V AudioCache: memcpy(0xb0569000, 0xb16df000, 4096)
07-26 15:21:33.087   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.087   329  8165 V AudioCache: memcpy(0xb056a000, 0xb16df000, 4096)
07-26 15:21:33.087  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.087   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.087   329  8165 V AudioCache: memcpy(0xb056b000, 0xb16df000, 4096)
07-26 15:21:33.088   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.088   329  8165 V AudioCache: memcpy(0xb056c000, 0xb16df000, 4096)
07-26 15:21:33.088   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.088   329  8165 V AudioCache: memcpy(0xb056d000, 0xb16df000, 4096)
07-26 15:21:33.088   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.088   329  8165 V AudioCache: memcpy(0xb056e000, 0xb16df000, 4096)
07-26 15:21:33.089   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.089   329  8165 V AudioCache: memcpy(0xb056f000, 0xb16df000, 4096)
07-26 15:21:33.089   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.089   329  8165 V AudioCache: memcpy(0xb0570000, 0xb16df000, 4096)
07-26 15:21:33.089   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.089   329  8165 V AudioCache: memcpy(0xb0571000, 0xb16df000, 4096)
07-26 15:21:33.090   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.090   329  8165 V AudioCache: memcpy(0xb0572000, 0xb16df000, 4096)
07-26 15:21:33.090   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.090   329  8165 V AudioCache: memcpy(0xb0573000, 0xb16df000, 4096)
07-26 15:21:33.090   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.090   329  8165 V AudioCache: memcpy(0xb0574000, 0xb16df000, 4096)
07-26 15:21:33.091   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.091   329  8165 V AudioCache: memcpy(0xb0575000, 0xb16df000, 4096)
07-26 15:21:33.091   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.091   329  8165 V AudioCache: memcpy(0xb0576000, 0xb16df000, 4096)
07-26 15:21:33.091   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.091   329  8165 V AudioCache: memcpy(0xb0577000, 0xb16df000, 4096)
07-26 15:21:33.092   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.092   329  8165 V AudioCache: memcpy(0xb0578000, 0xb16df000, 4096)
07-26 15:21:33.092   329  8165 ,V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.092   329  8165 V AudioCache: memcpy(0xb0579000, 0xb16df000, 4096)
07-26 15:21:33.092   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.092   329  8165 V AudioCache: memcpy(0xb057a000, 0xb16df000, 4096)
07-26 15:21:33.093   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.093   329  8165 V AudioCache: memcpy(0xb057b000, 0xb16df000, 4096)
07-26 15:21:33.093   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.093   329  8165 V AudioCache: memcpy(0xb057c000, 0xb16df000, 4096)
07-26 15:21:33.094   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.094   329  8165 V AudioCache: memcpy(0xb057d000, 0xb16df000, 4096)
07-26 15:21:33.094   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.094   329  8165 V AudioCache: memcpy(0xb057e000, 0xb16df000, 4096)
07-26 15:21:33.095   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.095   329  8165 V AudioCache: memcpy(0xb057f000, 0xb16df000, 4096)
07-26 15:21:33.096   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.096   329  8165 V AudioCache: memcpy(0xb0580000, 0xb16df000, 4096)
07-26 15:21:33.096   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.096   329  8165 V AudioCache: memcpy(0xb0581000, 0xb16df000, 4096)
07-26 15:21:33.096   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.096   329  8165 V AudioCache: memcpy(0xb0582000, 0xb16df000, 4096)
07-26 15:21:33.097   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.097   329  8165 V AudioCache: memcpy(0xb0583000, 0xb16df000, 4096)
07-26 15:21:33.097   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.097   329  8165 V AudioCache: memcpy(0xb0584000, 0xb16df000, 4096)
07-26 15:21:33.098   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.098   329  8165 V AudioCache: memcpy(0xb0585000, 0xb16df000, 4096)
07-26 15:21:33.098   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.098   329  8165 V AudioCache: memcpy(0xb0586000, 0xb16df000, 4096)
07-26 15:21:33.099   329  8165 V AudioCache: write(0xb16df000, 4096)
07-26 15:21:33.099   329  8165 V AudioCache: memcpy(0xb0587000, 0xb16df000, 4096)
07-26 15:21:33.099   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-26 15:21:33.099   329  8165 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-26 15:21:33.099   329  8165 V AwesomePlayer: postAudioEOS() 
07-26 15:21:33.099   329  8165 V AudioCache: write(0xb16df000, 280)
07-26 15:21:33.099   329  8165 V AudioCache: memcpy(0xb0588000, 0xb16df000, 280)
,07-26 15:21:33.100   329  8162 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-26 15:21:33.100   329  8162 V AwesomePlayer: onStreamDone
07-26 15:21:33.100   329  8162 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-26 15:21:33.100   329  8162 V AudioCache: notify(0xb16a69c0, 2, 0, 0)
07-26 15:21:33.100   329  8162 V AudioCache: playback complete
07-26 15:21:33.100   329  8162 V AwesomePlayer: pause_l() 
07-26 15:21:33.100   329  8162 V AudioCache: notify(0xb16a69c0, 7, 0, 0)
07-26 15:21:33.100   329  8162 V AudioCache: ignored
07-26 15:21:33.100   329  8162 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:33.101   329  1402 V AudioCache: wait - success
07-26 15:21:33.101   329  1402 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-26 15:21:33.101   329  8162 D AudioPlayer: Pause Playback at 1068125
07-26 15:21:33.105   329  1402 V AwesomePlayer: reset_l() 
07-26 15:21:33.105   329  1402 V AudioCache: notify(0xb16a69c0, 8, 0, 0)
07-26 15:21:33.105   329  1402 V AudioCache: ignored
07-26 15:21:33.105   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:33.105   329  1402 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-26 15:21:33.105   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-26 15:21:33.105   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-26 15:21:33.105   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-26 15:21:33.105   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb0b0 on port 1
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-26 15:21:33.106   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-26 15:21:33.106   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-26, 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-26 15:21:33.106   329  8164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-26 15:21:33.106   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-26 15:21:33.106   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-26 15:21:33.106   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-26 15:21:33.107  1040  1128 I art     : Explicit concurrent mark sweep GC freed 81761(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.577ms total 276.323ms
07-26 15:21:33.108   329  1402 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-26 15:21:33.108   329  1402 D AudioPlayer: AudioPlayer releasing audio source
07-26 15:21:33.108   329  1402 D AudioPlayer: AudioPlayer done releasing audio source
07-26 15:21:33.109   329  1402 V AwesomePlayer: reset_l() 
07-26 15:21:33.109   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:33.109   329  1402 V AwesomePlayer: ~AwesomePlayer call
07-26 15:21:33.109   329  1402 V AwesomePlayer: reset_l() 
07-26 15:21:33.109   329  1402 V AwesomePlayer: cancelPlayerEvents
07-26 15:21:33.109  8090  8160 V SoundPool: close(31)
07-26 15:21:33.109  8090  8160 V SoundPool: pointer = 0x9fe55000, size = 205080, sampleRate = 48000, numChannels = 2
07-26 15:21:33.134  1040  1921 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8166 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:33.138  8128  8128 D AndroidRuntime: Shutting down VM
07-26 15:21:33.141  2038  2038 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
07-26 15:21:33.184  2038  2873 I GBoardtInterface: onReloaded()
,07-26 15:21:33.185  1040  1128 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8183 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-26 15:21:33.186  2038  2038 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
07-26 15:21:33.188  3812  3828 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-26 15:21:33.191  3812  3827 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-26 15:21:33.201  1911  1911 D ActionManagerService: notifyUserLog: 1000001
07-26 15:21:33.203  3812  4520 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-26 15:21:33.203  3812  4520 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,07-26 15:21:33.205  1911  1911 D ActionManagerService: notifyUserLog: 1000001
07-26 15:21:33.206  8166  8166 I art     : Almond Protected OAT
07-26 15:21:33.206  3812  4520 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-26 15:21:33.206  3812  4520 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-26 15:21:33.207  3812  4520 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
07-26 15:21:33.207  3812  4520 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
07-26 15:21:33.207  3812  3828 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-26 15:21:33.210  2038  2038 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
07-26 15:21:33.210  2038  2038 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
07-26 15:21:33.212  2038  2038 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
07-26 15:21:33.212  2038  2038 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-26 15:21:33.213  2038  2038 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
07-26 15:21:33.214  2038  2038 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-26 15:21:33.234  8166  8166 D WeatherApplication: removeAccount
,07-26 15:21:33.235  8166  8166 D WeatherApplication: Account.length = 0
07-26 15:21:33.235  8166  8166 E WeatherApplication: OPERATOR:OPEN
07-26 15:21:33.238  8166  8166 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:21:33
07-26 15:21:33.240  8166  8166 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-26 15:21:33.240  8166  8166 D Weather.Utils: 2 : All the weather widget is gone.
07-26 15:21:33.241  8166  8166 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-26 15:21:33.242  8166  8166 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-26 15:21:33.242  8166  8166 D Weather.Utils: 2 : All the weather widget is gone.
07-26 15:21:33.242  8166  8166 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:21:33
07-26 15:21:33.243  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.245  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.246  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.247  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.248  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.251  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.253  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.255  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.257  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-26 15:21:33.258  8027  8027 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,07-26 15:21:33.261  1823  1823 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
07-26 15:21:33.264   352   381 E GBMv2   : DFP En is all cleared set to be enabled
07-26 15:21:33.264   352   381 E GBMv2   : Set value is all cleared set the max
07-26 15:21:33.264   352   381 I GBMv2   : DFP Enabled. Ignore VFP set
07-26 15:21:33.266  2218  2218 I ConfigService: onCreate
,07-26 15:21:33.266  2218  2218 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-26 15:21:33.269  1823  1823 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-26 15:21:33.273  2218  2218 I ConfigService: onBind returning update interface
07-26 15:21:33.274  2218  2218 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-26 15:21:33.274  2218  2218 I ConfigService: onBind returning config service
,07-26 15:21:33.292  2218  2218 I ConfigService: onDestroy
,07-26 15:21:33.295  1040  1106 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:33.299  1823  8202 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-26 15:21:33.302  1040  1106 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-26 15:21:33.307  2038  2038 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,07-26 15:21:33.307  7537  7537 I UEI.SmartControl: Supports setup maps: true
07-26 15:21:33.313  7537  7537 D UEI.SmartControl: QS start statue = true Error code = 0
07-26 15:21:33.313  7537  7537 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-26 15:21:33.313  7537  7537 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-26 15:21:33.313  7537  7537 I UEI.SmartControl: ### init IR Blaster...
07-26 15:21:33.317  7537  7537 D serial_port: Configuring serial port
07-26 15:21:33.317  7537  7537 E UEI.SmartControl: UEIBLaster setting for 616
07-26 15:21:33.317  7537  7537 I UEI.SmartControl: Setting serial record hearder size = 2
07-26 15:21:33.317  7537  7537 I UEI.SmartControl: configuring settings for MAXQ616
07-26 15:21:33.317  7537  7537 I UEI.SmartControl: Get version...
07-26 15:21:33.322  5893  8209 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,07-26 15:21:33.325  1823  8210 I PeopleContactsSync: CP2 sync disabled
07-26 15:21:33.328  1823  4784 I Icing   : doRemovePackageData com.test.thalitest
07-26 15:21:33.339  1823  8208 W GmsApplication: Using Auth Proxy for data requests.
,07-26 15:21:33.345  7537  8207 D UEI.SmartControl: serial port data available: 21
07-26 15:21:33.348  1823  8208 W GmsApplication: Using Auth Proxy for data requests.
07-26 15:21:33.368  6950  6950 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,07-26 15:21:33.372  7537  7537 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-26 15:21:33.372  7537  7537 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-26 15:21:33.372  7537  7537 I UEI.SmartControl: QS saving settings...
07-26 15:21:33.373  7537  7537 D UEI.SmartControl: IR Blaster version: 25672567
07-26 15:21:33.376  2382  8214 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-26 15:21:33.390  7537  8207 D UEI.SmartControl: serial port data available: 4
,07-26 15:21:33.403  1040  1055 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8216 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-26 15:21:33.419  7537  7537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-26 15:21:33.429  7537  7537 E UEI.SmartControl: Services init done
07-26 15:21:33.429  7537  7537 D UEI.SmartControl: QS Service init finished
,07-26 15:21:33.431  7537  7537 D UEI.SmartControl: QS Service version name: 2.1.91
07-26 15:21:33.431  7537  7537 D UEI.SmartControl: QS Service version code: 201091
07-26 15:21:33.431  7537  7537 D UEI.SmartControl: Service requested: Control
07-26 15:21:33.431  7537  8232 I UEI.SmartControl: Device manager: loading config....
07-26 15:21:33.432  7537  8232 D UEI.SmartControl: ----------- loading internal config...
07-26 15:21:33.435  2218  2234 I art     : Explicit concurrent mark sweep GC freed 5200(306KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.086ms total 18.669ms
07-26 15:21:33.440  7537  8232 E UEI.SmartControl: Loading SETTINGS...
,07-26 15:21:33.444  8090  8090 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-26 15:21:33.445  7537  7537 D UEI.SmartControl: Internal service binding...
07-26 15:21:33.445  7537  7552 I UEI.SmartControl: ------ IControl API: 11
07-26 15:21:33.445  7537  7552 D UEI.SmartControl: File observer start...
07-26 15:21:33.445  7537  7552 E UEI.SmartControl: IR Port is disabled: false
07-26 15:21:33.445  7537  7552 D UEI.SmartControl: Starting file observer...
07-26 15:21:33.445  7537  7552 I UEI.SmartControl: Registering callback...
07-26 15:21:33.445  7537  7553 I UEI.SmartControl: ------ IControl API: 19
07-26 15:21:33.446  7537  7553 I UEI.SmartControl: Registering Services Ready callback...
07-26 15:21:33.455  7537  8232 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-26 15:21:33.464  7537  8231 I UEI.SmartControl: Notify AllClients services are ready: 0
07-26 15:21:33.464  7537  8231 D UEI.SmartControl: -----service ready thread exits
07-26 15:21:33.464  8090  8108 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-26 15:21:33.465  8090  8158 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-26 15:21:33.466  8090  8158 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-26 15:21:33.466  8216  8216 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:33.466  8216  8216 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-26 15:21:33.466  8090  8090 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-26 15:21:33.466  8090  8090 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-26 15:21:33.467  8216  8216 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-26 15:21:33.467  8216  8216 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-26 15:21:33.471  7537  7552 I UEI.SmartControl: ------ IControl API: 8
,07-26 15:21:33.473  8090  8090 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-26 15:21:33.474  8090  8090 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-26 15:21:33.474  8090  8090 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-26 15:21:33.474  8090  8090 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-26 15:21:33.475  8090  8090 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-26 15:21:33.475  8090  8090 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-26 15:21:33.475  8090  8090 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-26 15:21:33.476  8090  8090 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-26 15:21:33.477  1040  1786 I ActivityManager: Killing 7714:com.android.gallery3d/u0a27 (adj 15): empty #17
07-26 15:21:33.524  2038  2873 I GBoardtInterface: exportHTML()
,07-26 15:21:33.560  2038  2873 I GBoardtInterface: exportHTML()
07-26 15:21:33.561  1040  1786 I ActivityManager: Killing 7640:com.google.android.talk/u0a72 (adj 15): empty #18
,07-26 15:21:33.584  2038  2873 I GBoardtInterface: exportHTML()

```
