#### Test 776224163c26f5f_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-28 09:43:27.574  4576  6508 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 194 ms] updated apps [took 194 ms] 
07-28 09:43:27.700  6512  6512 D DocsApplication: Installing DEX configuration.
07-28 09:43:27.717  6512  6512 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
07-28 09:43:27.721  6512  6512 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{b6c6eb com.google.android.apps.docs}
07-28 09:43:27.738  6512  6512 D TAG     : onCreate()
07-28 09:43:27.764  6512  6512 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
--------- beginning of system
07-28 09:43:28.064  1036  1996 I ActivityManager: Killing 5470:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-28 09:43:28.149  1036  2040 W libprocessgroup: failed to open /acct/uid_10005/pid_5470/cgroup.procs: No such file or directory
07-28 09:43:28.359   329   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-28 09:43:28.363  3184  6541 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-28 09:43:28.564  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-28 09:43:28.564  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-28 09:43:28.574  1843  4747 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
07-28 09:43:28.615  1843  4747 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-28 09:43:28.643  1843  4747 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
07-28 09:43:28.907  6553  6553 D AndroidRuntime: 
07-28 09:43:28.907  6553  6553 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 09:43:28.911  6553  6553 D AndroidRuntime: CheckJNI is OFF
07-28 09:43:29.066  6512  6512 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:29.066  6512  6512 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 09:43:29.116  6553  6553 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-28 09:43:29.122  1036  1951 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 09:43:29.133  1978  2004 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-28 09:43:29.136  1036  1951 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-28 09:43:29.137  1036  1951 D ActivityManager: setTaskToReturnTo : TaskRecord{3a3a68b0 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 09:43:29.137  1036  1951 D ActivityManager: setTaskToReturnTo : TaskRecord{3a3a68b0 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-28 09:43:29.138  1036  1951 D WindowStateEx: AppWindowTokenEx init.. 
07-28 09:43:29.139   342   364 E GBMv2   : DFP En is all cleared set to be enabled
07-28 09:43:29.174  1036  1951 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6576 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-28 09:43:29.178  6553  6553 D AndroidRuntime: Shutting down VM
07-28 09:43:29.192  6075  6075 I LockScreenSettings: New app installed broadcast received ..
07-28 09:43:29.196  6512  6512 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-28 09:43:29.203  6075  6075 I LockScreenSettings: Number of installed packages  1
07-28 09:43:29.222  1978  2004 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-28 09:43:29.222  1978  2004 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18e35157 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 09:43:29.223  1978  1994 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-28 09:43:29.223  1978  1994 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1bdc5444 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-28 09:43:29.261  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
07-28 09:43:29.266  6576  6576 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-28 09:43:29.318  1036  2095 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6609 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 09:43:29.332  6576  6576 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-28 09:43:29.338  6576  6576 I LibraryLoader: Loading: webviewchromium
07-28 09:43:29.342  6576  6576 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 490-494)
07-28 09:43:29.342  6576  6576 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 09:43:29.358  6576  6576 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3474741d}
07-28 09:43:29.359  6576  6576 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 09:43:29.359  6576  6576 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 09:43:29.363  6609  6609 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
07-28 09:43:29.363  6609  6609 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
07-28 09:43:29.366  6576  6576 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 09:43:29.366  6576  6576 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 09:43:29.375  6576  6576 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-28 09:43:29.375   320  3982 V AudioPolicyService: registerClient() client 0xb1427060, uid 10118
07-28 09:43:29.375  6576  6576 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-28 09:43:29.375  6576  6576 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-28 09:43:29.395  6576  6576 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 09:43:29.395  6576  6576 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 09:43:29.395  6576  6576 I Adreno-EGL: Build Date: 12/12/14 금
07-28 09:43:29.395  6576  6576 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 09:43:29.395  6576  6576 I Adreno-EGL: Remote Branch: 
07-28 09:43:29.395  6576  6576 I Adreno-EGL: Local Patches: 
07-28 09:43:29.395  6576  6576 I Adreno-EGL: Reconstruct Branch: 
07-28 09:43:29.414  1036  2091 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6644 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-28 09:43:29.415  1036  2091 I ActivityManager: Killing 5831:com.google.android.talk/u0a72 (adj 15): empty #17
07-28 09:43:29.418  1036  1098 D BluetoothManagerService: Message: 20
07-28 09:43:29.418  1036  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f89647:true
07-28 09:43:29.458  1036  2005 W libprocessgroup: failed to open /acct/uid_10072/pid_5831/cgroup.procs: No such file or directory
07-28 09:43:29.498  6576  6641 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-28 09:43:29.500  6576  6576 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-28 09:43:29.515  6644  6644 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
07-28 09:43:29.517  6576  6576 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 09:43:29.521  6576  6576 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-28 09:43:29.523  6576  6576 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-28 09:43:29.526  6576  6576 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-28 09:43:29.526  6576  6576 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-28 09:43:29.537  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
07-28 09:43:29.537  6644  6644 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 09:43:29.538  6576  6576 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-28 09:43:29.545  6576  6576 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 09:43:29.545  6576  6576 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 09:43:29.562  1036  2115 I ActivityManager: Killing 5639:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-28 09:43:29.580  5617  5617 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-28 09:43:29.580  5617  5617 W System.err: android.os.DeadObjectException
07-28 09:43:29.580  5617  5617 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 09:43:29.580  5617  5617 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 09:43:29.580  5617  5617 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-28 09:43:29.580  5617  5617 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-28 09:43:29.580  5617  5617 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 09:43:29.580  5617  5617 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 09:43:29.580  5617  5617 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 09:43:29.580  5617  5617 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 09:43:29.580  5617  5617 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 09:43:29.580  5617  5617 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 09:43:29.580  5617  5617 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:43:29.580  5617  5617 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 09:43:29.580  5617  5617 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 09:43:29.580  5617  5617 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 09:43:29.581  5617  5617 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-28 09:43:29.581  5617  5617 W System.err: android.os.DeadObjectException
07-28 09:43:29.581  5617  5617 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 09:43:29.581  5617  5617 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 09:43:29.581  5617  5617 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-28 09:43:29.581  5617  5617 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-28 09:43:29.581  5617  5617 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 09:43:29.581  5617  5617 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 09:43:29.581  5617  5617 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 09:43:29.581  5617  5617 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 09:43:29.581  5617  5617 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 09:43:29.581  5617  5617 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 09:43:29.581  5617  5617 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:43:29.581  5617  5617 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 09:43:29.581  5617  5617 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 09:43:29.581  5617  5617 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 09:43:29.581  5617  5617 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-28 09:43:29.582  5617  5617 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-28 09:43:29.640  6576  6670 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:29.641  6576  6670 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 09:43:29.772  1036  1094 W ActivityManager: Activity pause timeout for ActivityRecord{3ee46329 u0 com.test.thalitest/.MainActivity t40}
07-28 09:43:29.774  1036  1577 W libprocessgroup: failed to open /acct/uid_1000/pid_5639/cgroup.procs: No such file or directory
07-28 09:43:29.775  1036  1577 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
07-28 09:43:29.779  5617  5617 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-28 09:43:29.780  5617  5617 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 09:43:29.794  6576  6679 D OpenGLRenderer: Render dirty regions requested: true
07-28 09:43:29.794  6576  6679 I OpenGLRenderer: Initialized EGL, version 1.4
07-28 09:43:29.808  6576  6679 D OpenGLRenderer: Enabling debug mode 0
07-28 09:43:29.813  1036  2040 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6680 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 09:43:29.815  5617  5617 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 09:43:29.829  6576  6576 D Atlas   : Validating map...
07-28 09:43:29.833  1036  2120 D SplitWindow: check instance of lgWin Window{33b4a31a u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 09:43:29.879  6680  6680 D UEI.SmartControl: Quickset Services start...
07-28 09:43:29.880  6680  6680 I UEI.SmartControl: Manufacture = LGE
07-28 09:43:29.880  6680  6680 D UEI.SmartControl: Id = LGNevo
07-28 09:43:29.883  6680  6680 D UEI.SmartControl: File observer start...
07-28 09:43:29.884  6680  6680 E UEI.SmartControl: IR Port is disabled: false
07-28 09:43:29.884  6680  6680 D UEI.SmartControl: Starting file observer...
07-28 09:43:29.884  6680  6680 D UEI.SmartControl: Extracting JNI libs...
07-28 09:43:29.884  6680  6680 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-28 09:43:29.925  1036  1099 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +705ms (total +785ms)
07-28 09:43:29.925  1036  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ee46329 u0 com.test.thalitest/.MainActivity t40} time:121078
07-28 09:43:29.929  6576  6576 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1ec7cd90 time:121081
07-28 09:43:29.975  6680  6680 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-28 09:43:29.975  6680  6680 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-28 09:43:29.975  6680  6680 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-28 09:43:30.023  6680  6680 I UEI.SmartControl: --- Selecting new region: 6
07-28 09:43:30.025  6576  6576 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-28 09:43:30.026  6680  6680 I UEI.SmartControl: Model = LG-D855
07-28 09:43:30.028  6680  6680 D UEI.SmartControl: QS Service created
07-28 09:43:30.061  6576  6576 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-28 09:43:30.061  6576  6576 I chromium: 
07-28 09:43:30.062  6680  6680 I UEI.SmartControl: Service initServices...
07-28 09:43:30.069  6680  6680 D UEI.SmartControl: QS start get config
07-28 09:43:30.091  6576  6670 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-28 09:43:30.091  6576  6670 I chromium: 
07-28 09:43:30.142  6680  6680 D UEI.SmartControl: Loading JNI Libs...
,07-28 09:43:30.206  6576  6703 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435044352
,07-28 09:43:30.219  6576  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 09:43:30.219  6576  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 09:43:30.219  6576  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 09:43:30.219  6576  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 09:43:30.219  6576  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-28 09:43:30.219  6576  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38261d54 added. We now have 1 listener(s)
,07-28 09:43:30.224  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 09:43:30.231  6576  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-28 09:43:30.234  6576  6703 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:43:30.237  6576  6703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:43:30.238  6576  6703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-28 09:43:30.253  6576  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29849443 added. We now have 1 listener(s)
,07-28 09:43:30.253  6576  6703 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:43:30.258  1036  1400 D WifiService: New client listening to asynchronous messages
07-28 09:43:30.261  6576  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 09:43:30.262  6576  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-28 09:43:30.262  6576  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-28 09:43:30.262  6576  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-28 09:43:30.265  6576  6703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:43:30.266  1036  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 09:43:30.267  6576  6703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-28 09:43:30.275  6576  6703 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 09:43:30.275  6576  6703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:43:30.275  6576  6703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:30.275  6576  6703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:30.275  6576  6703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:30.275  6576  6703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:43:30.275  6576  6703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:30.275  6576  6703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:43:30.275  6576  6703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:43:30.275  6576  6703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-28 09:43:30.275  6576  6703 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:43:30.277  6576  6703 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 09:43:30.278  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:30.280  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:30.319  6576  6576 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 09:43:30.581  6680  6680 I UEI.SmartControl: Supports setup maps: true
07-28 09:43:30.587  6680  6680 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 09:43:30.587  6680  6680 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 09:43:30.587  6680  6680 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 09:43:30.587  6680  6680 I UEI.SmartControl: ### init IR Blaster...
,07-28 09:43:30.594  6680  6680 D serial_port: Configuring serial port
07-28 09:43:30.600  6680  6680 E UEI.SmartControl: UEIBLaster setting for 616
07-28 09:43:30.600  6680  6680 I UEI.SmartControl: Setting serial record hearder size = 2
,07-28 09:43:30.601  6680  6680 I UEI.SmartControl: configuring settings for MAXQ616
07-28 09:43:30.603  6680  6680 I UEI.SmartControl: Get version...
07-28 09:43:30.619  6680  6707 D UEI.SmartControl: serial port data available: 21
,07-28 09:43:30.644   342   367 E GBMv2   : DFP En is all cleared set to be enabled
,07-28 09:43:30.645   342   367 E GBMv2   : Set value is all cleared set the max
07-28 09:43:30.645   342   367 I GBMv2   : DFP Enabled. Ignore VFP set
07-28 09:43:30.649  6680  6680 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 09:43:30.649  6680  6680 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 09:43:30.649  6680  6680 I UEI.SmartControl: QS saving settings...
07-28 09:43:30.650  6680  6680 D UEI.SmartControl: IR Blaster version: 25672567
07-28 09:43:30.667  6680  6707 D UEI.SmartControl: serial port data available: 4
,07-28 09:43:30.701  6680  6710 I UEI.SmartControl: Device manager: loading config....
07-28 09:43:30.702  6680  6710 D UEI.SmartControl: ----------- loading internal config...
,07-28 09:43:30.704  6680  6680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 09:43:30.709  6680  6680 E UEI.SmartControl: Services init done
07-28 09:43:30.709  6680  6680 D UEI.SmartControl: QS Service init finished
07-28 09:43:30.710  6680  6680 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 09:43:30.710  6680  6680 D UEI.SmartControl: QS Service version code: 201091
07-28 09:43:30.711  6680  6680 D UEI.SmartControl: Service requested: Control
07-28 09:43:30.718  6680  6710 E UEI.SmartControl: Loading SETTINGS...
,07-28 09:43:30.724  6680  6680 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 09:43:30.728  5617  5617 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 09:43:30.728  1036  2120 I ActivityManager: Killing 5617:com.lge.qremote/u0a112 (adj 15): empty #17
07-28 09:43:30.729  6680  6695 I UEI.SmartControl: ------ IControl API: 11
07-28 09:43:30.731  6680  6695 I UEI.SmartControl: Registering callback...
07-28 09:43:30.734  6680  6710 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-28 09:43:30.761  6680  6709 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-28 09:43:30.761  6680  6709 D UEI.SmartControl: -----service ready thread exits
07-28 09:43:30.840  6680  6680 D UEI.SmartControl: Internal service binding...
07-28 09:43:30.840  1036  2091 W libprocessgroup: failed to open /acct/uid_10112/pid_5617/cgroup.procs: No such file or directory
,07-28 09:43:31.063  6576  6706 W jxcore-log: Initializing JXcore engine
07-28 09:43:31.063  6576  6706 W jxcore-log: JXcore engine is ready
,07-28 09:43:31.131  6706  6706 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10360]" dev="sockfs" ino=10360 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-28 09:43:31.131  6706  6706 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-28 09:43:31.131  6706  6706 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9850]" dev="sockfs" ino=9850 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-28 09:43:31.131  6706  6706 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-28 09:43:31.131  6706  6706 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32269]" dev="sockfs" ino=32269 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-28 09:43:31.159  6576  6706 W jxcore-log: Starting JXcore engine
,07-28 09:43:31.300  6576  6706 W jxcore-log: Platform android
07-28 09:43:31.300  6576  6706 W jxcore-log: 
07-28 09:43:31.300  6576  6706 W jxcore-log: Process ARCH arm
07-28 09:43:31.300  6576  6706 W jxcore-log: 
,07-28 09:43:31.499  6576  6706 I jxcore-log: JXcore Cordova bridge is ready!
07-28 09:43:31.499  6576  6706 I jxcore-log: 
07-28 09:43:31.500  6576  6706 W jxcore-log: JXcore engine is started
,07-28 09:43:31.506  6576  6703 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-28 09:43:31.508  6576  6576 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-28 09:43:33.126  6512  6512 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-28 09:43:33.129  1036  1950 I ActivityManager: Killing 6209:com.android.calendar/u0a13 (adj 15): empty #17
,07-28 09:43:33.209  1036  1577 W libprocessgroup: failed to open /acct/uid_10013/pid_6209/cgroup.procs: No such file or directory
,07-28 09:43:34.137  6512  6570 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-28 09:43:35.698  6680  6708 D serial_port: close(fd = 25)
,07-28 09:43:35.703  6680  6711 D UEI.SmartControl: Internal timer expired: 1
,07-28 09:43:35.704  6680  6708 I UEI.SmartControl: Serial port is closed.
07-28 09:43:35.703  6680  6711 D UEI.SmartControl: unbind internal service
07-28 09:43:35.711  6680  6680 D UEI.SmartControl: Service.onUnbind: IControl
07-28 09:43:35.711  6680  6680 D UEI.SmartControl: Service.onDestroy
07-28 09:43:35.711  6680  6680 D UEI.SmartControl: Lock is in USE false
07-28 09:43:35.711  6680  6680 D UEI.SmartControl: unbind internal service
07-28 09:43:35.711  6680  6680 I UEI.SmartControl: Serial port is closed.
07-28 09:43:35.711  6680  6680 I UEI.SmartControl: Serial port is closed.
07-28 09:43:35.711  6680  6680 D UEI.SmartControl: Blaster closed
07-28 09:43:35.711  6680  6680 D UEI.SmartControl: Shut down QS...
07-28 09:43:35.711  6680  6680 D UEI.SmartControl: Stopping QS lib
07-28 09:43:35.712  6680  6680 D UEI.SmartControl: QS lib stop result = true
07-28 09:43:35.712  6680  6680 D UEI.SmartControl: Stopped QS lib
07-28 09:43:35.712  6680  6680 D UEI.SmartControl: Stopped file observer...
07-28 09:43:35.712  6680  6680 D UEI.SmartControl: QS shutdown complete
,07-28 09:43:36.749  1843  6422 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-28 09:43:36.753   316  6721 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-28 09:43:36.753   316  6721 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-28 09:43:36.753   316  6721 D libc-netbsd: res_queryN name = android.clients.google.com succeed
07-28 09:43:36.967  1843  1843 I ConfigFetchService: fetch service done; releasing wakelock
,07-28 09:43:36.972  1843  1843 I ConfigFetchService: stopping self
07-28 09:43:36.982  2268  2268 I ConfigService: onDestroy
,07-28 09:43:41.833  1036  1094 I ActivityManager: Waited long enough for: ServiceRecord{242ee176 u0 com.google.android.gms/.wearable.service.WearableService}
,07-28 09:43:42.032  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 09:43:42.032  6576  6706 I jxcore-log: 
,07-28 09:43:42.034  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 09:43:42.034  6576  6706 I jxcore-log: 
07-28 09:43:42.038  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:43:42.038  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.038  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.038  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:42.038  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:43:42.038  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.038  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:43:42.038  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:43:42.040  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.043  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 09:43:42.043  6576  6706 I jxcore-log: 
07-28 09:43:42.044  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 09:43:42.044  6576  6706 I jxcore-log: 
,07-28 09:43:42.390  6576  6706 D ExecuteNativeTests: Running unit tests
,07-28 09:43:42.471  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:43:42.471  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e added. We now have 2 listener(s)
07-28 09:43:42.471  1036  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:42.473  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:43:42.473  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:43:42.473  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:43:42.474  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:43:42.474  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f added. We now have 2 listener(s)
07-28 09:43:42.474  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:43:42.474  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 09:43:42.476  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:43:42.481  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:43:42.481  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.481  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.481  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:42.481  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:43:42.481  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.481  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:43:42.481  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:43:42.482  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.482  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:43:42.484  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:42.485  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:42.492  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 09:43:42.494  6576  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 09:43:42.494  6576  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-28 09:43:42.497  6576  6706 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-28 09:43:42.498  6576  6706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 09:43:42.498  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 09:43:42.498  6576  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 09:43:42.498  6576  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 09:43:42.498  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.499  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.499  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.499  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.499  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.499  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:43:42.500  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:43:42.500  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e removed from the list
07-28 09:43:42.500  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.500  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f removed from the list
07-28 09:43:42.500  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.500  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.501  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.501  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.503  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.503  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.503  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.503  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
,07-28 09:43:42.507  6576  6706 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-28 09:43:42.507  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.507  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.507  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.508  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.508  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.508  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.508  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.508  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.508  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.508  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.508  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.508  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.508  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.508  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.508  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.508  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.508  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.508  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.512  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 09:43:42.512  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveA,llOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 09:43:42.513  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.513  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 09:43:42.513  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.513  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.513  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.513  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.513  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.513  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.513  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.513  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.514  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.514  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.514  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.514  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.514  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.514  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.514  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.514  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.515  6576  6706 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 09:43:42.517  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:43:42.524  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:43:42.524  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.524  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.524  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:42.524  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:43:42.524  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.524  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:43:42.524  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:43:42.525  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.526  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:43:42.527  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:43:42.528  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No rele,vant state changes
07-28 09:43:42.528  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:43:42.528  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:43:42.528  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 09:43:42.529  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:42.534  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 09:43:42.535  1036  2095 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:42.539  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 09:43:42.543  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 09:43:42.546  6576  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 09:43:42.547  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:43:42.547  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:43:42.549  6576  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 09:43:42.549  6576  6706 I io.jxcore.node.ConnectionHelper: start: OK
07-28 09:43:42.552  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.552  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.552  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.553  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.553  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.553  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:43:42.553  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.553  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.553  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.553  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.553  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.553  6576  6706 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 09:43:42.555  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:43:42.559  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:43:42.559  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.559  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.559  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:42.559  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:43:42.559  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.559  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:43:42.559  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:43:42.561  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.561  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:43:42.562  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:43:42.562  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:43:42.562  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:43:42.562  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 09:43:42.563  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:42.566  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:42.570  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:43:42.571  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:43:42.572  6576  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 09:43:42.572  6576  6706 I io.jxcore.node.ConnectionHelper: start: OK
07-28 09:43:42.574  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.574  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.574  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.575  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.575  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.575  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:43:42.575  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.575  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.575  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.575  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.575  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.577  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:43:42.577  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.579  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.579  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.583  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.583  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.583  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.583  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.585  6576  6706 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 09:43:42.587  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:43:42.589  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:43:42.589  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.589  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.589  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:42.589  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:43:42.589  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.589  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:43:42.589  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:43:42.591  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.591  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:43:42.592  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:43:42.592  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:42.592  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:43:42.592  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:43:42.592  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 09:43:42.593  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:42.596  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:43:42.597  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:43:42.598  6576  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 09:43:42.598  6576  6706 I io.jxcore.node.ConnectionHelper: start: OK
,07-28 09:43:42.598  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.599  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.599  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.600  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.600  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.600  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.600  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.600  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.600  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:43:42.600  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.600  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.600  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.600  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.600  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:43:42.603  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.603  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.604  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.604  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.605  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.605  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.605  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 09:43:42.605  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.606  6576  6706 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-28 09:43:42.606  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.606  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.606  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.607  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.607  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.607  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.607  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.607  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.607  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.607  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.607  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.607  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.607  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.607  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.609  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.609  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.609  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.609  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.609  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.610  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.611  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 09:43:42.611  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.611  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.611  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.612  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.612  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: releas,e: The given listener does not exist in the list - probably already removed
07-28 09:43:42.612  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.612  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.612  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.612  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.612  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.612  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.612  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.612  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.612  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.616  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.616  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.617  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.617  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.617  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.618  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.618  6576  6706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 09:43:42.619  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.619  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.619  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.619  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.619  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.619  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.619  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.619  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.619  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.619  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.619  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.619  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.619  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.619  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.620  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.620  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.621  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.621  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.621  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.621  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.622  6576  6706 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 09:43:42.622  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.622  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.622  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.622  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.622  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.622  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.622  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.622  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.622  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.622  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.622  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.623  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.623  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.623  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.623  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.623  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.624  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.624  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.624  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.624  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.625  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 09:43:42.627  6576  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 09:43:42.627  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 09:43:42.627  6576  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 09:43:42.627  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 09:43:42.628  6576  6706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 09:43:42.628  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.628  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.628  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.629  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.629  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.629  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.629  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.629  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.629  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.629  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.629  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.629  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.630  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.630  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.633  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.633  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.634  6576  6706 D BluetoothLeScanner: could not find callback wrapper
,07-28 09:43:42.634  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.634  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.634  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.635  6576  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 09:43:42.635  6576  6706 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 09:43:42.636  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 09:43:42.639  6576  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 09:43:42.639  6576  6706 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 09:43:42.639  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 09:43:42.640  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 09:43:42.641  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 09:43:42.641  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 09:43:42.641  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 09:43:42.641  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 09:43:42.641  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 09:43:42.641  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 09:43:42.641  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 09:43:42.641  6576  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 09:43:42.641  6576  6706 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 09:43:42.641  6576  6706 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 09:43:42.641  6576  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 09:43:42.641  6576  6706 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 09:43:42.642  6576  6706 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 09:43:42.642  6576  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 09:43:42.642  6576  6706 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 09:43:42.642  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 09:43:42.644  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 09:43:42.645  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 09:43:42.645  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 09:43:42.646  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-28 09:43:42.646  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 09:43:42.646  6576  6706 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 09:43:42.647  6576  6706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 09:43:42.647  6576  6706 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 09:43:42.647  6576  6724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
07-28 09:43:42.648  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.648  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.648  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.648  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.648  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.648  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.648  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 09:43:42.649  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.649  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.649  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.649  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.649  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.649  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.649  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.649  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.650  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.650  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.651  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.651  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.651  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.651  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.658  6576  6706 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 09:43:42.658  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.658  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.658  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.662  6576  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
07-28 09:43:42.662  6576  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
07-28 09:43:42.663  6576  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
07-28 09:43:42.663  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.663  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.663  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.663  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.663  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.663  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.663  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.663  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.663  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.663  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.663  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.665  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.665  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.665  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.665  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.666  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.666  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.667  6576  6706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 09:43:42.668  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.668  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.668  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.669  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.669  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.669  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.669  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.669  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.669  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.669  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.669  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.669  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.669  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.669  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.671  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.671  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.671  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.671  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.672  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.672  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.673  6576  6706 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 09:43:42.673  6576  6706 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 09:43:42.673  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 09:43:42.677  6576  6706 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 09:43:42.677  6576  6706 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 09:43:42.677  6576  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 09:43:42.678  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 09:43:42.678  6576  6706 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 09:43:42.678  6576  6706 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 09:43:42.678  6576  6706 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 09:43:42.678  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 09:43:42.678  6576  6706 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 09:43:42.678  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.678  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.678  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.678  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.678  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.678  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.679  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.679  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.679  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.679  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.679  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.679  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.679  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.679  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.680  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:43:42.680  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.680  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.680  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.680  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.680  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.681  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.681  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.681  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.681  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.681  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.681  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.681  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.681  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.681  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.682  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.682  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.682  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.682  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.682  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.682  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.682  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.682  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.682  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.684  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.684  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.684  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.684  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.684  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.684  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.684  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.684  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.684  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.684  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.684  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.686  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.686  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.686  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.686  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.686  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.686  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.689  6576  6706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 09:43:42.689  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:43:42.698  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 09:43:42.700  6576  6706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 09:43:42.700  6576  6706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 09:43:42.701  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 09:43:42.701  1036  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:42.701  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 09:43:42.702  6576  6730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:43:42.703  3863  3881 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
07-28 09:43:42.703  6576  6730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
07-28 09:43:42.706  6576  6576 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 09:43:42.707  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.708  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 09:43:42.708  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 09:43:42.708  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 09:43:42.710  6576  6730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-28 09:43:42.711  6576  6730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 09:43:42.711  6576  6730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 09:43:42.712  6576  6576 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 09:43:42.715  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.715  6576  6706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-28 09:43:42.716  6576  6576 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-28 09:43:42.716  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.716  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.716  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 09:43:42.717  6576  6706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 09:43:42.717  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 09:43:42.721  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 09:43:42.721  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:43:42.721  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:43:42.722  6576  6706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 09:43:42.722  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.722  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:43:42.724  6576  6706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:43:42.725  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.725  6576  6576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:43:42.725  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.725  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.725  6576  6576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:43:42.725  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.725  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.725  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.725  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.725  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.725  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.725  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.725  6576  6576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:43:42.725  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.725  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.725  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.726  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.726  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.726  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.726  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.726  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.726  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.727  6576  6706 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 09:43:42.727  6576  6706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 09:43:42.727  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 09:43:42.729  6576  6706 V org.thaliprojec,t.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 09:43:42.729  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.729  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.729  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.729  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.729  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.729  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.729  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.729  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.729  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.729  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.729  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.729  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.729  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.729  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:43:42.730  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.730  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.730  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.730  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.732  1036  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:42.732  1036  1657 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:42.733  1036  2120 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:42.734  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.734  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.734  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:43:42.734  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 09:43:42.734  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.734  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.734  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.734  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.734  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.734  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.734  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.734  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:43:42.734  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.734  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.735  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.735  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.735  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.735  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.736  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:43:42.736  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:43:42.736  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 09:43:42.736  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:43:42.736  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.736  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.736  6576  6706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ecc223e not in the list
07-28 09:43:42.736  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:43:42.736  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.736  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:42.736  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:43:42.736  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.736  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:43:42.736  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:43:42.737  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:43:42.737  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:43:42.737  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 09:43:42.737  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94da89f not in the list
07-28 09:43:42.739  6576  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-28 09:43:42.739  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 09:43:42.739  6576  6706 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 09:43:42.739  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 09:43:42.739  6576  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 09:43:42.739  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 09:43:42.744  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 09:43:42.744  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-28 09:43:42.745  6576  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-28 09:43:42.745  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 09:43:42.745  6576  6706 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 09:43:42.745  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 09:43:42.745  6576  6706 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 09:43:42.745  6576  6706 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-28 09:43:42.746  6576  6706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 09:43:42.746  6576  6706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-28 09:43:42.746  6576  6706 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-28 09:43:42.746  6576  6706 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 09:43:42.747  6576  6706 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 09:43:42.747  6576  6706 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-28 09:43:42.758  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:43:42.758  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31738e84 added. We now have 2 listener(s)
07-28 09:43:42.758  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:43:42.761  6576  6706 D BluetoothAdapter: enable(): BT is already enabled..!
,07-28 09:43:42.762  1036  1052 D WifiServiceImplEx: setWifiEnabled: true pid=6576, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 09:43:42.763  1036  1052 D WifiService: setWifiEnabled: true pid=6576, uid=10118
07-28 09:43:42.763  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 09:43:42.764  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:43:42.764  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b8166d added. We now have 3 listener(s)
07-28 09:43:42.764  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:43:42.767  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:43:42.767  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1784f2a2 added. We now have 4 listener(s)
,07-28 09:43:42.767  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:43:42.769  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:43:42.769  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10d4db33 added. We now have 5 listener(s)
07-28 09:43:42.769  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:43:42.775  1036  2040 D WifiServiceImplEx: setWifiEnabled: false pid=6576, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-28 09:43:42.775  1036  2040 D WifiService: setWifiEnabled: false pid=6576, uid=10118
07-28 09:43:42.775  1036  2040 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 09:43:42.778  6576  6724 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
07-28 09:43:42.779  6576  6724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
07-28 09:43:42.784  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 09:43:42.784  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 09:43:42.784  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 09:43:42.785  1036  1394 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:42.785  1036  2120 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:42.785  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:42.785  1036  2120 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1e1bd659 mBinding = false
07-28 09:43:42.785  1036  1394 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:42.786  1036  1394 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:42.786  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:42.786  1036  1394 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 09:43:42.786  1036  1394 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 09:43:42.786  1036  1394 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 09:43:42.787  1036  1394 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,07-28 09:43:42.787  1036  1394 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 09:43:42.790  1036  1394 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 09:43:42.790  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.790  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.791  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 09:43:42.791  2729  2729 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 09:43:42.792  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 09:43:42.792  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 09:43:42.792  1036  1394 D WifiNative-wlan0: SET ps 1: returned true
07-28 09:43:42.792  1036  2861 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.792   316   896 D CommandListener: Clearing all IP addresses on wlan0
07-28 09:43:42.799  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 09:43:42.799  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 09:43:42.799  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-28 09:43:42.802  1036  1098 D BluetoothManagerService: Message: 2
07-28 09:43:42.804  1036  1098 D BluetoothManagerService: Sending off request.
07-28 09:43:42.804  3863  3881 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 09:43:42.805  3863  3944 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 09:43:42.805  3863  3944 D BluetoothAdapterProperties: Setting state to 13
07-28 09:43:42.805  3863  3944 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 09:43:42.806  3863  3944 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 09:43:42.806  3863  3944 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 09:43:42.807  3863  3948 D BluetoothAdapterProperties: Scan Mode:20
07-28 09:43:42.808  3863  3944 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 09:43:42.809  3863  4214 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 09:43:42.809  3863  4214 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:42.809  3863  4214 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 09:43:42.809  3863  4214 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 09:43:42.809  3863  4214 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 09:43:42.809  3863  4214 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 09:43:42.809  3863  4214 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 09:43:42.809  3863  4214 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-28 09:43:42.838  1036  1407 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 09:43:42.838  1036  1407 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,07-28 09:43:42.848  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:42.848  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:42.848  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.848  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.848  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:42.848  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:42.848  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.848  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:43:42.848  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:43:42.850  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:42.850  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:43:42.853  1036  1094 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6735 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-28 09:43:42.854  1036  1394 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:42.854  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:42.855  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:42.855  1036  1394 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:42.855  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:42.855  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:42.856  1036  1394 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 09:43:42.856  1036  1394 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:42.856  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:42.857  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:42.867  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:43:42.869  1036  1392 D LGWifiP2pService: InactiveState{ when=-16ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.869  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:42.869  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.869  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:43:42.869  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.869  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.869  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:42.869  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:42.869  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:42.869  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:42.869  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:43:42.869  1036  1392 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@24e4e203
07-28 09:43:42.870  1036  1392 D LGWifiP2pService: P2pDisablingState
07-28 09:43:42.870  1036  1392 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.870  1036  1392 D LGWifiP2pService: p2p socket connection lost
07-28 09:43:42.870  1036  1392 D LGWifiP2pService: P2pDisabledState
07-28 09:43:42.872  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:42.872  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:42.872  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:43:42.879  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:42.879  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:42.880  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:42.881  1036  1098 D BluetoothManagerService: Message: 60
07-28 09:43:42.881  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 09:43:42.881  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-28 09:43:42.882  1978  1978 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-28 09:43:42.886  1036  1407 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-28 09:43:42.886  1036  1407 D DSQN    : disableDataServiceNotify
07-28 09:43:42.886  1036  1407 D DSQN    : stop dsqn bin
,07-28 09:43:42.894  1036  1407 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-28 09:43:42.894  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:42.894  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:43:42.894  1036  1407 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:43:42.894  1036  1407 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-28 09:43:42.895  1036  1407 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-28 09:43:42.895  1036  1407 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-28 09:43:42.895  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 09:43:42.896  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.896  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.896  1036  2860 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 09:43:42.897  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 09:43:42.901  1036  1407 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:42.901  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 09:43:42.901  1036  1407 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:42.901  1036  1407 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:42.901  1036  1407 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:42.901  1036  1407 D NetworkManagementService: Removing idletimer
07-28 09:43:42.902  1036  1407 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:42.903  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:42.903  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:42.904  1879  1879 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:42.905  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Cap,abilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 09:43:42.906  1036  1391 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 09:43:42.906  1036  1391 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,07-28 09:43:42.906  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 09:43:42.906  1978  1978 D WfdsService: WifiP2pState is changed : false
07-28 09:43:42.908  1036  1394 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-28 09:43:42.908  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 09:43:42.908  2729  2729 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 09:43:42.908  1036  1392 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.908  1036  1392 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.909  1978  2356 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 09:43:42.909  1978  2356 D WfdsService: Set the WFDS Monitor: false
07-28 09:43:42.910  1978  2356 D WfdsMonitor: WFDS Monitor is stopped
07-28 09:43:42.910  1978  2356 D WfdsService: STATE : WfdsDisabledState - enter
07-28 09:43:42.910  1978  2768 D CtrlSupplicant: Received on exit socket, terminate
07-28 09:43:42.910  1978  2768 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 09:43:42.910  1978  2768 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 09:43:42.910  1978  2768 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 09:43:42.911  1978  2358 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 09:43:42.911  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:42.913  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:42.913  1978  2356 W WfdsService: DefaultState - msg [9445378] is not handled
07-28 09:43:42.914  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:42.915  3863  3863 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:42.916  3863  3863 D BluetoothMapService: STATE_TURNING_OFF
07-28 09:43:42.916  3863  3863 V BluetoothMapService: Handler(): got msg=4
07-28 09:43:42.916  3863  3863 D BluetoothMapService: MAP Service closeService in
07-28 09:43:42.916  3863  3863 D BluetoothMapMasInstance: MAP Service shutdown
07-28 09:43:42.916  3863  3863 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 09:43:42.916  3863  3863 V BluetoothMapService: MAP Service closeService out
07-28 09:43:42.916  3863  3863 V BtOppService: Receiver DISABLED_ACTION 
07-28 09:43:42.917  3863  3863 I BtOppRfcommListener: stopping Accept Thread
07-28 09:43:42.917  3863  3863 V BtOppRfcommListener: close mBtServerSocket
07-28 09:43:42.917  3863  3863 V BtOppRfcommListener: waiting for thread to terminate
07-28 09:43:42.918  3863  4258 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:42.918  3863  4258 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 09:43:42.919  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 09:43:42.919  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 09:43:42.919  3863  3863 V BtOppRfcommListener: done waiting for thread to terminate
07-28 09:43:42.920  1036  1394 D WifiNative-wlan0: SET ps 1: returned true
07-28 09:43:42.920   316   896 D CommandListener: Clearing all IP addresses on wlan0
,07-28 09:43:42.922  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:42.957  1036  1094 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6761 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 09:43:42.959  1036  1394 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 09:43:42.960  1036  1394 D WifiNative-p2p0: TERMINATE: returned true
07-28 09:43:42.960  1036  1394 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 09:43:42.960  1036  1394 E WifiStateMachine: useWiFiOffloading() : false
07-28 09:43:42.960  1036  1394 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 09:43:42.960  3863  3863 V BtOppService: onDestroy
,07-28 09:43:42.961  1036  1052 I art     : Explicit concurrent mark sweep GC freed 24730(1274KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.274ms total 145.122ms
,07-28 09:43:42.962  1036  1381 V AlarmManager: RTC_WAKEUP set : Alarm{f8eb22a type 0 when 1469691822362 com.android.vending} when 1469691822362
07-28 09:43:42.965  3863  4267 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:42.965  3863  4215 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:42.965  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 09:43:42.965  3863  4058 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 09:43:42.965  3863  3944 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 09:43:42.966  3863  4268 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 09:43:42.967  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 09:43:42.967  3863  4058 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 09:43:42.973  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:42.973  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:42.973  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.973  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.973  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:42.973  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:42.973  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:42.973  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:42.973  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:43:42.975  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-28 09:43:42.975  1036  1407 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-28 09:43:42.976  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:42.976  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:42.976  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 09:43:42.976  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-28 09:43:42.976  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global,, returning read-only value.
07-28 09:43:42.976  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:42.977  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 09:43:42.977  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 09:43:42.977  1036  1036 D RttService: SCAN_AVAILABLE : 1
07-28 09:43:42.977  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 09:43:42.977  1036  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.978  1036  1559 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:42.979  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 09:43:42.979  1036  1394 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:42.979  1036  1036 D WifiHS20: hidePasspointNotification off =false
,07-28 09:43:42.979  1036  1394 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:43:42.979  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 09:43:42.979  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:42.979  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 09:43:42.979  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 09:43:42.979  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 09:43:42.979  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 09:43:42.980  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 09:43:42.980  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 09:43:42.980  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 09:43:42.981  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 09:43:42.981  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:42.981  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:42.985  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:42.986  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:42.986  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.986  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.986  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:42.986  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:42.986  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:42.986  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:42.986  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:42.986  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:42.986  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:42.988  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:42.988  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:42.988  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:42.988  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:42.988  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:42.988  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:42.988  6576  6576 ,V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:42.988  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:42.988  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:42.989  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:42.989  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 09:43:42.989  3863  3863 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-28 09:43:42.990  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:43:42.990  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,07-28 09:43:43.011  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-28 09:43:43.012  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:43.012  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:43.014  1036  2040 V SIM_STK : Menu title from STK is T-Mobile
07-28 09:43:43.022  6761  6761 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 09:43:43.022  6761  6761 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,07-28 09:43:43.022  6761  6761 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 09:43:43.022  6761  6761 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-28 09:43:43.023  6761  6761 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 09:43:43.024  6761  6761 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-28 09:43:43.032  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 09:43:43.033  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:43.033  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:43.033  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-28 09:43:43.049  6735  6735 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-28 09:43:43.049  6735  6735 W LG Account v2.2: No ProfileInfo entries
07-28 09:43:43.049  6735  6735 I LG Account v2.2: isEnabled: false
07-28 09:43:43.049  6735  6735 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-28 09:43:43.049  6735  6735 I Feature : [Lifetracker]Country: EU
07-28 09:43:43.049  6735  6735 I Feature : [Lifetracker]Operator: OPEN
07-28 09:43:43.049  6735  6735 I Feature : [Lifetracker]Ranking support: false
07-28 09:43:43.049  6735  6735 I Feature : [Lifetracker]Comfort support: false
07-28 09:43:43.049  6735  6735 I Feature : [Lifetracker]Accessory: true
07-28 09:43:43.049  6735  6735 I Feature : [Lifetracker]Health device: true
07-28 09:43:43.050  6735  6735 I Feature : [Lifetracker]Extra Pedometer: false
07-28 09:43:43.050  6735  6735 I Feature : [Lifetracker]Blood glucose device: false
07-28 09:43:43.050  6735  6735 I Feature : [Lifetracker]Device Number: 3
,07-28 09:43:43.055  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 09:43:43.056  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:43.056  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:43.058  1036  2861 D DhcpStateMachine: StoppedState
07-28 09:43:43.058  1036  2861 D DhcpStateMachine: StoppedState{ when=-138ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:43.058  1036  1394 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-28 09:43:43.058  1036  1394 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-28 09:43:43.063  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:43:43.068  2729  2729 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 09:43:43.068  2729  2729 I wpa_supplicant: monitor socket send errors count : 1
07-28 09:43:43.068  2729  2729 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1978-2\x00 that cannot receive messages
07-28 09:43:43.069  1036  2767 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-28 09:43:43.069  1036  2767 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 09:43:43.073  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:43.103  1036  2091 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6781 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 09:43:43.104  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-28 09:43:43.105  2729  2729 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 09:43:43.106  2729  2729 W wpa_supplicant: USIM:  scard_deinit function
07-28 09:43:43.106  1036  2767 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 09:43:43.106  1036  2767 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 09:43:43.107  1036  2767 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 09:43:43.107  1036  2767 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-28 09:43:43.107  1036  1098 D Tethering: InitialState.processMessage what=4
07-28 09:43:43.107  1036  2767 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:43:43.107  1036  2767 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:43:43.107  1036  1394 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=134248
07-28 09:43:43.108  1036  1394 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=134248
07-28 09:43:43.108  1036  1394 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=134248  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 09:43:43.108  1036  1394 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=134249  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 09:43:43.109  3863  3863 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 09:43:43.109  3863  3863 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:43.109  1036  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 09:43:43.109  3863  3863 V BluetoothPbapReceiver: ***********state = 13
07-28 09:43:43.109  1036  1394 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:43.110  1036  1394 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:43.110  3863  3863 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-28 09:43:43.111  3863  3863 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:43.111  3863  3863 V BluetoothPbapService: state: 13
07-28 09:43:43.111  3863  3863 V BluetoothPbapService: Pbap Service closeService in
07-28 09:43:43.112  3863  3863 V BluetoothPbapService: successfully stopped pbap service
07-28 09:43:43.112  3863  3863 V BluetoothPbapService: Pbap Service closeService out
07-28 09:43:43.113  2268  2268 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 09:43:43.113  1036  1098 D BluetoothManagerService: Message: 20
07-28 09:43:43.113  1036  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3040f791:true
07-28 09:43:43.113  3863  3863 V BluetoothPbapService: Pbap Service onDestroy
07-28 09:43:43.113  3863  3863 V BluetoothPbapService: Pbap Service closeService in
07-28 09:43:43.113  3863  3863 V BluetoothPbapService: Pbap Service closeService out
07-28 09:43:43.113  3863  3863 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-28 09:43:43.116   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 292us total 15.462ms
,07-28 09:43:43.125  1036  1098 D BluetoothManagerService: Message: 30
07-28 09:43:43.128  1036  1098 D BluetoothManagerService: Message: 30
,07-28 09:43:43.129   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 272us total 13.011ms
07-28 09:43:43.134  6761  6761 D LocalBluetoothProfileManager: Adding local MAP profile
07-28 09:43:43.135  6761  6761 D BluetoothMap: Create BluetoothMap proxy object
07-28 09:43:43.136  1036  1098 D BluetoothManagerService: Message: 30
07-28 09:43:43.138  1036  1098 D BluetoothManagerService: Message: 30
07-28 09:43:43.140  6761  6761 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-28 09:43:43.140  6761  6761 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-28 09:43:43.141   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 11.697ms
,07-28 09:43:43.149  6761  6761 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
07-28 09:43:43.150  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-28 09:43:43.155  6761  6761 D DockEventReceiver: finishStartingService: stopping service
,07-28 09:43:43.160  6781  6781 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 09:43:43.161  6761  6761 D BluetoothInputDevice: Proxy object connected
07-28 09:43:43.161  6761  6761 D HidProfile: Bluetooth service connected
07-28 09:43:43.162  6761  6761 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 09:43:43.162  6761  6761 D PanProfile: Bluetooth service connected
07-28 09:43:43.162  6761  6761 D BluetoothMap: Proxy object connected
07-28 09:43:43.163  6761  6761 D MapProfile: Bluetooth service connected
07-28 09:43:43.163  6761  6761 D BluetoothMap: getConnectedDevices()
07-28 09:43:43.163  6761  6761 D BluetoothMap: Bluetooth is Not enabled
07-28 09:43:43.163  6781  6781 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 09:43:43.164  6761  6761 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 09:43:43.164  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:43.165  6761  6761 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 09:43:43.165  1036  1051 I ActivityManager: Killing 6174:com.android.providers.calendar/u0a14 (adj 15): empty #17
,07-28 09:43:43.180  6037  6037 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,07-28 09:43:43.188  2729  2729 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 09:43:43.188  1036  2767 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,07-28 09:43:43.188  1036  2767 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-28 09:43:43.188  1036  2767 D WifiMonitor: Disconnecting from the supplicant, no more events
07-28 09:43:43.188  1036  1394 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
07-28 09:43:43.199  1036  1996 W libprocessgroup: failed to open /acct/uid_10014/pid_6174/cgroup.procs: No such file or directory
,07-28 09:43:43.204  1036  1051 I ActivityManager: Killing 2206:com.lge.music/u0a34 (adj 15): empty #17
,07-28 09:43:43.212  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:43.219   320   320 V AudioFlinger: 2206 died, releasing its sessions
07-28 09:43:43.219   320   320 V AudioFlinger:  pid 1879 @ 0
07-28 09:43:43.219   320   320 V AudioFlinger:  pid 3426 @ 1
,07-28 09:43:43.219   320   320 V AudioFlinger:  pid 3426 @ 2
07-28 09:43:43.255  6761  6761 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:43.255  6761  6761 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:43:43.265  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 09:43:43.266  6761  6761 D BluetoothPermissionRequest: onReceive
07-28 09:43:43.268  6761  6761 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-28 09:43:43.279  1036  1950 W libprocessgroup: failed to open /acct/uid_10034/pid_2206/cgroup.procs: No such file or directory
,07-28 09:43:43.291  1978  1978 D WfdsService: Supplicant Connection state is changed : false
07-28 09:43:43.291  1978  2356 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-28 09:43:43.291  1978  2356 D WfdsService: Set the WFDS Monitor: false
07-28 09:43:43.291  1978  2356 D WfdsMonitor: WFDS Monitor is stopped
,07-28 09:43:43.295  1036  1394 D WifiOffDelayIfNotUsed: stopMonitoring
07-28 09:43:43.296  1036  1394 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 09:43:43.296  1036  1394 E WifiStateMachine: useWiFiOffloading() : false
07-28 09:43:43.296  1036  1394 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-28 09:43:43.299  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 09:43:43.299  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:43.301  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 09:43:43.302  1036  1398 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 09:43:43.302  2511  2511 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:43.302  1036  1398 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 09:43:43.302  6761  6761 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 09:43:43.305  1036  1051 I ActivityManager: Killing 6427:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-28 09:43:43.306  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:43.310  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:43.363  3863  3863 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF,
07-28 09:43:43.364  3863  3863 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-28 09:43:43.364  1036  1950 W libprocessgroup: failed to open /acct/uid_10008/pid_6427/cgroup.procs: No such file or directory
07-28 09:43:43.365  3863  3863 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,07-28 09:43:43.452  1036  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6811 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-28 09:43:43.453  3863  3863 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:43.453  3863  3863 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,07-28 09:43:43.459  3863  3863 V BluetoothFtpService: Ftp Service onStartCommand
07-28 09:43:43.459  3863  3863 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:43.459  3863  3863 V BluetoothFtpService: Ftp Service closeService
07-28 09:43:43.460  3863  3863 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-28 09:43:43.460  3863  3863 V BluetoothFtpService: successfully stopped ftp service
07-28 09:43:43.461  3863  3863 V BluetoothFtpService: Ftp Service onDestroy
07-28 09:43:43.461  3863  3863 V BluetoothFtpService: Ftp Service closeService
07-28 09:43:43.464  3863  3863 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 09:43:43.464  3863  3863 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 09:43:43.464  3863  3863 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 09:43:43.464  3863  3863 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:43.464  3863  3863 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 09:43:43.464  3863  3863 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 09:43:43.465  3863  3863 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:43.465  3863  3863 V BluetoothSapService: state: 13
07-28 09:43:43.465  3863  3863 V BluetoothSapService: Stopping SAP server process
07-28 09:43:43.467  3863  3863 V BluetoothSapService: Sap Service closeSapService in
07-28 09:43:43.467  3863  3863 V BluetoothSapService: Close listen Socket : 
07-28 09:43:43.467  3863  3863 V BluetoothSapService: Close rfcomm Socket : 
07-28 09:43:43.467  3863  3863 V BluetoothSapService: Close sapd  Socket : 
07-28 09:43:43.523  1036  1051 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6828 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 09:43:43.529  3863  3863 V BluetoothSapService: Sap Service closeSapService out
07-28 09:43:43.529  3863  3863 V BluetoothSapService: Sap Service onDestroy
07-28 09:43:43.529  3863  3863 V BluetoothSapService: Sap Service closeSapService in
07-28 09:43:43.529  3863  3863 V BluetoothSapService: Close listen Socket : 
07-28 09:43:43.529  3863  3863 V BluetoothSapService: Close rfcomm Socket : 
07-28 09:43:43.529  3863  3863 V BluetoothSapService: Close sapd  Socket : 
07-28 09:43:43.530  3863  3863 V BluetoothSapService: Sap Service closeSapService out
07-28 09:43:43.548  6811  6811 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 09:43:43.578  6811  6811 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-28 09:43:43.603  6828  6828 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 09:43:43.621  6811  6811 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,07-28 09:43:43.621  6811  6811 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-28 09:43:43.621  1036  2041 I ActivityManager: Killing 5964:com.lge.appbox.client/u0a11 (adj 15): empty #17
07-28 09:43:43.622  6811  6811 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-28 09:43:43.625  6811  6811 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,07-28 09:43:43.626  6811  6811 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-28 09:43:43.629  6811  6811 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-28 09:43:43.638  6811  6811 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,07-28 09:43:43.653  1036  2120 W libprocessgroup: failed to open /acct/uid_10011/pid_5964/cgroup.procs: No such file or directory
,07-28 09:43:43.661  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 09:43:43.666  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:43.686  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 09:43:43.688  6811  6811 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-28 09:43:43.688  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:43:43.692  6811  6811 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-28 09:43:43.693  6781  6781 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 09:43:43.693  6781  6781 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 09:43:43.693  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:43.699  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:43.706  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:43.711  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:43.712  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 09:43:43.713  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 09:43:43.717  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:43:43.721  6781  6781 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 09:43:43.721  6781  6781 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 09:43:43.722  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:43.725  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:43.732  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 09:43:43.739  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:43.739  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:43.741  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 09:43:43.792  1036  1765 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6848 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-28 09:43:43.903  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 09:43:43.908  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 09:43:43.925  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 09:43:43.942  6848  6870 W FormManager: Network not available. Please check & try again.
,07-28 09:43:43.946  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 09:43:43.946  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 09:43:43.947  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 09:43:43.947  6761  6761 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 09:43:43.948  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 09:43:43.965  6761  6761 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 09:43:43.966  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 09:43:43.966  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 09:43:43.966  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 09:43:43.966  6761  6761 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 09:43:43.966  6761  6761 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-28 09:43:43.970  3863  4058 W bt-btif : ag scb idx 1 not allocated
07-28 09:43:43.970  3863  3948 D bt_hci_bdroid: cleanup
07-28 09:43:43.970  3863  4058 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:43:43.970  3863  4060 I bt_lpm  : LPM is already off!!!
07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,07-28 09:43:43.970  3863  4058 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 09:43:43.971  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 09:43:43.971  3863  4185 I bt_userial_mct: exiting userial_read_thread
07-28 09:43:43.971  3863  4058 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:43:43.971  3863  4185 D bt_userial_mct: Leaving userial_evt_read_thread()
07-28 09:43:43.971  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:43.971  3863  4058 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:43:43.971  3863  4058 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 09:43:43.971  3863  4058 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 09:43:43.971  3863  4058 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 09:43:43.971  3863  3948 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-28 09:43:43.971  3863  4060 I bt_vendor: hw_epilog_process
07-28 09:43:43.971  3863  3948 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 09:43:43.971  3863  3948 D bt_userial_mct: userial_close
07-28 09:43:43.971  3863  3948 E bt_userial_mct: pthread_join() FAILED result:3
07-28 09:43:43.971  3863  3948 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-28 09:43:43.974  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 09:43:43.974  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 09:43:43.977  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:43.980  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:43.987  4298  6875 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 09:43:43.991  6848  6871 V FormManager: Network unavailable.
07-28 09:43:43.992  4298  6876 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 09:43:43.992  4298  6876 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 09:43:43.994  6781  6781 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 09:43:43.995  6781  6781 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 09:43:43.995  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:43.999  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-28 09:43:44.002  6848  6871 V FormManager: Network unavailable.
07-28 09:43:44.008  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:44.023  3863  3948 D bt_hci_bdroid: set_power 0
07-28 09:43:44.023  3863  3948 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-28 09:43:44.023  3863  3948 I bt_vendor: bluetooth satus is on
07-28 09:43:44.023  3863  3948 I bt_vendor: bt-vendor : resetting BT status
07-28 09:43:44.024  3863  3948 I bt_vendor: Starting hciattach daemon
07-28 09:43:44.024  3863  3948 I bt_vendor: try to set false
07-28 09:43:44.024  6848  6877 W FormManager: Network not available. Please check & try again.
07-28 09:43:44.024  3863  3948 I bt_vendor: Starting hciattach daemon
07-28 09:43:44.024  3863  3948 I bt_vendor: try to set false
07-28 09:43:44.024  3863  3948 I bt_vendor: cleanup
,07-28 09:43:44.025  3863  4058 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 09:43:44.025  3863  3948 I GKI_LINUX: GKI_exit_task 0 done
07-28 09:43:44.025  3863  3948 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 09:43:44.025  6811  6811 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 09:43:44.026  3863  3944 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 09:43:44.027  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 09:43:44.028  6811  6811 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-28 09:43:44.029  3863  3863 D HeadsetService: Received stop request...Stopping profile...
07-28 09:43:44.031  3863  3863 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 09:43:44.031  3863  3863 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-28 09:43:44.031  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c647692
07-28 09:43:44.031  3863  3976 D HeadsetStateMachine: Exit Disconnected: -1
07-28 09:43:44.032  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 09:43:44.033  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 09:43:44.033  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 09:43:44.033  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-28 09:43:44.033  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 09:43:44.033  3863  3863 D A2dpService: Received stop request...Stopping profile...
07-28 09:43:44.035  3863  4031 D A2dpStateMachine: Exit Disconnected: -1
07-28 09:43:44.037  3863  3863 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-28 09:43:44.042  3863  3863 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-28 09:43:44.042  3863  3863 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 09:43:44.042  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c647692
07-28 09:43:44.043  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-28 09:43:44.043  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 09:43:44.044  3863  3944 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 09:43:44.044  3863  3863 D HidService: Received stop request...Stopping profile...
07-28 09:43:44.044  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c647692
07-28 09:43:44.046  6848  6878 V FormManager: Network unavailable.
07-28 09:43:44.046  3863  3863 D HeadsetStateMachine: Unbinding service...
07-28 09:43:44.046  6761  6761 D BluetoothInputDevice: Proxy object disconnected
07-28 09:43:44.046  6761  6761 D HidProfile: Bluetooth service disconnected
07-28 09:43:44.046  3863  3863 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 09:43:44.047  3863  3863 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 09:43:44.047  3863  3863 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 09:43:44.047  3863  3863 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 09:43:44.047  3863  3863 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-28 09:43:44.047  3863  3863 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 09:43:44.047  3863  3863 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 09:43:44.047  3863  3863 D HealthService: Received stop request...Stopping profile...
07-28 09:43:44.048  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c647692
07-28 09:43:44.049  3863  3863 D PanService: Received stop request...Stopping profile...
07-28 09:43:44.050  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c647692
07-28 09:43:44.052  3863  3863 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 09:43:44.053  3863  3863 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 09:43:44.053  3863  3863 D BtGatt.GattService: stop()
07-28 09:43:44.053  6761  6761 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 09:43:44.053  6761  6761 D PanProfile: Bluetooth service disconnected
07-28 09:43:44.053  3863  3863 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 09:43:44.054  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c647692
07-28 09:43:44.055  3863  3863 I BluetoothA2dpServiceJni: cleanupNative
07-28 09:43:44.055  3863  4036 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 09:43:44.055  3863  3863 I GKI_LINUX: GKI_exit_task 2 done
,07-28 09:43:44.055  3863  3863 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 09:43:44.056  3863  3863 D BluetoothMapService: Received stop request...Stopping profile...
07-28 09:43:44.056  3863  3863 D BluetoothMapService: stop()
07-28 09:43:44.057  3863  3863 D BluetoothMapEmailAppObserver: deinitObservers()
07-28 09:43:44.057  3863  3863 D BluetoothMapEmailAppObserver: removeReceiver()
07-28 09:43:44.057  3863  3863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c647692
07-28 09:43:44.059  3863  3863 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 09:43:44.059  3863  3863 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 09:43:44.059  3863  3863 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 09:43:44.059  3863  3863 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 09:43:44.059  3863  3863 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 09:43:44.060  3863  3863 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 09:43:44.060  3863  3863 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 09:43:44.061  6761  6761 D BluetoothMap: Proxy object disconnected
07-28 09:43:44.061  6761  6761 D MapProfile: Bluetooth service disconnected
07-28 09:43:44.061  3863  3863 V BluetoothMapService: Handler(): got msg=4
07-28 09:43:44.061  3863  3863 D BluetoothMapService: MAP Service closeService in
07-28 09:43:44.061  3863  3863 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 09:43:44.061  3863  3863 V BluetoothMapService: MAP Service closeService out
07-28 09:43:44.061  3863  3944 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 09:43:44.062  3863  3944 D BluetoothAdapterProperties: Setting state to 10
07-28 09:43:44.062  3863  3944 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 09:43:44.062  6848  6878 V FormManager: Network unavailable.
07-28 09:43:44.062  3863  3863 D BluetoothMapService: cleanup()
07-28 09:43:44.062  3863  3863 D BluetoothMapService: MAP Service closeService in
07-28 09:43:44.062  3863  3863 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 09:43:44.062  3863  3863 V BluetoothMapService: MAP Service closeService out
07-28 09:43:44.062  1036  1098 D BluetoothManagerService: Message: 60
07-28 09:43:44.062  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 09:43:44.062  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-28 09:43:44.063  3863  3944 I BluetoothAdapterState: Entering OffState
07-28 09:43:44.063  6761  6777 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 09:43:44.064  1879  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:43:44.065  1879  3980 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:43:44.065  6761  6776 D BluetoothMap: onBluetoothStateChange: up=false
07-28 09:43:44.066  6761  6777 D BluetoothPan: onBluetoothStateChange on: false
,07-28 09:43:44.068  1036  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:43:44.068  6761  6776 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 09:43:44.069  1879  2372 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:43:44.071  1036  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 09:43:44.072  1036  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 09:43:44.072  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 09:43:44.074  1036  2040 I ActivityManager: Killing 5988:com.android.contacts/u0a19 (adj 15): empty #17
07-28 09:43:44.078  1036  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 09:43:44.078  1036  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-28 09:43:44.078  1036  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1e1bd659 mBinding = false
07-28 09:43:44.078  1036  1098 D BluetoothManagerService: Sending unbind request.
07-28 09:43:44.083  6811  6811 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:44.084  6811  6811 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:43:44.091  6811  6811 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-28 09:43:44.093  6811  6811 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-28 09:43:44.093  6811  6811 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-28 09:43:44.094  6811  6811 V SoundPool: doLoad: loading sample sampleID=1
07-28 09:43:44.094  6811  6811 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 09:43:44.095  6811  6887 V SoundPool: Start decode
07-28 09:43:44.095  6811  6887 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-28 09:43:44.096   320  3982 V MediaPlayerService: decode(23, 10857164, 17813)
07-28 09:43:44.096   320  3982 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-28 09:43:44.096   320  3982 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-28 09:43:44.096   320  3982 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-28 09:43:44.096   320  3982 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-28 09:43:44.096   320  3982 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-28 09:43:44.096   320  3982 V MediaPlayerService: player type = 3
07-28 09:43:44.096   320  3982 V AwesomePlayer: AwesomePlayer create()
07-28 09:43:44.096   320  3982 V AwesomePlayer: reset_l() 
07-28 09:43:44.096   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:43:44.096   320  3982 V AwesomePlayer: setAudioSink() 
07-28 09:43:44.096   320  3982 V AwesomePlayer: reset_l() 
07-28 09:43:44.096   320  3982 V AudioCache: notify(0xb100e440, 8, 0, 0)
07-28 09:43:44.096   320  3982 V AudioCache: ignored
07-28 09:43:44.096   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:43:44.097   320  3982 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-28 09:43:44.097   320  3982 V AwesomePlayer: setDataSource_l dataSource
07-28 09:43:44.097   320  3982 V LGParserOSAL: SniffLGParser start
07-28 09:43:44.097   320  3982 V LGParserOSAL: MainType:5, SubType=0
07-28 09:43:44.097   320  3982 V LGParserOSAL: #### check Mime : application/ogg
07-28 09:43:44.097   320  3982 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-28 09:43:44.097   320  3982 E MediaExtractor: Use LGExtractor :application/ogg 
07-28 09:43:44.145   320  3982 V LGParserOSAL: supported mime: application/ogg
07-28 09:43:44.145   320  3982 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-28 09:43:44.145   320  3982 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-28 09:43:44.145   320  3982 V AwesomePlayer: mBitrate = -1 bits/sec
07-28 09:43:44.145   320  3982 V AwesomePlayer: AudioTrack Setting
07-28 09:43:44.145   320  3982 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-28 09:43:44.145   320  3982 V AwesomePlayer: setAudioSource() 
07-28 09:43:44.145   320  3982 V MediaPlayerService: prepare
07-28 09:43:44.145   320  3982 V AwesomePlayer: prepareAsync_l() 
07-28 09:43:44.146   320  3982 V MediaPlayerService: wait for prepare
07-28 09:43:44.146   320  6888 V AwesomePlayer: onPrepareAsyncEvent() 
07-28 09:43:44.146   320  6888 V AwesomePlayer: initAudioDecoder() 
07-28 09:43:44.146   320  6888 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 09:43:44.146   320  6888 V AudioSystem: isOffloadSupported()
07-28 09:43:44.146   320  6888 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 09:43:44.146   320  6888 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 09:43:44.146   320  6888 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 09:43:44.147   320  6888 V AwesomePlayer: getUseOffload() = 0 
07-28 09:43:44.147   320  6888 V OMXCodec: OMXCodec::Create
07-28 09:43:44.147   320,  6888 V OMXCodec: findMatchingCodecs()
07-28 09:43:44.147   320  6888 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-28 09:43:44.147   320  6888 V OMXCodec: matchingCodecs.size()=1
07-28 09:43:44.147   320  6888 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-28 09:43:44.151   320  6888 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-28 09:43:44.151   320  6888 V LGCodecAdapter: LG Codec Adapter start
07-28 09:43:44.151   320  6888 V OMXCodec: OMXCodec Createtor
07-28 09:43:44.151   320  6888 V OMXCodec: setComponentRole
07-28 09:43:44.152   320  6888 V OMXCodec: configureCodec protected=0
07-28 09:43:44.152   320  6888 V LGCodecAdapter: called getLGCodecSpecificData
07-28 09:43:44.152   320  6888 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-28 09:43:44.152   320  6888 V LGCodecOSAL: Called LGconfigureCodecMETA
07-28 09:43:44.152   320  6888 V LGCodecOSAL: Called LGconfigureCodecMSG
07-28 09:43:44.152   320  6888 V LGCodecOSAL: Not support LGCodec
07-28 09:43:44.152   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 09:43:44.152   320  6888 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-28 09:43:44.152   320  6888 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-28 09:43:44.152   320  6888 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-28 09:43:44.153   320  6888 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 09:43:44.153   320  6888 V AudioSystem: isOffloadSupported()
07-28 09:43:44.153   320  6888 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 09:43:44.153   320  6888 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 09:43:44.153   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-28 09:43:44.153   320  6888 V OMXCodec: init()
07-28 09:43:44.153   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-28 09:43:44.153   320  6888 V OMXCodec: allocateBuffers
07-28 09:43:44.153   320  6888 V OMXCodec: allocateBuffersOnPort portIndex=0
07-28 09:43:44.153   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-28 09:43:44.154   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on input port
07-28 09:43:44.154   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
07-28 09:43:44.154   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
07-28 09:43:44.154   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
07-28 09:43:44.154   320  6888 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 09:43:44.154   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 09:43:44.155   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-28 09:43:44.155   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-28 09:43:44.155   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
07-28 09:43:44.155   320  6888 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
07-28 09:43:44.155   320  6888 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 09:43:44.155   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 09:43:44.155   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 09:43:44.156   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-28 09:43:44.156   320  6888 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 09:43:44.156   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-28 09:43:44.156   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-28 09:43:44.156   32,0  6890 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-28 09:43:44.156   320  6888 V OMXCodec: init() mAsyncCompletion wait free! 
07-28 09:43:44.156   320  6888 V AwesomePlayer: finishAsyncPrepare_l() 
07-28 09:43:44.156   320  6888 V AudioCache: notify(0xb100e440, 5, 0, 0)
07-28 09:43:44.156   320  6888 V AudioCache: ignored
07-28 09:43:44.156   320  6888 V AudioCache: notify(0xb100e440, 1, 0, 0)
07-28 09:43:44.156   320  6888 V AudioCache: prepared
07-28 09:43:44.157   320  3982 V AudioCache: wait - success
07-28 09:43:44.157   320  3982 V MediaPlayerService: start
07-28 09:43:44.157   320  3982 V AwesomePlayer: play_l() 
07-28 09:43:44.157   320  3982 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-28 09:43:44.157   320  3982 V AwesomePlayer: createAudioPlayer_l
07-28 09:43:44.157   320  3982 V AwesomePlayer: seekAudioIfNecessary_l() 
07-28 09:43:44.157   320  3982 V AwesomePlayer: startAudioPlayer_l() 
07-28 09:43:44.157   320  3982 D AudioPlayer: start of Playback, useOffload 0
07-28 09:43:44.157   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 09:43:44.157   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 09:43:44.159  1036  1950 W libprocessgroup: failed to open /acct/uid_10019/pid_5988/cgroup.procs: No such file or directory
07-28 09:43:44.161  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-28 09:43:44.166   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-28 09:43:44.166   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-28 09:43:44.166   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-28 09:43:44.166   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-28 09:43:44.166   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-28 09:43:44.167   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
,07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat(),
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1),
07-28 09:43:44.168   320  6890 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 09:43:44.168   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
,07-28 09:43:44.169   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-28 09:43:44.169   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-28 09:43:44.169   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c5470 on output port,
07-28 09:43:44.169   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,07-28 09:43:44.169   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,07-28 09:43:44.170  6680  6680 D UEI.SmartControl: QS Service created
07-28 09:43:44.177   320  3982 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-28 09:43:44.179   320  3982 V AudioCache: notify(0xb100e440, 6, 0, 0)
07-28 09:43:44.179   320  3982 V AudioCache: ignored
07-28 09:43:44.181  6811  6811 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 09:43:44.182   320  3982 V MediaPlayerService: wait for playback complete
,07-28 09:43:44.185  6811  6811 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 09:43:44.186  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 09:43:44.188  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:44.188  1978  2215 D LGBluetoothAPIService: Message: 2
07-28 09:43:44.189  1978  2215 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2f14c92d mBinding = false
07-28 09:43:44.189  1978  2215 D LGBluetoothAPIService: Sending unbind request.
07-28 09:43:44.190   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.190   320  6891 V AudioCache: memcpy(0xac102000, 0xb16da000, 4096)
07-28 09:43:44.190  3863  3948 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 09:43:44.193   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.193   320  6891 V AudioCache: memcpy(0xac103000, 0xb16da000, 4096)
07-28 09:43:44.193  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 09:43:44.193   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.193   320  6891 V AudioCache: memcpy(0xac104000, 0xb16da000, 4096)
07-28 09:43:44.194   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.194   320  6891 V AudioCache: memcpy(0xac105000, 0xb16da000, 4096)
07-28 09:43:44.195   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.195   320  6891 V AudioCache: memcpy(0xac106000, 0xb16da000, 4096)
07-28 09:43:44.196   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.196   320  6891 V AudioCache: memcpy(0xac107000, 0xb16da000, 4096)
07-28 09:43:44.196   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.196   320  6891 V AudioCache: memcpy(0xac108000, 0xb16da000, 4096)
07-28 09:43:44.198   320  6891 V AudioCache: write(0xb16da000, 4096)
,07-28 09:43:44.198   320  6891 V AudioCache: memcpy(0xac109000, 0xb16da000, 4096)
07-28 09:43:44.198  3863  3863 I GKI_LINUX: GKI_exit_task 1 done
07-28 09:43:44.198  3863  3863 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 09:43:44.199  3863  3863 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 09:43:44.199  3863  3863 I art     : --- WEIRD: removing null entry 246
07-28 09:43:44.199  3863  3863 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-28 09:43:44.199  3863  3863 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-28 09:43:44.199  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:44.200   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.200   320  6891 V AudioCache: memcpy(0xac10a000, 0xb16da000, 4096)
07-28 09:43:44.201  6811  6811 V LGMDMManager: Create singleton instance
07-28 09:43:44.202   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.202   320  6891 V AudioCache: memcpy(0xac10b000, 0xb16da000, 4096)
07-28 09:43:44.203   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.203   320  6891 V AudioCache: memcpy(0xac10c000, 0xb16da000, 4096)
07-28 09:43:44.204   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.204   320  6891 V AudioCache: memcpy(0xac10d000, 0xb16da000, 4096)
07-28 09:43:44.204  6761  6761 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 09:43:44.204   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.204   320  6891 V AudioCache: memcpy(0xac10e000, 0xb16da000, 4096)
07-28 09:43:44.205   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.205   320  6891 V AudioCache: memcpy(0xac10f000, 0xb16da000, 4096)
07-28 09:43:44.205   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.205   320  6891 V AudioCache: memcpy(0xac110000, 0xb16da000, 4096)
07-28 09:43:44.205  6761  6761 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 09:43:44.205   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.205   320  6891 V AudioCache: memcpy(0xac111000, 0xb16da000, 4096)
07-28 09:43:44.205  6761  6761 D LGBluetoothEventManager: [BTUI] clear device connection state
07-28 09:43:44.206  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:44.207  3863  3863 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-28 09:43:44.208   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.208  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 09:43:44.210   320  6891 V AudioCache: memcpy(0xac112000, 0xb16da000, 4096)
07-28 09:43:44.210   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.210   320  6891 V AudioCache: memcpy(0xac113000, 0xb16da000, 4096)
07-28 09:43:44.210   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.210   320  6891 V AudioCache: memcpy(0xac114000, 0xb16da000, 4096)
07-28 09:43:44.210   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.210   320  6891 V AudioCache: memcpy(0xac115000, 0xb16da000, 4096)
07-28 09:43:44.212  1605  1605 D BluetoothAdapter: 418243340: getState() :  mService = null. Returning STATE_OFF
07-28 09:43:44.212  1605  1605 D BluetoothAdapter: 418243340: getState() :  mService = null. Returning STATE_OFF
07-28 09:43:44.213  3863  3863 I art     : System.exit called, status: 0
07-28 09:43:44.213  3863  3863 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 09:43:44.215   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.215   320  6891 V AudioCache: memcpy(0xac116000, 0xb16da000, 4096)
07-28 09:43:44.215   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.215   320  6891 V AudioCache: memcpy(0xac117000, 0xb16da000, 4096)
07-28 09:43:44.216   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.216   320  6891 V AudioCache: memcpy(0xac118000, 0xb16da000, 4096)
07-28 09:43:44.216   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.216   320  6891 V AudioCache: memcpy(0xac119000, 0xb16da000, 4096)
07-28 09:43:44.217   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.217   320  6891 V AudioCache: memcpy(0xac11a000, 0xb16da000, 4096)
07-28 09:43:44.218   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.218   320  6891 V AudioCache: memcpy(0xac11b000, 0xb16da000, 4096)
07-28 09:43:44.218  6761  6761 D DockEventReceiver: finishStartingService: stopping service
07-28 09:43:44.219   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.219   320  6891 V AudioCache: memcpy(0xac11c000, 0xb16da000, 4096)
07-28 09:43:44.219   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.219   320  6891 V AudioCache: memcpy(0xac11d000, 0xb16da000, 4096)
07-28 09:43:44.221   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.221   320  6891 V AudioCache: memcpy(0xac11e000, 0xb16da000, 4096)
07-28 09:43:44.221   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.221   320  6891 V AudioCache: memcpy(0xac11f000, 0xb16da000, 4096)
07-28 09:43:44.222   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.222   320  6891 V AudioCache: memcpy(0xac120000, 0xb16da000, 4096)
07-28 09:43:44.223   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.223   320  6891 V AudioCache: memcpy(0xac121000, 0xb16da000, 4096)
07-28 09:43:44.224   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.224   320  6891 V AudioCache: memcpy(0xac122000, 0xb16da000, 4096)
07-28 09:43:44.224   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.224   320  6891 V AudioCache: memcpy(0xac123000, 0xb16da000, 4096)
07-28 09:43:44.225   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.225   320  6891 V AudioCache: memcpy(0xac124000, 0xb16da000, 4096)
07-28 09:43:44.226   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.226   320  6891 V AudioCache: memcpy(0xac125000, 0xb16da000, 4096)
07-28 09:43:44.227   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.227   320  6891 V AudioCache: memcpy(0xac126000, 0xb16da000, 4096)
07-28 09:43:44.228   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.228   320  6891 V AudioCache: memcpy(0xac127000, 0xb16da000, 4096)
,07-28 09:43:44.230   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.230   320  6891 V AudioCache: memcpy(0xac128000, 0xb16da000, 4096)
07-28 09:43:44.230  6680  6680 I UEI.SmartControl: Service initServices...
07-28 09:43:44.231  6680  6680 D UEI.SmartControl: QS start get config
07-28 09:43:44.231   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.231   320  6891 V AudioCache: memcpy(0xac129000, 0xb16da000, 4096)
07-28 09:43:44.232   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.232   320  6891 V AudioCache: memcpy(0xac12a000, 0xb16da000, 4096)
07-28 09:43:44.232   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.232   320  6891 V AudioCache: memcpy(0xac12b000, 0xb16da000, 4096)
07-28 09:43:44.233   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.233   320  6891 V AudioCache: memcpy(0xac12c000, 0xb16da000, 4096)
07-28 09:43:44.234   320  1405 V AudioFlinger: 3863 died, releasing its sessions
07-28 09:43:44.234   320  1405 V AudioFlinger:  pid 1879 @ 0
07-28 09:43:44.234   320  1405 V AudioFlinger:  pid 3426 @ 1
07-28 09:43:44.234   320  1405 V AudioFlinger:  pid 3426 @ 2
07-28 09:43:44.235   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.235   320  6891 V AudioCache: memcpy(0xac12d000, 0xb16da000, 4096)
07-28 09:43:44.235  6761  6761 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-28 09:43:44.235   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.235   320  6891 V AudioCache: memcpy(0xac12e000, 0xb16da000, 4096)
07-28 09:43:44.236   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.236   320  6891 V AudioCache: memcpy(0xac12f000, 0xb16da000, 4096)
07-28 09:43:44.237   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.237   320  6891 V AudioCache: memcpy(0xac130000, 0xb16da000, 4096)
07-28 09:43:44.237   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.237   320  6891 V AudioCache: memcpy(0xac131000, 0xb16da000, 4096)
07-28 09:43:44.238   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.238   320  6891 V AudioCache: memcpy(0xac132000, 0xb16da000, 4096)
07-28 09:43:44.239   320  6891 V AudioCache: write(0xb16da000, 4096)
07-28 09:43:44.239   320  6891 V AudioCache: memcpy(0xac133000, 0xb16da000, 4096)
07-28 09:43:44.239   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-28 09:43:44.239   320  6891 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 09:43:44.239   320  6891 V AwesomePlayer: postAudioEOS() 
07-28 09:43:44.239   320  6891 V AudioCache: write(0xb16da000, 280)
07-28 09:43:44.239   320  6891 V AudioCache: memcpy(0xac134000, 0xb16da000, 280)
07-28 09:43:44.240   320  6888 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-28 09:43:44.240   320  6888 V AwesomePlayer: onStreamDone
07-28 09:43:44.240   320  6888 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-28 09:43:44.240   320  6888 V AudioCache: notify(0xb100e440, 2, 0, 0)
07-28 09:43:44.240   320  6888 V AudioCache: playback complete
07-28 09:43:44.241   320  6888 V AwesomePlayer: pause_l() 
07-28 09:43:44.241   320  3982 V AudioCache: wait - success
07-28 09:43:44.241   320  6888 V AudioCache: notify(0xb100e440, 7, 0, 0)
07-28 09:43:44.241   320  6888 V AudioCache: ignored
07-28 09:43:44.241   320  3982 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-28 09:43:44.241   320  6888 V AwesomePlayer: cancelPlayerEvents
07-28 09:43:44.241   320  6888 D AudioPlayer: Pause Playback at 1068125
,07-28 09:43:44.241   320  3982 V AwesomePlayer: reset_l() 
,07-28 09:43:44.241   320  3982 V AudioCache: notify(0xb100e440, 8, 0, 0)
07-28 09:43:44.241   320  3982 V AudioCache: ignored
07-28 09:43:44.241   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:43:44.241   320  3982 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-28 09:43:44.241   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-28 09:43:44.241   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-28 09:43:44.241   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-28 09:43:44.241   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 09:43:44.241   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 09:43:44.241   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 09:43:44.241   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-28 09:43:44.241   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
07-28 09:43:44.241   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-28 09:43:44.241   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 0
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c5470 on port 1
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:43:44.242   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-28 09:43:44.242   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 09:43:44.242   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 09:43:44.243   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-28 09:43:44.243   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-28 09:43:44.243   320  6890 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-28 09:43:44.243   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 09:43:44.243   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-28 09:43:44.243   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-28 09:43:44.244   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-28 09:43:44.244   320  3982 D AudioPlayer: AudioPlayer releasing audio source
07-28 09:43:44.244   320  3982 D AudioPlayer: AudioPlayer done releasing audio source
07-28 09:43:44.244   320  3982 V AwesomePlayer: reset_l() 
07-28 09:43:44.244   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:43:44.244   320  3982 V AwesomePlayer: ~AwesomePlayer call,
07-28 09:43:44.244   320  3982 V AwesomePlayer: reset_l() 
07-28 09:43:44.244   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:43:44.244  6811  6887 V SoundPool: close(31)
07-28 09:43:44.244  6811  6887 V SoundPool: pointer = 0x9fff4000, size = 205080, sampleRate = 48000, numChannels = 2
07-28 09:43:44.276  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 09:43:44.277  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,07-28 09:43:44.307  1036  1657 I ActivityManager: Process com.android.bluetooth (pid 3863) has died,
07-28 09:43:44.308  1036  1657 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,07-28 09:43:44.316  2268  2268 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 09:43:44.316  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7716
07-28 09:43:44.328  6761  6761 D BluetoothPermissionRequest: onReceive
,07-28 09:43:44.335  6761  6761 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 09:43:44.336  6761  6761 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-28 09:43:44.340  6761  6761 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 09:43:44.395  1036  2005 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6894 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-28 09:43:44.467  6894  6894 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 09:43:44.468  6894  6894 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 09:43:44.468  6894  6894 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 09:43:44.469  6894  6894 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 09:43:44.494  6894  6894 D BluetoothAdapterApp: Loading JNI Library
,07-28 09:43:44.510  6680  6680 I UEI.SmartControl: Supports setup maps: true
,07-28 09:43:44.513  6680  6680 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 09:43:44.513  6680  6680 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 09:43:44.513  6680  6680 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 09:43:44.513  6680  6680 I UEI.SmartControl: ### init IR Blaster...
07-28 09:43:44.516  6680  6680 D serial_port: Configuring serial port
07-28 09:43:44.516  6680  6680 E UEI.SmartControl: UEIBLaster setting for 616
07-28 09:43:44.516  6680  6680 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 09:43:44.516  6680  6680 I UEI.SmartControl: configuring settings for MAXQ616
07-28 09:43:44.516  6680  6680 I UEI.SmartControl: Get version...
07-28 09:43:44.529  6894  6894 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@b6c6eb Instance Count = 1
,07-28 09:43:44.535  6894  6894 D BluetoothAdapterApp: onCreate
07-28 09:43:44.535  6680  6911 D UEI.SmartControl: serial port data available: 21
,07-28 09:43:44.557  6894  6894 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,07-28 09:43:44.557  6894  6894 D ProfileConfigQcom: Adding HeadsetService
07-28 09:43:44.557  6894  6894 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-28 09:43:44.557  6894  6894 D ProfileConfigQcom: Adding A2dpService
07-28 09:43:44.558  6894  6894 D ProfileConfigQcom: [BTUI] HidService is supported
07-28 09:43:44.558  6894  6894 D ProfileConfigQcom: Adding HidService
07-28 09:43:44.558  6894  6894 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 09:43:44.558  6894  6894 D ProfileConfigQcom: Adding HealthService
07-28 09:43:44.558  6894  6894 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-28 09:43:44.559  6894  6894 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 09:43:44.559  6894  6894 D ProfileConfigQcom: Adding PanService
07-28 09:43:44.560  6894  6894 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 09:43:44.560  6894  6894 D ProfileConfigQcom: Adding GattService
07-28 09:43:44.560  6894  6894 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 09:43:44.560  6894  6894 D ProfileConfigQcom: Adding BluetoothMapService
07-28 09:43:44.560  6894  6894 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-28 09:43:44.561  6680  6680 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 09:43:44.561  6680  6680 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 09:43:44.562  6680  6680 I UEI.SmartControl: QS saving settings...
07-28 09:43:44.562  6894  6894 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-28 09:43:44.563  6680  6680 D UEI.SmartControl: IR Blaster version: 25672567
07-28 09:43:44.569  6761  6761 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 09:43:44.571  6894  6894 V LGMDMManagerInternal: Create singleton instance
,07-28 09:43:44.580  6680  6911 D UEI.SmartControl: serial port data available: 4
,07-28 09:43:44.610  6680  6915 I UEI.SmartControl: Device manager: loading config....
,07-28 09:43:44.614  6680  6915 D UEI.SmartControl: ----------- loading internal config...
,07-28 09:43:44.616  6680  6680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 09:43:44.618  6680  6680 E UEI.SmartControl: Services init done
07-28 09:43:44.618  6680  6680 D UEI.SmartControl: QS Service init finished
07-28 09:43:44.619  6680  6680 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 09:43:44.619  6680  6680 D UEI.SmartControl: QS Service version code: 201091
07-28 09:43:44.619  6680  6680 D UEI.SmartControl: Service requested: Control
07-28 09:43:44.625  6680  6680 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 09:43:44.625  6680  6915 E UEI.SmartControl: Loading SETTINGS...
,07-28 09:43:44.630  6680  6680 D UEI.SmartControl: Internal service binding...
,07-28 09:43:44.631  6811  6811 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 09:43:44.632  6680  6696 I UEI.SmartControl: ------ IControl API: 11
07-28 09:43:44.632  6680  6696 D UEI.SmartControl: File observer start...
07-28 09:43:44.632  6680  6696 E UEI.SmartControl: IR Port is disabled: false
07-28 09:43:44.633  6680  6696 D UEI.SmartControl: Starting file observer...
07-28 09:43:44.633  6680  6696 I UEI.SmartControl: Registering callback...
07-28 09:43:44.637  6680  6695 I UEI.SmartControl: ------ IControl API: 19
07-28 09:43:44.638  6680  6695 I UEI.SmartControl: Registering Services Ready callback...
07-28 09:43:44.638  6680  6915 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 09:43:44.643  6894  6894 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-28 09:43:44.647  6894  6894 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 09:43:44.647  6894  6894 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 09:43:44.648  6894  6894 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 09:43:44.648  6894  6894 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:44.649  6894  6894 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-28 09:43:44.649  6680  6914 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 09:43:44.651  6811  6826 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-28 09:43:44.651  6811  6885 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-28 09:43:44.651  6680  6914 D UEI.SmartControl: -----service ready thread exits
07-28 09:43:44.651  6811  6885 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-28 09:43:44.652  6811  6811 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-28 09:43:44.652  6811  6811 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-28 09:43:44.652  6680  6696 I UEI.SmartControl: ------ IControl API: 8
07-28 09:43:44.653  6811  6811 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-28 09:43:44.653  6811  6811 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-28 09:43:44.654  6811  6811 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-28 09:43:44.654  6811  6811 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-28 09:43:44.654  6811  6811 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-28 09:43:44.655  6811  6811 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-28 09:43:44.655  6811  6811 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,07-28 09:43:44.661  6828  6828 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-28 09:43:44.663  6811  6811 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 09:43:44.663  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 09:43:44.664  6811  6811 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 09:43:44.664  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 09:43:44.665  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 09:43:44.665  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-28 09:43:44.666  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-28 09:43:44.666  6811  6811 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469691824666]
07-28 09:43:44.667  6811  6811 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
07-28 09:43:44.671  1036  1950 I ActivityManager: Killing 6015:com.android.gallery3d/u0a27 (adj 15): empty #17
,07-28 09:43:44.690  6811  6918 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-28 09:43:44.708  1036  1950 I ActivityManager: Killing 6479:com.lge.email/u0a23 (adj 15): empty #18
,07-28 09:43:44.742  1036  2120 W libprocessgroup: failed to open /acct/uid_10023/pid_6479/cgroup.procs: No such file or directory
,07-28 09:43:44.744  6811  6811 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-28 09:43:44.745  6811  6811 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 09:43:44.745  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-28 09:43:44.746  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-28 09:43:44.746  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-28 09:43:44.746  1036  2005 W libprocessgroup: failed to open /acct/uid_10027/pid_6015/cgroup.procs: No such file or directory
07-28 09:43:44.746  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-28 09:43:44.747  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-28 09:43:44.762  6811  6811 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-28 09:43:44.879  1036  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1e10e230 type 2 when 136017 com.google.android.gms} when 136017
,07-28 09:43:44.894   316  6920 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,07-28 09:43:44.895  1036  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-28 09:43:45.878  1036  2005 D WifiServiceImplEx: setWifiEnabled: true pid=6576, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 09:43:45.880  1036  2005 D WifiService: setWifiEnabled: true pid=6576, uid=10118
07-28 09:43:45.880  1036  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 09:43:45.904  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:45.910  1036  1098 D Tethering: MasterInitialState.processMessage what=3
,07-28 09:43:45.916  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:45.918  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:45.923  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:45.932  1036  1098 D Tethering: MasterInitialState.processMessage what=3
07-28 09:43:45.940  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 09:43:45.940  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,07-28 09:43:45.941  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 09:43:45.943  1036  1394 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-28 09:43:45.943  1036  1394 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 09:43:45.946  1036  1394 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-28 09:43:45.946  1036  1394 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 09:43:45.946  1036  1394 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 09:43:45.946  1036  1394 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 09:43:45.946  1036  1394 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-28 09:43:45.946  1036  1394 E WifiHW  : unknown target_country: EU , set to default
07-28 09:43:45.946  1036  1394 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-28 09:43:45.946  1036  1394 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-28 09:43:45.946  1036  1394 I WifiUtil: gEnableBmps=1
07-28 09:43:45.954  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:45.958  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:45.960  1036  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:45.962  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 09:43:45.965  5735  5735 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 09:43:45.973  6387  6417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 09:43:45.986  5735  5735 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 09:43:46.005  2268  2268 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:46.034  1036  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:46.068  1036  2041 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6945 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-28 09:43:46.073  1036  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:46.073  1036  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 09:43:46.174  6945  6945 I AppUp4:AppBoxCP: onCreate
07-28 09:43:46.175  6945  6945 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-28 09:43:46.188  6945  6945 I AppUp4:DB:  setFingerPrint start
07-28 09:43:46.189  6945  6945 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-28 09:43:46.191  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-28 09:43:46.191  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
07-28 09:43:46.202  1605  1605 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
07-28 09:43:46.202  1605  1605 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-28 09:43:46.203  1036  1400 D WifiController: battery changed pluggedType: 2
07-28 09:43:46.204  1978  2172 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-28 09:43:46.204  1978  2172 D LEDHandler: Battery Level Remaining: 100%
07-28 09:43:46.204  1978  2172 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
07-28 09:43:46.205  1605  1605 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-28 09:43:46.210  6945  6945 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-28 09:43:46.210  6945  6945 I AppUp4:DB:  SDK version = 21
07-28 09:43:46.210  6945  6945 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-28 09:43:46.213  6644  6644 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-28 09:43:46.214  6945  6945 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-28 09:43:46.215  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 09:43:46.215  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:46.218  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 09:43:46.218  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-28 09:43:46.227  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 09:43:46.281  6945  6945 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:46.281  6945  6945 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:43:46.293  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3474741d
07-28 09:43:46.293  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 09:43:46.294  6945  6945 D AppUp4:CustFacade: isPhone : true
07-28 09:43:46.295  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
07-28 09:43:46.296  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-28 09:43:46.296  6945  6945 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-28 09:43:46.298  6945  6965 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,07-28 09:43:46.299  6945  6965 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-28 09:43:46.299  6945  6965 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-28 09:43:46.304  1036  1052 I ActivityManager: Killing 6319:com.android.defcontainer/u0a4 (adj 15): empty #17
07-28 09:43:46.342  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:46.343  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 09:43:46.344  1036  2040 W libprocessgroup: failed to open /acct/uid_10004/pid_6319/cgroup.procs: No such file or directory
,07-28 09:43:46.348  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 09:43:46.351  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:46.360  4298  6967 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 09:43:46.370  4298  6968 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:46.370  4298  6968 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 09:43:46.408  1036  1951 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6969 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-28 09:43:46.512  6969  6969 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 09:43:46.513  6969  6969 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 09:43:46.514  6969  6969 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 09:43:46.515  6969  6969 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-28 09:43:46.610  6969  6969 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-28 09:43:46.625  6969  6969 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-28 09:43:46.686   316   896 D SoftapController: Softap fwReload - Ok
07-28 09:43:46.688  1036  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 09:43:46.688  1036  1098 D Tethering: InitialState.processMessage what=4
07-28 09:43:46.690  1036  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 09:43:46.699  1036  1394 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (748ms)
07-28 09:43:46.700   316   896 D CommandListener: Setting iface cfg
07-28 09:43:46.700   316   896 D CommandListener: Trying to bring down wlan0
07-28 09:43:46.701   316   896 D CommandListener: Clearing all IP addresses on wlan0
07-28 09:43:46.703  1036  1394 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-28 09:43:46.710  1036  1394 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 09:43:46.710  1036  1394 E WifiStateMachine: useWiFiOffloading() : false
07-28 09:43:46.710  1036  1394 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 09:43:46.714  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-28 09:43:46.717  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:46.701  6998  6998 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 09:43:46.720  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:46.721  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:46.723  1036  1394 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 09:43:46.723  1036  1394 D WifiMonitor: connecting to supplicant
07-28 09:43:46.701  6998  6998 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:46.728  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,07-28 09:43:46.731  6998  6998 I wpa_supplicant: Successfully initialized wpa_supplicant
07-28 09:43:46.736  6969  6969 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 09:43:46.765  6998  6998 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 09:43:46.765  6998  6998 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-28 09:43:46.781  6969  6969 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:46.781  6969  6969 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:43:46.872  6998  6998 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 09:43:46.918  6969  6969 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 09:43:46.928  6998  6998 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-28 09:43:46.948  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-28 09:43:46.949  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,07-28 09:43:46.950  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 09:43:46.950  1036  1394 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 09:43:46.951  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:46.951  1036  1394 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:46.952  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:46.952  1036  1394 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:46.953  1036  1394 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 09:43:46.953  1036  1394 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 09:43:46.953  6998  6998 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-28 09:43:46.954  6998  6998 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-28 09:43:46.954  1036  7008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-28 09:43:46.954  1036  7008 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 09:43:46.954  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 09:43:46.954  1036  1394 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 09:43:46.955  1036  1394 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 09:43:46.955  1036  1394 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-28 09:43:46.956  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 09:43:46.956  1036  7008 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 09:43:46.956  1036  7008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-28 09:43:46.958  1036  1394 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 09:43:46.958  1036  1394 E WifiStateMachine: useWiFiOffloading() : false
07-28 09:43:46.958  1036  1394 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 09:43:46.959  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:46.959  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:46.959  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:46.959  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:46.959  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 09:43:46.965  1036  1394 D WifiNative-wlan0: doBoolean: SET update_config 1
07-28 09:43:46.965  1036  1394 D WifiNative-wlan0: SET update_config 1: returned true
07-28 09:43:46.966  1036  1394 D WifiConfigStore: Loading config and enabling all networks 
07-28 09:43:46.966  1036  1394 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 09:43:46.966  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:46.967  1036  1394 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,07-28 09:43:46.967  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 09:43:46.970  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:46.970  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:46.970  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:46.970  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:46.970  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:46.970  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:46.970  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:46.970  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:46.970  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:46.970  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:46.970  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:46.971  1036  1398 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 09:43:46.971  1978  1978 D WfdService: Waiting for WifiP2p enabling
07-28 09:43:46.971  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:46.971  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:46.971  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:46.971  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:46.971  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:43:46.971  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:46.971  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:46.971  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:46.971  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:46.972  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:46.972  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:46.977  6848  7010 W FormManager: Network not available. Please check & try again.
07-28 09:43:46.978  1036  1394 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-28 09:43:46.983  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 09:43:46.983  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:46.984  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-28 09:43:46.990  1036  1394 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 09:43:46.990  1036  1394 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 09:43:46.993  6969  6969 I HubEmail: JNI_OnLoad()
07-28 09:43:46.993  6969  6969 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 09:43:46.993  6969  6969 I HubEmail: registerNatives()
07-28 09:43:46.993  6969  6969 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 09:43:46.993  6969  6969 I HubEmail: registerNativeMethods()
07-28 09:43:46.993  6969  6969 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-28 09:43:46.993  6969  6969 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-28 09:43:47.012  1036  1996 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7014 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-28 09:43:47.015  1036  1394 D WifiStateMachine: enableVerboseLogging : level 2
07-28 09:43:47.015  1036  1394 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-28 09:43:47.015  1036  1394 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-28 09:43:47.015  1036  1394 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 09:43:47.016  6848  7011 V FormManager: Network unavailable.
07-28 09:43:47.016  1036  1394 D WifiNative-wlan0: SET manufacturer LGE: returned true
,07-28 09:43:47.016  1036  1394 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-28 09:43:47.017  1036  1394 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-28 09:43:47.017  1036  1394 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 09:43:47.017  1036  1394 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 09:43:47.017  6969  7013 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.017  1036  1394 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-28 09:43:47.018  1036  1394 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 09:43:47.018  1036  1394 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 09:43:47.018  1036  1394 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 09:43:47.018  1036  1394 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 09:43:47.019  1036  1394 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 09:43:47.019  6848  7011 V FormManager: Network unavailable.
07-28 09:43:47.019  1036  1394 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 09:43:47.019  1036  1394 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-28 09:43:47.020  1978  1978 D WfdsService: Supplicant Connection state is changed : true
07-28 09:43:47.020  1978  2356 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 09:43:47.020  1978  2356 D WfdsService: Set the WFDS Monitor: true
07-28 09:43:47.020  1978  2356 D WfdsMonitor: WfdsMonitorThread create
07-28 09:43:47.020  1978  2356 D WfdsMonitor: WFDS Monitor is created and started
07-28 09:43:47.020  1978  2356 D WfdsService: WiFi: Supplicant connection re-established
07-28 09:43:47.020  1036  1394 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 09:43:47.020  1036  1394 D WifiNative-HAL: Setting external_sim to 1
07-28 09:43:47.020  1036  1394 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 09:43:47.021  1036  1394 D WifiNative-wlan0: SET external_sim 1: returned true
07-28 09:43:47.021  1036  1394 I WifiNative-HAL: startHal
07-28 09:43:47.021  1036  1394 D wifi    : setting scan oui 0x956cb300
07-28 09:43:47.021  1978  7024 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 09:43:47.021  1036  1394 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 09:43:47.021  1978  7024 E CtrlSupplicant: Succeed to open control connection
07-28 09:43:47.021  1036  1394 I WifiNative-HAL: startHal
07-28 09:43:47.022  1036  1394 D wifi    : setting scan oui 0x956cb300
07-28 09:43:47.022  1978  7024 E CtrlSupplicant: Succeed to open monitor connection
07-28 09:43:47.022  1036  1394 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 09:43:47.022  1036  1394 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 09:43:47.022  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 09:43:47.022  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-28 09:43:47.023  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 09:43:47.023  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 09:43:47.023  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 09:43:47.023  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 09:43:47.023  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 09:43:47.023  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 09:43:47.023  1978  7024 D WfdsMonitor: Supplicant connection established
07-28 09:43:47.024  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 09:43:47.024  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 09:43:47.024  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 09:43:47.024  1036  139,4 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 09:43:47.024  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 09:43:47.024  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 09:43:47.025  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 09:43:47.025  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 09:43:47.025  6998  6998 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-28 09:43:47.025  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-28 09:43:47.025  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 09:43:47.025  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 09:43:47.025  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 09:43:47.025  1978  2356 D WfdsService: Connected to the supplicant for wfds
07-28 09:43:47.026  1036  1394 E WifiNative: : [138,166,354 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 09:43:47.026  1036  1394 D WifiNative-wlan0: doBoolean: RECONNECT
07-28 09:43:47.027  1036  1394 D WifiNative-wlan0: RECONNECT: returned true
07-28 09:43:47.027  1036  1394 D WifiNative-wlan0: doString: [STATUS]
,07-28 09:43:47.027  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 09:43:47.027  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 09:43:47.028  1036  1394 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 09:43:47.028  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 09:43:47.028  1036  1394 D WifiNative-wlan0: SET ps 1: returned true
07-28 09:43:47.028  1036  1392 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.030   316   896 D CommandListener: Setting iface cfg
07-28 09:43:47.030   316   896 D CommandListener: Trying to bring up p2p0
07-28 09:43:47.030  1036  1392 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 09:43:47.030  1036  1392 D LGWifiP2pService: P2pEnablingState
07-28 09:43:47.030  1036  1392 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.030  1036  1392 D LGWifiP2pService: P2p socket connection successful
07-28 09:43:47.030  1036  1392 D LGWifiP2pService: P2pEnabledState
07-28 09:43:47.030  1036  1392 D LGWifiP2pService: sending p2p connection changed broadcast
07-28 09:43:47.031  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-28 09:43:47.031  1036  1392 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 09:43:47.032  1978  1978 D WfdsService: WifiP2pState is changed : true
07-28 09:43:47.032  1978  2356 D WfdsService: Receive the WFDS_ENABLE Method
07-28 09:43:47.032  1978  2356 D WfdsService: Set the WFDS Monitor: true
07-28 09:43:47.032  1978  2356 D WfdsService: Connected to the supplicant for wfds
07-28 09:43:47.032  1978  2356 D WfdsJNI : doCommand: WFDS_SET TRUE
07-28 09:43:47.032  6998  6998 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-28 09:43:47.032  1978  2356 D WfdsService: selectPreferredScanChannel [36]
07-28 09:43:47.032  1978  1978 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,07-28 09:43:47.032  1978  2356 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 09:43:47.033  1978  1978 D WfdsService: isConnected: false
07-28 09:43:47.034  1036  1392 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 09:43:47.034  1036  1392 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 09:43:47.035  1036  1392 D WifiNative-p2p0: SET device_name G3: returned true
07-28 09:43:47.035  1036  1392 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 09:43:47.035  1036  1392 D LGWifiP2pService: before postfix = G3
07-28 09:43:47.035  1036  1392 D WifiServerServiceExt: postfix byte check : 2
07-28 09:43:47.035  1036  1392 D LGWifiP2pService: after postfix = G3
07-28 09:43:47.035  1036  1392 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 09:43:47.035  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 09:43:47.035  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-28 09:43:47.035  1036  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.035  1036  1558 I WifiNative-HAL: startHal
07-28 09:43:47.035  1036  1559 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.036  1036  1392 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 09:43:47.036  1036  1392 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 09:43:47.036  1036  1558 D wifi    : getting scan capabilities on interface[1] = 0x956cb300
07-28 09:43:47.036  1036  1558 D wifi    : failed to get capabilities : -3
07-28 09:43:47.036  1036  1394 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-28 09:43:47.036  1036  1558 E WifiScanningService: could not get scan capabilities
07-28 09:43:47.036  1036  1394 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 09:43:47.036  1036  1392 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 09:43:47.036  1036  1392 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 09:43:47.036  1036  1394 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 09:43:47.037  1036  1392 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 09:43:47.037  1036  1392 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 09:43:47.037  1036  1392 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-28 09:43:47.037  1036  1394 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-28 09:43:47.037  1036  1392 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 09:43:47.037  1036  1392 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 09:43:47.037  1036  1394 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-28 09:43:47.038  1036  1394 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-28 09:43:47.038  1036  1394 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-28 09:43:47.038  1036  1394 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 09:43:47.038  1978  1978 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 09:43:47.038  1978  1978 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,07-28 09:43:47.038  6998  6998 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-28 09:43:47.038  1978  1978 D WfdsService: Update P2p Interface State: 3
07-28 09:43:47.039  1036  1392 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 09:43:47.039  1036  1392 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 09:43:47.039  1036  1392 D WifiNative-p2p0: P2P_FLUSH: returned true
07-28 09:43:47.039  1036  1392 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 09:43:47.039  1036  1392 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-28 09:43:47.039  1036  1392 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,07-28 09:43:47.040  1036  1392 D WifiNative-p2p0:    returned OK
07-28 09:43:47.040  1036  1392 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 09:43:47.040  1036  1392 D WifiNative-p2p0: SAVE_CONFIG: returned false
07-28 09:43:47.041  1036  1392 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 09:43:47.041  1036  1392 D LGWifiP2pService: InactiveState
07-28 09:43:47.041  1036  1392 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.041  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.041  1036  1392 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,07-28 09:43:47.045  1036  1051 I ActivityManager: Killing 6512:com.google.android.apps.docs/u0a61 (adj 15): empty #17
07-28 09:43:47.048  1036  1394 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-28 09:43:47.048  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 09:43:47.049  1036  1394 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-28 09:43:47.049  1036  1394 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 09:43:47.049  6998  6998 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:43:47.049  1036  1394 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 09:43:47.049  6998  6998 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 09:43:47.050  6998  6998 E wpa_supplicant: disconnect_rssi_lvl: -100
07-28 09:43:47.050  6998  6998 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.050  1036  1394 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 09:43:47.050  1036  1394 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 09:43:47.050  6998  6998 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.050  1036  1394 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
07-28 09:43:47.050  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-28 09:43:47.051  1978  7024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 09:43:47.051  1978  7024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:43:47.051  1978  7024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:43:47.051  1036  7008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 09:43:47.051  1036  7008 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:43:47.051  1036  7008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,07-28 09:43:47.051  1036  7008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,07-28 09:43:47.051  1036  7008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:43:47.051  1036  7008 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.051  1036  7008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.051  1036  7008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.051  1036  7008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:43:47.051  1036  7008 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.051  1036  7008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.052  1036  7008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.052  1036  1392 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 09:43:47.052  1036  1392 D LGWifiP2pService: InactiveState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.052  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.052  1036  1392 D LGWifiP2pService: DefaultState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.053  1036  1392 D LGWifiP2pService: InactiveState{ when=-12ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.053  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.053  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 09:43:47.053  1036  1392 D LGWifiP2pService: DefaultState{ when=-12ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.053  6998  6998 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:43:47.053  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 09:43:47.053  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:43:47.053  1036  7008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:43:47.053  1036  7008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:43:47.054  6998  6998 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 09:43:47.054  6998  6998 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.054  1036  1394 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-28 09:43:47.054  1036  1394 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-28 09:43:47.054  1036  1394 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 09:43:47.054  6998  6998 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.054  1036  1394 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 09:43:47.054  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 09:43:47.055  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 09:43:47.055  6998  6998 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 09:43:47.056  1978  7024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:43:47.056  1036  1394 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 09:43:47.056  1036  7008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:43:47.056  1036  1394 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-28 09:43:47.056  1036  7008 E Wif,iMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.056  1036  7008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.056  1978  7024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:43:47.056  1036  7008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.056  1036  7008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:43:47.056  1036  1394 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-28 09:43:47.056  1036  7008 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.056  1036  1394 D WifiNative-wlan0: doBoolean: SCAN
07-28 09:43:47.056  1036  7008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.056  1036  7008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:43:47.056  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-28 09:43:47.056  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 09:43:47.056  1036  7008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 09:43:47.056  1036  7008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 09:43:47.056  1036  1394 D WifiNative-wlan0: SCAN: returned false
07-28 09:43:47.056  1978  2356 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 09:43:47.056  1036  1392 D LGWifiP2pService: InactiveState{ when=-15ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.056  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.056  1036  1392 D LGWifiP2pService: DefaultState{ when=-16ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.056  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=138197  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 09:43:47.056  1036  1392 D LGWifiP2pService: InactiveState{ when=-16ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.056  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.057  1036  1392 D LGWifiP2pService: DefaultState{ when=-16ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.057  1036  1392 D LGWifiP2pService: InactiveState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.057  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.057  1036  1036 E WifiServerServiceExt: No p2p device connected
07-28 09:43:47.086  7014  7014 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:47.087  7014  7014 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 09:43:47.088  7014  7014 D PhoneMonitor: Register our PhoneStateListener
,07-28 09:43:47.099  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=138240  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 09:43:47.099  1036  1394 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,07-28 09:43:47.100  1036  1394 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 09:43:47.100  1036  1394 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 09:43:47.100  1036  1394 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 09:43:47.100  1036  1394 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 09:43:47.101  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.101  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:47.102  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 09:43:47.104  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.104  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 09:43:47.104  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 09:43:47.105  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:43:47.105  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 09:43:47.106  1036  2041 W libprocessgroup: failed to open /acct/uid_10061/pid_6512/cgroup.procs: No such file or directory
07-28 09:43:47.120  7014  7014 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-28 09:43:47.124  7014  7014 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-28 09:43:47.142  7014  7014 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-28 09:43:47.142  7014  7014 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-28 09:43:47.143  7014  7014 D TelephonyAutoProfiling: [parse] Load xml
07-28 09:43:47.145  7014  7014 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-28 09:43:47.145  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-28 09:43:47.145  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-28 09:43:47.145  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-28 09:43:47.145  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-28 09:43:47.145  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-28 09:43:47.146  7014  7014 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-28 09:43:47.146  7014  7014 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,07-28 09:43:47.152  7014  7014 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,07-28 09:43:47.193  1036  1052 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7035 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 09:43:47.194  1036  1052 I ActivityManager: Killing 6075:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
07-28 09:43:47.248  1036  2091 W libprocessgroup: failed to open /acct/uid_10080/pid_6075/cgroup.procs: No such file or directory
,07-28 09:43:47.462  1036  2091 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7059 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-28 09:43:47.466  1036  2091 I ActivityManager: Killing 6104:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-28 09:43:47.532  1036  2041 W libprocessgroup: failed to open /acct/uid_10097/pid_6104/cgroup.procs: No such file or directory
,07-28 09:43:47.586  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 09:43:47.586  1036  7008 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,07-28 09:43:47.587  6998  6998 E wpa_supplicant: USIM:  scard_init function
07-28 09:43:47.589  1036  1394 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 09:43:47.589  1036  1394 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 09:43:47.590  1036  1394 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 09:43:47.590  1036  1394 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
07-28 09:43:47.590  1036  1394 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-28 09:43:47.590  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-28 09:43:47.590  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
07-28 09:43:47.590  1036  7008 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 09:43:47.592  6998  6998 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-28 09:43:47.593  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-28 09:43:47.593  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,07-28 09:43:47.640  1036  1052 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7076 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 09:43:47.644  1036  1052 I ActivityManager: Killing 6609:com.lge.eula/1000 (adj 15): empty #17
07-28 09:43:47.701  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=138842  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-28 09:43:47.708  6998  6998 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-28 09:43:47.709  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-28 09:43:47.709  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-28 09:43:47.709  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-28 09:43:47.709  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-28 09:43:47.710  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:43:47.710  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:43:47.717  6998  6998 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 09:43:47.717  6998  6998 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,07-28 09:43:47.722  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:43:47.722  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:43:47.722  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 09:43:47.722  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 09:43:47.722  1036  7008 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 09:43:47.722  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-28 09:43:47.722  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 09:43:47.722  1036  7008 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 09:43:47.722  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:43:47.723  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:43:47.727  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.727  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.727  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 09:43:47.728  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.728  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:47.729  1036  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 09:43:47.732  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6609/cgroup.procs: No such file or directory
07-28 09:43:47.733  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.735  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=138875  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 09:43:47.735  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=138876  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 09:43:47.736  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=138876  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 09:43:47.737  1036  1394 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138877
07-28 09:43:47.737  1036  1394 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138877
,07-28 09:43:47.746  1036  1394 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138886
,07-28 09:43:47.746  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138887
07-28 09:43:47.747  1036  1394 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138887
07-28 09:43:47.748  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.748  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.748  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 09:43:47.749  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=138887  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,07-28 09:43:47.753  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.755  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=138895  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 09:43:47.755  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=138896  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 09:43:47.756  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=138896  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 09:43:47.756  1036  1394 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138897
07-28 09:43:47.757  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.757  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:47.757  1036  1394 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138897
07-28 09:43:47.757  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.757  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,07-28 09:43:47.761  1036  1394 D WifiNative-wlan0: doString: [STATUS]
07-28 09:43:47.762  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.763  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:43:47.763  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:43:47.764  1036  1394 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 09:43:47.764  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.764  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:47.765  1036  1394 I WifiServiceExtension: setVHTCapabilityType  : false
07-28 09:43:47.767  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.770  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.770  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.770  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,07-28 09:43:47.772  1036  1394 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-28 09:43:47.772  1036  1394 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-28 09:43:47.781  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.781  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.781  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 09:43:47.781  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.781  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.781  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-28 09:43:47.785  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.785  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:47.786  1036  1394 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-28 09:43:47.786  1036  1394 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 09:43:47.786  1036  1394 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 09:43:47.787  1036  1407 D ConnectivityService: Got NetworkAgent Messenger
07-28 09:43:47.787  1036  1407 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 09:43:47.787  1036  1407 D ConnectivityService: NetworkAgent connected
07-28 09:43:47.787  1036  1394 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 09:43:47.787  1036  1394 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 09:43:47.790  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.793  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.794  1036  1394 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 09:43:47.794  1036  1394 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 09:43:47.794  1036  1394 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 09:43:47.794  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:47.795  1036  1394 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 09:43:47.795  1036  1394 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 09:43:47.796  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.798  1036  1394 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 09:43:47.799   316   896 D CommandListener: Setting iface cfg
,07-28 09:43:47.807  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.807  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:47.808  1036  1394 E WifiStateMachine: Start Dhcp Watchdog 2
07-28 09:43:47.808  1036  7102 D DhcpStateMachine: StoppedState
07-28 09:43:47.808  1036  7102 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.809  1036  7102 D DhcpStateMachine: WaitBeforeStartState
07-28 09:43:47.809  1036  1394 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=138949  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:43:47.809  1036  1394 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=138950  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:43:47.810  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.810  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=138950  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:43:47.811  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:47.811  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:47.812  1036  1394 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:47.812  1036  1394 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:47.813  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:47.813  1036  1394 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:47.814  1036  1394 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=138954  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:43:47.814  1036  1394 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=138955  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,07-28 09:43:47.815  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=138955  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:43:47.816  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:93418] from screen [on:0 period:813012584] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-28 09:43:47.817  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:813012585] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-28 09:43:47.817  1036  1394 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-28 09:43:47.822  1036  1407 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-28 09:43:47.822  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.822  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.822  1036  1394 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.823  1036  1394 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.823  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.824  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.824  1036  1407 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 09:43:47.824  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=128,0,0
07-28 09:43:47.825  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=128,0,0
07-28 09:43:47.825  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-28 09:43:47.825  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,07-28 09:43:47.826  1036  1394 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-28 09:43:47.826  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 09:43:47.827  1036  1394 D WifiNative-wlan0: SET ps 0: returned true
07-28 09:43:47.827  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-28 09:43:47.827  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 09:43:47.828  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 09:43:47.828  1036  1392 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e9e46ee target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.828  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e9e46ee target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.828  1036  7102 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.828  1036  7102 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-28 09:43:47.829  1036  1394 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,07-28 09:43:47.829  1036  1394 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 09:43:47.829  1036  1394 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 09:43:47.832   316   896 D CommandListener: Setting iface cfg
07-28 09:43:47.832   316   896 D CommandListener: Trying to bring up wlan0
07-28 09:43:47.833  1036  1394 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 09:43:47.834  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.835  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.835  1036  1394 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.835  1036  1394 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.836  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.836  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:47.836  1036  1407 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 09:43:47.837  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 09:43:47.837  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 09:43:47.837  7076  7076 I art     : Almond Protected OAT
07-28 09:43:47.837  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.838  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.838  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 09:43:47.838  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 09:43:47.838  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 09:43:47.838  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 09:43:47.838  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-28 09:43:47.839  1036  1394 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-28 09:43:47.839  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 09:43:47.849  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:43:47.849  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,07-28 09:43:47.850  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.854  1036  1394 D WifiNative-wlan0: SET ps 1: returned true
07-28 09:43:47.855  1036  1407 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-28 09:43:47.855  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 09:43:47.856  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 09:43:47.856  1036  1394 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 09:43:47.856  1036  1407 D ConnectivityService: ignoring duplicate network state non-change
07-28 09:43:47.860  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.860  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:47.860  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.860  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.860  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 09:43:47.860  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.861  1036  1407 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 09:43:47.862  1036  1407 D ConnectivityService: Adding iface wlan0 to network 101
07-28 09:43:47.863  1036  1394 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 09:43:47.865  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.866  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.866  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 09:43:47.866  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 09:43:47.870  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.870  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.870  1036  1392 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.870  1978  1978 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-28 09:43:47.872  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.872  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.873  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 09:43:47.874  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,07-28 09:43:47.879  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.879  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:47.879  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 09:43:47.879  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:47.879  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 09:43:47.882  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.884  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.884  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 09:43:47.884  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.888  1036  1407 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 09:43:47.888  1036  1407 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-28 09:43:47.889  1036  1407 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-28 09:43:47.890   316   896 E Netd    : netlink response contains error (File exists)
07-28 09:43:47.890  1036  1407 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-28 09:43:47.890  1036  1407 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 09:43:47.890  1036  1407 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-28 09:43:47.890  7076  7076 D WeatherApplication: removeAccount
07-28 09:43:47.890  1036  1407 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-28 09:43:47.891  7076  7076 D WeatherApplication: Account.length = 0
07-28 09:43:47.891  7076  7076 E WeatherApplication: OPERATOR:OPEN
07-28 09:43:47.892  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:47.892  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 09:43:47.892  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.893  1036  1407 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 09:43:47.894  1036  1407 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-28 09:43:47.894  1036  1407 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-28 09:43:47.894  1036  1407 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 09:43:47.894  1036  1407 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:43:47.894  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.894  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 09:43:47.894  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:47.894  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 09:43:47.894  1036  1407 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:43:47.894  1036  1407 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,07-28 09:43:47.894  1036  1407 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:47.894  1036  1407 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 09:43:47.894  1036  1407 D ConnectivityService: currentScore = 0, newScore = 20
07-28 09:43:47.894  1036  1407 D ConnectivityService:    accepting network in place of null
07-28 09:43:47.894  1036  1407 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:47.895  1036  1407 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 09:43:47.895  1036  1407 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 09:43:47.895  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 09:43:47.896  1036  1394 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:47.896  1036  1394 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:43:47.897  7076  7076 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:47
07-28 09:43:47.897  1879  1879 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:47.898  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 09:43:47.898  1036  1407 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:47.898  1036  1407 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 09:43:47.898   316  7110 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-28 09:43:47.899  1036  1407 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-28 09:43:47.900  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 09:43:47.901  1036  1407 D ConnectivityService: validation of new default Network = false
07-28 09:43:47.901  1036  1407 D Co,nnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 09:43:47.901  1036  1407 D DSQN    : enableDataServiceNotify 
07-28 09:43:47.901  1036  1407 D DSQN    : start dsqn bin
07-28 09:43:47.901  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 09:43:47.901  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 09:43:47.901  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 09:43:47.902  7076  7076 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 09:43:47.902  7076  7076 D Weather.Utils: 2 : All the weather widget is gone.
07-28 09:43:47.905  1036  1407 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 09:43:47.905  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:47.905  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 09:43:47.906  7076  7076 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 09:43:47.891  7111  7111 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:47.891  7111  7111 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:47.908  1036  1407 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:43:47.909  1036  1391 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-28 09:43:47.909  7076  7076 D WeatherAncestor: connectivity changed - connection : true
07-28 09:43:47.909  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-28 09:43:47.909  7076  7076 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-28 09:43:47.918  7111  7111 E DSQN    : DSQN ssw
,07-28 09:43:47.924  7076  7076 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,07-28 09:43:47.924  7076  7076 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 09:43:47.925  7076  7076 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
07-28 09:43:47.928  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 09:43:47.929  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:47.929  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 09:43:47.937  1843  7116 I CheckinService: active receiver: enabled
07-28 09:43:47.940  7076  7076 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 09:43:47.940  7076  7076 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:47
07-28 09:43:47.945  1843  7116 I CheckinService: Preparing to send checkin request
07-28 09:43:47.945  1843  7116 I EventLogService: Accumulating logs since 1469691746207
07-28 09:43:47.960  1036  1394 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 09:43:47.961  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 09:43:47.961  1036  1394 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 09:43:47.961  1036  1394 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 09:43:47.961  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-28 09:43:47.961  1036  1394 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,07-28 09:43:47.981  1036  1950 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7118 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 09:43:47.982  1036  1950 I ActivityManager: Killing 6644:com.lge.bnr/1000 (adj 15): empty #17
,07-28 09:43:47.995   346   346 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 262us total 12.697ms
07-28 09:43:48.009   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 862us total 12.449ms
,07-28 09:43:48.021   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 11.722ms
,07-28 09:43:48.030  1036  7102 D DhcpStateMachine: DHCPV4 request on wlan0
07-28 09:43:48.031  1036  7102 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 09:43:48.031  1036  7102 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-28 09:43:48.021  7135  7135 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:48.021  7135  7135 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 09:43:48.041  7135  7135 I dhcpcd  : version 5.5.6 starting
07-28 09:43:48.043  7135  7135 E dhcpcd  : get_duid: m
07-28 09:43:48.043  7135  7135 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 09:43:48.043  7135  7135 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-28 09:43:48.048  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6644/cgroup.procs: No such file or directory
07-28 09:43:48.049  1843  7116 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,07-28 09:43:48.102  7135  7135 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 09:43:48.102  7135  7135 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 09:43:48.102  7135  7135 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 09:43:48.103  7135  7135 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-28 09:43:48.103  7135  7135 D dhcpcd  : wlan0: sending REQUEST (xid 0xe2f0e155), next in 3.80 seconds
,07-28 09:43:48.152   316  7110 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-28 09:43:48.155  1036  1577 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7144 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-28 09:43:48.161  7135  7135 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
07-28 09:43:48.163   278   351 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 09:43:48.163   278   351 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 09:43:48.163   278   351 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 09:43:48.163  7118  7143 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-28 09:43:48.164   278   351 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 09:43:48.164   278   351 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 09:43:48.164   278   351 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 09:43:48.165  7118  7143 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 09:43:48.171   278   351 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 09:43:48.171   278   351 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-28 09:43:48.171   278   351 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 09:43:48.171  7118  7155 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-28 09:43:48.172  7135  7135 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 09:43:48.172  7135  7135 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-28 09:43:48.172   278   351 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-28 09:43:48.172   278   351 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-28 09:43:48.173   278   351 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 09:43:48.173  7135  7135 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 09:43:48.173  7135  7135 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 09:43:48.173  7135  7135 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 09:43:48.173  7118  7155 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-28 09:43:48.173  7135  7135 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 09:43:48.173  7135  7135 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 09:43:48.173  7135  7135 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-28 09:43:48.184   316  7110 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-28 09:43:48.214   316   895 D LGDataListener: argv[0]=dsqncommand
07-28 09:43:48.214   316   895 D LGDataListener: argv[1]=wlan0
07-28 09:43:48.214   316   895 D LGDataListener: argv[2]=1
07-28 09:43:48.214   316   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,07-28 09:43:48.215  1036  1096 D DSQN    : DSQM DsqnNotification wlan0  1
07-28 09:43:48.215  1036  1096 D DSQN    : start to monitor internet connection
07-28 09:43:48.228  7144  7144 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-28 09:43:48.228  7144  7144 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-28 09:43:48.240  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 07:43:48 GMT], X-Android-Received-Millis=[1469691828240], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469691828213]}
,07-28 09:43:48.240  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 09:43:48.240  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-28 09:43:48.240  1036  1407 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-28 09:43:48.241  1036  1407 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-28 09:43:48.241  1036  1407 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:43:48.241  1036  1407 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:43:48.241  1036  1407 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 09:43:48.241  1036  1407 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-28 09:43:48.241  1036  1407 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-28 09:43:48.241  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:48.241  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:43:48.241  1036  1407 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:43:48.242  1036  1407 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:48.242  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-28 09:43:48.242  1036  1394 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:48.242  1036  1394 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:43:48.242  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 09:43:48.244  1879  1879 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:48.244  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 09:43:48.254  7144  7144 I MultiDex: VM with version 2.1.0 has multidex support
07-28 09:43:48.254  7144  7144 I MultiDex: install
07-28 09:43:48.254  7144  7144 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-28 09:43:48.262  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 09:43:48.263  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:48.263  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:48.268  7144  7144 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-28 09:43:48.375  7118  7118 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-28 09:43:48.383  7118  7118 I LibraryLoader: Loading: webviewchromium
07-28 09:43:48.386  7118  7118 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9535-9539)
07-28 09:43:48.386  7118  7118 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 09:43:48.394  7118  7118 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {320432bc}
,07-28 09:43:48.400  7118  7118 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 09:43:48.401  7118  7118 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 09:43:48.419  7118  7118 I BrowserStartupController: Initializing chromium process, renderers=0
07-28 09:43:48.420  7118  7118 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 09:43:48.433  1036  7102 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-28 09:43:48.434  1036  7102 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-28 09:43:48.434  1036  7102 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 09:43:48.434  1036  7102 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-28 09:43:48.434  1036  7102 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-28 09:43:48.434  1036  7102 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 09:43:48.435  1036  7102 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-28 09:43:48.435  1036  7102 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-28 09:43:48.435  1036  7102 D DhcpStateMachine: RunningState
07-28 09:43:48.442   320  2203 V AudioPolicyService: registerClient() client 0xb14271c0, uid 10093
07-28 09:43:48.444  7118  7207 W AudioManagerAndroid: Requires BLUETOOTH permission
07-28 09:43:48.445  7118  7118 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-28 09:43:48.446  7118  7118 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-28 09:43:48.447  7118  7118 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,07-28 09:43:48.463  7118  7118 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 09:43:48.463  7118  7118 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 09:43:48.463  7118  7118 I Adreno-EGL: Build Date: 12/12/14 금
07-28 09:43:48.463  7118  7118 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 09:43:48.463  7118  7118 I Adreno-EGL: Remote Branch: 
07-28 09:43:48.463  7118  7118 I Adreno-EGL: Local Patches: 
07-28 09:43:48.463  7118  7118 I Adreno-EGL: Reconstruct Branch: 
,07-28 09:43:48.488  7144  7164 D LgDataFeature: LgDataFeature() Constructor: none
,07-28 09:43:48.488  7144  7164 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:43:48.555  7216  7216 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-28 09:43:48.560  7118  7118 I NSApplication: Starting up...
07-28 09:43:48.606  7216  7216 I dex2oat : dex2oat took 50.812ms (threads: 4)
,07-28 09:43:48.609  1036  1765 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7226 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-28 09:43:48.609  1036  1765 I ActivityManager: Killing 6037:com.android.vending/u0a44 (adj 15): empty #17
07-28 09:43:48.618  7144  7164 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 09:43:48.618  7144  7164 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 09:43:48.618  7144  7164 I Adreno-EGL: Build Date: 12/12/14 금
07-28 09:43:48.618  7144  7164 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 09:43:48.618  7144  7164 I Adreno-EGL: Remote Branch: 
07-28 09:43:48.618  7144  7164 I Adreno-EGL: Local Patches: 
07-28 09:43:48.618  7144  7164 I Adreno-EGL: Reconstruct Branch: 
07-28 09:43:48.672  1036  1951 W libprocessgroup: failed to open /acct/uid_10044/pid_6037/cgroup.procs: No such file or directory
,07-28 09:43:48.707  7144  7164 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 09:43:48.707  7144  7164 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 09:43:48.707  7144  7164 I Adreno-EGL: Build Date: 12/12/14 금
07-28 09:43:48.707  7144  7164 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 09:43:48.707  7144  7164 I Adreno-EGL: Remote Branch: 
07-28 09:43:48.707  7144  7164 I Adreno-EGL: Local Patches: 
07-28 09:43:48.707  7144  7164 I Adreno-EGL: Reconstruct Branch: 
,07-28 09:43:48.726  7226  7226 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 09:43:48.785  7144  7164 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-28 09:43:48.785  7144  7164 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-28 09:43:48.785  7144  7164 I Adreno-EGL: Build Date: 12/12/14 금
07-28 09:43:48.785  7144  7164 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-28 09:43:48.785  7144  7164 I Adreno-EGL: Remote Branch: 
07-28 09:43:48.785  7144  7164 I Adreno-EGL: Local Patches: 
07-28 09:43:48.785  7144  7164 I Adreno-EGL: Reconstruct Branch: 
,07-28 09:43:48.892  1036  1996 I art     : Explicit concurrent mark sweep GC freed 100024(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.736ms total 92.997ms
,07-28 09:43:48.906  1036  1407 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
07-28 09:43:48.945  1036  1765 D WifiServiceImplEx: setWifiEnabled: false pid=6576, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 09:43:48.945  1036  1765 D WifiService: setWifiEnabled: false pid=6576, uid=10118
07-28 09:43:48.945  1036  1765 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 09:43:48.953  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 09:43:48.953  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 09:43:48.953  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 09:43:48.953  1036  1394 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:48.953  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:48.954  1036  1394 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:48.954  1036  1394 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:48.954  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-28 09:43:48.954  1036  1394 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 09:43:48.954  1036  1394 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 09:43:48.954  1036  1394 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 09:43:48.955  1036  1394 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 09:43:48.955  1036  1394 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,07-28 09:43:48.958  1036  1394 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 09:43:48.958  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 09:43:48.958  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.958  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.958  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 09:43:48.958  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 09:43:48.958  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 1
,07-28 09:43:48.960  1036  1394 D WifiNative-wlan0: SET ps 1: returned true
07-28 09:43:48.961  1036  7102 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.961   316   896 D CommandListener: Clearing all IP addresses on wlan0
07-28 09:43:48.978  1036  1407 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-28 09:43:48.978  1036  1407 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,07-28 09:43:48.985  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:48.985  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:48.986  1978  1978 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-28 09:43:48.986  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-28 09:43:48.986  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:48.986  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:48.987  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 09:43:48.987  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:48.989  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-28 09:43:48.991  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:48.991  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:48.991  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 09:43:48.991  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.991  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.991  1036  1392 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@24e4e203
07-28 09:43:48.991  1036  1394 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:48.992  1036  1392 D LGWifiP2pService: P2pDisablingState
07-28 09:43:48.992  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 09:43:48.992  1036  1392 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.992  1036  1392 D LGWifiP2pService: p2p socket connection lost
07-28 09:43:48.992  1036  1392 D LGWifiP2pService: P2pDisabledState
07-28 09:43:48.992  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:48.992  1036  1394 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:48.992  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:48.993  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:43:48.993  1036  1394 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 09:43:48.993  1036  1394 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-28 09:43:48.993  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 09:43:48.993  1036  1392 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.993  1036  1392 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.993  6998  6998 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 09:43:48.993  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 09:43:48.994  1036  1558 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.994  1036  1036 D RttService: SCAN_AVAILABLE : 1
07-28 09:43:48.994  1036  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:48.995  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,07-28 09:43:48.995  1978  1978 D WfdsService: WifiP2pState is changed : false
07-28 09:43:48.995  1978  2356 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-28 09:43:48.995  1978  2356 D WfdsService: Set the WFDS Monitor: false
,07-28 09:43:48.996  1978  2356 D WfdsMonitor: WFDS Monitor is stopped
07-28 09:43:48.996  1978  2356 D WfdsService: STATE : WfdsDisabledState - enter
07-28 09:43:48.996  1978  7024 D CtrlSupplicant: Received on exit socket, terminate
07-28 09:43:48.996  1978  7024 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-28 09:43:48.996  1978  7024 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-28 09:43:48.996  1978  7024 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-28 09:43:48.997  1978  2356 W WfdsService: DefaultState - msg [9445378] is not handled
07-28 09:43:48.997  1978  2358 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-28 09:43:48.997  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 09:43:48.997  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 09:43:48.998  1036  1394 D WifiNative-wlan0: SET ps 1: returned true
07-28 09:43:49.004   316   896 D CommandListener: Clearing all IP addresses on wlan0
07-28 09:43:49.004  1036  1407 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-28 09:43:49.004  1036  1407 D DSQN    : disableDataServiceNotify
07-28 09:43:49.004  1036  1407 D DSQN    : stop dsqn bin
07-28 09:43:49.005  1036  1394 D WifiNative-p2p0: doBoolean: TERMINATE
07-28 09:43:49.006  1036  1036 D WifiHS20: hidePasspointNotification off =false
,07-28 09:43:49.008  1036  1407 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-28 09:43:49.008  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:49.008  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:43:49.009  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:49.009  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:49.009  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 09:43:49.009  1036  1407 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:43:49.009  1036  1407 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-28 09:43:49.009  1036  1394 D WifiNative-p2p0: TERMINATE: returned true
07-28 09:43:49.009  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:49.009  1036  1394 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 09:43:49.009  1036  1394 E WifiStateMachine: useWiFiOffloading() : false
07-28 09:43:49.009  1036  1394 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 09:43:49.009  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:49.009  1036  7093 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 09:43:49.009  1036  1407 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-28 09:43:49.009  1036  1407 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 09:43:49.010  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 09:43:49.010  1036  1407 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:49.010  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 09:43:49.010  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 09:43:49.010  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-28 09:43:49.012  1036  1391 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 09:43:49.012  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:49.012  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-28 09:43:49.012  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:49.012  1036  1036 D WifiServerServiceEx,t: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:43:49.012  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-28 09:43:49.012  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 09:43:49.012  1036  1407 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:49.012  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-28 09:43:49.012  1036  1407 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:49.012  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 09:43:49.012  1036  1407 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:49.012  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 09:43:49.013  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 09:43:49.013  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 09:43:49.013  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 09:43:49.013  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 09:43:49.013  1036  1394 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:49.013  1036  1394 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:43:49.013  1036  1391 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-28 09:43:49.014  1036  1407 D NetworkManagementService: Removing idletimer
07-28 09:43:49.014  1036  1407 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:49.014  1036  1407 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-28 09:43:49.014  1879  1879 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:43:49.014  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 09:43:49.014  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:49.014  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:49.014  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:49.014  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:49.014  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:49.014  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:49.014  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:49.014  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:49.014  6576  6576 V io.jxco,re.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:43:49.014  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:49.014  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:49.015  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:49.020  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:49.020  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:49.020  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:49.020  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:49.020  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:49.020  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:49.020  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:49.020  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:49.020  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:49.020  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:49.020  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:49.020  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 09:43:49.020  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:43:49.021  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:49.022  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:49.039  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 09:43:49.039  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:49.040  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 09:43:49.054  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 09:43:49.055  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:49.055  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:49.069  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-28 09:43:49.069  6387  6417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-28 09:43:49.079  2268  2268 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:49.088  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 09:43:49.088  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:49.088  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 09:43:49.088  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-28 09:43:49.090  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
07-28 09:43:49.092  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3474741d
07-28 09:43:49.092  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 09:43:49.092  6945  6945 D AppUp4:CustFacade: isPhone : true
07-28 09:43:49.092  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
07-28 09:43:49.093  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 09:43:49.095  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:49.095  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 09:43:49.096  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:49.097  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:49.099   316  7260 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-28 09:43:49.099  1036  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-28 09:43:49.100  1843  7116 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-28 09:43:49.101  4298  7258 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 09:43:49.102  6969  6969 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 09:43:49.105  4298  7261 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:49.105  4298  7261 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 09:43:49.108  6998  6998 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 09:43:49.108  6998  6998 I wpa_supplicant: monitor socket send errors count : 1
07-28 09:43:49.108  6998  6998 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1978-4\x00 that cannot receive messages
07-28 09:43:49.109  1036  7008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-28 09:43:49.109  1036  7008 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 09:43:49.110  1843  7116 I CheckinService: active receiver: disabled
,07-28 09:43:49.126  6969  7263 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:49.129  6998  6998 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 09:43:49.129  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-28 09:43:49.129  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 09:43:49.129  1036  7008 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 09:43:49.130  1036  7008 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-28 09:43:49.130  1036  1394 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=140270
07-28 09:43:49.130  6998  6998 W wpa_supplicant: USIM:  scard_deinit function
07-28 09:43:49.130  1036  1394 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=140271
07-28 09:43:49.131  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:43:49.132  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:43:49.132  1036  1098 D Tethering: InitialState.processMessage what=4
07-28 09:43:49.132  1036  1394 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=140272  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-28 09:43:49.132  1036  1394 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=140273  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,07-28 09:43:49.133  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 09:43:49.133  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:49.133  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 09:43:49.134  6848  7266 W FormManager: Network not available. Please check & try again.
07-28 09:43:49.134  1036  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 09:43:49.137  1036  1394 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:49.137  1036  1394 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:43:49.138  7014  7014 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 09:43:49.138  7014  7014 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 09:43:49.143  6848  7267 V FormManager: Network unavailable.
,07-28 09:43:49.147  7076  7076 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:49
07-28 09:43:49.148  6848  7267 V FormManager: Network unavailable.
07-28 09:43:49.148  7076  7076 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 09:43:49.149  7076  7076 D Weather.Utils: 2 : All the weather widget is gone.
07-28 09:43:49.149  7076  7076 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 09:43:49.149  7076  7076 D WeatherAncestor: connectivity changed - connection : true
07-28 09:43:49.149  7076  7076 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@19d32863
07-28 09:43:49.149  7076  7076 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 09:43:49.149  7076  7076 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 09:43:49.150  7076  7076 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 09:43:49.150  7076  7076 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 09:43:49.150  7076  7076 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:49
,07-28 09:43:49.166  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 09:43:49.166  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 09:43:49.166  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 09:43:49.166  6761  6761 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 09:43:49.167  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-28 09:43:49.167  6761  6761 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 09:43:49.167  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[],
07-28 09:43:49.167  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 09:43:49.167  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 09:43:49.167  6761  6761 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 09:43:49.167  6761  6761 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 09:43:49.172  1036  7102 D DhcpStateMachine: StoppedState
07-28 09:43:49.172  1036  7102 D DhcpStateMachine: StoppedState{ when=-175ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:43:49.173  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:49.173  1036  1394 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-28 09:43:49.173  1036  1394 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-28 09:43:49.175  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 09:43:49.177  6848  7271 W FormManager: Network not available. Please check & try again.
07-28 09:43:49.178  6998  6998 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 09:43:49.179  1036  7008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-28 09:43:49.179  1036  7008 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
07-28 09:43:49.179  1036  7008 D WifiMonitor: Disconnecting from the supplicant, no more events
07-28 09:43:49.179  1036  1394 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,07-28 09:43:49.182  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.185  6848  7272 V FormManager: Network unavailable.
07-28 09:43:49.188  6848  7272 V FormManager: Network unavailable.
07-28 09:43:49.196  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 09:43:49.199  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 09:43:49.203  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.207  6848  7274 W FormManager: Network not available. Please check & try again.
07-28 09:43:49.209  6848  7275 V FormManager: Network unavailable.
,07-28 09:43:49.211  6848  7275 V FormManager: Network unavailable.
,07-28 09:43:49.214  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 09:43:49.214  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 09:43:49.217  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:49.219  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:49.223  4298  7276 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 09:43:49.225  4298  7277 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 09:43:49.225  4298  7277 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 09:43:49.250  1036  2041 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7278 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
07-28 09:43:49.281  1036  1394 D WifiOffDelayIfNotUsed: stopMonitoring
,07-28 09:43:49.281  1036  1394 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 09:43:49.281  1036  1394 E WifiStateMachine: useWiFiOffloading() : false
07-28 09:43:49.281  1036  1394 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 09:43:49.281  1978  1978 D WfdsService: Supplicant Connection state is changed : false
07-28 09:43:49.282  1978  2356 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-28 09:43:49.282  1978  2356 D WfdsService: Set the WFDS Monitor: false
07-28 09:43:49.282  1978  2356 D WfdsMonitor: WFDS Monitor is stopped
07-28 09:43:49.285  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-28 09:43:49.288  2511  2511 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:49.289  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:43:49.290  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-28 09:43:49.291  1036  1398 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-28 09:43:49.292  1036  1398 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-28 09:43:49.292  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:49.292  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:49.292  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:49.292  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:49.292  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:49.292  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:49.292  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:49.292  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:49.292  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:49.294  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:49.396  7278  7278 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 09:43:49.397  7278  7278 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-28 09:43:49.409  7278  7278 V [BNRBootReceiver]: Boot Receiver Return
,07-28 09:43:49.410  7278  7278 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-28 09:43:49.416  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:43:49.430  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.442  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.468  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 09:43:49.468  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:49.472  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 09:43:49.483  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-28 09:43:49.491  6761  6761 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,07-28 09:43:49.498  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:43:49.508  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.519  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.530  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 09:43:49.531  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:49.535  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 09:43:49.539  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:43:49.551  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.563  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.576  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 09:43:49.577  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:49.578  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 09:43:49.585  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:43:49.597  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.608  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.613  6680  6916 D UEI.SmartControl: Internal timer expired: 2
07-28 09:43:49.613  6680  6916 D UEI.SmartControl: unbind internal service
,07-28 09:43:49.622  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:49.623  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:49.623  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 09:43:49.631  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:43:49.646  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.656  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.668  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:49.668  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:49.669  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 09:43:49.677  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:43:49.691  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.697  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.702  6680  6913 D serial_port: close(fd = 24)
07-28 09:43:49.706  6680  6913 I UEI.SmartControl: Serial port is closed.
,07-28 09:43:49.708  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 09:43:49.709  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:49.709  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 09:43:49.714  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:43:49.724  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.733  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.744  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:49.744  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:49.745  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 09:43:49.763  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:43:49.792  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.806  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.822  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-28 09:43:49.822  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 09:43:49.832  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 09:43:49.842  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:43:49.858  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.870  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.883  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:49.884  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:49.885  6811  6811 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 09:43:49.892  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:43:49.897  6781  6781 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-28 09:43:49.906  1036  1400 D WifiService: New client listening to asynchronous messages
,07-28 09:43:49.906  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:49.910  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.917  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null,
07-28 09:43:49.926  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:49.927  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 09:43:49.928  6811  6811 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 09:43:49.929  6811  6811 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 09:43:49.930  6811  6811 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 09:43:49.936  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:43:49.941  6781  6781 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 09:43:49.943  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 09:43:49.948  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:49.956  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:49.966  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:49.966  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:49.968  6811  6811 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 09:43:49.969  6811  6811 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 09:43:49.969  6811  6811 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 09:43:49.974  1036  1577 I ActivityManager: Killing 6735:com.lge.lifetracker/u0a37 (adj 15): empty #17
,07-28 09:43:50.052  1036  1996 W libprocessgroup: failed to open /acct/uid_10037/pid_6735/cgroup.procs: No such file or directory
,07-28 09:43:50.062  2268  2268 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-28 09:43:50.084  2268  2268 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-28 09:43:50.086  2268  2268 D c       : Getting all permits...
,07-28 09:43:50.086  2268  2268 D a       : Opening database...
07-28 09:43:50.099  2268  2268 D a       : Opening database auth.proximity.permit_store...
07-28 09:43:50.100  2268  2268 D a       : Closing database...
07-28 09:43:50.115  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:43:50.122  6781  6781 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 09:43:50.122  6781  6781 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 09:43:50.123  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:50.125  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:50.132  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:50.139  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:50.140  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:50.142  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 09:43:50.146  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:43:50.150  6781  6781 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 09:43:50.150  6781  6781 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 09:43:50.150  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:50.155  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 09:43:50.161  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 09:43:50.168  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:50.169  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:43:50.170  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 09:43:50.177  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:43:50.184  6781  6781 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-28 09:43:50.184  6781  6781 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 09:43:50.184  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:50.189  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:43:50.199  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:50.209  6811  6811 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:43:50.210  6811  6811 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-28 09:43:50.212  6811  6811 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 09:43:50.230  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-28 09:43:50.235  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 09:43:50.242  6848  7303 W FormManager: Network not available. Please check & try again.
,07-28 09:43:50.248  6848  7304 V FormManager: Network unavailable.
07-28 09:43:50.252  6848  7304 V FormManager: Network unavailable.
,07-28 09:43:50.258  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:50.284  2268  2268 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-28 09:43:50.308  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-28 09:43:50.308  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 09:43:50.313  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:50.315  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:50.320  4298  7305 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 09:43:50.324  4298  7306 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 09:43:50.324  4298  7306 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 09:43:50.329  6781  6781 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-28 09:43:50.329  6781  6781 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-28 09:43:50.329  6781  6781 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:43:50.334  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 09:43:50.340  6848  7308 W FormManager: Network not available. Please check & try again.
,07-28 09:43:50.347  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:43:50.358  6848  7309 V FormManager: Network unavailable.
,07-28 09:43:50.362  6848  7309 V FormManager: Network unavailable.
,07-28 09:43:50.825  1036  1394 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:813015592] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 09:43:50.827  1036  1394 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:813015595] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-28 09:43:50.902  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:50.919  1036  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:50.927  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:50.931  1036  1098 D Tethering: MasterInitialState.processMessage what=3
07-28 09:43:50.933  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:50.938  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 09:43:50.940  6387  6417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 09:43:50.946  5735  5735 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-28 09:43:50.977  2268  2268 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:50.996  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 09:43:50.996  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:50.996  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 09:43:50.996  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-28 09:43:51.003  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
07-28 09:43:51.007  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3474741d
07-28 09:43:51.007  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 09:43:51.007  6945  6945 D AppUp4:CustFacade: isPhone : true
07-28 09:43:51.007  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
07-28 09:43:51.008  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 09:43:51.012  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:51.012  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 09:43:51.014  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-28 09:43:51.020  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:51.028  6969  6969 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 09:43:51.051  4298  7318 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-28 09:43:51.073  1036  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 09:43:51.078  6969  7317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:51.086  6848  7325 W FormManager: Network not available. Please check & try again.
,07-28 09:43:51.087  4298  7319 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:51.087  4298  7319 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 09:43:51.090  6848  7326 V FormManager: Network unavailable.
07-28 09:43:51.092  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 09:43:51.092  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:51.092  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = true
07-28 09:43:51.092  3426  3426 D PhoneState: setPdpRejectCasuse : false
07-28 09:43:51.095  6848  7326 V FormManager: Network unavailable.
07-28 09:43:51.095  7014  7014 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 09:43:51.096  7014  7014 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 09:43:51.105  7076  7076 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:51
,07-28 09:43:51.109  7076  7076 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,07-28 09:43:51.109  7076  7076 D Weather.Utils: 2 : All the weather widget is gone.
07-28 09:43:51.109  7076  7076 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,07-28 09:43:51.109  7076  7076 D WeatherAncestor: connectivity changed - connection : true
07-28 09:43:51.109  7076  7076 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@19d32863
07-28 09:43:51.110  7076  7076 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 09:43:51.110  7076  7076 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 09:43:51.110  7076  7076 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 09:43:51.110  7076  7076 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 09:43:51.111  7076  7076 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:51
07-28 09:43:51.955  1036  2041 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:51.956  1036  2041 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-28 09:43:51.982  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 09:43:51.982  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 09:43:51.982  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 09:43:51.983  1036  1098 D BluetoothManagerService: Message: 1
07-28 09:43:51.983  1036  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-28 09:43:52.010  1036  1098 D BluetoothManagerService: Message: 20
07-28 09:43:52.010  1036  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13443b4f:true
,07-28 09:43:52.013  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.019  1036  1098 D Tethering: MasterInitialState.processMessage what=3
07-28 09:43:52.019  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.027  6894  6894 D BluetoothAdapterState: make
,07-28 09:43:52.034  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:52.035  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:52.038  1036  1098 D Tethering: MasterInitialState.processMessage what=3
07-28 09:43:52.042  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:52.046  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:52.055  6894  6894 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 09:43:52.055  6894  6894 I bluedroid-qcom: init
,07-28 09:43:52.059  6894  7349 I BluetoothAdapterState: Entering OffState
07-28 09:43:52.060  6894  6894 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 09:43:52.060  6894  6894 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 09:43:52.060  6894  6894 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 09:43:52.060  6894  6894 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 09:43:52.060  6894  6894 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-28 09:43:52.062  6894  6894 I bluedroid-qcom: get_profile_interface socket
07-28 09:43:52.062  6894  6894 I bluedroid-qcom: get_profile_interface map_client
07-28 09:43:52.063  6894  7353 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 09:43:52.066  6894  7353 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 09:43:52.051  7352  7352 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 09:43:52.061  7352  7352 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:52.078  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-28 09:43:52.081  6387  6417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 09:43:52.086  7352  7352 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 09:43:52.086  7352  7352 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 09:43:52.086  7352  7352 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-28 09:43:52.090  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 09:43:52.090  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 09:43:52.091  5735  5735 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 09:43:52.092  7352  7352 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-28 09:43:52.101  6894  7353 D BluetoothAdapterProperties: Name is: G3
,07-28 09:43:52.121  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-28 09:43:52.121  1036  1098 D BluetoothManagerService: Message: 40
07-28 09:43:52.121  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 09:43:52.122  6894  6909 I bluedroid-qcom: config_hci_snoop_log
07-28 09:43:52.124  1036  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks,
07-28 09:43:52.124  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-28 09:43:52.131  7352  7352 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 09:43:52.131  7352  7352 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-28 09:43:52.134  6894  7349 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 09:43:52.134  6894  7349 D BluetoothAdapterProperties: Setting state to 11
07-28 09:43:52.135  6894  7349 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 09:43:52.136  6894  7349 I LGBluetoothServiceJni: classInitNative: succeeds
07-28 09:43:52.142  6894  7349 D BluetoothBondStateMachine: make
07-28 09:43:52.142  1036  1098 D BluetoothManagerService: Message: 60
07-28 09:43:52.142  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 09:43:52.142  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-28 09:43:52.147  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 09:43:52.147  1036  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.148  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 09:43:52.151  6761  6761 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-28 09:43:52.152  5735  5735 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-28 09:43:52.155  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:52.156  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:52.161  6894  7349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:52.161  6894  7349 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 09:43:52.161  6894  7349 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:52.161  6894  7349 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 09:43:52.161  6894  7349 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,07-28 09:43:52.168  6894  6894 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 09:43:52.169  6894  6894 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:52.169  6894  6894 V BluetoothPbapReceiver: ***********state = 11
07-28 09:43:52.171  6894  7364 I BluetoothBondStateMachine: StableState(): Entering Off State
07-28 09:43:52.172  6894  7349 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:43:52.174  2268  2268 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 09:43:52.215  1036  2095 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7374 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-28 09:43:52.223  6894  6894 D HeadsetService: Received start request. Starting profile...
07-28 09:43:52.224  6894  6894 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 09:43:52.224  6894  6894 D LGBluetoothHfpAdapter: Version 1.6
07-28 09:43:52.225  6894  7349 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:43:52.226  6894  6894 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 09:43:52.227  6894  6894 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 09:43:52.227  6894  6894 D HeadsetStateMachine: make
07-28 09:43:52.230  1036  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:52.238  6894  7349 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:43:52.240  1036  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:43:52.240  1036  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 09:43:52.247  2268  2268 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.250  6894  7349 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:43:52.254  6894  7349 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:43:52.256  6894  6894 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:52.256  6894  6894 D LgDataFeature: LgDataFeature() Constructor Done, null
07-28 09:43:52.258  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 09:43:52.258  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.258  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 09:43:52.258  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-28 09:43:52.262  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
07-28 09:43:52.267  6894  6894 D HeadsetStateMachine: max_hf_connections = 1
07-28 09:43:52.267  6894  6894 I bluedroid-qcom: get_profile_interface handsfree
07-28 09:43:52.268  6894  6894 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 09:43:52.269   320  1406 V AudioPolicyService: registerClient() client 0xb14b7a20, uid 1002
07-28 09:43:52.269  6894  7349 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:43:52.269   320  3982 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 09:43:52.269   320  3982 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 09:43:52.269   320  3982 V AudioPolicyManagerEx: getOutput() returns output 2
,07-28 09:43:52.269  6894  6894 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 09:43:52.269   320  2203 V AudioFlinger: registerClient() client 0xb55815f8, pid 6894
07-28 09:43:52.270   320  1399 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:43:52.270   320  1399 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:43:52.270  6894  6894 V ToneGenerator: Create Track: 0xb4928a80
07-28 09:43:52.270  1605  3121 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:43:52.270  1605  3121 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:43:52.270  6894  6894 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 09:43:52.270  6894  6894 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 09:43:52.270  1879  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:43:52.270   320  1405 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 09:43:52.270  1879  1894 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:43:52.270   320  1405 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 09:43:52.270   320  1405 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 09:43:52.270   320  1405 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 09:43:52.270   320  1401 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:43:52.270  6894  6894 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 09:43:52.270   320  1401 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:43:52.270  6894  6909 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:43:52.270  6894  6909 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 09:43:52.270  1605  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:43:52.270  1605  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:43:52.270  1879  2372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:43:52.270  1879  2372 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:43:52.270  6894  6909 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:43:52.270  6894  6909 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 09:43:52.270   320   320 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 09:43:52.270   320  1405 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 09:43:52.270   320  1405 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 09:43:52.270   320  1405 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 09:43:52.270   320  1405 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 09:43:52.271  6894  6894 V AudioSystem: getLatency() output 2, latency 50
07-28 09:43:52.271  6894  6894 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 09:43:52.271  6894  6894 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 09:43:52.271   320  3982 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 09:43:52.271   320  3982 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 09:43:52.271   320  3982 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 09:43:52.271   320  3982 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 09:43:52.271   320  3982 V AudioFlinger: createTrack() lSessionId: 20
07-28 09:43:52.271  1036  1765 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:,43:52.271  1036  1765 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:43:52.271  1036  1765 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:43:52.271  1036  1765 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:43:52.272  3426  3446 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:43:52.272  3426  3446 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:43:52.272  3426  3446 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:43:52.272  3426  3446 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:43:52.273  6894  6894 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 09:43:52.273   320  1406 V AudioFlinger: acquiring 20 from 6894, for 6894
07-28 09:43:52.273   320  1406 V AudioFlinger:  added new entry for 20
07-28 09:43:52.273  6894  6894 V ToneGenerator: ToneGenerator INIT OK, time: 143426
07-28 09:43:52.273  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:52.274  6894  7390 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 09:43:52.274  6894  7390 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 09:43:52.274  6894  7390 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 09:43:52.274  6894  7390 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-28 09:43:52.274   320   320 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6894
07-28 09:43:52.274  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:52.275   320   320 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-28 09:43:52.275   320   320 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 09:43:52.275   320   320 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 09:43:52.275   320   320 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 09:43:52.275   320   320 V voice   : voice_set_parameters: exit with code(0)
07-28 09:43:52.275   320   320 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-28 09:43:52.275   320   320 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 09:43:52.276   320   320 V msm8974_platform: platform_set_parameters: exit with code(0)
07-28 09:43:52.276   320   320 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 09:43:52.276   320   320 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 09:43:52.276   320   320 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-28 09:43:52.276  6894  7390 V ToneGenerator: ToneGenerator destructor
07-28 09:43:52.276  6894  7390 V ToneGenerator: stopTone
07-28 09:43:52.276  6894  7390 V ToneGenerator: Delete Track: 0xb4928a80
07-28 09:43:52.276  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3474741d
07-28 09:43:52.276  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 09:43:52.276  6945  6945 D AppUp4:CustFacade: isPhone : true
07-28 09:43:52.277  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
07-28 09:43:52.277  6894  6894 D A2dpService: Received start request. Starting profile...
07-28 09:43:52.277  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 09:43:52.277  6894  6894 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 09:43:52.278  6894  6894 V Avrcp   : make
07-28 09:43:52.278  6894  6894 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 09:43:52.278  6894  6894 I bluedroid-qcom: get_profile_interface avrcp
07-28 09:43:52.280  1036  2091 W Process : Unable to open /proc/7392/status
07-28 09:43:52.281  6894  7390 V AudioTrack: ~AudioTrack, releasing session id from 6894 on behalf of 6894
07-28 09:43:52.281   320  1405 V AudioPolicyService: AudioCommandThread() adding release output 2
07-28 09:43:52.281   320  1405 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 09:43:52.281   320  2203 V AudioFlinger: releasing 20 from 6894 for 6894
07-28 09:43:52.281   320  2203 V AudioFlinger:  decremented refcount to 0
07-28 09:43:52.281   320  2203 V AudioFlinger: purging stale effects
07-28 09:43:52.281   320  1231 V AudioPolicyService: AudioCommandThread() waking up
07-28 09:43:52.281   320  1231 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 09:43:52.281   320  1231 V AudioPolicyManager: releaseOutput() 2
07-28 09:43:52.281   320  1231 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 09:43:52.281   320  1405 V AudioFlinger: PlaybackThread::Track destructor
07-28 09:43:52.281   320  1405 V AudioFlinger: removeClient_l() pid 6894, calling pid 320
07-28 09:43:52.282  6894  7349 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:43:52.283  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.283  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 09:43:52.284  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:52.287  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:52.287  6894  6894 V AudioManager: registerRemoteController: size of Media player list: 0
07-28 09:43:52.289  6894  6894 E AudioManager: No RCC entry present to update
07-28 09:43:52.289  6894  6894 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 09:43:52.292  6894  6894 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 09:43:52.292  6969  6969 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-28 09:43:52.293  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-28 09:43:52.293  6894  6894 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-28 09:43:52.298  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 09:43:52.302  6894  7349 V LGMDMManager: Create singleton instance
07-28 09:43:52.303  6894  7349 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 09:43:52.304  4298  7394 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 09:43:52.306  4298  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:52.306  4298  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 09:43:52.340  7374  7374 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-28 09:43:52.340  7374  7374 W LG Account v2.2: No ProfileInfo entries
07-28 09:43:52.340  7374  7374 I LG Account v2.2: isEnabled: false
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]Country: EU
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]Operator: OPEN
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]Ranking support: false
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]Comfort support: false
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]Accessory: true
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]Health device: true
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]Extra Pedometer: false
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]Blood glucose device: false
07-28 09:43:52.341  7374  7374 I Feature : [Lifetracker]Device Number: 3
07-28 09:43:52.342  6848  7401 W FormManager: Network not available. Please check & try again.
07-28 09:43:52.343  6969  7399 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:52.354  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 09:43:52.354  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:52.354  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 09:43:52.359  7014  7014 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 09:43:52.360  6848  7402 V FormManager: Network unavailable.
07-28 09:43:52.360  7014  7014 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 09:43:52.361  6761  6761 D BluetoothPermissionRequest: onReceive
07-28 09:43:52.368  6848  7402 V FormManager: Network unavailable.
07-28 09:43:52.369  6761  6761 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 09:43:52.370  7076  7076 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:52
07-28 09:43:52.372  7076  7076 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 09:43:52.372  7076  7076 D Weather.Utils: 2 : All the weather widget is gone.
07-28 09:43:52.373  7076  7076 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 09:43:52.373  7076  7076 D WeatherAncestor: connectivity changed - connection : true
07-28 09:43:52.373  7076  7076 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@19d32863
,07-28 09:43:52.373  7076  7076 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,07-28 09:43:52.373  7076  7076 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 09:43:52.373  7076  7076 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 09:43:52.373  7076  7076 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 09:43:52.374  7076  7076 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:52
07-28 09:43:52.381  1036  1996 V SIM_STK : Menu title from STK is T-Mobile
07-28 09:43:52.381  1036  1996 V SIM_STK : Menu title from STK is T-Mobile
07-28 09:43:52.389  6387  6387 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-28 09:43:52.389  6387  6417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-28 09:43:52.400  2268  2268 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.405  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-28 09:43:52.405  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.405  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-28 09:43:52.405  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-28 09:43:52.406  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
,07-28 09:43:52.409  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3474741d
07-28 09:43:52.409  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 09:43:52.409  6945  6945 D AppUp4:CustFacade: isPhone : true
07-28 09:43:52.409  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
07-28 09:43:52.409  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-28 09:43:52.411  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.411  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 09:43:52.412  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:52.414  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:43:52.416  4298  7404 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 09:43:52.418  6969  6969 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-28 09:43:52.421  4298  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-28 09:43:52.421  4298  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-28 09:43:52.429  6969  7406 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:52.433  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-28 09:43:52.433  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:43:52.433  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = false
07-28 09:43:52.435  7014  7014 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-28 09:43:52.436  7014  7014 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-28 09:43:52.441  6848  7409 W FormManager: Network not available. Please check & try again.
07-28 09:43:52.443  1036  2120 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-28 09:43:52.446  7076  7076 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:52
07-28 09:43:52.446  6848  7410 V FormManager: Network unavailable.
,07-28 09:43:52.448  7076  7076 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-28 09:43:52.448  6848  7410 V FormManager: Network unavailable.
07-28 09:43:52.448  7076  7076 D Weather.Utils: 2 : All the weather widget is gone.
07-28 09:43:52.448  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 09:43:52.451  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 09:43:52.451  7076  7076 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-28 09:43:52.451  7076  7076 D WeatherAncestor: connectivity changed - connection : true
07-28 09:43:52.451  7076  7076 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@19d32863
07-28 09:43:52.451  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 09:43:52.451  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 09:43:52.451  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 09:43:52.451  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 09:43:52.451  7076  7076 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-28 09:43:52.452  7076  7076 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-28 09:43:52.452  7076  7076 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-28 09:43:52.452  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 09:43:52.452  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 09:43:52.452  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 09:43:52.452  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 09:43:52.452  7076  7076 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-28 09:43:52.452  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 09:43:52.452  7076  7076 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:43:52
07-28 09:43:52.452  6894  6894 I BluetoothA2dpServiceJni: classInitNative
07-28 09:43:52.452  6894  6894 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 09:43:52.452  6894  6894 D A2dpStateMachine: make
07-28 09:43:52.454  6894  6894 I bluedroid-qcom: get_profile_interface a2dp
07-28 09:43:52.454  6894  7412 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 09:43:52.456  6894  6894 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-28 09:43:52.456  6894  6894 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 09:43:52.456  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:52.457  6894  7411 D A2dpStateMachine: Enter Disconnected: -2
07-28 09:43:52.457  6894  6894 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 09:43:52.459  6894  6894 D HidService: Received start request. Starting profile...
07-28 09:43:52.459  6894  6894 I bluedroid-qcom: get_profile_interface hidhost
07-28 09:43:52.459  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:52.459  6894  6894 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 09:43:52.463  6894  6894 D HealthService: Received start request. Starting profile...
07-28 09:43:52.463  6894  6894 I bluedroid-qcom: get_profile_interface health
07-28 09:43:52.464  6894  6894 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-28 09:43:52.464  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:52.464  6894  6894 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 09:43:52.465  6894  6894 D PanService: Received start request. Starting profile...
07-28 09:43:52.465  6894  6894 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 09:43:52.465  6894  6894 I bluedroid-qcom: get_profile_interface pan
07-28 09:43:52.471  6894  6894 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-28 09:43:52.471  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:52.471  6894  6894 D HeadsetStateMachine: Proxy object connected
07-28 09:43:52.472  6894  6894 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 09:43:52.472  6894  6894 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,07-28 09:43:52.473  6894  6894 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-28 09:43:52.477  6894  6894 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 09:43:52.477  6894  6894 D BtGatt.GattService: Received start request. Starting profile...
07-28 09:43:52.477  6894  6894 D BtGatt.GattService: start()
07-28 09:43:52.477  6894  6894 I bluedroid-qcom: get_profile_interface gatt
07-28 09:43:52.477  6894  6894 D BtGatt.AdvertiseManager: advertise manager created
07-28 09:43:52.483  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
,07-28 09:43:52.486  6894  6894 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 09:43:52.487  6894  7390 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 09:43:52.487  6894  7390 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 09:43:52.488  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:52.488  6894  6894 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 09:43:52.488  6894  7390 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-28 09:43:52.488  6894  6894 V BluetoothMapService: BluetoothMapBinder()
07-28 09:43:52.489  6894  6894 D BluetoothMapService: Received start request. Starting profile...
07-28 09:43:52.489  6894  6894 D BluetoothMapService: start()
07-28 09:43:52.492  6894  6894 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 09:43:52.492  6894  6894 D BluetoothMapEmailAppObserver: createReceiver()
07-28 09:43:52.493  6894  6894 D BluetoothMapEmailAppObserver: initObservers()
07-28 09:43:52.493  6894  6894 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-28 09:43:52.502  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
,07-28 09:43:52.508  6894  6894 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 09:43:52.515  6894  6894 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-28 09:43:52.519  6894  6894 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 09:43:52.519  6894  6894 V PanService: [BTUI] SIM Extra State :ABSENT
07-28 09:43:52.523  6894  6894 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 09:43:52.527  6894  6894 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-28 09:43:52.527  6894  6894 V BluetoothMapService: Handler(): got msg=1
,07-28 09:43:52.528  6894  7349 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-28 09:43:52.528  6894  7349 I bluedroid-qcom: enable
07-28 09:43:52.529  6894  7349 I bt_hci_bdroid: init
07-28 09:43:52.530  6894  7349 I bt_vendor: bt-vendor : init
07-28 09:43:52.530  6894  6894 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:52.530  6894  7349 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 09:43:52.531  6894  7349 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-28 09:43:52.531  6894  7349 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 09:43:52.531  6894  7349 D bt_userial_mct: userial_init
07-28 09:43:52.531  6894  7349 D bt_hci_bdroid: set_power 1
07-28 09:43:52.531  6894  7349 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 09:43:52.531  6894  7349 I bt_vendor: Starting hciattach daemon
07-28 09:43:52.531  6894  7349 I bt_vendor: try to set true
07-28 09:43:52.521  7422  7422 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:52.521  7422  7422 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:52.533  6894  6894 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 09:43:52.533  6894  6894 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 09:43:52.533  6894  6894 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 09:43:52.534  6894  6894 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:52.534  6894  6894 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 09:43:52.538  6894  7419 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 09:43:52.538  6894  7419 I bt-btu  : btu_task pending for preload complete event
07-28 09:43:52.561  7423  7423 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 09:43:52.619  7429  7429 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-28 09:43:52.630  7430  7430 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-28 09:43:52.658  7432  7432 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 09:43:52.668  7433  7433 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-28 09:43:52.679  7434  7434 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 09:43:52.690  7435  7435 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-28 09:43:52.715  7437  7437 I libmdmdetect: ESOC framework not supported
,07-28 09:43:52.718  7437  7437 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
07-28 09:43:52.731  7437  7437 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-28 09:43:52.731  7437  7437 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 09:43:52.731  7437  7437 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-28 09:43:52.732  7437  7437 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,07-28 09:43:52.732  7437  7437 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 09:43:52.732  7437  7437 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 09:43:52.732  7437  7437 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-28 09:43:52.772  7437  7438 E QC-QMI  : qmi_client [7437] 14: failed to locate client data
07-28 09:43:52.772   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 09:43:52.772   461   461 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,07-28 09:43:52.827  7439  7439 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 09:43:52.842  7443  7443 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 09:43:52.883  6894  7349 I bt_vendor: bluetooth satus is on
07-28 09:43:52.883  6894  7349 D bt_hci_bdroid: preload
,07-28 09:43:52.883  6894  7421 D bt_userial_mct: userial_open(port:0)
07-28 09:43:52.883  6894  7421 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-28 09:43:52.885  1036  1094 W ProcessCpuTracker: Skipping unknown process pid 7422
07-28 09:43:52.885  1036  1094 W ProcessCpuTracker: Skipping unknown process pid 7443
07-28 09:43:52.887  6894  7421 I bt_vendor: Done intiailizing UART
07-28 09:43:52.888  6894  7421 I bt_vendor: Done intiailizing UART
07-28 09:43:52.888  6894  7421 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-28 09:43:52.888  6894  7421 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-28 09:43:52.888  6894  7419 I bt-btu  : btu_task received preload complete event
07-28 09:43:52.888  6894  7445 D bt_userial_mct: Entering userial_read_thread()
07-28 09:43:52.889  6894  7419 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 09:43:52.889  6894  7419 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-28 09:43:52.891  6894  7419 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_HCI
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 09:43:52.894  6894  7419 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 09:43:52.987  6894  7419 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-28 09:43:52.987  6894  7419 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0202061 
07-28 09:43:52.988  6894  7419 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0202061 
,07-28 09:43:53.031  6894  7353 E bt-btif : Calling BTA_HhEnable
,07-28 09:43:53.031  6894  7353 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,07-28 09:43:53.032  6894  7353 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 09:43:53.036  6894  7419 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 09:43:53.037  6894  7419 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 09:43:53.037  6894  7419 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-28 09:43:53.038  6894  7419 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 09:43:53.038  6894  7419 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 09:43:53.038  6894  7353 D BluetoothAdapterProperties: Name is: G3
07-28 09:43:53.040  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 09:43:53.041  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 09:43:53.043  6894  7353 D BluetoothAdapterProperties: Scan Mode:20
07-28 09:43:53.043  6894  7353 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 09:43:53.044  6894  7353 D bt_hci_bdroid: postload
07-28 09:43:53.044  6894  7421 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 09:43:53.045  6894  7419 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-28 09:43:53.046  6894  7353 D bte_conf: Device ID record 1 : primary
07-28 09:43:53.046  6894  7353 D bte_conf:   vendorId            = 00c4
07-28 09:43:53.046  6894  7353 D bte_conf:   vendorIdSource      = 0001
07-28 09:43:53.046  6894  7353 D bte_conf:   product             = 13a1
07-28 09:43:53.046  6894  7353 D bte_conf:   version             = 1000
07-28 09:43:53.046  6894  7353 D bte_conf:   clientExecutableURL = 
07-28 09:43:53.046  6894  7353 D bte_conf:   serviceDescription  = 
07-28 09:43:53.046  6894  7353 D bte_conf:   documentationURL    = 
07-28 09:43:53.046  6894  7353 D bte_conf: bte_load_did_conf no section named DID2.
07-28 09:43:53.048  6894  7421 D bt_hci_bdroid: Used up Tx Cmd credits
,07-28 09:43:53.050  6894  7421 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 09:43:53.055  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:53.058  6894  7353 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 09:43:53.058  6894  7349 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 09:43:53.058  6894  7349 D BluetoothAdapterProperties: ScanMode =  20
07-28 09:43:53.058  6894  7349 D BluetoothAdapterProperties: State =  11
07-28 09:43:53.059  6894  7419 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 09:43:53.059  6894  7349 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 09:43:53.051  7447  7447 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:53.059  6894  7419 W bt-smp  : Plain text(LSB ~ MSB) = df 59 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:43:53.059  6894  7419 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 67 4b a4 e7 84 23 79 75 0f 4c e7 af 99 60 c7 
07-28 09:43:53.059  6894  7421 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 09:43:53.059  6894  7419 W bt-btm  : Stopping oneshot timer
07-28 09:43:53.051  7447  7447 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:53.059  6894  7349 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 09:43:53.060  6894  7349 D BluetoothAdapterProperties: Setting state to 12
07-28 09:43:53.060  6894  7349 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 09:43:53.060  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:53.066  1036  1098 D BluetoothManagerService: Message: 60
07-28 09:43:53.066  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 09:43:53.066  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-28 09:43:53.068  6894  7353 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 09:43:53.069  6894  7349 I BluetoothAdapterState: Entering On State
07-28 09:43:53.070  6894  7445 E bt_mct  : hci lib postload completed
,07-28 09:43:53.073  6894  7349 D LGBluetoothServiceAdapter: [BTUI] OnState
07-28 09:43:53.074  6894  7349 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 09:43:53.074  6894  7349 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-28 09:43:53.075  6894  7349 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-28 09:43:53.078  6894  7353 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 09:43:53.078  6894  7353 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-28 09:43:53.078  6761  6776 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 09:43:53.083  1879  3974 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:43:53.089  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 09:43:53.089  1879  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:43:53.092  1879  1879 D BluetoothHeadset: Proxy object connected
,07-28 09:43:53.092  6761  6777 D BluetoothMap: onBluetoothStateChange: up=true
07-28 09:43:53.093  6894  7419 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 09:43:53.093  6894  7419 W bt-smp  : Plain text(LSB ~ MSB) = 1b a0 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:43:53.093  6894  7419 W bt-smp  : Encrypted text(LSB ~ MSB) = 83 83 5f 24 ef d3 1a 61 44 e5 e0 14 02 47 81 5b 
07-28 09:43:53.093  6894  7419 W bt-btm  : Stopping oneshot timer
,07-28 09:43:53.100  6761  6776 D BluetoothPan: onBluetoothStateChange on: true
07-28 09:43:53.100  6761  6776 D BluetoothPan: onBluetoothStateChange call bindService
07-28 09:43:53.106  6761  6761 D BluetoothMap: Proxy object connected
07-28 09:43:53.106  6761  6761 D MapProfile: Bluetooth service connected
07-28 09:43:53.106  6761  6761 D BluetoothMap: getConnectedDevices()
07-28 09:43:53.107  1036  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:43:53.109  1036  1036 D BluetoothHeadset: Proxy object connected
07-28 09:43:53.110  6761  7450 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 09:43:53.114  6894  7419 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 09:43:53.114  6894  7419 W bt-smp  : Plain text(LSB ~ MSB) = 32 38 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:43:53.114  6894  7419 W bt-smp  : Encrypted text(LSB ~ MSB) = 52 4b be 81 dd 6a 46 8d 5b 71 5e 5e 17 b3 16 19 
07-28 09:43:53.114  6894  7419 W bt-btm  : Stopping oneshot timer
07-28 09:43:53.115  6894  6910 V BluetoothMapService: getConnectedDevices()
07-28 09:43:53.118  1879  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:43:53.119  6894  7349 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 09:43:53.122  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 09:43:53.122  1036  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 09:43:53.123  1036  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 09:43:53.123  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 09:43:53.128  1036  1036 D BluetoothA2dp: Proxy object connected
,07-28 09:43:53.132  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 09:43:53.133  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:53.134  1978  2215 D LGBluetoothAPIService: Message: 1
07-28 09:43:53.134  1978  2215 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 09:43:53.137  6761  6761 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 09:43:53.137  6761  6761 D PanProfile: Bluetooth service connected
07-28 09:43:53.140  6894  7419 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 09:43:53.140  6894  7419 W bt-smp  : Plain text(LSB ~ MSB) = 9f 2d 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:43:53.140  6894  7419 W bt-smp  : Encrypted text(LSB ~ MSB) = 5b 29 22 1d c3 9a 14 05 8c a2 50 99 21 9e bd 48 
07-28 09:43:53.140  6894  7419 W bt-btm  : Stopping oneshot timer
,07-28 09:43:53.150  6576  6576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 09:43:53.152  6894  7419 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 09:43:53.152  6894  7419 W bt-smp  : Plain text(LSB ~ MSB) = 47 2c 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:43:53.152  6894  7419 W bt-smp  : Encrypted text(LSB ~ MSB) = 48 dc ca 30 d0 47 8b 66 d6 0b 60 5d 05 37 4a 16 
07-28 09:43:53.152  6894  7419 W bt-btm  : Stopping oneshot timer
07-28 09:43:53.155  7454  7454 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,07-28 09:43:53.159  1978  2215 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-28 09:43:53.159  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:53.159  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:53.159  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:53.159  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:53.159  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:43:53.159  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:53.159  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:53.159  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:53.160  6894  6894 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:53.160  6894  6894 D BluetoothMapService: STATE_ON
07-28 09:43:53.161  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 09:43:53.161  1036  1098 D BluetoothManagerService: Message: 40
07-28 09:43:53.161  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-28 09:43:53.162  6761  6761 D BluetoothInputDevice: Proxy object connected
07-28 09:43:53.162  6761  6761 D HidProfile: Bluetooth service connected
07-28 09:43:53.162  6894  6894 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 09:43:53.162  6894  6894 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 09:43:53.166  1978  1978 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 09:43:53.166  1978  2215 D LGBluetoothAPIService: Message: 100
07-28 09:43:53.166  1978  2215 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-28 09:43:53.167  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:43:53.171  6761  6761 D LocalBluetoothProfileManager: Adding local A2DP profile
07-28 09:43:53.173  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:53.173  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:53.173  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:53.173  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:53.173  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:43:53.173  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:53.173  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:53.173  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:53.173  1036  1098 D BluetoothManagerService: Message: 30
07-28 09:43:53.175  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:53.176  6761  6761 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-28 09:43:53.180  1036  1098 D BluetoothManagerService: Message: 30
,07-28 09:43:53.183  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:53.183  6894  6894 V BluetoothPbapService: Pbap Service onCreate
07-28 09:43:53.183  6894  6894 V BluetoothPbapService: Starting PBAP service
07-28 09:43:53.184  6894  6894 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,07-28 09:43:53.184  6894  6894 V BluetoothMapService: Handler(): got msg=1
07-28 09:43:53.185  6894  6894 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-28 09:43:53.185  6894  6894 V BluetoothPbapService: Pbap Service onBind
07-28 09:43:53.186  6761  6761 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-28 09:43:53.186  6894  7463 D BluetoothMapMasInstance: MAS initSocket()
07-28 09:43:53.187  6894  6894 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:53.187  6894  6894 V BluetoothPbapService: state: 12
07-28 09:43:53.187  6894  6894 V BluetoothPbapService: Handler(): got msg=1
07-28 09:43:53.188  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 09:43:53.188  6894  6894 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 09:43:53.188  6894  7463 D BluetoothMapMasInstance:   masId = 00
07-28 09:43:53.188  6894  7463 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 09:43:53.188  6894  7463 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 09:43:53.188  6894  7463 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-28 09:43:53.189  6894  7464 V BluetoothPbapService: Pbap Service initSocket
07-28 09:43:53.190  7118  7158 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
07-28 09:43:53.191  1036  2115 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:53.191  1036  2091 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:53.191  6761  6761 D BluetoothA2dp: Proxy object connected
,07-28 09:43:53.194  6894  7463 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 09:43:53.194  6894  7464 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:43:53.194  6894  6894 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 09:43:53.194  6894  6894 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:53.195  6894  6894 V BluetoothPbapReceiver: ***********state = 12
07-28 09:43:53.196  6761  6761 D A2dpProfile: Bluetooth service connected
07-28 09:43:53.196  6894  7464 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-28 09:43:53.196  6894  7464 V BluetoothPbapService: Succeed to create listening socket 
07-28 09:43:53.196  6894  7464 V BluetoothPbapService: Accepting socket connection...
07-28 09:43:53.197  6894  7353 D BluetoothAdapterProperties: Scan Mode:21
07-28 09:43:53.197  6894  7353 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 09:43:53.197  6894  7463 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-28 09:43:53.197  6894  7463 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 09:43:53.197  6894  7463 D BluetoothMapMasInstance: Accepting socket connection...
07-28 09:43:53.199  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:53.201  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:53.205  2268  2268 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 09:43:53.205  2268  2268 D c       : Getting all permits...
07-28 09:43:53.205  2268  2268 D a       : Opening database...
,07-28 09:43:53.206  6761  6761 D BluetoothHeadset: Proxy object connected
,07-28 09:43:53.208  6761  6761 D HeadsetProfile: Bluetooth service connected
07-28 09:43:53.209  6761  6761 D BluetoothPbap: Proxy object connected
07-28 09:43:53.209  2268  2268 D a       : Opening database auth.proximity.permit_store...
07-28 09:43:53.210  6761  6761 D PbapServerProfile: Bluetooth service connected
07-28 09:43:53.210  2268  2268 D a       : Closing database...
07-28 09:43:53.217  6761  6761 D DockEventReceiver: finishStartingService: stopping service
,07-28 09:43:53.221  6761  6761 D BluetoothPermissionRequest: onReceive
07-28 09:43:53.223  6761  6761 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 09:43:53.225  6761  6761 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 09:43:53.228  6894  6894 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,07-28 09:43:53.229  6894  6894 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-28 09:43:53.235  6894  6894 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-28 09:43:53.251  6894  6894 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 09:43:53.251  6894  6894 V BtOppService: onCreate
,07-28 09:43:53.256  6894  6894 V BluetoothOppNotification: send message
07-28 09:43:53.259  6894  6894 V BtOppService: Starting RfcommListener
07-28 09:43:53.267  6894  6894 D BluetoothOppPreference: Dumping Names:  
,07-28 09:43:53.268  6894  6894 D BluetoothOppPreference: {}
07-28 09:43:53.268  6894  6894 D BluetoothOppPreference: Dumping Channels:  
07-28 09:43:53.268  6894  6894 D BluetoothOppPreference: {}
,07-28 09:43:53.268  6894  7469 V BtOppService: Deleted complete outbound shares, number =  0
07-28 09:43:53.270  6894  6894 V BtOppService: onStartCommand
07-28 09:43:53.270  6894  7469 V BtOppService: Deleted complete inbound failed shares, number = 0
07-28 09:43:53.271  6894  7469 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-28 09:43:53.272  6894  7469 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e07bf1c on behalf of 
07-28 09:43:53.273  6894  7472 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 09:43:53.273  6894  7472 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 09:43:53.274  6894  6894 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:53.274  6894  6894 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 09:43:53.276  6894  6894 V BluetoothOppNotification: new notify threadi!
07-28 09:43:53.277  6894  6894 V BluetoothOppNotification: send delay message
07-28 09:43:53.278  6894  6894 V BtOppService: start RfcommListener
07-28 09:43:53.279  6894  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 09:43:53.279  6894  6894 V BtOppService: RfcommListener started
07-28 09:43:53.280  6894  6894 V BtOppService: ContentObserver received notification
07-28 09:43:53.280  6894  6894 V BtOppService: ContentObserver received notification
07-28 09:43:53.280  6894  7474 V BtOppRfcommListener: Starting RFCOMM listener....
07-28 09:43:53.281  1036  1657 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:53.281  6894  7474 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:43:53.282  6894  7474 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
07-28 09:43:53.282  6894  7474 V BtOppRfcommListener: Started RFCOMM listener....
07-28 09:43:53.282  6894  7474 I BtOppRfcommListener: Accept thread started.
07-28 09:43:53.282  6894  7474 V BtOppRfcommListener: Accepting connection...
,07-28 09:43:53.287  6894  7472 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@112f1725 on behalf of 
07-28 09:43:53.289  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:53.289  6894  6894 V BluetoothFtpService: Ftp Service onCreate
07-28 09:43:53.289  6894  6894 I BluetoothFtpService: Ftp Service onCreate
07-28 09:43:53.289  6894  6894 V BluetoothFtpService: Ftp Service onStartCommand
07-28 09:43:53.289  6894  6894 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:53.289  6894  6894 V BluetoothFtpService: Starting Listening on sockets
07-28 09:43:53.289  6894  6894 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 09:43:53.290  6894  6894 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 09:43:53.290  6894  6894 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 09:43:53.290  6894  6894 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:53.290  6894  6894 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 09:43:53.290  6894  6894 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 09:43:53.292  6894  6894 V BluetoothFtpService: Handler(): got msg=1
07-28 09:43:53.292  6894  6894 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 09:43:53.292  6894  6894 V BluetoothFtpService: Ftp Service initSocket
07-28 09:43:53.292  6894  7472 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 09:43:53.292  6894  7472 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 09:43:53.293  6894  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2382d6ab on behalf of 
07-28 09:43:53.294  6894  7473 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 09:43:53.294  6894  7472 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f5fb108 on behalf of 
07-28 09:43:53.294  6894  7472 V BluetoothOppNotification: update too frequent, put in queue
07-28 09:43:53.295  1036  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 09:43:53.296  6894  6894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:43:53.297  6894  7472 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 09:43:53.298  6894  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 09:43:53.299  6894  6894 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
07-28 09:43:53.300  6894  6894 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 09:43:53.301  6894  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7df00a1 on behalf of 
07-28 09:43:53.303  6894  7473 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 09:43:53.305  6894  7475 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 09:43:53.305  6894  7473 V BluetoothOppNotification: outbound notification was removed.
,07-28 09:43:53.306  6894  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 09:43:53.309  6894  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29aa82c6 on behalf of 
07-28 09:43:53.310  6894  7473 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 09:43:53.316  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:53.316  6894  6894 V BluetoothSapService: Sap Service onCreate
,07-28 09:43:53.317  6894  7473 V BluetoothOppNotification: inbound notification was removed.
07-28 09:43:53.317  6894  7473 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 09:43:53.318  6894  6894 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:53.318  6894  6894 V BluetoothSapService: state: 12
07-28 09:43:53.319  6894  6894 V BluetoothSapService: Starting SAP server process
07-28 09:43:53.320  6894  6894 V BluetoothSapService: SAP Service startRfcommListenerThread
07-28 09:43:53.320  6894  7473 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@163c0552 on behalf of 
07-28 09:43:53.321  6894  7477 V BluetoothSapService: Sap Service initRfcommSocket
07-28 09:43:53.321  1036  2120 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:53.311  7476  7476 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:53.311  7476  7476 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:43:53.321  6894  7477 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:43:53.323  6894  7477 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=80
07-28 09:43:53.323  6894  7477 V BluetoothSapService: Succeed to create listening socket 
07-28 09:43:53.323  6894  7477 V BluetoothSapService: Accepting socket connection...
07-28 09:43:53.328  7476  7476 V BT_SAP  : Event pipe created
07-28 09:43:53.328  7476  7476 V BT_SAP  : create_server_socket qcom.sap.server
07-28 09:43:53.328  7476  7476 V BT_SAP  : created socket fd 6
,07-28 09:43:53.994  1036  1392 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 09:43:53.994  1036  1392 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 09:43:54.014  1036  1394 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-28 09:43:54.016  1036  1394 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-28 09:43:54.089  1036  1951 I ActivityManager: Killing 7278:com.lge.bnr/1000 (adj 15): empty #17
,07-28 09:43:54.125  1036  1657 W libprocessgroup: failed to open /acct/uid_1000/pid_7278/cgroup.procs: No such file or directory
,07-28 09:43:54.134  1036  1950 I ActivityManager: Killing 6680:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
07-28 09:43:54.153  6811  6811 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-28 09:43:54.154  6811  6811 W System.err: android.os.DeadObjectException
07-28 09:43:54.154  6811  6811 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 09:43:54.154  6811  6811 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 09:43:54.154  6811  6811 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-28 09:43:54.154  6811  6811 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-28 09:43:54.154  6811  6811 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 09:43:54.154  6811  6811 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 09:43:54.154  6811  6811 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 09:43:54.154  6811  6811 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 09:43:54.154  6811  6811 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 09:43:54.154  6811  6811 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 09:43:54.154  6811  6811 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:43:54.154  6811  6811 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 09:43:54.154  6811  6811 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 09:43:54.154  6811  6811 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 09:43:54.155  6811  6811 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-28 09:43:54.155  6811  6811 W System.err: android.os.DeadObjectException
07-28 09:43:54.155  6811  6811 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-28 09:43:54.155  6811  6811 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-28 09:43:54.155  6811  6811 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-28 09:43:54.155  6811  6811 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-28 09:43:54.155  6811  6811 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-28 09:43:54.155  6811  6811 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-28 09:43:54.155  6811  6811 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 09:43:54.155  6811  6811 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 09:43:54.155  6811  6811 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 09:43:54.155  6811  6811 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 09:43:54.156  6811  6811 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:43:54.156  6811  6811 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 09:43:54.156  6811  6811 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 09:43:54.156  6811  6811 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 09:43:54.156  6811  6811 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-28 09:43:54.156  6811  6811 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,07-28 09:43:54.191  1036  1577 W libprocessgroup: failed to open /acct/uid_1000/pid_6680/cgroup.procs: No such file or directory
07-28 09:43:54.192  1036  1577 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-28 09:43:54.205  6811  6811 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-28 09:43:54.206  6811  6811 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,07-28 09:43:54.255  1036  1996 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7487 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 09:43:54.256  6811  6811 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-28 09:43:54.279  6894  6894 V BluetoothOppNotification: new notify threadi!
07-28 09:43:54.280  6894  6894 V BluetoothOppNotification: send delay message
,07-28 09:43:54.309  6894  7502 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-28 09:43:54.327  6894  7502 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30997023 on behalf of 
07-28 09:43:54.328  6894  7502 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-28 09:43:54.339  6894  7502 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 09:43:54.352  6894  7502 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f919920 on behalf of 
07-28 09:43:54.353  6894  7502 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-28 09:43:54.357  7487  7487 D UEI.SmartControl: Quickset Services start...
07-28 09:43:54.359  7487  7487 I UEI.SmartControl: Manufacture = LGE
07-28 09:43:54.359  7487  7487 D UEI.SmartControl: Id = LGNevo
07-28 09:43:54.361  7487  7487 D UEI.SmartControl: File observer start...
07-28 09:43:54.361  7487  7487 E UEI.SmartControl: IR Port is disabled: false
07-28 09:43:54.361  7487  7487 D UEI.SmartControl: Starting file observer...
07-28 09:43:54.362  7487  7487 D UEI.SmartControl: Extracting JNI libs...
07-28 09:43:54.362  7487  7487 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,07-28 09:43:54.367  6894  7502 V BluetoothOppNotification: outbound notification was removed.
07-28 09:43:54.378  6894  7502 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 09:43:54.381  6894  7502 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c6622d9 on behalf of 
07-28 09:43:54.382  6894  7502 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 09:43:54.385  6894  7502 V BluetoothOppNotification: inbound notification was removed.
,07-28 09:43:54.385  6894  7502 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 09:43:54.386  6894  7502 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32f1249e on behalf of 
,07-28 09:43:54.469  7487  7487 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-28 09:43:54.469  7487  7487 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,07-28 09:43:54.470  7487  7487 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-28 09:43:54.509  7487  7487 I UEI.SmartControl: --- Selecting new region: 6
07-28 09:43:54.511  7487  7487 I UEI.SmartControl: Model = LG-D855
,07-28 09:43:54.513  7487  7487 D UEI.SmartControl: QS Service created
07-28 09:43:54.530  7487  7487 I UEI.SmartControl: Service initServices...
,07-28 09:43:54.535  7487  7487 D UEI.SmartControl: QS start get config
,07-28 09:43:54.594  7487  7487 D UEI.SmartControl: Loading JNI Libs...
,07-28 09:43:54.850  7487  7487 I UEI.SmartControl: Supports setup maps: true
,07-28 09:43:54.853  7487  7487 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 09:43:54.853  7487  7487 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 09:43:54.853  7487  7487 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 09:43:54.853  7487  7487 I UEI.SmartControl: ### init IR Blaster...
07-28 09:43:54.859  7487  7487 D serial_port: Configuring serial port
07-28 09:43:54.873  7487  7487 E UEI.SmartControl: UEIBLaster setting for 616
,07-28 09:43:54.873  7487  7487 I UEI.SmartControl: Setting serial record hearder size = 2
,07-28 09:43:54.875  7487  7487 I UEI.SmartControl: configuring settings for MAXQ616
07-28 09:43:54.875  7487  7487 I UEI.SmartControl: Get version...
07-28 09:43:54.894  7487  7520 D UEI.SmartControl: serial port data available: 21
,07-28 09:43:54.925  7487  7487 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-28 09:43:54.925  7487  7487 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 09:43:54.926  7487  7487 I UEI.SmartControl: QS saving settings...
07-28 09:43:54.929  7487  7487 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 09:43:54.950  7487  7520 D UEI.SmartControl: serial port data available: 4
,07-28 09:43:54.992  7487  7523 I UEI.SmartControl: Device manager: loading config....
,07-28 09:43:54.994  7487  7523 D UEI.SmartControl: ----------- loading internal config...
07-28 09:43:55.004  1036  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:43:55.004  1036  1996 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@37364a6 mBinding = false
07-28 09:43:55.005  7487  7487 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 09:43:55.009  7487  7487 E UEI.SmartControl: Services init done
07-28 09:43:55.009  7487  7487 D UEI.SmartControl: QS Service init finished
,07-28 09:43:55.010  7487  7487 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 09:43:55.011  7487  7487 D UEI.SmartControl: QS Service version code: 201091
07-28 09:43:55.011  7487  7487 D UEI.SmartControl: Service requested: Control
07-28 09:43:55.017  7487  7523 E UEI.SmartControl: Loading SETTINGS...
07-28 09:43:55.022  7487  7487 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 09:43:55.024  6811  6811 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,07-28 09:43:55.026  1036  1051 I ActivityManager: Killing 6811:com.lge.qremote/u0a112 (adj 15): empty #17
07-28 09:43:55.027  7487  7504 I UEI.SmartControl: ------ IControl API: 11
07-28 09:43:55.028  7487  7504 I UEI.SmartControl: Registering callback...
07-28 09:43:55.030  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 09:43:55.030  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 09:43:55.031  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-28 09:43:55.031  1036  1098 D BluetoothManagerService: Message: 2
07-28 09:43:55.032  1036  1098 D BluetoothManagerService: Sending off request.
07-28 09:43:55.032  7487  7523 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 09:43:55.032  6894  6910 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-28 09:43:55.033  6894  7349 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-28 09:43:55.033  6894  7349 D BluetoothAdapterProperties: Setting state to 13
07-28 09:43:55.033  6894  7349 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 09:43:55.034  6894  7349 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 09:43:55.034  6894  7349 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 09:43:55.035  1036  1098 D BluetoothManagerService: Message: 60
07-28 09:43:55.035  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-28 09:43:55.035  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,07-28 09:43:55.038  7487  7522 I UEI.SmartControl: Notify AllClients services are ready: 0
07-28 09:43:55.038  7487  7522 D UEI.SmartControl: -----service ready thread exits
07-28 09:43:55.069  7487  7487 D UEI.SmartControl: Internal service binding...
,07-28 09:43:55.070  1036  1052 W libprocessgroup: failed to open /acct/uid_10112/pid_6811/cgroup.procs: No such file or directory
,07-28 09:43:55.071  6894  7353 D BluetoothAdapterProperties: Scan Mode:20
07-28 09:43:55.071  6894  7349 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 09:43:55.072  6894  7349 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 09:43:55.073  6894  7464 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:55.074  6894  7463 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-28 09:43:55.074  6894  7463 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:55.074  6894  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-28 09:43:55.074  6894  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-28 09:43:55.074  6894  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-28 09:43:55.074  6894  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-28 09:43:55.074  6894  7463 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-28 09:43:55.074  6894  7463 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-28 09:43:55.075  6894  7474 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:55.076  6894  7475 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:55.076  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-28 09:43:55.076  6894  7419 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-28 09:43:55.078  6894  7477 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:43:55.090  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 09:43:55.090  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:55.090  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 09:43:55.091  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,07-28 09:43:55.091  6894  7419 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:43:55.091  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:55.091  6894  7419 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:43:55.091  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 09:43:55.091  6894  7419 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 09:43:55.091  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-28 09:43:55.091  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-28 09:43:55.091  6894  7419 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 09:43:55.093  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 09:43:55.093  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-28 09:43:55.096  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:55.096  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:55.096  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:55.096  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:55.096  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:55.096  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:55.096  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:55.096  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:55.096  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:55.097  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:55.097  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:55.100  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:55.100  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:43:55.100  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:43:55.100  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:43:55.100  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:43:55.100  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:43:55.100  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:43:55.100  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:43:55.100  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:43:55.101  6576  6576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:43:55.101  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:43:55.102  6894  6894 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:55.102  6894  6894 D BluetoothMapService: STATE_TURNING_OFF
07-28 09:43:55.102  6894  6894 V BluetoothMapService: Handler(): got msg=4
07-28 09:43:55.102  6894  6894 D BluetoothMapService: MAP Service closeService in
07-28 09:43:55.102  6894  6894 D BluetoothMapMasInstance: MAP Service shutdown
07-28 09:43:55.103  6894  6894 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 09:43:55.103  6894  6894 V BluetoothMapService: MAP Service closeService out
07-28 09:43:55.103  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:55.104  6894  6894 V BtOppService: Receiver DISABLED_ACTION 
07-28 09:43:55.104  6894  6894 I BtOppRfcommListener: stopping Accept Thread
07-28 09:43:55.104  6894  6894 V BtOppRfcommListener: close mBtServerSocket
07-28 09:43:55.105  6894  6894 V BtOppRfcommListener: waiting for thread to terminate
07-28 09:43:5,5.105  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:55.105  6894  7474 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 09:43:55.107  6761  6761 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,07-28 09:43:55.110  6894  6894 V BtOppRfcommListener: done waiting for thread to terminate
07-28 09:43:55.114  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 09:43:55.115  6894  6894 V BtOppService: onDestroy
07-28 09:43:55.121  6894  6894 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,07-28 09:43:55.123  6894  6894 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 09:43:55.123  6894  6894 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:55.123  6894  6894 V BluetoothPbapReceiver: ***********state = 13
07-28 09:43:55.125  6894  6894 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-28 09:43:55.126  6894  6894 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:55.126  6894  6894 V BluetoothPbapService: state: 13
07-28 09:43:55.126  6894  6894 V BluetoothPbapService: Pbap Service closeService in
07-28 09:43:55.127  6761  6761 D DockEventReceiver: finishStartingService: stopping service
07-28 09:43:55.129  2268  2268 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 09:43:55.130  6761  6761 D BluetoothPbap: Proxy object disconnected
07-28 09:43:55.130  6761  6761 D PbapServerProfile: Bluetooth service disconnected
07-28 09:43:55.131  6894  6894 V BluetoothPbapService: successfully stopped pbap service
07-28 09:43:55.131  6894  6894 V BluetoothPbapService: Pbap Service closeService out
07-28 09:43:55.131  6894  6894 V BluetoothPbapService: Pbap Service onDestroy
07-28 09:43:55.131  6894  6894 V BluetoothPbapService: Pbap Service closeService in
07-28 09:43:55.131  6894  6894 V BluetoothPbapService: Pbap Service closeService out
07-28 09:43:55.131  6894  6894 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-28 09:43:55.143  6761  6761 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-28 09:43:55.148  6761  6761 D BluetoothPermissionRequest: onReceive
07-28 09:43:55.148  6761  6761 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-28 09:43:55.154  6761  6761 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 09:43:55.158  6894  6894 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-28 09:43:55.158  6894  6894 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-28 09:43:55.159  6894  6894 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,07-28 09:43:55.165  6894  6894 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:55.165  6894  6894 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 09:43:55.166  6894  6894 V BluetoothFtpService: Ftp Service onStartCommand
07-28 09:43:55.166  6894  6894 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:55.166  6894  6894 V BluetoothFtpService: Ftp Service closeService
07-28 09:43:55.167  6894  6894 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-28 09:43:55.170  6894  6894 V BluetoothFtpService: successfully stopped ftp service
07-28 09:43:55.171  6894  6894 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 09:43:55.171  6894  6894 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 09:43:55.171  6894  6894 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 09:43:55.171  6894  6894 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:55.171  6894  6894 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-28 09:43:55.171  6894  6894 V BluetoothSapReceiver: Calling SAP service start service with action = null
,07-28 09:43:55.172  6894  6894 V BluetoothFtpService: Ftp Service onDestroy
,07-28 09:43:55.172  6894  6894 V BluetoothFtpService: Ftp Service closeService
07-28 09:43:55.176  6894  6894 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:55.176  6894  6894 V BluetoothSapService: state: 13
,07-28 09:43:55.177  6894  6894 V BluetoothSapService: Stopping SAP server process
07-28 09:43:55.178  6894  6894 V BluetoothSapService: Sap Service closeSapService in
07-28 09:43:55.179  6894  6894 V BluetoothSapService: Close listen Socket : 
07-28 09:43:55.179  6894  6894 V BluetoothSapService: Close rfcomm Socket : 
07-28 09:43:55.179  6894  6894 V BluetoothSapService: Close sapd  Socket : 
07-28 09:43:55.180  6894  6894 V BluetoothSapService: Sap Service closeSapService out
,07-28 09:43:55.180  6894  6894 V BluetoothSapService: Sap Service onDestroy
07-28 09:43:55.180  6894  6894 V BluetoothSapService: Sap Service closeSapService in
07-28 09:43:55.180  6894  6894 V BluetoothSapService: Close listen Socket : 
,07-28 09:43:55.180  6894  6894 V BluetoothSapService: Close rfcomm Socket : 
07-28 09:43:55.180  6894  6894 V BluetoothSapService: Close sapd  Socket : 
07-28 09:43:55.181  6894  6894 V BluetoothSapService: Sap Service closeSapService out
07-28 09:43:55.996  6894  7353 D bt_hci_bdroid: cleanup
,07-28 09:43:56.010  6894  7421 I bt_lpm  : LPM is already off!!!
07-28 09:43:56.010  6894  7445 I bt_userial_mct: exiting userial_read_thread
07-28 09:43:56.010  6894  7445 D bt_userial_mct: Leaving userial_evt_read_thread()
07-28 09:43:56.011  6894  7419 W bt-btif : ag scb idx 1 not allocated
07-28 09:43:56.011  6894  7419 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-28 09:43:56.011  6894  7419 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 09:43:56.011  6894  7419 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-28 09:43:56.013  6894  7353 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-28 09:43:56.013  6894  7421 I bt_vendor: hw_epilog_process
07-28 09:43:56.014  6894  7353 D bt_hci_bdroid: cleanup Finalizing cleanup
07-28 09:43:56.014  6894  7353 D bt_userial_mct: userial_close
07-28 09:43:56.014  6894  7353 E bt_userial_mct: pthread_join() FAILED result:3
07-28 09:43:56.014  6894  7353 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-28 09:43:56.018  6894  7353 D bt_hci_bdroid: set_power 0
07-28 09:43:56.018  6894  7353 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-28 09:43:56.018  6894  7353 I bt_vendor: bluetooth satus is on
07-28 09:43:56.018  6894  7353 I bt_vendor: bt-vendor : resetting BT status
07-28 09:43:56.018  6894  7353 I bt_vendor: Starting hciattach daemon
07-28 09:43:56.018  6894  7353 I bt_vendor: try to set false
07-28 09:43:56.019  6894  7353 I bt_vendor: Starting hciattach daemon
07-28 09:43:56.019  6894  7353 I bt_vendor: try to set false
,07-28 09:43:56.025  6894  7353 I bt_vendor: cleanup
07-28 09:43:56.027  6894  7419 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 09:43:56.028  6894  7353 I GKI_LINUX: GKI_exit_task 0 done
07-28 09:43:56.028  6894  7353 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 09:43:56.030  6894  7349 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 09:43:56.038  6894  6894 D HeadsetService: Received stop request...Stopping profile...
,07-28 09:43:56.041  6894  6894 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 09:43:56.041  6894  6894 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 09:43:56.042  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:56.042  6894  7390 D HeadsetStateMachine: Exit Disconnected: -1
07-28 09:43:56.046  6894  7349 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 09:43:56.048  6894  6894 D A2dpService: Received stop request...Stopping profile...
07-28 09:43:56.048  6894  7411 D A2dpStateMachine: Exit Disconnected: -1
07-28 09:43:56.049  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-28 09:43:56.049  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 09:43:56.051  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 09:43:56.051  1879  1879 D BluetoothHeadset: Proxy object disconnected
07-28 09:43:56.051  1879  1879 D BluetoothHeadset: Proxy object disconnected
,07-28 09:43:56.054  6894  6894 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-28 09:43:56.055  6894  6894 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-28 09:43:56.056  6894  6894 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 09:43:56.056  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:56.058  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-28 09:43:56.058  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 09:43:56.059  6894  6894 D HidService: Received stop request...Stopping profile...
07-28 09:43:56.059  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:56.061  6894  6894 D HealthService: Received stop request...Stopping profile...
07-28 09:43:56.061  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:56.063  6894  6894 D PanService: Received stop request...Stopping profile...
,07-28 09:43:56.066  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:56.068  6894  6894 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 09:43:56.069  6894  6894 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 09:43:56.069  6894  6894 D BtGatt.GattService: stop()
07-28 09:43:56.069  6894  6894 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 09:43:56.070  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
07-28 09:43:56.071  6894  6894 D HeadsetStateMachine: Unbinding service...
07-28 09:43:56.072  6894  6894 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 09:43:56.072  6894  6894 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 09:43:56.072  6894  6894 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 09:43:56.072  6894  6894 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 09:43:56.072  6894  6894 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 09:43:56.073  6894  6894 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 09:43:56.073  6894  6894 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-28 09:43:56.074  6894  6894 D BluetoothMapService: Received stop request...Stopping profile...
07-28 09:43:56.074  6894  6894 D BluetoothMapService: stop()
07-28 09:43:56.074  6894  6894 D BluetoothMapEmailAppObserver: deinitObservers()
07-28 09:43:56.074  6894  6894 D BluetoothMapEmailAppObserver: removeReceiver()
07-28 09:43:56.076  6894  6894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19d32863
,07-28 09:43:56.080  6894  6894 I BluetoothA2dpServiceJni: cleanupNative
07-28 09:43:56.080  6894  7412 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 09:43:56.080  6894  6894 I GKI_LINUX: GKI_exit_task 2 done
07-28 09:43:56.080  6894  6894 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 09:43:56.081  6894  6894 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 09:43:56.081  6894  6894 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 09:43:56.081  6894  6894 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 09:43:56.081  6894  6894 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 09:43:56.081  6894  6894 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 09:43:56.081  6894  6894 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 09:43:56.082  6894  6894 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 09:43:56.084  6894  6894 V BluetoothMapService: Handler(): got msg=4
07-28 09:43:56.084  6894  6894 D BluetoothMapService: MAP Service closeService in
07-28 09:43:56.084  6894  6894 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 09:43:56.084  6894  6894 V BluetoothMapService: MAP Service closeService out
07-28 09:43:56.085  6894  7349 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-28 09:43:56.085  6894  7349 D BluetoothAdapterProperties: Setting state to 10
07-28 09:43:56.085  6894  7349 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 09:43:56.086  6894  6894 D BluetoothMapService: cleanup()
07-28 09:43:56.086  6894  6894 D BluetoothMapService: MAP Service closeService in
07-28 09:43:56.086  6894  6894 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-28 09:43:56.086  6894  6894 V BluetoothMapService: MAP Service closeService out
07-28 09:43:56.087  1036  1098 D BluetoothManagerService: Message: 60
07-28 09:43:56.087  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-28 09:43:56.087  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
07-28 09:43:56.089  6894  7349 I BluetoothAdapterState: Entering OffState
,07-28 09:43:56.091  6761  6777 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 09:43:56.092  6761  6777 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 09:43:56.096  1879  2372 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:43:56.097  1879  1895 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:43:56.098  6761  6777 D BluetoothMap: onBluetoothStateChange: up=false
07-28 09:43:56.098  6761  6777 D BluetoothPan: onBluetoothStateChange on: false
07-28 09:43:56.100  1036  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 09:43:56.101  6761  6777 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 09:43:56.102  6761  6777 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:43:56.103  1879  3978 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:43:56.103  1036  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 09:43:56.104  1036  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-28 09:43:56.104  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-28 09:43:56.106  1036  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-28 09:43:56.106  1036  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-28 09:43:56.107  1036  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@37364a6 mBinding = false
07-28 09:43:56.107  1036  1098 D BluetoothManagerService: Sending unbind request.
07-28 09:43:56.112  6894  7353 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-28 09:43:56.114  6894  6894 I GKI_LINUX: GKI_exit_task 1 done
07-28 09:43:56.114  6894  6894 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 09:43:56.115  6894  6894 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 09:43:56.115  6894  6894 I art     : --- WEIRD: removing null entry 248
07-28 09:43:56.115  6894  6894 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
07-28 09:43:56.116  6894  6894 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-28 09:43:56.116  6894  6894 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-28 09:43:56.117  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-28 09:43:56.119  6894  6894 I art     : System.exit called, status: 0
07-28 09:43:56.119  6894  6894 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 09:43:56.138   320  3982 V AudioFlinger: 6894 died, releasing its sessions
07-28 09:43:56.138   320  3982 V AudioFlinger:  pid 1879 @ 0
07-28 09:43:56.138   320  3982 V AudioFlinger:  pid 3426 @ 1
07-28 09:43:56.138   320  3982 V AudioFlinger:  pid 3426 @ 2
,07-28 09:43:56.141  1978  1978 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
07-28 09:43:56.142  1978  2215 D LGBluetoothAPIService: Message: 101
07-28 09:43:56.142  1978  2215 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
07-28 09:43:56.142  1978  2215 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
07-28 09:43:56.142  1978  2215 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
07-28 09:43:56.144  6761  6761 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-28 09:43:56.148  1036  1951 I ActivityManager: Process com.android.bluetooth (pid 6894) has died
07-28 09:43:56.148  1036  1951 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
07-28 09:43:56.148  1036  1951 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
07-28 09:43:56.160  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-28 09:43:56.168  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:56.169  1978  2215 D LGBluetoothAPIService: Message: 2
07-28 09:43:56.169  1978  2215 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
07-28 09:43:56.171  6761  6761 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-28 09:43:56.171  6761  6761 D LGBluetoothEventManager: [BTUI] clear device connection state
07-28 09:43:56.173  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:43:56.174  1605  1605 D BluetoothAdapter: 418243340: getState() :  mService = null. Returning STATE_OFF
07-28 09:43:56.174  1605  1605 D BluetoothAdapter: 418243340: getState() :  mService = null. Returning STATE_OFF
,07-28 09:43:56.176  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:43:56.306  1036  2095 I art     : Explicit concurrent mark sweep GC freed 96869(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.282ms total 132.426ms
07-28 09:43:56.307  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-28 09:43:56.387  1036  1951 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7567 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-28 09:43:56.389  6761  6761 D DockEventReceiver: finishStartingService: stopping service
,07-28 09:43:56.454  7567  7567 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 09:43:56.454  7567  7567 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 09:43:56.455  7567  7567 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-28 09:43:56.455  7567  7567 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 09:43:56.476  7567  7567 D BluetoothAdapterApp: Loading JNI Library
,07-28 09:43:56.511  7567  7567 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@b6c6eb Instance Count = 1
,07-28 09:43:56.517  7567  7567 D BluetoothAdapterApp: onCreate
07-28 09:43:56.541  7567  7567 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,07-28 09:43:56.542  7567  7567 D ProfileConfigQcom: Adding HeadsetService
,07-28 09:43:56.543  7567  7567 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-28 09:43:56.543  7567  7567 D ProfileConfigQcom: Adding A2dpService
07-28 09:43:56.544  7567  7567 D ProfileConfigQcom: [BTUI] HidService is supported
,07-28 09:43:56.544  7567  7567 D ProfileConfigQcom: Adding HidService
07-28 09:43:56.545  7567  7567 D ProfileConfigQcom: [BTUI] HealthService is supported
07-28 09:43:56.545  7567  7567 D ProfileConfigQcom: Adding HealthService
07-28 09:43:56.546  7567  7567 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-28 09:43:56.548  7567  7567 D ProfileConfigQcom: [BTUI] PanService is supported
07-28 09:43:56.548  7567  7567 D ProfileConfigQcom: Adding PanService
07-28 09:43:56.549  7567  7567 D ProfileConfigQcom: [BTUI] GattService is supported
07-28 09:43:56.550  7567  7567 D ProfileConfigQcom: Adding GattService
07-28 09:43:56.550  7567  7567 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-28 09:43:56.551  7567  7567 D ProfileConfigQcom: Adding BluetoothMapService
07-28 09:43:56.552  7567  7567 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-28 09:43:56.554  7567  7567 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 09:43:56.557  7567  7567 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:56.558  7567  7567 V BluetoothPbapReceiver: ***********state = 10
07-28 09:43:56.560  7567  7567 V LGMDMManagerInternal: Create singleton instance
,07-28 09:43:56.659  2268  2268 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 09:43:56.665  7567  7567 D LGBluetoothAPIServer: [BTUI] onCreate()
07-28 09:43:56.665  7567  7567 D LGBluetoothAPIServer: [BTUI] onBind()
07-28 09:43:56.670  1978  1978 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-28 09:43:56.670  1978  2215 D LGBluetoothAPIService: Message: 100
07-28 09:43:56.670  1978  2215 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-28 09:43:56.674  6761  6761 D BluetoothPermissionRequest: onReceive
,07-28 09:43:56.678  6761  6761 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 09:43:56.678  6761  6761 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-28 09:43:56.681  6761  6761 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-28 09:43:56.682  6761  6761 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 09:43:56.687  7567  7567 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,07-28 09:43:56.692  7567  7567 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:56.695  7567  7567 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 09:43:56.696  7567  7567 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 09:43:56.696  7567  7567 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 09:43:56.697  7567  7567 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:43:56.697  7567  7567 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-28 09:43:56.700  6828  6828 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,07-28 09:43:57.985  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-28 09:43:58.037  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:43:58.037  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:43:58.047  1036  1383 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-28 09:43:58.091  1036  1094 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7595 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-28 09:43:58.097  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-28 09:43:58.098  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-28 09:43:58.104  1036  1036 D administrator: Handling package changes for user 0
,07-28 09:43:58.132  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-28 09:43:58.150  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 09:43:58.201  7595  7595 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-28 09:43:58.226  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-28 09:43:58.226  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-28 09:43:58.289  7595  7595 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:58.289  7595  7595 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:43:58.301  1036  1093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 09:43:58.312  1036  1093 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-28 09:43:58.330  2511  2511 V GmsNetworkLocationProvi: DISABLE
,07-28 09:43:58.331  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,07-28 09:43:58.375  1036  1093 D LocationProviderProxy: applying state to connected service
,07-28 09:43:58.377  2511  2511 E GCoreFlp: Bound FusedProviderService with LocationManager
07-28 09:43:58.392  7595  7639 I Babel   : MmsConfig: mnc/mcc: 0/0
07-28 09:43:58.393  7595  7639 I Babel   : MmsConfig.loadMmsSettings
,07-28 09:43:58.397  7595  7639 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-28 09:43:58.397  7595  7639 I Babel   : MmsConfig.loadFromDatabase
,07-28 09:43:58.418  7595  7639 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-28 09:43:58.419  7595  7595 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:43:58.419  7595  7639 I Babel   : MmsConfig.loadFromResources
,07-28 09:43:58.422  7595  7639 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-28 09:43:58.422  7595  7639 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,07-28 09:43:58.437  7595  7638 W AudioCapabilities: Unsupported mime audio/evrc
07-28 09:43:58.438  7595  7638 W AudioCapabilities: Unsupported mime audio/qcelp
07-28 09:43:58.439  7595  7638 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-28 09:43:58.449  1843  7642 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-28 09:43:58.450  1843  7642 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-28 09:43:58.458  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
07-28 09:43:58.462  7595  7638 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-28 09:43:58.463  7595  7638 W AudioCapabilities: Unsupported mime audio/qcelp
,07-28 09:43:58.464  7595  7638 W AudioCapabilities: Unsupported mime audio/evrc
07-28 09:43:58.466  1843  4747 I Icing   : updateResources: need to parse e{com.google.android.gms}
07-28 09:43:58.466  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3474741d
07-28 09:43:58.466  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
07-28 09:43:58.467  6945  6945 D AppUp4:CustFacade: isPhone : true
07-28 09:43:58.467  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
07-28 09:43:58.467  6945  6945 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-28 09:43:58.479  7595  7638 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-28 09:43:58.482  7595  7638 W VideoCapabilities: Unsupported mime video/divx
07-28 09:43:58.489  7595  7638 W VideoCapabilities: Unsupported mime video/divx311
07-28 09:43:58.494  7595  7638 W VideoCapabilities: Unsupported mime video/divx4
,07-28 09:43:58.504  7595  7638 W VideoCapabilities: Unsupported mime video/mp4v-esdp
07-28 09:43:58.506  1036  1996 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7645 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-28 09:43:58.510  1036  1657 I ActivityManager: Killing 6781:com.lge.sync/1000 (adj 15): empty #17
07-28 09:43:58.521  7595  7638 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-28 09:43:58.524  7595  7638 W AudioCapabilities: Unsupported mime audio/eac3
07-28 09:43:58.525  7595  7638 W AudioCapabilities: Unsupported mime audio/ac3
07-28 09:43:58.525  7595  7638 W AudioCapabilities: Unsupported mime audio/g726
07-28 09:43:58.526  7595  7638 W AudioCapabilities: Unsupported mime audio/wma-voice
07-28 09:43:58.527  7595  7638 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-28 09:43:58.528  7595  7638 W AudioCapabilities: Unsupported mime audio/adpcm
07-28 09:43:58.529  1036  1400 D WifiService: Client connection lost with reason: 4
07-28 09:43:58.530  7595  7638 W VideoCapabilities: Unsupported mime video/theora
07-28 09:43:58.531  7595  7638 W VideoCapabilities: Unsupported mime video/mjpg
,07-28 09:43:58.610  1036  1950 W libprocessgroup: failed to open /acct/uid_1000/pid_6781/cgroup.procs: No such file or directory
07-28 09:43:58.633  7645  7645 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 09:43:58.633  7645  7645 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 09:43:58.634  7645  7645 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-28 09:43:58.635  7645  7645 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-28 09:43:58.635  7645  7645 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-28 09:43:58.687  7645  7645 I SystemConfig: BUILD Country: EU
07-28 09:43:58.687  7645  7645 I SystemConfig: BUILD Operator: OPEN
,07-28 09:43:58.725  1036  1577 I ActivityManager: Killing 6969:com.lge.email/u0a23 (adj 15): empty #17
,07-28 09:43:58.896  1036  2041 W libprocessgroup: failed to open /acct/uid_10023/pid_6969/cgroup.procs: No such file or directory
,07-28 09:43:58.961  1036  1577 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7669 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-28 09:43:58.971  7645  7664 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-28 09:43:58.971  7645  7664 I SystemConfig: existFile = false
07-28 09:43:58.972  7645  7664 I SystemConfig: canReadFile = false
07-28 09:43:58.972  7645  7664 I SystemConfig: systemFeature RCS result false
07-28 09:43:58.972  7645  7664 D SystemConfig: refreshRcsSupport() :false
,07-28 09:43:59.018  1036  1407 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
07-28 09:43:59.037  7669  7669 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 09:43:59.037  7669  7669 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-28 09:43:59.037  7669  7669 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-28 09:43:59.038  7669  7669 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-28 09:43:59.170  7669  7669 I AppConfig: Total System Memory = 2995761152
,07-28 09:43:59.181  7669  7669 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,07-28 09:43:59.263  1036  1950 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7688 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-28 09:43:59.264  1036  1950 I ActivityManager: Killing 6848:com.lge.formmanager/u0a26 (adj 15): empty #17
07-28 09:43:59.330  1036  1577 W libprocessgroup: failed to open /acct/uid_10026/pid_6848/cgroup.procs: No such file or directory
,07-28 09:43:59.520  7688  7688 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-28 09:43:59.666  7688  7688 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:43:59.667  7688  7688 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:43:59.721  7688  7688 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-28 09:43:59.758  7688  7688 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-28 09:43:59.760  7688  7688 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-28 09:43:59.805  7688  7688 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-28 09:43:59.805  7688  7688 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-28 09:43:59.828  1036  1927 I ActivityManager: Killing 6387:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,07-28 09:43:59.861  1036  2115 W libprocessgroup: failed to open /acct/uid_1000/pid_6387/cgroup.procs: No such file or directory
,07-28 09:43:59.888  4576  7730 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-28 09:43:59.954   346   346 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 393us total 20.890ms
,07-28 09:43:59.971   346   346 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 14.351ms
,07-28 09:43:59.981  1036  2091 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7732 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
07-28 09:43:59.990   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 292us total 17.182ms
,07-28 09:43:59.991  7487  7524 D UEI.SmartControl: Internal timer expired: 1
07-28 09:43:59.991  7487  7524 D UEI.SmartControl: unbind internal service
07-28 09:44:00.001  1036  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=726699497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,07-28 09:44:00.010  7487  7487 D UEI.SmartControl: Service.onUnbind: IControl
07-28 09:44:00.010  7487  7487 D UEI.SmartControl: Service.onDestroy
07-28 09:44:00.010  7487  7487 D UEI.SmartControl: Lock is in USE false
07-28 09:44:00.010  7487  7487 D UEI.SmartControl: unbind internal service
07-28 09:44:00.011  7487  7487 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@6693519
07-28 09:44:00.011  7487  7487 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
07-28 09:44:00.012  7487  7487 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
07-28 09:44:00.012  7487  7487 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-28 09:44:00.012  7487  7487 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-28 09:44:00.012  7487  7487 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-28 09:44:00.012  7487  7487 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
07-28 09:44:00.012  7487  7487 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
07-28 09:44:00.012  7487  7487 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
07-28 09:44:00.012  7487  7487 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-28 09:44:00.012  7487  7487 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 09:44:00.012  7487  7487 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 09:44:00.012  7487  7487 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:44:00.012  7487  7487 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 09:44:00.012  7487  7487 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 09:44:00.012  7487  7487 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 09:44:00.012  7487  7487 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@6693519
07-28 09:44:00.013  7487  7487 D serial_port: close(fd = 25)
,07-28 09:44:00.029  2838  2855 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-28 09:44:00.032  2838  2855 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@63421d8 on behalf of 7688
07-28 09:44:00.033  7487  7487 I UEI.SmartControl: Serial port is closed.
07-28 09:44:00.033  7487  7487 I UEI.SmartControl: Serial port is closed.
,07-28 09:44:00.033  7487  7487 D UEI.SmartControl: Blaster closed
07-28 09:44:00.033  7487  7487 D UEI.SmartControl: Shut down QS...
07-28 09:44:00.033  7487  7487 D UEI.SmartControl: Stopping QS lib
07-28 09:44:00.033  7487  7487 D UEI.SmartControl: QS lib stop result = true
07-28 09:44:00.033  7487  7487 D UEI.SmartControl: Stopped QS lib
07-28 09:44:00.034  7487  7487 D UEI.SmartControl: Stopped file observer...
07-28 09:44:00.034  7487  7487 D UEI.SmartControl: QS shutdown complete
,07-28 09:44:00.037  2611  2611 D [Concierge]Service: onStartCommand(). Type : 9
07-28 09:44:00.045  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-28 09:44:00.045  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
07-28 09:44:00.045  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-28 09:44:00.045  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
07-28 09:44:00.046  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
07-28 09:44:00.046  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
07-28 09:44:00.047  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
,07-28 09:44:00.048  7688  7688 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-28 09:44:00.050  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
07-28 09:44:00.069  7688  7688 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-28 09:44:00.081  7732  7732 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-28 09:44:00.103  7732  7732 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-28 09:44:00.103  7732  7732 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-28 09:44:00.103  7732  7732 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-28 09:44:00.103  7732  7732 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-28 09:44:00.103  7732  7732 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-28 09:44:00.103  7732  7732 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,07-28 09:44:00.134  1036  1927 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7771 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-28 09:44:00.140  1036  1927 I ActivityManager: Killing 7014:com.google.android.setupwizard/u0a46 (adj 15): empty #17
07-28 09:44:00.172  1036  2041 W libprocessgroup: failed to open /acct/uid_10046/pid_7014/cgroup.procs: No such file or directory
,07-28 09:44:00.200  7771  7771 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-28 09:44:00.234  7771  7771 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,07-28 09:44:00.285  7771  7771 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,07-28 09:44:00.286  7771  7771 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,07-28 09:44:00.286  7771  7771 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,07-28 09:44:00.286  7771  7771 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-28 09:44:00.287  7771  7771 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-28 09:44:00.289  7771  7771 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-28 09:44:00.295  7771  7771 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-28 09:44:00.298  1036  2095 V SIM_STK : Menu title from STK is T-Mobile
,07-28 09:44:00.306  7771  7771 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
07-28 09:44:00.307  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7716
07-28 09:44:00.309  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=726699497 [*alarm*], flags=0x0
07-28 09:44:00.310  7771  7771 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-28 09:44:00.313  7771  7771 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-28 09:44:00.314  7771  7771 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,07-28 09:44:00.315  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,07-28 09:44:00.316  7771  7771 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-28 09:44:00.319  4576  7730 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 432 ms] updated apps [took 431 ms] 
07-28 09:44:00.354  7771  7771 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:44:00.354  7771  7771 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:44:00.363  7771  7771 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,07-28 09:44:00.364  7771  7771 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
,07-28 09:44:00.364  7771  7771 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-28 09:44:00.364  7771  7771 V SoundPool: doLoad: loading sample sampleID=1
07-28 09:44:00.365  7771  7771 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-28 09:44:00.368  7771  7791 V SoundPool: Start decode
07-28 09:44:00.369  7771  7791 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,07-28 09:44:00.370   320  3982 V MediaPlayerService: decode(23, 10857164, 17813)
07-28 09:44:00.370   320  3982 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-28 09:44:00.370   320  3982 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-28 09:44:00.370   320  3982 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-28 09:44:00.370   320  3982 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-28 09:44:00.370   320  3982 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-28 09:44:00.371   320  3982 V MediaPlayerService: player type = 3
07-28 09:44:00.371   320  3982 V AwesomePlayer: AwesomePlayer create()
07-28 09:44:00.371   320  3982 V AwesomePlayer: reset_l() 
07-28 09:44:00.371   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:44:00.371   320  3982 V AwesomePlayer: setAudioSink() 
07-28 09:44:00.371   320  3982 V AwesomePlayer: reset_l() 
07-28 09:44:00.371   320  3982 V AudioCache: notify(0xb100e440, 8, 0, 0)
07-28 09:44:00.371   320  3982 V AudioCache: ignored
07-28 09:44:00.371   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:44:00.372   320  3982 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-28 09:44:00.372   320  3982 V AwesomePlayer: setDataSource_l dataSource
07-28 09:44:00.372   320  3982 V LGParserOSAL: SniffLGParser start
07-28 09:44:00.372   320  3982 V LGParserOSAL: MainType:5, SubType=0
07-28 09:44:00.372   320  3982 V LGParserOSAL: #### check Mime : application/ogg
07-28 09:44:00.372   320  3982 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-28 09:44:00.372   320  3982 E MediaExtractor: Use LGExtractor :application/ogg 
,07-28 09:44:00.382  7771  7771 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-28 09:44:00.387  7487  7487 D UEI.SmartControl: QS Service created
,07-28 09:44:00.399  7771  7771 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 09:44:00.399  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 09:44:00.413  7771  7771 V LGMDMManager: Create singleton instance
,07-28 09:44:00.424   320  3982 V LGParserOSAL: supported mime: application/ogg
07-28 09:44:00.424   320  3982 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-28 09:44:00.424   320  3982 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-28 09:44:00.424   320  3982 V AwesomePlayer: mBitrate = -1 bits/sec
07-28 09:44:00.424   320  3982 V AwesomePlayer: AudioTrack Setting
07-28 09:44:00.424   320  3982 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-28 09:44:00.424   320  3982 V AwesomePlayer: setAudioSource() 
07-28 09:44:00.424   320  3982 V MediaPlayerService: prepare
07-28 09:44:00.424   320  3982 V AwesomePlayer: prepareAsync_l() 
07-28 09:44:00.425   320  3982 V MediaPlayerService: wait for prepare
07-28 09:44:00.425   320  7795 V AwesomePlayer: onPrepareAsyncEvent() 
07-28 09:44:00.425   320  7795 V AwesomePlayer: initAudioDecoder() 
07-28 09:44:00.425   320  7795 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 09:44:00.425   320  7795 V AudioSystem: isOffloadSupported()
07-28 09:44:00.425   320  7795 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 09:44:00.425   320  7795 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 09:44:00.425   320  7795 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 09:44:00.425   320  7795 V AwesomePlayer: getUseOffload() = 0 
07-28 09:44:00.425   320  7795 V OMXCodec: OMXCodec::Create
07-28 09:44:00.425   320  7795 V OMXCodec: findMatchingCodecs()
07-28 09:44:00.425   320  7795 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-28 09:44:00.425   320  7795 V OMXCodec: matchingCodecs.size()=1
07-28 09:44:00.425   320  7795 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-28 09:44:00.427   320  7795 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-28 09:44:00.427   320  7795 V LGCodecAdapter: LG Codec Adapter start
07-28 09:44:00.427   320  7795 V OMXCodec: OMXCodec Createtor
07-28 09:44:00.427   320  7795 V OMXCodec: setComponentRole
07-28 09:44:00.427   320  7795 V OMXCodec: configureCodec protected=0
07-28 09:44:00.427   320  7795 V LGCodecAdapter: called getLGCodecSpecificData
07-28 09:44:00.427   320  7795 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-28 09:44:00.427   320  7795 V LGCodecOSAL: Called LGconfigureCodecMETA
07-28 09:44:00.427   320  7795 V LGCodecOSAL: Called LGconfigureCodecMSG
07-28 09:44:00.427   320  7795 V LGCodecOSAL: Not support LGCodec
07-28 09:44:00.427   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 09:44:00.427   320  7795 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-28 09:44:00.427   320  7795 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-28 09:44:00.427   320  7795 I AwesomePlayer: Could not offload audio decode, try pcm offload
,07-28 09:44:00.427   320  7795 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-28 09:44:00.427   320  7795 V AudioSystem: isOffloadSupported()
07-28 09:44:00.427   320  7795 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-28 09:44:00.427   320  7795 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-28 09:44:00.427   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-28 09:44:00.427   320  7795 V OMXCodec: init()
07-28 09:44:00.427   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-28 09:44:00.427   320  7795 V OMXCodec: allocateBuffers
07-28 09:44:00.427   320  7795 V OMXCodec: allocateBuffersOnPort portIndex=0
07-28 09:44:00.427   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-28 09:44:00.428   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on input port
07-28 09:44:00.428   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
07-28 09:44:00.428   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
07-28 09:44:00.428   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
07-28 09:44:00.428   320  7795 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 09:44:00.428   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 09:44:00.428   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-28 09:44:00.428   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-28 09:44:00.428   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
07-28 09:44:00.428   320  7795 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
07-28 09:44:00.428   320  7795 V OMXCodec: init() mAsyncCompletion wait!!! 
07-28 09:44:00.428   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 09:44:00.428   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 09:44:00.428   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-28 09:44:00.428   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-28 09:44:00.428   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-28 09:44:00.428   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-28 09:44:00.428   320  7795 V OMXCodec: init() mAsyncCompletion wait free! 
07-28 09:44:00.429   320  7795 V AwesomePlayer: finishAsyncPrepare_l() 
07-28 09:44:00.429   320  7795 V AudioCache: notify(0xb100e440, 5, 0, 0)
07-28 09:44:00.429   320  7795 V AudioCache: ignored
07-28 09:44:00.429   320  7795 V AudioCache: notify(0xb100e440, 1, 0, 0)
07-28 09:44:00.429   320  7795 V AudioCache: prepared
07-28 09:44:00.429   320  3982 V AudioCache: wait - success
07-28 09:44:00.429   320  3982 V MediaPlayerService: start
07-28 09:44:00.429   320  3982 V AwesomePlayer: play_l() 
07-28 09:44:00.429   320  3982 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-28 09:44:00.429   320  3982 V AwesomePlayer: createAudioPlayer_l
07-28 09:44:00.429   320  3982 V AwesomePlayer: seekAudioIfNecessary_l() 
07-28 09:44:00.429   320  3982 V AwesomePlayer: startAudioPlayer_l() 
07-28 09:44:00.429   320  3982 D AudioPlayer: start of Playback, useOffload 0
07-28 09:44:00.429   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 09:44:00.429   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-28 09:44:00.431   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] ,OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-28 09:44:00.431   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-28 09:44:00.431   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-28 09:44:00.431   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-28 09:44:00.431   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-28 09:44:00.431   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-28 09:44:00.432   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-28 09:44:00.432   320  7797 V OMXCodec: allocateBuffersOnPort portIndex=1
07-28 09:44:00.432  7487  7487 I UEI.SmartControl: Service initServices...
,07-28 09:44:00.433  7487  7487 D UEI.SmartControl: QS start get config
07-28 09:44:00.434   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-28 09:44:00.434   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
07-28 09:44:00.434   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
07-28 09:44:00.434   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
07-28 09:44:00.434   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c5510 on output port
07-28 09:44:00.434   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-28 09:44:00.434   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-28 09:44:00.436   320  3982 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-28 09:44:00.436   320  3982 V AudioCache: notify(0xb100e440, 6, 0, 0)
07-28 09:44:00.436   320  3982 V AudioCache: ignored
07-28 09:44:00.437   320  3982 V MediaPlayerService: wait for playback complete
07-28 09:44:00.437   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.437   320  7798 V AudioCache: memcpy(0xac102000, 0xb1785000, 4096)
07-28 09:44:00.438   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.438   320  7798 V AudioCache: memcpy(0xac103000, 0xb1785000, 4096)
07-28 09:44:00.440   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.440   320  7798 V AudioCache: memcpy(0xac104000, 0xb1785000, 4096)
07-28 09:44:00.440   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.440   320  7798 V AudioCache: memcpy(0xac105000, 0xb1785000, 4096)
07-28 09:44:00.440   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.440   320  7798 V AudioCache: memcpy(0xac106000, 0xb1785000, 4096)
07-28 09:44:00.441   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.441   320  7798 V AudioCache: memcpy(0xac107000, 0xb1785000, 4096)
07-28 09:44:00.442   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.442   320  7798 V AudioCache: memcpy(0xac108000, 0xb1785000, 4096)
07-28 09:44:00.442   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.442   320  7798 V AudioCache: memcpy(0xac109000, 0xb1785000, 4096)
07-28 09:44:00.443   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.443   320  7798 V AudioCache: memcpy(0xac10a000, 0xb1785000, 4096)
07-28 09:44:00.443   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.443   320  7798 V AudioCache: memcpy(0xac10b000, 0xb1785000, 4096)
07-28 09:44:00.444   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.444   320  7798 V AudioCache: memcpy(0xac10c000, 0xb1785000, 4096)
07-28 09:44:00.444   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.444   320  7798 V AudioCache: memcpy(0xac10d000, 0xb1785000, 4096)
07-28 09:44:00.445   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.445   320  7798 V AudioCache: memcpy(0xac10e000, 0xb1785000, 4096)
,07-28 09:44:00.446   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.446   320  7798 V AudioCache: memcpy(0xac10f000, 0xb1785000, 4096)
07-28 09:44:00.446   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.446   320  7798 V AudioCache: memcpy(0xac110000, 0xb1785000, 4096)
07-28 09:44:00.447   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.447   320  7798 V AudioCache: memcpy(0xac111000, 0xb1785000, 4096)
07-28 09:44:00.447   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.447   320  7798 V AudioCache: memcpy(0xac112000, 0xb1785000, 4096)
07-28 09:44:00.448   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.448   320  7798 V AudioCache: memcpy(0xac113000, 0xb1785000, 4096)
07-28 09:44:00.449   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.449   320  7798 V AudioCache: memcpy(0xac114000, 0xb1785000, 4096)
07-28 09:44:00.450   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.450   320  7798 V AudioCache: memcpy(0xac115000, 0xb1785000, 4096)
07-28 09:44:00.450   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.450   320  7798 V AudioCache: memcpy(0xac116000, 0xb1785000, 4096)
07-28 09:44:00.451   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.451   320  7798 V AudioCache: memcpy(0xac117000, 0xb1785000, 4096)
07-28 09:44:00.451   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.451   320  7798 V AudioCache: memcpy(0xac118000, 0xb1785000, 4096)
07-28 09:44:00.452   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.452   320  7798 V AudioCache: memcpy(0xac119000, 0xb1785000, 4096)
07-28 09:44:00.452   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.452   320  7798 V AudioCache: memcpy(0xac11a000, 0xb1785000, 4096)
07-28 09:44:00.453   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.453   320  7798 V AudioCache: memcpy(0xac11b000, 0xb1785000, 4096)
07-28 09:44:00.453   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.453   320  7798 V AudioCache: memcpy(0xac11c000, 0xb1785000, 4096)
07-28 09:44:00.454   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.454   320  7798 V AudioCache: memcpy(0xac11d000, 0xb1785000, 4096)
07-28 09:44:00.454   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.454   320  7798 V AudioCache: memcpy(0xac11e000, 0xb1785000, 4096)
07-28 09:44:00.455   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.455   320  7798 V AudioCache: memcpy(0xac11f000, 0xb1785000, 4096)
07-28 09:44:00.456   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.456   320  7798 V AudioCache: memcpy(0xac120000, 0xb1785000, 4096)
07-28 09:44:00.456   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.456   320  7798 V AudioCache: memcpy(0xac121000, 0xb1785000, 4096)
07-28 09:44:00.457   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.457   320  7798 V AudioCache: memcpy(0xac122000, 0xb1785000, 4096)
07-28 09:44:00.457   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.457   320  7798 V AudioCache: memcpy(0xac123000, 0xb1785000, 4096)
,07-28 09:44:00.458   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.458   320  7798 V AudioCache: memcpy(0xac124000, 0xb1785000, 4096)
07-28 09:44:00.458   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.458   320  7798 V AudioCache: memcpy(0xac125000, 0xb1785000, 4096)
07-28 09:44:00.459   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.459   320  7798 V AudioCache: memcpy(0xac126000, 0xb1785000, 4096)
07-28 09:44:00.459   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.459   320  7798 V AudioCache: memcpy(0xac127000, 0xb1785000, 4096)
07-28 09:44:00.460   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.460   320  7798 V AudioCache: memcpy(0xac128000, 0xb1785000, 4096)
07-28 09:44:00.461   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.461   320  7798 V AudioCache: memcpy(0xac129000, 0xb1785000, 4096)
07-28 09:44:00.462   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.462   320  7798 V AudioCache: memcpy(0xac12a000, 0xb1785000, 4096)
07-28 09:44:00.462   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.462   320  7798 V AudioCache: memcpy(0xac12b000, 0xb1785000, 4096)
07-28 09:44:00.463   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.463   320  7798 V AudioCache: memcpy(0xac12c000, 0xb1785000, 4096)
07-28 09:44:00.463   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.463   320  7798 V AudioCache: memcpy(0xac12d000, 0xb1785000, 4096)
07-28 09:44:00.464   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.464   320  7798 V AudioCache: memcpy(0xac12e000, 0xb1785000, 4096)
07-28 09:44:00.464   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.464   320  7798 V AudioCache: memcpy(0xac12f000, 0xb1785000, 4096)
07-28 09:44:00.465   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.465   320  7798 V AudioCache: memcpy(0xac130000, 0xb1785000, 4096)
07-28 09:44:00.465   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.465   320  7798 V AudioCache: memcpy(0xac131000, 0xb1785000, 4096)
07-28 09:44:00.466   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.466   320  7798 V AudioCache: memcpy(0xac132000, 0xb1785000, 4096)
07-28 09:44:00.466   320  7798 V AudioCache: write(0xb1785000, 4096)
07-28 09:44:00.466   320  7798 V AudioCache: memcpy(0xac133000, 0xb1785000, 4096)
07-28 09:44:00.467   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-28 09:44:00.467   320  7798 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-28 09:44:00.467   320  7798 V AwesomePlayer: postAudioEOS() 
07-28 09:44:00.467   320  7798 V AudioCache: write(0xb1785000, 280)
07-28 09:44:00.467   320  7798 V AudioCache: memcpy(0xac134000, 0xb1785000, 280)
07-28 09:44:00.468   320  7795 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-28 09:44:00.468   320  7795 V AwesomePlayer: onStreamDone
07-28 09:44:00.468   320  7795 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
,07-28 09:44:00.468   320  7795 V AudioCache: notify(0xb100e440, 2, 0, 0)
07-28 09:44:00.468   320  7795 V AudioCache: playback complete
07-28 09:44:00.468   320  7795 V AwesomePlayer: pause_l() 
07-28 09:44:00.468   320  3982 V AudioCache: wait - success
07-28 09:44:00.468   320  7795 V AudioCache: notify(0xb100e440, 7, 0, 0)
07-28 09:44:00.468   320  7795 V AudioCache: ignored
07-28 09:44:00.468   320  3982 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-28 09:44:00.468   320  7795 V AwesomePlayer: cancelPlayerEvents
07-28 09:44:00.468   320  7795 D AudioPlayer: Pause Playback at 1068125
07-28 09:44:00.470   320  3982 V AwesomePlayer: reset_l() 
07-28 09:44:00.470   320  3982 V AudioCache: notify(0xb100e440, 8, 0, 0)
07-28 09:44:00.470   320  3982 V AudioCache: ignored
07-28 09:44:00.470   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:44:00.470   320  3982 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-28 09:44:00.470   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-28 09:44:00.470   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-28 09:44:00.470   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-28 09:44:00.470   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 09:44:00.470   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-28 09:44:00.470   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-28 09:44:00.470   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-28 09:44:00.470   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
07-28 09:44:00.470   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-28 09:44:00.470   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
07-28 09:44:00.470   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 0
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c5510 on port 1
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-28 09:44:00.471   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 09:44:00.471   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-28 09:44:00.471   320  7797 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-28 09:44:00.471   320  3982 V OMXCodec: ,[OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-28 09:44:00.471   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-28 09:44:00.471   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-28 09:44:00.474   320  3982 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-28 09:44:00.474   320  3982 D AudioPlayer: AudioPlayer releasing audio source
07-28 09:44:00.474   320  3982 D AudioPlayer: AudioPlayer done releasing audio source
07-28 09:44:00.474   320  3982 V AwesomePlayer: reset_l() 
07-28 09:44:00.474   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:44:00.474   320  3982 V AwesomePlayer: ~AwesomePlayer call
07-28 09:44:00.474   320  3982 V AwesomePlayer: reset_l() 
07-28 09:44:00.474   320  3982 V AwesomePlayer: cancelPlayerEvents
07-28 09:44:00.475  7771  7791 V SoundPool: close(31)
07-28 09:44:00.475  7771  7791 V SoundPool: pointer = 0x9fff4000, size = 205080, sampleRate = 48000, numChannels = 2
07-28 09:44:00.489  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 09:44:00.491  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,07-28 09:44:00.498  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1399
07-28 09:44:00.764  7487  7487 I UEI.SmartControl: Supports setup maps: true
,07-28 09:44:00.770  7487  7487 D UEI.SmartControl: QS start statue = true Error code = 0
07-28 09:44:00.771  7487  7487 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-28 09:44:00.771  7487  7487 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-28 09:44:00.771  7487  7487 I UEI.SmartControl: ### init IR Blaster...
07-28 09:44:00.774  7487  7487 D serial_port: Configuring serial port
07-28 09:44:00.774  7487  7487 E UEI.SmartControl: UEIBLaster setting for 616
07-28 09:44:00.774  7487  7487 I UEI.SmartControl: Setting serial record hearder size = 2
07-28 09:44:00.774  7487  7487 I UEI.SmartControl: configuring settings for MAXQ616
07-28 09:44:00.774  7487  7487 I UEI.SmartControl: Get version...
07-28 09:44:00.793  7487  7806 D UEI.SmartControl: serial port data available: 21
,07-28 09:44:00.819  7487  7487 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-28 09:44:00.820  7487  7487 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-28 09:44:00.820  7487  7487 I UEI.SmartControl: QS saving settings...
07-28 09:44:00.822  7487  7487 D UEI.SmartControl: IR Blaster version: 25672567
,07-28 09:44:00.838  7487  7806 D UEI.SmartControl: serial port data available: 4
,07-28 09:44:00.871  7487  7815 I UEI.SmartControl: Device manager: loading config....
07-28 09:44:00.871  7487  7815 D UEI.SmartControl: ----------- loading internal config...
,07-28 09:44:00.884  7487  7487 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-28 09:44:00.888  7487  7487 E UEI.SmartControl: Services init done
07-28 09:44:00.888  7487  7487 D UEI.SmartControl: QS Service init finished
,07-28 09:44:00.892  7487  7487 D UEI.SmartControl: QS Service version name: 2.1.91
07-28 09:44:00.892  7487  7487 D UEI.SmartControl: QS Service version code: 201091
07-28 09:44:00.893  7487  7487 D UEI.SmartControl: Service requested: Control
07-28 09:44:00.895  7487  7815 E UEI.SmartControl: Loading SETTINGS...
07-28 09:44:00.898  7487  7487 D UEI.SmartControl: Request IControl service: devices are loaded...
07-28 09:44:00.900  7771  7771 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-28 09:44:00.903  7487  7503 I UEI.SmartControl: ------ IControl API: 11
07-28 09:44:00.903  7487  7503 D UEI.SmartControl: File observer start...
07-28 09:44:00.904  7487  7503 E UEI.SmartControl: IR Port is disabled: false
07-28 09:44:00.904  7487  7503 D UEI.SmartControl: Starting file observer...
07-28 09:44:00.904  7487  7503 I UEI.SmartControl: Registering callback...
,07-28 09:44:00.906  7487  7487 D UEI.SmartControl: Internal service binding...
07-28 09:44:00.907  7487  7504 I UEI.SmartControl: ------ IControl API: 19
07-28 09:44:00.908  7487  7504 I UEI.SmartControl: Registering Services Ready callback...
07-28 09:44:00.911  7487  7815 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-28 09:44:00.926  7487  7814 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-28 09:44:00.931  7771  7786 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-28 09:44:00.931  7487  7814 D UEI.SmartControl: -----service ready thread exits
07-28 09:44:00.932  7771  7789 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-28 09:44:00.932  7771  7789 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-28 09:44:00.933  7771  7771 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-28 09:44:00.933  7771  7771 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-28 09:44:00.934  7487  7503 I UEI.SmartControl: ------ IControl API: 8
07-28 09:44:00.935  7771  7771 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-28 09:44:00.936  7771  7771 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-28 09:44:00.936  7771  7771 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-28 09:44:00.936  7771  7771 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-28 09:44:00.937  7771  7771 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-28 09:44:00.938  7771  7771 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-28 09:44:00.941  7771  7771 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,07-28 09:44:00.946  7771  7771 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-28 09:44:00.947  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-28 09:44:00.948  7771  7771 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 09:44:00.948  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-28 09:44:00.949  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-28 09:44:00.950  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-28 09:44:00.951  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-28 09:44:00.952  7771  7771 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469691840951]
07-28 09:44:00.955  7771  7771 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,07-28 09:44:00.962  1036  1657 I ActivityManager: Killing 7035:com.android.chrome/u0a57 (adj 15): empty #17
07-28 09:44:01.003  7771  7817 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-28 09:44:01.008  1036  1950 W libprocessgroup: failed to open /acct/uid_10057/pid_7035/cgroup.procs: No such file or directory
07-28 09:44:01.014  7771  7771 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-28 09:44:01.016  7771  7771 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-28 09:44:01.017  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-28 09:44:01.017  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-28 09:44:01.017  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-28 09:44:01.018  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-28 09:44:01.018  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,07-28 09:44:01.029  7771  7771 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-28 09:44:01.101  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 09:44:01.101  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@234cac69 added. We now have 6 listener(s)
07-28 09:44:01.102  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:44:01.111  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:01.111  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@266396ee added. We now have 7 listener(s)
07-28 09:44:01.111  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:01.112  6576  6706 I System.out: IsBluetoothEnabled
07-28 09:44:01.113  1036  2091 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:01.113  1036  2091 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
07-28 09:44:01.113  1036  1098 D BluetoothManagerService: Message: 2
07-28 09:44:01.117  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:01.119  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:01.119  1036  1052 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-28 09:44:01.136  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 09:44:01.136  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 09:44:01.136  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-28 09:44:01.140  1036  1098 D BluetoothManagerService: Message: 1
07-28 09:44:01.140  1036  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,07-28 09:44:01.168  1036  1098 D BluetoothManagerService: Message: 20
07-28 09:44:01.168  1036  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e146675:true
07-28 09:44:01.169  7567  7567 D BluetoothAdapterState: make
07-28 09:44:01.174  7567  7567 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-28 09:44:01.174  7567  7567 I bluedroid-qcom: init
,07-28 09:44:01.178  7567  7821 I BluetoothAdapterState: Entering OffState
07-28 09:44:01.179  7567  7567 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 09:44:01.179  7567  7567 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 09:44:01.179  7567  7567 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 09:44:01.179  7567  7567 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 09:44:01.179  7567  7567 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-28 09:44:01.181  7567  7567 I bluedroid-qcom: get_profile_interface socket
07-28 09:44:01.181  7567  7567 I bluedroid-qcom: get_profile_interface map_client
07-28 09:44:01.182  7567  7825 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 09:44:01.185  7567  7825 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-28 09:44:01.171  7824  7824 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 09:44:01.181  7824  7824 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:01.201  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 09:44:01.201  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,07-28 09:44:01.206  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-28 09:44:01.206  1036  1098 D BluetoothManagerService: Message: 40
07-28 09:44:01.206  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-28 09:44:01.207  7567  7583 I bluedroid-qcom: config_hci_snoop_log
07-28 09:44:01.208  1036  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-28 09:44:01.208  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-28 09:44:01.209  7824  7824 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-28 09:44:01.209  7824  7824 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-28 09:44:01.209  7824  7824 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-28 09:44:01.210  7824  7824 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-28 09:44:01.213  7567  7825 D BluetoothAdapterProperties: Name is: G3
07-28 09:44:01.215  7824  7824 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-28 09:44:01.215  7824  7824 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,07-28 09:44:01.223  7567  7821 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-28 09:44:01.224  7567  7821 D BluetoothAdapterProperties: Setting state to 11
07-28 09:44:01.224  7567  7821 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 09:44:01.225  7567  7821 I LGBluetoothServiceJni: classInitNative: succeeds
07-28 09:44:01.229  1036  1098 D BluetoothManagerService: Message: 60
07-28 09:44:01.229  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-28 09:44:01.229  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,07-28 09:44:01.234  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:01.234  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 09:44:01.238  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:01.240  6761  6761 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-28 09:44:01.246  7567  7567 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 09:44:01.246  7567  7567 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:01.246  7567  7567 V BluetoothPbapReceiver: ***********state = 11
,07-28 09:44:01.257  2268  2268 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 09:44:01.266  7567  7821 D BluetoothBondStateMachine: make
07-28 09:44:01.269  7567  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.269  7567  7821 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-28 09:44:01.269  7567  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.269  7567  7821 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-28 09:44:01.270  7567  7839 I BluetoothBondStateMachine: StableState(): Entering Off State
07-28 09:44:01.271  7567  7821 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,07-28 09:44:01.275  7567  7821 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:44:01.276  6761  6761 D BluetoothPermissionRequest: onReceive
07-28 09:44:01.281  7567  7821 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:44:01.282  7567  7567 D HeadsetService: Received start request. Starting profile...
07-28 09:44:01.283  7567  7567 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 09:44:01.283  7567  7567 D LGBluetoothHfpAdapter: Version 1.6
07-28 09:44:01.286  7567  7567 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 09:44:01.288  7567  7567 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 09:44:01.288  7567  7567 D HeadsetStateMachine: make
,07-28 09:44:01.291  6761  6761 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 09:44:01.295  7567  7821 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:44:01.304  7567  7821 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 09:44:01.311  7567  7821 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:44:01.316  7567  7821 E BluetoothAdapterService: File transfer profiles supported!!
07-28 09:44:01.321  7567  7821 E BluetoothAdapterService: File transfer profiles supported!!
,07-28 09:44:01.330  7567  7567 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:44:01.331  7567  7567 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:44:01.335  7567  7567 D HeadsetStateMachine: max_hf_connections = 1
07-28 09:44:01.335  7567  7567 I bluedroid-qcom: get_profile_interface handsfree
07-28 09:44:01.337  7567  7567 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-28 09:44:01.338   320  1406 V AudioPolicyService: registerClient() client 0xb57f80c0, uid 1002
07-28 09:44:01.338   320  1405 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-28 09:44:01.338  7567  7821 V LGMDMManager: Create singleton instance
07-28 09:44:01.338   320  1405 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 09:44:01.338   320  1405 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 09:44:01.338  7567  7567 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-28 09:44:01.339   320   320 V AudioFlinger: registerClient() client 0xb5581b98, pid 7567
07-28 09:44:01.339   320  1399 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:44:01.339   320  1399 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:44:01.340  1879  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:44:01.340  1879  1894 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:44:01.340  1036  1657 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:44:01.340  1036  1657 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:44:01.340  3426  3445 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:44:01.340  3426  3445 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:44:01.340  1605  3121 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:44:01.340  1605  3121 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-28 09:44:01.340  7567  7583 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-28 09:44:01.340  7567  7567 V ToneGenerator: Create Track: 0xb4928a80
07-28 09:44:01.340  7567  7567 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-28 09:44:01.340  7567  7583 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-28 09:44:01.340  7567  7567 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-28 09:44:01.340   320  3982 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 09:44:01.340   320  3982 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-28 09:44:01.340   320  3982 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-28 09:44:01.340   320  3982 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 09:44:01.341   320  1401 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:44:01.341   320  1401 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:44:01.341  3426  3446 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:44:01.341  3426  3446 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:44:01.341   320  1406 I AudioFlinger: isAudioPlaybackHookOn() false
07-28 09:44:01.341  7567  7583 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:44:01.341  7567  7583 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-28 09:44:01.341   320  1405 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-28 09:44:01.341  1036  2120 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:44:01.342   320  1405 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-28 09:44:01.342  1036  2120 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:44:01.342   320  1405 V AudioPolicyManagerEx,: AudioPolicyManagerEx: getOutputForDevice
07-28 09:44:01.342   320  1405 V AudioPolicyManagerEx: getOutput() returns output 2
07-28 09:44:01.342  1605  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:44:01.342  7567  7567 V AudioSystem: getLatency() output 2, latency 50
07-28 09:44:01.342  1605  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:44:01.342  7567  7567 V AudioSystem: getFrameCount() output 2, frameCount 960
07-28 09:44:01.342  7567  7567 V AudioTrack: createTrack_l() output 2 afLatency 50
07-28 09:44:01.342  1879  3980 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-28 09:44:01.342  1879  3980 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-28 09:44:01.342   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 09:44:01.342   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 09:44:01.342   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-28 09:44:01.342   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-28 09:44:01.342   320   320 V AudioFlinger: createTrack() lSessionId: 21
07-28 09:44:01.343  7567  7821 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 09:44:01.343  7567  7567 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-28 09:44:01.343   320   320 V AudioFlinger: acquiring 21 from 7567, for 7567
07-28 09:44:01.343   320   320 V AudioFlinger:  added new entry for 21
07-28 09:44:01.343  7567  7567 V ToneGenerator: ToneGenerator INIT OK, time: 152496
07-28 09:44:01.343  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.344  7567  7843 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-28 09:44:01.345  7567  7843 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-28 09:44:01.345  7567  7843 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-28 09:44:01.345  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.345  7567  7843 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-28 09:44:01.345   320  2203 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7567
07-28 09:44:01.346   320  2203 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
,07-28 09:44:01.346   320  2203 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-28 09:44:01.346   320  2203 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-28 09:44:01.346   320  2203 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-28 09:44:01.346   320  2203 V voice   : voice_set_parameters: exit with code(0)
07-28 09:44:01.346   320  2203 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
,07-28 09:44:01.346   320  2203 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-28 09:44:01.346   320  2203 V msm8974_platform: platform_set_parameters: exit with code(0)
07-28 09:44:01.346   320  2203 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-28 09:44:01.346   320  2203 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-28 09:44:01.346   320  2203 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null,
07-28 09:44:01.347  7567  7843 V ToneGenerator: ToneGenerator destructor
07-28 09:44:01.347  7567  7843 V ToneGenerator: stopTone
07-28 09:44:01.347  7567  7843 V ToneGenerator: Delete Track: 0xb4928a80
07-28 09:44:01.347  7567  7567 D A2dpService: Received start request. Starting profile...
,07-28 09:44:01.350  1036  1657 W Process : Unable to open /proc/7845/status
07-28 09:44:01.350   320  3982 V AudioPolicyService: AudioCommandThread() adding release output 2
,07-28 09:44:01.350  7567  7567 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 09:44:01.350   320  3982 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-28 09:44:01.350   320  1231 V AudioPolicyService: AudioCommandThread() waking up
07-28 09:44:01.350   320  1231 V AudioPolicyService: AudioCommandThread() processing release output 2
07-28 09:44:01.350   320  1231 V AudioPolicyManager: releaseOutput() 2
07-28 09:44:01.351   320  1231 V AudioPolicyService: AudioCommandThread() going to sleep
07-28 09:44:01.351   320  3982 V AudioFlinger: PlaybackThread::Track destructor
,07-28 09:44:01.351   320  3982 V AudioFlinger: removeClient_l() pid 7567, calling pid 320
07-28 09:44:01.351  7567  7843 V AudioTrack: ~AudioTrack, releasing session id from 7567 on behalf of 7567
07-28 09:44:01.351   320   320 V AudioFlinger: releasing 21 from 7567 for 7567
07-28 09:44:01.351   320   320 V AudioFlinger:  decremented refcount to 0
07-28 09:44:01.351   320   320 V AudioFlinger: purging stale effects
07-28 09:44:01.351  7567  7567 V Avrcp   : make
,07-28 09:44:01.352  7567  7567 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-28 09:44:01.352  7567  7567 I bluedroid-qcom: get_profile_interface avrcp
07-28 09:44:01.361  7567  7567 V AudioManager: registerRemoteController: size of Media player list: 0
,07-28 09:44:01.363  7567  7567 E AudioManager: No RCC entry present to update
,07-28 09:44:01.363  7567  7567 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 09:44:01.366  7567  7567 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-28 09:44:01.367  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,07-28 09:44:01.367  7567  7567 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-28 09:44:01.370  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 09:44:01.488  1036  2041 V SIM_STK : Menu title from STK is T-Mobile
07-28 09:44:01.488  1036  2041 V SIM_STK : Menu title from STK is T-Mobile
,07-28 09:44:01.564  1036  1951 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-28 09:44:01.572  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 09:44:01.576  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,07-28 09:44:01.577  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 09:44:01.577  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 09:44:01.577  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 09:44:01.577  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 09:44:01.577  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 09:44:01.577  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 09:44:01.577  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 09:44:01.577  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 09:44:01.577  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 09:44:01.577  7567  7567 I BluetoothA2dpServiceJni: classInitNative
07-28 09:44:01.577  7567  7567 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 09:44:01.578  7567  7567 D A2dpStateMachine: make
07-28 09:44:01.580  7567  7567 I bluedroid-qcom: get_profile_interface a2dp
,07-28 09:44:01.581  7567  7850 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 09:44:01.584  7567  7567 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-28 09:44:01.584  7567  7567 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-28 09:44:01.585  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.585  7567  7849 D A2dpStateMachine: Enter Disconnected: -2
07-28 09:44:01.587  7567  7567 I BluetoothHidServiceJni: classInitNative: succeeds
07-28 09:44:01.589  7567  7567 D HidService: Received start request. Starting profile...
,07-28 09:44:01.589  7567  7567 I bluedroid-qcom: get_profile_interface hidhost
07-28 09:44:01.589  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.589  7567  7567 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 09:44:01.591  7567  7567 D HealthService: Received start request. Starting profile...
07-28 09:44:01.594  7567  7567 I bluedroid-qcom: get_profile_interface health
,07-28 09:44:01.594  7567  7567 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-28 09:44:01.594  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.596  7567  7567 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-28 09:44:01.598  7567  7567 D PanService: Received start request. Starting profile...
07-28 09:44:01.598  7567  7567 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 09:44:01.598  7567  7567 I bluedroid-qcom: get_profile_interface pan
07-28 09:44:01.614  7567  7567 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,07-28 09:44:01.614  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.617  7567  7567 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-28 09:44:01.629  7567  7567 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 09:44:01.630  7567  7567 D BtGatt.GattService: Received start request. Starting profile...
07-28 09:44:01.630  7567  7567 D BtGatt.GattService: start()
07-28 09:44:01.630  7567  7567 I bluedroid-qcom: get_profile_interface gatt
07-28 09:44:01.630  7567  7567 D BtGatt.AdvertiseManager: advertise manager created
07-28 09:44:01.635  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.636  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:01.637  7567  7567 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-28 09:44:01.638  7567  7567 V BluetoothMapService: BluetoothMapBinder()
07-28 09:44:01.638  7567  7567 D BluetoothMapService: Received start request. Starting profile...
07-28 09:44:01.638  7567  7567 D BluetoothMapService: start()
07-28 09:44:01.642  7567  7567 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-28 09:44:01.642  7567  7567 D BluetoothMapEmailAppObserver: createReceiver()
,07-28 09:44:01.643  7567  7567 D BluetoothMapEmailAppObserver: initObservers()
07-28 09:44:01.643  7567  7567 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-28 09:44:01.653  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
,07-28 09:44:01.653  7567  7567 D HeadsetStateMachine: Proxy object connected
07-28 09:44:01.654  7567  7567 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-28 09:44:01.654  7567  7567 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-28 09:44:01.663  7567  7567 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 09:44:01.664  7567  7843 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-28 09:44:01.664  7567  7843 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 09:44:01.664  7567  7843 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,07-28 09:44:01.667  7567  7567 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 09:44:01.670  7567  7567 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:01.673  7567  7567 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 09:44:01.676  7567  7567 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 09:44:01.677  7567  7567 V PanService: [BTUI] SIM Extra State :ABSENT
,07-28 09:44:01.681  7567  7567 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-28 09:44:01.684  7567  7567 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-28 09:44:01.684  7567  7567 V BluetoothMapService: Handler(): got msg=1
07-28 09:44:01.685  7567  7567 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 09:44:01.685  7567  7567 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 09:44:01.685  7567  7567 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 09:44:01.685  7567  7567 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:01.686  7567  7567 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-28 09:44:01.686  7567  7821 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-28 09:44:01.686  7567  7821 I bluedroid-qcom: enable
07-28 09:44:01.687  7567  7821 I bt_hci_bdroid: init
07-28 09:44:01.688  7567  7821 I bt_vendor: bt-vendor : init
07-28 09:44:01.688  7567  7821 I bt_vendor: bt-vendor : get_bt_soc_type
07-28 09:44:01.688  7567  7821 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-28 09:44:01.688  7567  7821 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-28 09:44:01.688  7567  7821 D bt_userial_mct: userial_init
07-28 09:44:01.688  7567  7863 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 09:44:01.688  7567  7863 I bt-btu  : btu_task pending for preload complete event
07-28 09:44:01.689  7567  7821 D bt_hci_bdroid: set_power 1
07-28 09:44:01.689  7567  7821 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-28 09:44:01.689  7567  7821 I bt_vendor: Starting hciattach daemon
07-28 09:44:01.689  7567  7821 I bt_vendor: try to set true
07-28 09:44:01.681  7866  7866 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:01.681  7866  7866 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-28 09:44:01.714  7867  7867 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-28 09:44:01.786  7873  7873 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-28 09:44:01.798  7874  7874 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-28 09:44:01.823  7876  7876 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 09:44:01.836  7877  7877 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-28 09:44:01.849  7878  7878 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-28 09:44:01.862  7879  7879 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
07-28 09:44:01.883  7881  7881 I libmdmdetect: ESOC framework not supported
07-28 09:44:01.884  7881  7881 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-28 09:44:01.892  7881  7881 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,07-28 09:44:01.892  7881  7881 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-28 09:44:01.892  7881  7881 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-28 09:44:01.892  7881  7881 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-28 09:44:01.892  7881  7881 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-28 09:44:01.892  7881  7881 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-28 09:44:01.893  7881  7881 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-28 09:44:01.928  7881  7882 E QC-QMI  : qmi_client [7881] 15: failed to locate client data
,07-28 09:44:01.929   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-28 09:44:01.929   461   461 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
07-28 09:44:01.961  7883  7883 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-28 09:44:01.987  7884  7884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-28 09:44:02.042  7567  7821 I bt_vendor: bluetooth satus is on
07-28 09:44:02.042  7567  7821 D bt_hci_bdroid: preload
,07-28 09:44:02.048  7567  7865 D bt_userial_mct: userial_open(port:0)
,07-28 09:44:02.048  7567  7865 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-28 09:44:02.052  7567  7865 I bt_vendor: Done intiailizing UART
07-28 09:44:02.053  7567  7865 I bt_vendor: Done intiailizing UART
07-28 09:44:02.053  7567  7865 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-28 09:44:02.053  7567  7865 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-28 09:44:02.054  7567  7863 I bt-btu  : btu_task received preload complete event
07-28 09:44:02.055  7567  7863 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-28 09:44:02.055  7567  7886 D bt_userial_mct: Entering userial_read_thread()
07-28 09:44:02.055  7567  7863 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-28 09:44:02.061  7567  7863 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_A2D
,07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_BNEP,
07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_BTM,
07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-28 09:44:02.068  7567  7863 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 09:44:02.069  7567  7863 I         : BTE_InitTraceLevels -- TRC_PAN
,07-28 09:44:02.069  7567  7863 I         : BTE_InitTraceLevels -- TRC_SDP,
,07-28 09:44:02.069  7567  7863 I         : BTE_InitTraceLevels -- TRC_GATT
,07-28 09:44:02.069  7567  7863 I         : BTE_InitTraceLevels -- TRC_SMP
,07-28 09:44:02.069  7567  7863 I         : BTE_InitTraceLevels -- TRC_BTAPP,
07-28 09:44:02.069  7567  7863 I         : BTE_InitTraceLevels -- TRC_BTIF,
,07-28 09:44:02.175  7567  7863 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,07-28 09:44:02.175  7567  7863 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0202061 ,
07-28 09:44:02.175  7567  7863 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0202061 ,
,07-28 09:44:02.217  7567  7825 E bt-btif : Calling BTA_HhEnable
07-28 09:44:02.217  7567  7825 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-28 09:44:02.218  7567  7825 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-28 09:44:02.220  7567  7863 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-28 09:44:02.222  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-28 09:44:02.222  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-28 09:44:02.222  7567  7863 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-28 09:44:02.222  7567  7863 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-28 09:44:02.222  7567  7863 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-28 09:44:02.222  7567  7863 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-28 09:44:02.223  7567  7825 D BluetoothAdapterProperties: Name is: G3
07-28 09:44:02.224  7567  7825 D BluetoothAdapterProperties: Scan Mode:20
07-28 09:44:02.225  7567  7825 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 09:44:02.225  7567  7825 D bt_hci_bdroid: postload
07-28 09:44:02.225  7567  7865 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 09:44:02.226  7567  7865 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 09:44:02.227  7567  7863 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-28 09:44:02.227  7567  7865 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 09:44:02.226  7567  7825 D bte_conf: Device ID record 1 : primary
07-28 09:44:02.227  7567  7825 D bte_conf:   vendorId            = 00c4
07-28 09:44:02.227  7567  7825 D bte_conf:   vendorIdSource      = 0001
07-28 09:44:02.227  7567  7825 D bte_conf:   product             = 13a1
07-28 09:44:02.227  7567  7825 D bte_conf:   version             = 1000
07-28 09:44:02.227  7567  7825 D bte_conf:   clientExecutableURL = 
07-28 09:44:02.227  7567  7825 D bte_conf:   serviceDescription  = 
07-28 09:44:02.227  7567  7825 D bte_conf:   documentationURL    = 
07-28 09:44:02.228  7567  7825 D bte_conf: bte_load_did_conf no section named DID2.
07-28 09:44:02.231  7567  7821 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 09:44:02.231  7567  7821 D BluetoothAdapterProperties: ScanMode =  20
07-28 09:44:02.231  7567  7821 D BluetoothAdapterProperties: State =  11
07-28 09:44:02.231  7567  7821 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-28 09:44:02.232  7567  7821 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-28 09:44:02.232  7567  7821 D BluetoothAdapterProperties: Setting state to 12
07-28 09:44:02.232  7567  7821 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 09:44:02.237  7567  7825 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 09:44:02.231  7891  7891 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:02.240  1036  1098 D BluetoothManagerService: Message: 60
07-28 09:44:02.240  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-28 09:44:02.240  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
07-28 09:44:02.241  7567  7863 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 09:44:02.241  7567  7863 W bt-smp  : Plain text(LSB ~ MSB) = 99 c7 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:44:02.241  7567  7863 W bt-smp  : Encrypted text(LSB ~ MSB) = 91 a2 11 68 b4 19 f7 5b 73 04 68 c0 19 64 33 ca 
07-28 09:44:02.241  7567  7865 D bt_hci_bdroid: Used up Tx Cmd credits
07-28 09:44:02.242  7567  7863 W bt-btm  : Stopping oneshot timer
07-28 09:44:02.242  7567  7825 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 09:44:02.231  7891  7891 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:02.248  7567  7886 E bt_mct  : hci lib postload completed
,07-28 09:44:02.271  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:44:02.271  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:44:02.271  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:44:02.271  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:44:02.271  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:44:02.271  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:44:02.271  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:44:02.271  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:44:02.276  7567  7821 I BluetoothAdapterState: Entering On State
07-28 09:44:02.284  7567  7863 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 09:44:02.284  7567  7863 W bt-smp  : Plain text(LSB ~ MSB) = 60 79 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:44:02.284  7567  7863 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 d2 a3 63 e3 38 49 f9 0d de f9 2e a3 95 d1 d1 
,07-28 09:44:02.286  7567  7863 W bt-btm  : Stopping oneshot timer
07-28 09:44:02.298  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:44:02.305  7567  7825 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 09:44:02.306  7567  7825 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-28 09:44:02.309  7567  7863 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 09:44:02.309  7567  7863 W bt-smp  : Plain text(LSB ~ MSB) = 3c 6d 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:44:02.309  7567  7863 W bt-smp  : Encrypted text(LSB ~ MSB) = df 56 c0 82 f3 03 c2 ad 02 a3 2c 98 e5 13 6e f2 
07-28 09:44:02.309  7567  7863 W bt-btm  : Stopping oneshot timer
07-28 09:44:02.317  7567  7821 D LGBluetoothServiceAdapter: [BTUI] OnState
07-28 09:44:02.318  7567  7821 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-28 09:44:02.318  7567  7821 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,07-28 09:44:02.321  7567  7821 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-28 09:44:02.322  6761  7450 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 09:44:02.326  7567  7821 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-28 09:44:02.328  7567  7863 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-28 09:44:02.328  7567  7863 W bt-smp  : Plain text(LSB ~ MSB) = 64 eb 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:44:02.328  7567  7863 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 fd 78 96 5e 77 55 81 de a2 8b d1 66 81 52 be 
07-28 09:44:02.328  7567  7863 W bt-btm  : Stopping oneshot timer
07-28 09:44:02.355  6761  6776 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 09:44:02.362  7896  7896 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-28 09:44:02.371  1879  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 09:44:02.375  7567  7863 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,07-28 09:44:02.375  7567  7863 W bt-smp  : Plain text(LSB ~ MSB) = 63 2c 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-28 09:44:02.375  7567  7863 W bt-smp  : Encrypted text(LSB ~ MSB) = 51 0f 96 d5 76 6c e5 bb b0 f5 0e 4a 68 29 c7 0a 
,07-28 09:44:02.382  7567  7863 W bt-btm  : Stopping oneshot timer
07-28 09:44:02.383  1879  3978 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:44:02.384  6761  6761 D BluetoothA2dp: Proxy object connected
07-28 09:44:02.384  6761  6761 D A2dpProfile: Bluetooth service connected
07-28 09:44:02.385  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 09:44:02.390  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 09:44:02.390  6761  7450 D BluetoothMap: onBluetoothStateChange: up=true
07-28 09:44:02.392  6761  6776 D BluetoothPan: onBluetoothStateChange on: true
07-28 09:44:02.392  6761  6776 D BluetoothPan: onBluetoothStateChange call bindService
,07-28 09:44:02.395  6761  6761 D BluetoothMap: Proxy object connected
07-28 09:44:02.395  6761  6761 D MapProfile: Bluetooth service connected
07-28 09:44:02.395  6761  6761 D BluetoothMap: getConnectedDevices()
07-28 09:44:02.396  7567  7584 V BluetoothMapService: getConnectedDevices()
07-28 09:44:02.397  1036  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:44:02.398  1036  1036 D BluetoothHeadset: Proxy object connected
07-28 09:44:02.399  6761  6761 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 09:44:02.399  6761  7450 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 09:44:02.399  6761  6761 D PanProfile: Bluetooth service connected
07-28 09:44:02.402  6761  6776 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:44:02.402  6761  6761 D BluetoothInputDevice: Proxy object connected
07-28 09:44:02.403  6761  6761 D HidProfile: Bluetooth service connected
07-28 09:44:02.404  1879  3980 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 09:44:02.405  6761  6761 D BluetoothHeadset: Proxy object connected
,07-28 09:44:02.405  6761  6761 D HeadsetProfile: Bluetooth service connected
07-28 09:44:02.406  1879  1879 D BluetoothHeadset: Proxy object connected
07-28 09:44:02.407  1036  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 09:44:02.408  1036  1036 D BluetoothA2dp: Proxy object connected
07-28 09:44:02.409  1036  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-28 09:44:02.410  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-28 09:44:02.411  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-28 09:44:02.413  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:02.415  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-28 09:44:02.415  1978  1978 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:02.415  1036  1098 D BluetoothManagerService: Message: 40
07-28 09:44:02.415  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-28 09:44:02.416  1978  2215 D LGBluetoothAPIService: Message: 1
07-28 09:44:02.416  1978  2215 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-28 09:44:02.416  1978  2215 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
07-28 09:44:02.416  1978  2215 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-28 09:44:02.420  6761  6761 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,07-28 09:44:02.421  7567  7567 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:02.421  7567  7567 D BluetoothMapService: STATE_ON
07-28 09:44:02.437  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:02.437  7567  7567 V BluetoothPbapService: Pbap Service onCreate
07-28 09:44:02.437  7567  7567 V BluetoothPbapService: Starting PBAP service
07-28 09:44:02.439  7567  7567 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-28 09:44:02.439  7567  7567 V BluetoothMapService: Handler(): got msg=1
,07-28 09:44:02.440  7567  7567 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-28 09:44:02.441  7567  7567 V BluetoothPbapService: Pbap Service onBind
07-28 09:44:02.442  7567  7915 D BluetoothMapMasInstance: MAS initSocket()
07-28 09:44:02.442  7567  7567 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:02.442  7567  7567 V BluetoothPbapService: state: 12
07-28 09:44:02.442  7567  7567 V BluetoothPbapService: Handler(): got msg=1
07-28 09:44:02.443  7567  7567 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-28 09:44:02.443  7567  7915 D BluetoothMapMasInstance:   masId = 00
07-28 09:44:02.443  7567  7915 D BluetoothMapMasInstance:   msgTypes = 0e
07-28 09:44:02.443  7567  7915 D BluetoothMapMasInstance:   masName = SMS/MMS
07-28 09:44:02.443  7567  7915 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-28 09:44:02.444  7567  7916 V BluetoothPbapService: Pbap Service initSocket
07-28 09:44:02.444  1036  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:02.445  1036  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:02.446  7567  7915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:44:02.449  7567  7916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:44:02.451  7567  7916 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
,07-28 09:44:02.451  7567  7916 V BluetoothPbapService: Succeed to create listening socket 
07-28 09:44:02.452  7567  7916 V BluetoothPbapService: Accepting socket connection...
07-28 09:44:02.452  7567  7825 D BluetoothAdapterProperties: Scan Mode:21
07-28 09:44:02.452  7567  7915 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-28 09:44:02.452  7567  7915 V BluetoothMapMasInstance: Succeed to create listening socket 
07-28 09:44:02.452  7567  7915 D BluetoothMapMasInstance: Accepting socket connection...
07-28 09:44:02.453  7567  7825 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-28 09:44:02.455  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:02.548  1036  1051 I art     : Explicit concurrent mark sweep GC freed 26109(1283KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.929ms total 126.681ms
07-28 09:44:02.549  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-28 09:44:02.550  6761  6761 D BluetoothPbap: Proxy object connected
07-28 09:44:02.550  6761  6761 D PbapServerProfile: Bluetooth service connected
,07-28 09:44:02.552  7567  7567 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-28 09:44:02.552  7567  7567 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:02.552  7567  7567 V BluetoothPbapReceiver: ***********state = 12
07-28 09:44:02.556  2268  2268 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 09:44:02.556  2268  2268 D c       : Getting all permits...
07-28 09:44:02.556  2268  2268 D a       : Opening database...
07-28 09:44:02.559  2268  2268 D a       : Opening database auth.proximity.permit_store...
07-28 09:44:02.559  2268  2268 D a       : Closing database...
07-28 09:44:02.560  6761  6761 D DockEventReceiver: finishStartingService: stopping service
07-28 09:44:02.571  6761  6761 D BluetoothPermissionRequest: onReceive
,07-28 09:44:02.573  6761  6761 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-28 09:44:02.575  6761  6761 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-28 09:44:02.584  7567  7567 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-28 09:44:02.585  7567  7567 I LGBluetoothOppAdapter: [BTUI] startOppService()
,07-28 09:44:02.591  7567  7567 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-28 09:44:02.619  7567  7567 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-28 09:44:02.619  7567  7567 V BtOppService: onCreate
,07-28 09:44:02.623  7567  7567 V BluetoothOppNotification: send message
,07-28 09:44:02.626  7567  7567 V BtOppService: Starting RfcommListener
07-28 09:44:02.631  7567  7567 D BluetoothOppPreference: Dumping Names:  
07-28 09:44:02.631  7567  7567 D BluetoothOppPreference: {}
07-28 09:44:02.631  7567  7567 D BluetoothOppPreference: Dumping Channels:  
07-28 09:44:02.631  7567  7567 D BluetoothOppPreference: {}
07-28 09:44:02.632  7567  7567 V BtOppService: onStartCommand
07-28 09:44:02.633  7567  7924 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,07-28 09:44:02.635  7567  7567 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:02.635  7567  7567 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-28 09:44:02.638  7567  7567 V BluetoothOppNotification: new notify threadi!
07-28 09:44:02.639  7567  7567 V BluetoothOppNotification: send delay message
07-28 09:44:02.640  7567  7567 V BtOppService: start RfcommListener
07-28 09:44:02.641  7567  7921 V BtOppService: Deleted complete outbound shares, number =  0
07-28 09:44:02.642  7567  7924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 09:44:02.642  7567  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-28 09:44:02.644  7567  7921 V BtOppService: Deleted complete inbound failed shares, number = 0
07-28 09:44:02.644  7567  7924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e07bf1c on behalf of 
07-28 09:44:02.644  7567  7567 V BtOppService: RfcommListener started
07-28 09:44:02.645  7567  7921 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-28 09:44:02.645  7567  7926 V BtOppRfcommListener: Starting RFCOMM listener....
07-28 09:44:02.647  7567  7921 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@112f1725 on behalf of 
,07-28 09:44:02.647  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:02.648  7567  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35b850fa on behalf of 
07-28 09:44:02.649  7567  7925 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-28 09:44:02.650  7567  7926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:44:02.651  7567  7926 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
07-28 09:44:02.651  7567  7926 V BtOppRfcommListener: Started RFCOMM listener....
07-28 09:44:02.651  7567  7926 I BtOppRfcommListener: Accept thread started.
07-28 09:44:02.651  7567  7926 V BtOppRfcommListener: Accepting connection...
07-28 09:44:02.652  7567  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 09:44:02.653  7567  7924 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 09:44:02.654  7567  7924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 09:44:02.654  7567  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2382d6ab on behalf of 
07-28 09:44:02.655  7567  7925 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 09:44:02.655  7567  7924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f5fb108 on behalf of 
07-28 09:44:02.656  7567  7924 V BluetoothOppNotification: update too frequent, put in queue
07-28 09:44:02.657  7567  7925 V BluetoothOppNotification: outbound notification was removed.
07-28 09:44:02.657  7567  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 09:44:02.657  7567  7924 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 09:44:02.658  7567  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7df00a1 on behalf of 
07-28 09:44:02.659  7567  7925 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-28 09:44:02.660  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:02.660  7567  7567 V BluetoothFtpService: Ftp Service onCreate
07-28 09:44:02.660  7567  7567 I BluetoothFtpService: Ftp Service onCreate
07-28 09:44:02.660  7567  7567 V BluetoothFtpService: Ftp Service onStartCommand
07-28 09:44:02.660  7567  7567 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:02.661  7567  7567 V BluetoothFtpService: Starting Listening on sockets
07-28 09:44:02.661  7567  7925 V BluetoothOppNotification: inbound notification was removed.
07-28 09:44:02.661  7567  7925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 09:44:02.661  7567  7567 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-28 09:44:02.661  7567  7567 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-28 09:44:02.661  7567  7567 V BluetoothSapReceiver: SapReceiver onReceive 
07-28 09:44:02.661  7567  7567 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:02.661  7567  7567 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-28 09:44:02.661  7567  7567 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-28 09:44:02.662  7567  7925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c963287 on behalf of 
07-28 09:44:02.664  7567  7567 V BtOppService: ContentObserver received notification
07-28 09:44:02.664  7567  7567 V BtOppService: ContentObserver received notification
07-28 09:44:02.664  7567  7567 V BluetoothFtpService: Handler(): got msg=1
07-28 09:44:02.665  7567  7567 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-28 09:44:02.665  7567  7567 V BluetoothFtpService: Ftp Service initSocket
07-28 09:44:02.666  7567  7927 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-28 09:44:02.667  7567  7927 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-28 09:44:02.668  7567  7927 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ac2d5b4 on behalf of 
07-28 09:44:02.668  7567  7927 V BluetoothOppNotification: update too frequent, put in queue
07-28 09:44:02.669  7567  7927 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-28 09:44:02.671  1036  2040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:02.671  7567  7567 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 09:44:02.673  7567  7567 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-28 09:44:02.674  7567  7928 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-28 09:44:02.693  7567  7567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34c88c60
07-28 09:44:02.693  7567  7567 V BluetoothSapService: Sap Service onCreate
,07-28 09:44:02.695  7567  7567 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:44:02.695  7567  7567 V BluetoothSapService: state: 12
07-28 09:44:02.695  7567  7567 V BluetoothSapService: Starting SAP server process
07-28 09:44:02.698  7567  7567 V BluetoothSapService: SAP Service startRfcommListenerThread
07-28 09:44:02.691  7929  7929 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:02.691  7929  7929 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:02.699  7567  7930 V BluetoothSapService: Sap Service initRfcommSocket
07-28 09:44:02.700  1036  1927 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:02.700  7567  7930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:44:02.701  7567  7930 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-28 09:44:02.701  7567  7930 V BluetoothSapService: Succeed to create listening socket 
07-28 09:44:02.702  7567  7930 V BluetoothSapService: Accepting socket connection...
07-28 09:44:02.713  7929  7929 V BT_SAP  : Event pipe created
07-28 09:44:02.713  7929  7929 V BT_SAP  : create_server_socket qcom.sap.server
07-28 09:44:02.713  7929  7929 V BT_SAP  : created socket fd 6
,07-28 09:44:03.179  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:44:03.179  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:44:03.179  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:44:03.179  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:44:03.179  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:44:03.179  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:44:03.179  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:44:03.179  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:44:03.191  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:44:03.192  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:03.193  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a77f78f added. We now have 8 listener(s)
07-28 09:44:03.193  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:03.199  1036  1927 D WifiServiceImplEx: setWifiEnabled: false pid=6576, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 09:44:03.200  1036  1927 D WifiService: setWifiEnabled: false pid=6576, uid=10118
07-28 09:44:03.200  1036  1927 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 09:44:03.208  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:03.209  1036  1657 D WifiServiceImplEx: setWifiEnabled: true pid=6576, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-28 09:44:03.211  1036  1657 D WifiService: setWifiEnabled: true pid=6576, uid=10118
07-28 09:44:03.211  1036  1657 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 09:44:03.226  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-28 09:44:03.226  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-28 09:44:03.227  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-28 09:44:03.231  1036  1394 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-28 09:44:03.231  1036  1394 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-28 09:44:03.233  1036  1394 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-28 09:44:03.233  1036  1394 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 09:44:03.233  1036  1394 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-28 09:44:03.233  1036  1394 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-28 09:44:03.234  1036  1394 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-28 09:44:03.234  1036  1394 E WifiHW  : unknown target_country: EU , set to default
07-28 09:44:03.234  1036  1394 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-28 09:44:03.234  1036  1394 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-28 09:44:03.234  1036  1394 I WifiUtil: gEnableBmps=1
07-28 09:44:03.652  7567  7567 V BluetoothOppNotification: new notify threadi!
07-28 09:44:03.652  7567  7567 V BluetoothOppNotification: send delay message
,07-28 09:44:03.704  7567  7943 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-28 09:44:03.739  7567  7943 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f919920 on behalf of 
07-28 09:44:03.740  7567  7943 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-28 09:44:03.745  7567  7943 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-28 09:44:03.746  7567  7943 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c6622d9 on behalf of 
07-28 09:44:03.747  7567  7943 V BluetoothOppNotification: outbound: succ-0  fail-0
07-28 09:44:03.748  7567  7943 V BluetoothOppNotification: outbound notification was removed.
07-28 09:44:03.749  7567  7943 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-28 09:44:03.749  7567  7943 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32f1249e on behalf of 
07-28 09:44:03.750  7567  7943 V BluetoothOppNotification: inbound: succ-0  fail-0
07-28 09:44:03.751  7567  7943 V BluetoothOppNotification: inbound notification was removed.
07-28 09:44:03.752  7567  7943 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-28 09:44:03.753  7567  7943 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a08eb7f on behalf of 
,07-28 09:44:03.879   316   896 D SoftapController: Softap fwReload - Ok
,07-28 09:44:03.883  1036  1394 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (646ms)
07-28 09:44:03.889   316   896 D CommandListener: Setting iface cfg
07-28 09:44:03.889   316   896 D CommandListener: Trying to bring down wlan0
07-28 09:44:03.894  1036  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 09:44:03.909   316   896 D CommandListener: Clearing all IP addresses on wlan0
,07-28 09:44:03.920  1036  1394 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-28 09:44:03.921  7951  7951 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:03.921  7951  7951 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:03.936  1036  1394 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 09:44:03.936  1036  1394 E WifiStateMachine: useWiFiOffloading() : false
07-28 09:44:03.936  1036  1394 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 09:44:03.957  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,07-28 09:44:03.962  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:03.963  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-28 09:44:03.969  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:03.969  1036  1394 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 09:44:03.969  1036  1394 D WifiMonitor: connecting to supplicant
,07-28 09:44:03.994  7951  7951 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 09:44:04.012  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 09:44:04.012  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 09:44:04.012  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 09:44:04.012  6761  6761 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-28 09:44:04.016  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 09:44:04.016  6761  6761 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 09:44:04.017  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-28 09:44:04.017  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 09:44:04.017  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 09:44:04.017  6761  6761 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 09:44:04.017  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-28 09:44:04.018  6761  6761 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 09:44:04.025  7951  7951 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 09:44:04.025  7951  7951 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-28 09:44:04.029  1036  1098 D Tethering: InitialState.processMessage what=4
,07-28 09:44:04.058  1036  1927 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7969 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-28 09:44:04.060  1036  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 09:44:04.117  7951  7951 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 09:44:04.151  1036  2091 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7990 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-28 09:44:04.156  7969  7988 W FormManager: Network not available. Please check & try again.
07-28 09:44:04.162  7969  7989 V FormManager: Network unavailable.
,07-28 09:44:04.166  7969  7989 V FormManager: Network unavailable.
07-28 09:44:04.180  7951  7951 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-28 09:44:04.184  1036  1765 I ActivityManager: Killing 7059:com.lge.drmservice/u0a62 (adj 15): empty #17
07-28 09:44:04.186  7951  7951 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-28 09:44:04.186  7951  7951 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-28 09:44:04.187  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-28 09:44:04.187  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-28 09:44:04.187  1036  8008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-28 09:44:04.187  1036  8008 D WifiMonitor: Dropping event because (p2p0) is stopped
07-28 09:44:04.187  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-28 09:44:04.187  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-28 09:44:04.187  1036  8008 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-28 09:44:04.187  1036  8008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-28 09:44:04.188  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-28 09:44:04.188  1036  1394 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-28 09:44:04.189  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:44:04.189  1036  1394 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:44:04.190  1036  1394 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:44:04.190  1036  1394 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:44:04.191  1036  1394 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-28 09:44:04.191  1036  1394 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-28 09:44:04.191  1036  1394 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-28 09:44:04.192  1036  1394 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-28 09:44:04.192  1036  1394 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,07-28 09:44:04.211  1036  1394 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-28 09:44:04.211  1036  1394 E WifiStateMachine: useWiFiOffloading() : false
07-28 09:44:04.211  1036  1394 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-28 09:44:04.212  1036  1394 D WifiNative-wlan0: doBoolean: SET update_config 1
07-28 09:44:04.212  1036  2041 W libprocessgroup: failed to open /acct/uid_10062/pid_7059/cgroup.procs: No such file or directory
07-28 09:44:04.212  1036  1394 D WifiNative-wlan0: SET update_config 1: returned true
07-28 09:44:04.212  1036  1394 D WifiConfigStore: Loading config and enabling all networks 
07-28 09:44:04.212  1036  1394 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-28 09:44:04.213  1036  1394 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-28 09:44:04.214  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.215  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.215  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.215  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.215  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-28 09:44:04.215  1978  1978 D WfdService: Waiting for WifiP2p enabling
07-28 09:44:04.216  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:04.216  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-28 09:44:04.216  1036  1398 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-28 09:44:04.219  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:44:04.219  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:44:04.219  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:44:04.219  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:44:04.219  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:44:04.219  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:44:04.219  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:44:04.219  6576  6576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:44:04.221  6576  6576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:44:04.225  1036  1394 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-28 09:44:04.234  1036  1394 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-28 09:44:04.235  1036  1394 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 09:44:04.236  1036  1394 D WifiStateMachine: enableVerboseLogging : level 2
07-28 09:44:04.236  1036  1394 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-28 09:44:04.236  1036  1394 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-28 09:44:04.236  1036  1394 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-28 09:44:04.237  1036  1394 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-28 09:44:04.237  1036  1394 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-28 09:44:04.238  1036  1394 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-28 09:44:04.238  1036  1394 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-28 09:44:04.239  1036  1394 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-28 09:44:04.239  1036  1394 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-28 09:44:04.239  1036  1394 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-28 09:44:04.239  1036  1394 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-28 09:44:04.240  1036  1394 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-28 09:44:04.240  1036  1394 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-28 09:44:04.240  1036  1394 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-28 09:44:04.242  1978  1978 D WfdsService: Supplicant Connection state is changed : true
07-28 09:44:04.242  1978  2356 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-28 09:44:04.242  1978  2356 D WfdsService: Set the WFDS Monitor: true
07-28 09:44:04.242  1036  1394 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 09:44:04.242  1978  2356 D WfdsMonitor: WfdsMonitorThread create
07-28 09:44:04.242  1036  1394 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-28 09:44:04.242  1978  2356 D WfdsMonitor: WFDS Monitor is created and started
07-28 09:44:04.242  1978  2356 D WfdsService: WiFi: Supplicant connection re-established
07-28 09:44:04.242  7595  7595 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.243  1036  1394 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-28 09:44:04.243  1036  1394 D WifiNative-HAL: Setting external_sim to 1
07-28 09:44:04.243  1036  1394 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-28 09:44:04.243  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:44:04.243  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:44:04.243  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:44:04.243  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:44:04.243  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:44:04.243  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:44:04.243  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:44:04.243  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:44:04.243  1036  1394 D WifiNative-wlan0: SET external_sim 1: returned true
07-28 09:44:04.243  1978  8011 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-28 09:44:04.243  1036  1394 I WifiNative-HAL: startHal
07-28 09:44:04.243  1036  1394 D wifi    : setting scan oui 0x956cb300
07-28 09:44:04.244  1978  8011 E CtrlSupplicant: Succeed to open control connection
07-28 09:44:04.244  1036  1394 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 09:44:04.244  1036  1394 I WifiNative-HAL: startHal
07-28 09:44:04.244  1978  8011 E CtrlSupplicant: Succeed to open monitor connection
07-28 09:44:04.244  1036  1394 D wifi    : setting scan oui 0x956cb300
07-28 09:44:04.244  19,78  8011 D WfdsMonitor: Supplicant connection established
07-28 09:44:04.244  1036  1394 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-28 09:44:04.244  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:44:04.244  1978  2356 D WfdsService: Connected to the supplicant for wfds
07-28 09:44:04.244  1036  1394 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-28 09:44:04.245  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-28 09:44:04.245  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-28 09:44:04.245  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-28 09:44:04.245  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 09:44:04.245  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-28 09:44:04.245  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 09:44:04.245  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-28 09:44:04.246  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-28 09:44:04.246  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-28 09:44:04.246  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 09:44:04.246  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 09:44:04.246  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 09:44:04.246  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-28 09:44:04.246  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,07-28 09:44:04.248  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-28 09:44:04.248  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-28 09:44:04.248  7951  7951 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,07-28 09:44:04.248  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-28 09:44:04.248  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-28 09:44:04.249  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-28 09:44:04.249  6576  6706 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-28 09:44:04.249  1036  1394 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-28 09:44:04.249  1036  1394 E WifiNative: : [155,389,828 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-28 09:44:04.250  1036  1394 D WifiNative-wlan0: doBoolean: RECONNECT
07-28 09:44:04.250  6576  6706 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-28 09:44:04.250  1036  1394 D WifiNative-wlan0: RECONNECT: returned true
07-28 09:44:04.250  1036  1394 D WifiNative-wlan0: doString: [STATUS]
07-28 09:44:04.250  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-28 09:44:04.250  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-28 09:44:04.251  1036  1394 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 09:44:04.251  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 1
07-28 09:44:04.251  1036  1394 D WifiNative-wlan0: SET ps 1: returned true
07-28 09:44:04.251  1036  1392 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.252  6576  6706 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16630fb7 Bundle[{}]
07-28 09:44:04.252   316   896 D CommandListener: Setting iface cfg
07-28 09:44:04.252   316   896 D CommandListener: Trying to bring up p2p0
07-28 09:44:04.252  1036  1392 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 09:44:04.253  1036  1392 D LGWifiP2pService: P2pEnablingState
07-28 09:44:04.253  1036  1392 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.253  1036  1392 D LGWifiP2pService: P2p socket connection successful
07-28 09:44:04.253  1036  1392 D LGWifiP2pService: P2pEnabledState
07-28 09:44:04.253  1036  1392 D LGWifiP2pService: sending p2p connection changed broadcast
07-28 09:44:04.253  7990  7990 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:44:04.254  6576  6706 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 09:44:04.254  6576  6706 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-28 09:44:04.254  1036  1392 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-28 09:44:04.254  1978  1978 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-28 09:44:04.254  1978  1978 D WfdsService: WifiP2pState is changed : true
07-28 09:44:04.254  1978  2356 D WfdsService: Receive the WFDS_ENABLE Method
07-28 09:44:04.254  1978  2356 D WfdsService: Set the WFDS Monitor: true
07-28 09:44:04.254  1978  2356 D WfdsService: Connected to the supplicant for wfds
07-28 09:44:04.254  1978  2356 D WfdsJNI : doCommand: WFDS_SET TRUE
,07-28 09:44:04.254  6576  6706 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-28 09:44:04.255  7951  7951 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-28 09:44:04.255  1978  2356 D WfdsService: selectPreferredScanChannel [36]
07-28 09:44:04.255  1036  1392 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-28 09:44:04.255  1978  2356 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-28 09:44:04.255  1036  1392 D WifiNative-p2p0: doBoolean: SET device_name G3
07-28 09:44:04.255  1036  1392 D WifiNative-p2p0: SET device_name G3: returned true
07-28 09:44:04.255  1036  1392 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-28 09:44:04.255  1036  1392 D LGWifiP2pService: before postfix = G3
07-28 09:44:04.255  1036  1392 D WifiServerServiceExt: postfix byte check : 2
07-28 09:44:04.255  6576  6706 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-28 09:44:04.255  1036  1392 D LGWifiP2pService: after postfix = G3
07-28 09:44:04.255  1036  1392 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-28 09:44:04.255  1036  1392 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-28 09:44:04.255  1036  1392 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-28 09:44:04.256  1036  1392 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-28 09:44:04.256  1036  1392 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-28 09:44:04.256  6576  6706 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-28 09:44:04.256  1036  1392 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-28 09:44:04.256  1036  1392 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-28 09:44:04.256  1036  1392 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-28 09:44:04.256  1036  1392 D WifiNative-HAL: p2pGetDeviceAddress
07-28 09:44:04.256  6576  6706 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-28 09:44:04.256  1036  1392 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-28 09:44:04.257  1036  1392 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-28 09:44:04.257  1036  1392 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-28 09:44:04.257  1036  1392 D WifiNative-p2p0: P2P_FLUSH: returned true
07-28 09:44:04.257  1036  1392 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-28 09:44:04.258  1036  1392 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-28 09:44:04.258  1036  1392 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-28 09:44:04.258  1036  1392 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-28 09:44:04.258  1036  1392 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-28 09:44:04.259  1978  1978 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-28 09:44:04.260  1978  1978 D WfdsService: isConnected: false
07-28 09:44:04.260  1978  1978 I WfdStateTracker: handleP2pThisDeviceChanged
07-28 09:44:04.260  1978  1978 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-28 09:44:04.260  1978  1978 D WfdsService: Update P2p Interface State: 3
,07-28 09:44:04.262  6576  6706 I System.out: Running OutgoingSocketThread
07-28 09:44:04.264  6576  8013 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 856)
,07-28 09:44:04.265  6576  8013 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35270
07-28 09:44:04.265  6576  8013 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
07-28 09:44:04.266  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 09:44:04.266  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-28 09:44:04.266  1036  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.266  1036  1558 I WifiNative-HAL: startHal
07-28 09:44:04.266  1036  1394 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-28 09:44:04.266  1036  1559 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.267  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 09:44:04.267  1036  1394 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-28 09:44:04.267  1036  1394 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-28 09:44:04.268  1036  1394 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-28 09:44:04.268  1036  1392 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-28 09:44:04.268  1036  1392 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-28 09:44:04.269  1036  1392 D LGWifiP2pService: InactiveState
07-28 09:44:04.269  1036  1394 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-28 09:44:04.269  1036  1392 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.269  1036  1558 D wifi    : getting scan capabilities on interface[1] = 0x956cb300
07-28 09:44:04.269  1036  1558 D wifi    : failed to get capabilities : -3
07-28 09:44:04.269  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.269  1036  1558 E WifiScanningService: could not get scan capabilities
07-28 09:44:04.269  1036  1392 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-28 09:44:04.269  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 09:44:04.270  7951  7951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:44:04.270  1036  8008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 09:44:04.270  1036  8008 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:44:04.270  1036  8008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:44:04.270  1036  8008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:44:04.270  7951  7951 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 09:44:04.271  1978  8011 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 09:44:04.271  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:04.271  1036  1392 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-28 09:44:04.271  1036  1392 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.271  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.271  1036  1392 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.271  7951  7951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.272  1036  1996 I ActivityManager: Killing 7076:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
07-28 09:44:04.272  1978  8011 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:44:04.272  1036  1392 D LGWifiP2pSe,rvice: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.272  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.272  1036  1392 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.272  1036  1036 E WifiServerServiceExt: No p2p device connected
07-28 09:44:04.272  1036  1392 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.272  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.272  1036  1392 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.272  7951  7951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.272  1036  1392 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.272  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.272  1036  8008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:44:04.272  1036  8008 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.273  1036  8008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.273  1036  8008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.273  1036  8008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:44:04.273  1036  8008 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.273  1036  8008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.273  1036  8008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.273  1978  8011 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:44:04.273  1036  1392 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.273  1978  2356 W WfdsService: DefaultState - msg [9441285] is not handled
07-28 09:44:04.274  1036  1394 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-28 09:44:04.274  1036  1394 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-28 09:44:04.274  1036  1394 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-28 09:44:04.274  7951  7951 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,07-28 09:44:04.275  1036  1394 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-28 09:44:04.275  1036  1394 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-28 09:44:04.276  1036  1394 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-28 09:44:04.276  1036  1394 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-28 09:44:04.276  7951  7951 E wpa_supplicant: disconnect_rssi_lvl: -100
07-28 09:44:04.277  1036  1394 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 09:44:04.278  1036  1394 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 09:44:04.278  1036  1394 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-28 09:44:04.278  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-28 09:44:04.278  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-28 09:44:04.279  7951  7951 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:44:04.279  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-28 09:44:04.279  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:44:04.279  1036  8008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:44:04.279  1036  8008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-28 09:44:04.279  7951  7951 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-28 09:44:04.280  7951  7951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.280  1036  8008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:44:04.280  1036  8008 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.280  1036  8008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.280  1036  8008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.280  7951  7951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.280  1036  8008 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:44:04.280  1036  8008 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.280  1036  8008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.280  1036  8008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-28 09:44:04.282  1978  8011 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:44:04.282  1978  8011 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-28 09:44:04.282  1036  1394 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-28 09:44:04.282  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.282  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:04.282  1036  1394 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-28 09:44:04.283  1036  1394 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-28 09:44:04.283  1036  1394 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-28 09:44:04.283  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-28 09:44:04.283  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-28 09:44:04.283  7951  7951 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 09:44:04.284  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE typ,e=UNKNOWN]
07-28 09:44:04.284  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 09:44:04.284  1036  8008 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 09:44:04.284  1036  8008 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-28 09:44:04.284  1036  1394 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-28 09:44:04.284  1036  1394 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-28 09:44:04.285  1036  1394 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-28 09:44:04.285  1036  1394 D WifiNative-wlan0: doBoolean: SCAN
07-28 09:44:04.285  1036  1394 D WifiNative-wlan0: SCAN: returned false
07-28 09:44:04.285  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=155426  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,07-28 09:44:04.321  1036  2091 W libprocessgroup: failed to open /acct/uid_10085/pid_7076/cgroup.procs: No such file or directory
07-28 09:44:04.325  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:04.325  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:44:04.326  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.326  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.326  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-28 09:44:04.326  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=155467  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-28 09:44:04.326  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:04.327  1036  1394 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 09:44:04.328  1036  1394 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 09:44:04.328  1036  1394 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 09:44:04.329  1036  1394 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 09:44:04.330  1036  1394 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-28 09:44:04.338  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:44:04.339  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
07-28 09:44:04.344  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 09:44:04.345  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 09:44:04.345  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 09:44:04.345  6761  6761 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 09:44:04.345  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 09:44:04.346  6761  6761 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 09:44:04.346  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-28 09:44:04.346  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 09:44:04.346  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 09:44:04.346  6761  6761 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 09:44:04.346  6761  6761 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 09:44:04.357  7990  7990 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:44:04.362  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-28 09:44:04.366  7969  8015 W FormManager: Network not available. Please check & try again.
07-28 09:44:04.369  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 09:44:04.377  7969  8016 V FormManager: Network unavailable.
07-28 09:44:04.391  7969  8016 V FormManager: Network unavailable.
,07-28 09:44:04.392  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-28 09:44:04.393  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-28 09:44:04.395  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:44:04.397  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-28 09:44:04.402  4298  8017 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-28 09:44:04.408  4298  8018 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-28 09:44:04.408  4298  8018 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-28 09:44:04.441  1036  2120 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8019 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-28 09:44:04.582  8019  8019 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 09:44:04.582  8019  8019 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-28 09:44:04.596  8019  8019 V [BNRBootReceiver]: Boot Receiver Return
07-28 09:44:04.597  8019  8019 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-28 09:44:04.667  1036  2005 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8037 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-28 09:44:04.668  1036  2005 I ActivityManager: Killing 7118:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,07-28 09:44:04.779  1036  2115 W libprocessgroup: failed to open /acct/uid_10093/pid_7118/cgroup.procs: No such file or directory
,07-28 09:44:04.835  7951  7951 E wpa_supplicant: USIM:  scard_init function
07-28 09:44:04.835  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-28 09:44:04.836  1036  8008 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-28 09:44:04.836  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-28 09:44:04.836  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
07-28 09:44:04.836  7951  7951 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-28 09:44:04.836  1036  8008 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-28 09:44:04.837  1036  1394 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 09:44:04.838  1036  1394 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 09:44:04.839  1036  1394 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 09:44:04.840  1036  1394 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
07-28 09:44:04.840  1036  1394 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,07-28 09:44:04.843  8037  8037 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 09:44:04.845  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-28 09:44:04.845  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-28 09:44:04.862  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=156002  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-28 09:44:04.865  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=156005  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-28 09:44:04.868  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:04.868  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:44:04.869  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:04.873  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.873  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.873  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,07-28 09:44:04.880  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.880  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.880  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 09:44:04.880  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:44:04.881  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-28 09:44:04.882  8037  8037 D PluginManager: init()
07-28 09:44:04.890  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:04.890  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:44:04.891  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 09:44:04.960  7951  7951 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-28 09:44:04.966  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-28 09:44:04.966  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-28 09:44:04.967  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-28 09:44:04.967  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-28 09:44:04.969  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=156109  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 09:44:04.970  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=156110  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-28 09:44:04.971  1036  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 09:44:04.971  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:44:04.971  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:44:04.972  1036  1394 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156112
07-28 09:44:04.972  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:44:04.972  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-28 09:44:04.973  1036  1394 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156113
07-28 09:44:04.973  1036  1394 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156113
07-28 09:44:04.974  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156114
07-28 09:44:04.974  1036  1394 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156114
07-28 09:44:04.975  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=156115  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,07-28 09:44:04.982  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=156122  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-28 09:44:04.982  1036  1394 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:44:04.983  1036  1394 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:44:04.983  1036  1394 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:44:04.984  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:44:04.984  1036  1394 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-28 09:44:04.986  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:04.986  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:44:04.987  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:44:04.987  7951  7951 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 09:44:04.987  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:44:04.987  7951  7951 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 09:44:04.987  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-28 09:44:04.987  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 09:44:04.988  1036  8008 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 09:44:04.989  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-28 09:44:04.989  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 09:44:04.989  1036  8008 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-28 09:44:04.989  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:44:04.989  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:44:04.990  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 09:44:04.996  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 09:44:04.996  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:04.996  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-28 09:44:04.999  1036  1394 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=156139  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 09:44:05.000  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=156140  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-28 09:44:05.000  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.000  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.000  1036  1394 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=156141
07-28 09:44:05.000  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-28 09:44:05.000  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:44:05.000  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-28 09:44:05.001  1036  1394 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=156141
07-28 09:44:05.001  1036  1394 D WifiNative-wlan0: doString: [STATUS]
07-28 09:44:05.002  1036  8008 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-28 09:44:05.002  1036  8008 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-28 09:44:05.002  1036  1394 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-28 09:44:05.004  1036  1394 I WifiServiceExtension: setVHTCapabilityType  : false
,07-28 09:44:05.009  1036  1394 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-28 09:44:05.009  1036  1394 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-28 09:44:05.010  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:05.010  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:44:05.011  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.013  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.013  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.013  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-28 09:44:05.013  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:05.013  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:44:05.014  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.016  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.016  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.016  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-28 09:44:05.029  1036  1394 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,07-28 09:44:05.029  1036  1407 D ConnectivityService: Got NetworkAgent Messenger
07-28 09:44:05.029  1036  1394 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 09:44:05.029  1036  1394 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 09:44:05.029  1036  1407 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 09:44:05.029  1036  1407 D ConnectivityService: NetworkAgent connected
07-28 09:44:05.029  1036  1394 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 09:44:05.030  1036  1394 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 09:44:05.033  1036  1394 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 09:44:05.033  1036  1394 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 09:44:05.033  1036  1394 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-28 09:44:05.033  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:05.033  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:44:05.034  1036  1394 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-28 09:44:05.034  1036  1394 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-28 09:44:05.034  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 09:44:05.040  1036  1394 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-28 09:44:05.043   316   896 D CommandListener: Setting iface cfg
07-28 09:44:05.048  1036  8062 D DhcpStateMachine: StoppedState
07-28 09:44:05.048  1036  1394 E WifiStateMachine: Start Dhcp Watchdog 3
07-28 09:44:05.048  1036  8062 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:05.048  1036  8062 D DhcpStateMachine: WaitBeforeStartState
07-28 09:44:05.050  1036  1394 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=156191  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,07-28 09:44:05.052  1036  1394 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=156192  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:44:05.053  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=156193  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:44:05.054  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:44:05.054  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-28 09:44:05.056  1036  1394 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=156196  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:44:05.057  1036  1394 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=156197  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:44:05.058  1036  1394 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=156198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-28 09:44:05.059  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14220] from screen [on:0 period:813029827] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 09:44:05.060  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:813029828] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-28 09:44:05.060  1036  1394 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-28 09:44:05.064  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.065  1036  1407 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
07-28 09:44:05.065  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 09:44:05.066  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.066  1036  1394 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.067  1036  1394 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,07-28 09:44:05.067  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.067  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.068  1036  1407 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 09:44:05.068  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
07-28 09:44:05.069  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
07-28 09:44:05.069  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,07-28 09:44:05.069  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-28 09:44:05.069  1036  1394 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-28 09:44:05.069  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 0
07-28 09:44:05.070  1036  1394 D WifiNative-wlan0: SET ps 0: returned true
07-28 09:44:05.070  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-28 09:44:05.070  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-28 09:44:05.070  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-28 09:44:05.071  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2dca6032 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:05.071  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2dca6032 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:05.071  1036  8062 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:05.071  1036  8062 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-28 09:44:05.072  1036  1394 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-28 09:44:05.072  1036  1394 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 09:44:05.072  1036  1394 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 09:44:05.073   316   896 D CommandListener: Setting iface cfg
07-28 09:44:05.073   316   896 D CommandListener: Trying to bring up wlan0
07-28 09:44:05.074  1036  1394 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-28 09:44:05.074  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:44:05.074  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 09:44:05.075  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-28 09:44:05.075  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-28 09:44:05.076  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.076  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.077  1036  1394 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.077  1036  1394 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.078  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.078  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-28 09:44:05.078  1036  1407 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 09:44:05.079  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 09:44:05.079  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-28 09:44:05.080  1036  1392 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:05.080  1036  1392 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:05.080  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-28 09:44:05.080  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-28 09:44:05.080  1036  1394 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-28 09:44:05.080  1036  1394 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-28 09:44:05.080  7951  7951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-28 09:44:05.081  1036  1394 D WifiNative-wlan0: DRIVER SETSUSPENDMODE, 1: returned true
07-28 09:44:05.081  1036  1394 D WifiNative-wlan0: doBoolean: SET ps 1
,07-28 09:44:05.097  1036  1394 D WifiNative-wlan0: SET ps 1: returned true
,07-28 09:44:05.098  1036  1407 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-28 09:44:05.098  1036  1394 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 09:44:05.099  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-28 09:44:05.099  1036  1394 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 09:44:05.100  1036  1407 D ConnectivityService: ignoring duplicate network state non-change
07-28 09:44:05.102  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:05.102  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-28 09:44:05.103  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.104  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.104  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.104  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 09:44:05.107  1036  1407 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 09:44:05.108  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.108  1036  1407 D ConnectivityService: Adding iface wlan0 to network 102
07-28 09:44:05.108  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.108  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-28 09:44:05.111  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,07-28 09:44:05.116  1978  1978 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-28 09:44:05.119  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.120  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.120  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 09:44:05.121  1036  1394 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-28 09:44:05.122  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-28 09:44:05.126  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:05.126  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-28 09:44:05.127  1036  1407 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 09:44:05.127  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.127  1036  1407 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-28 09:44:05.128  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.128  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:44:05.128  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-28 09:44:05.128  1036  1407 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-28 09:44:05.129   316   896 E Netd    : netlink response contains error (File exists)
07-28 09:44:05.130  1036  1407 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-28 09:44:05.130  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:05.130  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,07-28 09:44:05.130  1036  1407 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-28 09:44:05.131  1036  1407 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
07-28 09:44:05.131  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.131  1036  1407 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-28 09:44:05.132  1036  1407 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 09:44:05.132  1036  1407 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 09:44:05.132  1036  1407 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-28 09:44:05.132  1036  1407 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-28 09:44:05.132  1036  1407 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:44:05.132  1036  1407 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:44:05.132  1036  1407 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 09:44:05.132  1036  8057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:05.132  1036  8057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-28 09:44:05.132  1036  1407 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:05.132  1036  1407 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-28 09:44:05.132  1036  1407 D ConnectivityService: currentScore = 0, newScore = 20
07-28 09:44:05.132  1036  1407 D ConnectivityService:    accepting network in place of null
,07-28 09:44:05.132  1036  1407 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:05.132  1036  1394 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:05.132  1036  1394 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:44:05.132  1036  8057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 09:44:05.133  1036  8057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 09:44:05.134  1879  1879 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:05.134  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 09:44:05.136  1036  1407 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 09:44:05.136  1036  1407 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-28 09:44:05.136  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 09:44:05.136  1036  1407 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:44:05.136  1036  1407 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-28 09:44:05.137  1036  1407 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-28 09:44:05.137  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-28 09:44:05.137  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-28 09:44:05.137  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-28 09:44:05.137  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-28 09:44:05.138  1036  1407 D ConnectivityService: validation of new default Network = false
07-28 09:44:05.138  1036  1407 D C,onnectivityService: Default network via Wi-Fi connected. start DSQN
07-28 09:44:05.138  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 09:44:05.138  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-28 09:44:05.139   316  8068 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-28 09:44:05.139  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-28 09:44:05.138  1036  1407 D DSQN    : enableDataServiceNotify 
07-28 09:44:05.143  1036  1407 D DSQN    : start dsqn bin
07-28 09:44:05.150  1036  1407 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,07-28 09:44:05.150  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:05.150  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:44:05.151  1036  1407 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:44:05.151  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 09:44:05.152  1036  1391 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-28 09:44:05.141  8069  8069 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:05.141  8069  8069 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:05.162  8069  8069 E DSQN    : DSQN ssw
,07-28 09:44:05.172  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 09:44:05.172  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.173  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.191   316  8068 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,07-28 09:44:05.225   316  8068 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-28 09:44:05.256   316   895 D LGDataListener: argv[0]=dsqncommand
07-28 09:44:05.256   316   895 D LGDataListener: argv[1]=wlan0
07-28 09:44:05.256   316   895 D LGDataListener: argv[2]=1
07-28 09:44:05.256   316   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-28 09:44:05.257  1036  1096 D DSQN    : DSQM DsqnNotification wlan0  1
07-28 09:44:05.257  1036  1096 D DSQN    : start to monitor internet connection
,07-28 09:44:05.265  6576  6706 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 857)
07-28 09:44:05.265  6576  6706 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 857)
07-28 09:44:05.266  6576  6706 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 857)
07-28 09:44:05.266  6576  6706 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 857)
07-28 09:44:05.273  1036  8062 D DhcpStateMachine: DHCPV4 request on wlan0
,07-28 09:44:05.273  1036  8062 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-28 09:44:05.273  1036  8062 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-28 09:44:05.271  8075  8075 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:05.271  8075  8075 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-28 09:44:05.280  6576  6706 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 862)
07-28 09:44:05.280  6576  6706 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 862)
07-28 09:44:05.280  6576  6706 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862)
07-28 09:44:05.283  6576  6706 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 863)
07-28 09:44:05.284  1036  8057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 07:44:05 GMT], X-Android-Received-Millis=[1469691845283], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469691845255]}
07-28 09:44:05.284  1036  8057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 09:44:05.284  1036  8057 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-28 09:44:05.284  1036  1407 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
07-28 09:44:05.284  1036  1407 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-28 09:44:05.284  1036  1407 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:44:05.284  1036  1407 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:44:05.284  1036  1407 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-28 09:44:05.284  1036  1407 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
07-28 09:44:05.285  1036  1407 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-28 09:44:05.285  8075  8075 I dhcpcd  : version 5.5.6 starting
07-28 09:44:05.285  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:05.285  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:44:05.285  1036  1407 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:44:05.285  1036  1407 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:05.285  1036  1407 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-28 09:44:05.286  8075  8075 E dhcpcd  : get_duid: m
07-28 09:44:05.286  8075  8075 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-28 09:44:05.286  8075  8075 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-28 09:44:05.287  1036  1394 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:05.287  1036  1394 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 09:44:05.287  1605  1813 D ConnectivityMa,nager.CallbackHandler: CM callback handler got msg 524290
07-28 09:44:05.287  6576  6706 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 865)
,07-28 09:44:05.288  1879  1879 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:05.291  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-28 09:44:05.302  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.302  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a1c2a1c added. We now have 2 listener(s)
07-28 09:44:05.303  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.308  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:44:05.309  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.309  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.309  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:05.309  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@207aa625 added. We now have 9 listener(s)
07-28 09:44:05.309  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:44:05.311  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 09:44:05.314  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:44:05.314  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-28 09:44:05.315  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.316  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-28 09:44:05.318  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:44:05.318  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:44:05.318  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:44:05.318  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:44:05.318  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:44:05.318  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.318  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:44:05.318  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:44:05.319  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.319  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:44:05.320  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.320  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b867dab added. We now have 3 listener(s)
07-28 09:44:05.320  1036  1657 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.321  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:44:05.323  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:05.327  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:44:05.327  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.327  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.327  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:05.327  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcfcc08 added. We now have 10 listener(s)
07-28 09:44:05.327  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:05.327  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:44:05.327  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:44:05.327  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:44:05.327  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.327  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.327  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:44:05.327  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.328  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a1c2a1c removed from the list
07-28 09:44:05.328  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.328  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@207aa625 removed from the list
07-28 09:44:05.328  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:44:05.328  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.328  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.328  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.329  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.329  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:44:05.329  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.329  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@207aa625 not in the list
07-28 09:44:05.329  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.329  6576  6706 D org.thaliproject.p2p.btco,nnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.330  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:44:05.330  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.330  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.330  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcfcc08 removed from the list
07-28 09:44:05.330  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.330  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.330  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.330  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.330  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b867dab removed from the list
07-28 09:44:05.331  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.331  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d47fa1 added. We now have 2 listener(s)
07-28 09:44:05.331  1036  2115 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.334  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:44:05.334  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.334  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.334  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:05.334  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3de395c6 added. We now have 9 listener(s)
07-28 09:44:05.334  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:05.334  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 09:44:05.337  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:44:05.341  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:44:05.341  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:44:05.341  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:44:05.341  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:44:05.341  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:44:05.341  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.341  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:44:05.341  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:44:05.342  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.343  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:44:05.344  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:05.345  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.346  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3199a0b4 added. We now have 3 listener(s)
,07-28 09:44:05.346  1036  2091 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.347  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:05.349  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,07-28 09:44:05.349  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.349  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.349  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:05.350  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c9874dd added. We now have 10 listener(s)
07-28 09:44:05.350  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:05.350  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:44:05.350  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:44:05.350  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:44:05.350  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 09:44:05.351  8075  8075 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 09:44:05.352  8075  8075 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 09:44:05.352  8075  8075 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 09:44:05.352  8075  8075 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-28 09:44:05.352  8075  8075 D dhcpcd  : wlan0: sending REQUEST (xid 0x11f65a9c), next in 3.81 seconds
07-28 09:44:05.352  8037  8037 W ExternalStrings: load override strings
07-28 09:44:05.352  8037  8037 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-28 09:44:05.352  8037  8037 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.m,ain(ZygoteInit.java:704)
07-28 09:44:05.353  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 09:44:05.353  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.354  8037  8037 D StatusProvider: onCreate
07-28 09:44:05.356  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 09:44:05.357  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 09:44:05.359  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:44:05.359  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 09:44:05.360  6576  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 09:44:05.361  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:44:05.361  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:44:05.363  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:44:05.363  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:44:05.363  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:44:05.363  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.363  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.363  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:44:05.363  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.363  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21d47fa1 removed from the list
07-28 09:44:05.363  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.363  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3de395c6 removed from the list
07-28 09:44:05.363  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:44:05.363  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.364  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.364  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.365  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.365  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:44:05.365  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.365  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3de395c6 not in the list
07-28 09:44:05.365  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.365  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.366  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:44:05.366  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:44:05.366  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:44:05.366  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.367  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.367  6576  6706 V org.thaliproject.p2p.btconnectorlib.Discove,ryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c9874dd removed from the list
07-28 09:44:05.367  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.367  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.367  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.367  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.367  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3199a0b4 removed from the list
07-28 09:44:05.367  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.368  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@348a1420 added. We now have 2 listener(s)
07-28 09:44:05.368  1036  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.370  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:44:05.370  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.370  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.370  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:05.370  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ac81d9 added. We now have 9 listener(s)
07-28 09:44:05.370  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:05.370  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 09:44:05.373  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:44:05.375  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:44:05.375  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:44:05.375  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:44:05.375  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:44:05.375  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:44:05.375  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.375  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:44:05.375  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:44:05.377  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.377  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:44:05.377  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.377  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70be27f added. We now have 3 listener(s)
07-28 09:44:05.378  1036  1577 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.379  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:05.380  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:05.380  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:44:05.380  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.381  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.381  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:05.381  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4c524c added. We now have 10 listener(s)
07-28 09:44:05.381  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:05.381  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:44:05.381  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:44:05.382  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:44:05.382  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:44:05.382  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 09:44:05.384  6576  6706 V org.thaliproject.p2p.btconnectorlib.Disco,veryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 09:44:05.384  1036  2115 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-28 09:44:05.388  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 09:44:05.389  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 09:44:05.391  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:44:05.391  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:44:05.392  6576  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 09:44:05.393  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:44:05.393  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:44:05.393  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:44:05.393  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.393  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.393  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:44:05.393  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.393  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@348a1420 removed from the list
07-28 09:44:05.393  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.393  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ac81d9 removed from the list
,07-28 09:44:05.393  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:44:05.393  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.394  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.394  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.395  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.395  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:44:05.395  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.395  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ac81d9 not in the list
07-28 09:44:05.395  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.395  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.396  8075  8075 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
07-28 09:44:05.396  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:44:05.397  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:44:05.397  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:44:05.397  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.397  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.397  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4c524c removed from the list
07-28 09:44:05.397  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.397  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.397  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.397  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.397  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70be27f removed from the list
07-28 09:44:05.398  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.398  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1486279b added. We now have 2 listener(s)
07-28 09:44:05.398  1036  2120 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.401  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:44:05.401  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.401  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.401  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: lo,ad: Already loaded
07-28 09:44:05.401  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a124738 added. We now have 9 listener(s)
07-28 09:44:05.401  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:05.401  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 09:44:05.403  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:44:05.406  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:44:05.406  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:44:05.406  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:44:05.406  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:44:05.406  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:44:05.406  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.406  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:44:05.406  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:44:05.410  8037  8037 V Signer  : override build config not found
07-28 09:44:05.410  8037  8037 D Signer  : value of property debug is false
07-28 09:44:05.410  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.410  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:44:05.411  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.411  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a2fc76 added. We now have 3 listener(s)
07-28 09:44:05.411  1036  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.412  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:05.413  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:05.414  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:44:05.414  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.414  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.414  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:05.414  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895a277 added. We now have 10 listener(s)
07-28 09:44:05.414  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:05.414  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:44:05.414  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:44:05.414  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:44:05.414  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 09:44:05.417  8075  8075 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-28 09:44:05.417  8075  8075 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-28 09:44:05.418  8075  8075 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-28 09:44:05.418  8075  8075 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-28 09:44:05.418  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 09:44:05.418  8075  8075 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-28 09:44:05.418  1036  2041 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.418  8075  8075 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-28 09:44:05.418  8075  8075 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-28 09:44:05.418  8075  8075 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-28 09:44:05.422  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx pow,er level: 3, timeout: 0, is connectable: false
07-28 09:44:05.423  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 09:44:05.428  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:44:05.428  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:44:05.429  6576  6706 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 09:44:05.431  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:44:05.431  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:44:05.431  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:44:05.431  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.431  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.431  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:44:05.431  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.431  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1486279b removed from the list
07-28 09:44:05.431  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.431  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a124738 removed from the list
07-28 09:44:05.431  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:44:05.432  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.437  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.437  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.438  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.438  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:44:05.438  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.438  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a124738 not in the list
07-28 09:44:05.438  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.438  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:44:05.442  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:44:05.443  6576  6706 D BluetoothLeScanner: could not find callback wrapper
07-28 09:44:05.443  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:44:05.443  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.443  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.443  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@895a277 removed from the list
07-28 09:44:05.443  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.443  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.443  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.443  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.443  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a2fc76 removed from the list
07-28 09:44:05.444  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.444  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@303a6a02 added. We now have 2 listener(s)
07-28 09:44:05.444  1036  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.446  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:44:05.446  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.446  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.446  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:05.446  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b7ef13 added. We now have 9 listener(s)
07-28 09:44:05.446  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:05.446  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 09:44:05.448  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:44:05.451  6576  6706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:44:05.451  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:44:05.451  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 09:44:05.451  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:44:05.451  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:44:05.451  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.451  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active netwo,rk: true
07-28 09:44:05.451  6576  6706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:44:05.453  6576  6706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:44:05.453  6576  6706 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:44:05.457  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:44:05.457  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29249349 added. We now have 3 listener(s)
07-28 09:44:05.458  1036  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-28 09:44:05.458  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:05.460  6576  6576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:44:05.461  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-28 09:44:05.461  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:44:05.461  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:44:05.461  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:44:05.461  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce9244e added. We now have 10 listener(s)
07-28 09:44:05.461  6576  6706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:44:05.462  6576  6706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:44:05.462  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:44:05.462  6576  6706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:44:05.462  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.462  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.462  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:44:05.462  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.462  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@303a6a02 removed from the list
07-28 09:44:05.462  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.462  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b7ef13 removed from the list
07-28 09:44:05.462  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
07-28 09:44:05.462  6576  6706 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:44:05.462  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.462  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The giv,en listener does not exist in the list - probably already removed
07-28 09:44:05.462  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
07-28 09:44:05.462  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.463  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-28 09:44:05.463  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.463  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:44:05.463  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.463  6576  6706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b7ef13 not in the list
07-28 09:44:05.463  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.463  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.463  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-28 09:44:05.464  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-28 09:44:05.464  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 09:44:05.464  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:44:05.464  6576  6706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:44:05.464  6576  6706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce9244e removed from the list
07-28 09:44:05.464  6576  6706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:44:05.464  6576  6706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:44:05.464  6576  6706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:44:05.464  6576  6706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:44:05.464  6576  6706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29249349 removed from the list
07-28 09:44:05.464  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-28 09:44:05.464  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-28 09:44:05.465  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 09:44:05.465  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
07-28 09:44:05.465  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 09:44:05.465  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 09:44:05.465  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 09:44:05.465  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-28 09:44:05.465  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 09:44:05.465  6576  6706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 09:44:05.465  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-28 09:44:05.466  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-28 09:44:05.466  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
07-28 09:44:05.466  8037  8037 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
07-28 09:44:05.478  6576  8089 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: My test thread name)
07-28 09:44:05.478  6576  8089 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 871, thread name: My test thread name)
07-28 09:44:05.478  6576  8089 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: My test thread name)
07-28 09:44:05.482  6576  8090 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 873, name: My test thread name)
07-28 09:44:05.482  6576  8090 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 873, thread name: My test thread name)
07-28 09:44:05.482  6576  8090 D io,.jxcore.node.StreamCopyingThread: Exiting thread (ID: 873, name: My test thread name)
,07-28 09:44:05.484  6576  6706 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-28 09:44:05.485  6576  6706 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-28 09:44:05.485  6576  6706 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 09:44:05.485  6576  6706 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-28 09:44:05.485  6576  6706 D com.test.thalitest.ThaliTestRunner: Total duration: 23016 ms
07-28 09:44:05.486  6576  6706 I jxcore-log: Total number of executed tests:  80
07-28 09:44:05.486  6576  6706 I jxcore-log: 
07-28 09:44:05.486  6576  6706 I jxcore-log: Number of passed tests:  80
07-28 09:44:05.486  6576  6706 I jxcore-log: 
07-28 09:44:05.486  6576  6706 I jxcore-log: Number of failed tests:  0
07-28 09:44:05.486  6576  6706 I jxcore-log: 
07-28 09:44:05.486  6576  6706 I jxcore-log: Number of ignored tests:  0
07-28 09:44:05.486  6576  6706 I jxcore-log: 
07-28 09:44:05.486  6576  6706 I jxcore-log: Total duration:  23016
07-28 09:44:05.486  6576  6706 I jxcore-log: 
07-28 09:44:05.486  6576  6706 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 09:44:05.486  6576  6706 I jxcore-log: 
07-28 09:44:05.486  8037  8037 V LGMDMManager: Create singleton instance
07-28 09:44:05.488  6576  6706 I jxcore-log: Unit Test app is loaded
07-28 09:44:05.488  6576  6706 I jxcore-log: 
07-28 09:44:05.498  6576  6576 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-28 09:44:05.499  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.499  6576  6706 I jxcore-log: 
07-28 09:44:05.503  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.503  6576  6706 I jxcore-log: 
07-28 09:44:05.504  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.504  6576  6706 I jxcore-log: 
07-28 09:44:05.508  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.508  6576  6706 I jxcore-log: 
07-28 09:44:05.508  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.508  6576  6706 I jxcore-log: 
07-28 09:44:05.509  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-28 09:44:05.509  6576  6706 I jxcore-log: 
07-28 09:44:05.512  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 09:44:05.512  6576  6706 I jxcore-log: 
07-28 09:44:05.513  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.513  6576  6706 I jxcore-log: 
07-28 09:44:05.514  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 09:44:05.514  6576  6706 I jxcore-log: 
07-28 09:44:05.515  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.515  6576  6706 I jxcore-log: 
07-28 09:44:05.515  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.515  6576  6706 I jxcore-log: 
07-28 09:44:05.516  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 09:44:05.516  6576  6706 I jxcore-log: 
07-28 09:44:05.517  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 09:44:05.517  6576  6706 I jxcore-log: 
07-28 09:44:05.518  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.518  6576  6706 I jxcore-log: 
07-28 09:44:05.519  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.519  6576  6706 I jxcore-log: 
07-28 09:44:05.519  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.519  6576  6706 I jxcore-log: 
07-28 09:44:05.520  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.520  6576  6706 I jxcore-log: 
07-28 09:44:05.520  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.520  6576  6706 I jxcore-log: 
07-28 09:44:05.521  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.521  6576  6706 I jxcore-log: 
07-28 09:44:05.522  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.522  6576  6706 I jxcore-log: 
07-28 09:44:05.522  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 09:44:05.522  6576  6706 I jxcore-log: 
07-28 09:44:05.523  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 09:44:05.523  6576  6706 I jxcore-log: 
,07-28 09:44:05.524  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 09:44:05.524  6576  6706 I jxcore-log: 
07-28 09:44:05.524  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.524  6576  6706 I jxcore-log: 
07-28 09:44:05.525  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.525  6576  6706 I jxcore-log: 
07-28 09:44:05.526  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.526  6576  6706 I jxcore-log: 
07-28 09:44:05.526  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.526  6576  6706 I jxcore-log: 
07-28 09:44:05.527  6576  6706 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:44:05.527  6576  6706 I jxcore-log: 
07-28 09:44:05.531  6576  6706 I jxcore-log: My device name is: LGE-LG-D855
07-28 09:44:05.531  6576  6706 I jxcore-log: 
07-28 09:44:05.570  8037  8037 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,07-28 09:44:05.621  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:44:05.628  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 09:44:05.630  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:44:05.635  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:05.643  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:05.649  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:05.655  7771  7771 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-28 09:44:05.661  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-28 09:44:05.663  6761  6761 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-28 09:44:05.676  1036  8062 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-28 09:44:05.676  1036  8062 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,07-28 09:44:05.677  1036  8062 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-28 09:44:05.677  1036  8062 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-28 09:44:05.677  1036  8062 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-28 09:44:05.677  1036  8062 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-28 09:44:05.677  1036  8062 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-28 09:44:05.677  1036  8062 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-28 09:44:05.677  1036  8062 D DhcpStateMachine: RunningState
07-28 09:44:05.725  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:44:05.725  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 09:44:05.725  8037  8107 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-28 09:44:05.730  8102  8102 D AndroidRuntime: 
07-28 09:44:05.730  8102  8102 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 09:44:05.732  8102  8102 D AndroidRuntime: CheckJNI is OFF
07-28 09:44:05.745  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:44:05.753  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:05.757  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:05.757  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:05.758  7771  7771 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-28 09:44:05.761  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:44:05.762  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 09:44:05.770  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:44:05.776  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:05.782  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:05.782  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:05.782  7771  7771 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 09:44:05.785  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-28 09:44:05.785  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-28 09:44:05.785  6761  6761 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-28 09:44:05.785  6761  6761 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-28 09:44:05.787  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-28 09:44:05.788  6761  6761 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-28 09:44:05.788  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-28 09:44:05.788  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-28 09:44:05.788  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-28 09:44:05.788  6761  6761 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-28 09:44:05.788  6761  6761 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-28 09:44:05.788  6761  6761 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-28 09:44:05.791  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:44:05.792  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 09:44:05.799  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:44:05.804  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:05.811  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:05.811  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:05.811  7771  7771 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-28 09:44:05.815  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 09:44:05.815  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:44:05.821  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:44:05.829  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:05.833  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:05.833  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:05.834  7771  7771 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 09:44:05.835  8102  8102 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-28 09:44:05.836  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:44:05.837  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 09:44:05.841  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 09:44:05.846  1036  1094 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-28 09:44:05.847  1036  1094 I ActivityManager: Killing 6576:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,07-28 09:44:05.856  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:05.868  7487  7816 D UEI.SmartControl: Internal timer expired: 2
07-28 09:44:05.868  7487  7816 D UEI.SmartControl: unbind internal service
,07-28 09:44:05.877  1036  2005 I WindowState: WIN DEATH: Window{33b4a31a u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 09:44:05.877  1036  1400 D WifiService: Client connection lost with reason: 4
07-28 09:44:05.882  1036  2005 D InputDispatcher: Window went away: Window{33b4a31a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-28 09:44:05.891  8037  8107 D LgDataFeature: LgDataFeature() Constructor: none
07-28 09:44:05.891  8037  8107 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:44:06.008  8037  8107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,07-28 09:44:06.068  1036  1094 I ActivityManager:   Force finishing activity ActivityRecord{3ee46329 u0 com.test.thalitest/.MainActivity t40}
,07-28 09:44:06.106   342   364 E GBMv2   : DFP En is all cleared set to be enabled
07-28 09:44:06.118  1036  2120 W ActivityManager: Spurious death for ProcessRecord{35a5df92 6576:com.test.thalitest/u0a118}, curProc for 6576: null
,07-28 09:44:06.119  1036  1107 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-28 09:44:06.120  1036  1107 I ActivityManager:   Force finishing activity ActivityRecord{3ee46329 u0 com.test.thalitest/.MainActivity t40 f}
07-28 09:44:06.121  1036  1107 W ActivityManager: Duplicate finish request for ActivityRecord{3ee46329 u0 com.test.thalitest/.MainActivity t40 f}
,07-28 09:44:06.143  2097  2097 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-28 09:44:06.147  2097  2097 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
07-28 09:44:06.150  1978  2004 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,07-28 09:44:06.151  1978  2004 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f6c70b0 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-28 09:44:06.153  1978  3122 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-28 09:44:06.155  1978  3122 D SplitWindowPolicy: topRunningActivity=ActivityInfo{13a1cb29 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-28 09:44:06.158  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-28 09:44:06.159  3808  3808 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,07-28 09:44:06.171  2054  2054 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-28 09:44:06.171  2511  2681 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-28 09:44:06.172  1036  1383 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 09:44:06.174  7567  7567 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-28 09:44:06.174  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-28 09:44:06.193  8037  8107 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,07-28 09:44:06.221  4576  4576 I art     : Explicit concurrent mark sweep GC freed 8198(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 1.541ms total 86.536ms
,07-28 09:44:06.233  1036  2120 V SIM_STK : Menu title from STK is T-Mobile
,07-28 09:44:06.236  1036  1093 W InputMethodInfo: Duplicated subtype definition found: , voice
07-28 09:44:06.256  4451  4451 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-28 09:44:06.256  4451  4451 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-28 09:44:06.256  4451  4451 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-28 09:44:06.256  4451  4451 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-28 09:44:06.256  4451  4451 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 09:44:06.256  4451  4451 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 09:44:06.256  4451  4451 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-28 09:44:06.256  4451  4451 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-28 09:44:06.256  4451  4451 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:44:06.256  4451  4451 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 09:44:06.256  4451  4451 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,07-28 09:44:06.256  4451  4451 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-28 09:44:06.258  1036  1036 D administrator: Handling package changes for user 0
07-28 09:44:06.260  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-28 09:44:06.261  2097  2193 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-28 09:44:06.263  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:06.264  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:06.269  7771  7771 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 09:44:06.274  1932  1932 D ActionManagerService: notifyUserLog: 1000003
07-28 09:44:06.276  3808  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-28 09:44:06.276  2097  2097 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-28 09:44:06.277  7487  7810 D serial_port: close(fd = 24)
07-28 09:44:06.281  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:44:06.283  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 09:44:06.286  2097  2097 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-28 09:44:06.287  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-28 09:44:06.287  7487  7810 I UEI.SmartControl: Serial port is closed.
07-28 09:44:06.297  2097  2097 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,07-28 09:44:06.314  2097  2097 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,07-28 09:44:06.317  2097  2097 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
07-28 09:44:06.317  1932  1932 D ActionManagerService: notifyUserLog: 1000004
07-28 09:44:06.317  3808  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-28 09:44:06.318  3808  3823 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 09:44:06.319  1896  1896 D SplitUIManager: split_name #11 / not available #0
07-28 09:44:06.320  1896  1896 D SplitUIService: removed split : 
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , create_time: 1430832262123
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , expire_time: 0
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , display: false
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , animation: false }
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , create_time: 1430832262287
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , expire_time: 0
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , display: false
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , animation: false }
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , create_time: 1469186101943
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , expire_time: 0
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , display: false
07-28 09:44:06.321  2097  2097 I GBoardWebViewUtils: , animation: false }
,07-28 09:44:06.337  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-28 09:44:06.337  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-28 09:44:06.343  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:44:06.343  2097  8137 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
07-28 09:44:06.348  1036  2095 V SIM_STK : Menu title from STK is T-Mobile
07-28 09:44:06.348  1036  2095 V SIM_STK : Menu title from STK is T-Mobile
07-28 09:44:06.353  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 09:44:06.354  2097  2097 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,07-28 09:44:06.360  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:06.368  1605  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 09:44:06.368  1605  1652 D KeyguardModel: createShortcutInfo...
,07-28 09:44:06.372  1605  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-28 09:44:06.372  1605  1652 D KeyguardModel: createShortcutInfo...
07-28 09:44:06.377  1605  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-28 09:44:06.377  1605  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 09:44:06.378  1605  1652 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-28 09:44:06.379  1605  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 09:44:06.380  1605  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 09:44:06.380  1605  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-28 09:44:06.381  1605  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 09:44:06.381  1605  1652 D KeyguardModel: createShortcutInfo...
07-28 09:44:06.383  1036  2091 V SIM_STK : Menu title from STK is T-Mobile
07-28 09:44:06.387  1896  1896 D SplitUIManager: split_name #11 / not available #0
07-28 09:44:06.387  1896  1896 I SplitUIService: split app #11
07-28 09:44:06.388  8037  8107 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
07-28 09:44:06.389  8037  8107 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-28 09:44:06.389  8037  8107 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-28 09:44:06.389  8037  8107 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
07-28 09:44:06.390  8037  8107 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
07-28 09:44:06.393  1605  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-28 09:44:06.393  1605  1652 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 09:44:06.394  1605  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-28 09:44:06.394  1605  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-28 09:44:06.395  1605  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 09:44:06.395  1605  1652 D KeyguardModel: createShortcutInfo...
07-28 09:44:06.400  1605  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 09:44:06.400  1605  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-28 09:44:06.400  1605  1652 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-28 09:44:06.400  1605  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-28 09:44:06.404  1605  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 09:44:06.404  1605  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-28 09:44:06.406  1605  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-28 09:44:06.406  1605  1652 D KeyguardModel: createShortcutInfo...
07-28 09:44:06.408  1036  2091 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-28 09:44:06.408  8037  8107 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-28 09:44:06.408  7567  7567 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-28 09:44:06.409  8037  8107 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,07-28 09:44:06.410  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:06.410  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:06.410  7771  7771 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 09:44:06.425  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 09:44:06.425  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-28 09:44:06.427  1605  1605 D KeyguardModel: handleShortcutListChanged...
07-28 09:44:06.427  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-28 09:44:06.434  1605  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-28 09:44:06.434  1605  1652 D KeyguardModel: createShortcutInfo...
07-28 09:44:06.434  2097  2097 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-28 09:44:06.447  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:44:06.448  1605  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-28 09:44:06.448  1605  1652 D KeyguardModel: createShortcutInfo...
07-28 09:44:06.451  1605  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 09:44:06.451  1605  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-28 09:44:06.452  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-28 09:44:06.452  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-28 09:44:06.452  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-28 09:44:06.453  1605  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-28 09:44:06.453  1605  1652 D KeyguardModel: createShortcutInfo...
07-28 09:44:06.453  1036  1579 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
07-28 09:44:06.454  1605  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 09:44:06.454  1605  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-28 09:44:06.455  1605  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-28 09:44:06.455  1605  1652 D KeyguardModel: createShortcutInfo...
07-28 09:44:06.456  1605  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-28 09:44:06.456  1605  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-28 09:44:06.457  1605  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-28 09:44:06.457  1605  1652 D KeyguardModel: createShortcutInfo...
07-28 09:44:06.458  1036  1394 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 09:44:06.458  1036  1394 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 09:44:06.458  1036  1394 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 09:44:06.459  1036  1394 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 09:44:06.459  1036  1394 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 09:44:06.459  1036  1394 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-28 09:44:06.460  1036  1407 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
07-28 09:44:06.460  1036  1407 D ConnectivityService: identical MTU - not setting
07-28 09:44:06.460  1036  1407 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-28 09:44:06.460  1036  1407 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 09:44:06.460  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 09:44:06.460  1036  1407 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:44:06.460  1036  1407 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 09:44:06.461  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-28 09:44:06.465  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:06.466  1605  1605 D KeyguardModel: handleShortcutListChanged...
07-28 09:44:06.466  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,07-28 09:44:06.471  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:06.471  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:06.475  7771  7771 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 09:44:06.482  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:44:06.483  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 09:44:06.489  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-28 09:44:06.494  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:06.499  1036  1107 I art     : Explicit concurrent mark sweep GC freed 77773(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 44MB/66MB, paused 5.937ms total 346.237ms
07-28 09:44:06.511   329   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-28 09:44:06.512  3184  8141 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,07-28 09:44:06.509  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:06.514  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:06.514  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
07-28 09:44:06.515  7771  7771 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-28 09:44:06.517  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 09:44:06.519  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-28 09:44:06.520  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-28 09:44:06.521  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-28 09:44:06.522  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,07-28 09:44:06.543  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,07-28 09:44:06.543  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 09:44:06.544  2097  2280 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,07-28 09:44:06.544  2097  2280 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
07-28 09:44:06.548  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:44:06.549  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 09:44:06.553  8102  8102 D AndroidRuntime: Shutting down VM
07-28 09:44:06.554  7990  7990 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 09:44:06.554  1036  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5934e40 u0 com.lge.launcher2/.Launcher t39} time:157707
,07-28 09:44:06.558  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
07-28 09:44:06.559  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 09:44:06.559  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 09:44:06.560  7990  7990 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:44:06.573  2097  2097 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,07-28 09:44:06.576  1036  1107 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8144 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-28 09:44:06.578  2611  2611 D [Concierge]Service: onStartCommand(). Type : 8
07-28 09:44:06.578  2611  2611 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-28 09:44:06.579  2611  2611 D [Concierge]Service: Update widget ID : 11
07-28 09:44:06.580  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 09:44:06.580  2097  2097 D [Concierge]WidgetView: change position of spinner
07-28 09:44:06.581  2611  2611 D [Concierge]Service: onStartCommand(). Type : 0
07-28 09:44:06.582  2097  2097 I [Concierge]WidgetView: initWebView(). Time : 1469691846582
07-28 09:44:06.585  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-28 09:44:06.592  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:06.593  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:06.593  7771  7771 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 09:44:06.594  7771  7771 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 09:44:06.594  7771  7771 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 09:44:06.595  2097  2097 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 582864712
07-28 09:44:06.595  2097  2097 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-28 09:44:06.595  2097  2097 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-28 09:44:06.597  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-28 09:44:06.599  2097  2097 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2c4fd7e5
07-28 09:44:06.599  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-28 09:44:06.597  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-28 09:44:06.601  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-28 09:44:06.602  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 09:44:06.602  7990  7990 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-28 09:44:06.602  7990  7990 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-28 09:44:06.605  6761  6761 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-28 09:44:06.607  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-28 09:44:06.607  2097  2097 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-28 09:44:06.607  2097  2097 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-28 09:44:06.609  6761  6761 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-28 09:44:06.609  2097  2097 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469691716855, New one : 1469691846582
07-28 09:44:06.609  2097  2097 D [Concierge]WidgetView: Unregister all receivers
07-28 09:44:06.609  2097  2097 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-28 09:44:06.611  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 09:44:06.614  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-28 09:44:06.615  7771  7771 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-28 09:44:06.615  7771  7771 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-28 09:44:06.615  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-28 09:44:06.616  7771  7771 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-28 09:44:06.616  7771  7771 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-28 09:44:06.616  7771  7771 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-28 09:44:06.616  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-28 09:44:06.617  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-28 09:44:06.619  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-28 09:44:06.621  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
07-28 09:44:06.623  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
07-28 09:44:06.623  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 09:44:06.623  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-28 09:44:06.624  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
07-28 09:44:06.626  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
07-28 09:44:06.627  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
07-28 09:44:06.630  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
07-28 09:44:06.630  8037  8037 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-28 09:44:06.631  1036  1577 I ActivityManager: Killing 7144:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-28 09:44:06.632  8037  8108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-28 09:44:06.666  2097  2097 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,07-28 09:44:06.674  2097  2097 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-28 09:44:06.674  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
07-28 09:44:06.675  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-28 09:44:06.678  1036  1093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 09:44:06.683  1036  1093 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-28 09:44:06.695  2097  2097 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@28fd204d time:157848
,07-28 09:44:06.708  1843  1843 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,07-28 09:44:06.710  1036  2120 W libprocessgroup: failed to open /acct/uid_10005/pid_7144/cgroup.procs: No such file or directory
07-28 09:44:06.713  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-28 09:44:06.716  2268  2268 I ConfigService: onCreate
07-28 09:44:06.716  2268  2268 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-28 09:44:06.718  1843  1843 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-28 09:44:06.719  1036  1951 I ActivityManager: Killing 7595:com.google.android.talk/u0a72 (adj 15): empty #17
07-28 09:44:06.721  2268  2268 I ConfigService: onBind returning update interface
,07-28 09:44:06.798  1036  2120 W libprocessgroup: failed to open /acct/uid_10072/pid_7595/cgroup.procs: No such file or directory
,07-28 09:44:06.798  2268  2268 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-28 09:44:06.798  2268  2268 I ConfigService: onBind returning config service
07-28 09:44:06.801  1843  1843 I ConfigFetchService: service connected
07-28 09:44:06.802  2097  2097 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
07-28 09:44:06.806  2268  2268 I ConfigService: onDestroy
07-28 09:44:06.807  1843  8165 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-28 09:44:06.825  5899  8171 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,07-28 09:44:06.832  1843  8173 I PeopleContactsSync: CP2 sync disabled
,07-28 09:44:06.834  1843  4747 I Icing   : doRemovePackageData com.test.thalitest
07-28 09:44:06.845  2097  2884 I GBoardtInterface: onReloaded()
,07-28 09:44:06.847  2097  2097 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
07-28 09:44:06.848  3808  3823 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 09:44:06.850  3808  3824 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 09:44:06.854  1932  1932 D ActionManagerService: notifyUserLog: 1000001
07-28 09:44:06.855  3808  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-28 09:44:06.855  3808  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-28 09:44:06.858  1932  1932 D ActionManagerService: notifyUserLog: 1000001
,07-28 09:44:06.860  3808  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-28 09:44:06.860  3808  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-28 09:44:06.860  3808  3824 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-28 09:44:06.860  3808  4489 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
07-28 09:44:06.860  3808  4489 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
07-28 09:44:06.861  2097  2097 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
07-28 09:44:06.861  2097  2097 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
07-28 09:44:06.863  2097  2097 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
07-28 09:44:06.863  2097  2097 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-28 09:44:06.864  2097  2097 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
07-28 09:44:06.864  2097  2097 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-28 09:44:06.887  1843  8172 W GmsApplication: Using Auth Proxy for data requests.
,07-28 09:44:06.891  1843  8172 W GmsApplication: Using Auth Proxy for data requests.
07-28 09:44:06.913  6945  6945 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,07-28 09:44:06.923  2154  8175 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-28 09:44:06.948  1036  2040 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8177 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-28 09:44:06.984  8177  8177 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 09:44:06.984  8177  8177 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-28 09:44:06.985  8177  8177 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-28 09:44:06.985  8177  8177 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-28 09:44:07.043  8177  8177 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-28 09:44:07.051  8177  8177 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
07-28 09:44:07.062  2268  2288 I art     : Explicit concurrent mark sweep GC freed 4864(294KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 452us total 17.047ms
,07-28 09:44:07.080  8177  8177 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-28 09:44:07.100  8177  8177 D LgDataFeature: LgDataFeature() Constructor: none
,07-28 09:44:07.100  8177  8177 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-28 09:44:07.150  8177  8177 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
