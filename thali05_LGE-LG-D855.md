#### Test 79689775e33639d_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-03 17:25:29.262  6552  6552 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-03 17:25:29.822   326   405 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 17:25:29.822  3205  6575 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-03 17:25:30.091  1801  4782 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-03 17:25:30.153  1801  4782 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-03 17:25:30.205  1801  4782 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-03 17:25:30.282  6552  6552 D LgDataFeature: LgDataFeature() Constructor: none
08-03 17:25:30.282  6552  6552 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 17:25:30.473  6114  6114 I LockScreenSettings: New app installed broadcast received ..
08-03 17:25:30.481  6576  6576 D AndroidRuntime: 
08-03 17:25:30.481  6576  6576 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-03 17:25:30.485  6576  6576 D AndroidRuntime: CheckJNI is OFF
08-03 17:25:30.495  6552  6552 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-03 17:25:30.497  6114  6114 I LockScreenSettings: Number of installed packages  1
08-03 17:25:30.549  1034  1559 V SIM_STK : Menu title from STK is T-Mobile
--------- beginning of system
08-03 17:25:30.619  1034  1765 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6605 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 17:25:30.628  6576  6576 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-03 17:25:30.633  1034  1050 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 17:25:30.649  1926  3931 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-03 17:25:30.653  1034  1050 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-03 17:25:30.655  1034  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{d78fccd #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 17:25:30.655  1034  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{d78fccd #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 17:25:30.657  1034  1050 D WindowStateEx: AppWindowTokenEx init.. 
08-03 17:25:30.657   335   343 E GBMv2   : DFP En is all cleared set to be enabled
08-03 17:25:30.704  1034  1050 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6626 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-03 17:25:30.709  6576  6576 D AndroidRuntime: Shutting down VM
08-03 17:25:30.757  1926  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-03 17:25:30.758  1926  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2866aa5d co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 17:25:30.759  1926  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-03 17:25:30.760  1926  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1c8d0fd2 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 17:25:30.770  6605  6605 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-03 17:25:30.772  6605  6605 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-03 17:25:30.831  1034  1765 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6643 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-03 17:25:30.832  1034  1765 I ActivityManager: Killing 5861:com.google.android.talk/u0a72 (adj 15): empty #17
08-03 17:25:30.868  1034  2016 W libprocessgroup: failed to open /acct/uid_10072/pid_5861/cgroup.procs: No such file or directory
08-03 17:25:30.877  6626  6626 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-03 17:25:30.932  6643  6643 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-03 17:25:30.954  6643  6643 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 17:25:30.955  6626  6626 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-03 17:25:30.956  6414  6414 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-03 17:25:30.962  6626  6626 I LibraryLoader: Loading: webviewchromium
08-03 17:25:30.965  6626  6626 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1614-1617)
08-03 17:25:30.965  6626  6626 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 17:25:30.984  6626  6626 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e4f9113}
08-03 17:25:30.985  6626  6626 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 17:25:30.986  6626  6626 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 17:25:30.995  6626  6626 I BrowserStartupController: Initializing chromium process, renderers=0
08-03 17:25:30.996  6626  6626 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 17:25:31.002  1034  1050 I ActivityManager: Killing 5673:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-03 17:25:31.006  6626  6626 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 17:25:31.007  6626  6626 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-03 17:25:31.007  6626  6626 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-03 17:25:31.015   313  1369 V AudioPolicyService: registerClient() client 0xb57f56c0, uid 10118
08-03 17:25:31.020  1034  1116 D BluetoothManagerService: Message: 20
08-03 17:25:31.020  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@188186da:true
08-03 17:25:31.022  5648  5648 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 17:25:31.023  5648  5648 W System.err: android.os.DeadObjectException
08-03 17:25:31.023  5648  5648 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 17:25:31.023  5648  5648 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 17:25:31.023  5648  5648 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 17:25:31.023  5648  5648 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 17:25:31.023  5648  5648 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 17:25:31.023  5648  5648 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 17:25:31.023  5648  5648 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 17:25:31.023  5648  5648 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 17:25:31.023  5648  5648 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 17:25:31.023  5648  5648 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 17:25:31.023  5648  5648 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 17:25:31.023  5648  5648 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 17:25:31.023  5648  5648 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 17:25:31.023  5648  5648 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 17:25:31.023  5648  5648 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 17:25:31.024  5648  5648 W System.err: android.os.DeadObjectException
08-03 17:25:31.024  5648  5648 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 17:25:31.024  5648  5648 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 17:25:31.024  5648  5648 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 17:25:31.024  5648  5648 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 17:25:31.024  5648  5648 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 17:25:31.024  5648  5648 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 17:25:31.024  5648  5648 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 17:25:31.024  5648  5648 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 17:25:31.024  5648  5648 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 17:25:31.024  5648  5648 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 17:25:31.024  5648  5648 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 17:25:31.024  5648  5648 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 17:25:31.024  5648  5648 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 17:25:31.024  5648  5648 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 17:25:31.024  5648  5648 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 17:25:31.025  5648  5648 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-03 17:25:31.031  6626  6626 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 17:25:31.031  6626  6626 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 17:25:31.031  6626  6626 I Adreno-EGL: Build Date: 12/12/14 금
08-03 17:25:31.031  6626  6626 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 17:25:31.031  6626  6626 I Adreno-EGL: Remote Branch: 
08-03 17:25:31.031  6626  6626 I Adreno-EGL: Local Patches: 
08-03 17:25:31.031  6626  6626 I Adreno-EGL: Reconstruct Branch: 
08-03 17:25:31.214  1034  1765 W libprocessgroup: failed to open /acct/uid_1000/pid_5673/cgroup.procs: No such file or directory
08-03 17:25:31.214  1034  1765 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-03 17:25:31.217  5648  5648 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 17:25:31.217  5648  5648 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 17:25:31.257  1034  1112 W ActivityManager: Activity pause timeout for ActivityRecord{2d184982 u0 com.test.thalitest/.MainActivity t40}
08-03 17:25:31.302  1034  1907 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6682 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 17:25:31.303  5648  5648 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 17:25:31.333  6626  6673 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-03 17:25:31.337  6626  6626 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-03 17:25:31.358  6626  6626 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 17:25:31.362  6626  6626 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-03 17:25:31.365  6626  6626 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-03 17:25:31.367  6626  6626 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-03 17:25:31.367  6626  6626 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-03 17:25:31.379  6626  6626 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-03 17:25:31.387  6626  6626 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 17:25:31.387  6626  6626 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 17:25:31.397  6682  6682 D UEI.SmartControl: Quickset Services start...
08-03 17:25:31.404  6682  6682 I UEI.SmartControl: Manufacture = LGE
08-03 17:25:31.404  6682  6682 D UEI.SmartControl: Id = LGNevo
08-03 17:25:31.405  6682  6682 D UEI.SmartControl: File observer start...
08-03 17:25:31.405  6682  6682 E UEI.SmartControl: IR Port is disabled: false
08-03 17:25:31.405  6682  6682 D UEI.SmartControl: Starting file observer...
08-03 17:25:31.405  6682  6682 D UEI.SmartControl: Extracting JNI libs...
08-03 17:25:31.406  6682  6682 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 17:25:31.424  6626  6711 D OpenGLRenderer: Render dirty regions requested: true
08-03 17:25:31.425  6626  6711 I OpenGLRenderer: Initialized EGL, version 1.4
08-03 17:25:31.432  6626  6711 D OpenGLRenderer: Enabling debug mode 0
08-03 17:25:31.440  6626  6626 D Atlas   : Validating map...
08-03 17:25:31.445  1034  2017 D SplitWindow: check instance of lgWin Window{30565c73 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 17:25:31.485  6626  6708 D LgDataFeature: LgDataFeature() Constructor: none
08-03 17:25:31.485  6626  6708 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 17:25:31.519  6682  6682 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 17:25:31.519  6682  6682 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 17:25:31.519  6682  6682 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-03 17:25:31.557  6682  6682 I UEI.SmartControl: --- Selecting new region: 6
08-03 17:25:31.559  6682  6682 I UEI.SmartControl: Model = LG-D855
08-03 17:25:31.561  6682  6682 D UEI.SmartControl: QS Service created
08-03 17:25:31.576  6682  6682 I UEI.SmartControl: Service initServices...
08-03 17:25:31.581  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +824ms (total +923ms)
08-03 17:25:31.581  6682  6682 D UEI.SmartControl: QS start get config
08-03 17:25:31.581  6626  6626 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@26b146fe time:132233
08-03 17:25:31.582  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d184982 u0 com.test.thalitest/.MainActivity t40} time:132234
08-03 17:25:31.627  6682  6682 D UEI.SmartControl: Loading JNI Libs...
08-03 17:25:31.705  6626  6626 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-03 17:25:31.705  6626  6626 I chromium: 
,08-03 17:25:31.742  6626  6626 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 17:25:31.904  6626  6722 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-03 17:25:31.918  6626  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 17:25:31.918  6626  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 17:25:31.918  6626  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 17:25:31.918  6626  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 17:25:31.918  6626  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-03 17:25:31.918  6626  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2384fb62 added. We now have 1 listener(s)
,08-03 17:25:31.923  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 17:25:31.926  6626  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-03 17:25:31.928  6626  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 17:25:31.930  6626  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 17:25:31.930  6626  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 17:25:31.937  6626  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b7fdc29 added. We now have 1 listener(s)
08-03 17:25:31.938  6626  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 17:25:31.942  1034  1528 D WifiService: New client listening to asynchronous messages
,08-03 17:25:31.952  6626  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 17:25:31.953  6626  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 17:25:31.956  6626  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 17:25:31.956  6626  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 17:25:31.956  6626  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-03 17:25:31.959  6626  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 17:25:31.960  1034  1765 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 17:25:31.961  6626  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-03 17:25:31.967  6626  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 17:25:31.968  6626  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 17:25:31.968  6626  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 17:25:31.968  6626  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 17:25:31.968  6626  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 17:25:31.968  6626  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 17:25:31.968  6626  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 17:25:31.968  6626  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 17:25:31.968  6626  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 17:25:31.968  6626  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 17:25:31.968  6626  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 17:25:31.969  6682  6682 I UEI.SmartControl: Supports setup maps: true
08-03 17:25:31.970  6626  6626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 17:25:31.972  6626  6626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 17:25:31.972  6626  6722 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 17:25:31.972  6682  6682 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 17:25:31.972  6682  6682 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 17:25:31.972  6682  6682 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 17:25:31.972  6682  6682 I UEI.SmartControl: ### init IR Blaster...
08-03 17:25:31.977  6682  6682 D serial_port: Configuring serial port
08-03 17:25:31.986  6682  6682 E UEI.SmartControl: UEIBLaster setting for 616
08-03 17:25:31.986  6682  6682 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 17:25:31.987  6682  6682 I UEI.SmartControl: configuring settings for MAXQ616
08-03 17:25:31.987  6682  6682 I UEI.SmartControl: Get version...
,08-03 17:25:32.002  6626  6708 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-03 17:25:32.002  6626  6708 I chromium: 
,08-03 17:25:32.009  6682  6726 D UEI.SmartControl: serial port data available: 21
08-03 17:25:32.036  6682  6682 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 17:25:32.036  6682  6682 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 17:25:32.036  6682  6682 I UEI.SmartControl: QS saving settings...
,08-03 17:25:32.040  6682  6682 D UEI.SmartControl: IR Blaster version: 25672567
08-03 17:25:32.056  6626  6626 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-03 17:25:32.056  6682  6726 D UEI.SmartControl: serial port data available: 4
,08-03 17:25:32.088  6682  6729 I UEI.SmartControl: Device manager: loading config....
08-03 17:25:32.088  6682  6729 D UEI.SmartControl: ----------- loading internal config...
08-03 17:25:32.089  6682  6682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-03 17:25:32.091  6682  6682 E UEI.SmartControl: Services init done
08-03 17:25:32.091  6682  6682 D UEI.SmartControl: QS Service init finished
08-03 17:25:32.094  6682  6682 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 17:25:32.094  6682  6682 D UEI.SmartControl: QS Service version code: 201091
08-03 17:25:32.094  6682  6682 D UEI.SmartControl: Service requested: Control
08-03 17:25:32.097  6682  6729 E UEI.SmartControl: Loading SETTINGS...
08-03 17:25:32.100  6682  6682 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 17:25:32.101  1034  1770 I ActivityManager: Killing 5648:com.lge.qremote/u0a112 (adj 15): empty #17
,08-03 17:25:32.108  6682  6729 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 17:25:32.127  6682  6728 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-03 17:25:32.127  6682  6728 D UEI.SmartControl: -----service ready thread exits
08-03 17:25:32.140   335   345 E GBMv2   : DFP En is all cleared set to be enabled
,08-03 17:25:32.140   335   345 E GBMv2   : Set value is all cleared set the max
,08-03 17:25:32.140   335   345 I GBMv2   : DFP Enabled. Ignore VFP set
08-03 17:25:32.199  1034  1944 W libprocessgroup: failed to open /acct/uid_10112/pid_5648/cgroup.procs: No such file or directory
,08-03 17:25:32.202  6682  6682 D UEI.SmartControl: Internal service binding...
08-03 17:25:32.785  6626  6725 W jxcore-log: Initializing JXcore engine
08-03 17:25:32.785  6626  6725 W jxcore-log: JXcore engine is ready
,08-03 17:25:32.813  6725  6725 W Thread-762: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8574]" dev="sockfs" ino=8574 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-03 17:25:32.813  6725  6725 W Thread-762: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-03 17:25:32.813  6725  6725 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9941]" dev="sockfs" ino=9941 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-03 17:25:32.813  6725  6725 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-03 17:25:32.813  6725  6725 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32991]" dev="sockfs" ino=32991 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-03 17:25:32.837  6626  6725 W jxcore-log: Starting JXcore engine
08-03 17:25:32.996  6626  6725 W jxcore-log: Platform android
08-03 17:25:32.996  6626  6725 W jxcore-log: 
08-03 17:25:32.996  6626  6725 W jxcore-log: Process ARCH arm
08-03 17:25:32.996  6626  6725 W jxcore-log: 
,08-03 17:25:33.412  6626  6725 I jxcore-log: JXcore Cordova bridge is ready!
08-03 17:25:33.412  6626  6725 I jxcore-log: 
08-03 17:25:33.413  6626  6725 W jxcore-log: JXcore engine is started
,08-03 17:25:33.416  6626  6722 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 17:25:33.419  6626  6626 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-03 17:25:33.439  6626  6725 E jxcore  : Error!: syntax error
08-03 17:25:33.439  6626  6725 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-03 17:25:33.446  6626  6626 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (57)
08-03 17:25:33.446  6626  6626 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
08-03 17:25:33.451  1034  1050 I ActivityManager: Killing 6231:com.android.calendar/u0a13 (adj 15): empty #17
08-03 17:25:33.469  1034  1907 W libprocessgroup: failed to open /acct/uid_10013/pid_6231/cgroup.procs: No such file or directory
08-03 17:25:33.470  6626  6722 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,08-03 17:25:33.472  6626  6626 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-03 17:25:33.476  6626  6626 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-03 17:25:33.478  6626  6626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 17:25:33.478  6626  6626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 17:25:33.478  6626  6626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 17:25:33.478  6626  6626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 17:25:33.478  6626  6626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2384fb62 removed from the list
08-03 17:25:33.479  6626  6626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 17:25:33.479  6626  6626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b7fdc29 removed from the list
08-03 17:25:33.479  6626  6626 D io.jxcore.node.ConnectivityMonitor: stop
08-03 17:25:33.479  6626  6626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-03 17:25:33.490   335   343 E GBMv2   : DFP En is all cleared set to be enabled
,08-03 17:25:33.495  1926  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-03 17:25:33.495  1926  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{314de8a3 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-03 17:25:33.496  1926  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-03 17:25:33.496  1926  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c1fe7a0 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-03 17:25:33.497  6626  6626 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-03 17:25:33.503  2018  2018 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-03 17:25:33.503  6626  6626 W ScreenOrientationListener: Removing an inexistent observer!
,08-03 17:25:33.506  2018  2018 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-03 17:25:33.508  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-03 17:25:33.508  2018  2111 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-03 17:25:33.513  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-03 17:25:33.515  1890  1890 D ActionManagerService: notifyUserLog: 1000003
08-03 17:25:33.516  3774  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-03 17:25:33.516  2018  2018 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-03 17:25:33.518  2018  2018 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-03 17:25:33.529  1034  1908 D InputDispatcher: Window went away: Window{30565c73 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-03 17:25:33.602  1034  1112 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6736 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 17:25:33.605  2018  2018 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-03 17:25:33.608  1890  1890 D ActionManagerService: notifyUserLog: 1000004
08-03 17:25:33.609  3774  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-03 17:25:33.609  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-03 17:25:33.612  3774  4174 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262123
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , display: false
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , animation: false }
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262287
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , display: false
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , animation: false }
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , create_time: 1469801565454
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , display: false
08-03 17:25:33.615  2018  2018 I GBoardWebViewUtils: , animation: false }
,08-03 17:25:33.633  2018  6742 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-03 17:25:33.663  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-03 17:25:33.697  6734  6734 D AndroidRuntime: 
08-03 17:25:33.697  6734  6734 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-03 17:25:33.699  6734  6734 D AndroidRuntime: CheckJNI is OFF
,08-03 17:25:33.809  6736  6736 I art     : Almond Protected OAT
,08-03 17:25:33.839  2018  2018 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-03 17:25:33.846  6734  6734 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-03 17:25:33.851  2018  2032 I art     : Background sticky concurrent mark sweep GC freed 49558(3MB) AllocSpace objects, 75(7MB) LOS objects, 3% free, 80MB/83MB, paused 1.457ms total 183.414ms
08-03 17:25:33.927  1034  1907 I art     : Explicit concurrent mark sweep GC freed 17723(917KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.636ms total 82.903ms
08-03 17:25:33.928  6736  6736 D WeatherApplication: removeAccount
08-03 17:25:33.928  6736  6736 D WeatherApplication: Account.length = 0
08-03 17:25:33.929  6736  6736 E WeatherApplication: OPERATOR:OPEN
08-03 17:25:33.931  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-03 17:25:33.931  6736  6736 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 17:25:33
,08-03 17:25:33.934  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 17:25:33.935  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-03 17:25:33.936  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-03 17:25:33.937  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-03 17:25:33.938  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-03 17:25:33.939  1034  1112 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-03 17:25:33.940  1034  1112 I ActivityManager: Killing 6626:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
08-03 17:25:33.945  6736  6736 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 17:25:33.945  6736  6736 D Weather.Utils: 2 : All the weather widget is gone.
,08-03 17:25:33.953  6736  6736 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 17:25:33.955  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-03 17:25:33.955  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 17:25:33.956  2018  2173 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-03 17:25:33.957  2018  2173 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-03 17:25:33.969  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-03 17:25:33.970  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-03 17:25:33.970  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 17:25:33.975  1034  1528 D WifiService: Client connection lost with reason: 4
,08-03 17:25:34.030  6736  6736 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-03 17:25:34.030  6736  6736 D Weather.Utils: 2 : All the weather widget is gone.
08-03 17:25:34.031  6736  6736 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 17:25:34
08-03 17:25:34.052  2018  2018 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-03 17:25:34.163  1034  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-03 17:25:34.200  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-03 17:25:34.205  3838  3838 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-03 17:25:34.205  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 17:25:34.207  1980  1980 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-03 17:25:34.207  3774  3774 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-03 17:25:34.209  2490  2623 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-03 17:25:34.212  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c1c1683 u0 com.lge.launcher2/.Launcher t39} time:134864
08-03 17:25:34.212  1034  1559 W ActivityManager: Spurious death for ProcessRecord{170f4863 6626:com.test.thalitest/u0a118}, curProc for 6626: null
,08-03 17:25:34.258  1034  1943 V SIM_STK : Menu title from STK is T-Mobile
08-03 17:25:34.258  1034  1111 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-03 17:25:34.261  4600  4600 I art     : Explicit concurrent mark sweep GC freed 17794(1072KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 471us total 61.867ms
08-03 17:25:34.267  4495  4495 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-03 17:25:34.268  4495  4495 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-03 17:25:34.268  4495  4495 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-03 17:25:34.268  4495  4495 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-03 17:25:34.268  4495  4495 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 17:25:34.268  4495  4495 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 17:25:34.268  4495  4495 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 17:25:34.268  4495  4495 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 17:25:34.268  4495  4495 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 17:25:34.268  4495  4495 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 17:25:34.268  4495  4495 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 17:25:34.268  4495  4495 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 17:25:34.270  2561  2561 D [Concierge]Service: onStartCommand(). Type : 8
08-03 17:25:34.270  2561  2561 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-03 17:25:34.275  2018  2018 D [Concierge]WidgetView: change position of spinner
,08-03 17:25:34.275  2561  2561 D [Concierge]Service: Update widget ID : 11
08-03 17:25:34.285  1034  1034 D administrator: Handling package changes for user 0
,08-03 17:25:34.299  2561  2561 D [Concierge]Service: onStartCommand(). Type : 0
,08-03 17:25:34.299  6414  6414 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-03 17:25:34.300  2018  2018 I [Concierge]WidgetView: initWebView(). Time : 1470237934300
08-03 17:25:34.306  1587  1645 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 17:25:34.306  1587  1645 D KeyguardModel: createShortcutInfo...
08-03 17:25:34.310  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-03 17:25:34.317  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-03 17:25:34.317  1587  1645 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 17:25:34.317  1587  1645 D KeyguardModel: createShortcutInfo...
08-03 17:25:34.324  1587  1645 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-03 17:25:34.325  1587  1645 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 17:25:34.325  1587  1645 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 17:25:34.326  1587  1645 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 17:25:34.327  1587  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 17:25:34.327  1587  1645 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-03 17:25:34.330  1587  1645 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 17:25:34.330  1587  1645 D KeyguardModel: createShortcutInfo...
08-03 17:25:34.333  2182  2182 I ConfigService: onCreate
08-03 17:25:34.333  2182  2182 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-03 17:25:34.333  1855  1855 D SplitUIManager: split_name #11 / not available #0
08-03 17:25:34.334  1855  1855 D SplitUIService: removed split : 
08-03 17:25:34.336  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-03 17:25:34.339  2018  2018 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1042682230
08-03 17:25:34.339  2018  2018 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-03 17:25:34.339  2182  2182 I ConfigService: onBind returning update interface
08-03 17:25:34.339  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-03 17:25:34.342  2018  2018 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1324cad2
08-03 17:25:34.342  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-03 17:25:34.343  2182  2182 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-03 17:25:34.343  2182  2182 I ConfigService: onBind returning config service
08-03 17:25:34.347  1587  1645 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-03 17:25:34.347  1587  1645 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 17:25:34.349  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-03 17:25:34.349  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 17:25:34.349  1587  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 17:25:34.349  1587  1645 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 17:25:34.351  1587  1645 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-03 17:25:34.351  1587  1645 D KeyguardModel: createShortcutInfo...
08-03 17:25:34.359  1034  1907 V SIM_STK : Menu title from STK is T-Mobile
08-03 17:25:34.359  1034  1907 V SIM_STK : Menu title from STK is T-Mobile
08-03 17:25:34.361  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-03 17:25:34.361  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-03 17:25:34.371  1587  1645 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 17:25:34.371  1587  1645 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 17:25:34.371  1587  1645 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 17:25:34.371  1587  1645 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 17:25:34.372  1587  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 17:25:34.372  1587  1645 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-03 17:25:34.373  1587  1645 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 17:25:34.373  1587  1645 D KeyguardModel: createShortcutInfo...
,08-03 17:25:34.378  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-03 17:25:34.379  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-03 17:25:34.379  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-03 17:25:34.381  1034  1417 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-03 17:25:34.384  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 17:25:34.385  2182  2182 I ConfigService: onDestroy
,08-03 17:25:34.385  2018  2018 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470237827489, New one : 1470237934300
08-03 17:25:34.386  2018  2018 D [Concierge]WidgetView: Unregister all receivers
08-03 17:25:34.386  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 17:25:34.386  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-03 17:25:34.386  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 17:25:34.387  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-03 17:25:34.389  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-03 17:25:34.390  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-03 17:25:34.391  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-03 17:25:34.392  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-03 17:25:34.399  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-03 17:25:34.399  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-03 17:25:34.400  1801  6784 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-03 17:25:34.403  1855  1855 D SplitUIManager: split_name #11 / not available #0
08-03 17:25:34.403  1855  1855 I SplitUIService: split app #11
08-03 17:25:34.407  1587  1645 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 17:25:34.407  1587  1645 D KeyguardModel: createShortcutInfo...
08-03 17:25:34.411  1587  1645 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 17:25:34.411  1587  1645 D KeyguardModel: createShortcutInfo...
08-03 17:25:34.412  1587  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 17:25:34.413  1587  1645 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-03 17:25:34.413  1587  1645 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 17:25:34.413  1587  1645 D KeyguardModel: createShortcutInfo...
08-03 17:25:34.414  1587  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 17:25:34.414  1587  1645 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 17:25:34.415  1587  1645 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-03 17:25:34.415  1587  1645 D KeyguardModel: createShortcutInfo...
08-03 17:25:34.418  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 17:25:34.418  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 17:25:34.421  1587  1645 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 17:25:34.421  1587  1645 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-03 17:25:34.422  1587  1645 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 17:25:34.422  1587  1645 D KeyguardModel: createShortcutInfo...
08-03 17:25:34.424  1034  2017 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 17:25:34.425  3838  3838 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 17:25:34.428  6552  6552 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-03 17:25:34.452  1034  1943 V SIM_STK : Menu title from STK is T-Mobile
,08-03 17:25:34.455  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-03 17:25:34.455  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-03 17:25:34.470  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-03 17:25:34.479  5930  6790 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-03 17:25:34.482  2018  2018 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-03 17:25:34.482  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-03 17:25:34.485  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 17:25:34.491  1801  6792 I PeopleContactsSync: CP2 sync disabled
,08-03 17:25:34.497  1801  4782 I Icing   : doRemovePackageData com.test.thalitest
08-03 17:25:34.498  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-03 17:25:34.498  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-03 17:25:34.498  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-03 17:25:34.503  2018  2018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@fb2ccc3 time:135155
08-03 17:25:34.504  2018  2018 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-03 17:25:34.506  1034  1562 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
,08-03 17:25:34.508  6002  6002 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-03 17:25:34.515  1801  6791 W GmsApplication: Using Auth Proxy for data requests.
08-03 17:25:34.516  1034  1979 I ActivityManager: Killing 6187:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-03 17:25:34.522   326   405 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 17:25:34.522  3205  6794 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-03 17:25:34.589  1034  1111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 17:25:34.595  1034  1111 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-03 17:25:34.609  1034  1050 W libprocessgroup: failed to open /acct/uid_10014/pid_6187/cgroup.procs: No such file or directory
,08-03 17:25:34.612  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-03 17:25:34.615  6517  6517 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-03 17:25:34.616  1034  1122 I art     : Explicit concurrent mark sweep GC freed 22180(1598KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.740ms total 311.265ms
08-03 17:25:34.617  1801  6791 W GmsApplication: Using Auth Proxy for data requests.
08-03 17:25:34.626  2338  6796 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-03 17:25:34.644  6734  6734 D AndroidRuntime: Shutting down VM
,08-03 17:25:34.647  2018  2018 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-03 17:25:34.660  1980  1980 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-03 17:25:34.660  1980  1980 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-03 17:25:34.662  1980  1980 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-03 17:25:34.666  6414  6414 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-03 17:25:34.689  2018  2873 I GBoardtInterface: onReloaded()
08-03 17:25:34.690  2018  2018 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-03 17:25:34.699  1034  1637 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6799 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-03 17:25:34.701  3774  3790 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 17:25:34.704  3774  3789 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 17:25:34.712  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-03 17:25:34.713  3774  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-03 17:25:34.714  3774  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 17:25:34.716  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-03 17:25:34.717  3774  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-03 17:25:34.717  3774  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 17:25:34.717  3774  4489 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-03 17:25:34.717  3774  4489 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-03 17:25:34.718  3774  3790 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 17:25:34.720  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-03 17:25:34.720  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-03 17:25:34.722  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-03 17:25:34.722  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-03 17:25:34.724  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-03 17:25:34.724  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-03 17:25:34.766  6799  6799 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-03 17:25:34.766  6799  6799 W LG Account v2.2: No ProfileInfo entries
08-03 17:25:34.766  6799  6799 I LG Account v2.2: isEnabled: false
08-03 17:25:34.766  6799  6799 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 17:25:34.766  6799  6799 I Feature : [Lifetracker]Country: EU
08-03 17:25:34.766  6799  6799 I Feature : [Lifetracker]Operator: OPEN
08-03 17:25:34.766  6799  6799 I Feature : [Lifetracker]Ranking support: false
08-03 17:25:34.766  6799  6799 I Feature : [Lifetracker]Comfort support: false
08-03 17:25:34.767  6799  6799 I Feature : [Lifetracker]Accessory: true
08-03 17:25:34.767  6799  6799 I Feature : [Lifetracker]Health device: true
,08-03 17:25:34.767  6799  6799 I Feature : [Lifetracker]Extra Pedometer: false
08-03 17:25:34.767  6799  6799 I Feature : [Lifetracker]Blood glucose device: false
08-03 17:25:34.767  6799  6799 I Feature : [Lifetracker]Device Number: 3
08-03 17:25:34.767  6799  6799 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-03 17:25:34.796  1034  2017 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6819 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 17:25:34.796  1034  2017 I ActivityManager: Killing 2118:com.lge.music/u0a34 (adj 15): empty #17
,08-03 17:25:34.807   313   313 V AudioFlinger: 2118 died, releasing its sessions
08-03 17:25:34.807   313   313 V AudioFlinger:  pid 1837 @ 0
08-03 17:25:34.807   313   313 V AudioFlinger:  pid 3408 @ 1
08-03 17:25:34.807   313   313 V AudioFlinger:  pid 3408 @ 2
,08-03 17:25:34.872  1034  1765 W libprocessgroup: failed to open /acct/uid_10034/pid_2118/cgroup.procs: No such file or directory
,08-03 17:25:34.886  6819  6819 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 17:25:34.886  6819  6819 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-03 17:25:34.887  6819  6819 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 17:25:34.887  6819  6819 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-03 17:25:34.887  6819  6819 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 17:25:34.888  6819  6819 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-03 17:25:34.989  6819  6819 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-03 17:25:34.992  2018  2873 I GBoardtInterface: exportHTML()
08-03 17:25:34.996  6819  6819 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-03 17:25:34.996  6819  6819 D HideNavigationAppsReceiver: replacing : false
08-03 17:25:34.999  6819  6819 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-03 17:25:35.001  6819  6819 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-03 17:25:35.001  6819  6819 D ButtonCombinationReceiver: replacing : false
,08-03 17:25:35.008  1034  1050 I ActivityManager: Killing 6460:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-03 17:25:35.019  2018  2873 I GBoardtInterface: exportHTML()
,08-03 17:25:35.042  2018  2873 I GBoardtInterface: exportHTML()

```
