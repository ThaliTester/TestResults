#### Test 797638309aa2d44_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 16:54:36.182  6607  6607 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 16:54:36.967  1800  4813 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-26 16:54:37.024  1800  4813 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-26 16:54:37.071  1800  4813 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-26 16:54:37.208   336   421 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-26 16:54:37.214  3188  6643 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-26 16:54:37.255  6607  6607 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:54:37.255  6607  6607 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 16:54:37.374  6644  6644 D AndroidRuntime: 
08-26 16:54:37.374  6644  6644 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 16:54:37.377  6644  6644 D AndroidRuntime: CheckJNI is OFF
08-26 16:54:37.421  6193  6193 I LockScreenSettings: New app installed broadcast received ..
08-26 16:54:37.424  6193  6193 I LockScreenSettings: Number of installed packages  1
08-26 16:54:37.440  6607  6607 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-26 16:54:37.478  6644  6644 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 16:54:37.481  1031  2017 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 16:54:37.498  1031  2319 V SIM_STK : Menu title from STK is T-Mobile
08-26 16:54:37.503  1927  2731 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 16:54:37.507  1031  2017 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 16:54:37.508  1031  2017 D ActivityManager: setTaskToReturnTo : TaskRecord{1a63b52e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 16:54:37.508  1031  2017 D ActivityManager: setTaskToReturnTo : TaskRecord{1a63b52e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 16:54:37.509  1031  2017 D WindowStateEx: AppWindowTokenEx init.. 
08-26 16:54:37.512   342   356 E GBMv2   : DFP En is all cleared set to be enabled
08-26 16:54:37.584  1031  2017 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6679 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 16:54:37.588  6644  6644 D AndroidRuntime: Shutting down VM
08-26 16:54:37.636  1031  1926 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6697 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 16:54:37.656  1927  2731 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 16:54:37.656  1927  2731 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d4c4e2c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 16:54:37.658  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 16:54:37.658  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b56e0f5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 16:54:37.724  6679  6679 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 16:54:37.740  6697  6697 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 16:54:37.740  6697  6697 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-26 16:54:37.785  1031  1051 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6715 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 16:54:37.787  1031  1051 I ActivityManager: Killing 5865:com.google.android.gm/u0a64 (adj 15): empty #17
08-26 16:54:37.814  6679  6679 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 16:54:37.842  1031  1998 W libprocessgroup: failed to open /acct/uid_10064/pid_5865/cgroup.procs: No such file or directory
,08-26 16:54:37.857  6679  6679 I LibraryLoader: Loading: webviewchromium
,08-26 16:54:37.861  6679  6679 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5720-5725)
08-26 16:54:37.861  6679  6679 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 16:54:37.878  6679  6679 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {327310ba}
,08-26 16:54:37.880  6679  6679 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 16:54:37.880  6679  6679 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 16:54:37.886  6715  6715 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-26 16:54:37.892  6679  6679 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 16:54:37.893  6679  6679 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 16:54:37.898  6715  6715 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 16:54:37.901  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 16:54:37.905  6679  6679 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 16:54:37.906  6679  6679 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-26 16:54:37.906  6679  6679 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-26 16:54:37.910   325  2188 V AudioPolicyService: registerClient() client 0xb558a860, uid 10118
08-26 16:54:37.916  1031  1102 D BluetoothManagerService: Message: 20
08-26 16:54:37.916  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ef492c7:true
08-26 16:54:37.919  6679  6679 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 16:54:37.919  6679  6679 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 16:54:37.919  6679  6679 I Adreno-EGL: Build Date: 12/12/14 금
08-26 16:54:37.919  6679  6679 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 16:54:37.919  6679  6679 I Adreno-EGL: Remote Branch: 
08-26 16:54:37.919  6679  6679 I Adreno-EGL: Local Patches: 
08-26 16:54:37.919  6679  6679 I Adreno-EGL: Reconstruct Branch: 
,08-26 16:54:37.935  6484  6484 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-26 16:54:37.937  1031  1907 I ActivityManager: Killing 5711:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-26 16:54:37.948  5689  5689 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 16:54:37.948  5689  5689 W System.err: android.os.DeadObjectException
08-26 16:54:37.948  5689  5689 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 16:54:37.948  5689  5689 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 16:54:37.948  5689  5689 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 16:54:37.948  5689  5689 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 16:54:37.948  5689  5689 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 16:54:37.948  5689  5689 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 16:54:37.948  5689  5689 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 16:54:37.948  5689  5689 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 16:54:37.948  5689  5689 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 16:54:37.948  5689  5689 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 16:54:37.948  5689  5689 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:37.948  5689  5689 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 16:54:37.948  5689  5689 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 16:54:37.948  5689  5689 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 16:54:37.949  5689  5689 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 16:54:37.949  5689  5689 W System.err: android.os.DeadObjectException
08-26 16:54:37.949  5689  5689 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 16:54:37.949  5689  5689 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 16:54:37.949  5689  5689 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 16:54:37.949  5689  5689 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-26 16:54:37.949  5689  5689 W System.err: ,	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 16:54:37.949  5689  5689 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 16:54:37.949  5689  5689 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 16:54:37.949  5689  5689 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-26 16:54:37.949  5689  5689 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 16:54:37.949  5689  5689 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 16:54:37.949  5689  5689 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:54:37.949  5689  5689 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 16:54:37.949  5689  5689 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-26 16:54:37.949  5689  5689 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 16:54:37.949  5689  5689 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,08-26 16:54:37.949  5689  5689 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 16:54:38.061  1031  1925 W libprocessgroup: failed to open /acct/uid_1000/pid_5711/cgroup.procs: No such file or directory
,08-26 16:54:38.062  1031  1925 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-26 16:54:38.073  5689  5689 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 16:54:38.074  5689  5689 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 16:54:38.106  1031  1559 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6755 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 16:54:38.113  5689  5689 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 16:54:38.136  6679  6745 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 16:54:38.146  6679  6679 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 16:54:38.155  1031  1098 W ActivityManager: Activity pause timeout for ActivityRecord{2d3c58cf u0 com.test.thalitest/.MainActivity t6}
,08-26 16:54:38.170  6679  6679 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 16:54:38.174  6679  6679 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 16:54:38.178  6679  6679 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 16:54:38.180  6679  6679 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 16:54:38.180  6679  6679 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-26 16:54:38.189  6755  6755 D UEI.SmartControl: Quickset Services start...
,08-26 16:54:38.191  6755  6755 I UEI.SmartControl: Manufacture = LGE
08-26 16:54:38.192  6755  6755 D UEI.SmartControl: Id = LGNevo
08-26 16:54:38.193  6755  6755 D UEI.SmartControl: File observer start...
08-26 16:54:38.193  6679  6679 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-26 16:54:38.194  6755  6755 E UEI.SmartControl: IR Port is disabled: false
08-26 16:54:38.194  6755  6755 D UEI.SmartControl: Starting file observer...
08-26 16:54:38.194  6755  6755 D UEI.SmartControl: Extracting JNI libs...
08-26 16:54:38.194  6755  6755 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 16:54:38.199  6679  6679 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 16:54:38.199  6679  6679 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 16:54:38.227  6679  6779 D OpenGLRenderer: Render dirty regions requested: true
08-26 16:54:38.227  6679  6779 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 16:54:38.238  6679  6779 D OpenGLRenderer: Enabling debug mode 0
,08-26 16:54:38.249  6679  6679 D Atlas   : Validating map...
,08-26 16:54:38.253  1031  1925 D SplitWindow: check instance of lgWin Window{1486eebc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 16:54:38.285  6679  6777 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:54:38.285  6679  6777 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 16:54:38.303  6755  6755 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 16:54:38.303  6755  6755 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 16:54:38.303  6755  6755 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 16:54:38.340  6755  6755 I UEI.SmartControl: --- Selecting new region: 6
,08-26 16:54:38.342  6755  6755 I UEI.SmartControl: Model = LG-D855
08-26 16:54:38.343  6755  6755 D UEI.SmartControl: QS Service created
08-26 16:54:38.360  6755  6755 I UEI.SmartControl: Service initServices...
08-26 16:54:38.363  6755  6755 D UEI.SmartControl: QS start get config
,08-26 16:54:38.369  1031  1103 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +714ms (total +857ms)
08-26 16:54:38.370  1031  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d3c58cf u0 com.test.thalitest/.MainActivity t6} time:106234
08-26 16:54:38.370  6679  6679 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4bd16d1 time:106234
08-26 16:54:38.414  6755  6755 D UEI.SmartControl: Loading JNI Libs...
,08-26 16:54:38.498  6679  6679 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 16:54:38.498  6679  6679 I chromium: 
,08-26 16:54:38.508  6679  6679 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-26 16:54:38.569  6679  6777 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 16:54:38.569  6679  6777 I chromium: 
,08-26 16:54:38.689  6679  6789 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-26 16:54:38.707  6679  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 16:54:38.707  6679  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 16:54:38.707  6679  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 16:54:38.707  6679  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 16:54:38.707  6679  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 16:54:38.708  6679  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19c852c5 added. We now have 1 listener(s)
,08-26 16:54:38.721  1031  2319 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:54:38.728  6679  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-26 16:54:38.731  6679  6789 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:54:38.733  6679  6789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:54:38.734  6679  6789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 16:54:38.748  6679  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a05928 added. We now have 1 listener(s)
,08-26 16:54:38.749  6679  6789 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:54:38.760  1031  1528 D WifiService: New client listening to asynchronous messages
,08-26 16:54:38.763  6679  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 16:54:38.763  6679  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 16:54:38.764  6679  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 16:54:38.764  6679  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 16:54:38.764  6679  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 16:54:38.768  6679  6789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:38.768  1031  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:54:38.770  6679  6789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-26 16:54:38.779  6679  6789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 16:54:38.780  6679  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:38.780  6679  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:38.780  6679  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:38.780  6679  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:38.780  6679  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:38.780  6679  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:38.780  6679  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:38.780  6679  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:38.780  6679  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 16:54:38.780  6679  6789 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 16:54:38.784  6679  6789 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 16:54:38.785  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:38.789  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:38.811  6755  6755 I UEI.SmartControl: Supports setup maps: true
08-26 16:54:38.814  6755  6755 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 16:54:38.814  6755  6755 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 16:54:38.814  6755  6755 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 16:54:38.814  6755  6755 I UEI.SmartControl: ### init IR Blaster...
,08-26 16:54:38.820  6755  6755 D serial_port: Configuring serial port
08-26 16:54:38.820  6679  6679 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-26 16:54:38.825  6755  6755 E UEI.SmartControl: UEIBLaster setting for 616
08-26 16:54:38.826  6755  6755 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 16:54:38.826  6755  6755 I UEI.SmartControl: configuring settings for MAXQ616
08-26 16:54:38.826  6755  6755 I UEI.SmartControl: Get version...
08-26 16:54:38.843  6755  6793 D UEI.SmartControl: serial port data available: 21
,08-26 16:54:38.870  6755  6755 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 16:54:38.870  6755  6755 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 16:54:38.870  6755  6755 I UEI.SmartControl: QS saving settings...
08-26 16:54:38.871  6755  6755 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 16:54:38.888  6755  6793 D UEI.SmartControl: serial port data available: 4
,08-26 16:54:38.927  6755  6796 I UEI.SmartControl: Device manager: loading config....
,08-26 16:54:38.933  6755  6796 D UEI.SmartControl: ----------- loading internal config...
08-26 16:54:38.936  6755  6755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 16:54:38.938  6755  6755 E UEI.SmartControl: Services init done
08-26 16:54:38.938  6755  6755 D UEI.SmartControl: QS Service init finished
08-26 16:54:38.939  6755  6755 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 16:54:38.939  6755  6755 D UEI.SmartControl: QS Service version code: 201091
,08-26 16:54:38.941  6755  6755 D UEI.SmartControl: Service requested: Control
08-26 16:54:38.946   342   358 E GBMv2   : DFP En is all cleared set to be enabled
08-26 16:54:38.947   342   358 E GBMv2   : Set value is all cleared set the max
08-26 16:54:38.947   342   358 I GBMv2   : DFP Enabled. Ignore VFP set
08-26 16:54:38.948  6755  6796 E UEI.SmartControl: Loading SETTINGS...
08-26 16:54:38.951  6755  6755 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 16:54:38.954  1031  1925 I ActivityManager: Killing 5689:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 16:54:38.962  6755  6796 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 16:54:38.986  6755  6795 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 16:54:38.986  6755  6795 D UEI.SmartControl: -----service ready thread exits
,08-26 16:54:39.037  1031  1889 W libprocessgroup: failed to open /acct/uid_10112/pid_5689/cgroup.procs: No such file or directory
,08-26 16:54:39.041  6755  6755 D UEI.SmartControl: Internal service binding...
08-26 16:54:39.731  6679  6792 W jxcore-log: Initializing JXcore engine
08-26 16:54:39.731  6679  6792 W jxcore-log: JXcore engine is ready
,08-26 16:54:39.755  6792  6792 W Thread-767: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7491]" dev="sockfs" ino=7491 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-26 16:54:39.755  6792  6792 W Thread-767: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 16:54:39.755  6792  6792 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7709]" dev="sockfs" ino=7709 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-26 16:54:39.755  6792  6792 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 16:54:39.755  6792  6792 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31311]" dev="sockfs" ino=31311 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-26 16:54:39.795  6679  6792 W jxcore-log: Starting JXcore engine
,08-26 16:54:39.964  6679  6792 W jxcore-log: Platform android
08-26 16:54:39.964  6679  6792 W jxcore-log: 
08-26 16:54:39.964  6679  6792 W jxcore-log: Process ARCH arm
08-26 16:54:39.964  6679  6792 W jxcore-log: 
,08-26 16:54:40.030  2780  2780 I MusicWidget: mDelayedStopHandler : unbind
,08-26 16:54:40.037  2179  2179 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 16:54:40.038  2179  2179 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 16:54:40.038  2179  2179 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-26 16:54:40.043  2179  2179 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 16:54:40.043  2179  2179 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 16:54:40.044  2179  2179 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,08-26 16:54:40.050  2179  2179 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 16:54:40.050  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-26 16:54:40.051  1031  2319 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1aed955bcom.lge.music.MediaPlaybackService$5@3a0c81f8
08-26 16:54:40.053  2179  2179 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 16:54:40.055  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 16:54:40.057  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 16:54:40.058  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 16:54:40.058  2179  2179 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@15b17e86
08-26 16:54:40.059  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 16:54:40.059  2179  2179 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 16:54:40.060  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 16:54:40.060  2179  2179 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 16:54:40.060  2179  2179 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 16:54:40.061  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 16:54:40.061  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 16:54:40.062  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 16:54:40.063  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 16:54:40.063  2179  2179 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 16:54:40.066  2179  2179 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 16:54:40.068  2179  2179 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 16:54:40.068  2179  2179 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 16:54:40.069  2179  2179 V MediaPlayer[Native]: reset
08-26 16:54:40.076  2179  2179 V MediaPlayer[Native]: setListener
08-26 16:54:40.076  2179  2179 V MediaPlayer[Native]: disconnect
08-26 16:54:40.076  2179  2179 V MediaPlayer[Native]: destructor
08-26 16:54:40.076   325  1369 V AudioFlinger: releasing 18 from 2179 for -1
08-26 16:54:40.076   325  1369 V AudioFlinger:  decremented refcount to 0
08-26 16:54:40.076   325  1369 V AudioFlinger: purging stale effects
08-26 16:54:40.076  2179  2179 V MediaPlayer[Native]: disconnect
08-26 16:54:40.077  2179  2179 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-26 16:54:40.079  2179  2179 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 16:54:40.080  2179  2179 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 16:54:40.082  2179  2179 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-26 16:54:40.082  2179  2179 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 16:54:40.083  2179  2179 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 16:54:40.083  2179  2179 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 79501009
08-26 16:54:40.083  2179  2179 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 79501009
08-26 16:54:40.087  2179  2179 I SmartShareClient: [SmartShareManagerClient] terminate service: 2179/MediaPlaybackService/787417308
08-26 16:54:40.091  2179  2179 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 16:54:40.091  2179  2179 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@181c9536
08-26 16:54:40.093  2179  2179 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 16:54:40.094  2179  2179 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,08-26 16:54:40.095  2179  2179 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 16:54:40.095  2179  2179 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-26 16:54:40.097  1031  1768 I ActivityManager: Killing 5905:com.google.android.talk/u0a72 (adj 15): empty #17
08-26 16:54:40.105  2179  2179 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
08-26 16:54:40.208  1031  1870 W libprocessgroup: failed to open /acct/uid_10072/pid_5905/cgroup.procs: No such file or directory
,08-26 16:54:40.374  6679  6792 I jxcore-log: JXcore Cordova bridge is ready!
08-26 16:54:40.374  6679  6792 I jxcore-log: 
,08-26 16:54:40.375  6679  6792 W jxcore-log: JXcore engine is started
,08-26 16:54:40.381  6679  6789 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 16:54:40.387  6679  6679 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-26 16:54:41.361  6607  6607 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-26 16:54:41.368  1031  1998 I ActivityManager: Killing 6325:com.android.calendar/u0a13 (adj 15): empty #17
08-26 16:54:41.458  1031  1980 W libprocessgroup: failed to open /acct/uid_10013/pid_6325/cgroup.procs: No such file or directory
,08-26 16:54:42.333  6607  6646 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 16:54:43.931  6755  6797 D UEI.SmartControl: Internal timer expired: 1
,08-26 16:54:43.945  6755  6797 D UEI.SmartControl: unbind internal service
,08-26 16:54:43.948  6755  6755 D UEI.SmartControl: Service.onUnbind: IControl
08-26 16:54:43.948  6755  6755 D UEI.SmartControl: Service.onDestroy
08-26 16:54:43.948  6755  6755 D UEI.SmartControl: Lock is in USE false
08-26 16:54:43.948  6755  6755 D UEI.SmartControl: unbind internal service
08-26 16:54:43.949  6755  6755 D serial_port: close(fd = 25)
08-26 16:54:43.952  6755  6755 I UEI.SmartControl: Serial port is closed.
08-26 16:54:43.952  6755  6755 I UEI.SmartControl: Serial port is closed.
08-26 16:54:43.952  6755  6755 D UEI.SmartControl: Blaster closed
08-26 16:54:43.952  6755  6755 D UEI.SmartControl: Shut down QS...
08-26 16:54:43.953  6755  6755 D UEI.SmartControl: Stopping QS lib
08-26 16:54:43.953  6755  6755 D UEI.SmartControl: QS lib stop result = true
08-26 16:54:43.953  6755  6755 D UEI.SmartControl: Stopped QS lib
08-26 16:54:43.953  6755  6755 D UEI.SmartControl: Stopped file observer...
08-26 16:54:43.953  6755  6755 D UEI.SmartControl: QS shutdown complete
08-26 16:54:45.217  1800  6518 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 16:54:45.222   321  6822 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-26 16:54:45.222   321  6822 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1,
08-26 16:54:45.222   321  6822 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-26 16:54:45.447  1800  1800 I ConfigFetchService: fetch service done; releasing wakelock
,08-26 16:54:45.455  1800  1800 I ConfigFetchService: stopping self
08-26 16:54:45.463  2115  2115 I ConfigService: onDestroy
,08-26 16:54:50.117  2179  2179 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
,08-26 16:54:50.170  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 16:54:50.170  6679  6792 I jxcore-log: 
,08-26 16:54:50.173  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 16:54:50.173  6679  6792 I jxcore-log: 
,08-26 16:54:50.178  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:50.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:50.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:50.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:50.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:50.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:50.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:50.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:50.181  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:50.183  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 16:54:50.183  6679  6792 I jxcore-log: 
,08-26 16:54:50.186  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 16:54:50.186  6679  6792 I jxcore-log: 
08-26 16:54:50.312  1031  1098 I ActivityManager: Waited long enough for: ServiceRecord{36b16d1b u0 com.google.android.gms/.wearable.service.WearableService}
,08-26 16:54:50.943  6679  6792 D executeNativeTests: Running unit tests
,08-26 16:54:51.079  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:54:51.079  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 added. We now have 2 listener(s)
,08-26 16:54:51.081  1031  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:54:51.084  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:54:51.084  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:54:51.085  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 16:54:51.085  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:54:51.085  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a added. We now have 2 listener(s)
08-26 16:54:51.085  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:54:51.085  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 16:54:51.088  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:51.092  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:51.092  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.092  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.092  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.092  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:51.092  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.092  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:51.092  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:51.097  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.097  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:54:51.099  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:51.101  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:51.104  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 16:54:51.108  6679  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 16:54:51.108  6679  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 16:54:51.111  6679  6792 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 16:54:51.113  6679  6792 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 16:54:51.113  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 16:54:51.113  6679  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 16:54:51.113  6679  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 16:54:51.113  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.114  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.114  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.115  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.115  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.116  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:51.116  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:54:51.116  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 removed from the list
08-26 16:54:51.116  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.116  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a removed from the list
08-26 16:54:51.116  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.116  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.117  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.117  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:51.121  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.121  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.121  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.121  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.124  6679  6792 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 16:54:51.124  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.125  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.125  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.125  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.125  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.125  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.125  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.125  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.125  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.125  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.125  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.125  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.128  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.128  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.129  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.129  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.129  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.129  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
,08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 16:54:51.140  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 16:54:51.141  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 16:54:51.141  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.142  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.142  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.143  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.143  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.143  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.143  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list,
08-26 16:54:51.143  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.143  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.143  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.143  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.143  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.143  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 16:54:51.143  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:51.150  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.150  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.150  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.150  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.151  6679  6792 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 16:54:51.154  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:51.157  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:51.157  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.157  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.157  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.157  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:51.157  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.157  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:51.157  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:51.161  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.161  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:54:51.163  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:51.164  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:51.165  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 16:54:51.165  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 16:54:51.165  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 16:54:51.165  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:51.165  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 16:54:51.170  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 16:54:51.172  1031  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:54:51.178  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 16:54:51.185  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 16:54:51.189  6679  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 16:54:51.191  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:54:51.192  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:51.193  6679  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 16:54:51.194  6679  6792 I io.jxcore.node.ConnectionHelper: start: OK
08-26 16:54:51.198  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.198  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.198  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 16:54:51.200  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.200  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.200  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:51.200  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.201  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.201  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.201  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.201  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.201  6679  6792 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 16:54:51.205  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:51.208  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:51.208  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.208  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.208  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.208  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:51.208  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.208  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:51.208  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:51.210  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.210  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 16:54:51.214  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:51.215  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:51.216  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 16:54:51.216  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 16:54:51.216  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 16:54:51.216  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:51.216  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 16:54:51.221  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:54:51.221  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:54:51.224  6679  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 16:54:51.224  6679  6792 I io.jxcore.node.ConnectionHelper: start: OK
08-26 16:54:51.226  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.227  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.227  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.227  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.227  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.227  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:51.227  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.227  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.227  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.227  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.227  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.228  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.228  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.229  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.229  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.231  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.231  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.231  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.231  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.232  6679  6792 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 16:54:51.234  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:54:51.240  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:51.240  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.240  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.240  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.240  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:54:51.240  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.240  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:51.240  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:51.242  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.242  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:54:51.244  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:51.245  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:51.246  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 16:54:51.246  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 16:54:51.246  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 16:54:51.246  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:51.246  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 16:54:51.252  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:54:51.253  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:51.254  6679  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 16:54:51.255  6679  6792 I io.jxcore.node.ConnectionHelper: start: OK
08-26 16:54:51.255  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.255  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.255  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.256  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.256  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.256  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.257  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.257  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.257  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:54:51.257  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.257  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.257  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.257  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.257  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.258  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.258  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:51.261  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.261  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.262  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.262  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.262  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.262  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.263  6679  6792 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 16:54:51.263  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.263  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.263  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.264  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.264  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.264  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.264  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.264  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.264  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.264  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.264  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.264  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.264  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.264  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.265  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.265  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.266  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.266  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.266  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.266  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.267  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 16:54:51.268  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.268  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: ,NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.268  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.268  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.268  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.268  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.268  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.268  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.268  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.268  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.268  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.269  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.269  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.269  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.270  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.270  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.275  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.275  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.275  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.275  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.276  6679  6792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 16:54:51.277  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.277  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.277  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.277  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.277  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.277  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.277  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.277  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.277  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.277  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.277  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.277  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.277  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.277  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.279  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.279  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.279  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.279  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.279  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.279  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.280  6679  6792 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 16:54:51.280  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.280  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.280  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.281  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.281  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.281  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.281  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.281  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.281  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.281  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.281  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.281  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.281  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.281  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.283  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.283  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.288  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.288  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.288  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.288  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.289  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 16:54:51.291  6679  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 16:54:51.291  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 16:54:51.291  6679  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 16:54:51.291  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 16:54:51.291  6679  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 16:54:51.291  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.291  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.291  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.292  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.292  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.292  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.292  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.292  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.292  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.292  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.292  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.292  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.292  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.292  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.293  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.293  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.294  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.294  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.294  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.294  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.295  6679  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:51.295  6679  6792 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 16:54:51.295  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 16:54:51.303  6679  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:51.303  6679  6792 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 16:54:51.303  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 16:54:51.304  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 16:54:51.306  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 16:54:51.306  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 16:54:51.306  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 16:54:51.306  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 16:54:51.306  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 16:54:51.306  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 16:54:51.306  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 16:54:51.306  6679  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 16:54:51.306  6679  6792 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 16:54:51.307  6679  6792 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 16:54:51.309  6679  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:51.309  6679  6792 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 16:54:51.309  6679  6792 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 16:54:51.314  6679  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:51.314  6679  6792 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 16:54:51.314  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 16:54:51.316  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 16:54:51.319  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 16:54:51.320  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 16:54:51.320  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 16:54:51.320  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 16:54:51.321  6679  6792 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 16:54:51.321  6679  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 16:54:51.321  6679  6792 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 16:54:51.321  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.321  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.321  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.323  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.323  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.324  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.326  6679  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
08-26 16:54:51.327  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 16:54:51.328  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.328  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.328  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.328  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.328  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.328  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.328  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.328  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.330  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.331  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.335  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.335  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.336  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.336  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.337  6679  6792 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 16:54:51.337  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.337  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.337  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 16:54:51.340  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.341  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.341  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.341  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.341  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.341  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.341  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.341  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.341  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.341  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.341  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.342  6679  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
08-26 16:54:51.343  6679  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 831)
08-26 16:54:51.343  6679  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 831)
08-26 16:54:51.344  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.344  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.344  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.344  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.344  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.345  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.346  6679  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 16:54:51.346  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.347  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.347  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.358  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.358  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.358  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.358  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Conn,ectionManager@27f16e55 not in the list
08-26 16:54:51.358  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.358  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.358  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.358  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.358  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.359  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.359  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:51.364  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.364  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.365  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.365  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.365  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.365  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.366  6679  6792 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 16:54:51.366  6679  6792 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 16:54:51.366  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 16:54:51.366  6679  6792 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 16:54:51.367  6679  6792 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 16:54:51.367  6679  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 16:54:51.367  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 16:54:51.367  6679  6792 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 16:54:51.367  6679  6792 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 16:54:51.367  6679  6792 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 16:54:51.367  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 16:54:51.367  6679  6792 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 16:54:51.367  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:54:51.367  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.367  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.368  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.368  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.368  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.368  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.368  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.369  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.369  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.369  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.369  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:54:51.369  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.369  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.370  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.370  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.371  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.371  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.371  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:51.371  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.371  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.371  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.371  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.371  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.372  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:51.372  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.372  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.372  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.372  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.372  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.372  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
,08-26 16:54:51.372  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.372  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.372  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.372  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.372  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.372  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 16:54:51.372  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 16:54:51.380  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.380  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.380  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.381  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.381  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.381  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.381  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.381  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.381  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.381  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.381  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.383  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.383  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.383  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.383  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.383  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.383  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.387  6679  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 16:54:51.387  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:54:51.398  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-26 16:54:51.399  6679  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 16:54:51.399  6679  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 16:54:51.399  6679  6679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-26 16:54:51.400  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 16:54:51.400  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 16:54:51.401  1031  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:54:51.401  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.401  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-26 16:54:51.401  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 16:54:51.401  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 16:54:51.401  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.401  6679  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 16:54:51.402  6679  6833 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:54:51.402  6679  6679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 16:54:51.402  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.402  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.402  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 16:54:51.403  6679  6792 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 16:54:51.403  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 16:54:51.403  3904  4040 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-26 16:54:51.404  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 16:54:51.404  6679  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 16:54:51.404  6679  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 16:54:51.404  6679  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 16:54:51.405  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:54:51.405  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:54:51.405  6679  6792 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 16:54:51.405  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.405  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.406  6679  6792 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:54:51.407  6679  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 16:54:51.407  6679  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 16:54:51.407  6679  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 16:54:51.407  6679  6679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 16:54:51.409  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.409  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.409  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 16:54:51.409  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.409  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.409  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.409  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.409  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.409  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.409  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.409  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.409  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.409  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.409  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.409  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.411  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 16:54:51.411  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.411  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.412  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.413  6679  6792 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 16:54:51.413  6679  6792 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 16:54:51.413  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 16:54:51.413  6679  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 16:54:51.413  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.414  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.414  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.414  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.414  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.414  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.414  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.414  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.414  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.414  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:54:51.414  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.414  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.414  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.414  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.416  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.416  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.416  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:54:51.416  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.423  1031  2319 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:54:51.426  1031  1631 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:54:51.427  1031  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:54:51.427  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 16:54:51.427  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.427  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.427  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.428  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.428  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.428  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.428  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.428  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.428  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:54:51.428  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.428  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.428  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.428  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.435  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 16:54:51.435  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.435  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.435  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.436  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:54:51.436  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:54:51.436  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:54:51.436  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:54:51.436  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.436  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.437  6679  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f16e55 not in the list
08-26 16:54:51.437  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.437  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.437  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:54:51.437  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.437  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.437  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:54:51.437  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:54:51.438  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:54:51.438  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:54:51.438  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:54:51.438  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28106a not in the list
08-26 16:54:51.440  6679  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 16:54:51.440  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 16:54:51.440  6679  6792 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 16:54:51.440  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 16:54:51.440  6679  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 16:54:51.440  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 16:54:51.442  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 16:54:51.442  66,79  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 16:54:51.442  6679  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 16:54:51.442  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 16:54:51.442  6679  6792 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 16:54:51.443  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 16:54:51.443  6679  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 16:54:51.443  6679  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 16:54:51.443  6679  6792 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 16:54:51.443  6679  6792 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 16:54:51.444  6679  6792 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 16:54:51.444  6679  6792 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 16:54:51.444  6679  6792 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 16:54:51.444  6679  6792 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 16:54:51.445  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:54:51.445  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13ddb8d3 added. We now have 2 listener(s)
08-26 16:54:51.445  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:54:51.446  6679  6792 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 16:54:51.447  1031  1870 D WifiServiceImplEx: setWifiEnabled: true pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 16:54:51.447  1031  1870 D WifiService: setWifiEnabled: true pid=6679, uid=10118
08-26 16:54:51.447  1031  1870 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 16:54:51.448  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:54:51.449  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ea2c10 added. We now have 3 listener(s)
08-26 16:54:51.449  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:54:51.454  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:54:51.454  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3681d309 added. We now have 4 listener(s)
08-26 16:54:51.454  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:54:51.455  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:54:51.455  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@589c90e added. We now have 5 listener(s)
08-26 16:54:51.455  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:54:51.457  1031  1870 D WifiServiceImplEx: setWifiEnabled: false pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 16:54:51.457  1031  1870 D WifiService: setWifiEnabled: false pid=6679, uid=10118
08-26 16:54:51.457  1031  1870 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 16:54:51.478  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 16:54:51.479  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 16:54:51.479  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-26 16:54:51.480  1031  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:51.481  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:51.481  1031  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:51.481  1031  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:51.482  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:51.482  1031  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:54:51.482  1031  1522 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 16:54:51.482  1031  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@ab8a152 mBinding = false
08-26 16:54:51.483  6679  6826 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-26 16:54:51.484  1031  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 16:54:51.484  1031  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 16:54:51.484  6679  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
08-26 16:54:51.484  1031  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 16:54:51.485  1031  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 16:54:51.503  1031  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 16:54:51.503  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 16:54:51.503  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.504  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 16:54:51.504  2658  2658 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 16:54:51.505  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 16:54:51.505  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 16:54:51.505  1031  1522 D WifiNative-wlan0: SET ps 1: returned true
08-26 16:54:51.506  1031  2851 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.507   321   890 D CommandListener: Clearing all IP addresses on wlan0
08-26 16:54:51.513  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 16:54:51.513  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 16:54:51.514  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-26 16:54:51.515  1031  1102 D BluetoothManagerService: Message: 2
,08-26 16:54:51.518  1031  1102 D BluetoothManagerService: Sending off request.
08-26 16:54:51.522  3904  4040 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 16:54:51.522  3904  3996 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 16:54:51.522  3904  3996 D BluetoothAdapterProperties: Setting state to 13
08-26 16:54:51.523  3904  3996 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 16:54:51.523  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:54:51.523  3904  3996 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 16:54:51.523  3904  3996 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 16:54:51.524  1031  1102 D BluetoothManagerService: Message: 60
08-26 16:54:51.524  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 16:54:51.524  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 16:54:51.536  3904  3904 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:51.536  3904  3904 D BluetoothMapService: STATE_TURNING_OFF
08-26 16:54:51.537  3904  3904 V BluetoothMapService: Handler(): got msg=4
08-26 16:54:51.537  3904  3904 D BluetoothMapService: MAP Service closeService in
08-26 16:54:51.537  3904  3904 D BluetoothMapMasInstance: MAP Service shutdown
08-26 16:54:51.537  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.537  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:54:51.537  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.537  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.537  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.537  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.537  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.537  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:51.537  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:54:51.539  3904  4209 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 16:54:51.539  3904  4209 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:54:51.539  3904  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 16:54:51.539  3904  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 16:54:51.539  3904  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 16:54:51.539  3904  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 16:54:51.539  3904  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 16:54:51.539  3904  4209 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 16:54:51.539  3904  3904 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 16:54:51.539  3904  3904 V BluetoothMapService: MAP Service closeService out
08-26 16:54:51.539  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:51.540  3904  3904 V BtOppService: Receiver DISABLED_ACTION 
08-26 16:54:51.541  3904  3904 I BtOppRfcommListener: stopping Accept Thread
08-26 16:54:51.541  3904  3904 V BtOppRfcommListener: close mBtServerSocket
08-26 16:54:51.541  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 16:54:51.541  3904  3904 V BtOppRfcommListener: waiting for thread to terminate
08-26 16:54:51.541  3904  4249 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:54:51.542  3904  4249 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 16:54:51.542  3904  3904 V BtOppRfcommListener: done waiting for thread to terminate
08-26 16:54:51.543  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.543  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:54:51.543  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:54:51.546  1031  1907 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-26 16:54:51.547  1031  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.547  1031  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.547  1031  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 16:54:51.547  1031  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.547  1031  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 16:54:51.548  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:51.549  1031  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 16:54:51.549  1031  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-26 16:54:51.554  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.554  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:51.554  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.554  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.554  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.554  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.554  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:51.554  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:54:51.554  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:51.556  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.556  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:51.559  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.559  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:51.559  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.559  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.559  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.559  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.559  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:51.559  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:51.559  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:51.560  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.560  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:51.562  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.562  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:51.562  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.562  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.562  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:51.562  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.562  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:51.562  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:51.562  6679  6679 V io.jxcore.node.Con,nectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:51.593  1031  1098 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6853 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 16:54:51.595  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.595  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.596  1031  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@32eedbe8
08-26 16:54:51.596  1031  1521 D LGWifiP2pService: P2pDisablingState
,08-26 16:54:51.596  1031  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.596  1031  1521 D LGWifiP2pService: p2p socket connection lost
08-26 16:54:51.596  1031  1521 D LGWifiP2pService: P2pDisabledState
08-26 16:54:51.599  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 16:54:51.599  3904  3904 V BtOppService: onDestroy
08-26 16:54:51.602  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-26 16:54:51.602  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:51.602  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:51.603  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 16:54:51.603  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-26 16:54:51.603  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:51.603  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:51.603  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 16:54:51.603  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 16:54:51.603  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-26 16:54:51.603  1031  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.604  1031  1541 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.604  1031  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:51.605  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 16:54:51.605  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:51.605  1031  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:51.606  1031  1522 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 16:54:51.606  1031  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:51.607  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 16:54:51.607  1031  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:51.607   321  6863 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 16:54:51.607  1031  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 16:54:51.607  1031  1529 D DSQN    : disableDataServiceNotify
08-26 16:54:51.608  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 16:54:51.608  1031  1529 D DSQN    : stop dsqn bin
08-26 16:54:51.608  1031  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:51.609  1031  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-26 16:54:51.609  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:51.609  1031  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:51.609  1031  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 16:54:51.610  1927  1927 D WfdsService: WifiP2pState is changed : false
08-26 16:54:51.610  1927  2231 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 16:54:51.610  1927  2231 D WfdsService: Set the WFDS Monitor: false
08-26 16:54:51.610  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.610  1031  1521 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.610  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 16:54:51.610  2658  2658 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 16:54:51.611  1927  2231 D WfdsMonitor: WFDS Monitor is stopped
08-26 16:54:51.611  1927  2724 D CtrlSupplicant: Received on exit socket, terminate
08-26 16:54:51.611  1927  2724 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 16:54:51.611  1927  2231 D WfdsService: STATE : WfdsDisabledState - enter
08-26 16:54:51.611  1927  2724 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 16:54:51.611  1927  2724 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 16:54:51.611  1927  2231 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 16:54:51.611  1927  2235 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 16:54:51.613  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 16:54:51.613  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 16:54:51.613  1031  1522 D WifiNative-wlan0: SET ps 1: returned true
08-26 16:54:51.613   321   890 D CommandListener: Clearing all IP addresses on wlan0
08-26 16:54:51.618  1031  1522 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 16:54:51.618  1031  1522 D WifiNative-p2p0: TERMINATE: returned true
08-26 16:54:51.619  1031  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 16:54:51.619  1031  1522 E WifiStateMachine: useWiFiOffloading() : false
08-26 16:54:51.619  1031  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 16:54:51.620  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:51.620  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:51.621  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-26 16:54:51.622  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:51.622  1031  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 16:54:51.622  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:51.622  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 16:54:51.622  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:51.622  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:54:51.622  1031  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:54:51.624  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 16:54:51.625  1031  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 16:54:51.625  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:51.625  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.625  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:51.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:51.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:51.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:51.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:51.625  1031  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 16:54:51.626  1031  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.626  1031  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.andr,oid.internal.util.StateMachine$SmHandler }
08-26 16:54:51.626  1031  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 16:54:51.626  1587  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 16:54:51.627  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.627  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:51.627  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 16:54:51.627  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:54:51.627  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 16:54:51.628  1031  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 16:54:51.628  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 16:54:51.628  1031  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:51.628  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 16:54:51.628  1031  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:51.628  1031  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:51.629  1031  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:51.629  1031  1529 D NetworkManagementService: Removing idletimer
08-26 16:54:51.629  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:51.629  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 16:54:51.629  1031  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:51.630  1031  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 16:54:51.630  1031  1522 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:51.630  1031  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 16:54:51.631  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.631  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:51.631  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.631  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.631  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:51.631  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.631  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:51.631  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:51.631  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:51.632  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.632  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:51.633  1031  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 16:54:51.633  1031  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 16:54:51.635  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 16:54:51.635  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 16:54:51.635  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 16:54:51.635  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 16:54:51.63,5  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 16:54:51.635  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 16:54:51.635  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 16:54:51.635  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 16:54:51.640  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:51.644  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:51.644  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:51.645  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:51.646  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 16:54:51.646  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:51.647  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:51.648  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:54:51.674  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 16:54:51.675  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:51.675  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:51.685  1031  1926 I art     : Explicit concurrent mark sweep GC freed 41279(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.365ms total 157.002ms
08-26 16:54:51.686  3904  4001 D BluetoothAdapterProperties: Scan Mode:20
,08-26 16:54:51.686  3904  3996 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 16:54:51.686  3904  4251 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:54:51.686  3904  3996 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 16:54:51.686  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 16:54:51.687  3904  4077 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 16:54:51.687  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 16:54:51.687  3904  4077 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 16:54:51.688  3904  4210 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:54:51.688  3904  4253 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:54:51.693  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.693  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:51.693  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.693  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.693  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:51.693  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.693  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:51.693  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:51.693  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:51.695  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:51.695  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:51.695  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:51.695  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:51.695  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:51.695  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:51.695  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:51.695  ,6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:51.695  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:51.717  1031  1962 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6872 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 16:54:51.720  1031  2851 D DhcpStateMachine: StoppedState
08-26 16:54:51.720  1031  2851 D DhcpStateMachine: StoppedState{ when=-107ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:51.720  1031  1522 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 16:54:51.721  1031  1522 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 16:54:51.723  3904  3904 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 16:54:51.726  2658  2658 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 16:54:51.726  2658  2658 I wpa_supplicant: monitor socket send errors count : 1
08-26 16:54:51.726  2658  2658 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
08-26 16:54:51.727  1031  2700 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 16:54:51.727  1031  2700 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 16:54:51.727  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 16:54:51.727  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:51.728  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:51.728   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 296us total 11.039ms
08-26 16:54:51.737  6853  6853 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 16:54:51.737  6853  6853 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-26 16:54:51.737  6853  6853 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 16:54:51.737  6853  6853 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-26 16:54:51.738   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 9.444ms
08-26 16:54:51.738  6853  6853 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 16:54:51.738  6853  6853 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 16:54:51.742  1031  1400 V AlarmManager: RTC_WAKEUP set : Alarm{26fee34c type 0 when 1472223290797 com.android.vending} when 1472223290797
08-26 16:54:51.742  1031  1400 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c901f95 type 2 when 119474 com.google.android.gms} when 119474
08-26 16:54:51.747   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 8.945ms
08-26 16:54:51.757  2658  2658 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 16:54:51.757  1031  2700 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 16:54:51.757  1031  2700 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 16:54:51.758  1031  2700 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 16:54:51.758  1031  2700 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 16:54:51.758  2658  2658 W wpa_supplicant: USIM:  scard_deinit function
,08-26 16:54:51.759  1031  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=119610
08-26 16:54:51.759  1031  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=119610
08-26 16:54:51.759  1031  1102 D Tethering: InitialState.processMessage what=4
08-26 16:54:51.760  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 16:54:51.760  1031  2700 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:54:51.760  1031  2700 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:54:51.761  1031  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=119612  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 16:54:51.761  1031  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=119612  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 16:54:51.762  1031  1522 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:51.762  1031  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:51.779  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 16:54:51.787  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 16:54:51.787  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:54:51.792  1031  1998 V SIM_STK : Menu title from STK is T-Mobile
,08-26 16:54:51.838  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 16:54:51.841  3904  3904 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 16:54:51.841  3904  3904 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:51.841  3904  3904 V BluetoothPbapReceiver: ***********state = 13
08-26 16:54:51.841  3904  3904 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 16:54:51.842  3904  3904 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:51.842  3904  3904 V BluetoothPbapService: state: 13
08-26 16:54:51.842  3904  3904 V BluetoothPbapService: Pbap Service closeService in
08-26 16:54:51.844  3904  3904 V BluetoothPbapService: successfully stopped pbap service
08-26 16:54:51.844  3904  3904 V BluetoothPbapService: Pbap Service closeService out
08-26 16:54:51.844  3904  3904 V BluetoothPbapService: Pbap Service onDestroy
08-26 16:54:51.844  3904  3904 V BluetoothPbapService: Pbap Service closeService in
08-26 16:54:51.844  3904  3904 V BluetoothPbapService: Pbap Service closeService out
08-26 16:54:51.844  3904  3904 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 16:54:51.845  2115  2115 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 16:54:51.855  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:51.886  1031  1051 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6893 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 16:54:51.889  2658  2658 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 16:54:51.889  1031  2700 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 16:54:51.889  1031  2700 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 16:54:51.889  1031  2700 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 16:54:51.890  1031  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-26 16:54:51.901  6853  6853 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:54:51.902  6853  6853 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 16:54:51.908  6679  6679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 16:54:51.913  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:51.922  1031  1102 D BluetoothManagerService: Message: 20
,08-26 16:54:51.923  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bdce838:true
08-26 16:54:51.938  1031  1102 D BluetoothManagerService: Message: 30
,08-26 16:54:51.944  1031  1102 D BluetoothManagerService: Message: 30
08-26 16:54:51.947  6853  6853 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 16:54:51.949  6853  6853 D BluetoothMap: Create BluetoothMap proxy object
08-26 16:54:51.949  1031  1102 D BluetoothManagerService: Message: 30
,08-26 16:54:51.956  1031  1102 D BluetoothManagerService: Message: 30
08-26 16:54:51.959  6853  6853 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 16:54:51.960  6853  6853 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-26 16:54:51.975  6853  6853 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-26 16:54:51.978  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-26 16:54:51.992  1031  1522 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 16:54:51.992  1031  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 16:54:51.992  1031  1522 E WifiStateMachine: useWiFiOffloading() : false
08-26 16:54:51.992  1031  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 16:54:51.992  1927  1927 D WfdsService: Supplicant Connection state is changed : false
,08-26 16:54:51.992  1927  2231 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 16:54:51.992  1927  2231 D WfdsService: Set the WFDS Monitor: false
08-26 16:54:51.992  1927  2231 D WfdsMonitor: WFDS Monitor is stopped
08-26 16:54:51.994  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 16:54:51.995  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:51.996  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 16:54:51.997  1031  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 16:54:51.997  1031  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 16:54:51.998  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:51.999  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:52.000  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:52.001  6853  6853 D DockEventReceiver: finishStartingService: stopping service
08-26 16:54:52.014  6155  6155 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-26 16:54:52.015  6893  6893 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 16:54:52.015  6893  6893 W LG Account v2.2: No ProfileInfo entries
08-26 16:54:52.015  6893  6893 I LG Account v2.2: isEnabled: false
,08-26 16:54:52.015  6893  6893 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 16:54:52.016  6893  6893 I Feature : [Lifetracker]Country: EU
08-26 16:54:52.017  6893  6893 I Feature : [Lifetracker]Operator: OPEN
08-26 16:54:52.017  6893  6893 I Feature : [Lifetracker]Ranking support: false
08-26 16:54:52.017  6893  6893 I Feature : [Lifetracker]Comfort support: false
08-26 16:54:52.017  6893  6893 I Feature : [Lifetracker]Accessory: true
08-26 16:54:52.017  6893  6893 I Feature : [Lifetracker]Health device: true
08-26 16:54:52.017  6893  6893 I Feature : [Lifetracker]Extra Pedometer: false
08-26 16:54:52.017  6893  6893 I Feature : [Lifetracker]Blood glucose device: false
08-26 16:54:52.017  6893  6893 I Feature : [Lifetracker]Device Number: 3
08-26 16:54:52.020  1031  1889 I ActivityManager: Killing 6271:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-26 16:54:52.022  6853  6853 D BluetoothInputDevice: Proxy object connected
08-26 16:54:52.023  6853  6853 D HidProfile: Bluetooth service connected
08-26 16:54:52.024  6853  6853 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 16:54:52.024  6853  6853 D PanProfile: Bluetooth service connected
08-26 16:54:52.025  6853  6853 D BluetoothMap: Proxy object connected
08-26 16:54:52.026  6853  6853 D MapProfile: Bluetooth service connected
08-26 16:54:52.026  6853  6853 D BluetoothMap: getConnectedDevices()
08-26 16:54:52.027  6853  6853 D BluetoothMap: Bluetooth is Not enabled
08-26 16:54:52.027  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-26 16:54:52.050  1031  1870 W libprocessgroup: failed to open /acct/uid_10014/pid_6271/cgroup.procs: No such file or directory
,08-26 16:54:52.053  1031  1889 I ActivityManager: Killing 6363:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 16:54:52.081  1031  1051 W libprocessgroup: failed to open /acct/uid_10004/pid_6363/cgroup.procs: No such file or directory
,08-26 16:54:52.087  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 16:54:52.095  6853  6853 D BluetoothPermissionRequest: onReceive
08-26 16:54:52.101  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 16:54:52.113  1031  1889 I ActivityManager: Killing 6525:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-26 16:54:52.116  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 16:54:52.172  3904  3904 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-26 16:54:52.173  3904  3904 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 16:54:52.174  3904  3904 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 16:54:52.178  1031  1925 W libprocessgroup: failed to open /acct/uid_10008/pid_6525/cgroup.procs: No such file or directory
08-26 16:54:52.262  1031  1889 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6920 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 16:54:52.268  3904  3904 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:52.269  3904  3904 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 16:54:52.271  3904  3904 V BluetoothFtpService: Ftp Service onStartCommand
08-26 16:54:52.271  3904  3904 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:52.271  3904  3904 V BluetoothFtpService: Ftp Service closeService
08-26 16:54:52.271  3904  3904 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 16:54:52.273  3904  3904 V BluetoothFtpService: successfully stopped ftp service
08-26 16:54:52.273  3904  3904 V BluetoothFtpService: Ftp Service onDestroy
08-26 16:54:52.273  3904  3904 V BluetoothFtpService: Ftp Service closeService
08-26 16:54:52.276  3904  3904 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 16:54:52.276  3904  3904 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 16:54:52.276  3904  3904 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 16:54:52.276  3904  3904 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:52.276  3904  3904 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 16:54:52.276  3904  3904 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-26 16:54:52.280  3904  3904 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:52.280  3904  3904 V BluetoothSapService: state: 13
08-26 16:54:52.280  3904  3904 V BluetoothSapService: Stopping SAP server process
08-26 16:54:52.282  3904  3904 V BluetoothSapService: Sap Service closeSapService in
08-26 16:54:52.282  3904  3904 V BluetoothSapService: Close listen Socket : 
08-26 16:54:52.282  3904  3904 V BluetoothSapService: Close rfcomm Socket : 
08-26 16:54:52.282  3904  3904 V BluetoothSapService: Close sapd  Socket : 
08-26 16:54:52.347  1031  1631 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6940 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 16:54:52.360  3904  3904 V BluetoothSapService: Sap Service closeSapService out
,08-26 16:54:52.362  3904  3904 V BluetoothSapService: Sap Service onDestroy
08-26 16:54:52.362  3904  3904 V BluetoothSapService: Sap Service closeSapService in
08-26 16:54:52.362  3904  3904 V BluetoothSapService: Close listen Socket : 
08-26 16:54:52.362  3904  3904 V BluetoothSapService: Close rfcomm Socket : 
08-26 16:54:52.362  3904  3904 V BluetoothSapService: Close sapd  Socket : 
08-26 16:54:52.363  3904  3904 V BluetoothSapService: Sap Service closeSapService out
08-26 16:54:52.385  6920  6920 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 16:54:52.410  6940  6940 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 16:54:52.421  6920  6920 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-26 16:54:52.428  1031  1961 I ActivityManager: Killing 6085:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-26 16:54:52.460  6920  6920 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-26 16:54:52.460  6920  6920 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 16:54:52.461  6920  6920 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 16:54:52.461  6920  6920 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 16:54:52.462  6920  6920 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 16:54:52.464  6920  6920 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 16:54:52.469  6920  6920 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 16:54:52.472  1031  1870 W libprocessgroup: failed to open /acct/uid_10011/pid_6085/cgroup.procs: No such file or directory
,08-26 16:54:52.481  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:52.484  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:52.503  6920  6920 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 16:54:52.507  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:52.510  6920  6920 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 16:54:52.513  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 16:54:52.513  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 16:54:52.513  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:54:52.513  6920  6920 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 16:54:52.522  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:52.532  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:52.540  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 16:54:52.542  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:54:52.544  6920  6920 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 16:54:52.547  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:52.550  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 16:54:52.550  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 16:54:52.550  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:54:52.554  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:52.561  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 16:54:52.570  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:52.571  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:52.573  6920  6920 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 16:54:52.624  1031  1998 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6960 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 16:54:52.692  3904  4001 D bt_hci_bdroid: cleanup
08-26 16:54:52.692  3904  4077 W bt-btif : ag scb idx 1 not allocated
08-26 16:54:52.692  3904  4077 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 16:54:52.692  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:54:52.693  3904  4077 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:54:52.693  3904  4077 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:54:52.693  3904  4077 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 16:54:52.693  3904  4077 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 16:54:52.693  3904  4181 I bt_userial_mct: exiting userial_read_thread
08-26 16:54:52.693  3904  4181 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 16:54:52.693  3904  4001 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 16:54:52.694  3904  4079 I bt_lpm  : LPM is already off!!!
08-26 16:54:52.694  3904  4079 I bt_vendor: hw_epilog_process
08-26 16:54:52.694  3904  4001 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 16:54:52.694  3904  4001 D bt_userial_mct: userial_close
08-26 16:54:52.694  3904  4001 E bt_userial_mct: pthread_join() FAILED result:3
08-26 16:54:52.694  3904  4001 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 16:54:52.743  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 16:54:52.751  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 16:54:52.767  6960  6980 W FormManager: Network not available. Please check & try again.
08-26 16:54:52.768  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:52.789  3904  4001 D bt_hci_bdroid: set_power 0
08-26 16:54:52.789  3904  4001 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 16:54:52.789  3904  4001 I bt_vendor: bluetooth satus is on
08-26 16:54:52.789  3904  4001 I bt_vendor: bt-vendor : resetting BT status
08-26 16:54:52.789  3904  4001 I bt_vendor: Starting hciattach daemon
08-26 16:54:52.789  3904  4001 I bt_vendor: try to set false
08-26 16:54:52.790  3904  4001 I bt_vendor: Starting hciattach daemon
08-26 16:54:52.790  3904  4001 I bt_vendor: try to set false
08-26 16:54:52.792  3904  4001 I bt_vendor: cleanup
,08-26 16:54:52.795  3904  4077 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 16:54:52.806   321  6984 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 16:54:52.807  3904  4001 I GKI_LINUX: GKI_exit_task 0 done
08-26 16:54:52.807  3904  4001 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 16:54:52.808  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 16:54:52.810  3904  3996 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 16:54:52.815  3904  3904 D HeadsetService: Received stop request...Stopping profile...
08-26 16:54:52.817  3904  3904 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 16:54:52.817  3904  3904 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 16:54:52.817  3904  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33f2fb6b
08-26 16:54:52.817  3904  4030 D HeadsetStateMachine: Exit Disconnected: -1
08-26 16:54:52.821  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:52.821  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:52.821  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:52.821  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-26 16:54:52.821  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 16:54:52.823  3904  3904 D A2dpService: Received stop request...Stopping profile...
08-26 16:54:52.823  3904  4060 D A2dpStateMachine: Exit Disconnected: -1
08-26 16:54:52.825  3904  3904 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 16:54:52.826  3904  3996 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 16:54:52.827  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 16:54:52.827  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 16:54:52.828  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 16:54:52.828  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 16:54:52.828  3904  3904 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 16:54:52.829  3904  3904 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 16:54:52.829  3904  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33f2fb6b
08-26 16:54:52.829  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-26 16:54:52.829  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 16:54:52.830  3904  3904 D HeadsetStateMachine: Unbinding service...
08-26 16:54:52.831  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 16:54:52.831  3904  3904 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 16:54:52.831  3904  3904 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 16:54:52.831  3904  3904 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 16:54:52.831  3904  3904 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 16:54:52.831  3904  3904 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 16:54:52.831  3904  3904 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 16:54:52.831  3904  3904 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 16:54:52.832  3904  3904 D HidService: Received stop request...Stopping profile...
08-26 16:54:52.832  3904  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33f2fb6b
08-26 16:54:52.833  6960  6981 V FormManager: Network unavailable.
,08-26 16:54:52.833  3904  3904 D HealthService: Received stop request...Stopping profile...
08-26 16:54:52.834  3904  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33f2fb6b
08-26 16:54:52.835  3904  3904 D PanService: Received stop request...Stopping profile...
08-26 16:54:52.836  3904  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33f2fb6b
,08-26 16:54:52.836  3904  3904 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 16:54:52.837  3904  3904 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 16:54:52.837  3904  3904 D BtGatt.GattService: stop()
08-26 16:54:52.837  3904  3904 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 16:54:52.838  3904  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33f2fb6b
08-26 16:54:52.839  3904  3904 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 16:54:52.839  3904  3904 D BluetoothMapService: stop()
08-26 16:54:52.840  3904  3904 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 16:54:52.840  3904  3904 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 16:54:52.841  3904  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33f2fb6b
08-26 16:54:52.842  6960  6981 V FormManager: Network unavailable.
08-26 16:54:52.842  3904  3904 I BluetoothA2dpServiceJni: cleanupNative
08-26 16:54:52.843  3904  4061 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 16:54:52.843  3904  3904 I GKI_LINUX: GKI_exit_task 2 done
08-26 16:54:52.843  3904  3904 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 16:54:52.843  3904  3904 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 16:54:52.843  3904  3904 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 16:54:52.843  3904  3904 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 16:54:52.843  3904  3904 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 16:54:52.843  3904  3904 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 16:54:52.844  3904  3904 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 16:54:52.844  3904  3904 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 16:54:52.845  3904  3904 V BluetoothMapService: Handler(): got msg=4
08-26 16:54:52.845  3904  3904 D BluetoothMapService: MAP Service closeService in
08-26 16:54:52.845  3904  3904 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 16:54:52.845  3904  3904 V BluetoothMapService: MAP Service closeService out
08-26 16:54:52.845  3904  3904 D BluetoothMapService: cleanup()
08-26 16:54:52.845  3904  3904 D BluetoothMapService: MAP Service closeService in
08-26 16:54:52.845  3904  3904 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 16:54:52.845  3904  3904 V BluetoothMapService: MAP Service closeService out
08-26 16:54:52.845  3904  3996 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 16:54:52.845  3904  3996 D BluetoothAdapterProperties: Setting state to 10
08-26 16:54:52.845  3904  3996 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 16:54:52.846  1031  1102 D BluetoothManagerService: Message: 60
08-26 16:54:52.846  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 16:54:52.846  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 16:54:52.846  3904  3996 I BluetoothAdapterState: Entering OffState
08-26 16:54:52.846  6853  6870 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 16:54:52.847  6853  6871 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 16:54:52.848  6853  6870 D BluetoothPan: onBluetoothStateChange on: false
08-26 16:54:52.848  6853  6871 D BluetoothMap: onBluetoothStateChange: up=false
08-26 16:54:52.849  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:52.849  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 16:54:52.849  1836  2414 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:52.850  1836  4028 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:52.850  1836  4037 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:54:52.851  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 16:54:52.852  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 16:54:52.854  1031  1102 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 16:54:52.854  1031  1102 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 16:54:52.854  1031  1102 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBlue,tooth$Stub$Proxy@ab8a152 mBinding = false
08-26 16:54:52.854  1031  1102 D BluetoothManagerService: Sending unbind request.
,08-26 16:54:52.862  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 16:54:52.863  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:52.864  1927  2090 D LGBluetoothAPIService: Message: 2
08-26 16:54:52.864  1927  2090 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@f069e8a mBinding = false
08-26 16:54:52.864  1927  2090 D LGBluetoothAPIService: Sending unbind request.
,08-26 16:54:52.865  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 16:54:52.866  3904  4001 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 16:54:52.868  3904  3904 I GKI_LINUX: GKI_exit_task 1 done
08-26 16:54:52.868  3904  3904 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 16:54:52.868  3904  3904 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 16:54:52.868  3904  3904 I art     : --- WEIRD: removing null entry 246
08-26 16:54:52.868  3904  3904 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 16:54:52.868  3904  3904 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 16:54:52.869  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:52.870  1587  1587 D BluetoothAdapter: 670587747: getState() :  mService = null. Returning STATE_OFF
08-26 16:54:52.870  1587  1587 D BluetoothAdapter: 670587747: getState() :  mService = null. Returning STATE_OFF
08-26 16:54:52.870  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:52.871  3904  3904 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-26 16:54:52.872  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 16:54:52.872  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 16:54:52.872  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 16:54:52.872  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 16:54:52.872  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 16:54:52.873  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 16:54:52.874  3904  3904 I art     : System.exit called, status: 0
08-26 16:54:52.874  3904  3904 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 16:54:52.876  6853  6853 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 16:54:52.877  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 16:54:52.877  6853  6853 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 16:54:52.879  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 16:54:52.879  1031  2017 I ActivityManager: Killing 6107:com.android.contacts/u0a19 (adj 15): empty #17
08-26 16:54:52.883  4528  6985 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 16:54:52.893   325  1368 V AudioFlinger: 3904 died, releasing its sessions
08-26 16:54:52.893   325  1368 V AudioFlinger:  pid 1836 @ 0
08-26 16:54:52.893   325  1368 V AudioFlinger:  pid 3439 @ 1
08-26 16:54:52.893   325  1368 V AudioFlinger:  pid 3439 @ 2
08-26 16:54:52.927  1031  2017 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
08-26 16:54:52.927  1031  2017 W BroadcastQueue: android.os.DeadObjectException
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-26 16:54:52.927  1031  2017 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 16:54:52.936  1031  2017 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-26 16:54:53.011  1031  2017 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6997 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 16:54:53.018  1031  1925 W ActivityManager: Spurious death for ProcessRecord{3aaede51 6997:com.android.bluetooth/1002}, curProc for 3904: null
08-26 16:54:53.018  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 16:54:53.018  1031  1870 W libprocessgroup: failed to open /acct/uid_10019/pid_6107/cgroup.procs: No such file or directory
08-26 16:54:53.022  1031  1400 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1f090c75 type 2 when 120802 com.google.android.gms} when 120802
08-26 16:54:53.027  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 16:54:53.027  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 16:54:53.030  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:54:53.033  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:54:53.039  6853  6853 D DockEventReceiver: finishStartingService: stopping service
08-26 16:54:53.048  6872  6872 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 16:54:53.048  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 16:54:53.048  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 16:54:53.051  4356  7017 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 16:54:53.051  4356  7017 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 16:54:53.053  4356  7013 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 16:54:53.056  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 16:54:53.057  6960  7018 W FormManager: Network not available. Please check & try again.
08-26 16:54:53.060  6960  7019 V FormManager: Network unavailable.
,08-26 16:54:53.062  6960  7019 V FormManager: Network unavailable.
08-26 16:54:53.067  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:53.085  6997  6997 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 16:54:53.085  6997  6997 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 16:54:53.085  6920  6920 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 16:54:53.085  6997  6997 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 16:54:53.086  6997  6997 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 16:54:53.087  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 16:54:53.088  6920  6920 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 16:54:53.101  6997  6997 D BluetoothAdapterApp: Loading JNI Library
,08-26 16:54:53.122  6997  6997 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@135b81b0 Instance Count = 1
,08-26 16:54:53.123  6920  6920 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:54:53.124  6920  6920 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 16:54:53.126  6997  6997 D BluetoothAdapterApp: onCreate
08-26 16:54:53.130  6920  6920 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 16:54:53.131  6920  6920 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 16:54:53.131  6920  6920 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 16:54:53.131  6920  6920 V SoundPool: doLoad: loading sample sampleID=1
08-26 16:54:53.131  6920  6920 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 16:54:53.132  6920  7024 V SoundPool: Start decode
08-26 16:54:53.132  6920  7024 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 16:54:53.133   325  1369 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 16:54:53.133   325  1369 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 16:54:53.133   325  1369 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 16:54:53.133   325  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 16:54:53.133   325  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 16:54:53.133   325  1369 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 16:54:53.133   325  1369 V MediaPlayerService: player type = 3
08-26 16:54:53.133   325  1369 V AwesomePlayer: AwesomePlayer create()
08-26 16:54:53.133   325  1369 V AwesomePlayer: reset_l() 
08-26 16:54:53.133   325  1369 V AwesomePlayer: cancelPlayerEvents
08-26 16:54:53.133   325  1369 V AwesomePlayer: setAudioSink() 
08-26 16:54:53.133   325  1369 V AwesomePlayer: reset_l() 
08-26 16:54:53.133   325  1369 V AudioCache: notify(0xb1432480, 8, 0, 0)
,08-26 16:54:53.133   325  1369 V AudioCache: ignored
08-26 16:54:53.133   325  1369 V AwesomePlayer: cancelPlayerEvents
08-26 16:54:53.133   325  1369 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 16:54:53.134   325  1369 V AwesomePlayer: setDataSource_l dataSource
08-26 16:54:53.134   325  1369 V LGParserOSAL: SniffLGParser start
08-26 16:54:53.134   325  1369 V LGParserOSAL: MainType:5, SubType=0
08-26 16:54:53.134   325  1369 V LGParserOSAL: #### check Mime : application/ogg
08-26 16:54:53.134   325  1369 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 16:54:53.134   325  1369 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 16:54:53.134  6920  6920 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 16:54:53.135  6920  6920 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 16:54:53.138  6755  6755 D UEI.SmartControl: QS Service created
08-26 16:54:53.143  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 16:54:53.146  6997  6997 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 16:54:53.146  6997  6997 D ProfileConfigQcom: Adding HeadsetService
08-26 16:54:53.146  6997  6997 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 16:54:53.146  6997  6997 D ProfileConfigQcom: Adding A2dpService
08-26 16:54:53.146  6997  6997 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 16:54:53.147  6997  6997 D ProfileConfigQcom: Adding HidService
08-26 16:54:53.147  6997  6997 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 16:54:53.147  6997  6997 D ProfileConfigQcom: Adding HealthService
08-26 16:54:53.147  6997  6997 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 16:54:53.147  6997  6997 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 16:54:53.148  6997  6997 D ProfileConfigQcom: Adding PanService
08-26 16:54:53.148  6997  6997 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 16:54:53.148  6997  6997 D ProfileConfigQcom: Adding GattService
08-26 16:54:53.148  6997  6997 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-26 16:54:53.148  6997  6997 D ProfileConfigQcom: Adding BluetoothMapService
,08-26 16:54:53.148  6997  6997 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 16:54:53.149  6997  6997 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 16:54:53.149  6997  6997 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:53.150  6997  6997 V BluetoothPbapReceiver: ***********state = 10
08-26 16:54:53.151  6997  6997 V LGMDMManagerInternal: Create singleton instance
08-26 16:54:53.162  6755  6755 I UEI.SmartControl: Service initServices...
08-26 16:54:53.162  6755  6755 D UEI.SmartControl: QS start get config
08-26 16:54:53.165   325  1369 V LGParserOSAL: supported mime: application/ogg
08-26 16:54:53.165   325  1369 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 16:54:53.165   325  1369 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 16:54:53.165   325  1369 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 16:54:53.165   325  1369 V AwesomePlayer: AudioTrack Setting
08-26 16:54:53.165   325  1369 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 16:54:53.165   325  1369 V AwesomePlayer: setAudioSource() 
08-26 16:54:53.165   325  1369 V MediaPlayerService: prepare
08-26 16:54:53.165   325  1369 V AwesomePlayer: prepareAsync_l() 
,08-26 16:54:53.165   325  1369 V MediaPlayerService: wait for prepare
08-26 16:54:53.166   325  7028 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 16:54:53.166   325  7028 V AwesomePlayer: initAudioDecoder() 
08-26 16:54:53.166   325  7028 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 16:54:53.166   325  7028 V AudioSystem: isOffloadSupported()
08-26 16:54:53.166   325  7028 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 16:54:53.166   325  7028 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 16:54:53.166   325  7028 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 16:54:53.166   325  7028 V AwesomePlayer: getUseOffload() = 0 
08-26 16:54:53.166   325  7028 V OMXCodec: OMXCodec::Create
08-26 16:54:53.166   325  7028 V OMXCodec: findMatchingCodecs()
08-26 16:54:53.166   325  7028 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 16:54:53.166   325  7028 V OMXCodec: matchingCodecs.size()=1
08-26 16:54:53.166   325  7028 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 16:54:53.167   325  7028 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 16:54:53.167   325  7028 V LGCodecAdapter: LG Codec Adapter start
08-26 16:54:53.167   325  7028 V OMXCodec: OMXCodec Createtor
08-26 16:54:53.167   325  7028 V OMXCodec: setComponentRole
08-26 16:54:53.167   325  7028 V OMXCodec: configureCodec protected=0
08-26 16:54:53.167   325  7028 V LGCodecAdapter: called getLGCodecSpecificData
08-26 16:54:53.167   325  7028 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 16:54:53.167   325  7028 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 16:54:53.167   325  7028 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 16:54:53.167   325  7028 V LGCodecOSAL: Not support LGCodec
08-26 16:54:53.167   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 16:54:53.168   325  7028 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 16:54:53.168   325  7028 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 16:54:53.168   325  7028 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 16:54:53.168   325  7028 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 16:54:53.168   325  7028 V AudioSystem: isOffloadSupported()
08-26 16:54:53.168   325  7028 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 16:54:53.168   325  7028 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 16:54:53.168   325  7028 V OMXCodec: init()
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 16:54:53.168   325  7028 V OMXCodec: allocateBuffers
08-26 16:54:53.168   325  7028 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.deco,der] allocated buffer 0xb54f7b50 on input port
08-26 16:54:53.168   325  7028 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1290 on output port
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1380 on output port
08-26 16:54:53.168   325  7028 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c15b0 on output port
08-26 16:54:53.168   325  7028 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-26 16:54:53.176   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 16:54:53.176   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 16:54:53.176   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 16:54:53.176   325  7028 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 16:54:53.176  6920  6920 V LGMDMManager: Create singleton instance
08-26 16:54:53.176   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 16:54:53.176   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 16:54:53.176   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 16:54:53.176   325  7028 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 16:54:53.176   325  7028 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 16:54:53.176   325  7028 V AudioCache: notify(0xb1432480, 5, 0, 0)
08-26 16:54:53.176   325  7028 V AudioCache: ignored
08-26 16:54:53.176   325  7028 V AudioCache: notify(0xb1432480, 1, 0, 0)
08-26 16:54:53.176   325  7028 V AudioCache: prepared
08-26 16:54:53.176   325  1369 V AudioCache: wait - success
08-26 16:54:53.176   325  1369 V MediaPlayerService: start
08-26 16:54:53.176   325  1369 V AwesomePlayer: play_l() 
08-26 16:54:53.176   325  1369 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 16:54:53.176   325  1369 V AwesomePlayer: createAudioPlayer_l
08-26 16:54:53.176   325  1369 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 16:54:53.176   325  1369 V AwesomePlayer: startAudioPlayer_l() 
08-26 16:54:53.176   325  1369 D AudioPlayer: start of Playback, useOffload 0
08-26 16:54:53.176   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 16:54:53.176   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807312
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044807552
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044808112
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 16:54:53.178   325  7030 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 16:54:53.178   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buf,fers of size 32768 on output port
08-26 16:54:53.179   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1380 on output port
08-26 16:54:53.179   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1290 on output port
08-26 16:54:53.179   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-26 16:54:53.179   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1880 on output port
08-26 16:54:53.179   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 16:54:53.179   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 16:54:53.179   325  1369 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 16:54:53.179   325  1369 V AudioCache: notify(0xb1432480, 6, 0, 0)
08-26 16:54:53.179   325  1369 V AudioCache: ignored
08-26 16:54:53.179   325  1369 V MediaPlayerService: wait for playback complete
08-26 16:54:53.180   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.180   325  7031 V AudioCache: memcpy(0xac300000, 0xb17f9000, 4096)
08-26 16:54:53.181   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.181   325  7031 V AudioCache: memcpy(0xac301000, 0xb17f9000, 4096)
,08-26 16:54:53.181   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.181   325  7031 V AudioCache: memcpy(0xac302000, 0xb17f9000, 4096)
08-26 16:54:53.182   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.182   325  7031 V AudioCache: memcpy(0xac303000, 0xb17f9000, 4096)
08-26 16:54:53.182   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.182   325  7031 V AudioCache: memcpy(0xac304000, 0xb17f9000, 4096)
08-26 16:54:53.182   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.183   325  7031 V AudioCache: memcpy(0xac305000, 0xb17f9000, 4096)
08-26 16:54:53.183   325  7031 V AudioCache: write(0xb17f9000, 4096)
,08-26 16:54:53.183   325  7031 V AudioCache: memcpy(0xac306000, 0xb17f9000, 4096)
08-26 16:54:53.183   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.183   325  7031 V AudioCache: memcpy(0xac307000, 0xb17f9000, 4096)
08-26 16:54:53.184   325  7031 V AudioCache: write(0xb17f9000, 4096)
,08-26 16:54:53.184   325  7031 V AudioCache: memcpy(0xac308000, 0xb17f9000, 4096)
08-26 16:54:53.184   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.184   325  7031 V AudioCache: memcpy(0xac309000, 0xb17f9000, 4096)
08-26 16:54:53.184   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.184   325  7031 V AudioCache: memcpy(0xac30a000, 0xb17f9000, 4096)
08-26 16:54:53.185   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.185   325  7031 V AudioCache: memcpy(0xac30b000, 0xb17f9000, 4096)
08-26 16:54:53.185   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.185   325  7031 V AudioCache: memcpy(0xac30c000, 0xb17f9000, 4096)
08-26 16:54:53.186   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.186   325  7031 V AudioCache: memcpy(0xac30d000, 0xb17f9000, 4096)
08-26 16:54:53.186   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.186   325  7031 V AudioCache: memcpy(0xac30e000, 0xb17f9000, 4096)
08-26 16:54:53.186   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.186   325  7031 V AudioCache: memcpy(0xac30f000, 0xb17f9000, 4096)
08-26 16:54:53.187   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.187   325  7031 V AudioCache: memcpy(0xac310000, 0xb17f9000, 4096)
08-26 16:54:53.187   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.187   325  7031 V AudioCache: memcpy(0xac311000, 0xb17f9000, 4096)
08-26 16:54:53.188   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.188   325  7031 V AudioCache: memcpy(0xac312000, 0xb17f9000, 4096)
08-26 16:54:53.188   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.188   325  7031 V AudioCache: memcpy(0xac313000, 0xb17f9000, 4096)
08-26 16:54:53.188   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.188   325  7031 V AudioCache: memcpy(0xac314000, 0xb17f9000, 4096)
08-26 16:54:53.189   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.189   325  7031 V AudioCache: memcpy(0xac315000, 0xb17f9000, 4096)
08-26 16:54:53.189   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.189   325  7031 V AudioCache: memcpy(0xac316000, 0xb17f9000, 4096)
08-26 16:54:53.190   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.190   325  7031 V AudioCache: memcpy(0xac317000, 0xb17f9000, 4096)
08-26 16:54:53.190   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.190   325  7031 V AudioCache: memcpy(0xac318000, 0xb17f9000, 4096)
08-26 16:54:53.191   325  7031 V AudioCache: write(0xb17f9000, 4096)
,08-26 16:54:53.191   325  7031 V AudioCache: memcpy(0xac319000, 0xb17f9000, 4096)
08-26 16:54:53.191   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.191   325  7031 V AudioCache: memcpy(0xac31a000, 0xb17f9000, 4096)
08-26 16:54:53.191   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.191   325  7031 V AudioCache: memcpy(0xac31b000, 0xb17f9000, 4096)
08-26 16:54:53.192   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.192   325  7031 V AudioCache: memcpy(0xac31c000, 0xb17f9000, 4096)
08-26 16:54:53.192   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.192   325  7031 V AudioCache: memcpy(0xac31d000, 0xb17f9000, 4096)
08-26 16:54:53.193   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.193   325  7031 V AudioCache: memcpy(0xac31e000, 0xb17f9000, 4096)
08-26 16:54:53.193   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.193   325  7031 V AudioCache: memcpy(0xac31f000, 0xb17f9000, 4096)
08-26 16:54:53.193   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.193   325  7031 V AudioCache: memcpy(0xac320000, 0xb17f9000, 4096)
08-26 16:54:53.194   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.194   325  7031 V AudioCache: memcpy(0xac321000, 0xb17f9000, 4096)
08-26 16:54:53.194   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.194   325  7031 V AudioCache: memcpy(0xac322000, 0xb17f9000, 4096)
08-26 16:54:53.195   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.195   325  7031 V AudioCache: memcpy(0xac323000, 0xb17f9000, 4096)
08-26 16:54:53.195   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.195   325  7031 V AudioCache: memcpy(0xac324000, 0xb17f9000, 4096)
08-26 16:54:53.198   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.198   325  7031 V AudioCache: memcpy(0xac325000, 0xb17f9000, 4096)
08-26 16:54:53.199   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.199   325  7031 V AudioCache: memcpy(0xac326000, 0xb17f9000, 4096)
08-26 16:54:53.199   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.199   325  7031 V AudioCache: memcpy(0xac327000, 0xb17f9000, 4096)
08-26 16:54:53.199   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.199   325  7031 V AudioCache: memcpy(0xac328000, 0xb17f9000, 4096)
08-26 16:54:53.200   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.200   325  7031 V AudioCache: memcpy(0xac329000, 0xb17f9000, 4096)
08-26 16:54:53.200   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.200   325  7031 V AudioCache: memcpy(0xac32a000, 0xb17f9000, 4096)
08-26 16:54:53.201   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.201   325  7031 V AudioCache: memcpy(0xac32b000, 0xb17f9000, 4096)
08-26 16:54:53.201   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.201   325  7031 V AudioCache: memcpy(0xac32c000, 0xb17f9000, 4096)
08-26 16:54:53.201   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.201   325  7031 V AudioCache: memcpy(0xac32d000, 0xb17f9000, 4096)
08-26 16:54:53.202   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.202   325  7031 V AudioCache: memcpy(0xac32e000, 0xb17f9000, 4096)
08-26 16:54:53.202   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.202   325  7031 V AudioCache: memcpy(0xac32f000, 0xb17f9000, 4096)
08-26 16:54:53.202   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.202   325  7031 V AudioCache: memcpy(0xac330000, 0xb17f9000, 4096)
08-26 16:54:53.203   325  7031 V AudioCache: write(0xb17f9000, 4096)
08-26 16:54:53.203   325  7031 V AudioCache: memcpy(0xac331000, 0xb17f9000, 4096)
08-26 16:54:53.203   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 16:54:53.203   325  7031 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 16:54:53.203   325  7031 V AwesomePlayer: postAudioEOS() 
08-26 16:54:53.203   325  7031 V AudioCach,e: write(0xb17f9000, 280)
08-26 16:54:53.203   325  7031 V AudioCache: memcpy(0xac332000, 0xb17f9000, 280)
08-26 16:54:53.203  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 16:54:53.203  2115  2115 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 16:54:53.205   325  7028 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 16:54:53.205   325  7028 V AwesomePlayer: onStreamDone
08-26 16:54:53.205   325  7028 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 16:54:53.205   325  7028 V AudioCache: notify(0xb1432480, 2, 0, 0)
08-26 16:54:53.205   325  7028 V AudioCache: playback complete
08-26 16:54:53.205   325  7028 V AwesomePlayer: pause_l() 
08-26 16:54:53.205   325  7028 V AudioCache: notify(0xb1432480, 7, 0, 0)
08-26 16:54:53.205   325  7028 V AudioCache: ignored
08-26 16:54:53.205   325  7028 V AwesomePlayer: cancelPlayerEvents
08-26 16:54:53.205   325  1369 V AudioCache: wait - success
08-26 16:54:53.205   325  1369 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 16:54:53.205   325  7028 D AudioPlayer: Pause Playback at 1068125
08-26 16:54:53.206   325  1369 V AwesomePlayer: reset_l() 
08-26 16:54:53.206   325  1369 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-26 16:54:53.206   325  1369 V AudioCache: ignored
08-26 16:54:53.206   325  1369 V AwesomePlayer: cancelPlayerEvents
08-26 16:54:53.206   325  1369 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 16:54:53.206   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 16:54:53.206   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 16:54:53.206   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 16:54:53.206   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1880 on port 1
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1290 on port 1
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 16:54:53.206   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1380 on port 1
08-26 16:54:53.207   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 16:54:53.207   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 16:54:53.207   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 16:54:53.207   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 16:54:53.209   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 16:54:53.209   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 16:54:53.209   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 16:54:53.209   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 16:54:53.209   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 16:54:53.209   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 16:54:53.210   325  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 16:54:53.210   325  1369 D AudioPlayer: AudioPlayer releasing audio source
08-26 16:54:53.210   325  1369 D AudioPlayer: AudioPlayer done releasing audio source
08-26 16:54:53.210   325  1369 V AwesomePlayer: reset_l() 
08-26 16:54:53.210   325  1369 V AwesomePlayer: cancelPlayerEvents
08-26 16:54:53.210   325  1369 V AwesomePlayer: ~AwesomePlayer call
08-26 16:54:53.213   325  1369 V AwesomePlayer: reset_l() 
08-26 16:54:53.213   325  1369 V AwesomePlayer: cancelPlayerEvents
08-26 16:54:53.213  6920  7024 V SoundPool: close(31)
08-26 16:54:53.213  6920  7024 V SoundPool: pointer = 0x9ffd7000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 16:54:53.214  6853  6853 D BluetoothPermissionRequest: onReceive
08-26 16:54:53.216  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 16:54:53.216  6853  6853 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 16:54:53.218  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 16:54:53.221  6997  6997 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 16:54:53.223  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 16:54:53.226  6997  6997 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 16:54:53.226  6997  6997 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 16:54:53.226  6997  6997 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 16:54:53.227  6997  6997 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:54:53.227  6997  6997 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 16:54:53.232  6940  6940 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 16:54:53.258  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-26 16:54:53.259  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 16:54:53.266  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1419
,08-26 16:54:53.440  6755  6755 I UEI.SmartControl: Supports setup maps: true
,08-26 16:54:53.443  6755  6755 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 16:54:53.443  6755  6755 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 16:54:53.443  6755  6755 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 16:54:53.443  6755  6755 I UEI.SmartControl: ### init IR Blaster...
08-26 16:54:53.447  6755  6755 D serial_port: Configuring serial port
08-26 16:54:53.447  6755  6755 E UEI.SmartControl: UEIBLaster setting for 616
08-26 16:54:53.447  6755  6755 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 16:54:53.447  6755  6755 I UEI.SmartControl: configuring settings for MAXQ616
08-26 16:54:53.447  6755  6755 I UEI.SmartControl: Get version...
08-26 16:54:53.466  6755  7034 D UEI.SmartControl: serial port data available: 21
,08-26 16:54:53.492  6755  6755 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 16:54:53.492  6755  6755 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 16:54:53.492  6755  6755 I UEI.SmartControl: QS saving settings...
08-26 16:54:53.493  6755  6755 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 16:54:53.509  6755  7034 D UEI.SmartControl: serial port data available: 4
,08-26 16:54:53.550  6755  6755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 16:54:53.559  1031  1400 V AlarmManager: ELAPSED_WAKEUP set : Alarm{b23552d type 2 when 121404 com.google.android.gms} when 121404
,08-26 16:54:53.562  6755  7040 I UEI.SmartControl: Device manager: loading config....
08-26 16:54:53.563  6755  7040 D UEI.SmartControl: ----------- loading internal config...
08-26 16:54:53.568  6755  6755 E UEI.SmartControl: Services init done
08-26 16:54:53.568  6755  6755 D UEI.SmartControl: QS Service init finished
,08-26 16:54:53.572  6755  6755 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 16:54:53.572  6755  6755 D UEI.SmartControl: QS Service version code: 201091
08-26 16:54:53.572  6755  6755 D UEI.SmartControl: Service requested: Control
08-26 16:54:53.579  6755  7040 E UEI.SmartControl: Loading SETTINGS...
,08-26 16:54:53.582  6755  6755 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 16:54:53.585  6755  6755 D UEI.SmartControl: Internal service binding...
08-26 16:54:53.586  6755  7040 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 16:54:53.586  6920  6920 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 16:54:53.587  6755  6771 I UEI.SmartControl: ------ IControl API: 11
08-26 16:54:53.587  6755  6771 D UEI.SmartControl: File observer start...
08-26 16:54:53.588  6755  6771 E UEI.SmartControl: IR Port is disabled: false
08-26 16:54:53.588  6755  6771 D UEI.SmartControl: Starting file observer...
08-26 16:54:53.589  6755  6771 I UEI.SmartControl: Registering callback...
08-26 16:54:53.590  6755  6772 I UEI.SmartControl: ------ IControl API: 19
08-26 16:54:53.591  6755  6772 I UEI.SmartControl: Registering Services Ready callback...
08-26 16:54:53.591  6755  6772 I UEI.SmartControl: Notify client services are ready...
08-26 16:54:53.592  6920  6939 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 16:54:53.592  6920  7022 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 16:54:53.593  6920  7022 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 16:54:53.593  6920  6920 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 16:54:53.594  6920  6920 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 16:54:53.594  6755  6771 I UEI.SmartControl: ------ IControl API: 8
,08-26 16:54:53.596  6920  6920 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 16:54:53.596  6920  6920 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 16:54:53.596  6920  6920 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 16:54:53.597  6920  6920 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 16:54:53.599  6920  6920 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 16:54:53.599  6920  6920 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 16:54:53.601  6755  7039 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 16:54:53.601  6920  6938 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 16:54:53.601  6920  7022 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 16:54:53.602  6920  7022 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 16:54:53.602  6755  7039 D UEI.SmartControl: -----service ready thread exits
08-26 16:54:53.602  6920  6920 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 16:54:53.603  6920  6920 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 16:54:53.604  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 16:54:53.605  6920  6920 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 16:54:53.605  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 16:54:53.606  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-26 16:54:53.607  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-26 16:54:53.608  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 16:54:53.609  6920  6920 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472223293609]
08-26 16:54:53.612  6920  6920 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-26 16:54:53.612  6920  6920 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 16:54:53.615  1031  2017 I ActivityManager: Killing 6136:com.android.gallery3d/u0a27 (adj 15): empty #17
08-26 16:54:53.633  6920  7046 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 16:54:53.646  1031  2017 I ActivityManager: Killing 6559:com.lge.email/u0a23 (adj 15): empty #18
,08-26 16:54:53.677  1031  1870 W libprocessgroup: failed to open /acct/uid_10027/pid_6136/cgroup.procs: No such file or directory
,08-26 16:54:53.683  1031  1559 W libprocessgroup: failed to open /acct/uid_10023/pid_6559/cgroup.procs: No such file or directory
08-26 16:54:53.684  6920  6920 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-26 16:54:53.684  6920  6920 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 16:54:53.685  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 16:54:53.686  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 16:54:53.687  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 16:54:53.687  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 16:54:53.688  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 16:54:53.699  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 16:54:54.152  1031  1400 V AlarmManager: ELAPSED_WAKEUP set : Alarm{10856cb0 type 2 when 121989 com.google.android.gms} when 121989
,08-26 16:54:54.552  1031  1631 D WifiServiceImplEx: setWifiEnabled: true pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 16:54:54.553  1031  1631 D WifiService: setWifiEnabled: true pid=6679, uid=10118
,08-26 16:54:54.553  1031  1631 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 16:54:54.579  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 16:54:54.580  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 16:54:54.580  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-26 16:54:54.583  1031  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-26 16:54:54.584  1031  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-26 16:54:54.586  1031  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 16:54:54.586  1031  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 16:54:54.586  1031  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 16:54:54.587  1031  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-26 16:54:54.587  1031  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 16:54:54.587  1031  1522 E WifiHW  : unknown target_country: EU , set to default
08-26 16:54:54.587  1031  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 16:54:54.587  1031  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 16:54:54.587  1031  1522 I WifiUtil: gEnableBmps=1
08-26 16:54:54.631  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:54.652  1031  1102 D Tethering: MasterInitialState.processMessage what=3
08-26 16:54:54.659  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:54.662  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:54.667  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:54.671  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:54.675  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 16:54:54.678  6484  6513 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 16:54:54.689  1031  1102 D Tethering: MasterInitialState.processMessage what=3
,08-26 16:54:54.693  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:54.694  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:54.702  5817  5817 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 16:54:54.711  5817  5817 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 16:54:54.732  2115  2115 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:54.767  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:54.805  1031  2319 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7052 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-26 16:54:54.822  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:54.822  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 16:54:54.914  7052  7052 I AppUp4:AppBoxCP: onCreate
08-26 16:54:54.915  7052  7052 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 16:54:54.925  7052  7052 I AppUp4:DB:  setFingerPrint start
,08-26 16:54:54.925  7052  7052 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 16:54:54.934  7052  7052 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-26 16:54:54.934  7052  7052 I AppUp4:DB:  SDK version = 21
08-26 16:54:54.934  7052  7052 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-26 16:54:54.936  7052  7052 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-26 16:54:54.938  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 16:54:54.938  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:54.941  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 16:54:54.941  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 16:54:54.949  7052  7052 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 16:54:54.991  7052  7052 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:54:54.991  7052  7052 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 16:54:55.002  7052  7052 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@327310ba
08-26 16:54:55.003  7052  7052 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 16:54:55.003  7052  7052 D AppUp4:CustFacade: isPhone : true
08-26 16:54:55.004  7052  7052 D AppUp4:CustModeStarterReceiver: begin check event
08-26 16:54:55.005  7052  7052 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 16:54:55.005  7052  7052 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-26 16:54:55.007  7052  7085 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 16:54:55.007  7052  7085 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-26 16:54:55.008  7052  7085 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-26 16:54:55.010  1031  2319 I ActivityManager: Killing 6193:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-26 16:54:55.051  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:55.052  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 16:54:55.052  1031  1962 W libprocessgroup: failed to open /acct/uid_10080/pid_6193/cgroup.procs: No such file or directory
,08-26 16:54:55.057  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 16:54:55.062  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:54:55.069  4356  7089 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 16:54:55.075  4356  7090 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:55.075  4356  7090 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 16:54:55.158  1031  1980 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7094 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 16:54:55.235  7094  7094 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 16:54:55.235  7094  7094 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 16:54:55.237  7094  7094 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 16:54:55.237  7094  7094 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 16:54:55.319  7094  7094 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 16:54:55.334  7094  7094 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 16:54:55.339  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 16:54:55.339  1031  1102 D Tethering: InitialState.processMessage what=4
,08-26 16:54:55.344   321   890 D SoftapController: Softap fwReload - Ok
,08-26 16:54:55.345  1031  1522 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (754ms)
08-26 16:54:55.347   321   890 D CommandListener: Setting iface cfg
08-26 16:54:55.347   321   890 D CommandListener: Trying to bring down wlan0
08-26 16:54:55.348   321   890 D CommandListener: Clearing all IP addresses on wlan0
08-26 16:54:55.349  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 16:54:55.352  1031  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 16:54:55.335  7121  7121 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:54:55.345  7121  7121 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:54:55.357  1031  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 16:54:55.357  1031  1522 E WifiStateMachine: useWiFiOffloading() : false
08-26 16:54:55.357  1031  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 16:54:55.359  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 16:54:55.360  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:54:55.367  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 16:54:55.367  1031  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 16:54:55.367  1031  1522 D WifiMonitor: connecting to supplicant
08-26 16:54:55.368  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:55.374  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:55.379  7121  7121 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 16:54:55.402  7121  7121 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 16:54:55.403  7121  7121 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 16:54:55.431  7094  7094 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 16:54:55.454  7094  7094 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:54:55.455  7094  7094 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 16:54:55.511  7121  7121 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 16:54:55.553  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 16:54:55.586  7121  7121 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 16:54:55.595  7121  7121 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 16:54:55.595  7121  7121 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 16:54:55.597  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 16:54:55.597  1031  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 16:54:55.597  1031  7137 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 16:54:55.597  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 16:54:55.598  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 16:54:55.598  1031  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 16:54:55.598  1031  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 16:54:55.599  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 16:54:55.601  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 16:54:55.602  1031  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 16:54:55.603  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:55.604  1031  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:55.607  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:55.609  1031  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-26 16:54:55.612  1031  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 16:54:55.612  1031  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 16:54:55.614  1031  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 16:54:55.614  1031  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 16:54:55.615  1031  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 16:54:55.616  1031  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 16:54:55.616  1031  1522 E WifiStateMachine: useWiFiOffloading() : false
08-26 16:54:55.616  1031  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 16:54:55.617  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:55.617  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:55.617  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:55.617  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 16:54:55.618  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 16:54:55.619  1927  1927 D WfdService: Waiting for WifiP2p enabling
08-26 16:54:55.621  7094  7094 I HubEmail: JNI_OnLoad()
08-26 16:54:55.621  7094  7094 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 16:54:55.621  7094  7094 I HubEmail: registerNatives()
08-26 16:54:55.621  7094  7094 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 16:54:55.621  7094  7094 I HubEmail: registerNativeMethods()
08-26 16:54:55.621  7094  7094 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 16:54:55.622  7094  7094 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-26 16:54:55.623  1031  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 16:54:55.623  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 16:54:55.623  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:55.623  1031  1522 D WifiNative-wlan0: SET update_config 1: returned true
08-26 16:54:55.623  1031  1522 D WifiConfigStore: Loading config and enabling all networks 
08-26 16:54:55.623  1031  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 16:54:55.624  1031  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 16:54:55.624  1031  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 16:54:55.625  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:55.625  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:55.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:55.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:55.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:55.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:55.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:55.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:55.625  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:55.625  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:55.626  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:54:55.630  1031  1522 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 16:54:55.633  6960  7139 W FormManager: Network not available. Please check & try again.
08-26 16:54:55.634  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:55.634  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:55.634  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:55.634  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:55.634  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:54:55.634  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:55.634  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:55.634  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:55.634  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:55.634  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:55.634  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:55.637  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 16:54:55.637  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:55.638  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 16:54:55.641  1031  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 16:54:55.642  1031  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 16:54:55.643  1031  1522 D WifiStateMachine: enableVerboseLogging : level 2
08-26 16:54:55.643  1031  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 16:54:55.643  1031  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 16:54:55.643  1031  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 16:54:55.644  1031  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 16:54:55.644  1031  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 16:54:55.645  1031  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
,08-26 16:54:55.645  1031  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 16:54:55.646  1031  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 16:54:55.646  1031  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-26 16:54:55.646  1031  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 16:54:55.646  1031  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 16:54:55.647  1031  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 16:54:55.647  1031  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 16:54:55.647  1031  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 16:54:55.684  1031  1768 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7143 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 16:54:55.689  6960  7140 V FormManager: Network unavailable.
08-26 16:54:55.690  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-26 16:54:55.690  1927  2231 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 16:54:55.690  1927  2231 D WfdsService: Set the WFDS Monitor: true
08-26 16:54:55.690  1927  2231 D WfdsMonitor: WfdsMonitorThread create
08-26 16:54:55.690  1927  2231 D WfdsMonitor: WFDS Monitor is created and started
08-26 16:54:55.690  1927  2231 D WfdsService: WiFi: Supplicant connection re-established
08-26 16:54:55.691  1031  1522 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 16:54:55.691  1031  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 16:54:55.692  1031  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
,08-26 16:54:55.693  1031  1522 D WifiNative-HAL: Setting external_sim to 1
08-26 16:54:55.693  1031  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 16:54:55.694  1031  1522 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 16:54:55.694  1031  1522 I WifiNative-HAL: startHal
08-26 16:54:55.694  1031  1522 D wifi    : setting scan oui 0xaf73a320
08-26 16:54:55.695  6960  7140 V FormManager: Network unavailable.
08-26 16:54:55.695  1031  1522 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 16:54:55.695  1031  1522 I WifiNative-HAL: startHal
,08-26 16:54:55.695  1031  1522 D wifi    : setting scan oui 0xaf73a320
08-26 16:54:55.696  1927  7153 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 16:54:55.696  1031  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 16:54:55.697  1927  7153 E CtrlSupplicant: Succeed to open control connection
08-26 16:54:55.697  1927  7153 E CtrlSupplicant: Succeed to open monitor connection
08-26 16:54:55.697  1927  7153 D WfdsMonitor: Supplicant connection established
08-26 16:54:55.697  1927  2231 D WfdsService: Connected to the supplicant for wfds
08-26 16:54:55.698  1031  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 16:54:55.698  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 16:54:55.698  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 16:54:55.699  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,08-26 16:54:55.703  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 16:54:55.703  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 16:54:55.704  1031  1907 I ActivityManager: Killing 6607:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-26 16:54:55.705  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 16:54:55.705  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 16:54:55.706  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 16:54:55.706  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 16:54:55.706  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 16:54:55.707  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 16:54:55.707  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 16:54:55.708  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 16:54:55.708  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 16:54:55.709  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 16:54:55.709  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 16:54:55.709  7121  7121 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 16:54:55.710  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 16:54:55.710  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 16:54:55.710  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 16:54:55.711  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 16:54:55.713  1031  1522 E WifiNative: : [123,562,438 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 16:54:55.713  1031  1522 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 16:54:55.714  1031  1522 D WifiNative-wlan0: RECONNECT: returned true
08-26 16:54:55.714  1031  1522 D WifiNative-wlan0: doString: [STATUS]
08-26 16:54:55.715  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 16:54:55.715  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 16:54:55.716  1031  1522 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 16:54:55.716  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 16:54:55.716  1031  1522 D WifiNative-wlan0: SET ps 1: returned true
08-26 16:54:55.716  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.718   321   890 D CommandListener: Setting iface cfg
08-26 16:54:55.718   321   890 D CommandListener: Trying to bring up p2p0
08-26 16:54:55.718  1031  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 16:54:55.719  1031  1521 D LGWifiP2pService: P2pEnablingState
08-26 16:54:55.719  1031  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.719  1031  1521 D LGWifiP2pService: P2p socket connection successful
08-26 16:54:55.719  1031  1521 D LGWifiP2pService: P2pEnabledState
08-26 16:54:55.747  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 16:54:55.747  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-26 16:54:55.747  1031  2017 W libprocessgroup: failed to open /acct/uid_10061/pid_6607/cgroup.procs: No such file or directory
08-26 16:54:55.747  1031  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-26 16:54:55.748  1031  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.748  1031  1540 I WifiNative-HAL: startHal
08-26 16:54:55.748  1031  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf73a320
08-26 16:54:55.748  1031  1540 D wifi    : failed to get capabilities : -3
08-26 16:54:55.748  1031  1540 E WifiScanningService: could not get scan capabilities
08-26 16:54:55.748  1031  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 16:54:55.748  1031  1541 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.748  1031  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 16:54:55.749  1031  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,08-26 16:54:55.749  1031  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 16:54:55.750  1031  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 16:54:55.750  1031  1522 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 16:54:55.750  1031  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-26 16:54:55.750  7121  7121 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 16:54:55.751  1031  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 16:54:55.752  1031  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 16:54:55.752  1031  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,08-26 16:54:55.752  1031  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-26 16:54:55.752  7121  7121 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 16:54:55.753  1031  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 16:54:55.753  1031  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 16:54:55.754  1031  1521 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 16:54:55.754  7094  7142 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:55.754  1031  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 16:54:55.754  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-26 16:54:55.755  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 16:54:55.755  7121  7121 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:54:55.755  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 16:54:55.755  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:54:55.755  1031  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:54:55.756  1031  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:54:55.756  1031  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 16:54:55.756  7121  7121 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 16:54:55.756  7121  7121 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.756  1927  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:54:55.756  1031  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:54:55.756  1031  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.756  1031  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.756  1031  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.757  7121  7121 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.757  1927  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:54:55.757  1031  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:54:55.757  1031  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.757  1031  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.757  1031  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.757  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 16:54:55.757  1927  1927 D WfdsService: WifiP2pState is changed : true
08-26 16:54:55.758  1927  2231 D WfdsService: Receive the WFDS_ENABLE Method
08-26 16:54:55.758  1927  2231 D WfdsService: Set the WFDS Monitor: true
08-26 16:54:55.758  1927  2231 D WfdsService: Connected to the supplicant for wfds
08-26 16:54:55.758  1927  2231 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 16:54:55.758  7121  7121 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 16:54:55.758  1927  2231 D WfdsService: selectPreferredScanChannel [36]
08-26 16:54:55.758  1927  2231 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 16:54:55.759  1031  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 16:54:55.759  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 16:54:55.759  1031  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 16:54:55.759  1031  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 16:54:55.759  1031  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 16:54:55.760  1031  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 16:54:55.760  1927  1927 D WfdsService: isConnected: false
08-26 16:54:55.760  1031  1521 D WifiNative-p2p0: SET device_name G3: returned true
08-26 16:54:55.760  1031  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 16:54:55.760  1031  1521 D LGWifiP2pService: before postfix = G3
08-26 16:54:55.760  1031  1521 D WifiServerServiceExt: postfix byte check : 2
08-26 16:54:55.760  1031  1521 D LGWifiP2pService: after postfix = G3
08-26 16:54:55.760  1031  1522 E, WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 16:54:55.760  1031  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 16:54:55.760  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 16:54:55.760  1031  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 16:54:55.761  1031  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 16:54:55.761  1031  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 16:54:55.761  1031  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 16:54:55.761  1031  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 16:54:55.761  1031  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 16:54:55.762  1031  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 16:54:55.762  1031  1521 D WifiNative-HAL: p2pGetDeviceAddress
08-26 16:54:55.762  1031  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 16:54:55.762  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 16:54:55.762  7121  7121 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 16:54:55.763  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 16:54:55.763  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 16:54:55.763  1031  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 16:54:55.763  1031  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 16:54:55.763  1031  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,08-26 16:54:55.763  1031  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 16:54:55.763  1031  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 16:54:55.763  1031  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 16:54:55.764  1031  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 16:54:55.764  1031  1522 D WifiNative-wlan0: doBoolean: SCAN
08-26 16:54:55.764  1031  1522 D WifiNative-wlan0: SCAN: returned false
08-26 16:54:55.765  1031  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
,08-26 16:54:55.765  1031  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 16:54:55.765  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 16:54:55.765  1031  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,08-26 16:54:55.765  1031  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 16:54:55.766  1031  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 16:54:55.766  1031  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 16:54:55.766  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 16:54:55.766  1927  1927 D WfdsService: Update P2p Interface State: 3
08-26 16:54:55.766  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=123617  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 16:54:55.770  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:55.770  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:55.772  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=123623  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-26 16:54:55.772  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:54:55.773  1031  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 16:54:55.774  1031  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 16:54:55.775  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:55.775  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:55.775  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 16:54:55.776  1031  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 16:54:55.776  1031  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 16:54:55.776  1031  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 16:54:55.776  1031  1521 D LGWifiP2pService: InactiveState
08-26 16:54:55.776  1031  1521 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.776  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-26 16:54:55.776  1031  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-26 16:54:55.776  1031  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 16:54:55.777  1031  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 16:54:55.777  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 16:54:55.778  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:54:55.778  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 16:54:55.779  7121  7121 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:54:55.779  1927  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 16:54:55.779  7121  7121 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 16:54:55.780  7121  7121 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.780  1927  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:54:55.780  7121  7121 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.780  1927  7153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:54:55.781  1031  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 16:54:55.781  1031  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:54:55.781  1031  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:54:55.781  1031  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:54:55.781  1031  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:54:55.781  1031  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.782  1031  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.782  1031  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.782  1031  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:54:55.782  1031  7137 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.782  1031  7137 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.782  1031  7137 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:54:55.782  1031  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 16:54:55.782  1031  1521 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.782  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.782  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.782  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.782  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=c,om.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1927  2231 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 16:54:55.783  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:55.783  1031  1031 E WifiServerServiceExt: No p2p device connected
08-26 16:54:55.826  7143  7143 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:54:55.826  7143  7143 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 16:54:55.828  7143  7143 D PhoneMonitor: Register our PhoneStateListener
,08-26 16:54:55.841  7143  7143 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 16:54:55.844  7143  7143 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 16:54:55.864  7143  7143 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-26 16:54:55.869  7143  7143 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-26 16:54:55.871  7143  7143 D TelephonyAutoProfiling: [parse] Load xml
,08-26 16:54:55.877  7143  7143 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-26 16:54:55.877  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,08-26 16:54:55.877  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 16:54:55.878  7143  7143 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 16:54:55.879  7143  7143 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-26 16:54:55.892  7143  7143 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-26 16:54:55.905  1031  2017 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7165 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 16:54:55.906  1031  2017 I ActivityManager: Killing 6224:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-26 16:54:55.967  1031  1050 W libprocessgroup: failed to open /acct/uid_10097/pid_6224/cgroup.procs: No such file or directory
,08-26 16:54:56.102  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 16:54:56.102  1031  7137 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 16:54:56.102  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 16:54:56.102  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-26 16:54:56.102  1031  7137 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-26 16:54:56.103  7121  7121 E wpa_supplicant: USIM:  scard_init function
,08-26 16:54:56.104  7121  7121 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-26 16:54:56.105  1031  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 16:54:56.105  1031  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 16:54:56.106  1031  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 16:54:56.106  1031  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 16:54:56.106  1031  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 16:54:56.106  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 16:54:56.107  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 16:54:56.121  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123972  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 16:54:56.125  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.125  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:56.126  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.126  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.126  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-26 16:54:56.130  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=123981  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 16:54:56.132  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.133  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.133  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.133  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 16:54:56.134  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:54:56.134  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 16:54:56.153  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.153  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:56.154  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:54:56.201  1031  1051 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7183 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-26 16:54:56.203  1031  1051 I ActivityManager: Killing 6697:com.lge.eula/1000 (adj 15): empty #17
,08-26 16:54:56.220  7121  7121 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 16:54:56.221  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 16:54:56.221  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 16:54:56.221  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 16:54:56.221  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 16:54:56.221  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:54:56.222  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:54:56.222  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124073  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 16:54:56.223  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124073  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 16:54:56.223  1031  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124074
08-26 16:54:56.224  1031  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124075
08-26 16:54:56.224  1031  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124075
08-26 16:54:56.224  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124075
08-26 16:54:56.225  1031  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124076
,08-26 16:54:56.226  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=124077  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 16:54:56.229  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:54:56.229  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:54:56.229  7121  7121 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 16:54:56.229  7121  7121 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 16:54:56.231  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 16:54:56.231  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 16:54:56.231  1031  7137 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 16:54:56.231  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 16:54:56.232  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 16:54:56.232  1031  7137 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 16:54:56.232  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:54:56.232  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:54:56.262  1031  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 16:54:56.263  1031  1961 W libprocessgroup: failed to open /acct/uid_1000/pid_6697/cgroup.procs: No such file or directory
08-26 16:54:56.280  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=124131  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 16:54:56.282  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.283  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 16:54:56.285  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.285  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.285  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 16:54:56.287  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.290  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.290  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.290  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 16:54:56.290  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:54:56.290  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 16:54:56.291  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=124141  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 16:54:56.291  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=124142  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 16:54:56.292  1031  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=124143
08-26 16:54:56.292  1031  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=124143
08-26 16:54:56.293  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.293  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:56.293  1031  1522 D WifiNative-wlan0: doString: [STATUS]
08-26 16:54:56.294  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:54:56.294  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:54:56.295  1031  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 16:54:56.296  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.297  1031  1522 I WifiServiceExtension: setVHTCapabilityType  : false
,08-26 16:54:56.305  1031  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 16:54:56.305  1031  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-26 16:54:56.311  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.312  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.312  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 16:54:56.312  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.312  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:56.316  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.316  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.317  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 16:54:56.318  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.321  1031  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 16:54:56.321  1031  1529 D ConnectivityService: Got NetworkAgent Messenger
08-26 16:54:56.321  1031  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 16:54:56.321  1031  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 16:54:56.321  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.321  1031  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 16:54:56.321  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:56.321  1031  1529 D ConnectivityService: NetworkAgent connected
08-26 16:54:56.322  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:54:56.324  1031  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 16:54:56.324  1031  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 16:54:56.328  1031  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 16:54:56.328  1031  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 16:54:56.328  1031  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 16:54:56.328  1031  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 16:54:56.328  1031  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 16:54:56.333  1031  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 16:54:56.334   321   890 D CommandListener: Setting iface cfg
,08-26 16:54:56.339  1031  1522 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 16:54:56.339  1031  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=124190  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:54:56.340  1031  7201 D DhcpStateMachine: StoppedState
08-26 16:54:56.340  1031  7201 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.340  1031  7201 D DhcpStateMachine: WaitBeforeStartState
08-26 16:54:56.340  1031  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=124191  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:54:56.341  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=124192  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:54:56.342  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:56.342  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:56.343  1031  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:56.343  1031  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:56.344  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:56.344  1031  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:56.345  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:54:56.345  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 16:54:56.346  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:54:56.346  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 16:54:56.346  1031  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=124197  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:54:56.347  1031  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=124198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:54:56.347  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=124198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 16:54:56.348  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77705] from screen [on:0 period:-950486180] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 16:54:56.349  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-950486179] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 16:54:56.349  1031  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 16:54:56.353  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.354  1031  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 16:54:56.355  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.356  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.356  1031  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.357  1031  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.357  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.357  1031  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.358  1031  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 16:54:56.358  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
,08-26 16:54:56.359  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
08-26 16:54:56.359  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 16:54:56.359  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 16:54:56.360  1031  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 16:54:56.360  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 16:54:56.360  1031  1522 D WifiNative-wlan0: SET ps 0: returned true
08-26 16:54:56.360  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 16:54:56.360  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 16:54:56.361  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 16:54:56.361  1031  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 16:54:56.361  1031  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 16:54:56.361  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a6e956e target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.361  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a6e956e target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.361  1031  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 16:54:56.361  1031  7201 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.361  1031  7201 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 16:54:56.362   321   890 D CommandListener: Setting iface cfg
08-26 16:54:56.363   321   890 D CommandListener: Trying to bring up wlan0
08-26 16:54:56.363  1031  1522 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 16:54:56.419  1031  1050 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7202 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 16:54:56.420  1031  1050 I ActivityManager: Killing 6715:com.lge.bnr/1000 (adj 15): empty #17
,08-26 16:54:56.442   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 438us total 21.155ms
,08-26 16:54:56.462   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 372us total 19.005ms
,08-26 16:54:56.480   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 17.340ms
,08-26 16:54:56.488  1031  1559 W libprocessgroup: failed to open /acct/uid_1000/pid_6715/cgroup.procs: No such file or directory
08-26 16:54:56.489  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:54:56.489  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 16:54:56.492  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.492  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.492  1031  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.493  1031  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.493  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.494  1031  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:56.494  1031  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 16:54:56.494  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 16:54:56.495  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 16:54:56.495  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.495  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.495  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 16:54:56.495  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 16:54:56.496  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 16:54:56.496  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 16:54:56.496  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 16:54:56.496  1031  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 16:54:56.496  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 16:54:56.502  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:54:56.502  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 16:54:56.514  1031  1522 D WifiNative-wlan0: SET ps 1: returned true
08-26 16:54:56.514  1031  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 16:54:56.514  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 16:54:56.515  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-26 16:54:56.515  1031  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 16:54:56.516  1031  1529 D ConnectivityService: ignoring duplicate network state non-change
08-26 16:54:56.521  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.521  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 16:54:56.523  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.528  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.528  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.528  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 16:54:56.530  1031  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 16:54:56.530  1031  1529 D ConnectivityService: Adding iface wlan0 to network 101
08-26 16:54:56.534  1031  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 16:54:56.542  7202  7202 I art     : Almond Protected OAT
,08-26 16:54:56.563  1031  7201 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 16:54:56.563  1031  7201 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 16:54:56.563  1031  7201 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-26 16:54:56.555  7221  7221 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:54:56.555  7221  7221 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:54:56.577  1031  1098 W ProcessCpuTracker: Skipping unknown process pid 7219
08-26 16:54:56.578  1031  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 16:54:56.578  1031  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 16:54:56.580  1031  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 16:54:56.580  7221  7221 I dhcpcd  : version 5.5.6 starting
08-26 16:54:56.581  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.581  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:56.581   321   890 E Netd    : netlink response contains error (File exists)
08-26 16:54:56.582  1031  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 16:54:56.582  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.583  7221  7221 E dhcpcd  : get_duid: m
08-26 16:54:56.583  7221  7221 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 16:54:56.583  7221  7221 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 16:54:56.583  1031  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 16:54:56.583  1031  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 16:54:56.583  1031  1529 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-26 16:54:56.588  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.588  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.588  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 16:54:56.588  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 16:54:56.591  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-26 16:54:56.595  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.595  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.595  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 16:54:56.595  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 16:54:56.597  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.597  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.597  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.598  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.598  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:56.598  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 16:54:56.598  1031  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 16:54:56.598  1031  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 16:54:56.598  1031  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 16:54:56.598  1031  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 16:54:56.599  1031  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 16:54:56.599  1031  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:54:56.599  1031  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-26 16:54:56.599  1031  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:56.599  1031  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 16:54:56.599  1031  1529 D ConnectivityService: currentScore = 0, newScore = 20
08-26 16:54:56.599  1031  1529 D ConnectivityService:    accepting network in place of null
08-26 16:54:56.599  1031  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:56.600  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.600  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 16:54:56.600  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:56.600  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 16:54:56.602  1031  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:56.602  1031  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 16:54:56.602  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:56.602  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 16:54:56.603  1031  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 16:54:56.603  1031  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 16:54:56.603  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 16:54:56.606   321  7226 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 16:54:56.609  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.609  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 16:54:56.609  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.612  1031  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:56.612  1031  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 16:54:56.612  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 16:54:56.613  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 16:54:56.613  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 16:54:56.613  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 16:54:56.615  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:56.615  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 16:54:56.616  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.616  1031  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-26 16:54:56.618  1031  1529 D ConnectivityService: validation of new default Network = false
08-26 16:54:56.618  1031  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 16:54:56.618  1031  1529 D DSQN    : enableDataServiceNotify 
08-26 16:54:56.618  1031  1529 D DSQN    : start dsqn bin
08-26 16:54:56.620  1031  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 16:54:56.620  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 16:54:56.621  1031  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-26 16:54:56.622  1031  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 16:54:56.622  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 16:54:56.623  1031  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 16:54:56.615  7229  7229 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:54:56.627  1031  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 16:54:56.630  1031  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 16:54:56.630  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:56.631  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:54:56.615  7229  7229 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:54:56.631  1031  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-26 16:54:56.615  7229  7229 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:54:56.632  1587  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 16:54:56.640  7221  7221 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 16:54:56.640  7221  7221 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 16:54:56.640  7221  7221 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 16:54:56.640  7221  7221 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 16:54:56.640  7221  7221 D dhcpcd  : wlan0: sending REQUEST (xid 0x57e75ec6), next in 3.41 seconds
,08-26 16:54:56.647  7229  7229 E DSQN    : DSQN ssw
08-26 16:54:56.647  7202  7202 D WeatherApplication: removeAccount
08-26 16:54:56.649  7202  7202 D WeatherApplication: Account.length = 0
08-26 16:54:56.650  7202  7202 E WeatherApplication: OPERATOR:OPEN
08-26 16:54:56.651  1800  7232 I CheckinService: active receiver: enabled
08-26 16:54:56.657  7202  7202 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:54:56
,08-26 16:54:56.659  1800  7232 I CheckinService: Preparing to send checkin request
08-26 16:54:56.659  1800  7232 I EventLogService: Accumulating logs since 1472223231645
08-26 16:54:56.661  7202  7202 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 16:54:56.661  7202  7202 D Weather.Utils: 2 : All the weather widget is gone.
08-26 16:54:56.664  7202  7202 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 16:54:56.664  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 16:54:56.665  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.666  7202  7202 D WeatherAncestor: connectivity changed - connection : true
08-26 16:54:56.666  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.666  7221  7221 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 16:54:56.666  7202  7202 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-26 16:54:56.669   321  7226 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-26 16:54:56.672  7202  7202 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 16:54:56.673  7202  7202 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 16:54:56.673  7202  7202 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-26 16:54:56.685  7202  7202 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-26 16:54:56.685  7202  7202 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:54:56
08-26 16:54:56.685  7221  7221 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 16:54:56.685  7221  7221 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 16:54:56.686  7221  7221 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 16:54:56.686  7221  7221 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 16:54:56.686  7221  7221 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 16:54:56.686  7221  7221 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 16:54:56.686  7221  7221 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 16:54:56.686  7221  7221 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 16:54:56.707   321  7226 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 16:54:56.735  1031  1870 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7242 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 16:54:56.737  1031  1870 I ActivityManager: Killing 2179:com.lge.music/u0a34 (adj 15): empty #17
08-26 16:54:56.763   325  2189 V AudioFlinger: 2179 died, releasing its sessions
08-26 16:54:56.763   325  2189 V AudioFlinger:  pid 1836 @ 0
08-26 16:54:56.763   325  2189 V AudioFlinger:  pid 3439 @ 1
08-26 16:54:56.763   325  2189 V AudioFlinger:  pid 3439 @ 2
,08-26 16:54:56.767   321   889 D LGDataListener: argv[0]=dsqncommand
08-26 16:54:56.767   321   889 D LGDataListener: argv[1]=wlan0
08-26 16:54:56.767   321   889 D LGDataListener: argv[2]=1
08-26 16:54:56.767   321   889 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 16:54:56.767  1031  1100 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 16:54:56.767  1031  1100 D DSQN    : start to monitor internet connection
08-26 16:54:56.808  1031  2017 W libprocessgroup: failed to open /acct/uid_10034/pid_2179/cgroup.procs: No such file or directory
08-26 16:54:56.808  1800  7232 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 16:54:56.812  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 14:54:56 GMT], X-Android-Received-Millis=[1472223296812], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472223296766]}
08-26 16:54:56.813  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 16:54:56.813  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 16:54:56.813  1031  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 16:54:56.813  1031  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 16:54:56.813  1031  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 16:54:56.813  1031  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:54:56.813  1031  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 16:54:56.813  1031  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 16:54:56.813  1031  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 16:54:56.813  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:56.813  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:54:56.814  1031  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:54:56.814  1031  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:56.814  1587  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 16:54:56.814  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 16:54:56.815  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:56.815  1031  1522 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:56.815  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 16:54:56.815  1031  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 16:54:56.843  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 16:54:56.844  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:56.845  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:54:56.916   281   350 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 16:54:56.916   281   350 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-26 16:54:56.916   281   350 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 16:54:56.917  7242  7278 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 16:54:56.918   281   350 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 16:54:56.918   281   350 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 16:54:56.918   281   350 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 16:54:56.918  7242  7278 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 16:54:56.937   281   350 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 16:54:56.937   281   350 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 16:54:56.937   281   350 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 16:54:56.938  7242  7280 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-26 16:54:56.946   281   350 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-26 16:54:56.947   281   350 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 16:54:56.947   281   350 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 16:54:56.947  7242  7280 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 16:54:56.963  1031  2017 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7283 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-26 16:54:56.966  1031  7201 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 16:54:56.967  1031  7201 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 16:54:56.967  1031  7201 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 16:54:56.967  1031  7201 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 16:54:56.967  1031  7201 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 16:54:56.967  1031  7201 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 16:54:56.967  1031  7201 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 16:54:56.967  1031  7201 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 16:54:56.968  1031  7201 D DhcpStateMachine: RunningState
,08-26 16:54:57.017  1031  1400 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23ad8a59 type 2 when 124868 com.google.android.gms} when 124868
,08-26 16:54:57.018  7283  7283 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 16:54:57.018  7283  7283 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 16:54:57.047  7283  7283 I MultiDex: VM with version 2.1.0 has multidex support
08-26 16:54:57.047  7283  7283 I MultiDex: install
08-26 16:54:57.047  7283  7283 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 16:54:57.057  7283  7283 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-26 16:54:57.167  7242  7242 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 16:54:57.188  7242  7242 I LibraryLoader: Loading: webviewchromium
,08-26 16:54:57.193  7242  7242 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5052-5057)
08-26 16:54:57.193  7242  7242 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 16:54:57.203  7242  7242 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c2b4f0d}
,08-26 16:54:57.205  7242  7242 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 16:54:57.206  7242  7242 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 16:54:57.220  7242  7242 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 16:54:57.221  7242  7242 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 16:54:57.250   325  2188 V AudioPolicyService: registerClient() client 0xb558a760, uid 10093
,08-26 16:54:57.252  7242  7320 W AudioManagerAndroid: Requires BLUETOOTH permission
08-26 16:54:57.254  7242  7242 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 16:54:57.256  7242  7242 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-26 16:54:57.256  7242  7242 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-26 16:54:57.271  7242  7242 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 16:54:57.271  7242  7242 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 16:54:57.271  7242  7242 I Adreno-EGL: Build Date: 12/12/14 금
08-26 16:54:57.271  7242  7242 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 16:54:57.271  7242  7242 I Adreno-EGL: Remote Branch: 
08-26 16:54:57.271  7242  7242 I Adreno-EGL: Local Patches: 
08-26 16:54:57.271  7242  7242 I Adreno-EGL: Reconstruct Branch: 
,08-26 16:54:57.537  7336  7336 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 16:54:57.561  1031  1925 I art     : Explicit concurrent mark sweep GC freed 86531(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.811ms total 180.991ms
,08-26 16:54:57.562  7242  7242 I NSApplication: Starting up...
,08-26 16:54:57.627  1031  1050 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7343 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-26 16:54:57.628  1031  1050 I ActivityManager: Killing 6155:com.android.vending/u0a44 (adj 15): empty #17
,08-26 16:54:57.630  7336  7336 I dex2oat : dex2oat took 92.556ms (threads: 4)
08-26 16:54:57.632  1031  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 16:54:57.648  7283  7300 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 16:54:57.648  7283  7300 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 16:54:57.648  7283  7300 I Adreno-EGL: Build Date: 12/12/14 금
08-26 16:54:57.648  7283  7300 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 16:54:57.648  7283  7300 I Adreno-EGL: Remote Branch: 
08-26 16:54:57.648  7283  7300 I Adreno-EGL: Local Patches: 
08-26 16:54:57.648  7283  7300 I Adreno-EGL: Reconstruct Branch: 
,08-26 16:54:57.706  1031  1926 D WifiServiceImplEx: setWifiEnabled: false pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 16:54:57.707  1031  1926 D WifiService: setWifiEnabled: false pid=6679, uid=10118
08-26 16:54:57.707  1031  1926 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 16:54:57.709  1031  1870 W libprocessgroup: failed to open /acct/uid_10044/pid_6155/cgroup.procs: No such file or directory
08-26 16:54:57.719  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 16:54:57.719  1031  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:57.719  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 16:54:57.719  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-26 16:54:57.719  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:57.720  1031  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:57.720  1031  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:57.721  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 16:54:57.721  1031  1522 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 16:54:57.721  1031  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 16:54:57.721  1031  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 16:54:57.721  1031  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 16:54:57.721  1031  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-26 16:54:57.729  1031  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 16:54:57.729  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 16:54:57.729  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 16:54:57.730  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.730  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.730  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 16:54:57.730  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 16:54:57.730  1031  1522 D WifiNative-wlan0: SET ps 1: returned true
08-26 16:54:57.731   321   890 D CommandListener: Clearing all IP addresses on wlan0
08-26 16:54:57.731  1031  7201 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.749  7343  7343 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 16:54:57.761  1031  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 16:54:57.761  1031  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-26 16:54:57.764  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-26 16:54:57.765  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:57.765  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:57.765  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 16:54:57.766  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 16:54:57.767  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:57.767  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:57.770  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-26 16:54:57.774  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:57.774  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:57.775  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 16:54:57.777  1031  1521 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.777  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.777  1031  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@32eedbe8
,08-26 16:54:57.786  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:57.786  1031  1521 D LGWifiP2pService: P2pDisablingState
08-26 16:54:57.786  1031  1521 D LGWifiP2pService: P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.786  1031  1521 D LGWifiP2pService: p2p socket connection lost
08-26 16:54:57.786  1031  1521 D LGWifiP2pService: P2pDisabledState
08-26 16:54:57.786  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 16:54:57.787  1031  1031 D RttService: SCAN_AVAILABLE : 1
08-26 16:54:57.787  1031  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.787  1031  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.787  1031  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 16:54:57.788  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:57.788  1031  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:54:57.788  1031  1522 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 16:54:57.789  1031  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 16:54:57.789  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 16:54:57.789  7121  7121 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 16:54:57.791  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:54:57.791  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:54:57.792  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 16:54:57.792  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 16:54:57.792  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 16:54:57.792  1927  1927 D WfdsService: WifiP2pState is changed : false
08-26 16:54:57.792  1927  2231 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 16:54:57.792  1927  2231 D WfdsService: Set the WFDS Monitor: false
08-26 16:54:57.793  1031  1522 D WifiNative-wlan0: SET ps 1: returned true
,08-26 16:54:57.793  1927  2231 D WfdsMonitor: WFDS Monitor is stopped
08-26 16:54:57.793  1927  2231 D WfdsService: STATE : WfdsDisabledState - enter
08-26 16:54:57.793  1927  7153 D CtrlSupplicant: Received on exit socket, terminate
08-26 16:54:57.793  1927  7153 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 16:54:57.793  1927  7153 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 16:54:57.793  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:57.793  1927  7153 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 16:54:57.793  1927  2235 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 16:54:57.794  1927  2231 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 16:54:57.794  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.794  1031  1521 D LGWifiP2pService: DefaultState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.814   321   890 D CommandListener: Clearing all IP addresses on wlan0
08-26 16:54:57.815  1031  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 16:54:57.815  1031  1529 D DSQN    : disableDataServiceNotify
08-26 16:54:57.815  1031  1529 D DSQN    : stop dsqn bin
08-26 16:54:57.817  1031  1522 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 16:54:57.818  1031  1031 D WifiHS20: hidePasspointNotification off =false
08-26 16:54:57.818  1031  1522 D WifiNative-p2p0: TERMINATE: returned true
08-26 16:54:57.819  1031  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 16:54:57.819  1031  1522 E WifiStateMachine: useWiFiOffloading() : false
08-26 16:54:57.819  1031  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 16:54:57.819  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 16:54:57.819  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 16:54:57.821  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:57.821  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:57.821  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 16:54:57.822  1031  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 16:54:57.822  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:57.822  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:54:57.822  1031  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:54:57.823  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:57.823  1031  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 16:54:57.824  1031  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 16:54:57.824  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.824  1031  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 16:54:57.824  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:54:57.824  1031  7200 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 16:54:57.824  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 16:54:57.824  1587  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 16:54:57.826  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 16:54:57.826  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:54:57.826  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 16:54:57.827  1031  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:57.827  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 16:54:57.827  1031  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:57.827  1031  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:57.827  1031  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:57.828  1031  1522 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1,, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:57.828  1031  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 16:54:57.828  1031  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 16:54:57.829  1031  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-26 16:54:57.830  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 16:54:57.831  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 16:54:57.831  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-26 16:54:57.831  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 16:54:57.831  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 16:54:57.831  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 16:54:57.831  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 16:54:57.831  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 16:54:57.831  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 16:54:57.836  1031  1529 D NetworkManagementService: Removing idletimer
08-26 16:54:57.836  1031  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:57.836  1031  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 16:54:57.837  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:54:57.837  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 16:54:57.837  7283  7300 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 16:54:57.837  7283  7300 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 16:54:57.837  7283  7300 I Adreno-EGL: Build Date: 12/12/14 금
08-26 16:54:57.837  7283  7300 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 16:54:57.837  7283  7300 I Adreno-EGL: Remote Branch: 
08-26 16:54:57.837  7283  7300 I Adreno-EGL: Local Patches: 
08-26 16:54:57.837  7283  7300 I Adreno-EGL: Reconstruct Branch: 
08-26 16:54:57.837  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:57.837  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:57.837  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:57.837  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:57.837  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:57.837  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:57.837  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:57.837  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:57.837  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:54:57.837  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:57.837  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:57.838  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored valu,e
08-26 16:54:57.838  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:57.838  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:57.838  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:57.838  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:57.838  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:57.838  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:57.838  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:57.838  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:57.838  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:57.838  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:54:57.844  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:54:57.864  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 16:54:57.865  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:57.865  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:54:57.889  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 16:54:57.889  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:57.890  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:57.926  7121  7121 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 16:54:57.927  7121  7121 I wpa_supplicant: monitor socket send errors count : 1
08-26 16:54:57.927  7121  7121 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
08-26 16:54:57.927  1031  7137 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 16:54:57.928  1031  7137 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-26 16:54:57.947  1031  7201 D DhcpStateMachine: StoppedState
08-26 16:54:57.948  1031  7201 D DhcpStateMachine: StoppedState{ when=-155ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 16:54:57.951  1031  1522 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 16:54:57.951  7283  7300 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 16:54:57.951  7283  7300 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 16:54:57.951  7283  7300 I Adreno-EGL: Build Date: 12/12/14 금
08-26 16:54:57.951  7283  7300 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 16:54:57.951  7283  7300 I Adreno-EGL: Remote Branch: 
08-26 16:54:57.951  7283  7300 I Adreno-EGL: Local Patches: 
08-26 16:54:57.951  7283  7300 I Adreno-EGL: Reconstruct Branch: 
08-26 16:54:57.952  1031  1522 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 16:54:57.968  7121  7121 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 16:54:57.969  7121  7121 W wpa_supplicant: USIM:  scard_deinit function
08-26 16:54:57.969  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 16:54:57.969  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 16:54:57.969  1031  7137 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 16:54:57.969  1031  1102 D Tethering: InitialState.processMessage what=4
08-26 16:54:57.969  1031  7137 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 16:54:57.970  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:54:57.970  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:54:57.970  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 16:54:57.970  1031  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=125821
08-26 16:54:57.970  1031  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=125821
08-26 16:54:57.971  1031  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=125822  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 16:54:57.971  1031  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=125822  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 16:54:57.971  1031  1522 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:57.972  1031  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:54:57.998  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 16:54:58.001  6484  6513 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 16:54:58.010  2115  2115 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:58.016  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 16:54:58.016  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:58.016  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 16:54:58.016  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 16:54:58.018  7052  7052 I AppUp4:CustModeStarterReceiver: onReceive
08-26 16:54:58.021  7052  7052 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@327310ba
08-26 16:54:58.021  7052  7052 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 16:54:58.021  7052  7052 D AppUp4:CustFacade: isPhone : true
08-26 16:54:58.021  7052  7052 D AppUp4:CustModeStarterReceiver: begin check event
08-26 16:54:58.022  7052  7052 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 16:54:58.024  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:58.024  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 16:54:58.026  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:54:58.027  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:54:58.032  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 16:54:58.036  4356  7381 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 16:54:58.038  4356  7383 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:58.038  4356  7383 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 16:54:58.046  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 16:54:58.047  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:58.047  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 16:54:58.049  6960  7387 W FormManager: Network not available. Please check & try again.
08-26 16:54:58.049  7094  7384 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:54:58.051  7143  7143 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 16:54:58.052  7143  7143 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 16:54:58.056  6960  7388 V FormManager: Network unavailable.
08-26 16:54:58.059  6960  7388 V FormManager: Network unavailable.
,08-26 16:54:58.063  7202  7202 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:54:58
08-26 16:54:58.065  7202  7202 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 16:54:58.065  7202  7202 D Weather.Utils: 2 : All the weather widget is gone.
08-26 16:54:58.065  7202  7202 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 16:54:58.065  7202  7202 D WeatherAncestor: connectivity changed - connection : true
08-26 16:54:58.065  7202  7202 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6d1d6c8
08-26 16:54:58.066  7202  7202 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 16:54:58.066  7202  7202 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 16:54:58.066  7202  7202 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 16:54:58.066  7202  7202 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 16:54:58.066  7202  7202 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:54:58
08-26 16:54:58.089  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 16:54:58.089  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 16:54:58.089  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 16:54:58.089  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 16:54:58.089  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-26 16:54:58.090  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-26 16:54:58.090  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 16:54:58.090  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 16:54:58.090  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 16:54:58.090  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 16:54:58.091  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 16:54:58.098  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:54:58.099  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 16:54:58.107  6960  7393 W FormManager: Network not available. Please check & try again.
08-26 16:54:58.108  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.108  6960  7394 V FormManager: Network unavailable.
08-26 16:54:58.112  6960  7394 V FormManager: Network unavailable.
,08-26 16:54:58.118  7121  7121 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 16:54:58.118  1031  7137 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 16:54:58.118  1031  7137 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 16:54:58.118  1031  7137 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 16:54:58.119  1031  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-26 16:54:58.123  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:54:58.126  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 16:54:58.128  6960  7396 W FormManager: Network not available. Please check & try again.
08-26 16:54:58.132  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.132  6960  7397 V FormManager: Network unavailable.
08-26 16:54:58.136  6960  7397 V FormManager: Network unavailable.
08-26 16:54:58.144  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 16:54:58.144  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 16:54:58.145  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 16:54:58.148  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:54:58.151  4356  7398 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 16:54:58.153  4356  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 16:54:58.154  4356  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 16:54:58.185  1031  1631 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7400 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 16:54:58.210  7283  7300 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 16:54:58.210  7283  7300 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 16:54:58.220  1031  1522 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 16:54:58.220  1031  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 16:54:58.220  1031  1522 E WifiStateMachine: useWiFiOffloading() : false
08-26 16:54:58.220  1031  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 16:54:58.220  1927  1927 D WfdsService: Supplicant Connection state is changed : false
08-26 16:54:58.220  1927  2231 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 16:54:58.221  1927  2231 D WfdsService: Set the WFDS Monitor: false
08-26 16:54:58.221  1927  2231 D WfdsMonitor: WFDS Monitor is stopped
08-26 16:54:58.221  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:54:58.222  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 16:54:58.222  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 16:54:58.223  1031  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 16:54:58.223  1031  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-26 16:54:58.223  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:54:58.223  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:54:58.223  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:54:58.223  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:54:58.223  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:54:58.223  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:54:58.223  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:54:58.223  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:54:58.223  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:54:58.224  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:58.227  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 16:54:58.255   321  7418 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 16:54:58.255  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 16:54:58.256  1800  7232 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-26 16:54:58.263  1800  7232 I CheckinService: active receiver: disabled
,08-26 16:54:58.287  7400  7400 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 16:54:58.287  7400  7400 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 16:54:58.292  7400  7400 V [BNRBootReceiver]: Boot Receiver Return
08-26 16:54:58.293  7400  7400 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 16:54:58.295  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:58.303  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.309  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.321  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.322  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:58.324  6920  6920 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 16:54:58.327  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 16:54:58.333  6853  6853 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 16:54:58.339  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 16:54:58.352  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.361  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.373  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 16:54:58.374  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:54:58.378  6920  6920 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 16:54:58.384  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:58.396  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.408  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 16:54:58.421  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.422  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:54:58.423  6920  6920 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 16:54:58.430  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:58.444  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.455  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.474  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.475  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:58.477  6920  6920 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 16:54:58.483  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:58.500  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.511  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.520  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.521  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:58.522  6920  6920 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 16:54:58.529  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:58.539  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:54:58.541  6755  7041 D UEI.SmartControl: Internal timer expired: 2
,08-26 16:54:58.541  6755  7041 D UEI.SmartControl: unbind internal service
,08-26 16:54:58.547  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.557  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.558  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:58.559  6920  6920 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 16:54:58.564  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:58.580  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.591  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 16:54:58.603  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.603  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:54:58.604  6920  6920 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 16:54:58.622  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 16:54:58.643  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.646  6755  7038 D serial_port: close(fd = 24)
,08-26 16:54:58.650  6755  7038 I UEI.SmartControl: Serial port is closed.
08-26 16:54:58.654  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.664  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.665  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:58.674  6920  6920 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 16:54:58.683  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 16:54:58.700  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.712  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.737  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.738  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:54:58.740  6920  6920 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 16:54:58.752  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 16:54:58.766  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 16:54:58.785  1031  1528 D WifiService: New client listening to asynchronous messages
08-26 16:54:58.787  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 16:54:58.796  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.811  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 16:54:58.831  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.832  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:58.835  6920  6920 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-26 16:54:58.840  6920  6920 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 16:54:58.841  6920  6920 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 16:54:58.857  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 16:54:58.867  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 16:54:58.870  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:54:58.879  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:58.893  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:58.906  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:58.906  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:58.911  6920  6920 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 16:54:58.912  6920  6920 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 16:54:58.913  6920  6920 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 16:54:58.917  1031  2319 I ActivityManager: Killing 6893:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-26 16:54:58.920   321  7425 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-26 16:54:58.921  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 16:54:58.957  1031  1980 W libprocessgroup: failed to open /acct/uid_10037/pid_6893/cgroup.procs: No such file or directory
,08-26 16:54:58.968  2115  2115 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 16:54:58.978  2115  2115 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 16:54:58.981  2115  2115 D c       : Getting all permits...
08-26 16:54:58.981  2115  2115 D a       : Opening database...
08-26 16:54:58.986  2115  2115 D a       : Opening database auth.proximity.permit_store...
08-26 16:54:58.987  2115  2115 D a       : Closing database...
08-26 16:54:59.002  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 16:54:59.009  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 16:54:59.009  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 16:54:59.009  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:54:59.014  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:59.022  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:59.033  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 16:54:59.034  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:59.037  6920  6920 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 16:54:59.043  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:59.050  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 16:54:59.050  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 16:54:59.050  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 16:54:59.054  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:54:59.061  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:59.073  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:59.073  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:59.074  6920  6920 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 16:54:59.080  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:54:59.088  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 16:54:59.088  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 16:54:59.088  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 16:54:59.095  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:54:59.101  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:59.109  6920  6920 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:54:59.109  6920  6920 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:54:59.111  6920  6920 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 16:54:59.120  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 16:54:59.127  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 16:54:59.133  6960  7430 W FormManager: Network not available. Please check & try again.
,08-26 16:54:59.140  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:59.149  6960  7431 V FormManager: Network unavailable.
,08-26 16:54:59.157  6960  7431 V FormManager: Network unavailable.
08-26 16:54:59.166  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 16:54:59.166  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 16:54:59.171  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:54:59.179  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 16:54:59.191  4356  7432 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 16:54:59.195  6872  6872 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 16:54:59.195  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 16:54:59.195  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:54:59.201  4356  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 16:54:59.201  4356  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 16:54:59.204  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 16:54:59.207  6960  7435 W FormManager: Network not available. Please check & try again.
,08-26 16:54:59.212  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:54:59.220  6960  7436 V FormManager: Network unavailable.
,08-26 16:54:59.225  6960  7436 V FormManager: Network unavailable.
08-26 16:54:59.229  2115  2115 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-26 16:54:59.359  1031  1522 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-950483170] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 16:54:59.361  1031  1522 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-950483167] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 16:54:59.614  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:59.627  1031  1102 D Tethering: MasterInitialState.processMessage what=3
08-26 16:54:59.636  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:54:59.641  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:54:59.644  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:59.646  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 16:54:59.648  6484  6513 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 16:54:59.649  5817  5817 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 16:54:59.680  2115  2115 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:54:59.699  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 16:54:59.699  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:59.699  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 16:54:59.699  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 16:54:59.704  7052  7052 I AppUp4:CustModeStarterReceiver: onReceive
08-26 16:54:59.707  7052  7052 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@327310ba
08-26 16:54:59.707  7052  7052 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 16:54:59.707  7052  7052 D AppUp4:CustFacade: isPhone : true
08-26 16:54:59.708  7052  7052 D AppUp4:CustModeStarterReceiver: begin check event
08-26 16:54:59.708  7052  7052 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 16:54:59.712  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:59.713  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 16:54:59.714  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 16:54:59.720  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:54:59.728  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 16:54:59.756  7094  7444 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 16:54:59.760  4356  7445 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 16:54:59.763  4356  7448 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:59.763  4356  7448 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 16:54:59.773  6960  7446 W FormManager: Network not available. Please check & try again.
,08-26 16:54:59.779  6960  7447 V FormManager: Network unavailable.
08-26 16:54:59.781  6960  7447 V FormManager: Network unavailable.
08-26 16:54:59.796  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 16:54:59.808  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-26 16:54:59.808  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 16:54:59.808  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 16:54:59.808  3439  3439 D PhoneState: setPdpRejectCasuse : false
08-26 16:54:59.813  7143  7143 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 16:54:59.813  7143  7143 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 16:54:59.831  7202  7202 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:54:59
,08-26 16:54:59.833  7202  7202 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 16:54:59.833  7202  7202 D Weather.Utils: 2 : All the weather widget is gone.
08-26 16:54:59.834  7202  7202 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 16:54:59.834  7202  7202 D WeatherAncestor: connectivity changed - connection : true
08-26 16:54:59.834  7202  7202 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6d1d6c8
08-26 16:54:59.835  7202  7202 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 16:54:59.835  7202  7202 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 16:54:59.835  7202  7202 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 16:54:59.835  7202  7202 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 16:54:59.835  7202  7202 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:54:59
08-26 16:55:00.001  1031  1400 D PowerManagerServiceEx: acquireWakeLockInternal: lock=893792392, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,08-26 16:55:00.016  6920  6920 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-26 16:55:00.017  6920  6920 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1419
,08-26 16:55:00.066  2583  2583 D [Concierge]Service: onStartCommand(). Type : 9
,08-26 16:55:00.067  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-26 16:55:00.067  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 16:55:00.068  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-26 16:55:00.073  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
08-26 16:55:00.078  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 16:55:00.078  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
,08-26 16:55:00.080  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-26 16:55:00.082  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 16:55:00.135  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=893792392 [*alarm*], flags=0x0
,08-26 16:55:00.720  1031  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 16:55:00.721  1031  1925 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 16:55:00.743  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 16:55:00.743  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 16:55:00.744  1031  1031 D Ulp_jni : JNI:system_update. Event-4
08-26 16:55:00.745  1031  1102 D BluetoothManagerService: Message: 1
08-26 16:55:00.746  1031  1102 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 16:55:00.779  1031  1102 D BluetoothManagerService: Message: 20
08-26 16:55:00.780  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@699355c:true
,08-26 16:55:00.783  6997  6997 D BluetoothAdapterState: make
08-26 16:55:00.788  6997  6997 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 16:55:00.788  6997  6997 I bluedroid-qcom: init
08-26 16:55:00.789  6997  7478 I BluetoothAdapterState: Entering OffState
08-26 16:55:00.790  6997  6997 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 16:55:00.790  6997  6997 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 16:55:00.790  6997  6997 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 16:55:00.790  6997  6997 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 16:55:00.790  6997  6997 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 16:55:00.792  6997  6997 I bluedroid-qcom: get_profile_interface socket
08-26 16:55:00.792  6997  6997 I bluedroid-qcom: get_profile_interface map_client
,08-26 16:55:00.797  6997  7482 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 16:55:00.799  6997  7482 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 16:55:00.785  7481  7481 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:00.785  7481  7481 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:00.812  7481  7481 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 16:55:00.812  7481  7481 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 16:55:00.812  7481  7481 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 16:55:00.815  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 16:55:00.817  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 16:55:00.819  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 16:55:00.822  1031  1102 D BluetoothManagerService: Message: 40
08-26 16:55:00.822  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 16:55:00.823  6997  7020 I bluedroid-qcom: config_hci_snoop_log
08-26 16:55:00.826  7481  7481 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-26 16:55:00.830  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:00.833  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 16:55:00.833  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 16:55:00.836  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:00.842  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:00.845  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:00.853  7481  7481 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 16:55:00.853  7481  7481 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 16:55:00.857  6997  7478 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-26 16:55:00.859  1031  1102 D Tethering: MasterInitialState.processMessage what=3
,08-26 16:55:00.863  1031  1102 D Tethering: MasterInitialState.processMessage what=3
08-26 16:55:00.863  6997  7482 D BluetoothAdapterProperties: Name is: G3
08-26 16:55:00.863  6997  7478 D BluetoothAdapterProperties: Setting state to 11
08-26 16:55:00.863  6997  7478 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 16:55:00.865  6997  7478 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 16:55:00.866  1031  1102 D BluetoothManagerService: Message: 60
08-26 16:55:00.866  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 16:55:00.866  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 16:55:00.882  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 16:55:00.890  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 16:55:00.892  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 16:55:00.895  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 16:55:00.898  6997  7478 D BluetoothBondStateMachine: make
08-26 16:55:00.899  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:00.899  6484  6513 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 16:55:00.902  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:00.903  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:00.904  6997  6997 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 16:55:00.904  6997  6997 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:00.904  6997  6997 V BluetoothPbapReceiver: ***********state = 11
08-26 16:55:00.906  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:00.907  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:00.907  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:00.908  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:00.909  6997  7478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
,08-26 16:55:00.909  6997  7478 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 16:55:00.909  6997  7478 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:00.909  6997  7478 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 16:55:00.910  6997  7478 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 16:55:00.911  6997  7497 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 16:55:00.914  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:00.916  2115  2115 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 16:55:00.917  6997  7478 E BluetoothAdapterService: File transfer profiles supported!!
08-26 16:55:00.919  5817  5817 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 16:55:00.967  1031  1998 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7501 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 16:55:00.975  6997  6997 D HeadsetService: Received start request. Starting profile...
08-26 16:55:00.975  5817  5817 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 16:55:00.976  6997  6997 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 16:55:00.976  6997  6997 D LGBluetoothHfpAdapter: Version 1.6
08-26 16:55:00.979  6997  6997 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 16:55:00.981  6997  6997 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 16:55:00.981  6997  6997 D HeadsetStateMachine: make
,08-26 16:55:00.984  6997  7478 E BluetoothAdapterService: File transfer profiles supported!!
08-26 16:55:00.992  6997  7478 E BluetoothAdapterService: File transfer profiles supported!!
08-26 16:55:00.998  6997  7478 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 16:55:01.014  2115  2115 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 16:55:01.016  6997  7478 E BluetoothAdapterService: File transfer profiles supported!!
08-26 16:55:01.018  6997  6997 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:55:01.018  6997  6997 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 16:55:01.026  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 16:55:01.026  6997  6997 D HeadsetStateMachine: max_hf_connections = 1
08-26 16:55:01.026  6997  6997 I bluedroid-qcom: get_profile_interface handsfree
08-26 16:55:01.028  6997  6997 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-26 16:55:01.029  6997  7478 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 16:55:01.030   325  1369 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 1002
08-26 16:55:01.030  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:01.030   325  2189 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 16:55:01.030   325  2189 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 16:55:01.030   325  2189 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 16:55:01.030  6997  6997 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 16:55:01.031   325  2188 V AudioFlinger: registerClient() client 0xb55818f8, pid 6997
08-26 16:55:01.031   325  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:01.031   325  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:01.031  1587  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:01.031  1587  2094 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:01.031   325  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:01.031   325  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 16:55:01.031  3439  3458 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:01.031  1836  4028 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:01.031  3439  3458 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:01.031  1836  4028 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:01.031  3439  3458 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:01.031  3439  3458 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 16:55:01.031  1836  4028 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:01.032  1836  4028 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 16:55:01.032  1587  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:01.032  1587  2094 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 16:55:01.032  6997  7020 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:01.032  1031  1926 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:01.032  1031  1926 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:01.032  1031  1926 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:01.032  1031  1926 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 16:55:01.032  6997  7020 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 16:55:01.032  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 16:55:01.032  6997  6997 V ToneGenerator: Create Track: 0xb4928a80
08-26 16:55:01.032  6997  7020 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:01.032  6997  6997 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 16:55:01.032  6997  7020 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 16:55:01.032  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 16:55:01.032  6997  6997 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 16:55:01.033   325  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 16:55:01.033   325  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 16:55:01.033   325  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 16:55:01.033   325  1368 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 16:55:01.033 ,  325  1369 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 16:55:01.033   325  2189 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 16:55:01.033   325  2189 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 16:55:01.033   325  2189 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 16:55:01.033   325  2189 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 16:55:01.033  6997  6997 V AudioSystem: getLatency() output 2, latency 50
08-26 16:55:01.033  6997  6997 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 16:55:01.033  6997  6997 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 16:55:01.034   325   325 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 16:55:01.034   325   325 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 16:55:01.034   325   325 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 16:55:01.034   325   325 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 16:55:01.034   325   325 V AudioFlinger: createTrack() lSessionId: 22
08-26 16:55:01.035  6997  6997 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 16:55:01.035  7052  7052 I AppUp4:CustModeStarterReceiver: onReceive
08-26 16:55:01.035   325   325 V AudioFlinger: acquiring 22 from 6997, for 6997
08-26 16:55:01.035   325   325 V AudioFlinger:  added new entry for 22
08-26 16:55:01.035  6997  6997 V ToneGenerator: ToneGenerator INIT OK, time: 128900
08-26 16:55:01.036  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:01.036  6997  7517 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 16:55:01.036  6997  7517 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 16:55:01.036  6997  7517 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 16:55:01.036  6997  7517 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 16:55:01.037   325  1368 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6997
08-26 16:55:01.037   325  1368 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 16:55:01.037   325  1368 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 16:55:01.037   325  1368 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 16:55:01.037   325  1368 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 16:55:01.037   325  1368 V voice   : voice_set_parameters: exit with code(0)
08-26 16:55:01.037   325  1368 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 16:55:01.037   325  1368 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 16:55:01.038   325  1368 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 16:55:01.038   325  1368 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 16:55:01.038   325  1368 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 16:55:01.038   325  1368 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,08-26 16:55:01.038  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:01.039  6997  6997 D A2dpService: Received start request. Starting profile...
08-26 16:55:01.040  6997  6997 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 16:55:01.040  6997  6997 V Avrcp   : make
08-26 16:55:01.041  6997  6997 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 16:55:01.041  6997  6997 I bluedroid-qcom: get_profile_interface avrcp
08-26 16:55:01.041  6997  7517 V ToneGenerator: ToneGenerator destructor
08-26 16:55:01.042  6997  7478 E BluetoothAdapterService: File transfer profiles supported!!
08-26 16:55:01.044  6997  7517 V ToneGenerator: stopTone
08-26 16:55:01.044  6997  7517 V ToneGenerator: Delete Track: 0xb4928a80
,08-26 16:55:01.046  6997  7517 V AudioTrack: ~AudioTrack, releasing session id from 6997 on behalf of 6997
08-26 16:55:01.046   325  1369 V AudioFlinger: releasing 22 from 6997 for 6997
08-26 16:55:01.046   325  1369 V AudioFlinger:  decremented refcount to 0
08-26 16:55:01.046   325  1369 V AudioFlinger: purging stale effects
08-26 16:55:01.046   325  1369 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 16:55:01.046   325  1369 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 16:55:01.046   325  1258 V AudioPolicyService: AudioCommandThread() waking up
08-26 16:55:01.046   325  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 16:55:01.046   325  1258 V AudioPolicyManager: releaseOutput() 2
08-26 16:55:01.046   325  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 16:55:01.046   325  1369 V AudioFlinger: PlaybackThread::Track destructor
08-26 16:55:01.046   325  1369 V AudioFlinger: removeClient_l() pid 6997, calling pid 325
08-26 16:55:01.050  7052  7052 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@327310ba
08-26 16:55:01.051  6997  6997 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 16:55:01.053  7052  7052 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 16:55:01.053  7052  7052 D AppUp4:CustFacade: isPhone : true
08-26 16:55:01.053  6997  6997 E AudioManager: No RCC entry present to update
08-26 16:55:01.053  6997  6997 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 16:55:01.053  7052  7052 D AppUp4:CustModeStarterReceiver: begin check event
08-26 16:55:01.053  7052  7052 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 16:55:01.056  6997  6997 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 16:55:01.056  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:01.056  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 16:55:01.057  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 16:55:01.057  6997  6997 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-26 16:55:01.060  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 16:55:01.061  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:55:01.062  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:55:01.065  6997  7478 V LGMDMManager: Create singleton instance
08-26 16:55:01.070  6997  7478 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 16:55:01.113  4356  7527 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 16:55:01.117  7501  7501 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 16:55:01.117  7501  7501 W LG Account v2.2: No ProfileInfo entries
08-26 16:55:01.118  7501  7501 I LG Account v2.2: isEnabled: false
,08-26 16:55:01.118  7501  7501 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,08-26 16:55:01.118  7501  7501 I Feature : [Lifetracker]Country: EU
08-26 16:55:01.118  7501  7501 I Feature : [Lifetracker]Operator: OPEN
08-26 16:55:01.118  7501  7501 I Feature : [Lifetracker]Ranking support: false
08-26 16:55:01.118  7501  7501 I Feature : [Lifetracker]Comfort support: false
08-26 16:55:01.119  7501  7501 I Feature : [Lifetracker]Accessory: true
08-26 16:55:01.119  7501  7501 I Feature : [Lifetracker]Health device: true
08-26 16:55:01.119  7501  7501 I Feature : [Lifetracker]Extra Pedometer: false
08-26 16:55:01.119  7501  7501 I Feature : [Lifetracker]Blood glucose device: false
08-26 16:55:01.119  7501  7501 I Feature : [Lifetracker]Device Number: 3
,08-26 16:55:01.120  4356  7528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:01.121  4356  7528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 16:55:01.123  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 16:55:01.142  6853  6853 D BluetoothPermissionRequest: onReceive
,08-26 16:55:01.150  1031  1926 V SIM_STK : Menu title from STK is T-Mobile
,08-26 16:55:01.150  1031  1926 V SIM_STK : Menu title from STK is T-Mobile
08-26 16:55:01.155  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 16:55:01.172  7094  7529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 16:55:01.182  6960  7531 W FormManager: Network not available. Please check & try again.
,08-26 16:55:01.185  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 16:55:01.185  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:01.185  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 16:55:01.188  7143  7143 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 16:55:01.188  7143  7143 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 16:55:01.196  6960  7532 V FormManager: Network unavailable.
08-26 16:55:01.199  7202  7202 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:1
,08-26 16:55:01.202  7202  7202 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 16:55:01.202  7202  7202 D Weather.Utils: 2 : All the weather widget is gone.
08-26 16:55:01.202  7202  7202 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 16:55:01.202  6960  7532 V FormManager: Network unavailable.
08-26 16:55:01.202  7202  7202 D WeatherAncestor: connectivity changed - connection : true
08-26 16:55:01.202  1031  2319 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 16:55:01.202  7202  7202 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6d1d6c8
08-26 16:55:01.203  7202  7202 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 16:55:01.203  7202  7202 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 16:55:01.203  7202  7202 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 16:55:01.203  7202  7202 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 16:55:01.203  7202  7202 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:1
08-26 16:55:01.207  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 16:55:01.210  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 16:55:01.210  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 16:55:01.210  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 16:55:01.210  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 16:55:01.210  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 16:55:01.210  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 16:55:01.210  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 16:55:01.210  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 16:55:01.211  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 16:55:01.211  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 16:55:01.211  6997  6997 I BluetoothA2dpServiceJni: classInitNative
,08-26 16:55:01.211  6997  6997 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 16:55:01.211  6997  6997 D A2dpStateMachine: make
08-26 16:55:01.214  6997  6997 I bluedroid-qcom: get_profile_interface a2dp
08-26 16:55:01.214  6997  7535 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 16:55:01.215  6997  6997 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 16:55:01.215  6997  6997 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 16:55:01.216  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:01.216  6997  7534 D A2dpStateMachine: Enter Disconnected: -2
08-26 16:55:01.217  6997  6997 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 16:55:01.218  6997  6997 D HidService: Received start request. Starting profile...
08-26 16:55:01.218  6997  6997 I bluedroid-qcom: get_profile_interface hidhost
08-26 16:55:01.218  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:01.218  6997  6997 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 16:55:01.219  6997  6997 D HealthService: Received start request. Starting profile...
08-26 16:55:01.221  6997  6997 I bluedroid-qcom: get_profile_interface health
08-26 16:55:01.221  6997  6997 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 16:55:01.221  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:01.221  6997  6997 D HeadsetStateMachine: Proxy object connected
08-26 16:55:01.222  6997  6997 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 16:55:01.222  6997  6997 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-26 16:55:01.224  6997  6997 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 16:55:01.225  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 16:55:01.226  6997  6997 D PanService: Received start request. Starting profile...
08-26 16:55:01.226  6997  6997 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 16:55:01.226  6997  6997 I bluedroid-qcom: get_profile_interface pan
08-26 16:55:01.227  6484  6513 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 16:55:01.232  6997  6997 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 16:55:01.232  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
,08-26 16:55:01.233  6997  6997 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 16:55:01.239  6997  6997 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 16:55:01.239  2115  2115 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:01.240  6997  6997 D BtGatt.GattService: Received start request. Starting profile...
08-26 16:55:01.240  6997  6997 D BtGatt.GattService: start()
08-26 16:55:01.240  6997  6997 I bluedroid-qcom: get_profile_interface gatt
08-26 16:55:01.241  6997  6997 D BtGatt.AdvertiseManager: advertise manager created
08-26 16:55:01.245  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
,08-26 16:55:01.248  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 16:55:01.248  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:01.249  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 16:55:01.249  7052  7052 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 16:55:01.249  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 16:55:01.249  6997  7517 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 16:55:01.250  6997  7517 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 16:55:01.250  6997  7517 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 16:55:01.251  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:01.251  7052  7052 I AppUp4:CustModeStarterReceiver: onReceive
08-26 16:55:01.251  6997  6997 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 16:55:01.253  6997  6997 V BluetoothMapService: BluetoothMapBinder()
08-26 16:55:01.254  6997  6997 D BluetoothMapService: Received start request. Starting profile...
08-26 16:55:01.254  6997  6997 D BluetoothMapService: start()
08-26 16:55:01.255  7052  7052 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@327310ba
08-26 16:55:01.255  7052  7052 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 16:55:01.255  7052  7052 D AppUp4:CustFacade: isPhone : true
08-26 16:55:01.256  7052  7052 D AppUp4:CustModeStarterReceiver: begin check event
08-26 16:55:01.256  7052  7052 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 16:55:01.256  6997  6997 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 16:55:01.256  6997  6997 D BluetoothMapEmailAppObserver: createReceiver()
08-26 16:55:01.258  6997  6997 D BluetoothMapEmailAppObserver: initObservers()
08-26 16:55:01.258  6997  6997 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 16:55:01.266  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:01.266  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 16:55:01.267  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
,08-26 16:55:01.267  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:55:01.270  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 16:55:01.270  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:55:01.273  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 16:55:01.275  4356  7542 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 16:55:01.276  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 16:55:01.276  6997  6997 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 16:55:01.277  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 16:55:01.281  4356  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:01.281  4356  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 16:55:01.281  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 16:55:01.284  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 16:55:01.285  6997  6997 V BluetoothMapService: Handler(): got msg=1
08-26 16:55:01.287  6997  7478 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 16:55:01.287  6997  7478 I bluedroid-qcom: enable
08-26 16:55:01.287  6997  7478 I bt_hci_bdroid: init
08-26 16:55:01.290  6997  7478 I bt_vendor: bt-vendor : init
08-26 16:55:01.290  6997  7478 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 16:55:01.290  6997  7478 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 16:55:01.290  6997  7478 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 16:55:01.290  6997  7478 D bt_userial_mct: userial_init
,08-26 16:55:01.291  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:01.291  6997  7544 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 16:55:01.291  6997  7544 I bt-btu  : btu_task pending for preload complete event
08-26 16:55:01.292  6997  6997 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 16:55:01.292  6997  6997 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 16:55:01.292  6997  6997 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 16:55:01.292  6997  6997 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:01.293  6997  6997 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 16:55:01.294  6997  7478 D bt_hci_bdroid: set_power 1
08-26 16:55:01.294  6997  7478 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 16:55:01.294  6997  7478 I bt_vendor: Starting hciattach daemon
08-26 16:55:01.295  6997  7478 I bt_vendor: try to set true
08-26 16:55:01.285  7551  7551 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:01.285  7551  7551 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:01.300  7094  7547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:01.304  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 16:55:01.304  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:01.304  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 16:55:01.307  6960  7548 W FormManager: Network not available. Please check & try again.
08-26 16:55:01.312  7143  7143 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 16:55:01.312  7143  7143 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 16:55:01.315  6960  7549 V FormManager: Network unavailable.
08-26 16:55:01.316  7553  7553 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 16:55:01.321  6960  7549 V FormManager: Network unavailable.
08-26 16:55:01.321  7202  7202 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:1
08-26 16:55:01.322  7202  7202 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-26 16:55:01.322  7202  7202 D Weather.Utils: 2 : All the weather widget is gone.
08-26 16:55:01.322  7202  7202 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 16:55:01.322  7202  7202 D WeatherAncestor: connectivity changed - connection : true
08-26 16:55:01.323  7202  7202 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6d1d6c8
08-26 16:55:01.323  7202  7202 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 16:55:01.323  7202  7202 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 16:55:01.323  7202  7202 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 16:55:01.323  7202  7202 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 16:55:01.323  7202  7202 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:1
08-26 16:55:01.365  7559  7559 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 16:55:01.374  7560  7560 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-26 16:55:01.393  7562  7562 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 16:55:01.404  7563  7563 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-26 16:55:01.414  7564  7564 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 16:55:01.424  7565  7565 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 16:55:01.462  7567  7567 I libmdmdetect: ESOC framework not supported
08-26 16:55:01.464  7567  7567 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 16:55:01.473  7567  7567 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 16:55:01.473  7567  7567 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 16:55:01.473  7567  7567 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 16:55:01.473  7567  7567 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 16:55:01.473  7567  7567 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 16:55:01.473  7567  7567 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 16:55:01.473  7567  7567 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 16:55:01.519  7567  7568 E QC-QMI  : qmi_client [7567] 14: failed to locate client data
08-26 16:55:01.520   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 16:55:01.520   478   478 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-26 16:55:01.579  7569  7569 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 16:55:01.597  7573  7573 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-26 16:55:01.647  6997  7478 I bt_vendor: bluetooth satus is on
,08-26 16:55:01.647  6997  7478 D bt_hci_bdroid: preload
08-26 16:55:01.647  6997  7550 D bt_userial_mct: userial_open(port:0)
08-26 16:55:01.647  6997  7550 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 16:55:01.651  6997  7550 I bt_vendor: Done intiailizing UART
08-26 16:55:01.652  6997  7550 I bt_vendor: Done intiailizing UART
08-26 16:55:01.652  6997  7550 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 16:55:01.652  6997  7550 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 16:55:01.652  6997  7544 I bt-btu  : btu_task received preload complete event
08-26 16:55:01.652  6997  7575 D bt_userial_mct: Entering userial_read_thread()
08-26 16:55:01.652  6997  7544 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 16:55:01.653  6997  7544 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 16:55:01.655  6997  7544 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 16:55:01.658  6997  7544 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 16:55:01.671  1031  1098 W ProcessCpuTracker: Skipping unknown process pid 7551
08-26 16:55:01.672  1031  1098 W ProcessCpuTracker: Skipping unknown process pid 7574
,08-26 16:55:01.759  6997  7544 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 16:55:01.759  6997  7544 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e5061 
08-26 16:55:01.759  6997  7544 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e5061 
,08-26 16:55:01.778  6997  7482 E bt-btif : Calling BTA_HhEnable
08-26 16:55:01.778  6997  7482 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 16:55:01.778  6997  7482 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 16:55:01.782  6997  7482 D BluetoothAdapterProperties: Name is: G3
08-26 16:55:01.783  6997  7482 D BluetoothAdapterProperties: Scan Mode:20
08-26 16:55:01.784  6997  7482 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 16:55:01.784  6997  7482 D bt_hci_bdroid: postload
08-26 16:55:01.785  6997  7482 D bte_conf: Device ID record 1 : primary
08-26 16:55:01.785  6997  7482 D bte_conf:   vendorId            = 00c4
08-26 16:55:01.785  6997  7482 D bte_conf:   vendorIdSource      = 0001
08-26 16:55:01.785  6997  7482 D bte_conf:   product             = 13a1
08-26 16:55:01.785  6997  7482 D bte_conf:   version             = 1000
08-26 16:55:01.785  6997  7482 D bte_conf:   clientExecutableURL = 
08-26 16:55:01.785  6997  7482 D bte_conf:   serviceDescription  = 
08-26 16:55:01.785  6997  7482 D bte_conf:   documentationURL    = 
08-26 16:55:01.786  6997  7550 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 16:55:01.786  6997  7482 D bte_conf: bte_load_did_conf no section named DID2.
08-26 16:55:01.788  6997  7550 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 16:55:01.775  7583  7583 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 16:55:01.797  6997  7575 E bt_mct  : hci lib postload completed
08-26 16:55:01.797  6997  7478 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 16:55:01.798  6997  7478 D BluetoothAdapterProperties: ScanMode =  20
08-26 16:55:01.798  6997  7478 D BluetoothAdapterProperties: State =  11
08-26 16:55:01.798  6997  7478 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 16:55:01.798  6997  7478 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 16:55:01.798  6997  7478 D BluetoothAdapterProperties: Setting state to 12
08-26 16:55:01.798  6997  7478 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 16:55:01.785  7583  7583 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:01.801  6997  7478 I BluetoothAdapterState: Entering On State
08-26 16:55:01.801  1031  1102 D BluetoothManagerService: Message: 60
08-26 16:55:01.808  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 16:55:01.808  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-26 16:55:01.813  6997  7482 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 16:55:01.823  6997  7478 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 16:55:01.823  6997  7478 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 16:55:01.823  6997  7478 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-26 16:55:01.827  6997  7478 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 16:55:01.827  6997  7544 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 16:55:01.828  6997  7544 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 16:55:01.828  6997  7544 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 16:55:01.829  6997  7544 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 16:55:01.829  6997  7544 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 16:55:01.829  6997  7544 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 16:55:01.830  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 16:55:01.830  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 16:55:01.853  6997  7478 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-26 16:55:01.866  6997  7544 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:01.866  6997  7544 W bt-smp  : Plain text(LSB ~ MSB) = 34 31 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:01.866  6997  7544 W bt-smp  : Encrypted text(LSB ~ MSB) = fc e4 fb f8 15 5d cb 76 f9 7c 9f 8d 8e cf 4b ed 
,08-26 16:55:01.870  6997  7544 W bt-btm  : Stopping oneshot timer
08-26 16:55:01.882  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:01.882  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:01.882  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:01.882  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:55:01.882  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:01.882  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:01.882  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:01.882  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 16:55:01.908  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:55:01.917  6997  7544 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:01.917  6997  7544 W bt-smp  : Plain text(LSB ~ MSB) = e9 44 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:01.917  6997  7544 W bt-smp  : Encrypted text(LSB ~ MSB) = 4d 47 3c d3 d5 5c f0 ac ab bd 23 e2 c1 e2 28 cb 
08-26 16:55:01.917  6997  7544 W bt-btm  : Stopping oneshot timer
08-26 16:55:01.926  6997  7482 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 16:55:01.926  6997  7482 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 16:55:01.927  6997  7482 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 16:55:01.938  6997  7544 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:01.938  6997  7544 W bt-smp  : Plain text(LSB ~ MSB) = d9 47 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:01.938  6997  7544 W bt-smp  : Encrypted text(LSB ~ MSB) = 48 21 f6 df 3a db 5e 4b f8 bb 75 7a 0d dd 23 a5 
08-26 16:55:01.939  6997  7544 W bt-btm  : Stopping oneshot timer
08-26 16:55:01.946  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:01.946  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:01.946  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:01.946  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:55:01.946  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:01.946  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:01.946  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:01.946  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 16:55:01.953  7588  7588 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 16:55:01.954  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:55:01.957  6853  7342 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 16:55:01.957  6997  7544 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:01.958  6997  7544 W bt-smp  : Plain text(LSB ~ MSB) = 0d 03 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:01.958  6997  7544 W bt-smp  : Encrypted text(LSB ~ MSB) = b5 9e 44 ab a8 39 d7 b2 06 ff 00 39 8c eb 15 62 
08-26 16:55:01.958  6997  7544 W bt-btm  : Stopping oneshot timer
08-26 16:55:01.961  7242  7256 W art     : Suspending all threads took: 6.483ms
,08-26 16:55:01.965  6853  6871 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 16:55:01.969  6853  6870 D BluetoothPan: onBluetoothStateChange on: true
08-26 16:55:01.969  6853  6870 D BluetoothPan: onBluetoothStateChange call bindService
08-26 16:55:01.969  6853  6853 D BluetoothInputDevice: Proxy object connected
08-26 16:55:01.969  6853  6853 D HidProfile: Bluetooth service connected
08-26 16:55:01.972  6853  7342 D BluetoothMap: onBluetoothStateChange: up=true
08-26 16:55:01.972  6853  6853 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 16:55:01.972  6853  6853 D PanProfile: Bluetooth service connected
08-26 16:55:01.973  6997  7544 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:01.973  6997  7544 W bt-smp  : Plain text(LSB ~ MSB) = 17 e3 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:01.973  6997  7544 W bt-smp  : Encrypted text(LSB ~ MSB) = 3e bb 4e 94 17 58 cd 00 ef 17 20 dd d2 c2 ab 09 
08-26 16:55:01.973  6997  7544 W bt-btm  : Stopping oneshot timer
08-26 16:55:01.974  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:01.976  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 16:55:01.977  1031  1031 D BluetoothHeadset: Proxy object connected
08-26 16:55:01.978  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 16:55:01.981  1031  1031 D BluetoothA2dp: Proxy object connected
08-26 16:55:01.981  1836  1836 D BluetoothHeadset: Proxy object connected
08-26 16:55:01.982  1836  4028 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:01.984  1836  1836 D BluetoothHeadset: Proxy object connected
08-26 16:55:01.984  6853  6853 D BluetoothMap: Proxy object connected
08-26 16:55:01.984  6853  6853 D MapProfile: Bluetooth service connected
08-26 16:55:01.984  6853  6853 D BluetoothMap: getConnectedDevices()
08-26 16:55:01.985  1836  4029 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:01.985  6997  7498 V BluetoothMapService: getConnectedDevices()
08-26 16:55:01.990  1836  1836 D BluetoothHeadset: Proxy object connected
08-26 16:55:01.991  1031  1102 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 16:55:01.991  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-26 16:55:01.995  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 16:55:01.997  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:01.998  1927  2090 D LGBluetoothAPIService: Message: 1
08-26 16:55:01.998  1927  2090 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 16:55:02.000  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 16:55:02.004  6679  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-26 16:55:02.008  1031  1102 D BluetoothManagerService: Message: 40
08-26 16:55:02.008  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 16:55:02.008  6853  6853 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 16:55:02.011  6997  6997 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:02.011  6997  6997 D BluetoothMapService: STATE_ON
08-26 16:55:02.012  6997  6997 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 16:55:02.013  6997  6997 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 16:55:02.014  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 16:55:02.015  1031  1102 D BluetoothManagerService: Message: 30
08-26 16:55:02.015  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:02.018  6853  6853 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 16:55:02.020  1927  2090 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 16:55:02.020  1927  2090 D LGBluetoothAPIService: Message: 100
08-26 16:55:02.020  1927  2090 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 16:55:02.021  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:02.025  1031  1102 D BluetoothManagerService: Message: 30
08-26 16:55:02.030  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:02.031  6997  6997 V BluetoothPbapService: Pbap Service onCreate
08-26 16:55:02.031  6997  6997 V BluetoothPbapService: Starting PBAP service
08-26 16:55:02.031  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-26 16:55:02.033  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 16:55:02.033  6997  6997 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 16:55:02.033  6997  6997 V BluetoothPbapService: Pbap Service onBind
08-26 16:55:02.038  6997  6997 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:02.039  6997  6997 V BluetoothPbapService: state: 12
08-26 16:55:02.039  6997  6997 V BluetoothMapService: Handler(): got msg=1
08-26 16:55:02.039  6997  6997 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 16:55:02.040  6997  6997 V BluetoothPbapService: Handler(): got msg=1
08-26 16:55:02.041  6853  6853 D BluetoothA2dp: Proxy object connected
08-26 16:55:02.041  6997  7606 D BluetoothMapMasInstance: MAS initSocket()
08-26 16:55:02.041  6997  7606 D BluetoothMapMasInstance:   masId = 00
08-26 16:55:02.041  6997  7606 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 16:55:02.041  6997  7606 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 16:55:02.041  6997  7606 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 16:55:02.041  6997  6997 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 16:55:02.042  6853  6853 D A2dpProfile: Bluetooth service connected
08-26 16:55:02.043  6997  6997 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 16:55:02.043  6997  6997 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:02.043  6853  6853 D BluetoothHeadset: Proxy object connected
08-26 16:55:02.043  6997  6997 V BluetoothPbapReceiver: ***********state = 12
08-26 16:55:02.044  6997  7607 V BluetoothPbapService: Pbap Service initSocket
,08-26 16:55:02.046  1031  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:02.046  1031  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:02.048  6853  6853 D HeadsetProfile: Bluetooth service connected
08-26 16:55:02.049  2115  2115 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 16:55:02.051  6997  7606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:02.051  6997  7607 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:02.052  6997  7606 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 16:55:02.053  6997  7606 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 16:55:02.053  6997  7606 D BluetoothMapMasInstance: Accepting socket connection...
08-26 16:55:02.053  6997  7482 D BluetoothAdapterProperties: Scan Mode:21
08-26 16:55:02.053  6997  7482 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 16:55:02.054  2115  2115 D c       : Getting all permits...
08-26 16:55:02.054  2115  2115 D a       : Opening database...
08-26 16:55:02.057  6997  7607 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 16:55:02.057  6997  7607 V BluetoothPbapService: Succeed to create listening socket 
08-26 16:55:02.057  6997  7607 V BluetoothPbapService: Accepting socket connection...
,08-26 16:55:02.058  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:02.059  6853  6853 D DockEventReceiver: finishStartingService: stopping service
08-26 16:55:02.060  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:02.060  6853  6853 D BluetoothPbap: Proxy object connected
08-26 16:55:02.061  6853  6853 D PbapServerProfile: Bluetooth service connected
08-26 16:55:02.062  7242  7281 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-26 16:55:02.064  2115  2115 D a       : Opening database auth.proximity.permit_store...
08-26 16:55:02.064  2115  2115 D a       : Closing database...
08-26 16:55:02.074  6853  6853 D BluetoothPermissionRequest: onReceive
,08-26 16:55:02.076  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 16:55:02.078  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 16:55:02.080  6997  6997 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 16:55:02.082  6997  6997 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 16:55:02.089  6997  6997 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 16:55:02.117  6997  6997 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 16:55:02.117  6997  6997 V BtOppService: onCreate
,08-26 16:55:02.122  6997  6997 V BluetoothOppNotification: send message
08-26 16:55:02.126  6997  6997 V BtOppService: Starting RfcommListener
08-26 16:55:02.136  6997  6997 D BluetoothOppPreference: Dumping Names:  
08-26 16:55:02.136  6997  6997 D BluetoothOppPreference: {}
,08-26 16:55:02.136  6997  6997 D BluetoothOppPreference: Dumping Channels:  
,08-26 16:55:02.136  6997  6997 D BluetoothOppPreference: {}
08-26 16:55:02.139  6997  6997 V BtOppService: onStartCommand
08-26 16:55:02.146  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:02.147  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 16:55:02.149  6997  7614 V BtOppService: Deleted complete outbound shares, number =  0
08-26 16:55:02.150  6997  7617 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-26 16:55:02.151  6997  7614 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 16:55:02.151  6997  7614 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 16:55:02.153  6997  7614 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b8157ed on behalf of 
08-26 16:55:02.153  6997  6997 V BluetoothOppNotification: new notify threadi!
08-26 16:55:02.154  6997  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 16:55:02.155  6997  6997 V BluetoothOppNotification: send delay message
08-26 16:55:02.156  6997  6997 V BtOppService: start RfcommListener
08-26 16:55:02.159  6997  7618 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 16:55:02.161  6997  7618 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d2ad622 on behalf of 
,08-26 16:55:02.162  6997  7618 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 16:55:02.164  6997  6997 V BtOppService: RfcommListener started
08-26 16:55:02.164  6997  6997 V BtOppService: ContentObserver received notification
08-26 16:55:02.165  6997  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38c7b8b3 on behalf of 
08-26 16:55:02.166  6997  7619 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 16:55:02.167  1031  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 16:55:02.168  6997  7619 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:02.168  6997  7619 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 16:55:02.169  6997  7619 V BtOppRfcommListener: Started RFCOMM listener....
08-26 16:55:02.169  6997  7619 I BtOppRfcommListener: Accept thread started.
08-26 16:55:02.169  6997  7619 V BtOppRfcommListener: Accepting connection...
08-26 16:55:02.170  6997  7617 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 16:55:02.170  6997  7617 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 16:55:02.172  6997  7617 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14c25e70 on behalf of 
08-26 16:55:02.174  6997  7617 V BluetoothOppNotification: update too frequent, put in queue
,08-26 16:55:02.176  6997  7617 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 16:55:02.176  6997  7618 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 16:55:02.179  6997  7618 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a2885e9 on behalf of 
08-26 16:55:02.179  6997  7618 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 16:55:02.181  6997  7618 V BluetoothOppNotification: outbound notification was removed.
08-26 16:55:02.181  6997  7618 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 16:55:02.182  6997  7618 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2744326e on behalf of 
08-26 16:55:02.183  6997  7618 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 16:55:02.184  6997  7618 V BluetoothOppNotification: inbound notification was removed.
08-26 16:55:02.185  6997  7618 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 16:55:02.185  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:02.186  6997  6997 V BluetoothFtpService: Ftp Service onCreate
08-26 16:55:02.186  6997  6997 I BluetoothFtpService: Ftp Service onCreate
,08-26 16:55:02.186  6997  6997 V BluetoothFtpService: Ftp Service onStartCommand
08-26 16:55:02.186  6997  6997 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:02.186  6997  6997 V BluetoothFtpService: Starting Listening on sockets
08-26 16:55:02.186  6997  6997 V BtOppService: ContentObserver received notification
08-26 16:55:02.187  6997  7618 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ac6f19c on behalf of 
08-26 16:55:02.187  6997  6997 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 16:55:02.187  6997  6997 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 16:55:02.187  6997  6997 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 16:55:02.187  6997  6997 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:02.187  6997  6997 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 16:55:02.187  6997  6997 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 16:55:02.188  6997  7620 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 16:55:02.188  6997  7620 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 16:55:02.190  6997  6997 V BluetoothFtpService: Handler(): got msg=1
08-26 16:55:02.192  6997  6997 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 16:55:02.192  6997  6997 V BluetoothFtpService: Ftp Service initSocket
08-26 16:55:02.198  1031  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 16:55:02.200  6997  6997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 16:55:02.201  6997  6997 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-26 16:55:02.201  6997  6997 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 16:55:02.206  6997  7621 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 16:55:02.217  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
,08-26 16:55:02.218  6997  6997 V BluetoothSapService: Sap Service onCreate
08-26 16:55:02.346  1031  2319 I art     : Explicit concurrent mark sweep GC freed 91714(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.361ms total 151.814ms
,08-26 16:55:02.349  6997  7620 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8478b2b on behalf of 
08-26 16:55:02.354  6997  6997 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:02.354  6997  6997 V BluetoothSapService: state: 12
08-26 16:55:02.355  6997  6997 V BluetoothSapService: Starting SAP server process
08-26 16:55:02.355  6997  7620 V BluetoothOppNotification: update too frequent, put in queue
08-26 16:55:02.356  6997  7620 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 16:55:02.359  6997  6997 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-26 16:55:02.345  7623  7623 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:02.345  7623  7623 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:02.362  6997  7624 V BluetoothSapService: Sap Service initRfcommSocket
08-26 16:55:02.363  1031  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:02.364  6997  7624 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:02.365  6997  7624 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 16:55:02.366  6997  7624 V BluetoothSapService: Succeed to create listening socket 
08-26 16:55:02.366  6997  7624 V BluetoothSapService: Accepting socket connection...
08-26 16:55:02.382  7623  7623 V BT_SAP  : Event pipe created
08-26 16:55:02.382  7623  7623 V BT_SAP  : create_server_socket qcom.sap.server
08-26 16:55:02.382  7623  7623 V BT_SAP  : created socket fd 6
,08-26 16:55:02.791  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:02.791  1031  1521 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 16:55:02.825  1031  1522 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 16:55:02.832  1031  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-26 16:55:03.022  1031  1980 I ActivityManager: Killing 7400:com.lge.bnr/1000 (adj 15): empty #17
,08-26 16:55:03.053  1031  1998 W libprocessgroup: failed to open /acct/uid_1000/pid_7400/cgroup.procs: No such file or directory
,08-26 16:55:03.158  6997  6997 V BluetoothOppNotification: new notify threadi!
,08-26 16:55:03.159  6997  6997 V BluetoothOppNotification: send delay message
,08-26 16:55:03.170  6997  7634 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 16:55:03.173  6997  7634 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a220921 on behalf of 
08-26 16:55:03.175  6997  7634 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-26 16:55:03.181  6997  7634 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-26 16:55:03.182  6997  7634 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fcc2146 on behalf of 
,08-26 16:55:03.183  6997  7634 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 16:55:03.184  6997  7634 V BluetoothOppNotification: outbound notification was removed.
08-26 16:55:03.185  6997  7634 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 16:55:03.186  6997  7634 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e31af07 on behalf of 
08-26 16:55:03.186  6997  7634 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 16:55:03.188  6997  7634 V BluetoothOppNotification: inbound notification was removed.
08-26 16:55:03.188  6997  7634 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 16:55:03.189  6997  7634 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24e5d834 on behalf of 
08-26 16:55:03.252  1031  1050 I ActivityManager: Killing 6872:com.lge.sync/1000 (adj 15): empty #17
,08-26 16:55:03.287  1031  1528 D WifiService: Client connection lost with reason: 4
,08-26 16:55:03.318  1031  1980 W libprocessgroup: failed to open /acct/uid_1000/pid_6872/cgroup.procs: No such file or directory
,08-26 16:55:03.769  1031  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 16:55:03.769  1031  1889 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1729318b mBinding = false
,08-26 16:55:03.799  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 16:55:03.799  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 16:55:03.799  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-26 16:55:03.803  1031  1102 D BluetoothManagerService: Message: 2
08-26 16:55:03.803  1031  1102 D BluetoothManagerService: Sending off request.
08-26 16:55:03.804  6997  7015 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 16:55:03.805  6997  7478 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 16:55:03.805  6997  7478 D BluetoothAdapterProperties: Setting state to 13
08-26 16:55:03.805  6997  7478 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 16:55:03.806  6997  7478 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 16:55:03.806  6997  7478 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 16:55:03.808  6997  7482 D BluetoothAdapterProperties: Scan Mode:20
08-26 16:55:03.809  6997  7478 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 16:55:03.811  6997  7606 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 16:55:03.811  6997  7606 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:55:03.811  6997  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 16:55:03.811  6997  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 16:55:03.811  6997  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 16:55:03.811  6997  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 16:55:03.811  6997  7606 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 16:55:03.811  6997  7606 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-26 16:55:03.814  6997  7607 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:55:03.816  6997  7619 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:55:03.816  6997  7621 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:55:03.817  6997  7624 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 16:55:03.817  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 16:55:03.817  6997  7544 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 16:55:03.819  6997  7478 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 16:55:03.824  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:55:03.824  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:55:03.824  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:55:03.824  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:55:03.824  6997  7544 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 16:55:03.824  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:55:03.824  6997  7544 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:55:03.824  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:55:03.824  6997  7544 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 16:55:03.831  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 16:55:03.831  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 16:55:03.831  6997  7544 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 16:55:03.836  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:55:03.836  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:03.836  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:03.836  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:03.836  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:55:03.836  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:55:03.836  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:03.836  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:03.836  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:55:03.837  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:55:03.837  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:55:03.845  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:55:03.845  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:03.845  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:03.845  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:03.845  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:55:03.845  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 16:55:03.845  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:03.845  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:03.845  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:55:03.848  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 16:55:03.848  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:55:03.849  1031  1102 D BluetoothManagerService: Message: 60
08-26 16:55:03.849  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 16:55:03.849  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-26 16:55:03.853  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:03.854  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 16:55:03.859  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:03.861  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:03.865  6997  6997 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:03.865  6997  6997 D BluetoothMapService: STATE_TURNING_OFF
08-26 16:55:03.865  6997  6997 V BluetoothMapService: Handler(): got msg=4
08-26 16:55:03.865  6997  6997 D BluetoothMapService: MAP Service closeService in
08-26 16:55:03.866  6997  6997 D BluetoothMapMasInstance: MAP Service shutdown
08-26 16:55:03.866  6997  6997 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 16:55:03.866  6997  6997 V BluetoothMapService: MAP Service closeService out
08-26 16:55:03.867  6997  6997 V BtOppService: Receiver DISABLED_ACTION 
08-26 16:55:03.867  6997  6997 I BtOppRfcommListener: stopping Accept Thread
08-26 16:55:03.867  6997  6997 V BtOppRfcommListener: close mBtServerSocket
08-26 16:55:03.868  6997  7619 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 16:55:03.868  6997  6997 V BtOppRfcommListener: waiting for thread to terminate
08-26 16:55:03.868  6997  6997 V BtOppRfcommListener: done waiting for thread to terminate
08-26 16:55:03.871  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-26 16:55:03.883  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 16:55:03.889  6997  6997 V BtOppService: onDestroy
,08-26 16:55:03.896  6997  6997 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 16:55:03.897  6997  6997 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 16:55:03.897  6997  6997 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:03.897  6997  6997 V BluetoothPbapReceiver: ***********state = 13
08-26 16:55:03.900  6997  6997 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 16:55:03.902  6997  6997 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:03.902  6997  6997 V BluetoothPbapService: state: 13
08-26 16:55:03.902  6997  6997 V BluetoothPbapService: Pbap Service closeService in
,08-26 16:55:03.907  2115  2115 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 16:55:03.908  6997  6997 V BluetoothPbapService: successfully stopped pbap service
08-26 16:55:03.908  6997  6997 V BluetoothPbapService: Pbap Service closeService out
,08-26 16:55:03.909  6997  6997 V BluetoothPbapService: Pbap Service onDestroy
,08-26 16:55:03.909  6997  6997 V BluetoothPbapService: Pbap Service closeService in
08-26 16:55:03.909  6997  6997 V BluetoothPbapService: Pbap Service closeService out
08-26 16:55:03.909  6997  6997 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-26 16:55:03.934  6853  6853 D DockEventReceiver: finishStartingService: stopping service
,08-26 16:55:03.942  6853  6853 D BluetoothPbap: Proxy object disconnected
08-26 16:55:03.943  6853  6853 D PbapServerProfile: Bluetooth service disconnected
08-26 16:55:03.950  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 16:55:03.959  6853  6853 D BluetoothPermissionRequest: onReceive
08-26 16:55:03.959  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 16:55:03.966  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 16:55:03.971  6997  6997 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 16:55:03.971  6997  6997 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 16:55:03.973  6997  6997 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 16:55:03.977  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:03.977  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 16:55:03.979  6997  6997 V BluetoothFtpService: Ftp Service onStartCommand
,08-26 16:55:03.979  6997  6997 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:03.979  6997  6997 V BluetoothFtpService: Ftp Service closeService
08-26 16:55:03.979  6997  6997 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 16:55:03.981  6997  6997 V BluetoothFtpService: successfully stopped ftp service
08-26 16:55:03.981  6997  6997 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 16:55:03.981  6997  6997 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 16:55:03.981  6997  6997 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 16:55:03.981  6997  6997 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:03.981  6997  6997 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 16:55:03.981  6997  6997 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 16:55:03.983  6997  6997 V BluetoothFtpService: Ftp Service onDestroy
08-26 16:55:03.983  6997  6997 V BluetoothFtpService: Ftp Service closeService
08-26 16:55:03.994  6997  6997 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:03.994  6997  6997 V BluetoothSapService: state: 13
08-26 16:55:03.994  6997  6997 V BluetoothSapService: Stopping SAP server process
,08-26 16:55:03.997  6997  6997 V BluetoothSapService: Sap Service closeSapService in
,08-26 16:55:03.998  6997  6997 V BluetoothSapService: Close listen Socket : 
,08-26 16:55:03.998  6997  6997 V BluetoothSapService: Close rfcomm Socket : 
,08-26 16:55:03.998  6997  6997 V BluetoothSapService: Close sapd  Socket : 
,08-26 16:55:03.999  6997  6997 V BluetoothSapService: Sap Service closeSapService out
08-26 16:55:04.000  6997  6997 V BluetoothSapService: Sap Service onDestroy
08-26 16:55:04.000  6997  6997 V BluetoothSapService: Sap Service closeSapService in
08-26 16:55:04.000  6997  6997 V BluetoothSapService: Close listen Socket : 
,08-26 16:55:04.000  6997  6997 V BluetoothSapService: Close rfcomm Socket : 
08-26 16:55:04.000  6997  6997 V BluetoothSapService: Close sapd  Socket : 
08-26 16:55:04.000  6997  6997 V BluetoothSapService: Sap Service closeSapService out
,08-26 16:55:04.727  6997  7482 D bt_hci_bdroid: cleanup
,08-26 16:55:04.740  6997  7550 I bt_lpm  : LPM is already off!!!
08-26 16:55:04.740  6997  7575 I bt_userial_mct: exiting userial_read_thread
08-26 16:55:04.740  6997  7575 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 16:55:04.740  6997  7544 W bt-btif : ag scb idx 1 not allocated
,08-26 16:55:04.740  6997  7544 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 16:55:04.740  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:55:04.740  6997  7544 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 16:55:04.740  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 16:55:04.741  6997  7544 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 16:55:04.741  6997  7544 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 16:55:04.743  6997  7482 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 16:55:04.744  6997  7550 I bt_vendor: hw_epilog_process
08-26 16:55:04.745  6997  7482 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 16:55:04.745  6997  7482 D bt_userial_mct: userial_close
08-26 16:55:04.745  6997  7482 E bt_userial_mct: pthread_join() FAILED result:3
08-26 16:55:04.745  6997  7482 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 16:55:04.756  6997  7482 D bt_hci_bdroid: set_power 0
08-26 16:55:04.756  6997  7482 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 16:55:04.756  6997  7482 I bt_vendor: bluetooth satus is on
08-26 16:55:04.756  6997  7482 I bt_vendor: bt-vendor : resetting BT status
08-26 16:55:04.756  6997  7482 I bt_vendor: Starting hciattach daemon
08-26 16:55:04.756  6997  7482 I bt_vendor: try to set false
,08-26 16:55:04.764  6997  7482 I bt_vendor: Starting hciattach daemon
08-26 16:55:04.764  6997  7482 I bt_vendor: try to set false
08-26 16:55:04.765  6997  7482 I bt_vendor: cleanup
08-26 16:55:04.766  6997  7544 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 16:55:04.766  6997  7482 I GKI_LINUX: GKI_exit_task 0 done
08-26 16:55:04.766  6997  7482 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 16:55:04.769  6997  7478 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 16:55:04.775  6997  6997 D HeadsetService: Received stop request...Stopping profile...
,08-26 16:55:04.779  6997  6997 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 16:55:04.779  6997  6997 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 16:55:04.779  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:04.780  6997  7517 D HeadsetStateMachine: Exit Disconnected: -1
08-26 16:55:04.783  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-26 16:55:04.783  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-26 16:55:04.783  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-26 16:55:04.785  1031  1031 D BluetoothHeadset: Proxy object disconnected
08-26 16:55:04.785  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 16:55:04.788  6997  7478 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-26 16:55:04.793  6997  6997 D A2dpService: Received stop request...Stopping profile...
08-26 16:55:04.793  6997  7534 D A2dpStateMachine: Exit Disconnected: -1
08-26 16:55:04.795  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 16:55:04.798  6997  6997 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 16:55:04.798  6997  6997 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 16:55:04.798  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:04.800  1031  1031 D BluetoothA2dp: Proxy object disconnected
08-26 16:55:04.800  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 16:55:04.802  6997  6997 D HidService: Received stop request...Stopping profile...
08-26 16:55:04.802  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:04.804  6997  6997 D HealthService: Received stop request...Stopping profile...
08-26 16:55:04.805  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:04.807  6997  6997 D HeadsetStateMachine: Unbinding service...
08-26 16:55:04.809  6997  6997 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 16:55:04.809  6997  6997 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 16:55:04.809  6997  6997 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 16:55:04.809  6997  6997 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 16:55:04.809  6997  6997 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 16:55:04.809  6997  6997 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 16:55:04.809  6997  6997 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 16:55:04.810  6997  6997 D PanService: Received stop request...Stopping profile...
08-26 16:55:04.811  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
,08-26 16:55:04.814  6997  6997 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 16:55:04.815  6997  6997 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 16:55:04.815  6997  6997 D BtGatt.GattService: stop()
08-26 16:55:04.816  6997  6997 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 16:55:04.817  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:04.818  6997  6997 D BluetoothMapService: Received stop request...Stopping profile...
08-26 16:55:04.818  6997  6997 D BluetoothMapService: stop()
08-26 16:55:04.818  6997  6997 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 16:55:04.819  6997  6997 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 16:55:04.820  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:04.822  6997  6997 I BluetoothA2dpServiceJni: cleanupNative
,08-26 16:55:04.826  6997  7535 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 16:55:04.827  6997  6997 I GKI_LINUX: GKI_exit_task 2 done
08-26 16:55:04.828  6997  6997 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 16:55:04.828  6997  6997 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 16:55:04.828  6997  6997 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 16:55:04.828  6997  6997 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 16:55:04.829  6997  6997 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 16:55:04.829  6997  6997 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 16:55:04.829  6997  6997 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 16:55:04.829  6997  6997 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 16:55:04.831  6997  6997 V BluetoothMapService: Handler(): got msg=4
08-26 16:55:04.831  6997  6997 D BluetoothMapService: MAP Service closeService in
08-26 16:55:04.831  6997  6997 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 16:55:04.831  6997  6997 V BluetoothMapService: MAP Service closeService out
08-26 16:55:04.833  6997  7478 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 16:55:04.833  6997  7478 D BluetoothAdapterProperties: Setting state to 10
08-26 16:55:04.833  6997  7478 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 16:55:04.834  6997  6997 D BluetoothMapService: cleanup()
08-26 16:55:04.834  6997  6997 D BluetoothMapService: MAP Service closeService in
08-26 16:55:04.834  6997  6997 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 16:55:04.834  6997  6997 V BluetoothMapService: MAP Service closeService out
,08-26 16:55:04.837  1031  1102 D BluetoothManagerService: Message: 60
08-26 16:55:04.837  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 16:55:04.837  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 16:55:04.838  6997  7478 I BluetoothAdapterState: Entering OffState
08-26 16:55:04.838  6853  6870 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 16:55:04.839  6853  6870 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 16:55:04.839  6853  6870 D BluetoothPan: onBluetoothStateChange on: false
08-26 16:55:04.840  6853  6870 D BluetoothMap: onBluetoothStateChange: up=false
08-26 16:55:04.840  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:55:04.841  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 16:55:04.841  6853  6870 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 16:55:04.842  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:55:04.842  1836  2414 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:55:04.843  6853  6870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:55:04.843  1836  4037 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 16:55:04.845  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 16:55:04.845  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-26 16:55:04.849  1031  1102 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 16:55:04.849  1031  1102 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 16:55:04.850  1031  1102 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1729318b mBinding = false
08-26 16:55:04.850  1031  1102 D BluetoothManagerService: Sending unbind request.
08-26 16:55:04.856  6997  7482 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 16:55:04.857  6997  6997 I GKI_LINUX: GKI_exit_task 1 done
08-26 16:55:04.857  6997  6997 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 16:55:04.857  6997  6997 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 16:55:04.857  6997  6997 I art     : --- WEIRD: removing null entry 248
08-26 16:55:04.857  6997  6997 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 16:55:04.858  6997  6997 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-26 16:55:04.860  6997  6997 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 16:55:04.862  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 16:55:04.864  6997  6997 I art     : System.exit called, status: 0
08-26 16:55:04.864  6997  6997 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 16:55:04.890  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 16:55:04.892  1927  2090 D LGBluetoothAPIService: Message: 2
,08-26 16:55:04.892  1927  2090 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@12dbbcfb mBinding = false
08-26 16:55:04.892  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 16:55:04.892  1927  2090 D LGBluetoothAPIService: Sending unbind request.
08-26 16:55:04.896   325  2188 V AudioFlinger: 6997 died, releasing its sessions
08-26 16:55:04.896   325  2188 V AudioFlinger:  pid 1836 @ 0
08-26 16:55:04.896   325  2188 V AudioFlinger:  pid 3439 @ 1
08-26 16:55:04.896   325  2188 V AudioFlinger:  pid 3439 @ 2
08-26 16:55:04.896  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 16:55:04.897  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:04.898  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:04.900  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 16:55:04.900  6853  6853 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 16:55:04.900  1031  1907 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
08-26 16:55:04.900  1031  1907 W ActivityManager: android.os.DeadObjectException
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-26 16:55:04.900  1031  1907 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 16:55:04.902  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 16:55:04.906  1587  1587 D BluetoothAdapter: 670587747: getState() :  mService = null. Returning STATE_OFF
08-26 16:55:04.906  1587  1587 D BluetoothAdapter: 670587747: getState() :  mService = null. Returning STATE_OFF
08-26 16:55:04.946  1031  2017 I ActivityManager: Process com.android.bluetooth (pid 6997) has died
08-26 16:55:04.946  1031  2017 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-26 16:55:05.020  1031  1961 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7683 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 16:55:05.022  6853  6853 D DockEventReceiver: finishStartingService: stopping service
,08-26 16:55:05.099  7683  7683 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 16:55:05.100  7683  7683 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 16:55:05.100  7683  7683 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-26 16:55:05.101  7683  7683 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 16:55:05.122  7683  7683 D BluetoothAdapterApp: Loading JNI Library
,08-26 16:55:05.159  7683  7683 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@135b81b0 Instance Count = 1
,08-26 16:55:05.166  7683  7683 D BluetoothAdapterApp: onCreate
08-26 16:55:05.196  7683  7683 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 16:55:05.197  7683  7683 D ProfileConfigQcom: Adding HeadsetService
08-26 16:55:05.197  7683  7683 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 16:55:05.197  7683  7683 D ProfileConfigQcom: Adding A2dpService
08-26 16:55:05.197  7683  7683 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 16:55:05.198  7683  7683 D ProfileConfigQcom: Adding HidService
08-26 16:55:05.198  7683  7683 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 16:55:05.198  7683  7683 D ProfileConfigQcom: Adding HealthService
08-26 16:55:05.198  7683  7683 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-26 16:55:05.200  7683  7683 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 16:55:05.202  7683  7683 D ProfileConfigQcom: Adding PanService
08-26 16:55:05.205  7683  7683 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 16:55:05.206  7683  7683 D ProfileConfigQcom: Adding GattService
08-26 16:55:05.207  7683  7683 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 16:55:05.207  7683  7683 D ProfileConfigQcom: Adding BluetoothMapService
08-26 16:55:05.208  7683  7683 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 16:55:05.210  7683  7683 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 16:55:05.213  7683  7683 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-26 16:55:05.213  7683  7683 V BluetoothPbapReceiver: ***********state = 10
,08-26 16:55:05.216  7683  7683 V LGMDMManagerInternal: Create singleton instance
,08-26 16:55:05.337  2115  2115 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 16:55:05.338  1031  1631 I ActivityManager: Killing 6755:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-26 16:55:05.346  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 16:55:05.360  6920  6920 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 16:55:05.360  6920  6920 W System.err: android.os.DeadObjectException
08-26 16:55:05.361  6920  6920 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 16:55:05.361  6920  6920 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 16:55:05.361  6920  6920 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 16:55:05.361  6920  6920 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 16:55:05.361  6920  6920 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 16:55:05.362  6920  6920 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 16:55:05.362  6920  6920 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 16:55:05.362  6920  6920 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 16:55:05.362  6920  6920 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 16:55:05.362  6920  6920 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 16:55:05.362  6920  6920 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-26 16:55:05.362  6920  6920 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-26 16:55:05.362  6920  6920 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 16:55:05.363  6920  6920 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 16:55:05.363  6920  6920 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 16:55:05.363  6920  6920 W System.err: android.os.DeadObjectException
08-26 16:55:05.365  6920  6920 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 16:55:05.365  6920  6920 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 16:55:05.365  6920  6920 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 16:55:05.366  6920  6920 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 16:55:05.366  6920  6920 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 16:55:05.366  6920  6920 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,08-26 16:55:05.366  6920  6920 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 16:55:05.366  6920  6920 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 16:55:05.366  6920  6920 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 16:55:05.366  6920  6920 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 16:55:05.367  6920  6920 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:55:05.367  6920  6920 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-26 16:55:05.367  6920  6920 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 16:55:05.367  6920  6920 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 16:55:05.367  6920  6920 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 16:55:05.368  6920  6920 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 16:55:05.447  1031  1926 W libprocessgroup: failed to open /acct/uid_1000/pid_6755/cgroup.procs: No such file or directory
08-26 16:55:05.448  1031  1926 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 16:55:05.462  6920  6920 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 16:55:05.463  6920  6920 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 16:55:05.527  1031  2017 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7709 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 16:55:05.528  6920  6920 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 16:55:05.542  6853  6853 D BluetoothPermissionRequest: onReceive
,08-26 16:55:05.547  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 16:55:05.547  6853  6853 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 16:55:05.550  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 16:55:05.555  7683  7683 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-26 16:55:05.562  7683  7683 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:05.567  7683  7683 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 16:55:05.567  7683  7683 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 16:55:05.568  7683  7683 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 16:55:05.569  7683  7683 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:05.569  7683  7683 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-26 16:55:05.574  6940  6940 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 16:55:05.616  7709  7709 D UEI.SmartControl: Quickset Services start...
08-26 16:55:05.618  7709  7709 I UEI.SmartControl: Manufacture = LGE
08-26 16:55:05.618  7709  7709 D UEI.SmartControl: Id = LGNevo
,08-26 16:55:05.619  7709  7709 D UEI.SmartControl: File observer start...
,08-26 16:55:05.620  7709  7709 E UEI.SmartControl: IR Port is disabled: false
08-26 16:55:05.620  7709  7709 D UEI.SmartControl: Starting file observer...
,08-26 16:55:05.621  7709  7709 D UEI.SmartControl: Extracting JNI libs...
08-26 16:55:05.621  7709  7709 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 16:55:05.726  7709  7709 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-26 16:55:05.726  7709  7709 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 16:55:05.726  7709  7709 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 16:55:05.769  7709  7709 I UEI.SmartControl: --- Selecting new region: 6
,08-26 16:55:05.772  7709  7709 I UEI.SmartControl: Model = LG-D855
,08-26 16:55:05.775  7709  7709 D UEI.SmartControl: QS Service created
08-26 16:55:05.793  7709  7709 I UEI.SmartControl: Service initServices...
,08-26 16:55:05.800  7709  7709 D UEI.SmartControl: QS start get config
,08-26 16:55:05.877  7709  7709 D UEI.SmartControl: Loading JNI Libs...
,08-26 16:55:06.291  7709  7709 I UEI.SmartControl: Supports setup maps: true
,08-26 16:55:06.300  7709  7709 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 16:55:06.300  7709  7709 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 16:55:06.300  7709  7709 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 16:55:06.300  7709  7709 I UEI.SmartControl: ### init IR Blaster...
08-26 16:55:06.307  7709  7709 D serial_port: Configuring serial port
08-26 16:55:06.312  7709  7709 E UEI.SmartControl: UEIBLaster setting for 616
08-26 16:55:06.312  7709  7709 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 16:55:06.313  7709  7709 I UEI.SmartControl: configuring settings for MAXQ616
08-26 16:55:06.313  7709  7709 I UEI.SmartControl: Get version...
,08-26 16:55:06.328  7709  7730 D UEI.SmartControl: serial port data available: 21
,08-26 16:55:06.360  7709  7709 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 16:55:06.360  7709  7709 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-26 16:55:06.361  7709  7709 I UEI.SmartControl: QS saving settings...
,08-26 16:55:06.363  7709  7709 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 16:55:06.393  7709  7730 D UEI.SmartControl: serial port data available: 4
,08-26 16:55:06.433  7709  7709 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 16:55:06.440  7709  7733 I UEI.SmartControl: Device manager: loading config....
08-26 16:55:06.440  7709  7733 D UEI.SmartControl: ----------- loading internal config...
08-26 16:55:06.447  7709  7709 E UEI.SmartControl: Services init done
08-26 16:55:06.447  7709  7709 D UEI.SmartControl: QS Service init finished
08-26 16:55:06.448  7709  7709 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 16:55:06.448  7709  7709 D UEI.SmartControl: QS Service version code: 201091
08-26 16:55:06.451  7709  7709 D UEI.SmartControl: Service requested: Control
,08-26 16:55:06.456  7709  7709 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 16:55:06.459  1031  2017 I ActivityManager: Killing 6920:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 16:55:06.462  7709  7733 E UEI.SmartControl: Loading SETTINGS...
08-26 16:55:06.469  7709  7733 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 16:55:06.485  7709  7732 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 16:55:06.488  7709  7732 D UEI.SmartControl: -----service ready thread exits
08-26 16:55:06.516  1031  1961 W libprocessgroup: failed to open /acct/uid_10112/pid_6920/cgroup.procs: No such file or directory
,08-26 16:55:06.521  7709  7709 D UEI.SmartControl: Internal service binding...
08-26 16:55:06.734  1031  1449 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 16:55:06.754  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 16:55:06.818  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 16:55:06.838  1031  1031 D administrator: Handling package changes for user 0
08-26 16:55:06.842  1031  1098 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7744 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-26 16:55:06.874  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 16:55:06.875  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-26 16:55:06.876  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:55:06.876  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 16:55:06.895  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 16:55:06.919  7744  7744 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 16:55:06.959  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-26 16:55:06.959  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 16:55:07.005  7744  7744 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 16:55:07.006  7744  7744 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 16:55:07.027  1031  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 16:55:07.033  1031  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-26 16:55:07.041  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 16:55:07.043  2478  2478 V GmsNetworkLocationProvi: DISABLE
,08-26 16:55:07.068  1031  1097 D LocationProviderProxy: applying state to connected service
,08-26 16:55:07.070  2478  2478 E GCoreFlp: Bound FusedProviderService with LocationManager
08-26 16:55:07.123  7744  7781 I Babel   : MmsConfig: mnc/mcc: 0/0
08-26 16:55:07.123  7744  7781 I Babel   : MmsConfig.loadMmsSettings
,08-26 16:55:07.125  7744  7781 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 16:55:07.125  7744  7781 I Babel   : MmsConfig.loadFromDatabase
,08-26 16:55:07.141  7744  7781 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 16:55:07.141  7744  7781 I Babel   : MmsConfig.loadFromResources
08-26 16:55:07.143  7744  7781 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 16:55:07.144  7744  7781 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-26 16:55:07.165  7744  7744 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:07.171  7744  7779 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 16:55:07.173  7744  7779 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 16:55:07.178  7744  7779 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 16:55:07.187  1800  7782 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 16:55:07.187  1800  7782 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-26 16:55:07.190  7052  7052 I AppUp4:CustModeStarterReceiver: onReceive
08-26 16:55:07.196  7052  7052 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@327310ba
08-26 16:55:07.196  7052  7052 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 16:55:07.196  7052  7052 D AppUp4:CustFacade: isPhone : true
08-26 16:55:07.196  7052  7052 D AppUp4:CustModeStarterReceiver: begin check event
08-26 16:55:07.196  7052  7052 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 16:55:07.201  1800  4813 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-26 16:55:07.203  7744  7779 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-26 16:55:07.207  7744  7779 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 16:55:07.208  7744  7779 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 16:55:07.232  7744  7779 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-26 16:55:07.235  7744  7779 W VideoCapabilities: Unsupported mime video/divx
,08-26 16:55:07.237  7744  7779 W VideoCapabilities: Unsupported mime video/divx311
08-26 16:55:07.239  7744  7779 W VideoCapabilities: Unsupported mime video/divx4
08-26 16:55:07.243  7744  7779 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-26 16:55:07.244  1031  2319 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7786 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-26 16:55:07.249  1031  2319 I ActivityManager: Killing 7094:com.lge.email/u0a23 (adj 15): empty #17
,08-26 16:55:07.272  7744  7779 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 16:55:07.276  7744  7779 W AudioCapabilities: Unsupported mime audio/eac3
,08-26 16:55:07.277  7744  7779 W AudioCapabilities: Unsupported mime audio/ac3
08-26 16:55:07.277  7744  7779 W AudioCapabilities: Unsupported mime audio/g726
08-26 16:55:07.278  7744  7779 W AudioCapabilities: Unsupported mime audio/wma-voice
08-26 16:55:07.279  7744  7779 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 16:55:07.280  7744  7779 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 16:55:07.281  7744  7779 W VideoCapabilities: Unsupported mime video/theora
08-26 16:55:07.282  7744  7779 W VideoCapabilities: Unsupported mime video/mjpg
08-26 16:55:07.326  1031  1962 W libprocessgroup: failed to open /acct/uid_10023/pid_7094/cgroup.procs: No such file or directory
,08-26 16:55:07.368  7786  7786 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 16:55:07.369  7786  7786 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 16:55:07.369  7786  7786 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 16:55:07.371  7786  7786 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 16:55:07.371  7786  7786 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 16:55:07.448  7786  7786 I SystemConfig: BUILD Country: EU
08-26 16:55:07.449  7786  7786 I SystemConfig: BUILD Operator: OPEN
,08-26 16:55:07.495  1031  1926 I ActivityManager: Killing 6960:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-26 16:55:07.598  7786  7804 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-26 16:55:07.599  7786  7804 I SystemConfig: existFile = false
08-26 16:55:07.599  7786  7804 I SystemConfig: canReadFile = false
08-26 16:55:07.599  7786  7804 I SystemConfig: systemFeature RCS result false
08-26 16:55:07.600  7786  7804 D SystemConfig: refreshRcsSupport() :false
,08-26 16:55:07.671  1031  1926 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7806 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 16:55:07.671  1031  1980 W libprocessgroup: failed to open /acct/uid_10026/pid_6960/cgroup.procs: No such file or directory
,08-26 16:55:07.748  7806  7806 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 16:55:07.748  7806  7806 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 16:55:07.749  7806  7806 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 16:55:07.749  7806  7806 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 16:55:07.843  1031  1529 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-26 16:55:07.854  7806  7806 I AppConfig: Total System Memory = 2995761152
08-26 16:55:07.864  7806  7806 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-26 16:55:07.986  1031  1962 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7828 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 16:55:07.991  1031  1962 I ActivityManager: Killing 6484:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-26 16:55:08.008   351   351 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 21.898ms
,08-26 16:55:08.031   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 21.646ms
,08-26 16:55:08.054   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 21.118ms
,08-26 16:55:08.057  1031  2017 W libprocessgroup: failed to open /acct/uid_1000/pid_6484/cgroup.procs: No such file or directory
,08-26 16:55:08.234  7828  7828 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 16:55:08.321  7828  7828 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:55:08.321  7828  7828 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 16:55:08.384  7828  7828 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 16:55:08.403  7828  7828 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 16:55:08.405  7828  7828 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 16:55:08.421  7828  7828 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 16:55:08.421  7828  7828 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-26 16:55:08.437  1031  1631 I ActivityManager: Killing 7143:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-26 16:55:08.469  1031  1889 W libprocessgroup: failed to open /acct/uid_10046/pid_7143/cgroup.procs: No such file or directory
,08-26 16:55:08.483  4628  7865 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-26 16:55:08.546  1031  1051 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7866 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-26 16:55:08.552  3480  3500 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-26 16:55:08.556  3480  3500 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@dc88c79 on behalf of 7828
08-26 16:55:08.598  7828  7828 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 16:55:08.613  7828  7828 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 16:55:08.645  7866  7866 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 16:55:08.676  7866  7866 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-26 16:55:08.676  7866  7866 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-26 16:55:08.676  7866  7866 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 16:55:08.676  7866  7866 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-26 16:55:08.676  7866  7866 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-26 16:55:08.676  7866  7866 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-26 16:55:08.702  1031  1907 I ActivityManager: Killing 7165:com.android.chrome/u0a57 (adj 15): empty #17
,08-26 16:55:08.738  1031  2319 W libprocessgroup: failed to open /acct/uid_10057/pid_7165/cgroup.procs: No such file or directory
,08-26 16:55:08.955  1031  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-26 16:55:08.998  4628  7865 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 515 ms] updated apps [took 515 ms] 
,08-26 16:55:09.883  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 16:55:09.883  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@132df93c added. We now have 6 listener(s)
,08-26 16:55:09.883  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 16:55:09.898  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:09.898  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ceb96c5 added. We now have 7 listener(s)
08-26 16:55:09.898  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:09.899  6679  6792 I System.out: IsBluetoothEnabled
08-26 16:55:09.900  1031  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:09.900  1031  1559 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-26 16:55:09.901  1031  1102 D BluetoothManagerService: Message: 2
08-26 16:55:09.904  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:09.907  1031  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:09.908  1031  1998 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-26 16:55:09.923  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 16:55:09.923  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 16:55:09.923  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-26 16:55:09.927  1031  1102 D BluetoothManagerService: Message: 1
08-26 16:55:09.927  1031  1102 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 16:55:09.958  1031  1102 D BluetoothManagerService: Message: 20
08-26 16:55:09.958  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@250ef2e7:true
,08-26 16:55:09.961  7683  7683 D BluetoothAdapterState: make
08-26 16:55:09.966  7683  7683 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 16:55:09.967  7683  7683 I bluedroid-qcom: init
08-26 16:55:09.968  7683  7905 I BluetoothAdapterState: Entering OffState
08-26 16:55:09.968  7683  7683 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 16:55:09.968  7683  7683 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 16:55:09.968  7683  7683 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 16:55:09.968  7683  7683 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 16:55:09.969  7683  7683 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 16:55:09.970  7683  7683 I bluedroid-qcom: get_profile_interface socket
08-26 16:55:09.970  7683  7683 I bluedroid-qcom: get_profile_interface map_client
,08-26 16:55:09.976  7683  7909 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 16:55:09.978  7683  7909 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 16:55:09.965  7908  7908 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:09.965  7908  7908 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:09.988  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 16:55:09.989  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
,08-26 16:55:09.994  7908  7908 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 16:55:09.995  7908  7908 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 16:55:09.995  7908  7908 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 16:55:09.996  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 16:55:09.996  1031  1102 D BluetoothManagerService: Message: 40
08-26 16:55:09.996  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 16:55:09.997  7683  7698 I bluedroid-qcom: config_hci_snoop_log
08-26 16:55:09.997  7908  7908 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 16:55:09.998  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 16:55:09.998  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 16:55:10.001  7683  7909 D BluetoothAdapterProperties: Name is: G3
,08-26 16:55:10.006  7908  7908 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 16:55:10.006  7908  7908 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 16:55:10.012  7683  7905 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 16:55:10.012  7683  7905 D BluetoothAdapterProperties: Setting state to 11
08-26 16:55:10.012  7683  7905 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 16:55:10.014  7683  7905 I LGBluetoothServiceJni: classInitNative: succeeds
,08-26 16:55:10.018  1031  1102 D BluetoothManagerService: Message: 60
08-26 16:55:10.018  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 16:55:10.018  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 16:55:10.022  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:10.023  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 16:55:10.026  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:10.028  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-26 16:55:10.043  7683  7683 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 16:55:10.043  7683  7683 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:10.043  7683  7683 V BluetoothPbapReceiver: ***********state = 11
,08-26 16:55:10.050  2115  2115 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 16:55:10.059  7683  7905 D BluetoothBondStateMachine: make
,08-26 16:55:10.063  7683  7926 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 16:55:10.063  7683  7905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:10.063  7683  7905 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 16:55:10.064  7683  7905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:10.064  7683  7905 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 16:55:10.064  7683  7905 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 16:55:10.067  6853  6853 D BluetoothPermissionRequest: onReceive
08-26 16:55:10.070  7683  7905 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 16:55:10.073  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 16:55:10.080  7683  7905 E BluetoothAdapterService: File transfer profiles supported!!
08-26 16:55:10.082  7683  7683 D HeadsetService: Received start request. Starting profile...
08-26 16:55:10.083  7683  7683 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 16:55:10.083  7683  7683 D LGBluetoothHfpAdapter: Version 1.6
,08-26 16:55:10.087  7683  7683 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 16:55:10.088  7683  7905 E BluetoothAdapterService: File transfer profiles supported!!
08-26 16:55:10.088  7683  7683 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 16:55:10.089  7683  7683 D HeadsetStateMachine: make
08-26 16:55:10.093  7683  7905 E BluetoothAdapterService: File transfer profiles supported!!
08-26 16:55:10.106  7683  7905 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 16:55:10.112  7683  7905 E BluetoothAdapterService: File transfer profiles supported!!
08-26 16:55:10.118  7683  7905 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 16:55:10.128  7683  7683 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:55:10.128  7683  7683 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 16:55:10.133  7683  7683 D HeadsetStateMachine: max_hf_connections = 1
08-26 16:55:10.133  7683  7683 I bluedroid-qcom: get_profile_interface handsfree
,08-26 16:55:10.136  7683  7683 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 16:55:10.137   325  1369 V AudioPolicyService: registerClient() client 0xb1427180, uid 1002
08-26 16:55:10.137   325  2188 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 16:55:10.137   325  2188 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 16:55:10.137   325  2188 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 16:55:10.137  7683  7683 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 16:55:10.138   325  1368 V AudioFlinger: registerClient() client 0xb55814d8, pid 7683
08-26 16:55:10.138   325  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-26 16:55:10.138   325  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:10.139  3439  3457 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:10.139  3439  3457 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:10.139   325  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:10.139   325  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 16:55:10.139  1587  2159 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:10.139  1587  2159 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:10.139  1587  2159 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:10.139  1587  2159 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-26 16:55:10.139  1031  1768 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:10.139  1031  1768 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:10.139  1836  2414 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:10.139  1836  2414 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 16:55:10.139  1031  1768 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:10.139  1836  2414 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:10.139  1031  1768 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 16:55:10.139  1836  2414 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 16:55:10.139  3439  3458 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 16:55:10.139  3439  3458 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 16:55:10.139  7683  7683 V ToneGenerator: Create Track: 0xb4928a80
08-26 16:55:10.139  7683  7683 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 16:55:10.139  7683  7683 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 16:55:10.141   325   325 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 16:55:10.141   325   325 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 16:55:10.141   325   325 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 16:55:10.141   325   325 V AudioPolicyManagerEx: getOutput() returns output 2
,08-26 16:55:10.141  7683  7683 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-26 16:55:10.141  7683  7698 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 16:55:10.141  7683  7698 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 16:55:10.141  7683  7698 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-26 16:55:10.141  7683  7698 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 16:55:10.141   325  2188 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 16:55:10.141   325  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 16:55:10.142   325  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 16:55:10.142   325  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 16:55:10.142   325  1368 V AudioPolicyManagerEx: getOutput() returns output 2
,08-26 16:55:10.142  7683  7683 V AudioSystem: getLatency() output 2, latency 50
08-26 16:55:10.142  7683  7683 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 16:55:10.142  7683  7683 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 16:55:10.142   325  2189 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 16:55:10.142   325  2189 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
,08-26 16:55:10.142   325  2189 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 16:55:10.142   325  2189 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 16:55:10.142   325  2189 V AudioFlinger: createTrack() lSessionId: 23
08-26 16:55:10.144  7683  7683 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 16:55:10.144  7683  7905 V LGMDMManager: Create singleton instance
08-26 16:55:10.144   325  2189 V AudioFlinger: acquiring 23 from 7683, for 7683
,08-26 16:55:10.144   325  2189 V AudioFlinger:  added new entry for 23
08-26 16:55:10.144  7683  7683 V ToneGenerator: ToneGenerator INIT OK, time: 138008
08-26 16:55:10.144  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:10.145  7683  7927 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 16:55:10.145  7683  7927 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 16:55:10.145  7683  7927 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-26 16:55:10.145  7683  7927 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 16:55:10.146   325   325 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7683
08-26 16:55:10.146   325   325 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 16:55:10.146   325   325 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 16:55:10.146   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
,08-26 16:55:10.146   325   325 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 16:55:10.146   325   325 V voice   : voice_set_parameters: exit with code(0)
08-26 16:55:10.146   325   325 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 16:55:10.146   325   325 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 16:55:10.146   325   325 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 16:55:10.146   325   325 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
,08-26 16:55:10.147   325   325 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 16:55:10.147   325   325 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 16:55:10.147  7683  7927 V ToneGenerator: ToneGenerator destructor
,08-26 16:55:10.147  7683  7927 V ToneGenerator: stopTone
08-26 16:55:10.147  7683  7927 V ToneGenerator: Delete Track: 0xb4928a80
08-26 16:55:10.148  7683  7905 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 16:55:10.148  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:10.149  7683  7927 V AudioTrack: ~AudioTrack, releasing session id from 7683 on behalf of 7683
08-26 16:55:10.152  7683  7683 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:10.152   325  2188 V AudioFlinger: releasing 23 from 7683 for 7683
08-26 16:55:10.152   325  2188 V AudioFlinger:  decremented refcount to 0
08-26 16:55:10.152   325  2188 V AudioFlinger: purging stale effects
08-26 16:55:10.152   325  2188 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 16:55:10.152   325  2188 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 16:55:10.153   325  1258 V AudioPolicyService: AudioCommandThread() waking up
08-26 16:55:10.153   325  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 16:55:10.153   325  1258 V AudioPolicyManager: releaseOutput() 2
08-26 16:55:10.153   325  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 16:55:10.153   325  2188 V AudioFlinger: PlaybackThread::Track destructor
08-26 16:55:10.153   325  2188 V AudioFlinger: removeClient_l() pid 7683, calling pid 325
08-26 16:55:10.154  7683  7683 D A2dpService: Received start request. Starting profile...
08-26 16:55:10.154  7683  7683 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 16:55:10.155  7683  7683 V Avrcp   : make
08-26 16:55:10.156  7683  7683 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 16:55:10.156  7683  7683 I bluedroid-qcom: get_profile_interface avrcp
08-26 16:55:10.165  7683  7683 V AudioManager: registerRemoteController: size of Media player list: 0
,08-26 16:55:10.168  7683  7683 E AudioManager: No RCC entry present to update
08-26 16:55:10.168  7683  7683 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 16:55:10.171  7683  7683 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 16:55:10.172  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 16:55:10.172  7683  7683 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 16:55:10.177  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-26 16:55:10.283  1031  1050 V SIM_STK : Menu title from STK is T-Mobile
08-26 16:55:10.283  1031  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-26 16:55:10.354  1031  1961 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 16:55:10.363  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 16:55:10.368  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 16:55:10.368  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 16:55:10.369  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 16:55:10.369  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 16:55:10.369  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 16:55:10.369  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 16:55:10.369  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 16:55:10.369  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 16:55:10.369  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 16:55:10.369  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 16:55:10.369  7683  7683 I BluetoothA2dpServiceJni: classInitNative
08-26 16:55:10.369  7683  7683 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 16:55:10.370  7683  7683 D A2dpStateMachine: make
08-26 16:55:10.374  7683  7683 I bluedroid-qcom: get_profile_interface a2dp
08-26 16:55:10.374  7683  7933 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 16:55:10.376  7683  7683 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 16:55:10.377  7683  7683 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 16:55:10.377  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:10.378  7683  7683 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 16:55:10.378  7683  7932 D A2dpStateMachine: Enter Disconnected: -2
08-26 16:55:10.379  7683  7683 D HidService: Received start request. Starting profile...
08-26 16:55:10.379  7683  7683 I bluedroid-qcom: get_profile_interface hidhost
08-26 16:55:10.379  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
,08-26 16:55:10.380  7683  7683 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 16:55:10.381  7683  7683 D HealthService: Received start request. Starting profile...
08-26 16:55:10.384  7683  7683 I bluedroid-qcom: get_profile_interface health
08-26 16:55:10.384  7683  7683 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 16:55:10.384  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:10.385  7683  7683 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 16:55:10.386  7683  7683 D PanService: Received start request. Starting profile...
08-26 16:55:10.386  7683  7683 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 16:55:10.386  7683  7683 I bluedroid-qcom: get_profile_interface pan
08-26 16:55:10.393  7683  7683 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 16:55:10.393  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
,08-26 16:55:10.396  7683  7683 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 16:55:10.400  7683  7683 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 16:55:10.400  7683  7683 D BtGatt.GattService: Received start request. Starting profile...
08-26 16:55:10.400  7683  7683 D BtGatt.GattService: start()
08-26 16:55:10.400  7683  7683 I bluedroid-qcom: get_profile_interface gatt
08-26 16:55:10.401  7683  7683 D BtGatt.AdvertiseManager: advertise manager created
08-26 16:55:10.414  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
,08-26 16:55:10.419  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:10.420  7683  7683 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 16:55:10.423  7683  7683 V BluetoothMapService: BluetoothMapBinder()
08-26 16:55:10.424  7683  7683 D BluetoothMapService: Received start request. Starting profile...
08-26 16:55:10.424  7683  7683 D BluetoothMapService: start()
08-26 16:55:10.429  7683  7683 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 16:55:10.429  7683  7683 D BluetoothMapEmailAppObserver: createReceiver()
,08-26 16:55:10.432  7683  7683 D BluetoothMapEmailAppObserver: initObservers()
08-26 16:55:10.433  7683  7683 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 16:55:10.454  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:10.454  7683  7683 D HeadsetStateMachine: Proxy object connected
,08-26 16:55:10.455  7683  7683 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 16:55:10.455  7683  7683 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 16:55:10.460  7683  7683 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 16:55:10.460  7683  7927 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 16:55:10.460  7683  7683 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 16:55:10.460  7683  7683 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 16:55:10.460  7683  7683 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 16:55:10.460  7683  7683 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:10.460  7683  7683 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 16:55:10.461  7683  7927 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 16:55:10.461  7683  7927 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 16:55:10.464  7683  7683 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 16:55:10.468  7683  7683 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 16:55:10.471  7683  7683 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 16:55:10.475  7683  7683 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 16:55:10.475  7683  7683 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 16:55:10.479  7683  7683 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 16:55:10.479  7683  7683 V BluetoothMapService: Handler(): got msg=1
08-26 16:55:10.480  7683  7905 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 16:55:10.480  7683  7905 I bluedroid-qcom: enable
,08-26 16:55:10.480  7683  7905 I bt_hci_bdroid: init
08-26 16:55:10.482  7683  7905 I bt_vendor: bt-vendor : init
08-26 16:55:10.482  7683  7905 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 16:55:10.482  7683  7905 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 16:55:10.482  7683  7905 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 16:55:10.482  7683  7905 D bt_userial_mct: userial_init
08-26 16:55:10.482  7683  7905 D bt_hci_bdroid: set_power 1
08-26 16:55:10.482  7683  7905 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 16:55:10.482  7683  7905 I bt_vendor: Starting hciattach daemon
08-26 16:55:10.482  7683  7905 I bt_vendor: try to set true
08-26 16:55:10.483  7683  7947 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 16:55:10.483  7683  7947 I bt-btu  : btu_task pending for preload complete event
08-26 16:55:10.475  7950  7950 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:10.475  7950  7950 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:10.511  7951  7951 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 16:55:10.610  7957  7957 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 16:55:10.623  7958  7958 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-26 16:55:10.648  7960  7960 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 16:55:10.659  7961  7961 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-26 16:55:10.671  7962  7962 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 16:55:10.684  7963  7963 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 16:55:10.708  7965  7965 I libmdmdetect: ESOC framework not supported
08-26 16:55:10.709  7965  7965 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 16:55:10.717  7965  7965 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-26 16:55:10.717  7965  7965 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 16:55:10.717  7965  7965 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 16:55:10.717  7965  7965 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 16:55:10.717  7965  7965 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 16:55:10.717  7965  7965 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 16:55:10.717  7965  7965 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 16:55:10.758  7965  7966 E QC-QMI  : qmi_client [7965] 15: failed to locate client data
08-26 16:55:10.759   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 16:55:10.759   478   478 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-26 16:55:10.800  7967  7967 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 16:55:10.814  7968  7968 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-26 16:55:10.838  7683  7905 I bt_vendor: bluetooth satus is on
08-26 16:55:10.838  7683  7905 D bt_hci_bdroid: preload
,08-26 16:55:10.838  7683  7949 D bt_userial_mct: userial_open(port:0)
08-26 16:55:10.838  7683  7949 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 16:55:10.842  7683  7949 I bt_vendor: Done intiailizing UART
,08-26 16:55:10.843  7683  7949 I bt_vendor: Done intiailizing UART
08-26 16:55:10.843  7683  7949 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 16:55:10.844  7683  7949 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 16:55:10.844  7683  7970 D bt_userial_mct: Entering userial_read_thread()
08-26 16:55:10.844  7683  7947 I bt-btu  : btu_task received preload complete event
08-26 16:55:10.844  7683  7947 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 16:55:10.844  7683  7947 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 16:55:10.847  7683  7947 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 16:55:10.851  7683  7947 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 16:55:10.939  7683  7947 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 16:55:10.939  7683  7947 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e5061 
08-26 16:55:10.939  7683  7947 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e5061 
,08-26 16:55:10.999  7683  7909 E bt-btif : Calling BTA_HhEnable
,08-26 16:55:11.000  7683  7909 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-26 16:55:11.000  7683  7909 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 16:55:11.011  7683  7947 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 16:55:11.011  7683  7947 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 16:55:11.011  7683  7947 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 16:55:11.012  7683  7947 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 16:55:11.012  7683  7947 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 16:55:11.017  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 16:55:11.021  7683  7909 D BluetoothAdapterProperties: Name is: G3
,08-26 16:55:11.027  7683  7909 D BluetoothAdapterProperties: Scan Mode:20
,08-26 16:55:11.027  7683  7909 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 16:55:11.028  7683  7909 D bt_hci_bdroid: postload
08-26 16:55:11.028  7683  7949 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 16:55:11.030  7683  7947 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 16:55:11.033  7683  7909 D bte_conf: Device ID record 1 : primary
08-26 16:55:11.033  7683  7909 D bte_conf:   vendorId            = 00c4
08-26 16:55:11.033  7683  7909 D bte_conf:   vendorIdSource      = 0001
08-26 16:55:11.033  7683  7909 D bte_conf:   product             = 13a1
08-26 16:55:11.033  7683  7909 D bte_conf:   version             = 1000
08-26 16:55:11.033  7683  7909 D bte_conf:   clientExecutableURL = 
08-26 16:55:11.033  7683  7909 D bte_conf:   serviceDescription  = 
08-26 16:55:11.033  7683  7909 D bte_conf:   documentationURL    = 
08-26 16:55:11.033  7683  7909 D bte_conf: bte_load_did_conf no section named DID2.
08-26 16:55:11.037  7683  7947 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:11.037  7683  7947 W bt-smp  : Plain text(LSB ~ MSB) = 26 fd 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:11.037  7683  7947 W bt-smp  : Encrypted text(LSB ~ MSB) = 38 d5 00 77 40 20 06 e2 2d 21 ac af 88 d2 a8 8d 
,08-26 16:55:11.040  7683  7949 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 16:55:11.040  7683  7947 W bt-btm  : Stopping oneshot timer
08-26 16:55:11.041  7683  7949 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 16:55:11.043  7683  7949 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 16:55:11.045  7683  7905 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 16:55:11.045  7683  7905 D BluetoothAdapterProperties: ScanMode =  20
08-26 16:55:11.047  7683  7905 D BluetoothAdapterProperties: State =  11
08-26 16:55:11.047  7683  7905 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 16:55:11.047  7683  7905 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 16:55:11.047  7683  7905 D BluetoothAdapterProperties: Setting state to 12
08-26 16:55:11.047  7683  7905 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 16:55:11.048  7683  7909 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 16:55:11.048  7683  7909 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 16:55:11.035  7975  7975 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 16:55:11.035  7975  7975 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:11.061  1031  1102 D BluetoothManagerService: Message: 60
08-26 16:55:11.061  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 16:55:11.061  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 16:55:11.066  7683  7905 I BluetoothAdapterState: Entering On State
,08-26 16:55:11.069  7683  7970 E bt_mct  : hci lib postload completed
08-26 16:55:11.082  7683  7947 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:11.082  7683  7947 W bt-smp  : Plain text(LSB ~ MSB) = ff 38 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:11.082  7683  7947 W bt-smp  : Encrypted text(LSB ~ MSB) = d4 2f d6 7e 02 36 d7 25 f9 89 a3 b4 a2 35 16 a1 
,08-26 16:55:11.085  7683  7947 W bt-btm  : Stopping oneshot timer
08-26 16:55:11.093  7683  7905 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 16:55:11.093  7683  7905 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 16:55:11.094  7683  7905 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-26 16:55:11.098  7683  7947 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:11.098  7683  7947 W bt-smp  : Plain text(LSB ~ MSB) = d9 62 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:11.098  7683  7947 W bt-smp  : Encrypted text(LSB ~ MSB) = 3c 57 d4 9c 48 e9 6f 17 09 b5 d5 20 61 6c ad f6 
08-26 16:55:11.099  7683  7947 W bt-btm  : Stopping oneshot timer
08-26 16:55:11.099  7683  7909 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 16:55:11.099  7683  7909 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 16:55:11.100  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 16:55:11.104  7683  7905 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 16:55:11.116  7683  7905 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-26 16:55:11.122  7683  7947 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:11.122  7683  7947 W bt-smp  : Plain text(LSB ~ MSB) = d4 31 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:11.122  7683  7947 W bt-smp  : Encrypted text(LSB ~ MSB) = 6e 4d 62 14 ec fa 39 b9 96 44 34 d3 f3 11 9c 23 
08-26 16:55:11.123  7683  7947 W bt-btm  : Stopping oneshot timer
08-26 16:55:11.123  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:11.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:11.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:11.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:55:11.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:11.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:11.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:11.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:55:11.133  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 16:55:11.136  7683  7947 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 16:55:11.136  7683  7947 W bt-smp  : Plain text(LSB ~ MSB) = 96 1c 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 16:55:11.136  7683  7947 W bt-smp  : Encrypted text(LSB ~ MSB) = 70 83 71 d8 64 99 f7 01 d9 e1 06 a3 f9 74 58 9e 
08-26 16:55:11.137  7683  7947 W bt-btm  : Stopping oneshot timer
08-26 16:55:11.142  6853  6870 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 16:55:11.162  6853  7342 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 16:55:11.171  6853  6871 D BluetoothPan: onBluetoothStateChange on: true
,08-26 16:55:11.171  6853  6871 D BluetoothPan: onBluetoothStateChange call bindService
08-26 16:55:11.173  6853  6853 D BluetoothInputDevice: Proxy object connected
08-26 16:55:11.173  6853  6853 D HidProfile: Bluetooth service connected
08-26 16:55:11.180  6853  7342 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 16:55:11.184  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 16:55:11.185  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 16:55:11.186  6853  6870 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 16:55:11.187  1031  1031 D BluetoothHeadset: Proxy object connected
08-26 16:55:11.187  7992  7992 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 16:55:11.189  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:11.191  1031  1031 D BluetoothA2dp: Proxy object connected
08-26 16:55:11.191  1836  1836 D BluetoothHeadset: Proxy object connected
08-26 16:55:11.191  1836  4029 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:11.193  1836  1836 D BluetoothHeadset: Proxy object connected
08-26 16:55:11.194  6853  7342 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 16:55:11.196  1836  2414 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 16:55:11.198  1836  1836 D BluetoothHeadset: Proxy object connected
08-26 16:55:11.198  1031  1102 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 16:55:11.199  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 16:55:11.200  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:11.200  1927  2090 D LGBluetoothAPIService: Message: 1
08-26 16:55:11.200  1927  2090 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 16:55:11.201  6853  6853 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 16:55:11.201  6853  6853 D PanProfile: Bluetooth service connected
08-26 16:55:11.203  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 16:55:11.206  1927  2090 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 16:55:11.207  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:11.212  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 16:55:11.212  1031  1102 D BluetoothManagerService: Message: 40
08-26 16:55:11.212  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 16:55:11.314  1031  1998 I art     : Explicit concurrent mark sweep GC freed 26825(1337KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.156ms total 106.290ms
,08-26 16:55:11.314  7683  7683 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:11.315  7683  7683 D BluetoothMapService: STATE_ON
08-26 16:55:11.316  7683  7683 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 16:55:11.316  7683  7683 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 16:55:11.317  7683  7683 V BluetoothMapService: Handler(): got msg=1
08-26 16:55:11.317  7683  7683 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-26 16:55:11.320  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 16:55:11.320  1927  2090 D LGBluetoothAPIService: Message: 100
08-26 16:55:11.320  1927  2090 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 16:55:11.323  6853  6853 D BluetoothMap: Proxy object connected
,08-26 16:55:11.323  6853  6853 D MapProfile: Bluetooth service connected
08-26 16:55:11.323  6853  6853 D BluetoothMap: getConnectedDevices()
08-26 16:55:11.325  7683  7698 V BluetoothMapService: getConnectedDevices()
08-26 16:55:11.326  7683  7999 D BluetoothMapMasInstance: MAS initSocket()
08-26 16:55:11.326  7683  7999 D BluetoothMapMasInstance:   masId = 00
08-26 16:55:11.326  7683  7999 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 16:55:11.326  7683  7999 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 16:55:11.326  7683  7999 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 16:55:11.327  6853  6853 D BluetoothA2dp: Proxy object connected
,08-26 16:55:11.327  6853  6853 D A2dpProfile: Bluetooth service connected
08-26 16:55:11.327  1031  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:11.330  7683  7999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:11.330  6853  6853 D BluetoothHeadset: Proxy object connected
08-26 16:55:11.330  6853  6853 D HeadsetProfile: Bluetooth service connected
,08-26 16:55:11.335  7683  7999 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 16:55:11.335  7683  7999 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 16:55:11.335  7683  7999 D BluetoothMapMasInstance: Accepting socket connection...
08-26 16:55:11.337  7683  7909 D BluetoothAdapterProperties: Scan Mode:21
08-26 16:55:11.337  7683  7909 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 16:55:11.338  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:11.339  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 16:55:11.340  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 16:55:11.343  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:11.343  7683  7683 V BluetoothPbapService: Pbap Service onCreate
08-26 16:55:11.343  7683  7683 V BluetoothPbapService: Starting PBAP service
08-26 16:55:11.344  7683  7683 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 16:55:11.344  7683  7683 V BluetoothPbapService: Pbap Service onBind
08-26 16:55:11.346  7683  7683 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:11.346  7683  7683 V BluetoothPbapService: state: 12
,08-26 16:55:11.346  7683  7683 V BluetoothPbapService: Handler(): got msg=1
08-26 16:55:11.346  7683  7683 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 16:55:11.347  7683  7683 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 16:55:11.347  7683  7683 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:11.347  7683  7683 V BluetoothPbapReceiver: ***********state = 12
08-26 16:55:11.348  7683  8001 V BluetoothPbapService: Pbap Service initSocket
08-26 16:55:11.348  1031  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:11.349  6853  6853 D DockEventReceiver: finishStartingService: stopping service
08-26 16:55:11.349  6853  6853 D BluetoothPbap: Proxy object connected
08-26 16:55:11.349  6853  6853 D PbapServerProfile: Bluetooth service connected
08-26 16:55:11.352  2115  2115 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 16:55:11.352  2115  2115 D c       : Getting all permits...
08-26 16:55:11.352  2115  2115 D a       : Opening database...
08-26 16:55:11.353  7683  8001 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:11.354  7683  8001 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 16:55:11.354  7683  8001 V BluetoothPbapService: Succeed to create listening socket 
08-26 16:55:11.354  7683  8001 V BluetoothPbapService: Accepting socket connection...
08-26 16:55:11.355  2115  2115 D a       : Opening database auth.proximity.permit_store...
08-26 16:55:11.355  2115  2115 D a       : Closing database...
08-26 16:55:11.364  6853  6853 D BluetoothPermissionRequest: onReceive
,08-26 16:55:11.365  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 16:55:11.366  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 16:55:11.368  7683  7683 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 16:55:11.369  7683  7683 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 16:55:11.374  7683  7683 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-26 16:55:11.392  7683  7683 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 16:55:11.392  7683  7683 V BtOppService: onCreate
,08-26 16:55:11.397  7683  7683 V BluetoothOppNotification: send message
,08-26 16:55:11.400  7683  7683 V BtOppService: Starting RfcommListener
08-26 16:55:11.406  7683  7683 D BluetoothOppPreference: Dumping Names:  
08-26 16:55:11.406  7683  7683 D BluetoothOppPreference: {}
,08-26 16:55:11.406  7683  7683 D BluetoothOppPreference: Dumping Channels:  
,08-26 16:55:11.406  7683  7683 D BluetoothOppPreference: {}
08-26 16:55:11.410  7683  7683 V BtOppService: onStartCommand
08-26 16:55:11.412  7683  8009 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 16:55:11.414  7683  7683 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:11.414  7683  7683 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 16:55:11.418  7683  8009 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 16:55:11.419  7683  8006 V BtOppService: Deleted complete outbound shares, number =  0
,08-26 16:55:11.422  7683  7683 V BluetoothOppNotification: new notify threadi!
08-26 16:55:11.423  7683  7683 V BluetoothOppNotification: send delay message
08-26 16:55:11.424  7683  7683 V BtOppService: start RfcommListener
08-26 16:55:11.424  7683  8006 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 16:55:11.425  7683  8006 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 16:55:11.425  7683  8009 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b8157ed on behalf of 
08-26 16:55:11.426  7683  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d2ad622 on behalf of 
08-26 16:55:11.429  7683  7683 V BtOppService: RfcommListener started
08-26 16:55:11.431  7709  7734 D UEI.SmartControl: Internal timer expired: 1
08-26 16:55:11.431  7709  7734 D UEI.SmartControl: unbind internal service
08-26 16:55:11.433  7683  8011 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 16:55:11.434  7683  8010 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 16:55:11.434  1031  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 16:55:11.436  7709  7709 D UEI.SmartControl: Service.onUnbind: IControl
08-26 16:55:11.437  7709  7709 D UEI.SmartControl: Service.onDestroy
08-26 16:55:11.437  7683  8009 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 16:55:11.437  7709  7709 D UEI.SmartControl: Lock is in USE false
08-26 16:55:11.437  7683  8009 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 16:55:11.437  7709  7709 D UEI.SmartControl: unbind internal service
08-26 16:55:11.438  7709  7709 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@15b17e86
08-26 16:55:11.438  7683  8009 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38c7b8b3 on behalf of 
08-26 16:55:11.438  7683  8011 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:11.439  7709  7709 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-26 16:55:11.439  7709  7709 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 16:55:11.439  7709  7709 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 16:55:11.440  7709  7709 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-26 16:55:11.440  7709  7709 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 16:55:11.440  7709  7709 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-26 16:55:11.440  7709  7709 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-26 16:55:11.440  7709  7709 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 16:55:11.440  7709  7709 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:11.440  7709  7709 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 16:55:11.440  7709  7709 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 16:55:11.440  7709  7709 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:55:11.440  7709  7709 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 16:55:11.440  7709  7709 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 16:55:11.440  7709  7709 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 16:55:11.440  7709  7709 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@15b17e86
08-26 16:55:11.440  7683  8009 V BluetoothOppNotification: update too frequent, put in queue
08-26 16:55:11.440  7683  8011 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 16:55:11.441  7683  8011 V BtOppRfcommListener: Started RFCOMM listener....
08-26 16:55:11.441  7683  8011 I BtOppRfcommListener: Accept thread started.
08-26 16:55:11.441  7683  8011 V BtOppRfcommListener: Accepting connection...
08-26 16:55:11.442  7683  8009 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 16:55:11.442  7683  8010 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14c25e70 on behalf of 
08-26 16:55:11.443  7709  7709 D serial_port: close(fd = 25)
08-26 16:55:11.443  7683  8010 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 16:55:11.446  7683  8010 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 16:55:11.447  7709  7709 I UEI.SmartControl: Serial port is closed.
08-26 16:55:11.448  7709  7709 I UEI.SmartControl: Serial port is closed.
08-26 16:55:11.448  7709  7709 D UEI.SmartControl: Blaster closed
08-26 16:55:11.448  76,83  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:11.448  7683  7683 V BluetoothFtpService: Ftp Service onCreate
08-26 16:55:11.448  7683  7683 I BluetoothFtpService: Ftp Service onCreate
08-26 16:55:11.449  7709  7709 D UEI.SmartControl: Shut down QS...
08-26 16:55:11.449  7683  7683 V BluetoothFtpService: Ftp Service onStartCommand
08-26 16:55:11.449  7709  7709 D UEI.SmartControl: Stopping QS lib
08-26 16:55:11.449  7683  7683 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:11.449  7683  7683 V BluetoothFtpService: Starting Listening on sockets
08-26 16:55:11.449  7709  7709 D UEI.SmartControl: QS lib stop result = true
08-26 16:55:11.449  7683  7683 V BtOppService: ContentObserver received notification
08-26 16:55:11.450  7709  7709 D UEI.SmartControl: Stopped QS lib
08-26 16:55:11.450  7683  7683 V BtOppService: ContentObserver received notification
08-26 16:55:11.450  7683  7683 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 16:55:11.450  7683  7683 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 16:55:11.450  7683  7683 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 16:55:11.450  7683  7683 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:11.450  7683  7683 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 16:55:11.450  7683  7683 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 16:55:11.451  7683  8012 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 16:55:11.451  7683  8012 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 16:55:11.453  7709  7709 D UEI.SmartControl: Stopped file observer...
08-26 16:55:11.454  7709  7709 D UEI.SmartControl: QS shutdown complete
08-26 16:55:11.456  7683  7683 V BluetoothFtpService: Handler(): got msg=1
08-26 16:55:11.458  7683  7683 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 16:55:11.458  7683  7683 V BluetoothFtpService: Ftp Service initSocket
08-26 16:55:11.459  7683  8012 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2744326e on behalf of 
08-26 16:55:11.459  7683  8010 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e7b2d0f on behalf of 
08-26 16:55:11.461  7683  8010 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 16:55:11.462  7683  8012 V BluetoothOppNotification: update too frequent, put in queue
08-26 16:55:11.463  7683  8012 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 16:55:11.463  1031  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:11.463  7683  8010 V BluetoothOppNotification: outbound notification was removed.
08-26 16:55:11.463  7683  8010 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 16:55:11.464  7683  7683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:11.465  7683  8010 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ac6f19c on behalf of 
08-26 16:55:11.466  7683  7683 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-26 16:55:11.466  7683  7683 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 16:55:11.468  7683  8010 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 16:55:11.470  7683  8010 V BluetoothOppNotification: inbound notification was removed.
08-26 16:55:11.471  7683  8010 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 16:55:11.471  7683  8013 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 16:55:11.472  7683  8010 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1efa97a5 on behalf of 
08-26 16:55:11.485  7683  7683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d1d6c8
08-26 16:55:11.485  7683  7683 V BluetoothSapService: Sap Service onCreate
,08-26 16:55:11.489  7683  7683 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 16:55:11.489  7683  7683 V BluetoothSapService: state: 12
08-26 16:55:11.489  7683  7683 V BluetoothSapService: Starting SAP server process
08-26 16:55:11.475  8014  8014 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:11.475  8014  8014 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:11.493  7683  7683 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 16:55:11.494  7683  8015 V BluetoothSapService: Sap Service initRfcommSocket
08-26 16:55:11.495  1031  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:11.496  7683  8015 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 16:55:11.497  7683  8015 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-26 16:55:11.497  7683  8015 V BluetoothSapService: Succeed to create listening socket 
08-26 16:55:11.497  7683  8015 V BluetoothSapService: Accepting socket connection...
08-26 16:55:11.511  8014  8014 V BT_SAP  : Event pipe created
08-26 16:55:11.511  8014  8014 V BT_SAP  : create_server_socket qcom.sap.server
08-26 16:55:11.511  8014  8014 V BT_SAP  : created socket fd 6
,08-26 16:55:11.971  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:11.971  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:11.971  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:11.971  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 16:55:11.971  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:11.971  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:11.971  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:11.971  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 16:55:11.975  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:55:11.977  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:11.977  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@99d681a added. We now have 8 listener(s)
08-26 16:55:11.977  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:11.979  1031  1870 D WifiServiceImplEx: setWifiEnabled: false pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 16:55:11.979  1031  1870 D WifiService: setWifiEnabled: false pid=6679, uid=10118
08-26 16:55:11.979  1031  1870 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 16:55:11.990  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:11.994  1031  2017 D WifiServiceImplEx: setWifiEnabled: true pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 16:55:11.994  1031  2017 D WifiService: setWifiEnabled: true pid=6679, uid=10118
08-26 16:55:11.994  1031  2017 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 16:55:12.011  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 16:55:12.011  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 16:55:12.011  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,08-26 16:55:12.016  1031  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 16:55:12.016  1031  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 16:55:12.018  1031  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 16:55:12.018  1031  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 16:55:12.018  1031  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 16:55:12.018  1031  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 16:55:12.018  1031  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 16:55:12.018  1031  1522 E WifiHW  : unknown target_country: EU , set to default
08-26 16:55:12.019  1031  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 16:55:12.019  1031  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 16:55:12.019  1031  1522 I WifiUtil: gEnableBmps=1
08-26 16:55:12.425  7683  7683 V BluetoothOppNotification: new notify threadi!
08-26 16:55:12.425  7683  7683 V BluetoothOppNotification: send delay message
,08-26 16:55:12.440  7683  8042 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 16:55:12.449  7683  8042 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a220921 on behalf of 
08-26 16:55:12.450  7683  8042 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 16:55:12.452  7683  8042 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 16:55:12.453  7683  8042 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fcc2146 on behalf of 
08-26 16:55:12.453  7683  8042 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-26 16:55:12.458  7683  8042 V BluetoothOppNotification: outbound notification was removed.
,08-26 16:55:12.458  7683  8042 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 16:55:12.459  7683  8042 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e31af07 on behalf of 
08-26 16:55:12.460  7683  8042 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 16:55:12.462  7683  8042 V BluetoothOppNotification: inbound notification was removed.
08-26 16:55:12.462  7683  8042 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 16:55:12.463  7683  8042 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24e5d834 on behalf of 
08-26 16:55:12.646   321   890 D SoftapController: Softap fwReload - Ok
,08-26 16:55:12.652  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 16:55:12.652  1031  1102 D Tethering: InitialState.processMessage what=4
,08-26 16:55:12.669  1031  1522 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (647ms)
08-26 16:55:12.673  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 16:55:12.692   321   890 D CommandListener: Setting iface cfg
08-26 16:55:12.692   321   890 D CommandListener: Trying to bring down wlan0
08-26 16:55:12.693   321   890 D CommandListener: Clearing all IP addresses on wlan0
08-26 16:55:12.697  1031  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-26 16:55:12.695  8045  8045 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:12.715  1031  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 16:55:12.715  1031  1522 E WifiStateMachine: useWiFiOffloading() : false
08-26 16:55:12.715  1031  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 16:55:12.718  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:55:12.705  8045  8045 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:12.729  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 16:55:12.750  1031  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 16:55:12.750  1031  1522 D WifiMonitor: connecting to supplicant
,08-26 16:55:12.757  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-26 16:55:12.785  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:12.786  8045  8045 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 16:55:12.826  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 16:55:12.826  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 16:55:12.827  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 16:55:12.827  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 16:55:12.827  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-26 16:55:12.828  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 16:55:12.828  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 16:55:12.828  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 16:55:12.828  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 16:55:12.828  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 16:55:12.828  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 16:55:12.831  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 16:55:12.831  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 16:55:12.831  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 16:55:12.831  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 16:55:12.832  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 16:55:12.832  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 16:55:12.832  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 16:55:12.832  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-26 16:55:12.833  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 16:55:12.833  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 16:55:12.834  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 16:55:12.842  8045  8045 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 16:55:12.842  8045  8045 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 16:55:12.882  1031  1631 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8063 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 16:55:12.923  8045  8045 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 16:55:12.977  8045  8045 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 16:55:12.982  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 16:55:12.983  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 16:55:12.983  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 16:55:12.984  1031  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 16:55:12.984  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:55:12.985  1031  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:55:12.986  1031  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:55:12.986  1031  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:55:12.987  8045  8045 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 16:55:12.987  1031  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 16:55:12.987  1031  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 16:55:12.987  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 16:55:12.987  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 16:55:12.987  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 16:55:12.987  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 16:55:12.987  1031  8085 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 16:55:12.987  1031  8085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 16:55:12.987  1031  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 16:55:12.988  1031  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 16:55:12.988  1031  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 16:55:13.005  1031  1631 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8086 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 16:55:13.013  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 16:55:13.013  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.013  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.013  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.013  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 16:55:13.013  1031  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 16:55:13.013  1031  1522 E WifiStateMachine: useWiFiOffloading() : false
08-26 16:55:13.013  1031  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 16:55:13.015  8063  8083 W FormManager: Network not available. Please check & try again.
08-26 16:55:13.017  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.017  1927  1927 D WfdService: Waiting for WifiP2p enabling
08-26 16:55:13.018  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 16:55:13.019  1031  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-26 16:55:13.020  1031  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 16:55:13.021  1031  1522 D WifiNative-wlan0: SET update_config 1: returned true
08-26 16:55:13.021  1031  1522 D WifiConfigStore: Loading config and enabling all networks 
08-26 16:55:13.021  1031  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 16:55:13.022  1031  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 16:55:13.023  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:13.023  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:13.023  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:13.023  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:13.023  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:13.023  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:13.023  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:13.023  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:55:13.025  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:55:13.031  1031  1522 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-26 16:55:13.034  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 16:55:13.034  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:13.034  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:13.034  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:13.034  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:13.034  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 16:55:13.034  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 16:55:13.034  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 16:55:13.038  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 16:55:13.039  8063  8084 V FormManager: Network unavailable.
08-26 16:55:13.041  8063  8084 V FormManager: Network unavailable.
08-26 16:55:13.043  1031  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-26 16:55:13.043  1031  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 16:55:13.044  6679  6792 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 16:55:13.044  1031  1522 D WifiStateMachine: enableVerboseLogging : level 2
08-26 16:55:13.044  1031  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 16:55:13.045  1031  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 16:55:13.045  1031  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 16:55:13.045  6679  6792 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 16:55:13.045  1031  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 16:55:13.045  1031  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 16:55:13.046  1031  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 16:55:13.046  1031  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 16:55:13.046  1031  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 16:55:13.046  1031  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 16:55:13.047  1031  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 16:55:13.047  1031  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 16:55:13.047  1031  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 16:55:13.047  1031  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 16:55:13.048  6679  6792 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@19f4610c Bundle[{}]
08-26 16:55:13.048  1031  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 16:55:13.048  6679  6792 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 16:55:13.049  6679  6792 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 16:55:13.049  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-26 16:55:13.049  1927  2231 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 16:55:13.049  1927  2231 D WfdsService: Set the WFDS Monitor: true
08-26 16:55:13.049  1927  2231 D WfdsMonitor: WfdsMonitorThread create
08-26 16:55:13.050  1031  1522 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 16:55:13.050  1031  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 16:55:13.050  1927  2231 D WfdsMonitor: WFDS Monitor is created and started
08-26 16:55:13.050  1927  2231 D WfdsService: WiFi: Supplicant connection re-established
08-26 16:55:13.050  6679  6792 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 16:55:13.050  7744  7744 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.050  1031  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 16:55:13.050  1031  1522 D WifiNative-HAL: Setting external_sim to 1
08-26 16:55:13.050  1031  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 16:55:13.051  1031  1522 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 16:55:13.051  1031  1522 I WifiNative-HAL: startHal
08-26 16:55:13.051  6679  6792 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 16:55:13.051  1031  1522 D wifi    : setting scan oui 0xaf73a320
08-26 16:55:13.051  1031  1522 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 16:55:13.051  1031  1522 I WifiNative-HAL: startHal
08-26 16:55:13.051  1031  1522 D wifi    : setting scan oui 0xaf73a320
08-26 16:55:13.052  6679  6792 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 16:55:13.052  1031  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 16:55:13.052  1031  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 16:55:13.052  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 16:55:13.052  6679  6792 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 16:55:13.052  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTC,OEXSCAN-STOP
08-26 16:55:13.053  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 16:55:13.053  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 16:55:13.053  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 16:55:13.053  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 16:55:13.054  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 16:55:13.054  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 16:55:13.054  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 16:55:13.054  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 16:55:13.054  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 16:55:13.055  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 16:55:13.055  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 16:55:13.055  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 16:55:13.055  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 16:55:13.055  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 16:55:13.055  8045  8045 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 16:55:13.056  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 16:55:13.056  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 16:55:13.056  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-26 16:55:13.057  1031  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 16:55:13.058  1927  8104 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 16:55:13.058  1031  1522 E WifiNative: : [140,908,358 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 16:55:13.058  1031  1522 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 16:55:13.058  1031  1522 D WifiNative-wlan0: RECONNECT: returned true
08-26 16:55:13.058  1031  1522 D WifiNative-wlan0: doString: [STATUS]
08-26 16:55:13.059  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 16:55:13.059  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 16:55:13.059  1031  1522 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 16:55:13.059  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 16:55:13.060  1031  1522 D WifiNative-wlan0: SET ps 1: returned true
08-26 16:55:13.060  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.061  1927  8104 E CtrlSupplicant: Succeed to open control connection
08-26 16:55:13.061   321   890 D CommandListener: Setting iface cfg
08-26 16:55:13.061  1927  8104 E CtrlSupplicant: Succeed to open monitor connection
08-26 16:55:13.061   321   890 D CommandListener: Trying to bring up p2p0
08-26 16:55:13.062  1031  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 16:55:13.062  1031  1521 D LGWifiP2pService: P2pEnablingState
08-26 16:55:13.062  1031  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.062  1031  1521 D LGWifiP2pService: P2p socket connection successful
08-26 16:55:13.062  1031  1521 D LGWifiP2pService: P2pEnabledState
08-26 16:55:13.063  1031  1521 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 16:55:13.063  1927  8104 D WfdsMonitor: Supplicant connection established
08-26 16:55:13.063  1927  2231 D WfdsService: Connected to the supplicant for wfds
08-26 16:55:13.065  6679  6792 I System.out: Running OutgoingSocketThread
08-26 16:55:13.067  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-26 16:55:13.067  1927  1927 D WfdsService: WifiP2pState is changed : true
08-26 16:55:13.068  1927  2231 D WfdsService: Receive the WFDS_ENABLE Method
08-26 16:55:13.068  1927  2231 D WfdsService: Set the WFDS Monitor: true
08-26 16:55:13.068  1927  2231 D WfdsService: Connected to the supplicant for wfds
08-26 16:55:13.068  1927  2231 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 16:55:13.068  8045  8045 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 16:55:13.068  1927  2231 D WfdsService: selectPreferredScanChannel [36]
08-26 16:55:13.068  1927  2231 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 16:55:13.068  6679  8105 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
08-26 16:55:13.069  1031  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 16:55:13.070  6679  8105 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39223
08-26 16:55:13.070  6679  8105 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-26 16:55:13.070  1031  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 16:55:13.070  1031  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 16:55:13.070  1031  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 16:55:13.070  1031  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 16:55:13.071  1031  1521 D WifiNative-p2p0: SET device_name G3: returned true
08-26 16:55:13.071  1031  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 16:55:13.071  1031  1521 D LGWifiP2pService: before postfix = G3
08-26 16:55:13.071  1031  1521 D WifiServerServiceExt: postfix byte check : 2
08-26 16:55:13.071  1031  1521 D LGWifiP2pService: after postfix = G3
08-26 16:55:13.071  1031  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 16:55:13.071  1031  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 16:55:13.071  1031  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 16:55:13.072  1031  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 16:55:13.072  1031  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 16:55:13.072  1031  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 16:55:13.072  1031  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 16:55:13.072  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=140923  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 16:55:13.073  1031  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 16:55:13.073  1031  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 16:55:13.073  1031  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 16:55:13.073  1031  1521 D WifiNative-HAL: p2pGetDeviceAddress
08-26 16:55:13.073  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 16:55:13.073  1031  1031 D RttService: SCAN_AVAILABLE : 3
08-26 16:55:13.074  1031  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 16:55:13.074  1031  1541 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.074  1031  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.074  1031  1540 I WifiNative-HAL: startHal
08-26 16:55:13.074  1031  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf73a320
08-26 16:55:13.074  1031  1540 D wifi    : failed to get capabilities : -3
08-26 16:55:13.074  1031  1540 E WifiScanningService: could not get scan capabilities
08-26 16:55:13.074  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 16:55:13.075  1927  1927 D WfdsService: isConnected: false
08-26 16:55:13.076  1031  1521 D LGWifiP2pSe,rvice: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 16:55:13.076  1031  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 16:55:13.077  1031  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 16:55:13.077  1031  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 16:55:13.077  1031  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 16:55:13.077  1031  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 16:55:13.077  1031  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 16:55:13.077  1031  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 16:55:13.079  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:13.079  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:55:13.080  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.080  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.080  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 16:55:13.080  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=140931  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 16:55:13.081  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.081  1031  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 16:55:13.081  1031  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 16:55:13.082  1031  1522 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 16:55:13.082  1031  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 16:55:13.082  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 16:55:13.082  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 16:55:13.082  1927  1927 D WfdsService: Update P2p Interface State: 3
,08-26 16:55:13.087  8045  8045 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-26 16:55:13.087  1031  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 16:55:13.087  1031  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 16:55:13.087  1031  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 16:55:13.088  1031  1521 D LGWifiP2pService: InactiveState
08-26 16:55:13.088  1031  1521 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.088  1031  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 16:55:13.088  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.088  1031  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 16:55:13.088  1031  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 16:55:13.088  1031  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 16:55:13.088  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 16:55:13.089  8045  8045 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:55:13.089  1031  8085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 16:55:13.089  1031  8085 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:55:13.089  1031  8085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:55:13.089  1031  8085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:55:13.089  1927  8104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 16:55:13.089  8045  8045 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 16:55:13.089  8045  8045 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 16:55:13.090  8045  8045 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.090  1031  8085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:55:13.090  1031  8085 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.090  1031  8085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.090  1031  8085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.090  8045  8045 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.090  1031  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 16:55:13.090  1031  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.090  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.090  1031  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 16:55:13.090  1031  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.091  1031  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.091  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.091  1031  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 16:55:13.091  1031  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.091  1927  8104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:55:13.091  1927  8104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WO,RLD]
08-26 16:55:13.091  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.091  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.091  1031  8085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:55:13.091  1031  8085 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.091  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.091  1031  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 16:55:13.091  1031  8085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.091  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 16:55:13.091  1031  8085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.091  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.091  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.091  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.092  1031  1031 E WifiServerServiceExt: No p2p device connected
08-26 16:55:13.092  1927  2231 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 16:55:13.092  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 16:55:13.093  8045  8045 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:55:13.093  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 16:55:13.093  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:55:13.093  1031  8085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:55:13.093  1031  8085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 16:55:13.093  8045  8045 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 16:55:13.094  8045  8045 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.094  1031  8085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:55:13.094  1031  8085 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.094  1031  8085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.094  1031  8085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.094  1031  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 16:55:13.094  8045  8045 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 16:55:13.094  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.094  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.095  1031  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 16:55:13.095  1927  8104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:55:13.095  1927  8104 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:55:13.095  1031  8085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 16:55:13.095  1031  8085 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.095  1031  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 16:55:13.095  1031  8085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 16:55:13.095  1031  8085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 16:55:13.097  1031  1522 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 16:55:13.097  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 16:55:13.097  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 16:55:13.097  8045  8045 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 16:55:13.098  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 16:55:13.098  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 16:55:13.098  1031  8085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 16:55:13.098  1031  8085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 16:55:13.098  1031  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 16:55:13.098  1031  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 16:55:13.098  1031  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 16:55:13.098  1031  1522 D WifiNative-wlan0: doBoolean: SCAN
08-26 16:55:13.099  1031  1522 D WifiNative-wlan0: SCAN: returned false
08-26 16:55:13.099  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=140950  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 16:55:13.100  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=140951  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 16:55:13.100  1031  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 16:55:13.100  1031  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 16:55:13.101  1031  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 16:55:13.101  1031  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 16:55:13.101  1031  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 16:55:13.103  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:13.103  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.103  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:55:13.103  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.103  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 16:55:13.104  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:55:13.104  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 16:55:13.104  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.105  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:55:13.105  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 16:55:13.110  8086  8086 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 16:55:13.118  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 16:55:13.122  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 16:55:13.125  1031  1889 I ActivityManager: Killing 7183:com.lge.drmservice/u0a62 (adj 15): empty #17
08-26 16:55:13.168  1031  2319 W libprocessgroup: failed to open /acct/uid_10062/pid_7183/cgroup.procs: No such file or directory
,08-26 16:55:13.191  8086  8086 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 16:55:13.197  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 16:55:13.206  8063  8109 W FormManager: Network not available. Please check & try again.
,08-26 16:55:13.212  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:13.227  8063  8110 V FormManager: Network unavailable.
,08-26 16:55:13.236  8063  8110 V FormManager: Network unavailable.
08-26 16:55:13.241  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 16:55:13.242  4356  4356 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 16:55:13.247  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 16:55:13.258  4356  4356 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 16:55:13.269  4356  8111 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 16:55:13.274  4356  8112 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 16:55:13.274  4356  8112 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 16:55:13.334  1031  1980 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8113 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 16:55:13.484  8113  8113 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 16:55:13.485  8113  8113 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 16:55:13.498  8113  8113 V [BNRBootReceiver]: Boot Receiver Return
,08-26 16:55:13.502  8113  8113 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 16:55:13.558  1031  1559 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8134 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 16:55:13.561  1031  1559 I ActivityManager: Killing 7202:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 16:55:13.628  1031  2319 W libprocessgroup: failed to open /acct/uid_10085/pid_7202/cgroup.procs: No such file or directory
,08-26 16:55:13.650  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 16:55:13.650  1031  8085 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-26 16:55:13.650  8045  8045 E wpa_supplicant: USIM:  scard_init function
,08-26 16:55:13.651  8045  8045 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 16:55:13.655  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 16:55:13.655  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-26 16:55:13.655  1031  8085 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 16:55:13.655  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 16:55:13.655  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 16:55:13.656  1031  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-26 16:55:13.657  1031  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-26 16:55:13.657  1031  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-26 16:55:13.658  1031  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-26 16:55:13.658  1031  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 16:55:13.662  8134  8134 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 16:55:13.673  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=141524  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 16:55:13.677  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:13.677  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:55:13.678  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=141529  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 16:55:13.678  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.679  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.680  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.680  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 16:55:13.680  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:55:13.680  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 16:55:13.696  8134  8134 D PluginManager: init()
,08-26 16:55:13.798  8045  8045 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 16:55:13.804  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,08-26 16:55:13.804  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-26 16:55:13.805  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 16:55:13.805  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 16:55:13.806  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:55:13.806  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:55:13.806  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=141656  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-26 16:55:13.806  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=141657  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 16:55:13.807  1031  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141658
08-26 16:55:13.807  1031  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141658
08-26 16:55:13.808  1031  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141659
08-26 16:55:13.808  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141659
,08-26 16:55:13.809  1031  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=141660
08-26 16:55:13.809  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=141660  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 16:55:13.813  1031  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 16:55:13.816  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.816  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.816  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 16:55:13.817  8045  8045 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 16:55:13.817  8045  8045 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 16:55:13.821  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.821  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:13.821  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.821  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:55:13.821  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-26 16:55:13.822  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:55:13.822  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:55:13.823  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 16:55:13.823  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 16:55:13.824  1031  8085 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 16:55:13.824  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 16:55:13.824  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 16:55:13.824  1031  8085 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 16:55:13.826  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:55:13.826  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:55:13.827  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=141666  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 16:55:13.827  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.829  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:55:13.829  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 16:55:13.830  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:13.830  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:55:13.830  1031  1522 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:55:13.831  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.831  1031  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:55:13.831  1031  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:55:13.832  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:55:13.832  1031  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 16:55:13.833  1031  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=141684  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 16:55:13.834  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=141685  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 16:55:13.834  1031  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=141685
08-26 16:55:13.835  1031  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=141686
,08-26 16:55:13.836  1031  1522 D WifiNative-wlan0: doString: [STATUS]
08-26 16:55:13.836  1031  8085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 16:55:13.837  1031  8085 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 16:55:13.837  1031  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 16:55:13.839  1031  1522 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 16:55:13.844  1031  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 16:55:13.844  1031  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 16:55:13.847  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.847  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.847  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 16:55:13.848  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 16:55:13.848  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:55:13.849  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.852  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.852  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.853  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 16:55:13.858  1031  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 16:55:13.858  1031  1529 D ConnectivityService: Got NetworkAgent Messenger
08-26 16:55:13.858  1031  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 16:55:13.858  1031  1529 D ConnectivityService: NetworkAgent connected
08-26 16:55:13.859  1031  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 16:55:13.859  1031  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 16:55:13.859  1031  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 16:55:13.859  1031  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 16:55:13.864  1031  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 16:55:13.865  1031  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 16:55:13.865  1031  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-26 16:55:13.865  1031  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 16:55:13.865  1031  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 16:55:13.871  1031  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 16:55:13.871  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:13.871  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:55:13.872  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.874   321   890 D CommandListener: Setting iface cfg
08-26 16:55:13.876  1031  1522 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 16:55:13.876  1031  8152 D DhcpStateMachine: StoppedState
08-26 16:55:13.876  1031  8152 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.877  1031  8152 D DhcpStateMachine: WaitBeforeStartState
,08-26 16:55:13.877  1031  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=141728  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:55:13.877  1031  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=141728  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:55:13.878  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=141729  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:55:13.879  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:55:13.879  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 16:55:13.880  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:55:13.880  1031  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=141731  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:55:13.880  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 16:55:13.880  1031  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=141731  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:55:13.881  1031  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=141732  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 16:55:13.883  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14521] from screen [on:0 period:-950468645] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 16:55:13.884  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-950468644] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 16:55:13.884  1031  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 16:55:13.888  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 16:55:13.888  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.889  1031  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.890  1031  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 16:55:13.891  1031  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.892  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.892  1031  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.893  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=138,0,0
08-26 16:55:13.893  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=138,0,0
08-26 16:55:13.893  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 16:55:13.893  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.894  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 16:55:13.894  1031  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 16:55:13.894  1031  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 16:55:13.894  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 16:55:13.895  1031  1522 D WifiNative-wlan0: SET ps 0: returned true
08-26 16:55:13.895  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 16:55:13.895  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 16:55:13.895  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 16:55:13.896  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32ca708b target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.896  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32ca708b target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.896  1031  8152 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.896  1031  8152 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 16:55:13.897  1031  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 16:55:13.897  1031  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 16:55:13.897  1031  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 16:55:13.898   321   890 D CommandListener: Setting iface cfg
08-26 16:55:13.898   321   890 D CommandListener: Trying to bring up wlan0
08-26 16:55:13.899  1031  1522 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 16:55:13.900  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:55:13.900  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-26 16:55:13.903  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 16:55:13.903  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.903  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 16:55:13.903  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.903  1031  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.904  1031  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.905  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.905  1031  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 16:55:13.906  1031  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 16:55:13.906  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 16:55:13.907  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 16:55:13.907  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.907  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.907  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 16:55:13.907  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 16:55:13.908  1031  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 16:55:13.908  1031  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 16:55:13.908  8045  8045 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 16:55:13.908  1031  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 16:55:13.908  1031  1522 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 16:55:13.925  1031  1522 D WifiNative-wlan0: SET ps 1: returned true
08-26 16:55:13.926  1031  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 16:55:13.926  1031  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 16:55:13.927  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 16:55:13.927  1031  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 16:55:13.927  1031  1529 D ConnectivityService: ignoring duplicate network state non-change
,08-26 16:55:13.934  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 16:55:13.934  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:55:13.934  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.934  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.934  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 16:55:13.935  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.936  1031  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 16:55:13.937  1031  1529 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 16:55:13.950  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.953  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.953  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 16:55:13.956  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:13.956  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 16:55:13.957  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 16:55:13.958  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.959  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 16:55:13.961  1031  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 16:55:13.961  1031  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 16:55:13.962  1031  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 16:55:13.963  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:13.963   321   890 E Netd    : netlink response contains error (File exists)
08-26 16:55:13.963  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,08-26 16:55:13.963  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.963  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.963  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 16:55:13.963  1031  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 16:55:13.963  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.964  1031  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 16:55:13.964  1031  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 16:55:13.964  1031  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 16:55:13.964  1031  1529 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 16:55:13.965  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 16:55:13.967  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 16:55:13.967  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 16:55:13.967  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 16:55:13.967  1031  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 16:55:13.967  1031  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 16:55:13.967  1031  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 16:55:13.967  1031  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 16:55:13.967  1031  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 16:55:13.967  1031  8151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.967  1031  8151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 16:55:13.967  1031  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:55:13.967  1031  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 16:55:13.968  1031  8151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 16:55:13.968  1031  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:13.968  1031  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 16:55:13.968  1031  1529 D ConnectivityService: currentScore = 0, newScore = 20
08-26 16:55:13.968  1031  8151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 16:55:13.968  1031  1529 D ConnectivityService:    accepting network in place of null
08-26 16:55:13.968  1031  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:13.969  1031  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 16:55:13.969  1031  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 16:55:13.969  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 16:55:13.969  1031  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:13.969  1031  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 16:55:13.969  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:13.970  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transpor,ts: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 16:55:13.971   321  8161 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 16:55:13.974  1031  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 16:55:13.974  1031  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 16:55:13.974  1031  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 16:55:13.975  1031  1529 D ConnectivityService: validation of new default Network = false
08-26 16:55:13.975  1031  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 16:55:13.975  1031  1529 D DSQN    : enableDataServiceNotify 
08-26 16:55:13.975  1031  1529 D DSQN    : start dsqn bin
,08-26 16:55:13.980  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 16:55:13.980  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 16:55:13.980  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 16:55:13.980  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 16:55:13.981  1031  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 16:55:13.981  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:13.981  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:55:13.965  8162  8162 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:13.965  8162  8162 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:13.982  1031  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:55:13.982  1587  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 16:55:13.984  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 16:55:13.985  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 16:55:13.985  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:13.985  1031  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 16:55:13.997  8162  8162 E DSQN    : DSQN ssw
,08-26 16:55:14.008  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 16:55:14.008  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:14.009  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:14.026   321  8161 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 16:55:14.064   321  8161 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 16:55:14.070  6679  6792 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
08-26 16:55:14.071  6679  6792 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
08-26 16:55:14.080  6679  6792 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
08-26 16:55:14.082  6679  6792 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 16:55:14.083  6679  6792 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
,08-26 16:55:14.091  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.091  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bd96f4b added. We now have 2 listener(s)
08-26 16:55:14.091  1031  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.096  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.096  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 16:55:14.097  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:14.097  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.097  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7f6d28 added. We now have 9 listener(s)
08-26 16:55:14.097  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.098  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 16:55:14.098  1031  8152 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 16:55:14.099  1031  8152 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 16:55:14.099  1031  8152 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 16:55:14.085  8167  8167 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:14.085  8167  8167 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 16:55:14.104   321   889 D LGDataListener: argv[0]=dsqncommand
08-26 16:55:14.104   321   889 D LGDataListener: argv[1]=wlan0
08-26 16:55:14.104   321   889 D LGDataListener: argv[2]=1
08-26 16:55:14.104   321   889 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 16:55:14.105  1031  1100 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 16:55:14.105  1031  1100 D DSQN    : start to monitor internet connection
08-26 16:55:14.107  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:55:14.110  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:14.110  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:14.110  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:14.110  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:14.110  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:14.110  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.110  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:14.110  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:55:14.112  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.112  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:55:14.113  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:14.115  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:14.115  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.115  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d19ebe6 added. We now have 3 listener(s)
,08-26 16:55:14.115  1031  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.117  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.117  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:14.117  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:14.117  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.117  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33cdb527 added. We now have 10 listener(s)
08-26 16:55:14.117  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.117  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:55:14.117  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:14.117  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:55:14.118  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:14.118  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.118  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:55:14.118  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.118  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bd96f4b removed from the list
08-26 16:55:14.118  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.118  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7f6d28 removed from the list
08-26 16:55:14.118  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:55:14.118  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.118  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.118  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.119  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.119  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.119  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.119  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7f6d28 not in the list
08-26 16:55:14.119  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.119  6679  6792 D org.thaliproject.p,2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.120  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.120  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.120  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.120  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33cdb527 removed from the list
08-26 16:55:14.120  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:14.120  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.120  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.120  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.120  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d19ebe6 removed from the list
08-26 16:55:14.120  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.120  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef233d4 added. We now have 2 listener(s)
08-26 16:55:14.121  1031  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.121  8167  8167 I dhcpcd  : version 5.5.6 starting
08-26 16:55:14.122  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.122  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:14.122  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:14.122  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.123  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2d97d added. We now have 9 listener(s)
08-26 16:55:14.123  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.123  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 16:55:14.125  8167  8167 E dhcpcd  : get_duid: m
08-26 16:55:14.125  8167  8167 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 16:55:14.125  8167  8167 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 16:55:14.126  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:55:14.129  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:14.129  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:14.129  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:14.129  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:14.129  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:14.129  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.129  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:14.129  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:55:14.131  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.131  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:55:14.131  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.131  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14d67cc3 added. We now have 3 listener(s)
08-26 16:55:14.132  1031  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.134  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.134  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:14.134  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:14.134  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.134  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b28b940 added. We now have 10 listener(s)
08-26 16:55:14.135  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.135  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 16:55:14.135  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 16:55:14.135  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 16:55:14.135  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:55:14.135  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 16:55:14.138  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 16:55:14.140  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:14.140  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 16:55:14.141  1031  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.143  1031  8151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 14:55:14 GMT], X-Android-Received-Millis=[1472223314143], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472223314103]}
08-26 16:55:14.143  1031  8151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 16:55:14.143  1031  8151 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 16:55:14.144  1031  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-26 16:55:14.144  1031  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 16:55:14.144  1031  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 16:55:14.144  1031  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:55:14.144  1031  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 16:55:14.144  1031  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 16:55:14.144  1031  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 16:55:14.144  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:14.144  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:55:14.145  1031  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:55:14.145  1031  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:14.145  1587  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 16:55:14.145  1031  1522 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:14.145  1031  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 16:55:14.145  1031  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 16:55:14.146  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:14.146  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 16:55:14.152  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 16:55:14.152  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 16:55:14.155  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:55:14.159  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:55:14.161  8167  8167 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 16:55:14.161  8167  8167 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 16:55:14.161  8167  8167 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 16:55:14.162  8167  8167 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 16:55:14.162  8167  8167 D dhcpcd  : wlan0: sending REQUEST (xid 0x9bb296a1), next in 4.97 seconds
08-26 16:55:14.162  6679  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 16:55:14.162  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:14.162  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:55:14.163  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 16:55:14.164  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 16:55:14.165  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 16:55:14.165  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:55:14.165  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:14.165  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:55:14.166  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:14.166  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.166  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:55:14.166  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.166  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef233d4 removed from the list
08-26 16:55:14.166  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.166  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2d97d removed from the list
08-26 16:55:14.166  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:55:14.166  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.166  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.166  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.167  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.167  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.167  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.168  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e2d97d not in the list
08-26 16:55:14.168  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.168  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.168  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.169  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:55:14.169  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:55:14.169  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.169  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.169  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b28b940 removed from the list
08-26 16:55:14.169  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:14.169  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:1,4.169  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.169  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.169  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14d67cc3 removed from the list
08-26 16:55:14.170  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.170  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171a221f added. We now have 2 listener(s)
08-26 16:55:14.170  1031  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.172  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.172  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:14.172  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:14.172  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.172  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f80296c added. We now have 9 listener(s)
08-26 16:55:14.172  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.172  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 16:55:14.174  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:55:14.178  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:14.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:14.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:14.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:14.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:14.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:14.178  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 16:55:14.179  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.179  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 16:55:14.181  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.181  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b00bca added. We now have 3 listener(s)
08-26 16:55:14.181  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:14.181  1031  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.183  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:14.185  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.185  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:14.185  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:14.185  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.185  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34c8c13b added. We now have 10 listener(s)
08-26 16:55:14.185  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.185  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 16:55:14.186  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 16:55:14.186  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 16:55:14.186  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 16:55:14.186  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:55:14.186  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 16:55:14.188  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 16:55:14.189  1031  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.192  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 16:55:14.194  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 16:55:14.196  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:55:14.197  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:55:14.198  6679  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 16:55:14.199  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:55:14.199  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:14.199  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:55:14.199  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:14.199  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.199  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:55:14.199  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.199  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171a221f removed from the list
08-26 16:55:14.199  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.199  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f80296c removed from the list
08-26 16:55:14.199  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:55:14.199  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.199  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.200  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.200  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.200  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.200  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.200  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f80296c not in the list
08-26 16:55:14.200  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.200  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.201  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.201  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:55:14.202  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:55:14.202  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.202  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.202  6679 , 6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34c8c13b removed from the list
08-26 16:55:14.202  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:14.202  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.202  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.202  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.202  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b00bca removed from the list
08-26 16:55:14.202  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.202  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab1a96 added. We now have 2 listener(s)
,08-26 16:55:14.203  1031  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.205  8167  8167 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-26 16:55:14.205  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.205  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:14.205  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 16:55:14.205  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.205  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10f83617 added. We now have 9 listener(s)
08-26 16:55:14.205  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.206  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 16:55:14.207  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 16:55:14.210  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:14.210  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:14.210  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:14.210  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-26 16:55:14.210  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:14.210  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.210  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:14.210  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:55:14.211  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.211  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:55:14.211  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.212  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c21bed added. We now have 3 listener(s)
08-26 16:55:14.212  1031  1631 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 16:55:14.215  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:14.217  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:14.217  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.217  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:14.217  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 16:55:14.218  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.218  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17764a22 added. We now have 10 listener(s)
08-26 16:55:14.218  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.218  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 16:55:14.218  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 16:55:14.218  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 16:55:14.218  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:55:14.218  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 16:55:14.220  8134  8134 W ExternalStrings: load override strings
08-26 16:55:14.220  8134  8134 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
,08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	,at com.mcafee.plugin.ak.a(Unknown Source)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 16:55:14.220  8134  8134 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 16:55:14.221  8134  8134 D StatusProvider: onCreate
08-26 16:55:14.222  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 16:55:14.222  1031  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.225  8167  8167 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 16:55:14.226  8167  8167 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 16:55:14.226  8167  8167 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 16:55:14.226  8167  8167 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 16:55:14.227  8167  8167 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-26 16:55:14.227  8167  8167 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 16:55:14.227  8167  8167 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 16:55:14.227  8167  8167 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT,
08-26 16:55:14.228  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 16:55:14.229  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 16:55:14.231  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 16:55:14.231  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 16:55:14.233  6679  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-26 16:55:14.236  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:55:14.236  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:14.236  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:55:14.236  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:14.236  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.236  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:55:14.236  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.236  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab1a96 removed from the list
08-26 16:55:14.236  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.236  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10f83617 removed from the list
08-26 16:55:14.236  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
08-26 16:55:14.237  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.237  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.237  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.238  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.238  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.238  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.238  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10f83617 not in the list
08-26 16:55:14.238  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.238  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.239  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.239  6679  6792 D BluetoothLeScanner: could not find callback wrapper
08-26 16:55:14.239  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 16:55:14.239  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.239  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.239  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17764a22 removed from the list
08-26 16:55:14.239  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:14.239  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.239  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16,:55:14.239  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.239  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c21bed removed from the list
08-26 16:55:14.240  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.240  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb189e9 added. We now have 2 listener(s)
08-26 16:55:14.241  1031  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.243  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.243  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:14.243  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:14.243  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.243  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd2e66e added. We now have 9 listener(s)
08-26 16:55:14.243  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.244  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 16:55:14.247  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 16:55:14.249  6679  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 16:55:14.249  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 16:55:14.249  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 16:55:14.249  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 16:55:14.249  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 16:55:14.249  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.249  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 16:55:14.249  6679  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 16:55:14.251  6679  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 16:55:14.251  6679  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 16:55:14.251  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 16:55:14.251  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@296c59c added. We now have 3 listener(s)
08-26 16:55:14.251  1031  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 16:55:14.254  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 16:55:14.254  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 16:55:14.254  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 16:55:14.255  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 16:55:14.255  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d0fdba5 added. We now have 10 listener(s)
08-26 16:55:14.255  6679  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 16:55:14.255  6679  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 16:55:14.255  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 16:55:14.255  6679  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 16:55:14.255  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 16:55:14.255  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.255  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:14.256  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 16:55:14.256  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.256  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb189e9 removed from the list
08-26 16:55:14.256  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.256  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd2e66e removed from the list
08-26 16:55:14.257  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 16:55:14.257  6679  6792 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 16:55:14.257  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.258  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.258  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.258  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.258  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.258  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 16:55:14.258  6679  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cd2e66e not in the list
08-26 16:55:14.258  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.259  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.259  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 16:55:14.259  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 16:55:14.259  6679  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 16:55:14.259  6679  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d0fdba5 removed from the list
08-26 16:55:14.259  6679  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 16:55:14.259  6679  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 16:55:14.259  6679  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 16:55:14.259  6679  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 16:55:14.259  6679  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@296c59c removed from the list
08-26 16:55:14.260  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 16:55:14.261  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 16:55:14.261  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 16:55:14.261  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 16:55:14.261  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-26 16:55:14.261  6679  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-26 16:55:14.273  6679  8182 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
08-26 16:55:14.274  6679  8182 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: My test thread name)
08-26 16:55:14.274  6679  8182 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 16:55:14.276  6679  8184 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: My test thread name)
08-26 16:55:14.276  6679  8184 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: My test thread name)
08-26 16:55:14.276  6679  8184 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 16:55:14.277  6679  6792 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 16:55:14.277  6679  6792 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 16:55:14.277  6679  6792 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 16:55:14.277  6679  6792 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 16:55:14.277  6679  6792 D com.test.thalitest.ThaliTestRunner: Total duration: 23202 ms
08-26 16:55:14.278  6679  6792 I jxcore-log: *Native tests were executed*
08-26 16:55:14.278  6679  6792 I jxcore-log: 
08-26 16:55:14.278  6679  6792 I jxcore-log: Total number of executed tests:  80
08-26 16:55:14.278  6679  6792 I jxcore-log: 
08-26 16:55:14.278  6679  6792 I jxcore-log: Number of passed tests:  80
08-26 16:55:14.278  6679  6792 I jxcore-log: 
08-26 16:55:14.279  6679  6792 I jxcore-log: Number of failed tests:  0
08-26 16:55:14.279  6679  6792 I jxcore-log: 
08-26 16:55:14.279  6679  6792 I jxcore-log: Number of ignored tests:  0
08-26 16:55:14.279  6679  6792 I jxcore-log: 
08-26 16:55:14.279  6679  6792 I jxcore-log: Total duration:  23202
08-26 16:55:14.279  6679  6792 I jxcore-log: 
08-26 16:55:14.279  6679  6792 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 16:55:14.279  6679  6792 I jxcore-log: 
08-26 16:55:14.281  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.281  6679  6792 I jxcore-log: 
08-26 16:55:14.282  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.282  6679  6792 I jxcore-log: 
,08-26 16:55:14.283  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.283  6679  6792 I jxcore-log: 
08-26 16:55:14.284  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.284  6679  6792 I jxcore-log: 
08-26 16:55:14.284  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.284  6679  6792 I jxcore-log: 
08-26 16:55:14.285  8134  8134 V Signer  : override build config not found
08-26 16:55:14.285  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 16:55:14.285  6679  6792 I jxcore-log: 
08-26 16:55:14.286  8134  8134 D Signer  : value of property debug is false
08-26 16:55:14.288  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.288  6679  6792 I jxcore-log: 
08-26 16:55:14.289  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 16:55:14.289  6679  6792 I jxcore-log: 
08-26 16:55:14.289  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.289  6679  6792 I jxcore-log: 
08-26 16:55:14.290  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.290  6679  6792 I jxcore-log: 
08-26 16:55:14.291  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 16:55:14.291  6679  6792 I jxcore-log: 
08-26 16:55:14.291  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 16:55:14.291  6679  6792 I jxcore-log: 
08-26 16:55:14.292  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 16:55:14.292  6679  6792 I jxcore-log: 
08-26 16:55:14.293  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.293  6679  6792 I jxcore-log: 
08-26 16:55:14.293  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.293  6679  6792 I jxcore-log: 
08-26 16:55:14.293  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.293  6679  6792 I jxcore-log: 
08-26 16:55:14.293  6679  6679 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 16:55:14.294  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.294  6679  6792 I jxcore-log: 
08-26 16:55:14.294  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.294  6679  6792 I jxcore-log: 
08-26 16:55:14.295  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.295  6679  6792 I jxcore-log: 
08-26 16:55:14.295  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.295  6679  6792 I jxcore-log: 
08-26 16:55:14.296  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 16:55:14.296  6679  6792 I jxcore-log: 
08-26 16:55:14.296  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 16:55:14.296  6679  6792 I jxcore-log: 
08-26 16:55:14.297  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 16:55:14.297  6679  6792 I jxcore-log: 
08-26 16:55:14.297  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.297  6679  6792 I jxcore-log: 
08-26 16:55:14.298  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.298  6679  6792 I jxcore-log: 
08-26 16:55:14.298  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.298  6679  6792 I jxcore-log: 
08-26 16:55:14.298  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.298  6679  6792 I jxcore-log: 
08-26 16:55:14.299  6679  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 16:55:14.299  6679  6792 I jxcore-log: 
,08-26 16:55:14.335  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-26 16:55:14.335  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-26 16:55:14.336  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 16:55:14.336  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,08-26 16:55:14.336  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 16:55:14.336  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 16:55:14.337  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 16:55:14.337  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 16:55:14.337  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 16:55:14.338  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-26 16:55:14.338  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 16:55:14.338  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 16:55:14.338  8134  8134 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-26 16:55:14.367  8134  8134 V LGMDMManager: Create singleton instance
,08-26 16:55:14.424  8134  8134 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-26 16:55:14.465  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:14.466  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 16:55:14.473  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:55:14.480  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 16:55:14.502  1031  8152 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 16:55:14.503  1031  8152 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 16:55:14.504  1031  8152 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-26 16:55:14.504  1031  8152 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 16:55:14.504  1031  8152 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 16:55:14.504  1031  8152 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 16:55:14.504  1031  8152 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 16:55:14.504  1031  8152 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 16:55:14.505  1031  8152 D DhcpStateMachine: RunningState
,08-26 16:55:14.514  1031  1889 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8205 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 16:55:14.514  1031  1889 I ActivityManager: Killing 7242:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-26 16:55:14.565  8193  8193 D AndroidRuntime: 
08-26 16:55:14.565  8193  8193 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 16:55:14.567  8193  8193 D AndroidRuntime: CheckJNI is OFF
,08-26 16:55:14.592  8134  8201 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 16:55:14.700  8193  8193 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 16:55:14.758  1031  1768 W libprocessgroup: failed to open /acct/uid_10093/pid_7242/cgroup.procs: No such file or directory
,08-26 16:55:14.836  1031  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-26 16:55:14.836  1031  1098 I ActivityManager: Killing 6679:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-26 16:55:14.871  8205  8205 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 16:55:14.884  1031  1631 I WindowState: WIN DEATH: Window{1486eebc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 16:55:14.885  1031  1528 D WifiService: Client connection lost with reason: 4
08-26 16:55:14.892  1031  1631 D InputDispatcher: Window went away: Window{1486eebc u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 16:55:15.000  1031  1522 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 16:55:15.002  1031  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 16:55:15.003  1031  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 16:55:15.004  1031  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 16:55:15.006  1031  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 16:55:15.008  1031  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 16:55:15.009  1031  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-26 16:55:15.009  1031  1529 D ConnectivityService: identical MTU - not setting
08-26 16:55:15.010  1031  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 16:55:15.010  1031  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 16:55:15.010  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 16:55:15.010  1031  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:55:15.012  1031  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 16:55:15.014  1587  1816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 16:55:15.061  1031  1098 I ActivityManager:   Force finishing activity ActivityRecord{2d3c58cf u0 com.test.thalitest/.MainActivity t6}
,08-26 16:55:15.110   342   356 E GBMv2   : DFP En is all cleared set to be enabled
,08-26 16:55:15.116  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-26 16:55:15.116  1031  1907 W ActivityManager: Spurious death for ProcessRecord{3ef3106b 6679:com.test.thalitest/u0a118}, curProc for 6679: null
,08-26 16:55:15.117  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{21b81956 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 16:55:15.118  1031  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-26 16:55:15.119  1927  2731 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 16:55:15.120  1031  1123 I ActivityManager:   Force finishing activity ActivityRecord{2d3c58cf u0 com.test.thalitest/.MainActivity t6 f}
08-26 16:55:15.120  1031  1123 W ActivityManager: Duplicate finish request for ActivityRecord{2d3c58cf u0 com.test.thalitest/.MainActivity t6 f}
08-26 16:55:15.120  1927  2731 D SplitWindowPolicy: topRunningActivity=ActivityInfo{219f2dd7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 16:55:15.128  8205  8205 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 16:55:15.151  2018  2018 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-26 16:55:15.153  2018  2018 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-26 16:55:15.155  1031  1449 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 16:55:15.161  3861  3861 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-26 16:55:15.168  7683  7683 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
,08-26 16:55:15.168  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 16:55:15.168  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-26 16:55:15.180  2478  2664 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 16:55:15.181  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 16:55:15.181  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 16:55:15.187  2018  2097 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-26 16:55:15.225  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 16:55:15.227  1890  1890 D ActionManagerService: notifyUserLog: 1000003
08-26 16:55:15.228  3861  4527 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-26 16:55:15.231  4528  4528 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 16:55:15.231  4528  4528 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 16:55:15.232  4528  4528 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 16:55:15.233  4528  4528 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 16:55:15.233  4528  4528 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 16:55:15.233  4528  4528 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 16:55:15.233  4528  4528 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 16:55:15.233  4528  4528 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 16:55:15.233  4528  4528 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 16:55:15.233  4528  4528 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 16:55:15.233  4528  4528 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 16:55:15.233  4528  4528 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 16:55:15.250  2018  2018 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-26 16:55:15.254  2018  2018 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-26 16:55:15.257  2018  2018 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 16:55:15.258  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-26 16:55:15.262  1890  1890 D ActionManagerService: notifyUserLog: 1000004
08-26 16:55:15.263  3861  4527 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 16:55:15.272  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 16:55:15.278  8134  8201 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:55:15.278  8134  8201 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 16:55:15.279  8205  8205 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 16:55:15.280  1587  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 16:55:15.280  1587  1647 D KeyguardModel: createShortcutInfo...
08-26 16:55:15.280  8205  8205 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 16:55:15.280  8205  8205 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 16:55:15.280  8205  8205 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-26 16:55:15.280  8205  8205 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 16:55:15.282  8205  8205 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 16:55:15.283  1587  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 16:55:15.283  1587  1647 D KeyguardModel: createShortcutInfo...
08-26 16:55:15.290  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 16:55:15.291  1587  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 16:55:15.291  1587  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 16:55:15.291  1587  1647 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 16:55:15.292  1587  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 16:55:15.293  8205  8205 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 16:55:15.293  1031  1031 D administrator: Handling package changes for user 0
,08-26 16:55:15.294  1587  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 16:55:15.294  1587  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 16:55:15.296  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-26 16:55:15.299  1587  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 16:55:15.299  1587  1647 D KeyguardModel: createShortcutInfo...
08-26 16:55:15.299  3861  3877 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , display: false
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , animation: false }
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , display: false
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , animation: false }
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , create_time: 1472216588858
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , display: false
08-26 16:55:15.304  2018  2018 I GBoardWebViewUtils: , animation: false }
08-26 16:55:15.304  1587  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 16:55:15.304  1587  1647 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 16:55:15.305  1587  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 16:55:15.305  1587  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-26 16:55:15.306  1587  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 16:55:15.306  1587  1647 D KeyguardModel: createShortcutInfo...
08-26 16:55:15.308  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:55:15.309  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.312  2018  8267 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-26 16:55:15.314  1031  1889 V SIM_STK : Menu title from STK is T-Mobile
08-26 16:55:15.329  1031  2319 V SIM_STK : Menu title from STK is T-Mobile
08-26 16:55:15.329  1031  2319 V SIM_STK : Menu title from STK is T-Mobile
,08-26 16:55:15.336  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-26 16:55:15.337  1853  1853 D SplitUIService: removed split : 
08-26 16:55:15.338  1587  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 16:55:15.338  1587  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 16:55:15.338  1587  1647 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 16:55:15.338  1587  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 16:55:15.339  1587  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 16:55:15.339  1587  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 16:55:15.347  4628  4628 I art     : Explicit concurrent mark sweep GC freed 8234(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 336us total 183.595ms
,08-26 16:55:15.348  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 16:55:15.350  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-26 16:55:15.357  1587  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 16:55:15.357  1587  1647 D KeyguardModel: createShortcutInfo...
08-26 16:55:15.360  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-26 16:55:15.360  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 16:55:15.368  8205  8205 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 16:55:15.371  1587  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 16:55:15.371  1587  1647 D KeyguardModel: createShortcutInfo...
08-26 16:55:15.371  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 16:55:15.372  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 16:55:15.383  8205  8205 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-26 16:55:15.385  1031  1559 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 16:55:15.385  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 16:55:15.385  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 16:55:15.386  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 16:55:15.386  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 16:55:15.386  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 16:55:15.386  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 16:55:15.386  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 16:55:15.386  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 16:55:15.386  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 16:55:15.386  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 16:55:15.386  7683  7683 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 16:55:15.386  1587  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 16:55:15.386  1587  1647 D KeyguardModel: createShortcutInfo...
08-26 16:55:15.387  8205  8205 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 16:55:15.388  1587  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 16:55:15.389  1587  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 16:55:15.389  1587  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 16:55:15.389  1587  1647 D KeyguardModel: createShortcutInfo...
08-26 16:55:15.390  1587  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 16:55:15.390  1587  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 16:55:15.391  1587  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 16:55:15.391  1587  1647 D KeyguardModel: createShortcutInfo...
08-26 16:55:15.392  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:55:15.396  1587  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 16:55:15.396  1587  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 16:55:15.397  1587  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 16:55:15.397  1587  1647 D KeyguardModel: createShortcutInfo...
,08-26 16:55:15.404  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-26 16:55:15.404  1853  1853 I SplitUIService: split app #11
08-26 16:55:15.411  1031  1051 V SIM_STK : Menu title from STK is T-Mobile
08-26 16:55:15.414  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-26 16:55:15.414  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-26 16:55:15.430  1031  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-26 16:55:15.451  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.452  2018  2018 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-26 16:55:15.454  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:55:15.454  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 16:55:15.461  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 16:55:15.461  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 16:55:15.461  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 16:55:15.463  8205  8205 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 16:55:15.466  1031  1561 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 16:55:15.467  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 16:55:15.469  6853  6853 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 16:55:15.473  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:15.475  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 16:55:15.479  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:55:15.483  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.486  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:55:15.487  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.487  8205  8205 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 16:55:15.497  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:15.497  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 16:55:15.502  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:55:15.506  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.514  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 16:55:15.514  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.515  8205  8205 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 16:55:15.517  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:15.518  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 16:55:15.522  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:55:15.525  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-26 16:55:15.528  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 16:55:15.530  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 16:55:15.531  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 16:55:15.532  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,08-26 16:55:15.533  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 16:55:15.538  8134  8201 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-26 16:55:15.549  1031  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{93e5451 u0 com.lge.launcher2/.Launcher t5} time:143413
08-26 16:55:15.551  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 16:55:15.551  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 16:55:15.555  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.560  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:55:15.561  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.561  8205  8205 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 16:55:15.562  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 16:55:15.562  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 16:55:15.562  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 16:55:15.563  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 16:55:15.565  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 16:55:15.565  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-26 16:55:15.560  8134  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-26 16:55:15.566  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 16:55:15.566  2018  2178 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 16:55:15.566  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 16:55:15.566  2018  2178 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-26 16:55:15.569  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 16:55:15.569  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 16:55:15.569  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 16:55:15.569  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 16:55:15.569  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 16:55:15.570  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 16:55:15.570  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 16:55:15.573  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:15.573  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 16:55:15.575  2018  2018 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-26 16:55:15.578  2583  2583 D [Concierge]Service: onStartCommand(). Type : 8
08-26 16:55:15.578  2583  2583 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 16:55:15.579  2583  2583 D [Concierge]Service: Update widget ID : 11
08-26 16:55:15.580  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:55:15.580  2018  2018 D [Concierge]WidgetView: change position of spinner
08-26 16:55:15.581  8134  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 16:55:15.581  8134  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 16:55:15.581  8134  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 16:55:15.582  2018  2018 I [Concierge]WidgetView: initWebView(). Time : 1472223315582
08-26 16:55:15.582  2583  2583 D [Concierge]Service: onStartCommand(). Type : 0
08-26 16:55:15.582  8134  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 16:55:15.584  8134  8201 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 16:55:15.586  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.588  8134  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-26 16:55:15.589  8134  8201 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-26 16:55:15.593  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:55:15.593  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.594  8205  8205 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 16:55:15.596  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:15.596  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 16:55:15.599  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:55:15.600  2018  2018 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 541753129
08-26 16:55:15.600  2018  2018 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-26 16:55:15.601  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 16:55:15.603  2018  2018 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@fd3a82e
08-26 16:55:15.603  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 16:55:15.604  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 16:55:15.604  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 16:55:15.609  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.610  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 16:55:15.611  2018  2018 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 16:55:15.611  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-26 16:55:15.615  2018  2018 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472223197985, New one : 1472223315582
08-26 16:55:15.615  2018  2018 D [Concierge]WidgetView: Unregister all receivers
08-26 16:55:15.615  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 16:55:15.615  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:55:15.616  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.616  8205  8205 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 16:55:15.617  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 16:55:15.618  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 16:55:15.619  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-26 16:55:15.620  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 16:55:15.621  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 16:55:15.622  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 16:55:15.622  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 16:55:15.622  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:15.623  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 16:55:15.623  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 16:55:15.639  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:55:15.642  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.651  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 16:55:15.651  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.654  8205  8205 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 16:55:15.657  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 16:55:15.659  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:15.659  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 16:55:15.665  2018  2018 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 16:55:15.665  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-26 16:55:15.665  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:55:15.667  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 16:55:15.670  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.675  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:55:15.675  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.675  8205  8205 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 16:55:15.678  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 16:55:15.679  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 16:55:15.682  8086  8086 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 16:55:15.684  8086  8086 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:55:15.687  2018  2018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36ee432a time:143552
08-26 16:55:15.688  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 16:55:15.692  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.696  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:55:15.696  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.696  8205  8205 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 16:55:15.697  8205  8205 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 16:55:15.697  8205  8205 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 16:55:15.700  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:15.700  8134  8202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 16:55:15.703  8086  8086 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 16:55:15.704  8086  8086 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 16:55:15.706  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 16:55:15.709  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 16:55:15.714  8205  8205 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 16:55:15.714  8205  8205 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 16:55:15.714  8205  8205 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 16:55:15.715  8205  8205 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 16:55:15.715  8205  8205 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 16:55:15.718  1031  1123 I art     : Explicit concurrent mark sweep GC freed 84657(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.474ms total 380.861ms
,08-26 16:55:15.718  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 16:55:15.734  8134  8134 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-26 16:55:15.737  1800  1800 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-26 16:55:15.762  8193  8193 D AndroidRuntime: Shutting down VM
,08-26 16:55:15.797  1031  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 16:55:15.805  1031  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-26 16:55:15.806  1031  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8281 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 16:55:15.810  2115  2115 I ConfigService: onCreate
08-26 16:55:15.811  2115  2115 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-26 16:55:15.812  1800  1800 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-26 16:55:15.815  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 16:55:15.825  2115  2115 I ConfigService: onBind returning update interface
08-26 16:55:15.826  2115  2115 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 16:55:15.826  2115  2115 I ConfigService: onBind returning config service
,08-26 16:55:15.829  2115  2115 I ConfigService: onDestroy
,08-26 16:55:15.831  1800  8299 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-26 16:55:15.841  2018  2018 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-26 16:55:15.852  5996  8305 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-26 16:55:15.862  1800  8306 I PeopleContactsSync: CP2 sync disabled
,08-26 16:55:15.866  1800  4813 I Icing   : doRemovePackageData com.test.thalitest
08-26 16:55:15.878  1800  8304 W GmsApplication: Using Auth Proxy for data requests.
,08-26 16:55:15.882  1800  8304 W GmsApplication: Using Auth Proxy for data requests.
08-26 16:55:15.893  2018  2865 I GBoardtInterface: onReloaded()
,08-26 16:55:15.897  2018  2018 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-26 16:55:15.898  3861  3877 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 16:55:15.900  3861  4546 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 16:55:15.906  1890  1890 D ActionManagerService: notifyUserLog: 1000001
,08-26 16:55:15.907  3861  4527 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 16:55:15.907  3861  4527 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 16:55:15.910  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-26 16:55:15.911  3861  4527 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 16:55:15.911  3861  4527 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 16:55:15.911  3861  4527 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-26 16:55:15.911  3861  4527 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-26 16:55:15.912  3861  3877 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 16:55:15.913  7052  7052 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-26 16:55:15.915  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-26 16:55:15.915  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-26 16:55:15.916  1031  1051 I ActivityManager: Killing 7283:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-26 16:55:15.917  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-26 16:55:15.917  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 16:55:15.920  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-26 16:55:15.920  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-26 16:55:15.945  1031  1907 W libprocessgroup: failed to open /acct/uid_10005/pid_7283/cgroup.procs: No such file or directory
,08-26 16:55:15.951  2322  8310 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 16:55:15.985  1031  1768 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8311 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 16:55:16.035  8311  8311 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 16:55:16.035  8311  8311 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 16:55:16.036  8311  8311 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 16:55:16.036  8311  8311 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 16:55:16.096  8311  8311 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 16:55:16.103  2115  4226 I art     : Explicit concurrent mark sweep GC freed 6530(388KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 2.690ms total 26.118ms
08-26 16:55:16.111  8311  8311 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 16:55:16.124  1800  8301 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-26 16:55:16.125  1800  8301 E DriveAsyncService: disk I/O error (code 3850)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
08-26 16:55:16.125  1800  8301 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 16:55:16.149  8311  8311 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 16:55:16.179  8311  8311 D LgDataFeature: LgDataFeature() Constructor: none
08-26 16:55:16.179  8311  8311 D LgDataFeature: LgDataFeature() Constructor Done, null

```
