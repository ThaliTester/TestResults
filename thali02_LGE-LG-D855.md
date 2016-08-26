#### Test 797638308bd3e25_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 12:45:27.874  6522  6522 D DocsApplication: Installing DEX configuration.
08-26 12:45:27.892  6522  6522 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 12:45:27.895  6522  6522 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2ce5fc3 com.google.android.apps.docs}
08-26 12:45:27.910  6522  6522 D TAG     : onCreate()
08-26 12:45:27.931  6522  6522 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 12:45:28.463   336   407 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-26 12:45:28.465  3191  6545 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-26 12:45:28.794  1805  4707 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-26 12:45:28.825  1805  4707 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-26 12:45:28.888  1805  4707 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-26 12:45:29.039  6546  6546 D AndroidRuntime: 
08-26 12:45:29.039  6546  6546 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 12:45:29.041  6546  6546 D AndroidRuntime: CheckJNI is OFF
08-26 12:45:29.051  6522  6522 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:45:29.051  6522  6522 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 12:45:29.151  6092  6092 I LockScreenSettings: New app installed broadcast received ..
08-26 12:45:29.154  6092  6092 I LockScreenSettings: Number of installed packages  1
08-26 12:45:29.169  6546  6546 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 12:45:29.172  1036  1906 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 12:45:29.177  6522  6522 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-26 12:45:29.185  1928  2651 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 12:45:29.187  1036  1906 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 12:45:29.187  1036  1906 D ActivityManager: setTaskToReturnTo : TaskRecord{8b9d58e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 12:45:29.187  1036  1906 D ActivityManager: setTaskToReturnTo : TaskRecord{8b9d58e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 12:45:29.188  1036  1906 D WindowStateEx: AppWindowTokenEx init.. 
08-26 12:45:29.190   344   360 E GBMv2   : DFP En is all cleared set to be enabled
08-26 12:45:29.201  1036  1760 V SIM_STK : Menu title from STK is T-Mobile
08-26 12:45:29.209  1036  1906 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6571 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 12:45:29.210  6546  6546 D AndroidRuntime: Shutting down VM
08-26 12:45:29.243  1036  2002 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6588 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 12:45:29.263  1928  2651 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 12:45:29.263  1928  2651 D SplitWindowPolicy: topRunningActivity=ActivityInfo{198909af co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 12:45:29.264  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 12:45:29.264  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{ca6a1bc co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 12:45:29.315  6588  6588 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 12:45:29.315  6588  6588 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-26 12:45:29.317  6571  6571 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 12:45:29.346  1036  1906 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6617 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-26 12:45:29.348  1036  1906 I ActivityManager: Killing 5820:com.google.android.talk/u0a72 (adj 15): empty #17
08-26 12:45:29.390  6571  6571 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-26 12:45:29.404  1036  1642 W libprocessgroup: failed to open /acct/uid_10072/pid_5820/cgroup.procs: No such file or directory
08-26 12:45:29.421  6571  6571 I LibraryLoader: Loading: webviewchromium
08-26 12:45:29.423  6571  6571 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2996-2999)
08-26 12:45:29.423  6571  6571 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 12:45:29.445  6571  6571 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23f98635}
,08-26 12:45:29.447  6571  6571 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 12:45:29.447  6571  6571 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 12:45:29.460  6571  6571 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 12:45:29.461  6571  6571 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 12:45:29.465  6617  6617 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-26 12:45:29.473  6571  6571 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-26 12:45:29.474  6571  6571 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-26 12:45:29.474  6571  6571 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-26 12:45:29.475   325  2151 V AudioPolicyService: registerClient() client 0xb558ace0, uid 10118
08-26 12:45:29.480  6617  6617 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 12:45:29.481  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 12:45:29.484  1036  1118 D BluetoothManagerService: Message: 20
08-26 12:45:29.484  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22f9d7a7:true
08-26 12:45:29.486  6571  6571 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 12:45:29.486  6571  6571 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 12:45:29.486  6571  6571 I Adreno-EGL: Build Date: 12/12/14 금
08-26 12:45:29.486  6571  6571 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 12:45:29.486  6571  6571 I Adreno-EGL: Remote Branch: 
08-26 12:45:29.486  6571  6571 I Adreno-EGL: Local Patches: 
08-26 12:45:29.486  6571  6571 I Adreno-EGL: Reconstruct Branch: 
,08-26 12:45:29.507  1036  2038 I ActivityManager: Killing 5609:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 12:45:29.525  5584  5584 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 12:45:29.525  5584  5584 W System.err: android.os.DeadObjectException
08-26 12:45:29.525  5584  5584 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 12:45:29.525  5584  5584 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-26 12:45:29.525  5584  5584 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 12:45:29.525  5584  5584 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 12:45:29.525  5584  5584 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 12:45:29.525  5584  5584 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 12:45:29.525  5584  5584 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 12:45:29.525  5584  5584 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 12:45:29.525  5584  5584 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 12:45:29.525  5584  5584 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 12:45:29.526  5584  5584 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:29.526  5584  5584 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 12:45:29.526  5584  5584 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 12:45:29.526  5584  5584 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 12:45:29.526  5584  5584 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 12:45:29.526  5584  5584 W System.err: android.os.DeadObjectException
08-26 12:45:29.526  5584  5584 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 12:45:29.526  5584  5584 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-26 12:45:29.526  5584  5584 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 12:45:29.526  5584  5584 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 12:45:29.526  5584  5584 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 12:45:29.526  5584  5584 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 12:45:29.526  5584  5584 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 12:45:29.526  5584  5584 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 12:45:29.526  5584  5584 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 12:45:29.526  5584  5584 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 12:45:29.526  5584  5584 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:29.526  5584  5584 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 12:45:29.526  5584  5584 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 12:45:29.526  5584  5584 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 12:45:29.526  5584  5584 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 12:45:29.526  5584  5584 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 12:45:29.617  1036  1910 W libprocessgroup: failed to open /acct/uid_1000/pid_5609/cgroup.procs: No such file or directory
08-26 12:45:29.618  1036  1910 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 12:45:29.625  5584  5584 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 12:45:29.625  5584  5584 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 12:45:29.672  1036  1765 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6653 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 12:45:29.672  5584  5584 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 12:45:29.695  6571  6646 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 12:45:29.703  6571  6571 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 12:45:29.717  6571  6571 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 12:45:29.721  6571  6571 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 12:45:29.723  6571  6571 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 12:45:29.726  6571  6571 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 12:45:29.726  6571  6571 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-26 12:45:29.737  6571  6571 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-26 12:45:29.742  6571  6571 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 12:45:29.742  6571  6571 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 12:45:29.763  1036  1103 W ActivityManager: Activity pause timeout for ActivityRecord{100561af u0 com.test.thalitest/.MainActivity t6}
,08-26 12:45:29.777  6653  6653 D UEI.SmartControl: Quickset Services start...
,08-26 12:45:29.781  6653  6653 I UEI.SmartControl: Manufacture = LGE
08-26 12:45:29.781  6653  6653 D UEI.SmartControl: Id = LGNevo
08-26 12:45:29.783  6653  6653 D UEI.SmartControl: File observer start...
08-26 12:45:29.784  6653  6653 E UEI.SmartControl: IR Port is disabled: false
08-26 12:45:29.785  6653  6653 D UEI.SmartControl: Starting file observer...
08-26 12:45:29.785  6653  6653 D UEI.SmartControl: Extracting JNI libs...
08-26 12:45:29.785  6653  6653 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 12:45:29.793  6571  6681 D OpenGLRenderer: Render dirty regions requested: true
08-26 12:45:29.793  6571  6681 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 12:45:29.809  6571  6681 D OpenGLRenderer: Enabling debug mode 0
,08-26 12:45:29.818  6571  6571 D Atlas   : Validating map...
08-26 12:45:29.823  1036  1058 D SplitWindow: check instance of lgWin Window{206b261c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 12:45:29.881  6653  6653 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-26 12:45:29.881  6653  6653 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 12:45:29.881  6653  6653 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-26 12:45:29.889  6571  6678 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:45:29.890  6571  6678 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 12:45:29.918  6653  6653 I UEI.SmartControl: --- Selecting new region: 6
,08-26 12:45:29.920  6653  6653 I UEI.SmartControl: Model = LG-D855
08-26 12:45:29.921  6653  6653 D UEI.SmartControl: QS Service created
08-26 12:45:29.946  6653  6653 I UEI.SmartControl: Service initServices...
08-26 12:45:29.949  6653  6653 D UEI.SmartControl: QS start get config
,08-26 12:45:29.963  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +701ms (total +773ms)
08-26 12:45:29.964  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{100561af u0 com.test.thalitest/.MainActivity t6} time:103540
08-26 12:45:29.964  6571  6571 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@316be688 time:103541
,08-26 12:45:30.016  6653  6653 D UEI.SmartControl: Loading JNI Libs...
,08-26 12:45:30.095  6571  6571 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 12:45:30.095  6571  6571 I chromium: 
,08-26 12:45:30.106  6571  6571 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 12:45:30.164  6571  6678 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 12:45:30.164  6571  6678 I chromium: 
,08-26 12:45:30.259   344   362 E GBMv2   : DFP En is all cleared set to be enabled
08-26 12:45:30.260   344   362 E GBMv2   : Set value is all cleared set the max
08-26 12:45:30.260   344   362 I GBMv2   : DFP Enabled. Ignore VFP set
,08-26 12:45:30.286  6571  6691 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-26 12:45:30.298  6571  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 12:45:30.298  6571  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 12:45:30.298  6571  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 12:45:30.298  6571  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 12:45:30.298  6571  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 12:45:30.298  6571  6691 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a564cc added. We now have 1 listener(s)
08-26 12:45:30.304  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:30.312  6571  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-26 12:45:30.318  6571  6691 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:45:30.321  6571  6691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:45:30.323  6653  6653 I UEI.SmartControl: Supports setup maps: true
08-26 12:45:30.324  6571  6691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:45:30.326  6653  6653 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 12:45:30.326  6653  6653 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 12:45:30.326  6653  6653 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 12:45:30.326  6653  6653 I UEI.SmartControl: ### init IR Blaster...
,08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 12:45:30.330  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 12:45:30.331  6571  6691 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c963c1b added. We now have 1 listener(s)
08-26 12:45:30.331  6571  6691 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:45:30.333  6653  6653 D serial_port: Configuring serial port
08-26 12:45:30.335  1036  1530 D WifiService: New client listening to asynchronous messages
08-26 12:45:30.337  6571  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 12:45:30.337  6571  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 12:45:30.338  6571  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 12:45:30.338  6571  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 12:45:30.338  6571  6691 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 12:45:30.341  6653  6653 E UEI.SmartControl: UEIBLaster setting for 616
,08-26 12:45:30.341  6653  6653 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 12:45:30.342  6653  6653 I UEI.SmartControl: configuring settings for MAXQ616
08-26 12:45:30.342  6571  6691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:30.342  6653  6653 I UEI.SmartControl: Get version...
08-26 12:45:30.342  1036  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:30.344  6571  6691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-26 12:45:30.353  6571  6691 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-26 12:45:30.353  6571  6691 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:30.353  6571  6691 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:30.353  6571  6691 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:30.353  6571  6691 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:30.353  6571  6691 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:30.353  6571  6691 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:30.353  6571  6691 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:30.353  6571  6691 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:30.353  6571  6691 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 12:45:30.353  6571  6691 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:45:30.356  6571  6691 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 12:45:30.356  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:30.357  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:30.359  6653  6697 D UEI.SmartControl: serial port data available: 21
08-26 12:45:30.387  6571  6571 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 12:45:30.389  6653  6653 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 12:45:30.389  6653  6653 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 12:45:30.389  6653  6653 I UEI.SmartControl: QS saving settings...
08-26 12:45:30.389  6653  6653 D UEI.SmartControl: IR Blaster version: 25672567
08-26 12:45:30.410  6653  6697 D UEI.SmartControl: serial port data available: 4
,08-26 12:45:30.441  6653  6706 I UEI.SmartControl: Device manager: loading config....
,08-26 12:45:30.441  6653  6706 D UEI.SmartControl: ----------- loading internal config...
08-26 12:45:30.454  6653  6653 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 12:45:30.458  6653  6653 E UEI.SmartControl: Services init done
,08-26 12:45:30.458  6653  6653 D UEI.SmartControl: QS Service init finished
08-26 12:45:30.463  6653  6653 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 12:45:30.463  6653  6653 D UEI.SmartControl: QS Service version code: 201091
08-26 12:45:30.463  6653  6653 D UEI.SmartControl: Service requested: Control
08-26 12:45:30.465  6653  6706 E UEI.SmartControl: Loading SETTINGS...
08-26 12:45:30.469  6653  6653 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 12:45:30.471  1036  1642 I ActivityManager: Killing 5584:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 12:45:30.479  6653  6706 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 12:45:30.507  6653  6705 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 12:45:30.507  6653  6705 D UEI.SmartControl: -----service ready thread exits
08-26 12:45:30.559  1036  1969 W libprocessgroup: failed to open /acct/uid_10112/pid_5584/cgroup.procs: No such file or directory
,08-26 12:45:30.560  6653  6653 D UEI.SmartControl: Internal service binding...
,08-26 12:45:31.214  6571  6698 W jxcore-log: Initializing JXcore engine
08-26 12:45:31.214  6571  6698 W jxcore-log: JXcore engine is ready
,08-26 12:45:31.245  6698  6698 W Thread-752: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8346]" dev="sockfs" ino=8346 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-26 12:45:31.245  6698  6698 W Thread-752: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 12:45:31.245  6698  6698 W Thread-752: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8464]" dev="sockfs" ino=8464 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 12:45:31.245  6698  6698 W Thread-752: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 12:45:31.245  6698  6698 W Thread-752: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30549]" dev="sockfs" ino=30549 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-26 12:45:31.274  6571  6698 W jxcore-log: Starting JXcore engine
,08-26 12:45:31.358  6571  6698 W jxcore-log: Platform android
08-26 12:45:31.358  6571  6698 W jxcore-log: 
08-26 12:45:31.358  6571  6698 W jxcore-log: Process ARCH arm
08-26 12:45:31.358  6571  6698 W jxcore-log: 
,08-26 12:45:31.551  6571  6698 I jxcore-log: JXcore Cordova bridge is ready!
08-26 12:45:31.551  6571  6698 I jxcore-log: 
,08-26 12:45:31.551  6571  6698 W jxcore-log: JXcore engine is started
,08-26 12:45:31.562  6571  6691 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 12:45:31.570  6571  6571 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 12:45:33.005  2786  2786 I MusicWidget: mDelayedStopHandler : unbind
,08-26 12:45:33.012  2169  2169 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 12:45:33.012  2169  2169 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 12:45:33.012  2169  2169 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-26 12:45:33.013  2169  2169 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 12:45:33.013  2169  2169 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 12:45:33.013  2169  2169 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-26 12:45:33.014  2169  2169 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 12:45:33.014  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-26 12:45:33.015  1036  1642 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1f352a7acom.lge.music.MediaPlaybackService$5@10f0722b
08-26 12:45:33.015  2169  2169 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 12:45:33.015  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 12:45:33.016  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 12:45:33.016  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 12:45:33.016  2169  2169 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2ec950b1
08-26 12:45:33.017  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 12:45:33.017  2169  2169 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 12:45:33.017  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 12:45:33.017  2169  2169 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 12:45:33.017  2169  2169 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 12:45:33.018  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 12:45:33.018  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 12:45:33.018  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 12:45:33.019  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 12:45:33.019  2169  2169 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 12:45:33.019  2169  2169 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 12:45:33.020  2169  2169 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 12:45:33.021  2169  2169 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 12:45:33.021  2169  2169 V MediaPlayer[Native]: reset
08-26 12:45:33.025  2169  2169 V MediaPlayer[Native]: setListener
08-26 12:45:33.025  2169  2169 V MediaPlayer[Native]: disconnect
08-26 12:45:33.025  2169  2169 V MediaPlayer[Native]: destructor
08-26 12:45:33.025   325  1371 V AudioFlinger: releasing 18 from 2169 for -1
08-26 12:45:33.025   325  1371 V AudioFlinger:  decremented refcount to 0
08-26 12:45:33.025   325  1371 V AudioFlinger: purging stale effects
08-26 12:45:33.026  2169  2169 V MediaPlayer[Native]: disconnect
08-26 12:45:33.027  2169  2169 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-26 12:45:33.028  2169  2169 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 12:45:33.028  2169  2169 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 12:45:33.029  2169  2169 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-26 12:45:33.029  2169  2169 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 12:45:33.029  2169  2169 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 12:45:33.029  2169  2169 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 829154952
08-26 12:45:33.029  2169  2169 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 829154952
08-26 12:45:33.037  2169  2169 I SmartShareClient: [SmartShareManagerClient] terminate service: 2169/MediaPlaybackService/808269087
,08-26 12:45:33.039  2169  2169 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 12:45:33.039  2169  2169 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@5ec821
08-26 12:45:33.040  2169  2169 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 12:45:33.041  2169  2169 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-26 12:45:33.041  2169  2169 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 12:45:33.041  2169  2169 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-26 12:45:33.043  1036  1561 I ActivityManager: Killing 5530:com.lge.clock/u0a10 (adj 15): empty #17
08-26 12:45:33.051  2169  2169 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
08-26 12:45:33.127  1036  1058 W libprocessgroup: failed to open /acct/uid_10010/pid_5530/cgroup.procs: No such file or directory
,08-26 12:45:33.140  6522  6522 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-26 12:45:33.151  1036  1969 I ActivityManager: Killing 6236:com.android.calendar/u0a13 (adj 15): empty #17
08-26 12:45:33.226  1036  1946 W libprocessgroup: failed to open /acct/uid_10013/pid_6236/cgroup.procs: No such file or directory
,08-26 12:45:34.126  6522  6548 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 12:45:35.452  6653  6707 D UEI.SmartControl: Internal timer expired: 1
,08-26 12:45:35.453  6653  6707 D UEI.SmartControl: unbind internal service
,08-26 12:45:35.464  6653  6653 D UEI.SmartControl: Service.onUnbind: IControl
08-26 12:45:35.465  6653  6653 D UEI.SmartControl: Service.onDestroy
08-26 12:45:35.465  6653  6653 D UEI.SmartControl: Lock is in USE false
08-26 12:45:35.465  6653  6653 D UEI.SmartControl: unbind internal service
08-26 12:45:35.466  6653  6653 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2ec950b1
08-26 12:45:35.466  6653  6653 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-26 12:45:35.467  6653  6653 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 12:45:35.467  6653  6653 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 12:45:35.467  6653  6653 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-26 12:45:35.467  6653  6653 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 12:45:35.467  6653  6653 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-26 12:45:35.467  6653  6653 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-26 12:45:35.467  6653  6653 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 12:45:35.467  6653  6653 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:45:35.468  6653  6653 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 12:45:35.468  6653  6653 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 12:45:35.468  6653  6653 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:35.468  6653  6653 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 12:45:35.468  6653  6653 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 12:45:35.468  6653  6653 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 12:45:35.468  6653  6653 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2ec950b1
08-26 12:45:35.472  6653  6653 D serial_port: close(fd = 25)
,08-26 12:45:35.480  6653  6653 I UEI.SmartControl: Serial port is closed.
08-26 12:45:35.480  6653  6653 I UEI.SmartControl: Serial port is closed.
08-26 12:45:35.480  6653  6653 D UEI.SmartControl: Blaster closed
08-26 12:45:35.481  6653  6653 D UEI.SmartControl: Shut down QS...
08-26 12:45:35.481  6653  6653 D UEI.SmartControl: Stopping QS lib
08-26 12:45:35.481  6653  6653 D UEI.SmartControl: QS lib stop result = true
08-26 12:45:35.481  6653  6653 D UEI.SmartControl: Stopped QS lib
08-26 12:45:35.481  6653  6653 D UEI.SmartControl: Stopped file observer...
08-26 12:45:35.481  6653  6653 D UEI.SmartControl: QS shutdown complete
08-26 12:45:36.937  1805  6428 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 12:45:36.944   320  6733 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-26 12:45:36.944   320  6733 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-26 12:45:36.945   320  6733 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-26 12:45:37.153  1805  1805 I ConfigFetchService: fetch service done; releasing wakelock
,08-26 12:45:37.154  1805  1805 I ConfigFetchService: stopping self
,08-26 12:45:37.161  2152  2152 I ConfigService: onDestroy
,08-26 12:45:41.622  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 12:45:41.622  6571  6698 I jxcore-log: 
,08-26 12:45:41.625  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 12:45:41.625  6571  6698 I jxcore-log: 
,08-26 12:45:41.629  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:41.629  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:41.629  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:41.629  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:41.629  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:41.629  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:41.629  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:41.629  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:41.632  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:45:41.634  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 12:45:41.634  6571  6698 I jxcore-log: 
,08-26 12:45:41.635  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-26 12:45:41.635  6571  6698 I jxcore-log: 
,08-26 12:45:42.053  1036  1103 I ActivityManager: Waited long enough for: ServiceRecord{2ee3bbfb u0 com.google.android.gms/.wearable.service.WearableService}
,08-26 12:45:42.146  6571  6698 D executeNativeTests: Running unit tests
,08-26 12:45:42.248  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 12:45:42.248  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c added. We now have 2 listener(s)
,08-26 12:45:42.249  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 12:45:42.251  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-26 12:45:42.251  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 12:45:42.251  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 12:45:42.251  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:45:42.251  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 added. We now have 2 listener(s),
,08-26 12:45:42.251  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 12:45:42.251  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-26 12:45:42.254  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:45:42.256  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-26 12:45:42.256  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.256  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.256  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.256  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:42.256  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.256  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:42.256  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:42.257  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:45:42.257  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:45:42.258  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:42.259  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:42.261  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 12:45:42.263  6571  6698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:45:42.263  6571  6698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 12:45:42.265  6571  6698 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
,08-26 12:45:42.266  6571  6698 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 12:45:42.266  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 12:45:42.266  6571  6698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 12:45:42.266  6571  6698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 12:45:42.267  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.267  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.267  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.268  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.268  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 12:45:42.268  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:45:42.268  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:45:42.268  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c removed from the list
08-26 12:45:42.268  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.268  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 removed from the list,
08-26 12:45:42.268  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.268  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.269  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 12:45:42.269  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.270  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.270  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.270  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.270  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
,08-26 12:45:42.271  6571  6698 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 12:45:42.271  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.271  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 12:45:42.271  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.271  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.271  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.271  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:42.272  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.272  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.272  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.272  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 12:45:42.272  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.272  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.272  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.272  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.272  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.272  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:45:42.272  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.272  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-26 12:45:42.278  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 12:45:42.279  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 12:45:42.279  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 12:45:42.279  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-26 12:45:42.279  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 12:45:42.279  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 12:45:42.279  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 12:45:42.279  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 12:45:42.279  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-26 12:45:42.279  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.279  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.279  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.280  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 12:45:42.280  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.280  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.280  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.280  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 12:45:42.280  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.280  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.280  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.280  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:42.280  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.280  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.281  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.281  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.281  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:45:42.281  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.282  6571  6698 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 12:45:42.284  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:42.286  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:42.286  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.286  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
08-26 12:45:42.286  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.286  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:42.286  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.286  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:42.286  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:42.286  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.287  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:45:42.288  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:42.288  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:42.289  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:45:42.289  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:45:42.289  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-26 12:45:42.289  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:42.289  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 12:45:42.292  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 12:45:42.292  1036  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-26 12:45:42.296  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 12:45:42.299  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:45:42.301  6571  6698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 12:45:42.302  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:45:42.302  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:45:42.303  6571  6698 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-26 12:45:42.304  6571  6698 I io.jxcore.node.ConnectionHelper: start: OK
08-26 12:45:42.306  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.306  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.306  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.307  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.307  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.307  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:45:42.307  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.307  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.307  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.307  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.307  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.307  6571  6698 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 12:45:42.308  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:42.310  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:42.310  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.310  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.310  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.310  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:42.310  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.310  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:42.310  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:42.311  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.311  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:45:42.312  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:42.313  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:45:42.313  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:45:42.313  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:45:42.313  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:42.313  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirect,Manager: bind: Binding a new listener
08-26 12:45:42.313  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:42.316  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:45:42.316  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:45:42.317  6571  6698 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 12:45:42.317  6571  6698 I io.jxcore.node.ConnectionHelper: start: OK
08-26 12:45:42.318  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.318  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.318  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.319  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.319  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.319  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:45:42.319  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.319  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.319  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.319  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.319  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.319  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.319  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.320  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.320  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.321  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.321  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.321  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.321  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.322  6571  6698 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 12:45:42.323  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:42.325  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:42.325  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.325  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.325  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.325  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:42.325  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.325  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:42.325  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:42.326  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.326  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:45:42.327  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:45:42.327  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:45:42.327  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:45:42.327  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:42.327  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 12:45:42.327  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:42.330  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:42.332  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:45:42.332  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:45:42.334  6571  6698 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 12:45:42.334  6571  6698 I io.jxcore.node.ConnectionHelper: start: OK
08-26 12:45:42.334  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.334  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.334  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.335  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.335  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.335  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.335  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.335  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.336  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:45:42.336  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.336  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.336  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.336  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.336  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.336  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.336  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.337  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.337  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.338  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.338  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.338  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.338  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.338  6571  6698 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 12:45:42.339  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.339  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.339  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.339  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.339  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.339  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.339  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.339  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.339  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.339  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.339  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.339  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.339  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.339  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.340  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.341  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.341  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.341  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.341  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.341  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.343  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 12:45:42.343  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.343  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.343  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.344  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.344  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.344  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.344  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.344  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.344  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.344  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.344  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.344  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.344  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.344  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.345  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.345  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.345  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.345  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.345  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.345  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.346  6571  6698 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 12:45:42.346  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.346  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.346  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.347  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.347  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.347  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.347  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.347  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.347  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.347  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.347  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.347  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.347  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.347  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.348  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.348  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.348  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.348  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.348  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.348  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.349  6571  6698 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 12:45:42.349  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.349  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.349  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.349  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.349  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.349  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.349  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.349  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.349  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.349  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.349  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.349  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.349  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.349  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:42.352  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.352  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.353  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.353  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.353  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.353  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.354  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 12:45:42.354  6571  6698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:45:42.354  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 12:45:42.355  6571  6698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 12:45:42.355  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 12:45:42.355  6571  6698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 12:45:42.355  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.355  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.355  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.355  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.355  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.355  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.355  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.355  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.356  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.356  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.356  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.356  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.356  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.356  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.356  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.356  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.356  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.357  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.357  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.357  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.357  6571  6698 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:45:42.357  6571  6698 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 12:45:42.357  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 12:45:42.359  6571  6698 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:45:42.359  6571  6698 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 12:45:42.359  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 12:45:42.360  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 12:45:42.360  6571  6698 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 12:45:42.360  6571  6698 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 12:45:42.360  6571  6698 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 12:45:42.360  6571  6698 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:45:42.360  6571  6698 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 12:45:42.360  6571  6698 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 12:45:42.360  6571  6698 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:45:42.360  6571  6698 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 12:45:42.360  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 12:45:42.365  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 12:45:42.368  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 12:45:42.368  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 12:45:42.369  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 12:45:42.369  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 12:45:42.369  6571  6698 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 12:45:42.370  6571  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 816)
08-26 12:45:42.370  6571  6698 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 12:45:42.370  6571  6698 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 12:45:42.371  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.371  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.371  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.371  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.371  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.371  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.371  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 12:45:42.372  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.372  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.372  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.372  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.372  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.373  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.373  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.373  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.374  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.374  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.375  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.375  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.375  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.375  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.376  6571  6698 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 12:45:42.376  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.376  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.376  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.376  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.376  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.376  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.377  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.377  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.377  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.377  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.377  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.377  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.377  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.377  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.379  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.379  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.379  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.379  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.379  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.379  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.380  6571  6735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 816
08-26 12:45:42.380  6571  6735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 816)
08-26 12:45:42.381  6571  6698 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 12:45:42.381  6571  6735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 816)
08-26 12:45:42.381  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.381  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.381  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.381  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.381  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.381  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.381  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.381  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.381  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.381  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.381  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.381  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.381  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.381  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.382  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.382  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.382  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.382  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.382  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.382  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.383  6571  6698 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 12:45:42.383  6571  6698 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 12:45:42.383  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 12:45:42.383  6571  6698 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 12:45:42.383  6571  6698 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55,
08-26 12:45:42.383  6571  6698 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 12:45:42.383  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 12:45:42.383  6571  6698 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 12:45:42.384  6571  6698 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 12:45:42.384  6571  6698 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 12:45:42.384  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 12:45:42.384  6571  6698 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 12:45:42.384  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.384  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.384  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.388  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.388  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.388  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.388  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.388  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.388  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.388  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.389  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.389  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.389  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.389  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.393  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.393  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.394  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.394  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.394  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.394  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.394  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.394  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.394  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.394  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.394  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.394  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.394  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.394  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.394  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.394  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.394  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.394  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.395  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.395  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.395  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.395  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.395  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.395  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.395  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.395  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.395  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.395  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.395  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.395  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.395  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.395  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.395  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.395  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.395  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.396  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.396  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.396  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.396  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.397  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.397  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.398  6571  6698 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 12:45:42.398  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:42.398  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 12:45:42.399  6571  6698 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 12:45:42.399  6571  6698 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 12:45:42.399  6571  6571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 12:45:42.399  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 12:45:42.399  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 12:45:42.405  1036  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:42.412  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.412  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 12:45:42.413  6571  6736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:45:42.413  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 12:45:42.413  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 12:45:42.413  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.413  6571  6698 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 12:45:42.413  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.413  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.413  6571  6571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 12:45:42.413  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 12:45:42.413  6571  6698 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 12:45:42.413  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 12:45:42.413  3850  3868 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=83
08-26 12:45:42.414  6571  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 12:45:42.414  6571  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 12:45:42.414  6571  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 12:45:42.415  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 12:45:42.416  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:45:42.416  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:45:42.416  6571  6698 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 12:45:42.416  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.416  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.417  6571  6698 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:45:42.420  6571  6571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:45:42.420  6571  6571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 12:45:42.420  6571  6571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 12:45:42.420  6571  6571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 12:45:42.421  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.421  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.421  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.421  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.421  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.421  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.421  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.421  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.421  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.421  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.421  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.421  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.421  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.421  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.421  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.433  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.433  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.433  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.433  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
,08-26 12:45:42.442  6571  6698 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 12:45:42.443  6571  6698 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 12:45:42.443  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 12:45:42.444  6571  6734 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-26 12:45:42.445  6571  6698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 12:45:42.445  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.445  6571  6734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 816)
08-26 12:45:42.445  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.445  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.446  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.446  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.446  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.446  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.446  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.446  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.446  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.446  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.446  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.446  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.446  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:45:42.450  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.450  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.450  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.450  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.451  1036  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:42.452  1036  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:42.453  1036  2002 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:42.454  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.454  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.454  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:45:42.454  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.454  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.454  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.454  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.454  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.454  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.454  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.455  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.455  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.455  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.455  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.455  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.455  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.455  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.455  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.456  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:45:42.456  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:45:42.456  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skip,ping...
08-26 12:45:42.456  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:45:42.456  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.456  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.456  6571  6698 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@493709c not in the list
08-26 12:45:42.456  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:45:42.457  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.457  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:42.457  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.457  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.457  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:45:42.457  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:42.457  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:45:42.457  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:45:42.457  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 12:45:42.457  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13beaaa5 not in the list
08-26 12:45:42.458  6571  6698 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 12:45:42.458  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-26 12:45:42.459  6571  6698 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 12:45:42.459  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 12:45:42.459  6571  6698 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 12:45:42.459  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 12:45:42.461  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 12:45:42.461  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 12:45:42.461  6571  6698 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 12:45:42.461  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-26 12:45:42.462  6571  6698 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 12:45:42.462  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 12:45:42.462  6571  6698 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 12:45:42.462  6571  6698 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 12:45:42.462  6571  6698 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 12:45:42.462  6571  6698 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-26 12:45:42.463  6571  6698 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 12:45:42.464  6571  6698 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 12:45:42.464  6571  6698 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 12:45:42.464  6571  6698 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 12:45:42.465  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:45:42.465  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c2b02d2 added. We now have 2 listener(s)
08-26 12:45:42.465  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:45:42.466  6571  6698 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 12:45:42.467  1036  2038 D WifiServiceImplEx: setWifiEnabled: true pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 12:45:42.467  1036  2038 D WifiService: setWifiEnabled: true pid=6571, uid=10118
08-26 12:45:42.467  1036  2038 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 12:45:42.469  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:45:42.469  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29985fa3 added. We now have 3 listener(s)
08-26 12:45:42.469  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:45:42.472  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 12:45:42.472  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e1692a0 added. We now have 4 listener(s)
08-26 12:45:42.472  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:45:42.474  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:45:42.474  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18095e59 added. We now have 5 listener(s)
08-26 12:45:42.474  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:45:42.476  1036  2038 D WifiServiceImplEx: setWifiEnabled: false pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 12:45:42.477  1036  2038 D WifiService: setWifiEnabled: false pid=6571, uid=10118
08-26 12:45:42.477  1036  2038 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:45:42.486  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 12:45:42.486  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 12:45:42.487  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 12:45:42.487  1036  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:42.487  1036  1059 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@351033b2 mBinding = false
08-26 12:45:42.488  1036  1524 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 12:45:42.488  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 12:45:42.489  1036  1524 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-26 12:45:42.489  1036  1524 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 12:45:42.490  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 12:45:42.490  1036  1524 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 12:45:42.490  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 12:45:42.490  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 12:45:42.491  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 12:45:42.491  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 12:45:42.497  1036  1118 D BluetoothManagerService: Message: 2
,08-26 12:45:42.498  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 12:45:42.499  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 12:45:42.499  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 12:45:42.499  1036  1118 D BluetoothManagerService: Sending off request.
08-26 12:45:42.499  3850  3868 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 12:45:42.500  3850  3926 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 12:45:42.500  3850  3926 D BluetoothAdapterProperties: Setting state to 13
08-26 12:45:42.500  3850  3926 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 12:45:42.500  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 12:45:42.501  1036  1523 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.501  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.501  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 12:45:42.501  2648  2648 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 12:45:42.501  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 12:45:42.501  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 12:45:42.502  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-26 12:45:42.502  1036  2784 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.502  3850  3926 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 12:45:42.503  3850  3926 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 12:45:42.503  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:45:42.506  3850  3933 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:45:42.506  3850  3926 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 12:45:42.506  3850  4214 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:42.507  3850  3926 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 12:45:42.507  3850  4258 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:42.508  3850  4211 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 12:45:42.508  3850  4211 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:42.508  3850  4211 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 12:45:42.508  3850  4211 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 12:45:42.508  3850  4211 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 12:45:42.508  3850  4211 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 12:45:42.508  3850  4211 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 12:45:42.508  3850  4211 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 12:45:42.508  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,08-26 12:45:42.508  3850  4035 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 12:45:42.508  3850  4253 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:42.508  3850  4254 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:42.509  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 12:45:42.510  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 12:45:42.510  3850  4035 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 12:45:42.515  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.515  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:45:42.515  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.515  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.515  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.515  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:42.515  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.515  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:42.515  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:42.515  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.516  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.516  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:45:42.517  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:42.518   320   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 12:45:42.521  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:42.540  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.541  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:42.541  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.541  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.541  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.541  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:42.541  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:45:42.541  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:42.541  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:45:42.556  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.556  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 12:45:42.559  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.559  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:42.559  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.559  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.559  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.559  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:42.559  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:42.559  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:45:42.559  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:42.560  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.560  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:42.560  1036  1103 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6739 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-26 12:45:42.561  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 12:45:42.561  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-26 12:45:42.561  1036  1118 D BluetoothManagerService: Message: 60
08-26 12:45:42.561  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 12:45:42.561  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 12:45:42.586  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 12:45:42.588  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:42.588  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:42.589  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 12:45:42.590  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:42.592  1036  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 12:45:42.592  1036  1531 D DSQN    : disableDataServiceNotify
08-26 12:45:42.592  1036  1531 D DSQN    : stop dsqn bin
08-26 12:45:42.594  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:42.594  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:42.594  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 12:45:42.595  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:42.596  3850  3850 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:42.597  3850  3850 D BluetoothMapService: STATE_TURNING_OFF
08-26 12:45:42.597  3850  3850 V BluetoothMapService: Handler(): got msg=4
08-26 12:45:42.597  3850  3850 D BluetoothMapService: MAP Service closeService in
08-26 12:45:42.597  3850  3850 D BluetoothMapMasInstance: MAP Service shutdown
08-26 12:45:42.597  3850  3850 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 12:45:42.597  3850  3850 V BluetoothMapService: MAP Service closeService out
08-26 12:45:42.598  3850  3850 V BtOppService: Receiver DISABLED_ACTION 
08-26 12:45:42.601  1036  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 12:45:42.601  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:42.601  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:42.602  1036  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:42.602  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 12:45:42.603  1036  2783 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.603  1036  2783 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.603  3850  3850 I BtOppRfcommListener: stopping Accept Thread
08-26 12:45:42.603  1036  2783 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 12:45:42.603  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.603  3850  3850 V BtOppRfcommListener: close mBtServerSocket
08-26 12:45:42.603  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:42.603  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.603  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.603  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.603  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:42.603  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:42.603  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:42.603  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:42.604  3850  4253 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 12:45:42.604  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.b,luetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.604  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:42.604  3850  3850 V BtOppRfcommListener: waiting for thread to terminate
08-26 12:45:42.604  3850  3850 V BtOppRfcommListener: done waiting for thread to terminate
08-26 12:45:42.605  1036  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 12:45:42.605  1036  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 12:45:42.605  1588  1820 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 12:45:42.605  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 12:45:42.615  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-26 12:45:42.656  1036  1103 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6770 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 12:45:42.660  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:42.660  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 12:45:42.662  3850  3850 V BtOppService: onDestroy
08-26 12:45:42.663  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:42.663  1036  1523 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.663  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.663  1036  1523 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1e43e1db
08-26 12:45:42.664  1036  1523 D LGWifiP2pService: P2pDisablingState
08-26 12:45:42.664  1036  1523 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.664  1036  1523 D LGWifiP2pService: p2p socket connection lost
08-26 12:45:42.664  1036  1523 D LGWifiP2pService: P2pDisabledState
08-26 12:45:42.665  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.665  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:42.665  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.665  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.665  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:42.665  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:42.665  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:42.665  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:42.665  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:42.665  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:42.665  1036  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:42.665  1036  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:42.665  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:42.666  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:42.666  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:42.667  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:42.667  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:42.668  1036  1524 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 12:45:42.668  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:42.668  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:42.668  1036  1531 D NetworkManagementService: Removing idletimer
08-26 12:45:42.669  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:42.669  1036  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:42.669  1036  1531 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 12:45:42.669  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 12:45:42.669  1841  1841 D TelephonyNetworkFactory-1: new score 0 for exisiting requ,est NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:42.669  1036  1372 V AlarmManager: RTC_WAKEUP set : Alarm{2a02f85f type 0 when 1472208342559 com.android.vending} when 1472208342559
08-26 12:45:42.670  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 12:45:42.670  1036  1522 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 12:45:42.671  1036  1522 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 12:45:42.673  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 12:45:42.673  1928  1928 D WfdsService: WifiP2pState is changed : false
,08-26 12:45:42.674  1928  2279 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 12:45:42.674  1928  2279 D WfdsService: Set the WFDS Monitor: false
08-26 12:45:42.674  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 12:45:42.674  1928  2279 D WfdsMonitor: WFDS Monitor is stopped
08-26 12:45:42.674  1928  2279 D WfdsService: STATE : WfdsDisabledState - enter
08-26 12:45:42.674  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 12:45:42.675  1928  2282 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 12:45:42.675  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 12:45:42.675  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:42.675  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:42.675  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 12:45:42.675  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 12:45:42.675  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-26 12:45:42.675  1036  1542 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.675  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 12:45:42.675  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 12:45:42.675  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 12:45:42.675  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 12:45:42.675  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 12:45:42.675  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 12:45:42.675  1928  2730 D CtrlSupplicant: Received on exit socket, terminate
08-26 12:45:42.675  1928  2730 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 12:45:42.676  1928  2730 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 12:45:42.676  1928  2730 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 12:45:42.676  1928  2279 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 12:45:42.676  1036  1543 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.682  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 12:45:42.682  1036  1523 D LGWifiP2pService: P2pDisabledState{ when=-13ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.682  1036  1523 D LGWifiP2pService: DefaultState{ when=-13ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:42.682  2648  2648 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 12:45:42.684  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 12:45:42.684  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 12:45:42.685  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
,08-26 12:45:42.685   320   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 12:45:42.690  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 12:45:42.691  1036  1524 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 12:45:42.692  1036  1524 D WifiNative-p2p0: TERMINATE: returned true
08-26 12:45:42.692  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 12:45:42.692  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-26 12:45:42.692  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 12:45:42.692  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:42.692  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:42.692  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 12:45:42.693  1036  1524 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:42.694  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:45:42.694  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 12:45:42.696  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,08-26 12:45:42.697  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.698  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:42.698  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.698  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.698  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:42.698  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:42.698  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:42.698  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:42.698  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:42.698  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:45:42.698  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 12:45:42.699  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.699  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:42.700  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.700  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:42.700  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:42.700  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:42.700  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:42.700  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:42.700  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:42.700  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:42.700  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:42.700  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:42.701  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:42.713  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 12:45:42.715  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:42.716  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:42.736  1036  1910 V SIM_STK : Menu title from STK is T-Mobile
08-26 12:45:42.737  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 12:45:42.738  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:42.738  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:42.739  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:42.739  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:42.739  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:42.755  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 12:45:42.756  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 12:45:42.756  1036  2038 I art     : Explicit concurrent mark sweep GC freed 44692(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.641ms total 115.229ms
08-26 12:45:42.761  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:42.762  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:42.764  3850  3850 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 12:45:42.774  6770  6770 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 12:45:42.774  6770  6770 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-26 12:45:42.774  6770  6770 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 12:45:42.774  6770  6770 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-26 12:45:42.775  6770  6770 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 12:45:42.776  6770  6770 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 12:45:42.795  1036  2784 D DhcpStateMachine: StoppedState
08-26 12:45:42.795  1036  2784 D DhcpStateMachine: StoppedState{ when=-109ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 12:45:42.796  1036  1524 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 12:45:42.797  1036  1524 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 12:45:42.804  2648  2648 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 12:45:42.804  2648  2648 I wpa_supplicant: monitor socket send errors count : 1
08-26 12:45:42.804  2648  2648 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-2\x00 that cannot receive messages
08-26 12:45:42.805  1036  2694 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 12:45:42.805  1036  2694 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 12:45:42.812  6739  6739 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-26 12:45:42.812  6739  6739 W LG Account v2.2: No ProfileInfo entries
08-26 12:45:42.812  6739  6739 I LG Account v2.2: isEnabled: false
08-26 12:45:42.812  6739  6739 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 12:45:42.812  6739  6739 I Feature : [Lifetracker]Country: EU
08-26 12:45:42.812  6739  6739 I Feature : [Lifetracker]Operator: OPEN
08-26 12:45:42.812  6739  6739 I Feature : [Lifetracker]Ranking support: false
08-26 12:45:42.812  6739  6739 I Feature : [Lifetracker]Comfort support: false
08-26 12:45:42.813  6739  6739 I Feature : [Lifetracker]Accessory: true
08-26 12:45:42.813  6739  6739 I Feature : [Lifetracker]Health device: true
08-26 12:45:42.813  6739  6739 I Feature : [Lifetracker]Extra Pedometer: false
08-26 12:45:42.813  6739  6739 I Feature : [Lifetracker]Blood glucose device: false
08-26 12:45:42.813  6739  6739 I Feature : [Lifetracker]Device Number: 3
08-26 12:45:42.821  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:42.843  2648  2648 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 12:45:42.844  2648  2648 W wpa_supplicant: USIM:  scard_deinit function
08-26 12:45:42.844  1036  2694 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 12:45:42.844  1036  2694 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 12:45:42.844  1036  2694 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 12:45:42.844  1036  2694 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 12:45:42.845  1036  2694 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:45:42.845  1036  2694 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:45:42.845  1036  1524 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116407
08-26 12:45:42.846  1036  1524 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116408
08-26 12:45:42.847  1036  1524 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116408  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 12:45:42.847  1036  1524 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116408  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 12:45:42.848  1036  1118 D Tethering: InitialState.processMessage what=4
08-26 12:45:42.854  1036  1642 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6791 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 12:45:42.856  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 12:45:42.857  6770  6770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 12:45:42.857  1036  1524 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:42.858  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:42.860  3850  3850 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 12:45:42.860  3850  3850 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:42.860  3850  3850 V BluetoothPbapReceiver: ***********state = 13
08-26 12:45:42.862  3850  3850 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 12:45:42.862  3850  3850 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:42.862  3850  3850 V BluetoothPbapService: state: 13
08-26 12:45:42.862  3850  3850 V BluetoothPbapService: Pbap Service closeService in
08-26 12:45:42.863  1036  1118 D BluetoothManagerService: Message: 20
08-26 12:45:42.863  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fe6870a:true
08-26 12:45:42.864  2152  2152 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:45:42.864  3850  3850 V BluetoothPbapService: successfully stopped pbap service
08-26 12:45:42.864  3850  3850 V BluetoothPbapService: Pbap Service closeService out
08-26 12:45:42.864  3850  3850 V BluetoothPbapService: Pbap Service onDestroy
08-26 12:45:42.864  3850  3850 V BluetoothPbapService: Pbap Service closeService in
08-26 12:45:42.864  3850  3850 V BluetoothPbapService: Pbap Service closeService out
08-26 12:45:42.864  3850  3850 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 12:45:42.871  1036  1118 D BluetoothManagerService: Message: 30
,08-26 12:45:42.873  1036  1118 D BluetoothManagerService: Message: 30
08-26 12:45:42.875  6770  6770 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 12:45:42.876  6770  6770 D BluetoothMap: Create BluetoothMap proxy object
08-26 12:45:42.876  1036  1118 D BluetoothManagerService: Message: 30
08-26 12:45:42.881  1036  1118 D BluetoothManagerService: Message: 30
08-26 12:45:42.882  6770  6770 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 12:45:42.883  6770  6770 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-26 12:45:42.891  6770  6770 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-26 12:45:42.893  6770  6770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-26 12:45:42.900  6770  6770 D DockEventReceiver: finishStartingService: stopping service
08-26 12:45:42.904  2648  2648 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 12:45:42.905  1036  2694 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 12:45:42.905  1036  2694 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 12:45:42.905  1036  2694 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 12:45:42.905  1036  1524 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-26 12:45:42.905  6770  6770 D BluetoothInputDevice: Proxy object connected
08-26 12:45:42.906  6770  6770 D HidProfile: Bluetooth service connected
08-26 12:45:42.907  6770  6770 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 12:45:42.908  6770  6770 D PanProfile: Bluetooth service connected
,08-26 12:45:42.908  6770  6770 D BluetoothMap: Proxy object connected
08-26 12:45:42.908  6770  6770 D MapProfile: Bluetooth service connected
08-26 12:45:42.909  6770  6770 D BluetoothMap: getConnectedDevices()
08-26 12:45:42.909  6770  6770 D BluetoothMap: Bluetooth is Not enabled
08-26 12:45:42.909  6770  6770 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 12:45:42.910  6770  6770 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 12:45:42.913  6770  6770 D BluetoothPermissionRequest: onReceive
08-26 12:45:42.914  6770  6770 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 12:45:42.915  6791  6791 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 12:45:42.918  6791  6791 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 12:45:42.918  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:45:42.919  6770  6770 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 12:45:42.920  1036  1933 I ActivityManager: Killing 6200:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-26 12:45:42.920  6571  6571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 12:45:42.929  6039  6039 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 12:45:42.945  1036  1984 W libprocessgroup: failed to open /acct/uid_10014/pid_6200/cgroup.procs: No such file or directory
,08-26 12:45:42.948  1036  1933 I ActivityManager: Killing 6299:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 12:45:42.959  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:42.996  6770  6770 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:45:42.996  6770  6770 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 12:45:43.007  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:43.016  1036  1946 W libprocessgroup: failed to open /acct/uid_10004/pid_6299/cgroup.procs: No such file or directory
08-26 12:45:43.016  3850  3850 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 12:45:43.016  3850  3850 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-26 12:45:43.019  3850  3850 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-26 12:45:43.027  1036  1524 D WifiOffDelayIfNotUsed: stopMonitoring
,08-26 12:45:43.027  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 12:45:43.027  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-26 12:45:43.027  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 12:45:43.028  1036  1933 I ActivityManager: Killing 6435:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-26 12:45:43.055  2169  2169 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
,08-26 12:45:43.085  1036  2021 W libprocessgroup: failed to open /acct/uid_10008/pid_6435/cgroup.procs: No such file or directory
,08-26 12:45:43.091  1928  1928 D WfdsService: Supplicant Connection state is changed : false
08-26 12:45:43.091  1928  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 12:45:43.091  1928  2279 D WfdsService: Set the WFDS Monitor: false
08-26 12:45:43.091  1928  2279 D WfdsMonitor: WFDS Monitor is stopped
08-26 12:45:43.093  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 12:45:43.094  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:43.097  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.097  2456  2456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 12:45:43.100  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.162  1036  1933 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6820 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 12:45:43.164  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 12:45:43.165  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 12:45:43.165  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 12:45:43.165  3850  3850 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:43.166  3850  3850 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 12:45:43.176  3850  3850 V BluetoothFtpService: Ftp Service onStartCommand
08-26 12:45:43.176  3850  3850 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:43.177  3850  3850 V BluetoothFtpService: Ftp Service closeService
,08-26 12:45:43.177  3850  3850 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 12:45:43.182  3850  3850 V BluetoothFtpService: successfully stopped ftp service
08-26 12:45:43.183  3850  3850 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 12:45:43.184  3850  3850 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 12:45:43.184  3850  3850 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 12:45:43.184  3850  3850 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:43.184  3850  3850 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 12:45:43.184  3850  3850 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 12:45:43.190  3850  3850 V BluetoothFtpService: Ftp Service onDestroy
,08-26 12:45:43.190  3850  3850 V BluetoothFtpService: Ftp Service closeService
08-26 12:45:43.269  1036  1561 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6840 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 12:45:43.270  3850  3850 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:43.271  3850  3850 V BluetoothSapService: state: 13
08-26 12:45:43.271  3850  3850 V BluetoothSapService: Stopping SAP server process
,08-26 12:45:43.274  3850  3850 V BluetoothSapService: Sap Service closeSapService in
08-26 12:45:43.274  3850  3850 V BluetoothSapService: Close listen Socket : 
08-26 12:45:43.275  3850  3850 V BluetoothSapService: Close rfcomm Socket : 
08-26 12:45:43.275  3850  3850 V BluetoothSapService: Close sapd  Socket : 
08-26 12:45:43.289  3850  3850 V BluetoothSapService: Sap Service closeSapService out
08-26 12:45:43.289  3850  3850 V BluetoothSapService: Sap Service onDestroy
08-26 12:45:43.290  3850  3850 V BluetoothSapService: Sap Service closeSapService in
08-26 12:45:43.290  3850  3850 V BluetoothSapService: Close listen Socket : 
08-26 12:45:43.290  3850  3850 V BluetoothSapService: Close rfcomm Socket : 
08-26 12:45:43.290  3850  3850 V BluetoothSapService: Close sapd  Socket : 
08-26 12:45:43.290  3850  3850 V BluetoothSapService: Sap Service closeSapService out
,08-26 12:45:43.292   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 469us total 25.649ms
08-26 12:45:43.311  6820  6820 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 12:45:43.316   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 21.131ms
,08-26 12:45:43.336  6840  6840 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 12:45:43.339   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 21.219ms
08-26 12:45:43.346  6820  6820 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-26 12:45:43.352  1036  1058 I ActivityManager: Killing 5969:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-26 12:45:43.377  6820  6820 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 12:45:43.378  6820  6820 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-26 12:45:43.378  6820  6820 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 12:45:43.378  6820  6820 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 12:45:43.379  6820  6820 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 12:45:43.380  6820  6820 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 12:45:43.385  6820  6820 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 12:45:43.405  1036  1561 W libprocessgroup: failed to open /acct/uid_10011/pid_5969/cgroup.procs: No such file or directory
,08-26 12:45:43.423  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 12:45:43.430  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:43.455  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 12:45:43.458  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:43.462  6820  6820 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 12:45:43.463  6791  6791 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 12:45:43.463  6791  6791 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 12:45:43.463  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:45:43.467  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:43.469  6820  6820 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 12:45:43.474  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:43.484  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:43.485  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 12:45:43.487  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 12:45:43.495  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:43.499  6791  6791 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 12:45:43.499  6791  6791 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 12:45:43.499  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 12:45:43.504  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 12:45:43.513  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:43.516  3850  4035 W bt-btif : ag scb idx 1 not allocated
08-26 12:45:43.516  3850  4035 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 12:45:43.516  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:43.516  3850  4035 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:43.516  3850  3933 D bt_hci_bdroid: cleanup
08-26 12:45:43.516  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:43.517  3850  4035 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 12:45:43.517  3850  4035 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 12:45:43.517  3850  4038 I bt_lpm  : LPM is already off!!!
08-26 12:45:43.517  3850  4190 I bt_userial_mct: exiting userial_read_thread
08-26 12:45:43.517  3850  4190 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 12:45:43.518  3850  3933 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 12:45:43.518  3850  4038 I bt_vendor: hw_epilog_process
08-26 12:45:43.519  3850  3933 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 12:45:43.519  3850  3933 D bt_userial_mct: userial_close
08-26 12:45:43.519  3850  3933 E bt_userial_mct: pthread_join() FAILED result:3
08-26 12:45:43.519  3850  3933 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 12:45:43.521  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:43.522  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:43.525  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 12:45:43.543  4447  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 12:45:43.587  1036  2021 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6865 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 12:45:43.671  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 12:45:43.679  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 12:45:43.690  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:43.695  3850  3933 D bt_hci_bdroid: set_power 0
08-26 12:45:43.695  3850  3933 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 12:45:43.695  3850  3933 I bt_vendor: bluetooth satus is on
08-26 12:45:43.695  3850  3933 I bt_vendor: bt-vendor : resetting BT status
08-26 12:45:43.695  3850  3933 I bt_vendor: Starting hciattach daemon
08-26 12:45:43.695  3850  3933 I bt_vendor: try to set false
08-26 12:45:43.695  3850  3933 I bt_vendor: Starting hciattach daemon
08-26 12:45:43.695  3850  3933 I bt_vendor: try to set false
08-26 12:45:43.696  3850  3933 I bt_vendor: cleanup
08-26 12:45:43.696  3850  4035 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 12:45:43.697  3850  3933 I GKI_LINUX: GKI_exit_task 0 done
08-26 12:45:43.697  3850  3933 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 12:45:43.698  3850  3926 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 12:45:43.699  3850  3850 D HeadsetService: Received stop request...Stopping profile...
08-26 12:45:43.700  3850  3850 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 12:45:43.700  3850  3850 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 12:45:43.700  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a207aca
08-26 12:45:43.701  3850  3958 D HeadsetStateMachine: Exit Disconnected: -1
08-26 12:45:43.702  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:43.703  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 12:45:43.703  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:43.703  1841  1841 D BluetoothHeadset: Proxy object disconnected
,08-26 12:45:43.706  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:43.707  3850  3850 D A2dpService: Received stop request...Stopping profile...
08-26 12:45:43.707  3850  4000 D A2dpStateMachine: Exit Disconnected: -1
08-26 12:45:43.707  3850  3850 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 12:45:43.712  3850  3850 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 12:45:43.712  3850  3850 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 12:45:43.712  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a207aca
08-26 12:45:43.713  3850  3926 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 12:45:43.714  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-26 12:45:43.714  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 12:45:43.714  6865  6887 W FormManager: Network not available. Please check & try again.
,08-26 12:45:43.714  3850  3850 D HidService: Received stop request...Stopping profile...
08-26 12:45:43.714  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a207aca
08-26 12:45:43.716  3850  3850 D HeadsetStateMachine: Unbinding service...
08-26 12:45:43.718  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 12:45:43.718  3850  3850 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 12:45:43.718  3850  3850 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 12:45:43.718  3850  3850 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 12:45:43.718  3850  3850 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 12:45:43.718  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 12:45:43.718  3850  3850 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 12:45:43.718  3850  3850 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 12:45:43.718  3850  3850 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 12:45:43.719  3850  3850 D HealthService: Received stop request...Stopping profile...
08-26 12:45:43.719  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a207aca
08-26 12:45:43.719  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 12:45:43.719  6770  6770 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 12:45:43.720  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 12:45:43.720  3850  3850 D PanService: Received stop request...Stopping profile...
08-26 12:45:43.721  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a207aca
08-26 12:45:43.722  3850  3850 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 12:45:43.722  3850  3850 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 12:45:43.722  3850  3850 D BtGatt.GattService: stop()
08-26 12:45:43.723  3850  3850 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 12:45:43.723  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a207aca
08-26 12:45:43.725  3850  3850 D BluetoothMapService: Received stop request...Stopping profile...
08-26 12:45:43.725  3850  3850 D BluetoothMapService: stop()
08-26 12:45:43.726  3850  3850 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 12:45:43.726  3850  3850 D BluetoothMapEmailAppObserver: removeReceiver()
,08-26 12:45:43.728  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a207aca
08-26 12:45:43.729  3850  3850 I BluetoothA2dpServiceJni: cleanupNative
08-26 12:45:43.729  3850  4001 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 12:45:43.729  3850  3850 I GKI_LINUX: GKI_exit_task 2 done
08-26 12:45:43.729  3850  3850 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 12:45:43.730  3850  3850 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 12:45:43.730  3850  3850 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 12:45:43.730  3850  3850 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 12:45:43.730  3850  3850 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 12:45:43.730  3850  3850 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 12:45:43.730  3850  3850 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 12:45:43.730  3850  3850 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 12:45:43.732  3850  3850 V BluetoothMapService: Handler(): got msg=4
08-26 12:45:43.732  3850  3850 D BluetoothMapService: MAP Service closeService in
08-26 12:45:43.732  3850  3850 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 12:45:43.732  3850  3850 V BluetoothMapService: MAP Service closeService out
08-26 12:45:43.732  3850  3850 D BluetoothMapService: cleanup()
08-26 12:45:43.733  3850  3850 D BluetoothMapService: MAP Service closeService in
08-26 12:45:43.733  3850  3850 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 12:45:43.733  3850  3850 V BluetoothMapService: MAP Service closeService out
08-26 12:45:43.733  3850  3926 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 12:45:43.733  3850  3926 D BluetoothAdapterProperties: Setting state to 10
08-26 12:45:43.733  3850  3926 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 12:45:43.734  1036  1118 D BluetoothManagerService: Message: 60
08-26 12:45:43.734  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 12:45:43.734  3850  3926 I BluetoothAdapterState: Entering OffState
08-26 12:45:43.734  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 12:45:43.734  6865  6889 V FormManager: Network unavailable.
08-26 12:45:43.734  1841  2428 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:43.735  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:43.735  6770  6786 D BluetoothPan: onBluetoothStateChange on: false
08-26 12:45:43.736  6770  6787 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 12:45:43.736  6770  6786 D BluetoothMap: onBluetoothStateChange: up=false
08-26 12:45:43.736  6865  6889 V FormManager: Network unavailable.
08-26 12:45:43.737  1841  4382 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:43.737  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 12:45:43.738  6770  6787 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 12:45:43.738  1841  1857 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:43.739  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 12:45:43.739  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 12:45:43.741  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 12:45:43.741  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 12:45:43.742  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@351033b2 mBinding = false
08-26 12:45:43.742  1036  1118 D BluetoothManagerService: Sending unbind request.
08-26 12:45:43.745  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 12:45:43.747  6770  6770 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 12:45:43.747  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 12:45:43.747  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 12:45:43.747  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 12:45:43.748  6770  6770 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 12:45:43.748  6770  6770 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 12:45:43.751  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 12:45:43.751  3850  3933 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 12:45:43.751  3850  3850 I GKI_LINUX: GKI_exit_task 1 done
08-26 12:45:43.751  3850  3850 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 12:45:43.752  3850  3850 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 12:45:43.752  3850  3850 I art     : --- WEIRD: removing null entry 246
08-26 12:45:43.752  3850  3850 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 12:45:43.752  3850  3850 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 12:45:43.752  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.753  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 12:45:43.755  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:43.755  1928  2091 D LGBluetoothAPIService: Message: 2
08-26 12:45:43.755  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:43.755  1928  2091 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3ba25545 mBinding = false
08-26 12:45:43.755  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:43.755  1928  2091 D LGBluetoothAPIService: Sending unbind request.
08-26 12:45:43.755  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 12:45:43.759  6770  6770 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 12:45:43.760  6770  6770 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 12:45:43.760  6770  6770 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 12:45:43.763  3850  3850 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 12:45:43.766  3850  3850 I art     : System.exit called, status: 0
,08-26 12:45:43.766  3850  3850 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 12:45:43.770  6770  6770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 12:45:43.771  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:43.787   325  1370 V AudioFlinger: 3850 died, releasing its sessions
08-26 12:45:43.787   325  1370 V AudioFlinger:  pid 1841 @ 0
08-26 12:45:43.787   325  1370 V AudioFlinger:  pid 3421 @ 1
08-26 12:45:43.787   325  1370 V AudioFlinger:  pid 3421 @ 2
08-26 12:45:43.788  1588  1588 D BluetoothAdapter: 648204653: getState() :  mService = null. Returning STATE_OFF
08-26 12:45:43.788  1588  1588 D BluetoothAdapter: 648204653: getState() :  mService = null. Returning STATE_OFF
,08-26 12:45:43.790  6770  6770 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:45:43.791  6770  6770 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 12:45:43.792  4285  6897 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 12:45:43.796  4285  6901 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 12:45:43.797  4285  6901 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 12:45:43.883  1036  1561 I ActivityManager: Process com.android.bluetooth (pid 3850) has died
08-26 12:45:43.884  1036  1561 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-26 12:45:43.901  6791  6791 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 12:45:43.903  6791  6791 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 12:45:43.903  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 12:45:43.908  2152  2152 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:45:43.918  6865  6902 W FormManager: Network not available. Please check & try again.
,08-26 12:45:43.925  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 12:45:43.926  6865  6903 V FormManager: Network unavailable.
,08-26 12:45:43.939  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 12:45:43.945  6865  6903 V FormManager: Network unavailable.
08-26 12:45:43.950  6770  6770 D BluetoothPermissionRequest: onReceive
,08-26 12:45:43.955  6770  6770 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 12:45:43.956  6770  6770 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 12:45:43.960  6770  6770 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 12:45:44.016  1036  1969 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6905 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-26 12:45:44.020  1036  1969 I ActivityManager: Killing 5991:com.android.contacts/u0a19 (adj 15): empty #17
08-26 12:45:44.114  1036  2002 W libprocessgroup: failed to open /acct/uid_10019/pid_5991/cgroup.procs: No such file or directory
,08-26 12:45:44.159  6820  6820 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-26 12:45:44.160  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 12:45:44.161  6820  6820 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 12:45:44.168  6905  6905 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 12:45:44.169  6905  6905 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 12:45:44.169  6905  6905 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 12:45:44.170  6905  6905 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 12:45:44.190  6905  6905 D BluetoothAdapterApp: Loading JNI Library
,08-26 12:45:44.201  6820  6820 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:45:44.201  6820  6820 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 12:45:44.208  6820  6820 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 12:45:44.209  6820  6820 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 12:45:44.209  6820  6820 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 12:45:44.209  6820  6820 V SoundPool: doLoad: loading sample sampleID=1
08-26 12:45:44.210  6820  6820 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 12:45:44.214  6653  6653 D UEI.SmartControl: QS Service created
08-26 12:45:44.224  6820  6820 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 12:45:44.225  6820  6930 V SoundPool: Start decode
08-26 12:45:44.225  6820  6930 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 12:45:44.228   325  1371 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 12:45:44.228   325  1371 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 12:45:44.228   325  1371 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 12:45:44.228   325  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 12:45:44.228   325  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 12:45:44.228   325  1371 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 12:45:44.228   325  1371 V MediaPlayerService: player type = 3
08-26 12:45:44.228   325  1371 V AwesomePlayer: AwesomePlayer create()
08-26 12:45:44.228   325  1371 V AwesomePlayer: reset_l() 
08-26 12:45:44.228   325  1371 V AwesomePlayer: cancelPlayerEvents
08-26 12:45:44.228   325  1371 V AwesomePlayer: setAudioSink() 
08-26 12:45:44.228   325  1371 V AwesomePlayer: reset_l() 
08-26 12:45:44.228   325  1371 V AudioCache: notify(0xb5474540, 8, 0, 0)
08-26 12:45:44.228   325  1371 V AudioCache: ignored
08-26 12:45:44.229   325  1371 V AwesomePlayer: cancelPlayerEvents
08-26 12:45:44.229   325  1371 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 12:45:44.229   325  1371 V AwesomePlayer: setDataSource_l dataSource
08-26 12:45:44.229   325  1371 V LGParserOSAL: SniffLGParser start
08-26 12:45:44.229   325  1371 V LGParserOSAL: MainType:5, SubType=0
08-26 12:45:44.229   325  1371 V LGParserOSAL: #### check Mime : application/ogg
08-26 12:45:44.229   325  1371 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 12:45:44.229   325  1371 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 12:45:44.232  6905  6905 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2ce5fc3 Instance Count = 1
08-26 12:45:44.237  6905  6905 D BluetoothAdapterApp: onCreate
,08-26 12:45:44.244  6820  6820 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 12:45:44.244  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 12:45:44.259  6653  6653 I UEI.SmartControl: Service initServices...
08-26 12:45:44.260  6653  6653 D UEI.SmartControl: QS start get config
08-26 12:45:44.264  6820  6820 V LGMDMManager: Create singleton instance
,08-26 12:45:44.300  6905  6905 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 12:45:44.300  6905  6905 D ProfileConfigQcom: Adding HeadsetService
08-26 12:45:44.300  6905  6905 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 12:45:44.300  6905  6905 D ProfileConfigQcom: Adding A2dpService
08-26 12:45:44.301  6905  6905 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 12:45:44.301  6905  6905 D ProfileConfigQcom: Adding HidService
08-26 12:45:44.301  6905  6905 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 12:45:44.301  6905  6905 D ProfileConfigQcom: Adding HealthService
08-26 12:45:44.302  6905  6905 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-26 12:45:44.303  6905  6905 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 12:45:44.303  6905  6905 D ProfileConfigQcom: Adding PanService
08-26 12:45:44.303  6905  6905 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 12:45:44.303  6905  6905 D ProfileConfigQcom: Adding GattService
08-26 12:45:44.304  6905  6905 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 12:45:44.304  6905  6905 D ProfileConfigQcom: Adding BluetoothMapService
08-26 12:45:44.305  6905  6905 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 12:45:44.307  6905  6905 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 12:45:44.309   325  1371 V LGParserOSAL: supported mime: application/ogg
08-26 12:45:44.309   325  1371 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 12:45:44.309   325  1371 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 12:45:44.309   325  1371 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 12:45:44.310   325  1371 V AwesomePlayer: AudioTrack Setting
08-26 12:45:44.310   325  1371 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 12:45:44.310   325  1371 V AwesomePlayer: setAudioSource() 
08-26 12:45:44.310   325  1371 V MediaPlayerService: prepare
08-26 12:45:44.310   325  1371 V AwesomePlayer: prepareAsync_l() 
08-26 12:45:44.310   325  1371 V MediaPlayerService: wait for prepare
08-26 12:45:44.314   325  6941 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 12:45:44.314   325  6941 V AwesomePlayer: initAudioDecoder() 
08-26 12:45:44.314   325  6941 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 12:45:44.314   325  6941 V AudioSystem: isOffloadSupported()
08-26 12:45:44.314   325  6941 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 12:45:44.314   325  6941 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 12:45:44.314   325  6941 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 12:45:44.314   325  6941 V AwesomePlayer: getUseOffload() = 0 
08-26 12:45:44.314   325  6941 V OMXCodec: OMXCodec::Create
08-26 12:45:44.315   325  6941 V OMXCodec: findMatchingCodecs()
08-26 12:45:44.315   325  6941 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 12:45:44.315   325  6941 V OMXCodec: matchingCodecs.size()=1
08-26 12:45:44.315   325  6941 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 12:45:44.318  6770  6770 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-26 12:45:44.320  6905  6905 V LGMDMManagerInternal: Create singleton instance
08-26 12:45:44.323   325  6941 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 12:45:44.323   325  6941 V LGCodecAdapter: LG Codec Adapter start
08-26 12:45:44.323   325  6941 V OMXCodec: OMXCodec Createtor
08-26 12:45:44.323   325  6941 V OMXCodec: setComponentRole
08-26 12:45:44.323   325  6941 V OMXCodec: configureCodec protected=0
08-26 12:45:44.323   325  6941 V LGCodecAdapter: called getLGCodecSpecificData
08-26 12:45:44.323   325  6941 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 12:45:44.323   325  6941 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 12:45:44.323   325  6941 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 12:45:44.323   325  6941 V LGCodecOSAL: Not support LGCodec
08-26 12:45:44.323   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 12:45:44.324   325  6941 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 12:45:44.324   325  6941 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 12:45:44.324   325  6941 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 12:45:44.324   325  6941 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 12:45:44.324   325  6941 V AudioSystem: isOffloadSupported()
08-26 12:45:44.324   325  6941 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 12:45:44.324   325  6941 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 12:45:44.324   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 12:45:44.324   325  6941 V OMXCodec: init()
08-26 12:45:44.324   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 12:45:44.324   325  6941 V OMXCodec: allocateBuffers
08-26 12:45:44.324   325  6941 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 12:45:44.324   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 12:45:44.324   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-26 12:45:44.324   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-26 12:45:44.324   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-26 12:45:44.324   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-26 12:45:44.324   325  6941 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 12:45:44.324   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 12:45:44.325   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-26 12:45:44.325   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-26 12:45:44.325   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-26 12:45:44.325   325  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fe290 on output port
08-26 12:45:44.325   325  6941 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 12:45:44.325   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 12:45:44.325   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 12:45:44.325   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 12:45:44.325   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 12:45:44.325   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 12:45:44.325,   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 12:45:44.333   325  6941 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 12:45:44.333   325  6941 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 12:45:44.333   325  6941 V AudioCache: notify(0xb5474540, 5, 0, 0)
08-26 12:45:44.333   325  6941 V AudioCache: ignored
08-26 12:45:44.333   325  6941 V AudioCache: notify(0xb5474540, 1, 0, 0)
08-26 12:45:44.333   325  6941 V AudioCache: prepared
08-26 12:45:44.333   325  1371 V AudioCache: wait - success
08-26 12:45:44.333   325  1371 V MediaPlayerService: start
08-26 12:45:44.333   325  1371 V AwesomePlayer: play_l() 
08-26 12:45:44.333   325  1371 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 12:45:44.333   325  1371 V AwesomePlayer: createAudioPlayer_l
08-26 12:45:44.333   325  1371 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 12:45:44.333   325  1371 V AwesomePlayer: startAudioPlayer_l() 
08-26 12:45:44.333   325  1371 D AudioPlayer: start of Playback, useOffload 0
08-26 12:45:44.333   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 12:45:44.334   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045057168,
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,08-26 12:45:44.336   325  6944 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 12:45:44.336   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 12:45:44.337   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-26 12:45:44.337   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-26 12:45:44.337   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-26 12:45:44.337   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-26 12:45:44.337   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 12:45:44.337   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 12:45:44.338   325  1371 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 12:45:44.338   325  1371 V AudioCache: notify(0xb5474540, 6, 0, 0)
08-26 12:45:44.338   325  1371 V AudioCache: ignored
08-26 12:45:44.338   325  1371 V MediaPlayerService: wait for playback complete
08-26 12:45:44.339   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.339   325  6945 V AudioCache: memcpy(0xac300000, 0xb16f8000, 4096)
08-26 12:45:44.340   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.340   325  6945 V AudioCache: memcpy(0xac301000, 0xb16f8000, 4096)
08-26 12:45:44.340   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.340   325  6945 V AudioCache: memcpy(0xac302000, 0xb16f8000, 4096)
08-26 12:45:44.342   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.342   325  6945 V AudioCache: memcpy(0xac303000, 0xb16f8000, 4096)
08-26 12:45:44.342   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.342   325  6945 V AudioCache: memcpy(0xac304000, 0xb16f8000, 4096)
08-26 12:45:44.342   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.342   325  6945 V AudioCache: memcpy(0xac305000, 0xb16f8000, 4096)
08-26 12:45:44.342   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.342   325  6945 V AudioCache: memcpy(0xac306000, 0xb16f8000, 4096)
08-26 12:45:44.344   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.344   325  6945 V AudioCache: memcpy(0xac307000, 0xb16f8000, 4096)
08-26 12:45:44.344   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.344   325  6945 V AudioCache: memcpy(0xac308000, 0xb16f8000, 4096)
08-26 12:45:44.344   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.344   325  6945 V AudioCache: memcpy(0xac309000, 0xb16f8000, 4096)
08-26 12:45:44.344   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.344   325  6945 V AudioCache: memcpy(0xac30a000, 0xb16f8000, 4096)
08-26 12:45:44.345   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.345   325  6945 V AudioCache: memcpy(0xac30b000, 0xb16f8000, 4096)
,08-26 12:45:44.353   325  6945 V AudioCache: write(0xb16f8000, 4096)
,08-26 12:45:44.353   325  6945 V AudioCache: memcpy(0xac30c000, 0xb16f8000, 4096)
08-26 12:45:44.354   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.354   325  6945 V AudioCache: memcpy(0xac30d000, 0xb16f8000, 4096)
08-26 12:45:44.354   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.354   325  6945 V AudioCache: memcpy(0xac30e000, 0xb16f8000, 4096)
08-26 12:45:44.355   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.355   325  6945 V AudioCache: memcpy(0xac30f000, 0xb16f8000, 4096)
08-26 12:45:44.355   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.355   325  6945 V AudioCache: memcpy(0xac310000, 0xb16f8000, 4096)
08-26 12:45:44.356   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.356   325  6945 V AudioCache: memcpy(0xac311000, 0xb16f8000, 4096)
08-26 12:45:44.357   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.357   325  6945 V AudioCache: memcpy(0xac312000, 0xb16f8000, 4096)
08-26 12:45:44.357   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.357   325  6945 V AudioCache: memcpy(0xac313000, 0xb16f8000, 4096)
08-26 12:45:44.358   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.358   325  6945 V AudioCache: memcpy(0xac314000, 0xb16f8000, 4096)
08-26 12:45:44.358   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.358   325  6945 V AudioCache: memcpy(0xac315000, 0xb16f8000, 4096)
08-26 12:45:44.359   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.359   325  6945 V AudioCache: memcpy(0xac316000, 0xb16f8000, 4096)
08-26 12:45:44.359   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.359   325  6945 V AudioCache: memcpy(0xac317000, 0xb16f8000, 4096)
08-26 12:45:44.360   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.360   325  6945 V AudioCache: memcpy(0xac318000, 0xb16f8000, 4096)
08-26 12:45:44.360   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.360   325  6945 V AudioCache: memcpy(0xac319000, 0xb16f8000, 4096)
08-26 12:45:44.361   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.361   325  6945 V AudioCache: memcpy(0xac31a000, 0xb16f8000, 4096)
08-26 12:45:44.361  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 12:45:44.362   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.362   325  6945 V AudioCache: memcpy(0xac31b000, 0xb16f8000, 4096)
08-26 12:45:44.362   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.362   325  6945 V AudioCache: memcpy(0xac31c000, 0xb16f8000, 4096)
08-26 12:45:44.362  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 12:45:44.363   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.363   325  6945 V AudioCache: memcpy(0xac31d000, 0xb16f8000, 4096)
08-26 12:45:44.364   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.364   325  6945 V AudioCache: memcpy(0xac31e000, 0xb16f8000, 4096)
08-26 12:45:44.364   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.364   325  6945 V AudioCache: memcpy(0xac31f000, 0xb16f8000, 4096)
08-26 12:45:44.364  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1529
08-26 12:45:44.365   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.365   325  6945 V AudioCache: memcpy(0xac320000, 0xb16f8000, 4096)
08-26 12:45:44.365   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.365   325  6945 V AudioCache: memcpy(0xac321000, 0xb16f8000, 4096)
08-26 12:45:44.366   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.366   325  6945 V AudioCache: memcpy(0xac322000, 0xb16f8000, 4096)
08-26 12:45:44.366   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.366   325  6945 V AudioCache: memcpy(0xac323000, 0xb16f8000, 4096)
08-26 12:45:44.367   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.367   325  6945 V AudioCache: memcpy(0xac324000, 0xb16f8000, 4096)
08-26 12:45:44.367   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.367   325  6945 V AudioCache: memcpy(0xac325000, 0xb16f8000, 4096)
08-26 12:45:44.368   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.368   325  6945 V AudioCache: memcpy(0xac326000, 0xb16f8000, 4096)
08-26 12:45:44.368   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.368   325  6945 V AudioCache: memcpy(0xac327000, 0xb16f8000, 4096)
08-26 12:45:44.369   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.369   325  6945 V AudioCache: memcpy(0xac328000, 0xb16f8000, 4096)
08-26 12:45:44.369   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.369   325  6945 V AudioCache: memcpy(0xac329000, 0xb16f8000, 4096)
08-26 12:45:44.370   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.370   325  6945 V AudioCache: memcpy(0xac32a000, 0xb16f8000, 4096)
08-26 12:45:44.370   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.370   325  6945 V AudioCache: memcpy(0xac32b000, 0xb16f8000, 4096)
08-26 12:45:44.371   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.371   325  6945 V AudioCache: memcpy(0xac32c000, 0xb16f8000, 4096)
08-26 12:45:44.371   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.371   325  6945 V AudioCache: memcpy(0xac32d000, 0xb16f8000, 4096)
08-26 12:45:44.371   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.371   325  6945 V AudioCache: memcpy(0xac32e000, 0xb16f8000, 4096)
08-26 12:45:44.372   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 12:45:44.372   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.372   325  6945 V AudioCache: memcpy(0xac32f000, 0xb16f8000, 4096)
08-26 12:45:44.372   325  6945 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 12:45:44.372   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.372   325  6945 V AudioCache: memcpy(0xac330000, 0xb16f8000, 4096)
08-26 12:45:44.372   325  6945 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 12:45:44.372   325  6945 V AudioCache: write(0xb16f8000, 4096)
08-26 12:45:44.372   325  6945 V AudioCache: memcpy(0xac331000, 0xb16f8000, 4096)
08-26 12:45:44.372   325  6945 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 12:45:44.372   325  6945 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 12:45:44.372   325  6945 V AwesomePlayer: postAudioEOS() 
08-26 12:45:44.372   325  6945 V AudioCache: write(0xb16f8000, 280)
08-26 12:45:44.372   325  6945 V AudioCache: memcpy(0xac332000, 0xb16f8000, 280)
08-26 12:45:44.374   325  6941 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 12:45:44.374   325  6941 V AwesomePlayer: onStreamDone
08-26 12:45:44.374   325  6941 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 12:45:44.374   325  6941 V AudioCache: notify(0xb5474540, 2, 0, 0)
08-26 12:45:44.374   325  6941 V AudioCache: playback complete
08-26 12:45:44.374   325  6941 V AwesomePlayer: pause_l() 
08-26 12:45:44.374   325  6941 V AudioCache: notify(0xb5474540, 7, 0, 0)
08-26 12:45:44.374   325  1371 V AudioCache: wait - success
08-26 12:45:44.374   325  6941 V AudioCache: ignored
08-26 12:45:44.374   325  6941 V AwesomePlayer: cancelPlayerEvents
08-26 12:45:44.374   325  1371 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 12:45:44.374   325  6941 D AudioPlayer: Pause Playback at 1068125
08-26 12:45:44.374   325  1371 V AwesomePlayer: reset_l() 
08-26 12:45:44.374   325  1371 V AudioCache: notify(0xb5474540, 8, 0, 0)
08-26 12:45:44.374   325  1371 V AudioCache: ignored
08-26 12:45:44.374   325  1371 V AwesomePlayer: cancelPlayerEvents
08-26 12:45:44.374   325  1371 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 12:45:44.374   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 12:45:44.374   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 12:45:44.374   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 12:45:44.374   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 12:45:44.374   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 1
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 12:45:44.375   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 12:45:44.375   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 12:45:44.375   325  6944 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 12:45:44.375   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 12:45:44.375   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 12:45:44.375   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 12:45:44.376   325  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 12:45:44.376   325  1371 D AudioPlayer: AudioPlayer releasing audio source
08-26 12:45:44.376   325  1371 D AudioPlayer: AudioPlayer done releasing audio source
08-26 12:45:44.376   325  1371 V AwesomePlayer: reset_l() 
08-26 12:45:44.376   325  1371 V AwesomePlayer: cancelPlayerEvents
08-26 12:45:44.376   325  1371 V AwesomePlayer: ~AwesomePlayer call
08-26 12:45:44.376   325  1371 V AwesomePlayer: reset_l() 
08-26 12:45:44.376   325  1371 V AwesomePlayer: cancelPlayerEvents
08-26 12:45:44.376  6820  6930 V SoundPool: close(31)
08-26 12:45:44.376  6820  6930 V SoundPool: pointer = 0x9fe82000, size = 205080, sampleRate = 48000, numChannels = 2,
08-26 12:45:44.401  6905  6905 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 12:45:44.404  6905  6905 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-26 12:45:44.404  6905  6905 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 12:45:44.404  6905  6905 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 12:45:44.405  6905  6905 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:44.405  6905  6905 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-26 12:45:44.410  6840  6840 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 12:45:44.593  6653  6653 I UEI.SmartControl: Supports setup maps: true
,08-26 12:45:44.596  6653  6653 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 12:45:44.596  6653  6653 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 12:45:44.596  6653  6653 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-26 12:45:44.596  6653  6653 I UEI.SmartControl: ### init IR Blaster...
,08-26 12:45:44.600  6653  6653 D serial_port: Configuring serial port
,08-26 12:45:44.601  6653  6653 E UEI.SmartControl: UEIBLaster setting for 616
,08-26 12:45:44.601  6653  6653 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 12:45:44.601  6653  6653 I UEI.SmartControl: configuring settings for MAXQ616
,08-26 12:45:44.601  6653  6653 I UEI.SmartControl: Get version...
08-26 12:45:44.619  6653  6948 D UEI.SmartControl: serial port data available: 21
,08-26 12:45:44.646  6653  6653 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 12:45:44.646  6653  6653 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 12:45:44.646  6653  6653 I UEI.SmartControl: QS saving settings...
08-26 12:45:44.648  6653  6653 D UEI.SmartControl: IR Blaster version: 25672567
08-26 12:45:44.664  6653  6948 D UEI.SmartControl: serial port data available: 4
08-26 12:45:44.697  6653  6954 I UEI.SmartControl: Device manager: loading config....
,08-26 12:45:44.698  6653  6954 D UEI.SmartControl: ----------- loading internal config...
08-26 12:45:44.699  6653  6653 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 12:45:44.702  6653  6653 E UEI.SmartControl: Services init done
08-26 12:45:44.703  6653  6653 D UEI.SmartControl: QS Service init finished
08-26 12:45:44.705  6653  6653 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 12:45:44.705  6653  6653 D UEI.SmartControl: QS Service version code: 201091
08-26 12:45:44.706  6653  6653 D UEI.SmartControl: Service requested: Control
08-26 12:45:44.717  6653  6954 E UEI.SmartControl: Loading SETTINGS...
,08-26 12:45:44.720  6653  6653 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 12:45:44.724  6820  6820 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 12:45:44.724  6653  6954 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 12:45:44.725  6653  6671 I UEI.SmartControl: ------ IControl API: 11
08-26 12:45:44.725  6653  6671 D UEI.SmartControl: File observer start...
08-26 12:45:44.726  6653  6671 E UEI.SmartControl: IR Port is disabled: false
08-26 12:45:44.726  6653  6671 D UEI.SmartControl: Starting file observer...
08-26 12:45:44.727  6653  6671 I UEI.SmartControl: Registering callback...
08-26 12:45:44.727  6653  6653 D UEI.SmartControl: Internal service binding...
08-26 12:45:44.728  6653  6669 I UEI.SmartControl: ------ IControl API: 19
08-26 12:45:44.729  6653  6669 I UEI.SmartControl: Registering Services Ready callback...
08-26 12:45:44.729  6653  6669 I UEI.SmartControl: Notify client services are ready...
08-26 12:45:44.729  6820  6839 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 12:45:44.730  6820  6928 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 12:45:44.730  6820  6928 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 12:45:44.730  6820  6820 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 12:45:44.731  6820  6820 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-26 12:45:44.731  6653  6671 I UEI.SmartControl: ------ IControl API: 8
08-26 12:45:44.733  6820  6820 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 12:45:44.733  6820  6820 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 12:45:44.734  6820  6820 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 12:45:44.734  6653  6953 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 12:45:44.734  6653  6953 D UEI.SmartControl: -----service ready thread exits
08-26 12:45:44.735  6820  6838 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 12:45:44.736  6820  6928 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 12:45:44.736  6820  6928 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 12:45:44.736  6820  6820 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 12:45:44.737  6820  6820 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 12:45:44.737  6820  6820 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 12:45:44.739  6820  6820 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 12:45:44.741  6820  6820 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-26 12:45:44.742  6820  6820 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 12:45:44.742  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-26 12:45:44.743  6820  6820 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-26 12:45:44.744  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 12:45:44.746  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 12:45:44.747  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 12:45:44.747  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 12:45:44.749  6820  6820 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472208344748]
08-26 12:45:44.750  6820  6820 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 12:45:44.754  1036  1947 I ActivityManager: Killing 6015:com.android.gallery3d/u0a27 (adj 15): empty #17
08-26 12:45:44.773  6820  6959 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 12:45:44.793  1036  1947 I ActivityManager: Killing 6481:com.lge.email/u0a23 (adj 15): empty #18
,08-26 12:45:44.826  1036  1561 W libprocessgroup: failed to open /acct/uid_10027/pid_6015/cgroup.procs: No such file or directory
,08-26 12:45:44.838  1036  2021 W libprocessgroup: failed to open /acct/uid_10023/pid_6481/cgroup.procs: No such file or directory
08-26 12:45:44.839  6820  6820 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-26 12:45:44.841  6820  6820 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 12:45:44.842  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-26 12:45:44.847  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 12:45:44.847  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 12:45:44.848  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 12:45:44.849  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 12:45:44.867  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 12:45:45.567  1036  1946 D WifiServiceImplEx: setWifiEnabled: true pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 12:45:45.569  1036  1946 D WifiService: setWifiEnabled: true pid=6571, uid=10118
,08-26 12:45:45.569  1036  1946 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:45:45.597  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 12:45:45.598  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 12:45:45.598  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-26 12:45:45.601  1036  1524 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-26 12:45:45.601  1036  1524 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-26 12:45:45.604  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-26 12:45:45.604  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 12:45:45.604  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 12:45:45.604  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 12:45:45.604  1036  1524 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-26 12:45:45.604  1036  1524 E WifiHW  : unknown target_country: EU , set to default,
,08-26 12:45:45.604  1036  1524 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
08-26 12:45:45.604  1036  1524 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 12:45:45.604  1036  1524 I WifiUtil: gEnableBmps=1
,08-26 12:45:45.665  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-26 12:45:45.692  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-26 12:45:45.705  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:45.710  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:45.712  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:45.720  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-26 12:45:45.733  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:45.740  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:45.740  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:45.742  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 12:45:45.745  6394  6421 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 12:45:45.759  5727  5727 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 12:45:45.767  5727  5727 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 12:45:45.788  2152  2152 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:45.846  1036  2038 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6964 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-26 12:45:45.878  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:45.880  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:45.880  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 12:45:45.938  6964  6964 I AppUp4:AppBoxCP: onCreate
,08-26 12:45:45.938  6964  6964 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-26 12:45:45.945  6964  6964 I AppUp4:DB:  setFingerPrint start
08-26 12:45:45.945  6964  6964 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 12:45:45.951  6964  6964 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-26 12:45:45.951  6964  6964 I AppUp4:DB:  SDK version = 21
08-26 12:45:45.951  6964  6964 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-26 12:45:45.952  6964  6964 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-26 12:45:45.953  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 12:45:45.953  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:45.956  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 12:45:45.956  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 12:45:45.962  6964  6964 I AppUp4:CustModeStarterReceiver: onReceive
08-26 12:45:45.992  6964  6964 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:45:45.992  6964  6964 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 12:45:45.998  6964  6964 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23f98635
,08-26 12:45:45.998  6964  6964 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-26 12:45:45.998  6964  6964 D AppUp4:CustFacade: isPhone : true
08-26 12:45:45.999  6964  6964 D AppUp4:CustModeStarterReceiver: begin check event
08-26 12:45:45.999  6964  6964 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 12:45:45.999  6964  6964 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-26 12:45:46.000  6964  6996 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 12:45:46.000  6964  6996 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-26 12:45:46.000  6964  6996 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-26 12:45:46.004  1036  1058 I ActivityManager: Killing 6092:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-26 12:45:46.080  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:46.082  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 12:45:46.085  1036  2002 W libprocessgroup: failed to open /acct/uid_10080/pid_6092/cgroup.procs: No such file or directory
,08-26 12:45:46.098  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:46.103  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 12:45:46.116  4285  7006 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 12:45:46.121  4285  7007 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:46.122  4285  7007 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 12:45:46.154  1036  1642 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7008 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 12:45:46.259  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 12:45:46.260  1036  1118 D Tethering: InitialState.processMessage what=4
08-26 12:45:46.262  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 12:45:46.265   320   894 D SoftapController: Softap fwReload - Ok
08-26 12:45:46.267  1036  1524 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (654ms)
08-26 12:45:46.269   320   894 D CommandListener: Setting iface cfg
08-26 12:45:46.270   320   894 D CommandListener: Trying to bring down wlan0
08-26 12:45:46.272   320   894 D CommandListener: Clearing all IP addresses on wlan0
,08-26 12:45:46.276  1036  1524 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 12:45:46.283  7008  7008 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 12:45:46.284  7008  7008 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 12:45:46.275  7026  7026 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:46.275  7026  7026 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:46.285  7008  7008 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 12:45:46.286  7008  7008 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 12:45:46.309  7026  7026 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 12:45:46.340  7026  7026 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 12:45:46.341  7026  7026 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 12:45:46.356  7008  7008 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 12:45:46.368  7008  7008 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 12:45:46.378  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 12:45:46.378  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-26 12:45:46.378  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 12:45:46.378  1036  1524 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 12:45:46.378  1036  1524 D WifiMonitor: connecting to supplicant
08-26 12:45:46.379  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:46.380  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-26 12:45:46.383  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 12:45:46.384  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:46.384  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:46.399  7026  7026 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 12:45:46.403  7008  7008 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 12:45:46.424  7008  7008 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 12:45:46.424  7008  7008 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 12:45:46.482  7026  7026 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 12:45:46.496  7026  7026 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 12:45:46.496  7026  7026 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-26 12:45:46.500  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 12:45:46.501  1036  7032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 12:45:46.501  1036  7032 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 12:45:46.501  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 12:45:46.501  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 12:45:46.501  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 12:45:46.502  1036  7032 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 12:45:46.502  1036  7032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 12:45:46.502  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 12:45:46.503  7008  7008 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 12:45:46.504  1036  1524 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 12:45:46.505  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:46.506  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:46.507  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-26 12:45:46.508  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-26 12:45:46.509  1036  1524 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 12:45:46.509  1036  1524 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 12:45:46.510  1036  1524 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 12:45:46.510  1036  1524 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 12:45:46.510  1036  1524 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 12:45:46.511  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 12:45:46.511  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-26 12:45:46.511  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 12:45:46.511  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:46.511  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:46.511  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:46.511  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:46.511  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 12:45:46.511  1036  1524 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 12:45:46.512  1036  1524 D WifiNative-wlan0: SET update_config 1: returned true
08-26 12:45:46.512  1036  1524 D WifiConfigStore: Loading config and enabling all networks 
08-26 12:45:46.512  1036  1524 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 12:45:46.512  1036  1524 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-26 12:45:46.513  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 12:45:46.513  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:46.513  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:46.513  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,08-26 12:45:46.513  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:45:46.513  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:46.513  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:46.513  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:46.513  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:45:46.514  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:46.514  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:45:46.514  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 12:45:46.514  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3,
08-26 12:45:46.513  1928  1928 D WfdService: Waiting for WifiP2p enabling
,08-26 12:45:46.516  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:46.517  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:45:46.517  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 12:45:46.517  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:46.517  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:46.517  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-26 12:45:46.517  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:46.517  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-26 12:45:46.517  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:46.517  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:46.517  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:46.517  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:46.519  1036  1524 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk,
,08-26 12:45:46.527  7008  7008 I HubEmail: JNI_OnLoad()
08-26 12:45:46.527  7008  7008 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-26 12:45:46.527  7008  7008 I HubEmail: registerNatives()
08-26 12:45:46.527  1036  1524 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 12:45:46.527  7008  7008 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 12:45:46.527  7008  7008 I HubEmail: registerNativeMethods()
08-26 12:45:46.527  7008  7008 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 12:45:46.527  7008  7008 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-26 12:45:46.527  1036  1524 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 12:45:46.528  1036  1524 D WifiStateMachine: enableVerboseLogging : level 2
08-26 12:45:46.528  1036  1524 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 12:45:46.529  1036  1524 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 12:45:46.529  1036  1524 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 12:45:46.529  1036  1524 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 12:45:46.529  1036  1524 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 12:45:46.530  1036  1524 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 12:45:46.530  1036  1524 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 12:45:46.530  1036  1524 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 12:45:46.530  1036  1524 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 12:45:46.531  1036  1524 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 12:45:46.531  1036  1524 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 12:45:46.531  1036  1524 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 12:45:46.531  1036  1524 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 12:45:46.531  1036  1524 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 12:45:46.536  1036  1524 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 12:45:46.536  1036  1524 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 12:45:46.537  1036  1524 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 12:45:46.537  1036  1524 D WifiNative-HAL: Setting external_sim to 1
08-26 12:45:46.537  1036  1524 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 12:45:46.537  1036  1524 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 12:45:46.537  1036  1524 I WifiNative-HAL: startHal
08-26 12:45:46.537  1928  1928 D WfdsService: Supplicant Connection state is changed : true
08-26 12:45:46.537  1036  1524 D wifi    : setting scan oui 0xaf6c9fc0
08-26 12:45:46.538  1928  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 12:45:46.538  1928  2279 D WfdsService: Set the WFDS Monitor: true
,08-26 12:45:46.538  1928  2279 D WfdsMonitor: WfdsMonitorThread create
08-26 12:45:46.538  1928  2279 D WfdsMonitor: WFDS Monitor is created and started
08-26 12:45:46.538  1928  2279 D WfdsService: WiFi: Supplicant connection re-established
08-26 12:45:46.538  1036  1524 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 12:45:46.538  1036  1524 I WifiNative-HAL: startHal
08-26 12:45:46.538  1036  1524 D wifi    : setting scan oui 0xaf6c9fc0
08-26 12:45:46.538  1036  1524 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 12:45:46.539  1928  7038 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 12:45:46.539  1928  7038 E CtrlSupplicant: Succeed to open control connection
,08-26 12:45:46.539  1036  1524 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 12:45:46.539  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 12:45:46.539  1928  7038 E CtrlSupplicant: Succeed to open monitor connection
,08-26 12:45:46.539  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 12:45:46.539  1928  7038 D WfdsMonitor: Supplicant connection established
08-26 12:45:46.540  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 12:45:46.540  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 12:45:46.540  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 12:45:46.540  1928  2279 D WfdsService: Connected to the supplicant for wfds
,08-26 12:45:46.540  7008  7033 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:46.541  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 12:45:46.541  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 12:45:46.541  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 12:45:46.541  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 12:45:46.541  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 12:45:46.541  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 12:45:46.542  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-26 12:45:46.542  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 12:45:46.542  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 12:45:46.542  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 12:45:46.542  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
,08-26 12:45:46.542  7026  7026 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 12:45:46.543  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 12:45:46.543  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 12:45:46.543  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-26 12:45:46.544  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 12:45:46.544  6865  7035 W FormManager: Network not available. Please check & try again.
,08-26 12:45:46.544  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 12:45:46.544  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:46.544  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 12:45:46.545  1036  1524 E WifiNative: : [120,105,425 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 12:45:46.545  1036  1524 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 12:45:46.545  1036  1524 D WifiNative-wlan0: RECONNECT: returned true
08-26 12:45:46.545  1036  1524 D WifiNative-wlan0: doString: [STATUS]
08-26 12:45:46.546  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 12:45:46.546  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 12:45:46.547  1036  1524 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 12:45:46.547  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 12:45:46.548  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-26 12:45:46.548  1036  1523 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.549   320   894 D CommandListener: Setting iface cfg
08-26 12:45:46.549   320   894 D CommandListener: Trying to bring up p2p0
08-26 12:45:46.550  1036  1523 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 12:45:46.550  1036  1523 D LGWifiP2pService: P2pEnablingState
08-26 12:45:46.550  1036  1523 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.550  1036  1523 D LGWifiP2pService: P2p socket connection successful
08-26 12:45:46.550  1036  1523 D LGWifiP2pService: P2pEnabledState
08-26 12:45:46.594  1036  1946 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7039 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 12:45:46.598  1036  1523 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 12:45:46.598  1036  1523 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 12:45:46.599  1036  1523 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 12:45:46.600  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 12:45:46.600  1036  1523 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 12:45:46.601  1036  1523 D WifiNative-p2p0: SET device_name G3: returned true
08-26 12:45:46.601  1036  1523 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 12:45:46.601  1036  1523 D LGWifiP2pService: before postfix = G3
08-26 12:45:46.601  1036  1523 D WifiServerServiceExt: postfix byte check : 2
,08-26 12:45:46.601  1036  1523 D LGWifiP2pService: after postfix = G3
08-26 12:45:46.601  1036  1523 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 12:45:46.601  1036  1524 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 12:45:46.601  1036  1523 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 12:45:46.601  1036  1523 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 12:45:46.602  1036  1523 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 12:45:46.602  1036  1523 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,08-26 12:45:46.602  1036  1524 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 12:45:46.602  1036  1523 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 12:45:46.602  1036  1523 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 12:45:46.602  1036  1523 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 12:45:46.603  1036  1523 D WifiNative-HAL: p2pGetDeviceAddress
08-26 12:45:46.603  1036  1523 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 12:45:46.603  1036  1523 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
,08-26 12:45:46.603  1036  1523 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 12:45:46.604  1036  1523 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 12:45:46.604  1036  1523 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 12:45:46.604  1036  1523 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 12:45:46.604  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 12:45:46.604  1036  1036 D RttService: SCAN_AVAILABLE : 3
,08-26 12:45:46.604  1036  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.604  1036  1542 I WifiNative-HAL: startHal
08-26 12:45:46.605  1036  1523 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 12:45:46.605  1036  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf6c9fc0
08-26 12:45:46.605  1036  1542 D wifi    : failed to get capabilities : -3
08-26 12:45:46.605  1036  1542 E WifiScanningService: could not get scan capabilities
,08-26 12:45:46.605  1036  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.605  1036  1523 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 12:45:46.605  1036  1523 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 12:45:46.606  1036  1524 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,08-26 12:45:46.606  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 12:45:46.606  1928  1928 D WfdsService: WifiP2pState is changed : true
08-26 12:45:46.606  1928  2279 D WfdsService: Receive the WFDS_ENABLE Method
08-26 12:45:46.607  1928  2279 D WfdsService: Set the WFDS Monitor: true
08-26 12:45:46.607  1928  2279 D WfdsService: Connected to the supplicant for wfds
,08-26 12:45:46.607  1928  2279 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 12:45:46.607  1036  1524 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 12:45:46.607  1036  1524 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 12:45:46.608  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 12:45:46.609  1928  1928 D WfdsService: isConnected: false
08-26 12:45:46.610  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
,08-26 12:45:46.612  1036  1524 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 12:45:46.612  1036  1524 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 12:45:46.613  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 12:45:46.613  1928  1928 D WfdsService: Update P2p Interface State: 3
08-26 12:45:46.617  7026  7026 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 12:45:46.617  7026  7026 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 12:45:46.617  1928  2279 D WfdsService: selectPreferredScanChannel [36]
08-26 12:45:46.617  1928  2279 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 12:45:46.618  1036  1524 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 12:45:46.618  1036  1524 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 12:45:46.618  6865  7036 V FormManager: Network unavailable.
08-26 12:45:46.618  1036  1524 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 12:45:46.618  1036  1524 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 12:45:46.619  7026  7026 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 12:45:46.619  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 12:45:46.619  1036  1524 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 12:45:46.620  1036  1523 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 12:45:46.620  1036  1523 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 12:45:46.620  1036  1524 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 12:45:46.620  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 12:45:46.620  1036  1523 D LGWifiP2pService: InactiveState
08-26 12:45:46.620  1036  1523 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.620  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.620  1036  1523 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 12:45:46.621  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 12:45:46.622  6865  7036 V FormManager: Network unavailable.
,08-26 12:45:46.623  7026  7026 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:45:46.624  7026  7026 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 12:45:46.624  7026  7026 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.624  1928  7038 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:45:46.624  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 12:45:46.624  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:45:46.624  1036  7032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:45:46.624  1036  7032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:45:46.624  1036  7032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:45:46.624  1036  7032 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.624  1036  7032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.624  1036  7032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.625  7026  7026 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.625  1036  7032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:45:46.625  1928  7038 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:45:46.625  1036  7032 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.625  1036  7032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.625  1036  7032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.626  1036  1524 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 12:45:46.626  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 12:45:46.626  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 12:45:46.627  1036  1524 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 12:45:46.627  7026  7026 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:45:46.627  1036  1524 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 12:45:46.627  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 12:45:46.628  7026  7026 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 12:45:46.628  7026  7026 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.628  1036  1523 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 12:45:46.628  7026  7026 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: InactiveState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1036  1523 D LG,WifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1928  7038 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 12:45:46.629  1928  7038 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1928  7038 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.629  1036  7032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 12:45:46.629  1036  1523 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.630  1036  7032 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:45:46.630  1036  7032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:45:46.630  1036  1523 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.630  1036  7032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:45:46.630  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.630  1036  7032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:45:46.630  1036  1523 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:46.630  1036  7032 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.630  1036  7032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 12:45:46.630  1036  7032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.630  1036  7032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:45:46.630  1036  7032 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.630  1036  7032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.630  1036  7032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:45:46.630  1036  1036 E WifiServerServiceExt: No p2p device connected
08-26 12:45:46.630  1928  2279 W WfdsService: DefaultState - msg [9441285] is not handled
,08-26 12:45:46.631  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 12:45:46.631  7026  7026 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 12:45:46.631  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 12:45:46.631  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 12:45:46.632  1036  7032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 12:45:46.632  1036  7032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 12:45:46.632  1036  1524 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,08-26 12:45:46.632  1036  1524 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 12:45:46.633  1036  1524 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 12:45:46.633  1036  1524 D WifiNative-wlan0: doBoolean: SCAN
08-26 12:45:46.633  1036  1524 D WifiNative-wlan0: SCAN: returned false
,08-26 12:45:46.635  1036  1933 I ActivityManager: Killing 6522:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-26 12:45:46.636  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120197  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-26 12:45:46.665  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120226  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 12:45:46.666  1036  1524 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:45:46.666  1036  1524 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:45:46.667  1036  1524 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:45:46.667  1036  1524 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:45:46.668  1036  1524 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:45:46.668  1036  1561 W libprocessgroup: failed to open /acct/uid_10061/pid_6522/cgroup.procs: No such file or directory
,08-26 12:45:46.672  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 12:45:46.672  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 12:45:46.672  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:46.672  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:46.672  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 12:45:46.673  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:45:46.673  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 12:45:46.673  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:46.743  7039  7039 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:45:46.744  7039  7039 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 12:45:46.747  7039  7039 D PhoneMonitor: Register our PhoneStateListener
,08-26 12:45:46.766  7039  7039 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 12:45:46.768  7039  7039 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 12:45:46.795  7039  7039 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-26 12:45:46.797  7039  7039 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-26 12:45:46.798  7039  7039 D TelephonyAutoProfiling: [parse] Load xml
08-26 12:45:46.806  7039  7039 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 12:45:46.806  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 12:45:46.806  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
,08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 12:45:46.807  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 12:45:46.808  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 12:45:46.808  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 12:45:46.808  7039  7039 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 12:45:46.808  7039  7039 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-26 12:45:46.819  1036  2038 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7058 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 12:45:46.821  1036  2038 I ActivityManager: Killing 6112:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-26 12:45:46.826  7039  7039 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-26 12:45:46.879  1036  1059 W libprocessgroup: failed to open /acct/uid_10097/pid_6112/cgroup.procs: No such file or directory
,08-26 12:45:47.115  1036  2038 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7079 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-26 12:45:47.117  1036  2038 I ActivityManager: Killing 6588:com.lge.eula/1000 (adj 15): empty #17
,08-26 12:45:47.136  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 12:45:47.136  1036  7032 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 12:45:47.136  7026  7026 E wpa_supplicant: USIM:  scard_init function
08-26 12:45:47.136  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 12:45:47.136  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-26 12:45:47.136  1036  7032 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 12:45:47.136  7026  7026 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-26 12:45:47.138  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 12:45:47.138  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 12:45:47.140  1036  1524 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 12:45:47.141  1036  1524 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 12:45:47.141  1036  1524 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 12:45:47.142  1036  1524 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 12:45:47.142  1036  1524 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 12:45:47.185  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=120746  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 12:45:47.192  1036  1059 W libprocessgroup: failed to open /acct/uid_1000/pid_6588/cgroup.procs: No such file or directory
08-26 12:45:47.197  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 12:45:47.197  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:47.199  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=120760  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 12:45:47.201  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.204  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.204  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.204  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 12:45:47.213  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.213  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.213  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 12:45:47.213  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-26 12:45:47.215  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 12:45:47.222  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:47.222  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:47.226  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:47.261  7026  7026 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 12:45:47.261  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 12:45:47.261  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 12:45:47.261  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 12:45:47.261  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 12:45:47.261  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:45:47.261  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:45:47.262  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=120823  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 12:45:47.263  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=120824  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 12:45:47.263  1036  1524 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120824
,08-26 12:45:47.264  1036  1524 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120825
08-26 12:45:47.264  1036  1524 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120825
08-26 12:45:47.265  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120826
08-26 12:45:47.265  1036  1524 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=120826
08-26 12:45:47.265  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=120826  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 12:45:47.269  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 12:45:47.272  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:47.272  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:47.274  7026  7026 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 12:45:47.274  7026  7026 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 12:45:47.275  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.275  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.275  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-26 12:45:47.276  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=120837  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 12:45:47.277  1036  1524 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:47.278  1036  1524 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:47.278  1036  1524 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:47.279  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:47.279  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:47.279  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.281  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:45:47.281  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:45:47.281  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 12:45:47.282  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 12:45:47.282  1036  7032 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 12:45:47.282  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 12:45:47.282  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 12:45:47.282  1036  7032 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 12:45:47.282  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:45:47.282  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:45:47.283  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.283  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.283  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 12:45:47.284  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:45:47.284  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 12:45:47.284  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=120845  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 12:45:47.284  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=120845  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 12:45:47.287  1036  1524 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120848
,08-26 12:45:47.288  1036  1524 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120849
08-26 12:45:47.288  1036  1524 D WifiNative-wlan0: doString: [STATUS]
08-26 12:45:47.290  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:45:47.290  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:45:47.291  1036  1524 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 12:45:47.293  1036  1524 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 12:45:47.300  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:47.300  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:47.301  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:47.318  1036  1058 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7110 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 12:45:47.319  1036  1058 I ActivityManager: Killing 6617:com.lge.bnr/1000 (adj 15): empty #17
,08-26 12:45:47.355  1036  1933 W libprocessgroup: failed to open /acct/uid_1000/pid_6617/cgroup.procs: No such file or directory
,08-26 12:45:47.366  1036  1524 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-26 12:45:47.367  1036  1524 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 12:45:47.372  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.372  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.372  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 12:45:47.372  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:47.372  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:47.374  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.376  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.376  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.376  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 12:45:47.377  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:47.377  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:47.378  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:47.382  1036  1524 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 12:45:47.382  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 12:45:47.382  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 12:45:47.383  1036  1531 D ConnectivityService: Got NetworkAgent Messenger
08-26 12:45:47.383  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 12:45:47.383  1036  1531 D ConnectivityService: NetworkAgent connected
08-26 12:45:47.383  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 12:45:47.383  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 12:45:47.389  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 12:45:47.389  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 12:45:47.389  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 12:45:47.389  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 12:45:47.389  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 12:45:47.394  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 12:45:47.398   320   894 D CommandListener: Setting iface cfg
08-26 12:45:47.399  7110  7110 I art     : Almond Protected OAT
08-26 12:45:47.402  1036  1524 E WifiStateMachine: Start Dhcp Watchdog 2
08-26 12:45:47.402  1036  7129 D DhcpStateMachine: StoppedState
08-26 12:45:47.402  1036  7129 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.402  1036  7129 D DhcpStateMachine: WaitBeforeStartState
08-26 12:45:47.402  1036  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=120963  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:45:47.403  1036  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=120964  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:45:47.403  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=120964  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:45:47.404  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:45:47.404  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 12:45:47.405  1036  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=120965  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:45:47.405  1036  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=120966  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:45:47.406  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=120967  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:45:47.407  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:75322] from screen [on:0 period:-965435121] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 12:45:47.408  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-965435120] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 12:45:47.408  1036  1524 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-26 12:45:47.412  1036  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 12:45:47.413  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.416  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.417  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.417  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.417  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.418  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.418  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.418  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 12:45:47.419  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
08-26 12:45:47.419  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
08-26 12:45:47.419  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,08-26 12:45:47.420  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 12:45:47.420  1036  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 12:45:47.420  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 12:45:47.420  1036  1524 D WifiNative-wlan0: SET ps 0: returned true
08-26 12:45:47.420  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 12:45:47.421  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 12:45:47.421  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 12:45:47.421  1036  1523 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@377b4a93 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.421  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@377b4a93 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.421  1036  7129 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.422  1036  7129 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 12:45:47.422  1036  1524 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 12:45:47.422  1036  1524 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 12:45:47.422  1036  1524 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 12:45:47.423   320   894 D CommandListener: Setting iface cfg
08-26 12:45:47.423   320   894 D CommandListener: Trying to bring up wlan0
08-26 12:45:47.424  1036  1524 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 12:45:47.425  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:45:47.425  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 12:45:47.425  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:45:47.425  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 12:45:47.426  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.426  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.426  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.427  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.427  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.427  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:47.428  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 12:45:47.429  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 12:45:47.429  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 12:45:47.429  1036  1523 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.429  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.429  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 12:45:47.430  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 12:45:47.430  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 12:45:47.430  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 12:45:47.430  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 12:45:47.431  1036  1524 D WifiNative-wlan0: DRIVER SE,TSUSPENDMODE 1: returned true
08-26 12:45:47.431  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 12:45:47.446  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-26 12:45:47.446  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 12:45:47.447  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 12:45:47.447  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 12:45:47.447  1036  1524 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 12:45:47.448  1036  1531 D ConnectivityService: ignoring duplicate network state non-change
08-26 12:45:47.448  7110  7110 D WeatherApplication: removeAccount
,08-26 12:45:47.449  7110  7110 D WeatherApplication: Account.length = 0
08-26 12:45:47.449  7110  7110 E WeatherApplication: OPERATOR:OPEN
08-26 12:45:47.450  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:47.450  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:47.451  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.453  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.453  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.453  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 12:45:47.457  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.457  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.457  7110  7110 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:47
08-26 12:45:47.457  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 12:45:47.458  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 12:45:47.459  1036  1531 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 12:45:47.462  7110  7110 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 12:45:47.462  7110  7110 D Weather.Utils: 2 : All the weather widget is gone.
08-26 12:45:47.465  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 12:45:47.465  7110  7110 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 12:45:47.467  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.467  7110  7110 D WeatherAncestor: connectivity changed - connection : true
08-26 12:45:47.468  7110  7110 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-26 12:45:47.468  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 12:45:47.469  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.469  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 12:45:47.469  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 12:45:47.472  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:47.472  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 12:45:47.476  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.476  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.477  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:47.477  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 12:45:47.477  1036  1524 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 12:45:47.479  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:47.479  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 12:45:47.479  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.483  1036  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 12:45:47.483  1036  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 12:45:47.483  7110  7110 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 12:45:47.483  7110  7110 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 12:45:47.484  7110  7110 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-26 12:45:47.484  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:47.484  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 12:45:47.484  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.485  1036  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 12:45:47.486   320   894 E Netd    : netlink response contains error (File exists)
08-26 12:45:47.486  1036  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 12:45:47.487  1036  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 12:45:47.487  1036  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 12:45:47.487  1036  1531 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-26 12:45:47.489  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 12:45:47.489  1036  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 12:45:47.489  1036  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 12:45:47.489  1036  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 12:45:47.489  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.489  1036  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:45:47.489  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 12:45:47.489  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:47.489  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.489  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 12:45:47.489  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 12:45:47.489  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:47.489  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 12:45:47.490  1036  1531 D ConnectivityService: currentScore = 0, newScore = 20
08-26 12:45:47.490  1036  1531 D ConnectivityService:    accepting network in place of null
08-26 12:45:47.491  1036  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:47.491  1036  1524 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:47.491  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:45:47.492   320  7134 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 12:45:47.493  1036  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover:, false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 12:45:47.493  1036  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 12:45:47.493  1841  1841 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:47.493  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 12:45:47.493  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 12:45:47.494  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:47.494  1036  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 12:45:47.494  1036  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 12:45:47.495  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 12:45:47.495  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 12:45:47.495  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 12:45:47.495  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-26 12:45:47.501  1036  1522 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 12:45:47.512  1036  1531 D ConnectivityService: validation of new default Network = false
08-26 12:45:47.512  1036  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
,08-26 12:45:47.512  1036  1531 D DSQN    : enableDataServiceNotify 
08-26 12:45:47.512  1036  1531 D DSQN    : start dsqn bin
08-26 12:45:47.513  7110  7110 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 12:45:47.514  7110  7110 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:47
08-26 12:45:47.524  1036  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,08-26 12:45:47.524  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:47.524  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:47.524  1036  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:47.525  1588  1820 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 12:45:47.515  7135  7135 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:47.515  7135  7135 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:47.539  7135  7135 E DSQN    : DSQN ssw
08-26 12:45:47.541  1036  1969 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7137 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 12:45:47.542  1036  1969 I ActivityManager: Killing 2169:com.lge.music/u0a34 (adj 15): empty #17
08-26 12:45:47.555   325  2151 V AudioFlinger: 2169 died, releasing its sessions
08-26 12:45:47.555   325  2151 V AudioFlinger:  pid 1841 @ 0
,08-26 12:45:47.555   325  2151 V AudioFlinger:  pid 3421 @ 1
,08-26 12:45:47.555   325  2151 V AudioFlinger:  pid 3421 @ 2
,08-26 12:45:47.577  1036  1059 W libprocessgroup: failed to open /acct/uid_10034/pid_2169/cgroup.procs: No such file or directory
,08-26 12:45:47.587  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 12:45:47.588  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.588  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:47.605  1805  7156 I CheckinService: active receiver: enabled
,08-26 12:45:47.612  1805  7156 I CheckinService: Preparing to send checkin request
08-26 12:45:47.613  1805  7156 I EventLogService: Accumulating logs since 1472208284560
08-26 12:45:47.623  1036  7129 D DhcpStateMachine: DHCPV4 request on wlan0
,08-26 12:45:47.624  1036  7129 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 12:45:47.624  1036  7129 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 12:45:47.615  7158  7158 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:47.615  7158  7158 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:47.631   320  7134 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-26 12:45:47.639  7158  7158 I dhcpcd  : version 5.5.6 starting
08-26 12:45:47.640  7158  7158 E dhcpcd  : get_duid: m
,08-26 12:45:47.640  7158  7158 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 12:45:47.640  7158  7158 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-26 12:45:47.647   278   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 12:45:47.647   278   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 12:45:47.647   278   331 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 12:45:47.651  7137  7160 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 12:45:47.656   278   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 12:45:47.656   278   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 12:45:47.656   278   331 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 12:45:47.656  7137  7160 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 12:45:47.657  1805  7156 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 12:45:47.668  1036  1523 D LGWifiP2pService: InactiveState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.668  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:47.668  1036  1523 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 12:45:47.670   320  7134 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-26 12:45:47.671   278   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 12:45:47.671   278   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 12:45:47.671   278   331 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 12:45:47.672  7137  7168 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 12:45:47.683   278   331 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 12:45:47.683   278   331 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 12:45:47.683   278   331 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 12:45:47.684  7137  7168 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 12:45:47.692  1036  1524 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 12:45:47.692  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 12:45:47.692  1036  1524 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 12:45:47.692  1036  1524 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 12:45:47.693  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 12:45:47.693  1036  1524 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 12:45:47.695  7158  7158 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 12:45:47.696  7158  7158 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 12:45:47.696  7158  7158 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 12:45:47.696  7158  7158 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 12:45:47.696  7158  7158 D dhcpcd  : wlan0: sending REQUEST (xid 0x5b1c56f1), next in 4.44 seconds
08-26 12:45:47.698   320   893 D LGDataListener: argv[0]=dsqncommand
08-26 12:45:47.698   320   893 D LGDataListener: argv[1]=wlan0
08-26 12:45:47.698   320   893 D LGDataListener: argv[2]=1
08-26 12:45:47.698   320   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 12:45:47.698  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 12:45:47.698  1036  1116 D DSQN    : start to monitor internet connection
,08-26 12:45:47.722  7158  7158 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 12:45:47.733  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 10:45:47 GMT], X-Android-Received-Millis=[1472208347733], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472208347697]}
,08-26 12:45:47.733  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 12:45:47.734  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 12:45:47.734  1036  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 12:45:47.734  1036  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 12:45:47.734  1036  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:45:47.734  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:47.734  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 12:45:47.734  1036  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 12:45:47.734  1036  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 12:45:47.734  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:47.735  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:47.735  1036  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:47.735  1036  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:47.735  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 12:45:47.736  1036  1524 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:47.736  1588  1820 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 12:45:47.736  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:45:47.736  1841  1841 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:47.736  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 12:45:47.739  7158  7158 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 12:45:47.739  1036  1947 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7174 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-26 12:45:47.739  7158  7158 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 12:45:47.739  7158  7158 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 12:45:47.740  7158  7158 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 12:45:47.740  7158  7158 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 12:45:47.741  7158  7158 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 12:45:47.741  7158  7158 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 12:45:47.741  7158  7158 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-26 12:45:47.762  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 12:45:47.763  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:47.764  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:47.806  7174  7174 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 12:45:47.806  7174  7174 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 12:45:47.823  7174  7174 I MultiDex: VM with version 2.1.0 has multidex support
08-26 12:45:47.823  7174  7174 I MultiDex: install
08-26 12:45:47.823  7174  7174 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 12:45:47.829  7174  7174 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-26 12:45:47.873  7137  7137 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 12:45:47.885  7137  7137 I LibraryLoader: Loading: webviewchromium
08-26 12:45:47.886  7137  7137 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1461-1463)
08-26 12:45:47.887  7137  7137 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 12:45:47.890  7137  7137 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d1ce334}
,08-26 12:45:47.891  7137  7137 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 12:45:47.891  7137  7137 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 12:45:47.900  7137  7137 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 12:45:47.901  7137  7137 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 12:45:47.908   325  1770 V AudioPolicyService: registerClient() client 0xb558a940, uid 10093
,08-26 12:45:47.908  7137  7137 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 12:45:47.908  7137  7230 W AudioManagerAndroid: Requires BLUETOOTH permission
08-26 12:45:47.909  7137  7137 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-26 12:45:47.909  7137  7137 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-26 12:45:47.922  7137  7137 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 12:45:47.922  7137  7137 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 12:45:47.922  7137  7137 I Adreno-EGL: Build Date: 12/12/14 금
08-26 12:45:47.922  7137  7137 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 12:45:47.922  7137  7137 I Adreno-EGL: Remote Branch: 
08-26 12:45:47.922  7137  7137 I Adreno-EGL: Local Patches: 
08-26 12:45:47.922  7137  7137 I Adreno-EGL: Reconstruct Branch: 
08-26 12:45:48.004  7137  7137 I NSApplication: Starting up...
,08-26 12:45:48.027  1036  7129 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-26 12:45:48.028  1036  7129 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 12:45:48.029  1036  7129 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 12:45:48.029  1036  7129 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 12:45:48.029  1036  7129 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 12:45:48.029  1036  7129 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 12:45:48.029  1036  7129 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 12:45:48.029  1036  7129 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 12:45:48.029  1036  7129 D DhcpStateMachine: RunningState
08-26 12:45:48.089  1036  1906 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7243 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-26 12:45:48.090  1036  1906 I ActivityManager: Killing 6039:com.android.vending/u0a44 (adj 15): empty #17
,08-26 12:45:48.106   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 19.362ms
,08-26 12:45:48.122   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 14.929ms
,08-26 12:45:48.139   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 16.571ms
,08-26 12:45:48.145  1036  1969 W libprocessgroup: failed to open /acct/uid_10044/pid_6039/cgroup.procs: No such file or directory
,08-26 12:45:48.169  7243  7243 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 12:45:48.185  7260  7260 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 12:45:48.244  7260  7260 I dex2oat : dex2oat took 58.138ms (threads: 4)
08-26 12:45:48.253  7174  7194 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 12:45:48.253  7174  7194 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 12:45:48.253  7174  7194 I Adreno-EGL: Build Date: 12/12/14 금
08-26 12:45:48.253  7174  7194 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 12:45:48.253  7174  7194 I Adreno-EGL: Remote Branch: 
08-26 12:45:48.253  7174  7194 I Adreno-EGL: Local Patches: 
08-26 12:45:48.253  7174  7194 I Adreno-EGL: Reconstruct Branch: 
,08-26 12:45:48.321  7174  7194 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 12:45:48.321  7174  7194 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 12:45:48.321  7174  7194 I Adreno-EGL: Build Date: 12/12/14 금
08-26 12:45:48.321  7174  7194 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 12:45:48.321  7174  7194 I Adreno-EGL: Remote Branch: 
08-26 12:45:48.321  7174  7194 I Adreno-EGL: Local Patches: 
08-26 12:45:48.321  7174  7194 I Adreno-EGL: Reconstruct Branch: 
,08-26 12:45:48.363  1036  1058 I art     : Explicit concurrent mark sweep GC freed 82586(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.177ms total 127.348ms
08-26 12:45:48.364  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 12:45:48.365  6394  6421 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 12:45:48.379  2152  2152 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:48.386   320  7275 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-26 12:45:48.386   320  7275 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-26 12:45:48.387  1036  1910 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-26 12:45:48.388  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.388  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.388  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 12:45:48.388  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.388  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 12:45:48.393  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 12:45:48.393  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:48.394  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-26 12:45:48.394  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 12:45:48.395  6964  6964 I AppUp4:CustModeStarterReceiver: onReceive
08-26 12:45:48.400  6964  6964 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23f98635
08-26 12:45:48.400  6964  6964 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 12:45:48.400  6964  6964 D AppUp4:CustFacade: isPhone : true
08-26 12:45:48.400  6964  6964 D AppUp4:CustModeStarterReceiver: begin check event
08-26 12:45:48.400  6964  6964 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 12:45:48.404  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:48.404  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 12:45:48.406  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:48.408  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 12:45:48.411  2840  2840 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:48.413  2840  2840 V DownloadManager: DownloadService onCreate
08-26 12:45:48.414  7008  7008 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 12:45:48.415  2840  7278 I DownloadManager: in removeSpuriousFiles
08-26 12:45:48.416  2840  7278 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-26 12:45:48.417  4285  7277 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 12:45:48.417  4285  7280 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:48.417  4285  7280 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 12:45:48.419  4285  7277 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-26 12:45:48.419   320  7275 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-26 12:45:48.420  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 10:45:48 GMT], X-Android-Received-Millis=[1472208348420], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472208348390]}
08-26 12:45:48.420  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 12:45:48.420  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 12:45:48.420  1036  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 12:45:48.420  1036  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 12:45:48.420  1036  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:45:48.420  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:48.421  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 12:45:48.421  1036  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 12:45:48.421  1036  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 12:45:48.421  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:48.421  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:48.421  1036  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-26 12:45:48.421  1588  1820 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 12:45:48.423  2840  7278 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@17df4fd0 on behalf of 2840
08-26 12:45:48.424  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-26 12:45:48.424  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-26 12:45:48.424  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-26 12:45:48.424  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-26 12:45:48.424  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-26 12:45:48.424  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-26 12:45:48.425  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-26 12:45:48.425  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-26 12:45:48.425  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-26 12:45:48.425  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-26 12:45:48.425  2840  7278 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-26 12:45:48.425  2840  7278 I DownloadManager: in trimDatabase
08-26 12:45:48.427  2840  7278 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-26 12:45:48.428  2840  7278 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3f468bc9 on behalf of 2840
08-26 12:45:48.429  4285  7277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-26 12:45:48.434  2840  2840 V DownloadManager: DownloadService onStartCommand
,08-26 12:45:48.434  4285  4285 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-26 12:45:48.435  4285  4285 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-26 12:45:48.435  4285  4285 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-26 12:45:48.436  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 12:45:48.436  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:48.437  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 12:45:48.437  2840  7279 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-26 12:45:48.438  7008  7285 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:48.438  4285  4285 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-26 12:45:48.439  2840  7279 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@33b198fc on behalf of 2840
08-26 12:45:48.442  4285  4285 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-26 12:45:48.443  7039  7039 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 12:45:48.443  7039  7039 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 12:45:48.444  2840  7279 V DownloadManager: processing inserted download 1
08-26 12:45:48.446  2840  7279 V DownloadManager: processing inserted download 4
08-26 12:45:48.447  2840  7279 V DownloadManager: processing inserted download 7
,08-26 12:45:48.449   320  7288 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-26 12:45:48.449   320  7288 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-26 12:45:48.450  2840  7279 V DownloadManager: processing inserted download 8
08-26 12:45:48.451  2840  7279 V DownloadManager: processing inserted download 9
08-26 12:45:48.451  2840  7279 V DownloadManager: processing inserted download 10
08-26 12:45:48.452  2840  7279 V DownloadManager: processing inserted download 11
08-26 12:45:48.453  2840  7279 V DownloadManager: processing inserted download 12
08-26 12:45:48.453  2840  7279 V DownloadManager: processing inserted download 13
08-26 12:45:48.454  2840  7279 V DownloadManager: processing inserted download 14
08-26 12:45:48.455  2840  7279 V DownloadManager: processing inserted download 16
08-26 12:45:48.457  7110  7110 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:48
08-26 12:45:48.458  7110  7110 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 12:45:48.458  7110  7110 D Weather.Utils: 2 : All the weather widget is gone.
08-26 12:45:48.458  7110  7110 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 12:45:48.459  7110  7110 D WeatherAncestor: connectivity changed - connection : true
08-26 12:45:48.459  7110  7110 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@77a043b
08-26 12:45:48.459  2840  2840 V DownloadManager: DownloadService onDestroy
08-26 12:45:48.459  7110  7110 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 12:45:48.459  7110  7110 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 12:45:48.459  7110  7110 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 12:45:48.459  7110  7110 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 12:45:48.459  7110  7110 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:48
,08-26 12:45:48.493   320  7288 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
08-26 12:45:48.493  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 12:45:48.493  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 12:45:48.493  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 12:45:48.493  6770  6770 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 12:45:48.495  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 12:45:48.497  6770  6770 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 12:45:48.497  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 12:45:48.497  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 12:45:48.497  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 12:45:48.497  6770  6770 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 12:45:48.497  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 12:45:48.497  6770  6770 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 12:45:48.502  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:45:48.505  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 12:45:48.509  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.519  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 12:45:48.521  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 12:45:48.524  1036  1531 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 12:45:48.525  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.533  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 12:45:48.534  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 12:45:48.535  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 12:45:48.536  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:48.540  7174  7194 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 12:45:48.540  7174  7194 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 12:45:48.540  7174  7194 I Adreno-EGL: Build Date: 12/12/14 금
08-26 12:45:48.540  7174  7194 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 12:45:48.540  7174  7194 I Adreno-EGL: Remote Branch: 
08-26 12:45:48.540  7174  7194 I Adreno-EGL: Local Patches: 
08-26 12:45:48.540  7174  7194 I Adreno-EGL: Reconstruct Branch: 
08-26 12:45:48.541  4285  7294 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 12:45:48.542  4285  7296 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 12:45:48.542  4285  7296 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 12:45:48.542  4285  7294 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-26 12:45:48.554  6865  7284 V FormManager: There are no updated forms. The schedule will be deleted.
,08-26 12:45:48.556  6865  7284 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-26 12:45:48.574  1036  1561 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7297 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 12:45:48.578  4285  7294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-26 12:45:48.585  4285  4285 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-26 12:45:48.585  4285  4285 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-26 12:45:48.585  4285  4285 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-26 12:45:48.586  4285  4285 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-26 12:45:48.594  4285  4285 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-26 12:45:48.603  1036  1946 D WifiServiceImplEx: setWifiEnabled: false pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 12:45:48.603  1036  1946 D WifiService: setWifiEnabled: false pid=6571, uid=10118
08-26 12:45:48.603  1036  1946 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 12:45:48.611  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 12:45:48.611  1036  1524 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 12:45:48.611  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 12:45:48.611  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 12:45:48.611  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 12:45:48.612  1036  1524 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 12:45:48.612  1036  1524 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 12:45:48.613  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 12:45:48.613  1036  1524 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 12:45:48.613  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 12:45:48.613  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 12:45:48.613  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 12:45:48.613  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 12:45:48.617  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 12:45:48.617  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 12:45:48.618  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 12:45:48.618  1036  1523 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.618  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.618  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 12:45:48.618  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 12:45:48.618  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-26 12:45:48.619   320   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 12:45:48.620  1036  7129 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.643  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 12:45:48.643  1036  1531 D ConnectivityService: ignoring duplicate network state non-change
08-26 12:45:48.643  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-26 12:45:48.643  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 12:45:48.644  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:48.644  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:48.644  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 12:45:48.645  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:48.645  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:48.654  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 12:45:48.655  1036  1523 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.655  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.655  1036  1523 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1e43e1db
08-26 12:45:48.655  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-26 12:45:48.656  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:48.657  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:48.657  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:48.657  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 12:45:48.657  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 12:45:48.657  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-26 12:45:48.657  1036  1523 D LGWifiP2pService: P2pDisablingState
08-26 12:45:48.657  1036  1542 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.658  1036  1523 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.658  1036  1523 D LGWifiP2pService: p2p socket connection lost
08-26 12:45:48.658  1036  1523 D LGWifiP2pService: P2pDisabledState
08-26 12:45:48.658  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:48.658  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:48.659  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:48.659  7297  7297 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 12:45:48.659  7297  7297 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-26 12:45:48.659  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:48.659  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:48.660  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:48.660  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:48.660  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:48.660  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:45:48.661  1036  1524 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 12:45:48.661  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 12:45:48.661  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 12:45:48.661  1036  1523 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.661  1036  1523 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.661  7026  7026 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 12:45:48.661  1036  1543 D RttService: EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.661  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 12:45:48.661  1928  1928 D WfdsService: WifiP2pState is changed : false
08-26 12:45:48.661  1928  2279 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 12:45:48.661  1928  2279 D WfdsService: Set the WFDS Monitor: false
08-26 12:45:48.662  1928  2279 D WfdsMonitor: WFDS Monitor is stopped
08-26 12:45:48.662  1928  2279 D WfdsService: STATE : WfdsDisabledState - enter
08-26 12:45:48.662  1928  7038 D CtrlSupplicant: Received on exit socket, terminate
08-26 12:45:48.662  1928  7038 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 12:45:48.662  1928  7038 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 12:45:48.662  1928  7038 D WfdsMonitor: WfdsMonit,orThread is received the interrupt - closing
08-26 12:45:48.662  1928  2282 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 12:45:48.662  1928  2279 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 12:45:48.662  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 12:45:48.662  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 12:45:48.662  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-26 12:45:48.666  7297  7297 V [BNRBootReceiver]: Boot Receiver Return
08-26 12:45:48.669  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 12:45:48.674  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 12:45:48.676  7297  7297 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 12:45:48.676  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:48.676  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:48.678  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:48.678  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.684  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.684  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:48.685  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 12:45:48.686   320   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 12:45:48.686  1036  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 12:45:48.686  1036  1531 D DSQN    : disableDataServiceNotify
08-26 12:45:48.686  1036  1531 D DSQN    : stop dsqn bin
08-26 12:45:48.688  1036  1524 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 12:45:48.689  1036  1524 D WifiNative-p2p0: TERMINATE: returned true
08-26 12:45:48.689  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 12:45:48.689  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-26 12:45:48.689  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 12:45:48.689  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 12:45:48.689  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 12:45:48.691  1036  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 12:45:48.691  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:48.691  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:48.692  1036  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:45:48.692  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 12:45:48.692  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 12:45:48.692  1588  1820 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 12:45:48.692  1036  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 12:45:48.692  1036  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 12:45:48.692  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 12:45:48.692  6770  6770 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 12:45:48.693  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.693  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:45:48.693  1036  7128 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 12:45:48.693  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:48.693  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:48.693  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 12:45:48.694  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:48.694  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 12:45:48.694  1036  1522 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 12:45:48.696  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 12:45:48.696  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:45:48.698  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:48.6,98  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 12:45:48.698  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-26 12:45:48.698  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 12:45:48.698  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 12:45:48.699  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 12:45:48.699  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 12:45:48.699  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 12:45:48.700  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:48.702  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:48.703  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:48.703  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:48.703  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:48.703  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:48.703  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:48.703  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:48.703  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:48.703  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:48.703  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:48.703  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:48.703  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:48.705  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:48.705  1036  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:48.705  1036  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:48.705  1036  1524 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:48.705  1036  1531 D NetworkManagementService: Removing idletimer
08-26 12:45:48.705  1036  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:48.705  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:45:48.706  1036  1522 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 12:45:48.706  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 12:45:48.706  1841  1841 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:45:48.706  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&,CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 12:45:48.707  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 12:45:48.707  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 12:45:48.707  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 12:45:48.708  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:48.708  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:48.708  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:48.708  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:48.708  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:48.708  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:48.708  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:48.708  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:48.708  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:45:48.708  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:48.708  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:48.713  6865  7316 I FormManager: Network unavailable (failed to connect to static-avc.lglime.com/54.230.230.111 (port 80): connect failed: ENETUNREACH (Network is unreachable), URL : http://static-avc.lglime.com/avc/list/FORMMANAGER_lastUpdatedTime.json)
,08-26 12:45:48.721  6865  7316 V FormManager: Network unavailable.
08-26 12:45:48.722  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 12:45:48.723  6865  7316 V FormManager: Network unavailable.
08-26 12:45:48.725  6865  7316 V FormManager: Network unavailable.
,08-26 12:45:48.727  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 12:45:48.728  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:48.728  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:48.729  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.730  6865  7323 W FormManager: Network not available. Please check & try again.
08-26 12:45:48.735  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.735  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:48.737  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 12:45:48.741  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:48.742  6865  7324 V FormManager: Network unavailable.
08-26 12:45:48.745  6865  7324 V FormManager: Network unavailable.
08-26 12:45:48.748  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:48.752  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 12:45:48.753  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:48.753  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.753  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:45:48.756  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.757  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:48.757  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 12:45:48.759  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:48.761  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:48.765  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.766  7174  7194 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:45:48.766  7174  7194 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 12:45:48.768  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.769  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:48.769  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 12:45:48.771  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 12:45:48.774  7026  7026 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 12:45:48.774  7026  7026 I wpa_supplicant: monitor socket send errors count : 1
08-26 12:45:48.774  7026  7026 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-4\x00 that cannot receive messages
08-26 12:45:48.774  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 12:45:48.775  1036  7032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 12:45:48.775  1036  7032 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-26 12:45:48.777  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.781  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.781  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:48.781  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 12:45:48.784  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:48.789  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 12:45:48.789   320  7326 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-26 12:45:48.790  1805  7156 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-26 12:45:48.791  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 12:45:48.796  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.800  1805  7156 I CheckinService: active receiver: disabled
08-26 12:45:48.801  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.801  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:48.801  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 12:45:48.809  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:48.811  7026  7026 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 12:45:48.812  7026  7026 W wpa_supplicant: USIM:  scard_deinit function
08-26 12:45:48.812  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 12:45:48.812  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 12:45:48.812  1036  1118 D Tethering: InitialState.processMessage what=4
08-26 12:45:48.812  1036  7032 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 12:45:48.812  1036  7032 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 12:45:48.812  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:45:48.812  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:45:48.813  1036  1524 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122374
08-26 12:45:48.814  1036  1524 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122375
,08-26 12:45:48.814  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 12:45:48.814  1036  1524 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=122375  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 12:45:48.815  1036  1524 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=122376  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 12:45:48.815  1036  1524 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:48.816  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:45:48.819  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 12:45:48.823  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.825  1036  7129 D DhcpStateMachine: StoppedState
08-26 12:45:48.825  1036  7129 D DhcpStateMachine: StoppedState{ when=-163ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 12:45:48.827  1036  1524 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 12:45:48.828  1036  1524 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-26 12:45:48.828  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.828  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:48.828  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 12:45:48.833  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:48.841  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:48.846  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.854  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.855  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 12:45:48.859  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 12:45:48.863  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:48.872  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:48.874  7026  7026 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 12:45:48.875  1036  7032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 12:45:48.876  1036  7032 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 12:45:48.876  1036  7032 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 12:45:48.877  1036  1524 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-26 12:45:48.885  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:48.897  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.897  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:48.899  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 12:45:48.906  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:48.912  6791  6791 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 12:45:48.927  1036  1530 D WifiService: New client listening to asynchronous messages
,08-26 12:45:48.930  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 12:45:48.934  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 12:45:48.941  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 12:45:48.953  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:48.954  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 12:45:48.956  6820  6820 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 12:45:48.958  6820  6820 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 12:45:48.959  6820  6820 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 12:45:48.967  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 12:45:48.976  6791  6791 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 12:45:48.977  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:45:48.986  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:48.988  1036  1524 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 12:45:48.989  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 12:45:48.989  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-26 12:45:48.989  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 12:45:48.991  1928  1928 D WfdsService: Supplicant Connection state is changed : false
08-26 12:45:48.991  1928  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 12:45:48.991  1928  2279 D WfdsService: Set the WFDS Monitor: false
08-26 12:45:48.991  1928  2279 D WfdsMonitor: WFDS Monitor is stopped
08-26 12:45:48.994  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 12:45:48.994  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:45:48.996  2456  2456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:48.998  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 12:45:48.999  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 12:45:48.999  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 12:45:49.000  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 12:45:49.001  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:49.001  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:49.001  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:49.001  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:49.001  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:49.001  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:49.001  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:49.001  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:45:49.002  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:49.002  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:49.002  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:49.002  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:49.002  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:49.002  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:49.002  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:49.002  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:49.002  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:49.007  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:49.018  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:49.018  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:49.020  6820  6820 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 12:45:49.022  6820  6820 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 12:45:49.023  6820  6820 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 12:45:49.030  1036  1561 I ActivityManager: Killing 6739:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-26 12:45:49.066  1036  2021 W libprocessgroup: failed to open /acct/uid_10037/pid_6739/cgroup.procs: No such file or directory
,08-26 12:45:49.070  2152  2152 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 12:45:49.085  2152  2152 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 12:45:49.086  2152  2152 D c       : Getting all permits...
,08-26 12:45:49.086  2152  2152 D a       : Opening database...
08-26 12:45:49.091  2152  2152 D a       : Opening database auth.proximity.permit_store...
08-26 12:45:49.092  2152  2152 D a       : Closing database...
08-26 12:45:49.112  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 12:45:49.123  6791  6791 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 12:45:49.124  6791  6791 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 12:45:49.124  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 12:45:49.131  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:49.144  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:49.158  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:49.159  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 12:45:49.165  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 12:45:49.173  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 12:45:49.179  6791  6791 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 12:45:49.180  6791  6791 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 12:45:49.180  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:45:49.189  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:49.199  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:49.206  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 12:45:49.206  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:49.208  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 12:45:49.213  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:45:49.216  6791  6791 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 12:45:49.217  6791  6791 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 12:45:49.217  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:45:49.221  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:45:49.228  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:49.234  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:45:49.234  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:45:49.236  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 12:45:49.244  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:45:49.247  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 12:45:49.256  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:45:49.257  6865  7335 W FormManager: Network not available. Please check & try again.
08-26 12:45:49.279  6865  7336 V FormManager: Network unavailable.
08-26 12:45:49.279  2152  2152 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-26 12:45:49.288  6865  7336 V FormManager: Network unavailable.
08-26 12:45:49.305  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 12:45:49.306  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 12:45:49.306  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 12:45:49.306  6770  6770 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 12:45:49.306  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-26 12:45:49.307  6770  6770 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 12:45:49.307  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 12:45:49.307  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 12:45:49.307  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 12:45:49.307  6770  6770 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 12:45:49.308  6770  6770 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 12:45:49.314  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 12:45:49.314  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 12:45:49.316  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:49.319  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 12:45:49.327  4285  7337 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 12:45:49.328  6791  6791 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 12:45:49.328  6791  6791 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 12:45:49.328  6791  6791 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:45:49.330  4285  7338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 12:45:49.331  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 12:45:49.332  4285  7338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 12:45:49.344  6865  7340 W FormManager: Network not available. Please check & try again.
08-26 12:45:49.346  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 12:45:49.351  6865  7341 V FormManager: Network unavailable.
08-26 12:45:49.358  6865  7341 V FormManager: Network unavailable.
,08-26 12:45:49.698  6653  6955 D UEI.SmartControl: Internal timer expired: 2
,08-26 12:45:49.698  6653  6955 D UEI.SmartControl: unbind internal service
,08-26 12:45:49.828  6653  6949 D serial_port: close(fd = 24)
,08-26 12:45:49.838  6653  6949 I UEI.SmartControl: Serial port is closed.
,08-26 12:45:50.416  1036  1524 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-965432113] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 12:45:50.418  1036  1524 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-965432110] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 12:45:50.496  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:50.510  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-26 12:45:50.521  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:50.525  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:50.528  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:50.531  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 12:45:50.533  6394  6421 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 12:45:50.548  5727  5727 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 12:45:50.571  2152  2152 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:50.598  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 12:45:50.598  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:50.598  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 12:45:50.598  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 12:45:50.604  6964  6964 I AppUp4:CustModeStarterReceiver: onReceive
08-26 12:45:50.607  6964  6964 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23f98635
08-26 12:45:50.607  6964  6964 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 12:45:50.607  6964  6964 D AppUp4:CustFacade: isPhone : true
08-26 12:45:50.608  6964  6964 D AppUp4:CustModeStarterReceiver: begin check event
08-26 12:45:50.608  6964  6964 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 12:45:50.614  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:50.614  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 12:45:50.615  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 12:45:50.621  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:50.637  7008  7008 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 12:45:50.677  4285  7360 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 12:45:50.677  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 12:45:50.677  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:50.677  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 12:45:50.678  3421  3421 D PhoneState: setPdpRejectCasuse : false
,08-26 12:45:50.679  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:50.683  4285  7367 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:50.683  4285  7367 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 12:45:50.688  7039  7039 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 12:45:50.688  7039  7039 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 12:45:50.692  7008  7363 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 12:45:50.699  6865  7365 W FormManager: Network not available. Please check & try again.
,08-26 12:45:50.710  6865  7366 V FormManager: Network unavailable.
08-26 12:45:50.711  7110  7110 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:50
,08-26 12:45:50.712  7110  7110 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-26 12:45:50.712  7110  7110 D Weather.Utils: 2 : All the weather widget is gone.
,08-26 12:45:50.713  7110  7110 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-26 12:45:50.713  7110  7110 D WeatherAncestor: connectivity changed - connection : true
08-26 12:45:50.713  7110  7110 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@77a043b
,08-26 12:45:50.713  6865  7366 V FormManager: Network unavailable.
08-26 12:45:50.714  7110  7110 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 12:45:50.714  7110  7110 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 12:45:50.714  7110  7110 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-26 12:45:50.714  7110  7110 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 12:45:50.714  7110  7110 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:50
08-26 12:45:51.613  1036  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 12:45:51.627  1036  1760 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-26 12:45:51.643  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 12:45:51.643  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 12:45:51.643  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-26 12:45:51.646  1036  1118 D BluetoothManagerService: Message: 1
08-26 12:45:51.646  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 12:45:51.678  1036  1118 D BluetoothManagerService: Message: 20
08-26 12:45:51.679  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bbaa8cb:true
,08-26 12:45:51.682  6905  6905 D BluetoothAdapterState: make
08-26 12:45:51.687  6905  6905 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 12:45:51.687  6905  6905 I bluedroid-qcom: init
08-26 12:45:51.688  6905  7381 I BluetoothAdapterState: Entering OffState
08-26 12:45:51.689  6905  6905 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 12:45:51.689  6905  6905 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 12:45:51.689  6905  6905 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 12:45:51.689  6905  6905 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 12:45:51.689  6905  6905 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 12:45:51.691  6905  6905 I bluedroid-qcom: get_profile_interface socket
08-26 12:45:51.691  6905  6905 I bluedroid-qcom: get_profile_interface map_client
,08-26 12:45:51.695  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:51.685  7384  7384 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:51.699  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-26 12:45:51.699  6905  7385 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 12:45:51.701  6905  7385 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 12:45:51.685  7384  7384 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:51.710  7384  7384 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 12:45:51.710  7384  7384 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 12:45:51.710  7384  7384 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 12:45:51.714  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:51.719  7384  7384 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 12:45:51.721  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-26 12:45:51.727  7384  7384 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 12:45:51.727  7384  7384 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-26 12:45:51.733  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:51.734  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:51.741  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:51.745  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:51.748  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 12:45:51.748  1036  1118 D BluetoothManagerService: Message: 40
08-26 12:45:51.748  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 12:45:51.749  6905  6921 I bluedroid-qcom: config_hci_snoop_log
08-26 12:45:51.750  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 12:45:51.750  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 12:45:51.755  6905  7385 D BluetoothAdapterProperties: Name is: G3
,08-26 12:45:51.758  6905  7381 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-26 12:45:51.758  6905  7381 D BluetoothAdapterProperties: Setting state to 11
08-26 12:45:51.759  6905  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 12:45:51.759  1036  1118 D BluetoothManagerService: Message: 60
08-26 12:45:51.759  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 12:45:51.759  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 12:45:51.761  6905  7381 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 12:45:51.769  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 12:45:51.777  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 12:45:51.778  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 12:45:51.779  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:51.783  6394  6421 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 12:45:51.787  6905  7381 D BluetoothBondStateMachine: make
08-26 12:45:51.789  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:51.789  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:51.790  6770  6770 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 12:45:51.791  6905  7400 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 12:45:51.791  6905  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:51.791  6905  7381 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 12:45:51.791  6905  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:51.791  6905  7381 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 12:45:51.792  6905  7381 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-26 12:45:51.793  5727  5727 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 12:45:51.794  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 12:45:51.795  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:51.799  6905  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:45:51.807  5727  5727 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 12:45:51.810  6905  6905 D HeadsetService: Received start request. Starting profile...
08-26 12:45:51.811  6905  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:45:51.811  6905  6905 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 12:45:51.811  6905  6905 D LGBluetoothHfpAdapter: Version 1.6
08-26 12:45:51.815  6905  6905 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 12:45:51.816  6905  6905 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 12:45:51.816  6905  6905 D HeadsetStateMachine: make
08-26 12:45:51.820  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:51.821  6905  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:45:51.821  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:45:51.821  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 12:45:51.827  6905  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:45:51.834  6905  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:45:51.835  2152  2152 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:51.841  6905  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:45:51.845  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 12:45:51.845  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:51.845  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 12:45:51.845  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 12:45:51.848  6964  6964 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 12:45:51.850  6905  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:45:51.857  6905  6905 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:45:51.857  6905  6905 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 12:45:51.859  6964  6964 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23f98635
,08-26 12:45:51.859  6964  6964 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 12:45:51.859  6964  6964 D AppUp4:CustFacade: isPhone : true
08-26 12:45:51.860  6964  6964 D AppUp4:CustModeStarterReceiver: begin check event
08-26 12:45:51.860  6905  7381 V LGMDMManager: Create singleton instance
08-26 12:45:51.860  6964  6964 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 12:45:51.861  6905  6905 D HeadsetStateMachine: max_hf_connections = 1
08-26 12:45:51.861  6905  6905 I bluedroid-qcom: get_profile_interface handsfree
08-26 12:45:51.862  6905  7381 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 12:45:51.863  6905  6905 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 12:45:51.863  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:51.863   325  1371 V AudioPolicyService: registerClient() client 0xb0410540, uid 1002
08-26 12:45:51.864  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 12:45:51.864   325  2151 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 12:45:51.864   325  2151 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 12:45:51.864   325  2151 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 12:45:51.864  6905  6905 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 12:45:51.864   325  1770 V AudioFlinger: registerClient() client 0xb14337a8, pid 6905
08-26 12:45:51.865   325  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:45:51.865   325  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:45:51.865  1841  2678 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:45:51.865  1841  2678 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:45:51.865  6905  7405 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:45:51.865  3421  3440 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:45:51.865  3421  3440 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:45:51.865  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:51.865  1036  1760 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:45:51.865  1036  1760 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:45:51.866  1588  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:45:51.866  1588  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:45:51.866   325  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:45:51.866   325  1366 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:45:51.866  1036  2002 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:45:51.866  1036  2002 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:45:51.866  1841  1856 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:45:51.866  1841  1856 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:45:51.866  1588  1605 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:45:51.866  1588  1605 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:45:51.866  6905  7405 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 12:45:51.866  6905  7405 V AudioSystem: ioConfigCh,anged() event 0, ioHandle 4
08-26 12:45:51.866  6905  7405 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 12:45:51.867  6905  6905 V ToneGenerator: Create Track: 0xb4928080
08-26 12:45:51.867  6905  6905 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 12:45:51.867  6905  6905 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 12:45:51.867  3421  3442 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:45:51.867  3421  3442 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:45:51.867   325  1370 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 12:45:51.867   325  1370 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 12:45:51.867   325  1370 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 12:45:51.867   325  1370 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 12:45:51.867   325  1371 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 12:45:51.867  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:51.867   325  2151 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 12:45:51.867   325  2151 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 12:45:51.867   325  2151 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 12:45:51.867   325  2151 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 12:45:51.867  6905  6905 V AudioSystem: getLatency() output 2, latency 50
08-26 12:45:51.867  6905  6905 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 12:45:51.867  6905  6905 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 12:45:51.868   325  1770 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 12:45:51.868   325  1770 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 12:45:51.868   325  1770 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 12:45:51.868   325  1770 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 12:45:51.868   325  1770 V AudioFlinger: createTrack() lSessionId: 22
08-26 12:45:51.869  6905  6905 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 12:45:51.870   325  1770 V AudioFlinger: acquiring 22 from 6905, for 6905
08-26 12:45:51.870   325  1770 V AudioFlinger:  added new entry for 22
08-26 12:45:51.870  6905  6905 V ToneGenerator: ToneGenerator INIT OK, time: 125446
,08-26 12:45:51.870  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
,08-26 12:45:51.871  6905  7404 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 12:45:51.871  6905  7404 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 12:45:51.871  6905  7404 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 12:45:51.871  6905  7404 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 12:45:51.871  4285  7408 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 12:45:51.872   325   325 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6905
08-26 12:45:51.872   325   325 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 12:45:51.872   325   325 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 12:45:51.872   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 12:45:51.872   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 12:45:51.872   325   325 V voice   : voice_set_parameters: exit with code(0)
08-26 12:45:51.872   325   325 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 12:45:51.872   325   325 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 12:45:51.872   325   325 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 12:45:51.872   325   325 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 12:45:51.872   325   325 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 12:45:51.872   325   325 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 12:45:51.873  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:51.873  6905  7404 V ToneGenerator: ToneGenerator destructor
08-26 12:45:51.873  6905  7404 V ToneGenerator: stopTone
08-26 12:45:51.873  6905  7404 V ToneGenerator: Delete Track: 0xb4928080
08-26 12:45:51.874  6905  6905 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 12:45:51.875  6905  6905 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:51.875  6905  6905 V BluetoothPbapReceiver: ***********state = 11
08-26 12:45:51.876   325  2151 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 12:45:51.876   325  2151 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 12:45:51.876   325  2151 V AudioFlinger: PlaybackThread::Track destructor
08-26 12:45:51.876   325  1272 V AudioPolicyService: AudioCommandThread() waking up
08-26 12:45:51.876   325  2151 V AudioFlinger: removeClient_l() pid 6905, calling pid 325
08-26 12:45:51.876   325  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 12:45:51.876   325  1272 V AudioPolicyManager: releaseOutput() 2
08-26 12:45:51.876   325  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 12:45:51.876  6905  7404 V AudioTrack: ~AudioTrack, releasing session id from 6905 on behalf of 6905
08-26 12:45:51.876   325  1770 V AudioFlinger: releasing 22 from 6905 for 6905
08-26 12:45:51.876   325  1770 V AudioFlinger:  decremented refcount to 0
08-26 12:45:51.876   325  1770 V AudioFlinger: purging stale effects
08-26 12:45:51.878  2152  2152 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:45:51.878  6905  6905 D A2dpService: Received start request. Starting profile...
08-26 12:45:51.879  6905  6905 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 12:45:51.880  6905  6905 V Avrcp   : make
08-26 12:45:51.880  6905  6905 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 12:45:51.880  6905 , 6905 I bluedroid-qcom: get_profile_interface avrcp
08-26 12:45:51.881  7008  7008 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 12:45:51.881  4285  7409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:51.881  4285  7409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 12:45:51.920  1036  1058 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7410 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 12:45:51.930  6905  6905 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 12:45:51.932  6905  6905 E AudioManager: No RCC entry present to update
,08-26 12:45:51.932  6905  6905 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 12:45:51.937  6905  6905 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 12:45:51.939  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 12:45:51.939  6905  6905 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 12:45:51.942  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 12:45:51.942  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:51.943  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 12:45:51.946  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-26 12:45:51.988  7039  7039 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 12:45:51.988  7039  7039 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 12:45:52.002  7008  7427 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:52.008  6865  7433 V FormManager: Network unavailable.
,08-26 12:45:52.011  6865  7432 W FormManager: Network not available. Please check & try again.
08-26 12:45:52.022  7110  7110 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:52
,08-26 12:45:52.025  7110  7110 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 12:45:52.025  7110  7110 D Weather.Utils: 2 : All the weather widget is gone.
08-26 12:45:52.025  6865  7433 V FormManager: Network unavailable.
08-26 12:45:52.025  7110  7110 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 12:45:52.025  7110  7110 D WeatherAncestor: connectivity changed - connection : true
08-26 12:45:52.026  7110  7110 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@77a043b
08-26 12:45:52.026  7110  7110 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 12:45:52.027  7110  7110 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 12:45:52.027  7110  7110 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 12:45:52.027  7110  7110 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 12:45:52.027  7110  7110 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:52
08-26 12:45:52.039  1036  2002 V SIM_STK : Menu title from STK is T-Mobile
08-26 12:45:52.040  1036  2002 V SIM_STK : Menu title from STK is T-Mobile
,08-26 12:45:52.047  6394  6394 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 12:45:52.048  6394  6421 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 12:45:52.062  2152  2152 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 12:45:52.073  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 12:45:52.073  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:52.073  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 12:45:52.073  6964  6964 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 12:45:52.075  6964  6964 I AppUp4:CustModeStarterReceiver: onReceive
08-26 12:45:52.079  6964  6964 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23f98635
,08-26 12:45:52.079  6964  6964 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 12:45:52.079  6964  6964 D AppUp4:CustFacade: isPhone : true
08-26 12:45:52.079  6964  6964 D AppUp4:CustModeStarterReceiver: begin check event
08-26 12:45:52.079  6964  6964 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 12:45:52.082  7410  7410 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 12:45:52.082  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:52.082  7410  7410 W LG Account v2.2: No ProfileInfo entries
08-26 12:45:52.082  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 12:45:52.082  7410  7410 I LG Account v2.2: isEnabled: false
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]Country: EU
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]Operator: OPEN
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]Ranking support: false
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]Comfort support: false
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]Accessory: true
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]Health device: true
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]Extra Pedometer: false
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]Blood glucose device: false
08-26 12:45:52.083  7410  7410 I Feature : [Lifetracker]Device Number: 3
,08-26 12:45:52.085  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:52.086  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:45:52.091  4285  7436 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 12:45:52.096  4285  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:52.097  4285  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 12:45:52.097  1036  2038 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 12:45:52.100  7008  7008 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 12:45:52.100  6770  6770 D BluetoothPermissionRequest: onReceive
08-26 12:45:52.102  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 12:45:52.104  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 12:45:52.105  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-26 12:45:52.105  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 12:45:52.105  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 12:45:52.105  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-26 12:45:52.105  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 12:45:52.105  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 12:45:52.105  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 12:45:52.105  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 12:45:52.105  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 12:45:52.105  6905  6905 I BluetoothA2dpServiceJni: classInitNative
08-26 12:45:52.106  6905  6905 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 12:45:52.106  6905  6905 D A2dpStateMachine: make
08-26 12:45:52.107  6905  6905 I bluedroid-qcom: get_profile_interface a2dp
08-26 12:45:52.108  6905  7439 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 12:45:52.108  6770  6770 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 12:45:52.109  6905  6905 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 12:45:52.109  6905  6905 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 12:45:52.110  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:52.110  6905  7438 D A2dpStateMachine: Enter Disconnected: -2
08-26 12:45:52.111  6905  6905 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 12:45:52.113  6905  6905 D HidService: Received start request. Starting profile...
08-26 12:45:52.113  6905  6905 I bluedroid-qcom: get_profile_interface hidhost
08-26 12:45:52.113  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:52.113  6905  6905 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 12:45:52.114  6905  6905 D HealthService: Received start request. Starting profile...
08-26 12:45:52.116  6905  6905 I bluedroid-qcom: get_profile_interface health
08-26 12:45:52.116  6905  6905 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 12:45:52.116  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
,08-26 12:45:52.118  6905  6905 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 12:45:52.119  6905  6905 D PanService: Received start request. Starting profile...
08-26 12:45:52.119  6905  6905 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 12:45:52.119  6905  6905 I bluedroid-qcom: get_profile_interface pan
08-26 12:45:52.120  6865  7445 W FormManager: Network not available. Please check & try again.
08-26 12:45:52.122  7008  7441 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:45:52.124  6905  6905 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 12:45:52.124  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:52.125  6865  7446 V FormManager: Network unavailable.
08-26 12:45:52.126  6905  6905 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 12:45:52.129  6865  7446 V FormManager: Network unavailable.
,08-26 12:45:52.131  6905  6905 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 12:45:52.131  3421  3421 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 12:45:52.131  3421  3421 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 12:45:52.132  3421  3421 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 12:45:52.132  6905  6905 D BtGatt.GattService: Received start request. Starting profile...
08-26 12:45:52.132  6905  6905 D BtGatt.GattService: start()
,08-26 12:45:52.132  6905  6905 I bluedroid-qcom: get_profile_interface gatt
08-26 12:45:52.132  6905  6905 D BtGatt.AdvertiseManager: advertise manager created
08-26 12:45:52.134  7039  7039 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 12:45:52.134  7039  7039 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 12:45:52.139  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:52.140  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:52.140  6905  6905 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 12:45:52.141  6905  6905 V BluetoothMapService: BluetoothMapBinder()
,08-26 12:45:52.142  6905  6905 D BluetoothMapService: Received start request. Starting profile...
08-26 12:45:52.142  6905  6905 D BluetoothMapService: start()
08-26 12:45:52.144  7110  7110 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:52
08-26 12:45:52.146  6905  6905 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 12:45:52.146  6905  6905 D BluetoothMapEmailAppObserver: createReceiver()
08-26 12:45:52.147  6905  6905 D BluetoothMapEmailAppObserver: initObservers()
08-26 12:45:52.147  6905  6905 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 12:45:52.150  7110  7110 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 12:45:52.150  7110  7110 D Weather.Utils: 2 : All the weather widget is gone.
08-26 12:45:52.150  7110  7110 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 12:45:52.150  7110  7110 D WeatherAncestor: connectivity changed - connection : true
08-26 12:45:52.150  7110  7110 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@77a043b
08-26 12:45:52.151  7110  7110 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 12:45:52.151  7110  7110 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 12:45:52.151  7110  7110 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 12:45:52.151  7110  7110 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 12:45:52.151  7110  7110 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:45:52
08-26 12:45:52.159  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
,08-26 12:45:52.159  6905  6905 D HeadsetStateMachine: Proxy object connected
08-26 12:45:52.161  6905  6905 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 12:45:52.162  6905  6905 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 12:45:52.166  6905  6905 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 12:45:52.166  6905  7404 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 12:45:52.166  6905  7404 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 12:45:52.166  6905  7404 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 12:45:52.168  6905  6905 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 12:45:52.171  6905  6905 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 12:45:52.175  6905  6905 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 12:45:52.175  6905  6905 V PanService: [BTUI] SIM Extra State :ABSENT
,08-26 12:45:52.177  6905  6905 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 12:45:52.179  6905  6905 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 12:45:52.179  6905  6905 V BluetoothMapService: Handler(): got msg=1
08-26 12:45:52.179  6905  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 12:45:52.180  6905  7381 I bluedroid-qcom: enable
08-26 12:45:52.180  6905  7451 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 12:45:52.180  6905  7381 I bt_hci_bdroid: init
08-26 12:45:52.180  6905  7451 I bt-btu  : btu_task pending for preload complete event
08-26 12:45:52.180  6905  6905 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:52.181  6905  7381 I bt_vendor: bt-vendor : init
08-26 12:45:52.181  6905  7381 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 12:45:52.181  6905  7381 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 12:45:52.181  6905  7381 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 12:45:52.181  6905  7381 D bt_userial_mct: userial_init
08-26 12:45:52.181  6905  7381 D bt_hci_bdroid: set_power 1
08-26 12:45:52.181  6905  7381 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 12:45:52.181  6905  7381 I bt_vendor: Starting hciattach daemon
08-26 12:45:52.181  6905  7381 I bt_vendor: try to set true
08-26 12:45:52.182  6905  6905 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 12:45:52.183  6905  6905 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 12:45:52.183  6905  6905 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 12:45:52.183  6905  6905 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:52.183  6905  6905 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 12:45:52.165  7454  7454 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:52.165  7454  7454 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 12:45:52.201  7455  7455 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 12:45:52.294  7461  7461 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 12:45:52.319  7462  7462 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 12:45:52.373  7464  7464 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 12:45:52.389  7465  7465 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 12:45:52.415  7466  7466 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 12:45:52.428  7467  7467 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 12:45:52.450  7469  7469 I libmdmdetect: ESOC framework not supported
,08-26 12:45:52.451  7469  7469 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 12:45:52.460  7469  7469 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 12:45:52.460  7469  7469 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 12:45:52.461  7469  7469 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 12:45:52.461  7469  7469 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 12:45:52.461  7469  7469 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 12:45:52.461  7469  7469 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 12:45:52.461  7469  7469 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 12:45:52.497  7469  7470 E QC-QMI  : qmi_client [7469] 14: failed to locate client data
,08-26 12:45:52.501   441   441 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-26 12:45:52.501   441   441 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-26 12:45:52.547  7477  7477 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 12:45:52.572  7478  7478 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 12:45:52.623  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7392
08-26 12:45:52.623  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7393
08-26 12:45:52.625  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7401
08-26 12:45:52.625  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7406
,08-26 12:45:52.626  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7454
08-26 12:45:52.626  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7474
08-26 12:45:52.628  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7479
08-26 12:45:52.633  6905  7381 I bt_vendor: bluetooth satus is on
08-26 12:45:52.633  6905  7381 D bt_hci_bdroid: preload
08-26 12:45:52.633  6905  7453 D bt_userial_mct: userial_open(port:0)
08-26 12:45:52.633  6905  7453 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 12:45:52.636  6905  7453 I bt_vendor: Done intiailizing UART
08-26 12:45:52.637  6905  7453 I bt_vendor: Done intiailizing UART
,08-26 12:45:52.637  6905  7453 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-26 12:45:52.637  6905  7453 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 12:45:52.638  6905  7480 D bt_userial_mct: Entering userial_read_thread()
08-26 12:45:52.638  6905  7451 I bt-btu  : btu_task received preload complete event
08-26 12:45:52.638  6905  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 12:45:52.638  6905  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 12:45:52.641  6905  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 12:45:52.643  6905  7451 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 12:45:52.644  6905  7451 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 12:45:52.644  6905  7451 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 12:45:52.644  6905  7451 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 12:45:52.644  6905  7451 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 12:45:52.644  6905  7451 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 12:45:52.665  7137  7164 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-26 12:45:52.696  6905  7451 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 12:45:52.696  6905  7451 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa018e061 
08-26 12:45:52.696  6905  7451 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa018e061 
,08-26 12:45:52.715  6905  7385 E bt-btif : Calling BTA_HhEnable
08-26 12:45:52.715  6905  7385 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 12:45:52.715  6905  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 12:45:52.715  6905  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-26 12:45:52.715  6905  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 12:45:52.715  6905  7385 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 12:45:52.716  6905  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 12:45:52.716  6905  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 12:45:52.718  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 12:45:52.718  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 12:45:52.718  6905  7385 D BluetoothAdapterProperties: Name is: G3
08-26 12:45:52.722  6905  7385 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:45:52.722  6905  7385 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 12:45:52.723  6905  7385 D bt_hci_bdroid: postload
08-26 12:45:52.723  6905  7453 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 12:45:52.724  6905  7385 D bte_conf: Device ID record 1 : primary
08-26 12:45:52.725  6905  7385 D bte_conf:   vendorId            = 00c4
08-26 12:45:52.725  6905  7385 D bte_conf:   vendorIdSource      = 0001
08-26 12:45:52.725  6905  7385 D bte_conf:   product             = 13a1
08-26 12:45:52.725  6905  7385 D bte_conf:   version             = 1000
08-26 12:45:52.725  6905  7385 D bte_conf:   clientExecutableURL = 
08-26 12:45:52.725  6905  7385 D bte_conf:   serviceDescription  = 
08-26 12:45:52.725  6905  7385 D bte_conf:   documentationURL    = 
08-26 12:45:52.725  6905  7385 D bte_conf: bte_load_did_conf no section named DID2.
08-26 12:45:52.726  6905  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 12:45:52.728  6905  7453 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 12:45:52.728  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:52.731  6905  7385 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 12:45:52.725  7484  7484 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:52.725  7484  7484 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:52.736  6905  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 12:45:52.737  6905  7381 D BluetoothAdapterProperties: ScanMode =  20
08-26 12:45:52.737  6905  7381 D BluetoothAdapterProperties: State =  11
08-26 12:45:52.737  6905  7381 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 12:45:52.738  6905  7381 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 12:45:52.738  6905  7381 D BluetoothAdapterProperties: Setting state to 12
08-26 12:45:52.738  6905  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 12:45:52.739  1036  1118 D BluetoothManagerService: Message: 60
08-26 12:45:52.739  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 12:45:52.739  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 12:45:52.740  6905  7453 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 12:45:52.740  6905  7381 I BluetoothAdapterState: Entering On State
08-26 12:45:52.741  1841  1857 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:45:52.745  6905  7385 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 12:45:52.750  6905  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:45:52.750  6905  7451 W bt-smp  : Plain text(LSB ~ MSB) = 82 42 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:45:52.750  6905  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = 3c 92 b8 ec 4f 47 a6 98 2e 75 1e 29 85 e7 c2 cd 
08-26 12:45:52.750  6905  7453 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 12:45:52.750  6905  7451 W bt-btm  : Stopping oneshot timer
08-26 12:45:52.751  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:52.751  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:52.751  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:52.751  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:52.751  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:52.751  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:52.751  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:52.751  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:52.753  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:52.754  6905  7480 E bt_mct  : hci lib postload completed
08-26 12:45:52.765  6905  7381 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 12:45:52.765  6905  7381 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 12:45:52.765  6905  7381 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-26 12:45:52.766  6905  7381 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 12:45:52.766  6905  7385 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 12:45:52.766  6905  7385 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 12:45:52.773  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:45:52.774  1841  1841 D BluetoothHeadset: Proxy object connected
08-26 12:45:52.775  6770  6787 D BluetoothPan: onBluetoothStateChange on: true
08-26 12:45:52.775  6770  6787 D BluetoothPan: onBluetoothStateChange call bindService
08-26 12:45:52.778  6770  6787 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 12:45:52.781  6770  6770 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 12:45:52.781  6770  6770 D PanProfile: Bluetooth service connected
08-26 12:45:52.783  6905  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:45:52.783  6905  7451 W bt-smp  : Plain text(LSB ~ MSB) = 96 f8 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:45:52.784  6905  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = 21 b2 61 55 d2 81 a5 79 70 68 81 e2 d2 d9 ec 3a 
08-26 12:45:52.784  6905  7451 W bt-btm  : Stopping oneshot timer
08-26 12:45:52.784  1036  1036 D BluetoothHeadset: Proxy object connected
08-26 12:45:52.790  6905  7381 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 12:45:52.791  6770  7487 D BluetoothMap: onBluetoothStateChange: up=true
08-26 12:45:52.798  6770  6770 D BluetoothMap: Proxy object connected
08-26 12:45:52.798  6770  6770 D MapProfile: Bluetooth service connected
08-26 12:45:52.798  6770  6770 D BluetoothMap: getConnectedDevices()
,08-26 12:45:52.801  1841  2678 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:45:52.804  1841  1841 D BluetoothHeadset: Proxy object connected
08-26 12:45:52.804  6905  6920 V BluetoothMapService: getConnectedDevices()
08-26 12:45:52.805  6905  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:45:52.805  6905  7451 W bt-smp  : Plain text(LSB ~ MSB) = 2c ae 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:45:52.805  6905  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = c0 48 c7 e5 cb 61 9c 80 3f cb 1c 66 af 4e e6 2b 
08-26 12:45:52.805  6905  7451 W bt-btm  : Stopping oneshot timer
08-26 12:45:52.806  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:45:52.808  1036  1036 D BluetoothA2dp: Proxy object connected
08-26 12:45:52.810  6770  6787 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 12:45:52.814  1841  4382 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 12:45:52.814  6770  6770 D BluetoothInputDevice: Proxy object connected
08-26 12:45:52.814  6770  6770 D HidProfile: Bluetooth service connected
08-26 12:45:52.817  6905  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:45:52.817  6905  7451 W bt-smp  : Plain text(LSB ~ MSB) = 75 b6 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:45:52.817  6905  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = af d5 fe 18 eb c6 2e 6c d6 6e e7 36 b6 79 0b b0 
08-26 12:45:52.817  6905  7451 W bt-btm  : Stopping oneshot timer
08-26 12:45:52.820  1841  1841 D BluetoothHeadset: Proxy object connected
08-26 12:45:52.823  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 12:45:52.824  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 12:45:52.824  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 12:45:52.825  1036  1118 D BluetoothManagerService: Message: 40
08-26 12:45:52.825  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-26 12:45:52.829  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 12:45:52.830  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:52.831  1928  2091 D LGBluetoothAPIService: Message: 1
08-26 12:45:52.831  1928  2091 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 12:45:52.837  7499  7499 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 12:45:52.838  6905  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:45:52.838  6905  7451 W bt-smp  : Plain text(LSB ~ MSB) = f0 45 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:45:52.838  6905  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = 5b 2b ad db 68 cb df b5 01 78 50 e2 eb 3a 00 23 
08-26 12:45:52.838  6905  7451 W bt-btm  : Stopping oneshot timer
,08-26 12:45:52.851  6571  6571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-26 12:45:52.856  6905  6905 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:52.856  6905  6905 D BluetoothMapService: STATE_ON
08-26 12:45:52.857  1928  2091 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 12:45:52.857  6770  6770 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 12:45:52.859  6905  6905 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 12:45:52.859  6905  6905 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 12:45:52.860  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 12:45:52.860  1928  2091 D LGBluetoothAPIService: Message: 100
08-26 12:45:52.860  1928  2091 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 12:45:52.862  1036  1118 D BluetoothManagerService: Message: 30
08-26 12:45:52.863  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:52.863  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:52.863  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:52.863  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:52.863  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:45:52.863  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:52.863  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:52.863  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:52.865  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:52.868  6770  6770 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 12:45:52.868  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:52.870  1036  1118 D BluetoothManagerService: Message: 30
08-26 12:45:52.875  6770  6770 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 12:45:52.877  6770  6770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 12:45:52.877  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:52.877  6905  6905 V BluetoothPbapService: Pbap Service onCreate
08-26 12:45:52.877  6905  6905 V BluetoothPbapService: Starting PBAP service
08-26 12:45:52.879  6905  6905 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 12:45:52.879  6905  6905 V BluetoothPbapService: Pbap Service onBind
,08-26 12:45:52.881  6905  6905 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:52.881  6905  6905 V BluetoothPbapService: state: 12
08-26 12:45:52.881  6905  6905 V BluetoothMapService: Handler(): got msg=1
08-26 12:45:52.882  6770  6770 D BluetoothA2dp: Proxy object connected
08-26 12:45:52.882  6905  6905 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 12:45:52.882  6905  6905 V BluetoothPbapService: Handler(): got msg=1
08-26 12:45:52.883  6905  6905 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 12:45:52.883  6905  7504 D BluetoothMapMasInstance: MAS initSocket()
08-26 12:45:52.884  6905  6905 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 12:45:52.884  6770  6770 D A2dpProfile: Bluetooth service connected
08-26 12:45:52.884  6905  6905 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:52.884  6905  6905 V BluetoothPbapReceiver: ***********state = 12
08-26 12:45:52.884  6905  7504 D BluetoothMapMasInstance:   masId = 00
08-26 12:45:52.884  6905  7504 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 12:45:52.884  6905  7504 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 12:45:52.884  6905  7504 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 12:45:52.886  6905  7505 V BluetoothPbapService: Pbap Service initSocket
08-26 12:45:52.887  1036  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:52.887  2152  2152 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:45:52.887  1036  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:52.888  2152  2152 D c       : Getting all permits...
08-26 12:45:52.888  2152  2152 D a       : Opening database...
08-26 12:45:52.888  6770  6770 D BluetoothHeadset: Proxy object connected
08-26 12:45:52.889  6770  6770 D HeadsetProfile: Bluetooth service connected
08-26 12:45:52.892  2152  2152 D a       : Opening database auth.proximity.permit_store...
,08-26 12:45:52.895  6905  7505 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 12:45:52.895  2152  2152 D a       : Closing database...
08-26 12:45:52.896  6905  7504 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:45:52.897  6905  7505 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 12:45:52.897  6905  7505 V BluetoothPbapService: Succeed to create listening socket 
,08-26 12:45:52.897  6905  7505 V BluetoothPbapService: Accepting socket connection...
08-26 12:45:52.898  6905  7504 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 12:45:52.898  6905  7504 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 12:45:52.898  6905  7504 D BluetoothMapMasInstance: Accepting socket connection...
,08-26 12:45:52.901  6905  7385 D BluetoothAdapterProperties: Scan Mode:21
08-26 12:45:52.901  6905  7385 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 12:45:52.903  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:52.904  6770  6770 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:45:52.905  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:45:52.905  6770  6770 D BluetoothPbap: Proxy object connected
08-26 12:45:52.906  6770  6770 D PbapServerProfile: Bluetooth service connected
08-26 12:45:52.914  6770  6770 D BluetoothPermissionRequest: onReceive
08-26 12:45:52.916  6770  6770 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 12:45:52.918  6770  6770 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 12:45:52.921  6905  6905 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 12:45:52.922  6905  6905 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 12:45:52.928  6905  6905 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 12:45:52.949  6905  6905 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 12:45:52.949  6905  6905 V BtOppService: onCreate
,08-26 12:45:52.954  6905  6905 V BluetoothOppNotification: send message
08-26 12:45:52.960  6905  6905 V BtOppService: Starting RfcommListener
08-26 12:45:52.966  6905  6905 W art     : No such thread id for suspend: 31
08-26 12:45:52.966  6905  6905 D BluetoothOppPreference: Dumping Names:  
08-26 12:45:52.966  6905  6905 D BluetoothOppPreference: {}
08-26 12:45:52.966  6905  6905 D BluetoothOppPreference: Dumping Channels:  
,08-26 12:45:52.966  6905  6905 D BluetoothOppPreference: {}
08-26 12:45:52.967  6905  6905 V BtOppService: onStartCommand
08-26 12:45:52.970  6905  6905 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:52.971  6905  6905 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 12:45:52.974  6905  6905 V BluetoothOppNotification: new notify threadi!
08-26 12:45:52.974  6905  7513 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 12:45:52.975  6905  6905 V BluetoothOppNotification: send delay message
08-26 12:45:52.976  6905  6905 V BtOppService: start RfcommListener
08-26 12:45:52.980  6905  6905 V BtOppService: RfcommListener started
,08-26 12:45:52.986  6905  7510 V BtOppService: Deleted complete outbound shares, number =  0
08-26 12:45:52.986  6905  7514 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 12:45:52.987  6905  7513 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 12:45:52.988  6905  7514 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d20b94 on behalf of 
08-26 12:45:52.991  6905  7510 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 12:45:52.992  6905  7514 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 12:45:52.992  6905  7510 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-26 12:45:52.993  6905  7513 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@216e363d on behalf of 
08-26 12:45:52.993  6905  7510 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a1de32 on behalf of 
,08-26 12:45:52.995  6905  7515 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 12:45:52.996  1036  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:52.997  6905  7515 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:45:52.998  6905  7514 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 12:45:52.999  6905  7515 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-26 12:45:52.999  6905  7515 V BtOppRfcommListener: Started RFCOMM listener....
08-26 12:45:52.999  6905  7515 I BtOppRfcommListener: Accept thread started.
08-26 12:45:52.999  6905  7515 V BtOppRfcommListener: Accepting connection...
08-26 12:45:53.004  6905  7514 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@234b0783 on behalf of 
08-26 12:45:53.004  6905  7513 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 12:45:53.005  6905  7514 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-26 12:45:53.007  6905  7514 V BluetoothOppNotification: outbound notification was removed.
08-26 12:45:53.007  6905  7514 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 12:45:53.009  6905  7514 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@358e4d00 on behalf of 
08-26 12:45:53.010  6905  7514 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 12:45:53.011  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:53.012  6905  6905 V BluetoothFtpService: Ftp Service onCreate
08-26 12:45:53.012  6905  6905 I BluetoothFtpService: Ftp Service onCreate
08-26 12:45:53.012  6905  6905 V BluetoothFtpService: Ftp Service onStartCommand
,08-26 12:45:53.012  6905  6905 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:53.012  6905  7514 V BluetoothOppNotification: inbound notification was removed.
08-26 12:45:53.012  6905  6905 V BluetoothFtpService: Starting Listening on sockets
08-26 12:45:53.012  6905  7514 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 12:45:53.013  6905  6905 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 12:45:53.013  6905  6905 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 12:45:53.013  6905  6905 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 12:45:53.013  6905  6905 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:53.013  6905  6905 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 12:45:53.013  6905  6905 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 12:45:53.015  6905  7514 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f8bab7e on behalf of 
08-26 12:45:53.016  6905  6905 V BtOppService: ContentObserver received notification
08-26 12:45:53.021  6905  6905 V BtOppService: ContentObserver received notification
08-26 12:45:53.021  6905  6905 V BluetoothFtpService: Handler(): got msg=1
08-26 12:45:53.022  6905  6905 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 12:45:53.022  6905  6905 V BluetoothFtpService: Ftp Service initSocket
08-26 12:45:53.022  6905  7516 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 12:45:53.022  6905  7516 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-26 12:45:53.025  1036  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:53.026  6905  7516 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e2c98df on behalf of 
08-26 12:45:53.027  6905  7516 V BluetoothOppNotification: update too frequent, put in queue
08-26 12:45:53.027  6905  6905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:45:53.028  6905  7516 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 12:45:53.028  6905  6905 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 12:45:53.030  6905  7517 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 12:45:53.045  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:53.045  6905  6905 V BluetoothSapService: Sap Service onCreate
08-26 12:45:53.048  6905  6905 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:53.048  6905  6905 V BluetoothSapService: state: 12
08-26 12:45:53.048  6905  6905 V BluetoothSapService: Starting SAP server process
,08-26 12:45:53.050  6905  6905 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-26 12:45:53.052  6905  7519 V BluetoothSapService: Sap Service initRfcommSocket
08-26 12:45:53.035  7518  7518 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:53.054  1036  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:45:53.035  7518  7518 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:45:53.055  6905  7519 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:45:53.056  6905  7519 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 12:45:53.056  6905  7519 V BluetoothSapService: Succeed to create listening socket 
08-26 12:45:53.056  6905  7519 V BluetoothSapService: Accepting socket connection...
08-26 12:45:53.078  7518  7518 V BT_SAP  : Event pipe created
08-26 12:45:53.078  7518  7518 V BT_SAP  : create_server_socket qcom.sap.server
08-26 12:45:53.078  7518  7518 V BT_SAP  : created socket fd 6
,08-26 12:45:53.376  1036  1760 I ActivityManager: Killing 7297:com.lge.bnr/1000 (adj 15): empty #17
,08-26 12:45:53.445  1036  1642 W libprocessgroup: failed to open /acct/uid_1000/pid_7297/cgroup.procs: No such file or directory
,08-26 12:45:53.663  1036  1523 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 12:45:53.663  1036  1523 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 12:45:53.693  1036  1524 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 12:45:53.699  1036  1524 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-26 12:45:53.796  1036  1906 I ActivityManager: Killing 6653:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 12:45:53.819  6820  6820 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 12:45:53.819  6820  6820 W System.err: android.os.DeadObjectException
08-26 12:45:53.819  6820  6820 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 12:45:53.819  6820  6820 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 12:45:53.819  6820  6820 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 12:45:53.819  6820  6820 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 12:45:53.819  6820  6820 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 12:45:53.819  6820  6820 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 12:45:53.819  6820  6820 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 12:45:53.820  6820  6820 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 12:45:53.820  6820  6820 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 12:45:53.820  6820  6820 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 12:45:53.820  6820  6820 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:53.820  6820  6820 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 12:45:53.820  6820  6820 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 12:45:53.820  6820  6820 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 12:45:53.820  6820  6820 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 12:45:53.820  6820  6820 W System.err: android.os.DeadObjectException
08-26 12:45:53.820  6820  6820 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 12:45:53.821  6820  6820 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 12:45:53.821  6820  6820 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 12:45:53.821  6820  6820 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 12:45:53.821  6820  6820 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 12:45:53.821  6820  6820 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 12:45:53.821  6820  6820 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 12:45:53.821  6820  6820 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 12:45:53.821  6820  6820 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 12:45:53.821  6820  6820 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 12:45:53.821  6820  6820 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:45:53.821  6820  6820 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 12:45:53.821  6820  6820 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 12:45:53.821  6820  6820 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 12:45:53.821  6820  6820 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 12:45:53.822  6820  6820 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-26 12:45:53.858  1036  1933 W libprocessgroup: failed to open /acct/uid_1000/pid_6653/cgroup.procs: No such file or directory
,08-26 12:45:53.865  1036  1933 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-26 12:45:53.876  6820  6820 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 12:45:53.876  6820  6820 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 12:45:53.922  1036  1947 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7530 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 12:45:53.923  6820  6820 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 12:45:53.978  6905  6905 V BluetoothOppNotification: new notify threadi!
08-26 12:45:53.978  6905  6905 V BluetoothOppNotification: send delay message
08-26 12:45:53.987  6905  7547 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 12:45:53.997  6905  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e6be3fb on behalf of 
08-26 12:45:54.003  6905  7547 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-26 12:45:54.013  6905  7547 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 12:45:54.020  7530  7530 D UEI.SmartControl: Quickset Services start...
08-26 12:45:54.022  7530  7530 I UEI.SmartControl: Manufacture = LGE
08-26 12:45:54.022  7530  7530 D UEI.SmartControl: Id = LGNevo
,08-26 12:45:54.028  6905  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2288bc18 on behalf of 
08-26 12:45:54.028  6905  7547 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 12:45:54.030  7530  7530 D UEI.SmartControl: File observer start...
08-26 12:45:54.030  7530  7530 E UEI.SmartControl: IR Port is disabled: false
08-26 12:45:54.031  7530  7530 D UEI.SmartControl: Starting file observer...
08-26 12:45:54.031  7530  7530 D UEI.SmartControl: Extracting JNI libs...
08-26 12:45:54.031  7530  7530 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 12:45:54.039  6905  7547 V BluetoothOppNotification: outbound notification was removed.
08-26 12:45:54.039  6905  7547 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-26 12:45:54.053  6905  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30179671 on behalf of 
08-26 12:45:54.055  6905  7547 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 12:45:54.056  6905  7547 V BluetoothOppNotification: inbound notification was removed.
08-26 12:45:54.056  6905  7547 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 12:45:54.057  6905  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3647ac56 on behalf of 
,08-26 12:45:54.141  7530  7530 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 12:45:54.142  7530  7530 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 12:45:54.142  7530  7530 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 12:45:54.183  7530  7530 I UEI.SmartControl: --- Selecting new region: 6
,08-26 12:45:54.186  7530  7530 I UEI.SmartControl: Model = LG-D855
,08-26 12:45:54.189  7530  7530 D UEI.SmartControl: QS Service created
,08-26 12:45:54.206  7530  7530 I UEI.SmartControl: Service initServices...
,08-26 12:45:54.210  7530  7530 D UEI.SmartControl: QS start get config
,08-26 12:45:54.259  7530  7530 D UEI.SmartControl: Loading JNI Libs...
,08-26 12:45:54.516  7530  7530 I UEI.SmartControl: Supports setup maps: true,
,08-26 12:45:54.519  7530  7530 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 12:45:54.519  7530  7530 I UEI.SmartControl: QS version = v2.7.10.1_RC1,
08-26 12:45:54.519  7530  7530 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 12:45:54.519  7530  7530 I UEI.SmartControl: ### init IR Blaster...
,08-26 12:45:54.525  7530  7530 D serial_port: Configuring serial port
08-26 12:45:54.528  7530  7530 E UEI.SmartControl: UEIBLaster setting for 616
08-26 12:45:54.529  7530  7530 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 12:45:54.529  7530  7530 I UEI.SmartControl: configuring settings for MAXQ616
08-26 12:45:54.529  7530  7530 I UEI.SmartControl: Get version...
08-26 12:45:54.548  7530  7563 D UEI.SmartControl: serial port data available: 21
,08-26 12:45:54.577  7530  7530 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 12:45:54.578  7530  7530 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 12:45:54.578  7530  7530 I UEI.SmartControl: QS saving settings...
08-26 12:45:54.580  7530  7530 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 12:45:54.600  7530  7563 D UEI.SmartControl: serial port data available: 4
,08-26 12:45:54.609  1588  1588 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-26 12:45:54.610  1588  1588 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 12:45:54.618  1928  2082 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 12:45:54.618  1928  2082 D LEDHandler: Battery Level Remaining: 100%
08-26 12:45:54.619  1928  2082 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
08-26 12:45:54.619  1588  1588 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
08-26 12:45:54.619  1588  1588 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 12:45:54.623  1036  1530 D WifiController: battery changed pluggedType: 2
,08-26 12:45:54.626  1588  1588 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 12:45:54.628  6905  7404 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 12:45:54.636  7530  7530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 12:45:54.639  7530  7530 E UEI.SmartControl: Services init done
08-26 12:45:54.639  7530  7530 D UEI.SmartControl: QS Service init finished
,08-26 12:45:54.641  7530  7566 I UEI.SmartControl: Device manager: loading config....
08-26 12:45:54.641  7530  7530 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 12:45:54.641  7530  7530 D UEI.SmartControl: QS Service version code: 201091
08-26 12:45:54.642  7530  7566 D UEI.SmartControl: ----------- loading internal config...
08-26 12:45:54.643  7530  7530 D UEI.SmartControl: Service requested: Control
08-26 12:45:54.649  7530  7530 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 12:45:54.649  7530  7566 E UEI.SmartControl: Loading SETTINGS...
08-26 12:45:54.650  1036  1984 I ActivityManager: Killing 6820:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 12:45:54.658  7530  7566 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 12:45:54.674  7530  7565 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 12:45:54.675  7530  7565 D UEI.SmartControl: -----service ready thread exits
,08-26 12:45:54.694  1036  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 12:45:54.694  1036  1058 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@34abf299 mBinding = false
,08-26 12:45:54.696  1036  1969 W libprocessgroup: failed to open /acct/uid_10112/pid_6820/cgroup.procs: No such file or directory
08-26 12:45:54.698  7530  7530 D UEI.SmartControl: Internal service binding...
,08-26 12:45:54.718  1036  1118 D BluetoothManagerService: Message: 2
,08-26 12:45:54.719  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-26 12:45:54.719  1036  1118 D BluetoothManagerService: Sending off request.
08-26 12:45:54.719  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-26 12:45:54.719  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 12:45:54.719  6905  7502 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 12:45:54.720  6905  7381 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 12:45:54.720  6905  7381 D BluetoothAdapterProperties: Setting state to 13
08-26 12:45:54.720  6905  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 12:45:54.721  6905  7381 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 12:45:54.721  6905  7381 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 12:45:54.722  1036  1118 D BluetoothManagerService: Message: 60
08-26 12:45:54.722  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 12:45:54.722  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 12:45:54.724  6905  7385 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:45:54.724  6905  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 12:45:54.726  6905  7505 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:54.726  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:54.727  6905  7504 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 12:45:54.727  6905  7504 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:54.727  6905  7504 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 12:45:54.727  6905  7504 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 12:45:54.727  6905  7504 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 12:45:54.727  6905  7504 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 12:45:54.727  6905  7504 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 12:45:54.727  6905  7504 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 12:45:54.727  6905  7515 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:54.728  6905  7517 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:54.728  6905  7519 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 12:45:54.730  6905  7381 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 12:45:54.731  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 12:45:54.731  6905  7451 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 12:45:54.732  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:54.732  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 12:45:54.732  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:54.733  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:54.733  6905  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:54.733  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-26 12:45:54.733  6905  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:54.733  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:54.733  6905  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 12:45:54.733  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 12:45:54.733  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 12:45:54.733  6905  7451 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-26 12:45:54.738  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 12:45:54.738  6905  6905 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:54.739  6905  6905 D BluetoothMapService: STATE_TURNING_OFF
08-26 12:45:54.739  6905  6905 V BluetoothMapService: Handler(): got msg=4
08-26 12:45:54.739  6905  6905 D BluetoothMapService: MAP Service closeService in
08-26 12:45:54.739  6905  6905 D BluetoothMapMasInstance: MAP Service shutdown
08-26 12:45:54.739  6905  6905 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 12:45:54.739  6905  6905 V BluetoothMapService: MAP Service closeService out
08-26 12:45:54.740  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:54.740  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:54.740  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:54.740  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:54.740  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:54.740  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:54.740  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:54.740  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:54.740  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:54.742  6905  6905 V BtOppService: Receiver DISABLED_ACTION 
08-26 12:45:54.742  6905  6905 I BtOppRfcommListener: stopping Accept Thread
08-26 12:45:54.742  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:54.742  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:54.743  6905  6905 V BtOppRfcommListener: close mBtServerSocket
08-26 12:45:54.746  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:54.747  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:45:54.747  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:45:54.747  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:45:54.747  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:45:54.747  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 12:45:54.747  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:45:54.747  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:45:54.747  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:45:54.747  6905  6905 V BtOppRfcommListener: waiting for thread to terminate
,08-26 12:45:54.747  6905  7515 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 12:45:54.748  6905  6905 V BtOppRfcommListener: done waiting for thread to terminate
08-26 12:45:54.749  6770  6770 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-26 12:45:54.751  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 12:45:54.751  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:45:54.754  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:54.758  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:54.758  6770  6770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 12:45:54.759  6905  6905 V BtOppService: onDestroy
08-26 12:45:54.909  1036  1058 I art     : Explicit concurrent mark sweep GC freed 93751(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 4.109ms total 147.929ms
,08-26 12:45:54.914  6905  6905 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 12:45:54.914  6905  6905 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 12:45:54.914  6905  6905 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:54.914  6905  6905 V BluetoothPbapReceiver: ***********state = 13
,08-26 12:45:54.916  6770  6770 D DockEventReceiver: finishStartingService: stopping service
08-26 12:45:54.916  6905  6905 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 12:45:54.917  6905  6905 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:54.917  6905  6905 V BluetoothPbapService: state: 13
08-26 12:45:54.917  6905  6905 V BluetoothPbapService: Pbap Service closeService in
08-26 12:45:54.920  2152  2152 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:45:54.921  6770  6770 D BluetoothPbap: Proxy object disconnected
08-26 12:45:54.921  6770  6770 D PbapServerProfile: Bluetooth service disconnected
08-26 12:45:54.922  6905  6905 V BluetoothPbapService: successfully stopped pbap service
08-26 12:45:54.922  6905  6905 V BluetoothPbapService: Pbap Service closeService out
08-26 12:45:54.922  6905  6905 V BluetoothPbapService: Pbap Service onDestroy
08-26 12:45:54.922  6905  6905 V BluetoothPbapService: Pbap Service closeService in
08-26 12:45:54.922  6905  6905 V BluetoothPbapService: Pbap Service closeService out
08-26 12:45:54.922  6905  6905 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-26 12:45:54.934  6770  6770 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 12:45:54.938  6770  6770 D BluetoothPermissionRequest: onReceive
08-26 12:45:54.938  6770  6770 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 12:45:54.943  6770  6770 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 12:45:54.948  6905  6905 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 12:45:54.948  6905  6905 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 12:45:54.949  6905  6905 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-26 12:45:54.952  6905  6905 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 12:45:54.952  6905  6905 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 12:45:54.953  6905  6905 V BluetoothFtpService: Ftp Service onStartCommand
,08-26 12:45:54.953  6905  6905 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:54.954  6905  6905 V BluetoothFtpService: Ftp Service closeService
08-26 12:45:54.954  6905  6905 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 12:45:54.955  6905  6905 V BluetoothFtpService: successfully stopped ftp service
08-26 12:45:54.955  6905  6905 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 12:45:54.955  6905  6905 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 12:45:54.955  6905  6905 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 12:45:54.956  6905  6905 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:54.956  6905  6905 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 12:45:54.956  6905  6905 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 12:45:54.957  6905  6905 V BluetoothFtpService: Ftp Service onDestroy
08-26 12:45:54.957  6905  6905 V BluetoothFtpService: Ftp Service closeService
08-26 12:45:54.963  6905  6905 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:54.964  6905  6905 V BluetoothSapService: state: 13
08-26 12:45:54.964  6905  6905 V BluetoothSapService: Stopping SAP server process
08-26 12:45:54.965  6905  6905 V BluetoothSapService: Sap Service closeSapService in
08-26 12:45:54.965  6905  6905 V BluetoothSapService: Close listen Socket : 
08-26 12:45:54.965  6905  6905 V BluetoothSapService: Close rfcomm Socket : 
08-26 12:45:54.965  6905  6905 V BluetoothSapService: Close sapd  Socket : 
08-26 12:45:54.967  6905  6905 V BluetoothSapService: Sap Service closeSapService out
,08-26 12:45:54.968  6905  6905 V BluetoothSapService: Sap Service onDestroy
,08-26 12:45:54.968  6905  6905 V BluetoothSapService: Sap Service closeSapService in
,08-26 12:45:54.968  6905  6905 V BluetoothSapService: Close listen Socket : 
,08-26 12:45:54.968  6905  6905 V BluetoothSapService: Close rfcomm Socket : 
,08-26 12:45:54.968  6905  6905 V BluetoothSapService: Close sapd  Socket : 
,08-26 12:45:54.969  6905  6905 V BluetoothSapService: Sap Service closeSapService out
,08-26 12:45:55.650  6905  7385 D bt_hci_bdroid: cleanup,
,08-26 12:45:55.665  6905  7453 I bt_lpm  : LPM is already off!!!
08-26 12:45:55.665  6905  7480 I bt_userial_mct: exiting userial_read_thread
08-26 12:45:55.665  6905  7480 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 12:45:55.666  6905  7451 W bt-btif : ag scb idx 1 not allocated
08-26 12:45:55.666  6905  7451 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 12:45:55.666  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:55.666  6905  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:55.666  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 12:45:55.666  6905  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:55.666  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:55.666  6905  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 12:45:55.667  6905  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 12:45:55.667  6905  7451 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 12:45:55.668  6905  7385 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 12:45:55.669  6905  7453 I bt_vendor: hw_epilog_process
08-26 12:45:55.669  6905  7385 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 12:45:55.669  6905  7385 D bt_userial_mct: userial_close
08-26 12:45:55.669  6905  7385 E bt_userial_mct: pthread_join() FAILED result:3
08-26 12:45:55.669  6905  7385 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 12:45:55.674  6905  7385 D bt_hci_bdroid: set_power 0
08-26 12:45:55.674  6905  7385 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 12:45:55.674  6905  7385 I bt_vendor: bluetooth satus is on
08-26 12:45:55.674  6905  7385 I bt_vendor: bt-vendor : resetting BT status
08-26 12:45:55.674  6905  7385 I bt_vendor: Starting hciattach daemon
08-26 12:45:55.674  6905  7385 I bt_vendor: try to set false
08-26 12:45:55.675  6905  7385 I bt_vendor: Starting hciattach daemon
,08-26 12:45:55.675  6905  7385 I bt_vendor: try to set false
08-26 12:45:55.682  6905  7385 I bt_vendor: cleanup
08-26 12:45:55.683  6905  7451 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 12:45:55.683  6905  7385 I GKI_LINUX: GKI_exit_task 0 done
08-26 12:45:55.683  6905  7385 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 12:45:55.685  6905  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 12:45:55.688  6905  6905 D HeadsetService: Received stop request...Stopping profile...
,08-26 12:45:55.691  6905  6905 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 12:45:55.691  6905  6905 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 12:45:55.691  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:55.693  6905  7404 D HeadsetStateMachine: Exit Disconnected: -1
08-26 12:45:55.695  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:55.695  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:55.695  1841  1841 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:55.696  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-26 12:45:55.696  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 12:45:55.697  6905  6905 D HeadsetStateMachine: Unbinding service...
08-26 12:45:55.698  6905  6905 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 12:45:55.698  6905  6905 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 12:45:55.699  6905  6905 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 12:45:55.699  6905  6905 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 12:45:55.699  6905  6905 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 12:45:55.699  6905  6905 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 12:45:55.699  6905  6905 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 12:45:55.704  6905  6905 D A2dpService: Received stop request...Stopping profile...
,08-26 12:45:55.708  6905  7438 D A2dpStateMachine: Exit Disconnected: -1
08-26 12:45:55.711  6905  6905 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 12:45:55.713  6905  7381 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 12:45:55.714  6905  6905 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 12:45:55.714  6905  6905 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 12:45:55.715  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:55.716  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-26 12:45:55.716  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 12:45:55.717  6905  6905 D HidService: Received stop request...Stopping profile...
08-26 12:45:55.717  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
,08-26 12:45:55.723  6905  6905 D HealthService: Received stop request...Stopping profile...
08-26 12:45:55.723  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:55.725  6905  6905 D PanService: Received stop request...Stopping profile...
08-26 12:45:55.725  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:55.726  6905  6905 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 12:45:55.727  6905  6905 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 12:45:55.727  6905  6905 D BtGatt.GattService: stop()
08-26 12:45:55.727  6905  6905 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 12:45:55.728  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:55.730  6905  6905 D BluetoothMapService: Received stop request...Stopping profile...
08-26 12:45:55.730  6905  6905 D BluetoothMapService: stop()
,08-26 12:45:55.733  6905  6905 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 12:45:55.733  6905  6905 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 12:45:55.734  6905  6905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77a043b
08-26 12:45:55.735  6905  6905 I BluetoothA2dpServiceJni: cleanupNative
08-26 12:45:55.735  6905  7439 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 12:45:55.736  6905  6905 I GKI_LINUX: GKI_exit_task 2 done
08-26 12:45:55.736  6905  6905 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 12:45:55.736  6905  6905 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 12:45:55.736  6905  6905 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 12:45:55.737  6905  6905 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 12:45:55.737  6905  6905 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 12:45:55.737  6905  6905 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 12:45:55.737  6905  6905 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 12:45:55.737  6905  6905 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 12:45:55.740  6905  6905 V BluetoothMapService: Handler(): got msg=4
08-26 12:45:55.740  6905  6905 D BluetoothMapService: MAP Service closeService in
08-26 12:45:55.740  6905  6905 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 12:45:55.740  6905  6905 V BluetoothMapService: MAP Service closeService out
08-26 12:45:55.741  6905  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 12:45:55.741  6905  7381 D BluetoothAdapterProperties: Setting state to 10
08-26 12:45:55.741  6905  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 12:45:55.741  6905  6905 D BluetoothMapService: cleanup()
08-26 12:45:55.742  6905  6905 D BluetoothMapService: MAP Service closeService in
08-26 12:45:55.742  6905  6905 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 12:45:55.742  6905  6905 V BluetoothMapService: MAP Service closeService out
,08-26 12:45:55.746  1036  1118 D BluetoothManagerService: Message: 60
08-26 12:45:55.746  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 12:45:55.746  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 12:45:55.748  1841  1857 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:55.749  6905  7381 I BluetoothAdapterState: Entering OffState
08-26 12:45:55.750  6770  6786 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:55.751  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:55.751  6770  6786 D BluetoothPan: onBluetoothStateChange on: false
08-26 12:45:55.752  6770  6786 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 12:45:55.752  6770  6786 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 12:45:55.753  6770  6786 D BluetoothMap: onBluetoothStateChange: up=false
08-26 12:45:55.754  1841  1856 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 12:45:55.756  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 12:45:55.757  6770  6786 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 12:45:55.758  1841  2428 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 12:45:55.759  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 12:45:55.759  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 12:45:55.761  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 12:45:55.761  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 12:45:55.761  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@34abf299 mBinding = false
08-26 12:45:55.762  1036  1118 D BluetoothManagerService: Sending unbind request.
08-26 12:45:55.767  6905  7385 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 12:45:55.769  6905  6905 I GKI_LINUX: GKI_exit_task 1 done
08-26 12:45:55.769  6905  6905 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 12:45:55.769  6905  6905 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 12:45:55.770  6905  6905 I art     : --- WEIRD: removing null entry 248
08-26 12:45:55.770  6905  6905 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 12:45:55.770  6905  6905 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 12:45:55.771  6905  6905 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 12:45:55.772  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 12:45:55.774  6905  6905 I art     : System.exit called, status: 0
08-26 12:45:55.774  6905  6905 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 12:45:55.793   325   325 V AudioFlinger: 6905 died, releasing its sessions
08-26 12:45:55.793   325   325 V AudioFlinger:  pid 1841 @ 0
08-26 12:45:55.793   325   325 V AudioFlinger:  pid 3421 @ 1
08-26 12:45:55.793   325   325 V AudioFlinger:  pid 3421 @ 2
,08-26 12:45:55.797  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-26 12:45:55.797  1928  2091 D LGBluetoothAPIService: Message: 101
08-26 12:45:55.797  1928  2091 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-26 12:45:55.798  1928  2091 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-26 12:45:55.798  1928  2091 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-26 12:45:55.800  6770  6770 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 12:45:55.804  1036  1906 I ActivityManager: Process com.android.bluetooth (pid 6905) has died
08-26 12:45:55.804  1036  1906 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-26 12:45:55.804  1036  1906 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-26 12:45:55.818  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:55.820  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 12:45:55.820  1928  2091 D LGBluetoothAPIService: Message: 2
08-26 12:45:55.820  1928  2091 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,08-26 12:45:55.826  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:55.827  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:45:55.830  6770  6770 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 12:45:55.830  6770  6770 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 12:45:55.832  6770  6770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 12:45:55.832  1588  1588 D BluetoothAdapter: 648204653: getState() :  mService = null. Returning STATE_OFF
08-26 12:45:55.832  1588  1588 D BluetoothAdapter: 648204653: getState() :  mService = null. Returning STATE_OFF
,08-26 12:45:55.876  1036  1059 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7601 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 12:45:55.877  6770  6770 D DockEventReceiver: finishStartingService: stopping service
,08-26 12:45:55.968  7601  7601 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 12:45:55.969  7601  7601 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 12:45:55.969  7601  7601 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 12:45:55.970  7601  7601 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 12:45:55.992  7601  7601 D BluetoothAdapterApp: Loading JNI Library
,08-26 12:45:56.027  7601  7601 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2ce5fc3 Instance Count = 1
,08-26 12:45:56.033  7601  7601 D BluetoothAdapterApp: onCreate
08-26 12:45:56.060  7601  7601 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 12:45:56.060  7601  7601 D ProfileConfigQcom: Adding HeadsetService
,08-26 12:45:56.060  7601  7601 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 12:45:56.060  7601  7601 D ProfileConfigQcom: Adding A2dpService
08-26 12:45:56.061  7601  7601 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 12:45:56.061  7601  7601 D ProfileConfigQcom: Adding HidService
08-26 12:45:56.061  7601  7601 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 12:45:56.061  7601  7601 D ProfileConfigQcom: Adding HealthService
08-26 12:45:56.061  7601  7601 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 12:45:56.062  7601  7601 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 12:45:56.062  7601  7601 D ProfileConfigQcom: Adding PanService
08-26 12:45:56.063  7601  7601 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 12:45:56.063  7601  7601 D ProfileConfigQcom: Adding GattService
08-26 12:45:56.064  7601  7601 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 12:45:56.064  7601  7601 D ProfileConfigQcom: Adding BluetoothMapService
08-26 12:45:56.064  7601  7601 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 12:45:56.065  7601  7601 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 12:45:56.066  7601  7601 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:56.066  7601  7601 V BluetoothPbapReceiver: ***********state = 10
,08-26 12:45:56.067  7601  7601 V LGMDMManagerInternal: Create singleton instance
08-26 12:45:56.156  2152  2152 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 12:45:56.169  6770  6770 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 12:45:56.171  7601  7601 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 12:45:56.171  7601  7601 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 12:45:56.182  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 12:45:56.184  1928  2091 D LGBluetoothAPIService: Message: 100
08-26 12:45:56.184  1928  2091 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-26 12:45:56.190  6770  6770 D BluetoothPermissionRequest: onReceive
,08-26 12:45:56.194  6770  6770 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 12:45:56.194  6770  6770 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 12:45:56.196  6770  6770 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 12:45:56.202  7601  7601 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 12:45:56.207  7601  7601 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:56.210  7601  7601 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-26 12:45:56.210  7601  7601 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-26 12:45:56.211  7601  7601 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 12:45:56.212  7601  7601 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:45:56.212  7601  7601 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 12:45:56.216  6840  6840 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 12:45:57.711  1036  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 12:45:57.719  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:45:57.719  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:45:57.733  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 12:45:57.813  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 12:45:57.822  1036  1036 D administrator: Handling package changes for user 0
08-26 12:45:57.827  1036  1103 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7642 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 12:45:57.832  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 12:45:57.833  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-26 12:45:57.856  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 12:45:57.888  7642  7642 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 12:45:57.949  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-26 12:45:57.949  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 12:45:57.965  7642  7642 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 12:45:57.966  7642  7642 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 12:45:57.987  1036  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 12:45:57.993  1036  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 12:45:58.000  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 12:45:58.001  2456  2456 V GmsNetworkLocationProvi: DISABLE
,08-26 12:45:58.031  1036  1101 D LocationProviderProxy: applying state to connected service
,08-26 12:45:58.033  2456  2456 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-26 12:45:58.093  7642  7675 I Babel   : MmsConfig: mnc/mcc: 0/0
08-26 12:45:58.094  7642  7675 I Babel   : MmsConfig.loadMmsSettings
08-26 12:45:58.095  7642  7675 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 12:45:58.095  7642  7675 I Babel   : MmsConfig.loadFromDatabase
,08-26 12:45:58.110  7642  7675 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 12:45:58.110  7642  7675 I Babel   : MmsConfig.loadFromResources
08-26 12:45:58.112  7642  7675 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 12:45:58.113  7642  7675 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 12:45:58.114  7642  7642 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 12:45:58.135  1805  7678 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 12:45:58.135  1805  7678 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-26 12:45:58.139  6964  6964 I AppUp4:CustModeStarterReceiver: onReceive
08-26 12:45:58.143  6964  6964 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23f98635
08-26 12:45:58.143  6964  6964 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 12:45:58.143  6964  6964 D AppUp4:CustFacade: isPhone : true
08-26 12:45:58.144  6964  6964 D AppUp4:CustModeStarterReceiver: begin check event
08-26 12:45:58.144  6964  6964 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 12:45:58.146  1805  4707 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-26 12:45:58.147  7642  7673 W AudioCapabilities: Unsupported mime audio/evrc
08-26 12:45:58.148  7642  7673 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 12:45:58.151  7642  7673 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 12:45:58.173  7642  7673 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-26 12:45:58.190  1036  1906 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7681 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-26 12:45:58.190  7642  7673 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 12:45:58.193  7642  7673 W AudioCapabilities: Unsupported mime audio/evrc
08-26 12:45:58.197  1036  1906 I ActivityManager: Killing 6791:com.lge.sync/1000 (adj 15): empty #17
08-26 12:45:58.206  7642  7673 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 12:45:58.208  7642  7673 W VideoCapabilities: Unsupported mime video/divx
08-26 12:45:58.210  7642  7673 W VideoCapabilities: Unsupported mime video/divx311
08-26 12:45:58.211  1036  1530 D WifiService: Client connection lost with reason: 4
08-26 12:45:58.212  7642  7673 W VideoCapabilities: Unsupported mime video/divx4
08-26 12:45:58.217  7642  7673 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-26 12:45:58.231  7642  7673 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 12:45:58.234  7642  7673 W AudioCapabilities: Unsupported mime audio/eac3
,08-26 12:45:58.235  7642  7673 W AudioCapabilities: Unsupported mime audio/ac3
08-26 12:45:58.235  7642  7673 W AudioCapabilities: Unsupported mime audio/g726
08-26 12:45:58.236  7642  7673 W AudioCapabilities: Unsupported mime audio/wma-voice
08-26 12:45:58.237  7642  7673 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 12:45:58.238  7642  7673 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 12:45:58.239  7642  7673 W VideoCapabilities: Unsupported mime video/theora
08-26 12:45:58.241  7642  7673 W VideoCapabilities: Unsupported mime video/mjpg
08-26 12:45:58.326  1036  1933 W libprocessgroup: failed to open /acct/uid_1000/pid_6791/cgroup.procs: No such file or directory
,08-26 12:45:58.369  7681  7681 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 12:45:58.370  7681  7681 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 12:45:58.370  7681  7681 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 12:45:58.371  7681  7681 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 12:45:58.372  7681  7681 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-26 12:45:58.431  7681  7681 I SystemConfig: BUILD Country: EU
,08-26 12:45:58.431  7681  7681 I SystemConfig: BUILD Operator: OPEN
,08-26 12:45:58.472  1036  1969 I ActivityManager: Killing 7008:com.lge.email/u0a23 (adj 15): empty #17
,08-26 12:45:58.623  1036  1059 W libprocessgroup: failed to open /acct/uid_10023/pid_7008/cgroup.procs: No such file or directory
,08-26 12:45:58.633  7681  7702 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 12:45:58.633  7681  7702 I SystemConfig: existFile = false
08-26 12:45:58.634  7681  7702 I SystemConfig: canReadFile = false
08-26 12:45:58.634  7681  7702 I SystemConfig: systemFeature RCS result false
08-26 12:45:58.634  7681  7702 D SystemConfig: refreshRcsSupport() :false
08-26 12:45:58.676  1036  1969 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7704 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 12:45:58.712  1036  1531 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-26 12:45:58.722  7704  7704 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 12:45:58.722  7704  7704 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 12:45:58.722  7704  7704 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 12:45:58.723  7704  7704 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 12:45:58.846  7704  7704 I AppConfig: Total System Memory = 2995761152
,08-26 12:45:58.858  7704  7704 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-26 12:45:58.924  1036  2038 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7723 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 12:45:58.925  1036  2038 I ActivityManager: Killing 6865:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-26 12:45:58.986  1036  2002 W libprocessgroup: failed to open /acct/uid_10026/pid_6865/cgroup.procs: No such file or directory
,08-26 12:45:59.175  7723  7723 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 12:45:59.271  7723  7723 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 12:45:59.271  7723  7723 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 12:45:59.333  7723  7723 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 12:45:59.355  7723  7723 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 12:45:59.356  7723  7723 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 12:45:59.373  7723  7723 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 12:45:59.374  7723  7723 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 12:45:59.392  1036  1765 I ActivityManager: Killing 6394:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-26 12:45:59.477  1036  2002 W libprocessgroup: failed to open /acct/uid_1000/pid_6394/cgroup.procs: No such file or directory
,08-26 12:45:59.505  4558  7763 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-26 12:45:59.555  1036  1059 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7764 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 12:45:59.561  2840  5802 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 12:45:59.564  2840  5802 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@25336dda on behalf of 7723
,08-26 12:45:59.602  7723  7723 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-26 12:45:59.616  7764  7764 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-26 12:45:59.616  7723  7723 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 12:45:59.635  7530  7567 D UEI.SmartControl: Internal timer expired: 1
08-26 12:45:59.635  7530  7567 D UEI.SmartControl: unbind internal service
,08-26 12:45:59.637  7530  7530 D UEI.SmartControl: Service.onUnbind: IControl
08-26 12:45:59.638  7764  7764 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-26 12:45:59.638  7764  7764 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-26 12:45:59.638  7764  7764 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 12:45:59.638  7764  7764 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-26 12:45:59.638  7764  7764 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-26 12:45:59.638  7764  7764 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-26 12:45:59.638  7530  7530 D UEI.SmartControl: Service.onDestroy
08-26 12:45:59.639  7530  7530 D UEI.SmartControl: Lock is in USE false
08-26 12:45:59.639  7530  7530 D UEI.SmartControl: unbind internal service
08-26 12:45:59.640  7530  7530 D serial_port: close(fd = 25)
08-26 12:45:59.647  7530  7530 I UEI.SmartControl: Serial port is closed.
08-26 12:45:59.648  7530  7530 I UEI.SmartControl: Serial port is closed.
08-26 12:45:59.648  7530  7530 D UEI.SmartControl: Blaster closed
08-26 12:45:59.648  7530  7530 D UEI.SmartControl: Shut down QS...
08-26 12:45:59.648  7530  7530 D UEI.SmartControl: Stopping QS lib
08-26 12:45:59.648  7530  7530 D UEI.SmartControl: QS lib stop result = true
08-26 12:45:59.648  7530  7530 D UEI.SmartControl: Stopped QS lib
08-26 12:45:59.649  7530  7530 D UEI.SmartControl: Stopped file observer...
08-26 12:45:59.649  7530  7530 D UEI.SmartControl: QS shutdown complete
,08-26 12:45:59.663  1036  1059 I ActivityManager: Killing 7039:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-26 12:45:59.693  1036  1969 W libprocessgroup: failed to open /acct/uid_10046/pid_7039/cgroup.procs: No such file or directory
,08-26 12:45:59.930  1036  1984 V SIM_STK : Menu title from STK is T-Mobile
,08-26 12:45:59.958  4558  7763 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 453 ms] updated apps [took 453 ms] 
,08-26 12:46:00.001  1036  1372 D PowerManagerServiceEx: acquireWakeLockInternal: lock=667211624, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-26 12:46:00.039  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-26 12:46:00.042  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 12:46:00.042  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-26 12:46:00.043  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
08-26 12:46:00.045  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 12:46:00.045  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-26 12:46:00.047  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-26 12:46:00.048  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 12:46:00.056  1036  1103 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7803 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 12:46:00.104  2629  2629 D [Concierge]Service: onStartCommand(). Type : 9
,08-26 12:46:00.159  7803  7803 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 12:46:00.185  7803  7803 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 12:46:00.222  7803  7803 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-26 12:46:00.222  7803  7803 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 12:46:00.222  7803  7803 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 12:46:00.223  7803  7803 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 12:46:00.224  7803  7803 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-26 12:46:00.228  7803  7803 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-26 12:46:00.234  7803  7803 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 12:46:00.242  7803  7803 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-26 12:46:00.242  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1529
08-26 12:46:00.245  7803  7803 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 12:46:00.247  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=667211624 [*alarm*], flags=0x0
,08-26 12:46:00.250  7803  7803 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 12:46:00.251  7803  7803 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 12:46:00.252  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 12:46:00.253  7803  7803 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-26 12:46:00.290  7803  7803 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 12:46:00.291  7803  7803 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 12:46:00.300  7803  7803 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-26 12:46:00.302  7803  7803 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 12:46:00.302  7803  7803 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 12:46:00.302  7803  7803 V SoundPool: doLoad: loading sample sampleID=1
08-26 12:46:00.302  7803  7823 V SoundPool: Start decode
,08-26 12:46:00.302  7803  7823 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 12:46:00.304   325  2151 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 12:46:00.304   325  2151 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 12:46:00.304   325  2151 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 12:46:00.304   325  2151 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,08-26 12:46:00.304   325  2151 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 12:46:00.304   325  2151 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 12:46:00.305   325  2151 V MediaPlayerService: player type = 3
08-26 12:46:00.305   325  2151 V AwesomePlayer: AwesomePlayer create()
08-26 12:46:00.305  7803  7803 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 12:46:00.306   325  2151 V AwesomePlayer: reset_l() 
08-26 12:46:00.306   325  2151 V AwesomePlayer: cancelPlayerEvents
08-26 12:46:00.306   325  2151 V AwesomePlayer: setAudioSink() 
08-26 12:46:00.306   325  2151 V AwesomePlayer: reset_l() 
08-26 12:46:00.306   325  2151 V AudioCache: notify(0xb5474980, 8, 0, 0)
08-26 12:46:00.307   325  2151 V AudioCache: ignored
08-26 12:46:00.307   325  2151 V AwesomePlayer: cancelPlayerEvents
08-26 12:46:00.307   325  2151 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 12:46:00.307   325  2151 V AwesomePlayer: setDataSource_l dataSource
08-26 12:46:00.307   325  2151 V LGParserOSAL: SniffLGParser start
08-26 12:46:00.307   325  2151 V LGParserOSAL: MainType:5, SubType=0
08-26 12:46:00.307   325  2151 V LGParserOSAL: #### check Mime : application/ogg
,08-26 12:46:00.307   325  2151 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 12:46:00.308   325  2151 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 12:46:00.314  7530  7530 D UEI.SmartControl: QS Service created
08-26 12:46:00.338  7530  7530 I UEI.SmartControl: Service initServices...
08-26 12:46:00.339  7530  7530 D UEI.SmartControl: QS start get config
,08-26 12:46:00.346  7803  7803 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 12:46:00.348  7803  7803 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 12:46:00.349  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 12:46:00.366   325  2151 V LGParserOSAL: supported mime: application/ogg
08-26 12:46:00.366   325  2151 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 12:46:00.366   325  2151 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 12:46:00.366   325  2151 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 12:46:00.366   325  2151 V AwesomePlayer: AudioTrack Setting
08-26 12:46:00.366   325  2151 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 12:46:00.366   325  2151 V AwesomePlayer: setAudioSource() 
,08-26 12:46:00.366   325  2151 V MediaPlayerService: prepare
08-26 12:46:00.367   325  2151 V AwesomePlayer: prepareAsync_l() 
08-26 12:46:00.367   325  2151 V MediaPlayerService: wait for prepare
08-26 12:46:00.367   325  7824 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 12:46:00.367   325  7824 V AwesomePlayer: initAudioDecoder() 
08-26 12:46:00.367   325  7824 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 12:46:00.367   325  7824 V AudioSystem: isOffloadSupported()
08-26 12:46:00.367   325  7824 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 12:46:00.367   325  7824 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 12:46:00.367   325  7824 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 12:46:00.367   325  7824 V AwesomePlayer: getUseOffload() = 0 
08-26 12:46:00.367   325  7824 V OMXCodec: OMXCodec::Create
08-26 12:46:00.367   325  7824 V OMXCodec: findMatchingCodecs()
08-26 12:46:00.367   325  7824 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 12:46:00.368   325  7824 V OMXCodec: matchingCodecs.size()=1
08-26 12:46:00.368   325  7824 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 12:46:00.373   325  7824 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 12:46:00.373   325  7824 V LGCodecAdapter: LG Codec Adapter start
08-26 12:46:00.373   325  7824 V OMXCodec: OMXCodec Createtor
08-26 12:46:00.373   325  7824 V OMXCodec: setComponentRole
08-26 12:46:00.373   325  7824 V OMXCodec: configureCodec protected=0
08-26 12:46:00.373   325  7824 V LGCodecAdapter: called getLGCodecSpecificData
08-26 12:46:00.373   325  7824 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 12:46:00.373   325  7824 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 12:46:00.373   325  7824 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 12:46:00.373   325  7824 V LGCodecOSAL: Not support LGCodec
08-26 12:46:00.373   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-26 12:46:00.373   325  7824 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 12:46:00.373   325  7824 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 12:46:00.373   325  7824 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 12:46:00.373   325  7824 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 12:46:00.373   325  7824 V AudioSystem: isOffloadSupported()
08-26 12:46:00.374   325  7824 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 12:46:00.374   325  7824 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 12:46:00.374   325  7824 V OMXCodec: init()
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 12:46:00.374   325  7824 V OMXCodec: allocateBuffers
08-26 12:46:00.374   325  7824 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-26 12:46:00.374   325  7824 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-26 12:46:00.374   325  7824 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-26 12:46:00.374   325  7824 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 12:46:00.375   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 12:46:00.375   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 12:46:00.375   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 12:46:00.375   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 12:46:00.375   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 12:46:00.375   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 12:46:00.375   325  7824 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 12:46:00.375   325  7824 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 12:46:00.375   325  7824 V AudioCache: notify(0xb5474980, 5, 0, 0)
08-26 12:46:00.375   325  7824 V AudioCache: ignored
08-26 12:46:00.375   325  7824 V AudioCache: notify(0xb5474980, 1, 0, 0)
08-26 12:46:00.375   325  7824 V AudioCache: prepared
08-26 12:46:00.375   325  2151 V AudioCache: wait - success
08-26 12:46:00.375   325  2151 V MediaPlayerService: start
08-26 12:46:00.375   325  2151 V AwesomePlayer: play_l() 
08-26 12:46:00.375   325  2151 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 12:46:00.375   325  2151 V AwesomePlayer: createAudioPlayer_l
08-26 12:46:00.375   325  2151 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 12:46:00.3,75   325  2151 V AwesomePlayer: startAudioPlayer_l() 
08-26 12:46:00.375   325  2151 D AudioPlayer: start of Playback, useOffload 0
08-26 12:46:00.375   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 12:46:00.375   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 12:46:00.378   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 12:46:00.378   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 12:46:00.378   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 12:46:00.378   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 12:46:00.378   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 12:46:00.378   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 12:46:00.378   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-26 12:46:00.378   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 12:46:00.379  7803  7803 V LGMDMManager: Create singleton instance
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 12:46:00.379   325  7826 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fe380 on output port,
,08-26 12:46:00.379   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 12:46:00.380   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 12:46:00.380   325  2151 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 12:46:00.380   325  2151 V AudioCache: notify(0xb5474980, 6, 0, 0)
08-26 12:46:00.380   325  2151 V AudioCache: ignored
08-26 12:46:00.381   325  2151 V MediaPlayerService: wait for playback complete
08-26 12:46:00.386   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.386   325  7827 V AudioCache: memcpy(0xac300000, 0xb17f9000, 4096)
08-26 12:46:00.388   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.388   325  7827 V AudioCache: memcpy(0xac301000, 0xb17f9000, 4096),
08-26 12:46:00.388   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.388   325  7827 V AudioCache: memcpy(0xac302000, 0xb17f9000, 4096)
08-26 12:46:00.389   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.389   325  7827 V AudioCache: memcpy(0xac303000, 0xb17f9000, 4096)
08-26 12:46:00.391   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.391   325  7827 V AudioCache: memcpy(0xac304000, 0xb17f9000, 4096)
08-26 12:46:00.391   325  7827 V AudioCache: write(0xb17f9000, 4096)
,08-26 12:46:00.391   325  7827 V AudioCache: memcpy(0xac305000, 0xb17f9000, 4096)
08-26 12:46:00.391   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.391   325  7827 V AudioCache: memcpy(0xac306000, 0xb17f9000, 4096)
08-26 12:46:00.391   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.391   325  7827 V AudioCache: memcpy(0xac307000, 0xb17f9000, 4096)
08-26 12:46:00.393   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.393   325  7827 V AudioCache: memcpy(0xac308000, 0xb17f9000, 4096)
08-26 12:46:00.394   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.394   325  7827 V AudioCache: memcpy(0xac309000, 0xb17f9000, 4096)
,08-26 12:46:00.394   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.394   325  7827 V AudioCache: memcpy(0xac30a000, 0xb17f9000, 4096)
08-26 12:46:00.396   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.396   325  7827 V AudioCache: memcpy(0xac30b000, 0xb17f9000, 4096)
08-26 12:46:00.400   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.400   325  7827 V AudioCache: memcpy(0xac30c000, 0xb17f9000, 4096)
08-26 12:46:00.401   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.401   325  7827 V AudioCache: memcpy(0xac30d000, 0xb17f9000, 4096)
,08-26 12:46:00.401   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.401   325  7827 V AudioCache: memcpy(0xac30e000, 0xb17f9000, 4096)
08-26 12:46:00.401   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.401   325  7827 V AudioCache: memcpy(0xac30f000, 0xb17f9000, 4096)
08-26 12:46:00.402   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.402   325  7827 V AudioCache: memcpy(0xac310000, 0xb17f9000, 4096)
08-26 12:46:00.402   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.402   325  7827 V AudioCache: memcpy(0xac311000, 0xb17f9000, 4096)
,08-26 12:46:00.403   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.403   325  7827 V AudioCache: memcpy(0xac312000, 0xb17f9000, 4096)
08-26 12:46:00.404   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.404   325  7827 V AudioCache: memcpy(0xac313000, 0xb17f9000, 4096)
08-26 12:46:00.404   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.404   325  7827 V AudioCache: memcpy(0xac314000, 0xb17f9000, 4096)
08-26 12:46:00.404   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.404   325  7827 V AudioCache: memcpy(0xac315000, 0xb17f9000, 4096)
08-26 12:46:00.405   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.405   325  7827 V AudioCache: memcpy(0xac316000, 0xb17f9000, 4096)
08-26 12:46:00.405   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.405   325  7827 V AudioCache: memcpy(0xac317000, 0xb17f9000, 4096)
08-26 12:46:00.406   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.406   325  7827 V AudioCache: memcpy(0xac318000, 0xb17f9000, 4096)
08-26 12:46:00.406   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.406   325  7827 V AudioCache: memcpy(0xac319000, 0xb17f9000, 4096)
08-26 12:46:00.406   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.406   325  7827 V AudioCache: memcpy(0xac31a000, 0xb17f9000, 4096)
08-26 12:46:00.407   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.407   325  7827 V AudioCache: memcpy(0xac31b000, 0xb17f9000, 4096)
08-26 12:46:00.407   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.407   325  7827 V AudioCache: memcpy(0xac31c000, 0xb17f9000, 4096)
08-26 12:46:00.408   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.408   325  7827 V AudioCache: memcpy(0xac31d000, 0xb17f9000, 4096)
08-26 12:46:00.408   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.408   325  7827 V AudioCache: memcpy(0xac31e000, 0xb17f9000, 4096)
08-26 12:46:00.408   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.408   325  7827 V AudioCache: memcpy(0xac31f000, 0xb17f9000, 4096)
08-26 12:46:00.409   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.409   325  7827 V AudioCache: memcpy(0xac320000, 0xb17f9000, 4096)
08-26 12:46:00.409   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.409   325  7827 V AudioCache: memcpy(0xac321000, 0xb17f9000, 4096)
08-26 12:46:00.410   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.410   325  7827 V AudioCache: memcpy(0xac322000, 0xb17f9000, 4096)
08-26 12:46:00.410   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.410   325  7827 V AudioCache: memcpy(0xac323000, 0xb17f9000, 4096)
08-26 12:46:00.411   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.411   325  7827 V AudioCache: memcpy(0xac324000, 0xb17f9000, 4096)
08-26 12:46:00.413   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.413   325  7827 V AudioCache: memcpy(0xac325000, 0xb17f9000, 4096)
08-26 12:46:00.414   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.414   325  7827 V AudioCache: memcpy(0xac326000, 0xb17f9000, 4096)
08-26 12:46:00.415   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.415   325  7827 V AudioCache: memcpy(0xac327000, 0xb17f9000, 4096)
,08-26 12:46:00.416   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.416   325  7827 V AudioCache: memcpy(0xac328000, 0xb17f9000, 4096)
08-26 12:46:00.416   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.416   325  7827 V AudioCache: memcpy(0xac329000, 0xb17f9000, 4096)
08-26 12:46:00.417   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.417   325  7827 V AudioCache: memcpy(0xac32a000, 0xb17f9000, 4096)
08-26 12:46:00.418   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.418   325  7827 V AudioCache: memcpy(0xac32b000, 0xb17f9000, 4096)
08-26 12:46:00.419   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.419   325  7827 V AudioCache: memcpy(0xac32c000, 0xb17f9000, 4096)
08-26 12:46:00.419   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.419   325  7827 V AudioCache: memcpy(0xac32d000, 0xb17f9000, 4096)
08-26 12:46:00.420   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.420   325  7827 V AudioCache: memcpy(0xac32e000, 0xb17f9000, 4096)
08-26 12:46:00.420   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.420   325  7827 V AudioCache: memcpy(0xac32f000, 0xb17f9000, 4096)
08-26 12:46:00.421   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.421   325  7827 V AudioCache: memcpy(0xac330000, 0xb17f9000, 4096)
08-26 12:46:00.422   325  7827 V AudioCache: write(0xb17f9000, 4096)
08-26 12:46:00.422   325  7827 V AudioCache: memcpy(0xac331000, 0xb17f9000, 4096)
08-26 12:46:00.422   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 12:46:00.422   325  7827 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 12:46:00.422   325  7827 V AwesomePlayer: postAudioEOS() 
08-26 12:46:00.422   325  7827 V AudioCache: write(0xb17f9000, 280)
08-26 12:46:00.422   325  7827 V AudioCache: memcpy(0xac332000, 0xb17f9000, 280)
08-26 12:46:00.424   325  7824 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 12:46:00.424   325  7824 V AwesomePlayer: onStreamDone
08-26 12:46:00.424   325  7824 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 12:46:00.424   325  7824 V AudioCache: notify(0xb5474980, 2, 0, 0)
08-26 12:46:00.424   325  7824 V AudioCache: playback complete
08-26 12:46:00.424   325  7824 V AwesomePlayer: pause_l() 
08-26 12:46:00.424   325  7824 V AudioCache: notify(0xb5474980, 7, 0, 0)
08-26 12:46:00.424   325  7824 V AudioCache: ignored
08-26 12:46:00.424   325  7824 V AwesomePlayer: cancelPlayerEvents
08-26 12:46:00.424   325  2151 V AudioCache: wait - success
08-26 12:46:00.424   325  2151 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 12:46:00.424   325  7824 D AudioPlayer: Pause Playback at 1068125
08-26 12:46:00.425   325  2151 V AwesomePlayer: reset_l() 
08-26 12:46:00.425   325  2151 V AudioCache: notify(0xb5474980, 8, 0, 0)
08-26 12:46:00.425   325  2151 V AudioCache: ignored
08-26 12:46:00.425   325  2151 V AwesomePlayer: cancelPlayerEvents
08-26 12:46:00.425   325  2151 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 12:46:00.425   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 12:46:00.425   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 12:46:00.425   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 12:46:00.425   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57fe380 on port 1
08-26 12:46:00.425   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 12:46:00.426   325  7826 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 12:46:00.426   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 12:46:00.426   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 12:46:00.426   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 12:46:00.427   325  2151 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 12:46:00.427   325  2151 D AudioPlayer: AudioPlayer releasing audio source
08-26 12:46:00.427   325  2151 D AudioPlayer: AudioPlayer done releasing audio source
08-26 12:46:00.427   325  2151 V AwesomePlayer: reset_l() 
08-26 12:46:00.427   325  2151 V AwesomePlayer: cancelPlayerEvents
08-26 12:46:00.427   325  2151 V AwesomePlayer: ~AwesomePlayer call
08-26 12:46:00.427   325  2151 V AwesomePlayer: reset_l() 
08-26 12:46:00.427   325  2151 V AwesomePlayer: cancelPlayerEvents
08-26 12:46:00.427  7803  7823 V SoundPool: close(31)
08-26 12:46:00.427  7803  7823 V SoundPool: pointer = 0x9fe82000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 12:46:00.457  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 12:46:00.458  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 12:46:00.459  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4958
,08-26 12:46:00.711  7530  7530 I UEI.SmartControl: Supports setup maps: true
,08-26 12:46:00.714  7530  7530 D UEI.SmartControl: QS start statue = true Error code = 0,
,08-26 12:46:00.714  7530  7530 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-26 12:46:00.714  7530  7530 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-26 12:46:00.714  7530  7530 I UEI.SmartControl: ### init IR Blaster...
08-26 12:46:00.718  7530  7530 D serial_port: Configuring serial port
08-26 12:46:00.718  7530  7530 E UEI.SmartControl: UEIBLaster setting for 616
08-26 12:46:00.718  7530  7530 I UEI.SmartControl: Setting serial record hearder size = 2
,08-26 12:46:00.718  7530  7530 I UEI.SmartControl: configuring settings for MAXQ616
08-26 12:46:00.718  7530  7530 I UEI.SmartControl: Get version...
08-26 12:46:00.735  7530  7843 D UEI.SmartControl: serial port data available: 21
,08-26 12:46:00.760  7530  7530 D UEI.SmartControl: MAXQ616 A2-X4 software.,
,08-26 12:46:00.760  7530  7530 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 12:46:00.760  7530  7530 I UEI.SmartControl: QS saving settings...
08-26 12:46:00.771  7530  7530 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 12:46:00.788  7530  7843 D UEI.SmartControl: serial port data available: 4
,08-26 12:46:00.821  7530  7849 I UEI.SmartControl: Device manager: loading config....
,08-26 12:46:00.845  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:00.845  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38c752ff added. We now have 6 listener(s)
08-26 12:46:00.845  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:00.847  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:00.847  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@186238cc added. We now have 7 listener(s)
08-26 12:46:00.847  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:00.848  6571  6698 I System.out: IsBluetoothEnabled
08-26 12:46:00.850  1036  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:00.850  1036  1760 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-26 12:46:00.854  1036  1118 D BluetoothManagerService: Message: 2
08-26 12:46:00.858  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:00.859  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:00.859  1036  1642 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-26 12:46:00.864  7530  7849 D UEI.SmartControl: ----------- loading internal config...
,08-26 12:46:00.885  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 12:46:00.885  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 12:46:00.885  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-26 12:46:00.888  1036  1118 D BluetoothManagerService: Message: 1
08-26 12:46:00.888  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 12:46:00.906  7530  7530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 12:46:00.948  7530  7530 E UEI.SmartControl: Services init done
08-26 12:46:00.948  7530  7530 D UEI.SmartControl: QS Service init finished
,08-26 12:46:00.954  1036  1118 D BluetoothManagerService: Message: 20
08-26 12:46:00.954  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e5c3024:true
08-26 12:46:00.955  7601  7601 D BluetoothAdapterState: make
08-26 12:46:00.956  7530  7530 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 12:46:00.956  7530  7530 D UEI.SmartControl: QS Service version code: 201091
08-26 12:46:00.960  7601  7601 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 12:46:00.960  7601  7601 I bluedroid-qcom: init
,08-26 12:46:00.963  7601  7857 I BluetoothAdapterState: Entering OffState
08-26 12:46:00.965  7601  7601 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 12:46:00.965  7601  7601 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 12:46:00.965  7601  7601 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 12:46:00.965  7601  7601 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 12:46:00.965  7601  7601 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 12:46:00.967  7601  7601 I bluedroid-qcom: get_profile_interface socket
08-26 12:46:00.967  7601  7601 I bluedroid-qcom: get_profile_interface map_client
08-26 12:46:00.968  7601  7861 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 12:46:00.971  7601  7861 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 12:46:00.955  7860  7860 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:00.955  7860  7860 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 12:46:00.982  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 12:46:00.982  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 12:46:00.984  7601  7861 D BluetoothAdapterProperties: Name is: G3
08-26 12:46:00.988  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 12:46:00.988  7860  7860 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 12:46:00.988  7860  7860 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 12:46:00.992  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 12:46:00.992  1036  1118 D BluetoothManagerService: Message: 40
08-26 12:46:00.992  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 12:46:00.993  7601  7617 I bluedroid-qcom: config_hci_snoop_log
08-26 12:46:00.994  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 12:46:00.998  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 12:46:00.998  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 12:46:01.015  7601  7857 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 12:46:01.015  7601  7857 D BluetoothAdapterProperties: Setting state to 11
,08-26 12:46:01.016  7601  7857 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-26 12:46:01.018  7601  7857 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 12:46:01.021  7601  7857 D BluetoothBondStateMachine: make
08-26 12:46:01.022  1036  1118 D BluetoothManagerService: Message: 60
08-26 12:46:01.022  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 12:46:01.022  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 12:46:01.023  7530  7530 D UEI.SmartControl: Service requested: Control
08-26 12:46:01.024  7530  7849 E UEI.SmartControl: Loading SETTINGS...
08-26 12:46:01.026  7530  7849 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 12:46:01.028  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:01.028  6770  6770 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 12:46:01.028  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 12:46:01.029  7530  7530 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 12:46:01.031  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:01.033  7803  7803 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 12:46:01.033  7530  7530 D UEI.SmartControl: Internal service binding...
08-26 12:46:01.034  7530  7546 I UEI.SmartControl: ------ IControl API: 11
08-26 12:46:01.034  7530  7546 D UEI.SmartControl: File observer start...
08-26 12:46:01.034  7601  7601 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 12:46:01.034  7601  7601 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:01.034  7530  7546 E UEI.SmartControl: IR Port is disabled: false
08-26 12:46:01.034  7601  7601 V BluetoothPbapReceiver: ***********state = 11
08-26 12:46:01.034  7530  7546 D UEI.SmartControl: Starting file observer...
08-26 12:46:01.035  7530  7546 I UEI.SmartControl: Registering callback...
08-26 12:46:01.035  7530  7545 I UEI.SmartControl: ------ IControl API: 19
08-26 12:46:01.035  7530  7545 I UEI.SmartControl: Registering Services Ready callback...
08-26 12:46:01.036  7530  7545 I UEI.SmartControl: Notify client services are ready...
08-26 12:46:01.036  7803  7818 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 12:46:01.037  2152  2152 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:46:01.039  7860  7860 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 12:46:01.039  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 12:46:01.041  7601  7857 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:01.041  7601  7870 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 12:46:01.041  7601  7857 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 12:46:01.042  7601  7857 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:01.042  7601  7857 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 12:46:01.042  7601  7857 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 12:46:01.044  6770  6770 D BluetoothPermissionRequest: onReceive
08-26 12:46:01.045  7803  7821 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 12:46:01.045  7803  7821 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-26 12:46:01.046  6770  6770 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 12:46:01.047  7530  7848 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 12:46:01.048  7803  7803 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 12:46:01.049  7803  7803 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 12:46:01.049  7530  7546 I UEI.SmartControl: ------ IControl API: 8
08-26 12:46:01.050  7803  7819 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 12:46:01.050  7803  7821 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 12:46:01.050  7530  7848 D UEI.SmartControl: -----service ready thread exits
08-26 12:46:01.051  7601  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:46:01.053  7601  7601 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:01.054  7601  7601 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 12:46:01.054  7601  7601 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 12:46:01.054  7601  7601 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 12:46:01.054  7601  7601 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:01.054  7601  7601 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 12:46:01.055  7803  7821 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 12:46:01.057  7803  7803 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 12:46:01.057  7803  7803 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 12:46:01.058  7803  7803 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 12:46:01.058  7803  7803 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-26 12:46:01.062  7601  7601 D HeadsetService: Received start request. Starting profile...
08-26 12:46:01.062  7601  7601 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 12:46:01.062  7601  7601 D LGBluetoothHfpAdapter: Version 1.6
08-26 12:46:01.062  7601  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:46:01.064  7601  7601 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 12:46:01.065  7601  7601 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 12:46:01.065  7601  7601 D HeadsetStateMachine: make
08-26 12:46:01.067  7601  7857 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 12:46:01.068  7803  7803 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 12:46:01.069  7803  7803 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-26 12:46:01.074  7601  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:46:01.075  7803  7803 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 12:46:01.080  7601  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:46:01.080  7803  7803 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-26 12:46:01.081  7803  7803 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-26 12:46:01.083  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 12:46:01.087  7803  7803 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 12:46:01.087  7601  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:46:01.087  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 12:46:01.087  7601  7601 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:46:01.087  7601  7601 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 12:46:01.090  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 12:46:01.092  7601  7601 D HeadsetStateMachine: max_hf_connections = 1
08-26 12:46:01.092  7601  7601 I bluedroid-qcom: get_profile_interface handsfree
08-26 12:46:01.093  7601  7601 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 12:46:01.093  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 12:46:01.093   325  1370 V AudioPolicyService: registerClient() client 0xb558a460, uid 1002
08-26 12:46:01.094  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 12:46:01.094   325  1370 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 12:46:01.094   325  1370 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 12:46:01.094   325  1370 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 12:46:01.094  7601  7601 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 12:46:01.094  7601  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-26 12:46:01.094  7803  7803 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472208361094]
08-26 12:46:01.094   325  1770 V AudioFlinger: registerClient() client 0xb1433118, pid 7601
,08-26 12:46:01.094   325  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:46:01.094   325  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:46:01.095  1588  2112 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:46:01.095  1588  2112 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:46:01.095  7601  7616 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:46:01.095  1036  1946 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:46:01.095  7803  7803 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 12:46:01.095  1036  1946 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:46:01.096  1841  1856 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:46:01.096  1841  1856 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:46:01.096  3421  3440 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 12:46:01.096  3421  3440 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 12:46:01.096   325  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:46:01.096   325  1366 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:46:01.096  1841  2428 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:46:01.096  1588  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:46:01.096  1841  2428 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:46:01.096  1588  1607 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:46:01.097  3421  3442 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:46:01.097  3421  3442 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:46:01.097  1036  2021 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:46:01.097  1036  2021 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 12:46:01.097  7601  7616 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 12:46:01.097  7601  7616 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 12:46:01.097  7601  7616 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 12:46:01.099  1036  2021 I ActivityManager: Killing 7058:com.android.chrome/u0a57 (adj 15): empty #17
08-26 12:46:01.099  7601  7601 V ToneGenerator: Create Track: 0xb4928080
08-26 12:46:01.099  7601  7601 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 12:46:01.099  7601  7601 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 12:46:01.099   325  2151 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 12:46:01.099   325  2151 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 12:46:01.099   325  2151 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 12:46:01.099   325  2151 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 12:46:01.100   325  1370 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 12:46:01.100   325   325 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 12:46:01.100   325   325 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 12:46:01.100   325   325 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 12:46:01.100   325   325 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 12:46:01.100  7601  7601 V AudioSystem: getLatency() output 2, latency 50
08-26 12:46:01.100  7601  7601 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 12:46:01.100  7601  7601 V AudioTrack: createTrack_l() output 2 afLatency 50,
08-26 12:46:01.100   325  1770 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 12:46:01.100   325  1770 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 12:46:01.100   325  1770 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 12:46:01.100   325  1770 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 12:46:01.100   325  1770 V AudioFlinger: createTrack() lSessionId: 23
08-26 12:46:01.101  7601  7601 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 12:46:01.101   325  1770 V AudioFlinger: acquiring 23 from 7601, for 7601
08-26 12:46:01.101   325  1770 V AudioFlinger:  added new entry for 23
08-26 12:46:01.101  7601  7601 V ToneGenerator: ToneGenerator INIT OK, time: 134678
08-26 12:46:01.101  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:01.102  7601  7879 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 12:46:01.102  7601  7879 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 12:46:01.102  7601  7879 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 12:46:01.103  7601  7879 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 12:46:01.103   325  1371 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7601
08-26 12:46:01.104   325  1371 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 12:46:01.104   325  1371 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 12:46:01.104   325  1371 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 12:46:01.104   325  1371 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 12:46:01.104   325  1371 V voice   : voice_set_parameters: exit with code(0)
08-26 12:46:01.104   325  1371 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 12:46:01.104   325  1371 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 12:46:01.104   325  1371 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 12:46:01.104   325  1371 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 12:46:01.104   325  1371 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 12:46:01.104   325  1371 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 12:46:01.104  7601  7879 V ToneGenerator: ToneGenerator destructor
08-26 12:46:01.104  7601  7879 V ToneGenerator: stopTone
08-26 12:46:01.104  7601  7879 V ToneGenerator: Delete Track: 0xb4928080
08-26 12:46:01.105  7601  7879 V AudioTrack: ~AudioTrack, releasing session id from 7601 on behalf of 7601
08-26 12:46:01.105   325   325 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 12:46:01.105   325   325 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 12:46:01.105   325  2151 V AudioFlinger: releasing 23 from 7601 for 7601
08-26 12:46:01.105   325  2151 V AudioFlinger:  decremented refcount to 0
08-26 12:46:01.105   325  2151 V AudioFlinger: purging stale effects
08-26 12:46:01.105  1036  2002 W Process : Unable to open /proc/7882/status
08-26 12:46:01.105   325  1272 V AudioPolicyService: AudioCommandThread() waking up
08-26 12:46:01.105   325  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 12:46:01.105   325  1272 V AudioPolicyManager: releaseOutput() 2
08-26 12:46:01.105   325  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 12:46:01.105   325   325 V AudioFlinger: PlaybackThread::Track destructor
08-26 12:46:01.105   325   325 V AudioFlinger: removeClient_l() pid 7601, calling pid 325
08-26 12:46:01.111  7601  7857 V LGMDMManager: Create singleton instance
,08-26 12:46:01.113  7601  7857 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 12:46:01.116  7803  7881 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-26 12:46:01.134  1036  1059 W libprocessgroup: failed to open /acct/uid_10057/pid_7058/cgroup.procs: No such file or directory
08-26 12:46:01.134  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
,08-26 12:46:01.135  7601  7601 D A2dpService: Received start request. Starting profile...
08-26 12:46:01.136  7601  7601 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 12:46:01.136  7601  7601 V Avrcp   : make
08-26 12:46:01.136  7601  7601 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 12:46:01.136  7601  7601 I bluedroid-qcom: get_profile_interface avrcp
08-26 12:46:01.140  7803  7803 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-26 12:46:01.141  7803  7803 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 12:46:01.141  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 12:46:01.141  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 12:46:01.142  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 12:46:01.142  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 12:46:01.142  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 12:46:01.145  7601  7601 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 12:46:01.146  7601  7601 E AudioManager: No RCC entry present to update
08-26 12:46:01.146  7601  7601 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 12:46:01.148  7601  7601 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 12:46:01.149  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 12:46:01.149  7601  7601 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 12:46:01.150  7803  7803 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 12:46:01.153  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 12:46:01.274  1036  1760 V SIM_STK : Menu title from STK is T-Mobile
08-26 12:46:01.274  1036  1760 V SIM_STK : Menu title from STK is T-Mobile
,08-26 12:46:01.429  1036  1058 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 12:46:01.443  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 12:46:01.449  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-26 12:46:01.450  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-26 12:46:01.450  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 12:46:01.450  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 12:46:01.450  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 12:46:01.450  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 12:46:01.450  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 12:46:01.450  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-26 12:46:01.450  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED),
08-26 12:46:01.451  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-26 12:46:01.451  7601  7601 I BluetoothA2dpServiceJni: classInitNative
,08-26 12:46:01.451  7601  7601 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 12:46:01.451  7601  7601 D A2dpStateMachine: make
08-26 12:46:01.456  7601  7601 I bluedroid-qcom: get_profile_interface a2dp,
08-26 12:46:01.456  7601  7893 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-26 12:46:01.471  7601  7601 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 12:46:01.471  7601  7601 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 12:46:01.473  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:01.474  7601  7601 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 12:46:01.477  7601  7601 D HidService: Received start request. Starting profile...
08-26 12:46:01.477  7601  7601 I bluedroid-qcom: get_profile_interface hidhost
08-26 12:46:01.477  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:01.478  7601  7892 D A2dpStateMachine: Enter Disconnected: -2
08-26 12:46:01.478  7601  7601 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 12:46:01.480  7601  7601 D HealthService: Received start request. Starting profile...
08-26 12:46:01.482  7601  7601 I bluedroid-qcom: get_profile_interface health
08-26 12:46:01.483  7601  7601 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 12:46:01.483  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:01.484  7601  7601 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 12:46:01.486  7601  7601 D PanService: Received start request. Starting profile...
08-26 12:46:01.487  7601  7601 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 12:46:01.487  7601  7601 I bluedroid-qcom: get_profile_interface pan
08-26 12:46:01.495  7601  7601 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 12:46:01.495  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:01.496  7601  7601 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 12:46:01.503  7601  7601 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 12:46:01.505  7601  7601 D BtGatt.GattService: Received start request. Starting profile...
08-26 12:46:01.505  7601  7601 D BtGatt.GattService: start()
08-26 12:46:01.505  7601  7601 I bluedroid-qcom: get_profile_interface gatt
08-26 12:46:01.506  7601  7601 D BtGatt.AdvertiseManager: advertise manager created
08-26 12:46:01.513  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:01.514  7601  7601 D HeadsetStateMachine: Proxy object connected
08-26 12:46:01.515  7601  7601 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 12:46:01.515  7601  7601 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-26 12:46:01.518  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:01.518  7601  7601 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 12:46:01.520  7601  7601 V BluetoothMapService: BluetoothMapBinder()
08-26 12:46:01.520  7601  7601 D BluetoothMapService: Received start request. Starting profile...
08-26 12:46:01.521  7601  7601 D BluetoothMapService: start()
08-26 12:46:01.524  7601  7601 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 12:46:01.524  7601  7601 D BluetoothMapEmailAppObserver: createReceiver()
08-26 12:46:01.525  7601  7601 D BluetoothMapEmailAppObserver: initObservers()
08-26 12:46:01.526  7601  7601 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 12:46:01.535  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
,08-26 12:46:01.539  7601  7601 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 12:46:01.541  7601  7879 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 12:46:01.541  7601  7879 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 12:46:01.541  7601  7879 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 12:46:01.545  7601  7601 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 12:46:01.548  7601  7601 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 12:46:01.551  7601  7601 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 12:46:01.552  7601  7601 V PanService: [BTUI] SIM Extra State :ABSENT
,08-26 12:46:01.555  7601  7601 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 12:46:01.559  7601  7601 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 12:46:01.559  7601  7601 V BluetoothMapService: Handler(): got msg=1
08-26 12:46:01.560  7601  7857 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 12:46:01.560  7601  7857 I bluedroid-qcom: enable
08-26 12:46:01.561  7601  7857 I bt_hci_bdroid: init
08-26 12:46:01.561  7601  7900 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 12:46:01.561  7601  7900 I bt-btu  : btu_task pending for preload complete event
,08-26 12:46:01.566  7601  7857 I bt_vendor: bt-vendor : init
08-26 12:46:01.566  7601  7857 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 12:46:01.566  7601  7857 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 12:46:01.566  7601  7857 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 12:46:01.566  7601  7857 D bt_userial_mct: userial_init
08-26 12:46:01.567  7601  7857 D bt_hci_bdroid: set_power 1
08-26 12:46:01.567  7601  7857 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 12:46:01.567  7601  7857 I bt_vendor: Starting hciattach daemon
08-26 12:46:01.567  7601  7857 I bt_vendor: try to set true
08-26 12:46:01.555  7903  7903 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:01.555  7903  7903 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:01.598  7904  7904 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 12:46:01.686  7910  7910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 12:46:01.700  7911  7911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 12:46:01.726  7913  7913 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 12:46:01.738  7914  7914 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 12:46:01.750  7915  7915 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 12:46:01.763  7916  7916 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 12:46:01.784  7918  7918 I libmdmdetect: ESOC framework not supported
08-26 12:46:01.785  7918  7918 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 12:46:01.794  7918  7918 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-26 12:46:01.794  7918  7918 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 12:46:01.794  7918  7918 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 12:46:01.794  7918  7918 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 12:46:01.794  7918  7918 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 12:46:01.794  7918  7918 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 12:46:01.794  7918  7918 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 12:46:01.837  7918  7919 E QC-QMI  : qmi_client [7918] 15: failed to locate client data
,08-26 12:46:01.838   441   441 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-26 12:46:01.838   441   441 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-26 12:46:01.888  7920  7920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 12:46:01.904  7921  7921 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 12:46:01.920  7601  7857 I bt_vendor: bluetooth satus is on
,08-26 12:46:01.920  7601  7857 D bt_hci_bdroid: preload
08-26 12:46:01.921  7601  7902 D bt_userial_mct: userial_open(port:0)
08-26 12:46:01.921  7601  7902 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 12:46:01.925  7601  7902 I bt_vendor: Done intiailizing UART
08-26 12:46:01.929  7601  7902 I bt_vendor: Done intiailizing UART
08-26 12:46:01.929  7601  7902 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-26 12:46:01.930  7601  7902 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 12:46:01.930  7601  7900 I bt-btu  : btu_task received preload complete event
08-26 12:46:01.930  7601  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 12:46:01.930  7601  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 12:46:01.933  7601  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 12:46:01.933  7601  7923 D bt_userial_mct: Entering userial_read_thread()
08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_BTM,
08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_GAP,
08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_PAN,
,08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 12:46:01.937  7601  7900 I         : BTE_InitTraceLevels -- TRC_BTIF,
,08-26 12:46:02.043  7601  7900 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 12:46:02.044  7601  7900 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa018e061 
,08-26 12:46:02.044  7601  7900 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa018e061 
,08-26 12:46:02.091  7601  7861 E bt-btif : Calling BTA_HhEnable
08-26 12:46:02.091  7601  7861 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 12:46:02.091  7601  7861 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 12:46:02.096  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-26 12:46:02.096  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-26 12:46:02.097  7601  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 12:46:02.097  7601  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 12:46:02.097  7601  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 12:46:02.097  7601  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 12:46:02.097  7601  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 12:46:02.098  7601  7861 D BluetoothAdapterProperties: Name is: G3
08-26 12:46:02.099  7601  7861 D BluetoothAdapterProperties: Scan Mode:20
08-26 12:46:02.099  7601  7861 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 12:46:02.100  7601  7861 D bt_hci_bdroid: postload
08-26 12:46:02.100  7601  7902 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 12:46:02.100  7601  7902 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 12:46:02.101  7601  7861 D bte_conf: Device ID record 1 : primary
,08-26 12:46:02.101  7601  7861 D bte_conf:   vendorId            = 00c4
08-26 12:46:02.102  7601  7900 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 12:46:02.102  7601  7902 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 12:46:02.101  7601  7861 D bte_conf:   vendorIdSource      = 0001
08-26 12:46:02.102  7601  7861 D bte_conf:   product             = 13a1
08-26 12:46:02.102  7601  7861 D bte_conf:   version             = 1000
08-26 12:46:02.102  7601  7861 D bte_conf:   clientExecutableURL = 
08-26 12:46:02.102  7601  7861 D bte_conf:   serviceDescription  = 
08-26 12:46:02.102  7601  7861 D bte_conf:   documentationURL    = 
08-26 12:46:02.102  7601  7861 D bte_conf: bte_load_did_conf no section named DID2.
08-26 12:46:02.106  7601  7857 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 12:46:02.106  7601  7857 D BluetoothAdapterProperties: ScanMode =  20
,08-26 12:46:02.106  7601  7857 D BluetoothAdapterProperties: State =  11
08-26 12:46:02.106  7601  7857 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,08-26 12:46:02.107  7601  7857 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 12:46:02.107  7601  7857 D BluetoothAdapterProperties: Setting state to 12
08-26 12:46:02.107  7601  7857 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 12:46:02.105  7928  7928 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:02.117  1036  1118 D BluetoothManagerService: Message: 60
08-26 12:46:02.117  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 12:46:02.117  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 12:46:02.118  7601  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:46:02.118  7601  7900 W bt-smp  : Plain text(LSB ~ MSB) = 99 17 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:46:02.118  7601  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = 0f d7 e9 4b 2a 32 73 e9 2d d2 1d 11 72 ce 83 c8 
08-26 12:46:02.119  7601  7902 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 12:46:02.119  7601  7900 W bt-btm  : Stopping oneshot timer
08-26 12:46:02.119  7601  7861 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 12:46:02.119  7601  7861 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 12:46:02.115  7928  7928 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:02.134  7601  7923 E bt_mct  : hci lib postload completed
08-26 12:46:02.139  7601  7857 I BluetoothAdapterState: Entering On State
,08-26 12:46:02.146  1841  2678 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:46:02.162  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:46:02.162  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:02.162  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:46:02.162  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:46:02.162  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:02.162  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:46:02.162  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:46:02.162  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:46:02.169  7601  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:46:02.169  7601  7900 W bt-smp  : Plain text(LSB ~ MSB) = 5c 0f 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:46:02.169  7601  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = 1b 22 2e 5e 21 cb 15 70 03 01 73 31 0e df 86 df 
08-26 12:46:02.169  7601  7900 W bt-btm  : Stopping oneshot timer
08-26 12:46:02.178  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 12:46:02.196  7601  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:46:02.196  7601  7900 W bt-smp  : Plain text(LSB ~ MSB) = 1d 46 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:46:02.196  7601  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = e2 66 1a 9f db 56 6f 83 6a 4c 86 87 a6 d5 ce 11 
,08-26 12:46:02.201  7601  7900 W bt-btm  : Stopping oneshot timer
08-26 12:46:02.211  7601  7857 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 12:46:02.211  7601  7857 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 12:46:02.211  7601  7857 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-26 12:46:02.215  7601  7857 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 12:46:02.216  7601  7857 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 12:46:02.222  7601  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:46:02.222  7601  7900 W bt-smp  : Plain text(LSB ~ MSB) = 29 3b 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:46:02.222  7601  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = bf 9e e2 e2 bd 8c fe 4c 43 8a e9 6a c3 04 86 25 
08-26 12:46:02.232  7601  7900 W bt-btm  : Stopping oneshot timer
,08-26 12:46:02.241  1841  1841 D BluetoothHeadset: Proxy object connected
08-26 12:46:02.246  7601  7900 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 12:46:02.246  7601  7900 W bt-smp  : Plain text(LSB ~ MSB) = d4 e8 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 12:46:02.246  7601  7900 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 15 3c b8 74 dc 0f a8 21 0e 49 10 ac b1 04 f5 
,08-26 12:46:02.249  7601  7900 W bt-btm  : Stopping oneshot timer
,08-26 12:46:02.263  6770  6786 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 12:46:02.270  7601  7861 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 12:46:02.270  7601  7861 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 12:46:02.277  7942  7942 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 12:46:02.281  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:46:02.282  6770  6770 D BluetoothHeadset: Proxy object connected
08-26 12:46:02.282  6770  6770 D HeadsetProfile: Bluetooth service connected
,08-26 12:46:02.283  1036  1036 D BluetoothHeadset: Proxy object connected
08-26 12:46:02.285  6770  6786 D BluetoothPan: onBluetoothStateChange on: true
08-26 12:46:02.285  6770  6786 D BluetoothPan: onBluetoothStateChange call bindService
08-26 12:46:02.288  6770  7487 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 12:46:02.289  6770  6770 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 12:46:02.289  6770  6770 D PanProfile: Bluetooth service connected
08-26 12:46:02.289  6770  6787 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:46:02.291  6770  6786 D BluetoothMap: onBluetoothStateChange: up=true
08-26 12:46:02.292  6770  6770 D BluetoothA2dp: Proxy object connected
08-26 12:46:02.292  6770  6770 D A2dpProfile: Bluetooth service connected
08-26 12:46:02.293  1841  1856 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 12:46:02.297  1841  1841 D BluetoothHeadset: Proxy object connected
08-26 12:46:02.297  6770  6770 D BluetoothMap: Proxy object connected
08-26 12:46:02.297  6770  6770 D MapProfile: Bluetooth service connected
08-26 12:46:02.297  6770  6770 D BluetoothMap: getConnectedDevices()
08-26 12:46:02.297  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 12:46:02.298  1036  1036 D BluetoothA2dp: Proxy object connected
08-26 12:46:02.298  6770  7487 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 12:46:02.298  7601  7616 V BluetoothMapService: getConnectedDevices()
08-26 12:46:02.415  1036  1118 I art     : Explicit concurrent mark sweep GC freed 25842(1274KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.567ms total 114.701ms
,08-26 12:46:02.419  1841  4382 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 12:46:02.420  6770  6770 D BluetoothInputDevice: Proxy object connected
08-26 12:46:02.420  6770  6770 D HidProfile: Bluetooth service connected
08-26 12:46:02.422  1841  1841 D BluetoothHeadset: Proxy object connected
08-26 12:46:02.424  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 12:46:02.425  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 12:46:02.425  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 12:46:02.427  1036  1118 D BluetoothManagerService: Message: 40
08-26 12:46:02.427  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 12:46:02.429  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 12:46:02.429  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 12:46:02.434  1928  2091 D LGBluetoothAPIService: Message: 1
08-26 12:46:02.434  1928  2091 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 12:46:02.434  1928  2091 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-26 12:46:02.435  1928  2091 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 12:46:02.438  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:02.445  7601  7601 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:02.445  7601  7601 D BluetoothMapService: STATE_ON
08-26 12:46:02.445  7601  7601 V BluetoothMapService: Handler(): got msg=1
,08-26 12:46:02.446  7601  7601 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 12:46:02.450  7601  7953 D BluetoothMapMasInstance: MAS initSocket()
08-26 12:46:02.451  7601  7953 D BluetoothMapMasInstance:   masId = 00
08-26 12:46:02.451  7601  7953 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 12:46:02.451  7601  7953 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 12:46:02.451  7601  7953 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 12:46:02.454  1036  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:02.455  7601  7953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:46:02.456  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:02.456  7601  7601 V BluetoothPbapService: Pbap Service onCreate
08-26 12:46:02.456  7601  7601 V BluetoothPbapService: Starting PBAP service
08-26 12:46:02.456  7601  7953 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 12:46:02.457  7601  7601 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 12:46:02.457  7601  7953 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 12:46:02.457  7601  7601 V BluetoothPbapService: Pbap Service onBind
08-26 12:46:02.457  7601  7953 D BluetoothMapMasInstance: Accepting socket connection...
08-26 12:46:02.458  7601  7861 D BluetoothAdapterProperties: Scan Mode:21
08-26 12:46:02.458  7601  7861 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 12:46:02.460  6770  6770 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-26 12:46:02.462  7601  7601 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:02.462  7601  7601 V BluetoothPbapService: state: 12
08-26 12:46:02.462  7601  7601 V BluetoothPbapService: Handler(): got msg=1
08-26 12:46:02.463  6770  6770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 12:46:02.463  7601  7601 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 12:46:02.464  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:02.466  6770  6770 D BluetoothPbap: Proxy object connected
08-26 12:46:02.466  6770  6770 D PbapServerProfile: Bluetooth service connected
08-26 12:46:02.467  7601  7954 V BluetoothPbapService: Pbap Service initSocket
08-26 12:46:02.468  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:02.469  7601  7954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:46:02.470  7601  7601 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 12:46:02.470  7601  7601 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:02.470  7601  7601 V BluetoothPbapReceiver: ***********state = 12
08-26 12:46:02.471  7601  7954 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 12:46:02.471  7601  7954 V BluetoothPbapService: Succeed to create listening socket 
08-26 12:46:02.471  7601  7954 V BluetoothPbapService: Accepting socket connection...
,08-26 12:46:02.474  2152  2152 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 12:46:02.474  2152  2152 D c       : Getting all permits...
08-26 12:46:02.474  2152  2152 D a       : Opening database...
08-26 12:46:02.477  2152  2152 D a       : Opening database auth.proximity.permit_store...
08-26 12:46:02.477  6770  6770 D DockEventReceiver: finishStartingService: stopping service
08-26 12:46:02.477  2152  2152 D a       : Closing database...
08-26 12:46:02.486  6770  6770 D BluetoothPermissionRequest: onReceive
08-26 12:46:02.488  6770  6770 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 12:46:02.489  6770  6770 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 12:46:02.493  7601  7601 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 12:46:02.494  7601  7601 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 12:46:02.499  7601  7601 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-26 12:46:02.517  7601  7601 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 12:46:02.518  7601  7601 V BtOppService: onCreate
,08-26 12:46:02.524  7601  7601 V BluetoothOppNotification: send message
,08-26 12:46:02.529  7601  7601 V BtOppService: Starting RfcommListener
,08-26 12:46:02.536  7601  7601 D BluetoothOppPreference: Dumping Names:  
,08-26 12:46:02.536  7601  7601 D BluetoothOppPreference: {}
08-26 12:46:02.536  7601  7601 D BluetoothOppPreference: Dumping Channels:  
08-26 12:46:02.536  7601  7601 D BluetoothOppPreference: {}
08-26 12:46:02.537  7601  7601 V BtOppService: onStartCommand
08-26 12:46:02.538  7601  7961 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 12:46:02.543  7601  7601 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:02.543  7601  7601 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-26 12:46:02.551  7601  7601 V BluetoothOppNotification: new notify threadi!
08-26 12:46:02.552  7601  7601 V BluetoothOppNotification: send delay message
08-26 12:46:02.553  7601  7601 V BtOppService: start RfcommListener
08-26 12:46:02.555  7601  7962 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 12:46:02.557  7601  7601 V BtOppService: RfcommListener started
,08-26 12:46:02.557  7601  7958 V BtOppService: Deleted complete outbound shares, number =  0
,08-26 12:46:02.559  7601  7962 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d20b94 on behalf of 
08-26 12:46:02.560  7601  7963 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 12:46:02.561  7601  7962 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 12:46:02.563  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:02.564  7601  7958 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 12:46:02.564  7601  7963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:46:02.564  7601  7958 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 12:46:02.565  7601  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 12:46:02.566  7601  7963 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 12:46:02.566  7601  7963 V BtOppRfcommListener: Started RFCOMM listener....
08-26 12:46:02.566  7601  7963 I BtOppRfcommListener: Accept thread started.
08-26 12:46:02.566  7601  7963 V BtOppRfcommListener: Accepting connection...
08-26 12:46:02.567  7601  7958 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a1de32 on behalf of 
08-26 12:46:02.567  7601  7962 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 12:46:02.568  7601  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@216e363d on behalf of 
08-26 12:46:02.571  7601  7962 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@234b0783 on behalf of 
08-26 12:46:02.571  7601  7961 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 12:46:02.571  7601  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 12:46:02.572  7601  7962 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-26 12:46:02.574  7601  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@358e4d00 on behalf of 
08-26 12:46:02.575  7601  7961 V BluetoothOppNotification: update too frequent, put in queue
08-26 12:46:02.575  7601  7962 V BluetoothOppNotification: outbound notification was removed.
08-26 12:46:02.576  7601  7962 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 12:46:02.577  7601  7961 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 12:46:02.577  7601  7962 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@370cf939 on behalf of 
08-26 12:46:02.580  7601  7962 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 12:46:02.581  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:02.581  7601  7601 V BluetoothFtpService: Ftp Service onCreate
08-26 12:46:02.581  7601  7601 I BluetoothFtpService: Ftp Service onCreate
08-26 12:46:02.581  7601  7601 V BluetoothFtpService: Ftp Service onStartCommand
08-26 12:46:02.581  7601  7601 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:02.582  7601  7601 V BluetoothFtpService: Starting Listening on sockets
08-26 12:46:02.582  7601  7601 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 12:46:02.582  7601  7601 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 12:46:02.582  7601  7601 V BluetoothSapReceiver: SapReceiver onReceive 
,08-26 12:46:02.582  7601  7601 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 12:46:02.582  7601  7601 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 12:46:02.582  7601  7601 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 12:46:02.585  7601  7601 V BtOppService: ContentObserver received notification
08-26 12:46:02.585  7601  7601 V BtOppService: ContentObserver received notification
08-26 12:46:02.585  7601  7601 V BluetoothFtpService: Handler(): got msg=1
08-26 12:46:02.585  7601  7962 V BluetoothOppNotification: inbound notification was removed.
08-26 12:46:02.586  7601  7601 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 12:46:02.586  7601  7962 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 12:46:02.586  7601  7601 V BluetoothFtpService: Ftp Service initSocket
08-26 12:46:02.587  7601  7962 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e2c98df on behalf of 
08-26 12:46:02.588  7601  7964 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 12:46:02.588  7601  7964 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 12:46:02.590  1036  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:02.590  7601  7964 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b0b392c on behalf of 
08-26 12:46:02.591  7601  7964 V BluetoothOppNotification: update too frequent, put in queue
08-26 12:46:02.591  7601  7601 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:46:02.592  7601  7964 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 12:46:02.599  7601  7601 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,08-26 12:46:02.599  7601  7601 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-26 12:46:02.602  7601  7965 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 12:46:02.620  7601  7601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cdff758
08-26 12:46:02.620  7601  7601 V BluetoothSapService: Sap Service onCreate
08-26 12:46:02.622  7601  7601 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 12:46:02.622  7601  7601 V BluetoothSapService: state: 12
08-26 12:46:02.622  7601  7601 V BluetoothSapService: Starting SAP server process
08-26 12:46:02.615  7966  7966 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:02.615  7966  7966 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 12:46:02.627  7601  7601 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 12:46:02.630  7601  7967 V BluetoothSapService: Sap Service initRfcommSocket
08-26 12:46:02.630  1036  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:02.632  7601  7967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 12:46:02.634  7601  7967 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 12:46:02.635  7601  7967 V BluetoothSapService: Succeed to create listening socket 
08-26 12:46:02.635  7601  7967 V BluetoothSapService: Accepting socket connection...
,08-26 12:46:02.642  7966  7966 V BT_SAP  : Event pipe created,
08-26 12:46:02.642  7966  7966 V BT_SAP  : create_server_socket qcom.sap.server
08-26 12:46:02.642  7966  7966 V BT_SAP  : created socket fd 6
08-26 12:46:02.948  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:46:02.948  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:02.948  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:46:02.948  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 12:46:02.948  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:02.948  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-26 12:46:02.948  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:46:02.948  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:46:02.952  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:46:02.954  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:02.954  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8e88715 added. We now have 8 listener(s)
08-26 12:46:02.954  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:02.957  1036  2038 D WifiServiceImplEx: setWifiEnabled: false pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 12:46:02.958  1036  2038 D WifiService: setWifiEnabled: false pid=6571, uid=10118
08-26 12:46:02.958  1036  2038 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 12:46:02.966  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:02.967  1036  1760 D WifiServiceImplEx: setWifiEnabled: true pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 12:46:02.968  1036  1760 D WifiService: setWifiEnabled: true pid=6571, uid=10118
08-26 12:46:02.968  1036  1760 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 12:46:02.980  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 12:46:02.981  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 12:46:02.981  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 12:46:02.982  1036  1524 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 12:46:02.982  1036  1524 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-26 12:46:02.982  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-26 12:46:02.982  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 12:46:02.982  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 12:46:02.982  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 12:46:02.983  1036  1524 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-26 12:46:02.983  1036  1524 E WifiHW  : unknown target_country: EU , set to default
08-26 12:46:02.983  1036  1524 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 12:46:02.983  1036  1524 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 12:46:02.983  1036  1524 I WifiUtil: gEnableBmps=1
08-26 12:46:03.555  7601  7601 V BluetoothOppNotification: new notify threadi!
08-26 12:46:03.555  7601  7601 V BluetoothOppNotification: send delay message
,08-26 12:46:03.562  7601  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 12:46:03.563  7601  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2288bc18 on behalf of 
,08-26 12:46:03.564  7601  7986 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 12:46:03.566  7601  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 12:46:03.568  7601  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30179671 on behalf of 
08-26 12:46:03.569  7601  7986 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-26 12:46:03.577  7601  7986 V BluetoothOppNotification: outbound notification was removed.
08-26 12:46:03.578  7601  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 12:46:03.579  7601  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3647ac56 on behalf of 
08-26 12:46:03.581  7601  7986 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 12:46:03.583  7601  7986 V BluetoothOppNotification: inbound notification was removed.
08-26 12:46:03.584  7601  7986 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 12:46:03.584  7601  7986 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@138ac4d7 on behalf of 
08-26 12:46:03.687   320   894 D SoftapController: Softap fwReload - Ok
,08-26 12:46:03.795  1036  1524 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (808ms)
,08-26 12:46:03.800   320   894 D CommandListener: Setting iface cfg
08-26 12:46:03.800   320   894 D CommandListener: Trying to bring down wlan0
08-26 12:46:03.801   320   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 12:46:03.803  1036  1524 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 12:46:03.795  8000  8000 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 12:46:03.809  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 12:46:03.809  1036  1118 D Tethering: InitialState.processMessage what=4
08-26 12:46:03.811  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 12:46:03.795  8000  8000 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:03.814  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 12:46:03.814  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 12:46:03.814  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 12:46:03.814  6770  6770 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 12:46:03.814  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 12:46:03.815  6770  6770 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 12:46:03.815  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 12:46:03.815  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 12:46:03.815  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 12:46:03.815  6770  6770 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 12:46:03.815  6770  6770 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 12:46:03.818  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 12:46:03.818  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 12:46:03.818  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 12:46:03.818  6770  6770 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 12:46:03.818  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 12:46:03.819  6770  6770 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 12:46:03.819  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 12:46:03.819  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 12:46:03.819  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 12:46:03.819  6770  6770 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 12:46:03.819  6770  6770 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 12:46:03.833  8000  8000 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 12:46:03.867  8000  8000 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 12:46:03.867  8000  8000 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 12:46:03.904  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 12:46:03.904  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-26 12:46:03.904  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 12:46:03.905  1036  1524 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 12:46:03.905  1036  1524 D WifiMonitor: connecting to supplicant
08-26 12:46:03.908  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:03.909  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 12:46:03.912  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:03.936  8000  8000 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 12:46:03.970  1036  1103 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8006 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-26 12:46:03.970  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-26 12:46:03.977  8000  8000 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-26 12:46:03.983  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-26 12:46:03.985  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 12:46:03.985  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 12:46:03.986  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 12:46:03.986  1036  1524 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 12:46:03.987  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:03.987  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:03.987  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:03.988  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:03.988  1036  1524 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 12:46:03.988  1036  1524 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 12:46:03.989  1036  1524 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 12:46:03.989  1036  1524 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 12:46:03.989  1036  1524 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 12:46:03.990   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 382us total 19.147ms
08-26 12:46:03.990  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:03.990  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 12:46:03.990  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-26 12:46:03.990  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 12:46:03.990  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:03.991  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:03.991  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:03.991  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 12:46:03.993  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:03.994  1036  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 12:46:03.994  1036  8021 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 12:46:03.994  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 12:46:03.994  8000  8000 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-26 12:46:03.995  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 12:46:03.996  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 12:46:03.997  1036  1524 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 12:46:03.997  1036  1524 D WifiNative-wlan0: SET update_config 1: returned true
08-26 12:46:03.997  1036  1524 D WifiConfigStore: Loading config and enabling all networks 
08-26 12:46:03.997  1036  1524 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 12:46:03.998  1036  1524 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 12:46:04.000  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:46:04.000  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:04.000  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:46:04.000  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:04.000  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:04.000  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:46:04.000  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:46:04.000  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 12:46:04.002  1928  1928 D WfdService: Waiting for WifiP2p enabling
08-26 12:46:04.002  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:46:04.005  1036  1524 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 12:46:04.007   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 16.397ms
08-26 12:46:04.009  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 12:46:04.009  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 12:46:04.009  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 12:46:04.009  1036  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 12:46:04.009  1036  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 12:46:04.015  1036  1524 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 12:46:04.015  1036  1524 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 12:46:04.017  1036  1524 D WifiStateMachine: enableVerboseLogging : level 2
08-26 12:46:04.017  1036  1524 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 12:46:04.017  1036  1524 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 12:46:04.018  1036  1524 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-26 12:46:04.018  1036  1524 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 12:46:04.018  1036  1524 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 12:46:04.018  1036  1524 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 12:46:04.018  1036  1524 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 12:46:04.019  1036  1524 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 12:46:04.019  1036  1524 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 12:46:04.019  1036  1524 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 12:46:04.019  1036  1524 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 12:46:04.019  1036  1524 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 12:46:04.019  1036  1524 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 12:46:04.020  1036  1524 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 12:46:04.022   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.387ms
08-26 12:46:04.024  1036  1524 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 12:46:04.024  1036  1524 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 12:46:04.024  1036  1524 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 12:46:04.024  1036  1524 D WifiNative-HAL: Setting external_sim to 1
08-26 12:46:04.024  1036  1524 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 12:46:04.025  1036  1524 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 12:46:04.025  1036  1524 I WifiNative-HAL: startHal
08-26 12:46:04.025  1036  1524 D wifi    : setting scan oui 0xaf6c9fc0
08-26 12:46:04.025  7642  7642 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.025  1928  1928 D WfdsService: Supplicant Connection state is changed : true
08-26 12:46:04.025  1928  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 12:46:04.025  1928  2279 D WfdsService: Set the WFDS Monitor: true
08-26 12:46:04.025  1928  2279 D WfdsMonitor: WfdsMonitorThread create
08-26 12:46:04.026  1928  2279 D WfdsMonitor: WFDS Monitor is created and started
08-26 12:46:04.026  1928  2279 D WfdsService: WiFi: Supplicant connection re-established
08-26 12:46:04.026  1036  1524 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 12:46:04.026  1036  1524 I WifiNative-HAL: startHal
08-26 12:46:04.026  1036  1524 D wifi    : setting scan oui 0xaf6c9fc0
08-26 12:46:04.026  1928  8025 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 12:46:04.026  1036  1524 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 12:46:04.027  1928  8025 E CtrlSupplicant: Succeed to open control connection
08-26 12:46:04.027  1928  8025 E CtrlSupplicant: Succeed to open monitor connection
08-26 12:46:04.027  1928  8025 D WfdsMonitor: Supplicant connection established
08-26 12:46:04.027  1036  1524 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 12:46:04.027  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 12:46:04.027  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 12:46:04.028  1928  2279 D WfdsService: Connected to the supplicant for wfds
08-26 12:46:04.028  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 12:46:04.028  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 12:46:04.028  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 12:46:04.029  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 12:46:04.029  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 12:46:04.029  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 12:46:04.029  1,036  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 12:46:04.029  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 12:46:04.029  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 12:46:04.030  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 12:46:04.030  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 12:46:04.030  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-26 12:46:04.032  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 12:46:04.032  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 12:46:04.032  8000  8000 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 12:46:04.032  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 12:46:04.033  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 12:46:04.033  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 12:46:04.033  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 12:46:04.034  1036  1524 E WifiNative: : [137,595,097 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 12:46:04.034  1036  1524 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 12:46:04.035  1036  1524 D WifiNative-wlan0: RECONNECT: returned true
08-26 12:46:04.035  1036  1524 D WifiNative-wlan0: doString: [STATUS]
08-26 12:46:04.035  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 12:46:04.035  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 12:46:04.036  1036  1524 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 12:46:04.036  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 12:46:04.036  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-26 12:46:04.037  1036  1523 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.037  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 12:46:04.037  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-26 12:46:04.038  1036  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.038  1036  1542 I WifiNative-HAL: startHal
08-26 12:46:04.038  1036  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf6c9fc0
08-26 12:46:04.038  1036  1542 D wifi    : failed to get capabilities : -3
08-26 12:46:04.038  1036  1542 E WifiScanningService: could not get scan capabilities
08-26 12:46:04.038  1036  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.038   320   894 D CommandListener: Setting iface cfg
08-26 12:46:04.038   320   894 D CommandListener: Trying to bring up p2p0
08-26 12:46:04.038  1036  1523 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 12:46:04.038  1036  1523 D LGWifiP2pService: P2pEnablingState
08-26 12:46:04.038  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 12:46:04.038  1036  1523 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.038  1036  1523 D LGWifiP2pService: P2p socket connection successful
08-26 12:46:04.039  1036  1523 D LGWifiP2pService: P2pEnabledState
08-26 12:46:04.039  1036  1523 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 12:46:04.039  1036  1524 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 12:46:04.039  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 12:46:04.039  1036  1523 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 12:46:04.039  1928  1928 D WfdsService: WifiP2pState is changed : true
08-26 12:46:04.040  1036  1523 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 12:46:04.040  1036  1524 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 12:46:04.040  1036  1523 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 12:46:04.040  1928  2279 D WfdsService: Receive the WFDS_ENABLE Method
08-26 12:46:04.040  1928  2279 D WfdsService: Set ,the WFDS Monitor: true
08-26 12:46:04.040  1928  2279 D WfdsService: Connected to the supplicant for wfds
08-26 12:46:04.040  1036  1524 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 12:46:04.040  1928  2279 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 12:46:04.040  8000  8000 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 12:46:04.040  1928  2279 D WfdsService: selectPreferredScanChannel [36]
08-26 12:46:04.040  1928  2279 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 12:46:04.040  1036  1524 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 12:46:04.040  1036  1523 D WifiNative-p2p0: SET device_name G3: returned true
08-26 12:46:04.040  1036  1523 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 12:46:04.040  1036  1523 D LGWifiP2pService: before postfix = G3
08-26 12:46:04.040  1036  1523 D WifiServerServiceExt: postfix byte check : 2
08-26 12:46:04.040  1036  1523 D LGWifiP2pService: after postfix = G3
08-26 12:46:04.041  1036  1523 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 12:46:04.041  1036  1524 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 12:46:04.041  1036  1523 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 12:46:04.041  1036  1524 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 12:46:04.041  1036  1523 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 12:46:04.041  1036  1524 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 12:46:04.041  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 12:46:04.041  8000  8000 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 12:46:04.041  1036  1523 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 12:46:04.041  1036  1523 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 12:46:04.041  1036  1524 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 12:46:04.041  1928  1928 D WfdsService: isConnected: false
08-26 12:46:04.041  1036  1524 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 12:46:04.042  1036  1524 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 12:46:04.042  1036  1524 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 12:46:04.042  8000  8000 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 12:46:04.042  1036  1523 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 12:46:04.042  1036  1523 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 12:46:04.042  1036  1523 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 12:46:04.042  1036  1523 D WifiNative-HAL: p2pGetDeviceAddress
08-26 12:46:04.042  1036  1523 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 12:46:04.042  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=137603  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 12:46:04.042  1036  1523 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 12:46:04.042  1036  1523 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-26 12:46:04.043  1036  1523 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 12:46:04.043  1036  1523 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-26 12:46:04.043  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=137604  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 12:46:04.044  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 12:46:04.044  1036  1524 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 12:46:04.045  1036  1524 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 12:46:04.045  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 12:46:04.045  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.045  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.045  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 12:46:04.047  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 12:46:04.047  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 12:46:04.047  1036  1523 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 12:46:04.047  1928  1928 D WfdsService: Update P2p Interface State: 3
08-26 12:46:04.047  1036  1523 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 12:46:04.048  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:04.048  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:46:04.048  1036  1523 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 12:46:04.048  1036  1523 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 12:46:04.048  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:04.058  1036  1523 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 12:46:04.058  1036  1523 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 12:46:04.059  1036  1523 D LGWifiP2pService: InactiveState
08-26 12:46:04.059  1036  1523 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.059  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.059  1036  1523 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 12:46:04.059  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-26 12:46:04.060  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:46:04.060  1928  8025 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 12:46:04.060  1036  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 12:46:04.060  1036  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:46:04.060  1036  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:46:04.060  1036  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:46:04.060  8000  8000 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 12:46:04.060  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.060  1928  8025 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:46:04.061  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.061  1928  8025 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:46:04.061  1036  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:46:04.061  1036  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.061  1036  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.061  1036  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.061  1036  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:46:04.062  1036  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.062  1036  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.062  1036  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.062  1036  1523 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 12:46:04.062  1036  1523 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.062  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.062  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 12:46:04.063  8000  8000 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:46:04.063  8000  8000 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 12:46:04.063  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.063  1036  1523 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.063  1036  1523 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.064  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.064  1036  1524 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 12:46:04.064  1036  1523 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.064  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.064  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 12:46:04.064  1036  1523 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.064  1928  2279 W WfdsS,ervice: DefaultState - msg [9441285] is not handled
08-26 12:46:04.064  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.064  1036  1523 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.064  1036  1523 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.064  1036  1524 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 12:46:04.064  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.064  1036  1523 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.064  1036  1036 E WifiServerServiceExt: No p2p device connected
08-26 12:46:04.065  1036  1523 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.065  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.065  1036  1524 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 12:46:04.065  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 12:46:04.065  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 12:46:04.065  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:46:04.065  1036  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:46:04.065  1928  8025 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:46:04.065  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 12:46:04.065  1036  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 12:46:04.065  1928  8025 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:46:04.065  8000  8000 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 12:46:04.065  1036  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:46:04.065  1036  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.065  1036  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.065  1036  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.065  1036  8021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 12:46:04.065  1036  8021 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.065  1036  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.065  1036  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 12:46:04.065  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 12:46:04.065  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 12:46:04.065  1036  8021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 12:46:04.065  1036  8021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 12:46:04.066  1036  1524 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 12:46:04.066  1036  1524 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 12:46:04.066  1036  1524 D WifiNative-wlan0: BSS,_FLUSH 0: returned true
08-26 12:46:04.066  1036  1524 D WifiNative-wlan0: doBoolean: SCAN
08-26 12:46:04.066  1036  1524 D WifiNative-wlan0: SCAN: returned false
08-26 12:46:04.067  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137628  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 12:46:04.091  1036  1561 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8030 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 12:46:04.092  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=137653  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 12:46:04.093  1036  1524 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:46:04.093  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.093  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.093  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 12:46:04.093  1036  1524 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:46:04.094  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:04.094  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:46:04.095  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:04.096  1036  1524 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:46:04.097  1036  1524 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:46:04.097  1036  1524 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 12:46:04.098  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:46:04.098  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 12:46:04.098  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:46:04.099  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 12:46:04.100  8006  8028 W FormManager: Network not available. Please check & try again.
08-26 12:46:04.103  8006  8029 V FormManager: Network unavailable.
08-26 12:46:04.105  8006  8029 V FormManager: Network unavailable.
,08-26 12:46:04.119  1036  1946 I ActivityManager: Killing 7079:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-26 12:46:04.139  8030  8030 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 12:46:04.154  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 12:46:04.155  1036  1059 W libprocessgroup: failed to open /acct/uid_10062/pid_7079/cgroup.procs: No such file or directory
08-26 12:46:04.159  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 12:46:04.163  1036  1984 I ActivityManager: Killing 7110:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 12:46:04.194  1036  2021 W libprocessgroup: failed to open /acct/uid_10085/pid_7110/cgroup.procs: No such file or directory
,08-26 12:46:04.223  8030  8030 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 12:46:04.229  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 12:46:04.239  8006  8051 W FormManager: Network not available. Please check & try again.
,08-26 12:46:04.245  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:04.255  8006  8052 V FormManager: Network unavailable.
,08-26 12:46:04.258  8006  8052 V FormManager: Network unavailable.
08-26 12:46:04.274  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 12:46:04.274  4285  4285 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 12:46:04.276  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:46:04.278  4285  4285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 12:46:04.286  4285  8053 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 12:46:04.290  4285  8054 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 12:46:04.290  4285  8054 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 12:46:04.327  1036  1969 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8055 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 12:46:04.517  8055  8055 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 12:46:04.517  8055  8055 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 12:46:04.528  8055  8055 V [BNRBootReceiver]: Boot Receiver Return
,08-26 12:46:04.531  8055  8055 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 12:46:04.569  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 12:46:04.569  8000  8000 E wpa_supplicant: USIM:  scard_init function
08-26 12:46:04.569  1036  8021 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 12:46:04.570  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 12:46:04.570  8000  8000 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 12:46:04.570  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-26 12:46:04.570  1036  8021 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 12:46:04.570  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 12:46:04.570  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 12:46:04.572  1036  1524 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,08-26 12:46:04.576  1036  1524 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 12:46:04.578  1036  1524 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 12:46:04.579  1036  1524 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 12:46:04.579  1036  1524 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 12:46:04.593  1036  1059 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8079 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 12:46:04.595  1036  1059 I ActivityManager: Killing 7137:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-26 12:46:04.680  8000  8000 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 12:46:04.683  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 12:46:04.683  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-26 12:46:04.684  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 12:46:04.684  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 12:46:04.684  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:46:04.684  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:46:04.693  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:46:04.693  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:46:04.694  8000  8000 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 12:46:04.694  8000  8000 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-26 12:46:04.696  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 12:46:04.697  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 12:46:04.697  1036  8021 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 12:46:04.697  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 12:46:04.697  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 12:46:04.697  1036  8021 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 12:46:04.697  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:46:04.698  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:46:04.812  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138373  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 12:46:04.814  1036  2021 W libprocessgroup: failed to open /acct/uid_10093/pid_7137/cgroup.procs: No such file or directory
,08-26 12:46:04.824  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138385  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 12:46:04.825  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138386  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-26 12:46:04.825  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=138386  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-26 12:46:04.826  1036  1524 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138387
,08-26 12:46:04.827  1036  1524 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138388
08-26 12:46:04.827  1036  1524 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138388
08-26 12:46:04.829  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138390
08-26 12:46:04.830  1036  1524 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138391
08-26 12:46:04.831  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138392  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 12:46:04.836  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 12:46:04.840  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:04.840  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:46:04.845  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 12:46:04.851  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138412  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 12:46:04.851  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 12:46:04.851  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.851  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 12:46:04.857  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.857  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.857  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 12:46:04.857  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138418  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 12:46:04.858  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.858  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=138419  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 12:46:04.858  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.858  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 12:46:04.859  1036  1524 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138420
08-26 12:46:04.859  1036  1524 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138420
08-26 12:46:04.860  1036  1524 D WifiNative-wlan0: doString: [STATUS]
08-26 12:46:04.861  1036  1524 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 12:46:04.861  1036  8021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 12:46:04.862  1036  8021 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 12:46:04.863  1036  1524 I WifiServiceExtension: setVHTCapabilityType  : false
,08-26 12:46:04.870  1036  1524 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 12:46:04.870  1036  1524 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-26 12:46:04.875  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:04.875  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:46:04.877  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.877  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.877  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 12:46:04.879  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:04.880  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.880  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.880  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 12:46:04.881  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:04.881  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:46:04.882  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:04.884  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:04.884  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:46:04.887  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:04.888  1036  1524 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-26 12:46:04.888  1036  1531 D ConnectivityService: Got NetworkAgent Messenger
08-26 12:46:04.888  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 12:46:04.888  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 12:46:04.889  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 12:46:04.889  1036  1531 D ConnectivityService: NetworkAgent connected
08-26 12:46:04.889  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 12:46:04.889  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 12:46:04.890  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:04.890  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:46:04.891  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:04.895  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 12:46:04.895  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 12:46:04.895  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 12:46:04.896  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 12:46:04.896  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 12:46:04.896  8079  8079 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 12:46:04.901  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 12:46:04.902   320   894 D CommandListener: Setting iface cfg
08-26 12:46:04.910  1036  1524 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 12:46:04.910  1036  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138471  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:46:04.911  1036  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:46:04.911  1036  8103 D DhcpStateMachine: StoppedState
08-26 12:46:04.911  1036  8103 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.911  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:46:04.912  1036  8103 D DhcpStateMachine: WaitBeforeStartState
08-26 12:46:04.912  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:46:04.912  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-26 12:46:04.914  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:46:04.914  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 12:46:04.915  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:46:04.915  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 12:46:04.916  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:04.917  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:04.917  1036  1524 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:04.918  1036  1524 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:04.918  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:04.918  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 12:46:04.920  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:46:04.920  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 12:46:04.921  1036  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138481  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:46:04.921  1036  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138482  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:46:04.922  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=138483  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 12:46:04.924  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14504] from screen [on:0 period:-965417605] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 12:46:04.925  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-965417604] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 12:46:04.925  1036  1524 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 12:46:04.928  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:04.929  1036  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-26 12:46:04.929  8079  8079 D PluginManager: init()
08-26 12:46:04.930  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.930  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.930  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.931  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.931  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.932  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.932  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 12:46:04.933  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:46:04.933  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 12:46:04.934  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-26 12:46:04.934  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=124,0,0
08-26 12:46:04.934  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 12:46:04.934  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 12:46:04.935  1036  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 12:46:04.935  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 12:46:04.935  1036  1524 D WifiNative-wlan0: SET ps 0: returned true
08-26 12:46:04.935  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 12:46:04.935  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 12:46:04.936  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 12:46:04.936  1036  1523 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34fcc655 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.936  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@34fcc655 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.936  1036  8103 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.936  1036  8103 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 12:46:04.937  1036  1524 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 12:46:04.937  1036  1524 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 12:46:04.937  1036  1524 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 12:46:04.938   320   894 D CommandListener: Setting iface cfg
08-26 12:46:04.939   320   894 D CommandListener: Trying to bring up wlan0
08-26 12:46:04.939  1036  1524 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-26 12:46:04.942  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 12:46:04.942  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 12:46:04.943  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.944  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.944  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.945  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.945  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.945  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 12:46:04.946  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 12:46:04.947  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 12:46:04.947  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 12:46:04.947  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 12:46:04.947  1036  1523 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.947  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 12:46:04.948  1036  1523 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:04.948  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 12:46:04.948  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 12:46:04.948  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 12:46:04.948  1036  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 12:46:04.948  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 12:46:04.964  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-26 12:46:04.965  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 12:46:04.965  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 12:46:04.965  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 12:46:04.965  1036  1524 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 12:46:04.966  1036  1531 D ConnectivityService: ignoring duplicate network state non-change
,08-26 12:46:04.970  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:04.970  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:46:04.971  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.971  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.971  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:04.971  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 12:46:04.973  1036  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 12:46:04.974  1036  1531 D ConnectivityService: Adding iface wlan0 to network 102
08-26 12:46:04.975  1036  1524 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 12:46:04.990  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.990  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:04.990  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 12:46:04.990  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 12:46:04.990  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:04.990  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:46:04.990  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:04.990  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:04.990  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 12:46:04.990  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 12:46:04.990  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 12:46:04.992  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 12:46:04.993  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 12:46:04.995  1036  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 12:46:04.995  1036  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 12:46:04.996  1036  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 12:46:04.997   320   894 E Netd    : netlink response contains error (File exists)
08-26 12:46:04.997  1036  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 12:46:04.997  6571  6698 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 12:46:04.997  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:04.997  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 12:46:04.998  1036  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 12:46:04.998  1036  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 12:46:04.998  1036  1531 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 12:46:04.998  6571  6698 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 12:46:04.999  6571  6698 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2893a40f Bundle[{}]
08-26 12:46:05.000  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:05.000  6571  6698 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 12:46:05.000  6571  6698 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 12:46:05.001  6571  6698 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 12:46:05.002  6571  6698 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 12:46:05.002  6571  6698 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 12:46:05.003  6571  6698 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 12:46:05.004  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 12:46:05.007  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:05.007  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 12:46:05.007  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:05.008  6571  6698 I System.out: Running OutgoingSocketThread
08-26 12:46:05.008  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:05.008  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:05.008  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 12:46:05.009  6571  8111 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 846)
08-26 12:46:05.009  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 12:46:05.010  6571  8111 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 53744
08-26 12:46:05.010  6571  8111 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 12:46:05.014  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:05.014  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 12:46:05.014  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 12:46:05.015  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 12:46:05.015  1036  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 12:46:05.015  1036  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 12:46:05.015  1036  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 12:46:05.015  1036  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:46:05.015  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:46:05.015  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 12:46:05.015  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:46:05.015  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 12:46:05.015  1036  1531 D ConnectivityService: currentScore = 0, newScore = 20
08-26 12:46:05.015  1036  1531 D ConnectivityService:    accepting network in place of null
08-26 12:46:05.015  1036  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:46:05.016  1036  8102 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:05.016  1036  8102 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 12:46:05.016  1036  8102 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 12:46:05.016  1036  8102 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 12:46:05.018  1036  1524 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:46:05.018  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:46:05.018  1841  1841 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:46:05.018  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 12:46:05.018   320  8113 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 12:46:05.019  1036  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 ,wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 12:46:05.019  1036  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 12:46:05.019  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 12:46:05.019  1036  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:46:05.019  1036  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 12:46:05.020  1036  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 12:46:05.021  1036  1531 D ConnectivityService: validation of new default Network = false
08-26 12:46:05.021  1036  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 12:46:05.021  1036  1531 D DSQN    : enableDataServiceNotify 
08-26 12:46:05.021  1036  1531 D DSQN    : start dsqn bin
08-26 12:46:05.022  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:05.022  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 12:46:05.023  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:05.027  1036  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 12:46:05.015  8114  8114 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:05.015  8114  8114 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:05.027  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:46:05.027  1036  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:46:05.028  1588  1820 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 12:46:05.029  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 12:46:05.029  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 12:46:05.029  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 12:46:05.029  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 12:46:05.041  8114  8114 E DSQN    : DSQN ssw
08-26 12:46:05.050  1036  1522 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 12:46:05.059  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 12:46:05.060  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:05.060  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:05.067   320  8113 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 12:46:05.099   320  8113 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 12:46:05.134   320   893 D LGDataListener: argv[0]=dsqncommand
,08-26 12:46:05.134   320   893 D LGDataListener: argv[1]=wlan0
08-26 12:46:05.134   320   893 D LGDataListener: argv[2]=1
,08-26 12:46:05.135   320   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 12:46:05.136  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 12:46:05.136  1036  1116 D DSQN    : start to monitor internet connection
08-26 12:46:05.139  1036  8103 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 12:46:05.141  1036  8103 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 12:46:05.141  1036  8103 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 12:46:05.135  8121  8121 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 12:46:05.135  8121  8121 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 12:46:05.161  8121  8121 I dhcpcd  : version 5.5.6 starting
08-26 12:46:05.163  8121  8121 E dhcpcd  : get_duid: m
08-26 12:46:05.163  8121  8121 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 12:46:05.163  8121  8121 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 12:46:05.166  1036  8102 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 10:46:05 GMT], X-Android-Received-Millis=[1472208365166], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472208365133]}
08-26 12:46:05.166  1036  8102 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 12:46:05.166  1036  8102 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 12:46:05.166  1036  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-26 12:46:05.166  1036  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-26 12:46:05.166  1036  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 12:46:05.166  1036  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:46:05.166  1036  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 12:46:05.166  1036  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 12:46:05.167  1036  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 12:46:05.167  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:46:05.167  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:46:05.167  1036  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:46:05.167  1036  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:46:05.167  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 12:46:05.169  1036  1524 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:46:05.169  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 12:46:05.169  1588  1820 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 12:46:05.170  1841  1841 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:46:05.170  1841  1841 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-26 12:46:05.183  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 12:46:05.184  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:05.185  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:05.219  8121  8121 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 12:46:05.219  8121  8121 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-26 12:46:05.219  8121  8121 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 12:46:05.219  8121  8121 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 12:46:05.220  8121  8121 D dhcpcd  : wlan0: sending REQUEST (xid 0x844b4c92), next in 4.48 seconds
,08-26 12:46:05.304  8121  8121 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 12:46:05.323  8121  8121 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-26 12:46:05.323  8121  8121 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-26 12:46:05.324  8121  8121 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-26 12:46:05.324  8121  8121 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-26 12:46:05.325  8121  8121 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-26 12:46:05.326  8121  8121 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-26 12:46:05.326  8121  8121 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-26 12:46:05.326  8121  8121 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-26 12:46:05.351  8079  8079 W ExternalStrings: load override strings
08-26 12:46:05.351  8079  8079 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 12:46:05.351  8079  8079 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 12:46:05.354  8079  8079 D StatusProvider: onCreate
08-26 12:46:05.391  8079  8079 V Signer  : override build config not found
08-26 12:46:05.391  8079  8079 D Signer  : value of property debug is false
,08-26 12:46:05.414  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-26 12:46:05.415  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-26 12:46:05.415  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 12:46:05.415  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 12:46:05.415  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 12:46:05.415  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 12:46:05.415  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 12:46:05.416  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 12:46:05.416  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 12:46:05.416  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-26 12:46:05.416  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 12:46:05.416  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 12:46:05.416  8079  8079 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-26 12:46:05.424  8079  8079 V LGMDMManager: Create singleton instance
,08-26 12:46:05.461  8079  8079 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-26 12:46:05.505  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 12:46:05.508  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:46:05.527  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:05.531  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.535  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:46:05.537  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 12:46:05.545  7803  7803 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 12:46:05.548  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:46:05.548  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 12:46:05.554  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:05.558  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.561  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:46:05.562  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:46:05.562  7803  7803 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 12:46:05.564  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-26 12:46:05.566  6770  6770 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 12:46:05.568  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:46:05.568  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 12:46:05.572  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 12:46:05.576  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.585  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 12:46:05.585  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:46:05.586  7803  7803 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 12:46:05.589  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 12:46:05.589  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 12:46:05.589  6770  6770 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 12:46:05.589  6770  6770 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 12:46:05.590  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 12:46:05.603  6770  6770 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 12:46:05.603  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 12:46:05.603  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 12:46:05.603  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 12:46:05.603  6770  6770 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 12:46:05.603  6770  6770 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 12:46:05.604  6770  6770 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-26 12:46:05.699  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:46:05.700  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 12:46:05.702  8079  8142 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-26 12:46:05.716  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:05.727  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.736  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:46:05.737  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:46:05.737  7803  7803 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 12:46:05.744  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:46:05.744  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 12:46:05.747  1036  8103 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 12:46:05.748  1036  8103 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 12:46:05.748  1036  8103 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 12:46:05.748  1036  8103 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 12:46:05.748  1036  8103 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 12:46:05.748  1036  8103 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 12:46:05.748  1036  8103 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 12:46:05.748  1036  8103 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 12:46:05.750  1036  8103 D DhcpStateMachine: RunningState
08-26 12:46:05.758  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:05.766  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.776  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 12:46:05.776  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:46:05.777  7803  7803 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 12:46:05.785  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 12:46:05.785  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 12:46:05.799  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:05.807  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.817  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:46:05.817  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:46:05.818  7803  7803 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 12:46:05.825  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:46:05.826  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 12:46:05.841  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:05.849  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.855  7530  7854 D UEI.SmartControl: Internal timer expired: 2
08-26 12:46:05.855  7530  7854 D UEI.SmartControl: unbind internal service
,08-26 12:46:05.861  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:46:05.861  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:46:05.861  7803  7803 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 12:46:05.882  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 12:46:05.883  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:46:05.897  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:05.903  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.910  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:46:05.910  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 12:46:05.919  7803  7803 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 12:46:05.924  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 12:46:05.924  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 12:46:05.931  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:05.937  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.946  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:46:05.946  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:46:05.948  7803  7803 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 12:46:05.952  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 12:46:05.954  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 12:46:05.960  8030  8030 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 12:46:05.964  8030  8030 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:46:05.968  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:05.976  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:05.983  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:46:05.983  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:46:05.984  7803  7803 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 12:46:05.985  7803  7803 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 12:46:05.986  7803  7803 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 12:46:05.990  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 12:46:05.990  8079  8144 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 12:46:05.993  8079  8142 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:46:05.993  8079  8142 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 12:46:05.995  8030  8030 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 12:46:05.995  8030  8030 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 12:46:06.001  6770  6770 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 12:46:06.009  6770  6770 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 12:46:06.009  6571  6698 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 847)
08-26 12:46:06.009  6571  6698 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 847)
08-26 12:46:06.014  6571  6698 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 852)
08-26 12:46:06.016  6571  6698 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 12:46:06.016  6571  6698 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 853)
08-26 12:46:06.016  7803  7803 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 12:46:06.016  7803  7803 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 12:46:06.017  7803  7803 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 12:46:06.018  7803  7803 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 12:46:06.018  7803  7803 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 12:46:06.021  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.021  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33681a2a added. We now have 2 listener(s)
08-26 12:46:06.022  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.024  1036  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.026  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.026  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.026  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.026  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.026  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.027  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c8201b added. We now have 9 listener(s)
08-26 12:46:06.027  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.027  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 12:46:06.028  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.030  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.031  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:46:06.033  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.035  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.035  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:06.035  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:06.035  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:46:06.035  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:06.035  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:06.035  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.035  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:06.035  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:46:06.038  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.038  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:46:06.038  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.038  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39577f91 added. We now have 3 listener(s)
,08-26 12:46:06.039  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.039  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.041  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.041  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.041  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.041  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.041  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.041  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e45aef6 added. We now have 10 listener(s)
08-26 12:46:06.042  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.042  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.042  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:46:06.042  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:06.042  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:46:06.042  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.042  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.042  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:06.042  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.042  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33681a2a removed from the list
08-26 12:46:06.042  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.042  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c8201b removed from the list
08-26 12:46:06.044  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.044  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.044  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:06.044  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.047  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.047  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.048  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.049  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.049  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.049  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.049  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c8201b not in the list
08-26 12:46:06.049  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.049  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.051  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.051  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.051  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.051  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e45aef6 removed from the list
08-26 12:46:06.051  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.051  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.051  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.051  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.051  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39577f91 removed from the list
08-26 12:46:06.052  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.052  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@173ea2f7 added. We now have 2 listener(s)
08-26 12:46:06.052  1036  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 12:46:06.056  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.056  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.057  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.057  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 12:46:06.057  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.058  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5cd564 added. We now have 9 listener(s)
08-26 12:46:06.058  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.058  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 12:46:06.058  1036  1765 I ActivityManager: Killing 7174:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-26 12:46:06.115  8079  8142 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-26 12:46:06.117  7530  7847 D serial_port: close(fd = 24)
,08-26 12:46:06.121  7530  7847 I UEI.SmartControl: Serial port is closed.
08-26 12:46:06.189  1036  1906 W libprocessgroup: failed to open /acct/uid_10005/pid_7174/cgroup.procs: No such file or directory
08-26 12:46:06.191  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:46:06.203  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:06.203  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:06.203  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:46:06.203  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:06.203  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:06.203  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.203  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:06.203  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:46:06.208  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.208  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 12:46:06.208  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.209  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2895c482 added. We now have 3 listener(s)
08-26 12:46:06.209  1036  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.215  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.219  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.220  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.220  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.220  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.220  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.220  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28307793 added. We now have 10 listener(s)
08-26 12:46:06.221  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.221  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:06.221  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:46:06.221  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:46:06.221  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:46:06.221  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 12:46:06.230  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 12:46:06.230  1036  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.239  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 12:46:06.240  8079  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-26 12:46:06.240  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 12:46:06.244  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:46:06.245  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:06.248  6571  6698 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 12:46:06.248  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:06.248  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:46:06.252  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:46:06.252  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:06.252  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:46:06.252  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.252  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.252  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:06.253  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.253  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@173ea2f7 removed from the list
08-26 12:46:06.253  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.253  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5cd564 removed from the list
08-26 12:46:06.253  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:06.253  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.253  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.253  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:46:06.256  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 12:46:06.256  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.256  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.256  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5cd564 not in the list
08-26 12:46:06.256  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.256  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.258  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.259  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:46:06.259  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:46:06.259  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.259  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.259  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28307793 removed from the list
08-26 12:46:06.259  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.260  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.260  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.260  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.260  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2895c482 removed from the list
08-26 12:46:06.261  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.261  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bdfa6ce added. We now have 2 listener(s)
08-26 12:46:06.261  8079  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 12:46:06.262  1036  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.262  8079  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 12:46:06.263  8079  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 12:46:06.265  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.265  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.265  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.265  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.265  6571 , 6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@460f9ef added. We now have 9 listener(s)
08-26 12:46:06.265  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.267  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 12:46:06.271  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:46:06.271  8079  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 12:46:06.272  8079  8142 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 12:46:06.276  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:06.276  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:06.276  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:46:06.276  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:06.276  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:06.276  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.276  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:06.276  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:46:06.279  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.279  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:46:06.279  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.279  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d3a5f85 added. We now have 3 listener(s)
,08-26 12:46:06.280  1036  2021 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.282  8079  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-26 12:46:06.282  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.285  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.286  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.286  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.286  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.286  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d361da added. We now have 10 listener(s)
08-26 12:46:06.286  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.286  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:06.287  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.287  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:06.287  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:46:06.287  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 12:46:06.287  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:46:06.287  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 12:46:06.288  8079  8142 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-26 12:46:06.291  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 12:46:06.292  1036  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 12:46:06.301  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 12:46:06.302  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 12:46:06.306  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:46:06.307  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 12:46:06.310  6571  6698 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 12:46:06.311  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 12:46:06.311  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:06.311  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:46:06.311  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.311  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.311  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:06.311  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.312  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bdfa6ce removed from the list
08-26 12:46:06.312  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.312  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@460f9ef removed from the list
08-26 12:46:06.312  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:06.312  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.313  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.313  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.315  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.315  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.315  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.315  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@460f9ef not in the list
08-26 12:46:06.315  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.315  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.317  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.319  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:46:06.319  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:46:06.319  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.319  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.319  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d361da removed from the list
08-26 12:46:06.319  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.319  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.319  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.319  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down.,..
08-26 12:46:06.319  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d3a5f85 removed from the list
08-26 12:46:06.321  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.322  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fc66f01 added. We now have 2 listener(s)
08-26 12:46:06.322  1036  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 12:46:06.326  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.326  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.326  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.326  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.326  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3915c1a6 added. We now have 9 listener(s)
08-26 12:46:06.326  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.326  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 12:46:06.329  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:46:06.334  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:06.334  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:06.334  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:46:06.334  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:06.334  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:06.334  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.334  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:06.334  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 12:46:06.336  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.337  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:46:06.337  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.337  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b525f94 added. We now have 3 listener(s)
08-26 12:46:06.338  1036  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.339  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.343  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.345  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.345  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.345  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.345  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.345  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba9fa3d added. We now have 10 listener(s)
08-26 12:46:06.345  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.345  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:06.345  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 12:46:06.345  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 12:46:06.345  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 12:46:06.345  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 12:46:06.354  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 12:46:06.354  1036  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.358  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 12:46:06.359  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 12:46:06.361  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 12:46:06.361  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:06.364  6571  6698 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 12:46:06.366  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:46:06.366  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:06.366  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:46:06.366  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.366  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.367  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:06.367  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.367  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fc66f01 removed from the list
08-26 12:46:06.367  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.367  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3915c1a6 removed from the list
08-26 12:46:06.367  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:06.367  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 12:46:06.368  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.368  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.370  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.370  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 12:46:06.370  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.370  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3915c1a6 not in the list
08-26 12:46:06.370  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.370  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.372  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.373  6571  6698 D BluetoothLeScanner: could not find callback wrapper
08-26 12:46:06.373  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 12:46:06.373  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.373  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.373  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba9fa3d removed from the list
08-26 12:46:06.373  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.373  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.373  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.373  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.373  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b525f94 removed from the list
08-26 12:46:06.375  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.375  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29bfe100 added. We now have 2 listener(s)
08-26 12:46:06.375  1036  1760 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.378  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.378  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.378  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.379  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.379  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340fd39 added. We now have 9 listener(s)
08-26 12:46:06.379  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.379  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 12:46:06.381  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 12:46:06.386  6571  6698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 12:46:06.386  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 12:46:06.386  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 12:46:06.386  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 12:46:06.386  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 12:46:06.386  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.386  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 12:46:06.386  6571  6698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 12:46:06.389  6571  6698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 12:46:06.389  6571  6698 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 12:46:06.389  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 12:46:06.389  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3cdf added. We now have 3 listener(s)
08-26 12:46:06.389  1036  1642 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 12:46:06.391  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 12:46:06.395  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 12:46:06.399  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 12:46:06.399  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 12:46:06.399  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 12:46:06.399  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 12:46:06.399  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12c20d2c added. We now have 10 listener(s)
08-26 12:46:06.399  6571  6698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 12:46:06.401  6571  6698 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 12:46:06.401  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:06.401  6571  6698 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 12:46:06.401  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.401  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.401  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 12:46:06.401  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.401  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29bfe100 removed from the list
08-26 12:46:06.402  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.402  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340fd39 removed from the list
08-26 12:46:06.402  6571  6698 D io.jxcore.node.ConnectivityMonitor: stop
08-26 12:46:06.402  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.402  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.402  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.405  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.405  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.405  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.405  6571  6698 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340fd39 not in the list
08-26 12:46:06.406  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.406  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.407  6571  6698 I org.thaliprojec,t.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 12:46:06.407  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 12:46:06.407  6571  6698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 12:46:06.407  6571  6698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12c20d2c removed from the list
08-26 12:46:06.407  6571  6698 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 12:46:06.407  6571  6698 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 12:46:06.407  6571  6698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 12:46:06.407  6571  6698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 12:46:06.407  6571  6698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ea3cdf removed from the list
,08-26 12:46:06.410  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 12:46:06.410  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 12:46:06.410  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 12:46:06.411  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 12:46:06.411  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 12:46:06.412  6571  6698 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 12:46:06.435  6571  8175 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 860, name: My test thread name)
08-26 12:46:06.435  6571  8175 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 860, thread name: My test thread name)
08-26 12:46:06.436  6571  8175 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 860, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 12:46:06.439  6571  8177 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 862, name: My test thread name)
08-26 12:46:06.439  6571  8177 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 862, thread name: My test thread name)
08-26 12:46:06.439  6571  8177 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 862, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 12:46:06.442  6571  6698 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 12:46:06.443  6571  6698 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 12:46:06.443  6571  6698 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 12:46:06.443  6571  6698 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 12:46:06.443  6571  6698 D com.test.thalitest.ThaliTestRunner: Total duration: 24197 ms
08-26 12:46:06.446  6571  6698 I jxcore-log: *Native tests were executed*
08-26 12:46:06.446  6571  6698 I jxcore-log: 
08-26 12:46:06.446  6571  6698 I jxcore-log: Total number of executed tests:  80
08-26 12:46:06.446  6571  6698 I jxcore-log: 
08-26 12:46:06.446  6571  6698 I jxcore-log: Number of passed tests:  80
08-26 12:46:06.446  6571  6698 I jxcore-log: 
08-26 12:46:06.447  6571  6698 I jxcore-log: Number of failed tests:  0
08-26 12:46:06.447  6571  6698 I jxcore-log: 
08-26 12:46:06.447  6571  6698 I jxcore-log: Number of ignored tests:  0
08-26 12:46:06.447  6571  6698 I jxcore-log: 
08-26 12:46:06.448  6571  6698 I jxcore-log: Total duration:  24197
08-26 12:46:06.448  6571  6698 I jxcore-log: 
08-26 12:46:06.448  6571  6698 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 12:46:06.448  6571  6698 I jxcore-log: 
08-26 12:46:06.454  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.454  6571  6698 I jxcore-log: 
,08-26 12:46:06.460  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.460  6571  6698 I jxcore-log: 
08-26 12:46:06.463  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.463  6571  6698 I jxcore-log: 
08-26 12:46:06.465  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.465  6571  6698 I jxcore-log: 
08-26 12:46:06.466  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.466  6571  6698 I jxcore-log: 
08-26 12:46:06.468  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.468  6571  6698 I jxcore-log: 
08-26 12:46:06.469  6571  6571 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-26 12:46:06.471  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.471  6571  6698 I jxcore-log: 
08-26 12:46:06.473  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.473  6571  6698 I jxcore-log: 
08-26 12:46:06.474  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.474  6571  6698 I jxcore-log: 
08-26 12:46:06.475  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.475  6571  6698 I jxcore-log: 
08-26 12:46:06.476  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.476  6571  6698 I jxcore-log: 
08-26 12:46:06.478  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 12:46:06.478  6571  6698 I jxcore-log: 
08-26 12:46:06.479  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.479  6571  6698 I jxcore-log: 
08-26 12:46:06.480  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.480  6571  6698 I jxcore-log: 
08-26 12:46:06.481  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.481  6571  6698 I jxcore-log: 
08-26 12:46:06.482  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.482  6571  6698 I jxcore-log: 
08-26 12:46:06.483  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.483  6571  6698 I jxcore-log: 
08-26 12:46:06.484  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.484  6571  6698 I jxcore-log: 
08-26 12:46:06.485  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.485  6571  6698 I jxcore-log: 
08-26 12:46:06.486  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.486  6571  6698 I jxcore-log: 
08-26 12:46:06.487  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.487  6571  6698 I jxcore-log: 
08-26 12:46:06.487  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 12:46:06.487  6571  6698 I jxcore-log: 
08-26 12:46:06.488  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.488  6571  6698 I jxcore-log: 
,08-26 12:46:06.489  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 12:46:06.489  6571  6698 I jxcore-log: 
,08-26 12:46:06.490  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.490  6571  6698 I jxcore-log: 
,08-26 12:46:06.491  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.491  6571  6698 I jxcore-log: 
,08-26 12:46:06.491  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.491  6571  6698 I jxcore-log: 
,08-26 12:46:06.492  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.492  6571  6698 I jxcore-log: 
,08-26 12:46:06.493  6571  6698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 12:46:06.493  6571  6698 I jxcore-log: 
08-26 12:46:06.759  1036  1524 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 12:46:06.761  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 12:46:06.762  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 12:46:06.775  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 12:46:06.776  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 12:46:06.776  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 12:46:06.777  1036  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-26 12:46:06.777  1036  1531 D ConnectivityService: identical MTU - not setting
08-26 12:46:06.777  1036  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 12:46:06.777  1036  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 12:46:06.777  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 12:46:06.777  1036  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:46:06.778  1036  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 12:46:06.779  1588  1820 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 12:46:06.877  8179  8179 D AndroidRuntime: 
08-26 12:46:06.877  8179  8179 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 12:46:06.882  8179  8179 D AndroidRuntime: CheckJNI is OFF
,08-26 12:46:07.066  8179  8179 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 12:46:07.081  1036  1103 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-26 12:46:07.081  1036  1103 I ActivityManager: Killing 6571:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-26 12:46:07.157  1036  1059 I WindowState: WIN DEATH: Window{206b261c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 12:46:07.157  1036  1530 D WifiService: Client connection lost with reason: 4
08-26 12:46:07.175  1036  1059 D InputDispatcher: Window went away: Window{206b261c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 12:46:07.301  1036  1103 I ActivityManager:   Force finishing activity ActivityRecord{100561af u0 com.test.thalitest/.MainActivity t6}
,08-26 12:46:07.359   344   360 E GBMv2   : DFP En is all cleared set to be enabled
,08-26 12:46:07.363  1036  1910 W ActivityManager: Spurious death for ProcessRecord{1014ce17 6571:com.test.thalitest/u0a118}, curProc for 6571: null
08-26 12:46:07.366  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-26 12:46:07.366  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2a1a1da8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 12:46:07.368  1928  2651 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 12:46:07.368  1928  2651 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a1800c1 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 12:46:07.369  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-26 12:46:07.372  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{100561af u0 com.test.thalitest/.MainActivity t6 f}
08-26 12:46:07.372  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{100561af u0 com.test.thalitest/.MainActivity t6 f}
,08-26 12:46:07.403  2022  2022 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-26 12:46:07.405  2022  2022 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-26 12:46:07.415  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-26 12:46:07.422  3801  3801 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-26 12:46:07.423  1985  1985 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 12:46:07.428  7601  7601 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-26 12:46:07.428  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-26 12:46:07.436  1036  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 12:46:07.446  2456  2593 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 12:46:07.451  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 12:46:07.451  4447  4447 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 12:46:07.451  4447  4447 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 12:46:07.451  4447  4447 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 12:46:07.451  4447  4447 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 12:46:07.452  4447  4447 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 12:46:07.452  4447  4447 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-26 12:46:07.452  4447  4447 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 12:46:07.452  4447  4447 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 12:46:07.452  4447  4447 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:46:07.452  4447  4447 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 12:46:07.452  4447  4447 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 12:46:07.452  4447  4447 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 12:46:07.452  2022  2095 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-26 12:46:07.466  8079  8079 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-26 12:46:07.470  4558  4558 I art     : Explicit concurrent mark sweep GC freed 8206(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 545us total 83.535ms
,08-26 12:46:07.480  1036  2002 V SIM_STK : Menu title from STK is T-Mobile
08-26 12:46:07.514  1036  1101 W InputMethodInfo: Duplicated subtype definition found: , voice
08-26 12:46:07.515  1036  1036 D administrator: Handling package changes for user 0
,08-26 12:46:07.518  1892  1892 D ActionManagerService: notifyUserLog: 1000003
08-26 12:46:07.519  2022  2022 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 12:46:07.520  3801  4438 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-26 12:46:07.530  2022  2022 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-26 12:46:07.531  1805  1805 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-26 12:46:07.543  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-26 12:46:07.561  2022  2022 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-26 12:46:07.563  2022  2022 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 12:46:07.577  1892  1892 D ActionManagerService: notifyUserLog: 1000004
,08-26 12:46:07.577  3801  4438 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 12:46:07.577  2022  2022 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-26 12:46:07.581  3801  3816 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 12:46:07.582  1588  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 12:46:07.582  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.583  2152  2152 I ConfigService: onCreate
08-26 12:46:07.583  2152  2152 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-26 12:46:07.588  1805  1805 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , expire_time: 0
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , display: false
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , animation: false }
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , expire_time: 0
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , display: false
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , animation: false }
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , create_time: 1471602816196
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , expire_time: 0
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , display: false
08-26 12:46:07.593  2022  2022 I GBoardWebViewUtils: , animation: false }
08-26 12:46:07.594  2152  2152 I ConfigService: onBind returning update interface
08-26 12:46:07.596  2152  2152 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 12:46:07.596  2152  2152 I ConfigService: onBind returning config service
08-26 12:46:07.599  1036  1933 V SIM_STK : Menu title from STK is T-Mobile
08-26 12:46:07.599  1036  1933 V SIM_STK : Menu title from STK is T-Mobile
,08-26 12:46:07.606  1588  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 12:46:07.606  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.607  2022  8213 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-26 12:46:07.616  1858  1858 D SplitUIManager: split_name #11 / not available #0
08-26 12:46:07.617  1858  1858 D SplitUIService: removed split : 
08-26 12:46:07.622  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 12:46:07.623  2022  2022 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-26 12:46:07.634  2152  2152 I ConfigService: onDestroy
08-26 12:46:07.637  1588  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 12:46:07.638  1588  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 12:46:07.638  1588  1647 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 12:46:07.639  1588  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 12:46:07.639  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 12:46:07.640  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 12:46:07.640  1588  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 12:46:07.640  1588  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 12:46:07.641  1588  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 12:46:07.641  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.641  1036  1760 V SIM_STK : Menu title from STK is T-Mobile
08-26 12:46:07.655  1588  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 12:46:07.655  1588  1647 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 12:46:07.657  1588  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 12:46:07.657  1588  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 12:46:07.662  1036  1910 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 12:46:07.662  7601  7601 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-26 12:46:07.665  1588  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 12:46:07.665  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.667  1805  8216 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-26 12:46:07.669  1588  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 12:46:07.669  1588  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 12:46:07.669  1588  1647 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 12:46:07.669  1588  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 12:46:07.670  1588  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 12:46:07.671  1588  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 12:46:07.675  1858  1858 D SplitUIManager: split_name #11 / not available #0
08-26 12:46:07.675  1858  1858 I SplitUIService: split app #11
,08-26 12:46:07.676  1588  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 12:46:07.676  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.679  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-26 12:46:07.679  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 12:46:07.681  1588  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 12:46:07.681  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.684  1588  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 12:46:07.684  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.694  1588  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 12:46:07.694  1588  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-26 12:46:07.696  1588  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 12:46:07.696  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.697  1588  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 12:46:07.697  1588  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 12:46:07.698  1588  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 12:46:07.698  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.700  1588  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 12:46:07.700  1588  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 12:46:07.701  2022  2022 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-26 12:46:07.702  1588  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 12:46:07.702  1588  1647 D KeyguardModel: createShortcutInfo...
08-26 12:46:07.710  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-26 12:46:07.710  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 12:46:07.710  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 12:46:07.712  1805  8223 I PeopleContactsSync: CP2 sync disabled
08-26 12:46:07.716  1036  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 12:46:07.719  5899  8220 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-26 12:46:07.725  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-26 12:46:07.725  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-26 12:46:07.729  1805  4707 I Icing   : doRemovePackageData com.test.thalitest
08-26 12:46:07.736  1805  8222 W GmsApplication: Using Auth Proxy for data requests.
,08-26 12:46:07.742  1805  8222 W GmsApplication: Using Auth Proxy for data requests.
08-26 12:46:07.743   336   407 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-26 12:46:07.744  3191  8225 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-26 12:46:07.775  6964  6964 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-26 12:46:07.785  2342  8227 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-26 12:46:07.791  2152  2167 I art     : Explicit concurrent mark sweep GC freed 7368(472KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 408us total 21.529ms
08-26 12:46:07.798  2022  2022 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-26 12:46:07.812  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 12:46:07.815  1036  1933 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8228 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-26 12:46:07.815  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-26 12:46:07.817  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 12:46:07.818  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 12:46:07.819  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 12:46:07.824  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d44ec25 u0 com.lge.launcher2/.Launcher t5} time:141400
08-26 12:46:07.836  2022  2022 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 12:46:07.836  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 12:46:07.840  2022  2235 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 12:46:07.840  2022  2235 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-26 12:46:07.853  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-26 12:46:07.853  2022  2022 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 12:46:07.854  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 12:46:07.860  1036  1124 I art     : Explicit concurrent mark sweep GC freed 86112(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.606ms total 335.488ms
08-26 12:46:07.863  2022  2022 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-26 12:46:07.864  2629  2629 D [Concierge]Service: onStartCommand(). Type : 8
08-26 12:46:07.864  2629  2629 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 12:46:07.864  8228  8228 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 12:46:07.864  8228  8228 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 12:46:07.865  2629  2629 D [Concierge]Service: Update widget ID : 11
08-26 12:46:07.865  8228  8228 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 12:46:07.865  8228  8228 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 12:46:07.866  2022  2022 D [Concierge]WidgetView: change position of spinner
,08-26 12:46:07.867  2629  2629 D [Concierge]Service: onStartCommand(). Type : 0
08-26 12:46:07.867  2022  2022 I [Concierge]WidgetView: initWebView(). Time : 1472208367867
08-26 12:46:07.897  2022  2022 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 893293376
,08-26 12:46:07.898  2022  2022 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-26 12:46:07.898  2022  2022 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 12:46:07.900  2022  2022 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@25432efd
08-26 12:46:07.900  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 12:46:07.901  2022  2022 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 12:46:07.901  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 12:46:07.902  8179  8179 D AndroidRuntime: Shutting down VM
08-26 12:46:07.907  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 12:46:07.908  2022  2022 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 12:46:07.908  2022  2022 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 12:46:07.909  2022  2022 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472208253646, New one : 1472208367867
08-26 12:46:07.909  2022  2022 D [Concierge]WidgetView: Unregister all receivers
08-26 12:46:07.909  2022  2022 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 12:46:07.909  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 12:46:07.911  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 12:46:07.912  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-26 12:46:07.912  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 12:46:07.914  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 12:46:07.915  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 12:46:07.918  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 12:46:07.918  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 12:46:07.933  1036  1524 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2437 sc=60 link=72 tx=62.0, 0.0, 0.0  rx=66.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-965414595] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 12:46:07.934  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2437 sc=60 link=72 tx=62.0, 0.0, 0.0  rx=66.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-965414594] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 12:46:07.934  1036  1524 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-26 12:46:07.955  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8248 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 12:46:07.957  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 12:46:07.969  8228  8228 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 12:46:07.976  2022  2022 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 12:46:07.977  8228  8228 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-26 12:46:07.984  2022  2022 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 12:46:07.985  2022  2022 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-26 12:46:07.986  2022  2022 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 12:46:07.994  1036  1525 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-26 12:46:08.003  1036  1058 I ActivityManager: Killing 7642:com.google.android.talk/u0a72 (adj 15): empty #17
08-26 12:46:08.007  8228  8228 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 12:46:08.010  2022  2022 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ae8c065 time:141587
,08-26 12:46:08.021  1036  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 12:46:08.033  1036  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 12:46:08.038  1036  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-26 12:46:08.094  1036  1946 W libprocessgroup: failed to open /acct/uid_10072/pid_7642/cgroup.procs: No such file or directory
,08-26 12:46:08.097  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-26 12:46:08.098  5727  5727 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-26 12:46:08.101  2022  2022 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 12:46:08.101  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 12:46:08.102  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 12:46:08.117  8228  8228 D LgDataFeature: LgDataFeature() Constructor: none
08-26 12:46:08.117  8228  8228 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 12:46:08.120  2022  2022 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-26 12:46:08.158  2022  2902 I GBoardtInterface: onReloaded()
08-26 12:46:08.159  2022  2022 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-26 12:46:08.160  3801  3816 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 12:46:08.163  3801  4439 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-26 12:46:08.163  8228  8228 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-26 12:46:08.169  1892  1892 D ActionManagerService: notifyUserLog: 1000001
08-26 12:46:08.170  3801  4438 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 12:46:08.170  3801  4438 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 12:46:08.172  1892  1892 D ActionManagerService: notifyUserLog: 1000001
08-26 12:46:08.173  3801  4438 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 12:46:08.173  3801  4438 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 12:46:08.173  3801  4438 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-26 12:46:08.173  3801  4438 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-26 12:46:08.174  3801  3816 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 12:46:08.175  1036  1933 I ActivityManager: Killing 7723:com.android.vending/u0a44 (adj 15): empty #17
,08-26 12:46:08.214  1985  1985 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 12:46:08.214  1985  1985 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-26 12:46:08.214  1036  1561 W libprocessgroup: failed to open /acct/uid_10044/pid_7723/cgroup.procs: No such file or directory
,08-26 12:46:08.216  1985  1985 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-26 12:46:08.218  2022  2022 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-26 12:46:08.218  2022  2022 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-26 12:46:08.223  2022  2022 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-26 12:46:08.223  2022  2022 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at an,droid.os.Handler.dispatchMessage(Handler.java:102)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 12:46:08.224  8079  8079 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 12:46:08.224  2022  2022 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-26 12:46:08.224  2022  2022 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 12:46:08.226  8079  8079 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-26 12:46:08.230  7410  7410 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-26 12:46:08.234  6770  6770 D PackageIntentReceiver: Not supported Hotkey customization function 
08-26 12:46:08.240  6770  6770 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,08-26 12:46:08.240  6770  6770 D HideNavigationAppsReceiver: replacing : false
08-26 12:46:08.243  6770  6770 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-26 12:46:08.245  6770  6770 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-26 12:46:08.245  6770  6770 D ButtonCombinationReceiver: replacing : false
08-26 12:46:08.264  1036  1059 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8276 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a

```
