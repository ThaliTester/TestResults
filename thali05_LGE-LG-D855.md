#### Test 72145431fb64fa4_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-05 12:50:36.207  6564  6564 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-05 12:50:36.213  6564  6564 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{352d773c com.google.android.apps.docs}
07-05 12:50:36.228  6564  6564 D TAG     : onCreate()
07-05 12:50:36.258  6564  6564 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,07-05 12:50:36.652  6593  6593 D AndroidRuntime: 
07-05 12:50:36.652  6593  6593 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:50:36.655  6593  6593 D AndroidRuntime: CheckJNI is OFF
07-05 12:50:36.771  6593  6593 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-05 12:50:36.774  1038  2008 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 12:50:36.782  1943  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-05 12:50:36.784  1038  2008 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-05 12:50:36.785  1038  2008 D ActivityManager: setTaskToReturnTo : TaskRecord{3c63edbf #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 12:50:36.785  1038  2008 D ActivityManager: setTaskToReturnTo : TaskRecord{3c63edbf #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 12:50:36.786  1038  2008 D WindowStateEx: AppWindowTokenEx init.. 
07-05 12:50:36.791   336   366 E GBMv2   : DFP En is all cleared set to be enabled
07-05 12:50:36.813  1038  2008 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6609 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:50:36.815  6593  6593 D AndroidRuntime: Shutting down VM
07-05 12:50:36.849  1943  3968 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-05 12:50:36.849  1943  3968 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3b63fd78 co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-05 12:50:36.850  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-05 12:50:36.850  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{39dac51 co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-05 12:50:36.884  6609  6609 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 12:50:36.952  6609  6609 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-05 12:50:36.967  6609  6609 I LibraryLoader: Loading: webviewchromium
07-05 12:50:36.969  6609  6609 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7445-7448)
07-05 12:50:36.970  6609  6609 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:36.990  6609  6609 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a6d79e6}
07-05 12:50:36.991  6609  6609 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:36.991  6609  6609 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:50:36.998  6609  6609 I BrowserStartupController: Initializing chromium process, renderers=0
07-05 12:50:36.999  6609  6609 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:37.009   317  2158 V AudioPolicyService: registerClient() client 0xb57e3de0, uid 10118
07-05 12:50:37.010  6609  6609 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-05 12:50:37.011  6609  6609 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-05 12:50:37.011  6609  6609 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,07-05 12:50:37.014  1038  1120 D BluetoothManagerService: Message: 20
07-05 12:50:37.014  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32414451:true
07-05 12:50:37.038  6609  6609 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:50:37.038  6609  6609 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:50:37.038  6609  6609 I Adreno-EGL: Build Date: 12/12/14 금
07-05 12:50:37.038  6609  6609 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-05 12:50:37.038  6609  6609 I Adreno-EGL: Remote Branch: 
07-05 12:50:37.038  6609  6609 I Adreno-EGL: Local Patches: 
07-05 12:50:37.038  6609  6609 I Adreno-EGL: Reconstruct Branch: 
,07-05 12:50:37.051  1817  4750 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,07-05 12:50:37.109  6609  6644 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,07-05 12:50:37.111  1817  4750 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-05 12:50:37.111  6609  6609 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-05 12:50:37.126  6609  6609 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:50:37.129  6609  6609 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 12:50:37.132  6609  6609 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-05 12:50:37.134  6609  6609 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 12:50:37.134  6609  6609 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-05 12:50:37.153  6609  6609 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-05 12:50:37.162  6609  6609 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:37.162  6609  6609 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:50:37.189  6609  6661 D OpenGLRenderer: Render dirty regions requested: true
07-05 12:50:37.190  6609  6661 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 12:50:37.195  6609  6661 D OpenGLRenderer: Enabling debug mode 0
,07-05 12:50:37.201  1817  4750 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
07-05 12:50:37.207  6609  6609 D Atlas   : Validating map...
,07-05 12:50:37.213  1038  2036 D SplitWindow: check instance of lgWin Window{1cf93a43 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-05 12:50:37.239  6609  6659 D LgDataFeature: LgDataFeature() Constructor: none
07-05 12:50:37.239  6609  6659 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-05 12:50:37.347  1038  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +502ms (total +560ms)
07-05 12:50:37.347  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9b69c8c u0 com.test.thalitest/.MainActivity t12} time:127826
07-05 12:50:37.351  6609  6609 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39c301ed time:127830
07-05 12:50:37.441  6609  6609 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 12:50:37.501  6609  6609 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-05 12:50:37.501  6609  6609 I chromium: 
,07-05 12:50:37.543  6609  6659 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-05 12:50:37.543  6609  6659 I chromium: 
,07-05 12:50:37.671  6609  6676 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,07-05 12:50:37.683  6609  6676 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:50:37.683  6609  6676 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:50:37.683  6609  6676 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:50:37.683  6609  6676 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:50:37.683  6609  6676 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 12:50:37.684  6609  6676 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12939321 added. We now have 1 listener(s)
,07-05 12:50:37.684  1038  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 12:50:37.689  6609  6676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-05 12:50:37.693  6609  6676 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-05 12:50:37.697  6609  6676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 12:50:37.700  6609  6676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 12:50:37.707  6609  6676 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@846a34 added. We now have 1 listener(s)
07-05 12:50:37.707  6609  6676 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 12:50:37.711  1038  1545 D WifiService: New client listening to asynchronous messages
,07-05 12:50:37.714  6609  6676 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 12:50:37.718  6609  6676 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-05 12:50:37.718  6609  6676 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-05 12:50:37.721  6609  6676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 12:50:37.722  1038  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 12:50:37.723  6609  6676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,07-05 12:50:37.731  6609  6676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:50:37.731  6609  6676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:37.731  6609  6676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:50:37.731  6609  6676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:50:37.731  6609  6676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:37.731  6609  6676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:50:37.731  6609  6676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:50:37.731  6609  6676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 12:50:37.731  6609  6676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:50:37.732  6609  6676 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 12:50:37.734  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 12:50:37.735  6609  6676 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 12:50:37.735  6609  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 12:50:37.742  6564  6564 D LgDataFeature: LgDataFeature() Constructor: none
07-05 12:50:37.742  6564  6564 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-05 12:50:37.768  6609  6609 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:50:37.859  6173  6173 I LockScreenSettings: New app installed broadcast received ..
,07-05 12:50:37.862  6173  6173 I LockScreenSettings: Number of installed packages  1
07-05 12:50:37.880  6564  6564 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 12:50:37.932  1038  1887 V SIM_STK : Menu title from STK is T-Mobile
,07-05 12:50:38.002  1038  1924 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6695 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-05 12:50:38.104  6695  6695 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-05 12:50:38.104  6695  6695 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
07-05 12:50:38.159  1038  1973 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6712 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-05 12:50:38.163  1038  1973 I ActivityManager: Killing 5825:com.google.android.gm/u0a64 (adj 15): empty #17
07-05 12:50:38.253  1038  1906 W libprocessgroup: failed to open /acct/uid_10064/pid_5825/cgroup.procs: No such file or directory
07-05 12:50:38.334  6712  6712 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-05 12:50:38.356  6712  6712 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:50:38.363  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-05 12:50:38.398  6441  6441 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-05 12:50:38.400  1038  2008 I ActivityManager: Killing 5669:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-05 12:50:38.401   336   368 E GBMv2   : DFP En is all cleared set to be enabled
07-05 12:50:38.401   336   368 E GBMv2   : Set value is all cleared set the max
07-05 12:50:38.401   336   368 I GBMv2   : DFP Enabled. Ignore VFP set
07-05 12:50:38.415  5627  5627 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-05 12:50:38.415  5627  5627 W System.err: android.os.DeadObjectException
07-05 12:50:38.416  5627  5627 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-05 12:50:38.416  5627  5627 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-05 12:50:38.416  5627  5627 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-05 12:50:38.416  5627  5627 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-05 12:50:38.416  5627  5627 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-05 12:50:38.416  5627  5627 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-05 12:50:38.416  5627  5627 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:50:38.416  5627  5627 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:50:38.416  5627  5627 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 12:50:38.416  5627  5627 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-05 12:50:38.416  5627  5627 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:50:38.416  5627  5627 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:50:38.416  5627  5627 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-05 12:50:38.416  5627  5627 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-05 12:50:38.416  5627  5627 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-05 12:50:38.417  5627  5627 W System.err: android.os.DeadObjectException
07-05 12:50:38.417  5627  5627 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-05 12:50:38.417  5627  5627 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-05 12:50:38.417  5627  5627 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-05 12:50:38.417  5627  5627 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-05 12:50:38.417  5627  5627 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-05 12:50:38.417  5627  5627 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-05 12:50:38.417  5627  5627 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:50:38.417  5627  5627 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:50:38.417  5627  5627 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 12:50:38.417  5627  5627 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-05 12:50:38.417  5627  5627 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:50:38.417  5627  5627 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:50:38.417  5627  5627 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-05 12:50:38.417  5627  5627 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-05 12:50:38.417  5627  5627 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-05 12:50:38.418  5627  5627 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-05 12:50:38.430  6609  6679 W jxcore-log: Initializing JXcore engine
07-05 12:50:38.430  6609  6679 W jxcore-log: JXcore engine is ready
07-05 12:50:38.503  6679  6679 W Thread-752: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7491]" dev="sockfs" ino=7491 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-05 12:50:38.503  6679  6679 W Thread-752: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-05 12:50:38.503  6679  6679 W Thread-752: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7686]" dev="sockfs" ino=7686 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-05 12:50:38.503  6679  6679 W Thread-752: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-05 12:50:38.503  6679  6679 W Thread-752: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30188]" dev="sockfs" ino=30188 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-05 12:50:38.528  6609  6679 W jxcore-log: Starting JXcore engine
07-05 12:50:38.613  6609  6679 W jxcore-log: Platform android
07-05 12:50:38.613  6609  6679 W jxcore-log: 
07-05 12:50:38.613  6609  6679 W jxcore-log: Process ARCH arm
07-05 12:50:38.613  6609  6679 W jxcore-log: 
07-05 12:50:38.642  1038  2052 W libprocessgroup: failed to open /acct/uid_1000/pid_5669/cgroup.procs: No such file or directory
,07-05 12:50:38.643  1038  2052 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
07-05 12:50:38.650  5627  5627 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-05 12:50:38.650  5627  5627 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-05 12:50:38.731  1038  1054 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6735 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-05 12:50:38.739  5627  5627 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-05 12:50:38.795  6735  6735 D UEI.SmartControl: Quickset Services start...
,07-05 12:50:38.798  6735  6735 I UEI.SmartControl: Manufacture = LGE
07-05 12:50:38.798  6735  6735 D UEI.SmartControl: Id = LGNevo
07-05 12:50:38.801  6735  6735 D UEI.SmartControl: File observer start...
07-05 12:50:38.803  6735  6735 E UEI.SmartControl: IR Port is disabled: false
07-05 12:50:38.803  6735  6735 D UEI.SmartControl: Starting file observer...
07-05 12:50:38.803  6735  6735 D UEI.SmartControl: Extracting JNI libs...
07-05 12:50:38.803  6735  6735 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-05 12:50:38.874  6735  6735 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-05 12:50:38.874  6735  6735 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-05 12:50:38.874  6735  6735 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-05 12:50:38.902  6735  6735 I UEI.SmartControl: --- Selecting new region: 6
,07-05 12:50:38.904  6609  6679 I jxcore-log: JXcore Cordova bridge is ready!
07-05 12:50:38.904  6609  6679 I jxcore-log: 
07-05 12:50:38.904  6609  6679 W jxcore-log: JXcore engine is started
07-05 12:50:38.904  6735  6735 I UEI.SmartControl: Model = LG-D855
07-05 12:50:38.906  6735  6735 D UEI.SmartControl: QS Service created
,07-05 12:50:38.907  6609  6676 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-05 12:50:38.909  6609  6609 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-05 12:50:38.923  6735  6735 I UEI.SmartControl: Service initServices...
07-05 12:50:38.927  6735  6735 D UEI.SmartControl: QS start get config
,07-05 12:50:38.987  6735  6735 D UEI.SmartControl: Loading JNI Libs...
,07-05 12:50:39.267  6735  6735 I UEI.SmartControl: Supports setup maps: true
,07-05 12:50:39.270  6735  6735 D UEI.SmartControl: QS start statue = true Error code = 0
07-05 12:50:39.270  6735  6735 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-05 12:50:39.270  6735  6735 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-05 12:50:39.270  6735  6735 I UEI.SmartControl: ### init IR Blaster...
,07-05 12:50:39.282  6735  6735 D serial_port: Configuring serial port
07-05 12:50:39.286  6735  6735 E UEI.SmartControl: UEIBLaster setting for 616
07-05 12:50:39.287  6735  6735 I UEI.SmartControl: Setting serial record hearder size = 2
07-05 12:50:39.287  6735  6735 I UEI.SmartControl: configuring settings for MAXQ616
07-05 12:50:39.287  6735  6735 I UEI.SmartControl: Get version...
,07-05 12:50:39.304  6735  6765 D UEI.SmartControl: serial port data available: 21
,07-05 12:50:39.333  6735  6735 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-05 12:50:39.333  6735  6735 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-05 12:50:39.333  6735  6735 I UEI.SmartControl: QS saving settings...
07-05 12:50:39.334  6735  6735 D UEI.SmartControl: IR Blaster version: 25672567
,07-05 12:50:39.347  6735  6765 D UEI.SmartControl: serial port data available: 4
,07-05 12:50:39.383  6735  6735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-05 12:50:39.393  6735  6768 I UEI.SmartControl: Device manager: loading config....
07-05 12:50:39.393  6735  6768 D UEI.SmartControl: ----------- loading internal config...
07-05 12:50:39.397  6735  6735 E UEI.SmartControl: Services init done
07-05 12:50:39.397  6735  6735 D UEI.SmartControl: QS Service init finished
,07-05 12:50:39.400  6735  6735 D UEI.SmartControl: QS Service version name: 2.1.91
07-05 12:50:39.400  6735  6735 D UEI.SmartControl: QS Service version code: 201091
07-05 12:50:39.401  6735  6735 D UEI.SmartControl: Service requested: Control
07-05 12:50:39.404  6735  6768 E UEI.SmartControl: Loading SETTINGS...
07-05 12:50:39.407  6735  6735 D UEI.SmartControl: Request IControl service: devices are loaded...
07-05 12:50:39.410  1038  1924 I ActivityManager: Killing 5627:com.lge.qremote/u0a112 (adj 15): empty #17
,07-05 12:50:39.422  6735  6768 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-05 12:50:39.433  6735  6767 I UEI.SmartControl: Notify AllClients services are ready: 0
07-05 12:50:39.433  6735  6767 D UEI.SmartControl: -----service ready thread exits
07-05 12:50:39.493  1038  2036 W libprocessgroup: failed to open /acct/uid_10112/pid_5627/cgroup.procs: No such file or directory
,07-05 12:50:39.497  6735  6735 D UEI.SmartControl: Internal service binding...
07-05 12:50:39.553  1038  1742 I ActivityManager: Killing 5872:com.google.android.talk/u0a72 (adj 15): empty #17
,07-05 12:50:39.692  1038  2052 W libprocessgroup: failed to open /acct/uid_10072/pid_5872/cgroup.procs: No such file or directory
,07-05 12:50:41.808  6564  6564 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-05 12:50:41.814  1038  1054 I ActivityManager: Killing 6280:com.android.calendar/u0a13 (adj 15): empty #17
07-05 12:50:41.950  1038  1602 W libprocessgroup: failed to open /acct/uid_10013/pid_6280/cgroup.procs: No such file or directory
,07-05 12:50:42.817  6564  6680 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 12:50:44.364  6735  6766 D serial_port: close(fd = 25)
,07-05 12:50:44.371  6735  6766 I UEI.SmartControl: Serial port is closed.
07-05 12:50:44.382  6735  6769 D UEI.SmartControl: Internal timer expired: 1
07-05 12:50:44.382  6735  6769 D UEI.SmartControl: unbind internal service
,07-05 12:50:44.389  6735  6735 D UEI.SmartControl: Service.onUnbind: IControl
07-05 12:50:44.389  6735  6735 D UEI.SmartControl: Service.onDestroy
07-05 12:50:44.390  6735  6735 D UEI.SmartControl: Lock is in USE false
07-05 12:50:44.390  6735  6735 D UEI.SmartControl: unbind internal service
07-05 12:50:44.390  6735  6735 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@16874e72
07-05 12:50:44.390  6735  6735 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-05 12:50:44.390  6735  6735 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-05 12:50:44.390  6735  6735 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-05 12:50:44.390  6735  6735 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-05 12:50:44.390  6735  6735 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-05 12:50:44.391  6735  6735 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-05 12:50:44.391  6735  6735 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-05 12:50:44.391  6735  6735 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-05 12:50:44.391  6735  6735 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:50:44.391  6735  6735 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 12:50:44.391  6735  6735 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-05 12:50:44.392  6735  6735 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:50:44.392  6735  6735 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:50:44.392  6735  6735 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-05 12:50:44.392  6735  6735 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-05 12:50:44.392  6735  6735 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@16874e72
07-05 12:50:44.392  6735  6735 I UEI.SmartControl: Serial port is closed.
07-05 12:50:44.392  6735  6735 I UEI.SmartControl: Serial port is closed.
,07-05 12:50:44.392  6735  6735 D UEI.SmartControl: Blaster closed
,07-05 12:50:44.392  6735  6735 D UEI.SmartControl: Shut down QS...
07-05 12:50:44.392  6735  6735 D UEI.SmartControl: Stopping QS lib
07-05 12:50:44.392  6735  6735 D UEI.SmartControl: QS lib stop result = true
07-05 12:50:44.393  6735  6735 D UEI.SmartControl: Stopped QS lib
07-05 12:50:44.393  6735  6735 D UEI.SmartControl: Stopped file observer...,
07-05 12:50:44.393  6735  6735 D UEI.SmartControl: QS shutdown complete
,07-05 12:50:45.258  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,07-05 12:50:45.269  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
07-05 12:50:45.343  1817  6476 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-05 12:50:45.351   313  6774 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-05 12:50:45.351   313  6774 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-05 12:50:45.352   313  6774 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-05 12:50:45.589  1817  1817 I ConfigFetchService: fetch service done; releasing wakelock
,07-05 12:50:45.591  1817  1817 I ConfigFetchService: stopping self
07-05 12:50:45.594  2207  2207 I ConfigService: onDestroy
,07-05 12:50:49.066  6609  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 12:50:49.066  6609  6679 I jxcore-log: 
,07-05 12:50:49.069  6609  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 12:50:49.069  6609  6679 I jxcore-log: 
07-05 12:50:49.073  6609  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:50:49.073  6609  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:49.073  6609  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:50:49.073  6609  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:50:49.073  6609  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:49.073  6609  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:50:49.073  6609  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:50:49.073  6609  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 12:50:49.075  6609  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-05 12:50:49.077  6609  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 12:50:49.077  6609  6679 I jxcore-log: 
07-05 12:50:49.079  6609  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 12:50:49.079  6609  6679 I jxcore-log: 
,07-05 12:50:49.402  6609  6679 I jxcore-log: Unit Test app is loaded
07-05 12:50:49.402  6609  6679 I jxcore-log: 
,07-05 12:50:49.410  6609  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 12:50:49.410  6609  6679 I jxcore-log: 
07-05 12:50:49.414  6609  6679 I jxcore-log: My device name is: LGE-LG-D855
07-05 12:50:49.414  6609  6679 I jxcore-log: 
07-05 12:50:49.416  6609  6679 I jxcore-log: WARN testUtils: myNameCallback not set!
07-05 12:50:49.416  6609  6679 I jxcore-log: 
,07-05 12:50:49.432  6609  6609 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 12:50:50.496  1038  1105 I ActivityManager: Waited long enough for: ServiceRecord{286bd283 u0 com.google.android.gms/.wearable.service.WearableService}
,07-05 12:50:53.264  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 12:50:53.264  6609  6679 I jxcore-log: 
,07-05 12:50:53.653  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 12:50:53.653  6609  6679 I jxcore-log: 
,07-05 12:50:53.679  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 12:50:53.679  6609  6679 I jxcore-log: 
,07-05 12:50:53.683  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 12:50:53.683  6609  6679 I jxcore-log: 
,07-05 12:50:53.698  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 12:50:53.698  6609  6679 I jxcore-log: 
,07-05 12:50:53.702  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 12:50:53.702  6609  6679 I jxcore-log: 
07-05 12:50:55.668  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 12:50:55.668  6609  6679 I jxcore-log: 
,07-05 12:50:55.680  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 12:50:55.680  6609  6679 I jxcore-log: 
07-05 12:50:55.690  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 12:50:55.690  6609  6679 I jxcore-log: 
,07-05 12:50:55.841  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 12:50:55.841  6609  6679 I jxcore-log: 
,07-05 12:50:55.923  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 12:50:55.923  6609  6679 I jxcore-log: 
,07-05 12:50:55.979  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 12:50:55.979  6609  6679 I jxcore-log: 
,07-05 12:50:55.986  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 12:50:55.986  6609  6679 I jxcore-log: 
,07-05 12:50:56.175  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 12:50:56.175  6609  6679 I jxcore-log: 
,07-05 12:50:56.198  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 12:50:56.198  6609  6679 I jxcore-log: 
,07-05 12:50:56.203  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 12:50:56.203  6609  6679 I jxcore-log: 
,07-05 12:50:56.209  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 12:50:56.209  6609  6679 I jxcore-log: 
,07-05 12:50:56.223  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 12:50:56.223  6609  6679 I jxcore-log: 
,07-05 12:50:56.242  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 12:50:56.242  6609  6679 I jxcore-log: 
,07-05 12:50:56.323  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 12:50:56.323  6609  6679 I jxcore-log: 
,07-05 12:50:56.330  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 12:50:56.330  6609  6679 I jxcore-log: 
,07-05 12:50:56.355  6609  6679 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 12:50:56.355  6609  6679 I jxcore-log: 
,07-05 12:50:56.365  6609  6679 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
07-05 12:50:56.366  6609  6679 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-05 12:50:56.366  6609  6679 I jxcore-log: 
07-05 12:50:59.842  1038  1381 V AlarmManager: RTC_WAKEUP set : Alarm{3edd38d9 type 0 when 1467715850870 com.android.vending} when 1467715850870
,07-05 12:50:59.914  1038  1982 V SIM_STK : Menu title from STK is T-Mobile
,07-05 12:51:00.036  6121  6121 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-05 12:51:00.055  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:51:00.055  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:51:00.055  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:51:00.055  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:51:00.058  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:51:00.058  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:51:00.059  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:51:00.060  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:52:00.040  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:52:00.040  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:52:00.040  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:52:00.041  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:52:00.053  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:52:00.053  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:52:00.056  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:52:00.058  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:53:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:53:00.051  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:53:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:53:00.052  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:53:00.064  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:53:00.064  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:53:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:53:00.068  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:53:21.624  1038  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1066723881, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,07-05 12:53:21.635  1038  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3c59829e type 2 when 247754 android} when 247754
07-05 12:53:21.676  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 12:53:21.710  1038  1038 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1066723881 [*alarm*], flags=0x0
,07-05 12:53:38.204  1606  1606 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:53:38.204  1606  1606 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:53:38.219  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:53:38.219  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:53:38.222  1038  1545 D WifiController: battery changed pluggedType: 2
07-05 12:53:38.225  1943  2124 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:53:38.225  1943  2124 D LEDHandler: Battery Level Remaining: 100%
07-05 12:53:38.225  1943  2124 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
07-05 12:53:38.222  3870  3987 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:53:38.226  1606  1606 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
07-05 12:53:38.227  1606  1606 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:53:38.228  1606  1606 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:53:38.234  6712  6712 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-05 12:54:00.052  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:54:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:54:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:54:00.053  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:54:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:54:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:54:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:54:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:54:04.560  1038  3555 I LocationManagerService: remove 35a4741f
,07-05 12:54:04.568  1038  3555 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-05 12:54:04.569  1038  3555 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-05 12:54:04.570  1038  3555 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-05 12:54:04.573  1038  3555 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-05 12:54:04.576  1038  3555 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-05 12:54:15.450  1038  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1066723881, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,07-05 12:54:15.506  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 12:54:15.538  1038  1038 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1066723881 [*alarm*], flags=0x0
,07-05 12:54:15.862  1038  1742 I art     : Explicit concurrent mark sweep GC freed 22184(1148KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.646ms total 84.839ms
,07-05 12:55:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:55:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:55:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:55:00.052  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:55:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:55:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:55:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:55:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:56:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:56:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:56:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:56:00.052  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:56:00.064  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:56:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:56:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:56:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:57:00.053  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:57:00.053  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:57:00.053  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:57:00.054  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:57:00.066  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:57:00.066  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:57:00.068  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:57:00.070  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:58:00.052  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:58:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:58:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:58:00.053  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:58:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:58:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:58:00.068  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:58:00.070  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:59:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:59:00.051  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:59:00.051  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 12:59:00.052  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:59:00.064  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:59:00.064  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:59:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:59:00.068  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:00:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:00:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:00:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:00:00.052  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:00:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:00:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:00:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:00:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:00:01.927  1038  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1066723881, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,07-05 13:00:02.002  1038  1105 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6831 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-05 13:00:02.034  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 13:00:02.156  6831  6831 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-05 13:00:02.159  6831  6831 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1c05854b
07-05 13:00:02.160  1038  1038 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1066723881 [*alarm*], flags=0x0
07-05 13:00:02.162  1038  2052 I ActivityManager: Killing 6246:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-05 13:00:02.203  1038  1906 W libprocessgroup: failed to open /acct/uid_10014/pid_6246/cgroup.procs: No such file or directory
,07-05 13:00:42.833  1038  1906 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
,07-05 13:00:42.866   317   317 V AudioFlinger: 2127 died, releasing its sessions
07-05 13:00:42.866   317   317 V AudioFlinger:  pid 1853 @ 0
07-05 13:00:42.866   317   317 V AudioFlinger:  pid 3497 @ 1
07-05 13:00:42.866   317   317 V AudioFlinger:  pid 3497 @ 2
,07-05 13:00:42.900  1038  1602 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
,07-05 13:01:00.052  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:01:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:01:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:01:00.053  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:01:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:01:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:01:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:01:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:02:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:02:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:02:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:02:00.052  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:02:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:02:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:02:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:02:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:03:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-05 13:03:00.051  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:03:00.057  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:03:00.057  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
07-05 13:03:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:03:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:03:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:03:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 13:04:00.052  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:04:00.053  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:04:00.053  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:04:00.053  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:04:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:04:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:04:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:04:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:04:11.569  1038  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1066723881, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,07-05 13:04:11.595  1038  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c1cf17f type 2 when 942028 com.android.bluetooth} when 942028
,07-05 13:04:11.606  3870  4063 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-05 13:04:11.606  3870  4063 W bt-smp  : Plain text(LSB ~ MSB) = 2c 01 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-05 13:04:11.606  3870  4063 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 6c b5 46 c3 8b ed 27 8b c4 e9 95 64 50 09 92 
07-05 13:04:11.606  3870  4063 W bt-btm  : Stopping oneshot timer
07-05 13:04:11.637  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 13:04:11.664  1038  1038 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1066723881 [*alarm*], flags=0x0
,07-05 13:05:00.050  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:05:00.050  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:05:00.051  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-05 13:05:00.057  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
07-05 13:05:00.064  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:05:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:05:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:05:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:05:03.789  1038  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1066723881, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,07-05 13:05:03.803  1038  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1121b54c type 2 when 960807 com.google.android.gms} when 960807
,07-05 13:05:03.848  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,07-05 13:05:03.880  1038  1038 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1066723881 [*alarm*], flags=0x0
,07-05 13:05:03.958  2207  5719 D GCM     : Message class com.google.e.a.a.h
07-05 13:06:00.053  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:06:00.053  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:06:00.053  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:06:00.054  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:06:00.066  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:06:00.066  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:06:00.068  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:06:00.070  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:07:00.065  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:07:00.065  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:07:00.066  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:07:00.066  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:07:00.078  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:07:00.078  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:07:00.081  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:07:00.084  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 13:08:00.099  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:08:00.100  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:08:00.100  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:08:00.100  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:08:00.113  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:08:00.114  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:08:00.116  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:08:00.118  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:08:49.522  1038  1102 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 13:09:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:09:00.051  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:09:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:09:00.052  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:09:00.064  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:09:00.064  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:09:00.066  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:09:00.068  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:10:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:10:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:10:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:10:00.052  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:10:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:10:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:10:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:10:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:11:00.052  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:11:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:11:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:11:00.053  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:11:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:11:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:11:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:11:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:12:00.052  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:12:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:12:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:12:00.053  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:12:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:12:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:12:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:12:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:13:00.051  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:13:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:13:00.052  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:13:00.052  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:13:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:13:00.065  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:13:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:13:00.069  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:14:00.052  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:14:00.052  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:14:00.053  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-05 13:14:00.053  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
