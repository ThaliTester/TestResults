#### Test 68102130ea857b4_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-28 12:43:19.641  4605  6493 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 156 ms] updated apps [took 156 ms] 
07-28 12:43:19.786  6494  6494 D DocsApplication: Installing DEX configuration.
07-28 12:43:19.805  6494  6494 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-28 12:43:19.809  6494  6494 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1d8b90d com.google.android.apps.docs}
07-28 12:43:19.824  6494  6494 D TAG     : onCreate()
07-28 12:43:19.841  6494  6494 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-28 12:43:19.861  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-28 12:43:19.861  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
--------- beginning of system
07-28 12:43:20.084  1038  1950 I ActivityManager: Killing 5434:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-28 12:43:20.186  1038  2321 W libprocessgroup: failed to open /acct/uid_10005/pid_5434/cgroup.procs: No such file or directory
07-28 12:43:20.435   331   418 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,07-28 12:43:20.438  3246  6521 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-28 12:43:20.640  1840  4741 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-28 12:43:20.670  1840  4741 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-28 12:43:20.730  1840  4741 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
07-28 12:43:20.826  6527  6527 D AndroidRuntime: 
07-28 12:43:20.826  6527  6527 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:43:20.828  6527  6527 D AndroidRuntime: CheckJNI is OFF
07-28 12:43:20.937  6527  6527 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-28 12:43:20.943  1038  2016 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 12:43:20.956  1969  1986 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-28 12:43:20.960  1038  2016 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-28 12:43:20.961  1038  2016 D ActivityManager: setTaskToReturnTo : TaskRecord{9da093d #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 12:43:20.961  1038  2016 D ActivityManager: setTaskToReturnTo : TaskRecord{9da093d #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 12:43:20.962  1038  2016 D WindowStateEx: AppWindowTokenEx init.. 
07-28 12:43:20.963   338   351 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:43:20.986  1038  2016 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6549 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-28 12:43:20.988  6527  6527 D AndroidRuntime: Shutting down VM
07-28 12:43:21.045  1969  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-28 12:43:21.045  1969  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f567319 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 12:43:21.047  1969  3991 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-28 12:43:21.047  1969  3991 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2d36cfde co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 12:43:21.076  6549  6549 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-28 12:43:21.154  6549  6549 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-28 12:43:21.162  6549  6549 I LibraryLoader: Loading: webviewchromium
07-28 12:43:21.165  6549  6549 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7806-7809)
07-28 12:43:21.165  6549  6549 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:43:21.193  6549  6549 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32fa852f}
07-28 12:43:21.196  6549  6549 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:43:21.196  6549  6549 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 12:43:21.208  6549  6549 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 12:43:21.209  6549  6549 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:43:21.224  6549  6549 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-28 12:43:21.224  6549  6549 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-28 12:43:21.225  6549  6549 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-28 12:43:21.229   315   315 V AudioPolicyService: registerClient() client 0xb558a7a0, uid 10118
07-28 12:43:21.235  1038  1120 D BluetoothManagerService: Message: 20
07-28 12:43:21.235  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27c1d3df:true
07-28 12:43:21.241  6549  6549 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:43:21.241  6549  6549 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:43:21.241  6549  6549 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:43:21.241  6549  6549 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:43:21.241  6549  6549 I Adreno-EGL: Remote Branch: 
07-28 12:43:21.241  6549  6549 I Adreno-EGL: Local Patches: 
07-28 12:43:21.241  6549  6549 I Adreno-EGL: Reconstruct Branch: 
07-28 12:43:21.255  6494  6494 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:21.255  6494  6494 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:43:21.329  6549  6578 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-28 12:43:21.331  6549  6549 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-28 12:43:21.347  6549  6549 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:43:21.350  6549  6549 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-28 12:43:21.352  6549  6549 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-28 12:43:21.355  6549  6549 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-28 12:43:21.355  6549  6549 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-28 12:43:21.366  6549  6549 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-28 12:43:21.371  6549  6549 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:43:21.371  6549  6549 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:43:21.400  6105  6105 I LockScreenSettings: New app installed broadcast received ..
07-28 12:43:21.402  6549  6594 D OpenGLRenderer: Render dirty regions requested: true
07-28 12:43:21.402  6549  6594 I OpenGLRenderer: Initialized EGL, version 1.4
07-28 12:43:21.402  6105  6105 I LockScreenSettings: Number of installed packages  1
07-28 12:43:21.407  6549  6594 D OpenGLRenderer: Enabling debug mode 0
07-28 12:43:21.416  6549  6549 D Atlas   : Validating map...
07-28 12:43:21.420  1038  1961 D SplitWindow: check instance of lgWin Window{2049a2f4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 12:43:21.436  6494  6494 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-28 12:43:21.453  6549  6591 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:21.453  6549  6591 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:43:21.477  1038  2016 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:43:21.519  1038  1577 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6611 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:43:21.560  1038  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +515ms (total +596ms)
07-28 12:43:21.560  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d4b532 u0 com.test.thalitest/.MainActivity t40} time:118205
07-28 12:43:21.561  6549  6549 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@32eff9ca time:118206
07-28 12:43:21.568  6611  6611 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-28 12:43:21.569  6611  6611 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
07-28 12:43:21.599  1038  1054 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6632 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-28 12:43:21.600  1038  1054 I ActivityManager: Killing 5842:com.google.android.talk/u0a72 (adj 15): empty #17
07-28 12:43:21.677  6549  6549 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-28 12:43:21.677  6549  6549 I chromium: 
07-28 12:43:21.690  6549  6549 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-28 12:43:21.717  1038  1983 W libprocessgroup: failed to open /acct/uid_10072/pid_5842/cgroup.procs: No such file or directory
07-28 12:43:21.778  6549  6591 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-28 12:43:21.778  6549  6591 I chromium: 
07-28 12:43:21.791  6632  6632 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-28 12:43:21.813  6632  6632 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 12:43:21.816  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-28 12:43:21.854  1038  2058 I ActivityManager: Killing 5658:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-28 12:43:21.878  5628  5628 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-28 12:43:21.878  5628  5628 W System.err: android.os.DeadObjectException
07-28 12:43:21.879  5628  5628 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:43:21.879  5628  5628 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:43:21.879  5628  5628 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-28 12:43:21.879  5628  5628 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-28 12:43:21.879  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:43:21.879  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:43:21.879  5628  5628 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:43:21.879  5628  5628 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:43:21.879  5628  5628 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:21.879  5628  5628 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:21.879  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:21.879  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:21.879  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:21.879  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:21.879  5628  5628 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-28 12:43:21.879  5628  5628 W System.err: android.os.DeadObjectException
07-28 12:43:21.880  5628  5628 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:43:21.880  5628  5628 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:43:21.880  5628  5628 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-28 12:43:21.880  5628  5628 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-28 12:43:21.880  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:43:21.880  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:43:21.880  5628  5628 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:43:21.880  5628  5628 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:43:21.880  5628  5628 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:21.880  5628  5628 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:21.880  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:21.880  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:21.880  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:21.880  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:21.880  5628  5628 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-28 12:43:21.881  5628  5628 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-28 12:43:21.887  6549  6653 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435064832
07-28 12:43:21.902  6549  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 12:43:21.902  6549  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 12:43:21.902  6549  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 12:43:21.902  6549  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 12:43:21.902  6549  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-28 12:43:21.902  6549  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3baf746e added. We now have 1 listener(s)
07-28 12:43:21.967  1038  1992 W libprocessgroup: failed to open /acct/uid_1000/pid_5658/cgroup.procs: No such file or directory
07-28 12:43:21.968  1038  1992 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
07-28 12:43:21.974  1038  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:21.978  5628  5628 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-28 12:43:21.978  5628  5628 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:43:21.979  6549  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-28 12:43:21.981  6549  6653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:21.984  6549  6653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:21.984  6549  6653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-28 12:43:21.993  6549  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4841a5 added. We now have 1 listener(s)
07-28 12:43:21.993  6549  6653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:21.999  1038  1545 D WifiService: New client listening to asynchronous messages
,07-28 12:43:22.003  6549  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:43:22.003  6549  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
07-28 12:43:22.004  6549  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-28 12:43:22.004  6549  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-28 12:43:22.004  6549  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
07-28 12:43:22.040  1038  1054 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6656 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:43:22.041  5628  5628 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:43:22.041  6549  6653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:22.041  1038  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:43:22.042  6549  6653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-28 12:43:22.052  6549  6653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:43:22.052  6549  6653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:22.052  6549  6653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:22.052  6549  6653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:22.052  6549  6653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:22.052  6549  6653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:22.052  6549  6653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:22.052  6549  6653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:22.052  6549  6653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:22.052  6549  6653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-28 12:43:22.053  6549  6653 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:22.054  6549  6653 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:43:22.055  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:22.058  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:22.112  6549  6549 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 12:43:22.119  6656  6656 D UEI.SmartControl: Quickset Services start...
07-28 12:43:22.121  6656  6656 I UEI.SmartControl: Manufacture = LGE
07-28 12:43:22.122  6656  6656 D UEI.SmartControl: Id = LGNevo
07-28 12:43:22.123  6656  6656 D UEI.SmartControl: File observer start...
,07-28 12:43:22.124  6656  6656 E UEI.SmartControl: IR Port is disabled: false
,07-28 12:43:22.124  6656  6656 D UEI.SmartControl: Starting file observer...
07-28 12:43:22.125  6656  6656 D UEI.SmartControl: Extracting JNI libs...
07-28 12:43:22.125  6656  6656 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-28 12:43:22.205  6656  6656 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-28 12:43:22.205  6656  6656 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-28 12:43:22.205  6656  6656 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-28 12:43:22.231  6656  6656 I UEI.SmartControl: --- Selecting new region: 6
07-28 12:43:22.233  6656  6656 I UEI.SmartControl: Model = LG-D855
07-28 12:43:22.234  6656  6656 D UEI.SmartControl: QS Service created
,07-28 12:43:22.238   338   353 E GBMv2   : DFP En is all cleared set to be enabled
07-28 12:43:22.238   338   353 E GBMv2   : Set value is all cleared set the max
07-28 12:43:22.238   338   353 I GBMv2   : DFP Enabled. Ignore VFP set
07-28 12:43:22.244  6656  6656 I UEI.SmartControl: Service initServices...
07-28 12:43:22.247  6656  6656 D UEI.SmartControl: QS start get config
,07-28 12:43:22.280  6656  6656 D UEI.SmartControl: Loading JNI Libs...
,07-28 12:43:22.506  6656  6656 I UEI.SmartControl: Supports setup maps: true
,07-28 12:43:22.509  6656  6656 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:43:22.509  6656  6656 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:43:22.509  6656  6656 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:43:22.510  6656  6656 I UEI.SmartControl: ### init IR Blaster...
07-28 12:43:22.514  6656  6656 D serial_port: Configuring serial port
07-28 12:43:22.518  6656  6656 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:43:22.518  6656  6656 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:43:22.518  6656  6656 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:43:22.518  6656  6656 I UEI.SmartControl: Get version...
,07-28 12:43:22.536  6656  6675 D UEI.SmartControl: serial port data available: 21
,07-28 12:43:22.563  6656  6656 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:43:22.563  6656  6656 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:43:22.563  6656  6656 I UEI.SmartControl: QS saving settings...
,07-28 12:43:22.564  6656  6656 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 12:43:22.582  6656  6675 D UEI.SmartControl: serial port data available: 4
,07-28 12:43:22.629  6656  6681 I UEI.SmartControl: Device manager: loading config....
,07-28 12:43:22.633  6656  6681 D UEI.SmartControl: ----------- loading internal config...
07-28 12:43:22.640  6656  6656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 12:43:22.645  6656  6656 E UEI.SmartControl: Services init done
07-28 12:43:22.645  6656  6656 D UEI.SmartControl: QS Service init finished
,07-28 12:43:22.649  6656  6656 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:43:22.649  6656  6656 D UEI.SmartControl: QS Service version code: 201091
07-28 12:43:22.651  6656  6656 D UEI.SmartControl: Service requested: Control
07-28 12:43:22.652  6656  6681 E UEI.SmartControl: Loading SETTINGS...
07-28 12:43:22.656  1038  2058 I ActivityManager: Killing 5628:com.lge.qremote/u0a112 (adj 15): empty #17
07-28 12:43:22.661  6656  6681 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-28 12:43:22.680  6656  6680 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 12:43:22.680  6656  6680 D UEI.SmartControl: -----service ready thread exits
,07-28 12:43:22.737  1038  1950 W libprocessgroup: failed to open /acct/uid_10112/pid_5628/cgroup.procs: No such file or directory
,07-28 12:43:22.739  6656  6656 D UEI.SmartControl: Internal service binding...
07-28 12:43:23.008  6549  6673 W jxcore-log: Initializing JXcore engine
07-28 12:43:23.008  6549  6673 W jxcore-log: JXcore engine is ready
,07-28 12:43:23.078  6673  6673 W Thread-752: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10358]" dev="sockfs" ino=10358 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-28 12:43:23.078  6673  6673 W Thread-752: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,07-28 12:43:23.078  6673  6673 W Thread-752: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7631]" dev="sockfs" ino=7631 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-28 12:43:23.078  6673  6673 W Thread-752: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-28 12:43:23.078  6673  6673 W Thread-752: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31043]" dev="sockfs" ino=31043 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-28 12:43:23.104  6549  6673 W jxcore-log: Starting JXcore engine
,07-28 12:43:23.212  6549  6673 W jxcore-log: Platform android
07-28 12:43:23.212  6549  6673 W jxcore-log: 
07-28 12:43:23.212  6549  6673 W jxcore-log: Process ARCH arm
07-28 12:43:23.212  6549  6673 W jxcore-log: 
,07-28 12:43:23.406  6549  6673 I jxcore-log: JXcore Cordova bridge is ready!
07-28 12:43:23.406  6549  6673 I jxcore-log: 
07-28 12:43:23.406  6549  6673 W jxcore-log: JXcore engine is started
,07-28 12:43:23.416  6549  6653 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-28 12:43:23.418  6549  6549 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-28 12:43:25.348  6494  6494 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-28 12:43:25.354  1038  1983 I ActivityManager: Killing 6211:com.android.calendar/u0a13 (adj 15): empty #17
,07-28 12:43:25.439  1038  2090 W libprocessgroup: failed to open /acct/uid_10013/pid_6211/cgroup.procs: No such file or directory
,07-28 12:43:26.339  6494  6580 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-28 12:43:27.620  6656  6679 D serial_port: close(fd = 25)
,07-28 12:43:27.625  6656  6679 I UEI.SmartControl: Serial port is closed.
07-28 12:43:27.627  6656  6682 D UEI.SmartControl: Internal timer expired: 1
07-28 12:43:27.628  6656  6682 D UEI.SmartControl: unbind internal service
07-28 12:43:27.630  6656  6656 D UEI.SmartControl: Service.onUnbind: IControl
07-28 12:43:27.631  6656  6656 D UEI.SmartControl: Service.onDestroy
07-28 12:43:27.631  6656  6656 D UEI.SmartControl: Lock is in USE false
07-28 12:43:27.631  6656  6656 D UEI.SmartControl: unbind internal service
07-28 12:43:27.631  6656  6656 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1234454b
07-28 12:43:27.632  6656  6656 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-28 12:43:27.632  6656  6656 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-28 12:43:27.632  6656  6656 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-28 12:43:27.632  6656  6656 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-28 12:43:27.632  6656  6656 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-28 12:43:27.632  6656  6656 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-28 12:43:27.632  6656  6656 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-28 12:43:27.632  6656  6656 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-28 12:43:27.632  6656  6656 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:27.632  6656  6656 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:27.632  6656  6656 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:27.632  6656  6656 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:27.632  6656  6656 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:27.632  6656  6656 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:27.632  6656  6656 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:27.632  6656  6656 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1234454b
07-28 12:43:27.632  6656  6656 I UEI.SmartControl: Serial port is closed.
07-28 12:43:27.632  6656  6656 I UEI.SmartControl: Serial port is closed.
07-28 12:43:27.632  6656  6656 D UEI.SmartControl: Blaster closed
07-28 12:43:27.633  6656  6656 D UEI.SmartControl: Shut down QS...
07-28 12:43:27.633  6656  6656 D UEI.SmartControl: Stopping QS lib
07-28 12:43:27.633  6656  6656 D UEI.SmartControl: QS lib stop result = true
07-28 12:43:27.633  6656  6656 D UEI.SmartControl: Stopped QS lib
07-28 12:43:27.634  6656  6656 D UEI.SmartControl: Stopped file observer...
07-28 12:43:27.634  6656  6656 D UEI.SmartControl: QS shutdown complete
,07-28 12:43:28.822  1840  6401 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-28 12:43:28.825   310  6690 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-28 12:43:28.825   310  6690 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-28 12:43:28.825   310  6690 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-28 12:43:29.013  1840  1840 I ConfigFetchService: fetch service done; releasing wakelock
07-28 12:43:29.015  1840  1840 I ConfigFetchService: stopping self
,07-28 12:43:29.022  2224  2224 I ConfigService: onDestroy
,07-28 12:43:33.935  1038  1105 I ActivityManager: Waited long enough for: ServiceRecord{2155eb21 u0 com.google.android.gms/.wearable.service.WearableService}
,07-28 12:43:34.361  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 12:43:34.361  6549  6673 I jxcore-log: 
,07-28 12:43:34.364  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 12:43:34.364  6549  6673 I jxcore-log: 
07-28 12:43:34.369  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.369  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.369  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.369  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.369  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:34.369  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.369  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.369  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:34.373  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.376  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 12:43:34.376  6549  6673 I jxcore-log: 
07-28 12:43:34.377  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 12:43:34.377  6549  6673 I jxcore-log: 
,07-28 12:43:34.728  6549  6673 D ExecuteNativeTests: Running unit tests
,07-28 12:43:34.809  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:43:34.809  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 added. We now have 2 listener(s),
07-28 12:43:34.809  1038  1604 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
07-28 12:43:34.811  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17",
07-28 12:43:34.811  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:43:34.811  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:34.811  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
07-28 12:43:34.811  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 added. We now have 2 listener(s)
,07-28 12:43:34.811  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:34.811  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,07-28 12:43:34.817  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.819  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.819  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.819  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.819  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.819  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:34.819  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.819  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.819  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:34.821  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.822  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:34.823  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.824  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:34.827  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:43:34.828  6549  6673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:43:34.828  6549  6673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:43:34.829  6549  6673 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-28 12:43:34.830  6549  6673 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:43:34.831  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:43:34.831  6549  6673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:43:34.831  6549  6673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:43:34.831  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.832  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.832  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.833  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.833  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.833  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.833  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:34.833  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 removed from the list
07-28 12:43:34.833  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.833  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 removed from the list
07-28 12:43:34.833  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.833  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.834  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.834  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.835  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.835  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.835  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.835  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.836  6549  6673 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-28 12:43:34.837  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.837  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.837  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.837  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.837  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:34.837  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.837  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.837  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.837  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.837  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.837  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.837  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.837  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.837  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.838  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.838  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.838  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.838  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.841  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:43:34.841  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:43:34.841  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:43:34.841  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:43:34.841  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:43:34.841  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:131,0:1310:1310:1310:1310]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,07-28 12:43:34.842  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:43:34.843  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.843  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.843  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.843  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.843  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.843  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.843  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.843  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.843  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.843  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.843  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:34.843  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.843  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.843  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.844  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.844  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.844  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
07-28 12:43:34.844  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.845  6549  6673 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:43:34.846  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.848  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.848  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.848  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,07-28 12:43:34.848  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.848  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:34.848  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.848  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.848  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:34.849  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.849  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:43:34.850  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
07-28 12:43:34.851  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.851  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:34.851  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:34.852  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-28 12:43:34.852  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.852  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:43:34.854  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:43:34.854  1038  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:34.858  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
07-28 12:43:34.861  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:43:34.863  6549  6673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
07-28 12:43:34.863  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:43:34.864  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.865  6549  6673 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:43:34.865  6549  6673 I io.jxcore.node.ConnectionHelper: start: OK
,07-28 12:43:34.867  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.867  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.867  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.867  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.867  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:34.867  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.867  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.867  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.867  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.867  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:43:34.867  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.868  6549  6673 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:43:34.869  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.871  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.871  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.871  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,07-28 12:43:34.871  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.871  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:34.871  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.871  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.871  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:34.872  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.872  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:43:34.873  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
07-28 12:43:34.874  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.874  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:34.874  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:34.874  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-28 12:43:34.874  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.874  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:43:34.877  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:43:34.877  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.878  6549  6673 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:43:34.878  6549  6673 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:43:34.879  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.879  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.879  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:43:34.879  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.879  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.880  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.880  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.880  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.880  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
,07-28 12:43:34.880  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.880  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.880  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.880  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.880  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.881  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.882  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.882  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-28 12:43:34.882  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.882  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.882  6549  6673 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-28 12:43:34.883  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
07-28 12:43:34.885  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.885  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.885  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.885  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.885  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:34.885  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.885  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,07-28 12:43:34.885  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:34.886  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.886  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:34.887  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:34.888  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.888  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:34.888  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:34.888  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
07-28 12:43:34.888  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.888  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
07-28 12:43:34.891  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:43:34.891  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.892  6549  6673 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:43:34.892  6549  6673 I io.jxcore.node.ConnectionHelper: start: OK
,07-28 12:43:34.892  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.892  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.892  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.893  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:34.893  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.893  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.893  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.893  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.893  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.893  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
,07-28 12:43:34.893  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.893  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.893  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.893  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.894  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.894  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.894  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.894  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,07-28 12:43:34.894  6549  6673 D BluetoothLeScanner: could not find callback wrapper,
07-28 12:43:34.894  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.894  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.894  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
,07-28 12:43:34.895  6549  6673 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-28 12:43:34.895  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.895  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.895  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
07-28 12:43:34.896  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.896  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.896  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.896  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list,
07-28 12:43:34.896  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:43:34.896  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
,07-28 12:43:34.896  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.896  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.896  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.896  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.896  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.898  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:43:34.898  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.898  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.898  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-28 12:43:34.898  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
07-28 12:43:34.898  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.899  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:43:34.899  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:34.899  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.899  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.899  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:43:34.899  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.899  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.899  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
,07-28 12:43:34.899  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.899  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.899  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:43:34.899  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.899  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.899  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.899  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.900  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.900  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.900  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.901  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
07-28 12:43:34.901  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,07-28 12:43:34.901  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.901  6549  6673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 12:43:34.901  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.901  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.901  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.902  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.902  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:34.902  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.902  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.902  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.902  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.902  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.902  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.902  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.902  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.902  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.902  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.902  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.903  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.903  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.903  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:43:34.903  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.903  6549  6673 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 12:43:34.903  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.903  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.903  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:43:34.904  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.904  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.904  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.904  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.904  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,07-28 12:43:34.904  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.904  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.904  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.904  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.904  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.904  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.905  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.905  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.905  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.905  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-28 12:43:34.905  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.905  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.906  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:43:34.906  6549  6673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:43:34.906  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:43:34.906  6549  6673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:43:34.906  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 12:43:34.906  6549  6673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:43:34.906  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.906  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.906  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.907  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.907  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.907  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.907  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.907  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:43:34.907  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.907  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.907  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.907  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.907  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.907  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.908  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.908  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.908  6549  6673 D BluetoothLeScanner: could not find callback wrapper
,07-28 12:43:34.909  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.909  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.909  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.909  6549  6673 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:43:34.909  6549  6673 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:43:34.909  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:43:34.912  6549  6673 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-28 12:43:34.912  6549  6673 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
,07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:43:34.913  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:43:34.915  6549  6673 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 12:43:34.915  6549  6673 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:43:34.915  6549  6673 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 12:43:34.915  6549  6673 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:43:34.916  6549  6673 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:43:34.916  6549  6673 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 12:43:34.916  6549  6673 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:43:34.916  6549  6673 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:43:34.916  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 12:43:34.917  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 12:43:34.918  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 12:43:34.918  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 12:43:34.919  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,07-28 12:43:34.919  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 12:43:34.919  6549  6673 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 12:43:34.919  6549  6673 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:43:34.919  6549  6673 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 12:43:34.919  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.919  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.919  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.919  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:43:34.919  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.919  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.919  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 12:43:34.920  6549  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 816)
07-28 12:43:34.921  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.921  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.921  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.921  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:43:34.921  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.921  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.921  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.921  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.922  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.922  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:43:34.923  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.923  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.923  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.923  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.924  6549  6673 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,07-28 12:43:34.924  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.924  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.924  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.925  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.925  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.925  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.925  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.925  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:43:34.925  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.925  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.925  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.925  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.925  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.925  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.926  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:43:34.926  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.928  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.928  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.928  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.928  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.929  6549  6673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 12:43:34.930  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.930  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.930  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:43:34.931  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.931  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.931  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.931  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.931  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.931  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.931  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.932  6549  6693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 816
07-28 12:43:34.932  6549  6693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 816)
07-28 12:43:34.932  6549  6693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 816),
,07-28 12:43:34.933  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.933  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.933  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.933  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.934  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.934  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.934  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.934  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.934  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.934  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
,07-28 12:43:34.935  6549  6673 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 12:43:34.935  6549  6673 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 12:43:34.935  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:43:34.935  6549  6673 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 12:43:34.935  6549  6673 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:43:34.935  6549  6673 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 12:43:34.937  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:43:34.937  6549  6673 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 12:43:34.937  6549  6673 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:43:34.937  6549  6673 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:43:34.937  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:43:34.937  6549  6673 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 12:43:34.937  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.937  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.937  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.939  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.939  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.939  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.939  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.939  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:43:34.939  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.939  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.939  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.939  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.939  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.939  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.940  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.940  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.940  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.940  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.940  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.940  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.941  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.941  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.941  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.941  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.941  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.941  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.941  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.941  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.941  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.941  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.942  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.942  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.942  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.942  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.942  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.942  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.942  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.942  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.945  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:43:34.945  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.945  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.945  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.945  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.945  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.945  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.945  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.945  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.945  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.945  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.948  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.948  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.949  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.949  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.949  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.949  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.951  6549  6673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 12:43:34.951  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.952  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 12:43:34.952  6549  6673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 12:43:34.952  6549  6673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 12:43:34.953  6549  6549 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 12:43:34.953  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 12:43:34.953  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:43:34.954  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.954  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 12:43:34.954  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 12:43:34.954  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 12:43:34.954  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.954  6549  6673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-28 12:43:34.954  6549  6549 I io.jxcore.node.ConnectionHelper: onConn,ectionManagerStateChanged: NOT_STARTED
07-28 12:43:34.954  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.954  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.954  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:43:34.954  6549  6673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:43:34.954  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:43:34.955  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:43:34.955  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.955  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.955  6549  6673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:43:34.955  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.955  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.956  6549  6673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:43:34.956  6549  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 12:43:34.956  6549  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 12:43:34.958  6549  6549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:43:34.958  6549  6549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:43:34.958  6549  6549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:43:34.958  6549  6549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 12:43:34.958  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.959  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.959  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.959  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.959  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.959  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.959  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.959  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.959  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.959  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.959  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.959  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.959  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.959  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.959  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.960  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.960  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.960  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.960  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.961  6549  6673 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 12:43:34.962  6549  6673 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:43:34.962  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:43:34.964  6549  6673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:43:34.965  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.965  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.965  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.965  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.966  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.966  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.966  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.966  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.966  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.966  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.966  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.966  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.966  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.966  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.967  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.967  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.967  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.967  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.969  1038  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:34.971  1038  2059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:34.976  1038  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:34.978  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.978  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.978  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.979  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.979  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.979  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.979  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.979  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.979  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.979  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.979  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.979  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.979  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.979  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.980  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.980  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.980  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.980  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.981  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.981  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.981  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.982  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.982  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.982  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.982  6549  6673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3102d888 not in the list
07-28 12:43:34.982  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.982  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.982  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.982  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.982  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.982  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.982  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.983  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.983  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.983  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.983  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5fd221 not in the list
07-28 12:43:34.984  6549  6673 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-28 12:43:34.984  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-28 12:43:34.984  6549  6673 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 12:43:34.984  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:43:34.984  6549  6673 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 12:43:34.984  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:43:34.987  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:43:34.987  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-28 12:43:34.988  6549  6673 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-28 12:43:34.988  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:43:34.988  6549  6673 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 12:43:34.988  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:43:34.988  6549  6673 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 12:43:34.988  6549  6673 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-28 12:43:34.989  6549  6673 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 12:43:34.989  6549  6673 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-28 12:43:34.990  6549  6673 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-28 12:43:34.990  6549  6673 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 12:43:34.990  6549  6673 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 12:43:34.991  6549  6673 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-28 12:43:34.992  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:34.992  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc2481e added. We now have 2 listener(s)
07-28 12:43:34.992  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:34.994  6549  6673 D BluetoothAdapter: enable(): BT is already enabled..!
07-28 12:43:34.995  1038  2323 D WifiServiceImplEx: setWifiEnabled: true pid=6549, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:43:34.995  1038  2323 D WifiService: setWifiEnabled: true pid=6549, uid=10118
07-28 12:43:34.995  1038  2323 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:43:34.997  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:34.997  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32e608ff added. We now have 3 listener(s)
07-28 12:43:34.997  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:35.001  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:35.001  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36e9b6cc added. We now have 4 listener(s)
07-28 12:43:35.001  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:35.003  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:35.003  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4fd2d15 added. We now have 5 listener(s)
07-28 12:43:35.003  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:35.005  1038  2323 D WifiServiceImplEx: setWifiEnabled: false pid=6549, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:43:35.006  1038  2323 D WifiService: setWifiEnabled: false pid=6549, uid=10118
07-28 12:43:35.006  1038  2323 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:43:35.016  1038  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:35.016  1038  1577 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@23d12da2 mBinding = false
07-28 12:43:35.017  1038  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:35.018  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:35.018  1038  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:35.018  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:43:35.018  1038  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:35.019  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:43:35.019  1038  1038 D Ulp_jni : JNI:system_update. Event-4
07-28 12:43:35.019  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:35.019  1038  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:43:35.019  1038  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:43:35.019  1038  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:43:35.020  1038  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:43:35.020  1038  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:43:35.025  1038  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:43:35.026  1038  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.026  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.026  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:43:35.026  2647  2647 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:43:35.026  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:43:35.026  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:43:35.027  1038  1540 D WifiNative-wlan0: SET ps 1: returned true
,07-28 12:43:35.027  1038  2799 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.028  1038  1120 D BluetoothManagerService: Message: 2
07-28 12:43:35.030  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:43:35.030  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:43:35.031  1038  1038 D Ulp_jni : JNI:system_update. Event-4
07-28 12:43:35.031  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:35.031  1038  1120 D BluetoothManagerService: Sending off request.
07-28 12:43:35.032  3895  3914 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 12:43:35.032  3895  3977 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 12:43:35.032  3895  3977 D BluetoothAdapterProperties: Setting state to 13
07-28 12:43:35.032  3895  3977 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:43:35.033  3895  3977 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:43:35.033  3895  3977 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:43:35.033  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.033  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:35.033  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:35.033  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:35.033  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:35.033  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:35.033  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:35.033  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:35.033  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:35.033   310   907 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:43:35.034  3895  3982 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:43:35.035  3895  3977 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:43:35.036  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.036  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:35.037  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:35.038  3895  4279 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 12:43:35.038  3895  4279 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:35.038  3895  4279 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 12:43:35.038  3895  4279 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 12:43:35.038  3895  4279 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 12:43:35.038  3895  4279 V BluetoothMapMasInstance: 	at android.bluetooth.Bluet,oothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 12:43:35.038  3895  4279 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 12:43:35.038  3895  4279 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-28 12:43:35.042  3895  4358 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:35.042  3895  3977 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:43:35.043  3895  4360 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-28 12:43:35.043  3895  4280 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:35.045  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 12:43:35.045  3895  4090 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 12:43:35.046  3895  4362 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 12:43:35.047  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 12:43:35.047  3895  4090 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:43:35.048  1038  1120 D BluetoothManagerService: Message: 60
07-28 12:43:35.048  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 12:43:35.048  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-28 12:43:35.050  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.050  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:35.050  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:35.050  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:35.050  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:35.050  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:35.050  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:35.050  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:35.050  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:35.050  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.051  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:35.053  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:35.056  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.056  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:35.056  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:35.056  6549  6549 V io.jxcore.node.ConnectivityMonitor:     ,- is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:35.056  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:35.056  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:35.056  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:35.056  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:35.056  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:35.057  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.057  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:35.058  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:35.066  1038  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 12:43:35.068  1038  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
07-28 12:43:35.074  6549  6692 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,07-28 12:43:35.076  6549  6692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 816)
07-28 12:43:35.084  1038  1105 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6711 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
07-28 12:43:35.088  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:35.089  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:43:35.090  3895  3895 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:35.090  3895  3895 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:43:35.091  3895  3895 V BluetoothMapService: Handler(): got msg=4
07-28 12:43:35.091  3895  3895 D BluetoothMapService: MAP Service closeService in
07-28 12:43:35.091  3895  3895 D BluetoothMapMasInstance: MAP Service shutdown
07-28 12:43:35.091  3895  3895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:43:35.091  3895  3895 V BluetoothMapService: MAP Service closeService out
07-28 12:43:35.092  3895  3895 V BtOppService: Receiver DISABLED_ACTION 
07-28 12:43:35.092  3895  3895 I BtOppRfcommListener: stopping Accept Thread
07-28 12:43:35.092  3895  3895 V BtOppRfcommListener: close mBtServerSocket
07-28 12:43:35.093  3895  3895 V BtOppRfcommListener: waiting for thread to terminate
07-28 12:43:35.094  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.094  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:35.094  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:35.094  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:35.094  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:35.094  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:35.094  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:35.094  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:35.094  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:35.095  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.095  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:35.095  3895  4358 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:43:35.096  3895  3895 V BtOppRfcommListener: done waiting for thread to terminate
07-28 12:43:35.097  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.097  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:35.097  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:35.097  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:35.097  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:35.097  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:35.097  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:35.097  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:35.097  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:35.097  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:3,5.097  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:35.107  1038  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-28 12:43:35.107  1038  1546 D DSQN    : disableDataServiceNotify
07-28 12:43:35.108  1038  1546 D DSQN    : stop dsqn bin
,07-28 12:43:35.111  1038  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-28 12:43:35.111  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:35.111  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:35.111  1038  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:35.112  1038  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-28 12:43:35.112  1038  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-28 12:43:35.112  1038  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-28 12:43:35.112  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:43:35.113  1038  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.113  1038  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.114  1038  2795 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 12:43:35.115  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:43:35.121  1038  1105 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6730 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:43:35.126  3895  3895 V BtOppService: onDestroy
07-28 12:43:35.126  1038  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:35.126  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:43:35.127  1038  1038 D WifiHS20: hidePasspointNotification off =false
07-28 12:43:35.130  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:35.130  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:35.130  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:43:35.130  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:43:35.131  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:43:35.131  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:43:35.131  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:43:35.131  1038  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:43:35.132  1038  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:35.132  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:35.133  1038  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:35.133  1038  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.133  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.133  1038  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@34a1165
07-28 12:43:35.133  1038  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:35.133  1038  1538 D LGWifiP2pService: P2pDisablingState
07-28 12:43:35.133  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:35.133  1038  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.134  1038  1538 D LGWifiP2pService: p2p socket connection lost
07-28 12:43:35.134  1038  1538 D LGWifiP2pService: P2pDisabledState
07-28 12:43:35.134  1038  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:35.134  1038  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:35.134  1038  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-28 12:43:35.134  1038  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:35.134  1038  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:35.135  1038  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:35.135  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-28 12:43:35.136  1038  1038 D WifiHS20: hidePasspointNotification off =false
07-28 12:43:35.136  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:35.136  1038  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:35.137  1038  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,07-28 12:43:35.137  1038  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.137  1038  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.137  1038  1546 D NetworkManagementService: Removing idletimer
07-28 12:43:35.137  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:43:35.137  2647  2647 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:43:35.137  1038  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:35.138  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:43:35.138  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:43:35.138  1038  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-28 12:43:35.138  1038  1540 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:43:35.138   310   907 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:43:35.140  1038  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:43:35.140  1879  1879 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:35.140  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:43:35.140  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:35.140  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:35.140  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:43:35.140  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:43:35.140  1038  1038 D RttService: SCAN_AVAILABLE : 1
07-28 12:43:35.140  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:43:35.140  1969  1969 D WfdsService: WifiP2pState is changed : false
07-28 12:43:35.141  1969  2314 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 12:43:35.141  1969  2314 D WfdsService: Set the WFDS Monitor: false
07-28 12:43:35.141  1038  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.141  1038  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.141  1969  2314 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:43:35.141  1969  2314 D WfdsService: STATE : WfdsDisabledState - enter
07-28 12:43:35.141  1969  2730 D CtrlSupplicant: Received on exit socket, terminate
07-28 12:43:35.141  1969  2730 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 12:43:35.141  1969  2730 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 12:43:35.141  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:43:35.141  1969  2317 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 12:43:35.141  1969  2730 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 12:43:35.142  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:43:35.142  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:43:35.142  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:43:35.143  1969  2314 W WfdsService: DefaultState - msg [9445378] is not handled
07-28 12:43:35.147  1038  1540 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 12:43:35.147  1038  1540 D WifiNative-p2p0: TERMINATE: returned true
07-28 12:43:35.147  1038  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:43:35.147  1038  1540 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:43:35.147  1038  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:43:35.148  1038  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:35.148  1038  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:35.150  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isCon,nectedToProvisioningNetwork: false]
07-28 12:43:35.150  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:35.150  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 12:43:35.150  1038  1038 D WifiHS20: hidePasspointNotification off =false
07-28 12:43:35.150  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:35.150  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:35.150  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,07-28 12:43:35.153  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:35.153  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.153  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:35.153  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:35.153  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:35.153  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:35.153  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:35.153  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:35.153  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:35.153  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:35.153  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 12:43:35.153  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:35.153  1038  1038 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-28 12:43:35.153  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.153  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:35.154  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.154  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:35.154  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:35.154  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:35.154  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:35.154  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:35.154  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:35.154  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:35.154  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:35.155  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:35.155  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:35.184  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:43:35.184  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:35.185  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:35.188  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:35.189  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:35.189  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:35.197  1038  1961 I art     : Explicit concurrent mark sweep GC freed 37677(1923KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.606ms total 137.621ms
,07-28 12:43:35.200  3895  3895 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-28 12:43:35.208  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:43:35.209  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:35.209  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:35.209  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:43:35.209  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:35.210  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:43:35.211  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:35.212  1038  1383 V AlarmManager: RTC_WAKEUP set : Alarm{143a068f type 0 when 1469702614466 com.android.vending} when 1469702614466
07-28 12:43:35.222  6730  6730 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:35.222  6730  6730 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-28 12:43:35.222  6730  6730 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:43:35.222  6730  6730 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-28 12:43:35.223  6730  6730 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:43:35.224  6730  6730 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:43:35.236  2647  2647 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:43:35.236  2647  2647 I wpa_supplicant: monitor socket send errors count : 1
07-28 12:43:35.236  2647  2647 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-2\x00 that cannot receive messages
07-28 12:43:35.237  1038  2699 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,07-28 12:43:35.237  1038  2699 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:43:35.238  1038  2799 D DhcpStateMachine: StoppedState
07-28 12:43:35.238  1038  2799 D DhcpStateMachine: StoppedState{ when=-99ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:35.239  1038  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-28 12:43:35.239  1038  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-28 12:43:35.252  1038  1054 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:43:35.263  6711  6711 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-28 12:43:35.263  6711  6711 W LG Account v2.2: No ProfileInfo entries
07-28 12:43:35.264  6711  6711 I LG Account v2.2: isEnabled: false
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]Country: EU
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]Operator: OPEN
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]Ranking support: false
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]Comfort support: false
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]Accessory: true
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]Health device: true
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]Extra Pedometer: false
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]Blood glucose device: false
07-28 12:43:35.264  6711  6711 I Feature : [Lifetracker]Device Number: 3
,07-28 12:43:35.271  2647  2647 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:43:35.272  2647  2647 W wpa_supplicant: USIM:  scard_deinit function
07-28 12:43:35.272  1038  2699 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 12:43:35.272  1038  2699 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:43:35.272  1038  2699 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:43:35.272  1038  2699 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-28 12:43:35.273  1038  2699 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:43:35.273  1038  2699 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:43:35.273  1038  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=131906
07-28 12:43:35.274  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:35.274  1038  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=131906
07-28 12:43:35.275  1038  1120 D Tethering: InitialState.processMessage what=4
07-28 12:43:35.276  1038  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=131907  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:43:35.276  1038  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=131909  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,07-28 12:43:35.296  6730  6730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-28 12:43:35.303  1038  2090 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6749 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:43:35.306  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:43:35.309  1038  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:35.309  1038  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:35.309  3895  3895 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:43:35.309  3895  3895 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:35.309  1038  1120 D BluetoothManagerService: Message: 20
07-28 12:43:35.309  3895  3895 V BluetoothPbapReceiver: ***********state = 13
,07-28 12:43:35.309  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4aecefa:true
07-28 12:43:35.314  3895  3895 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-28 12:43:35.315  3895  3895 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:35.315  3895  3895 V BluetoothPbapService: state: 13
07-28 12:43:35.315  3895  3895 V BluetoothPbapService: Pbap Service closeService in
07-28 12:43:35.316  2224  2224 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:43:35.316  3895  3895 V BluetoothPbapService: successfully stopped pbap service
07-28 12:43:35.316  3895  3895 V BluetoothPbapService: Pbap Service closeService out
07-28 12:43:35.317  3895  3895 V BluetoothPbapService: Pbap Service onDestroy
07-28 12:43:35.317  3895  3895 V BluetoothPbapService: Pbap Service closeService in
07-28 12:43:35.317  3895  3895 V BluetoothPbapService: Pbap Service closeService out
07-28 12:43:35.317  3895  3895 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-28 12:43:35.322  1038  1120 D BluetoothManagerService: Message: 30
,07-28 12:43:35.325  1038  1120 D BluetoothManagerService: Message: 30
07-28 12:43:35.327  6730  6730 D LocalBluetoothProfileManager: Adding local MAP profile
07-28 12:43:35.328  6730  6730 D BluetoothMap: Create BluetoothMap proxy object
07-28 12:43:35.328  1038  1120 D BluetoothManagerService: Message: 30
07-28 12:43:35.330  1038  1120 D BluetoothManagerService: Message: 30
07-28 12:43:35.332  6730  6730 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-28 12:43:35.332  6730  6730 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-28 12:43:35.340  6730  6730 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-28 12:43:35.341  6730  6730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-28 12:43:35.347  6730  6730 D DockEventReceiver: finishStartingService: stopping service
07-28 12:43:35.352  6730  6730 D BluetoothInputDevice: Proxy object connected
,07-28 12:43:35.353  6730  6730 D HidProfile: Bluetooth service connected
07-28 12:43:35.353  6730  6730 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:43:35.354  6730  6730 D PanProfile: Bluetooth service connected
07-28 12:43:35.354  6730  6730 D BluetoothMap: Proxy object connected
07-28 12:43:35.354  6730  6730 D MapProfile: Bluetooth service connected
07-28 12:43:35.355  6730  6730 D BluetoothMap: getConnectedDevices()
07-28 12:43:35.356  6730  6730 D BluetoothMap: Bluetooth is Not enabled
07-28 12:43:35.356  6730  6730 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 12:43:35.356  2647  2647 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:43:35.356  1038  2699 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-28 12:43:35.356  1038  2699 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-28 12:43:35.356  1038  2699 D WifiMonitor: Disconnecting from the supplicant, no more events
07-28 12:43:35.357  1038  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
07-28 12:43:35.358  6730  6730 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 12:43:35.361  6730  6730 D BluetoothPermissionRequest: onReceive
07-28 12:43:35.362  6730  6730 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-28 12:43:35.367  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:43:35.367  6730  6730 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:43:35.368  1038  1950 I ActivityManager: Killing 6183:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-28 12:43:35.371  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:43:35.371  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:35.406  1038  2059 W libprocessgroup: failed to open /acct/uid_10014/pid_6183/cgroup.procs: No such file or directory
07-28 12:43:35.407  3895  3895 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,07-28 12:43:35.407  3895  3895 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,07-28 12:43:35.407  3895  3895 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-28 12:43:35.409  6067  6067 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
07-28 12:43:35.415  1038  1950 I ActivityManager: Killing 2243:com.lge.music/u0a34 (adj 15): empty #17
07-28 12:43:35.425  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:35.430   315   315 V AudioFlinger: 2243 died, releasing its sessions
07-28 12:43:35.430   315   315 V AudioFlinger:  pid 1879 @ 0
07-28 12:43:35.430   315   315 V AudioFlinger:  pid 3364 @ 1
07-28 12:43:35.430   315   315 V AudioFlinger:  pid 3364 @ 2
07-28 12:43:35.459  6549  6549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-28 12:43:35.469  6730  6730 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:35.469  6730  6730 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:43:35.480  3895  3895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:35.480  3895  3895 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:43:35.482  1038  2058 W libprocessgroup: failed to open /acct/uid_10034/pid_2243/cgroup.procs: No such file or directory
07-28 12:43:35.483  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:43:35.496  3895  3895 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:43:35.496  3895  3895 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:35.497  3895  3895 V BluetoothFtpService: Ftp Service closeService
07-28 12:43:35.497  3895  3895 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,07-28 12:43:35.498  1969  1969 D WfdsService: Supplicant Connection state is changed : false
07-28 12:43:35.498  1969  2314 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,07-28 12:43:35.498  1969  2314 D WfdsService: Set the WFDS Monitor: false
07-28 12:43:35.498  1969  2314 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:43:35.500  1038  1540 D WifiOffDelayIfNotUsed: stopMonitoring
07-28 12:43:35.500  1038  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:43:35.500  1038  1540 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:43:35.500  1038  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:43:35.501  3895  3895 V BluetoothFtpService: successfully stopped ftp service
07-28 12:43:35.501  3895  3895 V BluetoothFtpService: Ftp Service onDestroy
07-28 12:43:35.501  3895  3895 V BluetoothFtpService: Ftp Service closeService
07-28 12:43:35.504  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 12:43:35.504  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:35.506  1038  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 12:43:35.506  1038  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 12:43:35.507  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:43:35.507  3895  3895 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:43:35.508  3895  3895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:43:35.508  3895  3895 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:43:35.508  3895  3895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:35.508  3895  3895 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 12:43:35.508  3895  3895 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:43:35.508  2502  2502 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:35.510  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:35.515  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:35.561  1038  2016 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6778 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-28 12:43:35.561  3895  3895 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:35.561  3895  3895 V BluetoothSapService: state: 13
07-28 12:43:35.562  3895  3895 V BluetoothSapService: Stopping SAP server process
07-28 12:43:35.563  3895  3895 V BluetoothSapService: Sap Service closeSapService in
07-28 12:43:35.563  1038  2016 I ActivityManager: Killing 6405:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-28 12:43:35.563  3895  3895 V BluetoothSapService: Close listen Socket : 
07-28 12:43:35.563  3895  3895 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:43:35.563  3895  3895 V BluetoothSapService: Close sapd  Socket : 
07-28 12:43:35.607  1038  2058 W libprocessgroup: failed to open /acct/uid_10008/pid_6405/cgroup.procs: No such file or directory
07-28 12:43:35.607  3895  3895 V BluetoothSapService: Sap Service closeSapService out
07-28 12:43:35.608  3895  3895 V BluetoothSapService: Sap Service onDestroy
07-28 12:43:35.608  3895  3895 V BluetoothSapService: Sap Service closeSapService in
,07-28 12:43:35.608  3895  3895 V BluetoothSapService: Close listen Socket : 
,07-28 12:43:35.608  3895  3895 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:43:35.608  3895  3895 V BluetoothSapService: Close sapd  Socket : 
07-28 12:43:35.651  6778  6778 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 12:43:35.696  1038  2016 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6795 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:43:35.698  3895  3895 V BluetoothSapService: Sap Service closeSapService out
07-28 12:43:35.700  6778  6778 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,07-28 12:43:35.724   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.159ms total 25.787ms
,07-28 12:43:35.737  6778  6778 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,07-28 12:43:35.738  6778  6778 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-28 12:43:35.738  6778  6778 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-28 12:43:35.739  6778  6778 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-28 12:43:35.739  6778  6778 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-28 12:43:35.741  6778  6778 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-28 12:43:35.746  6778  6778 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-28 12:43:35.752   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 26.469ms
,07-28 12:43:35.753  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:35.759  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:35.772  6795  6795 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:43:35.774   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 639us total 20.283ms
07-28 12:43:35.774  6778  6778 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 12:43:35.777  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:35.782  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:43:35.782  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:43:35.782  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:35.783  6778  6778 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-28 12:43:35.785  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:35.789  6778  6778 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-28 12:43:35.792  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:35.798  1038  1604 I ActivityManager: Killing 5999:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-28 12:43:35.880  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:35.881  1038  2321 W libprocessgroup: failed to open /acct/uid_10011/pid_5999/cgroup.procs: No such file or directory
,07-28 12:43:35.885  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:35.889  6778  6778 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:43:35.896  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:35.904  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:43:35.904  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:43:35.904  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:35.913  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:35.933  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:35.950  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:43:35.951  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:35.955  6778  6778 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:43:36.049  3895  3982 D bt_hci_bdroid: cleanup
07-28 12:43:36.050  3895  4092 I bt_lpm  : LPM is already off!!!
07-28 12:43:36.051  3895  4258 I bt_userial_mct: exiting userial_read_thread
07-28 12:43:36.051  3895  4258 D bt_userial_mct: Leaving userial_evt_read_thread()
,07-28 12:43:36.051  1038  1738 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6818 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
07-28 12:43:36.051  3895  4090 W bt-btif : ag scb idx 1 not allocated
07-28 12:43:36.051  3895  4090 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:36.051  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:36.052  3895  4090 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:36.052  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:36.052  3895  4090 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:36.052  3895  4090 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:43:36.052  3895  4090 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:36.052  3895  4090 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:43:36.052  3895  3982 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-28 12:43:36.052  3895  4092 I bt_vendor: hw_epilog_process
07-28 12:43:36.053  3895  3982 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 12:43:36.053  3895  3982 D bt_userial_mct: userial_close
07-28 12:43:36.053  3895  3982 E bt_userial_mct: pthread_join() FAILED result:3
07-28 12:43:36.053  3895  3982 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,07-28 12:43:36.130  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:43:36.135  3895  3982 D bt_hci_bdroid: set_power 0
07-28 12:43:36.135  3895  3982 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-28 12:43:36.135  3895  3982 I bt_vendor: bluetooth satus is on
07-28 12:43:36.135  3895  3982 I bt_vendor: bt-vendor : resetting BT status
07-28 12:43:36.135  3895  3982 I bt_vendor: Starting hciattach daemon
07-28 12:43:36.135  3895  3982 I bt_vendor: try to set false
07-28 12:43:36.136  3895  3982 I bt_vendor: Starting hciattach daemon
07-28 12:43:36.136  3895  3982 I bt_vendor: try to set false
07-28 12:43:36.137  3895  3982 I bt_vendor: cleanup
,07-28 12:43:36.138  3895  4090 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:43:36.138  3895  3982 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:43:36.138  3895  3982 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 12:43:36.139  3895  3977 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:43:36.144  3895  3895 D HeadsetService: Received stop request...Stopping profile...
07-28 12:43:36.145  3895  3895 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:43:36.145  3895  3895 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:43:36.145  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a99373c
07-28 12:43:36.146  3895  4011 D HeadsetStateMachine: Exit Disconnected: -1
07-28 12:43:36.147  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:36.148  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 12:43:36.148  1879  1879 D BluetoothHeadset: Proxy object disconnected
,07-28 12:43:36.150  1038  1038 D BluetoothHeadset: Proxy object disconnected
07-28 12:43:36.150  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 12:43:36.152  3895  3895 D A2dpService: Received stop request...Stopping profile...
07-28 12:43:36.152  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 12:43:36.152  3895  4067 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:43:36.153  3895  3895 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-28 12:43:36.153  3895  3977 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:43:36.154  3895  3895 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-28 12:43:36.154  3895  3895 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:43:36.154  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a99373c
07-28 12:43:36.155  1038  1038 D BluetoothA2dp: Proxy object disconnected
07-28 12:43:36.155  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 12:43:36.156  3895  3895 D HidService: Received stop request...Stopping profile...
07-28 12:43:36.156  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a99373c
07-28 12:43:36.158  3895  3895 D HealthService: Received stop request...Stopping profile...
07-28 12:43:36.158  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a99373c
07-28 12:43:36.161  6818  6838 W FormManager: Network not available. Please check & try again.
,07-28 12:43:36.162  3895  3895 D PanService: Received stop request...Stopping profile...
07-28 12:43:36.163  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a99373c
07-28 12:43:36.164  3895  3895 D HeadsetStateMachine: Unbinding service...
07-28 12:43:36.165  3895  3895 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:43:36.165  3895  3895 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:43:36.165  3895  3895 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,07-28 12:43:36.165  3895  3895 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:43:36.165  3895  3895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:43:36.165  3895  3895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:43:36.165  3895  3895 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:43:36.165  3895  3895 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:43:36.166  3895  3895 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:43:36.166  3895  3895 D BtGatt.GattService: stop()
07-28 12:43:36.166  3895  3895 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:43:36.167  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a99373c
07-28 12:43:36.168  3895  3895 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:43:36.168  3895  3895 D BluetoothMapService: stop()
07-28 12:43:36.168  3895  3895 D BluetoothMapEmailAppObserver: deinitObservers()
07-28 12:43:36.168  3895  3895 D BluetoothMapEmailAppObserver: removeReceiver()
07-28 12:43:36.169  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a99373c
07-28 12:43:36.169  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:36.170  3895  3895 I BluetoothA2dpServiceJni: cleanupNative
07-28 12:43:36.170  3895  4068 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:43:36.171  3895  3895 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:43:36.171  3895  3895 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:43:36.171  3895  3895 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:43:36.171  3895  3895 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:43:36.171  3895  3895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:43:36.171  3895  3895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:43:36.171  3895  3895 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:43:36.171  3895  3895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:43:36.171  3895  3895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:43:36.173  3895  3895 V BluetoothMapService: Handler(): got msg=4
07-28 12:43:36.173  3895  3895 D BluetoothMapService: MAP Service closeService in
07-28 12:43:36.173  3895  3895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:43:36.173  3895  3895 V BluetoothMapService: MAP Service closeService out
07-28 12:43:36.173  3895  3895 D BluetoothMapService: cleanup()
07-28 12:43:36.173  6730  6730 D BluetoothInputDevice: Proxy object disconnected
07-28 12:43:36.173  3895  3895 D BluetoothMapService: MAP Service closeService in
07-28 12:43:36.173  3895  3895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:43:36.173  3895  3895 V BluetoothMapService: MAP Service closeService out
07-28 12:43:36.173  3895  3977 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:43:36.173  6730  6730 D HidProfile: Bluetooth service disconnected
07-28 12:43:36.173  3895  3977 D BluetoothAdapterProperties: Setting state to 10
07-28 12:43:36.173  3895  3977 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:43:36.173  6730  6730 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:43:36.173  6730  6730 D PanProfile: Bluetooth service disconnected
07-28 12:43:36.174  6730  6730 D BluetoothMap: Proxy object disconnected
07-28 12:43:36.174  6730  6730 D MapProfile: Bluetooth service disconnected
07-28 12:43:36.175  3895  3977 I BluetoothAdapterState: Entering OffState
,07-28 12:43:36.178  1038  1120 D BluetoothManagerService: Message: 60
07-28 12:43:36.178  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 12:43:36.178  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-28 12:43:36.179  6730  6745 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:43:36.179  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:43:36.181  6730  6746 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:43:36.182  6730  6745 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:43:36.183  6730  6746 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:43:36.184  6818  6839 V FormManager: Network unavailable.
07-28 12:43:36.184  1879  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:43:36.185  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:43:36.186  1879  1895 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:43:36.190  1879  2570 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 12:43:36.191  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 12:43:36.191  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 12:43:36.193  6818  6839 V FormManager: Network unavailable.
07-28 12:43:36.194  1038  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 12:43:36.194  1038  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-28 12:43:36.194  1038  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@23d12da2 mBinding = false
07-28 12:43:36.194  1038  1120 D BluetoothManagerService: Sending unbind request.
07-28 12:43:36.195  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-28 12:43:36.197  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:36.197  1969  2177 D LGBluetoothAPIService: Message: 2
07-28 12:43:36.197  1969  2177 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@176055bf mBinding = false
07-28 12:43:36.197  1969  2177 D LGBluetoothAPIService: Sending unbind request.
07-28 12:43:36.201  3895  3982 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:43:36.201  3895  3895 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:43:36.201  3895  3895 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:43:36.202  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:43:36.202  3895  3895 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:43:36.202  3895  3895 I art     : --- WEIRD: removing null entry 246
07-28 12:43:36.202  3895  3895 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-28 12:43:36.202  3895  3895 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,07-28 12:43:36.204  3895  3895 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-28 12:43:36.206  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:36.207  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:36.208  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:43:36.208  1605  1605 D BluetoothAdapter: 958696038: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:36.208  1605  1605 D BluetoothAdapter: 958696038: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:36.208  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:43:36.208  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:43:36.208  6730  6730 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:43:36.209  3895  3895 I art     : System.exit called, status: 0
07-28 12:43:36.209  3895  3895 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:43:36.211  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:43:36.222  6730  6730 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:43:36.222  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:43:36.222  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:43:36.222  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:43:36.222  6730  6730 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:43:36.222  6730  6730 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:43:36.223  6730  6730 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:43:36.224  6730  6730 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 12:43:36.224  6730  6730 D LGBluetoothEventManager: [BTUI] clear device connection state
,07-28 12:43:36.226  1038  1053 I ActivityManager: Killing 6019:com.android.contacts/u0a19 (adj 15): empty #17
,07-28 12:43:36.228  6730  6730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:43:36.230   315  4021 V AudioFlinger: 3895 died, releasing its sessions
07-28 12:43:36.230   315  4021 V AudioFlinger:  pid 1879 @ 0
07-28 12:43:36.230   315  4021 V AudioFlinger:  pid 3364 @ 1
07-28 12:43:36.230   315  4021 V AudioFlinger:  pid 3364 @ 2
07-28 12:43:36.269  1038  1053 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
07-28 12:43:36.269  1038  1053 W BroadcastQueue: android.os.DeadObjectException
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
07-28 12:43:36.269  1038  1053 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:43:36.276  1038  1053 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,07-28 12:43:36.342  1038  1053 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6849 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-28 12:43:36.345  1038  1738 W ActivityManager: Spurious death for ProcessRecord{1d403d8 6849:com.android.bluetooth/1002}, curProc for 3895: null
07-28 12:43:36.348  1038  2059 W libprocessgroup: failed to open /acct/uid_10019/pid_6019/cgroup.procs: No such file or directory
07-28 12:43:36.349  6730  6730 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-28 12:43:36.355  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:43:36.356  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-28 12:43:36.358  6730  6730 D DockEventReceiver: finishStartingService: stopping service
07-28 12:43:36.360  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:36.367  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:43:36.374  4338  6867 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:43:36.380  4338  6868 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:43:36.380  4338  6868 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 12:43:36.386  6749  6749 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 12:43:36.387  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,07-28 12:43:36.387  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:36.393  6818  6870 W FormManager: Network not available. Please check & try again.
07-28 12:43:36.394  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:36.401  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:36.418  6818  6871 V FormManager: Network unavailable.
,07-28 12:43:36.423  6849  6849 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-28 12:43:36.424  6849  6849 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:43:36.424  6849  6849 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 12:43:36.425  6849  6849 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 12:43:36.427  6818  6871 V FormManager: Network unavailable.
07-28 12:43:36.434  6778  6778 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,07-28 12:43:36.436  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:43:36.436  6778  6778 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-28 12:43:36.447  6849  6849 D BluetoothAdapterApp: Loading JNI Library
,07-28 12:43:36.478  6778  6778 D LgDataFeature: LgDataFeature() Constructor: none
,07-28 12:43:36.478  6778  6778 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:43:36.484  6849  6849 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d8b90d Instance Count = 1
07-28 12:43:36.487  6778  6778 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-28 12:43:36.488  6778  6778 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-28 12:43:36.488  6778  6778 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-28 12:43:36.488  6778  6778 V SoundPool: doLoad: loading sample sampleID=1
07-28 12:43:36.489  6849  6849 D BluetoothAdapterApp: onCreate
07-28 12:43:36.489  6778  6778 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:43:36.496  6778  6874 V SoundPool: Start decode
07-28 12:43:36.496  6778  6874 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,07-28 12:43:36.497  6656  6656 D UEI.SmartControl: QS Service created
07-28 12:43:36.499   315   315 V MediaPlayerService: decode(22, 10857164, 17813)
07-28 12:43:36.500   315   315 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-28 12:43:36.500   315   315 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-28 12:43:36.500   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-28 12:43:36.500   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-28 12:43:36.500   315   315 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-28 12:43:36.500   315   315 V MediaPlayerService: player type = 3
07-28 12:43:36.500   315   315 V AwesomePlayer: AwesomePlayer create()
07-28 12:43:36.501   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:36.501   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:36.501   315   315 V AwesomePlayer: setAudioSink() 
07-28 12:43:36.501   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:36.501   315   315 V AudioCache: notify(0xb10041c0, 8, 0, 0)
07-28 12:43:36.501   315   315 V AudioCache: ignored
07-28 12:43:36.501   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:36.501   315   315 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
07-28 12:43:36.501   315   315 V AwesomePlayer: setDataSource_l dataSource
07-28 12:43:36.501   315   315 V LGParserOSAL: SniffLGParser start
07-28 12:43:36.502   315   315 V LGParserOSAL: MainType:5, SubType=0
07-28 12:43:36.502   315   315 V LGParserOSAL: #### check Mime : application/ogg
07-28 12:43:36.502   315   315 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-28 12:43:36.502   315   315 E MediaExtractor: Use LGExtractor :application/ogg 
07-28 12:43:36.505  6778  6778 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:43:36.509  6778  6778 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,07-28 12:43:36.509  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:43:36.514  6656  6656 I UEI.SmartControl: Service initServices...
07-28 12:43:36.514  6656  6656 D UEI.SmartControl: QS start get config
07-28 12:43:36.521  6849  6849 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,07-28 12:43:36.521  6849  6849 D ProfileConfigQcom: Adding HeadsetService
07-28 12:43:36.522  6849  6849 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-28 12:43:36.522  6849  6849 D ProfileConfigQcom: Adding A2dpService
07-28 12:43:36.523  6849  6849 D ProfileConfigQcom: [BTUI] HidService is supported
07-28 12:43:36.524  6849  6849 D ProfileConfigQcom: Adding HidService
07-28 12:43:36.525  6849  6849 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 12:43:36.526  6849  6849 D ProfileConfigQcom: Adding HealthService
07-28 12:43:36.526  6849  6849 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-28 12:43:36.527  6849  6849 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 12:43:36.527  6849  6849 D ProfileConfigQcom: Adding PanService
07-28 12:43:36.527  6849  6849 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 12:43:36.528  6849  6849 D ProfileConfigQcom: Adding GattService
07-28 12:43:36.528  6849  6849 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 12:43:36.528  6849  6849 D ProfileConfigQcom: Adding BluetoothMapService
07-28 12:43:36.528  6849  6849 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-28 12:43:36.529  6849  6849 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:43:36.531  6849  6849 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:36.531  6849  6849 V BluetoothPbapReceiver: ***********state = 10
07-28 12:43:36.533  6849  6849 V LGMDMManagerInternal: Create singleton instance
07-28 12:43:36.535  6778  6778 V LGMDMManager: Create singleton instance
07-28 12:43:36.556   315   315 V LGParserOSAL: supported mime: application/ogg
07-28 12:43:36.556   315   315 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-28 12:43:36.556   315   315 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-28 12:43:36.556   315   315 V AwesomePlayer: mBitrate = -1 bits/sec
07-28 12:43:36.556   315   315 V AwesomePlayer: AudioTrack Setting
07-28 12:43:36.556   315   315 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-28 12:43:36.556   315   315 V AwesomePlayer: setAudioSource() 
07-28 12:43:36.556   315   315 V MediaPlayerService: prepare
07-28 12:43:36.556   315   315 V AwesomePlayer: prepareAsync_l() 
07-28 12:43:36.556   315   315 V MediaPlayerService: wait for prepare
07-28 12:43:36.556   315  6876 V AwesomePlayer: onPrepareAsyncEvent() 
07-28 12:43:36.556   315  6876 V AwesomePlayer: initAudioDecoder() 
07-28 12:43:36.556   315  6876 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:43:36.556   315  6876 V AudioSystem: isOffloadSupported()
07-28 12:43:36.556   315  6876 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:43:36.556   315  6876 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:43:36.556   315  6876 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:43:36.556   315  6876 V AwesomePlayer: getUseOffload() = 0 
07-28 12:43:36.556   315  6876 V OMXCodec: OMXCodec::Create
07-28 12:43:36.556   315  6876 V OMXCodec: findMatchingCodecs()
07-28 12:43:36.556   315  6876 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-28 12:43:36.556   315  6876 V OMXCodec: matchingCodecs.size()=1
07-28 12:43:36.556   315  6876 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-28 12:43:36.558   315  6876 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,07-28 12:43:36.558   315  6876 V LGCodecAdapter: LG Codec Adapter start
07-28 12:43:36.558   315  6876 V OMXCodec: OMXCodec Createtor
07-28 12:43:36.558   315  6876 V OMXCodec: setComponentRole
07-28 12:43:36.558   315  6876 V OMXCodec: configureCodec protected=0
07-28 12:43:36.558   315  6876 V LGCodecAdapter: called getLGCodecSpecificData
07-28 12:43:36.558   315  6876 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-28 12:43:36.559   315  6876 V LGCodecOSAL: Called LGconfigureCodecMETA
07-28 12:43:36.559   315  6876 V LGCodecOSAL: Called LGconfigureCodecMSG
07-28 12:43:36.559   315  6876 V LGCodecOSAL: Not support LGCodec
07-28 12:43:36.559   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:43:36.559   315  6876 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-28 12:43:36.559   315  6876 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-28 12:43:36.559   315  6876 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-28 12:43:36.559   315  6876 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:43:36.559   315  6876 V AudioSystem: isOffloadSupported()
07-28 12:43:36.559   315  6876 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:43:36.559   315  6876 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:43:36.559   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-28 12:43:36.559   315  6876 V OMXCodec: init()
07-28 12:43:36.559   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-28 12:43:36.559   315  6876 V OMXCodec: allocateBuffers
07-28 12:43:36.559   315  6876 V OMXCodec: allocateBuffersOnPort portIndex=0
07-28 12:43:36.559   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-28 12:43:36.559   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
07-28 12:43:36.559   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
07-28 12:43:36.559   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on input port
07-28 12:43:36.559   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on input port
07-28 12:43:36.559   315  6876 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:43:36.560   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:43:36.560   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
07-28 12:43:36.560   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
07-28 12:43:36.560   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040ff10 on output port
07-28 12:43:36.560   315  6876 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040ff60 on output port
07-28 12:43:36.560   315  6876 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:43:36.560   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:43:36.560   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:43:36.561   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-28 12:43:36.561   315  6876 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:43:36.561   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-28 12:43:36.561   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-28 12:43:36.561   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-28 12:43:36.561   315,  6876 V OMXCodec: init() mAsyncCompletion wait free! 
07-28 12:43:36.561   315  6876 V AwesomePlayer: finishAsyncPrepare_l() 
07-28 12:43:36.561   315  6876 V AudioCache: notify(0xb10041c0, 5, 0, 0)
07-28 12:43:36.561   315  6876 V AudioCache: ignored
07-28 12:43:36.561   315  6876 V AudioCache: notify(0xb10041c0, 1, 0, 0)
07-28 12:43:36.561   315  6876 V AudioCache: prepared
07-28 12:43:36.562   315   315 V AudioCache: wait - success
07-28 12:43:36.562   315   315 V MediaPlayerService: start
07-28 12:43:36.562   315   315 V AwesomePlayer: play_l() 
07-28 12:43:36.562   315   315 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-28 12:43:36.562   315   315 V AwesomePlayer: createAudioPlayer_l
07-28 12:43:36.562   315   315 V AwesomePlayer: seekAudioIfNecessary_l() 
07-28 12:43:36.562   315   315 V AwesomePlayer: startAudioPlayer_l() 
07-28 12:43:36.562   315   315 D AudioPlayer: start of Playback, useOffload 0
07-28 12:43:36.562   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:43:36.562   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:43:36.564   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-28 12:43:36.564   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-28 12:43:36.564   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-28 12:43:36.564   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-28 12:43:36.564   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-28 12:43:36.564   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:43:36.564   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
07-28 12:43:36.564   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048896
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049616
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049696
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-28 12:43:36.565   315  6878 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:43:36.565   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:43:36.566   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040ff10 on output port
,07-28 12:43:36.566   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
07-28 12:43:36.566   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
07-28 12:43:36.566   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on output port
07-28 12:43:36.566   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-28 12:43:36.566   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-28 12:43:36.567   315   315 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-28 12:43:36.568   315   315 V AudioCache: notify(0xb10041c0, 6, 0, 0)
07-28 12:43:36.568   315   315 V AudioCache: ignored
07-28 12:43:36.568   315   315 V MediaPlayerService: wait for playback complete
,07-28 12:43:36.575   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.575   315  6879 V AudioCache: memcpy(0xaf1f9000, 0xb57db000, 4096)
07-28 12:43:36.576   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.576   315  6879 V AudioCache: memcpy(0xaf1fa000, 0xb57db000, 4096)
07-28 12:43:36.576   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.576   315  6879 V AudioCache: memcpy(0xaf1fb000, 0xb57db000, 4096)
07-28 12:43:36.577   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.577   315  6879 V AudioCache: memcpy(0xaf1fc000, 0xb57db000, 4096)
07-28 12:43:36.577   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.577   315  6879 V AudioCache: memcpy(0xaf1fd000, 0xb57db000, 4096)
07-28 12:43:36.577   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.577   315  6879 V AudioCache: memcpy(0xaf1fe000, 0xb57db000, 4096)
,07-28 12:43:36.577   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.577   315  6879 V AudioCache: memcpy(0xaf1ff000, 0xb57db000, 4096)
07-28 12:43:36.578   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.578   315  6879 V AudioCache: memcpy(0xaf200000, 0xb57db000, 4096)
07-28 12:43:36.578   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.578   315  6879 V AudioCache: memcpy(0xaf201000, 0xb57db000, 4096)
07-28 12:43:36.578   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.578   315  6879 V AudioCache: memcpy(0xaf202000, 0xb57db000, 4096)
07-28 12:43:36.579   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.579   315  6879 V AudioCache: memcpy(0xaf203000, 0xb57db000, 4096)
07-28 12:43:36.579   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.579   315  6879 V AudioCache: memcpy(0xaf204000, 0xb57db000, 4096)
,07-28 12:43:36.583   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.583   315  6879 V AudioCache: memcpy(0xaf205000, 0xb57db000, 4096)
07-28 12:43:36.584   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.584   315  6879 V AudioCache: memcpy(0xaf206000, 0xb57db000, 4096)
07-28 12:43:36.585   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.585   315  6879 V AudioCache: memcpy(0xaf207000, 0xb57db000, 4096)
07-28 12:43:36.585   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.585   315  6879 V AudioCache: memcpy(0xaf208000, 0xb57db000, 4096)
07-28 12:43:36.586   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.586   315  6879 V AudioCache: memcpy(0xaf209000, 0xb57db000, 4096)
07-28 12:43:36.587   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.587   315  6879 V AudioCache: memcpy(0xaf20a000, 0xb57db000, 4096)
07-28 12:43:36.587   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.588   315  6879 V AudioCache: memcpy(0xaf20b000, 0xb57db000, 4096)
07-28 12:43:36.588   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.588   315  6879 V AudioCache: memcpy(0xaf20c000, 0xb57db000, 4096)
07-28 12:43:36.588   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.588   315  6879 V AudioCache: memcpy(0xaf20d000, 0xb57db000, 4096)
07-28 12:43:36.588   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.588   315  6879 V AudioCache: memcpy(0xaf20e000, 0xb57db000, 4096)
07-28 12:43:36.588   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.588   315  6879 V AudioCache: memcpy(0xaf20f000, 0xb57db000, 4096)
07-28 12:43:36.590   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.590   315  6879 V AudioCache: memcpy(0xaf210000, 0xb57db000, 4096)
07-28 12:43:36.591   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.591   315  6879 V AudioCache: memcpy(0xaf211000, 0xb57db000, 4096)
07-28 12:43:36.591   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.591   315  6879 V AudioCache: memcpy(0xaf212000, 0xb57db000, 4096)
07-28 12:43:36.591   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.591   315  6879 V AudioCache: memcpy(0xaf213000, 0xb57db000, 4096)
07-28 12:43:36.593   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.593   315  6879 V AudioCache: memcpy(0xaf214000, 0xb57db000, 4096)
07-28 12:43:36.593   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.593   315  6879 V AudioCache: memcpy(0xaf215000, 0xb57db000, 4096)
07-28 12:43:36.593   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.593   315  6879 V AudioCache: memcpy(0xaf216000, 0xb57db000, 4096)
07-28 12:43:36.593   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.593   315  6879 V AudioCache: memcpy(0xaf217000, 0xb57db000, 4096)
07-28 12:43:36.596   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.596   315  6879 V AudioCache: memcpy(0xaf218000, 0xb57db000, 4096)
07-28 12:43:36.596   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.596   315  6879 V AudioCache: memcpy(0xaf219000, 0xb57db000, 4096)
07-28 12:43:36.597   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.597   315  6879 V AudioCache: memcpy(0xaf21a000, 0xb57db000, 4096)
07-28 12:43:36.597   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.597   315  6879 V AudioCache: memcpy(0xaf21b000, 0xb57db000, 4096)
07-28 12:43:36.597   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.598   315  6879 V AudioCache: memcpy(0xaf21c000, 0xb57db000, 4096)
07-28 12:43:36.598   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.598   315  6879 V AudioCache: memcpy(0xaf21d000, 0xb57db000, 4096)
07-28 12:43:36.599   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.599   315  6879 V AudioCache: memcpy(0xaf21e000, 0xb57db000, 4096)
07-28 12:43:36.599   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.600   315  6879 V AudioCache: memcpy(0xaf21f000, 0xb57db000, 4096)
07-28 12:43:36.600   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.600   315  6879 V AudioCache: memcpy(0xaf220000, 0xb57db000, 4096)
07-28 12:43:36.601   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.601   315  6879 V AudioCache: memcpy(0xaf221000, 0xb57db000, 4096)
07-28 12:43:36.601   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.601   315  6879 V AudioCache: memcpy(0xaf222000, 0xb57db000, 4096)
07-28 12:43:36.602   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.602   315  6879 V AudioCache: memcpy(0xaf223000, 0xb57db000, 4096)
07-28 12:43:36.603   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.603   315  6879 V AudioCache: memcpy(0xaf224000, 0xb57db000, 4096)
07-28 12:43:36.603   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.603   315  6879 V AudioCache: memcpy(0xaf225000, 0xb57db000, 4096)
07-28 12:43:36.604   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.604   315  6879 V AudioCache: memcpy(0xaf226000, 0xb57db000, 4096)
07-28 12:43:36.605   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.605   315  6879 V AudioCache: memcpy(0xaf227000, 0xb57db000, 4096)
07-28 12:43:36.607   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.607   315  6879 V AudioCache: memcpy(0xaf228000, 0xb57db000, 4096)
07-28 12:43:36.608   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.608   315  6879 V AudioCache: memcpy(0xaf229000, 0xb57db000, 4096)
07-28 12:43:36.608   315  6879 V AudioCache: write(0xb57db000, 4096)
07-28 12:43:36.608   315  6879 V AudioCache: memcpy(0xaf22a000, 0xb57db000, 4096)
07-28 12:43:36.609   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-28 12:43:36.609   315  6879 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:43:36.609   315  6879 V AwesomePlayer: postAudioEOS() 
07-28 12:43:36.609   315  6879 V AudioCache: write(0xb57db000, 280)
07-28 12:43:36.609   315  6879 V AudioCache: memcpy(0xaf22b000, 0xb57db000, 280)
07-28 12:43:36.610   315  6876 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-28 12:43:36.610   315  6876 V AwesomePlayer: onStreamDone
07-28 12:43:36.610   315  6876 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-28 12:43:36.610   315  6876 V AudioCache: notify(0xb10041c0, 2, 0, 0)
07-28 12:43:36.610   315  6876 V AudioCache: playback complete
07-28 12:43:36.610   315  6876 V AwesomePlayer: pause_l() 
07-28 12:43:36.610   315  6876 V AudioCache: notify(0xb10041c0, 7, 0, 0)
07-28 12:43:36.610   315  6876 V AudioCache: ignored
07-28 12:43:36.610   315  6876 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:36.610   315   315 V AudioCache: wait - success
07-28 12:43:36.610   315   315 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-28 12:43:36.613  2224  2224 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:43:36.614   315  6876 D AudioPlayer: Pause Playback at 1068125
07-28 12:43:36.614   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:36.614   315   315 V AudioCache: notify(0xb10041c0, 8, 0, 0)
07-28 12:43:36.614   315   315 V AudioCache: ignored
07-28 12:43:36.614   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:36.614   315   315 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-28 12:43:36.614   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-28 12:43:36.614   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-28 12:43:36.614   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-28 12:43:36.614   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:43:36.614   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:43:36.614   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:43:36.614   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-28 12:43:36.614   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 0
07-28 12:43:36.614   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 0
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 1
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fc40 on port 1
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040ff10 on port 1
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-28 12:43:36.615   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:43:36.615   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-28 12:43:36.615   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-28 12:43:36.616   315  6878 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-28 12:43:36.616   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:43:36.616   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-28 12:43:36.616   315   315 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-28 12:43:36.616  6730  6730 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 12:43:36.616   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-28 12:43:36.617   315   315 D AudioPlayer: AudioPlayer releasing audio source
07-28 12:43:36.617   315   315 D AudioPlayer: AudioPlayer done releasing audio source
07-28 12:43:36.617   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:36.617   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:36.617   315   315 V AwesomePlayer: ~AwesomePlayer call
07-28 12:43:36.617   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:36.617   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:36.617  6778  6874 V SoundPool: close(31)
07-28 12:43:36.617  6778  6874 V SoundPool: pointer = 0x9fe60000, size = 205080, sampleRate = 48000, numChannels = 2
,07-28 12:43:36.631  6730  6730 D BluetoothPermissionRequest: onReceive
07-28 12:43:36.632  6730  6730 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:43:36.633  6730  6730 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-28 12:43:36.634  6730  6730 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:43:36.638  6849  6849 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-28 12:43:36.640  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 12:43:36.640  6849  6849 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:36.641  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-28 12:43:36.642  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6925
07-28 12:43:36.642  6849  6849 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-28 12:43:36.643  6849  6849 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:43:36.643  6849  6849 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:43:36.644  6849  6849 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:36.644  6849  6849 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-28 12:43:36.649  6795  6795 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-28 12:43:36.820  6656  6656 I UEI.SmartControl: Supports setup maps: true
07-28 12:43:36.822  6656  6656 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:43:36.822  6656  6656 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:43:36.822  6656  6656 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:43:36.822  6656  6656 I UEI.SmartControl: ### init IR Blaster...
,07-28 12:43:36.826  6656  6656 D serial_port: Configuring serial port
,07-28 12:43:36.826  6656  6656 E UEI.SmartControl: UEIBLaster setting for 616
,07-28 12:43:36.826  6656  6656 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:43:36.826  6656  6656 I UEI.SmartControl: configuring settings for MAXQ616
,07-28 12:43:36.826  6656  6656 I UEI.SmartControl: Get version...
07-28 12:43:36.844  6656  6881 D UEI.SmartControl: serial port data available: 21
,07-28 12:43:36.871  6656  6656 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:43:36.871  6656  6656 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:43:36.871  6656  6656 I UEI.SmartControl: QS saving settings...
07-28 12:43:36.873  6656  6656 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 12:43:36.893  6656  6881 D UEI.SmartControl: serial port data available: 4
,07-28 12:43:36.924  6656  6887 I UEI.SmartControl: Device manager: loading config....
,07-28 12:43:36.925  6656  6656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-28 12:43:36.927  6656  6656 E UEI.SmartControl: Services init done
07-28 12:43:36.927  6656  6656 D UEI.SmartControl: QS Service init finished
07-28 12:43:36.927  6656  6887 D UEI.SmartControl: ----------- loading internal config...
,07-28 12:43:36.927  6656  6656 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:43:36.927  6656  6656 D UEI.SmartControl: QS Service version code: 201091
07-28 12:43:36.928  6656  6656 D UEI.SmartControl: Service requested: Control
07-28 12:43:36.936  6656  6887 E UEI.SmartControl: Loading SETTINGS...
07-28 12:43:36.938  6656  6656 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 12:43:36.941  6656  6656 D UEI.SmartControl: Internal service binding...
,07-28 12:43:36.951  6778  6778 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 12:43:36.952  6656  6887 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 12:43:36.953  6656  6672 I UEI.SmartControl: ------ IControl API: 11
07-28 12:43:36.953  6656  6672 D UEI.SmartControl: File observer start...
07-28 12:43:36.954  6656  6672 E UEI.SmartControl: IR Port is disabled: false
07-28 12:43:36.955  6656  6672 D UEI.SmartControl: Starting file observer...
07-28 12:43:36.957  6656  6672 I UEI.SmartControl: Registering callback...
07-28 12:43:36.961  6656  6671 I UEI.SmartControl: ------ IControl API: 19
,07-28 12:43:36.962  6656  6671 I UEI.SmartControl: Registering Services Ready callback...
07-28 12:43:36.962  6656  6671 I UEI.SmartControl: Notify client services are ready...
07-28 12:43:36.963  6778  6793 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-28 12:43:36.964  6656  6886 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 12:43:36.964  6778  6872 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-28 12:43:36.964  6778  6872 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-28 12:43:36.965  6656  6886 D UEI.SmartControl: -----service ready thread exits
07-28 12:43:36.965  6778  6794 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-28 12:43:36.965  6778  6778 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-28 12:43:36.966  6778  6872 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-28 12:43:36.966  6778  6872 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-28 12:43:36.966  6778  6778 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-28 12:43:36.967  6656  6672 I UEI.SmartControl: ------ IControl API: 8
07-28 12:43:36.969  6778  6778 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-28 12:43:36.970  6778  6778 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-28 12:43:36.970  6778  6778 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-28 12:43:36.971  6778  6778 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-28 12:43:36.972  6778  6778 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-28 12:43:36.972  6778  6778 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-28 12:43:36.975  6778  6778 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,07-28 12:43:36.978  6778  6778 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
07-28 12:43:36.979  6778  6778 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:43:36.979  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:43:36.980  6778  6778 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:43:36.981  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:43:36.981  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 12:43:36.982  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-28 12:43:36.983  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-28 12:43:36.984  6778  6778 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469702616984]
07-28 12:43:36.987  6778  6778 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,07-28 12:43:36.990  1038  1992 I ActivityManager: Killing 6042:com.android.gallery3d/u0a27 (adj 15): empty #17
07-28 12:43:37.009  6778  6892 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-28 12:43:37.025  1038  1992 I ActivityManager: Killing 6458:com.lge.email/u0a23 (adj 15): empty #18
,07-28 12:43:37.071  1038  2016 W libprocessgroup: failed to open /acct/uid_10027/pid_6042/cgroup.procs: No such file or directory
,07-28 12:43:37.080  1038  1054 W libprocessgroup: failed to open /acct/uid_10023/pid_6458/cgroup.procs: No such file or directory
07-28 12:43:37.095  6778  6778 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,07-28 12:43:37.098  6778  6778 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,07-28 12:43:37.099  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-28 12:43:37.100  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-28 12:43:37.101  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,07-28 12:43:37.102  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-28 12:43:37.103  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,07-28 12:43:37.120  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-28 12:43:38.041  1038  1738 D WifiServiceImplEx: setWifiEnabled: true pid=6549, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-28 12:43:38.043  1038  1738 D WifiService: setWifiEnabled: true pid=6549, uid=10118
,07-28 12:43:38.043  1038  1738 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:43:38.072  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:43:38.072  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:43:38.072  1038  1038 D Ulp_jni : JNI:system_update. Event-4
07-28 12:43:38.074  1038  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-28 12:43:38.074  1038  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 12:43:38.077  1038  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-28 12:43:38.077  1038  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:43:38.077  1038  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 12:43:38.077  1038  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:43:38.077  1038  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-28 12:43:38.077  1038  1540 E WifiHW  : unknown target_country: EU , set to default
07-28 12:43:38.077  1038  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-28 12:43:38.078  1038  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-28 12:43:38.078  1038  1540 I WifiUtil: gEnableBmps=1
07-28 12:43:38.130  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:38.143  1038  1120 D Tethering: MasterInitialState.processMessage what=3
07-28 12:43:38.148  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:38.156  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:38.161  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:38.165  1038  1120 D Tethering: MasterInitialState.processMessage what=3
07-28 12:43:38.174  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:38.179  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:38.180  1038  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:38.182  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:43:38.184  6360  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:43:38.186  5267  5267 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:43:38.205  5267  5267 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 12:43:38.224  2224  2224 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:38.265  1038  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:38.312  1038  2016 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6911 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-28 12:43:38.327  1038  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:38.327  1038  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:38.401  6911  6911 I AppUp4:AppBoxCP: onCreate
07-28 12:43:38.402  6911  6911 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-28 12:43:38.414  6911  6911 I AppUp4:DB:  setFingerPrint start
,07-28 12:43:38.415  6911  6911 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-28 12:43:38.424  6911  6911 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-28 12:43:38.424  6911  6911 I AppUp4:DB:  SDK version = 21
07-28 12:43:38.424  6911  6911 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-28 12:43:38.427  6911  6911 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-28 12:43:38.429  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:43:38.429  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:38.432  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,07-28 12:43:38.433  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:43:38.440  6911  6911 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 12:43:38.484  6911  6911 D LgDataFeature: LgDataFeature() Constructor: none
,07-28 12:43:38.485  6911  6911 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:43:38.493  6911  6911 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@32fa852f
07-28 12:43:38.493  6911  6911 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:43:38.493  6911  6911 D AppUp4:CustFacade: isPhone : true
07-28 12:43:38.494  6911  6911 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:43:38.494  6911  6911 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-28 12:43:38.495  6911  6911 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-28 12:43:38.496  6911  6932 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-28 12:43:38.496  6911  6932 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-28 12:43:38.496  6911  6932 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-28 12:43:38.500  1038  1783 I ActivityManager: Killing 6293:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-28 12:43:38.570  1038  1053 W libprocessgroup: failed to open /acct/uid_10004/pid_6293/cgroup.procs: No such file or directory
,07-28 12:43:38.572  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:38.573  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:43:38.578  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:38.587  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:43:38.600  4338  6934 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:43:38.611  4338  6935 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:38.611  4338  6935 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 12:43:38.674  1038  1983 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6941 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-28 12:43:38.755  6941  6941 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:43:38.756  6941  6941 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:43:38.758  6941  6941 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 12:43:38.758  6941  6941 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:43:38.824  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 12:43:38.834  1038  1120 D Tethering: InitialState.processMessage what=4
07-28 12:43:38.836  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:43:38.844   310   907 D SoftapController: Softap fwReload - Ok
,07-28 12:43:38.845  1038  1540 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (764ms)
07-28 12:43:38.849   310   907 D CommandListener: Setting iface cfg
07-28 12:43:38.849   310   907 D CommandListener: Trying to bring down wlan0
07-28 12:43:38.849   310   907 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:43:38.851  1038  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-28 12:43:38.848  6960  6960 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:38.848  6960  6960 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:43:38.881  6941  6941 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-28 12:43:38.897  6941  6941 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-28 12:43:38.904  6960  6960 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 12:43:38.934  6941  6941 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-28 12:43:38.939  6960  6960 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:43:38.939  6960  6960 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-28 12:43:38.952  1038  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:43:38.952  1038  1540 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:43:38.952  1038  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:43:38.953  1038  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:43:38.953  1038  1540 D WifiMonitor: connecting to supplicant
07-28 12:43:38.954  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-28 12:43:38.955  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,07-28 12:43:38.956  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:38.956  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:38.957  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:38.978  6941  6941 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:38.978  6941  6941 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:43:39.032  6960  6960 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:43:39.087  6960  6960 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-28 12:43:39.088  6941  6941 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 12:43:39.091  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-28 12:43:39.091  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-28 12:43:39.092  1038  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:43:39.093  1038  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-28 12:43:39.093  1038  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:43:39.093  1038  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:43:39.094  1038  6965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-28 12:43:39.094  1038  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:39.094  1038  6965 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:43:39.094  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 12:43:39.094  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 12:43:39.094  1038  6965 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:43:39.094  1038  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:39.094  1038  6965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:43:39.095  1038  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:39.095  1038  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:39.095  1038  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 12:43:39.095  1038  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 12:43:39.096  1038  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 12:43:39.097  1038  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 12:43:39.097  1038  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-28 12:43:39.097  1038  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:43:39.097  1038  1540 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:43:39.097  1038  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:43:39.098  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.098  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.098  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.098  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.098  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:43:39.099  1038  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
07-28 12:43:39.100  1038  1540 D WifiNative-wlan0: SET update_config 1: returned true
07-28 12:43:39.100  1038  1540 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:43:39.100  1038  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 12:43:39.101  1038  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,07-28 12:43:39.102  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:39.102  1969  1969 D WfdService: Waiting for WifiP2p enabling
07-28 12:43:39.107  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 12:43:39.108  1038  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 12:43:39.110  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:39.110  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:39.110  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:39.110  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:39.110  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:39.110  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:39.110  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:39.110  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:39.110  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:39.110  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:39.110  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:39.111  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:39.111  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:39.111  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:39.111  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:39.111  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:39.111  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:39.111  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:39.111  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:39.111  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:39.111  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:39.111  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:39.112  1038  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-28 12:43:39.123  1038  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 12:43:39.123  1038  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:43:39.124  1038  1540 D WifiStateMachine: enableVerboseLogging : level 2
07-28 12:43:39.124  1038  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-28 12:43:39.124  1038  1540 D WifiNative-wlan0: SET device_name g3_global_com: return,ed true
07-28 12:43:39.125  1038  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 12:43:39.125  1038  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-28 12:43:39.125  1038  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,07-28 12:43:39.126  1038  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-28 12:43:39.126  1038  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 12:43:39.126  1038  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 12:43:39.126  1038  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-28 12:43:39.126  1038  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 12:43:39.126  1038  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 12:43:39.127  1038  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 12:43:39.127  1038  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 12:43:39.128  1038  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 12:43:39.128  1038  1540 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:43:39.128  1038  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-28 12:43:39.129  1038  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 12:43:39.129  1038  1540 D WifiNative-HAL: Setting external_sim to 1
07-28 12:43:39.129  1038  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 12:43:39.130  1038  1540 D WifiNative-wlan0: SET external_sim 1: returned true
07-28 12:43:39.130  1038  1540 I WifiNative-HAL: startHal
07-28 12:43:39.130  1038  1540 D wifi    : setting scan oui 0xaf77d6a0
07-28 12:43:39.131  1038  1540 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:43:39.131  1038  1540 I WifiNative-HAL: startHal
07-28 12:43:39.131  1038  1540 D wifi    : setting scan oui 0xaf77d6a0
07-28 12:43:39.131  1038  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 12:43:39.131  1969  1969 D WfdsService: Supplicant Connection state is changed : true
07-28 12:43:39.132  1969  2314 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 12:43:39.132  1969  2314 D WfdsService: Set the WFDS Monitor: true
07-28 12:43:39.132  1969  2314 D WfdsMonitor: WfdsMonitorThread create
07-28 12:43:39.132  1969  2314 D WfdsMonitor: WFDS Monitor is created and started
07-28 12:43:39.132  1969  2314 D WfdsService: WiFi: Supplicant connection re-established
07-28 12:43:39.132  1038  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 12:43:39.132  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 12:43:39.132  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-28 12:43:39.133  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 12:43:39.133  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:43:39.133  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:43:39.134  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:43:39.134  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 12:43:39.134  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 12:43:39.134  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 12:43:39.134  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:43:39.134  1969  6966 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 12:43:39.134  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:43:39.135  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:43:39.135  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:43:39.136  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:43:39.136  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:43:39.136  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 12:43:39.136  6960  6960 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-28 12:43:39.136  1038  1540 D WifiNative-wlan0: DRIVER RX,FILTER-REMOVE 2: returned true
07-28 12:43:39.136  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:43:39.137  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:43:39.137  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:43:39.138  1038  1540 E WifiNative: : [135,769,937 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 12:43:39.138  1038  1540 D WifiNative-wlan0: doBoolean: RECONNECT
07-28 12:43:39.138  1038  1540 D WifiNative-wlan0: RECONNECT: returned true
07-28 12:43:39.138  1038  1540 D WifiNative-wlan0: doString: [STATUS]
,07-28 12:43:39.139  1038  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:43:39.139  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:43:39.139  1038  1540 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:43:39.140  1038  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.141  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:43:39.141  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:43:39.142  1969  6966 E CtrlSupplicant: Succeed to open control connection
07-28 12:43:39.142   310   907 D CommandListener: Setting iface cfg
07-28 12:43:39.142   310   907 D CommandListener: Trying to bring up p2p0
07-28 12:43:39.140  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:43:39.143  1038  1038 D RttService: SCAN_AVAILABLE : 3
07-28 12:43:39.143  1038  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.143  1038  1557 I WifiNative-HAL: startHal
07-28 12:43:39.143  1038  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf77d6a0
07-28 12:43:39.143  1038  1557 D wifi    : failed to get capabilities : -3
07-28 12:43:39.143  1038  1557 E WifiScanningService: could not get scan capabilities
07-28 12:43:39.143  1969  6966 E CtrlSupplicant: Succeed to open monitor connection
07-28 12:43:39.143  1038  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.144  1038  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:43:39.144  1038  1538 D LGWifiP2pService: P2pEnablingState
07-28 12:43:39.144  1038  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.144  1038  1538 D LGWifiP2pService: P2p socket connection successful
07-28 12:43:39.144  1038  1538 D LGWifiP2pService: P2pEnabledState
07-28 12:43:39.144  1038  1538 D LGWifiP2pService: sending p2p connection changed broadcast
07-28 12:43:39.144  1038  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 12:43:39.145  1038  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 12:43:39.145  1038  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 12:43:39.146  1038  1538 D WifiNative-p2p0: SET device_name G3: returned true
07-28 12:43:39.146  1038  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 12:43:39.146  1038  1538 D LGWifiP2pService: before postfix = G3
07-28 12:43:39.146  1038  1538 D WifiServerServiceExt: postfix byte check : 2
07-28 12:43:39.146  1038  1538 D LGWifiP2pService: after postfix = G3
07-28 12:43:39.146  1038  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 12:43:39.147  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-28 12:43:39.147  1038  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 12:43:39.147  1038  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 12:43:39.147  1038  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 12:43:39.147  1038  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 12:43:39.148  1038  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 12:43:39.148  1038  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 12:43:39.148  1038  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-28 12:43:39.148  1038  1538 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 12:43:39.148  1038  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 12:43:39.149  1038  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:43:39.149  1969  1969 D WfdsService: WifiP2pState is changed : true
07-28 12:43:39.150  1969  2314 D WfdsService: Receive the WFDS_ENABLE Method
07-28 12:43:39.150  1969  2314 D WfdsService: Set the WFDS Monitor: true
07-28 12:43:39.150  1969  2314 D WfdsService: Connected to the supplicant for wfds
07-28 12:43:39.150  1969  2314 D WfdsJNI : doCommand: WFDS_SET TRUE
07-28 12:43:39.150  6960  6960 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-28 12:43:39.150  1969  1969 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-28 12:43:39.150  1038  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 12:43:39.150  1969  2314 D WfdsService: selectPreferredScanChannel [36]
07-28 12:43:39.150  1969  2314 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 12:43:39.150  1038  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 12:43:39.151  1969  1969 D WfdsService: isConnected: false
07-28 12:43:39.152  1038  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-28 12:43:39.154  1038  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-28 12:43:39.155  1038  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-28 12:43:39.155  1038  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-28 12:43:39.155  1038  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 12:43:39.155  1969  6966 D WfdsMonitor: Supplicant connection established
07-28 12:43:39.156  6960  6960 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-28 12:43:39.156  1969  2314 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
07-28 12:43:39.156  1038  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-28 12:43:39.156  1038  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-28 12:43:39.157  1038  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 12:43:39.157  1038  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 12:43:39.157  6960  6960 E wpa_supplicant: disconnect_rssi_lvl: -100
,07-28 12:43:39.158  1038  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 12:43:39.158  1038  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 12:43:39.158  1038  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
07-28 12:43:39.158  1038  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 12:43:39.158  1038  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-28 12:43:39.159  1038  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-28 12:43:39.159  1038  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-28 12:43:39.159  1038  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 12:43:39.160  1969  1969 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 12:43:39.160  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-28 12:43:39.160  1969  1969 D WfdsService: Update P2p Interface State: 3
07-28 12:43:39.160  1038  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:43:39.160  3364  3364 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:43:39.160  3364  3364 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:39.160  1038  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:43:39.161  1038  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 12:43:39.161  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-28 12:43:39.162  3364  3364 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:43:39.167  1038  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-28 12:43:39.167  1038  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 12:43:39.168  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:43:39.168  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:39.168  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:43:39.168  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:39.169  1038  6965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:39.169  1038  6965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:39.169  6960  6960 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:43:39.169  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-28 12:43:39.169  1969  6966 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:39.169  1038  6965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:39.169  1038  6965 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.169  1038  6965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.169  1038  6965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.170  1038  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-28 12:43:39.170  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.170  1038  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:43:39.170  1038  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:43:39.171  1038  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:43:39.171  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 12:43:39.171  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 12:43:39.171  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:43:39.172  1038  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 12:43:39.172  1038  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-28 12:43:39.173  1969  6966 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:39.173  1038  6965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:39.173  1038  6965 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.173  1038  6965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.173  1038  6965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.173  1038  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-28 12:43:39.173  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-28 12:43:39.173  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:43:39.173  1038  1540 D WifiNative-wlan0: doBoolean: SCAN
07-28 12:43:39.173  1038  6965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:43:39.173  1038  6965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:43:39.174  1038  1540 D WifiNative-wlan0: SCAN: returned false
07-28 12:43:39.174  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=135807  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:43:39.175  6941  6941 I HubEmail: JNI_OnLoad()
07-28 12:43:39.175  6941  6941 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:43:39.175  6941  6941 I HubEmail: registerNatives()
07-28 12:43:39.175  6941  6941 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:43:39.175  6941  6941 I HubEmail: registerNativeMethods()
07-28 12:43:39.175  6941  6941 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 12:43:39.176  6941  6941 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-28 12:43:39.205  1038  1053 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6972 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
07-28 12:43:39.207  1038  1538 D LGWifiP2pService: InactiveState
07-28 12:43:39.207  1038  1538 D LGWifiP2pService: InactiveState{ when=-49ms what=143376 obj=cz ta,rget=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:43:39.207  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-49ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.208  1038  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-28 12:43:39.208  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:43:39.209  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:39.209  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=135842  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:43:39.210  1038  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:39.210  1038  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:39.210  1038  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:39.211  1038  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:39.211  6960  6960 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:43:39.211  1038  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:39.211  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.212  1038  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 12:43:39.212  1038  1538 D LGWifiP2pService: InactiveState{ when=-43ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.212  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-43ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.212  1038  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.213  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.213  1038  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.213  1038  6965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:43:39.213  1038  6965 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:39.213  1038  6965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:39.213  1038  6965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:39.213  1038  6965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:39.213  1038  6965 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.213  1038  6965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.213  1038  6965 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.214  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.214  1969  6966 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:43:39.214  1969  6966 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:39.214  1969  6966 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:39.214  1038  6965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:39.214  1038  6965 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.214  1038  6965 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.214  1038  6965 ,E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:39.217  1038  1538 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.217  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.217  1038  1538 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.217  1038  1538 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.217  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.217  1038  1538 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.217  1969  2314 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 12:43:39.218  6818  6969 V FormManager: Network unavailable.
07-28 12:43:39.218  6818  6968 W FormManager: Network not available. Please check & try again.
07-28 12:43:39.220  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:39.220  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:39.221  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:39.221  1038  1538 D LGWifiP2pService: InactiveState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.221  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.221  1038  1538 D LGWifiP2pService: DefaultState{ when=-14ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:43:39.225  1038  1038 E WifiServerServiceExt: No p2p device connected
07-28 12:43:39.225  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.226  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.226  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:43:39.226  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:39.226  1038  1038 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 12:43:39.232  6818  6969 V FormManager: Network unavailable.
07-28 12:43:39.235  6941  6971 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.239  1038  1577 I ActivityManager: Killing 6105:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,07-28 12:43:39.290  1038  2323 W libprocessgroup: failed to open /acct/uid_10080/pid_6105/cgroup.procs: No such file or directory
07-28 12:43:39.382  6972  6972 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:39.383  6972  6972 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:43:39.386  6972  6972 D PhoneMonitor: Register our PhoneStateListener
,07-28 12:43:39.408  6972  6972 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-28 12:43:39.413  6972  6972 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-28 12:43:39.443  6972  6972 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-28 12:43:39.446  6972  6972 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,07-28 12:43:39.447  6972  6972 D TelephonyAutoProfiling: [parse] Load xml
07-28 12:43:39.454  6972  6972 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-28 12:43:39.454  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,07-28 12:43:39.454  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-28 12:43:39.454  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-28 12:43:39.454  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,07-28 12:43:39.454  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-28 12:43:39.454  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-28 12:43:39.454  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-28 12:43:39.454  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-28 12:43:39.455  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-28 12:43:39.455  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-28 12:43:39.455  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-28 12:43:39.455  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-28 12:43:39.455  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-28 12:43:39.455  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-28 12:43:39.455  6972  6972 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-28 12:43:39.456  6972  6972 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,07-28 12:43:39.468  6972  6972 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-28 12:43:39.477  1038  1783 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6992 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:39.479  1038  1783 I ActivityManager: Killing 6494:com.google.android.apps.docs/u0a61 (adj 15): empty #17
07-28 12:43:39.537  1038  2059 W libprocessgroup: failed to open /acct/uid_10061/pid_6494/cgroup.procs: No such file or directory
,07-28 12:43:39.683  6960  6960 E wpa_supplicant: USIM:  scard_init function
,07-28 12:43:39.683  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 12:43:39.683  1038  6965 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-28 12:43:39.683  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-28 12:43:39.684  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
07-28 12:43:39.684  1038  6965 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 12:43:39.684  6960  6960 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-28 12:43:39.684  1038  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 12:43:39.684  1038  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 12:43:39.685  1038  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 12:43:39.685  1038  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 12:43:39.686  1038  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-28 12:43:39.686  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:43:39.686  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,07-28 12:43:39.755  1038  1783 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7013 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-28 12:43:39.760  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=136391  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 12:43:39.760  1038  1783 I ActivityManager: Killing 6135:com.google.android.apps.plus/u0a97 (adj 15): empty #17
07-28 12:43:39.806  6960  6960 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-28 12:43:39.810  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-28 12:43:39.810  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-28 12:43:39.810  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-28 12:43:39.810  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-28 12:43:39.811  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:43:39.811  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:43:39.815  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:43:39.815  6960  6960 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:43:39.815  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:43:39.815  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:43:39.815  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 12:43:39.815  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:43:39.815  1038  6965 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:43:39.816  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-28 12:43:39.816  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:43:39.816  1038  6965 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:43:39.816  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:43:39.816  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:43:39.828  1038  1053 W libprocessgroup: failed to open /acct/uid_10097/pid_6135/cgroup.procs: No such file or directory
,07-28 12:43:39.840  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 12:43:39.845  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=136477  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 12:43:39.846  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=136479  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:43:39.848  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=136480  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,07-28 12:43:39.850  1038  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136482
07-28 12:43:39.851  1038  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136483
,07-28 12:43:39.852  1038  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136484
07-28 12:43:39.853  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136486
07-28 12:43:39.855  1038  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=136488
07-28 12:43:39.856  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:39.856  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:39.857  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.857  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.857  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:43:39.859  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=136488  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:43:39.860  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:43:39.867  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.867  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.867  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:43:39.869  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=136501  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:43:39.870  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=136502  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:43:39.870  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=136503  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:43:39.871  1038  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=136504
07-28 12:43:39.871  1038  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=136504
07-28 12:43:39.872  1038  1540 D WifiNative-wlan0: doString: [STATUS]
07-28 12:43:39.873  1038  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:43:39.873  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:43:39.873  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,07-28 12:43:39.874  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.874  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.874  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:43:39.874  1038  1540 I WifiServiceExtension: setVHTCapabilityType  : false
07-28 12:43:39.879  1038  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-28 12:43:39.879  1038  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-28 12:43:39.879  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:39.879  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.880  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-28 12:43:39.882  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:39.882  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:39.884  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:39.886  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.886  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.886  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-28 12:43:39.891  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.891  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:39.891  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:43:39.892  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:39.892  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:39.893  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:39.895  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:39.895  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:39.896  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:39.897  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:39.897  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:39.899  1038  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,07-28 12:43:39.899  1038  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:43:39.899  1038  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:43:39.900  1038  1546 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:43:39.900  1038  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 12:43:39.900  1038  1546 D ConnectivityService: NetworkAgent connected
07-28 12:43:39.900  1038  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:43:39.900  1038  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:43:39.901  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:39.905  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:39.905  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:39.906  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:39.906  1038  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:43:39.906  1038  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:43:39.906  1038  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:43:39.907  1038  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:43:39.907  1038  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:43:39.910  1038  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-28 12:43:39.913   310   907 D CommandListener: Setting iface cfg
07-28 12:43:39.970  1038  1983 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7038 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 12:43:39.972  1038  1983 I ActivityManager: Killing 6611:com.lge.eula/1000 (adj 15): empty #17
,07-28 12:43:40.068  1038  2323 W libprocessgroup: failed to open /acct/uid_1000/pid_6611/cgroup.procs: No such file or directory
,07-28 12:43:40.085  1038  1540 E WifiStateMachine: Start Dhcp Watchdog 2
07-28 12:43:40.085  1038  7036 D DhcpStateMachine: StoppedState
07-28 12:43:40.085  1038  7036 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.086  1038  7036 D DhcpStateMachine: WaitBeforeStartState
07-28 12:43:40.086  1038  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=136718  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:40.086  1038  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=136719  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:40.087  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=136719  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,07-28 12:43:40.088  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,07-28 12:43:40.088  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:40.089  1038  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:40.089  1038  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:40.090  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:40.090  1038  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:40.091  1038  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=136724  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:40.092  1038  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=136724  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:40.092  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=136725  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:40.095  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:91008] from screen [on:0 period:823804863] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:43:40.096  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:823804864] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:43:40.096  1038  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-28 12:43:40.104  1038  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-28 12:43:40.105  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.106  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.106  1038  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 12:43:40.108  1038  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.109  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.109  1038  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.110  1038  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:43:40.111  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
07-28 12:43:40.112  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
07-28 12:43:40.112  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-28 12:43:40.113  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-28 12:43:40.113  1038  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-28 12:43:40.113  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 12:43:40.114  1038  1540 D WifiNative-wlan0: SET ps 0: returned true
07-28 12:43:40.114  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-28 12:43:40.114  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 12:43:40.115  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 12:43:40.116  1038  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26505e7d target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.116  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26505e7d target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.116  1038  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-28 12:43:40.116  1038  7036 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.116  1038  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:43:40.116  1038  7036 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-28 12:43:40.116  1038  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:43:40.117  7038  7038 I art     : Almond Protected OAT
,07-28 12:43:40.117   310   907 D CommandListener: Setting iface cfg
07-28 12:43:40.117   310   907 D CommandListener: Trying to bring up wlan0
07-28 12:43:40.119  1038  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 12:43:40.120  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.121  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.121  1038  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.122  1038  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.122  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.122  1038  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:40.123  1038  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:43:40.123  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:43:40.124  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:43:40.124  1038  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.124  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.124  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:43:40.124  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:43:40.125  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:43:40.125  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 12:43:40.125  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-28 12:43:40.126  1038  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-28 12:43:40.126  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:43:40.133  1038  1538 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.133  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.133  1038  1538 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.135  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:40.135  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:43:40.137  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:43:40.142  1038  1540 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:43:40.143  1038  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 12:43:40.143  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:43:40.144  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:43:40.144  1038  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 12:43:40.145  1038  1546 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:43:40.149  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.149  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:40.150  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:43:40.154  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:40.154  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:40.154  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:43:40.157  1038  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 12:43:40.157  1038  1546 D ConnectivityService: Adding iface wlan0 to network 101
07-28 12:43:40.164  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:40.164  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:40.164  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,07-28 12:43:40.167  1038  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-28 12:43:40.168  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:43:40.170  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-28 12:43:40.171  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:40.171  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:40.171  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:43:40.173  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:43:40.174  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.174  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:40.177  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:40.178  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:40.178  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:40.178  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,07-28 12:43:40.181  7038  7038 D WeatherApplication: removeAccount
07-28 12:43:40.182  7038  7038 D WeatherApplication: Account.length = 0
07-28 12:43:40.182  7038  7038 E WeatherApplication: OPERATOR:OPEN
07-28 12:43:40.182  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.183  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:43:40.183  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:40.187  7038  7038 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:40
07-28 12:43:40.187  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.187  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:43:40.187  1038  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:43:40.187  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:40.187  1038  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-28 12:43:40.188  1038  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:43:40.188  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:43:40.188  1038  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-28 12:43:40.188  1038  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:43:40.189  1038  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:43:40.189   310   907 E Netd    : netlink response contains error (File exists)
07-28 12:43:40.189  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:43:40.189  1038  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-28 12:43:40.189  1038  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 12:43:40.190  1038  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 12:43:40.190  1038  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-28 12:43:40.190  1038  1546 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-28 12:43:40.191  1038  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:43:40.191  1038  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-28 12:43:40.191  1038  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-28 12:43:40.192  1038  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 12:43:40.192  1038  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:40.192  1038  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:40.192  1038  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:43:40.192  1038  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:40.192  1038  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 12:43:40.192  1038  1546 D ConnectivityService: currentScore = 0, newScore = 20
07-28 12:43:40.192  1038  1546 D ConnectivityService:    accepting network in place of null
07-28 12:43:40.192  1038  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:40.192  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.192  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 12:43:40.192  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.192  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:43:40.193  7038  7038 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:43:40.193  1038  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:40.193  1038  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:40.193  7038  7038 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:43:40.194  1879  1879 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:40.195  1038  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:43:40.195  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:43:40.195  1038  1546 D CSL,egacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 12:43:40.197  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:43:40.198  1038  1038 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 12:43:40.198  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:43:40.198  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:43:40.198  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:43:40.199  1038  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:40.199  1038  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 12:43:40.200  7038  7038 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:43:40.201  1038  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-28 12:43:40.201   310  7058 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,07-28 12:43:40.202  1038  1546 D ConnectivityService: validation of new default Network = false
07-28 12:43:40.202  1038  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 12:43:40.202  1038  1546 D DSQN    : enableDataServiceNotify 
07-28 12:43:40.202  1038  1546 D DSQN    : start dsqn bin
07-28 12:43:40.204  7038  7038 D WeatherAncestor: connectivity changed - connection : true
07-28 12:43:40.205  7038  7038 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-28 12:43:40.209  1038  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 12:43:40.209  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:40.209  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:40.198  7059  7059 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:40.198  7059  7059 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:40.215  1038  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:43:40.222  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:43:40.223  7059  7059 E DSQN    : DSQN ssw
07-28 12:43:40.226  1038  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-28 12:43:40.235  7038  7038 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:43:40.235  7038  7038 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:43:40.236  7038  7038 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,07-28 12:43:40.245  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:43:40.246  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:40.246   310  7058 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-28 12:43:40.246  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:43:40.253  7038  7038 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:43:40.253  7038  7038 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:40
07-28 12:43:40.294   310  7058 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-28 12:43:40.295  1038  2323 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7065 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 12:43:40.297  1038  2323 I ActivityManager: Killing 6632:com.lge.bnr/1000 (adj 15): empty #17
,07-28 12:43:40.318  1038  7036 D DhcpStateMachine: DHCPV4 request on wlan0
,07-28 12:43:40.319  1038  7036 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 12:43:40.319  1038  7036 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-28 12:43:40.308  7081  7081 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:40.318  7081  7081 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:40.332   310   906 D LGDataListener: argv[0]=dsqncommand
,07-28 12:43:40.332   310   906 D LGDataListener: argv[1]=wlan0
07-28 12:43:40.332   310   906 D LGDataListener: argv[2]=1
07-28 12:43:40.332   310   906 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-28 12:43:40.334  1038  1118 D DSQN    : DSQM DsqnNotification wlan0  1
07-28 12:43:40.334  1038  1118 D DSQN    : start to monitor internet connection
,07-28 12:43:40.337  7081  7081 I dhcpcd  : version 5.5.6 starting
07-28 12:43:40.340  7081  7081 E dhcpcd  : get_duid: m
07-28 12:43:40.340  7081  7081 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 12:43:40.340  7081  7081 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-28 12:43:40.366  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:43:40 GMT], X-Android-Received-Millis=[1469702620365], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469702620331]}
,07-28 12:43:40.366  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 12:43:40.366  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-28 12:43:40.367  1038  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-28 12:43:40.367  1038  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 12:43:40.367  1038  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:40.367  1038  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:40.367  1038  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:43:40.367  1038  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-28 12:43:40.367  1038  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 12:43:40.368  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:40.368  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:40.369  1038  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:40.369  1038  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:40.369  1038  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:40.369  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-28 12:43:40.369  1038  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:40.370  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:43:40.370  1879  1879 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:40.370  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:43:40.376  1038  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_6632/cgroup.procs: No such file or directory
07-28 12:43:40.376  1840  7064 I CheckinService: active receiver: enabled
,07-28 12:43:40.395  1840  7064 I CheckinService: Preparing to send checkin request
,07-28 12:43:40.395  1840  7064 I EventLogService: Accumulating logs since 1469702540814
,07-28 12:43:40.414  7081  7081 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:43:40.414  7081  7081 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:43:40.414  7081  7081 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:43:40.414  7081  7081 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-28 12:43:40.415  7081  7081 D dhcpcd  : wlan0: sending REQUEST (xid 0xba0a9f8e), next in 3.52 seconds
,07-28 12:43:40.419  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-28 12:43:40.420  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:40.421  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:40.436  1840  7064 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-28 12:43:40.444  7081  7081 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-28 12:43:40.465  7081  7081 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 12:43:40.465  7081  7081 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,07-28 12:43:40.466  7081  7081 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 12:43:40.466  7081  7081 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 12:43:40.466  7081  7081 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:43:40.466  7081  7081 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:43:40.466  7081  7081 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:43:40.466  7081  7081 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-28 12:43:40.501   279   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:43:40.501   279   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 12:43:40.501   279   441 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:43:40.501  7065  7096 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-28 12:43:40.506   279   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:43:40.506   279   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 12:43:40.506   279   441 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:43:40.506  7065  7096 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 12:43:40.511   279   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:43:40.511   279   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 12:43:40.511   279   441 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:43:40.512  7065  7101 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-28 12:43:40.517   279   441 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 12:43:40.517   279   441 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 12:43:40.517   279   441 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:43:40.519  7065  7101 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 12:43:40.536  1038  1992 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7105 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-28 12:43:40.579  7105  7105 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-28 12:43:40.580  7105  7105 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-28 12:43:40.606  7105  7105 I MultiDex: VM with version 2.1.0 has multidex support
07-28 12:43:40.606  7105  7105 I MultiDex: install
07-28 12:43:40.607  7105  7105 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-28 12:43:40.614  7105  7105 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-28 12:43:40.697  7065  7065 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-28 12:43:40.704  7065  7065 I LibraryLoader: Loading: webviewchromium
07-28 12:43:40.707  7065  7065 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7348-7351)
07-28 12:43:40.707  7065  7065 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:43:40.711  7065  7065 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2bfbe896}
,07-28 12:43:40.712  7065  7065 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:43:40.712  7065  7065 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 12:43:40.721  7065  7065 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 12:43:40.721  7065  7065 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:43:40.722  1038  7036 D DhcpStateMachine: DHCPV4 succeeded on wlan0
07-28 12:43:40.724  1038  7036 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-28 12:43:40.724  1038  7036 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:43:40.725  1038  7036 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-28 12:43:40.725  1038  7036 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-28 12:43:40.725  1038  7036 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:43:40.725  1038  7036 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-28 12:43:40.725  1038  7036 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-28 12:43:40.726  1038  7036 D DhcpStateMachine: RunningState
07-28 12:43:40.731  7065  7065 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-28 12:43:40.731  7065  7065 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-28 12:43:40.732  7065  7065 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
07-28 12:43:40.741   315  1387 V AudioPolicyService: registerClient() client 0xb0410740, uid 10093
,07-28 12:43:40.748  7065  7155 W AudioManagerAndroid: Requires BLUETOOTH permission
07-28 12:43:40.763  7065  7065 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:43:40.763  7065  7065 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:43:40.763  7065  7065 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:43:40.763  7065  7065 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:43:40.763  7065  7065 I Adreno-EGL: Remote Branch: 
07-28 12:43:40.763  7065  7065 I Adreno-EGL: Local Patches: 
07-28 12:43:40.763  7065  7065 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:43:40.813  7065  7065 I NSApplication: Starting up...
,07-28 12:43:40.865  7105  7123 D LgDataFeature: LgDataFeature() Constructor: none
,07-28 12:43:40.865  7105  7123 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:43:40.881  1038  1783 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7168 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:40.885  1038  1783 I ActivityManager: Killing 6067:com.android.vending/u0a44 (adj 15): empty #17
07-28 12:43:40.908   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 584us total 27.686ms
,07-28 12:43:40.926  7184  7184 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
07-28 12:43:40.930   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 21.561ms
,07-28 12:43:40.952   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 427us total 20.445ms
,07-28 12:43:40.967  1038  1961 W libprocessgroup: failed to open /acct/uid_10044/pid_6067/cgroup.procs: No such file or directory
,07-28 12:43:40.978  7184  7184 I dex2oat : dex2oat took 51.774ms (threads: 4)
,07-28 12:43:40.989  7168  7168 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:40.996  7105  7123 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:43:40.996  7105  7123 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:43:40.996  7105  7123 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:43:40.996  7105  7123 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:43:40.996  7105  7123 I Adreno-EGL: Remote Branch: 
07-28 12:43:40.996  7105  7123 I Adreno-EGL: Local Patches: 
07-28 12:43:40.996  7105  7123 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:43:41.076  1038  1738 D WifiServiceImplEx: setWifiEnabled: false pid=6549, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:43:41.076  1038  1738 D WifiService: setWifiEnabled: false pid=6549, uid=10118
07-28 12:43:41.076  1038  1738 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:43:41.096  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:43:41.096  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:43:41.096  1038  1038 D Ulp_jni : JNI:system_update. Event-4
07-28 12:43:41.097  1038  1540 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:41.097  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:41.098  1038  1540 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:41.098  1038  1540 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:41.098  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 12:43:41.098  1038  1540 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:43:41.098  1038  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:43:41.098  1038  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:43:41.099  1038  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:43:41.099  1038  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-28 12:43:41.113  1038  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:43:41.113  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:43:41.113  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:43:41.113  1038  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.114  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.114  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:43:41.114  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:43:41.114  1038  1540 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:43:41.114  1038  7036 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.116   310   907 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:43:41.119  7105  7123 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:43:41.119  7105  7123 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:43:41.119  7105  7123 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:43:41.119  7105  7123 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:43:41.119  7105  7123 I Adreno-EGL: Remote Branch: 
07-28 12:43:41.119  7105  7123 I Adreno-EGL: Local Patches: 
07-28 12:43:41.119  7105  7123 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:43:41.135  1038  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:41.135  1038  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.135  1038  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 12:43:41.135  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.135  1038  1546 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:43:41.135  1038  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@34a1165
07-28 12:43:41.135  1038  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
07-28 12:43:41.135  1038  1538 D LGWifiP2pService: P2pDisablingState
07-28 12:43:41.135  1038  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.135  1038  1538 D LGWifiP2pService: p2p socket connection lost
07-28 12:43:41.135  1038  1538 D LGWifiP2pService: P2pDisabledState
07-28 12:43:41.140  1038  1038 D WifiHS20: hidePasspointNotification off =false
07-28 12:43:41.140  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:41.140  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:41.140  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:43:41.140  1038  1038 D WifiHS20: hidePasspointNotification off =false
07-28 12:43:41.141  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:41.141  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:41.141  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:43:41.141  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:43:41.141  1038  1038 D RttService: SCAN_AVAILABLE : 1
07-28 12:43:41.143  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-28 12:43:41.144  1038  1557 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.144  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:43:41.144  1969  1969 D WfdsService: WifiP2pState is changed : false
07-28 12:43:41.144  1038  1558 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.144  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:41.144  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:41.145  1969  2314 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 12:43:41.145  1969  2314 D WfdsService: Set the WFDS Monitor: false
07-28 12:43:41.147  1969  2314 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:43:41.147  1969  2314 D WfdsService: STATE : WfdsDisabledState - enter
07-28 12:43:41.147  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:41.147  1969  6966 D CtrlSupplicant: Received on exit socket, terminate
07-28 12:43:41.147  1969  6966 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 12:43:41.147  1969  6966 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 12:43:41.147  1969  6966 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 12:43:41.147  1038  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:41.147  1038  1540 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:43:41.147  1969  2314 W WfdsService: DefaultState - msg [9445378] is not handled
07-28 12:43:41.148  1038  1540 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-28 12:43:41.148  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:41.148  1038  1538 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.148  1038  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.149  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:43:41.149  6960  6960 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:43:41.149  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:43:41.149  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:43:41.149  1038  1540 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:43:41.150  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (,unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:41.150  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:41.151  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:41.152  1969  2317 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 12:43:41.172   310   907 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:43:41.172  1038  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-28 12:43:41.172  1038  1546 D DSQN    : disableDataServiceNotify
07-28 12:43:41.172  1038  1546 D DSQN    : stop dsqn bin
07-28 12:43:41.173  1038  1540 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 12:43:41.173  1038  1540 D WifiNative-p2p0: TERMINATE: returned true
07-28 12:43:41.173  1038  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:43:41.173  1038  1540 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:43:41.173  1038  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:43:41.173  1038  1038 D WifiHS20: hidePasspointNotification off =false
,07-28 12:43:41.175  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:41.175  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:41.175  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:43:41.176  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:43:41.176  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:41.177  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 12:43:41.178  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 12:43:41.178  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:41.178  1038  1038 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-28 12:43:41.178  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:41.178  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:41.178  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:41.178  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:41.178  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:41.178  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:41.178  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:41.178  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:41.178  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:41.178  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:41.178  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:41.179  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:41.179  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:41.179  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:41.179  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:41.179  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:41.179  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:41.179  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:41.179  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:41.179  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:41.179  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:41.179  6549  ,6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:41.179  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:41.180  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:41.183  1038  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-28 12:43:41.184  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:41.184  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:41.184  1038  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:41.184  1038  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,07-28 12:43:41.184  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:43:41.184  1038  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-28 12:43:41.184  1038  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 12:43:41.184  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:43:41.185  1038  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:41.185  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:43:41.185  1038  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:41.185  1038  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:41.185  1038  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:41.185  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.185  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.185  1038  7034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 12:43:41.185  1038  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:43:41.186  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:43:41.187  1038  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 12:43:41.188  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 12:43:41.188  1038  1540 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:41.188  1038  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:41.188  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:43:41.188  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:43:41.188  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:43:41.188  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:43:41.188  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:43:41.189  1038  1038 D LocSvc_java: ignore wif,i update if we are not in OPENING or CLOSING
07-28 12:43:41.189  1038  1546 D NetworkManagementService: Removing idletimer
07-28 12:43:41.189  1038  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:41.189  1879  1879 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:41.189  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,07-28 12:43:41.209  1038  1546 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-28 12:43:41.213  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:43:41.213  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:41.214  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:43:41.225  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:43:41.226  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:41.226  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:41.243  7105  7123 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 12:43:41.243  7105  7123 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 12:43:41.243  7105  7123 I Adreno-EGL: Build Date: 12/12/14 금
07-28 12:43:41.243  7105  7123 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 12:43:41.243  7105  7123 I Adreno-EGL: Remote Branch: 
07-28 12:43:41.243  7105  7123 I Adreno-EGL: Local Patches: 
07-28 12:43:41.243  7105  7123 I Adreno-EGL: Reconstruct Branch: 
,07-28 12:43:41.256  1038  1054 I art     : Explicit concurrent mark sweep GC freed 106135(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.313ms total 166.563ms
,07-28 12:43:41.278  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-28 12:43:41.280  6360  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 12:43:41.287  2224  2224 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:41.294  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,07-28 12:43:41.294  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:41.294  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:43:41.294  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:43:41.296  6911  6911 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:43:41.296  6960  6960 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:43:41.296  6960  6960 I wpa_supplicant: monitor socket send errors count : 1
07-28 12:43:41.296  6960  6960 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-4\x00 that cannot receive messages
07-28 12:43:41.297  1038  6965 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-28 12:43:41.297  1038  6965 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 12:43:41.298  6911  6911 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@32fa852f
07-28 12:43:41.298  6911  6911 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:43:41.298  6911  6911 D AppUp4:CustFacade: isPhone : true
07-28 12:43:41.298  6911  6911 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:43:41.298  6911  6911 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:43:41.301  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:41.301  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:43:41.302  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:41.303  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:41.306  4338  7205 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:43:41.308  4338  7206 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:41.308  4338  7206 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:43:41.310  6941  6941 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 12:43:41.317  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-28 12:43:41.318  6960  6960 W wpa_supplicant: USIM:  scard_deinit function
07-28 12:43:41.319  1038  1120 D Tethering: InitialState.processMessage what=4
07-28 12:43:41.319  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 12:43:41.319  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:43:41.320  1038  6965 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:43:41.320  1038  6965 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-28 12:43:41.320  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:43:41.320  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:43:41.320  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:43:41.321  1038  1540 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=137954
07-28 12:43:41.321  1038  1540 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=137954
07-28 12:43:41.323  1038  1540 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=137954  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:43:41.323  1038  1540 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=137955  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 12:43:41.323  1038  1540 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:41.324  1038  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:41.324  3364  3364 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:43:41.324  3364  3364 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:41.324  3364  3364 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:43:41.326  6972  6972 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:43:41.329  6818  7210 W FormManager: Network not available. Please check & try again.
,07-28 12:43:41.330  6818  7211 V FormManager: Network unavailable.
07-28 12:43:41.331  6972  6972 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:43:41.331  6941  7208 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:41.339  7038  7038 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:41
07-28 12:43:41.341  7038  7038 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,07-28 12:43:41.341  7038  7038 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:43:41.342  7038  7038 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:43:41.342  6818  7211 V FormManager: Network unavailable.
07-28 12:43:41.342  7038  7038 D WeatherAncestor: connectivity changed - connection : true
07-28 12:43:41.342  7038  7038 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1678fcc5
07-28 12:43:41.342  7038  7038 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:43:41.342  7038  7038 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:43:41.342  7038  7038 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:43:41.343  7038  7038 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:43:41.343  7038  7038 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:41
07-28 12:43:41.345  1038  7036 D DhcpStateMachine: StoppedState
07-28 12:43:41.345  1038  7036 D DhcpStateMachine: StoppedState{ when=-196ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:41.346  1038  1540 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-28 12:43:41.346  1038  1540 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-28 12:43:41.360  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,07-28 12:43:41.362  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:43:41.362  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:43:41.362  6730  6730 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:43:41.363  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:43:41.364  6730  6730 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:43:41.364  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:43:41.364  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:43:41.364  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:43:41.364  6730  6730 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:43:41.364  6730  6730 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:43:41.369  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:41.372  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:41.377  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:41.380  6818  7218 V FormManager: Network unavailable.
07-28 12:43:41.380  6818  7217 W FormManager: Network not available. Please check & try again.
07-28 12:43:41.384  6818  7218 V FormManager: Network unavailable.
,07-28 12:43:41.388  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:41.391  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:41.393  6818  7219 W FormManager: Network not available. Please check & try again.
07-28 12:43:41.395  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:41.395  6818  7220 V FormManager: Network unavailable.
,07-28 12:43:41.400  6818  7220 V FormManager: Network unavailable.
07-28 12:43:41.415  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:43:41.415  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:43:41.416  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:43:41.418  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:41.422  4338  7221 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:43:41.422  4338  7222 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:43:41.422  4338  7222 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:43:41.447  1038  2321 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7223 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-28 12:43:41.466  6960  6960 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:43:41.466  1038  6965 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-28 12:43:41.466  1038  6965 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
07-28 12:43:41.466  1038  6965 D WifiMonitor: Disconnecting from the supplicant, no more events
07-28 12:43:41.467  1038  1540 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,07-28 12:43:41.501   310  7241 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-28 12:43:41.501  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-28 12:43:41.502  1840  7064 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-28 12:43:41.509  1840  7064 I CheckinService: active receiver: disabled
07-28 12:43:41.519  7223  7223 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:43:41.519  7223  7223 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-28 12:43:41.524  7223  7223 V [BNRBootReceiver]: Boot Receiver Return
07-28 12:43:41.525  7223  7223 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 12:43:41.526  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:41.531  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.538  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:41.547  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:43:41.547  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:41.548  6778  6778 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:43:41.551  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-28 12:43:41.553  6730  6730 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-28 12:43:41.555  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:41.558  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.567  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:41.567  1038  1540 D WifiOffDelayIfNotUsed: stopMonitoring
07-28 12:43:41.567  1038  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:43:41.567  1038  1540 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:43:41.567  1038  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:43:41.569  1969  1969 D WfdsService: Supplicant Connection state is changed : false
07-28 12:43:41.569  1969  2314 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-28 12:43:41.569  1969  2314 D WfdsService: Set the WFDS Monitor: false
07-28 12:43:41.569  1969  2314 D WfdsMonitor: WFDS Monitor is stopped
07-28 12:43:41.570  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 12:43:41.570  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:43:41.572  2502  2502 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:41.575  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 12:43:41.575  1038  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 12:43:41.575  1038  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 12:43:41.576  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:41.576  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:41.576  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:41.576  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:41.576  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:41.576  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:41.576  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:41.576  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:41.576  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:41.576  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:41.577  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:41.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:41.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:41.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:41.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:41.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:41.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:41.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:41.579  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:41.580  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:41.581  6778  6778 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:43:41.583  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:41.591  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.598  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:41.607  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:43:41.608  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:41.609  6778  6778 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:41.612  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:41.617  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.625  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:43:41.634  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:41.635  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:41.636  6778  6778 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:41.645  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:41.660  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.673  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:41.683  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:43:41.683  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:41.684  6778  6778 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:41.689  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:41.706  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.719  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:43:41.729  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:43:41.730  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:41.730  6778  6778 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:43:41.736  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:41.747  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.754  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:41.767  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:41.768  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:41.769  6778  6778 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:41.787  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:41.815  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.829  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:43:41.848  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:41.849  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:41.862  6778  6778 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:41.873  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:41.895  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.905  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:41.915  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:43:41.917  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:41.919  6778  6778 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:41.925  6656  6888 D UEI.SmartControl: Internal timer expired: 2
07-28 12:43:41.925  6656  6888 D UEI.SmartControl: unbind internal service
07-28 12:43:41.927  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:41.938  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-28 12:43:41.952  1038  1545 D WifiService: New client listening to asynchronous messages
,07-28 12:43:41.954  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:41.961  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:41.970  6656  6882 D serial_port: close(fd = 24)
,07-28 12:43:41.971  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:41.973  6656  6882 I UEI.SmartControl: Serial port is closed.
07-28 12:43:41.982  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:41.983  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:41.984  6778  6778 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,07-28 12:43:41.985  6778  6778 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:43:41.986  6778  6778 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:43:41.994  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:42.000  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-28 12:43:42.003  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:42.009  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:42.021  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:42.032  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:42.032  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:42.036  6778  6778 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:43:42.038  6778  6778 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:43:42.039  6778  6778 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:43:42.043  1038  2059 I ActivityManager: Killing 6711:com.lge.lifetracker/u0a37 (adj 15): empty #17
07-28 12:43:42.145  1038  1992 W libprocessgroup: failed to open /acct/uid_10037/pid_6711/cgroup.procs: No such file or directory
,07-28 12:43:42.158  2224  2224 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-28 12:43:42.180  2224  2224 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-28 12:43:42.181  2224  2224 D c       : Getting all permits...
07-28 12:43:42.182  2224  2224 D a       : Opening database...
07-28 12:43:42.193  2224  2224 D a       : Opening database auth.proximity.permit_store...
,07-28 12:43:42.196  2224  2224 D a       : Closing database...
07-28 12:43:42.218  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:42.225  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:43:42.225  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:43:42.225  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:42.233  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:42.247  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:42.261  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:43:42.262  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:42.266  6778  6778 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:43:42.274  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:42.283  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:43:42.283  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:43:42.283  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:42.294  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:42.307  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:43:42.316  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:42.317  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:42.325  6778  6778 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:43:42.332  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:42.337  6749  6749 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 12:43:42.337  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:43:42.337  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:43:42.343  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:43:42.348  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:42.354  6778  6778 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:42.354  6778  6778 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:42.356  6778  6778 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:43:42.366  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:42.370  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:42.376  6818  7253 W FormManager: Network not available. Please check & try again.
07-28 12:43:42.380  6818  7254 V FormManager: Network unavailable.
07-28 12:43:42.381  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:42.396  6818  7254 V FormManager: Network unavailable.
,07-28 12:43:42.404  2224  2224 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-28 12:43:42.421  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-28 12:43:42.422  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-28 12:43:42.424  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:42.428  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:43:42.440  6749  6749 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 12:43:42.440  6749  6749 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 12:43:42.440  6749  6749 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:43:42.447  4338  7259 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:43:42.447  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:42.457  4338  7261 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:43:42.457  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:42.457  4338  7261 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 12:43:42.471  6818  7263 W FormManager: Network not available. Please check & try again.
,07-28 12:43:42.478  6818  7264 V FormManager: Network unavailable.
,07-28 12:43:42.480  6818  7264 V FormManager: Network unavailable.
07-28 12:43:42.535  1038  1383 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1a94c5c9 type 2 when 139164 com.google.android.gms} when 139164
,07-28 12:43:42.547   310  7267 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,07-28 12:43:42.548  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-28 12:43:42.550  6778  6778 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
07-28 12:43:42.550  6778  6778 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6925
,07-28 12:43:42.810  1038  1383 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2811a4ce type 2 when 139424 com.google.android.gms} when 139424
,07-28 12:43:43.104  1038  1540 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:823807872] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-28 12:43:43.117  1038  1540 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:823807885] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-28 12:43:43.202  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:43.223  1038  1120 D Tethering: MasterInitialState.processMessage what=3
,07-28 12:43:43.230  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:43.231  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:43.236  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:43:43.240  6360  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 12:43:43.243  1038  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:43.254  5267  5267 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 12:43:43.273  2224  2224 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:43.292  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:43:43.292  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:43.293  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:43:43.293  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-28 12:43:43.300  6911  6911 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:43:43.303  6911  6911 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@32fa852f
07-28 12:43:43.303  6911  6911 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:43:43.303  6911  6911 D AppUp4:CustFacade: isPhone : true
07-28 12:43:43.304  6911  6911 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:43:43.304  6911  6911 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:43:43.309  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:43.309  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:43:43.311  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:43:43.317  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:43.325  6941  6941 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 12:43:43.351  4338  7276 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 12:43:43.385  4338  7280 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:43.386  4338  7280 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 12:43:43.402  6941  7277 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:43.403  6818  7278 W FormManager: Network not available. Please check & try again.
07-28 12:43:43.411  3364  3364 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:43:43.411  3364  3364 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:43.411  3364  3364 I LgeMiscReceiver: networkInfo.isConnected() = true
07-28 12:43:43.411  3364  3364 D PhoneState: setPdpRejectCasuse : false
07-28 12:43:43.414  6972  6972 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:43:43.414  6972  6972 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:43:43.416  6818  7279 V FormManager: Network unavailable.
,07-28 12:43:43.425  7038  7038 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:43
07-28 12:43:43.427  6818  7279 V FormManager: Network unavailable.
07-28 12:43:43.427  7038  7038 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:43:43.427  7038  7038 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:43:43.427  7038  7038 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:43:43.428  7038  7038 D WeatherAncestor: connectivity changed - connection : true
07-28 12:43:43.428  7038  7038 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1678fcc5
07-28 12:43:43.428  7038  7038 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:43:43.428  7038  7038 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:43:43.428  7038  7038 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:43:43.428  7038  7038 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:43:43.429  7038  7038 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:43
,07-28 12:43:43.499  1038  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:44.099  1038  2058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:43:44.100  1038  2058 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-28 12:43:44.134  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:43:44.134  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:43:44.134  1038  1038 D Ulp_jni : JNI:system_update. Event-4
07-28 12:43:44.135  1038  1120 D BluetoothManagerService: Message: 1
07-28 12:43:44.135  1038  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-28 12:43:44.163  1038  1120 D BluetoothManagerService: Message: 20
07-28 12:43:44.163  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bfab183:true
,07-28 12:43:44.168  6849  6849 D BluetoothAdapterState: make
07-28 12:43:44.172  6849  6849 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 12:43:44.173  6849  6849 I bluedroid-qcom: init
07-28 12:43:44.174  6849  7309 I BluetoothAdapterState: Entering OffState
07-28 12:43:44.174  6849  6849 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:43:44.175  6849  6849 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:43:44.175  6849  6849 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:43:44.175  6849  6849 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:43:44.175  6849  6849 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-28 12:43:44.177  6849  6849 I bluedroid-qcom: get_profile_interface socket
07-28 12:43:44.177  6849  6849 I bluedroid-qcom: get_profile_interface map_client
,07-28 12:43:44.168  7312  7312 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:44.184  6849  7313 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 12:43:44.178  7312  7312 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:44.186  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.194  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:44.200  1038  1120 D Tethering: MasterInitialState.processMessage what=3
07-28 12:43:44.207  7312  7312 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 12:43:44.207  7312  7312 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 12:43:44.207  7312  7312 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-28 12:43:44.211  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:44.213  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:44.214  7312  7312 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-28 12:43:44.222  7312  7312 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 12:43:44.222  7312  7312 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,07-28 12:43:44.226  1038  1120 D Tethering: MasterInitialState.processMessage what=3
07-28 12:43:44.229  6849  7313 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 12:43:44.237  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:44.240  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:44.243  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-28 12:43:44.243  1038  1120 D BluetoothManagerService: Message: 40
07-28 12:43:44.243  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 12:43:44.244  6849  6865 I bluedroid-qcom: config_hci_snoop_log
07-28 12:43:44.246  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-28 12:43:44.246  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-28 12:43:44.250  6849  7313 D BluetoothAdapterProperties: Name is: G3
,07-28 12:43:44.252  1038  1383 V AlarmManager: ELAPSED_WAKEUP set : Alarm{332ce2df type 2 when 140883 com.google.android.gms} when 140883
,07-28 12:43:44.254  6849  7309 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 12:43:44.254  6849  7309 D BluetoothAdapterProperties: Setting state to 11
07-28 12:43:44.255  6849  7309 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:43:44.261  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:43:44.262  1038  1120 D BluetoothManagerService: Message: 60
,07-28 12:43:44.262  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 12:43:44.262  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-28 12:43:44.263  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:43:44.264  6849  7309 I LGBluetoothServiceJni: classInitNative: succeeds
07-28 12:43:44.264  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:43:44.266  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:43:44.266  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:44.269  6360  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 12:43:44.270  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:44.273  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:44.275  6730  6730 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-28 12:43:44.275  1038  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:44.283  5267  5267 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 12:43:44.288  1038  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:44.292  6849  6849 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:43:44.292  6849  6849 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:44.292  6849  6849 V BluetoothPbapReceiver: ***********state = 11
07-28 12:43:44.296  6849  7309 D BluetoothBondStateMachine: make
07-28 12:43:44.297  2224  2224 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:43:44.300  6849  7332 I BluetoothBondStateMachine: StableState(): Entering Off State
07-28 12:43:44.300  6849  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
,07-28 12:43:44.300  6849  7309 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 12:43:44.300  6849  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:44.300  6849  7309 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 12:43:44.302  6849  7309 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-28 12:43:44.306  6849  7309 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:44.341  1038  1053 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7333 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:44.346  5267  5267 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 12:43:44.347  1038  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:44.347  1038  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:44.347  6849  7309 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:44.349  6849  6849 D HeadsetService: Received start request. Starting profile...
07-28 12:43:44.350  6849  6849 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:43:44.350  6849  6849 D LGBluetoothHfpAdapter: Version 1.6
07-28 12:43:44.352  6849  6849 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:43:44.353  6849  6849 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-28 12:43:44.353  6849  6849 D HeadsetStateMachine: make
07-28 12:43:44.357  6849  7309 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:44.361  6849  7309 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:44.362  2224  2224 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.367  6849  7309 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:43:44.372  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 12:43:44.372  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.373  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:43:44.373  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:43:44.374  6849  7309 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:44.376  6911  6911 I AppUp4:CustModeStarterReceiver: onReceive
07-28 12:43:44.378  6849  7309 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:43:44.380  6849  6849 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:44.380  6849  6849 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:43:44.383  6849  6849 D HeadsetStateMachine: max_hf_connections = 1
07-28 12:43:44.383  6849  6849 I bluedroid-qcom: get_profile_interface handsfree
07-28 12:43:44.385  6849  6849 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 12:43:44.385   315   315 V AudioPolicyService: registerClient() client 0xb558aa60, uid 1002
07-28 12:43:44.385   315  1387 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:43:44.385   315  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:43:44.385   315  1387 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:43:44.385  6849  6849 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:43:44.386   315  1388 V AudioFlinger: registerClient() client 0xb14330a0, pid 6849
07-28 12:43:44.386  6849  6849 V ToneGenerator: Create Track: 0xb4928080
07-28 12:43:44.386  6849  6849 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 12:43:44.386  6849  6849 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 12:43:44.386   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:43:44.386   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:43:44.386   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:43:44.386   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:43:44.386  6911  6911 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@32fa852f
07-28 12:43:44.386  6911  6911 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:43:44.386  6911  6911 D AppUp4:CustFacade: isPhone : true
07-28 12:43:44.386  6849  6849 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:43:44.387   315  1388 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:43:44.387   315  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:44.387   315  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:44.387   315  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:43:44.387   315  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 12:43:44.387   315  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:43:44.387   315  1387 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:43:44.387   315  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:44.387   315  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:44.387  6849  7331 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:44.387  6849  7331 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 12:43:44.387  1038  2090 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:44.387  1038  2090 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:44.387  6849  7331 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,07-28 12:43:44.387  6849  7331 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 12:43:44.387  1038  2090 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:44.387  1038  2090 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:44.387  6849  6849 V AudioSystem: getLatency() output 2, latency 50
07-28 12:43:44.387  6849  6849 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 12:43:44.387  6849  6849 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 12:43:44.387  1605  1627 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:44.387  1605  1627 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:44.387  1605  1627 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:44.387  1605  1627 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:44.387  1879  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:44.387   315  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:43:44.387  1879  1894 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:44.387   315  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:43:44.387   315  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:43:44.387   315  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:43:44.387   315  1388 V AudioFlinger: createTrack() lSessionId: 22
07-28 12:43:44.387  1879  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:44.387  1879  1894 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:44.387  3364  3384 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:44.387  3364  3384 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:44.388  3364  3384 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:44.388  3364  3384 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:44.388  6849  6849 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 12:43:44.388   315   315 V AudioFlinger: acquiring 22 from 6849, for 6849
07-28 12:43:44.388   315   315 V AudioFlinger:  added new entry for 22
07-28 12:43:44.388  6849  6849 V ToneGenerator: ToneGenerator INIT OK, time: 141033
07-28 12:43:44.388  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:44.389  6849  7348 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 12:43:44.389  6849  7348 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:43:44.389  6849  7348 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:43:44.389  6849  7348 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-28 12:43:44.390   315  4021 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6849
07-28 12:43:44.390  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:44.390   315  4021 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-28 12:43:44.390   315  4021 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 12:43:44.390   315  4021 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 12:43:44.390   315  4021 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 12:43:44.390   315  4021 V voice   : voice_set_parameters: exit with code(0)
07-28 12:43:44.390   315  4021 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-28 12:43:44.390   315  4021 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 12:4,3:44.390   315  4021 V msm8974_platform: platform_set_parameters: exit with code(0)
07-28 12:43:44.390   315  4021 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 12:43:44.390   315  4021 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 12:43:44.390   315  4021 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-28 12:43:44.390  6849  7348 V ToneGenerator: ToneGenerator destructor
07-28 12:43:44.390  6849  7348 V ToneGenerator: stopTone
07-28 12:43:44.390  6849  7348 V ToneGenerator: Delete Track: 0xb4928080
07-28 12:43:44.391  6849  7348 V AudioTrack: ~AudioTrack, releasing session id from 6849 on behalf of 6849
07-28 12:43:44.391  6849  6849 D A2dpService: Received start request. Starting profile...
07-28 12:43:44.391   315  1387 V AudioFlinger: releasing 22 from 6849 for 6849
07-28 12:43:44.391   315  1387 V AudioFlinger:  decremented refcount to 0
07-28 12:43:44.391   315  1387 V AudioFlinger: purging stale effects
07-28 12:43:44.391   315  1387 V AudioPolicyService: AudioCommandThread() adding release output 2
07-28 12:43:44.391   315  1387 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 12:43:44.391   315  1276 V AudioPolicyService: AudioCommandThread() waking up
07-28 12:43:44.391   315  1276 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 12:43:44.391   315  1276 V AudioPolicyManager: releaseOutput() 2
07-28 12:43:44.391   315  1276 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 12:43:44.391   315  1387 V AudioFlinger: PlaybackThread::Track destructor
07-28 12:43:44.391   315  1387 V AudioFlinger: removeClient_l() pid 6849, calling pid 315
,07-28 12:43:44.391  6849  6849 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:43:44.392  6849  6849 V Avrcp   : make
07-28 12:43:44.392  6849  6849 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 12:43:44.392  6849  6849 I bluedroid-qcom: get_profile_interface avrcp
07-28 12:43:44.394  6849  7309 V LGMDMManager: Create singleton instance
07-28 12:43:44.394  6911  6911 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:43:44.394  6911  6911 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:43:44.396  6849  7309 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 12:43:44.397  1038  2059 W Process : Unable to open /proc/7352/status
07-28 12:43:44.399  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.399  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:43:44.400  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:44.402  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:44.406  6941  6941 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 12:43:44.408  4338  7354 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:43:44.409  6849  6849 V AudioManager: registerRemoteController: size of Media player list: 0
07-28 12:43:44.410  4338  7355 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.410  4338  7355 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:43:44.410  6849  6849 E AudioManager: No RCC entry present to update
07-28 12:43:44.410  6849  6849 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 12:43:44.413  6849  6849 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 12:43:44.413  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-28 12:43:44.413  6849  6849 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-28 12:43:44.418  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,07-28 12:43:44.456  3364  3364 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:43:44.456  3364  3364 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.456  3364  3364 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-28 12:43:44.465  6818  7359 W FormManager: Network not available. Please check & try again.
07-28 12:43:44.465  6941  7357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:44.465  6972  6972 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:43:44.466  6972  6972 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:43:44.470  6818  7360 V FormManager: Network unavailable.
,07-28 12:43:44.471  7333  7333 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-28 12:43:44.471  7333  7333 W LG Account v2.2: No ProfileInfo entries
07-28 12:43:44.471  7333  7333 I LG Account v2.2: isEnabled: false
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]Country: EU
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]Operator: OPEN
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]Ranking support: false
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]Comfort support: false
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]Accessory: true
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]Health device: true
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]Extra Pedometer: false
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]Blood glucose device: false
07-28 12:43:44.472  7333  7333 I Feature : [Lifetracker]Device Number: 3
07-28 12:43:44.484  7038  7038 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:44
,07-28 12:43:44.485  6818  7360 V FormManager: Network unavailable.
07-28 12:43:44.488  6730  6730 D BluetoothPermissionRequest: onReceive
07-28 12:43:44.489  7038  7038 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:43:44.489  7038  7038 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:43:44.489  7038  7038 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:43:44.489  7038  7038 D WeatherAncestor: connectivity changed - connection : true
07-28 12:43:44.490  7038  7038 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1678fcc5
07-28 12:43:44.490  7038  7038 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:43:44.490  7038  7038 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:43:44.490  7038  7038 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:43:44.490  7038  7038 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:43:44.491  7038  7038 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:44
07-28 12:43:44.491  6730  6730 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:43:44.499  1038  1604 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:43:44.499  1038  1604 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:43:44.513  6360  6360 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 12:43:44.514  6360  6395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 12:43:44.529  2224  2224 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:44.537  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,07-28 12:43:44.537  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.538  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 12:43:44.538  6911  6911 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 12:43:44.539  6911  6911 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 12:43:44.541  6911  6911 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@32fa852f
07-28 12:43:44.541  6911  6911 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:43:44.541  6911  6911 D AppUp4:CustFacade: isPhone : true
07-28 12:43:44.541  6911  6911 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:43:44.541  6911  6911 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 12:43:44.544  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.545  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 12:43:44.546  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:44.547  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:44.551  4338  7364 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:43:44.555  6941  6941 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 12:43:44.559  4338  7365 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.559  4338  7365 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:43:44.573  6941  7366 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:44.576  3364  3364 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 12:43:44.576  3364  3364 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:44.577  3364  3364 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 12:43:44.578  1038  1983 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-28 12:43:44.580  6972  6972 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 12:43:44.580  6972  6972 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 12:43:44.581  6818  7368 W FormManager: Network not available. Please check & try again.
07-28 12:43:44.585  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 12:43:44.586  6818  7370 V FormManager: Network unavailable.
07-28 12:43:44.587  6818  7370 V FormManager: Network unavailable.
,07-28 12:43:44.588  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:43:44.589  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:43:44.589  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:43:44.589  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:43:44.589  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:43:44.589  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:43:44.589  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,07-28 12:43:44.589  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:43:44.589  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:43:44.589  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:43:44.589  6849  6849 I BluetoothA2dpServiceJni: classInitNative
07-28 12:43:44.590  6849  6849 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:43:44.590  6849  6849 D A2dpStateMachine: make
07-28 12:43:44.591  6849  6849 I bluedroid-qcom: get_profile_interface a2dp
07-28 12:43:44.591  6849  7372 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:43:44.592  6849  6849 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:43:44.592  6849  6849 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 12:43:44.593  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:44.594  6849  6849 I BluetoothHidServiceJni: classInitNative: succeeds
07-28 12:43:44.595  6849  6849 D HidService: Received start request. Starting profile...
07-28 12:43:44.595  6849  6849 I bluedroid-qcom: get_profile_interface hidhost
07-28 12:43:44.595  6849  7371 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:43:44.595  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:44.595  6849  6849 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:43:44.597  6849  6849 D HealthService: Received start request. Starting profile...
07-28 12:43:44.597  7038  7038 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:44
07-28 12:43:44.598  6849  6849 I bluedroid-qcom: get_profile_interface health
07-28 12:43:44.598  6849  6849 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:43:44.598  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:44.599  6849  6849 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:43:44.599  7038  7038 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 12:43:44.599  7038  7038 D Weather.Utils: 2 : All the weather widget is gone.
07-28 12:43:44.599  7038  7038 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 12:43:44.599  7038  7038 D WeatherAncestor: connectivity changed - connection : true
07-28 12:43:44.599  7038  7038 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1678fcc5
07-28 12:43:44.600  7038  7038 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 12:43:44.600  7038  7038 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 12:43:44.600  7038  7038 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 12:43:44.600  7038  7038 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 12:43:44.600  6849  6849 D PanService: Received start request. Starting profile...
07-28 12:43:44.600  7038  7038 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:43:44
07-28 12:43:44.600  6849  6849 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:43:44.600  6849  6849 I bluedroid-qcom: get_profile_interface pan
07-28 12:43:44.606  6849  6849 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-28 12:43:44.606  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:44.607  6849  6849 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-28 12:43:44.610  6849  6849 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:43:44.611  6849  6849 D BtGatt.GattService: Received start request. Starting profile...
,07-28 12:43:44.611  6849  6849 D BtGatt.GattService: start()
07-28 12:43:44.611  6849  6849 I bluedroid-qcom: get_profile_interface gatt
07-28 12:43:44.611  6849  6849 D BtGatt.AdvertiseManager: advertise manager created
07-28 12:43:44.615  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:44.616  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:44.616  6849  6849 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 12:43:44.617  6849  6849 V BluetoothMapService: BluetoothMapBinder()
07-28 12:43:44.617  6849  6849 D BluetoothMapService: Received start request. Starting profile...
07-28 12:43:44.617  6849  6849 D BluetoothMapService: start()
07-28 12:43:44.618   310  7380 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-28 12:43:44.619  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-28 12:43:44.620  6849  6849 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 12:43:44.620  6849  6849 D BluetoothMapEmailAppObserver: createReceiver()
07-28 12:43:44.621  6849  6849 D BluetoothMapEmailAppObserver: initObservers()
07-28 12:43:44.621  6849  6849 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-28 12:43:44.626  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
,07-28 12:43:44.626  6849  6849 D HeadsetStateMachine: Proxy object connected
07-28 12:43:44.627  6849  6849 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 12:43:44.627  6849  6849 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,07-28 12:43:44.629  6849  6849 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:43:44.630  6849  7348 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:43:44.630  6849  7348 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:43:44.630  6849  7348 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-28 12:43:44.632  6849  6849 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:43:44.633  6849  6849 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:43:44.635  6849  6849 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:43:44.637  6849  6849 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:43:44.637  6849  6849 V PanService: [BTUI] SIM Extra State :ABSENT
,07-28 12:43:44.639  6849  6849 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-28 12:43:44.639  6849  6849 V BluetoothMapService: Handler(): got msg=1
07-28 12:43:44.640  6849  7309 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:43:44.640  6849  7309 I bluedroid-qcom: enable
07-28 12:43:44.640  6849  7381 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:43:44.640  6849  7381 I bt-btu  : btu_task pending for preload complete event
07-28 12:43:44.640  6849  7309 I bt_hci_bdroid: init
07-28 12:43:44.641  6849  6849 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:44.641  6849  7309 I bt_vendor: bt-vendor : init
07-28 12:43:44.641  6849  7309 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 12:43:44.641  6849  7309 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-28 12:43:44.641  6849  7309 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 12:43:44.641  6849  7309 D bt_userial_mct: userial_init
07-28 12:43:44.641  6849  7309 D bt_hci_bdroid: set_power 1
07-28 12:43:44.641  6849  7309 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 12:43:44.641  6849  7309 I bt_vendor: Starting hciattach daemon
07-28 12:43:44.641  6849  7309 I bt_vendor: try to set true
07-28 12:43:44.643  6849  6849 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:43:44.643  6849  6849 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:43:44.643  6849  6849 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:43:44.643  6849  6849 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:44.643  6849  6849 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 12:43:44.628  7384  7384 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:44.628  7384  7384 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:44.659  7385  7385 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 12:43:44.698  7391  7391 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-28 12:43:44.707  7392  7392 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-28 12:43:44.721  7394  7394 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:43:44.733  7395  7395 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-28 12:43:44.749  7396  7396 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:43:44.766  7397  7397 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-28 12:43:44.797  7399  7399 I libmdmdetect: ESOC framework not supported
,07-28 12:43:44.799  7399  7399 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-28 12:43:44.811  7399  7399 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-28 12:43:44.811  7399  7399 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 12:43:44.811  7399  7399 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-28 12:43:44.811  7399  7399 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-28 12:43:44.811  7399  7399 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 12:43:44.811  7399  7399 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 12:43:44.811  7399  7399 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-28 12:43:44.862  7399  7400 E QC-QMI  : qmi_client [7399] 14: failed to locate client data
,07-28 12:43:44.862   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 12:43:44.862   444   444 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
07-28 12:43:44.918  7404  7404 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 12:43:44.943  7408  7408 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:43:44.993  6849  7309 I bt_vendor: bluetooth satus is on
07-28 12:43:44.993  6849  7309 D bt_hci_bdroid: preload
07-28 12:43:44.994  6849  7383 D bt_userial_mct: userial_open(port:0)
07-28 12:43:44.994  6849  7383 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-28 12:43:44.998  6849  7383 I bt_vendor: Done intiailizing UART
,07-28 12:43:45.001  6849  7383 I bt_vendor: Done intiailizing UART
07-28 12:43:45.001  6849  7383 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-28 12:43:45.002  6849  7383 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-28 12:43:45.002  6849  7410 D bt_userial_mct: Entering userial_read_thread()
,07-28 12:43:45.003  6849  7381 I bt-btu  : btu_task received preload complete event
07-28 12:43:45.003  6849  7381 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 12:43:45.004  6849  7381 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,07-28 12:43:45.013  6849  7381 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_HCI,
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_BNEP,
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_GATT
,07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:43:45.037  6849  7381 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:43:45.102  6849  7381 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-28 12:43:45.102  6849  7381 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
07-28 12:43:45.102  6849  7381 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 
,07-28 12:43:45.123  6849  7313 E bt-btif : Calling BTA_HhEnable
07-28 12:43:45.123  6849  7313 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-28 12:43:45.124  6849  7313 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 12:43:45.126  6849  7381 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 12:43:45.126  6849  7381 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 12:43:45.126  6849  7381 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-28 12:43:45.126  6849  7381 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 12:43:45.127  6849  7381 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 12:43:45.128  6849  7313 D BluetoothAdapterProperties: Name is: G3
07-28 12:43:45.129  6849  7313 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:43:45.129  6849  7313 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:43:45.129  6849  7313 D bt_hci_bdroid: postload
07-28 12:43:45.129  6849  7383 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:43:45.130  6849  7313 D bte_conf: Device ID record 1 : primary
07-28 12:43:45.130  6849  7313 D bte_conf:   vendorId            = 00c4
07-28 12:43:45.130  6849  7313 D bte_conf:   vendorIdSource      = 0001
07-28 12:43:45.130  6849  7313 D bte_conf:   product             = 13a1
07-28 12:43:45.130  6849  7313 D bte_conf:   version             = 1000
07-28 12:43:45.130  6849  7313 D bte_conf:   clientExecutableURL = 
07-28 12:43:45.130  6849  7313 D bte_conf:   serviceDescription  = 
07-28 12:43:45.130  6849  7313 D bte_conf:   documentationURL    = 
07-28 12:43:45.130  6849  7313 D bte_conf: bte_load_did_conf no section named DID2.
07-28 12:43:45.131  6849  7381 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-28 12:43:45.131  6849  7383 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:43:45.132  6849  7383 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:43:45.132  6849  7383 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:43:45.134  6849  7383 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:43:45.134  6849  7309 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:43:45.135  6849  7309 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:43:45.135  6849  7309 D BluetoothAdapterProperties: State =  11
07-28 12:43:45.135  6849  7309 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 12:43:45.135  6849  7309 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 12:43:45.135  6849  7309 D BluetoothAdapterProperties: Setting state to 12
07-28 12:43:45.135  6849  7309 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 12:43:45.136  6849  7313 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 12:43:45.136  6849  7313 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-28 12:43:45.128  7415  7415 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:45.128  7415  7415 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:45.146  1038  1120 D BluetoothManagerService: Message: 60
07-28 12:43:45.146  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 12:43:45.146  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-28 12:43:45.146  6849  7410 E bt_mct  : hci lib postload completed
07-28 12:43:45.155  6849  7381 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:45.158  6849  7381 W bt-smp  : Plain text(LSB ~ MSB) = f6 6e 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:45.158  6849  7381 W bt-smp  : Encrypted text(LSB ~ MSB) = 69 1f 85 31 1a b2 46 28 3b e0 61 9e ba a8 29 ab 
,07-28 12:43:45.161  6849  7381 W bt-btm  : Stopping oneshot timer
07-28 12:43:45.162  6849  7309 I BluetoothAdapterState: Entering On State
07-28 12:43:45.165  6849  7309 D LGBluetoothServiceAdapter: [BTUI] OnState
07-28 12:43:45.165  6849  7309 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 12:43:45.165  6849  7309 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-28 12:43:45.167  6849  7309 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-28 12:43:45.178  6849  7313 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:43:45.178  6849  7313 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,07-28 12:43:45.211  6849  7381 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:45.211  6849  7381 W bt-smp  : Plain text(LSB ~ MSB) = 21 72 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:45.211  6849  7381 W bt-smp  : Encrypted text(LSB ~ MSB) = cb 3a 29 1b e5 d3 6e 79 3b e5 07 d3 3a 65 a3 bd 
07-28 12:43:45.211  6849  7381 W bt-btm  : Stopping oneshot timer
,07-28 12:43:45.214  6849  7309 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 12:43:45.217  6730  6745 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:43:45.217  6730  6745 D BluetoothPan: onBluetoothStateChange call bindService
07-28 12:43:45.235  7428  7428 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,07-28 12:43:45.238  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:43:45.240  6730  6745 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:43:45.240  1038  1038 D BluetoothA2dp: Proxy object connected
07-28 12:43:45.240  6730  6730 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:43:45.240  6730  6730 D PanProfile: Bluetooth service connected
07-28 12:43:45.242  6730  6746 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:43:45.244  6730  6745 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:43:45.247  6849  7381 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:45.247  6849  7381 W bt-smp  : Plain text(LSB ~ MSB) = 78 5d 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:45.247  6849  7381 W bt-smp  : Encrypted text(LSB ~ MSB) = 4c 66 db 6a a7 6c bf 90 35 0a a9 6f 0a 91 db bd 
07-28 12:43:45.247  6849  7381 W bt-btm  : Stopping oneshot timer
,07-28 12:43:45.249  1879  2540 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:43:45.250  6730  6730 D BluetoothInputDevice: Proxy object connected
07-28 12:43:45.250  6730  6730 D HidProfile: Bluetooth service connected
07-28 12:43:45.252  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:43:45.252  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 12:43:45.252  1038  1038 D BluetoothHeadset: Proxy object connected
07-28 12:43:45.252  6730  6730 D BluetoothMap: Proxy object connected
07-28 12:43:45.252  6730  6730 D MapProfile: Bluetooth service connected
07-28 12:43:45.253  6730  6730 D BluetoothMap: getConnectedDevices()
07-28 12:43:45.253  1879  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:43:45.255  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 12:43:45.256  1879  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:43:45.257  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:43:45.258  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:43:45.258  6849  6865 V BluetoothMapService: getConnectedDevices()
07-28 12:43:45.258  6849  7381 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:45.258  6849  7381 W bt-smp  : Plain text(LSB ~ MSB) = 55 c5 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:45.259  6849  7381 W bt-smp  : Encrypted text(LSB ~ MSB) = 14 9a 5c 4c ae 11 a5 59 7f e7 9c 9f eb 00 a2 b2 
07-28 12:43:45.259  6849  7381 W bt-btm  : Stopping oneshot timer
,07-28 12:43:45.264  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:45.264  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:45.264  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:45.264  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:45.264  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:45.264  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:45.264  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:45.264  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:45.265  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 12:43:45.266  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:45.266  1038  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 12:43:45.266  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 12:43:45.268  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 12:43:45.268  6849  7381 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:45.268  6849  7381 W bt-smp  : Plain text(LSB ~ MSB) = ee 46 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:45.268  6849  7381 W bt-smp  : Encrypted text(LSB ~ MSB) = 0b 21 1d cb 5b 70 58 8b c2 08 ae b2 74 19 88 9a 
07-28 12:43:45.268  6849  7381 W bt-btm  : Stopping oneshot timer
07-28 12:43:45.268  1038  1120 D BluetoothManagerService: Message: 40
07-28 12:43:45.268  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-28 12:43:45.269  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:45.269  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:45.269  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:45.269  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:45.269  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:45.269  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:45.269  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:45.269  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:45.270  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:45.270  1969  2177 D LGBluetoothAPIService: Message: 1
07-28 12:43:45.271  1969  2177 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 12:43:45.272  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:45.272  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-28 12:43:45.277  6549  6549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:43:45.278  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:45.279  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:45.287  6849  6849 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:45.288  6849  6849 D BluetoothMapService: STATE_ON
07-28 12:43:45.288  6849  6849 V BluetoothMapService: Handler(): got msg=1
,07-28 12:43:45.288  6849  6849 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-28 12:43:45.290  1969  2177 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-28 12:43:45.291  6730  6730 D LocalBluetoothProfileManager: Adding local A2DP profile
07-28 12:43:45.293  6849  7438 D BluetoothMapMasInstance: MAS initSocket()
,07-28 12:43:45.294  6849  7438 D BluetoothMapMasInstance:   masId = 00
07-28 12:43:45.294  6849  7438 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 12:43:45.294  6849  7438 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 12:43:45.294  6849  7438 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-28 12:43:45.295  1038  1120 D BluetoothManagerService: Message: 30
07-28 12:43:45.296  1038  1604 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:45.297  6849  7438 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:45.299  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:45.299  6849  6849 V BluetoothPbapService: Pbap Service onCreate
07-28 12:43:45.299  6849  6849 V BluetoothPbapService: Starting PBAP service
,07-28 12:43:45.300  6849  6849 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,07-28 12:43:45.301  6849  6849 V BluetoothPbapService: Pbap Service onBind
07-28 12:43:45.301  6849  6849 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:45.302  6849  6849 V BluetoothPbapService: state: 12
07-28 12:43:45.302  6849  7438 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-28 12:43:45.303  6849  7313 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:43:45.303  6849  7438 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 12:43:45.303  6849  7313 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 12:43:45.303  6849  7438 D BluetoothMapMasInstance: Accepting socket connection...
07-28 12:43:45.303  6849  6849 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 12:43:45.303  6849  6849 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 12:43:45.305  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:45.307  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:45.308  6849  6849 V BluetoothPbapService: Handler(): got msg=1
07-28 12:43:45.308  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 12:43:45.308  6730  6730 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-28 12:43:45.308  1969  2177 D LGBluetoothAPIService: Message: 100
07-28 12:43:45.308  1969  2177 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-28 12:43:45.308  6849  6849 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 12:43:45.309  6849  7440 V BluetoothPbapService: Pbap Service initSocket
07-28 12:43:45.310  1038  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:45.310  1038  1120 D BluetoothManagerService: Message: 30
07-28 12:43:45.310  6849  7440 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:45.313  6849  7440 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-28 12:43:45.313  6849  7440 V BluetoothPbapService: Succeed to create listening socket 
07-28 12:43:45.313  6849  7440 V BluetoothPbapService: Accepting socket connection...
,07-28 12:43:45.318  6730  6730 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-28 12:43:45.320  6730  6730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:43:45.322  6730  6730 D BluetoothPbap: Proxy object connected
07-28 12:43:45.322  6730  6730 D PbapServerProfile: Bluetooth service connected
07-28 12:43:45.322  6730  6730 D BluetoothA2dp: Proxy object connected
07-28 12:43:45.323  6730  6730 D A2dpProfile: Bluetooth service connected
07-28 12:43:45.323  6849  6849 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:43:45.323  6849  6849 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:45.323  6849  6849 V BluetoothPbapReceiver: ***********state = 12
07-28 12:43:45.324  6730  6730 D BluetoothHeadset: Proxy object connected
07-28 12:43:45.325  6730  6730 D HeadsetProfile: Bluetooth service connected
07-28 12:43:45.326  2224  2224 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:45.326  2224  2224 D c       : Getting all permits...
07-28 12:43:45.326  2224  2224 D a       : Opening database...
07-28 12:43:45.329  6730  6730 D DockEventReceiver: finishStartingService: stopping service
07-28 12:43:45.330  2224  2224 D a       : Opening database auth.proximity.permit_store...
07-28 12:43:45.330  2224  2224 D a       : Closing database...
07-28 12:43:45.341  6730  6730 D BluetoothPermissionRequest: onReceive
,07-28 12:43:45.342  6730  6730 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,07-28 12:43:45.344  6730  6730 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:43:45.346  6849  6849 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-28 12:43:45.347  6849  6849 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-28 12:43:45.353  6849  6849 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-28 12:43:45.380  6849  6849 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,07-28 12:43:45.381  6849  6849 V BtOppService: onCreate
,07-28 12:43:45.387  6849  6849 V BluetoothOppNotification: send message
07-28 12:43:45.390  6849  6849 V BtOppService: Starting RfcommListener
07-28 12:43:45.397  6849  6849 D BluetoothOppPreference: Dumping Names:  
07-28 12:43:45.397  6849  6849 D BluetoothOppPreference: {}
07-28 12:43:45.397  6849  6849 D BluetoothOppPreference: Dumping Channels:  
07-28 12:43:45.397  6849  6849 D BluetoothOppPreference: {}
,07-28 12:43:45.398  6849  6849 V BtOppService: onStartCommand
07-28 12:43:45.403  6849  7448 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:43:45.403  6849  6849 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:45.403  6849  6849 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:43:45.407  6849  6849 V BluetoothOppNotification: new notify threadi!
07-28 12:43:45.408  6849  6849 V BluetoothOppNotification: send delay message
07-28 12:43:45.409  6849  7448 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:43:45.410  6849  6849 V BtOppService: start RfcommListener
07-28 12:43:45.412  6849  7449 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-28 12:43:45.414  6849  6849 V BtOppService: RfcommListener started
07-28 12:43:45.416  6849  7450 V BtOppRfcommListener: Starting RFCOMM listener....
07-28 12:43:45.417  6849  7448 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@393b69f6 on behalf of 
07-28 12:43:45.418  6849  7449 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22d941f7 on behalf of 
07-28 12:43:45.419  6849  7449 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:43:45.420  6849  7445 V BtOppService: Deleted complete outbound shares, number =  0
07-28 12:43:45.420  6849  7448 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:43:45.420  6849  7449 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:43:45.422  1038  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:45.425  6849  7445 V BtOppService: Deleted complete inbound failed shares, number = 0
07-28 12:43:45.426  6849  7445 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,07-28 12:43:45.428  6849  7450 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:45.429  6849  7445 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4a48864 on behalf of 
07-28 12:43:45.432  6849  7450 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
07-28 12:43:45.432  6849  7450 V BtOppRfcommListener: Started RFCOMM listener....
07-28 12:43:45.432  6849  7450 I BtOppRfcommListener: Accept thread started.
07-28 12:43:45.433  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:45.433  6849  7450 V BtOppRfcommListener: Accepting connection...
07-28 12:43:45.433  6849  6849 V BluetoothFtpService: Ftp Service onCreate
07-28 12:43:45.433  6849  6849 I BluetoothFtpService: Ftp Service onCreate
07-28 12:43:45.433  6849  6849 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:43:45.433  6849  6849 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:45.433  6849  6849 V BluetoothFtpService: Starting Listening on sockets
07-28 12:43:45.434  6849  6849 V BtOppService: ContentObserver received notification
07-28 12:43:45.435  6849  6849 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:43:45.435  6849  6849 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:43:45.435  6849  6849 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:43:45.435  6849  6849 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:45.435  6849  6849 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 12:43:45.435  6849  6849 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:43:45.437  6849  7451 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,07-28 12:43:45.438  6849  6849 V BtOppService: ContentObserver received notification
07-28 12:43:45.438  6849  7451 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:43:45.438  6849  6849 V BluetoothFtpService: Handler(): got msg=1
07-28 12:43:45.439  6849  7449 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cac2f82 on behalf of 
07-28 12:43:45.439  6849  6849 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 12:43:45.439  6849  6849 V BluetoothFtpService: Ftp Service initSocket
07-28 12:43:45.440  6849  7451 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c560693 on behalf of 
07-28 12:43:45.442  1038  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:45.442  6849  7449 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:43:45.442  6849  7451 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:43:45.443  6849  6849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:45.444  6849  7451 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:43:45.444  6849  7451 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:43:45.445  6849  7451 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f53c6d0 on behalf of 
07-28 12:43:45.445  6849  7449 V BluetoothOppNotification: outbound notification was removed.
07-28 12:43:45.445  6849  6849 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
07-28 12:43:45.445  6849  7449 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:43:45.446  6849  6849 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 12:43:45.446  6849  7451 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:43:45.448  6849  7452 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 12:43:45.449  6849  7451 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:43:45.450  6849  7449 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21f36c9 on behalf of 
07-28 12:43:45.451  6849  7449 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-28 12:43:45.452  6849  7449 V BluetoothOppNotification: inbound notification was removed.
07-28 12:43:45.452  6849  7449 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:43:45.453  6849  7449 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1271c1ce on behalf of 
07-28 12:43:45.460  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:45.461  6849  6849 V BluetoothSapService: Sap Service onCreate
07-28 12:43:45.462  6849  6849 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:45.462  6849  6849 V BluetoothSapService: state: 12
07-28 12:43:45.462  6849  6849 V BluetoothSapService: Starting SAP server process
,07-28 12:43:45.464  6849  6849 V BluetoothSapService: SAP Service startRfcommListenerThread
07-28 12:43:45.448  7453  7453 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:45.448  7453  7453 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:43:45.466  6849  7454 V BluetoothSapService: Sap Service initRfcommSocket
07-28 12:43:45.466  1038  2059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:45.467  6849  7454 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:45.468  6849  7454 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-28 12:43:45.468  6849  7454 V BluetoothSapService: Succeed to create listening socket 
07-28 12:43:45.468  6849  7454 V BluetoothSapService: Accepting socket connection...
07-28 12:43:45.474  7453  7453 V BT_SAP  : Event pipe created
07-28 12:43:45.474  7453  7453 V BT_SAP  : create_server_socket qcom.sap.server
07-28 12:43:45.474  7453  7453 V BT_SAP  : created socket fd 6
,07-28 12:43:45.525  7065  7099 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-28 12:43:46.141  1038  1538 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:43:46.141  1038  1538 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:43:46.178  1038  1540 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-28 12:43:46.179  1038  1540 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-28 12:43:46.293  1038  1992 I ActivityManager: Killing 7223:com.lge.bnr/1000 (adj 15): empty #17
,07-28 12:43:46.328  1038  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_7223/cgroup.procs: No such file or directory
,07-28 12:43:46.411  6849  6849 V BluetoothOppNotification: new notify threadi!
,07-28 12:43:46.411  6849  6849 V BluetoothOppNotification: send delay message
,07-28 12:43:46.424  6849  7466 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:43:46.428  6849  7466 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dec2cda on behalf of 
07-28 12:43:46.429  6849  7466 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:43:46.431  6849  7466 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,07-28 12:43:46.434  6849  7466 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dd5b50b on behalf of 
07-28 12:43:46.435  6849  7466 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:43:46.437  6849  7466 V BluetoothOppNotification: outbound notification was removed.
07-28 12:43:46.437  6849  7466 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:43:46.438  6849  7466 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32a99fe8 on behalf of 
07-28 12:43:46.441  6849  7466 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:43:46.442  6849  7466 V BluetoothOppNotification: inbound notification was removed.
07-28 12:43:46.442  6849  7466 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:43:46.443  6849  7466 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1661f601 on behalf of 
,07-28 12:43:46.513  1038  2059 I ActivityManager: Killing 6749:com.lge.sync/1000 (adj 15): empty #17
,07-28 12:43:46.544  1038  1545 D WifiService: Client connection lost with reason: 4
,07-28 12:43:46.556  1038  1992 W libprocessgroup: failed to open /acct/uid_1000/pid_6749/cgroup.procs: No such file or directory
,07-28 12:43:47.148  1038  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:43:47.149  1038  1738 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@21b5407f mBinding = false
,07-28 12:43:47.174  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:43:47.174  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:43:47.174  1038  1038 D Ulp_jni : JNI:system_update. Event-4
,07-28 12:43:47.177  1038  1120 D BluetoothManagerService: Message: 2
07-28 12:43:47.178  1038  1120 D BluetoothManagerService: Sending off request.
07-28 12:43:47.179  6849  7331 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 12:43:47.179  6849  7309 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 12:43:47.179  6849  7309 D BluetoothAdapterProperties: Setting state to 13
07-28 12:43:47.179  6849  7309 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:43:47.180  6849  7309 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:43:47.180  6849  7309 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:43:47.182  6849  7313 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:43:47.184  6849  7309 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:43:47.187  6849  7309 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-28 12:43:47.190  6849  7440 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:47.190  6849  7450 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:47.191  6849  7452 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:47.191  6849  7454 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:47.192  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 12:43:47.192  6849  7381 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 12:43:47.194  6849  7438 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 12:43:47.194  6849  7438 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:47.194  6849  7438 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 12:43:47.194  6849  7438 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 12:43:47.194  6849  7438 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 12:43:47.194  6849  7438 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 12:43:47.194  6849  7438 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 12:43:47.194  6849  7438 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-28 12:43:47.197  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:47.197  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:47.197  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:43:47.197  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:47.197  6849  7381 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:47.197  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:47.198  6849  7381 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:47.198  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:43:47.198  6849  7381 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:47.198  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 12:43:47.198  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 12:43:47.198  6849  7381 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:43:47.209  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:47.209  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:47.209  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:47.209  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:47.209  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:47.209  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:47.209  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:47.209  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:47.209  6549  6549 V io.,jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:47.214  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:47.214  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:47.218  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:47.218  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:47.218  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:47.218  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:47.218  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:47.218  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:47.218  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:47.218  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:47.218  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:47.220  6549  6549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:47.220  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:47.221  1038  1120 D BluetoothManagerService: Message: 60
07-28 12:43:47.221  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 12:43:47.221  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,07-28 12:43:47.226  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:43:47.228  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:47.233  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:47.237  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:47.239  6849  6849 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:47.239  6849  6849 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:43:47.239  6849  6849 V BluetoothMapService: Handler(): got msg=4
07-28 12:43:47.239  6849  6849 D BluetoothMapService: MAP Service closeService in
07-28 12:43:47.239  6849  6849 D BluetoothMapMasInstance: MAP Service shutdown
07-28 12:43:47.240  6849  6849 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:43:47.241  6849  6849 V BluetoothMapService: MAP Service closeService out
07-28 12:43:47.242  6849  6849 V BtOppService: Receiver DISABLED_ACTION 
07-28 12:43:47.242  6849  6849 I BtOppRfcommListener: stopping Accept Thread
07-28 12:43:47.242  6849  6849 V BtOppRfcommListener: close mBtServerSocket
07-28 12:43:47.243  6849  7450 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:43:47.243  6849  6849 V BtOppRfcommListener: waiting for thread to terminate
07-28 12:43:47.244  6849  6849 V BtOppRfcommListener: done waiting for thread to terminate
07-28 12:43:47.246  6730  6730 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,07-28 12:43:47.259  6730  6730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-28 12:43:47.265  6849  6849 V BtOppService: onDestroy
07-28 12:43:47.266  6849  6849 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-28 12:43:47.270  6849  6849 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:43:47.270  6849  6849 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:47.270  6849  6849 V BluetoothPbapReceiver: ***********state = 13
07-28 12:43:47.271  6849  6849 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,07-28 12:43:47.276  6849  6849 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:47.276  6849  6849 V BluetoothPbapService: state: 13
07-28 12:43:47.276  6849  6849 V BluetoothPbapService: Pbap Service closeService in
07-28 12:43:47.279  2224  2224 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:43:47.280  6849  6849 V BluetoothPbapService: successfully stopped pbap service
07-28 12:43:47.280  6849  6849 V BluetoothPbapService: Pbap Service closeService out
07-28 12:43:47.283  6849  6849 V BluetoothPbapService: Pbap Service onDestroy
07-28 12:43:47.283  6849  6849 V BluetoothPbapService: Pbap Service closeService in
07-28 12:43:47.283  6849  6849 V BluetoothPbapService: Pbap Service closeService out
07-28 12:43:47.283  6849  6849 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-28 12:43:47.308  6730  6730 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:43:47.311  6730  6730 D BluetoothPbap: Proxy object disconnected
07-28 12:43:47.311  6730  6730 D PbapServerProfile: Bluetooth service disconnected
07-28 12:43:47.317  6730  6730 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 12:43:47.323  6730  6730 D BluetoothPermissionRequest: onReceive
07-28 12:43:47.323  6730  6730 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-28 12:43:47.331  6730  6730 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:43:47.335  6849  6849 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-28 12:43:47.335  6849  6849 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-28 12:43:47.335  6849  6849 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,07-28 12:43:47.340  6849  6849 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:47.340  6849  6849 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,07-28 12:43:47.341  6849  6849 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:43:47.341  6849  6849 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:47.341  6849  6849 V BluetoothFtpService: Ftp Service closeService
07-28 12:43:47.342  6849  6849 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-28 12:43:47.343  6849  6849 V BluetoothFtpService: successfully stopped ftp service
07-28 12:43:47.344  6849  6849 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:43:47.344  6849  6849 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:43:47.344  6849  6849 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:43:47.344  6849  6849 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:47.344  6849  6849 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 12:43:47.344  6849  6849 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:43:47.346  6849  6849 V BluetoothFtpService: Ftp Service onDestroy
07-28 12:43:47.346  6849  6849 V BluetoothFtpService: Ftp Service closeService
07-28 12:43:47.347  6849  6849 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:47.347  6849  6849 V BluetoothSapService: state: 13
07-28 12:43:47.347  6849  6849 V BluetoothSapService: Stopping SAP server process
,07-28 12:43:47.350  6849  6849 V BluetoothSapService: Sap Service closeSapService in
07-28 12:43:47.350  6849  6849 V BluetoothSapService: Close listen Socket : 
07-28 12:43:47.350  6849  6849 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:43:47.351  6849  6849 V BluetoothSapService: Close sapd  Socket : 
07-28 12:43:47.353  6849  6849 V BluetoothSapService: Sap Service closeSapService out
07-28 12:43:47.353  6849  6849 V BluetoothSapService: Sap Service onDestroy
07-28 12:43:47.353  6849  6849 V BluetoothSapService: Sap Service closeSapService in
07-28 12:43:47.353  6849  6849 V BluetoothSapService: Close listen Socket : 
07-28 12:43:47.353  6849  6849 V BluetoothSapService: Close rfcomm Socket : 
07-28 12:43:47.353  6849  6849 V BluetoothSapService: Close sapd  Socket : 
07-28 12:43:47.353  6849  6849 V BluetoothSapService: Sap Service closeSapService out
07-28 12:43:47.453  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-28 12:43:47.453  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-28 12:43:47.463  1605  1605 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 306
,07-28 12:43:47.466  1969  2144 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-28 12:43:47.466  1969  2144 D LEDHandler: Battery Level Remaining: 100%
07-28 12:43:47.466  1969  2144 D LEDHandler: Battery Temp: 306, mChargingStatus=5, mChargingStop=false
07-28 12:43:47.467  1038  1545 D WifiController: battery changed pluggedType: 2
,07-28 12:43:47.473  6849  7348 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-28 12:43:47.472  1605  1605 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-28 12:43:47.478  1605  1605 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-28 12:43:48.099  6849  7313 D bt_hci_bdroid: cleanup
,07-28 12:43:48.108  6849  7383 I bt_lpm  : LPM is already off!!!
07-28 12:43:48.108  6849  7410 I bt_userial_mct: exiting userial_read_thread
07-28 12:43:48.108  6849  7410 D bt_userial_mct: Leaving userial_evt_read_thread()
07-28 12:43:48.108  6849  7381 W bt-btif : ag scb idx 1 not allocated
07-28 12:43:48.108  6849  7381 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:43:48.108  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:48.108  6849  7381 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:48.108  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:48.108  6849  7381 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 12:43:48.109  6849  7381 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:48.109  6849  7381 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 12:43:48.110  6849  7313 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-28 12:43:48.110  6849  7383 I bt_vendor: hw_epilog_process
07-28 12:43:48.110  6849  7313 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 12:43:48.110  6849  7313 D bt_userial_mct: userial_close
07-28 12:43:48.110  6849  7313 E bt_userial_mct: pthread_join() FAILED result:3
07-28 12:43:48.110  6849  7313 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-28 12:43:48.115  6849  7313 D bt_hci_bdroid: set_power 0
07-28 12:43:48.116  6849  7313 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-28 12:43:48.116  6849  7313 I bt_vendor: bluetooth satus is on
07-28 12:43:48.116  6849  7313 I bt_vendor: bt-vendor : resetting BT status
07-28 12:43:48.116  6849  7313 I bt_vendor: Starting hciattach daemon
07-28 12:43:48.116  6849  7313 I bt_vendor: try to set false
07-28 12:43:48.119  6849  7313 I bt_vendor: Starting hciattach daemon
07-28 12:43:48.119  6849  7313 I bt_vendor: try to set false
,07-28 12:43:48.124  6849  7313 I bt_vendor: cleanup
07-28 12:43:48.125  6849  7381 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:43:48.125  6849  7313 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:43:48.125  6849  7313 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 12:43:48.127  6849  7309 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:43:48.131  6849  6849 D HeadsetService: Received stop request...Stopping profile...
,07-28 12:43:48.135  6849  6849 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:43:48.135  6849  6849 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:43:48.135  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:48.136  6849  7348 D HeadsetStateMachine: Exit Disconnected: -1
07-28 12:43:48.139  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 12:43:48.139  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 12:43:48.139  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 12:43:48.139  1038  1038 D BluetoothHeadset: Proxy object disconnected
07-28 12:43:48.139  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 12:43:48.141  6849  6849 D A2dpService: Received stop request...Stopping profile...
07-28 12:43:48.142  6849  7371 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:43:48.146  6849  6849 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,07-28 12:43:48.150  6849  7309 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:43:48.152  6849  6849 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-28 12:43:48.152  6849  6849 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:43:48.152  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:48.153  1038  1038 D BluetoothA2dp: Proxy object disconnected
07-28 12:43:48.153  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 12:43:48.155  6849  6849 D HidService: Received stop request...Stopping profile...
07-28 12:43:48.155  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:48.157  6849  6849 D HealthService: Received stop request...Stopping profile...
07-28 12:43:48.157  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:48.159  6849  6849 D HeadsetStateMachine: Unbinding service...
,07-28 12:43:48.164  6849  6849 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:43:48.164  6849  6849 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:43:48.164  6849  6849 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:43:48.164  6849  6849 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:43:48.164  6849  6849 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:43:48.164  6849  6849 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:43:48.164  6849  6849 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 12:43:48.166  6849  6849 D PanService: Received stop request...Stopping profile...
07-28 12:43:48.166  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:48.167  6849  6849 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:43:48.168  6849  6849 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:43:48.168  6849  6849 D BtGatt.GattService: stop()
07-28 12:43:48.168  6849  6849 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:43:48.169  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
07-28 12:43:48.170  6849  6849 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:43:48.170  6849  6849 D BluetoothMapService: stop()
07-28 12:43:48.170  6849  6849 D BluetoothMapEmailAppObserver: deinitObservers()
07-28 12:43:48.171  6849  6849 D BluetoothMapEmailAppObserver: removeReceiver()
07-28 12:43:48.173  6849  6849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1678fcc5
,07-28 12:43:48.176  6849  6849 I BluetoothA2dpServiceJni: cleanupNative
07-28 12:43:48.177  6849  7372 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:43:48.177  6849  6849 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:43:48.177  6849  6849 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:43:48.177  6849  6849 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:43:48.178  6849  6849 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:43:48.178  6849  6849 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:43:48.180  6849  6849 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:43:48.180  6849  6849 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:43:48.180  6849  6849 V BluetoothMapService: Handler(): got msg=4
07-28 12:43:48.180  6849  6849 D BluetoothMapService: MAP Service closeService in
07-28 12:43:48.180  6849  6849 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:43:48.180  6849  6849 V BluetoothMapService: MAP Service closeService out
07-28 12:43:48.181  6849  7309 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:43:48.181  6849  7309 D BluetoothAdapterProperties: Setting state to 10
07-28 12:43:48.181  6849  7309 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:43:48.182  1038  1120 D BluetoothManagerService: Message: 60
07-28 12:43:48.182  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 12:43:48.182  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
07-28 12:43:48.182  6849  7309 I BluetoothAdapterState: Entering OffState
07-28 12:43:48.183  6730  7431 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:43:48.185  6849  6849 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:43:48.185  6849  6849 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-28 12:43:48.189  6849  6849 D BluetoothMapService: cleanup()
07-28 12:43:48.189  6849  6849 D BluetoothMapService: MAP Service closeService in
07-28 12:43:48.189  6849  6849 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 12:43:48.189  6849  6849 V BluetoothMapService: MAP Service closeService out
07-28 12:43:48.191  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:43:48.191  6730  7431 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:43:48.198  6730  6745 D BluetoothPbap: onBluetoothStateChange: up=false
,07-28 12:43:48.202  6730  6745 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:43:48.203  6730  7431 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:43:48.203  6730  6745 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:43:48.204  1879  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:43:48.204  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:43:48.205  1879  1895 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:43:48.205  1879  2570 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:43:48.206  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 12:43:48.206  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 12:43:48.208  1038  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 12:43:48.208  1038  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-28 12:43:48.208  1038  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@21b5407f mBinding = false
07-28 12:43:48.209  1038  1120 D BluetoothManagerService: Sending unbind request.
07-28 12:43:48.214  6849  7313 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-28 12:43:48.218  6849  6849 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:43:48.218  6849  6849 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:43:48.218  6849  6849 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:43:48.218  6849  6849 I art     : --- WEIRD: removing null entry 248
07-28 12:43:48.219  6849  6849 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
07-28 12:43:48.219  6849  6849 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-28 12:43:48.220  6849  6849 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-28 12:43:48.221  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-28 12:43:48.223  6849  6849 I art     : System.exit called, status: 0
07-28 12:43:48.223  6849  6849 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:43:48.243   315   315 V AudioFlinger: 6849 died, releasing its sessions
07-28 12:43:48.243   315   315 V AudioFlinger:  pid 1879 @ 0
07-28 12:43:48.243   315   315 V AudioFlinger:  pid 3364 @ 1
07-28 12:43:48.243   315   315 V AudioFlinger:  pid 3364 @ 2
,07-28 12:43:48.253  6730  6730 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,07-28 12:43:48.253  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
07-28 12:43:48.254  1969  2177 D LGBluetoothAPIService: Message: 101
07-28 12:43:48.254  1969  2177 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
,07-28 12:43:48.254  1969  2177 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
07-28 12:43:48.255  1969  2177 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
07-28 12:43:48.455  1038  1983 I ActivityManager: Process com.android.bluetooth (pid 6849) has died
07-28 12:43:48.456  1038  1983 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
07-28 12:43:48.457  1038  1983 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,07-28 12:43:48.469  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:48.470  1969  2177 D LGBluetoothAPIService: Message: 2
07-28 12:43:48.470  1969  2177 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
07-28 12:43:48.471  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:43:48.477  6730  6730 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 12:43:48.477  6730  6730 D LGBluetoothEventManager: [BTUI] clear device connection state
,07-28 12:43:48.483  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:48.484  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:48.484  6730  6730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:43:48.488  1605  1605 D BluetoothAdapter: 958696038: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:48.488  1605  1605 D BluetoothAdapter: 958696038: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:48.551  1038  2058 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7515 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-28 12:43:48.554  6730  6730 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:43:48.626  7515  7515 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 12:43:48.627  7515  7515 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 12:43:48.627  7515  7515 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 12:43:48.628  7515  7515 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 12:43:48.647  7515  7515 D BluetoothAdapterApp: Loading JNI Library
,07-28 12:43:48.684  7515  7515 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d8b90d Instance Count = 1
,07-28 12:43:48.690  7515  7515 D BluetoothAdapterApp: onCreate
07-28 12:43:48.716  7515  7515 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,07-28 12:43:48.717  7515  7515 D ProfileConfigQcom: Adding HeadsetService
07-28 12:43:48.718  7515  7515 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-28 12:43:48.718  7515  7515 D ProfileConfigQcom: Adding A2dpService
,07-28 12:43:48.719  7515  7515 D ProfileConfigQcom: [BTUI] HidService is supported
07-28 12:43:48.719  7515  7515 D ProfileConfigQcom: Adding HidService
07-28 12:43:48.720  7515  7515 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 12:43:48.720  7515  7515 D ProfileConfigQcom: Adding HealthService
07-28 12:43:48.721  7515  7515 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-28 12:43:48.723  7515  7515 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 12:43:48.723  7515  7515 D ProfileConfigQcom: Adding PanService
07-28 12:43:48.724  7515  7515 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 12:43:48.724  7515  7515 D ProfileConfigQcom: Adding GattService
07-28 12:43:48.725  7515  7515 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 12:43:48.725  7515  7515 D ProfileConfigQcom: Adding BluetoothMapService
07-28 12:43:48.726  7515  7515 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-28 12:43:48.728  7515  7515 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:43:48.731  7515  7515 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:48.732  7515  7515 V BluetoothPbapReceiver: ***********state = 10
07-28 12:43:48.736  7515  7515 V LGMDMManagerInternal: Create singleton instance
,07-28 12:43:48.818  2224  2224 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:48.818  7515  7515 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 12:43:48.818  7515  7515 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 12:43:48.821  6730  6730 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 12:43:48.822  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 12:43:48.822  1969  2177 D LGBluetoothAPIService: Message: 100
07-28 12:43:48.822  1969  2177 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-28 12:43:48.842  6730  6730 D BluetoothPermissionRequest: onReceive
,07-28 12:43:48.846  6730  6730 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,07-28 12:43:48.846  6730  6730 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,07-28 12:43:48.848  6730  6730 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:43:48.858  7515  7515 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,07-28 12:43:48.862  7515  7515 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:48.865  7515  7515 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:43:48.865  7515  7515 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:43:48.866  7515  7515 V BluetoothSapReceiver: SapReceiver onReceive 
,07-28 12:43:48.866  7515  7515 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:48.866  7515  7515 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-28 12:43:48.868  6795  6795 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-28 12:43:50.258  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:50.258  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:50.465  2095  2095 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-28 12:43:50.480  1038  1443 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:43:50.487  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
07-28 12:43:50.580  1038  1105 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7543 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-28 12:43:50.587  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-28 12:43:50.587  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-28 12:43:50.605  1038  1038 D administrator: Handling package changes for user 0
,07-28 12:43:50.617  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:43:50.657  7543  7543 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-28 12:43:50.698  1038  1038 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-28 12:43:50.698  1038  1038 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-28 12:43:50.731  1038  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:43:50.735  1038  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-28 12:43:50.740  2095  2095 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-28 12:43:50.742  2502  2502 V GmsNetworkLocationProvi: DISABLE
,07-28 12:43:50.757  7543  7543 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:50.757  7543  7543 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 12:43:50.889  1038  1054 I art     : Explicit concurrent mark sweep GC freed 82787(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.680ms total 140.231ms
,07-28 12:43:50.915  1038  1102 D LocationProviderProxy: applying state to connected service
,07-28 12:43:50.918  2502  2502 E GCoreFlp: Bound FusedProviderService with LocationManager
,07-28 12:43:50.972  7543  7592 I Babel   : MmsConfig: mnc/mcc: 0/0
07-28 12:43:50.972  7543  7592 I Babel   : MmsConfig.loadMmsSettings
07-28 12:43:50.974  7543  7592 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-28 12:43:50.974  7543  7592 I Babel   : MmsConfig.loadFromDatabase
,07-28 12:43:50.979  7543  7543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:50.993  7543  7592 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-28 12:43:50.993  7543  7592 I Babel   : MmsConfig.loadFromResources
07-28 12:43:50.998  7543  7592 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-28 12:43:50.999  7543  7592 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-28 12:43:51.006  6911  6911 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 12:43:51.010  6911  6911 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@32fa852f
07-28 12:43:51.010  6911  6911 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 12:43:51.010  6911  6911 D AppUp4:CustFacade: isPhone : true
07-28 12:43:51.010  1840  7598 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-28 12:43:51.010  6911  6911 D AppUp4:CustModeStarterReceiver: begin check event
07-28 12:43:51.010  1840  7598 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
07-28 12:43:51.010  6911  6911 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-28 12:43:51.018  7543  7590 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:43:51.018  7543  7590 W AudioCapabilities: Unsupported mime audio/qcelp
07-28 12:43:51.019  7543  7590 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-28 12:43:51.027  7543  7590 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-28 12:43:51.029  7543  7590 W AudioCapabilities: Unsupported mime audio/qcelp
07-28 12:43:51.031  7543  7590 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:43:51.048  7543  7590 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-28 12:43:51.049  7543  7590 W VideoCapabilities: Unsupported mime video/divx
07-28 12:43:51.051  7543  7590 W VideoCapabilities: Unsupported mime video/divx311
07-28 12:43:51.052  7543  7590 W VideoCapabilities: Unsupported mime video/divx4
07-28 12:43:51.056  1038  1961 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7602 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
07-28 12:43:51.057  7543  7590 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-28 12:43:51.063  1038  1961 I ActivityManager: Killing 6656:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-28 12:43:51.067  1840  4741 I Icing   : updateResources: need to parse e{com.google.android.gms}
07-28 12:43:51.087  6778  6778 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-28 12:43:51.087  6778  6778 W System.err: android.os.DeadObjectException
07-28 12:43:51.087  6778  6778 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:43:51.087  6778  6778 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:43:51.087  6778  6778 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-28 12:43:51.087  6778  6778 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-28 12:43:51.087  6778  6778 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:43:51.087  6778  6778 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:43:51.087  6778  6778 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:43:51.087  6778  6778 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:43:51.087  6778  6778 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:51.087  6778  6778 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:51.087  6778  6778 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:51.087  6778  6778 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:51.087  6778  6778 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:51.087  6778  6778 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:51.088  6778  6778 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,07-28 12:43:51.088  6778  6778 W System.err: android.os.DeadObjectException
07-28 12:43:51.088  6778  6778 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 12:43:51.088  6778  6778 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 12:43:51.088  6778  6778 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-28 12:43:51.088  6778  6778 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-28 12:43:51.088  6778  6778 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 12:43:51.088  6778  6778 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 12:43:51.088  6778  6778 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:43:51.088  6778  6778 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:43:51.088  6778  6778 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:51.088  6778  6778 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:51.088  6778  6778 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:51.088  6778  6778 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:51.088  6778  6778 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:51.088  6778  6778 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:51.089  6778  6778 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-28 12:43:51.089  6778  6778 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-28 12:43:51.092  7543  7590 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-28 12:43:51.094  7543  7590 W AudioCapabilities: Unsupported mime audio/eac3
07-28 12:43:51.095  7543  7590 W AudioCapabilities: Unsupported mime audio/ac3
07-28 12:43:51.095  7543  7590 W AudioCapabilities: Unsupported mime audio/g726
07-28 12:43:51.096  7543  7590 W AudioCapabilities: Unsupported mime audio/wma-voice
07-28 12:43:51.096  7543  7590 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-28 12:43:51.097  7543  7590 W AudioCapabilities: Unsupported mime audio/adpcm
07-28 12:43:51.098  7543  7590 W VideoCapabilities: Unsupported mime video/theora
07-28 12:43:51.099  7543  7590 W VideoCapabilities: Unsupported mime video/mjpg
,07-28 12:43:51.222  1038  1738 W libprocessgroup: failed to open /acct/uid_1000/pid_6656/cgroup.procs: No such file or directory
07-28 12:43:51.223  1038  1738 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-28 12:43:51.230  6778  6778 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-28 12:43:51.231  6778  6778 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:43:51.255  7602  7602 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:51.255  7602  7602 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:43:51.256  7602  7602 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-28 12:43:51.257  7602  7602 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-28 12:43:51.257  7602  7602 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-28 12:43:51.281  1038  1950 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7620 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:43:51.281  6778  6778 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-28 12:43:51.335  7620  7620 D UEI.SmartControl: Quickset Services start...
,07-28 12:43:51.337  7620  7620 I UEI.SmartControl: Manufacture = LGE
07-28 12:43:51.337  7602  7602 I SystemConfig: BUILD Country: EU
07-28 12:43:51.337  7620  7620 D UEI.SmartControl: Id = LGNevo
07-28 12:43:51.337  7602  7602 I SystemConfig: BUILD Operator: OPEN
07-28 12:43:51.338  7620  7620 D UEI.SmartControl: File observer start...
07-28 12:43:51.338  7620  7620 E UEI.SmartControl: IR Port is disabled: false
07-28 12:43:51.339  7620  7620 D UEI.SmartControl: Starting file observer...
07-28 12:43:51.339  7620  7620 D UEI.SmartControl: Extracting JNI libs...
07-28 12:43:51.339  7620  7620 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-28 12:43:51.371  1038  2059 I ActivityManager: Killing 6778:com.lge.qremote/u0a112 (adj 15): empty #17
,07-28 12:43:51.398  7620  7620 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,07-28 12:43:51.398  7620  7620 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-28 12:43:51.398  7620  7620 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-28 12:43:51.417  7620  7620 I UEI.SmartControl: --- Selecting new region: 6
,07-28 12:43:51.418  7620  7620 I UEI.SmartControl: Model = LG-D855
,07-28 12:43:51.419  7620  7620 D UEI.SmartControl: QS Service created
07-28 12:43:51.446  1038  1053 W libprocessgroup: failed to open /acct/uid_10112/pid_6778/cgroup.procs: No such file or directory
,07-28 12:43:51.452  7602  7639 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,07-28 12:43:51.452  7602  7639 I SystemConfig: existFile = false
07-28 12:43:51.452  7602  7639 I SystemConfig: canReadFile = false
07-28 12:43:51.453  7602  7639 I SystemConfig: systemFeature RCS result false
07-28 12:43:51.453  7602  7639 D SystemConfig: refreshRcsSupport() :false
07-28 12:43:51.461  7620  7620 I UEI.SmartControl: Service initServices...
,07-28 12:43:51.466  7620  7620 D UEI.SmartControl: QS start get config
,07-28 12:43:51.501  1038  2059 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7641 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-28 12:43:51.508  7620  7620 D UEI.SmartControl: Loading JNI Libs...
,07-28 12:43:51.575  7641  7641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:51.576  7641  7641 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-28 12:43:51.576  7641  7641 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-28 12:43:51.576  7641  7641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-28 12:43:51.662  7641  7641 I AppConfig: Total System Memory = 2995761152
,07-28 12:43:51.671  7641  7641 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-28 12:43:51.748  7620  7620 I UEI.SmartControl: Supports setup maps: true
07-28 12:43:51.751  7620  7620 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 12:43:51.752  7620  7620 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:43:51.752  7620  7620 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:43:51.752  7620  7620 I UEI.SmartControl: ### init IR Blaster...
,07-28 12:43:51.758  7620  7620 D serial_port: Configuring serial port
,07-28 12:43:51.762  7620  7620 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:43:51.763  7620  7620 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:43:51.763  7620  7620 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:43:51.763  7620  7620 I UEI.SmartControl: Get version...
07-28 12:43:51.774  1038  1783 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7661 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:51.774  1038  1783 I ActivityManager: Killing 6941:com.lge.email/u0a23 (adj 15): empty #17
07-28 12:43:51.780  7620  7660 D UEI.SmartControl: serial port data available: 21
07-28 12:43:51.807  7620  7620 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:43:51.807  7620  7620 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:43:51.807  7620  7620 I UEI.SmartControl: QS saving settings...
,07-28 12:43:51.808  7620  7620 D UEI.SmartControl: IR Blaster version: 25672567
07-28 12:43:51.821  7620  7660 D UEI.SmartControl: serial port data available: 4
,07-28 12:43:51.838  1038  1053 W libprocessgroup: failed to open /acct/uid_10023/pid_6941/cgroup.procs: No such file or directory
,07-28 12:43:51.852  7620  7680 I UEI.SmartControl: Device manager: loading config....
,07-28 12:43:51.853  7620  7680 D UEI.SmartControl: ----------- loading internal config...
07-28 12:43:51.853  7620  7620 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 12:43:51.859  7620  7620 E UEI.SmartControl: Services init done
07-28 12:43:51.860  7620  7620 D UEI.SmartControl: QS Service init finished
07-28 12:43:51.860  7620  7620 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:43:51.861  7620  7620 D UEI.SmartControl: QS Service version code: 201091
07-28 12:43:51.861  7620  7620 D UEI.SmartControl: Service requested: Control
07-28 12:43:51.865  7620  7680 E UEI.SmartControl: Loading SETTINGS...
,07-28 12:43:51.867  7620  7620 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-28 12:43:51.869  7620  7620 D UEI.SmartControl: Service.onUnbind: IControl
07-28 12:43:51.871  7620  7620 D UEI.SmartControl: Service.onDestroy
07-28 12:43:51.871  7620  7620 D UEI.SmartControl: Lock is in USE false
07-28 12:43:51.871  7620  7620 D UEI.SmartControl: unbind internal service
07-28 12:43:51.875  7620  7620 D serial_port: close(fd = 25)
07-28 12:43:51.876  7620  7680 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 12:43:51.879  7620  7620 I UEI.SmartControl: Serial port is closed.
07-28 12:43:51.879  7620  7620 I UEI.SmartControl: Serial port is closed.
07-28 12:43:51.880  7620  7620 D UEI.SmartControl: Blaster closed
07-28 12:43:51.880  7620  7620 D UEI.SmartControl: Shut down QS...
,07-28 12:43:51.880  7620  7620 D UEI.SmartControl: Stopping QS lib
07-28 12:43:51.880  7620  7620 D UEI.SmartControl: QS lib stop result = true
07-28 12:43:51.880  7620  7620 D UEI.SmartControl: Stopped QS lib
07-28 12:43:51.880  7620  7620 D UEI.SmartControl: Stopped file observer...
07-28 12:43:51.880  7620  7620 D UEI.SmartControl: QS shutdown complete
07-28 12:43:51.884  7620  7620 D UEI.SmartControl: QS Service created
07-28 12:43:51.891  7620  7679 I UEI.SmartControl: Notify AllClients services are ready: 11
07-28 12:43:51.891  7620  7679 D UEI.SmartControl: -----service ready thread exits
07-28 12:43:51.900  7620  7620 I UEI.SmartControl: Service initServices...
,07-28 12:43:51.900  7620  7620 D UEI.SmartControl: QS start get config
07-28 12:43:52.052  7661  7661 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-28 12:43:52.138  7661  7661 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:52.138  7661  7661 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:43:52.188  7661  7661 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-28 12:43:52.211  7661  7661 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-28 12:43:52.212  7661  7661 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-28 12:43:52.229  7661  7661 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-28 12:43:52.229  7661  7661 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-28 12:43:52.238  1038  1383 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c9d826e type 2 when 148870 com.google.android.gms} when 148870
07-28 12:43:52.252  1038  1983 I ActivityManager: Killing 6818:com.lge.formmanager/u0a26 (adj 15): empty #17
,07-28 12:43:52.262  7620  7620 I UEI.SmartControl: Supports setup maps: true
07-28 12:43:52.266  7620  7620 D UEI.SmartControl: QS start statue = true Error code = 0
,07-28 12:43:52.266  7620  7620 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 12:43:52.266  7620  7620 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 12:43:52.266  7620  7620 I UEI.SmartControl: ### init IR Blaster...
,07-28 12:43:52.269  7620  7620 D serial_port: Configuring serial port
07-28 12:43:52.270  7620  7620 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:43:52.270  7620  7620 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:43:52.270  7620  7620 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:43:52.270  7620  7620 I UEI.SmartControl: Get version...
07-28 12:43:52.287  7620  7706 D UEI.SmartControl: serial port data available: 21
07-28 12:43:52.287  1038  2058 W libprocessgroup: failed to open /acct/uid_10026/pid_6818/cgroup.procs: No such file or directory
,07-28 12:43:52.290  3467  3487 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,07-28 12:43:52.291  3467  3487 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3dac2ea3 on behalf of 7661
07-28 12:43:52.295  4605  7707 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
07-28 12:43:52.298  7661  7661 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-28 12:43:52.313  7620  7620 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 12:43:52.313  7620  7620 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 12:43:52.313  7620  7620 I UEI.SmartControl: QS saving settings...
07-28 12:43:52.314  7620  7620 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 12:43:52.331  7620  7706 D UEI.SmartControl: serial port data available: 4
,07-28 12:43:52.349  1038  1961 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7710 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:52.366  7620  7721 I UEI.SmartControl: Device manager: loading config....
,07-28 12:43:52.368  7620  7620 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 12:43:52.370  7620  7721 D UEI.SmartControl: ----------- loading internal config...
07-28 12:43:52.376  7620  7620 E UEI.SmartControl: Services init done
07-28 12:43:52.376  7620  7620 D UEI.SmartControl: QS Service init finished
07-28 12:43:52.382  7620  7620 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 12:43:52.382  7620  7620 D UEI.SmartControl: QS Service version code: 201091
,07-28 12:43:52.383  7620  7620 D UEI.SmartControl: Service requested: Control
07-28 12:43:52.391  7620  7721 E UEI.SmartControl: Loading SETTINGS...
07-28 12:43:52.395  7620  7620 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-28 12:43:52.396  7620  7721 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 12:43:52.404  7661  7661 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
07-28 12:43:52.404  7620  7620 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1234454b that was originally bound here
07-28 12:43:52.404  7620  7620 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1234454b that was originally bound here
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:52.404  7620  7620 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:52.406  7620  7620 D UEI.SmartControl: Internal service binding...
07-28 12:43:52.407  7620  7720 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-28 12:43:52.407  7620  7720 D UEI.SmartControl: -----service ready thread exits
,07-28 12:43:52.410  1038  1992 I ActivityManager: Killing 6360:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,07-28 12:43:52.538  1038  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_6360/cgroup.procs: No such file or directory
07-28 12:43:52.588  7710  7710 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-28 12:43:52.614  7710  7710 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,07-28 12:43:52.615  7710  7710 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-28 12:43:52.615  7710  7710 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-28 12:43:52.615  7710  7710 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-28 12:43:52.615  7710  7710 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-28 12:43:52.615  7710  7710 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,07-28 12:43:52.629   310  7739 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,07-28 12:43:52.630  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-28 12:43:52.641  1038  2058 I ActivityManager: Killing 6972:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-28 12:43:52.675  1038  1992 W libprocessgroup: failed to open /acct/uid_10046/pid_6972/cgroup.procs: No such file or directory
,07-28 12:43:52.872  7620  7682 D UEI.SmartControl: Internal timer expired: 2
,07-28 12:43:52.887  1038  1604 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:43:52.911  4605  7707 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 616 ms] updated apps [took 616 ms] 
,07-28 12:43:53.277  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:43:53.277  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e1c361b added. We now have 6 listener(s)
07-28 12:43:53.277  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:53.291  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:43:53.291  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e6173b8 added. We now have 7 listener(s)
,07-28 12:43:53.292  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:53.296  6549  6673 I System.out: IsBluetoothEnabled
07-28 12:43:53.298  1038  1992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:43:53.298  1038  1992 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,07-28 12:43:53.307  1038  1120 D BluetoothManagerService: Message: 2
07-28 12:43:53.311  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:53.312  1038  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:53.312  1038  1054 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-28 12:43:53.330  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 12:43:53.330  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:43:53.330  1038  1038 D Ulp_jni : JNI:system_update. Event-4
07-28 12:43:53.331  1038  1120 D BluetoothManagerService: Message: 1
07-28 12:43:53.331  1038  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-28 12:43:53.357  1038  1120 D BluetoothManagerService: Message: 20
07-28 12:43:53.357  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c5b77f7:true
,07-28 12:43:53.361  7515  7515 D BluetoothAdapterState: make
07-28 12:43:53.367  7515  7515 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 12:43:53.367  7515  7515 I bluedroid-qcom: init
07-28 12:43:53.369  7515  7753 I BluetoothAdapterState: Entering OffState
07-28 12:43:53.369  7515  7515 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:43:53.369  7515  7515 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:43:53.369  7515  7515 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:43:53.369  7515  7515 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:43:53.369  7515  7515 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-28 12:43:53.373  7515  7515 I bluedroid-qcom: get_profile_interface socket
07-28 12:43:53.373  7515  7515 I bluedroid-qcom: get_profile_interface map_client
,07-28 12:43:53.377  7515  7757 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 12:43:53.368  7756  7756 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:53.382  7515  7757 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 12:43:53.368  7756  7756 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:53.394  7756  7756 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 12:43:53.394  7756  7756 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 12:43:53.394  7756  7756 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,07-28 12:43:53.399  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-28 12:43:53.399  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:43:53.399  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 12:43:53.399  1038  1120 D BluetoothManagerService: Message: 40
07-28 12:43:53.399  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 12:43:53.400  7515  7530 I bluedroid-qcom: config_hci_snoop_log
07-28 12:43:53.402  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-28 12:43:53.402  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-28 12:43:53.402  7515  7757 D BluetoothAdapterProperties: Name is: G3
07-28 12:43:53.403  7756  7756 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-28 12:43:53.409  7756  7756 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 12:43:53.409  7756  7756 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,07-28 12:43:53.415  7515  7753 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 12:43:53.416  7515  7753 D BluetoothAdapterProperties: Setting state to 11
07-28 12:43:53.416  7515  7753 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:43:53.417  1038  1120 D BluetoothManagerService: Message: 60
07-28 12:43:53.417  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 12:43:53.418  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-28 12:43:53.417  7515  7753 I LGBluetoothServiceJni: classInitNative: succeeds
,07-28 12:43:53.423  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:53.426  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:43:53.428  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:53.432  6730  6730 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-28 12:43:53.438  7515  7515 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:43:53.438  7515  7515 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:53.438  7515  7515 V BluetoothPbapReceiver: ***********state = 11
,07-28 12:43:53.444  2224  2224 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:43:53.459  7515  7753 D BluetoothBondStateMachine: make
,07-28 12:43:53.466  6730  6730 D BluetoothPermissionRequest: onReceive
07-28 12:43:53.470  7515  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:53.470  7515  7753 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 12:43:53.470  7515  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:53.471  7515  7753 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 12:43:53.471  7515  7753 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-28 12:43:53.473  7515  7759 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:43:53.483  7515  7753 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:53.493  6730  6730 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-28 12:43:53.500  7515  7515 D HeadsetService: Received start request. Starting profile...
07-28 12:43:53.500  7515  7515 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:43:53.501  7515  7515 D LGBluetoothHfpAdapter: Version 1.6
,07-28 12:43:53.504  7515  7753 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:53.504  7515  7515 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:43:53.505  7515  7515 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:43:53.505  7515  7515 D HeadsetStateMachine: make
07-28 12:43:53.509  7515  7753 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:43:53.517  7515  7753 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:53.521  7515  7753 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:53.526  7515  7753 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 12:43:53.531  7515  7753 E BluetoothAdapterService: File transfer profiles supported!!
07-28 12:43:53.538  7515  7515 D LgDataFeature: LgDataFeature() Constructor: none
,07-28 12:43:53.538  7515  7515 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:43:53.542  7515  7515 D HeadsetStateMachine: max_hf_connections = 1
07-28 12:43:53.542  7515  7515 I bluedroid-qcom: get_profile_interface handsfree
07-28 12:43:53.544  7515  7515 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 12:43:53.544   315   315 V AudioPolicyService: registerClient() client 0xb558a220, uid 1002
07-28 12:43:53.545   315  1388 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:43:53.545   315  1388 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:43:53.545   315  1388 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:43:53.545  7515  7515 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 12:43:53.546   315  1387 V AudioFlinger: registerClient() client 0xb1433178, pid 7515
07-28 12:43:53.546   315  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:53.546   315  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:53.546  1038  1577 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:53.546  1038  1577 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:53.546  7515  7531 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:53.546  1605  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:53.546  1605  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:53.546  1879  2540 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:53.547  1879  2540 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:53.547   315  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:53.547   315  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:53.547  7515  7531 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 12:43:53.547  7515  7531 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:53.547  7515  7531 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 12:43:53.547  7515  7515 V ToneGenerator: Create Track: 0xb4928080
07-28 12:43:53.547  7515  7515 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 12:43:53.547  7515  7515 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 12:43:53.547  1605  1941 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:53.547  1605  1941 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:53.547  1879  1895 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:53.547  1879  1895 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:53.547   315  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:43:53.547   315  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 12:43:53.547   315  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:43:53.547   315  1387 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:43:53.547  1038  2059 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:53.547  3364  3384 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 12:43:53.547  3364  3384 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 12:43:53.547  1038  2059 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:53.548  3364  3384 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 12:43:53.548  3364  3384 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 12:43:53.548   315   315 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 ,12:43:53.548   315  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 12:43:53.548   315  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 12:43:53.548   315  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 12:43:53.548   315  1387 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 12:43:53.548  7515  7515 V AudioSystem: getLatency() output 2, latency 50
07-28 12:43:53.548  7515  7515 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 12:43:53.548  7515  7515 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 12:43:53.548   315  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:43:53.548   315  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:43:53.548   315  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 12:43:53.548   315  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 12:43:53.548   315  1388 V AudioFlinger: createTrack() lSessionId: 23
07-28 12:43:53.549  7515  7515 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 12:43:53.549   315   315 V AudioFlinger: acquiring 23 from 7515, for 7515
07-28 12:43:53.549   315   315 V AudioFlinger:  added new entry for 23
07-28 12:43:53.549  7515  7515 V ToneGenerator: ToneGenerator INIT OK, time: 150194
07-28 12:43:53.549  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:53.550  7515  7774 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 12:43:53.550  7515  7774 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 12:43:53.551  7515  7774 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 12:43:53.551  7515  7774 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-28 12:43:53.551   315  1387 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7515
07-28 12:43:53.551  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:53.551   315  1387 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-28 12:43:53.551   315  1387 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 12:43:53.551   315  1387 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 12:43:53.551   315  1387 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 12:43:53.551   315  1387 V voice   : voice_set_parameters: exit with code(0)
07-28 12:43:53.551   315  1387 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-28 12:43:53.551   315  1387 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 12:43:53.552   315  1387 V msm8974_platform: platform_set_parameters: exit with code(0)
07-28 12:43:53.552   315  1387 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 12:43:53.552   315  1387 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 12:43:53.552   315  1387 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-28 12:43:53.552  7515  7774 V ToneGenerator: ToneGenerator destructor
07-28 12:43:53.552  7515  7774 V ToneGenerator: stopTone
07-28 12:43:53.552  7515  7774 V ToneGenerator: Delete Track: 0xb4928080
07-28 12:43:53.553  7515  7515 D A2dpService: Received start request. Starting profile...
07-28 12:43:53.554  7515  7515 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:43:53.554  7515  7753 V LGMDMManager: Create singleton instance
,07-28 12:43:53.555  7515  7515 V Avrcp   : make
,07-28 12:43:53.556  7515  7515 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 12:43:53.556  7515  7774 V AudioTrack: ~AudioTrack, releasing session id from 7515 on behalf of 7515
07-28 12:43:53.556  7515  7515 I bluedroid-qcom: get_profile_interface avrcp
07-28 12:43:53.556   315   315 V AudioFlinger: releasing 23 from 7515 for 7515
07-28 12:43:53.556   315   315 V AudioFlinger:  decremented refcount to 0
07-28 12:43:53.556   315   315 V AudioFlinger: purging stale effects
07-28 12:43:53.556   315   315 V AudioPolicyService: AudioCommandThread() adding release output 2
07-28 12:43:53.557   315   315 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 12:43:53.557   315  1276 V AudioPolicyService: AudioCommandThread() waking up
07-28 12:43:53.557   315  1276 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 12:43:53.557   315  1276 V AudioPolicyManager: releaseOutput() 2
07-28 12:43:53.557   315  1276 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 12:43:53.557   315   315 V AudioFlinger: PlaybackThread::Track destructor
07-28 12:43:53.557   315   315 V AudioFlinger: removeClient_l() pid 7515, calling pid 315
07-28 12:43:53.559  1038  1738 W Process : Unable to open /proc/7777/status
07-28 12:43:53.560  7515  7753 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 12:43:53.566  7515  7515 V AudioManager: registerRemoteController: size of Media player list: 0
,07-28 12:43:53.568  7515  7515 E AudioManager: No RCC entry present to update
07-28 12:43:53.568  7515  7515 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 12:43:53.572  7515  7515 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 12:43:53.573  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-28 12:43:53.573  7515  7515 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-28 12:43:53.577  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:43:53.700  1038  2090 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:43:53.700  1038  2090 V SIM_STK : Menu title from STK is T-Mobile
,07-28 12:43:53.840  1038  1738 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-28 12:43:53.863  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-28 12:43:53.870  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:43:53.871  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:43:53.871  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:43:53.871  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:43:53.871  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:43:53.872  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:43:53.872  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:43:53.872  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:43:53.872  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:43:53.872  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 12:43:53.872  7515  7515 I BluetoothA2dpServiceJni: classInitNative
07-28 12:43:53.873  7515  7515 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:43:53.873  7515  7515 D A2dpStateMachine: make
07-28 12:43:53.874  7515  7515 I bluedroid-qcom: get_profile_interface a2dp
07-28 12:43:53.874  7515  7789 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,07-28 12:43:53.877  7515  7515 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:43:53.877  7515  7515 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 12:43:53.879  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:53.879  7515  7788 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:43:53.880  7515  7515 I BluetoothHidServiceJni: classInitNative: succeeds
07-28 12:43:53.883  7515  7515 D HidService: Received start request. Starting profile...
07-28 12:43:53.883  7515  7515 I bluedroid-qcom: get_profile_interface hidhost
07-28 12:43:53.883  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:53.884  7515  7515 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:43:53.886  7515  7515 D HealthService: Received start request. Starting profile...
07-28 12:43:53.889  7515  7515 I bluedroid-qcom: get_profile_interface health
,07-28 12:43:53.889  7515  7515 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,07-28 12:43:53.889  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
,07-28 12:43:53.891  7515  7515 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-28 12:43:53.893  7515  7515 D PanService: Received start request. Starting profile...
07-28 12:43:53.893  7515  7515 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:43:53.893  7515  7515 I bluedroid-qcom: get_profile_interface pan
07-28 12:43:53.903  7515  7515 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-28 12:43:53.903  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:53.904  7515  7515 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,07-28 12:43:53.914  7515  7515 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:43:53.914  7515  7515 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:43:53.914  7515  7515 D BtGatt.GattService: start()
07-28 12:43:53.914  7515  7515 I bluedroid-qcom: get_profile_interface gatt
07-28 12:43:53.915  7515  7515 D BtGatt.AdvertiseManager: advertise manager created
07-28 12:43:53.922  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
,07-28 12:43:53.924  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:53.925  7515  7515 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 12:43:53.926  7515  7515 V BluetoothMapService: BluetoothMapBinder()
07-28 12:43:53.927  7515  7515 D BluetoothMapService: Received start request. Starting profile...
07-28 12:43:53.927  7515  7515 D BluetoothMapService: start()
07-28 12:43:53.931  7515  7515 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 12:43:53.931  7515  7515 D BluetoothMapEmailAppObserver: createReceiver()
07-28 12:43:53.933  7515  7515 D BluetoothMapEmailAppObserver: initObservers()
07-28 12:43:53.933  7515  7515 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-28 12:43:53.942  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:53.943  7515  7515 D HeadsetStateMachine: Proxy object connected
07-28 12:43:53.944  7515  7515 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 12:43:53.944  7515  7515 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,07-28 12:43:53.946  7515  7774 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 12:43:53.947  7515  7774 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:43:53.947  7515  7774 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,07-28 12:43:53.952  7515  7515 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:43:53.954  7515  7515 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:53.960  7515  7515 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-28 12:43:53.966  7515  7515 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:43:53.970  7515  7515 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 12:43:53.970  7515  7515 V PanService: [BTUI] SIM Extra State :ABSENT
07-28 12:43:53.974  7515  7515 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-28 12:43:53.978  7515  7515 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-28 12:43:53.979  7515  7515 V BluetoothMapService: Handler(): got msg=1
07-28 12:43:53.980  7515  7515 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:43:53.980  7515  7515 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:43:53.980  7515  7515 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:43:53.980  7515  7753 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:43:53.980  7515  7515 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:53.980  7515  7515 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 12:43:53.980  7515  7753 I bluedroid-qcom: enable
07-28 12:43:53.980  7515  7753 I bt_hci_bdroid: init
07-28 12:43:53.983  7515  7753 I bt_vendor: bt-vendor : init
07-28 12:43:53.983  7515  7753 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 12:43:53.983  7515  7753 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-28 12:43:53.983  7515  7753 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 12:43:53.983  7515  7753 D bt_userial_mct: userial_init
07-28 12:43:53.984  7515  7796 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:43:53.984  7515  7796 I bt-btu  : btu_task pending for preload complete event
07-28 12:43:53.985  7515  7753 D bt_hci_bdroid: set_power 1
07-28 12:43:53.985  7515  7753 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 12:43:53.985  7515  7753 I bt_vendor: Starting hciattach daemon
07-28 12:43:53.986  7515  7753 I bt_vendor: try to set true
07-28 12:43:53.978  7799  7799 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:53.978  7799  7799 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:43:54.013  7800  7800 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 12:43:54.085  7806  7806 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-28 12:43:54.096  7807  7807 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-28 12:43:54.120  7809  7809 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:43:54.130  7810  7810 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-28 12:43:54.142  7811  7811 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 12:43:54.166  7812  7812 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-28 12:43:54.196  7814  7814 I libmdmdetect: ESOC framework not supported
07-28 12:43:54.197  7814  7814 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-28 12:43:54.206  7814  7814 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,07-28 12:43:54.206  7814  7814 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 12:43:54.207  7814  7814 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-28 12:43:54.207  7814  7814 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-28 12:43:54.207  7814  7814 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 12:43:54.207  7814  7814 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 12:43:54.207  7814  7814 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-28 12:43:54.246  7814  7815 E QC-QMI  : qmi_client [7814] 15: failed to locate client data
07-28 12:43:54.248   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 12:43:54.248   444   444 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,07-28 12:43:54.296  7816  7816 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 12:43:54.311  7817  7817 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 12:43:54.340  7515  7753 I bt_vendor: bluetooth satus is on
07-28 12:43:54.340  7515  7753 D bt_hci_bdroid: preload
07-28 12:43:54.340  7515  7798 D bt_userial_mct: userial_open(port:0)
07-28 12:43:54.340  7515  7798 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-28 12:43:54.343  7515  7798 I bt_vendor: Done intiailizing UART
07-28 12:43:54.344  7515  7798 I bt_vendor: Done intiailizing UART
,07-28 12:43:54.344  7515  7798 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-28 12:43:54.345  7515  7798 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-28 12:43:54.345  7515  7819 D bt_userial_mct: Entering userial_read_thread()
07-28 12:43:54.345  7515  7796 I bt-btu  : btu_task received preload complete event
07-28 12:43:54.345  7515  7796 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 12:43:54.345  7515  7796 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-28 12:43:54.348  7515  7796 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-28 12:43:54.352  7515  7796 I         : BTE_InitTraceLevels -- TRC_HCI
07-28 12:43:54.352  7515  7796 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:43:54.352  7515  7796 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:43:54.352  7515  7796 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:43:54.352  7515  7796 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:43:54.352  7515  7796 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:43:54.352  7515  7796 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:43:54.352  7515  7796 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:43:54.352  7515  7796 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 12:43:54.353  7515  7796 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:43:54.353  7515  7796 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:43:54.353  7515  7796 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:43:54.353  7515  7796 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:43:54.353  7515  7796 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:43:54.353  7515  7796 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:43:54.353  7515  7796 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:43:54.434  7515  7796 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-28 12:43:54.434  7515  7796 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
07-28 12:43:54.434  7515  7796 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 
,07-28 12:43:54.492  7515  7757 E bt-btif : Calling BTA_HhEnable
,07-28 12:43:54.492  7515  7757 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-28 12:43:54.493  7515  7757 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 12:43:54.501  7515  7796 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 12:43:54.502  7515  7796 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 12:43:54.502  7515  7796 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-28 12:43:54.502  7515  7796 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 12:43:54.502  7515  7796 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 12:43:54.506  7515  7757 D BluetoothAdapterProperties: Name is: G3
07-28 12:43:54.509  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 12:43:54.509  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
,07-28 12:43:54.512  7515  7757 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:43:54.512  7515  7757 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:43:54.512  7515  7757 D bt_hci_bdroid: postload
07-28 12:43:54.512  7515  7798 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:43:54.513  7515  7757 D bte_conf: Device ID record 1 : primary
07-28 12:43:54.513  7515  7757 D bte_conf:   vendorId            = 00c4
07-28 12:43:54.513  7515  7757 D bte_conf:   vendorIdSource      = 0001
07-28 12:43:54.513  7515  7757 D bte_conf:   product             = 13a1
07-28 12:43:54.513  7515  7757 D bte_conf:   version             = 1000
07-28 12:43:54.513  7515  7757 D bte_conf:   clientExecutableURL = 
07-28 12:43:54.513  7515  7757 D bte_conf:   serviceDescription  = 
07-28 12:43:54.513  7515  7757 D bte_conf:   documentationURL    = 
07-28 12:43:54.513  7515  7757 D bte_conf: bte_load_did_conf no section named DID2.
07-28 12:43:54.514  7515  7796 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-28 12:43:54.515  7515  7798 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:43:54.517  7515  7753 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:43:54.518  7515  7753 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:43:54.518  7515  7753 D BluetoothAdapterProperties: State =  11
07-28 12:43:54.518  7515  7753 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 12:43:54.518  7515  7753 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 12:43:54.519  7515  7753 D BluetoothAdapterProperties: Setting state to 12
07-28 12:43:54.519  7515  7753 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 12:43:54.521  7515  7757 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 12:43:54.524  7515  7757 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:43:54.518  7824  7824 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:54.518  7824  7824 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:54.534  1038  1120 D BluetoothManagerService: Message: 60
07-28 12:43:54.534  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 12:43:54.534  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,07-28 12:43:54.538  7515  7753 I BluetoothAdapterState: Entering On State
07-28 12:43:54.539  7515  7798 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:43:54.547  7515  7753 D LGBluetoothServiceAdapter: [BTUI] OnState
,07-28 12:43:54.552  7515  7753 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 12:43:54.552  7515  7753 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-28 12:43:54.553  7515  7753 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-28 12:43:54.553  7515  7796 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:54.553  7515  7796 W bt-smp  : Plain text(LSB ~ MSB) = 81 cc 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:54.553  7515  7796 W bt-smp  : Encrypted text(LSB ~ MSB) = f0 c5 b8 1f 8d 81 b5 3e cd 16 83 6f 78 5f 21 1a 
07-28 12:43:54.553  7515  7798 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 12:43:54.554  7515  7796 W bt-btm  : Stopping oneshot timer
07-28 12:43:54.556  7515  7819 E bt_mct  : hci lib postload completed
07-28 12:43:54.577  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:54.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:54.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:54.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:54.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:54.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:54.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:54.577  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:54.589  7515  7753 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 12:43:54.601  7515  7757 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:43:54.601  7515  7757 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,07-28 12:43:54.604  7515  7796 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:54.604  7515  7796 W bt-smp  : Plain text(LSB ~ MSB) = ae f5 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:54.604  7515  7796 W bt-smp  : Encrypted text(LSB ~ MSB) = cf 95 f3 2f c3 7c 70 71 07 af b3 8d 1b 39 59 33 
07-28 12:43:54.604  7515  7796 W bt-btm  : Stopping oneshot timer
07-28 12:43:54.605  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:54.610  6730  6745 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:43:54.610  6730  6745 D BluetoothPan: onBluetoothStateChange call bindService
07-28 12:43:54.624  7515  7796 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:54.624  7515  7796 W bt-smp  : Plain text(LSB ~ MSB) = 15 4a 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:54.624  7515  7796 W bt-smp  : Encrypted text(LSB ~ MSB) = 55 6e 21 6b a6 c6 1d 8b 5e b7 32 b1 8e ff d8 c8 
,07-28 12:43:54.628  7515  7796 W bt-btm  : Stopping oneshot timer
07-28 12:43:54.632  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:43:54.640  1038  1038 D BluetoothA2dp: Proxy object connected
,07-28 12:43:54.646  7515  7796 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:54.646  7515  7796 W bt-smp  : Plain text(LSB ~ MSB) = ed f8 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:54.647  7515  7796 W bt-smp  : Encrypted text(LSB ~ MSB) = 7e a3 3e 14 3c 4b 4a 86 ca 26 21 6a 7f 3c 9b 27 
07-28 12:43:54.647  7515  7796 W bt-btm  : Stopping oneshot timer
07-28 12:43:54.655  6730  6745 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:43:54.661  7829  7829 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-28 12:43:54.664  7515  7796 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 12:43:54.664  7515  7796 W bt-smp  : Plain text(LSB ~ MSB) = 00 cc 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 12:43:54.664  7515  7796 W bt-smp  : Encrypted text(LSB ~ MSB) = 00 79 9d e2 f9 3d 04 75 47 4f 71 3d ab 31 a4 e7 
07-28 12:43:54.664  7515  7796 W bt-btm  : Stopping oneshot timer
07-28 12:43:54.665  6730  6746 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:43:54.667  6730  6745 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:43:54.673  6730  6730 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:43:54.673  6730  6730 D PanProfile: Bluetooth service connected
07-28 12:43:54.674  6730  6746 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:43:54.680  6730  6745 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:43:54.686  1879  2570 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:43:54.688  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 12:43:54.688  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:43:54.689  1038  1038 D BluetoothHeadset: Proxy object connected
07-28 12:43:54.690  1879  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:43:54.692  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 12:43:54.693  1879  2540 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:43:54.700  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 12:43:54.700  1038  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 12:43:54.700  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 12:43:54.702  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 12:43:54.705  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:54.708  1969  2177 D LGBluetoothAPIService: Message: 1
07-28 12:43:54.708  1969  2177 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 12:43:54.708  1969  2177 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
07-28 12:43:54.710  1969  2177 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-28 12:43:54.711  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:54.711  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 12:43:54.716  1038  1120 D BluetoothManagerService: Message: 40
07-28 12:43:54.716  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-28 12:43:54.717  6730  6730 D BluetoothA2dp: Proxy object connected
07-28 12:43:54.717  6730  6730 D A2dpProfile: Bluetooth service connected
07-28 12:43:54.720  7515  7515 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:54.720  7515  7515 D BluetoothMapService: STATE_ON
07-28 12:43:54.720  7515  7515 V BluetoothMapService: Handler(): got msg=1
,07-28 12:43:54.723  6730  6730 D BluetoothInputDevice: Proxy object connected
07-28 12:43:54.723  6730  6730 D HidProfile: Bluetooth service connected
07-28 12:43:54.725  6730  6730 D BluetoothHeadset: Proxy object connected
07-28 12:43:54.725  6730  6730 D HeadsetProfile: Bluetooth service connected
07-28 12:43:54.730  7515  7515 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,07-28 12:43:54.740  7515  7835 D BluetoothMapMasInstance: MAS initSocket()
07-28 12:43:54.741  7515  7835 D BluetoothMapMasInstance:   masId = 00
07-28 12:43:54.741  7515  7835 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 12:43:54.741  7515  7835 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 12:43:54.741  7515  7835 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-28 12:43:54.742  1038  1783 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:54.743  7515  7835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:54.746  7515  7757 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:43:54.746  7515  7757 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 12:43:54.750  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:54.751  7515  7835 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-28 12:43:54.751  7515  7835 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 12:43:54.751  7515  7835 D BluetoothMapMasInstance: Accepting socket connection...
,07-28 12:43:54.760  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
07-28 12:43:54.760  7515  7515 V BluetoothPbapService: Pbap Service onCreate
07-28 12:43:54.760  7515  7515 V BluetoothPbapService: Starting PBAP service
07-28 12:43:54.762  6730  6730 D BluetoothMap: Proxy object connected
07-28 12:43:54.762  6730  6730 D MapProfile: Bluetooth service connected
07-28 12:43:54.762  6730  6730 D BluetoothMap: getConnectedDevices()
07-28 12:43:54.762  7515  7515 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-28 12:43:54.762  7515  7515 V BluetoothPbapService: Pbap Service onBind
07-28 12:43:54.763  7515  7515 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:54.763  7515  7515 V BluetoothPbapService: state: 12
07-28 12:43:54.763  7515  7515 V BluetoothPbapService: Handler(): got msg=1
07-28 12:43:54.764  7515  7515 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 12:43:54.765  7515  7530 V BluetoothMapService: getConnectedDevices()
07-28 12:43:54.766  7515  7841 V BluetoothPbapService: Pbap Service initSocket
07-28 12:43:54.766  1038  2058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:54.767  7515  7841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:54.768  7515  7841 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,07-28 12:43:54.768  7515  7841 V BluetoothPbapService: Succeed to create listening socket 
07-28 12:43:54.768  7515  7841 V BluetoothPbapService: Accepting socket connection...
07-28 12:43:54.769  6730  6730 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-28 12:43:54.770  6730  6730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 12:43:54.774  6730  6730 D BluetoothPbap: Proxy object connected
07-28 12:43:54.774  6730  6730 D PbapServerProfile: Bluetooth service connected
07-28 12:43:54.774  7515  7515 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 12:43:54.774  7515  7515 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:54.774  7515  7515 V BluetoothPbapReceiver: ***********state = 12
07-28 12:43:54.779  2224  2224 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:54.780  2224  2224 D c       : Getting all permits...
07-28 12:43:54.780  2224  2224 D a       : Opening database...
07-28 12:43:54.784  2224  2224 D a       : Opening database auth.proximity.permit_store...
07-28 12:43:54.785  2224  2224 D a       : Closing database...
07-28 12:43:54.785  6730  6730 D DockEventReceiver: finishStartingService: stopping service
07-28 12:43:54.798  6730  6730 D BluetoothPermissionRequest: onReceive
,07-28 12:43:54.801  6730  6730 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 12:43:54.803  6730  6730 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 12:43:54.806  7515  7515 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-28 12:43:54.807  7515  7515 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-28 12:43:54.813  7515  7515 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-28 12:43:54.830  7515  7515 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 12:43:54.830  7515  7515 V BtOppService: onCreate
,07-28 12:43:54.835  7515  7515 V BluetoothOppNotification: send message
07-28 12:43:54.839  7515  7515 V BtOppService: Starting RfcommListener
07-28 12:43:54.845  7515  7515 D BluetoothOppPreference: Dumping Names:  
07-28 12:43:54.845  7515  7515 D BluetoothOppPreference: {}
07-28 12:43:54.845  7515  7515 D BluetoothOppPreference: Dumping Channels:  
07-28 12:43:54.845  7515  7515 D BluetoothOppPreference: {}
07-28 12:43:54.846  7515  7515 V BtOppService: onStartCommand
,07-28 12:43:54.852  7515  7854 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,07-28 12:43:54.852  7515  7515 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:54.853  7515  7515 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 12:43:54.855  7515  7854 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:43:54.856  7515  7851 V BtOppService: Deleted complete outbound shares, number =  0
07-28 12:43:54.858  7515  7515 V BluetoothOppNotification: new notify threadi!
,07-28 12:43:54.859  7515  7851 V BtOppService: Deleted complete inbound failed shares, number = 0
07-28 12:43:54.860  7515  7851 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-28 12:43:54.860  7515  7854 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@393b69f6 on behalf of 
07-28 12:43:54.862  7515  7851 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22d941f7 on behalf of 
07-28 12:43:54.864  7515  7515 V BluetoothOppNotification: send delay message
07-28 12:43:54.865  7515  7854 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:43:54.866  7515  7515 V BtOppService: start RfcommListener
,07-28 12:43:54.866  7515  7854 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:43:54.869  7515  7855 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:43:54.869  7515  7515 V BtOppService: RfcommListener started
07-28 12:43:54.870  7515  7515 V BtOppService: ContentObserver received notification
07-28 12:43:54.871  7515  7855 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4a48864 on behalf of 
07-28 12:43:54.872  7515  7856 V BtOppRfcommListener: Starting RFCOMM listener....
07-28 12:43:54.873  1038  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:54.873  7515  7856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:54.874  7515  7857 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:43:54.874  7515  7856 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
07-28 12:43:54.875  7515  7856 V BtOppRfcommListener: Started RFCOMM listener....
07-28 12:43:54.875  7515  7856 I BtOppRfcommListener: Accept thread started.
07-28 12:43:54.875  7515  7857 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:43:54.875  7515  7856 V BtOppRfcommListener: Accepting connection...
07-28 12:43:54.876  7515  7855 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 12:43:54.877  7515  7857 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cf4bacd on behalf of 
07-28 12:43:54.877  7515  7855 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:43:54.879  7515  7855 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cac2f82 on behalf of 
,07-28 12:43:54.883  7515  7857 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 12:43:54.884  7515  7855 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:43:54.886  7515  7855 V BluetoothOppNotification: outbound notification was removed.
07-28 12:43:54.887  7515  7855 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:43:54.889  7515  7855 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c560693 on behalf of 
07-28 12:43:54.890  7515  7855 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:43:54.891  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
,07-28 12:43:54.891  7515  7515 V BluetoothFtpService: Ftp Service onCreate
07-28 12:43:54.891  7515  7515 I BluetoothFtpService: Ftp Service onCreate
07-28 12:43:54.891  7515  7515 V BluetoothFtpService: Ftp Service onStartCommand
07-28 12:43:54.891  7515  7515 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:54.891  7515  7515 V BluetoothFtpService: Starting Listening on sockets
07-28 12:43:54.892  7515  7515 V BtOppService: ContentObserver received notification
07-28 12:43:54.892  7515  7515 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 12:43:54.892  7515  7515 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 12:43:54.892  7515  7515 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 12:43:54.892  7515  7515 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:54.892  7515  7515 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 12:43:54.892  7515  7515 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 12:43:54.894  7515  7515 V BluetoothFtpService: Handler(): got msg=1
07-28 12:43:54.895  7515  7858 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 12:43:54.895  7515  7858 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 12:43:54.896  7515  7515 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 12:43:54.896  7515  7515 V BluetoothFtpService: Ftp Service initSocket
07-28 12:43:54.898  7515  7855 V BluetoothOppNotification: inbound notification was removed.
07-28 12:43:54.898  7515  7855 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:43:54.899  1038  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:54.900  7515  7515 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:54.900  7515  7515 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
07-28 12:43:54.901  7515  7855 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21f36c9 on behalf of 
07-28 12:43:54.901  7515  7515 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 12:43:54.903  7515  7859 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 12:43:54.903  7515  7858 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1271c1ce on behalf of 
07-28 12:43:54.903  7515  7858 V BluetoothOppNotification: update too frequent, put in queue
07-28 12:43:54.905  7515  7858 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,07-28 12:43:54.926  7515  7515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33e5d61a
,07-28 12:43:54.926  7515  7515 V BluetoothSapService: Sap Service onCreate
07-28 12:43:54.928  7515  7515 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:54.928  7515  7515 V BluetoothSapService: state: 12
07-28 12:43:54.928  7515  7515 V BluetoothSapService: Starting SAP server process
07-28 12:43:54.930  7515  7515 V BluetoothSapService: SAP Service startRfcommListenerThread
,07-28 12:43:54.918  7861  7861 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:54.931  7515  7862 V BluetoothSapService: Sap Service initRfcommSocket
07-28 12:43:54.918  7861  7861 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:54.932  1038  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:54.932  7515  7862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:54.933  7515  7862 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-28 12:43:54.933  7515  7862 V BluetoothSapService: Succeed to create listening socket 
07-28 12:43:54.933  7515  7862 V BluetoothSapService: Accepting socket connection...
07-28 12:43:54.952  7861  7861 V BT_SAP  : Event pipe created
07-28 12:43:54.953  7861  7861 V BT_SAP  : create_server_socket qcom.sap.server
07-28 12:43:54.953  7861  7861 V BT_SAP  : created socket fd 6
,07-28 12:43:55.367  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:55.367  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:55.367  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:55.367  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:55.367  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:55.367  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:55.367  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:55.367  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:55.372  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:55.375  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:55.375  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19108591 added. We now have 8 listener(s)
07-28 12:43:55.375  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:55.378  1038  1738 D WifiServiceImplEx: setWifiEnabled: false pid=6549, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:43:55.379  1038  1738 D WifiService: setWifiEnabled: false pid=6549, uid=10118
07-28 12:43:55.379  1038  1738 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:43:55.384  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:55.388  1038  2323 D WifiServiceImplEx: setWifiEnabled: true pid=6549, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 12:43:55.389  1038  2323 D WifiService: setWifiEnabled: true pid=6549, uid=10118
07-28 12:43:55.389  1038  2323 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:43:55.407  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-28 12:43:55.407  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 12:43:55.407  1038  1038 D Ulp_jni : JNI:system_update. Event-4
07-28 12:43:55.408  1038  1540 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,07-28 12:43:55.408  1038  1540 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 12:43:55.411  1038  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,07-28 12:43:55.411  1038  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
,07-28 12:43:55.411  1038  1540 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 12:43:55.411  1038  1540 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 12:43:55.411  1038  1540 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-28 12:43:55.411  1038  1540 E WifiHW  : unknown target_country: EU , set to default
07-28 12:43:55.411  1038  1540 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-28 12:43:55.411  1038  1540 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
,07-28 12:43:55.411  1038  1540 I WifiUtil: gEnableBmps=1,
07-28 12:43:55.867  7515  7515 V BluetoothOppNotification: new notify threadi!
07-28 12:43:55.868  7515  7515 V BluetoothOppNotification: send delay message
,07-28 12:43:55.893  7515  7881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 12:43:55.895  7515  7881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dec2cda on behalf of 
07-28 12:43:55.896  7515  7881 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-28 12:43:55.899  7515  7881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 12:43:55.900  7515  7881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dd5b50b on behalf of 
07-28 12:43:55.901  7515  7881 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 12:43:55.902  7515  7881 V BluetoothOppNotification: outbound notification was removed.
07-28 12:43:55.902  7515  7881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 12:43:55.904  7515  7881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32a99fe8 on behalf of 
07-28 12:43:55.904  7515  7881 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 12:43:55.907  7515  7881 V BluetoothOppNotification: inbound notification was removed.
07-28 12:43:55.907  7515  7881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 12:43:55.909  7515  7881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1661f601 on behalf of 
,07-28 12:43:55.977  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:43:55.977  1038  1120 D Tethering: InitialState.processMessage what=4
,07-28 12:43:55.984   310   907 D SoftapController: Softap fwReload - Ok
07-28 12:43:55.989  1038  1540 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (574ms)
07-28 12:43:55.996   310   907 D CommandListener: Setting iface cfg
07-28 12:43:55.996   310   907 D CommandListener: Trying to bring down wlan0
,07-28 12:43:55.999   310   907 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:43:56.002  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:43:56.007  1038  1540 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-28 12:43:55.998  7883  7883 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:43:56.018  7883  7883 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:43:56.034  1038  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:43:56.034  1038  1540 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:43:56.034  1038  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:43:56.035  1038  1540 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:43:56.035  1038  1540 D WifiMonitor: connecting to supplicant
,07-28 12:43:56.052  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:56.053  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-28 12:43:56.057  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:56.062  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-28 12:43:56.063  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:43:56.063  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:43:56.063  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,07-28 12:43:56.063  6730  6730 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:43:56.065  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:43:56.066  6730  6730 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:43:56.066  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:43:56.066  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:43:56.066  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:43:56.066  6730  6730 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:43:56.066  6730  6730 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:43:56.066  7883  7883 I wpa_supplicant: Successfully initialized wpa_supplicant
07-28 12:43:56.069  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:43:56.069  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:43:56.069  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:43:56.069  6730  6730 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:43:56.069  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 12:43:56.070  6730  6730 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:43:56.071  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 12:43:56.071  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:43:56.071  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:43:56.071  6730  6730 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:43:56.071  6730  6730 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:43:56.100  7883  7883 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:43:56.100  7883  7883 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-28 12:43:56.115  1038  2058 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7900 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-28 12:43:56.156  7883  7883 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:43:56.235  7883  7883 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-28 12:43:56.249  7883  7883 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,07-28 12:43:56.251  1038  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:43:56.251  1038  1540 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-28 12:43:56.252  1038  1540 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:43:56.252  1038  1540 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 12:43:56.253  1038  1540 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:56.253  1038  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:56.254  1038  1540 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 12:43:56.254  1038  1540 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 12:43:56.254  1038  1540 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 12:43:56.255  1038  1540 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 12:43:56.255  1038  1540 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-28 12:43:56.256  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 12:43:56.256  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 12:43:56.256  1038  7923 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:43:56.256  1038  7923 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-28 12:43:56.260  1038  1054 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7922 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 12:43:56.263  1038  1540 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 12:43:56.263  1038  1540 E WifiStateMachine: useWiFiOffloading() : false
07-28 12:43:56.263  1038  1540 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 12:43:56.264  1038  1540 D WifiNative-wlan0: doBoolean: SET update_config 1
07-28 12:43:56.265  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.265  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:56.266  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:56.267  1969  1969 D WfdService: Waiting for WifiP2p enabling
07-28 12:43:56.267  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.267  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.267  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 12:43:56.269  1038  1540 D WifiNative-wlan0: SET update_config 1: returned true
07-28 12:43:56.269  1038  1540 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:43:56.269  1038  1540 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 12:43:56.270  1038  1540 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-28 12:43:56.272  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 12:43:56.272  1038  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 12:43:56.276  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:56.276  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:56.276  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:56.276  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:56.276  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:56.276  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:56.276  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:56.276  6549  6549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:56.277  1038  1540 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-28 12:43:56.278  6549  6549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:56.281   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 21.860ms
,07-28 12:43:56.291  1038  1540 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 12:43:56.291  1038  1540 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:43:56.292  1038  1540 D WifiStateMachine: enableVerboseLogging : level 2
07-28 12:43:56.292  1038  1540 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-28 12:43:56.294  7900  7921 V FormManager: Network unavailable.
,07-28 12:43:56.297  7900  7921 V FormManager: Network unavailable.
07-28 12:43:56.299  1038  1540 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-28 12:43:56.299  1038  1540 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 12:43:56.299  1038  1540 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-28 12:43:56.299   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 359us total 17.084ms
07-28 12:43:56.299  1038  1540 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-28 12:43:56.300  1038  1540 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-28 12:43:56.300  1038  1540 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 12:43:56.300  7900  7920 W FormManager: Network not available. Please check & try again.
07-28 12:43:56.300  1038  1540 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 12:43:56.300  1038  1540 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-28 12:43:56.301  1038  1540 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 12:43:56.301  1038  1540 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 12:43:56.301  1038  1540 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 12:43:56.301  1038  1540 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 12:43:56.301  1038  1540 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 12:43:56.302  1038  1540 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:43:56.302  1038  1540 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-28 12:43:56.302  1038  1540 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 12:43:56.303  1038  1540 D WifiNative-HAL: Setting external_sim to 1
07-28 12:43:56.303  1038  1540 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 12:43:56.303  1038  1540 D WifiNative-wlan0: SET external_sim 1: returned true
07-28 12:43:56.303  1038  1540 I WifiNative-HAL: startHal
07-28 12:43:56.303  1038  1540 D wifi    : setting scan oui 0xaf77d6a0
07-28 12:43:56.303  1969  1969 D WfdsService: Supplicant Connection state is changed : true
07-28 12:43:56.303  1969  2314 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 12:43:56.303  1969  2314 D WfdsService: Set the WFDS Monitor: true
07-28 12:43:56.303  1969  2314 D WfdsMonitor: WfdsMonitorThread create
07-28 12:43:56.303  1038  1540 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:43:56.303  1038  1540 I WifiNative-HAL: startHal
07-28 12:43:56.303  1969  2314 D WfdsMonitor: WFDS Monitor is created and started
07-28 12:43:56.304  1038  1540 D wifi    : setting scan oui 0xaf77d6a0
07-28 12:43:56.304  1969  2314 D WfdsService: WiFi: Supplicant connection re-established
07-28 12:43:56.304  1038  1540 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 12:43:56.304  7543  7543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.304  1038  1540 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 12:43:56.304  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 12:43:56.304  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-28 12:43:56.304  1969  7941 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 12:43:56.305  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 12:43:56.305  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:43:56.305  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:43:56.305  1969  7941 E CtrlSupplicant: Succeed to open control connection
07-28 12:43:56.305  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:43:56.305  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 12:43:56.305  1969  79,41 E CtrlSupplicant: Succeed to open monitor connection
07-28 12:43:56.305  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 12:43:56.306  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 12:43:56.306  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:43:56.306  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:43:56.306  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:43:56.306  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 12:43:56.306  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 12:43:56.306  1969  7941 D WfdsMonitor: Supplicant connection established
07-28 12:43:56.307  1969  2314 D WfdsService: Connected to the supplicant for wfds
07-28 12:43:56.307  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 12:43:56.307  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 12:43:56.307  7883  7883 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-28 12:43:56.307  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-28 12:43:56.307  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 12:43:56.307  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 12:43:56.308  1038  1540 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 12:43:56.308  1038  1540 E WifiNative: : [152,940,670 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 12:43:56.308  1038  1540 D WifiNative-wlan0: doBoolean: RECONNECT
,07-28 12:43:56.312  1038  1540 D WifiNative-wlan0: RECONNECT: returned true
07-28 12:43:56.312  1038  1540 D WifiNative-wlan0: doString: [STATUS]
07-28 12:43:56.313  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:43:56.313  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 12:43:56.314  1038  1540 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:43:56.314  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:43:56.314  1038  1540 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:43:56.314  1038  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.315  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:43:56.315  1038  1540 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-28 12:43:56.315  1038  1038 D RttService: SCAN_AVAILABLE : 3
07-28 12:43:56.316  1038  1540 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 12:43:56.316  1038  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.316  1038  1557 I WifiNative-HAL: startHal
07-28 12:43:56.316  1038  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf77d6a0
07-28 12:43:56.316  1038  1557 D wifi    : failed to get capabilities : -3
07-28 12:43:56.316  1038  1557 E WifiScanningService: could not get scan capabilities
07-28 12:43:56.316  1038  1540 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 12:43:56.316  1038  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.316  1038  1540 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-28 12:43:56.317  1038  1540 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-28 12:43:56.317  1038  1540 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-28 12:43:56.317  1038  1540 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-28 12:43:56.317  1038  1540 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 12:43:56.317   310   907 D CommandListener: Setting iface cfg
07-28 12:43:56.317   310   907 D CommandListener: Trying to bring up p2p0
07-28 12:43:56.318  7883  7883 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-28 12:43:56.318  1038  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:43:56.318  1038  1538 D LGWifiP2pService: P2pEnablingState
07-28 12:43:56.318  1038  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.318  1038  1538 D LGWifiP2pService: P2p socket connection successful
07-28 12:43:56.318  1038  1538 D LGWifiP2pService: P2pEnabledState
07-28 12:43:56.319  1038  1540 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-28 12:43:56.319  1038  1540 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-28 12:43:56.319  1038  1540 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 12:43:56.319  1038  1540 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 12:43:56.320  7883  7883 E wpa_supplicant: disconnect_rssi_lvl: -100
07-28 12:43:56.320  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-28 12:43:56.320  1969  1969 D WfdsService: WifiP2pState is changed : true
07-28 12:43:56.321  1969  2314 D WfdsService: Receive the WFDS_ENABLE Method
07-28 12:43:56.321  1969  2314 D WfdsService: Set the WFDS Monitor: true
07-28 12:43:56.321  1969  2314 D WfdsService: Connected to the supplicant for wfds
07-28 12:43:56.321  1969  2314 D WfdsJNI : doCommand: WFDS_SET TRUE
07-28 12:43:56.321  7883  7883 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd =, SET TRUE
07-28 12:43:56.321  1969  2314 D WfdsService: selectPreferredScanChannel [36]
07-28 12:43:56.321  1969  2314 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 12:43:56.322  1038  1538 D LGWifiP2pService: sending p2p connection changed broadcast
07-28 12:43:56.324   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 24.062ms
07-28 12:43:56.325  1038  1540 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:43:56.326  1038  1540 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:43:56.326  1038  1540 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 12:43:56.326  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-28 12:43:56.326  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:43:56.327  7883  7883 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:56.327  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:43:56.327  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:56.327  1038  7923 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:56.327  1038  7923 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:56.327  7883  7883 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:43:56.327  7883  7883 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.328  1038  1540 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-28 12:43:56.328  7883  7883 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.328  1038  1540 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,07-28 12:43:56.328  1969  7941 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:56.328  1969  7941 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:56.329  1038  1540 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:43:56.329  1038  7923 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:56.329  1038  7923 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.329  1038  7923 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.329  1038  7923 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.329  1038  1540 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 12:43:56.329  1038  7923 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:56.329  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 12:43:56.329  1038  7923 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.329  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 12:43:56.330  7883  7883 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:43:56.331  1038  1540 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 12:43:56.331  1038  1540 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-28 12:43:56.331  1038  1540 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-28 12:43:56.331  1038  1540 D WifiNative-wlan0: doBoolean: SCAN
07-28 12:43:56.331  1038  7923 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.331  1038  7923 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.331  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-28 12:43:56.331  1038  1540 D WifiNative-wlan0: SCAN: returned false
07-28 12:43:56.331  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:43:56.331  7620  7631 E UEI.SmartControl: file observer is disposed!
07-28 12:43:56.331  1038  7923 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:43:56.331  1038  7923 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 12:43:56.332  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=152964  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:43:56.333  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:56.333  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:56.334  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.334  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.334  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:43:56.334  1038  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 12:43:56.335  1038  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 12:43:56.335  1038  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 12:43:56.335  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=152968  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 12:43:56.335  1038  1538 D WifiNative-p2p0: SET d,evice_name G3: returned true
07-28 12:43:56.335  1038  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 12:43:56.335  1038  1538 D LGWifiP2pService: before postfix = G3
07-28 12:43:56.335  1038  1538 D WifiServerServiceExt: postfix byte check : 2
07-28 12:43:56.335  1038  1538 D LGWifiP2pService: after postfix = G3
07-28 12:43:56.335  1038  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 12:43:56.335  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:56.336  1038  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 12:43:56.336  1038  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 12:43:56.336  1038  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 12:43:56.336  1038  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 12:43:56.336  1038  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 12:43:56.336  1038  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 12:43:56.336  1038  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-28 12:43:56.336  1038  1538 D WifiNative-HAL: p2pGetDeviceAddress
07-28 12:43:56.337  1038  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 12:43:56.337  1038  1540 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:56.337  1038  1540 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:56.338  1969  1969 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-28 12:43:56.338  1038  1540 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:56.338  1969  1969 D WfdsService: isConnected: false
07-28 12:43:56.338  1038  1540 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:56.338  1038  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 12:43:56.338  1038  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 12:43:56.338  1038  1540 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 12:43:56.338  1038  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
07-28 12:43:56.339  1038  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 12:43:56.339  1969  1969 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 12:43:56.339  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-28 12:43:56.339  1969  1969 D WfdsService: Update P2p Interface State: 3
07-28 12:43:56.339  1038  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-28 12:43:56.339  1038  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-28 12:43:56.339  1038  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-28 12:43:56.339  1038  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 12:43:56.339  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:56.340  1038  1038 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 12:43:56.341  1038  1983 I ActivityManager: Killing 6992:com.android.chrome/u0a57 (adj 15): empty #17
,07-28 12:43:56.346  1038  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-28 12:43:56.346  1038  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 12:43:56.368  7922  7922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 12:43:56.417  1038  1538 D LGWifiP2pService: InactiveState
,07-28 12:43:56.418  1038  1538 D LGWifiP2pService: InactiveState{ when=-90ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.418  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-90ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.418  1038  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-28 12:43:56.420  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 12:43:56.420  7883  7883 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:56.423  7883  7883 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 12:43:56.423  7883  7883 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.423  1038  7923 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:43:56.423  1038  7923 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:56.423  1038  7923 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:56.423  1038  7923 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 12:43:56.423  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:56.424  1038  7923 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:56.424  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:56.424  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:56.424  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:56.424  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:56.424  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:56.424  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:56.424  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:56.424  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:56.424  1038  7923 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.424  1038  7923 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.424  1038  7923 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.424  1038  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 12:43:56.424  1969  7941 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 12:43:56.424  1038  1538 D LGWifiP2pService: InactiveState{ when=-85ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.424  1969  7941 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:56.424  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-85ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.424  1038  1538 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.424  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.425  1038  1538 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.425  1038  1538 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.425  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=13928,5 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.425  1038  1538 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.426  7883  7883 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.427  1969  7941 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:56.427  1038  7923 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 12:43:56.427  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:56.427  1038  7923 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.427  1038  7923 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.427  1038  7923 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 12:43:56.429  1038  1538 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.429  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.429  1038  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.429  1038  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.429  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.430  1038  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.430  1038  1038 E WifiServerServiceExt: No p2p device connected
07-28 12:43:56.430  1969  2314 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 12:43:56.431  1038  1577 W libprocessgroup: failed to open /acct/uid_10057/pid_6992/cgroup.procs: No such file or directory
,07-28 12:43:56.436  6549  6673 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-28 12:43:56.437  6549  6673 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-28 12:43:56.439  6549  6673 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@29791679 Bundle[{}]
07-28 12:43:56.440  6549  6673 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:43:56.441  6549  6673 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-28 12:43:56.441  6549  6673 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-28 12:43:56.442  6549  6673 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-28 12:43:56.443  6549  6673 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-28 12:43:56.444  6549  6673 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-28 12:43:56.448  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:43:56.450  1038  1604 I ActivityManager: Killing 7013:com.lge.drmservice/u0a62 (adj 15): empty #17
07-28 12:43:56.456  6549  6673 I System.out: Running OutgoingSocketThread
07-28 12:43:56.458  6549  7945 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 846)
07-28 12:43:56.459  6549  7945 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54076
07-28 12:43:56.459  6549  7945 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
07-28 12:43:56.510  1038  2321 W libprocessgroup: failed to open /acct/uid_10062/pid_7013/cgroup.procs: No such file or directory
,07-28 12:43:56.632  1038  1961 I art     : Explicit concurrent mark sweep GC freed 39451(1921KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.791ms total 107.847ms
,07-28 12:43:56.635  7922  7922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:56.639  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:56.646  7900  7947 W FormManager: Network not available. Please check & try again.
,07-28 12:43:56.648  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:56.663  7900  7948 V FormManager: Network unavailable.
,07-28 12:43:56.667  7900  7948 V FormManager: Network unavailable.
07-28 12:43:56.679  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:43:56.679  4338  4338 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-28 12:43:56.681  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 12:43:56.682  4338  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 12:43:56.688  4338  7949 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 12:43:56.691  4338  7950 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 12:43:56.692  4338  7950 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 12:43:56.741  1038  1054 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7951 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 12:43:56.845  7951  7951 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 12:43:56.858  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 12:43:56.858  7883  7883 E wpa_supplicant: USIM:  scard_init function
07-28 12:43:56.858  1038  7923 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-28 12:43:56.859  7883  7883 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-28 12:43:56.859  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-28 12:43:56.859  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
07-28 12:43:56.859  1038  7923 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 12:43:56.859  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-28 12:43:56.859  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-28 12:43:56.860  1038  1540 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:43:56.861  1038  1540 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,07-28 12:43:56.863  1038  1540 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,07-28 12:43:56.864  1038  1540 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 12:43:56.864  1038  1540 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,07-28 12:43:56.871  7951  7951 D PluginManager: init()
07-28 12:43:56.877  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=153510  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 12:43:56.881  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:56.881  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:56.882  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.882  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.882  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 12:43:56.883  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:56.888  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.888  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.888  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:43:56.888  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=153521  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 12:43:56.889  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:56.889  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-28 12:43:56.903  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:56.904  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:56.906  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:56.970  7883  7883 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-28 12:43:56.970  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-28 12:43:56.970  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-28 12:43:56.971  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-28 12:43:56.971  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-28 12:43:56.971  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,07-28 12:43:56.972  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:43:56.977  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=153609  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:43:56.978  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=153611  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 12:43:56.982  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 12:43:56.983  1038  1540 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=153615
07-28 12:43:56.984  1038  1540 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=153616
07-28 12:43:56.985  1038  1540 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=153617
07-28 12:43:56.988  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:43:56.989  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:43:56.989  7883  7883 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:43:56.989  7883  7883 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,07-28 12:43:56.992  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 12:43:56.993  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:43:56.993  1038  7923 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:43:56.993  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-28 12:43:56.993  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=153626
07-28 12:43:56.993  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:43:56.993  1038  7923 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 12:43:56.993  1038  1540 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=153626
07-28 12:43:56.994  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:43:56.994  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:43:56.994  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=153626  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:43:56.997  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:56.997  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:56.998  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.998  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:56.998  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 12:43:56.999  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:56.999  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=153631  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 12:43:57.001  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:57.001  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.001  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-28 12:43:57.002  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:57.002  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:57.004  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.005  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:57.005  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-28 12:43:57.006  1038  1540 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:57.006  1038  1540 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:57.006  1038  1540 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:57.007  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:57.007  1038  1540 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 12:43:57.008  1038  1540 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=153640  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:43:57.008  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=153641  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 12:43:57.009  1038  1540 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=153641
07-28 12:43:57.009  1038  1540 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=153642
07-28 12:43:57.010  1038  1540 D WifiNative-wlan0: doString: [STATUS]
07-28 12:43:57.010  1038  7923 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 12:43:57.010  1038  7923 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 12:43:57.010  1038  1540 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 12:43:57.012  1038  1540 I WifiServiceExtension: setVHTCapabilityType  : false
07-28 12:43:57.016  1038  1540 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-28 12:43:57.016  1038  1540 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,07-28 12:43:57.021  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.021  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.021  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:43:57.024  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.024  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.024  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 12:43:57.030  1038  1540 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-28 12:43:57.030  1038  1546 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:43:57.030  1038  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:43:57.030  1038  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:43:57.030  1038  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 12:43:57.030  1038  1546 D ConnectivityService: NetworkAgent connected
07-28 12:43:57.031  1038  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:43:57.031  1038  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-28 12:43:57.034  1038  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:43:57.035  1038  1540 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:43:57.035  1038  1540 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 12:43:57.035  1038  1540 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 12:43:57.035  1038  1540 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 12:43:57.038  1038  1540 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 12:43:57.039   310   907 D CommandListener: Setting iface cfg
07-28 12:43:57.040  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:57.040  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:57.041  1038  1540 E WifiStateMachine: Start Dhcp Watchdog 3
07-28 12:43:57.041  1038  7969 D DhcpStateMachine: StoppedState
07-28 12:43:57.041  1038  7969 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:57.041  1038  7969 D DhcpStateMachine: WaitBeforeStartState
07-28 12:43:57.042  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.042  1038  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=153674  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:57.042  1038  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=153675  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:57.043  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=153675  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:57.043  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:57.044  1038  1038 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-28 12:43:57.044  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:57.044  1038  1038 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,07-28 12:43:57.045  1038  1540 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=153677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:57.045  1038  1540 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=153677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:57.045  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:57.045  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:57.045  1038  1540 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=153678  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 12:43:57.046  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13929] from screen [on:0 period:823821814] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:43:57.047  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.047  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:823821815] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 12:43:57.047  1038  1540 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-28 12:43:57.052  1038  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
07-28 12:43:57.052  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.052  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.053  1038  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.053  1038  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.053  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.054  1038  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.054  1038  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 12:43:57.054  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=110,0,0
07-28 12:43:57.055  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=110,0,0
07-28 12:43:57.055  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-28 12:43:57.055  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,07-28 12:43:57.055  1038  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-28 12:43:57.055  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 12:43:57.056  1038  1540 D WifiNative-wlan0: SET ps 0: returned true
07-28 12:43:57.056  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-28 12:43:57.056  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 12:43:57.056  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 12:43:57.057  1038  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2ee066d9 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:57.057  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2ee066d9 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:57.057  1038  7969 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:57.057  1038  7969 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-28 12:43:57.059  1038  1540 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-28 12:43:57.059  1038  1540 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:43:57.059  1038  1540 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,07-28 12:43:57.059   310   907 D CommandListener: Setting iface cfg
07-28 12:43:57.060   310   907 D CommandListener: Trying to bring up wlan0
07-28 12:43:57.061  1038  1540 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 12:43:57.061  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:57.061  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,07-28 12:43:57.062  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 12:43:57.062  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 12:43:57.062  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.063  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.063  1038  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.063  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.064  1038  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.064  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.064  1038  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 12:43:57.065  1038  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 12:43:57.065  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:43:57.065  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 12:43:57.066  1038  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:43:57.066  1038  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:57.066  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 12:43:57.066  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 12:43:57.066  1038  1540 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 12:43:57.066  1038  1540 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 12:43:57.067  7883  7883 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-28 12:43:57.067  1038  1540 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-28 12:43:57.067  1038  1540 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 12:43:57.083  1038  1540 D WifiNative-wlan0: SET ps 1: returned true
07-28 12:43:57.083  1038  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 12:43:57.084  1038  1540 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:43:57.084  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 12:43:57.084  1038  1540 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 12:43:57.084  1038  1546 D ConnectivityService: ignoring duplicate network state non-change
07-28 12:43:57.086  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:57.086  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 12:43:57.087  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.089  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.089  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.089  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:43:57.092  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.092  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.092  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 12:43:57.092  1038  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 12:43:57.093  1038  1546 D ConnectivityService: Adding iface wlan0 to network 102
07-28 12:43:57.096  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:43:57.098  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-28 12:43:57.099  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.099  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:57.101  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:43:57.101  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 12:43:57.102  1038  1540 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-28 12:43:57.107  1038  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:43:57.107  1038  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-28 12:43:57.108  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.108  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:57.108  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 12:43:57.108  1038  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-28 12:43:57.109   310   907 E Netd    : netlink response contains error (File exists)
07-28 12:43:57.109  1038  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-28 12:43:57.110  1038  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 12:43:57.110  1038  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
07-28 12:43:57.110  1038  1546 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-28 12:43:57.110  1038  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:43:57.111  1038  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 12:43:57.111  1038  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-28 12:43:57.111  1038  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-28 12:43:57.111  1038  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:57.111  1038  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:57.111  1038  7968 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:57.111  1038  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:43:57.111  1038  7968 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 12:43:57.111  1038  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:57.111  1038  7968 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:57.111  1038  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 12:43:57.111  1038  1546 D ConnectivityService: currentScore = 0, newScore = 20
07-28 12:43:57.111  1038  1546 D ConnectivityService:    accepting network in place of null
07-28 12:43:57.111  1038  7968 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:43:57.111  1038  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:57.112  1038  1540 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:57.112  10,38  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:57.113  1879  1879 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:57.113  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:43:57.114  1038  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:43:57.114  1038  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-28 12:43:57.114  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:43:57.115  1038  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:57.115  1038  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 12:43:57.115  1038  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,07-28 12:43:57.116   310  7973 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-28 12:43:57.116  1038  1038 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 12:43:57.116  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 12:43:57.116  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 12:43:57.116  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 12:43:57.115  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:57.117  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 12:43:57.118  1038  1546 D ConnectivityService: validation of new default Network = false
07-28 12:43:57.118  1038  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 12:43:57.118  1038  1546 D DSQN    : enableDataServiceNotify 
07-28 12:43:57.118  1038  1546 D DSQN    : start dsqn bin
07-28 12:43:57.119  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.121  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:57.121  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:43:57.121  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.122  1038  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-28 12:43:57.122  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:57.122  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:57.122  1038  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:57.123  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:57.123  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 12:43:57.123  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.108  7974  7974 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:57.125  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:43:57.108  7974  7974 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:43:57.137  1038  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-28 12:43:57.138  7974  7974 E DSQN    : DSQN ssw
,07-28 12:43:57.143  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:43:57.144  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.145  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.162   310  7973 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,07-28 12:43:57.202   310  7973 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-28 12:43:57.253  7951  7951 W ExternalStrings: load override strings
07-28 12:43:57.253  7951  7951 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:57.253  7951  7951 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:57.255  7951  7951 D StatusProvider: onCreate
07-28 12:43:57.261  1038  7969 D DhcpStateMachine: DHCPV4 request on wlan0
07-28 12:43:57.262  1038  7969 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 12:43:57.263  1038  7969 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-28 12:43:57.263   310   906 D LGDataListener: argv[0]=dsqncommand
07-28 12:43:57.263   310   906 D LGDataListener: argv[1]=wlan0
07-28 12:43:57.263   310   906 D LGDataListener: argv[2]=1
07-28 12:43:57.263   310   906 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-28 12:43:57.264  1038  1118 D DSQN    : DSQM DsqnNotification wlan0  1
07-28 12:43:57.264  1038  1118 D DSQN    : start to monitor internet connection
07-28 12:43:57.258  7981  7981 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 12:43:57.258  7981  7981 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 12:43:57.275  7981  7981 I dhcpcd  : version 5.5.6 starting
07-28 12:43:57.276  7981  7981 E dhcpcd  : get_duid: m
07-28 12:43:57.276  7981  7981 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 12:43:57.276  7981  7981 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-28 12:43:57.298  1038  7968 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:43:57 GMT], X-Android-Received-Millis=[1469702637297], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469702637262]}
07-28 12:43:57.298  1038  7968 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 12:43:57.298  1038  7968 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-28 12:43:57.298  1038  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
07-28 12:43:57.298  1038  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-28 12:43:57.298  1038  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:57.298  1038  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:57.299  1038  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 12:43:57.299  1038  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
07-28 12:43:57.299  1038  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-28 12:43:57.299  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:57.299  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:57.299  1038  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:57.300  1038  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:57.300  1038  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-28 12:43:57.301  1038  1540 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:57.301  1038  1540 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:57.303  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:43:57.304  1879  1879 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:43:57.311  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 12:43:57.315  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 12:43:57.316  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 12:43:57.316  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 12:43:57.329  7951  7951 V Signer  : override build config not found
,07-28 12:43:57.329  7951  7951 D Signer  : value of property debug is false
07-28 12:43:57.357  7981  7981 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,07-28 12:43:57.357  7981  7981 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 12:43:57.357  7981  7981 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:43:57.357  7981  7981 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-28 12:43:57.357  7981  7981 D dhcpcd  : wlan0: sending REQUEST (xid 0x70c506a1), next in 4.79 seconds
,07-28 12:43:57.362  7620  7722 D UEI.SmartControl: Internal timer expired: 3
07-28 12:43:57.363  7620  7722 D UEI.SmartControl: unbind internal service
07-28 12:43:57.364  7620  7620 D UEI.SmartControl: Service.onUnbind: IControl
07-28 12:43:57.364  7620  7620 D UEI.SmartControl: Service.onDestroy
07-28 12:43:57.364  7620  7620 D UEI.SmartControl: Lock is in USE false
07-28 12:43:57.364  7620  7620 D UEI.SmartControl: unbind internal service
07-28 12:43:57.364  7620  7620 D serial_port: close(fd = 24)
07-28 12:43:57.369  7620  7620 I UEI.SmartControl: Serial port is closed.
07-28 12:43:57.369  7620  7620 I UEI.SmartControl: Serial port is closed.
07-28 12:43:57.369  7620  7620 D UEI.SmartControl: Blaster closed
07-28 12:43:57.369  7620  7620 D UEI.SmartControl: Shut down QS...
07-28 12:43:57.369  7620  7620 D UEI.SmartControl: Stopping QS lib
07-28 12:43:57.369  7620  7620 D UEI.SmartControl: QS lib stop result = true
07-28 12:43:57.369  7620  7620 D UEI.SmartControl: Stopped QS lib
07-28 12:43:57.369  7620  7620 D UEI.SmartControl: QS shutdown complete
07-28 12:43:57.378  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,07-28 12:43:57.378  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
07-28 12:43:57.379  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-28 12:43:57.379  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-28 12:43:57.379  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-28 12:43:57.379  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-28 12:43:57.380  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-28 12:43:57.380  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
07-28 12:43:57.380  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-28 12:43:57.381  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-28 12:43:57.383  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-28 12:43:57.384  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
07-28 12:43:57.384  7951  7951 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
07-28 12:43:57.396  7981  7981 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-28 12:43:57.411  7951  7951 V LGMDMManager: Create singleton instance
,07-28 12:43:57.425  7981  7981 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 12:43:57.425  7981  7981 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-28 12:43:57.426  7981  7981 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 12:43:57.426  7981  7981 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 12:43:57.427  7981  7981 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 12:43:57.427  7981  7981 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 12:43:57.427  7981  7981 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,07-28 12:43:57.427  7981  7981 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-28 12:43:57.467  6549  6673 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 847)
07-28 12:43:57.468  6549  6673 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 847)
07-28 12:43:57.478  6549  6673 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 852)
,07-28 12:43:57.482  6549  6673 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-28 12:43:57.482  6549  6673 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 853)
07-28 12:43:57.487  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.487  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e13cf6 added. We now have 2 listener(s)
07-28 12:43:57.488  1038  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:57.493  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.493  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:57.493  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.493  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.493  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33be18f7 added. We now have 9 listener(s)
07-28 12:43:57.493  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:57.496  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:43:57.499  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:57.502  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:57.502  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:57.502  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:57.502  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:57.502  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:57.502  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.502  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:57.502  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:57.505  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.506  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:57.506  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.506  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2226e9cd added. We now have 3 listener(s)
07-28 12:43:57.506  1038  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:43:57.509  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.516  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.517  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.517  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:57.517  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.517  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.517  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75c3282 added. We now have 10 listener(s)
07-28 12:43:57.517  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:57.518  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:57.518  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:57.518  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:57.518  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.518  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.518  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:57.518  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.518  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e13cf6 removed from the list
07-28 12:43:57.518  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.519  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33be18f7 removed from the list
07-28 12:43:57.519  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:43:57.519  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.521  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.521  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.522  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.522  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.522  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.522  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33be18f7 not in the list
07-28 12:43:57.522  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.522  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:57.523  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.523  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.523  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.524  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75c3282 removed from the list
07-28 12:43:57.524  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.524  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.524  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.524  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.524  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2226e9cd removed from the list
07-28 12:43:57.525  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.525  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c314d93 added. We now have 2 listener(s)
07-28 12:43:57.526  1038  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:57.528  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.528  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:57.528  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.529  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.529  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95301d0 added. We now have 9 listener(s)
07-28 12:43:57.529  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:57.529  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:43:57.532  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:57.546  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:57.546  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:57.546  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:57.546  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:57.546  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:57.546  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.546  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:57.546  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:57.548  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.548  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:57.549  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.549  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9ef4ce added. We now have 3 listener(s)
07-28 12:43:57.552  1038  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:57.553  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.556  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.567  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.567  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:57.567  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.568  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.568  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16992fef added. We now have 10 listener(s)
07-28 12:43:57.568  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:57.568  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:57.568  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:57.568  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:43:57.568  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:57.568  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:43:57.570  7951  7951 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
07-28 12:43:57.576  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:43:57.576  1038  2321 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:57.581  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:43:57.581  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:43:57.584  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:43:57.584  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:57.586  6549  6673 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:43:57.586  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:57.586  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:57.588  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:57.588  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:57.588  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:57.588  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.588  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.588  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:57.588  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.588  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c314d93 removed from the list
07-28 12:43:57.588  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.589  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95301d0 removed from the list
07-28 12:43:57.589  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:57.589  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.589  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.589  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.590  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.590  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.590  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.590  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95301d0 not in the list
07-28 12:43:57.590  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.590  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.591  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.59,2  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:57.592  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:57.592  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.592  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.592  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16992fef removed from the list
07-28 12:43:57.592  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.592  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.592  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.592  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.592  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9ef4ce removed from the list
07-28 12:43:57.593  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.593  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8398fda added. We now have 2 listener(s)
,07-28 12:43:57.593  1038  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:57.599  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.599  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:57.599  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.599  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.600  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26f2dc0b added. We now have 9 listener(s)
07-28 12:43:57.600  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:57.600  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:43:57.604  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:57.607  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:57.607  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:57.607  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:57.607  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:57.607  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:57.607  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.607  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:57.607  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:57.609  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.609  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:57.609  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.609  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3accf501 added. We now have 3 listener(s)
07-28 12:43:57.610  1038  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:57.612  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.614  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.615  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.615  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:57.615  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.615  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.615  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb0cfa6 added. We now have 10 listener(s)
,07-28 12:43:57.615  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:57.615  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:43:57.625  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:57.625  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:57.625  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:43:57.625  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:57.625  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:43:57.628  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:43:57.628  1038  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:43:57.632  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:43:57.633  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:43:57.634  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:43:57.635  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:57.636  6549  6673 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:43:57.637  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:57.637  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:57.637  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:57.637  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.637  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.637  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:57.637  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.637  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8398fda removed from the list
07-28 12:43:57.637  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.637  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26f2dc0b removed from the list
07-28 12:43:57.637  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:57.637  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.638  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.638  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.640  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.640  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.640  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.640  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26f2dc0b not in the list
07-28 12:43:57.640  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.640  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.641  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.642  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:57.642  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:57.642  6549  6673 I ,org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.642  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.642  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb0cfa6 removed from the list
07-28 12:43:57.642  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.642  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.642  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.642  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.642  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3accf501 removed from the list
07-28 12:43:57.643  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.643  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1792e03d added. We now have 2 listener(s)
07-28 12:43:57.643  1038  2090 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:43:57.647  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.647  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:57.647  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.648  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.648  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360a4032 added. We now have 9 listener(s)
07-28 12:43:57.648  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:57.649  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:43:57.651  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:57.655  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:57.655  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:57.655  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:57.655  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:57.655  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:57.655  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.655  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:57.655  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:57.657  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.658  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:43:57.658  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.658  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c527f00 added. We now have 3 listener(s)
07-28 12:43:57.658  1038  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:57.661  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.662  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:57.663  7951  8017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:43:57.664  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.664  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:57.664  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.664  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.664  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bd24339 added. We now have 10 listener(s)
07-28 12:43:57.664  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:57.664  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:57.664  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:57.664  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:43:57.664  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:57.664  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:43:57.667  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.670  1038  7969 D DhcpStateMachine: DHCPV4 succeeded on wlan0
07-28 12:43:57.671  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:43:57.671  1038  2090 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:57.671  1038  7969 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-28 12:43:57.671  1038  7969 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 12:43:57.672  1038  7969 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-28 12:43:57.672  1038  7969 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-28 12:43:57.672  1038  7969 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 12:43:57.672  1038  7969 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-28 12:43:57.672  1038  7969 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-28 12:43:57.672  1038  7969 D DhcpStateMachine: RunningState
07-28 12:43:57.679  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:43:57.679  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:43:57.680  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:43:57.681  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:43:57.682  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:43:57.683  6549  6673 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:43:57.686  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:57.687  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:57.687  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:57.687  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:57.687  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.687  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.687  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:57.687  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.687  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1792e03d removed from the list
07-28 12:43:57.688  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.688  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360a4032 removed from the list
07-28 12:43:57.688  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:57.688  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.689  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.689  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.689  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.690  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.690  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.690  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360a4032 not in the list
07-28 12:43:57.690  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.690  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.691  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.692  6549  6673 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:57.692  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:57.692  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.692  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.692  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bd24339 removed from the list
07-28 12:43:57.692  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.692  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: re,lease: The given listener does not exist in the list - probably already removed
07-28 12:43:57.692  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.692  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.692  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c527f00 removed from the list
07-28 12:43:57.694  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.694  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ee08b2c added. We now have 2 listener(s)
,07-28 12:43:57.738  1038  2016 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8022 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-28 12:43:57.739  1038  2016 I ActivityManager: Killing 7038:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,07-28 12:43:57.828  1038  1961 W libprocessgroup: failed to open /acct/uid_10085/pid_7038/cgroup.procs: No such file or directory
07-28 12:43:57.828  1038  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 12:43:57.837  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.838  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:57.838  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.838  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.838  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@300ad9f5 added. We now have 9 listener(s)
07-28 12:43:57.839  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:57.840  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:43:57.848  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:57.851  7951  8015 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-28 12:43:57.856  6549  6673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:57.856  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:57.856  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:57.856  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:57.856  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:57.856  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.856  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:57.856  6549  6673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:57.859  6549  6673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:57.859  6549  6673 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:57.859  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:57.859  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2676ddfb added. We now have 3 listener(s)
07-28 12:43:57.859  1038  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 12:43:57.861  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.864  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 12:43:57.864  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:43:57.864  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:57.865  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:57.865  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3612e18 added. We now have 10 listener(s)
07-28 12:43:57.865  6549  6673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:57.866  6549  6549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:57.866  6549  6673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:57.866  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:57.866  6549  6673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:57.866  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.866  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.866  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:57.867  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.867  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ee08b2c removed from the list
07-28 12:43:57.867  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.868  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@300ad9f5 removed from the list
07-28 12:43:57.868  6549  6673 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:57.868  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.874  8022  8022 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:43:57.875  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.875  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.876  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.876  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.876  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:57.876  6549  6673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@300ad9f5 not in the list
07-28 12:43:57.876  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.876  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.879  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:57.879  6549  6673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:57.879  6549  6673 I org.thaliproject.p2p.btcon,nectorlib.DiscoveryManager: dispose
07-28 12:43:57.879  6549  6673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3612e18 removed from the list
07-28 12:43:57.879  6549  6673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:57.879  6549  6673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:57.879  6549  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:57.879  6549  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:57.879  6549  6673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2676ddfb removed from the list
07-28 12:43:57.880  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:43:57.881  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 12:43:57.881  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 12:43:57.881  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:57.881  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 12:43:57.881  6549  6673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:43:57.897  6549  8041 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 860, name: My test thread name)
07-28 12:43:57.898  6549  8041 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 860, thread name: My test thread name)
,07-28 12:43:57.898  6549  8041 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 860, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
07-28 12:43:57.904  8022  8022 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-28 12:43:57.906  6549  8042 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 862, name: My test thread name)
07-28 12:43:57.907  6549  8042 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 862, thread name: My test thread name)
07-28 12:43:57.907  6549  8042 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 862, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
07-28 12:43:57.909  6549  6673 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-28 12:43:57.909  6549  6673 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,07-28 12:43:57.909  6549  6673 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 12:43:57.909  6549  6673 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-28 12:43:57.910  6549  6673 D com.test.thalitest.ThaliTestRunner: Total duration: 23103 ms
07-28 12:43:57.911  6549  6673 I jxcore-log: Total number of executed tests:  80
07-28 12:43:57.911  6549  6673 I jxcore-log: 
07-28 12:43:57.912  6549  6673 I jxcore-log: Number of passed tests:  80
07-28 12:43:57.912  6549  6673 I jxcore-log: 
07-28 12:43:57.912  6549  6673 I jxcore-log: Number of failed tests:  0
07-28 12:43:57.912  6549  6673 I jxcore-log: 
07-28 12:43:57.912  6549  6673 I jxcore-log: Number of ignored tests:  0
07-28 12:43:57.912  6549  6673 I jxcore-log: 
07-28 12:43:57.912  6549  6673 I jxcore-log: Total duration:  23103
07-28 12:43:57.912  6549  6673 I jxcore-log: 
07-28 12:43:57.912  6549  6673 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 12:43:57.912  6549  6673 I jxcore-log: 
07-28 12:43:57.916  6549  6673 I jxcore-log: Unit Test app is loaded
07-28 12:43:57.916  6549  6673 I jxcore-log: 
07-28 12:43:57.924  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.924  6549  6673 I jxcore-log: 
,07-28 12:43:57.930  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.930  6549  6673 I jxcore-log: 
07-28 12:43:57.931  6549  6549 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-28 12:43:57.931  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.931  6549  6673 I jxcore-log: 
07-28 12:43:57.932  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.932  6549  6673 I jxcore-log: 
07-28 12:43:57.933  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.933  6549  6673 I jxcore-log: 
07-28 12:43:57.934  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.934  6549  6673 I jxcore-log: 
07-28 12:43:57.934  8022  8022 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-28 12:43:57.935  8022  8022 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-28 12:43:57.935  8022  8022 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-28 12:43:57.936  8022  8022 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-28 12:43:57.936  8022  8022 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-28 12:43:57.938  8022  8022 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-28 12:43:57.938  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.938  6549  6673 I jxcore-log: 
07-28 12:43:57.940  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.940  6549  6673 I jxcore-log: 
07-28 12:43:57.941  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:43:57.941  6549  6673 I jxcore-log: 
07-28 12:43:57.942  8022  8022 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-28 12:43:57.942  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:43:57.942  6549  6673 I jxcore-log: 
07-28 12:43:57.943  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.943  6549  6673 I jxcore-log: 
07-28 12:43:57.944  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.944  6549  6673 I jxcore-log: 
07-28 12:43:57.946  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:43:57.946  6549  6673 I jxcore-log: 
07-28 12:43:57.947  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:43:57.947  6549  6673 I jxcore-log: 
07-28 12:43:57.947  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:43:57.947  6549  6673 I jxcore-log: 
07-28 12:43:57.948  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.948  6549  6673 I jxcore-log: 
07-28 12:43:57.949  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:57.949  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.949  6549  6673 I jxcore-log: 
07-28 12:43:57.950  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.950  6549  6673 I jxcore-log: 
07-28 12:43:57.950  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:57.950  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.950  6549  6673 I jxcore-log: 
07-28 12:43:57.951  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.951  6549  6673 I jxcore-log: 
07-28 12:43:57.952  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.952  6549  6673 I jxcore-log: 
07-28 12:43:57.953  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.953  6549  6673 I jxcore-log: 
07-28 12:43:57.953  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:43:57.953  6549  6673 I jxcore-log: 
07-28 12:43:57.954  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:43:57.954  6549  6673 I jxcore-log: 
07-28 12:43:57.955  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:43:57.955  6549  6673 I jxcore-log: 
07-28 12:43:57.956  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.956  6549  6673 I jxcore-log: 
07-28 12:43:57.957  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.957  6549  6673 I jxcore-log: 
07-28 12:43:57.957  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.957  6549  6673 I jxcore-log: 
07-28 12:43:57.958  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.958  6549  6673 I jxcore-log: 
07-28 12:43:57.959  6549  6673 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:57.959  6549  6673 I jxcore-log: 
07-28 12:43:57.961  8022  8022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:43:57.964  6549  6673 I jxcore-log: My device name is: LGE-LG-D855
07-28 12:43:57.964  6549  6673 I jxcore-log: 
07-28 12:43:57.965  8022  8022 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-28 12:43:57.967  8022  8022 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,07-28 12:43:57.998  1038  1783 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8052 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-28 12:43:58.001  7951  8015 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:58.001  7951  8015 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:43:58.085  8052  8052 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:43:58.086  8052  8052 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-28 12:43:58.096  8052  8052 V [BNRBootReceiver]: Boot Receiver Return
07-28 12:43:58.096  8052  8052 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 12:43:58.097  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-28 12:43:58.108  6730  6730 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-28 12:43:58.110  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:58.111  7951  8017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:43:58.116  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:58.121  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:58.123  1038  1961 I ActivityManager: Killing 7065:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
07-28 12:43:58.139  8063  8063 D AndroidRuntime: 
07-28 12:43:58.139  8063  8063 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-28 12:43:58.141  8063  8063 D AndroidRuntime: CheckJNI is OFF
07-28 12:43:58.143  7951  8015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
07-28 12:43:58.308  8063  8063 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-28 12:43:58.421  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:58.421  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:58.421  1038  1105 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-28 12:43:58.422  1038  1105 I ActivityManager: Killing 6549:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
07-28 12:43:58.438  7951  8015 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,07-28 12:43:58.452  7951  8015 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
07-28 12:43:58.452  7951  8015 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-28 12:43:58.452  7951  8015 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-28 12:43:58.453  7951  8015 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
07-28 12:43:58.453  7951  8015 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
07-28 12:43:58.458  1038  2090 I WindowState: WIN DEATH: Window{2049a2f4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-28 12:43:58.459  1038  1545 D WifiService: Client connection lost with reason: 4
07-28 12:43:58.465  7951  8015 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
07-28 12:43:58.468  7951  8015 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
07-28 12:43:58.469  1038  2090 D InputDispatcher: Window went away: Window{2049a2f4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-28 12:43:58.592  1038  1105 I ActivityManager:   Force finishing activity ActivityRecord{2d4b532 u0 com.test.thalitest/.MainActivity t40}
,07-28 12:43:58.628   338   351 E GBMv2   : DFP En is all cleared set to be enabled
,07-28 12:43:58.633  1038  1604 W libprocessgroup: failed to open /acct/uid_10093/pid_7065/cgroup.procs: No such file or directory
07-28 12:43:58.638  1038  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-28 12:43:58.639  8022  8022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 12:43:58.642  1038  1126 I ActivityManager:   Force finishing activity ActivityRecord{2d4b532 u0 com.test.thalitest/.MainActivity t40 f}
07-28 12:43:58.642  1038  1126 W ActivityManager: Duplicate finish request for ActivityRecord{2d4b532 u0 com.test.thalitest/.MainActivity t40 f}
,07-28 12:43:58.664  1038  1992 W ActivityManager: Spurious death for ProcessRecord{37f4ba98 6549:com.test.thalitest/u0a118}, curProc for 6549: null
07-28 12:43:58.667  1969  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,07-28 12:43:58.668  1969  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{b5c0bea co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-28 12:43:58.671  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-28 12:43:58.677  4495  4495 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-28 12:43:58.678  4495  4495 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-28 12:43:58.678  4495  4495 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-28 12:43:58.678  4495  4495 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-28 12:43:58.678  4495  4495 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:43:58.678  4495  4495 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:43:58.678  4495  4495 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:58.678  4495  4495 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:58.678  4495  4495 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:58.678  2041  2041 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-28 12:43:58.678  4495  4495 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:58.678  4495  4495 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:58.678  4495  4495 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:58.678  3848  3848 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,07-28 12:43:58.683  7515  7515 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-28 12:43:58.684  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 12:43:58.684  2095  2095 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-28 12:43:58.686  1969  3991 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-28 12:43:58.686  1969  3991 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ce8edb co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-28 12:43:58.686  2095  2095 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
07-28 12:43:58.688  1038  1540 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:43:58.688  1038  1540 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:43:58.689  1038  1540 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:43:58.689  1038  1540 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:43:58.689  2502  2616 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-28 12:43:58.689  1038  1540 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:43:58.690  1038  1540 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 12:43:58.692  1038  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
07-28 12:43:58.692  1038  1546 D ConnectivityService: identical MTU - not setting
07-28 12:43:58.692  1038  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 12:43:58.692  1038  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 12:43:58.692  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:58.692  1038  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:58.693  1038  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:58.694  1605  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-28 12:43:58.707  1038  1443 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:43:58.714  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:58.714  7951  8017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:43:58.739  1038  1102 W InputMethodInfo: Duplicated subtype definition found: , voice
,07-28 12:43:58.744  1038  1961 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:43:58.748  4605  4605 I art     : Explicit concurrent mark sweep GC freed 8188(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 438us total 95.935ms
07-28 12:43:58.760  1038  1038 D administrator: Handling package changes for user 0
,07-28 12:43:58.787  2095  2095 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-28 12:43:58.787  2095  2205 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-28 12:43:58.802  2095  2095 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-28 12:43:58.803  1931  1931 D ActionManagerService: notifyUserLog: 1000003
07-28 12:43:58.804  2095  2095 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-28 12:43:58.804  3848  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,07-28 12:43:58.804  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-28 12:43:58.805  1605  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 12:43:58.805  1605  1655 D KeyguardModel: createShortcutInfo...
07-28 12:43:58.805  2095  2095 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-28 12:43:58.807  2095  2095 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-28 12:43:58.808  1605  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-28 12:43:58.808  1605  1655 D KeyguardModel: createShortcutInfo...
07-28 12:43:58.811  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:43:58.815  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:58.826  2095  2095 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
07-28 12:43:58.827  1931  1931 D ActionManagerService: notifyUserLog: 1000004
07-28 12:43:58.828  3848  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-28 12:43:58.829  1605  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,07-28 12:43:58.829  1605  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:58.829  1605  1655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-28 12:43:58.830  1605  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:43:58.833  3848  4487 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:43:58.836  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-28 12:43:58.836  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-28 12:43:58.837  1038  1054 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:43:58.837  1038  1054 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , create_time: 1430832262123
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , expire_time: 0
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , display: false
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , animation: false }
07-28 12:43:58.838  1605  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , create_time: 1430832262287
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , expire_time: 0
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , display: false
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , animation: false }
07-28 12:43:58.838  1605  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , create_time: 1469186101943
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , expire_time: 0
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , display: false
07-28 12:43:58.838  2095  2095 I GBoardWebViewUtils: , animation: false }
07-28 12:43:58.845  1605  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 12:43:58.845  1605  1655 D KeyguardModel: createShortcutInfo...
,07-28 12:43:58.848  2095  8095 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
07-28 12:43:58.851  1605  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-28 12:43:58.851  1605  1655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 12:43:58.859  1605  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:43:58.859  1605  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,07-28 12:43:58.861  1605  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 12:43:58.861  1605  1655 D KeyguardModel: createShortcutInfo...
07-28 12:43:58.865  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:58.865  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:58.866  8022  8022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:58.869  2095  2095 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 12:43:58.870  2095  2095 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,07-28 12:43:58.872  1605  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:58.872  1605  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-28 12:43:58.873  1605  1655 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-28 12:43:58.873  1605  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 12:43:58.873  1605  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:43:58.873  1605  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-28 12:43:58.874  1605  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-28 12:43:58.874  1605  1655 D KeyguardModel: createShortcutInfo...
,07-28 12:43:58.877  1896  1896 D SplitUIManager: split_name #11 / not available #0
07-28 12:43:58.877  1896  1896 D SplitUIService: removed split : 
07-28 12:43:58.877  1605  1605 D KeyguardModel: handleShortcutListChanged...
07-28 12:43:58.877  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-28 12:43:58.883  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 12:43:58.883  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 12:43:58.883  6730  6730 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 12:43:58.883  6730  6730 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 12:43:58.888  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-28 12:43:58.908  1038  2016 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-28 12:43:58.908  1896  1896 D SplitUIManager: split_name #11 / not available #0
07-28 12:43:58.908  1896  1896 I SplitUIService: split app #11
07-28 12:43:58.909  1605  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 12:43:58.909  1605  1655 D KeyguardModel: createShortcutInfo...
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 12:43:58.909  7515  7515 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,07-28 12:43:58.909  6730  6730 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 12:43:58.909  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-28 12:43:58.910  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 12:43:58.910  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 12:43:58.910  6730  6730 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 12:43:58.910  6730  6730 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-28 12:43:58.910  6730  6730 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 12:43:58.913  1605  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-28 12:43:58.913  1605  1655 D KeyguardModel: createShortcutInfo...
07-28 12:43:58.914  1605  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:43:58.914  1605  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-28 12:43:58.915  1605  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 12:43:58.915  1605  1655 D KeyguardModel: createShortcutInfo...
07-28 12:43:58.916  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:58.916  7951  8017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:43:58.917  1605  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:43:58.917  1605  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-28 12:43:58.917  1038  1577 V SIM_STK : Menu title from STK is T-Mobile
07-28 12:43:58.918  1605  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 12:43:58.918  1605  1655 D KeyguardModel: createShortcutInfo...
07-28 12:43:58.919  1605  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 12:43:58.920  1605  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-28 12:43:58.925  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:43:58.926  1605  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-28 12:43:58.926  1605  1655 D KeyguardModel: createShortcutInfo...
,07-28 12:43:58.939  1605  1605 D KeyguardModel: handleShortcutListChanged...
07-28 12:43:58.939  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,07-28 12:43:58.948  2095  2095 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-28 12:43:58.952  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:58.957  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:58.957  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:58.957  8022  8022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:58.959  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:58.960  7951  8017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:43:58.967  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:43:58.969  1038  1038 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-28 12:43:58.969  1038  1038 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 12:43:58.969  1038  1038 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-28 12:43:58.971  1038  1579 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
,07-28 12:43:58.978  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:58.981  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:58.982  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:58.982  8022  8022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:58.983  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:58.984  7951  8017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 12:43:58.989  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:43:58.992  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:58.995  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:58.995  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:58.996  8022  8022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:43:58.999  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:59.001   331   418 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,07-28 12:43:59.002  3246  8101 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-28 12:43:59.016  2095  2095 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
07-28 12:43:59.018  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:43:59.020  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-28 12:43:59.021  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-28 12:43:59.022  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-28 12:43:59.024  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-28 12:43:59.036  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:59.040  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{248d40fa u0 com.lge.launcher2/.Launcher t39} time:155684
07-28 12:43:59.040  2095  2095 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-28 12:43:59.040  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:43:59.042  2095  2319 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-28 12:43:59.042  2095  2319 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
07-28 12:43:59.050  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 12:43:59.055  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
07-28 12:43:59.056  2095  2095 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 12:43:59.056  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:43:59.057  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:59.057  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:59.057  8022  8022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:59.063  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:59.065  2095  2095 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
07-28 12:43:59.067  2652  2652 D [Concierge]Service: onStartCommand(). Type : 8
07-28 12:43:59.067  2652  2652 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-28 12:43:59.068  2652  2652 D [Concierge]Service: Update widget ID : 11
07-28 12:43:59.070  2095  2095 D [Concierge]WidgetView: change position of spinner
07-28 12:43:59.071  2652  2652 D [Concierge]Service: onStartCommand(). Type : 0
07-28 12:43:59.071  2095  2095 I [Concierge]WidgetView: initWebView(). Time : 1469702639071
07-28 12:43:59.075  1038  1126 I art     : Explicit concurrent mark sweep GC freed 62013(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.448ms total 276.599ms
07-28 12:43:59.075  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 12:43:59.079  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:59.083  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:59.083  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:59.086  8022  8022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 12:43:59.089  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 12:43:59.103  8063  8063 D AndroidRuntime: Shutting down VM
,07-28 12:43:59.114  2095  2095 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 704146370
,07-28 12:43:59.114  2095  2095 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-28 12:43:59.115  2095  2095 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-28 12:43:59.117  2095  2095 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@297bd078
07-28 12:43:59.118  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-28 12:43:59.118  2095  2095 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 12:43:59.119  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:43:59.123  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-28 12:43:59.123  2095  2095 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-28 12:43:59.123  2095  2095 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-28 12:43:59.142  1038  1126 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8105 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-28 12:43:59.144  2095  2095 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469702511842, New one : 1469702639071
07-28 12:43:59.144  2095  2095 D [Concierge]WidgetView: Unregister all receivers
07-28 12:43:59.144  2095  2095 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-28 12:43:59.146  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:43:59.146  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:43:59.148  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-28 12:43:59.149  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:59.149  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-28 12:43:59.150  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-28 12:43:59.151  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-28 12:43:59.152  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-28 12:43:59.153  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:43:59.153  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 12:43:59.154  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 12:43:59.163  1038  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:59.163  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:59.167  1038  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-28 12:43:59.179  8022  8022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 12:43:59.181  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:59.184  7922  7922 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:43:59.187  7922  7922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:59.189  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:43:59.192  2095  2095 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,07-28 12:43:59.193  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:59.198  1038  1577 I ActivityManager: Killing 7105:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-28 12:43:59.203  2095  2095 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-28 12:43:59.203  2095  2095 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
07-28 12:43:59.204  2095  2095 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-28 12:43:59.206  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:59.206  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:59.206  2095  2095 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 12:43:59.209  8022  8022 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 12:43:59.210  8022  8022 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:43:59.210  8022  8022 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:43:59.225  2095  2095 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ab77bdf time:155870
,07-28 12:43:59.266  1038  1983 W libprocessgroup: failed to open /acct/uid_10005/pid_7105/cgroup.procs: No such file or directory
,07-28 12:43:59.269  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:59.271  7922  7922 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 12:43:59.271  7922  7922 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 12:43:59.272  6730  6730 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 12:43:59.275  6730  6730 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 12:43:59.279  8022  8022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 12:43:59.279  8022  8022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 12:43:59.279  8022  8022 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,07-28 12:43:59.280  8022  8022 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 12:43:59.280  8022  8022 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 12:43:59.282  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:59.284  8022  8022 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 12:43:59.285  8022  8022 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 12:43:59.286  8022  8022 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-28 12:43:59.306  8022  8022 D LgDataFeature: LgDataFeature() Constructor: none
07-28 12:43:59.306  8022  8022 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 12:43:59.310  8022  8022 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-28 12:43:59.312  8022  8022 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-28 12:43:59.312  8022  8022 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-28 12:43:59.312  8022  8022 V SoundPool: doLoad: loading sample sampleID=1
07-28 12:43:59.312  8022  8125 V SoundPool: Start decode
07-28 12:43:59.312  8022  8125 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-28 12:43:59.312   315   315 V MediaPlayerService: decode(22, 10857164, 17813)
07-28 12:43:59.312   315   315 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-28 12:43:59.312   315   315 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-28 12:43:59.312   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-28 12:43:59.312   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-28 12:43:59.312   315   315 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-28 12:43:59.312   315   315 V MediaPlayerService: player type = 3
07-28 12:43:59.312  8022  8022 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 12:43:59.312   315   315 V AwesomePlayer: AwesomePlayer create()
07-28 12:43:59.312   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:59.312   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:59.312   315   315 V AwesomePlayer: setAudioSink() 
07-28 12:43:59.312   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:59.312   315   315 V AudioCache: notify(0xb1432280, 8, 0, 0)
07-28 12:43:59.312   315   315 V AudioCache: ignored
07-28 12:43:59.312   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:59.313   315   315 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
07-28 12:43:59.313   315   315 V AwesomePlayer: setDataSource_l dataSource
07-28 12:43:59.313   315   315 V LGParserOSAL: SniffLGParser start
07-28 12:43:59.313   315   315 V LGParserOSAL: MainType:5, SubType=0
07-28 12:43:59.313   315   315 V LGParserOSAL: #### check Mime : application/ogg
07-28 12:43:59.313   315   315 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-28 12:43:59.313   315   315 E MediaExtractor: Use LGExtractor :application/ogg 
07-28 12:43:59.315  7620  7620 D UEI.SmartControl: QS Service created
07-28 12:43:59.315  8022  8022 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 12:43:59.316  8022  8022 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 12:43:59.316  8022  8022 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 12:43:59.321  7620  7620 I UEI.SmartControl: Service initServices...
07-28 12:43:59.322  7620  7620 D UEI.SmartControl: QS start get config
07-28 12:43:59.322  8022  8022 V LGMDMManager: Create singleton instance
07-28 12:43:59.334   315   315 V LGParserOSAL: supported mime: application/ogg
07-28 12:43:59.334   315   315 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-28 12:43:59.334   315   315 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-28 12:43:59.334   315   315 V AwesomePlayer: mBitrate = -1 bits/sec
07-28 12:43:59.334   315   315 V AwesomePlayer: AudioTrack Setting
07-28 12:43:59.334   315   315 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-28 12:43:59.334   315   315 V AwesomePlayer: setAudioSource() 
07-28 12:43:59.334   315   315 V MediaPlayerService: prepare
07-28 12:43:59.334   315   315 V AwesomePlayer: prepareAsync_l() 
07-28 12:43:59.334   315   315 V MediaPlayerService: wait for prepare
,07-28 12:43:59.334   315  8126 V AwesomePlayer: onPrepareAsyncEvent() 
07-28 12:43:59.334   315  8126 V AwesomePlayer: initAudioDecoder() 
07-28 12:43:59.334   315  8126 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:43:59.334   315  8126 V AudioSystem: isOffloadSupported()
07-28 12:43:59.334   315  8126 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:43:59.334   315  8126 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:43:59.334   315  8126 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 12:43:59.334   315  8126 V AwesomePlayer: getUseOffload() = 0 
07-28 12:43:59.334   315  8126 V OMXCodec: OMXCodec::Create
07-28 12:43:59.334   315  8126 V OMXCodec: findMatchingCodecs()
07-28 12:43:59.334   315  8126 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-28 12:43:59.335   315  8126 V OMXCodec: matchingCodecs.size()=1
07-28 12:43:59.335   315  8126 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-28 12:43:59.336   315  8126 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-28 12:43:59.336   315  8126 V LGCodecAdapter: LG Codec Adapter start
07-28 12:43:59.336   315  8126 V OMXCodec: OMXCodec Createtor
07-28 12:43:59.336   315  8126 V OMXCodec: setComponentRole
07-28 12:43:59.336   315  8126 V OMXCodec: configureCodec protected=0
07-28 12:43:59.336   315  8126 V LGCodecAdapter: called getLGCodecSpecificData
07-28 12:43:59.336   315  8126 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-28 12:43:59.337   315  8126 V LGCodecOSAL: Called LGconfigureCodecMETA
07-28 12:43:59.337   315  8126 V LGCodecOSAL: Called LGconfigureCodecMSG
07-28 12:43:59.337   315  8126 V LGCodecOSAL: Not support LGCodec
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:43:59.337   315  8126 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-28 12:43:59.337   315  8126 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-28 12:43:59.337   315  8126 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-28 12:43:59.337   315  8126 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 12:43:59.337   315  8126 V AudioSystem: isOffloadSupported()
07-28 12:43:59.337   315  8126 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 12:43:59.337   315  8126 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-28 12:43:59.337   315  8126 V OMXCodec: init()
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-28 12:43:59.337   315  8126 V OMXCodec: allocateBuffers
07-28 12:43:59.337   315  8126 V OMXCodec: allocateBuffersOnPort portIndex=0
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
07-28 12:43:59.337   31,5  8126 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
07-28 12:43:59.337   315  8126 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
07-28 12:43:59.337   315  8126 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:43:59.337   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:43:59.337   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:43:59.337   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-28 12:43:59.337   315  8126 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 12:43:59.337   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-28 12:43:59.337   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-28 12:43:59.337   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-28 12:43:59.338   315  8126 V OMXCodec: init() mAsyncCompletion wait free! 
07-28 12:43:59.338   315  8126 V AwesomePlayer: finishAsyncPrepare_l() 
07-28 12:43:59.338   315  8126 V AudioCache: notify(0xb1432280, 5, 0, 0)
07-28 12:43:59.338   315  8126 V AudioCache: ignored
07-28 12:43:59.338   315  8126 V AudioCache: notify(0xb1432280, 1, 0, 0)
07-28 12:43:59.338   315  8126 V AudioCache: prepared
07-28 12:43:59.340   315   315 V AudioCache: wait - success
07-28 12:43:59.340   315   315 V MediaPlayerService: start
07-28 12:43:59.340   315   315 V AwesomePlayer: play_l() 
07-28 12:43:59.340   315   315 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-28 12:43:59.340   315   315 V AwesomePlayer: createAudioPlayer_l
07-28 12:43:59.340   315   315 V AwesomePlayer: seekAudioIfNecessary_l() 
07-28 12:43:59.340   315   315 V AwesomePlayer: startAudioPlayer_l() 
07-28 12:43:59.340   315   315 D AudioPlayer: start of Playback, useOffload 0
07-28 12:43:59.340   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:43:59.340   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048736
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048896
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:59.341   315 , 8128 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-28 12:43:59.341   315  8128 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 12:43:59.341   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 12:43:59.342   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
07-28 12:43:59.342   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
07-28 12:43:59.342   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
07-28 12:43:59.342   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
07-28 12:43:59.342   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-28 12:43:59.342   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-28 12:43:59.342   315   315 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-28 12:43:59.345   315   315 V AudioCache: notify(0xb1432280, 6, 0, 0)
07-28 12:43:59.345   315   315 V AudioCache: ignored
07-28 12:43:59.345   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.345   315  8129 V AudioCache: memcpy(0xaf1f9000, 0xb57f5000, 4096)
07-28 12:43:59.345   315   315 V MediaPlayerService: wait for playback complete
07-28 12:43:59.345   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.345   315  8129 V AudioCache: memcpy(0xaf1fa000, 0xb57f5000, 4096)
07-28 12:43:59.345   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.345   315  8129 V AudioCache: memcpy(0xaf1fb000, 0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: memcpy(0xaf1fc000, 0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: memcpy(0xaf1fd000, 0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: memcpy(0xaf1fe000, 0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: memcpy(0xaf1ff000, 0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.346   315  8129 V AudioCache: memcpy(0xaf200000, 0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: memcpy(0xaf201000, 0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: memcpy(0xaf202000, 0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: memcpy(0xaf203000, 0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: memcpy(0xaf204000, 0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: memcpy(0xaf205000, 0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: memcpy(0xaf206000, 0xb57f5000, 4096)
07-28 12:43:59.347   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: memcpy(0xaf207000, 0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: memcpy(0xaf208000, 0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: memcpy(0xaf209000, 0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: memcpy(0xaf20a000, 0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: memcpy(0xaf20b000, 0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.348   315  8129 V AudioCache: memcpy(0xaf20c000, 0xb57f5000, 4096)
07-28 12:43:59.349   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.349   315  8129 V AudioCache: memcpy(0xaf20d000, 0xb57f5000, 4096)
07-28 12:43:59.350   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.350   315  8129 V AudioCache: memcpy(0xaf20e000, 0xb57f5000, 4096)
07-28 12:43:59.351   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.351   315  8129 V AudioCache: memcpy(0xaf20f000, 0xb57f5000, 4096)
07-28 12:43:59.351   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.351   315  8129 V AudioCache: memcpy(0xaf210000, 0xb57f5000, 4096)
07-28 12:43:59.351   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.351   315  8129 V AudioCache: memcpy(0xaf211000, 0xb57f5000, 4096)
07-28 12:43:59.352   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.352   315  8129 V AudioCache: memcpy(0xaf212000, 0xb57f5000, 4096)
07-28 12:43:59.352   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.352   315  8129 V AudioCache: memcpy(0xaf213000, 0xb57f5000, 4096)
07-28 12:43:59.352   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.352   315  8129 V AudioCache: memcpy(0xaf214000, 0xb57f5000, 4096)
07-28 12:43:59.352   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.352   315  8129 V AudioCache: memcpy(0xaf215000, 0xb57f5000, 4096)
07-28 12:43:59.353   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.353   315  8129 V AudioCache: memcpy(0xaf216000, 0xb57f5000, 4096)
07-28 12:43:59.353   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.353   315  8129 V AudioCache: memcpy(0xaf217000, 0xb57f5000, 4096)
07-28 12:43:59.353   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.353   315  8129 V AudioCache: memcpy(0xaf218000, 0xb57f5000, 4096)
07-28 12:43:59.354   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.354   315  8129 V AudioCache: memcpy(0xaf219000, 0xb57f5000, 4096)
07-28 12:43:59.354   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.354   315  8129 V AudioCache: memcpy(0xaf21a000, 0xb57f5000, 4096)
07-28 12:43:59.355   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.355   315  8129 V AudioCache: memcpy(0xaf21b000, 0xb57f5000, 4096)
07-28 12:43:59.355   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.355   315  8129 V AudioCache: memcpy(0xaf21c000, 0xb57f5000, 4096)
07-28 12:43:59.355   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.355   315  8129 V AudioCache: memcpy(0xaf21d000, 0xb57f5000, 4096)
07-28 12:43:59.356   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.356   315  8129 V AudioCache: memcpy(0xaf21e000, 0xb57f5000, 4096)
07-28 12:43:59.356   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.356   315  8129 V AudioCache: memcpy(0xaf21f000, 0xb57f5000, 4096)
07-28 12:43:59.356   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.356   315  8129 V AudioCache: memcpy(0xaf220000, 0xb57f5000, 4096)
07-28 12:43:59.357   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.357   315  8129 V AudioCache: memcpy(0xaf221000, 0xb57f5000, 4096)
07-28 12:43:59.357   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.357   315  8129 V AudioCache: memcpy(0xaf222000, 0xb57f5000, 4096)
07-28 12:43:59.358  8022  8022 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 12:43:59.358   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.358   315  8129 V AudioCache: memcpy(0xaf223000, 0xb57f5000, 4096)
07-28 12:43:59.358   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.358  8022  8022 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
07-28 12:43:59.358   315  8129 V AudioCache: memcpy(0xaf224000, 0xb57f5000, 4096)
07-28 12:43:59.359   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.359   315  8129 V AudioCache: memcpy(0xaf225000, 0xb57f5000, 4096)
07-28 12:43:59.359   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.359   315  8129 V AudioCache: memcpy(0xaf226000, 0xb57f5000, 4096)
07-28 12:43:59.359   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.359   315  8129 V AudioCache: memcpy(0xaf227000, 0xb57f5000, 4096)
07-28 12:43:59.359  8022  8022 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7236
07-28 12:43:59.359   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-28 12:43:59.360   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.360   315  8129 V AudioCache: memcpy(0xaf228000, 0xb57f5000, 4096)
07-28 12:43:59.360   315  8129 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:43:59.360   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.360   315  8129 V AudioCache: memcpy(0xaf229000, 0xb57f5000, 4096)
07-28 12:43:59.360   315  8129 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:43:59.360   315  8129 V AudioCache: write(0xb57f5000, 4096)
07-28 12:43:59.360   315  8129 V AudioCache: memcpy(0xaf22a000, 0xb57f5000, 4096)
07-28 12:43:59.360   315  8129 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:43:59.360   315  8129 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 12:43:59.360   315  8129 V AwesomePlayer: postAudioEOS() 
07-28 12:43:59.360   315  8129 V AudioCache: write(0xb57f5000, 280)
07-28 12:43:59.360   315  8129 V AudioCache: memcpy(0xaf22b000, 0xb57f5000, 280)
07-28 12:43:59.361  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 12:43:59.361   315  8126 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-28 12:43:59.361   315  8126 V AwesomePlayer: onStreamDone
07-28 12:43:59.361   315  8126 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-28 12:43:59.361   315  8126 V AudioCache: notify(0xb1432280, 2, 0, 0)
07-28 12:43:59.361   315  8126 V AudioCache: playback complete
07-28 12:43:59.361   315  8126 V AwesomePlayer: pause_l() 
07-28 12:43:59.361   315  8126 V AudioCache: notify(0xb1432280, 7, 0, 0)
07-28 12:43:59.361   315  8126 V AudioCache: ignored
07-28 12:43:59.361   315  8126 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:59.361   315  8126 D AudioPlayer: Pause Playback at 1068125
07-28 12:43:59.361   315   315 V AudioCache: wait - success
07-28 12:43:59.361   315   315 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-28 12:43:59.362   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:59.362   315   315 V AudioCache: notify(0xb1432280, 8, 0, 0)
07-28 12:43:59.362   315   315 V AudioCache: ignored
07-28 12:43:59.362   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:59.362   315   315 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-28 12:43:59.362   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-28 12:43:59.362   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-28 12:43:59.362   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-28 12:43:59.362   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
07-28 12:43:59.362   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-28 12:43:59.363   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
07-28 12:43:59.363   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-28 12:43:59.363   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
07-28 12:43:59.363   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-28 12:43:59.363   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
07-28 12:43:59.363   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 12:43:59.363   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-28 12:43:59.363   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:43:59.363   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 12:43:59.364   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-28 12:43:59.364   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-28 12:43:59.364   315  8128 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-28 12:43:59.364   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 12:43:59.364   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-28 12:43:59.364   315   315 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-28 12:43:59.365  7951  7951 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-28 12:43:59.365   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-28 12:43:59.365   315   315 D AudioPlayer: AudioPlayer releasing audio source
07-28 12:43:59.365   315   315 D AudioPlayer: AudioPlayer done releasing audio source
07-28 12:43:59.365  2095  2095 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
07-28 12:43:59.366   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:59.366   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:59.366   315   315 V AwesomePlayer: ~AwesomePlayer call
07-28 12:43:59.366   315   315 V AwesomePlayer: reset_l() 
07-28 12:43:59.366   315   315 V AwesomePlayer: cancelPlayerEvents
07-28 12:43:59.366  8022  8125 V SoundPool: close(31)
07-28 12:43:59.366  8022  8125 V SoundPool: pointer = 0x9fe56000, size = 205080, sampleRate = 48000, numChannels = 2
07-28 12:43:59.367  1840  1840 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
07-28 12:43:59.371  2224  2224 I ConfigService: onCreate
07-28 12:43:59.372  2224  2224 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,07-28 12:43:59.375  1840  1840 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-28 12:43:59.385  2224  2224 I ConfigService: onBind returning update interface
07-28 12:43:59.386  2224  2224 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-28 12:43:59.386  2224  2224 I ConfigService: onBind returning config service
07-28 12:43:59.405  2095  2935 I GBoardtInterface: onReloaded()
07-28 12:43:59.409  2095  2095 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
07-28 12:43:59.414  3848  4487 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:43:59.420  3848  3864 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,07-28 12:43:59.421  2224  2224 I ConfigService: onDestroy
07-28 12:43:59.425  1840  8132 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-28 12:43:59.426  1931  1931 D ActionManagerService: notifyUserLog: 1000001
07-28 12:43:59.427  3848  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-28 12:43:59.427  3848  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-28 12:43:59.431  1931  1931 D ActionManagerService: notifyUserLog: 1000001
07-28 12:43:59.432  3848  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-28 12:43:59.432  3848  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,07-28 12:43:59.432  3848  4489 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
07-28 12:43:59.432  3848  4489 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
07-28 12:43:59.433  3848  4487 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 12:43:59.436  2095  2095 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
07-28 12:43:59.436  2095  2095 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
07-28 12:43:59.438  2095  2095 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
07-28 12:43:59.438  2095  2095 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-28 12:43:59.440  2095  2095 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
07-28 12:43:59.440  2095  2095 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-28 12:43:59.452  5927  8137 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,07-28 12:43:59.452  1840  8139 I PeopleContactsSync: CP2 sync disabled
07-28 12:43:59.457  1840  4741 I Icing   : doRemovePackageData com.test.thalitest
07-28 12:43:59.463  1840  8138 W GmsApplication: Using Auth Proxy for data requests.
07-28 12:43:59.467  1840  8138 W GmsApplication: Using Auth Proxy for data requests.
,07-28 12:43:59.564  6911  6911 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,07-28 12:43:59.573  2186  2329 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:59.575  2186  2329 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:43:59.576  2186  8142 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-28 12:43:59.580  2186  8142 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
07-28 12:43:59.581  2186  8142 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-28 12:43:59.581  2186  8142 E AndroidRuntime: Process: android.process.acore, PID: 2186
07-28 12:43:59.581  2186  8142 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
,07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:59.581  2186  8142 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:43:59.600  1038  2058 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8144 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-28 12:43:59.604  2186  8142 I Process : Sending signal. PID: 2186 SIG: 9
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:43:59.606  1038  8150 E DropBoxManagerService: 	... 5 more
07-28 12:43:59.607  2224  2241 I art     : Explicit concurrent mark sweep GC freed 5149(307KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 854us total 24.338ms
07-28 12:43:59.611  1840  8156 E SQLiteLog: (3850) statement aborts at 125: [DELETE FROM FileContent40 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
07-28 12:43:59.612  1840  8156 E DocListDatabase: Failed to delete from FileContent40
07-28 12:43:59.612  1840  8156 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:393)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at com.google.android.gms.drive.database.d.a(SourceFile:1017)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at com.google.android.gms.drive.b.c.run(SourceFile:58)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at com.google.android.gms.drive.g.an.run(SourceFile:51)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-28 12:43:59.612  1840  8156 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: FATAL EXCEPTION: pool-29-thread-1
07-28 12:43:59.613  1840  8156 E AndroidRuntime: Process: com.google.android.gms, PID: 1840
07-28 12:43:59.613  1840  8156 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:393)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.a(SourceFile:1017)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at com.google.android.gms.drive.b.c.run(SourceFile:58)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at com.google.android.gms.drive.g.an.run(SourceFile:51)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-28 12:43:59.613  1840  8156 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,07-28 12:43:59.615  1840  8156 I Process : Sending signal. PID: 1840 SIG: 9
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:43:59.617  1038  8163 E DropBoxManagerService: 	... 5 more
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: Error inserting f004=13 f005=8144 f002=1469702639605 f003=com.lge.email f006=10023
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:59.633  4495  4542 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
,07-28 12:43:59.638  1038  1545 D WifiService: Client connection lost with reason: 4
07-28 12:43:59.655  7620  7620 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac2: open failed: EROFS (Read-only file system)
,07-28 12:43:59.656  7620  7620 I UEI.SmartControl: Specific region DB is not found, use default...
07-28 12:43:59.673  7620  7620 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)
07-28 12:43:59.673  7620  7620 I UEI.SmartControl: Supports setup maps: true
07-28 12:43:59.674  7620  7620 W System.err: java.lang.NullPointerException: Attempt to get length of null array
,07-28 12:43:59.674  7620  7620 W System.err: 	at com.uei.control.core.ab.b(Unknown Source)
07-28 12:43:59.674  7620  7620 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
07-28 12:43:59.674  7620  7620 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
07-28 12:43:59.674  7620  7620 W System.err: 	at com.uei.control.Service.a(Unknown Source)
07-28 12:43:59.674  7620  7620 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
07-28 12:43:59.674  7620  7620 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
07-28 12:43:59.674  7620  7620 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
07-28 12:43:59.674  7620  7620 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
07-28 12:43:59.674  7620  7620 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:59.674  7620  7620 W System.err: ,	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:59.674  7620  7620 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:59.674  7620  7620 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:59.674  7620  7620 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:59.674  7620  7620 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:59.674  7620  7620 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:59.674  7620  7620 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 12:43:59.674  7620  76,20 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 12:43:59.674  7620  7620 I UEI.SmartControl: ### init IR Blaster...
07-28 12:43:59.678  7620  7620 D serial_port: Configuring serial port
07-28 12:43:59.678  7620  7620 E UEI.SmartControl: UEIBLaster setting for 616
07-28 12:43:59.678  7620  7620 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 12:43:59.678  7620  7620 I UEI.SmartControl: configuring settings for MAXQ616
07-28 12:43:59.678  7620  7620 I UEI.SmartControl: Get version...
07-28 12:43:59.694  7620  8169 D UEI.SmartControl: serial port data available: 21

```
