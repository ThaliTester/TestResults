#### Test 82894682929afb6_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-31 08:51:40.757  6458  6458 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
--------- beginning of system
08-31 08:51:40.762  6458  6458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-31 08:51:40.782  4610  6592 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-31 08:51:40.829  1069  1931 V SIM_STK : Menu title from STK is T-Mobile
08-31 08:51:40.839  1069  1885 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6595 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:51:40.945  4610  6592 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 163 ms] updated apps [took 163 ms] 
08-31 08:51:41.096  6595  6595 D DocsApplication: Installing DEX configuration.
08-31 08:51:41.125  6595  6595 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-31 08:51:41.130  6595  6595 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{f91b01 com.google.android.apps.docs}
08-31 08:51:41.145  6595  6595 D TAG     : onCreate()
08-31 08:51:41.172  6595  6595 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-31 08:51:41.607   333   414 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-31 08:51:41.610  3190  6620 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-31 08:51:41.911  6621  6621 D AndroidRuntime: 
08-31 08:51:41.911  6621  6621 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 08:51:41.913  6621  6621 D AndroidRuntime: CheckJNI is OFF
08-31 08:51:41.949  1799  4763 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-31 08:51:42.002  1799  4763 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-31 08:51:42.032  6621  6621 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 08:51:42.036  1069  1985 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 08:51:42.047  1922  1939 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 08:51:42.050  1069  1985 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 08:51:42.051  1069  1985 D ActivityManager: setTaskToReturnTo : TaskRecord{34114e80 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 08:51:42.051  1069  1985 D ActivityManager: setTaskToReturnTo : TaskRecord{34114e80 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 08:51:42.052  1069  1985 D WindowStateEx: AppWindowTokenEx init.. 
08-31 08:51:42.053   342   355 E GBMv2   : DFP En is all cleared set to be enabled
08-31 08:51:42.082  1069  1985 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6648 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 08:51:42.083  6621  6621 D AndroidRuntime: Shutting down VM
08-31 08:51:42.109  1799  4763 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-31 08:51:42.142  1922  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 08:51:42.142  1922  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{abb334d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 08:51:42.143  1922  1939 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 08:51:42.143  1922  1939 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15e47e02 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 08:51:42.205  6648  6648 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-31 08:51:42.275  6648  6648 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-31 08:51:42.282  6648  6648 I LibraryLoader: Loading: webviewchromium
08-31 08:51:42.285  6648  6648 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3435-3438)
08-31 08:51:42.285  6648  6648 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 08:51:42.296  6648  6648 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2473b783}
08-31 08:51:42.297  6648  6648 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 08:51:42.297  6648  6648 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 08:51:42.305  6648  6648 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 08:51:42.306  6648  6648 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 08:51:42.319  6648  6648 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-31 08:51:42.326  6648  6648 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-31 08:51:42.326  6648  6648 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-31 08:51:42.329   321   321 V AudioPolicyService: registerClient() client 0xb14e9f80, uid 10118
08-31 08:51:42.336  6648  6648 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 08:51:42.336  6648  6648 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 08:51:42.336  6648  6648 I Adreno-EGL: Build Date: 12/12/14 금
08-31 08:51:42.336  6648  6648 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 08:51:42.336  6648  6648 I Adreno-EGL: Remote Branch: 
08-31 08:51:42.336  6648  6648 I Adreno-EGL: Local Patches: 
08-31 08:51:42.336  6648  6648 I Adreno-EGL: Reconstruct Branch: 
,08-31 08:51:42.356  1069  1165 D BluetoothManagerService: Message: 20
,08-31 08:51:42.356  1069  1165 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ea1f70a:true
08-31 08:51:42.423  6648  6683 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-31 08:51:42.429  6648  6648 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-31 08:51:42.442  6648  6648 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 08:51:42.446  6648  6648 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 08:51:42.449  6648  6648 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 08:51:42.451  6648  6648 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 08:51:42.451  6648  6648 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-31 08:51:42.462  6648  6648 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 08:51:42.469  6648  6648 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 08:51:42.469  6648  6648 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 08:51:42.512  6595  6595 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:51:42.512  6595  6595 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 08:51:42.516  6648  6695 D OpenGLRenderer: Render dirty regions requested: true
08-31 08:51:42.516  6648  6695 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 08:51:42.529  6648  6695 D OpenGLRenderer: Enabling debug mode 0
,08-31 08:51:42.537  6648  6648 D Atlas   : Validating map...
08-31 08:51:42.542  1069  1935 D SplitWindow: check instance of lgWin Window{1b838d74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 08:51:42.602  6648  6693 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 08:51:42.603  6648  6693 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 08:51:42.627  1069  1166 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +487ms (total +573ms)
,08-31 08:51:42.628  6648  6648 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30b8602e time:103781
08-31 08:51:42.628  1069  1166 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{28499cb9 u0 com.test.thalitest/.MainActivity t6} time:103781
08-31 08:51:42.636  6204  6204 I LockScreenSettings: New app installed broadcast received ..
08-31 08:51:42.638  6204  6204 I LockScreenSettings: Number of installed packages  1
08-31 08:51:42.651  6595  6595 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-31 08:51:42.672  1069  1931 V SIM_STK : Menu title from STK is T-Mobile
,08-31 08:51:42.722  1069  1954 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6718 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 08:51:42.742  6648  6648 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 08:51:42.768  6718  6718 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-31 08:51:42.768  6718  6718 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-31 08:51:42.776  6648  6648 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 08:51:42.776  6648  6648 I chromium: 
08-31 08:51:42.797  6648  6693 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 08:51:42.797  6648  6693 I chromium: 
,08-31 08:51:42.813  1069  2014 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6735 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-31 08:51:42.814  1069  2014 I ActivityManager: Killing 5692:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-31 08:51:42.828  5668  5668 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 08:51:42.828  5668  5668 W System.err: android.os.DeadObjectException
,08-31 08:51:42.828  5668  5668 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 08:51:42.828  5668  5668 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 08:51:42.828  5668  5668 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 08:51:42.828  5668  5668 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 08:51:42.828  5668  5668 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 08:51:42.828  5668  5668 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 08:51:42.828  5668  5668 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 08:51:42.828  5668  5668 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 08:51:42.828  5668  5668 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:51:42.828  5668  5668 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:51:42.828  5668  5668 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:42.828  5668  5668 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:42.828  5668  5668 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:51:42.829  5668  5668 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:51:42.829  5668  5668 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 08:51:42.829  5668  5668 W System.err: android.os.DeadObjectException
08-31 08:51:42.829  5668  5668 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 08:51:42.829  5668  5668 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 08:51:42.829  5668  5668 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 08:51:42.829  5668  5668 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 08:51:42.829  5668  5668 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 08:51:42.829  5668  5668 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 08:51:42.829  5668  5668 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 08:51:42.829  5668  5668 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 08:51:42.829  5668  5668 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:51:42.829  5668  5668 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:51:42.829  5668  5668 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:42.829  5668  5668 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:42.829  5668  5668 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:51:42.829  5668  5668 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:51:42.829  5668  5668 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 08:51:42.830  5668  5668 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-31 08:51:42.899  6648  6752 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435128832
,08-31 08:51:42.912  6648  6752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 08:51:42.912  6648  6752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 08:51:42.912  6648  6752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 08:51:42.912  6648  6752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 08:51:42.912  6648  6752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 08:51:42.912  6648  6752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2829cd92 added. We now have 1 listener(s)
08-31 08:51:42.929  1069  1597 W libprocessgroup: failed to open /acct/uid_1000/pid_5692/cgroup.procs: No such file or directory
,08-31 08:51:42.929  1069  1597 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-31 08:51:42.932  5668  5668 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 08:51:42.932  5668  5668 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 08:51:42.941  1069  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 08:51:42.946  6648  6752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-31 08:51:42.948  6648  6752 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:51:42.950  6648  6752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:51:42.950  6648  6752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 08:51:42.970  6648  6752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fd3b819 added. We now have 1 listener(s)
08-31 08:51:42.971  6648  6752 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:51:42.982  1069  1385 D WifiService: New client listening to asynchronous messages
08-31 08:51:42.993  6648  6752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:51:42.993  6648  6752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 08:51:42.994  6648  6752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 08:51:42.994  6648  6752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 08:51:42.996  6648  6752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 08:51:42.997  1069  1954 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6755 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 08:51:42.998  5668  5668 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 08:51:43.000  6648  6752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:43.000  1069  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:51:43.001  6648  6752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-31 08:51:43.010  6648  6752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 08:51:43.010  6648  6752 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:43.010  6648  6752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:43.010  6648  6752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:43.010  6648  6752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:43.010  6648  6752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:43.010  6648  6752 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:43.010  6648  6752 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:43.010  6648  6752 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:43.011  6648  6752 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 08:51:43.011  6648  6752 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:51:43.012  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:43.014  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:43.015  6648  6752 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 08:51:43.029  6735  6735 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-31 08:51:43.045  6755  6755 D UEI.SmartControl: Quickset Services start...
08-31 08:51:43.046  6755  6755 I UEI.SmartControl: Manufacture = LGE
08-31 08:51:43.047  6755  6755 D UEI.SmartControl: Id = LGNevo
08-31 08:51:43.047  6755  6755 D UEI.SmartControl: File observer start...
08-31 08:51:43.048  6755  6755 E UEI.SmartControl: IR Port is disabled: false
08-31 08:51:43.048  6755  6755 D UEI.SmartControl: Starting file observer...
08-31 08:51:43.048  6755  6755 D UEI.SmartControl: Extracting JNI libs...
08-31 08:51:43.048  6755  6755 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 08:51:43.050  6735  6735 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 08:51:43.052  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 08:51:43.052  6648  6648 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-31 08:51:43.082  1069  1976 I ActivityManager: Killing 5845:com.google.android.gm/u0a64 (adj 15): empty #17
,08-31 08:51:43.118  6755  6755 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 08:51:43.118  6755  6755 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-31 08:51:43.118  6755  6755 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-31 08:51:43.142  6755  6755 I UEI.SmartControl: --- Selecting new region: 6
08-31 08:51:43.143  6755  6755 I UEI.SmartControl: Model = LG-D855
08-31 08:51:43.144  6755  6755 D UEI.SmartControl: QS Service created
,08-31 08:51:43.181  1069  1935 W libprocessgroup: failed to open /acct/uid_10064/pid_5845/cgroup.procs: No such file or directory
,08-31 08:51:43.214  6755  6755 I UEI.SmartControl: Service initServices...
,08-31 08:51:43.219  6755  6755 D UEI.SmartControl: QS start get config
,08-31 08:51:43.283  6755  6755 D UEI.SmartControl: Loading JNI Libs...
,08-31 08:51:43.594  6755  6755 I UEI.SmartControl: Supports setup maps: true
,08-31 08:51:43.598  6755  6755 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 08:51:43.599  6755  6755 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 08:51:43.599  6755  6755 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 08:51:43.599  6755  6755 I UEI.SmartControl: ### init IR Blaster...
08-31 08:51:43.604  6755  6755 D serial_port: Configuring serial port
08-31 08:51:43.608  6755  6755 E UEI.SmartControl: UEIBLaster setting for 616
08-31 08:51:43.608  6755  6755 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 08:51:43.608  6755  6755 I UEI.SmartControl: configuring settings for MAXQ616
08-31 08:51:43.608  6755  6755 I UEI.SmartControl: Get version...
,08-31 08:51:43.614   342   357 E GBMv2   : DFP En is all cleared set to be enabled
08-31 08:51:43.614   342   357 E GBMv2   : Set value is all cleared set the max
08-31 08:51:43.615   342   357 I GBMv2   : DFP Enabled. Ignore VFP set
08-31 08:51:43.627  6755  6778 D UEI.SmartControl: serial port data available: 21
,08-31 08:51:43.654  6755  6755 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 08:51:43.654  6755  6755 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 08:51:43.654  6755  6755 I UEI.SmartControl: QS saving settings...
08-31 08:51:43.655  6755  6755 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 08:51:43.671  6755  6778 D UEI.SmartControl: serial port data available: 4
,08-31 08:51:43.697  6648  6772 W jxcore-log: Initializing JXcore engine
08-31 08:51:43.697  6648  6772 W jxcore-log: JXcore engine is ready
,08-31 08:51:43.720  6755  6755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 08:51:43.722  6755  6755 E UEI.SmartControl: Services init done
08-31 08:51:43.722  6755  6755 D UEI.SmartControl: QS Service init finished
08-31 08:51:43.725  6755  6755 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 08:51:43.726  6755  6781 I UEI.SmartControl: Device manager: loading config....
08-31 08:51:43.726  6755  6781 D UEI.SmartControl: ----------- loading internal config...
08-31 08:51:43.727  6755  6755 D UEI.SmartControl: QS Service version code: 201091
08-31 08:51:43.728  6755  6755 D UEI.SmartControl: Service requested: Control
08-31 08:51:43.720  6772  6772 W Thread-762: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10244]" dev="sockfs" ino=10244 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 08:51:43.720  6772  6772 W Thread-762: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-31 08:51:43.720  6772  6772 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10311]" dev="sockfs" ino=10311 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 08:51:43.720  6772  6772 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 08:51:43.720  6772  6772 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31964]" dev="sockfs" ino=31964 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-31 08:51:43.745  6648  6772 W jxcore-log: Starting JXcore engine
08-31 08:51:43.753  6755  6781 E UEI.SmartControl: Loading SETTINGS...
,08-31 08:51:43.757  6755  6755 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 08:51:43.760  1069  1954 I ActivityManager: Killing 5668:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 08:51:43.765  6755  6781 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 08:51:43.782  6755  6780 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-31 08:51:43.782  6755  6780 D UEI.SmartControl: -----service ready thread exits
08-31 08:51:43.819  6648  6772 W jxcore-log: Platform android
08-31 08:51:43.819  6648  6772 W jxcore-log: 
08-31 08:51:43.819  6648  6772 W jxcore-log: Process ARCH arm
08-31 08:51:43.819  6648  6772 W jxcore-log: 
,08-31 08:51:43.848  1069  2014 W libprocessgroup: failed to open /acct/uid_10112/pid_5668/cgroup.procs: No such file or directory
,08-31 08:51:43.849  6755  6755 D UEI.SmartControl: Internal service binding...
08-31 08:51:44.008  6648  6772 I jxcore-log: JXcore Cordova bridge is ready!
08-31 08:51:44.008  6648  6772 I jxcore-log: 
08-31 08:51:44.009  6648  6772 W jxcore-log: JXcore engine is started
,08-31 08:51:44.019  6648  6752 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 08:51:44.022  6648  6648 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 08:51:45.687  2768  2768 I MusicWidget: mDelayedStopHandler : unbind
,08-31 08:51:45.689  2110  2110 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-31 08:51:45.689  2110  2110 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-31 08:51:45.690  2110  2110 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,08-31 08:51:45.694  2110  2110 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-31 08:51:45.695  2110  2110 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-31 08:51:45.695  2110  2110 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-31 08:51:45.707  2110  2110 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-31 08:51:45.708  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-31 08:51:45.709  1069  1976 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3dde630com.lge.music.MediaPlaybackService$5@3abdd2a9
08-31 08:51:45.712  2110  2110 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-31 08:51:45.712  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.713  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.713  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.713  2110  2110 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@13048df
08-31 08:51:45.713  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.714  2110  2110 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-31 08:51:45.714  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.714  2110  2110 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-31 08:51:45.714  2110  2110 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-31 08:51:45.714  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.715  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.715  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.715  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.716  2110  2110 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 08:51:45.716  2110  2110 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-31 08:51:45.717  2110  2110 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-31 08:51:45.718  2110  2110 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-31 08:51:45.718  2110  2110 V MediaPlayer[Native]: reset
08-31 08:51:45.721  2110  2110 V MediaPlayer[Native]: setListener
08-31 08:51:45.721  2110  2110 V MediaPlayer[Native]: disconnect
08-31 08:51:45.721  2110  2110 V MediaPlayer[Native]: destructor
08-31 08:51:45.722   321  3959 V AudioFlinger: releasing 16 from 2110 for -1
08-31 08:51:45.722   321  3959 V AudioFlinger:  decremented refcount to 0
08-31 08:51:45.722   321  3959 V AudioFlinger: purging stale effects
08-31 08:51:45.722  2110  2110 V MediaPlayer[Native]: disconnect
08-31 08:51:45.723  2110  2110 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-31 08:51:45.723  2110  2110 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-31 08:51:45.724  2110  2110 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-31 08:51:45.724  2110  2110 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-31 08:51:45.724  2110  2110 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-31 08:51:45.725  2110  2110 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-31 08:51:45.725  2110  2110 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 817389614
08-31 08:51:45.725  2110  2110 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 817389614
08-31 08:51:45.738  2110  2110 I SmartShareClient: [SmartShareManagerClient] terminate service: 2110/MediaPlaybackService/190539325
08-31 08:51:45.740  2110  2110 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-31 08:51:45.740  2110  2110 I Smart,ShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3d6327cf
,08-31 08:51:45.743  2110  2110 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-31 08:51:45.743  2110  2110 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-31 08:51:45.744  2110  2110 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-31 08:51:45.745  2110  2110 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-31 08:51:45.746  1069  1084 I ActivityManager: Killing 5892:com.google.android.talk/u0a72 (adj 15): empty #17
08-31 08:51:45.754  2110  2110 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,08-31 08:51:45.818  1069  1597 W libprocessgroup: failed to open /acct/uid_10072/pid_5892/cgroup.procs: No such file or directory
,08-31 08:51:46.575  6595  6595 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-31 08:51:46.581  1069  1931 I ActivityManager: Killing 6310:com.android.calendar/u0a13 (adj 15): empty #17
08-31 08:51:46.668  1069  1904 W libprocessgroup: failed to open /acct/uid_10013/pid_6310/cgroup.procs: No such file or directory
,08-31 08:51:47.580  6595  6700 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-31 08:51:48.715  6755  6779 D serial_port: close(fd = 25)
,08-31 08:51:48.720  6755  6782 D UEI.SmartControl: Internal timer expired: 1
,08-31 08:51:48.720  6755  6782 D UEI.SmartControl: unbind internal service
08-31 08:51:48.729  6755  6755 D UEI.SmartControl: Service.onUnbind: IControl
08-31 08:51:48.730  6755  6755 D UEI.SmartControl: Service.onDestroy
08-31 08:51:48.730  6755  6755 D UEI.SmartControl: Lock is in USE false
08-31 08:51:48.730  6755  6755 D UEI.SmartControl: unbind internal service
08-31 08:51:48.731  6755  6755 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@13048df
08-31 08:51:48.732  6755  6755 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 08:51:48.732  6755  6755 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
,08-31 08:51:48.732  6755  6755 W System.err: ,	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 08:51:48.732  6755  6755 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-31 08:51:48.732  6755  6755 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
,08-31 08:51:48.732  6755  6755 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
,08-31 08:51:48.732  6755  6755 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 08:51:48.732  6755  6755 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 08:51:48.733  6755  6755 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:48.733  6755  6755 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:51:48.733  6755  6755 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:51:48.733  6755  6755 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:48.733  6755  6755 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:51:48.733  6755  6755 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:51:48.733  6755  6755 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:51:48.733  6755  6755 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@13048df
,08-31 08:51:48.752  6755  6779 I UEI.SmartControl: Serial port is closed.
08-31 08:51:48.753  6755  6755 I UEI.SmartControl: Serial port is closed.
08-31 08:51:48.753  6755  6755 I UEI.SmartControl: Serial port is closed.
08-31 08:51:48.754  6755  6755 D UEI.SmartControl: Blaster closed
,08-31 08:51:48.754  6755  6755 D UEI.SmartControl: Shut down QS...
08-31 08:51:48.766  6755  6755 D UEI.SmartControl: Stopping QS lib
08-31 08:51:48.767  6755  6755 D UEI.SmartControl: QS lib stop result = true
08-31 08:51:48.767  6755  6755 D UEI.SmartControl: Stopped QS lib
,08-31 08:51:48.769  6755  6755 D UEI.SmartControl: Stopped file observer...
08-31 08:51:48.769  6755  6755 D UEI.SmartControl: QS shutdown complete
08-31 08:51:50.102  1799  6512 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-31 08:51:50.117   317  6797 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 08:51:50.117   317  6797 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-31 08:51:50.164   317  6797 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-31 08:51:50.382  1799  1799 I ConfigFetchService: fetch service done; releasing wakelock
,08-31 08:51:50.387  1799  1799 I ConfigFetchService: stopping self
,08-31 08:51:50.391  2203  2203 I ConfigService: onDestroy
,08-31 08:51:53.747  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 08:51:53.747  6648  6772 I jxcore-log: 
,08-31 08:51:53.750  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 08:51:53.750  6648  6772 I jxcore-log: 
08-31 08:51:53.755  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:53.755  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:53.755  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:53.755  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:53.755  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:53.755  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:53.755  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:53.755  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:53.758  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:53.760  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 08:51:53.760  6648  6772 I jxcore-log: 
,08-31 08:51:53.762  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 08:51:53.762  6648  6772 I jxcore-log: 
,08-31 08:51:54.263  6648  6772 D executeNativeTests: Running unit tests
,08-31 08:51:54.346  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 08:51:54.346  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 added. We now have 2 listener(s)
,08-31 08:51:54.346  1069  1084 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 08:51:54.348  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-31 08:51:54.349  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:51:54.349  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 08:51:54.349  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:51:54.349  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 added. We now have 2 listener(s)
,08-31 08:51:54.349  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:54.349  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:51:54.351  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:54.359  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:54.359  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:54.359  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:54.359  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:54.359  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:54.359  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:54.359  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:54.359  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:54.360  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:54.361  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:54.362  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.363  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.366  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 08:51:54.366  6648  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:51:54.366  6648  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:51:54.368  6648  6772 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 08:51:54.368  6648  6772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 08:51:54.368  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:51:54.368  6648  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:54.368  6648  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:54.369  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.370  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.370  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.370  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.371  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.371  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:54.371  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:51:54.371  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 removed from the list
08-31 08:51:54.371  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.371  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 removed from the list
08-31 08:51:54.371  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.371  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.372  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.372  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.373  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.373  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.373  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.374  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Di,scoveryManager@50deb73 not in the list
,08-31 08:51:54.376  6648  6772 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 08:51:54.376  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.376  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.376  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.377  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.377  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.377  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.377  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.377  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.377  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.377  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.377  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.377  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.377  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.377  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.378  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.378  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.378  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.378  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOu,tgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 08:51:54.383  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 08:51:54.383  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.383  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.383  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.384  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.384  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.384  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.384  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.384  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.384  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.384  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.384  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.384  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.384  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.384  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.387  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.387  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.387  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.387  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.387  6648  6772 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 08:51:54.389  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:54.391  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:54.391  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:54.391  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:54.391  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:54.391  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:54.391  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:54.391  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:54.391  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:54.392  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:54.392  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:51:54.393  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.394  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.394  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:51:54.394  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:51:54.395  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:51:54.395  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:54.395  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:51:54.398  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 08:51:54.398  1069  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:51:54.401  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 08:51:54.405  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 08:51:54.407  6648  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 08:51:54.407  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:51:54.407  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:54.408  6648  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 08:51:54.408  6648  6772 I io.jxcore.node.ConnectionHelper: start: OK
08-31 08:51:54.410  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.410  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.410  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.411  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.411  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.411  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:54.411  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.411  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.411  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.411  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.411  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.411  6648  6772 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 08:51:54.412  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:54.414  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:54.414  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:54.414  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:54.414  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:54.414  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:54.414  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:54.414  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:54.414  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:54.415  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:54.415  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:54.416  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.417  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.418  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:51:54.418  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:51:54.418  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:51:54.418  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:54.418  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:51:54.421  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:51:54.421  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:54.422  6648  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 08:51:54.422  6648  6772 I io.jxcore.node.ConnectionHelper: start: OK
08-31 08:51:54.423  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.423  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.423  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.423  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.423  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.423  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:54.423  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.423  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.423  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.423  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.423  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.424  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.424  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.424  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.424  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.425  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.425  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.425  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.425  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.426  6648  6772 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 08:51:54.427  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:54.429  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:54.429  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:54.429  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:54.429  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:54.429  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:54.429  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:54.429  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:54.429  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:54.430  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:54.430  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:51:54.431  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.432  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.432  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:51:54.432  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:51:54.432  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:51:54.432  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:54.432  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:51:54.435  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:51:54.435  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:54.436  6648  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 08:51:54.436  6648  6772 I io.jxcore.node.ConnectionHelper: start: OK
08-31 08:51:54.436  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.437  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.437  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.437  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.437  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.437  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.438  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.438  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.438  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:54.438  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.438  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.438  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.438  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.438  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.438  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.438  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.439  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.439  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.439  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.439  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.439  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.439  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.440  6648  6772 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 08:51:54.440  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.440  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.440  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.440  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.440  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.440  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.440  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.440  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.441  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list,
08-31 08:51:54.441  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.441  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.441  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:54.441  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.441  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.441  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.441  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.442  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.442  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-31 08:51:54.442  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.442  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.443  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 08:51:54.443  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.443  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:51:54.443  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.443  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.443  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.443  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:54.443  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.443  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.443  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.443  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.443  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.443  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:54.443  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.443  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.444  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.444  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.444  6648  6772 D BluetoothLeScanner: could not find callback wrapper
,08-31 08:51:54.444  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.445  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.445  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.445  6648  6772 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-31 08:51:54.445  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.445  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.445  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.446  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.446  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:54.446  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.446  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.446  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.446  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
,08-31 08:51:54.446  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.446  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.446  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.446  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.446  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.447  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.447  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.447  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.447  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.447  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.447  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.448  6648  6772 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 08:51:54.448  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.448  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.448  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.448  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.448  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.448  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.448  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.448  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.448  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.448  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.448  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.448  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.448  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.448  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.449  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.449  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.449  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.449  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.449  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.450  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.450  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 08:51:54.450  6648  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:51:54.450  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:51:54.450  6648  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:54.450  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 08:51:54.450  6648  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:51:54.450  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.450  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.450  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.452  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.452  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.452  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.452  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.452  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.452  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.452  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.452  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.452  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.452  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.452  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.453  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.453  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.453  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.453  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.453  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.453  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.454  6648  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:54.454  6648  6772 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 08:51:54.454  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 08:51:54.456  6648  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:54.456  6648  6772 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 08:51:54.456  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 08:51:54.457  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 08:51:54.457  6648  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 08:51:54.457  6648  6772 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-31 08:51:54.457  6648  6772 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 08:51:54.457  6648  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:54.457  6648  6772 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 08:51:54.457  6648  6772 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-31 08:51:54.457  6648  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:54.457  6648  6772 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 08:51:54.457  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 08:51:54.460  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-31 08:51:54.461  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 08:51:54.461  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 08:51:54.461  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 08:51:54.462  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 08:51:54.462  6648  6772 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 08:51:54.463  6648  6772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:54.463  6648  6772 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 08:51:54.464  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.464  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.464  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.464  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.464  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.464  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.465  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 08:51:54.467  6648  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-31 08:51:54.467  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.467  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.468  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.468  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.468  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.468  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.468  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.468  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.471  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.471  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.471  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.471  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 08:51:54.471  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.471  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.472  6648  6772 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-31 08:51:54.472  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.473  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.473  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.473  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.473  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.473  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.473  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list,
08-31 08:51:54.473  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.473  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.473  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop,
08-31 08:51:54.473  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.473  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.473  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:54.473  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.474  6648  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
08-31 08:51:54.474  6648  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
,08-31 08:51:54.474  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.474  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.475  6648  6772 D BluetoothLeScanner: could not find callback wrapper
,08-31 08:51:54.475  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.475  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.475  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
,08-31 08:51:54.475  6648  6772 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 08:51:54.476  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.476  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:51:54.476  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.476  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.476  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.476  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 08:51:54.476  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.476  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.476  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
,08-31 08:51:54.476  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.476  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.476  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:54.476  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.476  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.477  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:51:54.477  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.478  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.478  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 08:51:54.478  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.478  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.478  6648  6772 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 08:51:54.478  6648  6772 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 08:51:54.478  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:51:54.478  6648  6772 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-31 08:51:54.479  6648  6772 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 08:51:54.479  6648  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 08:51:54.479  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-31 08:51:54.479  6648  6772 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 08:51:54.479  6648  6772 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 08:51:54.479  6648  6772 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 08:51:54.479  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:51:54.479  6648  6772 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 08:51:54.479  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.479  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.479  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:51:54.480  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.480  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.480  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.480  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.480  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.480  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.480  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.480  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.480  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.480  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.480  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.481  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.481  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.481  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.481  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.481  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.481  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.481  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.481  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.481  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.481  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.481  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:51:54.481  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.482  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.482  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.482  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.482  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.482  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.482  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.482  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.482  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:54.482  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.482  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.482  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.482  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.482  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.482  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.482  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.482  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.482  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:51:54.482  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.482  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.482  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.482  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.482  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.482  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.483  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.484  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.484  6648  6772 D BluetoothLeScanner: could not find callback wrapper
,08-31 08:51:54.484  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.484  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.484  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.485  6648  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 08:51:54.485  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:54.486  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 08:51:54.486  6648  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 08:51:54.486  6648  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 08:51:54.487  6648  6648 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-31 08:51:54.487  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 08:51:54.487  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:51:54.488  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.488  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 08:51:54.488  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 08:51:54.488  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 08:51:54.488  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.488  6648  6772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 08:51:54.488  6648  6648 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-31 08:51:54.488  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.488  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.488  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:51:54.488  6648  6772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:51:54.488  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:51:54.489  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:51:54.489  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:51:54.489  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:54.489  6648  6772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 08:51:54.489  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.489  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.490  6648  6772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:54.490  6648  6648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:54.490  6648  6648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:54.490  6648  6648 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:54.490  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.490  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.490  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:51:54.490  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.491  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.491  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.491  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.491  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.491  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.491  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.491  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:51:54.491  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.491  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.491  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.491  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.491  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.492  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.492  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.492  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.492  6648  6772 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-31 08:51:54.493  6648  6805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 08:51:54.493  6648  6805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 08:51:54.494  6648  6772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 08:51:54.494  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:51:54.495  6648  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:54.495  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.495  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.495  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:51:54.495  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.495  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.495  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.495  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.495  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.495  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.495  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.495  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:54.495  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.495  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.495  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.496  6648  6648 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 08:51:54.497  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.497  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.497  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.497  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
,08-31 08:51:54.498  1069  1085 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:51:54.498  1069  1985 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:51:54.499  1069  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:51:54.499  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.499  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.499  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.499  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.499  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.499  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:54.499  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.500  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.500  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.500  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.500  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.500  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.500  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.500  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.500  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:51:54.500  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.500  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.500  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.501  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:54.501  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:54.501  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:54.501  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:54.501  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:54.501  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.501  6648  6772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12331be2 not in the list
08-31 08:51:54.501  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.501  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.501  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:54.501  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:54.501  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.501  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:54.501  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:54.502  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:54.502  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:54.502  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:54.502  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50deb73 not in the list
08-31 08:51:54.503  6648  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 08:51:54.503  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:51:54.503  6648  6772 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-31 08:51:54.503  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:51:54.503  6648  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 08:51:54.503  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:51:54.505  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 08:51:54.505  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 08:51:54.505  6648  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 08:51:54.505  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 08:51:54.505  6648  6772 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 08:51:54.505  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-31 08:51:54.505  6648  6772 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 08:51:54.505  6648  6772 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 08:51:54.506  6648  6772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 08:51:54.506  6648  6772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 08:51:54.507  6648  6772 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 08:51:54.507  6648  6772 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 08:51:54.507  6648  6772 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 08:51:54.507  6648  6772 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-31 08:51:54.508  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:51:54.508  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d295f48 added. We now have 2 listener(s)
08-31 08:51:54.508  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:51:54.509  6648  6772 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 08:51:54.510  1069  2014 D WifiServiceImplEx: setWifiEnabled: true pid=6648, uid=10118, package= com.test.thalitest, App Lable : ThaliTest,
08-31 08:51:54.510  1069  2014 D WifiService: setWifiEnabled: true pid=6648, uid=10118
08-31 08:51:54.510  1069  2014 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,08-31 08:51:54.511  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:51:54.511  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f55b1e1 added. We now have 3 listener(s)
08-31 08:51:54.511  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:51:54.514  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:51:54.514  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18b57b06 added. We now have 4 listener(s)
08-31 08:51:54.514  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:51:54.515  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:51:54.515  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d6565c7 added. We now have 5 listener(s)
08-31 08:51:54.515  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:51:54.516  1069  1931 D WifiServiceImplEx: setWifiEnabled: false pid=6648, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-31 08:51:54.516  1069  1931 D WifiService: setWifiEnabled: false pid=6648, uid=10118
08-31 08:51:54.516  1069  1931 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 08:51:54.534  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 08:51:54.534  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 08:51:54.534  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-31 08:51:54.535  1069  1375 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-31 08:51:54.535  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 08:51:54.536  1069  1375 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 08:51:54.536  1069  1375 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,08-31 08:51:54.536  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 08:51:54.537  1069  1375 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 08:51:54.537  1069  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:51:54.537  1069  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 08:51:54.537  1069  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 08:51:54.537  1069  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-31 08:51:54.538  1069  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:51:54.538  1069  1954 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@190aa3e9 mBinding = false
08-31 08:51:54.551  1069  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-31 08:51:54.552  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler },
08-31 08:51:54.552  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:51:54.553  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 08:51:54.553  2682  2682 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-31 08:51:54.553  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true,
08-31 08:51:54.553  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 08:51:54.553  1069  1375 D WifiNative-wlan0: SET ps 1: returned true,
08-31 08:51:54.554  1069  2843 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler },
08-31 08:51:54.556   317   892 D CommandListener: Clearing all IP addresses on wlan0
08-31 08:51:54.557  1069  1165 D BluetoothManagerService: Message: 2
,08-31 08:51:54.558  1069  1165 D BluetoothManagerService: Sending off request.
08-31 08:51:54.558  3832  3856 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 08:51:54.559  3832  3933 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,08-31 08:51:54.559  3832  3933 D BluetoothAdapterProperties: Setting state to 13
08-31 08:51:54.559  3832  3933 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 08:51:54.559  3832  3933 D BluetoothAdapterProperties: onBluetoothDisable(),
08-31 08:51:54.560  3832  3933 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 08:51:54.562  3832  3941 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:51:54.562  3832  3933 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true,
,08-31 08:51:54.564  3832  3933 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 08:51:54.566  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 08:51:54.566  3832  4011 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 08:51:54.566  3832  4216 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:51:54.569  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:51:54.569  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:51:54.569  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:51:54.569  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:51:54.569  3832  4011 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:51:54.571  1069  1165 D BluetoothManagerService: Message: 60
08-31 08:51:54.571  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 08:51:54.571  1069  1165 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 08:51:54.572  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:54.572  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:54.572  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:54.572  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:54.572  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:54.572  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:54.572  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:54.572  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:54.572  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:54.572  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:54.572  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:54.573  3832  4169 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 08:51:54.573  3832  4169 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:51:54.573  3832  4169 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 08:51:54.573  3832  4169 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 08:51:54.573  3832  4169 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 08:51:54.573  3832  4169 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 08:51:54.573  3832  4169 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 08:51:54.573  3832  4169 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 08:51:54.573  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 08:51:54.574  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,cu,rrentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 08:51:54.574  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-31 08:51:54.574  3832  4171 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:51:54.574  3832  4208 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:51:54.575  3832  4214 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:51:54.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:51:54.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:51:54.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:51:54.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:51:54.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 08:51:54.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 08:51:54.575  3832  4011 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-31 08:51:54.596  1069  1390 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 08:51:54.597  1069  1390 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-31 08:51:54.598  1069  1135 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6815 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 08:51:54.600  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:54.601  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 08:51:54.601  3832  3832 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:54.601  3832  3832 D BluetoothMapService: STATE_TURNING_OFF
08-31 08:51:54.602  3832  3832 V BtOppService: Receiver DISABLED_ACTION 
08-31 08:51:54.602  3832  3832 V BluetoothMapService: Handler(): got msg=4
08-31 08:51:54.602  3832  3832 D BluetoothMapService: MAP Service closeService in
08-31 08:51:54.602  3832  3832 D BluetoothMapMasInstance: MAP Service shutdown
08-31 08:51:54.602  3832  3832 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 08:51:54.602  3832  3832 V BluetoothMapService: MAP Service closeService out
08-31 08:51:54.602  3832  3832 I BtOppRfcommListener: stopping Accept Thread
08-31 08:51:54.602  3832  3832 V BtOppRfcommListener: close mBtServerSocket
08-31 08:51:54.603  3832  3832 V BtOppRfcommListener: waiting for thread to terminate
08-31 08:51:54.603  3832  4208 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 08:51:54.603  3832  3832 V BtOppRfcommListener: done waiting for thread to terminate
08-31 08:51:54.604  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:54.604  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:54.604  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:54.604  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:54.604  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:54.604  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:54.604  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:54.604  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:54.604  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:54.604  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:54.604  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:51:54.655  1069  1135 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6835 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 08:51:54.656  3832  3832 V BtOppService: onDestroy
08-31 08:51:54.656  1069  1390 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 08:51:54.657  1069  1390 D DSQN    : disableDataServiceNotify
08-31 08:51:54.657  1069  1390 D DSQN    : stop dsqn bin
08-31 08:51:54.658  1922  1922 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 08:51:54.659  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-31 08:51:54.659  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:54.659  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:54.659  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 08:51:54.660  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.660  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.660  1069  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@393f3bd9
08-31 08:51:54.661  1069  1374 D LGWifiP2pService: P2pDisablingState
08-31 08:51:54.661  1069  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:54.661  1069  1374 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.661  1069  1374 D LGWifiP2pService: p2p socket connection lost
08-31 08:51:54.661  1069  1374 D LGWifiP2pService: P2pDisabledState
08-31 08:51:54.661  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:54.661  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:54.662  1069  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:54.662  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:54.662  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:54.663  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-31 08:51:54.663  1069  1375 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 08:51:54.663  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:54.663  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:54.663  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 08:51:54.663  1069  1069 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 08:51:54.663  1069  1069 D RttService: SCAN_AVAILABLE : 1
08-31 08:51:54.663  1069  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:54.663  1069  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.664  1069  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.664  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:54.664  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:54.665  1069  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 08:51:54.665  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 08:51:54.665  2682  2682 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 08:51:54.665  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateCh,angedEvent: 0
08-31 08:51:54.666  1922  1922 D WfdsService: WifiP2pState is changed : false
08-31 08:51:54.666  1922  2319 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 08:51:54.666  1922  2319 D WfdsService: Set the WFDS Monitor: false
08-31 08:51:54.666  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.666  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-31 08:51:54.666  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.666  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 08:51:54.668  1069  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 08:51:54.668   317   892 D CommandListener: Clearing all IP addresses on wlan0
08-31 08:51:54.669  1922  2319 D WfdsMonitor: WFDS Monitor is stopped
08-31 08:51:54.669  1922  2319 D WfdsService: STATE : WfdsDisabledState - enter
08-31 08:51:54.669  1922  2322 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 08:51:54.669  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:54.669  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:51:54.670  1922  2748 D CtrlSupplicant: Received on exit socket, terminate
08-31 08:51:54.670  1922  2748 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 08:51:54.670  1922  2748 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 08:51:54.670  1922  2748 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 08:51:54.670  1922  2319 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 08:51:54.671  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:54.672  1069  1375 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 08:51:54.672  1069  1375 D WifiNative-p2p0: TERMINATE: returned true
08-31 08:51:54.672  1069  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 08:51:54.672  1069  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 08:51:54.672  1069  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 08:51:54.676  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-31 08:51:54.678  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:54.678  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:54.678  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-31 08:51:54.680  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 08:51:54.683  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:54.683  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:54.683  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:54.683  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:54.683  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:54.683  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:54.683  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:54.683  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:54.683  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:54.683  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 08:51:54.683  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:51:54.683  1069  1069 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 08:51:54.683  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:54.684  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:51:54.717  1069  1390 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 08:51:54.717  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:54.717  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:51:54.717  1069  1390 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-31 08:51:54.717  1069  1390 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 08:51:54.718  1069  1390 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 08:51:54.718  1069  1390 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 08:51:54.718  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 08:51:54.719  1069  1390 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:51:54.719  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 08:51:54.719  1069  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 08:51:54.719  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 08:51:54.719  1069  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.719  1069  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.719  1069  2840 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 08:51:54.719  1069  1069 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 08:51:54.719  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 08:51:54.719  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 08:51:54.719  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 08:51:54.724  1069  2009 I art     : Explicit concurrent mark sweep GC freed 27942(1381KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.581ms total 159.629ms
08-31 08:51:54.724  1069  1390 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:51:54.724  1069  1390 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:54.724  1069  1390 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:54.724  1069  1375 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:54.724  1069  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:51:54.725  1834  1834 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:54.725  1834  1834 D TelephonyNetworkFactory-,1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 08:51:54.725  1069  1390 D NetworkManagementService: Removing idletimer
08-31 08:51:54.725  1069  1390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:54.726  1069  1390 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 08:51:54.726  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:54.727  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:54.727  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:54.727  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:54.727  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:54.727  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:54.727  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:54.727  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:54.727  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:54.727  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:51:54.728  1069  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 08:51:54.728  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:54.728  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:51:54.728  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:54.733  1069  1069 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 08:51:54.733  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 08:51:54.733  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 08:51:54.733  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 08:51:54.739  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:54.739  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 08:51:54.742  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:54.742  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.743  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:54.744  3832  3832 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 08:51:54.750  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 08:51:54.750  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:51:54.750  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 08:51:54.751  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:54.752  6835  6835 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:51:54.752  6835  6835 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 08:51:54.753  6835  6835 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 08:51:54.753  6835  6835 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-31 08:51:54.754  6835  6835 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 08:51:54.755  6835  6835 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 08:51:54.767  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-31 08:51:54.768  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:54.768  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:54.778  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 08:51:54.779  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:54.779  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:54.789  1069  2843 D DhcpStateMachine: StoppedState
08-31 08:51:54.789  1069  2843 D DhcpStateMachine: StoppedState{ when=-122ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:54.790  1069  1375 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 08:51:54.790  1069  1375 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-31 08:51:54.792  6815  6815 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 08:51:54.792  6815  6815 W LG Account v2.2: No ProfileInfo entries
08-31 08:51:54.792  6815  6815 I LG Account v2.2: isEnabled: false
08-31 08:51:54.792  6815  6815 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 08:51:54.792  6815  6815 I Feature : [Lifetracker]Country: EU
08-31 08:51:54.792  6815  6815 I Feature : [Lifetracker]Operator: OPEN
08-31 08:51:54.792  6815  6815 I Feature : [Lifetracker]Ranking support: false
08-31 08:51:54.792  6815  6815 I Feature : [Lifetracker]Comfort support: false
08-31 08:51:54.792  6815  6815 I Feature : [Lifetracker]Accessory: true
08-31 08:51:54.792  6815  6815 I Feature : [Lifetracker]Health device: true
08-31 08:51:54.793  6815  6815 I Feature : [Lifetracker]Extra Pedometer: false
08-31 08:51:54.793  6815  6815 I Feature : [Lifetracker]Blood glucose device: false
08-31 08:51:54.793  6815  6815 I Feature : [Lifetracker]Device Number: 3
08-31 08:51:54.797  2682  2682 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 08:51:54.797  2682  2682 I wpa_supplicant: monitor socket send errors count : 1
08-31 08:51:54.797  2682  2682 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1922-2\x00 that cannot receive messages
08-31 08:51:54.798  1069  2743 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 08:51:54.798  1069  2743 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 08:51:54.800  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:51:54.826  1069  1084 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6856 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 08:51:54.827  1069  1084 I ActivityManager: Killing 6252:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-31 08:51:54.829   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 9.886ms
08-31 08:51:54.834  2682  2682 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 08:51:54.835  2682  2682 W wpa_supplicant: USIM:  scard_deinit function
08-31 08:51:54.835  1069  2743 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 08:51:54.835  1069  2743 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 08:51:54.835  1069  2743 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 08:51:54.835  1069  2743 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 08:51:54.835  1069  2743 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 08:51:54.835  1069  2743 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 08:51:54.836  1069  1375 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=115976
08-31 08:51:54.836  1069  1375 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=115976
08-31 08:51:54.836  1069  1165 D Tethering: InitialState.processMessage what=4
08-31 08:51:54.837  1069  1375 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=115977  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 08:51:54.837  1069  1375 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=115978  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 08:51:54.841   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 11.362ms
,08-31 08:51:54.842  6835  6835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 08:51:54.850   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 9.106ms
08-31 08:51:54.882  2682  2682 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 08:51:54.882  1069  2743 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 08:51:54.882  1069  2743 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 08:51:54.883  1069  2743 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 08:51:54.884  1069  1375 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-31 08:51:54.898  1069  1165 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 08:51:54.907  1069  2009 W libprocessgroup: failed to open /acct/uid_10014/pid_6252/cgroup.procs: No such file or directory
,08-31 08:51:54.919  3832  3832 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 08:51:54.920  3832  3832 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:54.920  3832  3832 V BluetoothPbapReceiver: ***********state = 13
08-31 08:51:54.922  1069  1165 D BluetoothManagerService: Message: 20
08-31 08:51:54.923  1069  1165 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2268b92b:true
08-31 08:51:54.923  3832  3832 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-31 08:51:54.929  3832  3832 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:54.929  3832  3832 V BluetoothPbapService: state: 13
08-31 08:51:54.929  3832  3832 V BluetoothPbapService: Pbap Service closeService in
08-31 08:51:54.933  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 08:51:54.934  3832  3832 V BluetoothPbapService: successfully stopped pbap service
08-31 08:51:54.934  3832  3832 V BluetoothPbapService: Pbap Service closeService out
08-31 08:51:54.934  3832  3832 V BluetoothPbapService: Pbap Service onDestroy
08-31 08:51:54.934  3832  3832 V BluetoothPbapService: Pbap Service closeService in
08-31 08:51:54.934  3832  3832 V BluetoothPbapService: Pbap Service closeService out
08-31 08:51:54.934  3832  3832 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 08:51:54.948  1069  1165 D BluetoothManagerService: Message: 30
,08-31 08:51:54.953  1069  1165 D BluetoothManagerService: Message: 30
08-31 08:51:54.955  6835  6835 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 08:51:54.957  6835  6835 D BluetoothMap: Create BluetoothMap proxy object
08-31 08:51:54.958  1069  1165 D BluetoothManagerService: Message: 30
08-31 08:51:54.962  1069  1165 D BluetoothManagerService: Message: 30
,08-31 08:51:54.964  6835  6835 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 08:51:54.965  6835  6835 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-31 08:51:54.967  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 08:51:54.972  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 08:51:54.972  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 08:51:54.975  1069  1935 I ActivityManager: Killing 6349:com.android.defcontainer/u0a4 (adj 15): empty #17
08-31 08:51:54.991  6648  6648 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 08:51:55.006  1069  1680 W libprocessgroup: failed to open /acct/uid_10004/pid_6349/cgroup.procs: No such file or directory
,08-31 08:51:55.009  1069  1375 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 08:51:55.009  1069  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 08:51:55.009  1069  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 08:51:55.009  1069  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 08:51:55.010  1922  1922 D WfdsService: Supplicant Connection state is changed : false
08-31 08:51:55.010  1922  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 08:51:55.010  1922  2319 D WfdsService: Set the WFDS Monitor: false
08-31 08:51:55.010  1922  2319 D WfdsMonitor: WFDS Monitor is stopped
08-31 08:51:55.010  6835  6835 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-31 08:51:55.013  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:55.014  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 08:51:55.014  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 08:51:55.014  1069  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 08:51:55.015  1069  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 08:51:55.015  2479  2479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:55.016  6835  6835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-31 08:51:55.018  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:55.018  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:55.018  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:55.018  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:55.018  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:55.018  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:55.018  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:55.018  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:55.018  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:51:55.021  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:55.034  6835  6835 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:51:55.046  6835  6835 D BluetoothInputDevice: Proxy object connected
08-31 08:51:55.048  6835  6835 D HidProfile: Bluetooth service connected
,08-31 08:51:55.049  6835  6835 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 08:51:55.050  6835  6835 D PanProfile: Bluetooth service connected
08-31 08:51:55.051  6835  6835 D BluetoothMap: Proxy object connected
,08-31 08:51:55.052  6835  6835 D MapProfile: Bluetooth service connected
,08-31 08:51:55.052  6835  6835 D BluetoothMap: getConnectedDevices()
08-31 08:51:55.052  6835  6835 D BluetoothMap: Bluetooth is Not enabled
,08-31 08:51:55.065  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:51:55.107  6835  6835 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:51:55.107  6835  6835 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 08:51:55.119  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 08:51:55.122  6835  6835 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-31 08:51:55.124  6835  6835 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 08:51:55.129  6835  6835 D BluetoothPermissionRequest: onReceive
,08-31 08:51:55.132  6835  6835 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 08:51:55.148  6835  6835 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 08:51:55.148  1069  1935 I ActivityManager: Killing 6522:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-31 08:51:55.206  1069  1085 W libprocessgroup: failed to open /acct/uid_10008/pid_6522/cgroup.procs: No such file or directory
08-31 08:51:55.208  3832  3832 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-31 08:51:55.209  3832  3832 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-31 08:51:55.211  3832  3832 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 08:51:55.214  1069  1375 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:55.215  1069  1135 I ActivityManager: Waited long enough for: ServiceRecord{39ff7808 u0 com.google.android.gms/.wearable.service.WearableService}
08-31 08:51:55.216  1069  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:55.285  1069  1931 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6884 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-31 08:51:55.288  3832  3832 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:55.288  3832  3832 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 08:51:55.294  3832  3832 V BluetoothFtpService: Ftp Service onStartCommand
08-31 08:51:55.294  3832  3832 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:55.295  3832  3832 V BluetoothFtpService: Ftp Service closeService
08-31 08:51:55.295  3832  3832 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 08:51:55.297  3832  3832 V BluetoothFtpService: successfully stopped ftp service
08-31 08:51:55.299  3832  3832 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 08:51:55.299  3832  3832 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 08:51:55.299  3832  3832 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 08:51:55.299  3832  3832 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:55.300  3832  3832 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 08:51:55.300  3832  3832 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-31 08:51:55.304  3832  3832 V BluetoothFtpService: Ftp Service onDestroy
08-31 08:51:55.304  3832  3832 V BluetoothFtpService: Ftp Service closeService
,08-31 08:51:55.355  1069  1976 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6904 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 08:51:55.356  3832  3832 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:55.356  3832  3832 V BluetoothSapService: state: 13
08-31 08:51:55.356  3832  3832 V BluetoothSapService: Stopping SAP server process
08-31 08:51:55.357  3832  3832 V BluetoothSapService: Sap Service closeSapService in
08-31 08:51:55.357  3832  3832 V BluetoothSapService: Close listen Socket : 
08-31 08:51:55.358  3832  3832 V BluetoothSapService: Close rfcomm Socket : 
08-31 08:51:55.358  3832  3832 V BluetoothSapService: Close sapd  Socket : 
08-31 08:51:55.364  3832  3832 V BluetoothSapService: Sap Service closeSapService out
08-31 08:51:55.364  3832  3832 V BluetoothSapService: Sap Service onDestroy
08-31 08:51:55.364  3832  3832 V BluetoothSapService: Sap Service closeSapService in
08-31 08:51:55.364  3832  3832 V BluetoothSapService: Close listen Socket : 
08-31 08:51:55.364  3832  3832 V BluetoothSapService: Close rfcomm Socket : 
08-31 08:51:55.364  3832  3832 V BluetoothSapService: Close sapd  Socket : 
08-31 08:51:55.365  3832  3832 V BluetoothSapService: Sap Service closeSapService out
08-31 08:51:55.394  6884  6884 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 08:51:55.428  6904  6904 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 08:51:55.428  6884  6884 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-31 08:51:55.447  1069  1904 I ActivityManager: Killing 6090:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-31 08:51:55.463  6884  6884 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-31 08:51:55.464  6884  6884 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 08:51:55.464  6884  6884 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 08:51:55.465  6884  6884 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 08:51:55.465  6884  6884 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 08:51:55.467  6884  6884 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 08:51:55.473  6884  6884 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 08:51:55.488  1069  1597 W libprocessgroup: failed to open /acct/uid_10011/pid_6090/cgroup.procs: No such file or directory
,08-31 08:51:55.497  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:51:55.500  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 08:51:55.522  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 08:51:55.525  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:51:55.526  6884  6884 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 08:51:55.532  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 08:51:55.533  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 08:51:55.533  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:51:55.536  6884  6884 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-31 08:51:55.540  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:51:55.552  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:51:55.565  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 08:51:55.566  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:51:55.570  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 08:51:55.574  3832  3941 D bt_hci_bdroid: cleanup
08-31 08:51:55.574  3832  4013 I bt_lpm  : LPM is already off!!!
08-31 08:51:55.574  3832  4011 W bt-btif : ag scb idx 1 not allocated
08-31 08:51:55.574  3832  4011 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:51:55.575  3832  4155 I bt_userial_mct: exiting userial_read_thread
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:51:55.575  3832  4155 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:51:55.575  3832  4011 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:51:55.575  3832  3941 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 08:51:55.575  3832  4011 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 08:51:55.576  3832  4013 I bt_vendor: hw_epilog_process
08-31 08:51:55.577  3832  3941 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 08:51:55.577  3832  3941 D bt_userial_mct: userial_close
08-31 08:51:55.577  3832  3941 E bt_userial_mct: pthread_join() FAILED result:3
08-31 08:51:55.577  3832  3941 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 08:51:55.578  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 08:51:55.585  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-31 08:51:55.586  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 08:51:55.586  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:51:55.590  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:51:55.598  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:51:55.609  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:51:55.609  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 08:51:55.613  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 08:51:55.657  3832  3941 D bt_hci_bdroid: set_power 0
08-31 08:51:55.657  3832  3941 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 08:51:55.657  3832  3941 I bt_vendor: bluetooth satus is on
08-31 08:51:55.657  3832  3941 I bt_vendor: bt-vendor : resetting BT status
08-31 08:51:55.657  3832  3941 I bt_vendor: Starting hciattach daemon
08-31 08:51:55.657  3832  3941 I bt_vendor: try to set false
,08-31 08:51:55.659  3832  3941 I bt_vendor: Starting hciattach daemon
08-31 08:51:55.659  3832  3941 I bt_vendor: try to set false
08-31 08:51:55.661  3832  3941 I bt_vendor: cleanup
08-31 08:51:55.663  3832  4011 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 08:51:55.664  3832  3941 I GKI_LINUX: GKI_exit_task 0 done
08-31 08:51:55.664  3832  3941 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 08:51:55.665  1069  1976 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6925 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-31 08:51:55.668  3832  3933 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 08:51:55.676  3832  3832 D HeadsetService: Received stop request...Stopping profile...
,08-31 08:51:55.678  3832  3832 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 08:51:55.678  3832  3832 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 08:51:55.678  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39813d00
08-31 08:51:55.678  3832  3958 D HeadsetStateMachine: Exit Disconnected: -1
08-31 08:51:55.680  1834  1834 D BluetoothHeadset: Proxy object disconnected
08-31 08:51:55.681  1069  1069 D BluetoothHeadset: Proxy object disconnected
08-31 08:51:55.681  1069  1069 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 08:51:55.681  1834  1834 D BluetoothHeadset: Proxy object disconnected
08-31 08:51:55.681  1834  1834 D BluetoothHeadset: Proxy object disconnected
08-31 08:51:55.683  3832  3832 D A2dpService: Received stop request...Stopping profile...
08-31 08:51:55.683  3832  3997 D A2dpStateMachine: Exit Disconnected: -1
08-31 08:51:55.684  3832  3832 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 08:51:55.684  3832  3933 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 08:51:55.685  3832  3832 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 08:51:55.685  3832  3832 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 08:51:55.685  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39813d00
08-31 08:51:55.686  1069  1069 D BluetoothA2dp: Proxy object disconnected
08-31 08:51:55.686  1069  1069 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 08:51:55.687  3832  3832 D HidService: Received stop request...Stopping profile...
08-31 08:51:55.687  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39813d00
08-31 08:51:55.688  6835  6835 D BluetoothInputDevice: Proxy object disconnected
08-31 08:51:55.688  6835  6835 D HidProfile: Bluetooth service disconnected
08-31 08:51:55.689  3832  3832 D HealthService: Received stop request...Stopping profile...
08-31 08:51:55.689  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39813d00
,08-31 08:51:55.691  3832  3832 D HeadsetStateMachine: Unbinding service...
08-31 08:51:55.693  3832  3832 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 08:51:55.693  3832  3832 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 08:51:55.693  3832  3832 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 08:51:55.693  3832  3832 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 08:51:55.693  3832  3832 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 08:51:55.693  3832  3832 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 08:51:55.693  3832  3832 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 08:51:55.693  3832  3832 D PanService: Received stop request...Stopping profile...
08-31 08:51:55.694  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39813d00
08-31 08:51:55.695  3832  3832 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 08:51:55.695  3832  3832 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 08:51:55.695  3832  3832 D BtGatt.GattService: stop()
08-31 08:51:55.695  3832  3832 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 08:51:55.696  6835  6835 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 08:51:55.696  6835  6835 D PanProfile: Bluetooth service disconnected
08-31 08:51:55.697  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39813d00
08-31 08:51:55.698  3832  3832 D BluetoothMapService: Received stop request...Stopping profile...
08-31 08:51:55.698  3832  3832 D BluetoothMapService: stop()
08-31 08:51:55.698  3832  3832 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 08:51:55.698  3832  3832 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 08:51:55.699  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39813d00
08-31 08:51:55.700  3832  3832 I BluetoothA2dpServiceJni: cleanupNative
08-31 08:51:55.700  3832  3998 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-31 08:51:55.700  3832  3832 I GKI_LINUX: GKI_exit_task 2 done
08-31 08:51:55.700  3832  3832 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 08:51:55.701  3832  3832 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-31 08:51:55.701  3832  3832 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 08:51:55.701  3832  3832 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 08:51:55.701  3832  3832 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 08:51:55.701  3832  3832 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 08:51:55.702  3832  3832 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-31 08:51:55.702  3832  3832 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 08:51:55.703  3832  3832 V BluetoothMapService: Handler(): got msg=4
08-31 08:51:55.703  3832  3832 D BluetoothMapService: MAP Service closeService in
08-31 08:51:55.703  3832  3832 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 08:51:55.703  3832  3832 V BluetoothMapService: MAP Service closeService out
08-31 08:51:55.703  3832  3832 D BluetoothMapService: cleanup()
08-31 08:51:55.703  3832  3832 D BluetoothMapService: MAP Service closeService in
08-31 08:51:55.703  3832  3832 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 08:51:55.703  3832  3933 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 08:51:55.703  3832  3832 V BluetoothMapService: MAP Service closeService out
08-31 08:51:55.704  3832  3933 D BluetoothAdapterProperties: Setting state to 10
08-31 08:51:55.704  3832  3933 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 08:51:55.704  1069  1165 D BluetoothManagerService: Message: 60
08-31 08:51:55.704  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 08:51:55.704  1069  1165 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-31 08:51:55.704  3832  3933 I BluetoothAdapterState: Entering OffState
08-31 08:51:55.705  1834  2697 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:51:55.706  6835  6851 D BluetoothPan: onBluetoothStateChange on: false
08-31 08:51:55.707  6835  6835 D BluetoothMap: Proxy object disconnected
08-31 08:51:55.707  1069  1165 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:51:55.707  6835  6835 D MapProfile: Bluetooth service disconnected
08-31 08:51:55.707  1834  2378 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:51:55.708  1069  1165 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:51:55.708  6835  6852 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 08:51:55.708  6835  6851 D BluetoothMap: onBluetoothStateChange: up=false
08-31 08:51:55.709  6835  6852 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 08:51:55.709  1834  1850 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:51:55.711  1069  1165 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 08:51:55.711  1069  1165 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 08:51:55.713  1069  1165 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 08:51:55.713  1069  1165 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 08:51:55.713  1069  1165 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@190aa3e9 mBinding = false
08-31 08:51:55.714  1069  1165 D BluetoothManagerService: Sending unbind request.
,08-31 08:51:55.717  1069  1165 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 08:51:55.725  3832  3941 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 08:51:55.725  3832  3832 I GKI_LINUX: GKI_exit_task 1 done
08-31 08:51:55.725  3832  3832 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 08:51:55.725  3832  3832 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 08:51:55.725  3832  3832 I art     : --- WEIRD: removing null entry 246
08-31 08:51:55.726  3832  3832 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-31 08:51:55.726  3832  3832 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 08:51:55.727  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 08:51:55.728  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:55.728  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:55.731  6835  6835 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 08:51:55.731  3832  3832 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 08:51:55.732  6835  6835 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 08:51:55.732  6835  6835 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 08:51:55.732  1586  1586 D BluetoothAdapter: 627574936: getState() :  mService = null. Returning STATE_OFF
08-31 08:51:55.732  1586  1586 D BluetoothAdapter: 627574936: getState() :  mService = null. Returning STATE_OFF
08-31 08:51:55.733  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:55.734  1922  2109 D LGBluetoothAPIService: Message: 2
08-31 08:51:55.734  1922  2109 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@283a7313 mBinding = false
08-31 08:51:55.734  1922  2109 D LGBluetoothAPIService: Sending unbind request.
08-31 08:51:55.734  6835  6835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 08:51:55.735  3832  3832 I art     : System.exit called, status: 0
08-31 08:51:55.736  3832  3832 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 08:51:55.748  6835  6835 D DockEventReceiver: finishStartingService: stopping service
08-31 08:51:55.758   321  3959 V AudioFlinger: 3832 died, releasing its sessions
08-31 08:51:55.758   321  3959 V AudioFlinger:  pid 1834 @ 0
08-31 08:51:55.758   321  3959 V AudioFlinger:  pid 3429 @ 1
08-31 08:51:55.758   321  3959 V AudioFlinger:  pid 3429 @ 2
08-31 08:51:55.759  6835  6835 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 08:51:55.759  2110  2110 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
08-31 08:51:55.788  1069  1085 I ActivityManager: Process com.android.bluetooth (pid 3832) has died
08-31 08:51:55.788  1069  1085 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-31 08:51:55.800  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 08:51:55.810  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 08:51:55.823  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:55.827  6925  6951 W FormManager: Network not available. Please check & try again.
,08-31 08:51:55.835  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:51:55.839  6835  6835 D BluetoothPermissionRequest: onReceive
08-31 08:51:55.843  6835  6835 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 08:51:55.844  6835  6835 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 08:51:55.848  6835  6835 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 08:51:55.849  6925  6953 V FormManager: Network unavailable.
08-31 08:51:55.911  1069  1559 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6955 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 08:51:55.920  6925  6953 V FormManager: Network unavailable.
08-31 08:51:55.945  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-31 08:51:55.946  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 08:51:55.947  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 08:51:55.948  6835  6835 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 08:51:55.950  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 08:51:55.963  6835  6835 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 08:51:55.963  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 08:51:55.963  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 08:51:55.963  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 08:51:55.964  6835  6835 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-31 08:51:55.964  6835  6835 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 08:51:55.965  1069  1985 I ActivityManager: Killing 6110:com.android.contacts/u0a19 (adj 15): empty #17
,08-31 08:51:55.997  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 08:51:56.000  1069  1954 W libprocessgroup: failed to open /acct/uid_10019/pid_6110/cgroup.procs: No such file or directory
08-31 08:51:56.001  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 08:51:56.003  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:51:56.013  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 08:51:56.027  4305  6974 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 08:51:56.027  4305  6974 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 08:51:56.028  6955  6955 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 08:51:56.028  6955  6955 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 08:51:56.029  6955  6955 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 08:51:56.029  6856  6856 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 08:51:56.029  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 08:51:56.029  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:51:56.030  6955  6955 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 08:51:56.032  4305  6973 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 08:51:56.035  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:51:56.044  6925  6976 W FormManager: Network not available. Please check & try again.
08-31 08:51:56.047  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:51:56.051  6925  6977 V FormManager: Network unavailable.
08-31 08:51:56.054  6925  6977 V FormManager: Network unavailable.
08-31 08:51:56.054  6955  6955 D BluetoothAdapterApp: Loading JNI Library
,08-31 08:51:56.066  6884  6884 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 08:51:56.067  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 08:51:56.067  6884  6884 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-31 08:51:56.090  6955  6955 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@f91b01 Instance Count = 1
,08-31 08:51:56.096  6955  6955 D BluetoothAdapterApp: onCreate
08-31 08:51:56.105  6884  6884 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:51:56.105  6884  6884 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 08:51:56.114  6884  6884 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 08:51:56.116  6884  6884 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 08:51:56.116  6884  6884 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 08:51:56.116  6884  6884 V SoundPool: doLoad: loading sample sampleID=1
08-31 08:51:56.116  6884  6884 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 08:51:56.122  6884  6980 V SoundPool: Start decode
08-31 08:51:56.122  6884  6980 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-31 08:51:56.124  6755  6755 D UEI.SmartControl: QS Service created
08-31 08:51:56.127   321  2143 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 08:51:56.127   321  2143 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 08:51:56.127   321  2143 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 08:51:56.127   321  2143 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 08:51:56.127   321  2143 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 08:51:56.127   321  2143 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 08:51:56.127   321  2143 V MediaPlayerService: player type = 3
08-31 08:51:56.127   321  2143 V AwesomePlayer: AwesomePlayer create()
08-31 08:51:56.127   321  2143 V AwesomePlayer: reset_l() 
08-31 08:51:56.127   321  2143 V AwesomePlayer: cancelPlayerEvents
08-31 08:51:56.127   321  2143 V AwesomePlayer: setAudioSink() 
08-31 08:51:56.127   321  2143 V AwesomePlayer: reset_l() 
08-31 08:51:56.127   321  2143 V AudioCache: notify(0xb54745c0, 8, 0, 0)
08-31 08:51:56.128   321  2143 V AudioCache: ignored
08-31 08:51:56.128   321  2143 V AwesomePlayer: cancelPlayerEvents
08-31 08:51:56.128   321  2143 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 08:51:56.128   321  2143 V AwesomePlayer: setDataSource_l dataSource
08-31 08:51:56.128   321  2143 V LGParserOSAL: SniffLGParser start
08-31 08:51:56.128   321  2143 V LGParserOSAL: MainType:5, SubType=0
08-31 08:51:56.128   321  2143 V LGParserOSAL: #### check Mime : application/ogg
08-31 08:51:56.128   321  2143 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 08:51:56.128   321  2143 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 08:51:56.132  6955  6955 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 08:51:56.133  6955  6955 D ProfileConfigQcom: Adding HeadsetService
08-31 08:51:56.133  6955  6955 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 08:51:56.134  6955  6955 D ProfileConfigQcom: Adding A2dpService
08-31 08:51:56.135  6955  6955 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 08:51:56.135  6955  6955 D ProfileConfigQcom: Adding HidService
08-31 08:51:56.137  6955  6955 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 08:51:56.138  6955  6955 D ProfileConfigQcom: Adding HealthService
08-31 08:51:56.138  6884  6884 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 08:51:56.138  6955  6955 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 08:51:56.140  6955  6955 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 08:51:56.140  6755  6755 I UEI.SmartControl: Service initServices...
08-31 08:51:56.140  6755  6755 D UEI.SmartControl: QS start get config
08-31 08:51:56.140  6955  6955 D ProfileConfigQcom: Adding PanService
08-31 08:51:56.141  6955  6955 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 08:51:56.142  6955  6955 D ProfileConfigQcom: Adding GattService
08-31 08:51:56.142  6955  6955 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 08:51:56.143  6955  6955 D ProfileConfigQcom: Adding BluetoothMapService
08-31 08:51:56.144  6955  6955 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 08:51:56.147  6955  6955 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 08:51:56.153  6884  6884 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 08:51:56.154  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-31 08:51:56.163  6955  6955 V LGMDMManagerInternal: Create singleton instance
08-31 08:51:56.172   321  2143 V LGParserOSAL: supported mime: application/ogg
08-31 08:51:56.173   321  2143 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 08:51:56.173   321  2143 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 08:51:56.173   321  2143 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 08:51:56.173   321  2143 V AwesomePlayer: AudioTrack Setting
08-31 08:51:56.173   321  2143 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 08:51:56.173   321  2143 V AwesomePlayer: setAudioSource() 
08-31 08:51:56.173   321  2143 V MediaPlayerService: prepare
08-31 08:51:56.173   321  2143 V AwesomePlayer: prepareAsync_l() 
08-31 08:51:56.173   321  2143 V MediaPlayerService: wait for prepare
08-31 08:51:56.173   321  6982 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 08:51:56.173   321  6982 V AwesomePlayer: initAudioDecoder() 
08-31 08:51:56.173   321  6982 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 08:51:56.173   321  6982 V AudioSystem: isOffloadSupported()
08-31 08:51:56.173   321  6982 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 08:51:56.173   321  6982 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 08:51:56.173   321  6982 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 08:51:56.173   321  6982 V AwesomePlayer: getUseOffload() = 0 
08-31 08:51:56.173   321  6982 V OMXCodec: OMXCodec::Create
08-31 08:51:56.173   321  6982 V OMXCodec: findMatchingCodecs()
08-31 08:51:56.173   321  6982 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 08:51:56.174   321  6982 V OMXCodec: matchingCodecs.size()=1
08-31 08:51:56.174   321  6982 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 08:51:56.174  6835  6835 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-31 08:51:56.176   321  6982 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 08:51:56.176   321  6982 V LGCodecAdapter: LG Codec Adapter start
08-31 08:51:56.176   321  6982 V OMXCodec: OMXCodec Createtor
08-31 08:51:56.176   321  6982 V OMXCodec: setComponentRole
08-31 08:51:56.176   321  6982 V OMXCodec: configureCodec protected=0
08-31 08:51:56.176   321  6982 V LGCodecAdapter: called getLGCodecSpecificData
08-31 08:51:56.176   321  6982 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 08:51:56.176   321  6982 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 08:51:56.176   321  6982 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 08:51:56.176   321  6982 V LGCodecOSAL: Not support LGCodec
08-31 08:51:56.176   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 08:51:56.176   321  6982 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 08:51:56.176   321  6982 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 08:51:56.176   321  6982 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 08:51:56.176   321  6982 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 08:51:56.176   321  6982 V AudioSystem: isOffloadSupported()
08-31 08:51:56.176   321  6982 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 08:51:56.176   321  6982 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 08:51:56.176   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 08:51:56.176   321  6982 V OMXCodec: init()
08-31 08:51:56.177   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 08:51:56.177   321  6982 V OMXCodec: allocateBuffers
08-31 08:51:56.177   321  6982 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 08:51:56.177   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 08:51:56.177   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-31 08:51:56.177   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-31 08:51:56.177   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-31 08:51:56.177   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-31 08:51:56.177   321  6982 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 08:51:56.177   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 08:51:56.179   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-31 08:51:56.179   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-31 08:51:56.179   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-31 08:51:56.179   321  6982 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-31 08:51:56.179   321  6982 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 08:51:56.179   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 08:51:56.179   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 08:51:56.179   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 08:51:56.179   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 08:51:56.179   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 08:51:56.179   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-31 08:51:56.179   321  6982 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 08:51:56.179   321  6982 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 08:51:56.179   321  6982 V AudioCache: notify(0xb54745c0, 5, 0, 0)
08-31 08:51:56.179   321  6982 V AudioCache: ignored
08-31 08:51:56.179   321  6982 V AudioCache: notify(0xb54745c0, 1, 0, 0)
08-31 08:51:56.179   321  6982 V AudioCache: prepared
08-31 08:51:56.179   321  2143 V AudioCache: wait - success
08-31 08:51:56.179   321  2143 V MediaPlayerService: start
08-31 08:51:56.179   321  2143 V AwesomePlayer: play_l() 
08-31 08:51:56.179   321  2143 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 08:51:56.179   321  2143 V AwesomePlayer: createAudioPlayer_l
08-31 08:51:56.179   321  2143 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 08:51:56.179   321  2143 V AwesomePlayer: startAudioPlayer_l() 
08-31 08:51:56.179   321  2143 D AudioPlayer: start of Playback, useOffload 0
08-31 08:51:56.179   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 08:51:56.179   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 08:51:56.181  6884  6884 V LGMDMManager: Create singleton instance
08-31 08:51:56.181   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
,08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 08:51:56.182   321  6984 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-31 08:51:56.182   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 08:51:56.183   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-31 08:51:56.183   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-31 08:51:56.183   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-31 08:51:56.183   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04101a0 on output port
08-31 08:51:56.183   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 08:51:56.183   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 08:51:56.184   321  2143 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 08:51:56.184   321  2143 V AudioCache: notify(0xb54745c0, 6, 0, 0)
,08-31 08:51:56.184   321  2143 V AudioCache: ignored
08-31 08:51:56.185   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.185   321  6985 V AudioCache: memcpy(0xaf006000, 0xb1472000, 4096)
08-31 08:51:56.185   321  2143 V MediaPlayerService: wait for playback complete
,08-31 08:51:56.186   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.187   321  6985 V AudioCache: memcpy(0xaf007000, 0xb1472000, 4096)
08-31 08:51:56.187   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.187   321  6985 V AudioCache: memcpy(0xaf008000, 0xb1472000, 4096)
08-31 08:51:56.187   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.187   321  6985 V AudioCache: memcpy(0xaf009000, 0xb1472000, 4096)
08-31 08:51:56.188   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.188   321  6985 V AudioCache: memcpy(0xaf00a000, 0xb1472000, 4096)
08-31 08:51:56.189   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.189   321  6985 V AudioCache: memcpy(0xaf00b000, 0xb1472000, 4096)
08-31 08:51:56.189   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.189   321  6985 V AudioCache: memcpy(0xaf00c000, 0xb1472000, 4096)
08-31 08:51:56.190   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.190   321  6985 V AudioCache: memcpy(0xaf00d000, 0xb1472000, 4096)
08-31 08:51:56.191   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.191   321  6985 V AudioCache: memcpy(0xaf00e000, 0xb1472000, 4096)
08-31 08:51:56.191   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.191   321  6985 V AudioCache: memcpy(0xaf00f000, 0xb1472000, 4096)
08-31 08:51:56.193   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.193   321  6985 V AudioCache: memcpy(0xaf010000, 0xb1472000, 4096)
08-31 08:51:56.195   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.195   321  6985 V AudioCache: memcpy(0xaf011000, 0xb1472000, 4096)
08-31 08:51:56.196   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.196   321  6985 V AudioCache: memcpy(0xaf012000, 0xb1472000, 4096)
08-31 08:51:56.197   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.197   321  6985 V AudioCache: memcpy(0xaf013000, 0xb1472000, 4096)
08-31 08:51:56.198   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.198   321  6985 V AudioCache: memcpy(0xaf014000, 0xb1472000, 4096)
08-31 08:51:56.198   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.198   321  6985 V AudioCache: memcpy(0xaf015000, 0xb1472000, 4096)
08-31 08:51:56.199   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.199   321  6985 V AudioCache: memcpy(0xaf016000, 0xb1472000, 4096)
08-31 08:51:56.199   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.199   321  6985 V AudioCache: memcpy(0xaf017000, 0xb1472000, 4096)
08-31 08:51:56.201   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.201   321  6985 V AudioCache: memcpy(0xaf018000, 0xb1472000, 4096)
08-31 08:51:56.202   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.202   321  6985 V AudioCache: memcpy(0xaf019000, 0xb1472000, 4096)
08-31 08:51:56.202   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.202   321  6985 V AudioCache: memcpy(0xaf01a000, 0xb1472000, 4096)
08-31 08:51:56.203   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.203   321  6985 V AudioCache: memcpy(0xaf01b000, 0xb1472000, 4096)
08-31 08:51:56.204   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.204   321  6985 V AudioCache: memcpy(0xaf01c000, 0xb1472000, 4096)
08-31 08:51:56.204   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.204   321  6985 V AudioCache: memcpy(0xaf01d000, 0xb1472000, 4096)
08-31 08:51:56.205   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.205   321  6985 V AudioCache: memcpy(0xaf01e000, 0xb1472000, 4096)
08-31 08:51:56.206   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.206   321  6985 V AudioCache: memcpy(0xaf01f000, 0xb1472000, 4096)
08-31 08:51:56.207   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.207   321  6985 V AudioCache: memcpy(0xaf020000, 0xb1472000, 4096)
08-31 08:51:56.208   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.208   321  6985 V AudioCache: mem,cpy(0xaf021000, 0xb1472000, 4096)
,08-31 08:51:56.208   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.208   321  6985 V AudioCache: memcpy(0xaf022000, 0xb1472000, 4096)
08-31 08:51:56.209   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.209   321  6985 V AudioCache: memcpy(0xaf023000, 0xb1472000, 4096)
08-31 08:51:56.210   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.210   321  6985 V AudioCache: memcpy(0xaf024000, 0xb1472000, 4096)
08-31 08:51:56.210   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.210   321  6985 V AudioCache: memcpy(0xaf025000, 0xb1472000, 4096)
08-31 08:51:56.211   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.211   321  6985 V AudioCache: memcpy(0xaf026000, 0xb1472000, 4096)
08-31 08:51:56.212   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.212   321  6985 V AudioCache: memcpy(0xaf027000, 0xb1472000, 4096)
08-31 08:51:56.212   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.212   321  6985 V AudioCache: memcpy(0xaf028000, 0xb1472000, 4096)
08-31 08:51:56.213   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.213   321  6985 V AudioCache: memcpy(0xaf029000, 0xb1472000, 4096)
08-31 08:51:56.213   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.213   321  6985 V AudioCache: memcpy(0xaf02a000, 0xb1472000, 4096)
08-31 08:51:56.214   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.214   321  6985 V AudioCache: memcpy(0xaf02b000, 0xb1472000, 4096)
08-31 08:51:56.215   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.215   321  6985 V AudioCache: memcpy(0xaf02c000, 0xb1472000, 4096)
08-31 08:51:56.215   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.215   321  6985 V AudioCache: memcpy(0xaf02d000, 0xb1472000, 4096)
08-31 08:51:56.216   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.216   321  6985 V AudioCache: memcpy(0xaf02e000, 0xb1472000, 4096)
08-31 08:51:56.217   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.217   321  6985 V AudioCache: memcpy(0xaf02f000, 0xb1472000, 4096)
08-31 08:51:56.218   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.218   321  6985 V AudioCache: memcpy(0xaf030000, 0xb1472000, 4096)
08-31 08:51:56.218   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.218   321  6985 V AudioCache: memcpy(0xaf031000, 0xb1472000, 4096)
08-31 08:51:56.219   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.219   321  6985 V AudioCache: memcpy(0xaf032000, 0xb1472000, 4096)
08-31 08:51:56.219   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.219   321  6985 V AudioCache: memcpy(0xaf033000, 0xb1472000, 4096)
08-31 08:51:56.220   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.220   321  6985 V AudioCache: memcpy(0xaf034000, 0xb1472000, 4096)
08-31 08:51:56.221   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.221   321  6985 V AudioCache: memcpy(0xaf035000, 0xb1472000, 4096)
08-31 08:51:56.222   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.222   321  6985 V AudioCache: memcpy(0xaf036000, 0xb1472000, 4096)
08-31 08:51:56.222   321  6985 V AudioCache: write(0xb1472000, 4096)
08-31 08:51:56.223   321  6985 V AudioCache: memcpy(0xaf037000, 0xb1472000, 4096)
08-31 08:51:56.223   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 08:51:56.223   321  6985 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 08:51:56.223   321  6985 V AwesomePlayer: postAudioEOS() 
08-31 08:51:56.223   321  6985 V AudioCache: write(0xb1472000, 280)
08-31 08:51:56.223   321  6985 V AudioCache: memcpy(0xaf038000, 0xb1472000, 280)
08-31 08:51:56.226   321  6982 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 08:51:56.226   321  6982 V AwesomePlayer: onStreamDone
08-31 08:51:56.226   321  6982 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 08:51:56.226   321  6982 V AudioCache: notify(0xb,54745c0, 2, 0, 0)
08-31 08:51:56.227   321  6982 V AudioCache: playback complete
08-31 08:51:56.227   321  6982 V AwesomePlayer: pause_l() 
08-31 08:51:56.227   321  2143 V AudioCache: wait - success
08-31 08:51:56.227   321  6982 V AudioCache: notify(0xb54745c0, 7, 0, 0)
08-31 08:51:56.227   321  6982 V AudioCache: ignored
08-31 08:51:56.227   321  6982 V AwesomePlayer: cancelPlayerEvents
08-31 08:51:56.227   321  2143 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 08:51:56.227   321  6982 D AudioPlayer: Pause Playback at 1068125
08-31 08:51:56.227   321  2143 V AwesomePlayer: reset_l() 
08-31 08:51:56.227   321  2143 V AudioCache: notify(0xb54745c0, 8, 0, 0)
08-31 08:51:56.227   321  2143 V AudioCache: ignored
08-31 08:51:56.227   321  2143 V AwesomePlayer: cancelPlayerEvents
08-31 08:51:56.227   321  2143 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 08:51:56.227   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 08:51:56.227   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 08:51:56.227   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 08:51:56.227   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 08:51:56.227   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 08:51:56.227   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 08:51:56.227   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 08:51:56.227   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-31 08:51:56.227   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04101a0 on port 1
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 08:51:56.228   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 08:51:56.228   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 08:51:56.228   321  6984 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 08:51:56.228   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 08:51:56.228   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
,08-31 08:51:56.228   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 08:51:56.229   321  2143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-31 08:51:56.230   321  2143 D AudioPlayer: AudioPlayer releasing audio source
08-31 08:51:56.230   321  2143 D AudioPlayer: AudioPlayer done releasing audio source
08-31 08:51:56.230   321  2143 V AwesomePlayer: reset_l() 
08-31 08:51:56.230   321  2143 V AwesomePlayer: cancelPlayerEvents
08-31 08:51:56.230   321  2143 V AwesomePlayer: ~AwesomePlayer call
08-31 08:51:56.230   321  2143 V AwesomePlayer: reset_l() 
08-31 08:51:56.230   321  2143 V AwesomePlayer: cancelPlayerEvents
08-31 08:51:56.230  6884  6980 V SoundPool: close(31)
08-31 08:51:56.230  6884  6980 V SoundPool: pointer = 0x9fe8d000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 08:51:56.245  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 08:51:56.246  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 08:51:56.249  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:71
08-31 08:51:56.249  6955  6955 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:51:56.253  6955  6955 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 08:51:56.253  6955  6955 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 08:51:56.253  6955  6955 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 08:51:56.254  6955  6955 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:56.254  6955  6955 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 08:51:56.261  6904  6904 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 08:51:56.444  6755  6755 I UEI.SmartControl: Supports setup maps: true
,08-31 08:51:56.448  6755  6755 D UEI.SmartControl: QS start statue = true Error code = 0
,08-31 08:51:56.448  6755  6755 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 08:51:56.448  6755  6755 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 08:51:56.448  6755  6755 I UEI.SmartControl: ### init IR Blaster...
08-31 08:51:56.451  6755  6755 D serial_port: Configuring serial port
,08-31 08:51:56.452  6755  6755 E UEI.SmartControl: UEIBLaster setting for 616
08-31 08:51:56.452  6755  6755 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 08:51:56.452  6755  6755 I UEI.SmartControl: configuring settings for MAXQ616
08-31 08:51:56.452  6755  6755 I UEI.SmartControl: Get version...
,08-31 08:51:56.470  6755  6987 D UEI.SmartControl: serial port data available: 21
,08-31 08:51:56.497  6755  6755 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-31 08:51:56.497  6755  6755 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 08:51:56.497  6755  6755 I UEI.SmartControl: QS saving settings...
08-31 08:51:56.499  6755  6755 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 08:51:56.518  6755  6987 D UEI.SmartControl: serial port data available: 4
,08-31 08:51:56.554  6755  6993 I UEI.SmartControl: Device manager: loading config....
,08-31 08:51:56.556  6755  6755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 08:51:56.557  6755  6993 D UEI.SmartControl: ----------- loading internal config...
08-31 08:51:56.560  6755  6755 E UEI.SmartControl: Services init done
08-31 08:51:56.560  6755  6755 D UEI.SmartControl: QS Service init finished
08-31 08:51:56.562  6755  6755 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 08:51:56.562  6755  6755 D UEI.SmartControl: QS Service version code: 201091
08-31 08:51:56.563  6755  6755 D UEI.SmartControl: Service requested: Control
08-31 08:51:56.576  6755  6755 D UEI.SmartControl: Request IControl service: devices are loaded...,
,08-31 08:51:56.577  6755  6993 E UEI.SmartControl: Loading SETTINGS...
,08-31 08:51:56.585  6884  6884 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 08:51:56.588  6755  6771 I UEI.SmartControl: ------ IControl API: 11
08-31 08:51:56.588  6755  6771 D UEI.SmartControl: File observer start...
08-31 08:51:56.588  6755  6771 E UEI.SmartControl: IR Port is disabled: false
08-31 08:51:56.588  6755  6771 D UEI.SmartControl: Starting file observer...
08-31 08:51:56.589  6755  6771 I UEI.SmartControl: Registering callback...
08-31 08:51:56.590  6755  6755 D UEI.SmartControl: Internal service binding...
08-31 08:51:56.591  6755  6771 I UEI.SmartControl: ------ IControl API: 19
08-31 08:51:56.591  6755  6771 I UEI.SmartControl: Registering Services Ready callback...
08-31 08:51:56.594  6755  6993 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-31 08:51:56.612  6755  6992 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-31 08:51:56.613  6884  6903 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 08:51:56.614  6755  6992 D UEI.SmartControl: -----service ready thread exits
08-31 08:51:56.614  6884  6978 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 08:51:56.614  6884  6978 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 08:51:56.615  6884  6884 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 08:51:56.615  6884  6884 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 08:51:56.615  6755  6770 I UEI.SmartControl: ------ IControl API: 8
08-31 08:51:56.617  6884  6884 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 08:51:56.617  6884  6884 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 08:51:56.618  6884  6884 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 08:51:56.618  6884  6884 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 08:51:56.619  6884  6884 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 08:51:56.619  6884  6884 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-31 08:51:56.620  6884  6884 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 08:51:56.624  6884  6884 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 08:51:56.624  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-31 08:51:56.625  6884  6884 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 08:51:56.626  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 08:51:56.627  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 08:51:56.628  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 08:51:56.629  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 08:51:56.630  6884  6884 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472626316629]
08-31 08:51:56.633  6884  6884 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 08:51:56.635  1069  1885 I ActivityManager: Killing 6136:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-31 08:51:56.654  6884  6998 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 08:51:56.667  1069  1885 I ActivityManager: Killing 6557:com.lge.email/u0a23 (adj 15): empty #18
,08-31 08:51:56.698  1069  1935 W libprocessgroup: failed to open /acct/uid_10027/pid_6136/cgroup.procs: No such file or directory
,08-31 08:51:56.705  1069  1976 W libprocessgroup: failed to open /acct/uid_10023/pid_6557/cgroup.procs: No such file or directory
08-31 08:51:56.706  6884  6884 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-31 08:51:56.706  6884  6884 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 08:51:56.707  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 08:51:56.707  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 08:51:56.708  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 08:51:56.708  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-31 08:51:56.708  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 08:51:56.718  6884  6884 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 08:51:57.722  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:57.738  1069  1165 D Tethering: MasterInitialState.processMessage what=3
08-31 08:51:57.748  1069  1559 D WifiServiceImplEx: setWifiEnabled: true pid=6648, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-31 08:51:57.751  1069  1559 D WifiService: setWifiEnabled: true pid=6648, uid=10118
08-31 08:51:57.751  1069  1559 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 08:51:57.755  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.757  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.758  1069  1131 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 08:51:57.760  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:57.765  1069  1165 D Tethering: MasterInitialState.processMessage what=3
08-31 08:51:57.777  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:57.779  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.782  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 08:51:57.782  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 08:51:57.782  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-31 08:51:57.784  1069  1375 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 08:51:57.784  1069  1375 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 08:51:57.786  1069  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1069] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 08:51:57.786  1069  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 08:51:57.787  1069  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1069] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 08:51:57.787  1069  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 08:51:57.787  1069  1375 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 08:51:57.787  1069  1375 E WifiHW  : unknown target_country: EU , set to default
08-31 08:51:57.787  1069  1375 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 08:51:57.787  1069  1375 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 08:51:57.787  1069  1375 I WifiUtil: gEnableBmps=1
,08-31 08:51:57.794  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 08:51:57.803  5798  5798 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 08:51:57.810  5798  5798 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 08:51:57.811  6458  6490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 08:51:57.845  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:57.924  1069  1935 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7018 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-31 08:51:57.929  1069  1131 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 08:51:57.930  1069  1131 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:57.930  1069  1131 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 08:51:58.023  7018  7018 I AppUp4:AppBoxCP: onCreate
,08-31 08:51:58.024  7018  7018 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-31 08:51:58.034  7018  7018 I AppUp4:DB:  setFingerPrint start
08-31 08:51:58.035  7018  7018 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-31 08:51:58.046  7018  7018 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 08:51:58.046  7018  7018 I AppUp4:DB:  SDK version = 21
08-31 08:51:58.046  7018  7018 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-31 08:51:58.048  7018  7018 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-31 08:51:58.050  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-31 08:51:58.050  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:51:58.053  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 08:51:58.053  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 08:51:58.061  7018  7018 I AppUp4:CustModeStarterReceiver: onReceive
08-31 08:51:58.113  7018  7018 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:51:58.114  7018  7018 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 08:51:58.122  7018  7018 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2473b783
08-31 08:51:58.122  7018  7018 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 08:51:58.122  7018  7018 D AppUp4:CustFacade: isPhone : true
08-31 08:51:58.123  7018  7018 D AppUp4:CustModeStarterReceiver: begin check event
08-31 08:51:58.124  7018  7018 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-31 08:51:58.124  7018  7018 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-31 08:51:58.125  7018  7037 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-31 08:51:58.125  7018  7037 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 08:51:58.125  7018  7037 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-31 08:51:58.128  1069  1886 I ActivityManager: Killing 6158:com.android.vending/u0a44 (adj 15): empty #17
,08-31 08:51:58.254  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:58.254  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 08:51:58.258  1069  2009 W libprocessgroup: failed to open /acct/uid_10044/pid_6158/cgroup.procs: No such file or directory
,08-31 08:51:58.265  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 08:51:58.268  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:51:58.281  4305  7046 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 08:51:58.288  4305  7047 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:51:58.288  4305  7047 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 08:51:58.342  1069  1935 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7048 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 08:51:58.420  7048  7048 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:51:58.420  7048  7048 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 08:51:58.422  7048  7048 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 08:51:58.422  7048  7048 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 08:51:58.532  7048  7048 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-31 08:51:58.538  1069  1165 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 08:51:58.543   317   892 D SoftapController: Softap fwReload - Ok
,08-31 08:51:58.548  1069  1375 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (757ms)
08-31 08:51:58.551   317   892 D CommandListener: Setting iface cfg
08-31 08:51:58.551   317   892 D CommandListener: Trying to bring down wlan0
08-31 08:51:58.552   317   892 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:51:58.558  1069  1375 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-31 08:51:58.560  7072  7072 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:51:58.560  7072  7072 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 08:51:58.576  7048  7048 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-31 08:51:58.608  7072  7072 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 08:51:58.628  7048  7048 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 08:51:58.640  7072  7072 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 08:51:58.640  7072  7072 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-31 08:51:58.643  1069  1165 D Tethering: InitialState.processMessage what=4
08-31 08:51:58.643  1069  1165 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 08:51:58.659  1069  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 08:51:58.659  1069  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 08:51:58.659  1069  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 08:51:58.660  1069  1375 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 08:51:58.660  1069  1375 D WifiMonitor: connecting to supplicant
,08-31 08:51:58.663  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:58.663  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 08:51:58.664  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:58.664  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 08:51:58.664  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 08:51:58.670  7048  7048 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:51:58.670  7048  7048 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 08:51:58.738  7072  7072 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 08:51:58.769  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 08:51:58.771  7072  7072 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-31 08:51:58.775  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 08:51:58.777  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 08:51:58.777  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 08:51:58.778  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 08:51:58.778  1069  1375 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 08:51:58.779  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:58.779  1069  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 08:51:58.779  1069  7087 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 08:51:58.779  1069  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:58.780  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:58.780  1069  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:58.781  1069  1375 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 08:51:58.781  1069  1375 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 08:51:58.781  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 08:51:58.782  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 08:51:58.782  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 08:51:58.782  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 08:51:58.782  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 08:51:58.782  1069  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 08:51:58.782  1069  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 08:51:58.782  1069  1375 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 08:51:58.782  1069  1375 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 08:51:58.783  1069  1375 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-31 08:51:58.790  1069  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 08:51:58.790  1069  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 08:51:58.790  1069  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 08:51:58.790  1069  1375 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 08:51:58.790  1069  1375 D WifiNative-wlan0: SET update_config 1: returned true
08-31 08:51:58.790  1069  1375 D WifiConfigStore: Loading config and enabling all networks 
08-31 08:51:58.791  1069  1375 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 08:51:58.791  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:58.791  1069  1375 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 08:51:58.791  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:58.791  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:58.791  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:58.792  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 08:51:58.794  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:58.796  1922  1922 D WfdService: Waiting for WifiP2p enabling
,08-31 08:51:58.797  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 08:51:58.798  1069  1375 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 08:51:58.800  1069  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 08:51:58.802  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:58.802  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:58.802  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:58.802  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:58.802  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:58.802  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:58.802  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:58.802  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:58.802  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:51:58.802  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:58.802  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:51:58.803  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:58.803  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:58.803  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:58.803  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:51:58.803  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:58.803  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:58.803  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:58.803  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:58.803  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:51:58.804  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:58.804  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:51:58.815  7048  7048 I HubEmail: JNI_OnLoad()
08-31 08:51:58.815  7048  7048 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 08:51:58.816  7048  7048 I HubEmail: registerNatives()
08-31 08:51:58.816  7048  7048 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 08:51:58.816  7048  7048 I HubEmail: registerNativeMethods()
08-31 08:51:58.816  7048  7048 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 08:51:58.816  7048  7048 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-31 08:51:58.819  1069  1375 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 08:51:58.819  1069  1375 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 08:51:58.820  3429  3429 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 08:51:58.820  3429  3429 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 08:51:58.820  3429  3429 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 08:51:58.820  1069  1375 D WifiStateMachine: enableVerboseLogging : level 2
08-31 08:51:58.821  1069  1375 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 08:51:58.821  1069  1375 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 08:51:58.821  1069  1375 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 08:51:58.822  1069  1375 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 08:51:58.822  1069  1375 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 08:51:58.822  1069  1375 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 08:51:58.822  1069  1375 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 08:51:58.823  1069  1375 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 08:51:58.823  1069  1375 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 08:51:58.823  1069  1375 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 08:51:58.823  1069  1375 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 08:51:58.824  1069  1375 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 08:51:58.824  1069  1375 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 08:51:58.824  1069  1375 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 08:51:58.859  1069  1886 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7094 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 08:51:58.861  1069  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 08:51:58.861  1069  1375 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 08:51:58.862  1069  1375 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 08:51:58.862  1069  1375 D WifiNative-HAL: Setting external_sim to 1
08-31 08:51:58.862  1069  1375 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 08:51:58.862  1922  1922 D WfdsService: Supplicant Connection state is changed : true
08-31 08:51:58.862  1069  1375 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 08:51:58.862  1069  1375 I WifiNative-HAL: startHal
08-31 08:51:58.862  1069  1375 D wifi    : setting scan oui 0xaf7130e0
08-31 08:51:58.862  1922  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 08:51:58.862  1922  2319 D WfdsService: Set the WFDS Monitor: true
08-31 08:51:58.862  1922  2319 D WfdsMonitor: WfdsMonitorThread create
08-31 08:51:58.863  1922  2319 D WfdsMonitor: WFDS Monitor is created and started
08-31 08:51:58.863  1922  2319 D WfdsService: WiFi: Supplicant connection re-established
08-31 08:51:58.863  1069  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 08:51:58.863  1069  1375 I WifiNative-HAL: startHal
08-31 08:51:58.863  1069  1375 D wifi    : setting scan oui 0xaf7130e0
08-31 08:51:58.863  1069  1375 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 08:51:58.864  1069  1375 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 08:51:58.864  7048  7091 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:58.864  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 08:51:58.864  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 08:51:58.864  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 08:51:58.864  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 08:51:58.864  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 08:51:58.865  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 08:51:58.865  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 08:51:58.865  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 08:51:58.865  1922  7105 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 08:51:58.865  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 08:51:58.865  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 08:51:58.865  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 08:51:58.865  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 08:51:58.865  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 08:51:58.866  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 08:51:58.866  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-31 08:51:58.866  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 08:51:58.866  7072  7072 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 08:51:58.866  1922  7105 E CtrlSupplicant: Succeed to open control connection
08-31 08:51:58.866  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 08:51:58.866  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 08:51:58.866  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 08:51:58.866  1922  7105 E CtrlSupplicant: Succeed to open monitor connection
08-31 08:51:58.867  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 08:51:58.867  1922  7105 D WfdsMonitor: Supplicant connection established
08-31 08:51:58.867  1922  2319 D WfdsService: Connected to the supplicant for wfds
08-31 08:51:58.867  1069  1375 E WifiNative: : [120,007,647 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 08:51:58.867  1069  1375 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 08:51:58.868  1069  1375 D WifiNative-wlan0: RECONNECT: returned true
08-31 08:51:58.868  1069  1375 D WifiNative-wlan0: doString: [STATUS]
08-31 08:51:58.868  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 08:51:58.868  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 08:51:58.868  1069  1375 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 08:51:58.868  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 08:51:58.869  1069  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 08:51:58.869  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.869  1069  1069 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 08:51:58.869  1069  1069 D RttService: SCAN_AVAILABLE : 3
08-31 08:51:58.869  1069  1375 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 08:51:58.870  1069  1375 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 08:51:58.870  1069  1375 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 08:51:58.870  1069  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.870  1069  1540 I WifiNative-HAL: startHal
08-31 08:51:58.870  1069  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf7130e0
08-31 08:51:58.870  1069  1375 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 08:51:58.870  1069  1540 D wifi    : failed to get capabilities : -3
08-31 08:51:58.870  1069  1540 E WifiScanningService: could not get scan capabilities
08-31 08:51:58.870  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=120011  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 08:51:58.871  1069  1541 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.871  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=120011  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 08:51:58.871  1069  1375 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 08:51:58.872  1069  1375 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 08:51:58.872  1069  1375 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 08:51:58.872  1069  1375 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 08:51:58.872  7072  7072 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 08:51:58.873  1069  1375 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 08:51:58.873   317   892 D CommandListener: Settin,g iface cfg
08-31 08:51:58.873   317   892 D CommandListener: Trying to bring up p2p0
08-31 08:51:58.873  1069  1375 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 08:51:58.873  1069  1375 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 08:51:58.873  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:58.873  1069  1375 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 08:51:58.873  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:51:58.873  7072  7072 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 08:51:58.874  1069  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 08:51:58.874  1069  1374 D LGWifiP2pService: P2pEnablingState
08-31 08:51:58.874  1069  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.874  1069  1374 D LGWifiP2pService: P2p socket connection successful
08-31 08:51:58.874  1069  1374 D LGWifiP2pService: P2pEnabledState
,08-31 08:51:58.875  1069  1375 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 08:51:58.875  1069  1375 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 08:51:58.875  1069  1375 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-31 08:51:58.875  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 08:51:58.876  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 08:51:58.877  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:51:58.877  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 08:51:58.877  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:51:58.877  1069  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-31 08:51:58.877  1069  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:51:58.877  7072  7072 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 08:51:58.878  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.878  1069  1375 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 08:51:58.878  1069  1375 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 08:51:58.878  1069  1375 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 08:51:58.878  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.878  1069  1375 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 08:51:58.878  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 08:51:58.878  1069  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:51:58.879  1069  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.879  1922  7105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:51:58.879  1069  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.879  1069  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.879  1922  7105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:51:58.879  1069  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:51:58.879  1069  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.879  1069  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.879  1069  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.879  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 08:51:58.879  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 08:51:58.879  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 08:51:58.879  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 08:51:58.879  1069  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 08:51:58.879  1069  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 08:51:58.880  1069  1375 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 08:51:58.880  1069  1375 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 08:51:58.880  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:58.880  1069  1375 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 08:51:58.880  1069  1375 D WifiNative-wlan0: doBoolean: SCAN
08-31 08:51:58.880  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:58.880  1069  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 08:51:58.880  1069  1375 D WifiNative-wlan0: SCAN: returned false
08-31 08:51:58.880  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 08:51:58.880  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=120021  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 08:51:58.880  6925  7092 W FormManager: Network not available. Please check & try again.
08-31 08:51:58.882  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 08:51:58.882  1069  1374 D W,ifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 08:51:58.882  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=120023  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 08:51:58.882  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:58.885  1922  1922 D WfdsService: WifiP2pState is changed : true
08-31 08:51:58.885  1922  1922 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 08:51:58.885  1069  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 08:51:58.885  1922  1922 D WfdsService: isConnected: false
08-31 08:51:58.885  1069  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 08:51:58.885  1922  2319 D WfdsService: Receive the WFDS_ENABLE Method
08-31 08:51:58.885  1069  1375 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:51:58.886  1069  1375 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:51:58.886  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:58.886  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:58.886  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 08:51:58.886  1069  1375 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:51:58.885  1922  2319 D WfdsService: Set the WFDS Monitor: true
08-31 08:51:58.886  1069  1375 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:51:58.886  1922  2319 D WfdsService: Connected to the supplicant for wfds
,08-31 08:51:58.886  1922  2319 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 08:51:58.886  7072  7072 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 08:51:58.886  1069  1375 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:51:58.887  1922  2319 D WfdsService: selectPreferredScanChannel [36]
08-31 08:51:58.887  1922  2319 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 08:51:58.887  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:51:58.887  1069  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-31 08:51:58.887  1069  1069 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 08:51:58.887  1069  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
,08-31 08:51:58.887  1069  1374 D LGWifiP2pService: before postfix = G3
08-31 08:51:58.887  1069  1374 D WifiServerServiceExt: postfix byte check : 2
08-31 08:51:58.887  1069  1374 D LGWifiP2pService: after postfix = G3
08-31 08:51:58.887  1069  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 08:51:58.888  1069  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 08:51:58.888  1069  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 08:51:58.889  1069  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 08:51:58.889  1069  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 08:51:58.889  1069  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
,08-31 08:51:58.889  1069  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 08:51:58.890  1069  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 08:51:58.890  1069  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-31 08:51:58.890  1069  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 08:51:58.890  1069  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 08:51:58.890  1069  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-31 08:51:58.891  1069  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 08:51:58.891  1069  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 08:51:58.891  1922  1922 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 08:51:58.891  1922  1922 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 08:51:58.891  1922  1922 D WfdsService: Update P2p Interface State: 3
08-31 08:51:58.892  1069  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 08:51:58.892  1069  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 08:51:58.892  1069  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 08:51:58.892  1069  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 08:51:58.894  6925  7093 V FormManager: Network unavailable.
08-31 08:51:58.899  6925  7093 V FormManager: Network unavailable.
08-31 08:51:58.901  1069  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 08:51:58.901  1069  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 08:51:58.901  1069  1374 D LGWifiP2pService: InactiveState
08-31 08:51:58.902  1069  1374 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.902  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.902  1069  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-31 08:51:58.902  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 08:51:58.902  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:51:58.903  7072  7072 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 08:51:58.903  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.903  1069  1976 I ActivityManager: Killing 6204:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-31 08:51:58.903  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.904  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:58.904  1069  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 08:51:58.904  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:51:58.904  1069  1374 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.904  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.904  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.904  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.904  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.904  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.904  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.904  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.905  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:58.905  1922  7105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 08:51:58.905  1922  2319 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 08:51:58.905  1922  7105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:51:58.905  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.905  1922  7105 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:51:58.905  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.905  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.905  1069  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 08:51:58.905  1069  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:51:58.905  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.905  1069  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:51:58.905  1069  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:51:58.905  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.S,tateMachine$SmHandler }
08-31 08:51:58.905  1069  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:51:58.905  1069  1374 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:58.905  1069  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.905  1069  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.905  1069  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.905  1069  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:51:58.905  1069  1069 E WifiServerServiceExt: No p2p device connected
08-31 08:51:58.905  1069  7087 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.905  1069  7087 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:51:58.905  1069  7087 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 08:51:58.930  1069  1084 W libprocessgroup: failed to open /acct/uid_10080/pid_6204/cgroup.procs: No such file or directory
08-31 08:51:58.979  7094  7094 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:51:58.979  7094  7094 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 08:51:58.981  7094  7094 D PhoneMonitor: Register our PhoneStateListener
08-31 08:51:59.000  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-31 08:51:59.004  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 08:51:59.035  7094  7094 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-31 08:51:59.037  7094  7094 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-31 08:51:59.038  7094  7094 D TelephonyAutoProfiling: [parse] Load xml
,08-31 08:51:59.045  7094  7094 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 08:51:59.045  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 08:51:59.045  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 08:51:59.045  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 08:51:59.045  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 08:51:59.045  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 08:51:59.045  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 08:51:59.046  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 08:51:59.046  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 08:51:59.046  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 08:51:59.046  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 08:51:59.046  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 08:51:59.046  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-31 08:51:59.048  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 08:51:59.048  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 08:51:59.048  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 08:51:59.048  7094  7094 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-31 08:51:59.065  7094  7094 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-31 08:51:59.072  1069  1084 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7115 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:51:59.074  1069  1084 I ActivityManager: Killing 6595:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-31 08:51:59.137  1069  1559 W libprocessgroup: failed to open /acct/uid_10061/pid_6595/cgroup.procs: No such file or directory
,08-31 08:51:59.395  1069  1085 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7139 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-31 08:51:59.400  1069  1085 I ActivityManager: Killing 5572:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-31 08:51:59.429  7072  7072 E wpa_supplicant: USIM:  scard_init function
08-31 08:51:59.429  7072  7072 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-31 08:51:59.432  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 08:51:59.432  1069  7087 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 08:51:59.432  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 08:51:59.433  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-31 08:51:59.433  1069  7087 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 08:51:59.433  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 08:51:59.433  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 08:51:59.435  1069  1375 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 08:51:59.435  1069  1375 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 08:51:59.435  1069  1375 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 08:51:59.436  1069  1375 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 08:51:59.436  1069  1375 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 08:51:59.478  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=120618  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 08:51:59.479  1069  1886 W libprocessgroup: failed to open /acct/uid_10097/pid_5572/cgroup.procs: No such file or directory
08-31 08:51:59.482  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=120622  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 08:51:59.490  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.490  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.490  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 08:51:59.491  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:51:59.491  1069  1069 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 08:51:59.491  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:59.492  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 08:51:59.498  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.568  7072  7072 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 08:51:59.573  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 08:51:59.573  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 08:51:59.574  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 08:51:59.574  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 08:51:59.574  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 08:51:59.574  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 08:51:59.578  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=120718  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 08:51:59.579  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=120719  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 08:51:59.579  1069  1375 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120720
08-31 08:51:59.580  1069  1375 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120720
08-31 08:51:59.580  1069  1375 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120720
08-31 08:51:59.580  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120721
,08-31 08:51:59.582  1069  1375 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120721
08-31 08:51:59.583  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=120723  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 08:51:59.590  1069  2009 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7156 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:51:59.592  1069  2009 I ActivityManager: Killing 6718:com.lge.eula/1000 (adj 15): empty #17
08-31 08:51:59.593  7072  7072 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 08:51:59.593  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-31 08:51:59.596  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 08:51:59.596  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 08:51:59.596  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 08:51:59.596  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 08:51:59.596  1069  7087 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 08:51:59.600  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 08:51:59.600  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 08:51:59.600  1069  7087 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 08:51:59.600  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 08:51:59.600  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 08:51:59.661  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.661  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.661  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:51:59.672  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=120813  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 08:51:59.673  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:59.673  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 08:51:59.676  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.678  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.678  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.679  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 08:51:59.684  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.684  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.684  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-31 08:51:59.693  1069  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_6718/cgroup.procs: No such file or directory
08-31 08:51:59.697  1069  1165 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 08:51:59.698  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=120838  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 08:51:59.698  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:51:59.698  1069  1069 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 08:51:59.698  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=120839  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 08:51:59.699  1069  1375 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120839
08-31 08:51:59.699  1069  1375 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120840
,08-31 08:51:59.700  1069  1375 D WifiNative-wlan0: doString: [STATUS]
08-31 08:51:59.701  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 08:51:59.701  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 08:51:59.704  1069  1375 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 08:51:59.705  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:59.705  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:51:59.705  1069  1375 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 08:51:59.707  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.713  1069  1375 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 08:51:59.713  1069  1375 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 08:51:59.719  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.719  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.719  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 08:51:59.728  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:59.728  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 08:51:59.734  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.734  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:51:59.734  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.734  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 08:51:59.735  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:59.736  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:51:59.742  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 08:51:59.745  1069  1375 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 08:51:59.746  1069  1390 D ConnectivityService: Got NetworkAgent Messenger
08-31 08:51:59.746  1069  1390 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 08:51:59.746  1069  1390 D ConnectivityService: NetworkAgent connected
08-31 08:51:59.746  1069  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 08:51:59.746  1069  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 08:51:59.747  1069  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 08:51:59.747  1069  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 08:51:59.755  1069  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 08:51:59.755  1069  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 08:51:59.755  1069  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-31 08:51:59.756  1069  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 08:51:59.756  1069  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 08:51:59.760  1069  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 08:51:59.763   317   892 D CommandListener: Setting iface cfg
08-31 08:51:59.766  1069  7174 D DhcpStateMachine: StoppedState
08-31 08:51:59.766  1069  1375 E WifiStateMachine: Start Dhcp Watchdog 2
08-31 08:51:59.766  1069  7174 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.767  1069  7174 D DhcpStateMachine: WaitBeforeStartState
08-31 08:51:59.767  1069  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=120907  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-31 08:51:59.767  1069  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=120908  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:51:59.768  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=120908  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:51:59.771  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-31 08:51:59.771  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 08:51:59.772  1069  1375 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 08:51:59.772  1069  1375 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 08:51:59.773  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 08:51:59.773  1069  1375 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 08:51:59.774  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:51:59.774  1069  1069 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 08:51:59.776  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:59.776  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:59.777  1069  1375 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:59.778  1069  1375 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:59.778  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:51:59.779  1069  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 08:51:59.780  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:51:59.780  1069  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=120920  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:51:59.780  1069  1069 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 08:51:59.781  7156  7156 I art     : Almond Protected OAT
08-31 08:51:59.781  1069  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=120921  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:51:59.781  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=120921  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:51:59.782  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:75204] from screen [on:0 period:-547462746] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 08:51:59.783  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-547462745] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 08:51:59.783  1069  1375 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 08:51:59.788  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.790  1069  1390 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-31 08:51:59.790  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:59.790  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:59.791  1069  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:59.791  1069  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:59.791  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:59.792  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:51:59.792  1069  1390 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 08:51:59.793  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
08-31 08:51:59.793  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
08-31 08:51:59.793  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 08:51:59.794  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 08:51:59.794  1069  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 08:51:59.794  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 08:51:59.795  1069  1375 D WifiNative-wlan0: SET ps 0: returned true
08-31 08:51:59.795  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 08:51:59.795  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 08:51:59.795  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 08:51:59.795  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@331a14c0 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.795  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@331a14c0 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.796  1069  7174 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.796  1069  7174 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 08:51:59.796  1069  1375 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine,.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 08:51:59.796  1069  1375 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-31 08:51:59.798  1069  1375 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 08:51:59.799   317   892 D CommandListener: Setting iface cfg
08-31 08:51:59.800   317   892 D CommandListener: Trying to bring up wlan0
,08-31 08:51:59.801  1069  1375 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 08:51:59.802  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-31 08:51:59.802  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:51:59.802  1069  1069 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 08:51:59.802  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-31 08:51:59.802  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 08:51:59.802  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-31 08:51:59.802  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.802  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.803  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 08:51:59.803  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 08:51:59.803  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 08:51:59.803  1069  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 08:51:59.803  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 08:51:59.820  1069  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 08:51:59.820  1069  1390 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 08:51:59.821  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:51:59.821  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:51:59.822  1069  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:51:59.822  1069  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:51:59.822  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:51:59.823  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:51:59.823  1069  1390 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-31 08:51:59.824  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 08:51:59.824  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 08:51:59.824  1069  1375 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 08:51:59.824  1069  1390 D ConnectivityService: ignoring duplicate network state non-change
08-31 08:51:59.827  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:59.827  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 08:51:59.828  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.829  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.830  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.830  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 08:51:59.830  1069  1390 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 08:51:59.831  1069  1390 D ConnectivityService: Adding iface wlan0 to network 101
08-31 08:51:59.833  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.834  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.834  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 08:51:59.834  1069  1375 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 08:51:59.835  1069  1069 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 08:51:59.836  1922  1922 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 08:51:59.837  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.837  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.837  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 08:51:59.837  1069  1069 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 08:51:59.843  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.843  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:59.843  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 08:51:59.844  7156  7156 D WeatherApplication: removeAccount
08-31 08:51:59.846  7156  7156 D WeatherApplication: Account.length = 0
08-31 08:51:59.846  7156  7156 E WeatherApplication: OPERATOR:OPEN
08-31 08:51:59.848  1069  1390 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 08:51:59.848  1069  1390 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-31 08:51:59.849  1069  1390 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-31 08:51:59.849   317   892 E Netd    : netlink response contains error (File exists)
08-31 08:51:59.850  1069  1390 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-31 08:51:59.850  1069  1390 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 08:51:59.850  1069  1390 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-31 08:51:59.850  1069  1390 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-31 08:51:59.851  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:59.851  1069  1390 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 08:51:59.851  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:51:59.851  1069  1390 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 08:51:59.851  1069  1390 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-31 08:51:59.851  1069  1390 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 08:51:59.851  1069  1390 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:51:59.851  1069  7173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.851  1069  7173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 08:51:59.851  1069  1390 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:51:59.851  1069  1390 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 08:51:59.851  1069  1390 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:59.851  1069  1390 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 08:51:59.851  1069  1390 D ConnectivityService: currentScore = 0, newScore = 20
08-31 08:51:59.851  1069  1390 D ConnectivityService:    accepting network in place of null
08-31 08:51:59.851  1069  7173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:51:59.851  1069  1390 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:59.851  1069  7173 D NetworkMonitor NetworkAgentInfo [WIFI () - nul,l]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 08:51:59.852  1069  1375 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:59.852  1069  1390 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 08:51:59.852  1069  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:51:59.852  1069  1390 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 08:51:59.852  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 08:51:59.853  1834  1834 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:59.854  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 08:51:59.854  1069  1390 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:51:59.854  1069  1390 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 08:51:59.854  1069  1390 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 08:51:59.855  1069  1390 D ConnectivityService: validation of new default Network = false
08-31 08:51:59.855  1069  1390 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 08:51:59.855  1069  1390 D DSQN    : enableDataServiceNotify 
08-31 08:51:59.855  1069  1390 D DSQN    : start dsqn bin
08-31 08:51:59.857  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:51:59
08-31 08:51:59.857   317  7189 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 08:51:59.857   317  7189 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 08:51:59.858  1069  1069 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 08:51:59.860  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 08:51:59.860  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 08:51:59.860  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 08:51:59.863  1069  1390 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 08:51:59.863  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:51:59.863  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:51:59.863  1069  1390 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:51:59.850  7190  7190 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:51:59.850  7190  7190 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:51:59.867  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 08:51:59.868  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.871  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:59.871  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 08:51:59.872  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.872  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 08:51:59.872  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-31 08:51:59.874  1069  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 08:51:59.875  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 08:51:59.875  7190  7190 E DSQN    : DSQN ssw
08-31 08:51:59.878  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-31 08:51:59.878  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:51:59.878  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 08:51:59.878  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.878  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-31 08:51:59.883  1799  7194 I CheckinService: active receiver: enabled
08-31 08:51:59.889  1799  7194 I CheckinService: Preparing to send checkin request
08-31 08:51:59.889  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 08:51:59.889  1799  7194 I EventLogService: Accumulating logs since 1472626257866
08-31 08:51:59.889  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 08:51:59.889  7156  7156 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-31 08:51:59.895  1799  7194 W EventLogAggregator: Unknown tag: snet_gcore
08-31 08:51:59.895  1799  7194 W EventLogAggregator: Unknown tag: snet_launch_service
,08-31 08:51:59.899  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 08:51:59.900  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.900  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:51:59.915  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 08:51:59.915  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:51:59
,08-31 08:51:59.956  1069  1985 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7197 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:51:59.957  1069  1985 I ActivityManager: Killing 6735:com.lge.bnr/1000 (adj 15): empty #17
08-31 08:51:59.970   346   346 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 275us total 12.548ms
,08-31 08:51:59.982   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 261us total 11.967ms
,08-31 08:51:59.995   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 248us total 11.552ms
,08-31 08:51:59.998  1069  7174 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 08:51:59.998  1069  7174 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 08:51:59.998  1069  7174 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 08:51:59.999  1069  1886 W libprocessgroup: failed to open /acct/uid_1000/pid_6735/cgroup.procs: No such file or directory
08-31 08:51:59.990  7215  7215 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:51:59.990  7215  7215 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:00.005  7215  7215 I dhcpcd  : version 5.5.6 starting
,08-31 08:52:00.007  7215  7215 E dhcpcd  : get_duid: m
08-31 08:52:00.007  7215  7215 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 08:52:00.007  7215  7215 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 08:52:00.036  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-31 08:52:00.036  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
08-31 08:52:00.036  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-31 08:52:00.036  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-31 08:52:00.037  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-31 08:52:00.037  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-31 08:52:00.037  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-31 08:52:00.037  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 08:52:00.053  1069  1363 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7219 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 08:52:00.055  1069  1363 V AlarmManager: RTC_WAKEUP set : Alarm{1171d39f type 0 when 1472626315772 com.android.vending} when 1472626315772
08-31 08:52:00.072  1799  7194 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-31 08:52:00.073  7215  7215 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 08:52:00.073  7215  7215 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 08:52:00.073  7215  7215 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 08:52:00.073  7215  7215 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-31 08:52:00.073  7215  7215 D dhcpcd  : wlan0: sending REQUEST (xid 0x9007aed7), next in 4.67 seconds
,08-31 08:52:00.119  7215  7215 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-31 08:52:00.146  7215  7215 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 08:52:00.146  7215  7215 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-31 08:52:00.147  7215  7215 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 08:52:00.148  7215  7215 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 08:52:00.148  7215  7215 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 08:52:00.148  7215  7215 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 08:52:00.149  7215  7215 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 08:52:00.149  7215  7215 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 08:52:00.169   277   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-31 08:52:00.169   277   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 08:52:00.169   277   354 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:52:00.169  7197  7241 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 08:52:00.173   277   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 08:52:00.173   277   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 08:52:00.173   277   354 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:52:00.174  7197  7241 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 08:52:00.182   277   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 08:52:00.182   277   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 08:52:00.182   277   354 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:52:00.183  7197  7246 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-31 08:52:00.186   277   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 08:52:00.186   277   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 08:52:00.186   277   354 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 08:52:00.186  7197  7246 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 08:52:00.224  1069  1985 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7254 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-31 08:52:00.289  7254  7254 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 08:52:00.290  7254  7254 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 08:52:00.317  7219  7219 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-31 08:52:00.319  7254  7254 I MultiDex: VM with version 2.1.0 has multidex support
08-31 08:52:00.319  7254  7254 I MultiDex: install
,08-31 08:52:00.319  7254  7254 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-31 08:52:00.332  7254  7254 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-31 08:52:00.373  7219  7219 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:52:00.373  7219  7219 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 08:52:00.387  1069  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2049487 type 2 when 121527 com.google.android.gms} when 121527
,08-31 08:52:00.400  1069  7174 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 08:52:00.401  1069  7174 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 08:52:00.401  1069  7174 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 08:52:00.401  1069  7174 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 08:52:00.401  1069  7174 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 08:52:00.401  1069  7174 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 08:52:00.401  1069  7174 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 08:52:00.401  1069  7174 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 08:52:00.401  1069  7174 D DhcpStateMachine: RunningState
08-31 08:52:00.402  7219  7219 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-31 08:52:00.412  2559  2559 D [Concierge]Service: onStartCommand(). Type : 9
08-31 08:52:00.415  7219  7219 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-31 08:52:00.415  7219  7219 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 08:52:00.425  7219  7219 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-31 08:52:00.425  7219  7219 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-31 08:52:00.425  7197  7197 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 08:52:00.444  7197  7197 I LibraryLoader: Loading: webviewchromium
08-31 08:52:00.447  7197  7197 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1597-1601)
08-31 08:52:00.448  7197  7197 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 08:52:00.451  7197  7197 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f6e513a}
08-31 08:52:00.452  7197  7197 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 08:52:00.452  7197  7197 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 08:52:00.460  7197  7197 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 08:52:00.460  7197  7197 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 08:52:00.469  7197  7197 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 08:52:00.469  7197  7197 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
08-31 08:52:00.470  7197  7197 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
08-31 08:52:00.472  1069  1680 V SIM_STK : Menu title from STK is T-Mobile
08-31 08:52:00.474   321   321 V AudioPolicyService: registerClient() client 0xb14e9160, uid 10093
,08-31 08:52:00.475  7197  7324 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 08:52:00.482  7197  7197 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 08:52:00.482  7197  7197 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 08:52:00.482  7197  7197 I Adreno-EGL: Build Date: 12/12/14 금
08-31 08:52:00.482  7197  7197 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 08:52:00.482  7197  7197 I Adreno-EGL: Remote Branch: 
08-31 08:52:00.482  7197  7197 I Adreno-EGL: Local Patches: 
08-31 08:52:00.482  7197  7197 I Adreno-EGL: Reconstruct Branch: 
08-31 08:52:00.526  1069  1559 I art     : Explicit concurrent mark sweep GC freed 100396(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.148ms total 87.033ms
,08-31 08:52:00.531  7197  7197 I NSApplication: Starting up...
08-31 08:52:00.534  2823  3892 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-31 08:52:00.536  2823  3892 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@207d2ab7 on behalf of 7219
08-31 08:52:00.568  7254  7274 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 08:52:00.568  7254  7274 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 08:52:00.578  1069  2009 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7337 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-31 08:52:00.580  1069  2009 I ActivityManager: Killing 2110:com.lge.music/u0a34 (adj 15): empty #17
,08-31 08:52:00.610   321  3959 V AudioFlinger: 2110 died, releasing its sessions
08-31 08:52:00.610   321  3959 V AudioFlinger:  pid 1834 @ 0
08-31 08:52:00.610   321  3959 V AudioFlinger:  pid 3429 @ 1
08-31 08:52:00.610   321  3959 V AudioFlinger:  pid 3429 @ 2
,08-31 08:52:00.611  7352  7352 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-31 08:52:00.613  7219  7219 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-31 08:52:00.659  1069  1085 W libprocessgroup: failed to open /acct/uid_10034/pid_2110/cgroup.procs: No such file or directory
,08-31 08:52:00.668  7352  7352 I dex2oat : dex2oat took 57.224ms (threads: 4)
08-31 08:52:00.671  1069  1954 I ActivityManager: Killing 6815:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-31 08:52:00.687  7254  7274 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 08:52:00.687  7254  7274 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 08:52:00.687  7254  7274 I Adreno-EGL: Build Date: 12/12/14 금
08-31 08:52:00.687  7254  7274 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 08:52:00.687  7254  7274 I Adreno-EGL: Remote Branch: 
08-31 08:52:00.687  7254  7274 I Adreno-EGL: Local Patches: 
08-31 08:52:00.687  7254  7274 I Adreno-EGL: Reconstruct Branch: 
,08-31 08:52:00.690  7337  7337 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:52:00.758  1069  1559 W libprocessgroup: failed to open /acct/uid_10037/pid_6815/cgroup.procs: No such file or directory
,08-31 08:52:00.766  7219  7219 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-31 08:52:00.787  1069  2009 D WifiServiceImplEx: setWifiEnabled: false pid=6648, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 08:52:00.787  1069  2009 D WifiService: setWifiEnabled: false pid=6648, uid=10118
08-31 08:52:00.787  1069  2009 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 08:52:00.788  7219  7219 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-31 08:52:00.797  1069  1375 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 08:52:00.798  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 08:52:00.798  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 08:52:00.798  1069  1069 D Ulp_jni : JNI:system_update. Event-4
,08-31 08:52:00.798  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 08:52:00.798  1069  1375 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 08:52:00.799  1069  1375 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 08:52:00.799  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 08:52:00.799  1069  1375 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 08:52:00.799  1069  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 08:52:00.799  1069  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 08:52:00.800  1069  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 08:52:00.800  1069  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-31 08:52:00.805  1069  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 08:52:00.805  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.805  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.805  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 08:52:00.805  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 08:52:00.805  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 08:52:00.805  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 08:52:00.806  1069  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 08:52:00.806  1069  7174 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.809   317   892 D CommandListener: Clearing all IP addresses on wlan0
08-31 08:52:00.818  1069  1135 W ProcessCpuTracker: Skipping unknown process pid 7215
08-31 08:52:00.837  1069  1390 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 08:52:00.837  1069  1390 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-31 08:52:00.838  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.838  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.838  1069  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@393f3bd9
08-31 08:52:00.838  1069  1374 D LGWifiP2pService: P2pDisablingState
08-31 08:52:00.838  1069  1374 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.838  1069  1374 D LGWifiP2pService: p2p socket connection lost
08-31 08:52:00.838  1069  1374 D LGWifiP2pService: P2pDisabledState
08-31 08:52:00.840  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:00.840  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 08:52:00.841  1922  1922 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 08:52:00.842  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-31 08:52:00.842  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:00.842  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:00.842  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 08:52:00.845  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 08:52:00.845  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:00.845  1922  1922 D WfdsService: WifiP2pState is changed : false
08-31 08:52:00.845  1922  2319 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 08:52:00.845  1922  2319 D WfdsService: Set the WFDS Monitor: false
08-31 08:52:00.846  1922  2319 D WfdsMonitor: WFDS Monitor is stopped
08-31 08:52:00.846  1922  2319 D WfdsService: STATE : WfdsDisabledState - enter
08-31 08:52:00.846  1922  7105 D CtrlSupplicant: Received on exit socket, terminate
08-31 08:52:00.846  1922  7105 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 08:52:00.846  1922  7105 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 08:52:00.846  1922  7105 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 08:52:00.846  1922  2322 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 08:52:00.846  1069  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:00.846  1922  2319 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 08:52:00.847  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:00.847  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-31 08:52:00.847  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:00.847  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:00.847  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:00.847  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 08:52:00.847  1069  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:00.847  1069  1069 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 08:52:00.847  1069  1069 D RttService: SCAN_AVAILABLE : 1
08-31 08:52:00.848  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:00.848  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:00.848  1069  1375 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 08:52:00.848  1069  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 08:52:00.848  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 08:52:00.848  1069  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.849  7072  7072 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 08:52:00.849  1069  1541 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.849  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 08:52:00.849  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 08:52:00.850  1069  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 0,8:52:00.850  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.850  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:00.850  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:00.850  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 08:52:00.851  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:00.853  7254  7274 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 08:52:00.853  7254  7274 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 08:52:00.853  7254  7274 I Adreno-EGL: Build Date: 12/12/14 금
08-31 08:52:00.853  7254  7274 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 08:52:00.853  7254  7274 I Adreno-EGL: Remote Branch: 
08-31 08:52:00.853  7254  7274 I Adreno-EGL: Local Patches: 
08-31 08:52:00.853  7254  7274 I Adreno-EGL: Reconstruct Branch: 
08-31 08:52:00.869   317   892 D CommandListener: Clearing all IP addresses on wlan0
08-31 08:52:00.870  1069  1390 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 08:52:00.870  1069  1390 D DSQN    : disableDataServiceNotify
08-31 08:52:00.870  1069  1390 D DSQN    : stop dsqn bin
,08-31 08:52:00.871  1069  1375 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 08:52:00.871  1069  1375 D WifiNative-p2p0: TERMINATE: returned true
08-31 08:52:00.872  1069  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 08:52:00.872  1069  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 08:52:00.872  1069  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 08:52:00.872  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-31 08:52:00.873  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 08:52:00.873  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:00.875  1069  1390 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 08:52:00.875  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:00.875  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:00.875  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:00.875  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:00.875  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 08:52:00.875  1069  1390 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:00.875  1069  1390 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 08:52:00.875  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 08:52:00.875  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:00.875  1069  1390 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 08:52:00.875  1069  1390 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 08:52:00.875  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 08:52:00.876  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 08:52:00.878  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:00.878  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 08:52:00.879  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:52:00.879  1069  1069 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 08:52:00.879  1069  1390 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:00.879  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 08:52:,00.879  1069  1390 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:00.879  1069  1390 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:00.880  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:00.880  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:00.880  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:00.880  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:00.880  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:00.880  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:00.880  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:00.880  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:00.880  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:00.880  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:00.880  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:00.881  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:00.881  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:00.881  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:00.881  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:00.881  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:00.881  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:00.881  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:00.881  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:00.881  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:00.881  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:00.881  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:00.881  1069  1390 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:00.882  1069  1390 D NetworkManagementService: Removing idletimer
08-31 08:52:00.882  1069  1390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:00.882  1069  1390 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 08:52:00.882  1834  1834 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRIC,TED&TRUSTED&NOT_VPN] ]
08-31 08:52:00.882  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 08:52:00.882  1069  1375 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:00.882  1069  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:52:00.883  1069  1390 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-31 08:52:00.883  1069  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 08:52:00.884  1069  1069 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 08:52:00.884  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 08:52:00.884  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 08:52:00.884  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 08:52:00.887  1069  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 08:52:00.887  1069  1069 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 08:52:00.888  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 08:52:00.888  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 08:52:00.888  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 08:52:00.909  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-31 08:52:00.910  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:00.910  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:00.915  7254  7274 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 08:52:00.915  7254  7274 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 08:52:00.915  7254  7274 I Adreno-EGL: Build Date: 12/12/14 금
08-31 08:52:00.915  7254  7274 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 08:52:00.915  7254  7274 I Adreno-EGL: Remote Branch: 
08-31 08:52:00.915  7254  7274 I Adreno-EGL: Local Patches: 
08-31 08:52:00.915  7254  7274 I Adreno-EGL: Reconstruct Branch: 
08-31 08:52:00.922  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 08:52:00.923  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 08:52:00.924  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 08:52:00.949  7072  7072 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 08:52:00.949  7072  7072 I wpa_supplicant: monitor socket send errors count : 1
08-31 08:52:00.949  7072  7072 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1922-4\x00 that cannot receive messages
08-31 08:52:00.950  1069  7087 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 08:52:00.950  1069  7087 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-31 08:52:00.951  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 08:52:00.952  6458  6490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 08:52:00.964  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:00.971  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 08:52:00.971  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:00.971  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 08:52:00.971  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 08:52:00.972  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 08:52:00.973  7072  7072 W wpa_supplicant: USIM:  scard_deinit function
08-31 08:52:00.974  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 08:52:00.974  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 08:52:00.974  1069  7087 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 08:52:00.974  1069  7087 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 08:52:00.974  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 08:52:00.974  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 08:52:00.975  1069  1165 D Tethering: InitialState.processMessage what=4
08-31 08:52:00.975  1069  1375 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122115
08-31 08:52:00.975  1069  1165 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 08:52:00.976  1069  1375 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122116
,08-31 08:52:00.977  1069  1375 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=122117  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 08:52:00.977  1069  1375 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=122118  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 08:52:00.978  1069  1375 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:00.979  1069  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:00.980  7018  7018 I AppUp4:CustModeStarterReceiver: onReceive
08-31 08:52:00.982  7018  7018 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2473b783
08-31 08:52:00.982  7018  7018 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 08:52:00.982  7018  7018 D AppUp4:CustFacade: isPhone : true
08-31 08:52:00.982  7018  7018 D AppUp4:CustModeStarterReceiver: begin check event
08-31 08:52:00.983  7018  7018 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 08:52:00.985  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:00.985  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 08:52:00.987  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:00.988  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:00.991  4305  7377 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 08:52:00.993  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 08:52:00.997  4305  7378 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:00.997  4305  7378 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 08:52:01.008  7048  7380 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:52:01.012  3429  3429 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 08:52:01.012  3429  3429 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:01.013  3429  3429 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 08:52:01.015  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 08:52:01.015  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 08:52:01.017  1069  7174 D DhcpStateMachine: StoppedState
08-31 08:52:01.017  1069  7174 D DhcpStateMachine: StoppedState{ when=-167ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:01.019  1069  1375 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 08:52:01.019  1069  1375 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 08:52:01.021  6925  7385 W FormManager: Network not available. Please check & try again.
,08-31 08:52:01.024  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:52:1
08-31 08:52:01.027  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 08:52:01.027  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-31 08:52:01.029  6925  7386 V FormManager: Network unavailable.
08-31 08:52:01.031  6925  7386 V FormManager: Network unavailable.
08-31 08:52:01.031  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 08:52:01.031  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-31 08:52:01.032  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a9d2939
08-31 08:52:01.032  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-31 08:52:01.032  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 08:52:01.032  7156  7156 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 08:52:01.032  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 08:52:01.032  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:52:1
08-31 08:52:01.054  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 08:52:01.054  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 08:52:01.054  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-31 08:52:01.054  6835  6835 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 08:52:01.054  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 08:52:01.054  6835  6835 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 08:52:01.054  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 08:52:01.054  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 08:52:01.054  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 08:52:01.055  6835  6835 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 08:52:01.055  6835  6835 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 08:52:01.061  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:52:01.063  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 08:52:01.070  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.071  6925  7388 W FormManager: Network not available. Please check & try again.
08-31 08:52:01.075  6925  7389 V FormManager: Network unavailable.
08-31 08:52:01.076  6925  7389 V FormManager: Network unavailable.
08-31 08:52:01.085  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 08:52:01.088  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:01.089  6925  7391 W FormManager: Network not available. Please check & try again.
08-31 08:52:01.091  6925  7392 V FormManager: Network unavailable.
08-31 08:52:01.092  6925  7392 V FormManager: Network unavailable.
08-31 08:52:01.094  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.103  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 08:52:01.103  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 08:52:01.105  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:01.106  7072  7072 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 08:52:01.107  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:01.107  1069  7087 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 08:52:01.107  1069  7087 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 08:52:01.107  1069  7087 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 08:52:01.110  1069  1375 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-31 08:52:01.113  1922  1922 D WfdsService: Supplicant Connection state is changed : false
08-31 08:52:01.113  1922  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 08:52:01.113  1922  2319 D WfdsService: Set the WFDS Monitor: false
08-31 08:52:01.113  1922  2319 D WfdsMonitor: WFDS Monitor is stopped
08-31 08:52:01.113  1069  1375 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 08:52:01.114  1069  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 08:52:01.114  1069  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 08:52:01.114  1069  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 08:52:01.117  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:01.117  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-31 08:52:01.119  2479  2479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:01.119  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:01.119  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:01.119  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:01.119  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:01.119  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:01.119  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:01.119  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:01.119  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:01.119  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:01.120  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:01.120  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:01.120  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:01.120  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:01.120  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:01.120  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:01.120  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:01.120  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:01.120  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:01.121  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 08:52:01.121  1069  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 08:52:01.121  1069  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 08:52:01.122  4305  7393 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 08:52:01.125  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:01.127  4305  7394 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 08:52:01.127  4305  7394 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 08:52:01.131  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.136  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.144  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:01.144  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:01.146  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 08:52:01.203  1069  1954 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7395 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 08:52:01.244   317  7413 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 08:52:01.244  1069  1163 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 08:52:01.244  1799  7194 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-31 08:52:01.257  1799  7194 I CheckinService: active receiver: disabled
,08-31 08:52:01.315  7395  7395 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 08:52:01.315  7395  7395 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 08:52:01.325  7395  7395 V [BNRBootReceiver]: Boot Receiver Return
08-31 08:52:01.325  7395  7395 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 08:52:01.333  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 08:52:01.347  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.355  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.367  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 08:52:01.368  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 08:52:01.371  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 08:52:01.379  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-31 08:52:01.386  6835  6835 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 08:52:01.393  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:01.409  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.424  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 08:52:01.442  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:01.442  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:01.444  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 08:52:01.453  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 08:52:01.469  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.479  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.500  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:01.501  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 08:52:01.502  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 08:52:01.513  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:01.532  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.544  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 08:52:01.554  6755  6994 D UEI.SmartControl: Internal timer expired: 2
08-31 08:52:01.554  6755  6994 D UEI.SmartControl: unbind internal service
08-31 08:52:01.557  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:01.558  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:01.559  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 08:52:01.567  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:01.583  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.597  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.612  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:01.613  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 08:52:01.616  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 08:52:01.625  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:01.639  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.651  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.665  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:01.665  6755  6988 D serial_port: close(fd = 24)
,08-31 08:52:01.665  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:01.667  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 08:52:01.671  6755  6988 I UEI.SmartControl: Serial port is closed.
08-31 08:52:01.684  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 08:52:01.710  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.724  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.740  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:01.741  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:01.747  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 08:52:01.759  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:01.780  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.798  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 08:52:01.819  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:01.820  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:01.823  6884  6884 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 08:52:01.834  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:01.850  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 08:52:01.864  1069  1385 D WifiService: New client listening to asynchronous messages
08-31 08:52:01.866  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 08:52:01.871  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.881  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.895  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 08:52:01.896  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:01.898  6884  6884 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 08:52:01.899  6884  6884 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 08:52:01.900  6884  6884 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 08:52:01.907  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 08:52:01.916  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 08:52:01.919  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 08:52:01.927  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:01.937  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:01.951  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:01.952  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 08:52:01.952  6884  6884 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 08:52:01.953  6884  6884 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 08:52:01.954  6884  6884 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 08:52:01.958  1069  1885 I ActivityManager: Killing 6904:com.lge.settings.easy/1000 (adj 15): empty #17
08-31 08:52:01.987  4492  7422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-31 08:52:02.018  1069  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_6904/cgroup.procs: No such file or directory
,08-31 08:52:02.029  2203  2203 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-31 08:52:02.051  2203  2203 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-31 08:52:02.052  2203  2203 D c       : Getting all permits...
08-31 08:52:02.052  2203  2203 D a       : Opening database...
08-31 08:52:02.061  2203  2203 D a       : Opening database auth.proximity.permit_store...
08-31 08:52:02.062  2203  2203 D a       : Closing database...
08-31 08:52:02.079   317  7430 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-31 08:52:02.081  1069  1163 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-31 08:52:02.089  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:02.093  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 08:52:02.093  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 08:52:02.093  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 08:52:02.104  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:02.110  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:02.119  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 08:52:02.120  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:02.122  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 08:52:02.125  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:02.128  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 08:52:02.128  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 08:52:02.128  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:52:02.132  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 08:52:02.137  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:02.141  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:02.142  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:02.143  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 08:52:02.148  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:02.153  6856  6856 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 08:52:02.153  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 08:52:02.153  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:52:02.156  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:02.162  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:02.169  6884  6884 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:02.169  6884  6884 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:02.170  6884  6884 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 08:52:02.176  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:52:02.180  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:02.182  6925  7442 W FormManager: Network not available. Please check & try again.
,08-31 08:52:02.186  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:02.191  6925  7443 V FormManager: Network unavailable.
08-31 08:52:02.197  6925  7443 V FormManager: Network unavailable.
,08-31 08:52:02.205  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 08:52:02.205  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 08:52:02.207  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:02.209  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:02.215  4305  7447 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 08:52:02.216  6856  6856 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 08:52:02.216  6856  6856 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 08:52:02.216  6856  6856 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:52:02.219  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:02.220  4305  7448 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 08:52:02.220  4305  7448 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 08:52:02.223  6925  7450 W FormManager: Network not available. Please check & try again.
,08-31 08:52:02.227  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:02.237  6925  7451 V FormManager: Network unavailable.
08-31 08:52:02.239  2203  2203 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-31 08:52:02.243  6925  7451 V FormManager: Network unavailable.
,08-31 08:52:02.792  1069  1375 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-547459737] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 08:52:02.794  1069  1375 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-547459734] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 08:52:02.857  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:02.868  1069  1165 D Tethering: MasterInitialState.processMessage what=3
08-31 08:52:02.876  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:02.880  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:02.883  1069  1131 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:02.885  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 08:52:02.887  5798  5798 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 08:52:02.889  6458  6490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 08:52:02.919  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:02.938  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 08:52:02.938  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:02.939  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 08:52:02.939  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 08:52:02.943  7018  7018 I AppUp4:CustModeStarterReceiver: onReceive
08-31 08:52:02.947  7018  7018 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2473b783
08-31 08:52:02.947  7018  7018 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 08:52:02.947  7018  7018 D AppUp4:CustFacade: isPhone : true
08-31 08:52:02.948  7018  7018 D AppUp4:CustModeStarterReceiver: begin check event
08-31 08:52:02.948  7018  7018 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 08:52:02.953  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:02.953  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 08:52:02.954  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 08:52:02.960  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:02.968  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 08:52:02.999  4305  7464 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 08:52:03.006  7048  7463 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:03.027  4305  7465 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:03.027  4305  7465 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 08:52:03.031  1069  1131 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:03.038  3429  3429 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 08:52:03.039  3429  3429 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:03.039  3429  3429 I LgeMiscReceiver: networkInfo.isConnected() = true
08-31 08:52:03.039  3429  3429 D PhoneState: setPdpRejectCasuse : false
,08-31 08:52:03.045  6925  7476 W FormManager: Network not available. Please check & try again.
08-31 08:52:03.047  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 08:52:03.047  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 08:52:03.060  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:52:3
,08-31 08:52:03.062  6925  7479 V FormManager: Network unavailable.
08-31 08:52:03.063  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 08:52:03.063  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-31 08:52:03.063  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 08:52:03.063  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-31 08:52:03.063  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a9d2939
08-31 08:52:03.066  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 08:52:03.066  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 08:52:03.066  7156  7156 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 08:52:03.066  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 08:52:03.066  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:52:3
08-31 08:52:03.076  6925  7479 V FormManager: Network unavailable.
,08-31 08:52:03.800  1069  1985 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 08:52:03.801  1069  1985 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 08:52:03.829  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 08:52:03.830  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 08:52:03.830  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-31 08:52:03.831  1069  1165 D BluetoothManagerService: Message: 1
08-31 08:52:03.831  1069  1165 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 08:52:03.858  1069  1165 D BluetoothManagerService: Message: 20
08-31 08:52:03.858  1069  1165 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@108f0098:true
,08-31 08:52:03.862  6955  6955 D BluetoothAdapterState: make
08-31 08:52:03.867  6955  6955 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 08:52:03.867  6955  6955 I bluedroid-qcom: init
08-31 08:52:03.868  6955  7494 I BluetoothAdapterState: Entering OffState
08-31 08:52:03.869  6955  6955 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 08:52:03.869  6955  6955 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 08:52:03.869  6955  6955 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 08:52:03.869  6955  6955 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 08:52:03.869  6955  6955 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 08:52:03.871  6955  6955 I bluedroid-qcom: get_profile_interface socket
08-31 08:52:03.871  6955  6955 I bluedroid-qcom: get_profile_interface map_client
,08-31 08:52:03.876  6955  7498 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 08:52:03.870  7497  7497 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:03.880  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:03.870  7497  7497 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:03.888  1069  1165 D Tethering: MasterInitialState.processMessage what=3
,08-31 08:52:03.891  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:03.892  1069  1131 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:03.896  7497  7497 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 08:52:03.896  7497  7497 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 08:52:03.896  7497  7497 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-31 08:52:03.902  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:03.905  7497  7497 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 08:52:03.909  7497  7497 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 08:52:03.909  7497  7497 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 08:52:03.912  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:03.917  1069  1165 D Tethering: MasterInitialState.processMessage what=3
,08-31 08:52:03.921  6955  7498 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 08:52:03.929  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:03.932  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:03.936  1069  1069 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 08:52:03.936  1069  1165 D BluetoothManagerService: Message: 40
08-31 08:52:03.936  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 08:52:03.937  6955  6970 I bluedroid-qcom: config_hci_snoop_log
08-31 08:52:03.938  1069  1165 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 08:52:03.938  1069  1165 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 08:52:03.942  6955  7498 D BluetoothAdapterProperties: Name is: G3
,08-31 08:52:03.947  6955  7494 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 08:52:03.947  6955  7494 D BluetoothAdapterProperties: Setting state to 11
08-31 08:52:03.947  6955  7494 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 08:52:03.949  6955  7494 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 08:52:03.952  1069  1069 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 08:52:03.952  1069  1069 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 08:52:03.953  1069  1165 D BluetoothManagerService: Message: 60
08-31 08:52:03.953  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 08:52:03.953  1069  1165 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 08:52:03.954  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:03.972  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-31 08:52:03.976  6955  7494 D BluetoothBondStateMachine: make
08-31 08:52:03.977  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:03.978  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 08:52:03.981  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:03.983  6835  6835 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 08:52:03.984  6955  7494 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:03.984  6955  7494 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 08:52:03.984  6955  7494 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:03.984  6955  7494 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 08:52:03.985  1069  1131 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:03.986  6955  7494 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 08:52:03.986  1069  1131 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:03.986  1069  1131 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:03.987  6955  7511 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 08:52:03.992  6955  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:03.993  6955  6955 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 08:52:03.994  6955  6955 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:03.994  6955  6955 V BluetoothPbapReceiver: ***********state = 11
08-31 08:52:03.997  6458  6490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 08:52:04.010  6955  6955 D HeadsetService: Received start request. Starting profile...
08-31 08:52:04.010  5798  5798 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 08:52:04.011  6955  6955 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 08:52:04.011  6955  6955 D LGBluetoothHfpAdapter: Version 1.6
08-31 08:52:04.012  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 08:52:04.013  6955  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:04.014  6955  6955 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 08:52:04.015  6955  6955 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 08:52:04.016  6955  6955 D HeadsetStateMachine: make
08-31 08:52:04.020  6955  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:04.028  6955  7494 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 08:52:04.059  6955  6955 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 08:52:04.059  6955  6955 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 08:52:04.072  1069  1931 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7519 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-31 08:52:04.081  6955  6955 D HeadsetStateMachine: max_hf_connections = 1
08-31 08:52:04.081  6955  6955 I bluedroid-qcom: get_profile_interface handsfree
08-31 08:52:04.082  5798  5798 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 08:52:04.082  6955  6955 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 08:52:04.084  6955  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:04.084   321  2143 V AudioPolicyService: registerClient() client 0xb1508560, uid 1002
08-31 08:52:04.084   321   321 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 08:52:04.084   321   321 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 08:52:04.084   321   321 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 08:52:04.084  6955  6955 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 08:52:04.085   321  1388 V AudioFlinger: registerClient() client 0xb5581610, pid 6955
08-31 08:52:04.085   321  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:04.085   321  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:04.085  6955  6955 V ToneGenerator: Create Track: 0xb4928080
08-31 08:52:04.085  6955  6955 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 08:52:04.085  6955  6955 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 08:52:04.085  1586  2541 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:04.085  1586  2541 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:04.085  1834  1850 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:04.085  1834  1850 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:04.085  3429  3446 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:04.085  3429  3446 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:04.085   321   321 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 08:52:04.085   321   321 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 08:52:04.085   321   321 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 08:52:04.085   321   321 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 08:52:04.086  6955  6955 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 08:52:04.086   321  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:04.086   321  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:04.086  1586  2073 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:04.086  1586  2073 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:04.086   321  1387 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 08:52:04.086  1834  2697 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:04.086  1834  2697 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:04.086  3429  3445 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:04.086  3429  3445 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:04.086   321  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 08:52:04.086   321  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 08:52:04.086   321  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 08:52:04.086   321  1387 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 08:52:04.086  6955  6971 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:04.086  ,6955  6971 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 08:52:04.093  6955  6971 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:04.093  1069  1680 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:04.093  1069  1680 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:04.093  6955  6971 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 08:52:04.093  1069  1680 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:04.093  1069  1680 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:04.093  6955  6955 V AudioSystem: getLatency() output 2, latency 50
08-31 08:52:04.093  6955  6955 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 08:52:04.093  6955  6955 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 08:52:04.096   321  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 08:52:04.096   321  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 08:52:04.096   321  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 08:52:04.096   321  2143 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 08:52:04.096   321  2143 V AudioFlinger: createTrack() lSessionId: 20
08-31 08:52:04.097  6955  6955 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 08:52:04.098   321  2143 V AudioFlinger: acquiring 20 from 6955, for 6955
08-31 08:52:04.098   321  2143 V AudioFlinger:  added new entry for 20
08-31 08:52:04.098  6955  6955 V ToneGenerator: ToneGenerator INIT OK, time: 125251
08-31 08:52:04.098  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:04.098  6955  7518 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 08:52:04.098  6955  7518 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 08:52:04.099  6955  7518 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 08:52:04.099  6955  7518 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 08:52:04.105   321  1388 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6955
08-31 08:52:04.105   321  1388 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 08:52:04.106   321  1388 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 08:52:04.106   321  1388 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 08:52:04.106   321  1388 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 08:52:04.106   321  1388 V voice   : voice_set_parameters: exit with code(0)
08-31 08:52:04.106   321  1388 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 08:52:04.106   321  1388 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 08:52:04.106   321  1388 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 08:52:04.106   321  1388 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 08:52:04.106   321  1388 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 08:52:04.106   321  1388 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 08:52:04.106  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:04.107  6955  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:04.108  6955  6955 D A2dpService: Received start request. Starting profile...
,08-31 08:52:04.109  6955  6955 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 08:52:04.110  6955  6955 V Avrcp   : make
08-31 08:52:04.110  6955  7518 V ToneGenerator: ToneGenerator destructor
08-31 08:52:04.110  6955  7518 V ToneGenerator: stopTone
08-31 08:52:04.110  6955  7518 V ToneGenerator: Delete Track: 0xb4928080
08-31 08:52:04.110  6955  7518 V AudioTrack: ~AudioTrack, releasing session id from 6955 on behalf of 6955
08-31 08:52:04.110   321  3959 V AudioFlinger: releasing 20 from 6955 for 6955
08-31 08:52:04.110   321  3959 V AudioFlinger:  decremented refcount to 0
08-31 08:52:04.110   321  3959 V AudioFlinger: purging stale effects
08-31 08:52:04.110   321  3959 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 08:52:04.110   321  3959 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 08:52:04.110  6955  6955 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 08:52:04.110  6955  6955 I bluedroid-qcom: get_profile_interface avrcp
08-31 08:52:04.111   321  1260 V AudioPolicyService: AudioCommandThread() waking up
08-31 08:52:04.111   321  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 08:52:04.111   321  1260 V AudioPolicyManager: releaseOutput() 2
08-31 08:52:04.111   321  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 08:52:04.111   321  3959 V AudioFlinger: PlaybackThread::Track destructor
08-31 08:52:04.111   321  3959 V AudioFlinger: removeClient_l() pid 6955, calling pid 321
08-31 08:52:04.118  6955  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:04.124  6955  6955 V AudioManager: registerRemoteController: size of Media player list: 0
,08-31 08:52:04.126  6955  6955 E AudioManager: No RCC entry present to update
08-31 08:52:04.126  6955  6955 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 08:52:04.127  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:04.130  6955  6955 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 08:52:04.131  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 08:52:04.131  6955  6955 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 08:52:04.137  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-31 08:52:04.137  6955  7494 V LGMDMManager: Create singleton instance
,08-31 08:52:04.141  6955  7494 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 08:52:04.182  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 08:52:04.182  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:04.183  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 08:52:04.183  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 08:52:04.187  7018  7018 I AppUp4:CustModeStarterReceiver: onReceive
08-31 08:52:04.196  7018  7018 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2473b783
08-31 08:52:04.197  7018  7018 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 08:52:04.197  7018  7018 D AppUp4:CustFacade: isPhone : true
,08-31 08:52:04.198  7018  7018 D AppUp4:CustModeStarterReceiver: begin check event
08-31 08:52:04.198  7018  7018 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 08:52:04.205  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:04.205  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 08:52:04.208  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:04.210  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 08:52:04.222  4305  7540 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 08:52:04.226  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 08:52:04.232  1069  2009 V SIM_STK : Menu title from STK is T-Mobile
08-31 08:52:04.232  1069  2009 V SIM_STK : Menu title from STK is T-Mobile
08-31 08:52:04.232  4305  7541 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:04.233  4305  7541 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 08:52:04.250  7048  7543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:52:04.252  6925  7545 W FormManager: Network not available. Please check & try again.
08-31 08:52:04.253  7519  7519 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-31 08:52:04.254  7519  7519 W LG Account v2.2: No ProfileInfo entries
08-31 08:52:04.254  7519  7519 I LG Account v2.2: isEnabled: false
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]Country: EU
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]Operator: OPEN
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]Ranking support: false
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]Comfort support: false
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]Accessory: true
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]Health device: true
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]Extra Pedometer: false
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]Blood glucose device: false
08-31 08:52:04.254  7519  7519 I Feature : [Lifetracker]Device Number: 3
08-31 08:52:04.257  6925  7547 V FormManager: Network unavailable.
08-31 08:52:04.262  3429  3429 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 08:52:04.262  3429  3429 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:04.262  3429  3429 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 08:52:04.263  6925  7547 V FormManager: Network unavailable.
08-31 08:52:04.266  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 08:52:04.266  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 08:52:04.271  6835  6835 D BluetoothPermissionRequest: onReceive
08-31 08:52:04.276  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:52:4
,08-31 08:52:04.277  6835  6835 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 08:52:04.278  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 08:52:04.278  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-31 08:52:04.279  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 08:52:04.279  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-31 08:52:04.279  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a9d2939
08-31 08:52:04.280  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 08:52:04.280  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 08:52:04.280  7156  7156 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 08:52:04.280  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 08:52:04.280  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:52:4
08-31 08:52:04.296  6458  6458 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-31 08:52:04.297  6458  6490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 08:52:04.310  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:04.316  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 08:52:04.317  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:04.317  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 08:52:04.317  7018  7018 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 08:52:04.318  7018  7018 I AppUp4:CustModeStarterReceiver: onReceive
08-31 08:52:04.322  1069  1904 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 08:52:04.322  7018  7018 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2473b783
08-31 08:52:04.322  7018  7018 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 08:52:04.322  7018  7018 D AppUp4:CustFacade: isPhone : true
08-31 08:52:04.323  7018  7018 D AppUp4:CustModeStarterReceiver: begin check event
08-31 08:52:04.323  7018  7018 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 08:52:04.327  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:04.327  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 08:52:04.328  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 08:52:04.328  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:04.331  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:04.332  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 08:52:04.333  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 08:52:04.333  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 08:52:04.333  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 08:52:04.333  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 08:52:04.333  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 08:52:04.333  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 08:52:04.333  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 08:52:04.333  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 08:52:04.333  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 08:52:04.334  6955  6955 I BluetoothA2dpServiceJni: classInitNative
08-31 08:52:04.334  6955  6955 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 08:52:04.334  6955  6955 D A2dpStateMachine: make
08-31 08:52:04.335  6955  6955 I bluedroid-qcom: get_profile_interface a2dp
,08-31 08:52:04.335  6955  7551 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 08:52:04.336  7048  7048 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 08:52:04.337  4305  7549 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 08:52:04.337  6955  6955 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 08:52:04.337  6955  6955 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 08:52:04.338  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:04.338  6955  7550 D A2dpStateMachine: Enter Disconnected: -2
08-31 08:52:04.339  6955  6955 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 08:52:04.339  4305  7553 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:04.339  4305  7553 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 08:52:04.341  6955  6955 D HidService: Received start request. Starting profile...
08-31 08:52:04.341  6955  6955 I bluedroid-qcom: get_profile_interface hidhost
08-31 08:52:04.341  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:04.341  6955  6955 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 08:52:04.343  6955  6955 D HealthService: Received start request. Starting profile...
08-31 08:52:04.344  6955  6955 I bluedroid-qcom: get_profile_interface health
08-31 08:52:04.344  6955  6955 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 08:52:04.345  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:04.345  6955  6955 D HeadsetStateMachine: Proxy object connected
08-31 08:52:04.345  6955  6955 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 08:52:04.345  6955  6955 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 08:52:04.346  6955  6955 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 08:52:04.348  6955  6955 D PanService: Received start request. Starting profile...
08-31 08:52:04.348  6955  6955 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 08:52:04.348  6955  6955 I bluedroid-qcom: get_profile_interface pan
08-31 08:52:04.352  6955  6955 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 08:52:04.352  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:04.353  6955  7518 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 08:52:04.353  6955  7518 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 08:52:04.354  6955  7518 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-31 08:52:04.355  6955  6955 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 08:52:04.356  6955  6955 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 08:52:04.360  7048  7556 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:04.361  6925  7559 W FormManager: Network not available. Please check & try again.
08-31 08:52:04.362  6955  6955 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 08:52:04.362  6955  6955 D BtGatt.GattService: Received start request. Starting profile...
08-31 08:52:04.362  6955  6955 D BtGatt.GattService: start()
08-31 08:52:04.362  6955  6955 I bluedroid-qcom: get_profile_interface gatt
08-31 08:52:04.362  6955  6955 D BtGatt.AdvertiseManager: advertise manager created
08-31 08:52:04.363  3429  3429 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 08:52:04.363  3429  3429 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:04.364  3429  3429 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 08:52:04.366  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 08:52:04.366  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 08:52:04.369  6925  7560 V FormManager: Network unavailable.
08-31 08:52:04.372  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:04.374  7156  7156 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:52:4
08-31 08:52:04.375  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:04.375  6955  6955 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 08:52:04.376  6955  6955 V BluetoothMapService: BluetoothMapBinder()
08-31 08:52:04.376  6925  7560 V FormManager: Network unavailable.
08-31 08:52:04.376  7156  7156 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 08:52:04.376  7156  7156 D Weather.Utils: 2 : All the weather widget is gone.
08-31 08:52:04.376  6955  6955 D BluetoothMapService: Received start request. Starting profile...
08-31 08:52:04.376  6955  6955 D BluetoothMapService: start()
08-31 08:52:04.377  7156  7156 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-31 08:52:04.377  7156  7156 D WeatherAncestor: connectivity changed - connection : true
08-31 08:52:04.377  7156  7156 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a9d2939
08-31 08:52:04.378  7156  7156 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 08:52:04.378  7156  7156 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 08:52:04.378  7156  7156 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 08:52:04.378  7156  7156 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 08:52:04.378  7156  7156 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:52:4
08-31 08:52:04.379  6955  6955 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 08:52:04.379  6955  6955 D BluetoothMapEmailAppObserver: createReceiver()
08-31 08:52:04.380  6955  6955 D BluetoothMapEmailAppObserver: initObservers()
08-31 08:52:04.380  6955  6955 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 08:52:04.388  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
,08-31 08:52:04.391  6955  6955 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 08:52:04.396  6955  6955 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 08:52:04.398  6955  6955 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 08:52:04.399  6955  6955 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 08:52:04.401  6955  6955 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 08:52:04.403  6955  6955 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 08:52:04.403  6955  6955 V BluetoothMapService: Handler(): got msg=1
08-31 08:52:04.404  6955  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 08:52:04.404  6955  7494 I bluedroid-qcom: enable
08-31 08:52:04.404  6955  7564 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 08:52:04.404  6955  7564 I bt-btu  : btu_task pending for preload complete event
08-31 08:52:04.404  6955  7494 I bt_hci_bdroid: init
08-31 08:52:04.405  6955  6955 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:04.405  6955  7494 I bt_vendor: bt-vendor : init
08-31 08:52:04.405  6955  7494 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 08:52:04.405  6955  7494 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 08:52:04.405  6955  7494 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 08:52:04.405  6955  7494 D bt_userial_mct: userial_init
08-31 08:52:04.407  6955  7494 D bt_hci_bdroid: set_power 1
08-31 08:52:04.407  6955  7494 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 08:52:04.407  6955  7494 I bt_vendor: Starting hciattach daemon
08-31 08:52:04.407  6955  7494 I bt_vendor: try to set true
08-31 08:52:04.407  6955  6955 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 08:52:04.407  6955  6955 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 08:52:04.407  6955  6955 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 08:52:04.407  6955  6955 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:04.407  6955  6955 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 08:52:04.400  7567  7567 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:04.400  7567  7567 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:04.447  7568  7568 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 08:52:04.450  1069  1597 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7569 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 08:52:04.527  7569  7569 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 08:52:04.547  1069  1597 I ActivityManager: Killing 7219:com.android.vending/u0a44 (adj 15): empty #17
,08-31 08:52:04.548  7591  7591 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-31 08:52:04.570  7592  7592 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 08:52:04.603  7594  7594 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 08:52:04.611  1069  2009 W libprocessgroup: failed to open /acct/uid_10044/pid_7219/cgroup.procs: No such file or directory
,08-31 08:52:04.623  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 08:52:04.648  7596  7596 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 08:52:04.664  7597  7597 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 08:52:04.687  7602  7602 I libmdmdetect: ESOC framework not supported
08-31 08:52:04.687  7602  7602 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 08:52:04.699  7602  7602 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-31 08:52:04.699  7602  7602 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 08:52:04.699  7602  7602 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-31 08:52:04.699  7602  7602 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 08:52:04.699  7602  7602 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 08:52:04.700  7602  7602 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 08:52:04.700  7602  7602 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-31 08:52:04.742  7602  7603 E QC-QMI  : qmi_client [7602] 14: failed to locate client data
,08-31 08:52:04.744   450   450 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-31 08:52:04.744   450   450 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-31 08:52:04.779  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 08:52:04.794  7608  7608 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 08:52:04.808  6955  7494 I bt_vendor: bluetooth satus is on
08-31 08:52:04.808  6955  7494 D bt_hci_bdroid: preload
,08-31 08:52:04.810  6955  7566 D bt_userial_mct: userial_open(port:0)
08-31 08:52:04.810  6955  7566 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 08:52:04.814  6955  7566 I bt_vendor: Done intiailizing UART
08-31 08:52:04.814  6955  7566 I bt_vendor: Done intiailizing UART
08-31 08:52:04.814  6955  7566 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 08:52:04.815  6955  7566 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 08:52:04.815  6955  7610 D bt_userial_mct: Entering userial_read_thread()
08-31 08:52:04.815  6955  7564 I bt-btu  : btu_task received preload complete event
08-31 08:52:04.815  6955  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 08:52:04.816  6955  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 08:52:04.818  6955  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 08:52:04.821  6955  7564 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 08:52:04.821  6955  7564 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 08:52:04.821  6955  7564 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 08:52:04.821  6955  7564 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 08:52:04.821  6955  7564 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 08:52:04.821  6955  7564 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 08:52:04.822  6955  7564 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 08:52:04.862   317  7189 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
,08-31 08:52:04.868  1069  1163 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-31 08:52:04.869  1069  7173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-31 08:52:04.870  1069  7173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-3s995ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:52:04.871  1069  7173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3s996ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:52:04.871  1069  7173 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-31 08:52:04.938  6955  7564 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-31 08:52:04.938  6955  7564 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0199061 ,
08-31 08:52:04.938  6955  7564 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0199061 ,
,08-31 08:52:04.991  6955  7498 E bt-btif : Calling BTA_HhEnable
08-31 08:52:04.991  6955  7498 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 08:52:04.992  6955  7498 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 08:52:04.999  1069  1069 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-31 08:52:04.999  1069  1069 D BluetoothManagerService: Stored Bluetooth name: G3
,08-31 08:52:05.000  6955  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-31 08:52:05.000  6955  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-31 08:52:05.000  6955  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-31 08:52:05.001  6955  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 08:52:05.001  6955  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-31 08:52:05.002  6955  7498 D BluetoothAdapterProperties: Name is: G3
08-31 08:52:05.004  6955  7498 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:52:05.005  6955  7498 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 08:52:05.005  6955  7498 D bt_hci_bdroid: postload
,08-31 08:52:05.014  6955  7566 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 08:52:05.017  6955  7564 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 08:52:05.018  6955  7498 D bte_conf: Device ID record 1 : primary
08-31 08:52:05.018  6955  7498 D bte_conf:   vendorId            = 00c4
08-31 08:52:05.018  6955  7498 D bte_conf:   vendorIdSource      = 0001
08-31 08:52:05.018  6955  7498 D bte_conf:   product             = 13a1
08-31 08:52:05.018  6955  7498 D bte_conf:   version             = 1000
08-31 08:52:05.018  6955  7498 D bte_conf:   clientExecutableURL = 
08-31 08:52:05.018  6955  7498 D bte_conf:   serviceDescription  = 
08-31 08:52:05.018  6955  7498 D bte_conf:   documentationURL    = 
08-31 08:52:05.018  6955  7498 D bte_conf: bte_load_did_conf no section named DID2.
08-31 08:52:05.019  6955  7566 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 08:52:05.022  6955  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 08:52:05.022  6955  7494 D BluetoothAdapterProperties: ScanMode =  20
08-31 08:52:05.022  6955  7494 D BluetoothAdapterProperties: State =  11
08-31 08:52:05.022  6955  7494 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 08:52:05.023  6955  7494 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 08:52:05.023  6955  7494 D BluetoothAdapterProperties: Setting state to 12
08-31 08:52:05.023  6955  7494 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 08:52:05.027  6955  7498 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 08:52:05.028  1069  1165 D BluetoothManagerService: Message: 60
08-31 08:52:05.028  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 08:52:05.028  1069  1165 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-31 08:52:05.029  6955  7566 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 08:52:05.030  6955  7498 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 08:52:05.020  7615  7615 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:05.020  7615  7615 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:05.037  6955  7566 D bt_hci_bdroid: Used up Tx Cmd credits
,08-31 08:52:05.041  6955  7610 E bt_mct  : hci lib postload completed
08-31 08:52:05.050  6955  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 08:52:05.050  6955  7564 W bt-smp  : Plain text(LSB ~ MSB) = cb 79 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:05.050  6955  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = 50 a1 90 d0 43 d2 75 4d 47 58 c2 09 dc 4c f9 ed 
,08-31 08:52:05.052  6955  7564 W bt-btm  : Stopping oneshot timer
08-31 08:52:05.067  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:05.067  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:05.067  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:05.067  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:05.067  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:05.067  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:05.067  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:05.067  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:05.075  6955  7494 I BluetoothAdapterState: Entering On State
08-31 08:52:05.076  1834  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:05.079  6955  7498 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 08:52:05.079  6955  7498 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-31 08:52:05.084  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:05.088  6955  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 08:52:05.088  6955  7564 W bt-smp  : Plain text(LSB ~ MSB) = 76 cd 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:05.088  6955  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = 77 07 b6 bc 96 4d 0b 4a d6 db 89 2f 47 67 b3 4f 
08-31 08:52:05.089  6955  7564 W bt-btm  : Stopping oneshot timer
08-31 08:52:05.102  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:05.102  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:05.102  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:05.102  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:05.102  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:05.102  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:05.102  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:05.102  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:05.107  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:05.108  6955  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 08:52:05.108  6955  7564 W bt-smp  : Plain text(LSB ~ MSB) = 74 b5 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:05.108  6955  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = 5d af e5 b9 9b 4b d2 3f b0 31 91 f7 59 68 d8 db 
08-31 08:52:05.108  6955  7564 W bt-btm  : Stopping oneshot timer
08-31 08:52:05.114  6955  7494 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 08:52:05.114  6955  7494 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 08:52:05.114  6955  7494 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-31 08:52:05.117  6955  7494 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 08:52:05.125  1834  1834 D BluetoothHeadset: Proxy object connected
08-31 08:52:05.126  6955  7494 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-31 08:52:05.128  6955  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 08:52:05.128  6955  7564 W bt-smp  : Plain text(LSB ~ MSB) = 0e 70 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:05.128  6955  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = a8 8a 97 8e d1 f2 74 a2 68 bf 59 ef b9 ee ce 46 
08-31 08:52:05.128  6955  7564 W bt-btm  : Stopping oneshot timer
08-31 08:52:05.146  6835  6851 D BluetoothPan: onBluetoothStateChange on: true
08-31 08:52:05.146  6835  6851 D BluetoothPan: onBluetoothStateChange call bindService
,08-31 08:52:05.157  7620  7620 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 08:52:05.163  1069  1165 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:52:05.167  1069  1069 D BluetoothA2dp: Proxy object connected
08-31 08:52:05.169  1834  1849 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:05.171  1834  1834 D BluetoothHeadset: Proxy object connected
08-31 08:52:05.171  1069  1165 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:05.172  1069  1069 D BluetoothHeadset: Proxy object connected
08-31 08:52:05.173  6835  6852 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 08:52:05.174  6955  7564 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 08:52:05.174  6955  7564 W bt-smp  : Plain text(LSB ~ MSB) = 73 dc 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:05.174  6955  7564 W bt-smp  : Encrypted text(LSB ~ MSB) = 54 fa ac 9d 4b 7f 5b f0 f5 26 ad c5 69 c4 4e ad 
08-31 08:52:05.174  6955  7564 W bt-btm  : Stopping oneshot timer
08-31 08:52:05.185  6835  6835 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 08:52:05.185  6835  6835 D PanProfile: Bluetooth service connected
,08-31 08:52:05.191  6835  6851 D BluetoothMap: onBluetoothStateChange: up=true
08-31 08:52:05.193  6835  6835 D BluetoothInputDevice: Proxy object connected
08-31 08:52:05.193  6835  6835 D HidProfile: Bluetooth service connected
08-31 08:52:05.199  6835  6852 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 08:52:05.199  6835  6835 D BluetoothMap: Proxy object connected
08-31 08:52:05.199  6835  6835 D MapProfile: Bluetooth service connected
,08-31 08:52:05.199  6835  6835 D BluetoothMap: getConnectedDevices()
,08-31 08:52:05.201  6955  6971 V BluetoothMapService: getConnectedDevices()
08-31 08:52:05.201  1834  2697 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:05.203  1834  1834 D BluetoothHeadset: Proxy object connected
08-31 08:52:05.204  1069  1165 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 08:52:05.204  1069  1165 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 08:52:05.205  1069  1069 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 08:52:05.206  1069  1165 D BluetoothManagerService: Message: 40
08-31 08:52:05.206  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 08:52:05.208  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:05.209  1922  2109 D LGBluetoothAPIService: Message: 1
08-31 08:52:05.209  1922  2109 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 08:52:05.210  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 08:52:05.211  6955  6955 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:05.211  6955  6955 D BluetoothMapService: STATE_ON
08-31 08:52:05.217  1922  2109 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-31 08:52:05.218  6648  6648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 08:52:05.221  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:05.223  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:05.223  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:05.224  6955  6955 V BluetoothPbapService: Pbap Service onCreate
08-31 08:52:05.224  6955  6955 V BluetoothPbapService: Starting PBAP service
08-31 08:52:05.225  6835  6835 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 08:52:05.225  6955  6955 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 08:52:05.225  6955  6955 V BluetoothPbapService: Pbap Service onBind
08-31 08:52:05.226  6955  6955 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:05.226  6955  6955 V BluetoothPbapService: state: 12
08-31 08:52:05.227  6955  6955 V BluetoothMapService: Handler(): got msg=1
08-31 08:52:05.227  1069  1165 D BluetoothManagerService: Message: 30
08-31 08:52:05.227  6955  6955 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 08:52:05.229  6955  7639 D BluetoothMapMasInstance: MAS initSocket()
08-31 08:52:05.229  6955  7639 D BluetoothMapMasInstance:   masId = 00
08-31 08:52:05.229  6955  7639 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 08:52:05.229  6955  7639 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 08:52:05.229  6955  7639 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 08:52:05.229  6955  6955 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 08:52:05.229  6955  6955 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 08:52:05.230  6835  6835 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 08:52:05.230  1069  1680 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:05.230  1922  1922 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 08:52:05.231  1922  2109 D LGBluetoothAPIService: Message: 100
08-31 08:52:05.231  1922  2109 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-31 08:52:05.231  6955  6955 V BluetoothPbapService: Handler(): got msg=1
08-31 08:52:05.231  6955  6955 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 08:52:05.232  6955  7639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:05.235  1069  1165 D BluetoothManagerService: Message: 30
08-31 08:52:05.236  6955  7639 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 08:52:05.236  6955  7640 V BluetoothPbapService: Pbap Service initSocket
08-31 08:52:05.236  6955  7639 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 08:52:05.236  6955  7639 D BluetoothMapMasInstance: Accepting socket connection...
08-31 08:52:05.237  6955  7498 D BluetoothAdapterProperties: Scan Mode:21
08-31 08:52:05.237  6955  7498 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 08:52:05.238  1069  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:05.239  6955  7640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:05.240  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:05.242  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:05.243  6955  7640 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 08:52:05.243  6955  7640 V BluetoothPbapService: Succeed to create listening socket 
08-31 08:52:05.243  6955  7640 V BluetoothPbapService: Accepting socket connection...
,08-31 08:52:05.244  6835  6835 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 08:52:05.246  6835  6835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 08:52:05.249  6835  6835 D BluetoothPbap: Proxy object connected
08-31 08:52:05.250  6835  6835 D PbapServerProfile: Bluetooth service connected
08-31 08:52:05.250  6835  6835 D BluetoothA2dp: Proxy object connected
08-31 08:52:05.251  6835  6835 D A2dpProfile: Bluetooth service connected
08-31 08:52:05.252  6955  6955 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 08:52:05.252  6955  6955 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:05.252  6955  6955 V BluetoothPbapReceiver: ***********state = 12
08-31 08:52:05.254  6835  6835 D BluetoothHeadset: Proxy object connected
08-31 08:52:05.255  6835  6835 D HeadsetProfile: Bluetooth service connected
08-31 08:52:05.257  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:05.258  2203  2203 D c       : Getting all permits...
,08-31 08:52:05.258  2203  2203 D a       : Opening database...
08-31 08:52:05.259  7197  7248 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-31 08:52:05.261  6835  6835 D DockEventReceiver: finishStartingService: stopping service
08-31 08:52:05.261  2203  2203 D a       : Opening database auth.proximity.permit_store...
08-31 08:52:05.262  2203  2203 D a       : Closing database...
08-31 08:52:05.271  6835  6835 D BluetoothPermissionRequest: onReceive
,08-31 08:52:05.273  6835  6835 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 08:52:05.275  6835  6835 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 08:52:05.277  6955  6955 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 08:52:05.278  6955  6955 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 08:52:05.283  6955  6955 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-31 08:52:05.301  6955  6955 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 08:52:05.301  6955  6955 V BtOppService: onCreate
,08-31 08:52:05.305  6955  6955 V BluetoothOppNotification: send message
08-31 08:52:05.307  6955  6955 V BtOppService: Starting RfcommListener
08-31 08:52:05.310  6955  6955 D BluetoothOppPreference: Dumping Names:  
08-31 08:52:05.310  6955  6955 D BluetoothOppPreference: {}
08-31 08:52:05.310  6955  6955 D BluetoothOppPreference: Dumping Channels:  
08-31 08:52:05.310  6955  6955 D BluetoothOppPreference: {}
08-31 08:52:05.311  6955  6955 V BtOppService: onStartCommand
08-31 08:52:05.313  6955  7649 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-31 08:52:05.314  6955  7646 V BtOppService: Deleted complete outbound shares, number =  0
08-31 08:52:05.314  6955  7649 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 08:52:05.314  6955  6955 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:05.314  6955  6955 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 08:52:05.318  6955  6955 V BluetoothOppNotification: new notify threadi!
08-31 08:52:05.319  6955  7649 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f86f49a on behalf of 
08-31 08:52:05.319  6955  7646 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 08:52:05.320  6955  6955 V BluetoothOppNotification: send delay message
08-31 08:52:05.320  6955  7646 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 08:52:05.320  6955  6955 V BtOppService: start RfcommListener
08-31 08:52:05.321  6955  7649 V BluetoothOppNotification: update too frequent, put in queue
08-31 08:52:05.322  6955  7646 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@141941cb on behalf of 
08-31 08:52:05.324  6955  7649 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 08:52:05.327  6955  6955 V BtOppService: RfcommListener started
08-31 08:52:05.327  6955  6955 V BtOppService: ContentObserver received notification
08-31 08:52:05.328  6955  7651 V BtOppRfcommListener: Starting RFCOMM listener....
,08-31 08:52:05.329  6955  7652 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 08:52:05.329  6955  7652 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 08:52:05.330  1069  1931 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:05.330  6955  7652 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ecf0da8 on behalf of 
08-31 08:52:05.331  6955  7650 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 08:52:05.331  6955  7651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:05.332  6955  7650 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c4230c1 on behalf of 
08-31 08:52:05.332  6955  7652 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 08:52:05.333  6955  7651 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-31 08:52:05.333  6955  7651 V BtOppRfcommListener: Started RFCOMM listener....
08-31 08:52:05.333  6955  7651 I BtOppRfcommListener: Accept thread started.
08-31 08:52:05.333  6955  7651 V BtOppRfcommListener: Accepting connection...
08-31 08:52:05.334  6955  7650 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 08:52:05.334  6955  7650 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 08:52:05.349  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
,08-31 08:52:05.349  6955  6955 V BluetoothFtpService: Ftp Service onCreate
08-31 08:52:05.349  6955  6955 I BluetoothFtpService: Ftp Service onCreate
08-31 08:52:05.350  6955  6955 V BluetoothFtpService: Ftp Service onStartCommand
08-31 08:52:05.350  6955  6955 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:05.350  6955  6955 V BluetoothFtpService: Starting Listening on sockets
08-31 08:52:05.350  6955  6955 V BtOppService: ContentObserver received notification
08-31 08:52:05.351  6955  6955 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 08:52:05.351  6955  6955 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 08:52:05.351  6955  6955 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 08:52:05.351  6955  6955 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:05.351  6955  6955 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 08:52:05.351  6955  6955 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 08:52:05.352  6955  7653 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 08:52:05.353  6955  7653 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 08:52:05.355  6955  6955 V BluetoothFtpService: Handler(): got msg=1
08-31 08:52:05.355  6955  6955 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 08:52:05.356  6955  6955 V BluetoothFtpService: Ftp Service initSocket
08-31 08:52:05.361  1069  1985 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:05.362  6955  6955 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:52:05.364  6955  6955 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,08-31 08:52:05.364  6955  6955 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 08:52:05.366  6955  7655 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 08:52:05.387  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:05.387  6955  6955 V BluetoothSapService: Sap Service onCreate
,08-31 08:52:05.391  6955  6955 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:05.391  6955  6955 V BluetoothSapService: state: 12
08-31 08:52:05.391  6955  6955 V BluetoothSapService: Starting SAP server process
08-31 08:52:05.394  6955  6955 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 08:52:05.380  7656  7656 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:05.380  7656  7656 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:05.395  6955  7657 V BluetoothSapService: Sap Service initRfcommSocket
08-31 08:52:05.396  1069  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:05.397  6955  7657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:05.398  6955  7657 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 08:52:05.398  6955  7657 V BluetoothSapService: Succeed to create listening socket 
08-31 08:52:05.398  6955  7657 V BluetoothSapService: Accepting socket connection...
08-31 08:52:05.405  7656  7656 V BT_SAP  : Event pipe created
08-31 08:52:05.405  7656  7656 V BT_SAP  : create_server_socket qcom.sap.server
08-31 08:52:05.405  7656  7656 V BT_SAP  : created socket fd 6
,08-31 08:52:05.487  1069  1976 I art     : Explicit concurrent mark sweep GC freed 93751(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.939ms total 150.601ms
08-31 08:52:05.487  6955  7650 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b877cf2 on behalf of 
,08-31 08:52:05.488  6955  7650 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-31 08:52:05.488  6955  7653 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15ee1f43 on behalf of 
,08-31 08:52:05.489  6955  7650 V BluetoothOppNotification: outbound notification was removed.
08-31 08:52:05.489  6955  7650 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 08:52:05.490  6955  7653 V BluetoothOppNotification: update too frequent, put in queue
08-31 08:52:05.491  6955  7653 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 08:52:05.491  6955  7650 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14bbe9c0 on behalf of 
08-31 08:52:05.493  6955  7650 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 08:52:05.495  6955  7650 V BluetoothOppNotification: inbound notification was removed.
08-31 08:52:05.495  6955  7650 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 08:52:05.499  6955  7650 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fbb36f9 on behalf of 
08-31 08:52:05.843  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:05.843  1069  1374 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:52:05.874  1069  1375 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-31 08:52:05.875  1069  1375 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 08:52:05.974  1069  2014 I ActivityManager: Killing 7395:com.lge.bnr/1000 (adj 15): empty #17
,08-31 08:52:06.008  1069  1935 W libprocessgroup: failed to open /acct/uid_1000/pid_7395/cgroup.procs: No such file or directory
,08-31 08:52:06.244  1069  1931 I ActivityManager: Killing 6755:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-31 08:52:06.279  6884  6884 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-31 08:52:06.279  6884  6884 W System.err: android.os.DeadObjectException
08-31 08:52:06.279  6884  6884 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 08:52:06.279  6884  6884 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-31 08:52:06.279  6884  6884 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,08-31 08:52:06.279  6884  6884 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 08:52:06.279  6884  6884 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 08:52:06.280  6884  6884 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 08:52:06.280  6884  6884 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 08:52:06.280  6884  6884 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 08:52:06.280  6884  6884 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:06.280  6884  6884 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:52:06.280  6884  6884 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:06.280  6884  6884 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:06.280  6884  6884 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:52:06.280  6884  6884 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:52:06.280  6884  6884 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 08:52:06.280  6884  6884 W System.err: android.os.DeadObjectException
08-31 08:52:06.281  6884  6884 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 08:52:06.281  6884  6884 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 08:52:06.281  6884  6884 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 08:52:06.281  6884  6884 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 08:52:06.281  6884  6884 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 08:52:06.281  6884  6884 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 08:52:06.281  6884  6884 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-31 08:52:06.281  6884  6884 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 08:52:06.281  6884  6884 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-31 08:52:06.281  6884  6884 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:52:06.281  6884  6884 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:06.281  6884  6884 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-31 08:52:06.281  6884  6884 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:52:06.281  6884  6884 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:52:06.281  6884  6884 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,08-31 08:52:06.282  6884  6884 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-31 08:52:06.319  1069  1976 W libprocessgroup: failed to open /acct/uid_1000/pid_6755/cgroup.procs: No such file or directory
08-31 08:52:06.320  1069  1976 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-31 08:52:06.323  6955  6955 V BluetoothOppNotification: new notify threadi!
,08-31 08:52:06.323  6955  6955 V BluetoothOppNotification: send delay message
08-31 08:52:06.329  6884  6884 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 08:52:06.329  6884  6884 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-31 08:52:06.330  6955  7668 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 08:52:06.344  6955  7668 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b0c763e on behalf of 
08-31 08:52:06.345  6955  7668 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 08:52:06.387  1069  2014 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7669 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 08:52:06.410  6884  6884 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 08:52:06.426  6955  7668 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-31 08:52:06.441  6955  7668 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32496c9f on behalf of 
08-31 08:52:06.442  6955  7668 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-31 08:52:06.455  6955  7668 V BluetoothOppNotification: outbound notification was removed.
08-31 08:52:06.455  6955  7668 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-31 08:52:06.465  6955  7668 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a55e1ec on behalf of 
08-31 08:52:06.466  6955  7668 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 08:52:06.474  7669  7669 D UEI.SmartControl: Quickset Services start...
08-31 08:52:06.476  7669  7669 I UEI.SmartControl: Manufacture = LGE
08-31 08:52:06.476  7669  7669 D UEI.SmartControl: Id = LGNevo
,08-31 08:52:06.480  6955  7668 V BluetoothOppNotification: inbound notification was removed.
08-31 08:52:06.480  6955  7668 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 08:52:06.481  7669  7669 D UEI.SmartControl: File observer start...
08-31 08:52:06.482  7669  7669 E UEI.SmartControl: IR Port is disabled: false
08-31 08:52:06.482  7669  7669 D UEI.SmartControl: Starting file observer...
08-31 08:52:06.482  7669  7669 D UEI.SmartControl: Extracting JNI libs...
08-31 08:52:06.482  7669  7669 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 08:52:06.500  6955  7668 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19ef49b5 on behalf of 
,08-31 08:52:06.589  7669  7669 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-31 08:52:06.589  7669  7669 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-31 08:52:06.589  7669  7669 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 08:52:06.628  7669  7669 I UEI.SmartControl: --- Selecting new region: 6
,08-31 08:52:06.630  7669  7669 I UEI.SmartControl: Model = LG-D855
,08-31 08:52:06.632  7669  7669 D UEI.SmartControl: QS Service created
08-31 08:52:06.648  7669  7669 I UEI.SmartControl: Service initServices...
,08-31 08:52:06.653  7669  7669 D UEI.SmartControl: QS start get config
08-31 08:52:06.698  7669  7669 D UEI.SmartControl: Loading JNI Libs...
,08-31 08:52:06.849  1069  1931 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 08:52:06.849  1069  1931 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@357a5993 mBinding = false
,08-31 08:52:06.889  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 08:52:06.889  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 08:52:06.889  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-31 08:52:06.890  1069  1165 D BluetoothManagerService: Message: 2
08-31 08:52:06.891  1069  1165 D BluetoothManagerService: Sending off request.
08-31 08:52:06.891  6955  6971 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-31 08:52:06.892  6955  7494 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 08:52:06.892  6955  7494 D BluetoothAdapterProperties: Setting state to 13
08-31 08:52:06.892  6955  7494 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 08:52:06.893  6955  7494 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 08:52:06.893  6955  7494 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 08:52:06.894  6955  7498 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:52:06.896  6955  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 08:52:06.897  6955  7640 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 08:52:06.903  6955  7651 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:52:06.903  6955  7657 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:52:06.904  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 08:52:06.904  6955  7564 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 08:52:06.905  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 08:52:06.906  6955  7564 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 08:52:06.906  6955  7655 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:52:06.906  6955  7494 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 08:52:06.907  6955  7639 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 08:52:06.907  6955  7639 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:52:06.907  6955  7639 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 08:52:06.907  6955  7639 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 08:52:06.907  6955  7639 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 08:52:06.907  6955  7639 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 08:52:06.907  6955  7639 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 08:52:06.907  6955  7639 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 08:52:06.914  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:06.914  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:06.914  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:06.914  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:06.914  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:06.914  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:06.914  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:06.914  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:06.914  6648  6648 V io.jxcore.node.Connectivity,Monitor:     - active network type is Wi-Fi: false
08-31 08:52:06.918  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:06.918  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:06.920  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:06.920  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:06.920  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:06.920  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:06.920  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:06.920  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:06.920  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:06.920  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:06.920  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:06.921  6648  6648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:06.921  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:06.921  1069  1165 D BluetoothManagerService: Message: 60
08-31 08:52:06.921  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 08:52:06.921  1069  1165 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 08:52:06.924  6835  6835 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-31 08:52:06.925  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:06.925  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 08:52:06.926  6955  6955 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:06.926  6955  6955 D BluetoothMapService: STATE_TURNING_OFF
08-31 08:52:06.926  6955  6955 V BluetoothMapService: Handler(): got msg=4
08-31 08:52:06.926  6955  6955 D BluetoothMapService: MAP Service closeService in
08-31 08:52:06.926  6955  6955 D BluetoothMapMasInstance: MAP Service shutdown
08-31 08:52:06.926  6955  6955 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 08:52:06.926  6955  6955 V BluetoothMapService: MAP Service closeService out
08-31 08:52:06.927  6955  6955 V BtOppService: Receiver DISABLED_ACTION 
08-31 08:52:06.927  6955  6955 I BtOppRfcommListener: stopping Accept Thread
08-31 08:52:06.927  6955  6955 V BtOppRfcommListener: close mBtServerSocket
08-31 08:52:06.927  6955  6955 V BtOppRfcommListener: waiting for thread to terminate
08-31 08:52:06.928  6955  7651 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 08:52:06.928  6955  6955 V BtOppRfcommListener: done waiting for thread to terminate
08-31 08:52:06.930  6955  6955 V BtOppService: onDestroy
08-31 08:52:06.930  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:06.932  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:06.933  6955  6955 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 08:52:06.934  6835  6835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 08:52:06.939  6955  6955 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 08:52:06.939  6955  6955 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:06.939  6955  6955 V BluetoothPbapReceiver: ***********state = 13
,08-31 08:52:06.942  6955  6955 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 08:52:06.943  6955  6955 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:06.943  6955  6955 V BluetoothPbapService: state: 13
08-31 08:52:06.943  6955  6955 V BluetoothPbapService: Pbap Service closeService in
08-31 08:52:06.946  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 08:52:06.947  6955  6955 V BluetoothPbapService: successfully stopped pbap service
08-31 08:52:06.947  6955  6955 V BluetoothPbapService: Pbap Service closeService out
08-31 08:52:06.947  6955  6955 V BluetoothPbapService: Pbap Service onDestroy
08-31 08:52:06.947  6955  6955 V BluetoothPbapService: Pbap Service closeService in
08-31 08:52:06.947  6955  6955 V BluetoothPbapService: Pbap Service closeService out
08-31 08:52:06.948  6955  6955 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 08:52:06.947  6835  6835 D DockEventReceiver: finishStartingService: stopping service
08-31 08:52:06.950  6835  6835 D BluetoothPbap: Proxy object disconnected
08-31 08:52:06.950  6835  6835 D PbapServerProfile: Bluetooth service disconnected
08-31 08:52:06.968  6835  6835 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 08:52:06.973  6835  6835 D BluetoothPermissionRequest: onReceive
08-31 08:52:06.973  6835  6835 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 08:52:06.976  6835  6835 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 08:52:06.979  6955  6955 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 08:52:06.979  6955  6955 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 08:52:06.980  6955  6955 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 08:52:06.983  6955  6955 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:06.983  6955  6955 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 08:52:06.984  6955  6955 V BluetoothFtpService: Ftp Service onStartCommand
08-31 08:52:06.984  6955  6955 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:06.984  6955  6955 V BluetoothFtpService: Ftp Service closeService
08-31 08:52:06.984  6955  6955 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 08:52:06.986  6955  6955 V BluetoothFtpService: successfully stopped ftp service
08-31 08:52:06.986  6955  6955 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 08:52:06.986  6955  6955 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 08:52:06.986  6955  6955 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 08:52:06.986  6955  6955 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:06.986  6955  6955 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 08:52:06.986  6955  6955 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 08:52:06.987  6955  6955 V BluetoothFtpService: Ftp Service onDestroy
08-31 08:52:06.987  6955  6955 V BluetoothFtpService: Ftp Service closeService
08-31 08:52:06.990  6955  6955 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:06.990  6955  6955 V BluetoothSapService: state: 13
08-31 08:52:06.990  6955  6955 V BluetoothSapService: Stopping SAP server process
08-31 08:52:06.991  6955  6955 V BluetoothSapService: Sap Service closeSapService in
08-31 08:52:06.991  6955  6955 V BluetoothSapService: Close listen Socket : 
08-31 08:52:06.991  6955  6955 V BluetoothSapService: Close rfcomm Socket : 
08-31 08:52:06.991  6955  6955 V BluetoothSapService: Close sapd  Socket : 
,08-31 08:52:06.995  6955  6955 V BluetoothSapService: Sap Service closeSapService out
08-31 08:52:06.996  6955  6955 V BluetoothSapService: Sap Service onDestroy
08-31 08:52:06.996  6955  6955 V BluetoothSapService: Sap Service closeSapService in
08-31 08:52:06.996  6955  6955 V BluetoothSapService: Close listen Socket : 
08-31 08:52:06.996  6955  6955 V BluetoothSapService: Close rfcomm Socket : 
08-31 08:52:06.996  6955  6955 V BluetoothSapService: Close sapd  Socket : 
08-31 08:52:06.996  6955  6955 V BluetoothSapService: Sap Service closeSapService out
08-31 08:52:07.028  1586  1586 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-31 08:52:07.028  1586  1586 I [SystemUI]LGPowerUI: On Skip Timer : true
08-31 08:52:07.037  1069  1385 D WifiController: battery changed pluggedType: 2
08-31 08:52:07.040  1922  2079 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-31 08:52:07.040  1586  1586 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
08-31 08:52:07.040  1922  2079 D LEDHandler: Battery Level Remaining: 100%
08-31 08:52:07.040  1586  1586 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-31 08:52:07.040  1922  2079 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
,08-31 08:52:07.042  7669  7669 I UEI.SmartControl: Supports setup maps: true
08-31 08:52:07.043  1586  1586 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-31 08:52:07.045  7669  7669 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 08:52:07.045  7669  7669 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 08:52:07.045  7669  7669 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 08:52:07.045  7669  7669 I UEI.SmartControl: ### init IR Blaster...
08-31 08:52:07.050  6955  7518 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 08:52:07.050  7669  7669 D serial_port: Configuring serial port
08-31 08:52:07.053  7669  7669 E UEI.SmartControl: UEIBLaster setting for 616
08-31 08:52:07.053  7669  7669 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 08:52:07.053  7669  7669 I UEI.SmartControl: configuring settings for MAXQ616
08-31 08:52:07.054  7669  7669 I UEI.SmartControl: Get version...
,08-31 08:52:07.070  7669  7714 D UEI.SmartControl: serial port data available: 21
,08-31 08:52:07.096  7669  7669 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 08:52:07.096  7669  7669 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-31 08:52:07.096  7669  7669 I UEI.SmartControl: QS saving settings...
,08-31 08:52:07.097  7669  7669 D UEI.SmartControl: IR Blaster version: 25672567
08-31 08:52:07.113  7669  7714 D UEI.SmartControl: serial port data available: 4
,08-31 08:52:07.152  7669  7718 I UEI.SmartControl: Device manager: loading config....
,08-31 08:52:07.155  7669  7718 D UEI.SmartControl: ----------- loading internal config...
08-31 08:52:07.158  7669  7669 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 08:52:07.161  7669  7669 E UEI.SmartControl: Services init done
08-31 08:52:07.161  7669  7669 D UEI.SmartControl: QS Service init finished
08-31 08:52:07.162  7669  7669 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 08:52:07.162  7669  7669 D UEI.SmartControl: QS Service version code: 201091
,08-31 08:52:07.162  7669  7669 D UEI.SmartControl: Service requested: Control
08-31 08:52:07.168  7669  7718 E UEI.SmartControl: Loading SETTINGS...
08-31 08:52:07.171  7669  7669 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 08:52:07.173  6884  6884 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-31 08:52:07.174  7669  7685 I UEI.SmartControl: ------ IControl API: 11
08-31 08:52:07.174  1069  1985 I ActivityManager: Killing 6884:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 08:52:07.175  7669  7685 I UEI.SmartControl: Registering callback...
08-31 08:52:07.181  7669  7718 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 08:52:07.207  7669  7717 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 08:52:07.207  7669  7717 D UEI.SmartControl: -----service ready thread exits
,08-31 08:52:07.230  1069  1904 W libprocessgroup: failed to open /acct/uid_10112/pid_6884/cgroup.procs: No such file or directory
,08-31 08:52:07.230  7669  7669 D UEI.SmartControl: Internal service binding...
,08-31 08:52:07.828  6955  7498 D bt_hci_bdroid: cleanup
,08-31 08:52:07.834  6955  7566 I bt_lpm  : LPM is already off!!!
08-31 08:52:07.835  6955  7610 I bt_userial_mct: exiting userial_read_thread
08-31 08:52:07.835  6955  7610 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 08:52:07.838  6955  7564 W bt-btif : ag scb idx 1 not allocated
08-31 08:52:07.838  6955  7564 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:52:07.838  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 08:52:07.839  6955  7564 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:52:07.839  6955  7564 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 08:52:07.839  6955  7564 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 08:52:07.839  6955  7564 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 08:52:07.839  6955  7498 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 08:52:07.840  6955  7566 I bt_vendor: hw_epilog_process
08-31 08:52:07.840  6955  7498 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 08:52:07.840  6955  7498 D bt_userial_mct: userial_close
08-31 08:52:07.840  6955  7498 E bt_userial_mct: pthread_join() FAILED result:3
08-31 08:52:07.840  6955  7498 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 08:52:07.847  6955  7498 D bt_hci_bdroid: set_power 0
08-31 08:52:07.847  6955  7498 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 08:52:07.847  6955  7498 I bt_vendor: bluetooth satus is on
08-31 08:52:07.847  6955  7498 I bt_vendor: bt-vendor : resetting BT status
08-31 08:52:07.847  6955  7498 I bt_vendor: Starting hciattach daemon
08-31 08:52:07.847  6955  7498 I bt_vendor: try to set false
,08-31 08:52:07.854  6955  7498 I bt_vendor: Starting hciattach daemon
08-31 08:52:07.854  6955  7498 I bt_vendor: try to set false
08-31 08:52:07.855  6955  7498 I bt_vendor: cleanup
08-31 08:52:07.856  6955  7564 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 08:52:07.856  6955  7498 I GKI_LINUX: GKI_exit_task 0 done
08-31 08:52:07.856  6955  7498 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 08:52:07.858  6955  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 08:52:07.863  6955  6955 D HeadsetService: Received stop request...Stopping profile...
,08-31 08:52:07.868  6955  6955 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 08:52:07.868  6955  6955 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 08:52:07.868  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:07.869  6955  7518 D HeadsetStateMachine: Exit Disconnected: -1
08-31 08:52:07.871  1834  1834 D BluetoothHeadset: Proxy object disconnected
08-31 08:52:07.871  1834  1834 D BluetoothHeadset: Proxy object disconnected
08-31 08:52:07.871  1834  1834 D BluetoothHeadset: Proxy object disconnected
08-31 08:52:07.873  1069  1069 D BluetoothHeadset: Proxy object disconnected
08-31 08:52:07.873  1069  1069 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 08:52:07.874  6955  6955 D A2dpService: Received stop request...Stopping profile...
08-31 08:52:07.875  6955  7550 D A2dpStateMachine: Exit Disconnected: -1
,08-31 08:52:07.880  6955  7494 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 08:52:07.882  6955  6955 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 08:52:07.884  6955  6955 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 08:52:07.884  6955  6955 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 08:52:07.884  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:07.886  1069  1069 D BluetoothA2dp: Proxy object disconnected
08-31 08:52:07.887  1069  1069 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 08:52:07.889  6955  6955 D HidService: Received stop request...Stopping profile...
08-31 08:52:07.889  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:07.891  6955  6955 D HealthService: Received stop request...Stopping profile...
08-31 08:52:07.892  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:07.893  6955  6955 D HeadsetStateMachine: Unbinding service...
08-31 08:52:07.895  6955  6955 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 08:52:07.895  6955  6955 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 08:52:07.896  6955  6955 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 08:52:07.896  6955  6955 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 08:52:07.896  6955  6955 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 08:52:07.896  6955  6955 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 08:52:07.896  6955  6955 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 08:52:07.897  6955  6955 D PanService: Received stop request...Stopping profile...
08-31 08:52:07.898  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
,08-31 08:52:07.901  6955  6955 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 08:52:07.902  6955  6955 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 08:52:07.902  6955  6955 D BtGatt.GattService: stop()
08-31 08:52:07.902  6955  6955 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 08:52:07.903  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:07.905  6955  6955 D BluetoothMapService: Received stop request...Stopping profile...
08-31 08:52:07.905  6955  6955 D BluetoothMapService: stop()
08-31 08:52:07.906  6955  6955 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 08:52:07.906  6955  6955 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 08:52:07.907  6955  6955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a9d2939
08-31 08:52:07.908  6955  6955 V BluetoothMapService: Handler(): got msg=4
08-31 08:52:07.908  6955  6955 D BluetoothMapService: MAP Service closeService in
08-31 08:52:07.908  6955  6955 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 08:52:07.908  6955  6955 V BluetoothMapService: MAP Service closeService out
08-31 08:52:07.909  6955  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 08:52:07.909  6955  7494 D BluetoothAdapterProperties: Setting state to 10
08-31 08:52:07.909  6955  7494 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-31 08:52:07.912  1069  1165 D BluetoothManagerService: Message: 60
08-31 08:52:07.912  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 08:52:07.913  1069  1165 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-31 08:52:07.913  6955  7494 I BluetoothAdapterState: Entering OffState
08-31 08:52:07.913  1834  1849 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:52:07.914  6835  6851 D BluetoothPan: onBluetoothStateChange on: false
08-31 08:52:07.915  1069  1165 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:52:07.915  1834  2697 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:52:07.916  1069  1165 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:52:07.917  6835  6851 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 08:52:07.918  6955  6955 I BluetoothA2dpServiceJni: cleanupNative
08-31 08:52:07.918  6955  7551 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 08:52:07.919  6955  6955 I GKI_LINUX: GKI_exit_task 2 done
08-31 08:52:07.919  6955  6955 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 08:52:07.920  6835  6851 D BluetoothMap: onBluetoothStateChange: up=false
08-31 08:52:07.921  6835  6851 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:52:07.924  6955  6955 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 08:52:07.924  6955  6955 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 08:52:07.927  6955  6955 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 08:52:07.927  6955  6955 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 08:52:07.927  6955  6955 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 08:52:07.929  6835  6851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:52:07.931  6955  6955 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 08:52:07.931  6955  6955 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 08:52:07.932  6835  6851 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 08:52:07.933  1834  2378 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 08:52:07.936  6955  6955 D BluetoothMapService: cleanup()
08-31 08:52:07.936  6955  6955 D BluetoothMapService: MAP Service closeService in
08-31 08:52:07.936  6955  6955 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 08:52:07.936  6955  6955 V BluetoothMapService: MAP Service closeService out
08-31 08:52:07.937  1069  1165 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 08:52:07.937  1069  1165 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 08:52:07.939  1069  1165 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 08:52:07.939  1069  1165 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 08:52:07.939  1069  1165 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@357a5993 mBinding = false
08-31 08:52:07.941  1069  1165 D BluetoothManagerService: Sending unbind request.
08-31 08:52:07.945  6955  7498 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 08:52:07.947  6955  6955 I GKI_LINUX: GKI_exit_task 1 done
08-31 08:52:07.947  6955  6955 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 08:52:07.948  6955  6955 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 08:52:07.948  6955  6955 I art     : --- WEIRD: removing null entry 248
08-31 08:52:07.948  6955  6955 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-31 08:52:07.948  6955  6955 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 08:52:07.949  6955  6955 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 08:52:07.950  1069  1165 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 08:52:07.953  6955  6955 I art     : System.exit called, status: 0
08-31 08:52:07.953  6955  6955 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 08:52:07.973   321  1388 V AudioFlinger: 6955 died, releasing its sessions
08-31 08:52:07.973   321  1388 V AudioFlinger:  pid 1834 @ 0
08-31 08:52:07.973   321  1388 V AudioFlinger:  pid 3429 @ 1
08-31 08:52:07.973   321  1388 V AudioFlinger:  pid 3429 @ 2
,08-31 08:52:07.982  6835  6835 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 08:52:07.983  1922  1922 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-31 08:52:07.983  1922  2109 D LGBluetoothAPIService: Message: 101
08-31 08:52:07.983  1922  2109 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
,08-31 08:52:07.984  1922  2109 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
,08-31 08:52:07.984  1922  2109 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-31 08:52:08.037  1069  1680 I ActivityManager: Process com.android.bluetooth (pid 6955) has died
08-31 08:52:08.037  1069  1680 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-31 08:52:08.038  1069  1680 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-31 08:52:08.047  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:08.047  1922  2109 D LGBluetoothAPIService: Message: 2
08-31 08:52:08.047  1922  2109 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-31 08:52:08.049  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 08:52:08.052  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:08.052  6835  6835 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 08:52:08.052  6835  6835 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-31 08:52:08.054  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:08.061  6835  6835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 08:52:08.063  1586  1586 D BluetoothAdapter: 627574936: getState() :  mService = null. Returning STATE_OFF
08-31 08:52:08.063  1586  1586 D BluetoothAdapter: 627574936: getState() :  mService = null. Returning STATE_OFF
08-31 08:52:08.107  1069  1954 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7748 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 08:52:08.110  6835  6835 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:52:08.178  7748  7748 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 08:52:08.179  7748  7748 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 08:52:08.180  7748  7748 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-31 08:52:08.180  7748  7748 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 08:52:08.202  7748  7748 D BluetoothAdapterApp: Loading JNI Library
,08-31 08:52:08.237  7748  7748 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@f91b01 Instance Count = 1
,08-31 08:52:08.243  7748  7748 D BluetoothAdapterApp: onCreate
08-31 08:52:08.269  7748  7748 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 08:52:08.270  7748  7748 D ProfileConfigQcom: Adding HeadsetService
08-31 08:52:08.270  7748  7748 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 08:52:08.270  7748  7748 D ProfileConfigQcom: Adding A2dpService
,08-31 08:52:08.270  7748  7748 D ProfileConfigQcom: [BTUI] HidService is supported
,08-31 08:52:08.270  7748  7748 D ProfileConfigQcom: Adding HidService
,08-31 08:52:08.271  7748  7748 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 08:52:08.271  7748  7748 D ProfileConfigQcom: Adding HealthService
08-31 08:52:08.271  7748  7748 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-31 08:52:08.273  7748  7748 D ProfileConfigQcom: [BTUI] PanService is supported
,08-31 08:52:08.273  7748  7748 D ProfileConfigQcom: Adding PanService
08-31 08:52:08.273  7748  7748 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 08:52:08.273  7748  7748 D ProfileConfigQcom: Adding GattService
,08-31 08:52:08.273  7748  7748 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 08:52:08.274  7748  7748 D ProfileConfigQcom: Adding BluetoothMapService
08-31 08:52:08.274  7748  7748 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 08:52:08.275  7748  7748 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-31 08:52:08.277  7748  7748 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:08.277  7748  7748 V BluetoothPbapReceiver: ***********state = 10
08-31 08:52:08.279  7748  7748 V LGMDMManagerInternal: Create singleton instance
,08-31 08:52:08.400  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:08.418  7748  7748 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 08:52:08.418  7748  7748 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 08:52:08.421  1922  1922 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-31 08:52:08.423  1922  2109 D LGBluetoothAPIService: Message: 100
08-31 08:52:08.423  1922  2109 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 08:52:08.425  6835  6835 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 08:52:08.429  6835  6835 D BluetoothPermissionRequest: onReceive
08-31 08:52:08.431  6835  6835 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 08:52:08.431  6835  6835 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 08:52:08.434  6835  6835 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 08:52:08.439  7748  7748 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 08:52:08.445  7748  7748 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:08.448  7748  7748 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 08:52:08.449  7748  7748 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 08:52:08.449  7748  7748 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 08:52:08.450  7748  7748 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:08.451  7748  7748 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-31 08:52:08.458  7569  7569 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 08:52:09.921  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:52:09.922  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:09.958  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 08:52:09.982  1069  1365 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 08:52:10.049  1069  1135 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7778 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 08:52:10.062  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 08:52:10.065  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-31 08:52:10.093  2015  2015 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 08:52:10.109  1069  1069 D administrator: Handling package changes for user 0
,08-31 08:52:10.119  2015  2015 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 08:52:10.144  7778  7778 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 08:52:10.206  7778  7778 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:52:10.207  7778  7778 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 08:52:10.213  1069  1069 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-31 08:52:10.213  1069  1069 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-31 08:52:10.247  1069  1131 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:52:10.252  1069  1131 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-31 08:52:10.258  2015  2015 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 08:52:10.259  2479  2479 V GmsNetworkLocationProvi: DISABLE
,08-31 08:52:10.282  1069  1131 D LocationProviderProxy: applying state to connected service
,08-31 08:52:10.284  2479  2479 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-31 08:52:10.318  7778  7822 I Babel   : MmsConfig: mnc/mcc: 0/0
08-31 08:52:10.319  7778  7822 I Babel   : MmsConfig.loadMmsSettings
08-31 08:52:10.322  7778  7822 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 08:52:10.322  7778  7822 I Babel   : MmsConfig.loadFromDatabase
,08-31 08:52:10.340  7778  7822 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-31 08:52:10.340  7778  7822 I Babel   : MmsConfig.loadFromResources
08-31 08:52:10.342  7778  7822 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-31 08:52:10.342  7778  7822 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 08:52:10.345  7778  7820 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 08:52:10.345  7778  7778 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:10.347  7778  7820 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 08:52:10.350  7778  7820 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:52:10.362  7778  7820 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-31 08:52:10.363  7778  7820 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 08:52:10.364  7778  7820 W AudioCapabilities: Unsupported mime audio/evrc
08-31 08:52:10.372  7018  7018 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 08:52:10.372  1799  7824 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-31 08:52:10.372  1799  7824 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-31 08:52:10.375  7018  7018 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2473b783
08-31 08:52:10.375  7018  7018 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 08:52:10.375  7018  7018 D AppUp4:CustFacade: isPhone : true
08-31 08:52:10.376  7018  7018 D AppUp4:CustModeStarterReceiver: begin check event
08-31 08:52:10.376  7018  7018 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-31 08:52:10.385  7778  7820 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 08:52:10.388  7778  7820 W VideoCapabilities: Unsupported mime video/divx
08-31 08:52:10.390  1799  4763 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-31 08:52:10.391  7778  7820 W VideoCapabilities: Unsupported mime video/divx311
08-31 08:52:10.399  7778  7820 W VideoCapabilities: Unsupported mime video/divx4
08-31 08:52:10.399  1069  1680 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7828 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-31 08:52:10.404  1069  1886 I ActivityManager: Killing 6856:com.lge.sync/1000 (adj 15): empty #17
08-31 08:52:10.420  1069  1385 D WifiService: Client connection lost with reason: 4
,08-31 08:52:10.422  7778  7820 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-31 08:52:10.433  7778  7820 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 08:52:10.466  7778  7820 W AudioCapabilities: Unsupported mime audio/eac3
,08-31 08:52:10.467  7778  7820 W AudioCapabilities: Unsupported mime audio/ac3
,08-31 08:52:10.468  7778  7820 W AudioCapabilities: Unsupported mime audio/g726
08-31 08:52:10.469  7778  7820 W AudioCapabilities: Unsupported mime audio/wma-voice
08-31 08:52:10.470  7778  7820 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 08:52:10.470  7778  7820 W AudioCapabilities: Unsupported mime audio/adpcm
08-31 08:52:10.472  7778  7820 W VideoCapabilities: Unsupported mime video/theora
08-31 08:52:10.473  7778  7820 W VideoCapabilities: Unsupported mime video/mjpg
,08-31 08:52:10.482  1069  1559 W libprocessgroup: failed to open /acct/uid_1000/pid_6856/cgroup.procs: No such file or directory
08-31 08:52:10.503  7828  7828 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:52:10.504  7828  7828 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 08:52:10.504  7828  7828 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-31 08:52:10.505  7828  7828 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-31 08:52:10.506  7828  7828 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 08:52:10.577  7828  7828 I SystemConfig: BUILD Country: EU
08-31 08:52:10.577  7828  7828 I SystemConfig: BUILD Operator: OPEN
,08-31 08:52:10.625  1069  2014 I ActivityManager: Killing 7048:com.lge.email/u0a23 (adj 15): empty #17
,08-31 08:52:10.748  1069  1931 W libprocessgroup: failed to open /acct/uid_10023/pid_7048/cgroup.procs: No such file or directory
,08-31 08:52:10.808  1069  2014 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7852 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-31 08:52:10.813  7828  7847 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-31 08:52:10.813  7828  7847 I SystemConfig: existFile = false
08-31 08:52:10.813  7828  7847 I SystemConfig: canReadFile = false
08-31 08:52:10.813  7828  7847 I SystemConfig: systemFeature RCS result false
,08-31 08:52:10.814  7828  7847 D SystemConfig: refreshRcsSupport() :false
08-31 08:52:10.833   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 20.402ms
,08-31 08:52:10.851   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 17.466ms
,08-31 08:52:10.868   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 371us total 16.848ms
,08-31 08:52:10.892  7852  7852 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 08:52:10.892  7852  7852 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 08:52:10.893  7852  7852 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 08:52:10.893  7852  7852 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 08:52:11.004  7852  7852 I AppConfig: Total System Memory = 2995761152
,08-31 08:52:11.015  7852  7852 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-31 08:52:11.136  1069  1085 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7874 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 08:52:11.138  1069  1085 I ActivityManager: Killing 6925:com.lge.formmanager/u0a26 (adj 15): empty #17
08-31 08:52:11.187  1069  2009 W libprocessgroup: failed to open /acct/uid_10026/pid_6925/cgroup.procs: No such file or directory
,08-31 08:52:11.397  7874  7874 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-31 08:52:11.485  7874  7874 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 08:52:11.485  7874  7874 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 08:52:11.532  7874  7874 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-31 08:52:11.551  7874  7874 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 08:52:11.553  7874  7874 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 08:52:11.568  7874  7874 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 08:52:11.568  7874  7874 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-31 08:52:11.587  1069  2014 I ActivityManager: Killing 6458:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-31 08:52:11.651  1069  1680 W libprocessgroup: failed to open /acct/uid_1000/pid_6458/cgroup.procs: No such file or directory
,08-31 08:52:11.653  2823  2839 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-31 08:52:11.655  2823  2839 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@38d92224 on behalf of 7874
,08-31 08:52:11.666  4610  7916 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-31 08:52:11.744  1069  1597 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7918 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-31 08:52:11.769  7874  7874 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-31 08:52:11.786  7874  7874 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-31 08:52:11.841  7918  7918 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-31 08:52:11.868  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-31 08:52:11.868  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-31 08:52:11.868  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-31 08:52:11.868  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-31 08:52:11.868  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-31 08:52:11.868  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-31 08:52:11.893  1069  1935 I ActivityManager: Killing 7094:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-31 08:52:11.925  1069  2014 W libprocessgroup: failed to open /acct/uid_10046/pid_7094/cgroup.procs: No such file or directory
,08-31 08:52:12.080  1069  1935 V SIM_STK : Menu title from STK is T-Mobile
,08-31 08:52:12.124  4610  7916 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 457 ms] updated apps [took 457 ms] 
,08-31 08:52:12.150  7669  7719 D UEI.SmartControl: Internal timer expired: 1
08-31 08:52:12.151  7669  7719 D UEI.SmartControl: unbind internal service
,08-31 08:52:12.157  7669  7669 D UEI.SmartControl: Service.onUnbind: IControl
,08-31 08:52:12.158  7669  7669 D UEI.SmartControl: Service.onDestroy
,08-31 08:52:12.158  7669  7669 D UEI.SmartControl: Lock is in USE false
,08-31 08:52:12.158  7669  7669 D UEI.SmartControl: unbind internal service
08-31 08:52:12.159  7669  7669 D serial_port: close(fd = 25)
08-31 08:52:12.163  7669  7669 I UEI.SmartControl: Serial port is closed.
08-31 08:52:12.163  7669  7669 I UEI.SmartControl: Serial port is closed.
08-31 08:52:12.165  7669  7669 D UEI.SmartControl: Blaster closed
08-31 08:52:12.165  7669  7669 D UEI.SmartControl: Shut down QS...
08-31 08:52:12.166  7669  7669 D UEI.SmartControl: Stopping QS lib
08-31 08:52:12.166  7669  7669 D UEI.SmartControl: QS lib stop result = true
08-31 08:52:12.166  7669  7669 D UEI.SmartControl: Stopped QS lib
08-31 08:52:12.167  7669  7669 D UEI.SmartControl: Stopped file observer...
08-31 08:52:12.167  7669  7669 D UEI.SmartControl: QS shutdown complete
,08-31 08:52:12.939  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-31 08:52:12.940  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@379a8b1d added. We now have 6 listener(s)
08-31 08:52:12.940  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:12.950  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:12.950  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@389e4192 added. We now have 7 listener(s)
08-31 08:52:12.950  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:12.951  6648  6772 I System.out: IsBluetoothEnabled
08-31 08:52:12.952  1069  1985 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:12.952  1069  1985 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-31 08:52:12.953  1069  1165 D BluetoothManagerService: Message: 2
08-31 08:52:12.956  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:12.959  1069  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:12.959  1069  1885 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 08:52:12.975  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 08:52:12.976  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 08:52:12.976  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-31 08:52:12.977  1069  1165 D BluetoothManagerService: Message: 1
08-31 08:52:12.977  1069  1165 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 08:52:13.002  1069  1165 D BluetoothManagerService: Message: 20
08-31 08:52:13.003  1069  1165 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21893d49:true
,08-31 08:52:13.007  7748  7748 D BluetoothAdapterState: make
08-31 08:52:13.011  7748  7748 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 08:52:13.012  7748  7748 I bluedroid-qcom: init
08-31 08:52:13.013  7748  7948 I BluetoothAdapterState: Entering OffState
08-31 08:52:13.013  7748  7748 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 08:52:13.013  7748  7748 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 08:52:13.013  7748  7748 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 08:52:13.013  7748  7748 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 08:52:13.013  7748  7748 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 08:52:13.015  7748  7748 I bluedroid-qcom: get_profile_interface socket
08-31 08:52:13.015  7748  7748 I bluedroid-qcom: get_profile_interface map_client
,08-31 08:52:13.010  7951  7951 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:13.021  7748  7952 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 08:52:13.024  7748  7952 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 08:52:13.010  7951  7951 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:13.033  7951  7951 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 08:52:13.033  7951  7951 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 08:52:13.033  7951  7951 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-31 08:52:13.039  1069  1069 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 08:52:13.040  1069  1069 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 08:52:13.044  1069  1069 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 08:52:13.044  1069  1165 D BluetoothManagerService: Message: 40
08-31 08:52:13.044  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 08:52:13.047  7951  7951 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-31 08:52:13.051  7748  7764 I bluedroid-qcom: config_hci_snoop_log
08-31 08:52:13.054  1069  1165 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 08:52:13.054  1069  1165 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 08:52:13.056  7748  7952 D BluetoothAdapterProperties: Name is: G3
08-31 08:52:13.059  7748  7948 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 08:52:13.060  7748  7948 D BluetoothAdapterProperties: Setting state to 11
08-31 08:52:13.060  7748  7948 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-31 08:52:13.065  7748  7948 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 08:52:13.066  1069  1165 D BluetoothManagerService: Message: 60
08-31 08:52:13.067  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 08:52:13.067  1069  1165 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 08:52:13.069  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:13.072  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-31 08:52:13.076  7951  7951 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 08:52:13.076  7951  7951 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 08:52:13.082  6835  6835 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 08:52:13.085  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:13.091  7748  7748 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-31 08:52:13.091  7748  7748 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:13.092  7748  7748 V BluetoothPbapReceiver: ***********state = 11
08-31 08:52:13.101  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:13.112  7748  7948 D BluetoothBondStateMachine: make
,08-31 08:52:13.114  7748  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.114  7748  7948 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 08:52:13.114  7748  7948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.114  7748  7948 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 08:52:13.115  7748  7948 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 08:52:13.116  7748  7967 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 08:52:13.120  7748  7948 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:13.124  6835  6835 D BluetoothPermissionRequest: onReceive
08-31 08:52:13.127  7748  7948 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:13.127  7748  7748 D HeadsetService: Received start request. Starting profile...
08-31 08:52:13.128  7748  7748 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 08:52:13.128  7748  7748 D LGBluetoothHfpAdapter: Version 1.6
08-31 08:52:13.130  7748  7948 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:13.131  6835  6835 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 08:52:13.131  7748  7748 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 08:52:13.132  7748  7748 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 08:52:13.132  7748  7748 D HeadsetStateMachine: make
,08-31 08:52:13.141  7748  7948 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:13.147  7748  7948 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 08:52:13.153  7748  7948 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:13.154  7748  7748 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:52:13.154  7748  7748 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 08:52:13.158  7748  7748 D HeadsetStateMachine: max_hf_connections = 1
08-31 08:52:13.158  7748  7748 I bluedroid-qcom: get_profile_interface handsfree
08-31 08:52:13.159  7748  7948 E BluetoothAdapterService: File transfer profiles supported!!
08-31 08:52:13.159  7748  7748 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 08:52:13.159   321   321 V AudioPolicyService: registerClient() client 0xb558ad40, uid 1002
08-31 08:52:13.159   321  3959 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 08:52:13.160   321  3959 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 08:52:13.160   321  3959 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 08:52:13.160  7748  7748 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-31 08:52:13.160   321  1387 V AudioFlinger: registerClient() client 0xb1433628, pid 7748
08-31 08:52:13.160   321  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:13.160   321  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:13.161  1069  2009 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:13.161  1069  2009 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:13.161  1586  2073 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:13.161  1586  2073 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:13.161  1834  1850 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:13.161  1834  1850 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:13.161   321  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:13.161   321  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:13.161  1834  1849 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:13.161  1834  1849 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:13.161  1069  1559 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:13.161  1069  1559 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:13.161  1586  4210 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:13.161  1586  4210 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:13.162  7748  7765 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:13.162  3429  3446 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 08:52:13.162  3429  3446 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 08:52:13.162  3429  3446 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:13.162  3429  3446 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 08:52:13.162  7748  7765 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 08:52:13.162  7748  7765 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 08:52:13.162  7748  7765 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 08:52:13.162  7748  7748 V ToneGenerator: Create Track: 0xb4928080
08-31 08:52:13.162  7748  7748 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 08:52:13.162  7748  7748 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 08:52:13.162   321  2143 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 08:52:13.162   321  2143 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 08:52:13.162   321  2143 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 08:52:13.162   321  2143 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 08:52:13.162   321   321 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 08:52:13.162   321  3959 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 08:52:13.163   321  3959 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 08:52:13.163   321  3959 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 08:52:13.163   321  3959 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 08:52:13.163  7748  7748 V AudioSystem: getLatency() output 2, latency 50
08-31 08:52:13.163  7748  7748 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 08:52:13.163  7748  7748 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 08:52:13.163   321  1387 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 08,:52:13.163   321  1387 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 08:52:13.163   321  1387 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 08:52:13.163   321  1387 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 08:52:13.163   321  1387 V AudioFlinger: createTrack() lSessionId: 21
08-31 08:52:13.163  7748  7748 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 08:52:13.164   321  1387 V AudioFlinger: acquiring 21 from 7748, for 7748
08-31 08:52:13.164   321  1387 V AudioFlinger:  added new entry for 21
08-31 08:52:13.164  7748  7748 V ToneGenerator: ToneGenerator INIT OK, time: 134318
08-31 08:52:13.164  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.165  7748  7969 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 08:52:13.165  7748  7969 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 08:52:13.165  7748  7969 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 08:52:13.165  7748  7969 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 08:52:13.165   321  1388 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7748
08-31 08:52:13.166   321  1388 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 08:52:13.166   321  1388 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 08:52:13.166   321  1388 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 08:52:13.166   321  1388 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 08:52:13.166   321  1388 V voice   : voice_set_parameters: exit with code(0)
08-31 08:52:13.166   321  1388 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 08:52:13.166   321  1388 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 08:52:13.166   321  1388 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 08:52:13.166   321  1388 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 08:52:13.166   321  1388 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 08:52:13.166   321  1388 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 08:52:13.166  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.167  7748  7969 V ToneGenerator: ToneGenerator destructor
08-31 08:52:13.167  7748  7969 V ToneGenerator: stopTone
08-31 08:52:13.167  7748  7969 V ToneGenerator: Delete Track: 0xb4928080
08-31 08:52:13.167  7748  7969 V AudioTrack: ~AudioTrack, releasing session id from 7748 on behalf of 7748
08-31 08:52:13.168   321  2143 V AudioFlinger: releasing 21 from 7748 for 7748
08-31 08:52:13.168   321  2143 V AudioFlinger:  decremented refcount to 0
08-31 08:52:13.168   321  2143 V AudioFlinger: purging stale effects
08-31 08:52:13.168   321  2143 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 08:52:13.168   321  2143 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 08:52:13.168  7748  7748 D A2dpService: Received start request. Starting profile...
08-31 08:52:13.168   321  2143 V AudioFlinger: PlaybackThread::Track destructor
08-31 08:52:13.168   321  1260 V AudioPolicyService: AudioCommandThread() waking up
08-31 08:52:13.168   321  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 08:52:13.168   321  2143 V AudioFlinger: removeClient_l() pid 7748, calling pid 321
08-31 08:52:13.168   321  1260 V AudioPolicyManager: releaseOutput() 2
08-31 08:52:13.168   321  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 08:52:13.168  7748  7748 I BluetoothAvrcpServiceJni: classInitN,ative: succeeds
08-31 08:52:13.169  7748  7748 V Avrcp   : make
08-31 08:52:13.169  7748  7748 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 08:52:13.169  7748  7748 I bluedroid-qcom: get_profile_interface avrcp
08-31 08:52:13.171  1069  1680 W Process : Unable to open /proc/7972/status
08-31 08:52:13.172  7748  7948 V LGMDMManager: Create singleton instance
08-31 08:52:13.173  7748  7948 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 08:52:13.177  7748  7748 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 08:52:13.179  7748  7748 E AudioManager: No RCC entry present to update
08-31 08:52:13.179  7748  7748 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 08:52:13.181  7748  7748 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 08:52:13.182  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 08:52:13.182  7748  7748 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 08:52:13.185  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-31 08:52:13.269  1069  1904 V SIM_STK : Menu title from STK is T-Mobile
,08-31 08:52:13.269  1069  1904 V SIM_STK : Menu title from STK is T-Mobile
,08-31 08:52:13.339  1069  1954 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 08:52:13.348  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-31 08:52:13.352  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 08:52:13.352  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 08:52:13.352  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 08:52:13.353  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 08:52:13.353  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 08:52:13.353  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 08:52:13.353  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 08:52:13.353  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 08:52:13.353  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 08:52:13.353  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 08:52:13.353  7748  7748 I BluetoothA2dpServiceJni: classInitNative
08-31 08:52:13.353  7748  7748 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 08:52:13.353  7748  7748 D A2dpStateMachine: make
08-31 08:52:13.356  7748  7748 I bluedroid-qcom: get_profile_interface a2dp
08-31 08:52:13.357  7748  7977 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-31 08:52:13.359  7748  7748 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 08:52:13.359  7748  7748 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 08:52:13.360  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.360  7748  7976 D A2dpStateMachine: Enter Disconnected: -2
,08-31 08:52:13.361  7748  7748 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 08:52:13.362  7748  7748 D HidService: Received start request. Starting profile...
08-31 08:52:13.362  7748  7748 I bluedroid-qcom: get_profile_interface hidhost
08-31 08:52:13.362  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.363  7748  7748 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 08:52:13.364  7748  7748 D HealthService: Received start request. Starting profile...
08-31 08:52:13.367  7748  7748 I bluedroid-qcom: get_profile_interface health
08-31 08:52:13.367  7748  7748 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 08:52:13.367  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.368  7748  7748 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 08:52:13.369  7748  7748 D PanService: Received start request. Starting profile...
08-31 08:52:13.369  7748  7748 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 08:52:13.369  7748  7748 I bluedroid-qcom: get_profile_interface pan
,08-31 08:52:13.376  7748  7748 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-31 08:52:13.376  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.377  7748  7748 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 08:52:13.380  7748  7748 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 08:52:13.381  7748  7748 D BtGatt.GattService: Received start request. Starting profile...
08-31 08:52:13.381  7748  7748 D BtGatt.GattService: start()
08-31 08:52:13.381  7748  7748 I bluedroid-qcom: get_profile_interface gatt
08-31 08:52:13.381  7748  7748 D BtGatt.AdvertiseManager: advertise manager created
08-31 08:52:13.391  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
,08-31 08:52:13.392  7748  7748 D HeadsetStateMachine: Proxy object connected
08-31 08:52:13.392  7748  7748 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 08:52:13.392  7748  7748 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 08:52:13.394  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.394  7748  7748 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 08:52:13.395  7748  7748 V BluetoothMapService: BluetoothMapBinder()
08-31 08:52:13.395  7748  7748 D BluetoothMapService: Received start request. Starting profile...
08-31 08:52:13.395  7748  7748 D BluetoothMapService: start()
,08-31 08:52:13.399  7748  7748 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 08:52:13.399  7748  7748 D BluetoothMapEmailAppObserver: createReceiver()
08-31 08:52:13.400  7748  7748 D BluetoothMapEmailAppObserver: initObservers()
08-31 08:52:13.400  7748  7748 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 08:52:13.405  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:13.406  7748  7969 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 08:52:13.406  7748  7969 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 08:52:13.406  7748  7969 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-31 08:52:13.410  7748  7748 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 08:52:13.412  7748  7748 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 08:52:13.415  7748  7748 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 08:52:13.417  7748  7748 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:13.419  7748  7748 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 08:52:13.422  7748  7748 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 08:52:13.422  7748  7748 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 08:52:13.425  7748  7748 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 08:52:13.425  7748  7748 V BluetoothMapService: Handler(): got msg=1
08-31 08:52:13.425  7748  7748 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 08:52:13.426  7748  7748 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 08:52:13.426  7748  7748 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 08:52:13.426  7748  7748 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:13.426  7748  7748 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 08:52:13.427  7748  7948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 08:52:13.429  7748  7948 I bluedroid-qcom: enable
08-31 08:52:13.430  7748  7987 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 08:52:13.430  7748  7987 I bt-btu  : btu_task pending for preload complete event
08-31 08:52:13.431  7748  7948 I bt_hci_bdroid: init
08-31 08:52:13.434  7748  7948 I bt_vendor: bt-vendor : init
08-31 08:52:13.434  7748  7948 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 08:52:13.434  7748  7948 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 08:52:13.434  7748  7948 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 08:52:13.434  7748  7948 D bt_userial_mct: userial_init
08-31 08:52:13.435  7748  7948 D bt_hci_bdroid: set_power 1
08-31 08:52:13.435  7748  7948 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 08:52:13.435  7748  7948 I bt_vendor: Starting hciattach daemon
08-31 08:52:13.435  7748  7948 I bt_vendor: try to set true
,08-31 08:52:13.430  7990  7990 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 08:52:13.430  7990  7990 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:13.469  7991  7991 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 08:52:13.577  7997  7997 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 08:52:13.592  7998  7998 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 08:52:13.618  8000  8000 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 08:52:13.629  8001  8001 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-31 08:52:13.641  8002  8002 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 08:52:13.652  8003  8003 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-31 08:52:13.684  8005  8005 I libmdmdetect: ESOC framework not supported
,08-31 08:52:13.685  8005  8005 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 08:52:13.693  8005  8005 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-31 08:52:13.693  8005  8005 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 08:52:13.693  8005  8005 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 08:52:13.693  8005  8005 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 08:52:13.693  8005  8005 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 08:52:13.693  8005  8005 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 08:52:13.693  8005  8005 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 08:52:13.730  8005  8006 E QC-QMI  : qmi_client [8005] 15: failed to locate client data
,08-31 08:52:13.731   450   450 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-31 08:52:13.731   450   450 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-31 08:52:13.789  8007  8007 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 08:52:13.804  8008  8008 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 08:52:13.839  7748  7948 I bt_vendor: bluetooth satus is on
08-31 08:52:13.839  7748  7948 D bt_hci_bdroid: preload
08-31 08:52:13.840  7748  7989 D bt_userial_mct: userial_open(port:0)
08-31 08:52:13.840  7748  7989 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 08:52:13.844  7748  7989 I bt_vendor: Done intiailizing UART
08-31 08:52:13.847  7748  7989 I bt_vendor: Done intiailizing UART
08-31 08:52:13.847  7748  7989 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 08:52:13.847  7748  7989 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-31 08:52:13.847  7748  7987 I bt-btu  : btu_task received preload complete event
08-31 08:52:13.848  7748  8010 D bt_userial_mct: Entering userial_read_thread()
08-31 08:52:13.848  7748  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 08:52:13.848  7748  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 08:52:13.850  7748  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_SMP
,08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 08:52:13.855  7748  7987 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 08:52:13.971  7748  7987 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-31 08:52:13.971  7748  7987 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0199061 
,08-31 08:52:13.971  7748  7987 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0199061 
,08-31 08:52:14.008  7748  7952 E bt-btif : Calling BTA_HhEnable
08-31 08:52:14.008  7748  7952 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 08:52:14.008  7748  7952 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 08:52:14.012  1069  1069 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-31 08:52:14.012  1069  1069 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 08:52:14.013  7748  7952 D BluetoothAdapterProperties: Name is: G3
08-31 08:52:14.014  7748  7952 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:52:14.015  7748  7952 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 08:52:14.015  7748  7952 D bt_hci_bdroid: postload
08-31 08:52:14.016  7748  7952 D bte_conf: Device ID record 1 : primary
08-31 08:52:14.016  7748  7952 D bte_conf:   vendorId            = 00c4
08-31 08:52:14.016  7748  7952 D bte_conf:   vendorIdSource      = 0001
08-31 08:52:14.016  7748  7952 D bte_conf:   product             = 13a1
08-31 08:52:14.016  7748  7952 D bte_conf:   version             = 1000
08-31 08:52:14.016  7748  7952 D bte_conf:   clientExecutableURL = 
08-31 08:52:14.016  7748  7952 D bte_conf:   serviceDescription  = 
08-31 08:52:14.016  7748  7952 D bte_conf:   documentationURL    = 
08-31 08:52:14.017  7748  7989 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 08:52:14.017  7748  7952 D bte_conf: bte_load_did_conf no section named DID2.
08-31 08:52:14.020  7748  7948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 08:52:14.020  7748  7948 D BluetoothAdapterProperties: ScanMode =  20
08-31 08:52:14.020  7748  7948 D BluetoothAdapterProperties: State =  11
08-31 08:52:14.021  7748  7948 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 08:52:14.021  7748  7948 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 08:52:14.021  7748  7948 D BluetoothAdapterProperties: Setting state to 12
08-31 08:52:14.021  7748  7948 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 08:52:14.026  7748  7952 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 08:52:14.020  8018  8018 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 08:52:14.030  1069  1165 D BluetoothManagerService: Message: 60
08-31 08:52:14.030  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 08:52:14.030  1069  1165 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-31 08:52:14.020  8018  8018 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:14.045  7748  7989 D bt_hci_bdroid: Used up Tx Cmd credits
,08-31 08:52:14.051  7748  7948 I BluetoothAdapterState: Entering On State
,08-31 08:52:14.064  7748  8010 E bt_mct  : hci lib postload completed
,08-31 08:52:14.054  1834  2378 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:14.073  7748  7952 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 08:52:14.074  7748  7952 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-31 08:52:14.079  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:14.079  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:14.079  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:14.079  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:14.079  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:14.079  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:14.079  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:14.079  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:14.103  1834  1834 D BluetoothHeadset: Proxy object connected
,08-31 08:52:14.106  7748  7948 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 08:52:14.109  7748  7948 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 08:52:14.111  7748  7948 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 08:52:14.114  7748  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-31 08:52:14.114  7748  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 08:52:14.114  7748  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 08:52:14.114  7748  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 08:52:14.114  7748  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 08:52:14.114  7748  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 08:52:14.114  7748  7952 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 08:52:14.116  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:14.120  7748  7948 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 08:52:14.120  7748  7948 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 08:52:14.121  6835  6851 D BluetoothPan: onBluetoothStateChange on: true
08-31 08:52:14.121  6835  6851 D BluetoothPan: onBluetoothStateChange call bindService
08-31 08:52:14.128  1069  1165 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 08:52:14.131  1069  1069 D BluetoothA2dp: Proxy object connected
08-31 08:52:14.134  1834  2697 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:14.137  1834  1834 D BluetoothHeadset: Proxy object connected
,08-31 08:52:14.140  1069  1165 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:14.141  6835  6835 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 08:52:14.141  6835  6835 D PanProfile: Bluetooth service connected
08-31 08:52:14.142  1069  1069 D BluetoothHeadset: Proxy object connected
08-31 08:52:14.144  6835  7621 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 08:52:14.150  7748  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 08:52:14.150  7748  7987 W bt-smp  : Plain text(LSB ~ MSB) = b5 2c 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:14.150  7748  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = 43 5b e3 1d ad bd 94 33 ea aa d6 f7 fe 30 f9 c8 
08-31 08:52:14.150  7748  7987 W bt-btm  : Stopping oneshot timer
,08-31 08:52:14.160  8035  8035 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 08:52:14.161  6835  6835 D BluetoothInputDevice: Proxy object connected
08-31 08:52:14.162  6835  6835 D HidProfile: Bluetooth service connected
,08-31 08:52:14.163  6835  6852 D BluetoothMap: onBluetoothStateChange: up=true
08-31 08:52:14.166  6835  6835 D BluetoothMap: Proxy object connected
08-31 08:52:14.166  6835  6835 D MapProfile: Bluetooth service connected
08-31 08:52:14.166  6835  7621 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 08:52:14.166  6835  6835 D BluetoothMap: getConnectedDevices()
08-31 08:52:14.167  7748  8036 V BluetoothMapService: getConnectedDevices()
08-31 08:52:14.168  6835  6835 D BluetoothA2dp: Proxy object connected
08-31 08:52:14.168  6835  6851 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:14.168  6835  6835 D A2dpProfile: Bluetooth service connected
08-31 08:52:14.170  6835  6835 D BluetoothHeadset: Proxy object connected
08-31 08:52:14.170  6835  6835 D HeadsetProfile: Bluetooth service connected
08-31 08:52:14.170  6835  7621 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 08:52:14.171  7748  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 08:52:14.171  7748  7987 W bt-smp  : Plain text(LSB ~ MSB) = 26 a3 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:14.171  7748  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = 42 2f be 21 de 46 64 fc c1 55 ed f7 bd 68 7f 23 
08-31 08:52:14.171  7748  7987 W bt-btm  : Stopping oneshot timer
08-31 08:52:14.172  1834  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 08:52:14.176  1834  1834 D BluetoothHeadset: Proxy object connected
08-31 08:52:14.177  1069  1165 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 08:52:14.177  1069  1165 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 08:52:14.180  1922  1922 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:14.181  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 08:52:14.181  7748  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 08:52:14.181  7748  7987 W bt-smp  : Plain text(LSB ~ MSB) = 79 51 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:14.181  7748  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = 78 1b 10 b5 57 2a cb 56 f6 23 40 e7 59 8f 46 b3 
08-31 08:52:14.181  7748  7987 W bt-btm  : Stopping oneshot timer
08-31 08:52:14.182  1922  2109 D LGBluetoothAPIService: Message: 1
08-31 08:52:14.182  1922  2109 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 08:52:14.182  1922  2109 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-31 08:52:14.182  1922  2109 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-31 08:52:14.185  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:14.191  7748  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-31 08:52:14.191  7748  7987 W bt-smp  : Plain text(LSB ~ MSB) = 07 35 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:14.191  7748  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = 28 d4 bf 00 74 8f 55 87 0f e7 c1 3e 0e bb e3 4f 
08-31 08:52:14.191  7748  7987 W bt-btm  : Stopping oneshot timer
08-31 08:52:14.200  7748  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 08:52:14.200  7748  7987 W bt-smp  : Plain text(LSB ~ MSB) = 03 1a 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 08:52:14.200  7748  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = 53 1c 84 85 10 8e 3c 4c d1 e1 e7 44 bd 68 97 1d 
,08-31 08:52:14.200  7748  7987 W bt-btm  : Stopping oneshot timer
,08-31 08:52:14.305  1069  1931 I art     : Explicit concurrent mark sweep GC freed 28057(1395KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.609ms total 127.491ms
,08-31 08:52:14.308  1069  1069 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 08:52:14.309  6835  6835 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 08:52:14.309  1069  1165 D BluetoothManagerService: Message: 40
08-31 08:52:14.310  1069  1165 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 08:52:14.310  6835  6835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 08:52:14.311  7748  7748 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:14.311  7748  7748 D BluetoothMapService: STATE_ON
08-31 08:52:14.321  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:14.321  7748  7748 V BluetoothPbapService: Pbap Service onCreate
08-31 08:52:14.321  7748  7748 V BluetoothPbapService: Starting PBAP service
08-31 08:52:14.322  7748  7748 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 08:52:14.323  7748  7748 V BluetoothMapService: Handler(): got msg=1
,08-31 08:52:14.323  7748  7748 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 08:52:14.324  7748  7748 V BluetoothPbapService: Pbap Service onBind
08-31 08:52:14.326  7748  7748 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:14.326  7748  7748 V BluetoothPbapService: state: 12
08-31 08:52:14.326  7748  8044 D BluetoothMapMasInstance: MAS initSocket()
08-31 08:52:14.326  7748  7748 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 08:52:14.326  7748  7748 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:14.326  7748  7748 V BluetoothPbapReceiver: ***********state = 12
08-31 08:52:14.326  7748  8044 D BluetoothMapMasInstance:   masId = 00
08-31 08:52:14.326  7748  8044 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 08:52:14.326  7748  8044 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 08:52:14.326  7748  8044 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 08:52:14.327  7748  7748 V BluetoothPbapService: Handler(): got msg=1
08-31 08:52:14.328  7748  7748 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 08:52:14.328  6835  6835 D DockEventReceiver: finishStartingService: stopping service
08-31 08:52:14.329  1069  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:14.329  6835  6835 D BluetoothPbap: Proxy object connected
08-31 08:52:14.329  6835  6835 D PbapServerProfile: Bluetooth service connected
08-31 08:52:14.329  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 08:52:14.329  2203  2203 D c       : Getting all permits...
08-31 08:52:14.330  2203  2203 D a       : Opening database...
08-31 08:52:14.332  7748  8045 V BluetoothPbapService: Pbap Service initSocket
08-31 08:52:14.332  2203  2203 D a       : Opening database auth.proximity.permit_store...
08-31 08:52:14.333  7748  8044 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:14.334  2203  2203 D a       : Closing database...
,08-31 08:52:14.340  1069  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:14.341  7748  8044 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 08:52:14.341  7748  8044 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 08:52:14.341  7748  8044 D BluetoothMapMasInstance: Accepting socket connection...
08-31 08:52:14.341  7748  8045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:52:14.344  7748  8045 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 08:52:14.344  7748  8045 V BluetoothPbapService: Succeed to create listening socket 
08-31 08:52:14.344  7748  8045 V BluetoothPbapService: Accepting socket connection...
08-31 08:52:14.352  7748  7952 D BluetoothAdapterProperties: Scan Mode:21
08-31 08:52:14.352  7748  7952 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-31 08:52:14.355  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:14.357  6835  6835 D BluetoothPermissionRequest: onReceive
08-31 08:52:14.366  6835  6835 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-31 08:52:14.368  6835  6835 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 08:52:14.375  7748  7748 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-31 08:52:14.376  7748  7748 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 08:52:14.383  7748  7748 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-31 08:52:14.400  7748  7748 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 08:52:14.400  7748  7748 V BtOppService: onCreate
,08-31 08:52:14.404  7748  7748 V BluetoothOppNotification: send message
08-31 08:52:14.408  7748  7748 V BtOppService: Starting RfcommListener
08-31 08:52:14.415  7748  7748 D BluetoothOppPreference: Dumping Names:  
08-31 08:52:14.415  7748  7748 D BluetoothOppPreference: {}
08-31 08:52:14.415  7748  7748 D BluetoothOppPreference: Dumping Channels:  
08-31 08:52:14.415  7748  7748 D BluetoothOppPreference: {}
,08-31 08:52:14.417  7748  7748 V BtOppService: onStartCommand
,08-31 08:52:14.422  7748  7748 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:14.422  7748  7748 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 08:52:14.427  7748  7748 V BluetoothOppNotification: new notify threadi!
08-31 08:52:14.427  7748  8052 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-31 08:52:14.430  7748  7748 V BluetoothOppNotification: send delay message
08-31 08:52:14.431  7748  7748 V BtOppService: start RfcommListener
08-31 08:52:14.433  7748  8049 V BtOppService: Deleted complete outbound shares, number =  0
08-31 08:52:14.434  7748  8052 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 08:52:14.434  7748  8053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 08:52:14.435  7748  8049 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 08:52:14.436  7748  8049 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 08:52:14.436  7748  8052 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f86f49a on behalf of 
08-31 08:52:14.437  7748  8053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@141941cb on behalf of 
08-31 08:52:14.437  7748  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ecf0da8 on behalf of 
08-31 08:52:14.438  7748  8053 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 08:52:14.439  7748  8052 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-31 08:52:14.440  7748  7748 V BtOppService: RfcommListener started
,08-31 08:52:14.440  7748  8053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-31 08:52:14.441  7748  8054 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 08:52:14.441  1069  1085 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:14.442  7748  8054 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:14.443  7748  8054 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-31 08:52:14.443  7748  8054 V BtOppRfcommListener: Started RFCOMM listener....
08-31 08:52:14.443  7748  8053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c4230c1 on behalf of 
08-31 08:52:14.443  7748  8054 I BtOppRfcommListener: Accept thread started.
08-31 08:52:14.443  7748  8054 V BtOppRfcommListener: Accepting connection...
08-31 08:52:14.444  7748  8053 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 08:52:14.445  7748  8053 V BluetoothOppNotification: outbound notification was removed.
08-31 08:52:14.445  7748  8053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 08:52:14.447  7748  8053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@94fc066 on behalf of 
08-31 08:52:14.448  7748  8053 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 08:52:14.449  7748  8053 V BluetoothOppNotification: inbound notification was removed.
08-31 08:52:14.449  7748  8053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 08:52:14.450  7748  8053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38782fa7 on behalf of 
08-31 08:52:14.458  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:14.458  7748  7748 V BluetoothFtpService: Ftp Service onCreate
08-31 08:52:14.458  7748  7748 I BluetoothFtpService: Ftp Service onCreate
08-31 08:52:14.458  7748  7748 V BluetoothFtpService: Ftp Service onStartCommand
08-31 08:52:14.458  7748  7748 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:14.458  7748  7748 V BluetoothFtpService: Starting Listening on sockets
08-31 08:52:14.459  7748  7748 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 08:52:14.459  7748  7748 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 08:52:14.459  7748  7748 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 08:52:14.459  7748  7748 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:14.459  7748  7748 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 08:52:14.459  7748  7748 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-31 08:52:14.462  7748  7748 V BtOppService: ContentObserver received notification
08-31 08:52:14.462  7748  7748 V BtOppService: ContentObserver received notification
08-31 08:52:14.462  7748  7748 V BluetoothFtpService: Handler(): got msg=1
08-31 08:52:14.463  7748  7748 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 08:52:14.463  7748  7748 V BluetoothFtpService: Ftp Service initSocket
08-31 08:52:14.463  7748  8055 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 08:52:14.463  7748  8055 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 08:52:14.464  7748  8055 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f8017fd on behalf of 
08-31 08:52:14.465  7748  8055 V BluetoothOppNotification: update too frequent, put in queue
08-31 08:52:14.466  7748  8055 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 08:52:14.468  1069  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:14.469  7748  7748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:14.469  7748  7748 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-31 08:52:14.470  7748  7748 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 08:52:14.471  7748  8056 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-31 08:52:14.485  7748  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2901b7e
08-31 08:52:14.486  7748  7748 V BluetoothSapService: Sap Service onCreate
,08-31 08:52:14.488  7748  7748 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:14.488  7748  7748 V BluetoothSapService: state: 12
08-31 08:52:14.488  7748  7748 V BluetoothSapService: Starting SAP server process
08-31 08:52:14.490  7748  7748 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-31 08:52:14.480  8057  8057 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:14.492  7748  8058 V BluetoothSapService: Sap Service initRfcommSocket
,08-31 08:52:14.480  8057  8057 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:14.492  1069  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:14.493  7748  8058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:14.494  7748  8058 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 08:52:14.494  7748  8058 V BluetoothSapService: Succeed to create listening socket 
08-31 08:52:14.494  7748  8058 V BluetoothSapService: Accepting socket connection...
08-31 08:52:14.503  8057  8057 V BT_SAP  : Event pipe created
08-31 08:52:14.503  8057  8057 V BT_SAP  : create_server_socket qcom.sap.server
08-31 08:52:14.503  8057  8057 V BT_SAP  : created socket fd 6
,08-31 08:52:15.006  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:15.006  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:15.006  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:15.006  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:15.006  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:15.006  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:15.006  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:15.006  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:15.013  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:15.015  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:15.015  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c489763 added. We now have 8 listener(s)
,08-31 08:52:15.015  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:15.025  1069  1680 D WifiServiceImplEx: setWifiEnabled: false pid=6648, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 08:52:15.026  1069  1680 D WifiService: setWifiEnabled: false pid=6648, uid=10118
08-31 08:52:15.026  1069  1680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 08:52:15.035  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:15.037  1069  1976 D WifiServiceImplEx: setWifiEnabled: true pid=6648, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 08:52:15.037  1069  1976 D WifiService: setWifiEnabled: true pid=6648, uid=10118
08-31 08:52:15.037  1069  1976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 08:52:15.063  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 08:52:15.063  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 08:52:15.063  1069  1069 D Ulp_jni : JNI:system_update. Event-4
,08-31 08:52:15.065  1069  1375 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-31 08:52:15.065  1069  1375 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-31 08:52:15.067  1069  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1069] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-31 08:52:15.067  1069  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 08:52:15.067  1069  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1069] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-31 08:52:15.067  1069  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 08:52:15.067  1069  1375 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 08:52:15.067  1069  1375 E WifiHW  : unknown target_country: EU , set to default
08-31 08:52:15.067  1069  1375 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 08:52:15.067  1069  1375 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 08:52:15.067  1069  1375 I WifiUtil: gEnableBmps=1
08-31 08:52:15.432  7748  7748 V BluetoothOppNotification: new notify threadi!
08-31 08:52:15.433  7748  7748 V BluetoothOppNotification: send delay message
,08-31 08:52:15.451  7748  8071 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 08:52:15.454  7748  8071 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fbb36f9 on behalf of 
08-31 08:52:15.455  7748  8071 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 08:52:15.456  7748  8071 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 08:52:15.457  7748  8071 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b0c763e on behalf of 
08-31 08:52:15.458  7748  8071 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-31 08:52:15.462  7748  8071 V BluetoothOppNotification: outbound notification was removed.
,08-31 08:52:15.462  7748  8071 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 08:52:15.463  7748  8071 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32496c9f on behalf of 
08-31 08:52:15.464  7748  8071 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-31 08:52:15.467  7748  8071 V BluetoothOppNotification: inbound notification was removed.
08-31 08:52:15.467  7748  8071 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 08:52:15.468  7748  8071 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a55e1ec on behalf of 
08-31 08:52:15.704   317   892 D SoftapController: Softap fwReload - Ok
,08-31 08:52:15.716  1069  1375 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (642ms)
08-31 08:52:15.721   317   892 D CommandListener: Setting iface cfg
08-31 08:52:15.721   317   892 D CommandListener: Trying to bring down wlan0
,08-31 08:52:15.727   317   892 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:52:15.751  1069  1165 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 08:52:15.758  1069  1375 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 08:52:15.760  8079  8079 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:15.778  1069  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 08:52:15.778  1069  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 08:52:15.778  1069  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 08:52:15.785  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 08:52:15.780  8079  8079 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:15.793  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-31 08:52:15.823  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:15.827  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-31 08:52:15.828  1069  1375 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 08:52:15.828  1069  1375 D WifiMonitor: connecting to supplicant
08-31 08:52:15.832  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 08:52:15.832  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 08:52:15.832  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 08:52:15.833  6835  6835 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 08:52:15.835  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 08:52:15.837  6835  6835 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 08:52:15.837  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 08:52:15.837  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 08:52:15.837  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 08:52:15.837  6835  6835 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 08:52:15.838  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 08:52:15.839  6835  6835 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-31 08:52:15.840  8079  8079 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 08:52:15.873  8079  8079 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 08:52:15.873  8079  8079 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 08:52:15.878  1069  1165 D Tethering: InitialState.processMessage what=4
08-31 08:52:15.912  1069  2009 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8096 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-31 08:52:15.915  1069  1165 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 08:52:15.969  8079  8079 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 08:52:16.026  8079  8079 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 08:52:16.031  8079  8079 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 08:52:16.033  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 08:52:16.033  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 08:52:16.033  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-31 08:52:16.033  1069  8127 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 08:52:16.034  1069  8127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 08:52:16.034  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 08:52:16.034  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 08:52:16.035  1069  1375 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 08:52:16.035  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:16.036  1069  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:16.037  1069  1931 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8118 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 08:52:16.038  1069  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:16.038  1069  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:16.039  1069  1375 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 08:52:16.039  1069  1375 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 08:52:16.040  1069  1375 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 08:52:16.040  1069  1375 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 08:52:16.040  1069  1375 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-31 08:52:16.044  1069  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 08:52:16.044  1069  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 08:52:16.044  1069  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 08:52:16.045  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.045  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:52:16.045  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.046  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.046  1069  1375 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 08:52:16.046  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 08:52:16.047  1922  1922 D WfdService: Waiting for WifiP2p enabling
,08-31 08:52:16.047  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.047  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 08:52:16.048  1069  1379 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 08:52:16.049  1069  1375 D WifiNative-wlan0: SET update_config 1: returned true
08-31 08:52:16.049  1069  1375 D WifiConfigStore: Loading config and enabling all networks 
08-31 08:52:16.049  1069  1375 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 08:52:16.050  1069  1375 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 08:52:16.052  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:16.052  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:16.052  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:16.052  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:16.052  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:16.052  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:16.052  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:16.052  6648  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:16.053  8096  8116 W FormManager: Network not available. Please check & try again.
,08-31 08:52:16.056  1069  1375 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 08:52:16.057  6648  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:16.064  1069  1375 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 08:52:16.064  1069  1375 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 08:52:16.065  1069  1375 D WifiStateMachine: enableVerboseLogging : level 2
08-31 08:52:16.065  1069  1375 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 08:52:16.065  1069  1375 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 08:52:16.066  1069  1375 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 08:52:16.066  1069  1375 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 08:52:16.066  1069  1375 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 08:52:16.066  1069  1375 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 08:52:16.066  1069  1375 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 08:52:16.067  1069  1375 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 08:52:16.067  1069  1375 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 08:52:16.067  1069  1375 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 08:52:16.067  1069  1375 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 08:52:16.067  1069  1375 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 08:52:16.067  1069  1375 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 08:52:16.068  1069  1375 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 08:52:16.069  1922  1922 D WfdsService: Supplicant Connection state is changed : true
,08-31 08:52:16.069  1922  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 08:52:16.069  1922  2319 D WfdsService: Set the WFDS Monitor: true
08-31 08:52:16.069  1922  2319 D WfdsMonitor: WfdsMonitorThread create
08-31 08:52:16.070  1922  2319 D WfdsMonitor: WFDS Monitor is created and started
08-31 08:52:16.070  1922  2319 D WfdsService: WiFi: Supplicant connection re-established
08-31 08:52:16.070  1069  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 08:52:16.070  1069  1375 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 08:52:16.071  1069  1375 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 08:52:16.071  1069  1375 D WifiNative-HAL: Setting external_sim to 1
08-31 08:52:16.071  1069  1375 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 08:52:16.071  1922  8137 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-31 08:52:16.071  1069  1375 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 08:52:16.071  1069  1375 I WifiNative-HAL: startHal
08-31 08:52:16.071  1069  1375 D wifi    : setting scan oui 0xaf7130e0
08-31 08:52:16.071  1922  8137 E CtrlSupplicant: Succeed to open control connection
08-31 08:52:16.071  1922  8137 E CtrlSupplicant: Succeed to open monitor connection
08-31 08:52:16.071  1069  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 08:52:16.071  1069  1375 I WifiNative-HAL: startHal
08-31 08:52:16.071  1069  1375 D wifi    : setting scan oui 0xaf7130e0
08-31 08:52:16.072  1922  8137 D WfdsMonitor: Supplicant connection established
08-31 08:52:16.072  1069  1375 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 08:52:16.072  1069  1375 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 08:52:16.072  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 08:52:16.073  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 08:52:16.073  1922  2319 D WfdsService: Connected to the supplicant for wfds
08-31 08:52:16.073  8096  8117 V FormManager: Network unavailable.
08-31 08:52:16.073  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 08:52:16.073  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 08:52:16.073  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 08:52:16.074  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 08:52:16.074  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 08:52:16.074  7778  7778 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.074  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 08:52:16.075  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 08:52:16.075  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 08:52:16.075  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 08:52:16.075  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-31 08:52:16.075  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:16.075  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:16.075  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:16.075  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:16.075  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:16.075  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:16.075  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:16.076  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 08:52:16.076  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 08:52:16.076  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-31 08:52:16.076  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 08:52:16.076  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 08:52:16.077  8079  8079 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 08:52:16.077  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:16.077  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,08-31 08:52:16.077  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 08:52:16.077  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 08:52:16.078  1069  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 08:52:16.078  1069  1375 E WifiNative: : [137,218,512 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 08:52:16.079  1069  1375 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 08:52:16.079  1069  1375 D WifiNative-wlan0: RECONNECT: returned true
,08-31 08:52:16.079  1069  1375 D WifiNative-wlan0: doString: [STATUS]
08-31 08:52:16.079  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 08:52:16.079  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 08:52:16.080  1069  1375 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 08:52:16.080  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 08:52:16.080  1069  1375 D WifiNative-wlan0: SET ps 1: returned true
,08-31 08:52:16.081  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 08:52:16.082   317   892 D CommandListener: Setting iface cfg
08-31 08:52:16.082   317   892 D CommandListener: Trying to bring up p2p0
08-31 08:52:16.083  1069  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 08:52:16.083  1069  1374 D LGWifiP2pService: P2pEnablingState
08-31 08:52:16.083  1069  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.083  1069  1374 D LGWifiP2pService: P2p socket connection successful
08-31 08:52:16.083  1069  1374 D LGWifiP2pService: P2pEnabledState
08-31 08:52:16.083  6648  6772 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 08:52:16.084  6648  6772 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 08:52:16.086  8096  8117 V FormManager: Network unavailable.
08-31 08:52:16.087  1069  1069 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 08:52:16.087  1069  1069 D RttService: SCAN_AVAILABLE : 3
,08-31 08:52:16.087  6648  6772 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@27d758ad Bundle[{}]
08-31 08:52:16.087  1069  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 08:52:16.088  1069  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,08-31 08:52:16.088  1069  1541 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.088  1069  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.088  1069  1540 I WifiNative-HAL: startHal
08-31 08:52:16.088  6648  6772 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 08:52:16.088  6648  6772 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 08:52:16.089  6648  6772 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 08:52:16.089  1922  1922 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 08:52:16.090  1922  1922 D WfdsService: WifiP2pState is changed : true
08-31 08:52:16.090  1922  1922 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 08:52:16.090  6648  6772 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 08:52:16.090  1069  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 08:52:16.090  1922  1922 D WfdsService: isConnected: false
08-31 08:52:16.090  1922  2319 D WfdsService: Receive the WFDS_ENABLE Method
08-31 08:52:16.090  1922  2319 D WfdsService: Set the WFDS Monitor: true
08-31 08:52:16.090  1922  2319 D WfdsService: Connected to the supplicant for wfds
08-31 08:52:16.090  1069  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 08:52:16.090  1922  2319 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 08:52:16.091  8079  8079 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 08:52:16.091  6648  6772 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 08:52:16.091  1922  2319 D WfdsService: selectPreferredScanChannel [36]
08-31 08:52:16.091  1922  2319 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 08:52:16.091  6648  6772 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 08:52:16.092  1069  1375 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 08:52:16.092  1069  1375 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 08:52:16.092  1069  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-31 08:52:16.092  1069  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 08:52:16.092  1069  1374 D LGWifiP2pService: before postfix = G3
08-31 08:52:16.092  1069  1374 D WifiServerServiceExt: postfix byte check : 2
08-31 08:52:16.092  1069  1374 D LGWifiP2pService: after postfix = G3
08-31 08:52:16.093  1069  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 08:52:16.093  1069  1375 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 08:52:16.093  1069  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 08:52:16.093  1069  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 08:52:16.093  1069  1375 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 08:52:16.093  1069  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 08:52:16.093  1069  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 08:52:16.094  1069  1375 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 08:52:16.094  1069  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 08:52:16.094  1069  1375 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 08:52:16.094  1069  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf7130e0
08-31 08:52:16.094  1069  1540 D wifi    : failed to get capabilities : -3
08-31 08:52:16.094  1069  1540 E WifiScanningService: could not get scan capabilities
08-31 08:52:16.094  1069  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 08:52:16.094  1069  1375 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 08:52:16.094  1069  1375 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 08:52:16.095  8079  8079 E wpa_supplicant,: nWIFIDualbandAPConnection: 1
08-31 08:52:16.095  1069  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 08:52:16.095  1069  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-31 08:52:16.095  1069  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-31 08:52:16.097  1922  1922 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 08:52:16.097  1922  1922 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 08:52:16.097  1069  1374 D LGWifiP2pService: DeviceAddress: 
08-31 08:52:16.097  1069  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 08:52:16.097  1922  1922 D WfdsService: Update P2p Interface State: 3
08-31 08:52:16.097  1069  1374 D WifiNative-p2p0: P2P_FLUSH: returned false
08-31 08:52:16.097  1069  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 08:52:16.098  1069  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 08:52:16.098  1069  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 08:52:16.098  6648  6772 I System.out: Running OutgoingSocketThread
08-31 08:52:16.098  1069  1374 D WifiNative-p2p0:    returned OK
08-31 08:52:16.098  1069  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 08:52:16.099  1069  1374 D WifiNative-p2p0: SAVE_CONFIG: returned false
08-31 08:52:16.099  1069  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 08:52:16.100  1069  1374 D LGWifiP2pService: InactiveState
08-31 08:52:16.100  6648  8138 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 856)
08-31 08:52:16.100  1069  1374 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.100  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.100  1069  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 08:52:16.101  6648  8138 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50211
08-31 08:52:16.101  6648  8138 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-31 08:52:16.105  1069  1931 I ActivityManager: Killing 7115:com.android.chrome/u0a57 (adj 15): empty #17
08-31 08:52:16.124  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-31 08:52:16.124  1069  1375 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,08-31 08:52:16.124  8079  8079 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:52:16.124  1069  1375 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 08:52:16.125  1922  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 08:52:16.125  1069  1375 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 08:52:16.125  1069  1375 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 08:52:16.125  1069  8127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 08:52:16.125  1069  8127 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:52:16.125  1069  8127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:52:16.125  1069  8127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:52:16.125  8079  8079 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 08:52:16.125  8079  8079 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 08:52:16.125  8079  8079 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.125  1069  1375 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 08:52:16.126  1069  1375 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 08:52:16.126  1069  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 08:52:16.126  1069  1374 D LGWifiP2pService: InactiveState{ when=-26ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.126  8079  8079 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.126  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.126  1069  1374 D LGWifiP2pService: DefaultState{ when=-26ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.126  1069  1375 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 08:52:16.126  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 08:52:16.126  1069  1374 D LGWifiP2pService: InactiveState{ when=-26ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.126  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.126  1922  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:52:16.127  1922  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:52:16.127  1069  1374 D LGWifiP2pService: DefaultState{ when=-26ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.127  1069  1374 D LGWifiP2pService: InactiveState{ when=-27ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.127  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.127  1069  1374 D LGWifiP2pService: DefaultState{ when=-27ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.127  1069  1374 D LGWifiP2pService: InactiveState{ when=-27ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.127  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.127  1069  1374 D LGWifiP2pService: DefaultState{ when=-27ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.127  1069  8127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:52:16.127  1069  8127 E WifiMonitor: WifiMonitor:p2p,0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.127  1069  1069 E WifiServerServiceExt: No p2p device connected
08-31 08:52:16.127  1069  8127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.127  1069  8127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.127  1069  8127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:52:16.127  1069  8127 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.127  1069  8127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.127  1922  2319 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 08:52:16.127  1069  8127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.128  8118  8118 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:52:16.128  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 08:52:16.128  8079  8079 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:52:16.128  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 08:52:16.128  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:52:16.129  1069  8127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:52:16.129  1069  8127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 08:52:16.129  8079  8079 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 08:52:16.129  8079  8079 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.129  1922  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:52:16.129  1069  1375 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 08:52:16.129  1069  8127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:52:16.129  1069  8127 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.129  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.129  1069  8127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.129  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.129  1069  8127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.129  1069  1375 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 08:52:16.130  8079  8079 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.130  1069  1375 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 08:52:16.130  1922  8137 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:52:16.130  1069  8127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 08:52:16.130  1069  8127 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.130  1069  8127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.130  1069  8127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 08:52:16.130  1069  1375 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 08:52:16.130  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 08:52:16.130  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 08:52:16.130  8079  8079 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 08:52:16.130  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 08:52:16.131  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 08:52:16.131  1069  8127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 08:52:16.131  1069  8127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 08:52:16.131  1069  1375 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 08:52:16.131  1069  1375 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 08:52:16.131  1069  1375 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 08:52:16.131  1069  1375 D WifiNative-wlan0: doBoolean: SCAN
08-31 08:52:16.132  1069  1375 D WifiNative-wlan0: SCAN: returned false
08-31 08:52:16.132  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137272  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 08:52:16.149  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:16.150  1069  1559 W libprocessgroup: failed to open /acct/uid_10057/pid_7115/cgroup.procs: No such file or directory
08-31 08:52:16.153  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137294  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 08:52:16.154  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.154  1069  1375 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:52:16.154  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:16.154  1069  1375 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:52:16.155  1069  1375 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:52:16.155  1069  1375 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:52:16.155  1069  1375 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 08:52:16.156  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.156  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.156  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 08:52:16.156  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:52:16.156  1069  1069 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 08:52:16.157  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.158  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:16.159  1069  1597 I ActivityManager: Killing 7139:com.lge.drmservice/u0a62 (adj 15): empty #17
08-31 08:52:16.189  1069  1976 W libprocessgroup: failed to open /acct/uid_10062/pid_7139/cgroup.procs: No such file or directory
,08-31 08:52:16.203  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 08:52:16.203  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 08:52:16.203  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 08:52:16.203  6835  6835 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 08:52:16.204  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 08:52:16.204  6835  6835 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 08:52:16.205  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 08:52:16.205  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 08:52:16.205  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 08:52:16.205  6835  6835 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 08:52:16.205  6835  6835 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 08:52:16.219  8118  8118 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:52:16.222  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 08:52:16.227  8096  8143 W FormManager: Network not available. Please check & try again.
,08-31 08:52:16.232  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:16.245  8096  8144 V FormManager: Network unavailable.
,08-31 08:52:16.251  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 08:52:16.252  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 08:52:16.253  8096  8144 V FormManager: Network unavailable.
08-31 08:52:16.253  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:16.256  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 08:52:16.265  4305  8145 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 08:52:16.270  4305  8146 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 08:52:16.270  4305  8146 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 08:52:16.301  1069  1597 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8147 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 08:52:16.439  8147  8147 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 08:52:16.439  8147  8147 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-31 08:52:16.447  8147  8147 V [BNRBootReceiver]: Boot Receiver Return
08-31 08:52:16.450  8147  8147 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 08:52:16.523  1069  2009 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8165 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 08:52:16.526  1069  2009 I ActivityManager: Killing 7156:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-31 08:52:16.586  1069  1886 W libprocessgroup: failed to open /acct/uid_10085/pid_7156/cgroup.procs: No such file or directory
,08-31 08:52:16.618  8165  8165 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 08:52:16.649  8165  8165 D PluginManager: init()
,08-31 08:52:16.660  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 08:52:16.660  1069  8127 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 08:52:16.660  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 08:52:16.660  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-31 08:52:16.660  8079  8079 E wpa_supplicant: USIM:  scard_init function
08-31 08:52:16.660  1069  8127 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 08:52:16.661  8079  8079 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-31 08:52:16.662  1069  1375 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 08:52:16.663  1069  1375 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 08:52:16.664  1069  1375 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 08:52:16.665  1069  1375 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 08:52:16.665  1069  1375 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 08:52:16.666  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 08:52:16.666  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 08:52:16.678  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=137819  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 08:52:16.688  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.688  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:16.688  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=137828  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 08:52:16.691  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.691  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.691  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 08:52:16.693  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.693  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.693  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 08:52:16.694  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:52:16.694  1069  1069 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 08:52:16.695  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 08:52:16.700  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.700  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:16.701  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.783  1069  1165 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 08:52:16.784  8079  8079 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 08:52:16.787  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 08:52:16.787  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 08:52:16.787  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 08:52:16.787  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 08:52:16.787  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 08:52:16.787  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-31 08:52:16.788  1069  1375 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:16.788  1069  1375 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:16.789  1069  1375 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:16.789  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-31 08:52:16.789  1069  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 08:52:16.790  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=137930  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 08:52:16.790  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=137931  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 08:52:16.791  1069  1375 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137931
08-31 08:52:16.791  1069  1375 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137932
08-31 08:52:16.792  1069  1375 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137932
08-31 08:52:16.792  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137932
08-31 08:52:16.792  1069  1375 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137933
08-31 08:52:16.793  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=137933  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 08:52:16.798  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.798  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.798  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 08:52:16.799  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.799  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:16.804  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 08:52:16.804  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 08:52:16.805  8079  8079 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 08:52:16.805  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 08:52:16.805  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 08:52:16.805  1069  8127 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 08:52:16.805  8079  8079 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 08:52:16.806  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 08:52:16.806  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 08:52:16.806  1069  8127 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 08:52:16.809  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-31 08:52:16.809  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 08:52:16.812  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=137953  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 08:52:16.815  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.817  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.817  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.817  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 08:52:16.818  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:52:16.818  1069  1069 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 08:52:16.818  1069  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=137958  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 08:52:16.819  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.819  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:16.819  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=137959  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 08:52:16.819  1069  1375 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137960
08-31 08:52:16.819  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.820  1069  1375 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137960
08-31 08:52:16.820  1069  1375 D WifiNative-wlan0: doString: [STATUS]
08-31 08:52:16.821  1069  8127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 08:52:16.821  1069  8127 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 08:52:16.821  1069  1375 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 08:52:16.823  1069  1375 I WifiServiceExtension: setVHTCapabilityType  : false
,08-31 08:52:16.830  1069  1375 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 08:52:16.830  1069  1375 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-31 08:52:16.836  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.836  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:16.837  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.837  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:52:16.837  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 08:52:16.838  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.842  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.842  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.842  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 08:52:16.846  1069  1375 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 08:52:16.846  1069  1390 D ConnectivityService: Got NetworkAgent Messenger
08-31 08:52:16.847  1069  1390 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 08:52:16.847  1069  1390 D ConnectivityService: NetworkAgent connected
08-31 08:52:16.847  1069  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 08:52:16.847  1069  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 08:52:16.848  1069  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 08:52:16.848  1069  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 08:52:16.857  1069  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 08:52:16.857  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.857  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:16.857  1069  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 08:52:16.857  1069  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-31 08:52:16.858  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.858  1069  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 08:52:16.858  1069  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 08:52:16.864  1069  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 08:52:16.865   317   892 D CommandListener: Setting iface cfg
08-31 08:52:16.867  1069  1375 E WifiStateMachine: Start Dhcp Watchdog 3
08-31 08:52:16.867  1069  8186 D DhcpStateMachine: StoppedState
08-31 08:52:16.868  1069  8186 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.868  1069  8186 D DhcpStateMachine: WaitBeforeStartState
08-31 08:52:16.869  1069  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138009  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:52:16.869  1069  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138009  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:52:16.870  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138010  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:52:16.870  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:52:16.870  1069  1069 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-31 08:52:16.872  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:52:16.872  1069  1069 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 08:52:16.872  1069  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138012  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:52:16.872  1069  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138013  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:52:16.873  1069  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138013  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 08:52:16.874  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14079] from screen [on:0 period:-547445654] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 08:52:16.874  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-547445654] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 08:52:16.874  1069  1375 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 08:52:16.878  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.878  1069  1390 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-31 08:52:16.878  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.879  1069  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.879  1069  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.879  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.879  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.880  1069  1390 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 08:52:16.880  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-31 08:52:16.880  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-31 08:52:16.880  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 08:52:16.881  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 08:52:16.881  1069  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 08:52:16.881  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 08:52:16.881  1069  1375 D WifiNative-wlan0: SET ps 0: returned true
08-31 08:52:16.881  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 08:52:16.881  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 08:52:16.881  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 08:52:16.882  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@70203f6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.882  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@70203f6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.882  1069  8186 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.882  1069  8186 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 08:52:16.882  1069  1375 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 08:52:16.883  1069  1375 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 08:52:16.883  1069  1375 V LgDhcpStateMachineHelper: [bssid ,+ ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 08:52:16.883   317   892 D CommandListener: Setting iface cfg
08-31 08:52:16.883   317   892 D CommandListener: Trying to bring up wlan0
08-31 08:52:16.884  1069  1375 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 08:52:16.885  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.885  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:52:16.885  1069  1069 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 08:52:16.886  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 08:52:16.886  1069  1069 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 08:52:16.887  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.887  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.888  1069  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.888  1069  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.888  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.888  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 08:52:16.889  1069  1390 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 08:52:16.889  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 08:52:16.889  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 08:52:16.890  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.890  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.890  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 08:52:16.890  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 08:52:16.890  1069  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 08:52:16.890  1069  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 08:52:16.890  8079  8079 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 08:52:16.890  1069  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 08:52:16.890  1069  1375 D WifiNative-wlan0: doBoolean: SET ps 1
,08-31 08:52:16.908  1069  1375 D WifiNative-wlan0: SET ps 1: returned true
,08-31 08:52:16.909  1069  1375 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-31 08:52:16.909  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 08:52:16.909  1069  1375 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 08:52:16.910  1069  1390 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 08:52:16.910  1069  1390 D ConnectivityService: ignoring duplicate network state non-change
08-31 08:52:16.911  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.912  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:16.913  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.913  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.914  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.914  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 08:52:16.915  1069  1390 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 08:52:16.915  1069  1390 D ConnectivityService: Adding iface wlan0 to network 102
08-31 08:52:16.918  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.918  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.918  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 08:52:16.920  1069  1375 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 08:52:16.922  1069  1069 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 08:52:16.927  1922  1922 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 08:52:16.934  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.934  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 08:52:16.935  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.936  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.936  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.937  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 08:52:16.937  1069  1069 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 08:52:16.940  1069  1390 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 08:52:16.940  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.940  1069  1390 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-31 08:52:16.940  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 08:52:16.940  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.941  1069  1390 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-31 08:52:16.941   317   892 E Netd    : netlink response contains error (File exists)
08-31 08:52:16.942  1069  1390 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-31 08:52:16.943  1069  1390 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 08:52:16.943  1069  1390 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-31 08:52:16.943  1069  1390 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-31 08:52:16.943  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.943  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:16.943  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 08:52:16.944  1069  1390 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 08:52:16.944  1069  1390 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 08:52:16.944  1069  1390 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 08:52:16.944  1069  1390 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 08:52:16.944  1069  1390 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:52:16.944  1069  1390 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:16.944  1069  1390 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 08:52:16.944  1069  1390 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:16.944  1069  1390 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 08:52:16.944  1069  1390 D ConnectivityService: currentScore = 0, newScore = 20
08-31 08:52:16.944  1069  1390 D ConnectivityService:    accepting network in place of null
08-31 08:52:16.944  1069  1390 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:16.944  1069  8185 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.944  1069  8185 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 08:52:16.944  1069  8185 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 08:52:16.944  1069  8185 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 08:52:16.946  1069,  1375 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:16.946  1069  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:52:16.947  1834  1834 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:16.947  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 08:52:16.947   317  8196 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 08:52:16.948  1069  1390 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 08:52:16.948  1069  1390 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 08:52:16.948  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 08:52:16.948  1069  1390 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:16.948  1069  1390 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 08:52:16.948  1069  1390 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 08:52:16.949  1069  1390 D ConnectivityService: validation of new default Network = false
08-31 08:52:16.949  1069  1390 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 08:52:16.949  1069  1390 D DSQN    : enableDataServiceNotify 
08-31 08:52:16.949  1069  1390 D DSQN    : start dsqn bin
,08-31 08:52:16.957  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 08:52:16.957  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 08:52:16.958  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:16.958  1069  1390 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 08:52:16.958  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:16.958  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:16.958  1069  1390 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:16.958  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 08:52:16.950  8197  8197 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:16.950  8197  8197 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 08:52:16.970  8197  8197 E DSQN    : DSQN ssw
,08-31 08:52:16.986  1069  1069 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 08:52:16.987  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 08:52:16.987  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 08:52:16.987  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 08:52:16.998  1069  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-31 08:52:17.001   317  8196 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 08:52:17.005  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 08:52:17.006  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:17.007  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:17.038   317  8196 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-31 08:52:17.068   317   891 D LGDataListener: argv[0]=dsqncommand
08-31 08:52:17.068   317   891 D LGDataListener: argv[1]=wlan0
08-31 08:52:17.068   317   891 D LGDataListener: argv[2]=1
08-31 08:52:17.068   317   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 08:52:17.069  1069  1163 D DSQN    : DSQM DsqnNotification wlan0  1
08-31 08:52:17.069  1069  1163 D DSQN    : start to monitor internet connection
,08-31 08:52:17.084  1069  8186 D DhcpStateMachine: DHCPV4 request on wlan0
,08-31 08:52:17.086  1069  8186 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-31 08:52:17.086  1069  8186 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 08:52:17.080  8203  8203 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:17.080  8203  8203 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 08:52:17.104  6648  6772 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 857)
08-31 08:52:17.104  6648  6772 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 857)
08-31 08:52:17.113  6648  6772 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862)
08-31 08:52:17.114  8203  8203 I dhcpcd  : version 5.5.6 starting
08-31 08:52:17.115  1069  8185 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 06:52:17 GMT], X-Android-Received-Millis=[1472626337114], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472626337067]}
08-31 08:52:17.116  1069  8185 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 08:52:17.116  1069  8185 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 08:52:17.116  6648  6772 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 08:52:17.116  6648  6772 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
08-31 08:52:17.116  1069  1390 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-31 08:52:17.116  1069  1390 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 08:52:17.117  1069  1390 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 08:52:17.117  1069  1390 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:17.117  1069  1390 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 08:52:17.117  1069  1390 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-31 08:52:17.117  1069  1390 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 08:52:17.117  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:17.118  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:17.118  8203  8203 E dhcpcd  : get_duid: m
08-31 08:52:17.118  8203  8203 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 08:52:17.118  8203  8203 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 08:52:17.119  1069  1390 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:17.119  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 08:52:17.119  1069  1390 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:17.120  1069  1390 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 08:52:17.120  1069  1375 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:17.120  1069  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 08:52:17.123  1834  1834 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:17.124  1834  1834 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 08:52:17.131  8165  8165 W ExternalStrings: load override strings
08-31 08:52:17.131  8165  8165 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:52:17.131  8165  8165 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:52:17.133  8165  8165 D StatusProvider: onCreate
,08-31 08:52:17.137  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.137  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@229acf60 added. We now have 2 listener(s)
08-31 08:52:17.137  1069  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.140  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.140  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.140  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.141  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.141  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b59bc19 added. We now have 9 listener(s)
08-31 08:52:17.141  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:17.142  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:52:17.143  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:17.147  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:17.147  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:17.147  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:17.147  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:17.147  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:17.147  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.147  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:17.147  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:17.149  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.149  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 08:52:17.150  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:17.150  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.150  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a346bf added. We now have 3 listener(s)
08-31 08:52:17.150  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:17.150  1069  1680 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.150  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 08:52:17.152  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.152  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.152  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.152  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.152  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcd818c added. We now have 10 listener(s)
08-31 08:52:17.153  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:17.153  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:17.153  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:17.153  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:17.153  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.153  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.153  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:17.153  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.153  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@229acf60 removed from the list
08-31 08:52:17.153  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.153  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b59bc19 removed from the list
08-31 08:52:17.154  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.154  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:17.154  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 list,ener(s) left
08-31 08:52:17.154  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.154  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.155  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.155  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.155  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.155  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.156  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b59bc19 not in the list
08-31 08:52:17.156  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.156  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.156  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.156  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.156  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.156  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcd818c removed from the list
08-31 08:52:17.156  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.156  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.156  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.156  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.157  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a346bf removed from the list
08-31 08:52:17.157  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.157  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224100d5 added. We now have 2 listener(s)
08-31 08:52:17.157  1069  1931 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.158  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.158  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.158  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.158  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.159  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dac70ea added. We now have 9 listener(s)
08-31 08:52:17.159  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listene,rs is now 1
08-31 08:52:17.159  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:52:17.160  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:17.162  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:17.162  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:17.162  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:17.162  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:17.162  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:17.162  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.162  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:17.162  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:17.163  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.163  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:17.164  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.164  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3972a78 added. We now have 3 listener(s)
08-31 08:52:17.164  1069  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.165  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.166  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.167  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.167  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.167  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.167  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.167  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@271dd551 added. We now have 10 listener(s)
08-31 08:52:17.167  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:17.167  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:17.167  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:17.167  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:17.167  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:17.167  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:52:17.169  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 08:52:17.170  1069  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.173  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 08:52:17.174  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 08:52:17.175  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:52:17.175  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:17.177  6648  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 08:52:17.177  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:17.177  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:17.178  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:17.178  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:17.179  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:17.179  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.179  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.179  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:17.179  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.179  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224100d5 removed from the list
08-31 08:52:17.179  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.179  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dac70ea removed from the list
08-31 08:52:17.179  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:17.179  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.179  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.179  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.180  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.180  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.180  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.180  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dac70ea not in the list
08-31 08:52:17.180  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.180  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.186  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.186  8203  8203 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 08:52:17.187  8203  8203 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 08:52:17.187  8203  8203 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 08:52:17.187  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:52:17.187  8203  8203 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 08:52:17.187  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:52:17.187  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.187  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.187  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@271dd551 removed from the list
08-31 08:52:17.187  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.187  8203  8203 D dhcpcd  : wlan0: sending REQUEST (xid 0x20f01c30), next in 4.84 seconds
08-31 08:52:17.187  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.187  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.187  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.187  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3972a78 removed from the list
08-31 08:52:17.188  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.188  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20507624 added. We now have 2 listener(s)
08-31 08:52:17.188  1069  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.190  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.190  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.190  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.190  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.190  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a19758d added. We now have 9 listener(s)
08-31 08:52:17.190  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:17.190  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:52:17.192  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:17.194  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:17.194  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:17.194  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:17.194  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:17.194  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:17.194  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.194  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:17.194  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:17.195  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.195  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:17.196  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.196  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63e1f53 added. We now have 3 listener(s)
08-31 08:52:17.196  1069  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.197  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.198  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.198  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.198  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.198  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.198  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.198  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2330d090 added. We now have 10 listener(s)
08-31 08:52:17.198  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:17.198  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:17.199  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:17.199  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:17.199  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:17.199  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:17.199  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:52:17.200  8165  8165 V Signer  : override build config not found
08-31 08:52:17.200  8165  8165 D Signer  : value of property debug is false
,08-31 08:52:17.201  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 08:52:17.201  1069  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.204  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 08:52:17.204  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 08:52:17.205  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:52:17.206  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:17.207  6648  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 08:52:17.207  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:17.207  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:17.207  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:17.207  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.207  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.207  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:17.207  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.207  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20507624 removed from the list
08-31 08:52:17.207  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.207  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a19758d removed from the list
08-31 08:52:17.207  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:17.207  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.207  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.207  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.208  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.208  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.208  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.208  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a19758d not in the list
08-31 08:52:17.208  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.208  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.208  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.209  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:52:17.209  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:52:17.209  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.209  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.209  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2330d090 removed from the list
08-31 08:52:17.209  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.209  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.209  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.209  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.209  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63e1f53 removed from the list
08-31 08:52:17.209  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.209  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38015daf added. We now have 2 listener(s)
08-31 08:52:17.209  1069  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.210  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.210  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.210  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.211  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.211  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277a65bc added. We now have 9 listener(s)
08-31 08:52:17.211  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:17.211  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:52:17.212  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:17.214  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:17.214  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:17.214  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:17.214  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:17.214  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:17.214  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.214  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:17.214  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:17.215  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.215  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:17.215  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.215  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f3ae89a added. We now have 3 listener(s)
08-31 08:52:17.215  1069  1085 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.217  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.218  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.220  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.220  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.220  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.220  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.220  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@201025cb added. We now have 10 listener(s)
08-31 08:52:17.220  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:17.220  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:17.221  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:17.221  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:17.221  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:17.221  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:52:17.224  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 08:52:17.224  1069  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.227  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 08:52:17.228  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 08:52:17.229  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:52:17.229  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:17.230  6648  6772 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 08:52:17.231  8203  8203 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-31 08:52:17.232  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:17.232  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:17.232  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:17.232  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.232  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.232  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:17.232  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.232  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38015daf removed from the list
08-31 08:52:17.232  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.232  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277a65bc removed from the list
08-31 08:52:17.232  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:17.232  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.233  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.233  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.233  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.233  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.233  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.233  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277a65bc not in the list
08-31 08:52:17.233  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.233  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.234  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.235  6648  6772 D BluetoothLeScanner: could not find callback wrapper
08-31 08:52:17.235  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:52:17.235  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.235  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.235  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@201025cb removed from the list
08-31 08:52:17.235  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.235  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.235  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.235  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.235  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f3ae89a removed from the list
08-31 08:52:17.235  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.235  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224ef466 added. We now have 2 listener(s)
08-31 08:52:17.235  1069  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.237  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.237  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.237  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.237  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.237  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16f953a7 added. We now have 9 listener(s)
08-31 08:52:17.237  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:17.238  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:52:17.240  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:17.249  6648  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:17.249  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:17.249  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 08:52:17.249  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:17.249  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:17.249  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.249  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:17.249  6648  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:17.256  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-31 08:52:17.257  8203  8203 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 08:52:17.257  8203  8203 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 08:52:17.257  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-31 08:52:17.257  6648  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:17.257  6648  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:17.257  8203  8203 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 08:52:17.258  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-31 08:52:17.258  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:17.258  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1fdbfd added. We now have 3 listener(s)
08-31 08:52:17.258  8203  8203 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 08:52:17.258  1069  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 08:52:17.258  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-31 08:52:17.258  8203  8203 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 08:52:17.259  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-31 08:52:17.259  8203  8203 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 08:52:17.259  8203  8203 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 08:52:17.259  8203  8203 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 08:52:17.259  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.260  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-31 08:52:17.260  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-31 08:52:17.260  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 08:52:17.260  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:17.260  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:17.261  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:17.261  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1745f0f2 added. We now have 10 listener(s)
08-31 08:52:17.261  6648  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:17.261  6648  6772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:17.261  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:17.261  6648  6772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:17.261  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.261  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.261  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:17.261  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.261  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224ef466 removed from the list
08-31 08:52:17.261  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.261  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16f953a7 removed from the list
08-31 08:52:17.264  6648  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:17.264  6648  6772 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:17.264  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.264  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.264  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.265  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.265  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.265  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.265  6648  6772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16f953a7 not in the list
08-31 08:52:17.265  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.265  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-31 08:52:17.265  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.265  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-31 08:52:17.265  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:17.265  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:17.266  6648  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:17.266  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-31 08:52:17.266  6648  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1745f0f2 removed from the list
08-31 08:52:17.266  6648  6772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:17.266  6648  6772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:17.266  6648  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:17.266  6648  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:17.266  6648  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1fdbfd removed from the list
08-31 08:52:17.266  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-31 08:52:17.266  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-31 08:52:17.266  8165  8165 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-31 08:52:17.267  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 08:52:17.267  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 08:52:17.267  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 08:52:17.267  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:17.267  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 08:52:17.267  6648  6772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:17.276  8165  8165 V LGMDMManager: Create singleton instance
,08-31 08:52:17.280  6648  8212 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: My test thread name)
08-31 08:52:17.281  6648  8212 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: My test thread name)
08-31 08:52:17.281  6648  8212 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 08:52:17.288  6648  8214 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: My test thread name)
08-31 08:52:17.288  6648  8214 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 872, thread name: My test thread name)
08-31 08:52:17.288  6648  8214 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 872, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 08:52:17.290  6648  6772 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-31 08:52:17.290  6648  6772 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 08:52:17.290  6648  6772 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 08:52:17.290  6648  6772 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 08:52:17.290  6648  6772 D com.test.thalitest.ThaliTestRunner: Total duration: 22946 ms
08-31 08:52:17.291  6648  6772 I jxcore-log: *Native tests were executed*
08-31 08:52:17.291  6648  6772 I jxcore-log: 
08-31 08:52:17.292  6648  6772 I jxcore-log: Total number of executed tests:  80
08-31 08:52:17.292  6648  6772 I jxcore-log: 
08-31 08:52:17.292  6648  6772 I jxcore-log: Number of passed tests:  80
08-31 08:52:17.292  6648  6772 I jxcore-log: 
08-31 08:52:17.292  6648  6772 I jxcore-log: Number of failed tests:  0
08-31 08:52:17.292  6648  6772 I jxcore-log: 
08-31 08:52:17.292  6648  6772 I jxcore-log: Number of ignored tests:  0
08-31 08:52:17.292  6648  6772 I jxcore-log: 
08-31 08:52:17.293  6648  6772 I jxcore-log: Total duration:  22946
08-31 08:52:17.293  6648  6772 I jxcore-log: 
08-31 08:52:17.293  6648  6772 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 08:52:17.293  6648  6772 I jxcore-log: 
08-31 08:52:17.297  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.297  6648  6772 I jxcore-log: 
08-31 08:52:17.300  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.300  6648  6772 I jxcore-log: 
08-31 08:52:17.304  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.304  6648  6772 I jxcore-log: 
,08-31 08:52:17.305  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.305  6648  6772 I jxcore-log: 
08-31 08:52:17.306  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.306  6648  6772 I jxcore-log: 
08-31 08:52:17.308  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.308  6648  6772 I jxcore-log: 
08-31 08:52:17.311  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:52:17.311  6648  6772 I jxcore-log: 
08-31 08:52:17.311  6648  6648 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 08:52:17.314  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.314  6648  6772 I jxcore-log: 
08-31 08:52:17.315  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.315  6648  6772 I jxcore-log: 
08-31 08:52:17.316  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:52:17.316  6648  6772 I jxcore-log: 
08-31 08:52:17.317  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:52:17.317  6648  6772 I jxcore-log: 
08-31 08:52:17.318  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:52:17.318  6648  6772 I jxcore-log: 
08-31 08:52:17.319  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.319  6648  6772 I jxcore-log: 
08-31 08:52:17.320  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.320  6648  6772 I jxcore-log: 
08-31 08:52:17.321  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.321  6648  6772 I jxcore-log: 
08-31 08:52:17.322  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.322  6648  6772 I jxcore-log: 
08-31 08:52:17.323  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.323  6648  6772 I jxcore-log: 
08-31 08:52:17.324  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.324  6648  6772 I jxcore-log: 
08-31 08:52:17.324  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.324  6648  6772 I jxcore-log: 
08-31 08:52:17.325  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:17.325  6648  6772 I jxcore-log: 
08-31 08:52:17.326  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:17.326  6648  6772 I jxcore-log: 
08-31 08:52:17.327  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:17.327  6648  6772 I jxcore-log: 
08-31 08:52:17.327  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.327  6648  6772 I jxcore-log: 
,08-31 08:52:17.328  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.328  6648  6772 I jxcore-log: 
08-31 08:52:17.329  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.329  6648  6772 I jxcore-log: 
08-31 08:52:17.330  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.330  6648  6772 I jxcore-log: 
08-31 08:52:17.330  6648  6772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:17.330  6648  6772 I jxcore-log: 
08-31 08:52:17.342  8165  8165 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-31 08:52:17.391  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:17.394  8165  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 08:52:17.399  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 08:52:17.402  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:17.439  1069  1935 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8238 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-31 08:52:17.439  1069  1935 I ActivityManager: Killing 7197:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-31 08:52:17.492  1069  8186 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 08:52:17.494  1069  8186 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 08:52:17.494  1069  8186 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 08:52:17.494  1069  8186 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,08-31 08:52:17.494  1069  8186 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 08:52:17.494  1069  8186 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 08:52:17.494  1069  8186 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 08:52:17.494  1069  8186 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 08:52:17.495  1069  8186 D DhcpStateMachine: RunningState
08-31 08:52:17.503  8165  8228 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-31 08:52:17.561  8225  8225 D AndroidRuntime: 
08-31 08:52:17.561  8225  8225 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 08:52:17.563  8225  8225 D AndroidRuntime: CheckJNI is OFF
,08-31 08:52:17.708  1069  1931 W libprocessgroup: failed to open /acct/uid_10093/pid_7197/cgroup.procs: No such file or directory
,08-31 08:52:17.725  8225  8225 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 08:52:17.748  1069  1135 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-31 08:52:17.748  1069  1135 I ActivityManager: Killing 6648:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-31 08:52:17.813  1069  1885 I WindowState: WIN DEATH: Window{1b838d74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 08:52:17.814  1069  1385 D WifiService: Client connection lost with reason: 4
,08-31 08:52:17.823  1069  1885 D InputDispatcher: Window went away: Window{1b838d74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 08:52:17.869  8238  8238 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 08:52:17.961  1069  1135 I ActivityManager:   Force finishing activity ActivityRecord{28499cb9 u0 com.test.thalitest/.MainActivity t6}
,08-31 08:52:18.012   342   355 E GBMv2   : DFP En is all cleared set to be enabled
,08-31 08:52:18.020  1069  1931 W ActivityManager: Spurious death for ProcessRecord{31e968fb 6648:com.test.thalitest/u0a118}, curProc for 6648: null
08-31 08:52:18.021  1069  1253 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-31 08:52:18.026  1069  1253 I ActivityManager:   Force finishing activity ActivityRecord{28499cb9 u0 com.test.thalitest/.MainActivity t6 f}
,08-31 08:52:18.027  1069  1253 W ActivityManager: Duplicate finish request for ActivityRecord{28499cb9 u0 com.test.thalitest/.MainActivity t6 f}
,08-31 08:52:18.048  2015  2015 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-31 08:52:18.050  1922  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-31 08:52:18.051  1922  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3520784e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 08:52:18.053  1922  1939 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 08:52:18.053  1922  1939 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1dcf2d6f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 08:52:18.056  2015  2015 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-31 08:52:18.063  8238  8238 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-31 08:52:18.067  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-31 08:52:18.077  1977  1977 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-31 08:52:18.078  1069  1365 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 08:52:18.083  3771  3771 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-31 08:52:18.087  2015  2015 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-31 08:52:18.090  7748  7748 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-31 08:52:18.090  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-31 08:52:18.093  2015  2108 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-31 08:52:18.096  2479  2644 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 08:52:18.120  1069  1084 V SIM_STK : Menu title from STK is T-Mobile
,08-31 08:52:18.139  1069  1131 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-31 08:52:18.163  1069  1069 D administrator: Handling package changes for user 0
08-31 08:52:18.165  4492  4492 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-31 08:52:18.166  4492  4492 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 08:52:18.166  4492  4492 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 08:52:18.166  4492  4492 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 08:52:18.166  4492  4492 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 08:52:18.166  4492  4492 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 08:52:18.166  4492  4492 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:18.166  4492  4492 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:52:18.167  4492  4492 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:18.167  4492  4492 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:18.167  2015  2015 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-31 08:52:18.167  4492  4492 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:52:18.167  4492  4492 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:52:18.167  1887  1887 D ActionManagerService: notifyUserLog: 1000003
08-31 08:52:18.168  3771  4484 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-31 08:52:18.177  4610  4610 I art     : Explicit concurrent mark sweep GC freed 8410(477KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 472us total 135.478ms
,08-31 08:52:18.190  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-31 08:52:18.190  2015  2015 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-31 08:52:18.195  2015  2015 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-31 08:52:18.195  1586  1645 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 08:52:18.195  1586  1645 D KeyguardModel: createShortcutInfo...
08-31 08:52:18.202  1586  1645 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 08:52:18.202  2015  2015 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 08:52:18.202  1586  1645 D KeyguardModel: createShortcutInfo...
,08-31 08:52:18.208  1586  1645 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 08:52:18.208  1586  1645 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:52:18.209  1586  1645 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 08:52:18.210  1586  1645 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 08:52:18.214  1586  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 08:52:18.214  1586  1645 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 08:52:18.215  1586  1645 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 08:52:18.215  1586  1645 D KeyguardModel: createShortcutInfo...
,08-31 08:52:18.220  2015  2015 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-31 08:52:18.220  1887  1887 D ActionManagerService: notifyUserLog: 1000004
08-31 08:52:18.220  8238  8238 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-31 08:52:18.220  1586  1645 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 08:52:18.220  1586  1645 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 08:52:18.221  3771  4484 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-31 08:52:18.221  3771  3787 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 08:52:18.222  1586  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 08:52:18.222  1586  1645 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 08:52:18.223  1586  1645 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 08:52:18.223  1586  1645 D KeyguardModel: createShortcutInfo...
08-31 08:52:18.225  8238  8238 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 08:52:18.225  8238  8238 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 08:52:18.225  8238  8238 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 08:52:18.226  8238  8238 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , expire_time: 0
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , display: false
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , animation: false }
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , expire_time: 0
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , display: false
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , animation: false }
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , expire_time: 0
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , display: false
08-31 08:52:18.227  2015  2015 I GBoardWebViewUtils: , animation: false }
08-31 08:52:18.230  2015  8286 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 08:52:18.234  8238  8238 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 08:52:18.238  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 08:52:18.238  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-31 08:52:18.238  8238  8238 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 08:52:18.248  1586  1645 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:52:18.248  1586  1645 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 08:52:18.248  1586  1645 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 08:52:18.249  1586  1645 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 08:52:18.250  8165  8228 D LgDataFeature: LgDataFeature() Constructor: none
08-31 08:52:18.250  8165  8228 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 08:52:18.252  1586  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 08:52:18.252  1586  1645 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 08:52:18.253  1851  1851 D SplitUIManager: split_name #11 / not available #0
08-31 08:52:18.254  1851  1851 D SplitUIService: removed split : 
08-31 08:52:18.259  1586  1645 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 08:52:18.259  1586  1645 D KeyguardModel: createShortcutInfo...
08-31 08:52:18.261  1069  1904 V SIM_STK : Menu title from STK is T-Mobile
08-31 08:52:18.261  1069  1904 V SIM_STK : Menu title from STK is T-Mobile
,08-31 08:52:18.269  2015  2015 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 08:52:18.270  2015  2015 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-31 08:52:18.270  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-31 08:52:18.270  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 08:52:18.281  1586  1645 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 08:52:18.281  1586  1645 D KeyguardModel: createShortcutInfo...
,08-31 08:52:18.293  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.300  1586  1645 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 08:52:18.300  1586  1645 D KeyguardModel: createShortcutInfo...
,08-31 08:52:18.305  1586  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 08:52:18.305  1586  1645 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 08:52:18.309  1586  1645 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 08:52:18.309  1586  1645 D KeyguardModel: createShortcutInfo...
08-31 08:52:18.310  1069  1976 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 08:52:18.311  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 08:52:18.311  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 08:52:18.311  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 08:52:18.311  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 08:52:18.311  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 08:52:18.311  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 08:52:18.312  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 08:52:18.312  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 08:52:18.312  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 08:52:18.312  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 08:52:18.312  7748  7748 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-31 08:52:18.321  1586  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 08:52:18.321  1586  1645 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 08:52:18.325  1586  1645 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,08-31 08:52:18.325  1586  1645 D KeyguardModel: createShortcutInfo...
08-31 08:52:18.327  1851  1851 D SplitUIManager: split_name #11 / not available #0
08-31 08:52:18.327  1851  1851 I SplitUIService: split app #11
08-31 08:52:18.328  1586  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 08:52:18.328  1586  1645 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 08:52:18.329  1586  1645 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 08:52:18.329  1586  1645 D KeyguardModel: createShortcutInfo...
08-31 08:52:18.340  1069  1084 V SIM_STK : Menu title from STK is T-Mobile
08-31 08:52:18.342  1069  1069 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-31 08:52:18.342  1069  1069 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 08:52:18.343  1069  1069 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 08:52:18.344  1069  1561 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-31 08:52:18.352  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.353  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-31 08:52:18.353  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 08:52:18.360  2015  2030 I art     : Background sticky concurrent mark sweep GC freed 2778(152KB) AllocSpace objects, 3(176KB) LOS objects, 0% free, 80MB/80MB, paused 6.939ms total 14.111ms
,08-31 08:52:18.378  8238  8238 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 08:52:18.382  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-31 08:52:18.384  8238  8238 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 08:52:18.387  8238  8238 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 08:52:18.387  6835  6835 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 08:52:18.388  1069  1253 I art     : Explicit concurrent mark sweep GC freed 80662(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 3.010ms total 332.724ms
08-31 08:52:18.393  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:18.393  8165  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 08:52:18.396   333   414 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-31 08:52:18.397  3190  8292 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-31 08:52:18.404  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 08:52:18.404  8165  8228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-31 08:52:18.408  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.411  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.412  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.412  8238  8238 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 08:52:18.414  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:18.414  8165  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 08:52:18.421  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:18.426  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.430  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.430  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.431  8238  8238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 08:52:18.434  8165  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-31 08:52:18.441  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 08:52:18.441  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 08:52:18.441  6835  6835 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 08:52:18.441  6835  6835 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 08:52:18.442  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 08:52:18.444  8165  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-31 08:52:18.445  6835  6835 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 08:52:18.445  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 08:52:18.445  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 08:52:18.445  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 08:52:18.445  6835  6835 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 08:52:18.445  6835  6835 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 08:52:18.445  6835  6835 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 08:52:18.446  8165  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 08:52:18.446  8165  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 08:52:18.447  8165  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-31 08:52:18.447  8165  8228 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-31 08:52:18.450  8165  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-31 08:52:18.452  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:18.453  8165  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 08:52:18.454  2015  2015 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-31 08:52:18.454  2015  2015 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-31 08:52:18.454  8165  8228 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-31 08:52:18.456  2015  2015 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 08:52:18.458  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 08:52:18.459  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 08:52:18.460  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 08:52:18.460  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 08:52:18.461  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-31 08:52:18.468  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.472  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.472  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.473  8238  8238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 08:52:18.474  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:18.475  8165  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 08:52:18.477  2015  2015 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-31 08:52:18.477  2015  2015 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 08:52:18.477  1069  1375 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:52:18.477  1069  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:52:18.478  1069  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:52:18.478  1069  1166 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{af98d26 u0 com.lge.launcher2/.Launcher t5} time:139631
08-31 08:52:18.478  1069  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 08:52:18.478  1069  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:52:18.478  1069  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 08:52:18.480  1069  1390 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-31 08:52:18.480  1069  1390 D ConnectivityService: identical MTU - not setting
08-31 08:52:18.480  1069  1390 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 08:52:18.480  1069  1390 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 08:52:18.480  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 08:52:18.480  1069  1390 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:18.480  1069  1390 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 08:52:18.482  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 08:52:18.483  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 08:52:18.486  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.489  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.489  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.490  8238  8238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 08:52:18.491  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 08:52:18.492  2015  2015 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 08:52:18.492  2015  2015 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 08:52:18.493  2015  2166 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 08:52:18.493  2015  2166 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-31 08:52:18.494  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:18.494  8165  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 08:52:18.500  2015  2015 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-31 08:52:18.501  8225  8225 D AndroidRuntime: Shutting down VM
,08-31 08:52:18.503  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 08:52:18.504  2559  2559 D [Concierge]Service: onStartCommand(). Type : 8
08-31 08:52:18.504  2559  2559 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-31 08:52:18.507  2015  2015 D [Concierge]WidgetView: change position of spinner
08-31 08:52:18.507  2559  2559 D [Concierge]Service: Update widget ID : 11
08-31 08:52:18.508  2559  2559 D [Concierge]Service: onStartCommand(). Type : 0
08-31 08:52:18.508  2015  2015 I [Concierge]WidgetView: initWebView(). Time : 1472626338508
08-31 08:52:18.508  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.513  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.513  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.513  8238  8238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 08:52:18.515  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:18.516  8165  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 08:52:18.521  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:18.525  2015  2015 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 928024742
08-31 08:52:18.525  2015  2015 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-31 08:52:18.525  2015  2015 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 08:52:18.526  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.528  2015  2015 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3ab4ce26
08-31 08:52:18.528  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-31 08:52:18.529  2015  2015 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 08:52:18.529  2015  2015 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 08:52:18.530  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.530  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.530  8238  8238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 08:52:18.534  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 08:52:18.534  2015  2015 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 08:52:18.534  2015  2015 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 08:52:18.535  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:18.535  2015  2015 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472626227483, New one : 1472626338508
08-31 08:52:18.535  2015  2015 D [Concierge]WidgetView: Unregister all receivers
08-31 08:52:18.535  2015  2015 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 08:52:18.536  8165  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 08:52:18.540  2015  2015 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 08:52:18.541  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 08:52:18.543  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 08:52:18.543  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 08:52:18.544  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 08:52:18.545  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-31 08:52:18.546  2015  2015 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 08:52:18.546  2015  2015 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 08:52:18.547  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:18.553  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.558  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.558  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.562  8238  8238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 08:52:18.563  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 08:52:18.566  8165  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 08:52:18.569  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 08:52:18.572  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.576  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.576  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.576  8238  8238 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 08:52:18.582  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:18.584  2015  2015 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 08:52:18.591  2015  2015 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 08:52:18.591  2015  2015 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-31 08:52:18.595  2015  2015 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 08:52:18.603  8118  8118 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 08:52:18.607  8118  8118 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:52:18.608  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 08:52:18.613  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.616  2015  2015 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29c55f33 time:139769
08-31 08:52:18.618  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.618  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.619  8238  8238 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 08:52:18.619  8238  8238 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 08:52:18.620  8238  8238 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 08:52:18.622  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 08:52:18.624  8118  8118 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 08:52:18.624  8118  8118 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 08:52:18.627  6835  6835 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 08:52:18.631  6835  6835 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 08:52:18.632  1069  1131 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:52:18.635  8238  8238 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 08:52:18.635  8238  8238 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 08:52:18.635  8238  8238 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-31 08:52:18.636  8238  8238 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 08:52:18.636  8238  8238 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 08:52:18.638  1069  1131 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 08:52:18.638  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 08:52:18.639  8165  8165 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-31 08:52:18.641  1799  1799 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-31 08:52:18.643  2015  2015 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 08:52:18.646  2203  2203 I ConfigService: onCreate
08-31 08:52:18.646  2203  2203 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-31 08:52:18.647  1799  1799 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-31 08:52:18.650  2203  2203 I ConfigService: onBind returning update interface
,08-31 08:52:18.652  2203  2203 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-31 08:52:18.652  2203  2203 I ConfigService: onBind returning config service
08-31 08:52:18.660  2203  2203 I ConfigService: onDestroy
08-31 08:52:18.663  1799  8302 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-31 08:52:18.678  5957  8308 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-31 08:52:18.695  1799  8309 I PeopleContactsSync: CP2 sync disabled
,08-31 08:52:18.697  1799  4763 I Icing   : doRemovePackageData com.test.thalitest
08-31 08:52:18.700  7018  7018 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-31 08:52:18.712  2320  8310 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 08:52:18.737  1069  2009 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8313 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 08:52:18.768  1069  1253 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8331 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 08:52:18.771  2015  2015 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-31 08:52:18.801  2203  2226 I art     : Explicit concurrent mark sweep GC freed 7060(425KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 585us total 18.019ms
08-31 08:52:18.803  1799  8307 W GmsApplication: Using Auth Proxy for data requests.
08-31 08:52:18.807  1799  8307 W GmsApplication: Using Auth Proxy for data requests.
,08-31 08:52:18.815  1799  8307 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:18.815  1799  8307 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: Runtime exception while performing operation
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.databas,e.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:18.815  1799  8307 E ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:52:18.815  8313  8313 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 08:52:18.815  8313  8313 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 08:52:18.816  1799  8307 F ClearPendingState,Op: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:18.816  1799  8307 F ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:52:18.817  8313  8313 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 08:52:18.817  2015  2868 I GBoardtInterface: onReloaded()
08-31 08:52:18.817  8313  8313 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 08:52:18.819  2015  2015 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-31 08:52:18.820  3771  3787 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 08:52:18.823  3771  3786 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: Can't write: system_app_wtf
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 08:52:18.824  1069  8349 E DropBoxManagerService: 	... 5 more
08-31 08:52:18.830  1887  1887 D ActionManagerService: notifyUserLog: 1000001
,08-31 08:52:18.832  3771  4484 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 08:52:18.832  3771  4484 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 08:52:18.833  1069  2014 I ActivityManager: Killing 7254:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:52:18.863  8313  8313 E SQLiteDatabase: 	at com.android.internal.os.ZygoteIni,t.main(ZygoteInit.java:704)
08-31 08:52:18.863  8313  8313 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:18.863  8313  8313 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:18.864  8313  8313 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:18.864  8313  8313 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:52:18.864  8313  8313 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:18.864  8313  8313 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:18.864  8313  8313 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:52:18.864  8313  8313 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:52:18.868  8313  8313 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:52:18.868  8313  8313 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-31 08:52:18.869  8313  8313 E AndroidRuntime: FATAL EXCEPTION: main
08-31 08:52:18.869  8313  8313 E AndroidRuntime: Process: com.lge.email, PID: 8313
08-31 08:52:18.869  8313  8313 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-31 08:52:18.869  8313  8313 E AndroidRuntime: 	... 11 more
08-31 08:52:18.877  1887  1887 D ActionManagerService: notifyUserLog: 1000001
08-31 08:52:18.877  1069  1085 W libprocessgroup: failed to open /acct/uid_10005/pid_7254/cgroup.procs: No such file or directory
08-31 08:52:18.878  3771  4484 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 08:52:18.878  3771  4484 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 08:52:18.878  3771  4484 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-31 08:52:18.878  3771  4484 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0

```
