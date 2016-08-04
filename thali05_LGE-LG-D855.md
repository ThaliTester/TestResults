#### Test 794266502283b5d_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-04 11:12:50.831  6506  6506 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-04 11:12:51.610  1811  4706 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-04 11:12:51.668  1811  4706 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-04 11:12:51.704  1811  4706 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-04 11:12:51.872  6532  6532 D AndroidRuntime: 
08-04 11:12:51.872  6532  6532 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-04 11:12:51.874  6532  6532 D AndroidRuntime: CheckJNI is OFF
08-04 11:12:51.985  6532  6532 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-04 11:12:51.989  1044  1586 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 11:12:52.001  1935  1952 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-04 11:12:52.003  1044  1586 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-04 11:12:52.005  1044  1586 D ActivityManager: setTaskToReturnTo : TaskRecord{3d950d52 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 11:12:52.005  1044  1586 D ActivityManager: setTaskToReturnTo : TaskRecord{3d950d52 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 11:12:52.007  1044  1586 D WindowStateEx: AppWindowTokenEx init.. 
08-04 11:12:52.009   343   372 E GBMv2   : DFP En is all cleared set to be enabled
08-04 11:12:52.035  1044  1586 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6547 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-04 11:12:52.036  6532  6532 D AndroidRuntime: Shutting down VM
08-04 11:12:52.066  6506  6506 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:12:52.066  6506  6506 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 11:12:52.113  1935  1952 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-04 11:12:52.113  1935  1952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{46526b5 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-04 11:12:52.115  1935  2634 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-04 11:12:52.115  1935  2634 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15dad14a co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-04 11:12:52.183  6547  6547 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-04 11:12:52.247  6120  6120 I LockScreenSettings: New app installed broadcast received ..
08-04 11:12:52.250  6120  6120 I LockScreenSettings: Number of installed packages  1
08-04 11:12:52.271  6506  6506 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-04 11:12:52.295  6547  6547 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-04 11:12:52.300  1044  1953 V SIM_STK : Menu title from STK is T-Mobile
08-04 11:12:52.305  6547  6547 I LibraryLoader: Loading: webviewchromium
08-04 11:12:52.309  6547  6547 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7647-7651)
08-04 11:12:52.309  6547  6547 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:12:52.325  6547  6547 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1fe072b}
08-04 11:12:52.326  1044  2026 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6583 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 11:12:52.327  6547  6547 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:12:52.327  6547  6547 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 11:12:52.338  6547  6547 I BrowserStartupController: Initializing chromium process, renderers=0
08-04 11:12:52.339  6547  6547 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:12:52.354   328  2121 V AudioPolicyService: registerClient() client 0xb558abc0, uid 10118
08-04 11:12:52.354  6547  6547 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-04 11:12:52.355  6547  6547 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-04 11:12:52.355  6547  6547 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-04 11:12:52.361  1044  1126 D BluetoothManagerService: Message: 20
08-04 11:12:52.361  1044  1126 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@977fc11:true
08-04 11:12:52.373  6547  6547 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:12:52.373  6547  6547 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:12:52.373  6547  6547 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:12:52.373  6547  6547 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:12:52.373  6547  6547 I Adreno-EGL: Remote Branch: 
08-04 11:12:52.373  6547  6547 I Adreno-EGL: Local Patches: 
08-04 11:12:52.373  6547  6547 I Adreno-EGL: Reconstruct Branch: 
08-04 11:12:52.426  6583  6583 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-04 11:12:52.426  6583  6583 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-04 11:12:52.465  1044  1060 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6621 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-04 11:12:52.467  1044  1060 I ActivityManager: Killing 5772:com.google.android.gm/u0a64 (adj 15): empty #17
08-04 11:12:52.558  1044  1947 W libprocessgroup: failed to open /acct/uid_10064/pid_5772/cgroup.procs: No such file or directory
08-04 11:12:52.589  6547  6615 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-04 11:12:52.591  6547  6547 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-04 11:12:52.611  1044  1117 W ActivityManager: Activity pause timeout for ActivityRecord{1f1d823 u0 com.test.thalitest/.MainActivity t40}
08-04 11:12:52.613  6547  6547 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:12:52.618  6547  6547 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-04 11:12:52.621  6547  6547 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-04 11:12:52.625  6547  6547 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-04 11:12:52.625  6547  6547 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-04 11:12:52.636  6621  6621 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-04 11:12:52.641  6547  6547 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-04 11:12:52.648  6547  6547 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:12:52.648  6547  6547 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:12:52.660  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-04 11:12:52.661  6621  6621 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 11:12:52.678  6547  6649 D OpenGLRenderer: Render dirty regions requested: true
08-04 11:12:52.679  6547  6649 I OpenGLRenderer: Initialized EGL, version 1.4
08-04 11:12:52.683  6547  6649 D OpenGLRenderer: Enabling debug mode 0
08-04 11:12:52.687  1044  2026 I ActivityManager: Killing 5616:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-04 11:12:52.691  6547  6547 D Atlas   : Validating map...
08-04 11:12:52.694  1044  2000 D SplitWindow: check instance of lgWin Window{3c34d1fe u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-04 11:12:52.702  5583  5583 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-04 11:12:52.702  5583  5583 W System.err: android.os.DeadObjectException
08-04 11:12:52.703  5583  5583 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 11:12:52.703  5583  5583 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 11:12:52.703  5583  5583 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-04 11:12:52.703  5583  5583 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-04 11:12:52.703  5583  5583 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 11:12:52.703  5583  5583 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 11:12:52.703  5583  5583 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:12:52.703  5583  5583 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:12:52.703  5583  5583 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:12:52.703  5583  5583 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:12:52.703  5583  5583 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:12:52.703  5583  5583 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:12:52.703  5583  5583 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:12:52.703  5583  5583 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:12:52.703  5583  5583 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-04 11:12:52.703  5583  5583 W System.err: android.os.DeadObjectException
08-04 11:12:52.703  5583  5583 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 11:12:52.703  5583  5583 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 11:12:52.703  5583  5583 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-04 11:12:52.703  5583  5583 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-04 11:12:52.704  5583  5583 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 11:12:52.704  5583  5583 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 11:12:52.704  5583  5583 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:12:52.704  5583  5583 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:12:52.704  5583  5583 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:12:52.704  5583  5583 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:12:52.704  5583  5583 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:12:52.704  5583  5583 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:12:52.704  5583  5583 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:12:52.704  5583  5583 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:12:52.704  5583  5583 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-04 11:12:52.704  5583  5583 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-04 11:12:52.735  6547  6646 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:12:52.735  6547  6646 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 11:12:52.920  1044  1569 W libprocessgroup: failed to open /acct/uid_1000/pid_5616/cgroup.procs: No such file or directory
08-04 11:12:52.921  1044  1569 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-04 11:12:52.929  5583  5583 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-04 11:12:52.929  5583  5583 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 11:12:53.004  1044  2000 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6664 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 11:12:53.006  1044  1586 I ActivityManager: Killing 5583:com.lge.qremote/u0a112 (adj 15): empty #17
,08-04 11:12:53.041  1044  1059 W libprocessgroup: failed to open /acct/uid_10112/pid_5583/cgroup.procs: No such file or directory
08-04 11:12:53.096  6664  6664 D UEI.SmartControl: Quickset Services start...
08-04 11:12:53.098  6664  6664 I UEI.SmartControl: Manufacture = LGE
08-04 11:12:53.098  6664  6664 D UEI.SmartControl: Id = LGNevo
08-04 11:12:53.099  6664  6664 D UEI.SmartControl: File observer start...
08-04 11:12:53.100  6664  6664 E UEI.SmartControl: IR Port is disabled: false
08-04 11:12:53.100  6664  6664 D UEI.SmartControl: Starting file observer...
08-04 11:12:53.100  6664  6664 D UEI.SmartControl: Extracting JNI libs...
08-04 11:12:53.100  6664  6664 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-04 11:12:53.106  1044  1127 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +996ms (total +1s96ms)
,08-04 11:12:53.107  6547  6547 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@225e13f6 time:118449
08-04 11:12:53.107  1044  1127 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f1d823 u0 com.test.thalitest/.MainActivity t40} time:118449
08-04 11:12:53.217  6547  6547 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 11:12:53.225  6664  6664 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-04 11:12:53.225  6664  6664 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-04 11:12:53.225  6664  6664 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-04 11:12:53.254  6664  6664 I UEI.SmartControl: --- Selecting new region: 6
08-04 11:12:53.255  6664  6664 I UEI.SmartControl: Model = LG-D855
08-04 11:12:53.257  6664  6664 D UEI.SmartControl: QS Service created
,08-04 11:12:53.266  6664  6664 I UEI.SmartControl: Service initServices...
08-04 11:12:53.271  6664  6664 D UEI.SmartControl: QS start get config
08-04 11:12:53.273  6547  6547 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-04 11:12:53.273  6547  6547 I chromium: 
08-04 11:12:53.296  6547  6646 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-04 11:12:53.296  6547  6646 I chromium: 
,08-04 11:12:53.316  6664  6664 D UEI.SmartControl: Loading JNI Libs...
,08-04 11:12:53.424  6547  6697 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,08-04 11:12:53.437   343   374 E GBMv2   : DFP En is all cleared set to be enabled
08-04 11:12:53.438   343   374 E GBMv2   : Set value is all cleared set the max
08-04 11:12:53.438   343   374 I GBMv2   : DFP Enabled. Ignore VFP set
08-04 11:12:53.438  6547  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 11:12:53.438  6547  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 11:12:53.438  6547  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 11:12:53.438  6547  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 11:12:53.438  6547  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-04 11:12:53.438  6547  6697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6eb6da added. We now have 1 listener(s)
,08-04 11:12:53.441  1044  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:12:53.444  6547  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-04 11:12:53.445  6547  6697 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:12:53.449  6547  6697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:12:53.450  6547  6697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 11:12:53.468  6547  6697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13058801 added. We now have 1 listener(s)
,08-04 11:12:53.469  6547  6697 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:12:53.475  1044  1537 D WifiService: New client listening to asynchronous messages
08-04 11:12:53.479  6547  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:12:53.479  6547  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 11:12:53.480  6547  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 11:12:53.480  6547  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 11:12:53.480  6547  6697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-04 11:12:53.483  6547  6697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:12:53.483  1044  1911 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:12:53.484  6547  6697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-04 11:12:53.490  6547  6697 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 11:12:53.490  6547  6697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:12:53.490  6547  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:12:53.490  6547  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:12:53.490  6547  6697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:12:53.490  6547  6697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:12:53.490  6547  6697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:12:53.490  6547  6697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:12:53.490  6547  6697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:12:53.490  6547  6697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 11:12:53.491  6547  6697 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:12:53.491  6547  6697 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 11:12:53.492  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:12:53.493  6547  6547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:12:53.524  6547  6547 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 11:12:53.637  6664  6664 I UEI.SmartControl: Supports setup maps: true
08-04 11:12:53.643  6664  6664 D UEI.SmartControl: QS start statue = true Error code = 0
08-04 11:12:53.643  6664  6664 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-04 11:12:53.643  6664  6664 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-04 11:12:53.643  6664  6664 I UEI.SmartControl: ### init IR Blaster...
,08-04 11:12:53.650  6664  6664 D serial_port: Configuring serial port
08-04 11:12:53.655  6664  6664 E UEI.SmartControl: UEIBLaster setting for 616
08-04 11:12:53.655  6664  6664 I UEI.SmartControl: Setting serial record hearder size = 2
08-04 11:12:53.655  6664  6664 I UEI.SmartControl: configuring settings for MAXQ616
08-04 11:12:53.656  6664  6664 I UEI.SmartControl: Get version...
08-04 11:12:53.676  6664  6706 D UEI.SmartControl: serial port data available: 21
,08-04 11:12:53.704  6664  6664 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-04 11:12:53.704  6664  6664 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-04 11:12:53.704  6664  6664 I UEI.SmartControl: QS saving settings...
08-04 11:12:53.705  6664  6664 D UEI.SmartControl: IR Blaster version: 25672567
,08-04 11:12:53.721  6664  6706 D UEI.SmartControl: serial port data available: 4
,08-04 11:12:53.759  6664  6709 I UEI.SmartControl: Device manager: loading config....
08-04 11:12:53.760  6664  6709 D UEI.SmartControl: ----------- loading internal config...
08-04 11:12:53.761  6664  6664 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-04 11:12:53.763  6664  6664 E UEI.SmartControl: Services init done
08-04 11:12:53.764  6664  6664 D UEI.SmartControl: QS Service init finished
,08-04 11:12:53.769  6664  6664 D UEI.SmartControl: QS Service version name: 2.1.91
08-04 11:12:53.769  6664  6664 D UEI.SmartControl: QS Service version code: 201091
08-04 11:12:53.771  6664  6664 D UEI.SmartControl: Service requested: Control
08-04 11:12:53.775  6664  6709 E UEI.SmartControl: Loading SETTINGS...
08-04 11:12:53.776  6664  6664 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-04 11:12:53.782  1044  1981 I ActivityManager: Killing 5815:com.google.android.talk/u0a72 (adj 15): empty #17
08-04 11:12:53.785  6664  6709 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-04 11:12:53.793  6664  6708 I UEI.SmartControl: Notify AllClients services are ready: 0
08-04 11:12:53.793  6664  6708 D UEI.SmartControl: -----service ready thread exits
,08-04 11:12:53.920  6664  6664 D UEI.SmartControl: Internal service binding...
08-04 11:12:53.920  1044  2023 W libprocessgroup: failed to open /acct/uid_10072/pid_5815/cgroup.procs: No such file or directory
,08-04 11:12:54.627  6547  6700 W jxcore-log: Initializing JXcore engine
08-04 11:12:54.627  6547  6700 W jxcore-log: JXcore engine is ready
,08-04 11:12:54.662  6700  6700 W Thread-752: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7626]" dev="sockfs" ino=7626 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-04 11:12:54.662  6700  6700 W Thread-752: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-04 11:12:54.662  6700  6700 W Thread-752: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8504]" dev="sockfs" ino=8504 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-04 11:12:54.662  6700  6700 W Thread-752: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-04 11:12:54.662  6700  6700 W Thread-752: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30114]" dev="sockfs" ino=30114 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-04 11:12:54.682  6547  6700 W jxcore-log: Starting JXcore engine
,08-04 11:12:54.780  6547  6700 W jxcore-log: Platform android
08-04 11:12:54.780  6547  6700 W jxcore-log: 
08-04 11:12:54.780  6547  6700 W jxcore-log: Process ARCH arm
08-04 11:12:54.780  6547  6700 W jxcore-log: 
,08-04 11:12:55.156  6547  6700 I jxcore-log: JXcore Cordova bridge is ready!
08-04 11:12:55.156  6547  6700 I jxcore-log: 
08-04 11:12:55.156  6547  6700 W jxcore-log: JXcore engine is started
,08-04 11:12:55.160  6547  6697 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 11:12:55.162  6547  6547 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-04 11:12:56.195  6506  6506 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-04 11:12:56.197  1044  1060 I ActivityManager: Killing 6227:com.android.calendar/u0a13 (adj 15): empty #17
,08-04 11:12:56.289  1044  2026 W libprocessgroup: failed to open /acct/uid_10013/pid_6227/cgroup.procs: No such file or directory
,08-04 11:12:57.180  6506  6564 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-04 11:12:58.768  6664  6710 D UEI.SmartControl: Internal timer expired: 1
08-04 11:12:58.768  6664  6710 D UEI.SmartControl: unbind internal service
,08-04 11:12:58.779  6664  6664 D UEI.SmartControl: Service.onUnbind: IControl
08-04 11:12:58.780  6664  6664 D UEI.SmartControl: Service.onDestroy
08-04 11:12:58.780  6664  6664 D UEI.SmartControl: Lock is in USE false
08-04 11:12:58.780  6664  6664 D UEI.SmartControl: unbind internal service
08-04 11:12:58.782  6664  6664 D serial_port: close(fd = 25)
,08-04 11:12:58.790  6664  6664 I UEI.SmartControl: Serial port is closed.
08-04 11:12:58.790  6664  6664 I UEI.SmartControl: Serial port is closed.
08-04 11:12:58.790  6664  6664 D UEI.SmartControl: Blaster closed
08-04 11:12:58.790  6664  6664 D UEI.SmartControl: Shut down QS...
08-04 11:12:58.791  6664  6664 D UEI.SmartControl: Stopping QS lib
08-04 11:12:58.791  6664  6664 D UEI.SmartControl: QS lib stop result = true
08-04 11:12:58.791  6664  6664 D UEI.SmartControl: Stopped QS lib
08-04 11:12:58.792  6664  6664 D UEI.SmartControl: Stopped file observer...
08-04 11:12:58.792  6664  6664 D UEI.SmartControl: QS shutdown complete
08-04 11:12:59.879  1811  2332 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-04 11:12:59.884   324  6726 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 11:12:59.884   324  6726 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-04 11:12:59.884   324  6726 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-04 11:13:00.000  1044  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=812394971, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,08-04 11:13:00.041  4461  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-04 11:13:00.044  1598  1598 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-04 11:13:00.044  1598  1598 I KeyguardUpdateMonitor: called onTimeUpdated()
08-04 11:13:00.044  1598  1598 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-04 11:13:00.044  1598  1598 I [SystemUI]Clock: called onTimeUpdated()
08-04 11:13:00.044  1598  1598 I LgeClockWidgetControlView: called onTimeUpdated()
08-04 11:13:00.044  1598  1598 I [SystemUI]DateView: called onTimeUpdated()
08-04 11:13:00.045  1598  1598 I [SystemUI]DateView: called onTimeUpdated()
08-04 11:13:00.045  1598  1598 D KeyguardUpdateMonitor: handleTimeUpdate
08-04 11:13:00.047  2673  2673 D [Concierge]Service: onStartCommand(). Type : 9
08-04 11:13:00.093  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=812394971 [*alarm*], flags=0x0
,08-04 11:13:00.174  1811  1811 I ConfigFetchService: fetch service done; releasing wakelock
,08-04 11:13:00.174  1811  1811 I ConfigFetchService: stopping self
08-04 11:13:00.178  2149  2149 I ConfigService: onDestroy
,08-04 11:13:02.846  1598  1598 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-04 11:13:02.847  1598  1598 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-04 11:13:02.863  1044  1537 D WifiController: battery changed pluggedType: 2
,08-04 11:13:02.866  1598  1598 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-04 11:13:02.866  1598  1598 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-04 11:13:02.869  1935  2084 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-04 11:13:02.869  1935  2084 D LEDHandler: Battery Level Remaining: 100%
08-04 11:13:02.869  1935  2084 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-04 11:13:02.871  1598  1598 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-04 11:13:02.878  3868  3981 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-04 11:13:02.884  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:13:02.884  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:13:02.884  1598  1598 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-04 11:13:02.885  1598  1598 I [SystemUI]LGPowerUI: On Skip Timer : true
08-04 11:13:02.886  6621  6621 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 11:13:04.964  1044  1117 I ActivityManager: Waited long enough for: ServiceRecord{52f06a8 u0 com.google.android.gms/.wearable.service.WearableService}
,08-04 11:13:08.572  6547  6700 E jxcore  : Error!: Cannot find module '../thalilogger'
08-04 11:13:08.572  6547  6700 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-04 11:13:08.582  6547  6547 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
08-04 11:13:08.582  6547  6547 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-04 11:13:08.592  1044  2026 I ActivityManager: Killing 6199:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-04 11:13:08.611  6547  6697 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
08-04 11:13:08.611  1044  2000 W libprocessgroup: failed to open /acct/uid_10014/pid_6199/cgroup.procs: No such file or directory
,08-04 11:13:08.615  6547  6547 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-04 11:13:08.615  6547  6547 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-04 11:13:08.616  6547  6547 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:13:08.616  6547  6547 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:13:08.616  6547  6547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:13:08.616  6547  6547 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:13:08.616  6547  6547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6eb6da removed from the list
08-04 11:13:08.616  6547  6547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:13:08.616  6547  6547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13058801 removed from the list
08-04 11:13:08.616  6547  6547 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:13:08.616  6547  6547 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-04 11:13:08.632   343   372 E GBMv2   : DFP En is all cleared set to be enabled
,08-04 11:13:08.637  1935  1951 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-04 11:13:08.637  1935  1951 D SplitWindowPolicy: topRunningActivity=ActivityInfo{232bd8bb co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-04 11:13:08.638  6547  6547 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-04 11:13:08.638  1935  1952 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-04 11:13:08.639  1935  1952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{315671d8 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-04 11:13:08.641  6547  6547 W ScreenOrientationListener: Removing an inexistent observer!
08-04 11:13:08.646  2027  2027 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-04 11:13:08.647  2027  2027 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-04 11:13:08.648  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-04 11:13:08.650  2027  2120 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-04 11:13:08.654  2027  2027 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-04 11:13:08.655  2027  2027 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-04 11:13:08.659  1899  1899 D ActionManagerService: notifyUserLog: 1000003
08-04 11:13:08.660  2027  2027 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-04 11:13:08.661  3821  4460 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-04 11:13:08.675  1044  1586 D InputDispatcher: Window went away: Window{3c34d1fe u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-04 11:13:08.712  1044  1117 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6753 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:13:08.721  2027  2027 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-04 11:13:08.728  1899  1899 D ActionManagerService: notifyUserLog: 1000004
08-04 11:13:08.729  2027  2027 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-04 11:13:08.730  3821  4460 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-04 11:13:08.730  3821  3836 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , create_time: 1430832262123
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , expire_time: 0
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , display: false
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , animation: false }
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , create_time: 1430832262287
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , expire_time: 0
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , display: false
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , animation: false }
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , create_time: 1469801565454
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , expire_time: 0
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , display: false
08-04 11:13:08.732  2027  2027 I GBoardWebViewUtils: , animation: false }
08-04 11:13:08.747  2027  6778 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-04 11:13:08.767  2027  2027 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-04 11:13:08.789  6753  6753 I art     : Almond Protected OAT
,08-04 11:13:08.800  6751  6751 D AndroidRuntime: 
08-04 11:13:08.800  6751  6751 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-04 11:13:08.803  6751  6751 D AndroidRuntime: CheckJNI is OFF
,08-04 11:13:08.848  2027  2027 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-04 11:13:08.909  6751  6751 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 11:13:08.911  1044  1731 I art     : Explicit concurrent mark sweep GC freed 20831(1138KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.655ms total 73.321ms
08-04 11:13:08.912  6753  6753 D WeatherApplication: removeAccount
08-04 11:13:08.914  6753  6753 D WeatherApplication: Account.length = 0
08-04 11:13:08.914  6753  6753 E WeatherApplication: OPERATOR:OPEN
08-04 11:13:08.922  6753  6753 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 11:13:8
,08-04 11:13:08.924  1044  1117 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-04 11:13:08.925  1044  1117 I ActivityManager: Killing 6547:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
08-04 11:13:08.927  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-04 11:13:08.930  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:13:08.932  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-04 11:13:08.934  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-04 11:13:08.936  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,08-04 11:13:08.937  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-04 11:13:08.938  6753  6753 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 11:13:08.938  6753  6753 D Weather.Utils: 2 : All the weather widget is gone.
08-04 11:13:08.940  6753  6753 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:13:08.957  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-04 11:13:08.957  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-04 11:13:08.958  2027  5750 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,08-04 11:13:08.958  2027  5750 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-04 11:13:08.964  1044  1537 D WifiService: Client connection lost with reason: 4
08-04 11:13:08.973  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-04 11:13:08.974  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-04 11:13:08.974  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-04 11:13:08.991  6753  6753 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 11:13:08.991  6753  6753 D Weather.Utils: 2 : All the weather widget is gone.
08-04 11:13:08.992  6753  6753 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 11:13:8
08-04 11:13:09.001  2027  2027 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-04 11:13:09.036  1044  1731 W ActivityManager: Spurious death for ProcessRecord{13c77f9d 6547:com.test.thalitest/u0a118}, curProc for 6547: null
,08-04 11:13:09.037  1044  1132 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-04 11:13:09.065  2673  2673 D [Concierge]Service: onStartCommand(). Type : 8
08-04 11:13:09.065  2673  2673 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-04 11:13:09.068  2673  2673 D [Concierge]Service: Update widget ID : 11
08-04 11:13:09.070  1598  1598 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-04 11:13:09.073  2027  2027 D [Concierge]WidgetView: change position of spinner
08-04 11:13:09.075  3868  3868 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-04 11:13:09.075  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-04 11:13:09.076  1989  1989 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-04 11:13:09.078  2464  2580 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-04 11:13:09.079  3821  3821 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-04 11:13:09.082  1044  1127 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3b833925 u0 com.lge.launcher2/.Launcher t39} time:134424
08-04 11:13:09.108  4574  4574 I art     : Explicit concurrent mark sweep GC freed 463(31KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 443us total 59.253ms
,08-04 11:13:09.111  1044  1947 V SIM_STK : Menu title from STK is T-Mobile
08-04 11:13:09.129  2673  2673 D [Concierge]Service: onStartCommand(). Type : 0
,08-04 11:13:09.131  2027  2027 I [Concierge]WidgetView: initWebView(). Time : 1470301989131
08-04 11:13:09.132  4461  4461 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-04 11:13:09.132  4461  4461 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-04 11:13:09.132  4461  4461 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-04 11:13:09.132  4461  4461 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-04 11:13:09.132  4461  4461 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:13:09.132  4461  4461 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:13:09.132  4461  4461 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:13:09.132  4461  4461 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:13:09.132  4461  4461 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:13:09.132  4461  4461 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:13:09.132  4461  4461 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:13:09.132  4461  4461 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:13:09.133  1044  1044 D administrator: Handling package changes for user 0
08-04 11:13:09.138  1044  1419 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-04 11:13:09.148  1598  1598 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-04 11:13:09.148  1598  1661 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 11:13:09.148  1598  1661 D KeyguardModel: createShortcutInfo...
,08-04 11:13:09.155  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-04 11:13:09.159  1598  1661 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 11:13:09.159  1598  1661 D KeyguardModel: createShortcutInfo...
08-04 11:13:09.173  1598  1661 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-04 11:13:09.174  1598  1661 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 11:13:09.175  1811  1811 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-04 11:13:09.176  1598  1661 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-04 11:13:09.181  1598  1661 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-04 11:13:09.182  1598  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:09.182  1598  1661 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-04 11:13:09.183  2027  2027 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 876087662
08-04 11:13:09.183  2027  2027 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-04 11:13:09.183  2027  2027 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-04 11:13:09.187  2027  2027 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1e747e6d
08-04 11:13:09.187  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-04 11:13:09.189  2027  2027 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-04 11:13:09.189  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:13:09.195  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-04 11:13:09.196  2149  2149 I ConfigService: onCreate
08-04 11:13:09.196  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 11:13:09.196  2149  2149 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-04 11:13:09.197  2027  2027 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-04 11:13:09.198  1598  1661 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-04 11:13:09.198  1598  1661 D KeyguardModel: createShortcutInfo...
,08-04 11:13:09.202  2149  2149 I ConfigService: onBind returning update interface
08-04 11:13:09.205  1598  1598 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-04 11:13:09.205  1598  1598 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-04 11:13:09.205  2027  2027 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-04 11:13:09.206  1863  1863 D SplitUIManager: split_name #11 / not available #0
08-04 11:13:09.206  1863  1863 D SplitUIService: removed split : 
08-04 11:13:09.206  2027  2027 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470301882857, New one : 1470301989131
,08-04 11:13:09.206  2027  2027 D [Concierge]WidgetView: Unregister all receivers
08-04 11:13:09.207  2027  2027 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-04 11:13:09.207  2027  2027 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-04 11:13:09.207  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:13:09.207  2149  2149 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-04 11:13:09.207  2149  2149 I ConfigService: onBind returning config service
08-04 11:13:09.208  1811  1811 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-04 11:13:09.208  1598  1661 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-04 11:13:09.209  1598  1661 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 11:13:09.209  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-04 11:13:09.210  1598  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:09.210  1598  1661 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-04 11:13:09.210  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-04 11:13:09.212  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-04 11:13:09.213  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-04 11:13:09.214  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-04 11:13:09.218  1044  2026 V SIM_STK : Menu title from STK is T-Mobile
08-04 11:13:09.218  1044  2026 V SIM_STK : Menu title from STK is T-Mobile
08-04 11:13:09.223  1598  1661 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 11:13:09.224  1598  1661 D KeyguardModel: createShortcutInfo...
,08-04 11:13:09.226  1811  1811 I ConfigFetchService: service connected
08-04 11:13:09.226  1811  1811 I ConfigClient: service connected
08-04 11:13:09.232  2149  2149 I ConfigService: onDestroy
08-04 11:13:09.234  1598  1661 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:13:09.234  1598  1661 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-04 11:13:09.234  1598  1661 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-04 11:13:09.234  1598  1661 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-04 11:13:09.235  1598  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:09.235  1598  1661 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-04 11:13:09.240  1811  6800 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-04 11:13:09.242  1598  1661 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 11:13:09.242  1598  1661 D KeyguardModel: createShortcutInfo...
08-04 11:13:09.245  1863  1863 D SplitUIManager: split_name #11 / not available #0
08-04 11:13:09.245  1863  1863 I SplitUIService: split app #11
08-04 11:13:09.246  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:13:09.247  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:13:09.267  1598  1598 D KeyguardModel: handleShortcutListChanged...
08-04 11:13:09.267  1598  1598 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-04 11:13:09.272  1044  2000 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-04 11:13:09.272  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-04 11:13:09.272  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-04 11:13:09.272  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 11:13:09.272  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 11:13:09.272  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 11:13:09.272  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 11:13:09.273  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 11:13:09.273  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 11:13:09.273  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 11:13:09.273  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 11:13:09.273  3868  3868 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-04 11:13:09.274  1598  1661 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 11:13:09.274  1598  1661 D KeyguardModel: createShortcutInfo...
08-04 11:13:09.283  1598  1661 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 11:13:09.283  1598  1661 D KeyguardModel: createShortcutInfo...
08-04 11:13:09.284  1598  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:09.284  1598  1661 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-04 11:13:09.285  1598  1661 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-04 11:13:09.285  1598  1661 D KeyguardModel: createShortcutInfo...
08-04 11:13:09.285  1598  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:09.286  1598  1661 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-04 11:13:09.286  1598  1661 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 11:13:09.286  1598  1661 D KeyguardModel: createShortcutInfo...
,08-04 11:13:09.288  1598  1661 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:13:09.288  1598  1661 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-04 11:13:09.290  1598  1661 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 11:13:09.290  1598  1661 D KeyguardModel: createShortcutInfo...
08-04 11:13:09.290  2027  2027 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-04 11:13:09.299  2027  2027 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-04 11:13:09.299  2027  2027 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-04 11:13:09.312  1044  1731 V SIM_STK : Menu title from STK is T-Mobile
08-04 11:13:09.318  1811  6807 I PeopleContactsSync: CP2 sync disabled
,08-04 11:13:09.320  3200  6808 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-04 11:13:09.320   337   438 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-04 11:13:09.323  1598  1598 D KeyguardModel: handleShortcutListChanged...
08-04 11:13:09.323  1598  1598 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-04 11:13:09.323  2027  2027 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:13:09.328  1811  4706 I Icing   : doRemovePackageData com.test.thalitest
08-04 11:13:09.332  1044  1044 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-04 11:13:09.333  1044  1044 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 11:13:09.333  1044  1044 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-04 11:13:09.335  5909  6806 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-04 11:13:09.335  1044  1572 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-04 11:13:09.340  1044  1114 W InputMethodInfo: Duplicated subtype definition found: , voice
08-04 11:13:09.343  2027  2027 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-04 11:13:09.346  2027  2027 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17ecd0db time:134688
,08-04 11:13:09.348  5987  5987 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-04 11:13:09.351  1811  6805 W GmsApplication: Using Auth Proxy for data requests.
08-04 11:13:09.358  6471  6471 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-04 11:13:09.359  1811  6805 W GmsApplication: Using Auth Proxy for data requests.
08-04 11:13:09.391  2370  6809 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-04 11:13:09.397  1989  1989 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-04 11:13:09.397  1989  1989 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-04 11:13:09.398  1989  1989 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-04 11:13:09.400  6377  6377 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-04 11:13:09.430  1044  1059 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6813 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-04 11:13:09.480  2027  2027 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-04 11:13:09.489  1044  1132 I art     : Explicit concurrent mark sweep GC freed 22519(1666KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.872ms total 331.850ms
08-04 11:13:09.495  2123  2123 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-04 11:13:09.495  2123  2123 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-04 11:13:09.509  6751  6751 D AndroidRuntime: Shutting down VM
,08-04 11:13:09.521  2027  2938 I GBoardtInterface: onReloaded()
,08-04 11:13:09.523  2027  2027 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-04 11:13:09.524  3821  4458 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 11:13:09.526  3821  3837 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 11:13:09.548  1899  1899 D ActionManagerService: notifyUserLog: 1000001
,08-04 11:13:09.553  6813  6813 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-04 11:13:09.554  3821  4460 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-04 11:13:09.554  3821  4460 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-04 11:13:09.554  1899  1899 D ActionManagerService: notifyUserLog: 1000001
08-04 11:13:09.554  6813  6813 W LG Account v2.2: No ProfileInfo entries
08-04 11:13:09.554  6813  6813 I LG Account v2.2: isEnabled: false
08-04 11:13:09.554  6813  6813 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-04 11:13:09.554  6813  6813 I Feature : [Lifetracker]Country: EU
08-04 11:13:09.554  6813  6813 I Feature : [Lifetracker]Operator: OPEN
08-04 11:13:09.554  6813  6813 I Feature : [Lifetracker]Ranking support: false
08-04 11:13:09.554  6813  6813 I Feature : [Lifetracker]Comfort support: false
08-04 11:13:09.554  6813  6813 I Feature : [Lifetracker]Accessory: true
08-04 11:13:09.554  6813  6813 I Feature : [Lifetracker]Health device: true
08-04 11:13:09.555  6813  6813 I Feature : [Lifetracker]Extra Pedometer: false
08-04 11:13:09.555  6813  6813 I Feature : [Lifetracker]Blood glucose device: false
08-04 11:13:09.555  6813  6813 I Feature : [Lifetracker]Device Number: 3
08-04 11:13:09.555  6813  6813 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-04 11:13:09.556  3821  3837 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 11:13:09.557  3821  4460 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-04 11:13:09.557  3821  4460 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-04 11:13:09.557  3821  4460 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-04 11:13:09.557  3821  4460 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-04 11:13:09.584  1044  1953 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6834 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 11:13:09.587  1044  1953 I ActivityManager: Killing 2123:com.lge.music/u0a34 (adj 15): empty #17
08-04 11:13:09.596   328   328 V AudioFlinger: 2123 died, releasing its sessions
08-04 11:13:09.596   328   328 V AudioFlinger:  pid 1846 @ 0
08-04 11:13:09.596   328   328 V AudioFlinger:  pid 3388 @ 1
08-04 11:13:09.596   328   328 V AudioFlinger:  pid 3388 @ 2
,08-04 11:13:09.611  1044  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 11:13:09.615  1044  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-04 11:13:09.617  1044  1884 W libprocessgroup: failed to open /acct/uid_10034/pid_2123/cgroup.procs: No such file or directory
08-04 11:13:09.621  2027  2027 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-04 11:13:09.621  2027  2027 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-04 11:13:09.623  2027  2027 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-04 11:13:09.623  2027  2027 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,08-04 11:13:09.625  2027  2027 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-04 11:13:09.625  2027  2027 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-04 11:13:09.628  2027  2027 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-04 11:13:09.640  6834  6834 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:13:09.640  6834  6834 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-04 11:13:09.640  6834  6834 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 11:13:09.641  6834  6834 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-04 11:13:09.641  6834  6834 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 11:13:09.642  6834  6834 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-04 11:13:09.712  6834  6834 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-04 11:13:09.719  6834  6834 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-04 11:13:09.719  6834  6834 D HideNavigationAppsReceiver: replacing : false
08-04 11:13:09.720  6834  6834 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-04 11:13:09.722  6834  6834 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-04 11:13:09.722  6834  6834 D ButtonCombinationReceiver: replacing : false
,08-04 11:13:09.733  1044  1882 I ActivityManager: Killing 6435:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-04 11:13:09.829  1044  2000 W libprocessgroup: failed to open /acct/uid_10008/pid_6435/cgroup.procs: No such file or directory
,08-04 11:13:09.832  4574  6852 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-04 11:13:09.862  1044  1981 V SIM_STK : Menu title from STK is T-Mobile
,08-04 11:13:09.868  1044  2026 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6853 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 11:13:09.868  4574  6852 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-04 11:13:09.870  2027  2938 I GBoardtInterface: exportHTML()
,08-04 11:13:09.899  2027  2938 I GBoardtInterface: exportHTML()
--------- beginning of crash
08-04 11:13:09.899  4574  6852 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-04 11:13:09.899  4574  6852 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4574
08-04 11:13:09.899  4574  6852 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at csx.d(PG:186)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at cun.g(PG:594)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at cuy.ub(PG:301)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:13:09.899  4574  6852 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:13:09.904  4574  6852 I Process : Sending signal. PID: 4574 SIG: 9
,08-04 11:13:09.907  1044  6873 E DropBoxManagerService: Can't write: system_app_crash
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-04 11:13:09.907  1044  6873 E DropBoxManagerService: 	... 5 more
08-04 11:13:09.918  1044  1537 D WifiService: Client connection lost with reason: 4
,08-04 11:13:09.926  2027  2938 I GBoardtInterface: exportHTML()
08-04 11:13:09.927  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
08-04 11:13:09.957  1044  1884 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 4574) has died
,08-04 11:13:09.959  1044  1884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
08-04 11:13:09.959  1044  1884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
08-04 11:13:09.967  6120  6120 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-04 11:13:09.967  6120  6120 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-04 11:13:09.967  6120  6120 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-04 11:13:09.967  6120  6120 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-04 11:13:09.967  6120  6120 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-04 11:13:09.968  6120  6120 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:13:09.978  6853  6876 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-04 11:13:09.979  6853  6876 E AndroidRuntime: Process: com,.android.keychain, PID: 6853
08-04 11:13:09.979  6853  6876 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:13:09.979  6853  6876 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:13:09.982  6853  6876 I Process : Sending signal. PID: 6853 SIG: 9
08-04 11:13:09.983  6621  6621 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: Can't write: system_app_crash
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-04 11:13:09.983  1044  6878 E DropBoxManagerService: 	... 5 more
08-04 11:13:09.997  6834  6834 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-04 11:13:10.030  1044  1060 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6880 uid=10060 gids={50060, 9997, 1028, 4002} abi=armeabi-v7a
08-04 11:13:10.043   359   359 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 13.165ms
,08-04 11:13:10.057   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 276us total 12.764ms
08-04 11:13:10.067  1044  2026 I ActivityManager: Process com.android.keychain (pid 6853) has died
,08-04 11:13:10.067  1044  2026 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10891ms
,08-04 11:13:10.070   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 381us total 11.890ms
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1388)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:13:10.114  6880  6880 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)

```
