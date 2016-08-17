#### Test 80807573a62a5c7_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-17 14:01:16.460  1818  1818 I art     : Explicit concurrent mark sweep GC freed 25950(1783KB) AllocSpace objects, 16(256KB) LOS objects, 51% free, 29MB/61MB, paused 1.410ms total 43.715ms
08-17 14:01:16.484  4660  6634 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 214 ms] updated apps [took 214 ms] 
08-17 14:01:16.572  6635  6635 D DocsApplication: Installing DEX configuration.
08-17 14:01:16.588  6635  6635 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-17 14:01:16.592  6635  6635 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{115ba5dc com.google.android.apps.docs}
08-17 14:01:16.607  6635  6635 D TAG     : onCreate()
08-17 14:01:16.623  6635  6635 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-17 14:01:17.487  1818  4811 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-17 14:01:17.595  1818  4811 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-17 14:01:17.636  1818  4811 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-17 14:01:17.685  6676  6676 D AndroidRuntime: 
08-17 14:01:17.685  6676  6676 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 14:01:17.687  6676  6676 D AndroidRuntime: CheckJNI is OFF
08-17 14:01:17.794  6635  6635 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:01:17.794  6635  6635 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 14:01:17.856  6676  6676 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 14:01:17.861  1035  1970 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 14:01:17.875  1941  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-17 14:01:17.878  1035  1970 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-17 14:01:17.879  1035  1970 D ActivityManager: setTaskToReturnTo : TaskRecord{30f9057e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 14:01:17.879  1035  1970 D ActivityManager: setTaskToReturnTo : TaskRecord{30f9057e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 14:01:17.881  1035  1970 D WindowStateEx: AppWindowTokenEx init.. 
08-17 14:01:17.882   342   351 E GBMv2   : DFP En is all cleared set to be enabled
08-17 14:01:17.917  1035  1970 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6708 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 14:01:17.919  6676  6676 D AndroidRuntime: Shutting down VM
08-17 14:01:17.955  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-17 14:01:17.956  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{13644e18 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 14:01:17.956  1941  2547 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-17 14:01:17.957  1941  2547 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1010c071 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 14:01:17.965  6243  6243 I LockScreenSettings: New app installed broadcast received ..
08-17 14:01:17.967  6243  6243 I LockScreenSettings: Number of installed packages  1
08-17 14:01:17.972  6635  6635 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-17 14:01:18.038  1035  2032 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:01:18.080  1035  1647 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6738 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 14:01:18.090  6708  6708 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-17 14:01:18.132  6738  6738 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-17 14:01:18.132  6738  6738 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-17 14:01:18.163  6708  6708 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 14:01:18.178  1035  2032 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6756 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-17 14:01:18.179  1035  2032 I ActivityManager: Killing 5956:com.google.android.talk/u0a72 (adj 15): empty #17
08-17 14:01:18.187  6708  6708 I LibraryLoader: Loading: webviewchromium
08-17 14:01:18.190  6708  6708 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2465-2469)
,08-17 14:01:18.190  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:01:18.207  6708  6708 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26b13386}
,08-17 14:01:18.208  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:01:18.208  6708  6708 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 14:01:18.219  6708  6708 I BrowserStartupController: Initializing chromium process, renderers=0
,08-17 14:01:18.221  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 14:01:18.231  1035  1575 W libprocessgroup: failed to open /acct/uid_10072/pid_5956/cgroup.procs: No such file or directory
,08-17 14:01:18.232  6708  6708 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-17 14:01:18.232   318  1397 V AudioPolicyService: registerClient() client 0xb557c3e0, uid 10118
08-17 14:01:18.233  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-17 14:01:18.233  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-17 14:01:18.239  1035  1111 D BluetoothManagerService: Message: 20
08-17 14:01:18.239  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ed90aad:true
08-17 14:01:18.247  6708  6708 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:01:18.247  6708  6708 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:01:18.247  6708  6708 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:01:18.247  6708  6708 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:01:18.247  6708  6708 I Adreno-EGL: Remote Branch: 
08-17 14:01:18.247  6708  6708 I Adreno-EGL: Local Patches: 
08-17 14:01:18.247  6708  6708 I Adreno-EGL: Reconstruct Branch: 
,08-17 14:01:18.279  6756  6756 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-17 14:01:18.298  6756  6756 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-17 14:01:18.299  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-17 14:01:18.329  6708  6785 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-17 14:01:18.335  6708  6708 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-17 14:01:18.337  1035  1890 I ActivityManager: Killing 5744:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-17 14:01:18.349  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:01:18.351  5720  5720 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-17 14:01:18.351  5720  5720 W System.err: android.os.DeadObjectException
08-17 14:01:18.352  5720  5720 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 14:01:18.352  5720  5720 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 14:01:18.352  5720  5720 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-17 14:01:18.352  5720  5720 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-17 14:01:18.352  5720  5720 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 14:01:18.352  5720  5720 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 14:01:18.352  5720  5720 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:01:18.352  5720  5720 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:01:18.352  5720  5720 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:01:18.352  5720  5720 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:01:18.352  5720  5720 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:18.352  5720  5720 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:01:18.352  5720  5720 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:01:18.352  5720  5720 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:01:18.352  5720  5720 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-17 14:01:18.352  5720  5720 W System.err: android.os.DeadObjectException
08-17 14:01:18.353  5720  5720 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 14:01:18.353  5720  5720 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 14:01:18.353  5720  5720 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-17 14:01:18.353  5720  5720 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-17 14:01:18.353  5720  5720 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 14:01:18.353  5720  5720 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 14:01:18.353  5720  5720 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:01:18.353  5720  5720 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:01:18.353  5720  5720 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:01:18.353  5720  5720 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:01:18.353  6708  6708 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 14:01:18.353  5720  5720 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:18.353  5720  5720 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:01:18.353  5720  5720 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:01:18.353  5720  5720 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:01:18.353  5720  5720 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-17 14:01:18.354  5720  5720 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-17 14:01:18.355  6708  6708 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-17 14:01:18.357  6708  6708 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : col,ors=0xfff5f5f5
08-17 14:01:18.357  6708  6708 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-17 14:01:18.368  6708  6708 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-17 14:01:18.446  1035  1647 W libprocessgroup: failed to open /acct/uid_1000/pid_5744/cgroup.procs: No such file or directory
,08-17 14:01:18.446  1035  1647 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-17 14:01:18.449  5720  5720 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-17 14:01:18.450  5720  5720 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-17 14:01:18.450  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 14:01:18.450  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 14:01:18.457  1035  1092 W ActivityManager: Activity pause timeout for ActivityRecord{3727eadf u0 com.test.thalitest/.MainActivity t6}
,08-17 14:01:18.525  1035  1958 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6800 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 14:01:18.525  5720  5720 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 14:01:18.539  6708  6814 D OpenGLRenderer: Render dirty regions requested: true
08-17 14:01:18.539  6708  6814 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 14:01:18.545  6708  6814 D OpenGLRenderer: Enabling debug mode 0
,08-17 14:01:18.557  6708  6708 D Atlas   : Validating map...
08-17 14:01:18.561  1035  1922 D SplitWindow: check instance of lgWin Window{1bf6e351 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 14:01:18.578  6800  6800 D UEI.SmartControl: Quickset Services start...
08-17 14:01:18.579  6800  6800 I UEI.SmartControl: Manufacture = LGE
08-17 14:01:18.579  6800  6800 D UEI.SmartControl: Id = LGNevo
08-17 14:01:18.580  6800  6800 D UEI.SmartControl: File observer start...
08-17 14:01:18.581  6800  6800 E UEI.SmartControl: IR Port is disabled: false
08-17 14:01:18.581  6800  6800 D UEI.SmartControl: Starting file observer...
08-17 14:01:18.581  6800  6800 D UEI.SmartControl: Extracting JNI libs...
08-17 14:01:18.581  6800  6800 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-17 14:01:18.605  6708  6798 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:01:18.605  6708  6798 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:01:18.645  6800  6800 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-17 14:01:18.646  6800  6800 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-17 14:01:18.646  6800  6800 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-17 14:01:18.679  1035  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +724ms (total +797ms)
,08-17 14:01:18.679  6708  6708 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2712880d time:112958
08-17 14:01:18.679  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3727eadf u0 com.test.thalitest/.MainActivity t6} time:112959
08-17 14:01:18.685  6800  6800 I UEI.SmartControl: --- Selecting new region: 6
08-17 14:01:18.687  6800  6800 I UEI.SmartControl: Model = LG-D855
08-17 14:01:18.689  6800  6800 D UEI.SmartControl: QS Service created
08-17 14:01:18.705  6800  6800 I UEI.SmartControl: Service initServices...
,08-17 14:01:18.709  6800  6800 D UEI.SmartControl: QS start get config
,08-17 14:01:18.791  6800  6800 D UEI.SmartControl: Loading JNI Libs...
,08-17 14:01:18.802  6708  6708 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-17 14:01:18.802  6708  6708 I chromium: 
,08-17 14:01:18.813  6708  6708 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-17 14:01:18.925  6708  6830 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,08-17 14:01:18.937  6708  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 14:01:18.937  6708  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 14:01:18.937  6708  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 14:01:18.937  6708  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 14:01:18.937  6708  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 14:01:18.937  6708  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20523f41 added. We now have 1 listener(s)
08-17 14:01:18.942  1035  1647 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:01:18.945  6708  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-17 14:01:18.947  6708  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:18.948  6708  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:18.948  6708  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 14:01:18.956  6708  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5b9cd4 added. We now have 1 listener(s)
08-17 14:01:18.956  6708  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:18.960  1035  1473 D WifiService: New client listening to asynchronous messages
08-17 14:01:18.964  6708  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:01:18.964  6708  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 14:01:18.964  6708  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 14:01:18.964  6708  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 14:01:18.964  6708  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-17 14:01:18.967  6708  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:18.968  1035  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:01:18.970  6708  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-17 14:01:18.979  6708  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 14:01:18.979  6708  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:18.979  6708  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:18.979  6708  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:18.979  6708  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:18.979  6708  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:18.979  6708  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:18.979  6708  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:18.979  6708  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:18.979  6708  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 14:01:18.979  6708  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:18.981  6708  6830 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 14:01:18.984  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:18.986  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:19.039  6708  6798 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-17 14:01:19.039  6708  6798 I chromium: 
,08-17 14:01:19.043  6800  6800 I UEI.SmartControl: Supports setup maps: true
08-17 14:01:19.046  6800  6800 D UEI.SmartControl: QS start statue = true Error code = 0
08-17 14:01:19.046  6800  6800 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 14:01:19.046  6800  6800 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 14:01:19.046  6800  6800 I UEI.SmartControl: ### init IR Blaster...
08-17 14:01:19.050  6800  6800 D serial_port: Configuring serial port
,08-17 14:01:19.054  6800  6800 E UEI.SmartControl: UEIBLaster setting for 616
08-17 14:01:19.054  6800  6800 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 14:01:19.054  6800  6800 I UEI.SmartControl: configuring settings for MAXQ616
08-17 14:01:19.054  6800  6800 I UEI.SmartControl: Get version...
08-17 14:01:19.071  6800  6834 D UEI.SmartControl: serial port data available: 21
,08-17 14:01:19.100  6800  6800 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-17 14:01:19.100  6800  6800 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-17 14:01:19.101  6800  6800 I UEI.SmartControl: QS saving settings...
08-17 14:01:19.102  6800  6800 D UEI.SmartControl: IR Blaster version: 25672567
08-17 14:01:19.112  6708  6708 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-17 14:01:19.120  6800  6834 D UEI.SmartControl: serial port data available: 4
,08-17 14:01:19.156  6800  6837 I UEI.SmartControl: Device manager: loading config....
,08-17 14:01:19.159  6800  6837 D UEI.SmartControl: ----------- loading internal config...
08-17 14:01:19.164  6800  6800 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-17 14:01:19.169  6800  6800 E UEI.SmartControl: Services init done
08-17 14:01:19.169  6800  6800 D UEI.SmartControl: QS Service init finished
,08-17 14:01:19.174  6800  6800 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 14:01:19.174  6800  6800 D UEI.SmartControl: QS Service version code: 201091
08-17 14:01:19.175  6800  6800 D UEI.SmartControl: Service requested: Control
08-17 14:01:19.176  6800  6837 E UEI.SmartControl: Loading SETTINGS...
08-17 14:01:19.178  5720  5720 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-17 14:01:19.179  6800  6820 I UEI.SmartControl: ------ IControl API: 11
08-17 14:01:19.180  6800  6820 I UEI.SmartControl: Registering callback...
08-17 14:01:19.181  1035  1933 I ActivityManager: Killing 5720:com.lge.qremote/u0a112 (adj 15): empty #17
08-17 14:01:19.203  6800  6837 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-17 14:01:19.229  6800  6836 I UEI.SmartControl: Notify AllClients services are ready: 0
08-17 14:01:19.229  6800  6836 D UEI.SmartControl: -----service ready thread exits
,08-17 14:01:19.282  6800  6800 D UEI.SmartControl: Internal service binding...
08-17 14:01:19.282  1035  1970 W libprocessgroup: failed to open /acct/uid_10112/pid_5720/cgroup.procs: No such file or directory
,08-17 14:01:19.564   342   353 E GBMv2   : DFP En is all cleared set to be enabled
08-17 14:01:19.565   342   353 E GBMv2   : Set value is all cleared set the max
08-17 14:01:19.565   342   353 I GBMv2   : DFP Enabled. Ignore VFP set
,08-17 14:01:20.327  6708  6833 W jxcore-log: Initializing JXcore engine
08-17 14:01:20.327  6708  6833 W jxcore-log: JXcore engine is ready
,08-17 14:01:20.356  6833  6833 W Thread-751: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10246]" dev="sockfs" ino=10246 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 14:01:20.356  6833  6833 W Thread-751: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-17 14:01:20.356  6833  6833 W Thread-751: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9958]" dev="sockfs" ino=9958 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 14:01:20.356  6833  6833 W Thread-751: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-17 14:01:20.356  6833  6833 W Thread-751: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32053]" dev="sockfs" ino=32053 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-17 14:01:20.378  6708  6833 W jxcore-log: Starting JXcore engine
08-17 14:01:20.455  6708  6833 W jxcore-log: Platform android
08-17 14:01:20.455  6708  6833 W jxcore-log: 
08-17 14:01:20.455  6708  6833 W jxcore-log: Process ARCH arm
08-17 14:01:20.455  6708  6833 W jxcore-log: 
,08-17 14:01:20.524   332   413 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-17 14:01:20.530  3228  6859 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-17 14:01:20.838  6708  6833 I jxcore-log: JXcore Cordova bridge is ready!
08-17 14:01:20.838  6708  6833 I jxcore-log: 
08-17 14:01:20.838  6708  6833 W jxcore-log: JXcore engine is started
,08-17 14:01:20.845  6708  6830 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-17 14:01:20.848  6708  6708 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-17 14:01:21.912  6635  6635 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-17 14:01:21.915  1035  1958 I ActivityManager: Killing 5255:com.android.calendar/u0a13 (adj 15): empty #17
08-17 14:01:21.981  1035  2032 W libprocessgroup: failed to open /acct/uid_10013/pid_5255/cgroup.procs: No such file or directory
,08-17 14:01:22.659  2174  2174 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19989
,08-17 14:01:22.861  6635  6699 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-17 14:01:24.161  6800  6838 D UEI.SmartControl: Internal timer expired: 1
08-17 14:01:24.161  6800  6838 D UEI.SmartControl: unbind internal service
,08-17 14:01:24.176  6800  6800 D UEI.SmartControl: Service.onUnbind: IControl
,08-17 14:01:24.182  6800  6800 D UEI.SmartControl: Service.onDestroy
08-17 14:01:24.183  6800  6800 D UEI.SmartControl: Lock is in USE false
08-17 14:01:24.183  6800  6800 D UEI.SmartControl: unbind internal service
08-17 14:01:24.183  6800  6800 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@19dd0212
08-17 14:01:24.184  6800  6800 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-17 14:01:24.184  6800  6800 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-17 14:01:24.184  6800  6800 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-17 14:01:24.185  6800  6800 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-17 14:01:24.185  6800  6800 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-17 14:01:24.185  6800  6800 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-17 14:01:24.185  6800  6800 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-17 14:01:24.185  6800  6800 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-17 14:01:24.185  6800  6800 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:24.185  6800  6800 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:01:24.185  6800  6800 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:01:24.185  6800  6800 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:24.186  6800  6800 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:01:24.186  6800  6800 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:01:24.186  6800  6800 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:01:24.186  6800  6800 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@19dd0212
08-17 14:01:24.192  6800  6800 D serial_port: close(fd = 25)
,08-17 14:01:24.203  6800  6800 I UEI.SmartControl: Serial port is closed.
08-17 14:01:24.203  6800  6800 I UEI.SmartControl: Serial port is closed.
08-17 14:01:24.203  6800  6800 D UEI.SmartControl: Blaster closed
08-17 14:01:24.204  6800  6800 D UEI.SmartControl: Shut down QS...
08-17 14:01:24.204  6800  6800 D UEI.SmartControl: Stopping QS lib
08-17 14:01:24.204  6800  6800 D UEI.SmartControl: QS lib stop result = true
08-17 14:01:24.204  6800  6800 D UEI.SmartControl: Stopped QS lib
08-17 14:01:24.204  6800  6800 D UEI.SmartControl: Stopped file observer...
08-17 14:01:24.205  6800  6800 D UEI.SmartControl: QS shutdown complete
,08-17 14:01:25.539  1818  6542 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-17 14:01:25.543   314  6863 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 14:01:25.544   314  6863 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-17 14:01:25.544   314  6863 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-17 14:01:25.766  1818  1818 I ConfigFetchService: fetch service done; releasing wakelock
,08-17 14:01:25.772  1818  1818 I ConfigFetchService: stopping self
08-17 14:01:25.780  2198  2198 I ConfigService: onDestroy
,08-17 14:01:30.670  1035  1092 I ActivityManager: Waited long enough for: ServiceRecord{10b82da3 u0 com.google.android.gms/.wearable.service.WearableService}
,08-17 14:01:31.181  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 14:01:31.181  6708  6833 I jxcore-log: 
,08-17 14:01:31.183  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 14:01:31.183  6708  6833 I jxcore-log: 
08-17 14:01:31.188  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:31.188  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:31.188  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:31.188  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:31.188  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:31.188  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.188  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:31.188  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:31.191  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.193  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 14:01:31.193  6708  6833 I jxcore-log: 
,08-17 14:01:31.195  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 14:01:31.195  6708  6833 I jxcore-log: 
,08-17 14:01:31.528  6708  6833 D ExecuteNativeTests: Running unit tests
,08-17 14:01:31.611  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 14:01:31.611  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 added. We now have 2 listener(s)
,08-17 14:01:31.611  1035  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:01:31.613  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-17 14:01:31.613  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:31.613  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:31.614  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:31.614  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 added. We now have 2 listener(s)
08-17 14:01:31.614  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:31.614  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:01:31.617  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:31.619  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:31.619  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:31.619  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:31.619  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:31.619  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:31.619  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.619  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:31.619  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:31.620  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.620  6708  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:31.621  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:31.622  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:31.629  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:01:31.629  6708  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:01:31.629  6708  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 14:01:31.639  6708  6833 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 14:01:31.641  6708  6833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 14:01:31.641  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 14:01:31.641  6708  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:01:31.641  6708  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:01:31.642  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.644  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.644  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.645  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.645  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.645  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:31.645  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:31.645  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 removed from the list
08-17 14:01:31.646  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.646  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 removed from the list
08-17 14:01:31.646  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.646  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.646  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.646  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.647  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.647  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.647  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.647  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.651  6708  6833 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 14:01:31.651  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.651  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.651  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.651  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.651  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.651  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.651  6708  6833 E org.thaliproject.p2p.btconnectorlib.Conne,ctionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.651  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.651  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.651  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.651  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.651  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.651  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.652  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.652  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.652  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.652  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.652  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 14:01:31.656  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 14:01:31.657  6708  6833 D ,io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:01:31.657  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.657  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.657  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.657  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.657  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.657  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.657  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.657  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:01:31.657  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.657  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.657  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.657  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.657  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.657  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.658  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.658  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.658  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.658  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.661  6708  6833 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 14:01:31.663  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:31.665  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:31.665  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:31.665  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:31.665  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:31.665  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:31.665  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.665  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:31.665  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:31.666  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.666  6708  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:31.667  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:31.668  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:31.668  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:31.668  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:31.668  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:31.668  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:31.668  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:01:31.671  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing.,..
,08-17 14:01:31.671  1035  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:31.676  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:01:31.680  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:01:31.681  6708  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 14:01:31.682  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:01:31.682  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:31.683  6708  6833 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-17 14:01:31.683  6708  6833 I io.jxcore.node.ConnectionHelper: start: OK
08-17 14:01:31.686  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.686  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.686  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.686  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.686  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.686  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:31.686  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.686  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.686  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.686  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.686  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.687  6708  6833 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 14:01:31.688  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:31.690  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:31.690  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:31.690  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:31.690  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:31.690  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:31.690  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.690  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:31.690  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:31.691  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.691  6708  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:31.692  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:31.692  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:31.692  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:31.692  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:31.692  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:01:31.692  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnect,ivityInfo: No relevant state changes
08-17 14:01:31.694  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:31.696  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:01:31.696  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:31.697  6708  6833 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:01:31.697  6708  6833 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 14:01:31.701  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.701  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.701  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.701  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.701  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.701  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:31.701  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.701  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.701  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.701  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.701  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.702  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.702  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.703  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.703  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.704  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.704  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.704  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.704  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.704  6708  6833 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 14:01:31.705  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:31.707  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:31.707  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:31.707  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:31.707  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:31.707  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:31.707  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.707  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:31.707  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:31.708  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:31.708  6708  6833 D io.jxcore.node.ConnectivityMoni,tor: start: OK
08-17 14:01:31.709  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:31.710  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:31.710  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:31.711  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:31.711  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:31.711  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:31.711  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:01:31.714  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:01:31.714  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:31.715  6708  6833 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:01:31.715  6708  6833 I io.jxcore.node.ConnectionHelper: start: OK
08-17 14:01:31.715  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.715  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.715  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.716  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.716  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.716  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.716  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.716  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.716  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:31.716  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.716  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.716  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.716  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.716  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.717  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.717  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.717  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.717  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.717  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.717  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.717  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.717  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.718  6708  6833 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 14:01:31.718  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.718  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.718  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.718  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.719  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.719  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.719  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.719  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.719  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.719  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.719  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.719  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.719  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.719  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.719  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.719  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.720  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.720  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.720  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.720  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.722  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 14:01:31.723  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.723  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.723  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.723  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.723  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.723  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.723  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.723  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.723  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.723  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.724  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.724  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.724  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.724  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.724  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.724  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.725  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.725  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.725  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.725  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.725  6708  6833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 14:01:31.726  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.726  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.726  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.726  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.726  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.726  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.726  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.726  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.726  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.726  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.726  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.726  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.726  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.726  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.727  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.727  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.727  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.727  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.727  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.727  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.727  6708  6833 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 14:01:31.728  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.728  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.728  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.728  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.728  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.728  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.728  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.728  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.728  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.728  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.728  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.728  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.728  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.728  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.728  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.728  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.729  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.729  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.729  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.729  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.729  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:01:31.729  6708  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:01:31.729  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:01:31.729  6708  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:01:31.729  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:01:31.729  6708  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:01:31.730  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.730  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.730  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.730  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.730  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.730  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.730  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.730  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.730  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.730  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.730  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.730  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.730  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.730  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.731  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.731  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.731  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.731  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.731  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.731  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.732  6708  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:01:31.733  6708  6833 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:01:31.733  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 14:01:31.737  6708  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:01:31.738  6708  6833 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 14:01:31.738  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:01:31.738  6708  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 14:01:31.739  6708  6833 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:01:31.739  6708  6833 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 14:01:31.739  6708  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:01:31.739  6708  6833 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:01:31.739  6708  6833 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 14:01:31.739  6708  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:01:31.739  6708  6833 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:01:31.739  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 14:01:31.741  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 14:01:31.742  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 14:01:31.742  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 14:01:31.742  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 14:01:31.742  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 14:01:31.742  6708  6833 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 14:01:31.742  6708  6833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:01:31.742  6708  6833 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 14:01:31.743  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.743  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.743  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.743  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.744  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.744  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 lis,tener(s) left
08-17 14:01:31.744  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 14:01:31.744  6708  6868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 815)
08-17 14:01:31.744  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.744  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.744  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.744  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.744  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.744  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.744  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.744  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.745  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.745  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.745  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.745  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.745  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.745  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.746  6708  6833 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 14:01:31.746  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.746  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.746  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.746  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.746  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.746  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.746  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.748  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.749  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.749  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.749  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.749  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.749  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.749  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.750  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.750  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.750  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.750  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.750  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.750  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.752  6708  6869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 815
08-17 14:01:31.755  6708  6833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 14:01:31.760  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.760  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.760  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.760  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.760  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.761  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.761  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.761  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.763  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.763  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.763  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.763  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.763  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.763  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.771  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.771  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.771  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.771  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.771  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.771  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
,08-17 14:01:31.772  6708  6833 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 14:01:31.772  6708  6833 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 14:01:31.772  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:01:31.773  6708  6833 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 14:01:31.773  6708  6833 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:01:31.773  6708  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 14:01:31.774  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:01:31.774  6708  6833 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 14:01:31.774  6708  6833 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:01:31.774  6708  6833 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:01:31.774  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:01:31.774  6708  6833 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 14:01:31.774  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.774  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.774  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.774  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.774  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.774  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.774  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.774  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.774  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.774  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.774  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.774  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.775  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.775  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1, listener(s) left
08-17 14:01:31.775  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.775  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.776  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.776  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.776  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.776  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.776  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.776  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.776  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.776  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.776  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.776  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.776  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.776  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.776  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.777  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.777  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.777  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.777  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.777  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.777  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.777  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.777  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.777  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.777  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.777  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.777  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.777  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in, the list
08-17 14:01:31.777  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.777  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.777  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.777  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.777  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.777  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.777  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.781  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.781  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.781  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.781  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.781  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.782  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.783  6708  6833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 14:01:31.784  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:31.784  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 14:01:31.787  6708  6833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 14:01:31.787  6708  6833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 14:01:31.788  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 14:01:31.788  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 14:01:31.788  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:01:31.788  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:31.789  6708  6875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:31.789  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.789  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 14:01:31.789  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 14:01:31.789  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 14:01:31.789  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.789  6708  6833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 14:01:31.789  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 14:01:31.789  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.790  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.790  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:01:31.790  6708  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:01:31.790  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:01:31.792  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:01:31.792  3875  3895 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=83
08-17 14:01:31.793  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:31.793  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:31.793  6708  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:01:31.793  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.793  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.793  6708  6875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 14:01:31.793  6708  6875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 14:01:31.794  6708  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 14:01:31.794  6708  6833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:31.794  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:31.794  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:01:31.794  6708  6708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 14:01:31.794  6708  6708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:01:31.794  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.794  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.794  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.794  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.795  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.795  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.795  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.795  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.795  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.795  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.795  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.795  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.795  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.795  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.795  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.796  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.796  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.796  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.796  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.796  6708  6833 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 14:01:31.797  6708  6833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 14:01:31.797  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:01:31.797  6708  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:01:31.797  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.797  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.797  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.797  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.797  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.798  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.798  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.798  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.798  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.798  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.798  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.798  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.798  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.798  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.799  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.799  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.799  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.799  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.800  1035  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:31.800  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:31.801  1035  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:31.803  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.803  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.803  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.804  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.804  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.804  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.804  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.804  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.804  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.804  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.804  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.804  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.805  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.805  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.806  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.806  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.806  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.806  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.807  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:31.807  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:31.807  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:31.807  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:31.807  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.807  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.807  6708  6833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ed98e7 not in the list
08-17 14:01:31.807  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.807  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.807  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:31.807  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.807  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.807  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:31.807  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:31.808  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:31.808  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:31.808  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:31.808  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86aac94 not in the list
08-17 14:01:31.810  6708  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 14:01:31.810  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:01:31.810  6708  6833 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 14:01:31.810  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:01:31.810  6708  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 14:01:31.810  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:01:31.812  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 14:01:31.812  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 14:01:31.813  6708  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 14:01:31.813  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:01:31.813  6708  6833 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 14:01:31.813  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:01:31.813  6708  6833 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 14:01:31.813  6708  6833 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 14:01:31.814  6708  6833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 14:01:31.814  6708  6833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 14:01:31.814  6708  6833 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 14:01:31.814  6708  6833 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 14:01:31.815  6708  6833 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 14:01:31.815  6708  6833 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 14:01:31.815  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:31.816  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@116a1cf5 added. We now have 2 listener(s)
08-17 14:01:31.816  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:31.821  6708  6833 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 14:01:31.823  1035  1776 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 14:01:31.824  1035  1776 D WifiService: setWifiEnabled: true pid=6708, uid=10118
08-17 14:01:31.824  1035  1776 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 14:01:31.825  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:31.825  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@197f2a8a added. We now have 3 listener(s)
08-17 14:01:31.825  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:31.828  6708  6868 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-17 14:01:31.828  6708  6868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:31.829  3875  4008 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:31.829  3875  4098 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
08-17 14:01:31.831  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:31.831  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad758fb added. We now have 4 listener(s)
08-17 14:01:31.831  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:31.832  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:31.832  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7ef8d18 added. We now have 5 listener(s)
08-17 14:01:31.832  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:31.834  1035  1647 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 14:01:31.834  1035  1647 D WifiService: setWifiEnabled: false pid=6708, uid=10118
08-17 14:01:31.834  1035  1647 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:01:31.855  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:01:31.855  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:01:31.855  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 14:01:31.856  1035  1435 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 14:01:31.856  1035  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:31.857  1035  1778 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1a02dd8f mBinding = false
08-17 14:01:31.857  1035  1435 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 14:01:31.857  1035  1435 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 14:01:31.858  1035  1435 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-17 14:01:31.858  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 14:01:31.858  1035  1435 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 14:01:31.858  1035  1435 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:01:31.858  1035  1435 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 14:01:31.859  1035  1435 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 14:01:31.859  1035  1435 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 14:01:31.870  1035  1435 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 14:01:31.870  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 14:01:31.870  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.870  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.870  2723  2723 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 14:01:31.871  1035  1435 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 14:01:31.871  1035  1435 D WifiNative-wlan0: doBoolean: SET ps 1
,08-17 14:01:31.872  1035  1435 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:01:31.872  1035  2866 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.872   314   880 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:01:31.886  1035  1111 D BluetoothManagerService: Message: 2
08-17 14:01:31.888  1035  1111 D BluetoothManagerService: Sending off request.
08-17 14:01:31.890  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:01:31.890  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:01:31.890  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 14:01:31.891  3875  3895 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 14:01:31.892  1035  1050 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-17 14:01:31.903  1035  1376 V AlarmManager: RTC_WAKEUP set : Alarm{acefc25 type 0 when 1471435291256 com.android.vending} when 1471435291256
,08-17 14:01:31.904  3875  3972 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 14:01:31.904  3875  3972 D BluetoothAdapterProperties: Setting state to 13
08-17 14:01:31.904  3875  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 14:01:31.904  1035  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-11ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.904  1035  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-11ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.904  1035  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 14:01:31.904  1035  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.904  1035  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 14:01:31.908  3875  3972 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 14:01:31.908  3875  3972 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 14:01:31.913  1035  1111 D BluetoothManagerService: Message: 60
08-17 14:01:31.913  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 14:01:31.913  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-17 14:01:31.913   314  6881 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 14:01:31.915  1035  1483 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 14:01:31.916  1035  1483 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-17 14:01:31.916  1035  1109 D DSQN    : Dns fail occured do internet check.
08-17 14:01:31.917  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-17 14:01:31.917  1035  1035 D DSQN    : try Internet connection check
,08-17 14:01:31.921  1035  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-17 14:01:31.922  1035  1435 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:31.923  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:31.923  1035  1435 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:31.924  1035  1435 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:31.924  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:31.924  1035  1435 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:31.925  1035  1435 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 14:01:31.925  1035  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.925  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.925  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@17c8b94
08-17 14:01:31.926  1035  1390 D LGWifiP2pService: P2pDisablingState
08-17 14:01:31.926  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.926  1035  1390 D LGWifiP2pService: p2p socket connection lost
08-17 14:01:31.926  1035  1390 D LGWifiP2pService: P2pDisabledState
08-17 14:01:31.928  3875  3875 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:31.928  3875  3875 D BluetoothMapService: STATE_TURNING_OFF
08-17 14:01:31.928  3875  3875 V BluetoothMapService: Handler(): got msg=4
08-17 14:01:31.928  3875  3875 D BluetoothMapService: MAP Service closeService in
08-17 14:01:31.928  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:31.928  3875  3875 D BluetoothMapMasInstance: MAP Service shutdown
,08-17 14:01:31.929  3875  4289 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 14:01:31.929  3875  4289 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:31.929  3875  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 14:01:31.929  3875  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 14:01:31.929  3875  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-17 14:01:31.929  3875  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 14:01:31.929  3875  4289 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 14:01:31.929  3875  4289 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-17 14:01:31.929  3875  3875 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:01:31.930  3875  3875 V BluetoothMapService: MAP Service closeService out
08-17 14:01:31.930  3875  3875 V BtOppService: Receiver DISABLED_ACTION 
08-17 14:01:31.930  3875  3875 I BtOppRfcommListener: stopping Accept Thread
08-17 14:01:31.930  3875  3875 V BtOppRfcommListener: close mBtServerSocket
08-17 14:01:31.930  3875  3875 V BtOppRfcommListener: waiting for thread to terminate
08-17 14:01:31.931  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:01:31.932  3875  4353 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:31.932  3875  4353 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 14:01:31.933  3875  3875 V BtOppRfcommListener: done waiting for thread to terminate
08-17 14:01:31.936  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:31.936  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:31.936  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:31.936  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:31.936  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:31.936  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:31.936  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:31.936  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:31.936  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:31.937  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:31.937  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:31.951  1035  1435 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-17 14:01:31.954  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.955  1035  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.955  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 14:01:31.955  2723  2723 I wpa_supplicant:, wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-17 14:01:31.965  1035  1435 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 14:01:31.965  1035  1435 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:01:31.965  1035  1435 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:01:31.982  1035  1483 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-17 14:01:31.982  1035  1483 D DSQN    : disableDataServiceNotify
08-17 14:01:31.982  1035  1483 D DSQN    : stop dsqn bin
,08-17 14:01:31.983  1035  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6889 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 14:01:31.984   314   880 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:01:31.987   314  6895 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 14:01:31.987  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-17 14:01:31.987  1035  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 14:01:31.987  1035  6884 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-17 14:01:31.987  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:31.987  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:31.987  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:01:31.987  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-17 14:01:31.988  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-17 14:01:31.988  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:31.988  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:01:31.988  1035  6883 D DSQN    : ThreadInternetCheck internet check NOK 
08-17 14:01:31.988  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 14:01:31.988  1035  6883 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-17 14:01:31.988  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-17 14:01:31.988  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.988  1035  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:31.989  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-17 14:01:31.989  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 14:01:31.989  1941  1941 D WfdsService: WifiP2pState is changed : false
08-17 14:01:31.989  1941  2265 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-17 14:01:31.989  1941  2265 D WfdsService: Set the WFDS Monitor: false
08-17 14:01:31.990  1941  2265 D WfdsMonitor: WFDS Monitor is stopped
08-17 14:01:31.990  1941  2265 D WfdsService: STATE : WfdsDisabledState - enter
08-17 14:01:31.990  1941  2782 D CtrlSupplicant: Received on exit socket, terminate
08-17 14:01:31.990  1941  2782 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 14:01:31.990  1941  2782 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 14:01:31.990  1941  2270 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 14:01:31.990  1941  2782 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-17 14:01:31.991  1941  2265 W WfdsService: DefaultState - msg [9445378] is not handled
08-17 14:01:31.992  3875  3875 V BtOppService: onDestroy
08-17 14:01:31.992  1035  1435 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 14:01:31.993  1035  1435 D WifiNative-p2p0: TERMINATE: returned true
08-17 14:01:31.993  1035  1435 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:01:31.993  1035  1435 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:01:31.993  1035  1435 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:01:31.993  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-17 14:01:31.996  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:31.996  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:31.996  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:01:31.999  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,08-17 14:01:32.001  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:32.001  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 14:01:32.001  1035  1483 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 14:01:32.001  1035  1483 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:32.002  1035  1483 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:32.002  1035  1483 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:32.002  1035  1483 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-17 14:01:32.002  1035  1483 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-17 14:01:32.002  1035  1483 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-17 14:01:32.002  1035  1483 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 14:01:32.003  1035  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:32.003  1035  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:32.003  1035  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 14:01:32.003  1035  1483 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:32.003  1035  1483 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 14:01:32.003  1602  1815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 14:01:32.004  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-17 14:01:32.005  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 14:01:32.005  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 14:01:32.005  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 14:01:32.005  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 14:01:32.005  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 14:01:32.005  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:32.005  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:32.005  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:32.005  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetoo,th LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:32.005  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:32.005  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:32.005  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:32.005  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:32.005  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:32.006  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:32.006  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:32.007  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:32.007  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:32.008  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:32.008  1035  1483 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:32.008  1035  1483 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:32.008  1035  1483 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:32.009  1035  1435 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:32.009  1035  1435 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:01:32.009  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:32.010  1035  1483 D NetworkManagementService: Removing idletimer
08-17 14:01:32.010  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 14:01:32.010  1035  1483 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:32.011  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 14:01:32.011  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 14:01:32.012  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 14:01:32.012  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 14:01:32.012  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 14:01:32.012  1035  1483 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-17 14:01:32.020  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:32.040  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:32.040  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 14:01:32.042  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:32.045  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 14:01:32.045  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:32.046  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:32.048  1035  1922 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:01:32.051  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:32.063  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 14:01:32.063  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:32.064  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:01:32.076  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 14:01:32.077  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:32.077  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:01:32.082  1035  2866 D DhcpStateMachine: StoppedState
08-17 14:01:32.082  1035  2866 D DhcpStateMachine: StoppedState{ when=-116ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:32.082  2723  2723 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 14:01:32.082  2723  2723 I wpa_supplicant: monitor socket send errors count : 1
08-17 14:01:32.082  2723  2723 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
08-17 14:01:32.083  1035  2779 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 14:01:32.083  1035  2779 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 14:01:32.085  1035  1435 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-17 14:01:32.085  1035  1435 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-17 14:01:32.094  1035  1994 I art     : Explicit concurrent mark sweep GC freed 45227(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.715ms total 204.545ms
,08-17 14:01:32.095  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:32.095  3875  3978 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:01:32.095  3875  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 14:01:32.096  3875  4291 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:32.096  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 14:01:32.096  3875  3972 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 14:01:32.096  3875  4098 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 14:01:32.096  3875  4354 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:32.096  6708  6868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 815)
08-17 14:01:32.096  3875  4357 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 14:01:32.100  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-17 14:01:32.101  3875  4098 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 14:01:32.101  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:32.101  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:32.101  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:32.101  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:32.101  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:32.101  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:32.101  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:32.101  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:32.101  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:32.102  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:32.102  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:32.102  6708  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:32.103  6708  6708 V io.jxcore.node.ConnectivityMo,nitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:32.104  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:32.105  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:32.105  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:32.105  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:32.105  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:32.105  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:32.105  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:32.105  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:32.105  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:32.105  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:32.106  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:32.128  1035  1051 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6907 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 14:01:32.133  3875  3875 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-17 14:01:32.143  6889  6889 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:01:32.143  6889  6889 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-17 14:01:32.143  6889  6889 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:01:32.143  6889  6889 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-17 14:01:32.144  6889  6889 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 14:01:32.145  6889  6889 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 14:01:32.185  6907  6907 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-17 14:01:32.190  6907  6907 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:01:32.191  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:32.204  2723  2723 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:01:32.204  1035  2779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-17 14:01:32.204  1035  2779 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:01:32.204  1035  2779 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:01:32.204  2723  2723 W wpa_supplicant: USIM:  scard_deinit function
,08-17 14:01:32.205  1035  2779 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-17 14:01:32.205  1035  2779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:01:32.205  1035  2779 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:01:32.205  1035  1435 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=126472
08-17 14:01:32.206  1035  1435 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=126472
08-17 14:01:32.206  1035  1435 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=126472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 14:01:32.206  1035  1435 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=126472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 14:01:32.207  1035  1111 D Tethering: InitialState.processMessage what=4
08-17 14:01:32.208  6198  6198 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-17 14:01:32.208  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:01:32.208  1035  1435 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:32.209  1035  1435 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:32.210  1035  1958 I ActivityManager: Killing 5999:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-17 14:01:32.228  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-17 14:01:32.281  1035  1778 W libprocessgroup: failed to open /acct/uid_10014/pid_5999/cgroup.procs: No such file or directory
,08-17 14:01:32.295  6708  6708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:01:32.297  3875  3875 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:01:32.298  3875  3875 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:32.298  3875  3875 V BluetoothPbapReceiver: ***********state = 13
08-17 14:01:32.300  3875  3875 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-17 14:01:32.302  3875  3875 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:32.302  3875  3875 V BluetoothPbapService: state: 13
08-17 14:01:32.302  3875  3875 V BluetoothPbapService: Pbap Service closeService in
08-17 14:01:32.305  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:01:32.308  3875  3875 V BluetoothPbapService: successfully stopped pbap service
08-17 14:01:32.309  3875  3875 V BluetoothPbapService: Pbap Service closeService out
08-17 14:01:32.309  3875  3875 V BluetoothPbapService: Pbap Service onDestroy
08-17 14:01:32.309  3875  3875 V BluetoothPbapService: Pbap Service closeService in
08-17 14:01:32.309  3875  3875 V BluetoothPbapService: Pbap Service closeService out
08-17 14:01:32.309  3875  3875 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-17 14:01:32.312  2723  2723 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 14:01:32.313  1035  2779 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 14:01:32.314  1035  2779 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 14:01:32.314  1035  2779 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 14:01:32.318  1035  1435 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-17 14:01:32.320  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:32.361  6889  6889 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:01:32.362  6889  6889 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:01:32.374  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:01:32.380  1035  1111 D BluetoothManagerService: Message: 20
08-17 14:01:32.380  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b214eb4:true
08-17 14:01:32.385  1035  2003 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6930 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-17 14:01:32.386  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-17 14:01:32.387  1941  2265 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-17 14:01:32.387  1941  2265 D WfdsService: Set the WFDS Monitor: false
08-17 14:01:32.387  1941  2265 D WfdsMonitor: WFDS Monitor is stopped
08-17 14:01:32.389  1035  1435 D WifiOffDelayIfNotUsed: stopMonitoring
,08-17 14:01:32.389  1035  1435 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:01:32.389  1035  1435 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:01:32.389  1035  1435 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:01:32.390  1035  1111 D BluetoothManagerService: Message: 30
08-17 14:01:32.391  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:32.394  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-17 14:01:32.395  1035  1446 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 14:01:32.396  1035  1446 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-17 14:01:32.396  2488  2488 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:32.397  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 14:01:32.398  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:32.400  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:32.402  1035  1111 D BluetoothManagerService: Message: 30
,08-17 14:01:32.404  6889  6889 D LocalBluetoothProfileManager: Adding local MAP profile
08-17 14:01:32.405  6889  6889 D BluetoothMap: Create BluetoothMap proxy object
08-17 14:01:32.406  1035  1111 D BluetoothManagerService: Message: 30
08-17 14:01:32.409  1035  1111 D BluetoothManagerService: Message: 30
08-17 14:01:32.412  6889  6889 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-17 14:01:32.414  6889  6889 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-17 14:01:32.426  6889  6889 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-17 14:01:32.428  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-17 14:01:32.435  6889  6889 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:01:32.441  6889  6889 D BluetoothInputDevice: Proxy object connected
,08-17 14:01:32.442  6889  6889 D HidProfile: Bluetooth service connected
08-17 14:01:32.443  6889  6889 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:01:32.445  6889  6889 D PanProfile: Bluetooth service connected
08-17 14:01:32.446  6889  6889 D BluetoothMap: Proxy object connected
08-17 14:01:32.447  6889  6889 D MapProfile: Bluetooth service connected
08-17 14:01:32.447  6889  6889 D BluetoothMap: getConnectedDevices()
08-17 14:01:32.447  6889  6889 D BluetoothMap: Bluetooth is Not enabled
08-17 14:01:32.448  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 14:01:32.501  1035  2003 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6952 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-17 14:01:32.504  1035  2003 I ActivityManager: Killing 2174:com.lge.music/u0a34 (adj 15): empty #17
,08-17 14:01:32.530   318  2197 V AudioFlinger: 2174 died, releasing its sessions
08-17 14:01:32.530   318  2197 V AudioFlinger:  pid 1853 @ 0
08-17 14:01:32.530   318  2197 V AudioFlinger:  pid 3418 @ 1
08-17 14:01:32.530   318  2197 V AudioFlinger:  pid 3418 @ 2
,08-17 14:01:32.561  1035  1050 W libprocessgroup: failed to open /acct/uid_10034/pid_2174/cgroup.procs: No such file or directory
,08-17 14:01:32.568  6930  6930 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-17 14:01:32.569  6930  6930 W LG Account v2.2: No ProfileInfo entries
08-17 14:01:32.569  6930  6930 I LG Account v2.2: isEnabled: false
08-17 14:01:32.569  6930  6930 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 14:01:32.569  6930  6930 I Feature : [Lifetracker]Country: EU
08-17 14:01:32.569  6930  6930 I Feature : [Lifetracker]Operator: OPEN
08-17 14:01:32.569  6930  6930 I Feature : [Lifetracker]Ranking support: false
08-17 14:01:32.569  6930  6930 I Feature : [Lifetracker]Comfort support: false
08-17 14:01:32.569  6930  6930 I Feature : [Lifetracker]Accessory: true
08-17 14:01:32.569  6930  6930 I Feature : [Lifetracker]Health device: true
08-17 14:01:32.570  6930  6930 I Feature : [Lifetracker]Extra Pedometer: false
08-17 14:01:32.570  6930  6930 I Feature : [Lifetracker]Blood glucose device: false
08-17 14:01:32.570  6930  6930 I Feature : [Lifetracker]Device Number: 3
08-17 14:01:32.579  6889  6889 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 14:01:32.588  6889  6889 D BluetoothPermissionRequest: onReceive
08-17 14:01:32.592  6889  6889 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 14:01:32.607  6952  6952 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 14:01:32.611  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:01:32.613  1035  1958 I ActivityManager: Killing 6434:com.android.defcontainer/u0a4 (adj 15): empty #17
08-17 14:01:32.672  3875  3875 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-17 14:01:32.672  3875  3875 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-17 14:01:32.673  3875  3875 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-17 14:01:32.677  1035  1776 W libprocessgroup: failed to open /acct/uid_10004/pid_6434/cgroup.procs: No such file or directory
08-17 14:01:32.680  6952  6952 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-17 14:01:32.691  3875  3875 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:32.691  3875  3875 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-17 14:01:32.694  3875  3875 V BluetoothFtpService: Ftp Service onStartCommand
08-17 14:01:32.694  3875  3875 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:32.694  3875  3875 V BluetoothFtpService: Ftp Service closeService
08-17 14:01:32.695  3875  3875 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-17 14:01:32.696  3875  3875 V BluetoothFtpService: successfully stopped ftp service
08-17 14:01:32.697  3875  3875 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:01:32.697  3875  3875 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:01:32.697  3875  3875 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:01:32.697  3875  3875 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:32.697  3875  3875 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 14:01:32.697  3875  3875 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 14:01:32.698  3875  3875 V BluetoothFtpService: Ftp Service onDestroy
08-17 14:01:32.698  3875  3875 V BluetoothFtpService: Ftp Service closeService
08-17 14:01:32.722  6952  6952 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-17 14:01:32.722  6952  6952 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-17 14:01:32.723  6952  6952 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-17 14:01:32.724  6952  6952 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-17 14:01:32.724  6952  6952 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-17 14:01:32.726  6952  6952 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-17 14:01:32.732  6952  6952 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-17 14:01:32.755  1035  2027 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6975 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 14:01:32.758  3875  3875 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:32.758  3875  3875 V BluetoothSapService: state: 13
08-17 14:01:32.758  3875  3875 V BluetoothSapService: Stopping SAP server process
08-17 14:01:32.761  3875  3875 V BluetoothSapService: Sap Service closeSapService in
08-17 14:01:32.762  3875  3875 V BluetoothSapService: Close listen Socket : 
08-17 14:01:32.763  3875  3875 V BluetoothSapService: Close rfcomm Socket : 
08-17 14:01:32.763  3875  3875 V BluetoothSapService: Close sapd  Socket : 
08-17 14:01:32.764  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:32.765  3875  3875 V BluetoothSapService: Sap Service closeSapService out
08-17 14:01:32.766  3875  3875 V BluetoothSapService: Sap Service onDestroy
08-17 14:01:32.766  3875  3875 V BluetoothSapService: Sap Service closeSapService in
08-17 14:01:32.766  3875  3875 V BluetoothSapService: Close listen Socket : 
08-17 14:01:32.766  3875  3875 V BluetoothSapService: Close rfcomm Socket : 
08-17 14:01:32.766  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:32.766  3875  3875 V BluetoothSapService: Close sapd  Socket : 
08-17 14:01:32.769  3875  3875 V BluetoothSapService: Sap Service closeSapService out
08-17 14:01:32.776   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 386us total 21.527ms
,08-17 14:01:32.783  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:01:32.785  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:32.788  6907  6907 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-17 14:01:32.788  6907  6907 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:01:32.788  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:32.790  6952  6952 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-17 14:01:32.791  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:32.793   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 343us total 16.530ms
08-17 14:01:32.795  6952  6952 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-17 14:01:32.798  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:32.804  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 14:01:32.804  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:32.806  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:01:32.808  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:32.809   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 338us total 15.257ms
08-17 14:01:32.814  6975  6975 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:01:32.814  6907  6907 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 14:01:32.814  6907  6907 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:01:32.814  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:32.816  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:01:32.821  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:32.825  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:32.825  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:32.826  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:01:32.866  1035  1958 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6995 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-17 14:01:32.867  1035  1958 I ActivityManager: Killing 6551:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-17 14:01:32.898  1035  2027 W libprocessgroup: failed to open /acct/uid_10008/pid_6551/cgroup.procs: No such file or directory
,08-17 14:01:32.945  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:01:32.953  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 14:01:32.959  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:32.971  6995  7014 W FormManager: Network not available. Please check & try again.
,08-17 14:01:32.986  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:01:32.986  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 14:01:32.986  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:01:32.986  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 14:01:32.987  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-17 14:01:32.988  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
08-17 14:01:32.994  6995  7015 V FormManager: Network unavailable.
08-17 14:01:32.997  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 14:01:32.997  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 14:01:32.997  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:01:32.997  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:01:32.997  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:01:32.998  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 14:01:33.004  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-17 14:01:33.005  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:01:33.006  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:01:33.007  6995  7015 V FormManager: Network unavailable.
08-17 14:01:33.011  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 14:01:33.022  4371  7018 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:01:33.025  6907  6907 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 14:01:33.025  6907  6907 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:01:33.025  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:33.028  4371  7019 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:01:33.029  4371  7019 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 14:01:33.031  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 14:01:33.037  6995  7020 W FormManager: Network not available. Please check & try again.
08-17 14:01:33.038  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:33.046  6995  7021 V FormManager: Network unavailable.
,08-17 14:01:33.049  6995  7021 V FormManager: Network unavailable.
,08-17 14:01:33.055  1035  1051 I ActivityManager: Killing 6110:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-17 14:01:33.083  1035  1922 W libprocessgroup: failed to open /acct/uid_10011/pid_6110/cgroup.procs: No such file or directory
,08-17 14:01:33.089  6952  6952 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 14:01:33.090  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 14:01:33.091  6952  6952 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-17 14:01:33.103  3875  3978 D bt_hci_bdroid: cleanup
08-17 14:01:33.103  3875  4103 I bt_lpm  : LPM is already off!!!
,08-17 14:01:33.104  3875  4278 I bt_userial_mct: exiting userial_read_thread
,08-17 14:01:33.104  3875  4278 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 14:01:33.104  3875  4098 W bt-btif : ag scb idx 1 not allocated
08-17 14:01:33.104  3875  4098 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 14:01:33.104  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:33.104  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:33.105  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:33.105  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:33.105  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:33.105  3875  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:01:33.105  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:33.105  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:33.105  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:33.105  3875  3978 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 14:01:33.106  3875  4103 I bt_vendor: hw_epilog_process
08-17 14:01:33.106  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:33.106  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:33.106  3875  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:01:33.106  3875  3978 D bt_hci_bdroid: cleanup Finalizing cleanup
08-17 14:01:33.106  3875  3978 D bt_userial_mct: userial_close
08-17 14:01:33.106  3875  3978 E bt_userial_mct: pthread_join() FAILED result:3
08-17 14:01:33.106  3875  3978 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 14:01:33.107  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:33.107  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:33.107  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:33.107  3875  4098 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:33.107  3875  4098 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:33.107  3875  4098 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:01:33.107  3875  4098 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 14:01:33.140  6952  6952 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:01:33.141  6952  6952 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:01:33.149  6952  6952 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-17 14:01:33.150  6952  6952 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-17 14:01:33.150  6952  6952 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-17 14:01:33.150  6952  6952 V SoundPool: doLoad: loading sample sampleID=1
08-17 14:01:33.151  6952  6952 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-17 14:01:33.154  6952  6952 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 14:01:33.156  6952  7028 V SoundPool: Start decode
08-17 14:01:33.156  6952  7028 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-17 14:01:33.157  6800  6800 D UEI.SmartControl: QS Service created
08-17 14:01:33.158   318  2208 V MediaPlayerService: decode(23, 10857164, 17813)
08-17 14:01:33.158   318  2208 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-17 14:01:33.158   318  2208 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-17 14:01:33.158   318  2208 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-17 14:01:33.158   318  2208 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-17 14:01:33.158   318  2208 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-17 14:01:33.158   318  2208 V MediaPlayerService: player type = 3
08-17 14:01:33.158   318  2208 V AwesomePlayer: AwesomePlayer create()
08-17 14:01:33.159   318  2208 V AwesomePlayer: reset_l() 
08-17 14:01:33.159   318  2208 V AwesomePlayer: cancelPlayerEvents
08-17 14:01:33.159   318  2208 V AwesomePlayer: setAudioSink() 
08-17 14:01:33.159   318  2208 V AwesomePlayer: reset_l() 
08-17 14:01:33.159   318  2208 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-17 14:01:33.159   318  2208 V AudioCache: ignored
08-17 14:01:33.159   318  2208 V AwesomePlayer: cancelPlayerEvents
08-17 14:01:33.159   318  2208 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-17 14:01:33.159   318  2208 V AwesomePlayer: setDataSource_l dataSource
08-17 14:01:33.159   318  2208 V LGParserOSAL: SniffLGParser start
08-17 14:01:33.159   318  2208 V LGParserOSAL: MainType:5, SubType=0
08-17 14:01:33.159   318  2208 V LGParserOSAL: #### check Mime : application/ogg
08-17 14:01:33.159   318  2208 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-17 14:01:33.159   318  2208 E MediaExtractor: Use LGExtractor :application/ogg 
,08-17 14:01:33.167  6952  6952 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 14:01:33.168  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-17 14:01:33.185  6800  6800 I UEI.SmartControl: Service initServices...
08-17 14:01:33.185  6800  6800 D UEI.SmartControl: QS start get config
,08-17 14:01:33.197   318  2208 V LGParserOSAL: supported mime: application/ogg
08-17 14:01:33.197   318  2208 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-17 14:01:33.197   318  2208 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-17 14:01:33.197   318  2208 V AwesomePlayer: mBitrate = -1 bits/sec
08-17 14:01:33.197   318  2208 V AwesomePlayer: AudioTrack Setting
08-17 14:01:33.197   318  2208 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-17 14:01:33.197   318  2208 V AwesomePlayer: setAudioSource() 
08-17 14:01:33.197   318  2208 V MediaPlayerService: prepare
08-17 14:01:33.197   318  2208 V AwesomePlayer: prepareAsync_l() 
08-17 14:01:33.197   318  2208 V MediaPlayerService: wait for prepare
08-17 14:01:33.197   318  7029 V AwesomePlayer: onPrepareAsyncEvent() 
08-17 14:01:33.197   318  7029 V AwesomePlayer: initAudioDecoder() 
08-17 14:01:33.197   318  7029 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 14:01:33.197   318  7029 V AudioSystem: isOffloadSupported()
08-17 14:01:33.197   318  7029 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 14:01:33.197   318  7029 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 14:01:33.197   318  7029 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 14:01:33.197   318  7029 V AwesomePlayer: getUseOffload() = 0 
08-17 14:01:33.197   318  7029 V OMXCodec: OMXCodec::Create
08-17 14:01:33.197   318  7029 V OMXCodec: findMatchingCodecs()
08-17 14:01:33.197   318  7029 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-17 14:01:33.198   318  7029 V OMXCodec: matchingCodecs.size()=1
08-17 14:01:33.198   318  7029 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-17 14:01:33.199   318  7029 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-17 14:01:33.200   318  7029 V LGCodecAdapter: LG Codec Adapter start
08-17 14:01:33.200   318  7029 V OMXCodec: OMXCodec Createtor
08-17 14:01:33.200   318  7029 V OMXCodec: setComponentRole
08-17 14:01:33.200   318  7029 V OMXCodec: configureCodec protected=0
08-17 14:01:33.200   318  7029 V LGCodecAdapter: called getLGCodecSpecificData
08-17 14:01:33.200   318  7029 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-17 14:01:33.200   318  7029 V LGCodecOSAL: Called LGconfigureCodecMETA
08-17 14:01:33.200   318  7029 V LGCodecOSAL: Called LGconfigureCodecMSG
08-17 14:01:33.200   318  7029 V LGCodecOSAL: Not support LGCodec
08-17 14:01:33.200   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 14:01:33.200   318  7029 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-17 14:01:33.200   318  7029 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-17 14:01:33.200   318  7029 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-17 14:01:33.200   318  7029 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 14:01:33.200   318  7029 V AudioSystem: isOffloadSupported()
08-17 14:01:33.201   318  7029 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 14:01:33.201   318  7029 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 14:01:33.201   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-17 14:01:33.201   318  7029 V OMXCodec: init()
08-17 14:01:33.201   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-17 14:01:33.202   318  7029 V OMXCodec: allocateBuffers
08-17 14:01:33.202   318  7029 V OMXCodec: allocateBuffersOnPort portIndex=0
08-17 14:01:33.202   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-17 14:01:33.203   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-17 14:01:33.203  6952  6952 V LGMDMManager: Create singleton instance
08-17 14:01:33.203   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-17 14:01:33.203   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-17 14:01:33.203   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-17 14:01:33.203   318  7029 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 14:01:33.203   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 14:01:33.204   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-17 14:01:33.204   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-17 14:01:33.204   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-17 14:01:33.204   318  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-17 14:01:33.204   318  7029 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-17 14:01:33.206   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 14:01:33.206   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 14:01:33.206   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-17 14:01:33.207   318  7029 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 14:01:33.207   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-17 14:01:33.207   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-17 14:01:33.207   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-17 14:01:33.207   318  7029 V OMXCodec: init() mAsyncCompletion wait free! 
08-17 14:01:33.207   318  7029 V AwesomePlayer: finishAsyncPrepare_l() 
08-17 14:01:33.207   318  7029 V AudioCache: notify(0xb5474940, 5, 0, 0)
08-17 14:01:33.207   318  7029 V AudioCache: ignored
08-17 14:01:33.207   318  7029 V AudioCache: notify(0xb5474940, 1, 0, 0)
08-17 14:01:33.207   318  7029 V AudioCache: prepared
08-17 14:01:33.207   318  2208 V AudioCache: wait - success
08-17 14:01:33.207   318  2208 V MediaPlayerService: start
08-17 14:01:33.207   318  2208 V AwesomePlayer: play_l() 
08-17 14:01:33.207   318  2208 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-17 14:01:33.207   318  2208 V AwesomePlayer: createAudioPlayer_l
08-17 14:01:33.207   318  2208 V AwesomePlayer: seekAudioIfNecessary_l() 
08-17 14:01:33.207   318  2208 V AwesomePlayer: startAudioPlayer_l() 
08-17 14:01:33.207   318  2208 D AudioPlayer: start of Playback, useOffload 0
08-17 14:01:33.207   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 14:01:33.208   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 14:01:33.210   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-17 14:01:33.210   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-17 14:01:33.210   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-17 14:01:33.212   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-17 14:01:33.213   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-17 14:01:33.214   318  7031 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 14:01:33.214   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 14:01:33.214   318  7031 V OMXCod,ec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-17 14:01:33.214   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-17 14:01:33.214   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-17 14:01:33.214   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-17 14:01:33.214   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-17 14:01:33.214   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-17 14:01:33.216   318  2208 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-17 14:01:33.216   318  2208 V AudioCache: notify(0xb5474940, 6, 0, 0)
08-17 14:01:33.216   318  2208 V AudioCache: ignored
08-17 14:01:33.217   318  2208 V MediaPlayerService: wait for playback complete
,08-17 14:01:33.218   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.218   318  7032 V AudioCache: memcpy(0xaf006000, 0xb16e4000, 4096)
08-17 14:01:33.220   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.221   318  7032 V AudioCache: memcpy(0xaf007000, 0xb16e4000, 4096)
08-17 14:01:33.221   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.221   318  7032 V AudioCache: memcpy(0xaf008000, 0xb16e4000, 4096)
08-17 14:01:33.221   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.221   318  7032 V AudioCache: memcpy(0xaf009000, 0xb16e4000, 4096)
08-17 14:01:33.222   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.222   318  7032 V AudioCache: memcpy(0xaf00a000, 0xb16e4000, 4096)
08-17 14:01:33.223   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.223   318  7032 V AudioCache: memcpy(0xaf00b000, 0xb16e4000, 4096)
08-17 14:01:33.223   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.223   318  7032 V AudioCache: memcpy(0xaf00c000, 0xb16e4000, 4096)
08-17 14:01:33.224   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.224   318  7032 V AudioCache: memcpy(0xaf00d000, 0xb16e4000, 4096)
08-17 14:01:33.225   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.225   318  7032 V AudioCache: memcpy(0xaf00e000, 0xb16e4000, 4096)
08-17 14:01:33.226   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.226   318  7032 V AudioCache: memcpy(0xaf00f000, 0xb16e4000, 4096)
08-17 14:01:33.227   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.227   318  7032 V AudioCache: memcpy(0xaf010000, 0xb16e4000, 4096)
08-17 14:01:33.227   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.227   318  7032 V AudioCache: memcpy(0xaf011000, 0xb16e4000, 4096)
08-17 14:01:33.228   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.228   318  7032 V AudioCache: memcpy(0xaf012000, 0xb16e4000, 4096)
08-17 14:01:33.229   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.229   318  7032 V AudioCache: memcpy(0xaf013000, 0xb16e4000, 4096)
08-17 14:01:33.230   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.230   318  7032 V AudioCache: memcpy(0xaf014000, 0xb16e4000, 4096)
08-17 14:01:33.231   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.231   318  7032 V AudioCache: memcpy(0xaf015000, 0xb16e4000, 4096)
08-17 14:01:33.231   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.231   318  7032 V AudioCache: memcpy(0xaf016000, 0xb16e4000, 4096)
08-17 14:01:33.232   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.232   318  7032 V AudioCache: memcpy(0xaf017000, 0xb16e4000, 4096)
08-17 14:01:33.233   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.233   318  7032 V AudioCache: memcpy(0xaf018000, 0xb16e4000, 4096)
08-17 14:01:33.234   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.234   318  7032 V AudioCache: memcpy(0xaf019000, 0xb16e4000, 4096)
08-17 14:01:33.235   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.235   318  7032 V AudioCache: memcpy(0xaf01a000, 0xb16e4000, 4096)
08-17 14:01:33.235   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.235   318  7032 V AudioCache: memcpy(0xaf01b000, 0xb16e4000, 4096)
08-17 14:01:33.236   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.236   318  7032 V AudioCache: memcpy(0xaf01c000, 0xb16e4000, 4096)
08-17 14:01:33.237   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.237   318  7032 V AudioCache: memcpy(0xaf01d000, 0xb16e4000, 4096)
08-17 14:01:33.238   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.238   318  7032 V AudioCache: memcpy(0xaf01e000, 0xb16e4000, 4096)
08-17 14:01:33.239   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.239   318  7032 V AudioCache: memcpy(0xaf01f000, 0xb16e4000, 4096)
08-17 14:01:33.239   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.239   318  7032 V AudioCache: mem,cpy(0xaf020000, 0xb16e4000, 4096)
08-17 14:01:33.241   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.241   318  7032 V AudioCache: memcpy(0xaf021000, 0xb16e4000, 4096)
08-17 14:01:33.242   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.242   318  7032 V AudioCache: memcpy(0xaf022000, 0xb16e4000, 4096)
,08-17 14:01:33.243   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.243   318  7032 V AudioCache: memcpy(0xaf023000, 0xb16e4000, 4096)
08-17 14:01:33.243   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.243   318  7032 V AudioCache: memcpy(0xaf024000, 0xb16e4000, 4096)
08-17 14:01:33.244   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.244   318  7032 V AudioCache: memcpy(0xaf025000, 0xb16e4000, 4096)
08-17 14:01:33.246   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.246   318  7032 V AudioCache: memcpy(0xaf026000, 0xb16e4000, 4096)
08-17 14:01:33.247   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.247   318  7032 V AudioCache: memcpy(0xaf027000, 0xb16e4000, 4096)
08-17 14:01:33.248   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.248   318  7032 V AudioCache: memcpy(0xaf028000, 0xb16e4000, 4096)
08-17 14:01:33.249   318  7032 V AudioCache: write(0xb16e4000, 4096)
,08-17 14:01:33.249   318  7032 V AudioCache: memcpy(0xaf029000, 0xb16e4000, 4096)
08-17 14:01:33.249   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.249   318  7032 V AudioCache: memcpy(0xaf02a000, 0xb16e4000, 4096)
08-17 14:01:33.254   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.254   318  7032 V AudioCache: memcpy(0xaf02b000, 0xb16e4000, 4096)
08-17 14:01:33.256   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.256   318  7032 V AudioCache: memcpy(0xaf02c000, 0xb16e4000, 4096)
08-17 14:01:33.257   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.257   318  7032 V AudioCache: memcpy(0xaf02d000, 0xb16e4000, 4096)
08-17 14:01:33.258   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.258   318  7032 V AudioCache: memcpy(0xaf02e000, 0xb16e4000, 4096)
08-17 14:01:33.259   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.259   318  7032 V AudioCache: memcpy(0xaf02f000, 0xb16e4000, 4096)
08-17 14:01:33.261   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.261   318  7032 V AudioCache: memcpy(0xaf030000, 0xb16e4000, 4096)
08-17 14:01:33.262   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.262   318  7032 V AudioCache: memcpy(0xaf031000, 0xb16e4000, 4096)
,08-17 14:01:33.263   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.263   318  7032 V AudioCache: memcpy(0xaf032000, 0xb16e4000, 4096)
08-17 14:01:33.264   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.264   318  7032 V AudioCache: memcpy(0xaf033000, 0xb16e4000, 4096)
08-17 14:01:33.265   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.265   318  7032 V AudioCache: memcpy(0xaf034000, 0xb16e4000, 4096)
08-17 14:01:33.266   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.266   318  7032 V AudioCache: memcpy(0xaf035000, 0xb16e4000, 4096)
08-17 14:01:33.267   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.267   318  7032 V AudioCache: memcpy(0xaf036000, 0xb16e4000, 4096)
08-17 14:01:33.268   318  7032 V AudioCache: write(0xb16e4000, 4096)
08-17 14:01:33.268   318  7032 V AudioCache: memcpy(0xaf037000, 0xb16e4000, 4096)
08-17 14:01:33.269   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-17 14:01:33.269   318  7032 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 14:01:33.269   318  7032 V AwesomePlayer: postAudioEOS() 
08-17 14:01:33.269   318  7032 V AudioCache: write(0xb16e4000, 280)
08-17 14:01:33.269   318  7032 V AudioCache: memcpy(0xaf038000, 0xb16e4000, 280)
08-17 14:01:33.270  3875  3978 D bt_hci_bdroid: set_power 0
08-17 14:01:33.271  3875  3978 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 14:01:33.271  3875  3978 I bt_vendor: bluetooth satus is on
08-17 14:01:33.271  3875  3978 I bt_vendor: bt-vendor : resetting BT status
08-17 14:01:33.271  3875  3978 I bt_vendor: Starting hciattach daemon
08-17 14:01:33.271  3875  3978 I bt_vendor: try to set false
08-17 14:01:33.271   318  7029 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-17 14:01:33.271   318  7029 V AwesomePlayer: onStreamDone
08-17 14:01:33.271   318  7029 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-17 14:01:33.271   318  7029 V AudioCache: notify(0xb5474940, 2, 0, 0)
08-17 14:01:33.271   318  7029 V AudioCache: playback complete
08-17 14:01:33.271   318  7029 V AwesomePlayer: pause_l() 
08-17 14:01:33.271   318  7029 V AudioCache: notify(0xb5474940, 7, 0, 0)
08-17 14:01:33.271   318  7029 V AudioCache: ignored
08-17 14:01:33.271   318  7029 V AwesomePlayer: cancelPlayerEvents
08-17 14:01:33.271  3875  3978 I bt_vendor: Starting hciattach daemon
08-17 14:01:33.271  3875  3978 I bt_vendor: try to set false
08-17 14:01:33.272  3875  3978 I bt_vendor: cleanup
,08-17 14:01:33.273   318  7029 D AudioPlayer: Pause Playback at 1068125
08-17 14:01:33.273  3875  4098 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 14:01:33.273  3875  3978 I GKI_LINUX: GKI_exit_task 0 done
08-17 14:01:33.273  3875  3978 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 14:01:33.274  3875  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 14:01:33.277   318  2208 V AudioCache: wait - success
08-17 14:01:33.277   318  2208 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-17 14:01:33.277   318  2208 V AwesomePlayer: reset_l() 
08-17 14:01:33.277   318  2208 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-17 14:01:33.277   318  2208 V AudioCache: ignored
08-17 14:01:33.277   318  2208 V AwesomePlayer: cancelPlayerEvents
08-17 14:01:33.277   318  2208 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-17 14:01:33.277   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-17 14:01:33.277   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-17 14:01:33.277   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-17 14:01:33.277   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 14:01:33.277  3875  3875 D HeadsetService: Received stop request...Stopping profile...
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 14:01:33.277  3875  3875 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-17 14:01:33.277   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-17 14:01:33.277  3875  3875 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:01:33.277  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16c9f447
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-17 14:01:33.278  3875  3993 D HeadsetStateMachine: Exit Disconnected: -1
08-17 14:01:33.278   3,18  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 14:01:33.278   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-17 14:01:33.278   318  7031 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-17 14:01:33.278   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 14:01:33.278   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-17 14:01:33.279   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-17 14:01:33.279  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:33.279  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 14:01:33.280  3875  3875 D A2dpService: Received stop request...Stopping profile...
08-17 14:01:33.280  3875  4069 D A2dpStateMachine: Exit Disconnected: -1
08-17 14:01:33.280   318  2208 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-17 14:01:33.280  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-17 14:01:33.280   318  2208 D AudioPlayer: AudioPlayer releasing audio source
08-17 14:01:33.280   318  2208 D AudioPlayer: AudioPlayer done releasing audio source
08-17 14:01:33.281   318  2208 V AwesomePlayer: reset_l() 
08-17 14:01:33.281   318  2208 V AwesomePlayer: cancelPlayerEvents
08-17 14:01:33.281   318  2208 V AwesomePlayer: ~AwesomePlayer call
08-17 14:01:33.279  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:33.281  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:33.281  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:33.281   318  2208 V AwesomePlayer: reset_l() 
08-17 14:01:33.281   318  2208 V AwesomePlayer: cancelPlayerEvents
08-17 14:01:33.282  6952  7028 V SoundPool: close(31)
08-17 14:01:33.282  6952  7028 V SoundPool: pointer = 0x9fe96000, size = 205080, sampleRate = 48000, numChannels = 2
08-17 14:01:33.283  3875  3875 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 14:01:33.283  3875  3875 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:01:33.283  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16c9f447
08-17 14:01:33.283  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-17 14:01:33.283  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 14:01:33.284  3875  3972 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 14:01:33.285  3875  3875 D HeadsetStateMachine: Unbinding service...
,08-17 14:01:33.286  3875  3875 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:01:33.286  3875  3875 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-17 14:01:33.286  3875  3875 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:01:33.286  3875  3875 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:01:33.286  3875  3875 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 14:01:33.286  3875  3875 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:01:33.286  3875  3875 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 14:01:33.286  3875  3875 D HidService: Received stop request...Stopping profile...
08-17 14:01:33.286  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16c9f447
08-17 14:01:33.287  6889  6889 D BluetoothInputDevice: Proxy object disconnected
08-17 14:01:33.287  6889  6889 D HidProfile: Bluetooth service disconnected
08-17 14:01:33.287  3875  3875 D HealthService: Received stop request...Stopping profile...
,08-17 14:01:33.288  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16c9f447
08-17 14:01:33.290  3875  3875 D PanService: Received stop request...Stopping profile...
08-17 14:01:33.291  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16c9f447
08-17 14:01:33.291  6889  6889 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 14:01:33.291  6889  6889 D PanProfile: Bluetooth service disconnected
08-17 14:01:33.291  3875  3875 I BluetoothA2dpServiceJni: cleanupNative
08-17 14:01:33.292  3875  4070 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 14:01:33.292  3875  3875 I GKI_LINUX: GKI_exit_task 2 done
08-17 14:01:33.292  3875  3875 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 14:01:33.292  3875  3875 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 14:01:33.292  3875  3875 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 14:01:33.292  3875  3875 D BtGatt.GattService: stop()
08-17 14:01:33.293  3875  3875 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 14:01:33.293  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16c9f447
,08-17 14:01:33.294  3875  3875 D BluetoothMapService: Received stop request...Stopping profile...
08-17 14:01:33.294  3875  3875 D BluetoothMapService: stop()
08-17 14:01:33.294  3875  3875 D BluetoothMapEmailAppObserver: deinitObservers()
08-17 14:01:33.295  3875  3875 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 14:01:33.295  3875  3875 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16c9f447
08-17 14:01:33.295  6889  6889 D BluetoothMap: Proxy object disconnected
08-17 14:01:33.296  6889  6889 D MapProfile: Bluetooth service disconnected
08-17 14:01:33.296  3875  3875 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:01:33.296  3875  3875 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 14:01:33.296  3875  3875 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 14:01:33.296  3875  3875 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:01:33.296  3875  3875 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:01:33.296  3875  3875 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 14:01:33.296  3875  3875 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 14:01:33.297  3875  3875 V BluetoothMapService: Handler(): got msg=4
08-17 14:01:33.297  3875  3875 D BluetoothMapService: MAP Service closeService in
08-17 14:01:33.297  3875  3875 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:01:33.297  3875  3875 V BluetoothMapService: MAP Service closeService out
08-17 14:01:33.298  3875  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 14:01:33.298  3875  3972 D BluetoothAdapterProperties: Setting state to 10
08-17 14:01:33.298  3875  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 14:01:33.298  1035  1111 D BluetoothManagerService: Message: 60
08-17 14:01:33.299  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 14:01:33.299  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-17 14:01:33.299  3875  3875 D BluetoothMapService: cleanup()
08-17 14:01:33.299  3875  3875 D BluetoothMapService: MAP Service closeService in
08-17 14:01:33.299  3875  3875 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:01:33.299  3875  3875 V BluetoothMapService: MAP Service closeService out
08-17 14:01:33.300  3875  3972 I BluetoothAdapterState: Entering OffState
08-17 14:01:33.300  1853  2459 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:33.301  6889  6906 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:01:33.301  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-17 14:01:33.301  6889  6905 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:01:33.302  1853  2461 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:33.302  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-17 14:01:33.302  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:01:33.302  6889  6906 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 14:01:33.303  6889  6905 D BluetoothMap: onBluetoothStateChange: up=false
08-17 14:01:33.303  1853  3528 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:33.304  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4278
08-17 14:01:33.304  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:33.305  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 14:01:33.305  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-17 14:01:33.307  1035  1111 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 14:01:33.307  1035  1111 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 14:01:33.307  1035  1111 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1a02dd8f mBinding = false
08-17 14:01:33.308  1035  1111 D BluetoothManagerService: Sending unbind request.
08-17 14:01:33.308  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-17 14:01:33.310  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:01:33.313  6889  6889 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:01:33.313  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 14:01:33.313  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:33.313  6889  6889 D LGBluetoothEventManager: [BTUI] clear device connection state
08-17 14:01:33.314  1941  2104 D LGBluetoothAPIService: Message: 2
08-17 14:01:33.314  1941  2104 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3a2a8e56 mBinding = false
08-17 14:01:33.314  1941  2104 D LGBluetoothAPIService: Sending unbind request.
08-17 14:01:33.315  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:33.315  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:33.315  1602  1602 D BluetoothAdapter: 249548254: getState() :  mService = null. Returning STATE_OFF
08-17 14:01:33.316  1602  1602 D BluetoothAdapter: 249548254: getState() :  mService = null. Returning STATE_OFF
08-17 14:01:33.320  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 14:01:33.326  3875  3978 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 14:01:33.326  3875  3875 I GKI_LINUX: GKI_exit_task 1 done
,08-17 14:01:33.326  3875  3875 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 14:01:33.326  3875  3875 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 14:01:33.327  3875  3875 I art     : --- WEIRD: removing null entry 246
08-17 14:01:33.327  3875  3875 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-17 14:01:33.327  3875  3875 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 14:01:33.327  6889  6889 D DockEventReceiver: finishStartingService: stopping service
08-17 14:01:33.327  3875  3875 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-17 14:01:33.330  3875  3875 I art     : System.exit called, status: 0
08-17 14:01:33.330  3875  3875 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 14:01:33.347   318  1397 V AudioFlinger: 3875 died, releasing its sessions
08-17 14:01:33.347   318  1397 V AudioFlinger:  pid 1853 @ 0
08-17 14:01:33.347   318  1397 V AudioFlinger:  pid 3418 @ 1
08-17 14:01:33.347   318  1397 V AudioFlinger:  pid 3418 @ 2
08-17 14:01:33.347  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-17 14:01:33.391  1035  1051 I ActivityManager: Process com.android.bluetooth (pid 3875) has died
,08-17 14:01:33.392  1035  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-17 14:01:33.397  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:01:33.409  6889  6889 D BluetoothPermissionRequest: onReceive
,08-17 14:01:33.411  6889  6889 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-17 14:01:33.412  6889  6889 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-17 14:01:33.415  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:01:33.497  1035  1778 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7041 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-17 14:01:33.552  7041  7041 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 14:01:33.552  7041  7041 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:01:33.552  7041  7041 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-17 14:01:33.553  7041  7041 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 14:01:33.558  6800  6800 I UEI.SmartControl: Supports setup maps: true
08-17 14:01:33.561  6800  6800 D UEI.SmartControl: QS start statue = true Error code = 0
08-17 14:01:33.561  6800  6800 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 14:01:33.561  6800  6800 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 14:01:33.561  6800  6800 I UEI.SmartControl: ### init IR Blaster...
08-17 14:01:33.564  6800  6800 D serial_port: Configuring serial port
,08-17 14:01:33.564  6800  6800 E UEI.SmartControl: UEIBLaster setting for 616
,08-17 14:01:33.564  6800  6800 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 14:01:33.564  6800  6800 I UEI.SmartControl: configuring settings for MAXQ616
08-17 14:01:33.564  6800  6800 I UEI.SmartControl: Get version...
08-17 14:01:33.569  7041  7041 D BluetoothAdapterApp: Loading JNI Library
08-17 14:01:33.581  6800  7058 D UEI.SmartControl: serial port data available: 21
,08-17 14:01:33.600  7041  7041 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@115ba5dc Instance Count = 1
,08-17 14:01:33.605  7041  7041 D BluetoothAdapterApp: onCreate
08-17 14:01:33.607  6800  6800 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-17 14:01:33.607  6800  6800 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-17 14:01:33.607  6800  6800 I UEI.SmartControl: QS saving settings...
08-17 14:01:33.611  6800  6800 D UEI.SmartControl: IR Blaster version: 25672567
08-17 14:01:33.626  6800  7058 D UEI.SmartControl: serial port data available: 4
08-17 14:01:33.626  7041  7041 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-17 14:01:33.626  7041  7041 D ProfileConfigQcom: Adding HeadsetService
08-17 14:01:33.626  7041  7041 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-17 14:01:33.626  7041  7041 D ProfileConfigQcom: Adding A2dpService
08-17 14:01:33.627  7041  7041 D ProfileConfigQcom: [BTUI] HidService is supported
08-17 14:01:33.627  7041  7041 D ProfileConfigQcom: Adding HidService
08-17 14:01:33.627  7041  7041 D ProfileConfigQcom: [BTUI] HealthService is supported
08-17 14:01:33.627  7041  7041 D ProfileConfigQcom: Adding HealthService
,08-17 14:01:33.627  7041  7041 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 14:01:33.628  7041  7041 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 14:01:33.628  7041  7041 D ProfileConfigQcom: Adding PanService
08-17 14:01:33.628  7041  7041 D ProfileConfigQcom: [BTUI] GattService is supported
08-17 14:01:33.629  7041  7041 D ProfileConfigQcom: Adding GattService
08-17 14:01:33.629  7041  7041 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-17 14:01:33.629  7041  7041 D ProfileConfigQcom: Adding BluetoothMapService
08-17 14:01:33.629  7041  7041 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 14:01:33.631  7041  7041 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-17 14:01:33.636  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 14:01:33.637  7041  7041 V LGMDMManagerInternal: Create singleton instance
08-17 14:01:33.657  6800  7065 I UEI.SmartControl: Device manager: loading config....
08-17 14:01:33.657  6800  7065 D UEI.SmartControl: ----------- loading internal config...
08-17 14:01:33.658  6800  6800 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-17 14:01:33.667  6800  6800 E UEI.SmartControl: Services init done
08-17 14:01:33.668  6800  6800 D UEI.SmartControl: QS Service init finished
08-17 14:01:33.669  6800  6800 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 14:01:33.669  6800  6800 D UEI.SmartControl: QS Service version code: 201091
08-17 14:01:33.670  6800  6800 D UEI.SmartControl: Service requested: Control
08-17 14:01:33.672  6800  7065 E UEI.SmartControl: Loading SETTINGS...
08-17 14:01:33.676  6800  6800 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-17 14:01:33.679  6952  6952 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-17 14:01:33.681  6800  6821 I UEI.SmartControl: ------ IControl API: 11
08-17 14:01:33.681  6800  6821 D UEI.SmartControl: File observer start...
08-17 14:01:33.681  6800  6821 E UEI.SmartControl: IR Port is disabled: false
08-17 14:01:33.682  6800  6821 D UEI.SmartControl: Starting file observer...
08-17 14:01:33.682  6800  6821 I UEI.SmartControl: Registering callback...
08-17 14:01:33.682  6800  6800 D UEI.SmartControl: Internal service binding...
08-17 14:01:33.683  6800  7065 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-17 14:01:33.683  6800  6820 I UEI.SmartControl: ------ IControl API: 19
08-17 14:01:33.685  6800  6820 I UEI.SmartControl: Registering Services Ready callback...
08-17 14:01:33.690  7041  7041 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:01:33.695  6800  7064 I UEI.SmartControl: Notify AllClients services are ready: 0
08-17 14:01:33.695  7041  7041 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:01:33.695  7041  7041 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:01:33.695  7041  7041 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:01:33.696  7041  7041 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:33.696  6952  6969 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-17 14:01:33.696  7041  7041 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-17 14:01:33.696  6952  7026 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-17 14:01:33.697  6952  7026 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-17 14:01:33.697  6952  6952 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-17 14:01:33.697  6952  6952 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-17 14:01:33.698  6800  6821 I UEI.SmartControl: ------ IControl API: 8
08-17 14:01:33.699  6800  7064 D UEI.SmartControl: -----service ready thread exits
08-17 14:01:33.699  6952  6952 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-17 14:01:33.699  6952  6952 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-17 14:01:33.700  6952  6952 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-17 14:01:33.700  6952  6952 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-17 14:01:33.701  6952  6952 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-17 14:01:33.701  6952  6952 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-17 14:01:33.706  6952  6952 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-17 14:01:33.707  6975  6975 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-17 14:01:33.708  6952  6952 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 14:01:33.709  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 14:01:33.709  6952  6952 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 14:01:33.710  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-17 14:01:33.710  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-17 14:01:33.711  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-17 14:01:33.712  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-17 14:01:33.713  6952  6952 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471435293712]
08-17 14:01:33.714  6952  6952 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-17 14:01:33.715  1035  2027 I ActivityManager: Killing 6600:com.lge.email/u0a23 (adj 15): empty #17
,08-17 14:01:33.734  6952  7068 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0,
,08-17 14:01:33.742  1035  2027 I ActivityManager: Killing 6131:com.android.contacts/u0a19 (adj 15): empty #18
08-17 14:01:33.770  1035  1970 W libprocessgroup: failed to open /acct/uid_10023/pid_6600/cgroup.procs: No such file or directory
,08-17 14:01:33.775  1035  1647 W libprocessgroup: failed to open /acct/uid_10019/pid_6131/cgroup.procs: No such file or directory
08-17 14:01:33.775  6952  6952 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-17 14:01:33.776  6952  6952 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 14:01:33.776  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-17 14:01:33.776  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-17 14:01:33.776  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-17 14:01:33.777  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-17 14:01:33.777  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-17 14:01:33.787  6952  6952 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-17 14:01:33.907  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-17 14:01:33.908  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-17 14:01:33.922  1035  1473 D WifiController: battery changed pluggedType: 2
08-17 14:01:33.926  1941  2094 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-17 14:01:33.927  1941  2094 D LEDHandler: Battery Level Remaining: 100%
08-17 14:01:33.927  1941  2094 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
,08-17 14:01:33.929  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
08-17 14:01:33.929  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-17 14:01:33.935  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-17 14:01:33.941  6756  6756 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-17 14:01:34.944  1035  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{de7f25f type 2 when 129203 com.google.android.gms} when 129203
,08-17 14:01:34.958   314  7076 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-17 14:01:34.966  1035  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 14:01:35.007  1035  1483 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:35.022  1035  1111 D Tethering: MasterInitialState.processMessage what=3
08-17 14:01:35.035  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:35.039  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:35.040  1035  1483 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:35.047  1035  1111 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:01:35.057  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:35.058  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:35.061  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:35.063  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 14:01:35.066  6509  6534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 14:01:35.076  5854  5854 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 14:01:35.087  5854  5854 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 14:01:35.106  1035  2003 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 14:01:35.106  1035  2003 D WifiService: setWifiEnabled: true pid=6708, uid=10118
08-17 14:01:35.106  1035  2003 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:01:35.111  2198  2198 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:35.128  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:01:35.129  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:01:35.129  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-17 14:01:35.132  1035  1435 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-17 14:01:35.132  1035  1435 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-17 14:01:35.134  1035  1435 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-17 14:01:35.134  1035  1435 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 14:01:35.134  1035  1435 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 14:01:35.134  1035  1435 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 14:01:35.135  1035  1435 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 14:01:35.135  1035  1435 E WifiHW  : unknown target_country: EU , set to default
08-17 14:01:35.135  1035  1435 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-17 14:01:35.135  1035  1435 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-17 14:01:35.135  1035  1435 I WifiUtil: gEnableBmps=1
,08-17 14:01:35.174  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:35.211  1035  2027 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7091 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-17 14:01:35.221  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:35.222  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 14:01:35.297  7091  7091 I AppUp4:AppBoxCP: onCreate
,08-17 14:01:35.299  7091  7091 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-17 14:01:35.311  7091  7091 I AppUp4:DB:  setFingerPrint start
,08-17 14:01:35.312  7091  7091 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-17 14:01:35.323  7091  7091 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-17 14:01:35.323  7091  7091 I AppUp4:DB:  SDK version = 21
,08-17 14:01:35.323  7091  7091 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-17 14:01:35.325  7091  7091 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-17 14:01:35.327  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 14:01:35.327  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:35.329  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 14:01:35.330  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 14:01:35.336  7091  7091 I AppUp4:CustModeStarterReceiver: onReceive
08-17 14:01:35.385  7091  7091 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:01:35.386  7091  7091 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:01:35.396  7091  7091 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26b13386
08-17 14:01:35.396  7091  7091 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 14:01:35.396  7091  7091 D AppUp4:CustFacade: isPhone : true
08-17 14:01:35.397  7091  7091 D AppUp4:CustModeStarterReceiver: begin check event
08-17 14:01:35.397  7091  7091 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-17 14:01:35.397  7091  7091 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-17 14:01:35.399  7091  7112 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-17 14:01:35.399  7091  7112 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-17 14:01:35.399  7091  7112 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-17 14:01:35.400  1035  1575 I ActivityManager: Killing 6161:com.android.gallery3d/u0a27 (adj 15): empty #17
08-17 14:01:35.457  1035  1922 W libprocessgroup: failed to open /acct/uid_10027/pid_6161/cgroup.procs: No such file or directory
,08-17 14:01:35.458  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:35.459  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:01:35.467  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:01:35.471  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:01:35.482  4371  7114 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 14:01:35.486  4371  7115 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:35.486  4371  7115 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 14:01:35.545  1035  1933 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7119 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-17 14:01:35.612  7119  7119 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:01:35.613  7119  7119 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:01:35.614  7119  7119 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 14:01:35.614  7119  7119 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-17 14:01:35.689  7119  7119 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-17 14:01:35.701  7119  7119 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-17 14:01:35.732  7119  7119 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 14:01:35.756  7119  7119 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:01:35.756  7119  7119 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:01:35.853  1035  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 14:01:35.858   314   880 D SoftapController: Softap fwReload - Ok
08-17 14:01:35.859  1035  1435 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (718ms)
08-17 14:01:35.861   314   880 D CommandListener: Setting iface cfg
08-17 14:01:35.861   314   880 D CommandListener: Trying to bring down wlan0
08-17 14:01:35.862   314   880 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:01:35.866  1035  1435 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-17 14:01:35.867  1035  1435 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:01:35.867  1035  1435 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:01:35.867  1035  1435 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:01:35.869  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:35.869  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-17 14:01:35.871  1035  1435 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 14:01:35.871  1035  1435 D WifiMonitor: connecting to supplicant
08-17 14:01:35.871  1035  1435 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-17 14:01:35.871  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-17 14:01:35.866  7151  7151 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:35.866  7151  7151 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:35.875  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:35.881  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:35.898  7151  7151 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 14:01:35.931  7151  7151 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 14:01:35.932  7151  7151 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-17 14:01:35.934  1035  1111 D Tethering: InitialState.processMessage what=4
08-17 14:01:35.935  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:01:35.937  7119  7119 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 14:01:35.974  3418  3418 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 14:01:35.974  3418  3418 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:35.974  3418  3418 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-17 14:01:35.984  7119  7119 I HubEmail: JNI_OnLoad()
08-17 14:01:35.984  7119  7119 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 14:01:35.984  7119  7119 I HubEmail: registerNatives()
08-17 14:01:35.984  7119  7119 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 14:01:35.984  7119  7119 I HubEmail: registerNativeMethods()
08-17 14:01:35.984  7119  7119 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 14:01:35.984  7119  7119 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-17 14:01:35.990  7151  7151 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 14:01:36.010  1035  1776 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7168 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-17 14:01:36.014  7119  7166 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:36.016  6995  7163 W FormManager: Network not available. Please check & try again.
08-17 14:01:36.017  6995  7164 V FormManager: Network unavailable.
08-17 14:01:36.019  6995  7164 V FormManager: Network unavailable.
08-17 14:01:36.025  1035  1922 I ActivityManager: Killing 6243:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-17 14:01:36.041  7151  7151 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-17 14:01:36.052  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-17 14:01:36.054  1035  1776 W libprocessgroup: failed to open /acct/uid_10080/pid_6243/cgroup.procs: No such file or directory
,08-17 14:01:36.109  7168  7168 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 14:01:36.109  7168  7168 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:01:36.113  7168  7168 D PhoneMonitor: Register our PhoneStateListener
08-17 14:01:36.126  7168  7168 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-17 14:01:36.128  7168  7168 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 14:01:36.140  7168  7168 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-17 14:01:36.140  7168  7168 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-17 14:01:36.141  7168  7168 D TelephonyAutoProfiling: [parse] Load xml
,08-17 14:01:36.143  7168  7168 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-17 14:01:36.144  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-17 14:01:36.144  7168  7168 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-17 14:01:36.150  7168  7168 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-17 14:01:36.211  1035  1994 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7188 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 14:01:36.212  1035  1994 I ActivityManager: Killing 6635:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-17 14:01:36.283  1035  1050 W libprocessgroup: failed to open /acct/uid_10061/pid_6635/cgroup.procs: No such file or directory
,08-17 14:01:36.494  1035  1051 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7212 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-17 14:01:36.495  1035  1051 I ActivityManager: Killing 6269:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-17 14:01:36.562  1035  1958 W libprocessgroup: failed to open /acct/uid_10097/pid_6269/cgroup.procs: No such file or directory
,08-17 14:01:36.667  7151  7151 E wpa_supplicant: USIM:  scard_init function
08-17 14:01:36.668  7151  7151 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-17 14:01:36.685  1035  1970 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7229 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 14:01:36.686  1035  1970 I ActivityManager: Killing 6738:com.lge.eula/1000 (adj 15): empty #17
08-17 14:01:36.741  1035  1778 W libprocessgroup: failed to open /acct/uid_1000/pid_6738/cgroup.procs: No such file or directory
,08-17 14:01:36.777  7229  7229 I art     : Almond Protected OAT
,08-17 14:01:36.790  7151  7151 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-17 14:01:36.795  1035  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 14:01:36.802  7151  7151 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:01:36.802  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:01:36.856  7229  7229 D WeatherApplication: removeAccount
08-17 14:01:36.859  7229  7229 D WeatherApplication: Account.length = 0
08-17 14:01:36.859  7229  7229 E WeatherApplication: OPERATOR:OPEN
08-17 14:01:36.867  7229  7229 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:1:36
08-17 14:01:36.870  7229  7229 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 14:01:36.870  7229  7229 D Weather.Utils: 2 : All the weather widget is gone.
,08-17 14:01:36.872  7229  7229 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 14:01:36.875  7229  7229 D WeatherAncestor: connectivity changed - connection : true
08-17 14:01:36.876  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-17 14:01:36.876  7229  7229 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-17 14:01:36.876  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 14:01:36.877  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-17 14:01:36.877  1035  1435 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 14:01:36.878  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:36.878  1035  1435 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:36.879  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:36.879  1035  1435 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:36.879  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:36.880  1035  1435 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:36.882  1035  1435 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 14:01:36.882  1035  1435 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 14:01:36.883  1035  1435 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-17 14:01:36.883  1035  1435 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 14:01:36.883  1035  1435 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 14:01:36.884  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:36.884  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:36.885  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:36.885  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:36.885  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:01:36.885  1035  1435 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:01:36.885  1035  1435 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:01:36.885  1035  1435 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:01:36.887  7229  7229 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 14:01:36.887  7229  7229 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 14:01:36.887  7229  7229 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-17 14:01:36.887  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:36.888  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-17 14:01:36.891  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-17 14:01:36.893  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:36.893  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:36.893  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:36.893  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:36.893  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:36.893  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:36.893  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:36.893  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:36.893  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:36.893  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:36.893  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:36.893  1035  1446 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 14:01:36.895  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:36.895  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:36.895  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:36.895  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:36.895  6708  6708 V io.jxcore.node.Connectiv,ityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:36.895  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:36.895  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:36.895  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:36.895  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:36.895  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:36.895  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:36.901  1035  1435 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-17 14:01:36.901  1035  1435 D WifiNative-wlan0: SET update_config 1: returned true
08-17 14:01:36.901  1035  1435 D WifiConfigStore: Loading config and enabling all networks 
08-17 14:01:36.901  1035  1435 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 14:01:36.902  1035  1435 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-17 14:01:36.908  1035  1435 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-17 14:01:36.912  7229  7229 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 14:01:36.912  7229  7229 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:1:36
,08-17 14:01:36.919  1035  1435 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-17 14:01:36.919  1035  1435 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 14:01:36.931  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:36.931  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:01:36.967  1035  1647 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7254 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 14:01:36.969  1035  1647 I ActivityManager: Killing 6756:com.lge.bnr/1000 (adj 15): empty #17
,08-17 14:01:37.083  1035  1970 W libprocessgroup: failed to open /acct/uid_1000/pid_6756/cgroup.procs: No such file or directory
08-17 14:01:37.084  1035  1435 D WifiStateMachine: enableVerboseLogging : level 2
08-17 14:01:37.084  1035  1435 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 14:01:37.086  1035  1435 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 14:01:37.086  1035  1435 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-17 14:01:37.088  1035  1435 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 14:01:37.088  1035  1435 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-17 14:01:37.091  1035  1435 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-17 14:01:37.092  1035  1435 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-17 14:01:37.093  1035  1435 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 14:01:37.093  1035  1435 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 14:01:37.095  1035  1435 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 14:01:37.095  1035  1435 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 14:01:37.097  1035  1435 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 14:01:37.097  1035  1435 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-17 14:01:37.101  1035  1435 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-17 14:01:37.111  1035  1435 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 14:01:37.111  1035  1435 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-17 14:01:37.112  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-17 14:01:37.113  1941  2265 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 14:01:37.113  1941  2265 D WfdsService: Set the WFDS Monitor: true
08-17 14:01:37.113  1941  2265 D WfdsMonitor: WfdsMonitorThread create
08-17 14:01:37.113  1941  2265 D WfdsMonitor: WFDS Monitor is created and started
08-17 14:01:37.113  1941  2265 D WfdsService: WiFi: Supplicant connection re-established
08-17 14:01:37.116  1035  1435 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 14:01:37.116  1035  1435 D WifiNative-HAL: Setting external_sim to 1
08-17 14:01:37.116  1035  1435 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 14:01:37.117  1035  1435 D WifiNative-wlan0: SET external_sim 1: returned true
08-17 14:01:37.117  1035  1435 I WifiNative-HAL: startHal
08-17 14:01:37.117  1035  1435 D wifi    : setting scan oui 0xaf7075e0
08-17 14:01:37.118  1035  1435 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 14:01:37.118  1035  1435 I WifiNative-HAL: startHal
08-17 14:01:37.118  1035  1435 D wifi    : setting scan oui 0xaf7075e0
08-17 14:01:37.119  1941  7271 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 14:01:37.119  1035  1435 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 14:01:37.119  1035  1435 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 14:01:37.120  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 14:01:37.120  1941  7271 E CtrlSupplicant: Succeed to open control connection
08-17 14:01:37.120  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-17 14:01:37.121  1941  7271 E CtrlSupplicant: Succeed to open monitor connection
08-17 14:01:37.121  1941  7271 D WfdsMonitor: Supplicant connection established
08-17 14:01:37.121  1941  2265 D WfdsService: Connected to the supplicant for wfds
08-17 14:01:37.121  1035  1435 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-17 14:01:37.122  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 14:01:37.122  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 14:01:37.122  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 14:01:37.122  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-17 14:01:37.123  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 14:01:37.123  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-17 14:01:37.123  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 14:01:37.124  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 14:01:37.125  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 14:01:37.125  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 14:01:37.125  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-17 14:01:37.128  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 14:01:37.128  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 14:01:37.128  7151  7151 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-17 14:01:37.128  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-17 14:01:37.128  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 14:01:37.129  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 14:01:37.129  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 14:01:37.131  1035  1435 E WifiNative: : [131,396,178 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 14:01:37.131  1035  1435 D WifiNative-wlan0: doBoolean: RECONNECT
08-17 14:01:37.131  1035  1435 D WifiNative-wlan0: RECONNECT: returned true
08-17 14:01:37.131  1035  1435 D WifiNative-wlan0: doString: [STATUS]
08-17 14:01:37.132  1035  7251 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:01:37.132  1035  7251 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:01:37.132  1035  1435 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 14:01:37.132  1035  1435 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:01:37.133  1035  1435 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:01:37.134  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.135  1035  1435 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 14:01:37.135  1035  1435 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-17 14:01:37.136  1035  1435 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 14:01:37.136  1035  1435 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 14:01:37.137  1035  1435 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-17 14:01:37.137   314   880 D CommandListener: Setting iface cfg
08-17 14:01:37.137  1035  1435 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 14:01:37.137   314   880 D CommandListener: Trying to bring up p2p0
08-17 14:01:37.138  1035  1435 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 14:01:37.138  1035  1435 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-17 14:01:37.138  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 14:01:37.138  1035  1390 D LGWifiP2pService: P2pEnablingState
08-17 14:01:37.138  7151  7151 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-17 14:01:37.138  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.138  1035  1390 D LGWifiP2pService: P2p socket connection successful
08-17 14:01:37.138  1035  1390 D LGWifiP2pService: P2pEnabledState
08-17 14:01:37.139  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 14:01:37.139  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 14:01:37.140  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 14:01:37.141  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-17 14:01:37.141  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.141  1035  1556 I WifiNative-HAL: startHal
08-17 14:01:37.141  1035  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.142  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,08-17 14:01:37.142  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 14:01:37.144  1035  1435 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 14:01:37.144  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-17 14:01:37.144  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 14:01:37.144  1035  1390 D LGWifiP2pService: before postfix = G3
08-17 14:01:37.144  1035  1390 D WifiServerServiceExt: postfix byte check : 2
08-17 14:01:37.144  1035  1390 D LGWifiP2pService: after postfix = G3
08-17 14:01:37.144  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 14:01:37.144  1035  1435 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-17 14:01:37.145  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 14:01:37.145  1941  1941 D WfdsService: WifiP2pState is changed : true
08-17 14:01:37.145  1941  2265 D WfdsService: Receive the WFDS_ENABLE Method
08-17 14:01:37.145  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 14:01:37.145  1941  2265 D WfdsService: Set the WFDS Monitor: true
08-17 14:01:37.145  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 14:01:37.145  1941  2265 D WfdsService: Connected to the supplicant for wfds
08-17 14:01:37.145  1941  2265 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 14:01:37.146  7151  7151 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-17 14:01:37.146  1941  2265 D WfdsService: selectPreferredScanChannel [36]
08-17 14:01:37.146  1941  2265 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-17 14:01:37.146  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 14:01:37.146  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 14:01:37.146  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-17 14:01:37.146  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf7075e0
08-17 14:01:37.147  1035  1556 D wifi    : failed to get capabilities : -3
08-17 14:01:37.147  1035  1556 E WifiScanningService: could not get scan capabilities
08-17 14:01:37.147  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 14:01:37.147  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 14:01:37.148  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 14:01:37.148  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-17 14:01:37.148  1941  1941 D WfdsService: isConnected: false
08-17 14:01:37.150  1035  1435 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-17 14:01:37.150  1035  1435 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-17 14:01:37.150  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-17 14:01:37.151  7151  7151 E wpa_supplicant: disconnect_rssi_lvl: -100
08-17 14:01:37.151  1035  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 14:01:37.152  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 14:01:37.152  1035  1435 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:01:37.152  1035  1435 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:01:37.153  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-17 14:01:37.153  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 14:01:37.153  1035  1435 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:01:37.153  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 14:01:37.153  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-17 14:01:37.153  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:01:37.153  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-17 14:01:37.154  1035  1390 D WifiNative,-p2p0: doBoolean: SAVE_CONFIG
08-17 14:01:37.154  1035  1435 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 14:01:37.154  1035  1435 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 14:01:37.155  1035  1435 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 14:01:37.155  1035  1435 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 14:01:37.155  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-17 14:01:37.156  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 14:01:37.156  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 14:01:37.156  1941  1941 D WfdsService: Update P2p Interface State: 3
,08-17 14:01:37.234   277   349 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 14:01:37.234   277   349 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-17 14:01:37.234   277   349 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 14:01:37.235  7254  7278 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 14:01:37.238   277   349 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-17 14:01:37.238   277   349 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 14:01:37.238   277   349 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 14:01:37.238  7254  7278 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-17 14:01:37.255   277   349 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 14:01:37.255   277   349 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 14:01:37.255   277   349 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 14:01:37.257  7254  7281 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-17 14:01:37.261   277   349 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 14:01:37.261   277   349 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 14:01:37.261   277   349 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 14:01:37.262  7254  7281 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-17 14:01:37.288  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-17 14:01:37.288  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 14:01:37.289  1035  1390 D LGWifiP2pService: InactiveState
08-17 14:01:37.289  1035  1390 D LGWifiP2pService: InactiveState{ when=-136ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.289  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-136ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.289  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-17 14:01:37.289  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 14:01:37.289  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:37.290  1035  7251 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:01:37.290  1035  7251 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:37.290  1035  7251 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:37.290  1035  7251 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:37.290  7151  7151 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 14:01:37.290  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.290  1035  7251 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:37.290  1035  7251 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.290  1941  7271 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:37.290  1035  7251 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.290  1035  7251 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.290  1035  1435 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 14:01:37.291  1035  1435 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:01:37.292  1035  1435 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:01:37.292  1035  1435 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:01:37.292  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-17 14:01:37.293  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 14:01:37.294  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-17 14:01:37.294  1941  7271 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-17 14:01:37.294  1035  7251 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:01:37.294  1035  7251 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:37.294  1035  7251 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:37.294  1035  7251 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-17 14:01:37.295  7151  7151 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 14:01:37.296  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 14:01:37.296  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1941  7271 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:37.296  1035  1035 E WifiServerServiceExt: No p2p device connected
08-17 14:01:37.297  1941  2265 W WfdsService: DefaultState - msg [9441285] is not handled
08-17 14:01:37.297  1035  7251 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:37.297  1035  7251 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.297  1035  7251 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.297  1035  7251 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.298  7151  7151 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 14:01:37.298  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:01:37.298  1035  7251 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 14:01:37.298  1035  7251 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:01:37.298  1035  7251 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:01:37.298  1035  7251 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:01:37.300  1035  1435 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-17 14:01:37.300  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.30,0  1035  1435 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-17 14:01:37.300  1941  7271 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:37.300  1035  7251 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:37.301  1035  7251 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.301  1035  7251 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.301  1035  7251 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.308  1035  1435 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-17 14:01:37.308  1035  1435 D WifiNative-wlan0: doBoolean: SCAN
08-17 14:01:37.309  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.309  1941  7271 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:37.309  1035  7251 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:37.309  1035  7251 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.309  1035  7251 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.309  1035  7251 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:37.311  1035  1435 D WifiNative-wlan0: SCAN: returned true
08-17 14:01:37.312  1035  1435 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=131578  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:01:37.313  1035  1435 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=131579  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-17 14:01:37.314  1035  1435 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:37.314  1035  1435 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:37.314  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:37.315  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:37.315  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 14:01:37.315  1035  1435 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:37.315  1035  1435 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:37.315  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-17 14:01:37.316  1035  1435 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:37.316  1035  7251 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 14:01:37.316  1035  7251 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 14:01:37.316  1035  7251 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 14:01:37.316  1035  7251 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-17 14:01:37.316  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:37.316  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:37.316  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:37.316  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 14:01:37.317  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:37.549  7254  7254 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 14:01:37.559  7254  7254 I LibraryLoader: Loading: webviewchromium,
08-17 14:01:37.562  7254  7254 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1837-1841)
08-17 14:01:37.562  7254  7254 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:01:37.573  7254  7254 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3287b5d3}
,08-17 14:01:37.575  7254  7254 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:01:37.575  7254  7254 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 14:01:37.587  7254  7254 I BrowserStartupController: Initializing chromium process, renderers=0
08-17 14:01:37.588  7254  7254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:01:37.616   318  2208 V AudioPolicyService: registerClient() client 0xb558a5a0, uid 10093
,08-17 14:01:37.618  7254  7303 W AudioManagerAndroid: Requires BLUETOOTH permission
08-17 14:01:37.619  7254  7254 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-17 14:01:37.620  7254  7254 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-17 14:01:37.621  7254  7254 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-17 14:01:37.637  7254  7254 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:01:37.637  7254  7254 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:01:37.637  7254  7254 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:01:37.637  7254  7254 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:01:37.637  7254  7254 I Adreno-EGL: Remote Branch: 
08-17 14:01:37.637  7254  7254 I Adreno-EGL: Local Patches: 
08-17 14:01:37.637  7254  7254 I Adreno-EGL: Reconstruct Branch: 
,08-17 14:01:37.733  7254  7254 I NSApplication: Starting up...
,08-17 14:01:37.810  1035  1994 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7319 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-17 14:01:37.812  1035  1575 I ActivityManager: Killing 6198:com.android.vending/u0a44 (adj 15): empty #17
,08-17 14:01:37.894  1035  1922 W libprocessgroup: failed to open /acct/uid_10044/pid_6198/cgroup.procs: No such file or directory
,08-17 14:01:37.952  7319  7319 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:01:38.136  1035  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 14:01:38.136  1035  1051 D WifiService: setWifiEnabled: false pid=6708, uid=10118
08-17 14:01:38.136  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:01:38.156  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-17 14:01:38.156  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:01:38.156  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-17 14:01:38.162  1035  1435 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-17 14:01:38.162  1035  1435 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 14:01:38.163  1035  1435 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-17 14:01:38.163  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 14:01:38.170  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 14:01:38.170  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-17 14:01:38.170  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:38.170  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:38.170  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@17c8b94
,08-17 14:01:38.171  1035  1390 D LGWifiP2pService: P2pDisablingState
08-17 14:01:38.171  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:38.171  1035  1390 D LGWifiP2pService: p2p socket connection lost
08-17 14:01:38.171  1035  1557 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:38.171  1035  1390 D LGWifiP2pService: P2pDisabledState
08-17 14:01:38.172  1035  1556 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:38.173  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 14:01:38.173  1941  1941 D WfdsService: WifiP2pState is changed : false
08-17 14:01:38.174  1035  1435 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-17 14:01:38.174   314   880 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:01:38.174  1941  2265 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-17 14:01:38.174  1941  2265 D WfdsService: Set the WFDS Monitor: false
08-17 14:01:38.176  1941  2265 D WfdsMonitor: WFDS Monitor is stopped
08-17 14:01:38.176  1941  2265 D WfdsService: STATE : WfdsDisabledState - enter
08-17 14:01:38.177  1941  2270 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 14:01:38.177  1941  7271 D CtrlSupplicant: Received on exit socket, terminate
08-17 14:01:38.177  1941  7271 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 14:01:38.178  1941  7271 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 14:01:38.178  1941  7271 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-17 14:01:38.179  1035  1435 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 14:01:38.179  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 14:01:38.179  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:38.180  1035  1435 D WifiNative-p2p0: TERMINATE: returned true
08-17 14:01:38.180  1035  1435 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:01:38.180  1035  1435 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:01:38.180  1035  1435 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:01:38.180  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-17 14:01:38.180  1941  2265 W WfdsService: DefaultState - msg [9445378] is not handled
08-17 14:01:38.181  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:38.181  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:38.181  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:01:38.181  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:01:38.182  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-17 14:01:38.182  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:38.182  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:38.183  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:01:38.184  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 14:01:38.184  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:38.189  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:38.189  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:38.189  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:38.189  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:38.189  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:38.189  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:38.189  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:38.189  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:38.189  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:38.189  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:38.189  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:38.190  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:38.190  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:38.190  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:38.190  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:38.190  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:38.190  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:38.190  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:38.190  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:38.190  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:38.190  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:38.190  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:38.191  1941  1941 V, WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-17 14:01:38.191  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-17 14:01:38.191  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:38.191  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 14:01:38.192  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:38.203  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:01:38.252  7151  7151 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 14:01:38.252  7151  7151 I wpa_supplicant: monitor socket send errors count : 1
08-17 14:01:38.252  7151  7151 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-17 14:01:38.254  1035  7251 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 14:01:38.254  1035  7251 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-17 14:01:38.260  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 14:01:38.265  6509  6534 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-17 14:01:38.283  2198  2198 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:01:38.296  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 14:01:38.296  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:38.297  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 14:01:38.297  7091  7091 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 14:01:38.299  7091  7091 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 14:01:38.304  7091  7091 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26b13386
08-17 14:01:38.304  7091  7091 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 14:01:38.304  7091  7091 D AppUp4:CustFacade: isPhone : true
08-17 14:01:38.304  7091  7091 D AppUp4:CustModeStarterReceiver: begin check event
08-17 14:01:38.304  7091  7091 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 14:01:38.309  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:38.309  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:01:38.311  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 14:01:38.315  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:01:38.323  7119  7119 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-17 14:01:38.323  4371  7346 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:01:38.341  4371  7347 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:38.341  4371  7347 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 14:01:38.345  7119  7349 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:38.348  6995  7350 W FormManager: Network not available. Please check & try again.
08-17 14:01:38.356  6995  7351 V FormManager: Network unavailable.
,08-17 14:01:38.359  6995  7351 V FormManager: Network unavailable.
08-17 14:01:38.370  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 14:01:38.372  7151  7151 W wpa_supplicant: USIM:  scard_deinit function
08-17 14:01:38.374  1035  7251 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-17 14:01:38.375  1035  7251 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:01:38.375  1035  7251 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:01:38.375  1035  7251 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-17 14:01:38.375  1035  7251 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:01:38.375  1035  7251 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:01:38.376  1035  1435 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=132642
08-17 14:01:38.376  1035  1435 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=132643
08-17 14:01:38.377  1035  1435 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=132643  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 14:01:38.377  1035  1435 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=132644  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 14:01:38.379  1035  1111 D Tethering: InitialState.processMessage what=4
08-17 14:01:38.381  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:01:38.382  1035  1435 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:38.382  1035  1435 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-17 14:01:38.425  1035  1647 I art     : Explicit concurrent mark sweep GC freed 63397(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.913ms total 154.296ms
,08-17 14:01:38.436  3418  3418 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 14:01:38.436  3418  3418 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:38.437  3418  3418 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 14:01:38.440  7168  7168 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 14:01:38.440  7168  7168 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 14:01:38.450  7229  7229 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:1:38
08-17 14:01:38.452  7229  7229 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 14:01:38.452  7229  7229 D Weather.Utils: 2 : All the weather widget is gone.
,08-17 14:01:38.453  7229  7229 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-17 14:01:38.453  7229  7229 D WeatherAncestor: connectivity changed - connection : true
08-17 14:01:38.453  7229  7229 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3254d474
08-17 14:01:38.453  7229  7229 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 14:01:38.453  7229  7229 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 14:01:38.454  7229  7229 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 14:01:38.454  7229  7229 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 14:01:38.454  7229  7229 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:1:38
08-17 14:01:38.474  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:01:38.474  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 14:01:38.474  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:01:38.474  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-17 14:01:38.475  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 14:01:38.475  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 14:01:38.476  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 14:01:38.476  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:01:38.476  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:01:38.476  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:01:38.476  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-17 14:01:38.481  7151  7151 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 14:01:38.481  1035  7251 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 14:01:38.481  1035  7251 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 14:01:38.481  1035  7251 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 14:01:38.482  1035  1435 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 33 0
08-17 14:01:38.486  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:38.488  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:01:38.493  6995  7363 W FormManager: Network not available. Please check & try again.
08-17 14:01:38.494  6995  7364 V FormManager: Network unavailable.
08-17 14:01:38.496  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:38.496  6995  7364 V FormManager: Network unavailable.
08-17 14:01:38.513  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:01:38.518  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 14:01:38.520  6995  7366 W FormManager: Network not available. Please check & try again.
08-17 14:01:38.522  6995  7367 V FormManager: Network unavailable.
08-17 14:01:38.523  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:01:38.528  6995  7367 V FormManager: Network unavailable.
,08-17 14:01:38.538  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:01:38.538  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:01:38.541  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:01:38.545  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 14:01:38.553  4371  7368 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 14:01:38.561  4371  7369 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:01:38.561  4371  7369 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 14:01:38.591  1035  1994 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7370 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-17 14:01:38.594  1035  1435 D WifiOffDelayIfNotUsed: stopMonitoring
08-17 14:01:38.594  1035  1435 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:01:38.594  1035  1435 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:01:38.594  1035  1435 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:01:38.597  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:38.598  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-17 14:01:38.599  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-17 14:01:38.599  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 14:01:38.599  1035  1446 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 14:01:38.599  1035  1446 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-17 14:01:38.599  1941  2265 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-17 14:01:38.599  1941  2265 D WfdsService: Set the WFDS Monitor: false
08-17 14:01:38.599  1941  2265 D WfdsMonitor: WFDS Monitor is stopped
08-17 14:01:38.600  2488  2488 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:38.601  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:38.602  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:38.615   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 565us total 22.228ms
,08-17 14:01:38.637   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 21.143ms
08-17 14:01:38.655   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 377us total 17.240ms
,08-17 14:01:38.657  6800  7066 D UEI.SmartControl: Internal timer expired: 2
08-17 14:01:38.657  6800  7066 D UEI.SmartControl: unbind internal service
08-17 14:01:38.688  7370  7370 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 14:01:38.689  7370  7370 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-17 14:01:38.694  7370  7370 V [BNRBootReceiver]: Boot Receiver Return
08-17 14:01:38.696  7370  7370 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-17 14:01:38.697  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:38.704  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:38.704  6800  7062 D serial_port: close(fd = 24)
,08-17 14:01:38.707  6800  7062 I UEI.SmartControl: Serial port is closed.
,08-17 14:01:38.716  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:38.740  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:38.741  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:38.743  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:01:38.753  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:38.760  6907  6907 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 14:01:38.760  6907  6907 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:01:38.760  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:01:38.765  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:01:38.774  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:01:38.786  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:38.786  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:01:38.788  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 14:01:38.792  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:38.795  6907  6907 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 14:01:38.795  6907  6907 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:01:38.796  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:38.804  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:01:38.811  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:38.826  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:38.827  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:01:38.831  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:01:38.852  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:01:38.859  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:01:38.875  6995  7389 W FormManager: Network not available. Please check & try again.
08-17 14:01:38.884  6995  7390 V FormManager: Network unavailable.
08-17 14:01:38.885  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:01:38.897  6995  7390 V FormManager: Network unavailable.
,08-17 14:01:38.906  1035  1922 I ActivityManager: Killing 6930:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-17 14:01:39.005  1035  1994 W libprocessgroup: failed to open /acct/uid_10037/pid_6930/cgroup.procs: No such file or directory
,08-17 14:01:39.037  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:01:39.038  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-17 14:01:39.045  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:01:39.047  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:01:39.053  4371  7397 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 14:01:39.063  6907  6907 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 14:01:39.063  6907  6907 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 14:01:39.063  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:39.067  4371  7398 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-17 14:01:39.068  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:01:39.071  4371  7398 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 14:01:39.077  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:39.086  6995  7400 W FormManager: Network not available. Please check & try again.
,08-17 14:01:39.095  6995  7401 V FormManager: Network unavailable.
08-17 14:01:39.097  6995  7401 V FormManager: Network unavailable.
,08-17 14:01:41.159  1035  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:41.160  1035  1970 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 14:01:41.187  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:01:41.188  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:01:41.188  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-17 14:01:41.192  1035  1111 D BluetoothManagerService: Message: 1
08-17 14:01:41.192  1035  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-17 14:01:41.221  1035  1111 D BluetoothManagerService: Message: 20
08-17 14:01:41.222  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@380cca3:true
08-17 14:01:41.223  7041  7041 D BluetoothAdapterState: make
,08-17 14:01:41.231  7041  7041 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 14:01:41.231  7041  7041 I bluedroid-qcom: init
08-17 14:01:41.232  7041  7406 I BluetoothAdapterState: Entering OffState
08-17 14:01:41.233  7041  7041 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 14:01:41.233  7041  7041 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 14:01:41.233  7041  7041 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 14:01:41.233  7041  7041 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 14:01:41.233  7041  7041 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 14:01:41.235  7041  7041 I bluedroid-qcom: get_profile_interface socket
08-17 14:01:41.235  7041  7041 I bluedroid-qcom: get_profile_interface map_client
08-17 14:01:41.237  7041  7410 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 14:01:41.239  7041  7410 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-17 14:01:41.236  7409  7409 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:41.236  7409  7409 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:41.254  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 14:01:41.254  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-17 14:01:41.258  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-17 14:01:41.258  1035  1111 D BluetoothManagerService: Message: 40
08-17 14:01:41.258  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 14:01:41.259  7041  7057 I bluedroid-qcom: config_hci_snoop_log
08-17 14:01:41.260  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 14:01:41.260  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-17 14:01:41.262  7409  7409 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 14:01:41.262  7409  7409 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 14:01:41.262  7409  7409 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-17 14:01:41.265  7409  7409 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-17 14:01:41.269  7409  7409 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 14:01:41.269  7409  7409 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-17 14:01:41.275  7041  7406 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-17 14:01:41.276  7041  7410 D BluetoothAdapterProperties: Name is: G3
08-17 14:01:41.276  7041  7406 D BluetoothAdapterProperties: Setting state to 11
08-17 14:01:41.276  7041  7406 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 14:01:41.278  7041  7406 I LGBluetoothServiceJni: classInitNative: succeeds
08-17 14:01:41.280  1035  1111 D BluetoothManagerService: Message: 60
08-17 14:01:41.280  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 14:01:41.280  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-17 14:01:41.285  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:01:41.289  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:01:41.290  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:41.293  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:41.294  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-17 14:01:41.303  7041  7041 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:01:41.304  7041  7041 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:41.304  7041  7041 V BluetoothPbapReceiver: ***********state = 11
,08-17 14:01:41.310  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:01:41.324  7041  7406 D BluetoothBondStateMachine: make
,08-17 14:01:41.333  7041  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.334  7041  7406 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 14:01:41.334  7041  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.334  7041  7406 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 14:01:41.335  7041  7406 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 14:01:41.338  7041  7422 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 14:01:41.343  7041  7406 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:41.389  1035  1933 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7427 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-17 14:01:41.397  7041  7406 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:41.403  7041  7041 D HeadsetService: Received start request. Starting profile...
08-17 14:01:41.404  7041  7041 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 14:01:41.404  7041  7406 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 14:01:41.405  7041  7041 D LGBluetoothHfpAdapter: Version 1.6
08-17 14:01:41.412  7041  7406 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:41.412  7041  7041 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:01:41.414  7041  7041 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 14:01:41.414  7041  7041 D HeadsetStateMachine: make
08-17 14:01:41.418  7041  7406 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:41.424  7041  7406 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 14:01:41.430  7041  7406 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:41.448  7041  7041 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 14:01:41.448  7041  7041 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 14:01:41.450  7041  7406 V LGMDMManager: Create singleton instance
08-17 14:01:41.452  7041  7041 D HeadsetStateMachine: max_hf_connections = 1
08-17 14:01:41.452  7041  7041 I bluedroid-qcom: get_profile_interface handsfree
08-17 14:01:41.454  7041  7406 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 14:01:41.455  7041  7041 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 14:01:41.455   318   318 V AudioPolicyService: registerClient() client 0xb558a760, uid 1002
08-17 14:01:41.456   318  1397 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 14:01:41.456   318  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:01:41.456   318  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:01:41.456  7041  7041 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 14:01:41.456   318  2197 V AudioFlinger: registerClient() client 0xb55819a0, pid 7041
08-17 14:01:41.456   318  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:41.456   318  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:41.457  1853  4003 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:41.457  1853  4003 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:41.457   318  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:41.457   318  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:41.457  7041  7057 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:41.457  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:41.457  7041  7057 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 14:01:41.457  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:41.457  7041  7057 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:41.457  7041  7057 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 14:01:41.457  1602  2103 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:41.457  1602  2103 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:41.457  1602  2103 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:41.457  1602  2103 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:41.457  7041  7041 V ToneGenerator: Create Track: 0xb4928080
08-17 14:01:41.457  7041  7041 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 14:01:41.457  7041  7041 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-17 14:01:41.457   318  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 14:01:41.457   318  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 14:01:41.457   318  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:01:41.457   318  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:01:41.458  1035  1575 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:41.458  1035  1575 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:41.458  1035  1575 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:41.458  1035  1575 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:41.458   318  2208 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 14:01:41.458   318  2197 V AudioPolicyManager: getOutputForAttr() usage=3,, content=4, tag= flags=00000000
08-17 14:01:41.458   318  2197 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 14:01:41.458   318  2197 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:01:41.458   318  2197 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:01:41.458  7041  7041 V AudioSystem: getLatency() output 2, latency 50
08-17 14:01:41.458  3418  3433 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:41.458  3418  3433 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:41.458  7041  7041 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 14:01:41.458  7041  7041 V AudioTrack: createTrack_l() output 2 afLatency 50
08-17 14:01:41.458  3418  3433 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:41.459  3418  3433 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:41.459   318  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 14:01:41.459   318  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 14:01:41.459   318  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 14:01:41.459   318  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 14:01:41.459   318  1397 V AudioFlinger: createTrack() lSessionId: 21
08-17 14:01:41.460  7041  7041 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-17 14:01:41.461   318  1397 V AudioFlinger: acquiring 21 from 7041, for 7041
08-17 14:01:41.461   318  1397 V AudioFlinger:  added new entry for 21
08-17 14:01:41.461  7041  7041 V ToneGenerator: ToneGenerator INIT OK, time: 135740
08-17 14:01:41.461  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.461  7041  7446 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 14:01:41.461  7041  7446 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:01:41.462  7041  7446 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:01:41.462  7041  7446 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 14:01:41.462   318  2208 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7041
,08-17 14:01:41.463   318  2208 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 14:01:41.463   318  2208 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 14:01:41.463   318  2208 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-17 14:01:41.463   318  2208 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 14:01:41.463   318  2208 V voice   : voice_set_parameters: exit with code(0)
08-17 14:01:41.463   318  2208 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-17 14:01:41.463   318  2208 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 14:01:41.463   318  2208 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 14:01:41.463   318  2208 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 14:01:41.463   318  2208 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-17 14:01:41.463   318  2208 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 14:01:41.465  7041  7446 V ToneGenerator: ToneGenerator destructor
08-17 14:01:41.465  7041  7446 V ToneGenerator: stopTone
08-17 14:01:41.466  7041  7446 V ToneGenerator: Delete Track: 0xb4928080
08-17 14:01:41.466  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.466  7041  7446 V AudioTrack: ~AudioTrack, releasing session id from 7041 on behalf of 7041
08-17 14:01:41.466   318   318 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 14:01:41.466   318   318 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 14:01:41.466   318   318 V AudioFlinger: PlaybackThread::Track destructor
08-17 14:01:41.466   318  1256 V AudioPolicyService: AudioCommandThread() waking up
08-17 14:01:41.466   318   318 V AudioFlinger: removeClient_l() pid 7041, calling pid 318
08-17 14:01:41.466   318  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 14:01:41.466   318  1256 V AudioPolicyManager: releaseOutput() 2
08-17 14:01:41.466   318  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 14:01:41.466   318  1397 V AudioFlinger: releasing 21 from 7041 for 7041
08-17 14:01:41.466   318  1397 V AudioFlinger:  decremented refcount to 0
08-17 14:01:41.466   318  1397 V AudioFlinger: purging stale effects
08-17 14:01:41.467  7041  7041 D A2dpService: Received start request. Starting profile...
08-17 14:01:41.467  7041  7041 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 14:01:41.468  7041  7041 V Avrcp   : make
08-17 14:01:41.469  7041  7041 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-17 14:01:41.469  7041  7041 I bluedroid-qcom: get_profile_interface avrcp
08-17 14:01:41.476  7041  7041 V AudioManager: registerRemoteController: size of Media player list: 0
08-17 14:01:41.477  7041  7041 E AudioManager: No RCC entry present to update
08-17 14:01:41.477  7041  7041 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 14:01:41.480  7041  7041 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-17 14:01:41.481  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 14:01:41.481  7041  7041 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-17 14:01:41.484  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 14:01:41.543  7427  7427 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-17 14:01:41.544  7427  7427 W LG Account v2.2: No ProfileInfo entries
08-17 14:01:41.545  7427  7427 I LG Account v2.2: isEnabled: false
08-17 14:01:41.545  7427  7427 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 14:01:41.545  7427  7427 I Feature : [Lifetracker]Country: EU
08-17 14:01:41.545  7427  7427 I Feature : [Lifetracker]Operator: OPEN
08-17 14:01:41.546  7427  7427 I Feature : [Lifetracker]Ranking support: false
08-17 14:01:41.546  7427  7427 I Feature : [Lifetracker]Comfort support: false
08-17 14:01:41.546  7427  7427 I Feature : [Lifetracker]Accessory: true
08-17 14:01:41.546  7427  7427 I Feature : [Lifetracker]Health device: true
08-17 14:01:41.546  7427  7427 I Feature : [Lifetracker]Extra Pedometer: false
08-17 14:01:41.547  7427  7427 I Feature : [Lifetracker]Blood glucose device: false
08-17 14:01:41.547  7427  7427 I Feature : [Lifetracker]Device Number: 3
08-17 14:01:41.564  6889  6889 D BluetoothPermissionRequest: onReceive
,08-17 14:01:41.569  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:01:41.614  1035  1890 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:01:41.614  1035  1890 V SIM_STK : Menu title from STK is T-Mobile
,08-17 14:01:41.727  1035  2032 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 14:01:41.736  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 14:01:41.740  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 14:01:41.741  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 14:01:41.741  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 14:01:41.741  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 14:01:41.741  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:01:41.741  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 14:01:41.741  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 14:01:41.741  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 14:01:41.741  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:01:41.741  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 14:01:41.741  7041  7041 I BluetoothA2dpServiceJni: classInitNative
08-17 14:01:41.742  7041  7041 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:01:41.742  7041  7041 D A2dpStateMachine: make
,08-17 14:01:41.744  7041  7041 I bluedroid-qcom: get_profile_interface a2dp
08-17 14:01:41.745  7041  7457 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 14:01:41.749  7041  7041 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:01:41.750  7041  7041 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 14:01:41.756  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.756  7041  7456 D A2dpStateMachine: Enter Disconnected: -2
,08-17 14:01:41.759  7041  7041 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 14:01:41.763  7041  7041 D HidService: Received start request. Starting profile...
08-17 14:01:41.763  7041  7041 I bluedroid-qcom: get_profile_interface hidhost
08-17 14:01:41.763  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.764  7041  7041 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:01:41.765  7041  7041 D HealthService: Received start request. Starting profile...
08-17 14:01:41.768  7041  7041 I bluedroid-qcom: get_profile_interface health
08-17 14:01:41.769  7041  7041 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:01:41.769  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
,08-17 14:01:41.770  7041  7041 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 14:01:41.773  7041  7041 D PanService: Received start request. Starting profile...
08-17 14:01:41.773  7041  7041 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 14:01:41.773  7041  7041 I bluedroid-qcom: get_profile_interface pan
08-17 14:01:41.777  7041  7041 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-17 14:01:41.778  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.778  7041  7041 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-17 14:01:41.782  7041  7041 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:01:41.783  7041  7041 D BtGatt.GattService: Received start request. Starting profile...
08-17 14:01:41.783  7041  7041 D BtGatt.GattService: start()
08-17 14:01:41.783  7041  7041 I bluedroid-qcom: get_profile_interface gatt
08-17 14:01:41.783  7041  7041 D BtGatt.AdvertiseManager: advertise manager created
08-17 14:01:41.788  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.790  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.790  7041  7041 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-17 14:01:41.791  7041  7041 V BluetoothMapService: BluetoothMapBinder()
08-17 14:01:41.792  7041  7041 D BluetoothMapService: Received start request. Starting profile...
08-17 14:01:41.792  7041  7041 D BluetoothMapService: start()
08-17 14:01:41.795  7041  7041 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-17 14:01:41.795  7041  7041 D BluetoothMapEmailAppObserver: createReceiver()
08-17 14:01:41.798  7041  7041 D BluetoothMapEmailAppObserver: initObservers()
08-17 14:01:41.798  7041  7041 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-17 14:01:41.807  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:41.807  7041  7041 D HeadsetStateMachine: Proxy object connected
08-17 14:01:41.808  7041  7041 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 14:01:41.808  7041  7041 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-17 14:01:41.809  7041  7446 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 14:01:41.811  7041  7446 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 14:01:41.811  7041  7446 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-17 14:01:41.814  7041  7041 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:01:41.817  7041  7041 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:01:41.819  7041  7041 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:01:41.822  7041  7041 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:01:41.822  7041  7041 V PanService: [BTUI] SIM Extra State :ABSENT
,08-17 14:01:41.825  7041  7041 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:01:41.827  7041  7041 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-17 14:01:41.828  7041  7041 V BluetoothMapService: Handler(): got msg=1
08-17 14:01:41.829  7041  7406 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-17 14:01:41.829  7041  7406 I bluedroid-qcom: enable
08-17 14:01:41.829  7041  7464 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 14:01:41.829  7041  7406 I bt_hci_bdroid: init
08-17 14:01:41.830  7041  7041 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:41.830  7041  7464 I bt-btu  : btu_task pending for preload complete event
08-17 14:01:41.832  7041  7041 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:01:41.832  7041  7041 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:01:41.832  7041  7041 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:01:41.832  7041  7041 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:41.832  7041  7041 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-17 14:01:41.832  7041  7406 I bt_vendor: bt-vendor : init
08-17 14:01:41.832  7041  7406 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 14:01:41.832  7041  7406 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 14:01:41.832  7041  7406 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 14:01:41.832  7041  7406 D bt_userial_mct: userial_init
08-17 14:01:41.833  7041  7406 D bt_hci_bdroid: set_power 1
08-17 14:01:41.833  7041  7406 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 14:01:41.833  7041  7406 I bt_vendor: Starting hciattach daemon
08-17 14:01:41.833  7041  7406 I bt_vendor: try to set true
08-17 14:01:41.826  7467  7467 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:41.826  7467  7467 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 14:01:41.854  7468  7468 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 14:01:41.974  7474  7474 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 14:01:41.988  7475  7475 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 14:01:42.021  1035  1483 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-17 14:01:42.028  7477  7477 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-17 14:01:42.044  7478  7478 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-17 14:01:42.070  7479  7479 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 14:01:42.086  7480  7480 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-17 14:01:42.107  7485  7485 I libmdmdetect: ESOC framework not supported
08-17 14:01:42.109  7485  7485 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-17 14:01:42.119  7485  7485 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-17 14:01:42.119  7485  7485 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-17 14:01:42.119  7485  7485 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-17 14:01:42.119  7485  7485 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-17 14:01:42.119  7485  7485 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-17 14:01:42.119  7485  7485 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-17 14:01:42.119  7485  7485 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-17 14:01:42.159  7485  7486 E QC-QMI  : qmi_client [7485] 14: failed to locate client data
08-17 14:01:42.160   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-17 14:01:42.160   483   483 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-17 14:01:42.199  7487  7487 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-17 14:01:42.212  7488  7488 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-17 14:01:42.234  7041  7406 I bt_vendor: bluetooth satus is on
08-17 14:01:42.234  7041  7406 D bt_hci_bdroid: preload
08-17 14:01:42.235  7041  7466 D bt_userial_mct: userial_open(port:0)
08-17 14:01:42.235  7041  7466 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 14:01:42.238  7041  7466 I bt_vendor: Done intiailizing UART
08-17 14:01:42.239  7041  7466 I bt_vendor: Done intiailizing UART
08-17 14:01:42.239  7041  7466 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 14:01:42.239  7041  7466 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 14:01:42.240  7041  7464 I bt-btu  : btu_task received preload complete event
08-17 14:01:42.240  7041  7490 D bt_userial_mct: Entering userial_read_thread()
08-17 14:01:42.240  7041  7464 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 14:01:42.241  7041  7464 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-17 14:01:42.243  7041  7464 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_GAP
,08-17 14:01:42.246  7041  7464 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 14:01:42.247  7041  7464 I         : BTE_InitTraceLevels -- TRC_SDP
,08-17 14:01:42.247  7041  7464 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 14:01:42.247  7041  7464 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 14:01:42.247  7041  7464 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-17 14:01:42.247  7041  7464 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 14:01:42.262  7254  7282 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-17 14:01:42.309  7041  7464 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-17 14:01:42.309  7041  7464 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a2061 
08-17 14:01:42.309  7041  7464 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a2061 
,08-17 14:01:42.348  7041  7410 E bt-btif : Calling BTA_HhEnable
08-17 14:01:42.348  7041  7410 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-17 14:01:42.349  7041  7410 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 14:01:42.352  7041  7410 D BluetoothAdapterProperties: Name is: G3
08-17 14:01:42.354  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 14:01:42.355  7041  7464 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-17 14:01:42.355  7041  7464 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-17 14:01:42.355  7041  7464 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-17 14:01:42.355  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 14:01:42.355  7041  7464 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 14:01:42.355  7041  7464 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-17 14:01:42.358  7041  7410 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:01:42.359  7041  7410 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:01:42.360  7041  7410 D bt_hci_bdroid: postload
08-17 14:01:42.362  7041  7410 D bte_conf: Device ID record 1 : primary
08-17 14:01:42.362  7041  7410 D bte_conf:   vendorId            = 00c4
08-17 14:01:42.362  7041  7410 D bte_conf:   vendorIdSource      = 0001
08-17 14:01:42.362  7041  7410 D bte_conf:   product             = 13a1
08-17 14:01:42.362  7041  7410 D bte_conf:   version             = 1000
08-17 14:01:42.362  7041  7410 D bte_conf:   clientExecutableURL = 
08-17 14:01:42.362  7041  7410 D bte_conf:   serviceDescription  = 
08-17 14:01:42.362  7041  7410 D bte_conf:   documentationURL    = 
08-17 14:01:42.362  7041  7410 D bte_conf: bte_load_did_conf no section named DID2.
08-17 14:01:42.363  7041  7466 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:01:42.363  7041  7464 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-17 14:01:42.367  7041  7466 D bt_hci_bdroid: Used up Tx Cmd credits
,08-17 14:01:42.369  7041  7406 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 14:01:42.370  7041  7406 D BluetoothAdapterProperties: ScanMode =  20
08-17 14:01:42.370  7041  7406 D BluetoothAdapterProperties: State =  11
08-17 14:01:42.371  7041  7406 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 14:01:42.371  7041  7406 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 14:01:42.372  7041  7406 D BluetoothAdapterProperties: Setting state to 12
08-17 14:01:42.372  7041  7406 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 14:01:42.372  7041  7410 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 14:01:42.373  7041  7466 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:01:42.373  1035  1111 D BluetoothManagerService: Message: 60
08-17 14:01:42.373  7041  7406 I BluetoothAdapterState: Entering On State
08-17 14:01:42.366  7494  7494 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:42.366  7494  7494 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:42.374  7041  7410 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 14:01:42.373  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 14:01:42.376  7041  7490 E bt_mct  : hci lib postload completed
08-17 14:01:42.378  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-17 14:01:42.384  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:42.384  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:42.384  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:42.384  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:42.384  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:42.384  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:42.384  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:42.384  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:01:42.387  7041  7464 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:42.387  7041  7464 W bt-smp  : Plain text(LSB ~ MSB) = d3 9b 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:01:42.387  7041  7464 W bt-smp  : Encrypted text(LSB ~ MSB) = d3 c1 69 df a9 82 e4 c8 a3 94 c7 6c 36 b7 66 01 
08-17 14:01:42.387  7041  7464 W bt-btm  : Stopping oneshot timer
08-17 14:01:42.388  1853  2461 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:42.393  7041  7410 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:01:42.393  7041  7410 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-17 14:01:42.400  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:01:42.405  7041  7464 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:42.405  7041  7464 W bt-smp  : Plain text(LSB ~ MSB) = e1 d9 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:01:42.405  7041  7464 W bt-smp  : Encrypted text(LSB ~ MSB) = d6 a0 c7 30 d1 1f 8f f8 60 00 41 85 02 94 21 f2 
08-17 14:01:42.405  7041  7464 W bt-btm  : Stopping oneshot timer
08-17 14:01:42.406  7041  7406 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 14:01:42.406  7041  7406 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 14:01:42.406  7041  7406 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-17 14:01:42.407  7041  7406 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-17 14:01:42.409  1853  1853 D BluetoothHeadset: Proxy object connected
08-17 14:01:42.411  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:42.411  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:42.411  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:42.411  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:42.411  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:42.411  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:42.411  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:42.411  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:42.414  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:01:42.418  6889  6906 D BluetoothPan: onBluetoothStateChange on: true
08-17 14:01:42.418  6889  6906 D BluetoothPan: onBluetoothStateChange call bindService
08-17 14:01:42.423  6889  6905 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 14:01:42.424  7041  7464 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:42.424  7041  7464 W bt-smp  : Plain text(LSB ~ MSB) = 56 a6 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:01:42.424  7041  7464 W bt-smp  : Encrypted text(LSB ~ MSB) = 3a a4 3d 4e 45 73 08 e6 34 0c 90 ee 64 f2 1d 49 
08-17 14:01:42.424  7041  7464 W bt-btm  : Stopping oneshot timer
08-17 14:01:42.424  7041  7406 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-17 14:01:42.426  1853  4004 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:01:42.431  6889  6889 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:01:42.431  6889  6889 D PanProfile: Bluetooth service connected
08-17 14:01:42.440  7041  7464 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:42.440  7041  7464 W bt-smp  : Plain text(LSB ~ MSB) = 69 c7 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-17 14:01:42.440  7041  7464 W bt-smp  : Encrypted text(LSB ~ MSB) = e5 9d b2 bb f9 c8 f8 6e 70 ec d3 65 58 e6 1b a6 
,08-17 14:01:42.440  7041  7464 W bt-btm  : Stopping oneshot timer
08-17 14:01:42.442  1853  1853 D BluetoothHeadset: Proxy object connected
08-17 14:01:42.444  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:01:42.447  6889  6906 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 14:01:42.447  1035  1035 D BluetoothA2dp: Proxy object connected
08-17 14:01:42.453  6889  6889 D BluetoothInputDevice: Proxy object connected
08-17 14:01:42.453  6889  6889 D HidProfile: Bluetooth service connected
,08-17 14:01:42.456  6889  7499 D BluetoothMap: onBluetoothStateChange: up=true
08-17 14:01:42.457  7041  7464 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:42.458  7041  7464 W bt-smp  : Plain text(LSB ~ MSB) = e0 9f 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:01:42.458  7041  7464 W bt-smp  : Encrypted text(LSB ~ MSB) = 37 4b 63 7d 64 38 88 24 0a b3 80 2a 24 48 9e 4a 
08-17 14:01:42.458  7041  7464 W bt-btm  : Stopping oneshot timer
08-17 14:01:42.461  1853  4003 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:42.461  6889  6889 D BluetoothMap: Proxy object connected
08-17 14:01:42.461  6889  6889 D MapProfile: Bluetooth service connected
08-17 14:01:42.461  6889  6889 D BluetoothMap: getConnectedDevices()
08-17 14:01:42.462  7041  7496 V BluetoothMapService: getConnectedDevices()
08-17 14:01:42.463  7511  7511 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-17 14:01:42.465  1853  1853 D BluetoothHeadset: Proxy object connected
08-17 14:01:42.465  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:42.466  1035  1035 D BluetoothHeadset: Proxy object connected
,08-17 14:01:42.469  1035  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 14:01:42.469  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-17 14:01:42.470  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-17 14:01:42.471  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:42.471  1941  2104 D LGBluetoothAPIService: Message: 1
08-17 14:01:42.471  1941  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-17 14:01:42.475  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:01:42.475  1035  1111 D BluetoothManagerService: Message: 40
08-17 14:01:42.475  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 14:01:42.478  7041  7041 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:01:42.479  7041  7041 D BluetoothMapService: STATE_ON
08-17 14:01:42.481  6889  6889 D LocalBluetoothProfileManager: Adding local A2DP profile
08-17 14:01:42.484  1035  1111 D BluetoothManagerService: Message: 30
08-17 14:01:42.485  1941  2104 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-17 14:01:42.489  6889  6889 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-17 14:01:42.489  6708  6708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 14:01:42.490  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:42.492  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:42.494  1035  1111 D BluetoothManagerService: Message: 30
08-17 14:01:42.496  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:42.496  7041  7041 V BluetoothPbapService: Pbap Service onCreate
08-17 14:01:42.496  7041  7041 V BluetoothPbapService: Starting PBAP service
08-17 14:01:42.498  7041  7041 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-17 14:01:42.498  7041  7041 V BluetoothPbapService: Pbap Service onBind
08-17 14:01:42.499  7041  7041 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:42.499  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-17 14:01:42.499  7041  7041 V BluetoothPbapService: state: 12
08-17 14:01:42.499  7041  7041 V BluetoothMapService: Handler(): got msg=1
08-17 14:01:42.500  7041  7041 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-17 14:01:42.501  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 14:01:42.502  7041  7041 D LGBluetoothAPIServer: [BTUI] onCreate()
08-17 14:01:42.502  7041  7041 D LGBluetoothAPIServer: [BTUI] onBind()
08-17 14:01:42.503  6889  6889 D BluetoothA2dp: Proxy object connected
,08-17 14:01:42.504  7041  7514 D BluetoothMapMasInstance: MAS initSocket()
08-17 14:01:42.504  6889  6889 D A2dpProfile: Bluetooth service connected
08-17 14:01:42.505  7041  7514 D BluetoothMapMasInstance:   masId = 00
08-17 14:01:42.505  7041  7514 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 14:01:42.505  7041  7514 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 14:01:42.505  7041  7514 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-17 14:01:42.506  6889  6889 D BluetoothHeadset: Proxy object connected
08-17 14:01:42.508  6889  6889 D HeadsetProfile: Bluetooth service connected
08-17 14:01:42.508  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-17 14:01:42.508  1941  2104 D LGBluetoothAPIService: Message: 100
08-17 14:01:42.508  1941  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 14:01:42.508  7041  7041 V BluetoothPbapService: Handler(): got msg=1
08-17 14:01:42.508  1035  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:42.509  7041  7041 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-17 14:01:42.510  7041  7041 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:01:42.510  7041  7041 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:42.510  7041  7041 V BluetoothPbapReceiver: ***********state = 12
08-17 14:01:42.510  7041  7514 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:42.511  7041  7515 V BluetoothPbapService: Pbap Service initSocket
08-17 14:01:42.511  1035  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:42.513  6889  6889 D BluetoothPbap: Proxy object connected
08-17 14:01:42.514  6889  6889 D PbapServerProfile: Bluetooth service connected
08-17 14:01:42.514  7041  7410 D BluetoothAdapterProperties: Scan Mode:21
08-17 14:01:42.514  7041  7410 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 14:01:42.515  7041  7514 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 14:01:42.515  7041  7514 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 14:01:42.515  7041  7514 D BluetoothMapMasInstance: Accepting socket connection...
08-17 14:01:42.516  7041  7515 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:42.517  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:01:42.517  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:42.517  2198  2198 D c       : Getting all permits...
08-17 14:01:42.517  2198  2198 D a       : Opening database...
08-17 14:01:42.518  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:42.520  7041  7515 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 14:01:42.520  7041  7515 V BluetoothPbapService: Succeed to create listening socket 
08-17 14:01:42.520  7041  7515 V BluetoothPbapService: Accepting socket connection...
08-17 14:01:42.521  2198  2198 D a       : Opening database auth.proximity.permit_store...
08-17 14:01:42.521  2198  2198 D a       : Closing database...
08-17 14:01:42.522  6889  6889 D DockEventReceiver: finishStartingService: stopping service
08-17 14:01:42.536  6889  6889 D BluetoothPermissionRequest: onReceive
,08-17 14:01:42.538  6889  6889 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-17 14:01:42.540  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:01:42.543  7041  7041 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 14:01:42.544  7041  7041 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-17 14:01:42.549  7041  7041 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-17 14:01:42.568  7041  7041 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:01:42.569  7041  7041 V BtOppService: onCreate
,08-17 14:01:42.575  7041  7041 V BluetoothOppNotification: send message
08-17 14:01:42.579  7041  7041 V BtOppService: Starting RfcommListener
08-17 14:01:42.584  7041  7041 D BluetoothOppPreference: Dumping Names:  
08-17 14:01:42.584  7041  7041 D BluetoothOppPreference: {}
,08-17 14:01:42.584  7041  7041 D BluetoothOppPreference: Dumping Channels:  
,08-17 14:01:42.584  7041  7041 D BluetoothOppPreference: {}
08-17 14:01:42.585  7041  7041 V BtOppService: onStartCommand
08-17 14:01:42.586  7041  7522 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 14:01:42.587  7041  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 14:01:42.588  7041  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3162cee9 on behalf of 
08-17 14:01:42.588  7041  7519 V BtOppService: Deleted complete outbound shares, number =  0
08-17 14:01:42.589  7041  7522 V BluetoothOppNotification: update too frequent, put in queue
08-17 14:01:42.590  7041  7519 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 14:01:42.590  7041  7522 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 14:01:42.590  7041  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 14:01:42.590  7041  7519 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 14:01:42.591  7041  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1353476e on behalf of 
08-17 14:01:42.591  7041  7041 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:42.591  7041  7041 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 14:01:42.591  7041  7522 V BluetoothOppNotification: update too frequent, put in queue
08-17 14:01:42.591  7041  7519 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@74d1e0f on behalf of 
08-17 14:01:42.593  7041  7522 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 14:01:42.594  7041  7041 V BluetoothOppNotification: new notify threadi!
08-17 14:01:42.595  7041  7041 V BluetoothOppNotification: send delay message
08-17 14:01:42.596  7041  7041 V BtOppService: start RfcommListener
08-17 14:01:42.596  7041  7523 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-17 14:01:42.598  7041  7523 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29988e9c on behalf of 
08-17 14:01:42.599  7041  7523 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 14:01:42.600  7041  7523 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 14:01:42.602  7041  7523 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a1070a5 on behalf of 
08-17 14:01:42.602  7041  7041 V BtOppService: RfcommListener started
08-17 14:01:42.602  7041  7041 V BtOppService: ContentObserver received notification
08-17 14:01:42.602  7041  7524 V BtOppRfcommListener: Starting RFCOMM listener....
08-17 14:01:42.602  7041  7041 V BtOppService: ContentObserver received notification
08-17 14:01:42.603  1035  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:42.603  7041  7524 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:01:42.604  7041  7524 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-17 14:01:42.604  7041  7524 V BtOppRfcommListener: Started RFCOMM listener....
08-17 14:01:42.604  7041  7524 I BtOppRfcommListener: Accept thread started.
08-17 14:01:42.604  7041  7525 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 14:01:42.604  7041  7524 V BtOppRfcommListener: Accepting connection...
08-17 14:01:42.605  7041  7525 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 14:01:42.611  7041  7523 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-17 14:01:42.612  7041  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ff06c7a on behalf of 
,08-17 14:01:42.612  7041  7523 V BluetoothOppNotification: outbound notification was removed.
08-17 14:01:42.613  7041  7523 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 14:01:42.615  7041  7525 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 14:01:42.615  7041  7523 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ac78c2b on behalf of 
08-17 14:01:42.616  7041  7523 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 14:01:42.618  7041  7523 V BluetoothOppNotification: inbound notification was removed.
08-17 14:01:42.618  7041  7523 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 14:01:42.619  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:42.619  7041  7041 V BluetoothFtpService: Ftp Service onCreate
08-17 14:01:42.619  7041  7041 I BluetoothFtpService: Ftp Service onCreate
08-17 14:01:42.620  7041  7523 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33c7221 on behalf of 
08-17 14:01:42.620  7041  7041 V BluetoothFtpService: Ftp Service onStartCommand
08-17 14:01:42.620  7041  7041 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:42.620  7041  7041 V BluetoothFtpService: Starting Listening on sockets
08-17 14:01:42.620  7041  7041 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:01:42.620  7041  7041 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:01:42.620  7041  7041 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:01:42.620  7041  7041 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:42.620  7041  7041 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 14:01:42.620  7041  7041 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 14:01:42.622  7041  7041 V BluetoothFtpService: Handler(): got msg=1
08-17 14:01:42.623  7041  7041 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 14:01:42.623  7041  7041 V BluetoothFtpService: Ftp Service initSocket
,08-17 14:01:42.629  1035  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:01:42.629  7041  7041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:42.631  7041  7041 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 14:01:42.633  7041  7526 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-17 14:01:42.652  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:42.653  7041  7041 V BluetoothSapService: Sap Service onCreate
,08-17 14:01:42.656  7041  7041 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:42.656  7041  7041 V BluetoothSapService: state: 12
08-17 14:01:42.656  7041  7041 V BluetoothSapService: Starting SAP server process
08-17 14:01:42.658  7041  7041 V BluetoothSapService: SAP Service startRfcommListenerThread
08-17 14:01:42.646  7527  7527 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:42.646  7527  7527 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:42.660  7041  7528 V BluetoothSapService: Sap Service initRfcommSocket
08-17 14:01:42.661  1035  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:42.662  7041  7528 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:42.663  7041  7528 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-17 14:01:42.663  7041  7528 V BluetoothSapService: Succeed to create listening socket 
08-17 14:01:42.663  7041  7528 V BluetoothSapService: Accepting socket connection...
08-17 14:01:42.671  7527  7527 V BT_SAP  : Event pipe created
08-17 14:01:42.671  7527  7527 V BT_SAP  : create_server_socket qcom.sap.server
08-17 14:01:42.671  7527  7527 V BT_SAP  : created socket fd 6
,08-17 14:01:43.176  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:01:43.176  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:01:43.186  1035  1435 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-17 14:01:43.188  1035  1435 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-17 14:01:43.266  1035  1890 I ActivityManager: Killing 7091:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-17 14:01:43.298  1035  2003 W libprocessgroup: failed to open /acct/uid_10011/pid_7091/cgroup.procs: No such file or directory
,08-17 14:01:43.597  7041  7041 V BluetoothOppNotification: new notify threadi!
,08-17 14:01:43.598  7041  7041 V BluetoothOppNotification: send delay message
,08-17 14:01:43.611  7041  7538 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-17 14:01:43.617  7041  7538 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24cd0f5d on behalf of 
,08-17 14:01:43.623  7041  7538 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 14:01:43.625  7041  7538 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 14:01:43.626  7041  7538 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24ec10d2 on behalf of 
08-17 14:01:43.626  7041  7538 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 14:01:43.628  7041  7538 V BluetoothOppNotification: outbound notification was removed.
08-17 14:01:43.628  7041  7538 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 14:01:43.629  7041  7538 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a0f55a3 on behalf of 
08-17 14:01:43.630  7041  7538 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 14:01:43.632  7041  7538 V BluetoothOppNotification: inbound notification was removed.
08-17 14:01:43.633  7041  7538 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-17 14:01:43.636  7041  7538 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b150a0 on behalf of 
,08-17 14:01:44.205  1035  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:44.205  1035  1994 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@6a2aaf mBinding = false
,08-17 14:01:44.234  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:01:44.234  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:01:44.235  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-17 14:01:44.238  1035  1111 D BluetoothManagerService: Message: 2
08-17 14:01:44.238  1035  1111 D BluetoothManagerService: Sending off request.
08-17 14:01:44.239  7041  7057 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 14:01:44.240  7041  7406 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 14:01:44.240  7041  7406 D BluetoothAdapterProperties: Setting state to 13
08-17 14:01:44.240  7041  7406 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 14:01:44.241  7041  7406 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 14:01:44.241  7041  7406 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 14:01:44.243  7041  7410 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:01:44.245  7041  7406 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 14:01:44.246  7041  7514 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 14:01:44.246  7041  7514 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:44.246  7041  7514 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 14:01:44.246  7041  7514 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 14:01:44.246  7041  7514 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-17 14:01:44.246  7041  7514 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 14:01:44.246  7041  7514 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 14:01:44.246  7041  7514 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-17 14:01:44.250  7041  7515 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:44.251  7041  7524 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:44.251  7041  7528 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:44.254  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 14:01:44.254  7041  7464 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 14:01:44.256  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-17 14:01:44.256  7041  7464 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 14:01:44.257  7041  7406 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 14:01:44.268  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:44.268  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:44.268  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:44.268  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:44.268  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:44.268  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:44.268  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:44.268  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:44.268  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:01:44.275  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:44.275  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:44.277  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:44.278  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:44.278  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:44.278  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:44.278  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:44.278  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:01:44.278  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:44.278  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:44.278  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:44.279  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:01:44.279  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:44.280  1035  1111 D BluetoothManagerService: Message: 60
08-17 14:01:44.280  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 14:01:44.280  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-17 14:01:44.285  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:44.287  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:01:44.292  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:44.294  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:44.297  7041  7041 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:44.297  7041  7041 D BluetoothMapService: STATE_TURNING_OFF
08-17 14:01:44.297  7041  7041 V BluetoothMapService: Handler(): got msg=4
08-17 14:01:44.297  7041  7041 D BluetoothMapService: MAP Service closeService in
08-17 14:01:44.297  7041  7041 D BluetoothMapMasInstance: MAP Service shutdown
08-17 14:01:44.298  7041  7041 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:01:44.298  7041  7041 V BluetoothMapService: MAP Service closeService out
,08-17 14:01:44.301  7041  7041 V BtOppService: Receiver DISABLED_ACTION 
08-17 14:01:44.301  7041  7041 I BtOppRfcommListener: stopping Accept Thread
08-17 14:01:44.301  7041  7041 V BtOppRfcommListener: close mBtServerSocket
08-17 14:01:44.302  7041  7524 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 14:01:44.302  7041  7041 V BtOppRfcommListener: waiting for thread to terminate
08-17 14:01:44.302  7041  7041 V BtOppRfcommListener: done waiting for thread to terminate
08-17 14:01:44.305  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-17 14:01:44.315  7041  7526 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:01:44.319  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 14:01:44.322  7041  7041 V BtOppService: onDestroy
08-17 14:01:44.323  7041  7041 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-17 14:01:44.328  7041  7041 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:01:44.328  7041  7041 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:44.328  7041  7041 V BluetoothPbapReceiver: ***********state = 13
,08-17 14:01:44.332  7041  7041 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-17 14:01:44.334  7041  7041 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:44.334  7041  7041 V BluetoothPbapService: state: 13
08-17 14:01:44.335  7041  7041 V BluetoothPbapService: Pbap Service closeService in
08-17 14:01:44.338  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:01:44.339  7041  7041 V BluetoothPbapService: successfully stopped pbap service
08-17 14:01:44.339  7041  7041 V BluetoothPbapService: Pbap Service closeService out
08-17 14:01:44.340  7041  7041 V BluetoothPbapService: Pbap Service onDestroy
08-17 14:01:44.340  7041  7041 V BluetoothPbapService: Pbap Service closeService in
08-17 14:01:44.340  7041  7041 V BluetoothPbapService: Pbap Service closeService out
08-17 14:01:44.340  7041  7041 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-17 14:01:44.362  6889  6889 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:01:44.373  6889  6889 D BluetoothPbap: Proxy object disconnected
08-17 14:01:44.374  6889  6889 D PbapServerProfile: Bluetooth service disconnected
08-17 14:01:44.378  6889  6889 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 14:01:44.385  6889  6889 D BluetoothPermissionRequest: onReceive
08-17 14:01:44.385  6889  6889 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-17 14:01:44.391  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:01:44.395  7041  7041 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-17 14:01:44.395  7041  7041 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-17 14:01:44.395  7041  7041 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-17 14:01:44.399  7041  7041 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:44.399  7041  7041 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 14:01:44.400  7041  7041 V BluetoothFtpService: Ftp Service onStartCommand
08-17 14:01:44.400  7041  7041 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:44.401  7041  7041 V BluetoothFtpService: Ftp Service closeService
08-17 14:01:44.401  7041  7041 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-17 14:01:44.402  7041  7041 V BluetoothFtpService: successfully stopped ftp service
08-17 14:01:44.402  7041  7041 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:01:44.402  7041  7041 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:01:44.402  7041  7041 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:01:44.403  7041  7041 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:44.403  7041  7041 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 14:01:44.403  7041  7041 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 14:01:44.404  7041  7041 V BluetoothFtpService: Ftp Service onDestroy
08-17 14:01:44.404  7041  7041 V BluetoothFtpService: Ftp Service closeService
,08-17 14:01:44.407  7041  7041 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:44.407  7041  7041 V BluetoothSapService: state: 13
08-17 14:01:44.408  7041  7041 V BluetoothSapService: Stopping SAP server process
,08-17 14:01:44.409  7041  7041 V BluetoothSapService: Sap Service closeSapService in
,08-17 14:01:44.409  7041  7041 V BluetoothSapService: Close listen Socket : 
08-17 14:01:44.409  7041  7041 V BluetoothSapService: Close rfcomm Socket : 
08-17 14:01:44.409  7041  7041 V BluetoothSapService: Close sapd  Socket : 
08-17 14:01:44.412  7041  7041 V BluetoothSapService: Sap Service closeSapService out
08-17 14:01:44.412  7041  7041 V BluetoothSapService: Sap Service onDestroy
08-17 14:01:44.412  7041  7041 V BluetoothSapService: Sap Service closeSapService in
08-17 14:01:44.412  7041  7041 V BluetoothSapService: Close listen Socket : 
08-17 14:01:44.412  7041  7041 V BluetoothSapService: Close rfcomm Socket : 
08-17 14:01:44.412  7041  7041 V BluetoothSapService: Close sapd  Socket : 
08-17 14:01:44.413  7041  7041 V BluetoothSapService: Sap Service closeSapService out
08-17 14:01:45.257  7041  7410 D bt_hci_bdroid: cleanup
,08-17 14:01:45.268  7041  7466 I bt_lpm  : LPM is already off!!!
08-17 14:01:45.268  7041  7490 I bt_userial_mct: exiting userial_read_thread
08-17 14:01:45.268  7041  7490 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 14:01:45.269  7041  7464 W bt-btif : ag scb idx 1 not allocated
08-17 14:01:45.269  7041  7464 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 14:01:45.269  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:45.269  7041  7464 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:45.269  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:01:45.270  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 14:01:45.273  7041  7410 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 14:01:45.273  7041  7466 I bt_vendor: hw_epilog_process
08-17 14:01:45.274  7041  7410 D bt_hci_bdroid: cleanup Finalizing cleanup
08-17 14:01:45.274  7041  7410 D bt_userial_mct: userial_close
08-17 14:01:45.274  7041  7410 E bt_userial_mct: pthread_join() FAILED result:3
08-17 14:01:45.274  7041  7410 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 14:01:45.274  7041  7464 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:01:45.274  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 14:01:45.274  7041  7464 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:01:45.274  7041  7464 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 14:01:45.274  7041  7464 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:01:45.274  7041  7464 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 14:01:45.281  7041  7410 D bt_hci_bdroid: set_power 0
08-17 14:01:45.281  7041  7410 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 14:01:45.281  7041  7410 I bt_vendor: bluetooth satus is on
08-17 14:01:45.281  7041  7410 I bt_vendor: bt-vendor : resetting BT status
08-17 14:01:45.281  7041  7410 I bt_vendor: Starting hciattach daemon
08-17 14:01:45.281  7041  7410 I bt_vendor: try to set false
,08-17 14:01:45.288  7041  7410 I bt_vendor: Starting hciattach daemon
08-17 14:01:45.288  7041  7410 I bt_vendor: try to set false
08-17 14:01:45.289  7041  7410 I bt_vendor: cleanup
08-17 14:01:45.290  7041  7464 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 14:01:45.291  7041  7410 I GKI_LINUX: GKI_exit_task 0 done
08-17 14:01:45.291  7041  7410 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 14:01:45.292  7041  7406 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 14:01:45.296  7041  7041 D HeadsetService: Received stop request...Stopping profile...
,08-17 14:01:45.300  7041  7041 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 14:01:45.300  7041  7041 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:01:45.300  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:45.301  7041  7446 D HeadsetStateMachine: Exit Disconnected: -1
08-17 14:01:45.306  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:45.306  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:45.309  7041  7406 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-17 14:01:45.311  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:45.311  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 14:01:45.314  7041  7041 D A2dpService: Received stop request...Stopping profile...
08-17 14:01:45.315  7041  7456 D A2dpStateMachine: Exit Disconnected: -1
08-17 14:01:45.316  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-17 14:01:45.316  7041  7041 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-17 14:01:45.318  7041  7041 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 14:01:45.318  7041  7041 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:01:45.318  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:45.319  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-17 14:01:45.319  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 14:01:45.320  7041  7041 D HidService: Received stop request...Stopping profile...
08-17 14:01:45.320  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
,08-17 14:01:45.325  7041  7041 D HeadsetStateMachine: Unbinding service...
08-17 14:01:45.326  7041  7041 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:01:45.326  7041  7041 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:01:45.326  7041  7041 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:01:45.326  7041  7041 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:01:45.327  7041  7041 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 14:01:45.327  7041  7041 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:01:45.327  7041  7041 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 14:01:45.328  7041  7041 D HealthService: Received stop request...Stopping profile...
08-17 14:01:45.328  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:45.331  7041  7041 D PanService: Received stop request...Stopping profile...
08-17 14:01:45.331  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:45.332  7041  7041 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:01:45.335  7041  7041 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 14:01:45.335  7041  7041 D BtGatt.GattService: stop()
08-17 14:01:45.335  7041  7041 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 14:01:45.336  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:45.338  7041  7041 D BluetoothMapService: Received stop request...Stopping profile...
08-17 14:01:45.338  7041  7041 D BluetoothMapService: stop()
08-17 14:01:45.339  7041  7041 D BluetoothMapEmailAppObserver: deinitObservers()
08-17 14:01:45.339  7041  7041 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 14:01:45.340  7041  7041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3254d474
08-17 14:01:45.341  7041  7041 I BluetoothA2dpServiceJni: cleanupNative
08-17 14:01:45.341  7041  7457 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 14:01:45.342  7041  7041 I GKI_LINUX: GKI_exit_task 2 done
08-17 14:01:45.342  7041  7041 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 14:01:45.342  7041  7041 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:01:45.342  7041  7041 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 14:01:45.342  7041  7041 V BluetoothMapService: Handler(): got msg=4
08-17 14:01:45.342  7041  7041 D BluetoothMapService: MAP Service closeService in
08-17 14:01:45.342  7041  7041 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:01:45.342  7041  7041 V BluetoothMapService: MAP Service closeService out
08-17 14:01:45.343  7041  7406 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 14:01:45.343  7041  7406 D BluetoothAdapterProperties: Setting state to 10
08-17 14:01:45.343  7041  7406 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-17 14:01:45.347  1035  1111 D BluetoothManagerService: Message: 60
08-17 14:01:45.347  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 14:01:45.347  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-17 14:01:45.347  7041  7406 I BluetoothAdapterState: Entering OffState
08-17 14:01:45.348  1853  2461 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:45.350  6889  7499 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:01:45.351  7041  7041 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 14:01:45.351  7041  7041 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:01:45.351  7041  7041 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:01:45.352  7041  7041 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 14:01:45.352  7041  7041 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 14:01:45.356  7041  7041 D BluetoothMapService: cleanup()
08-17 14:01:45.356  7041  7041 D BluetoothMapService: MAP Service closeService in
08-17 14:01:45.356  7041  7041 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 14:01:45.356  7041  7041 V BluetoothMapService: MAP Service closeService out
,08-17 14:01:45.360  6889  7499 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:01:45.361  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:45.362  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:01:45.362  6889  7499 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 14:01:45.363  6889  7499 D BluetoothMap: onBluetoothStateChange: up=false
08-17 14:01:45.363  6889  7499 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:45.364  1853  4003 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:45.365  6889  7499 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:01:45.365  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:01:45.366  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 14:01:45.366  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-17 14:01:45.369  1035  1111 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 14:01:45.369  1035  1111 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 14:01:45.369  1035  1111 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@6a2aaf mBinding = false
,08-17 14:01:45.372  1035  1111 D BluetoothManagerService: Sending unbind request.
08-17 14:01:45.377  7041  7410 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 14:01:45.378  7041  7041 I GKI_LINUX: GKI_exit_task 1 done
08-17 14:01:45.378  7041  7041 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 14:01:45.378  7041  7041 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 14:01:45.378  7041  7041 I art     : --- WEIRD: removing null entry 248
08-17 14:01:45.378  7041  7041 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-17 14:01:45.378  7041  7041 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 14:01:45.379  7041  7041 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-17 14:01:45.380  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-17 14:01:45.385  7041  7041 I art     : System.exit called, status: 0
08-17 14:01:45.385  7041  7041 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 14:01:45.404   318  2208 V AudioFlinger: 7041 died, releasing its sessions
08-17 14:01:45.404   318  2208 V AudioFlinger:  pid 1853 @ 0
08-17 14:01:45.404   318  2208 V AudioFlinger:  pid 3418 @ 1
08-17 14:01:45.404   318  2208 V AudioFlinger:  pid 3418 @ 2
,08-17 14:01:45.408  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-17 14:01:45.408  1941  2104 D LGBluetoothAPIService: Message: 101
08-17 14:01:45.408  1941  2104 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-17 14:01:45.408  1941  2104 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-17 14:01:45.408  1941  2104 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-17 14:01:45.410  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-17 14:01:45.440  1035  1890 I ActivityManager: Process com.android.bluetooth (pid 7041) has died
,08-17 14:01:45.441  1035  1890 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-17 14:01:45.441  1035  1890 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-17 14:01:45.456  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:45.457  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-17 14:01:45.462  1941  2104 D LGBluetoothAPIService: Message: 2
08-17 14:01:45.462  1941  2104 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-17 14:01:45.464  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:45.465  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:45.466  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 14:01:45.466  6889  6889 D LGBluetoothEventManager: [BTUI] clear device connection state
08-17 14:01:45.471  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 14:01:45.477  1602  1602 D BluetoothAdapter: 249548254: getState() :  mService = null. Returning STATE_OFF
08-17 14:01:45.477  1602  1602 D BluetoothAdapter: 249548254: getState() :  mService = null. Returning STATE_OFF
,08-17 14:01:45.528  1035  2032 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7581 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-17 14:01:45.529  6889  6889 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:01:45.579  7581  7581 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 14:01:45.579  7581  7581 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:01:45.579  7581  7581 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-17 14:01:45.580  7581  7581 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 14:01:45.598  7581  7581 D BluetoothAdapterApp: Loading JNI Library
,08-17 14:01:45.633  7581  7581 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@115ba5dc Instance Count = 1
,08-17 14:01:45.638  7581  7581 D BluetoothAdapterApp: onCreate
08-17 14:01:45.663  7581  7581 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-17 14:01:45.664  7581  7581 D ProfileConfigQcom: Adding HeadsetService
08-17 14:01:45.664  7581  7581 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-17 14:01:45.664  7581  7581 D ProfileConfigQcom: Adding A2dpService
08-17 14:01:45.664  7581  7581 D ProfileConfigQcom: [BTUI] HidService is supported
08-17 14:01:45.665  7581  7581 D ProfileConfigQcom: Adding HidService
08-17 14:01:45.665  7581  7581 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-17 14:01:45.665  7581  7581 D ProfileConfigQcom: Adding HealthService
08-17 14:01:45.665  7581  7581 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 14:01:45.666  7581  7581 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 14:01:45.666  7581  7581 D ProfileConfigQcom: Adding PanService
08-17 14:01:45.667  7581  7581 D ProfileConfigQcom: [BTUI] GattService is supported
08-17 14:01:45.667  7581  7581 D ProfileConfigQcom: Adding GattService
08-17 14:01:45.667  7581  7581 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-17 14:01:45.667  7581  7581 D ProfileConfigQcom: Adding BluetoothMapService
08-17 14:01:45.668  7581  7581 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 14:01:45.669  7581  7581 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:01:45.670  7581  7581 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:45.670  7581  7581 V BluetoothPbapReceiver: ***********state = 10
08-17 14:01:45.672  7581  7581 V LGMDMManagerInternal: Create singleton instance
08-17 14:01:45.756  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:01:45.762  6889  6889 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 14:01:45.763  7581  7581 D LGBluetoothAPIServer: [BTUI] onCreate()
08-17 14:01:45.763  7581  7581 D LGBluetoothAPIServer: [BTUI] onBind()
08-17 14:01:45.764  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-17 14:01:45.764  1941  2104 D LGBluetoothAPIService: Message: 100
08-17 14:01:45.764  1941  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 14:01:45.778  6889  6889 D BluetoothPermissionRequest: onReceive
,08-17 14:01:45.780  6889  6889 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-17 14:01:45.780  6889  6889 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-17 14:01:45.783  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:01:45.787  7581  7581 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-17 14:01:45.790  7581  7581 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:01:45.793  7581  7581 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-17 14:01:45.793  7581  7581 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-17 14:01:45.794  7581  7581 V BluetoothSapReceiver: SapReceiver onReceive 
,08-17 14:01:45.795  7581  7581 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:01:45.795  7581  7581 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-17 14:01:45.798  6975  6975 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings,
,08-17 14:01:47.297  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:01:47.297  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:50.311  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:01:50.311  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@292d6556 added. We now have 6 listener(s)
08-17 14:01:50.312  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:50.323  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:50.323  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13b889d7 added. We now have 7 listener(s)
08-17 14:01:50.323  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:50.324  6708  6833 I System.out: IsBluetoothEnabled
08-17 14:01:50.325  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:50.325  1035  1050 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-17 14:01:50.325  1035  1111 D BluetoothManagerService: Message: 2
08-17 14:01:50.329  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:50.331  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:50.331  1035  2032 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 14:01:50.348  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 14:01:50.349  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:01:50.349  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 14:01:50.349  1035  1111 D BluetoothManagerService: Message: 1
08-17 14:01:50.349  1035  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-17 14:01:50.374  1035  1111 D BluetoothManagerService: Message: 20
08-17 14:01:50.374  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37d1f566:true
,08-17 14:01:50.378  7581  7581 D BluetoothAdapterState: make
08-17 14:01:50.383  7581  7581 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 14:01:50.383  7581  7581 I bluedroid-qcom: init
08-17 14:01:50.385  7581  7609 I BluetoothAdapterState: Entering OffState
08-17 14:01:50.385  7581  7581 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 14:01:50.385  7581  7581 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 14:01:50.385  7581  7581 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 14:01:50.385  7581  7581 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 14:01:50.385  7581  7581 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 14:01:50.387  7581  7581 I bluedroid-qcom: get_profile_interface socket
08-17 14:01:50.387  7581  7581 I bluedroid-qcom: get_profile_interface map_client
,08-17 14:01:50.392  7581  7613 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 14:01:50.394  7581  7613 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 14:01:50.387  7612  7612 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:50.387  7612  7612 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:50.403  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 14:01:50.403  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-17 14:01:50.409  7612  7612 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 14:01:50.409  7612  7612 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 14:01:50.409  7612  7612 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-17 14:01:50.411  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-17 14:01:50.411  1035  1111 D BluetoothManagerService: Message: 40
08-17 14:01:50.411  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 14:01:50.412  7581  7596 I bluedroid-qcom: config_hci_snoop_log
08-17 14:01:50.414  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 14:01:50.414  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-17 14:01:50.415  7612  7612 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-17 14:01:50.418  7581  7613 D BluetoothAdapterProperties: Name is: G3
,08-17 14:01:50.421  7612  7612 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 14:01:50.421  7612  7612 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-17 14:01:50.427  7581  7609 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-17 14:01:50.428  7581  7609 D BluetoothAdapterProperties: Setting state to 11
08-17 14:01:50.428  7581  7609 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 14:01:50.430  1035  1111 D BluetoothManagerService: Message: 60
08-17 14:01:50.430  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 14:01:50.430  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-17 14:01:50.434  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:50.435  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 14:01:50.439  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:50.442  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-17 14:01:50.444  7581  7609 I LGBluetoothServiceJni: classInitNative: succeeds
08-17 14:01:50.452  7581  7581 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:01:50.452  7581  7581 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:50.452  7581  7581 V BluetoothPbapReceiver: ***********state = 11
08-17 14:01:50.457  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:01:50.479  7581  7609 D BluetoothBondStateMachine: make
,08-17 14:01:50.487  6889  6889 D BluetoothPermissionRequest: onReceive
08-17 14:01:50.487  7581  7626 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 14:01:50.488  7581  7609 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.488  7581  7609 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 14:01:50.488  7581  7609 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.488  7581  7609 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 14:01:50.490  7581  7609 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 14:01:50.493  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:01:50.494  7581  7609 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:50.503  7581  7609 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 14:01:50.503  7581  7581 D HeadsetService: Received start request. Starting profile...
08-17 14:01:50.504  7581  7581 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 14:01:50.504  7581  7581 D LGBluetoothHfpAdapter: Version 1.6
08-17 14:01:50.507  7581  7581 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:01:50.508  7581  7581 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 14:01:50.509  7581  7581 D HeadsetStateMachine: make
08-17 14:01:50.509  7581  7609 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:50.514  7581  7609 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:50.522  7581  7609 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:50.527  7581  7609 E BluetoothAdapterService: File transfer profiles supported!!
08-17 14:01:50.532  7581  7609 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 14:01:50.545  7581  7609 V LGMDMManager: Create singleton instance
08-17 14:01:50.546  7581  7581 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:01:50.546  7581  7581 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 14:01:50.550  7581  7609 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 14:01:50.551  7581  7581 D HeadsetStateMachine: max_hf_connections = 1
08-17 14:01:50.551  7581  7581 I bluedroid-qcom: get_profile_interface handsfree
08-17 14:01:50.552  7581  7581 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 14:01:50.553   318  1397 V AudioPolicyService: registerClient() client 0xb557c4c0, uid 1002
,08-17 14:01:50.553   318  2208 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 14:01:50.553   318  2208 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:01:50.553   318  2208 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:01:50.553  7581  7581 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 14:01:50.555   318  1396 V AudioFlinger: registerClient() client 0xb55819e8, pid 7581
08-17 14:01:50.555   318  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:50.555   318  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:50.555  7581  7581 V ToneGenerator: Create Track: 0xb4928080
08-17 14:01:50.555  1035  1994 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:50.555  1035  1994 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:50.555  7581  7581 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 14:01:50.555  7581  7581 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-17 14:01:50.555  1602  2103 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:50.555  1602  2103 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:50.555  1853  2461 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:50.555  1853  2461 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:50.555  7581  7596 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:50.555   318  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 14:01:50.555  7581  7596 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 14:01:50.555   318  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 14:01:50.555   318  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:01:50.556   318  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:01:50.556   318  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:50.556   318  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:50.556  3418  3434 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 14:01:50.556  3418  3434 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 14:01:50.556  1035  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:50.556  1035  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:50.556  1602  2102 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:50.556  1602  2102 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:50.556  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:50.556  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:50.556  3418  3433 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:50.556  3418  3433 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 14:01:50.557   318  1397 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 14:01:50.557  7581  7597 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 14:01:50.557  7581  7597 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 14:01:50.557   318  2197 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 14:01:50.557   318  2197 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 14:01:50.557   318  2197 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 14:01:50.557   318 , 2197 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 14:01:50.557  7581  7581 V AudioSystem: getLatency() output 2, latency 50
08-17 14:01:50.557  7581  7581 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 14:01:50.557  7581  7581 V AudioTrack: createTrack_l() output 2 afLatency 50
08-17 14:01:50.558   318  2208 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 14:01:50.558   318  2208 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 14:01:50.558   318  2208 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 14:01:50.558   318  2208 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 14:01:50.558   318  2208 V AudioFlinger: createTrack() lSessionId: 22
08-17 14:01:50.558  7581  7581 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-17 14:01:50.559   318  2208 V AudioFlinger: acquiring 22 from 7581, for 7581
08-17 14:01:50.559   318  2208 V AudioFlinger:  added new entry for 22
08-17 14:01:50.559  7581  7581 V ToneGenerator: ToneGenerator INIT OK, time: 144838
08-17 14:01:50.559  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.560  7581  7632 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 14:01:50.560  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.561  7581  7632 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 14:01:50.561  7581  7632 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 14:01:50.561  7581  7632 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 14:01:50.562  7581  7581 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:50.562   318   318 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7581
08-17 14:01:50.563  7581  7581 D A2dpService: Received start request. Starting profile...
08-17 14:01:50.563   318   318 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 14:01:50.563   318   318 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 14:01:50.563   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-17 14:01:50.564   318   318 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 14:01:50.564   318   318 V voice   : voice_set_parameters: exit with code(0)
08-17 14:01:50.564   318   318 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-17 14:01:50.564   318   318 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 14:01:50.564   318   318 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 14:01:50.564   318   318 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 14:01:50.564   318   318 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-17 14:01:50.564   318   318 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 14:01:50.564  7581  7581 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 14:01:50.564  7581  7632 V ToneGenerator: ToneGenerator destructor
08-17 14:01:50.564  7581  7632 V ToneGenerator: stopTone
08-17 14:01:50.564  7581  7632 V ToneGenerator: Delete Track: 0xb4928080
,08-17 14:01:50.565  7581  7581 V Avrcp   : make
08-17 14:01:50.565  7581  7581 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-17 14:01:50.565  7581  7581 I bluedroid-qcom: get_profile_interface avrcp
,08-17 14:01:50.567  1035  1051 W Process : Unable to open /proc/7633/status
08-17 14:01:50.567  7581  7632 V AudioTrack: ~AudioTrack, releasing session id from 7581 on behalf of 7581
08-17 14:01:50.569   318  1396 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 14:01:50.569   318  1396 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 14:01:50.569   318  1396 V AudioFlinger: PlaybackThread::Track destructor
08-17 14:01:50.569   318  1256 V AudioPolicyService: AudioCommandThread() waking up
08-17 14:01:50.569   318  1396 V AudioFlinger: removeClient_l() pid 7581, calling pid 318
08-17 14:01:50.569   318  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 14:01:50.569   318  1256 V AudioPolicyManager: releaseOutput() 2
08-17 14:01:50.569   318  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 14:01:50.569   318   318 V AudioFlinger: releasing 22 from 7581 for 7581
08-17 14:01:50.569   318   318 V AudioFlinger:  decremented refcount to 0
08-17 14:01:50.569   318   318 V AudioFlinger: purging stale effects
08-17 14:01:50.576  7581  7581 V AudioManager: registerRemoteController: size of Media player list: 0
08-17 14:01:50.578  7581  7581 E AudioManager: No RCC entry present to update
08-17 14:01:50.578  7581  7581 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 14:01:50.581  7581  7581 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-17 14:01:50.582  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 14:01:50.582  7581  7581 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-17 14:01:50.585  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 14:01:50.692  1035  1970 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:01:50.692  1035  1970 V SIM_STK : Menu title from STK is T-Mobile
,08-17 14:01:50.807  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 14:01:50.817  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 14:01:50.822  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 14:01:50.822  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 14:01:50.823  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 14:01:50.823  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 14:01:50.823  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:01:50.823  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 14:01:50.823  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 14:01:50.823  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 14:01:50.823  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:01:50.823  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 14:01:50.823  7581  7581 I BluetoothA2dpServiceJni: classInitNative
08-17 14:01:50.823  7581  7581 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:01:50.823  7581  7581 D A2dpStateMachine: make
08-17 14:01:50.824  7581  7581 I bluedroid-qcom: get_profile_interface a2dp
08-17 14:01:50.825  7581  7641 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 14:01:50.829  7581  7581 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:01:50.829  7581  7581 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 14:01:50.830  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.831  7581  7640 D A2dpStateMachine: Enter Disconnected: -2
08-17 14:01:50.831  7581  7581 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 14:01:50.832  7581  7581 D HidService: Received start request. Starting profile...
08-17 14:01:50.832  7581  7581 I bluedroid-qcom: get_profile_interface hidhost
08-17 14:01:50.832  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.832  7581  7581 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:01:50.834  7581  7581 D HealthService: Received start request. Starting profile...
08-17 14:01:50.835  7581  7581 I bluedroid-qcom: get_profile_interface health
08-17 14:01:50.835  7581  7581 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:01:50.835  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.836  7581  7581 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 14:01:50.837  7581  7581 D PanService: Received start request. Starting profile...
08-17 14:01:50.837  7581  7581 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 14:01:50.837  7581  7581 I bluedroid-qcom: get_profile_interface pan
08-17 14:01:50.843  7581  7581 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-17 14:01:50.843  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.844  7581  7581 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-17 14:01:50.847  7581  7581 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:01:50.847  7581  7581 D BtGatt.GattService: Received start request. Starting profile...
08-17 14:01:50.848  7581  7581 D BtGatt.GattService: start()
08-17 14:01:50.848  7581  7581 I bluedroid-qcom: get_profile_interface gatt
08-17 14:01:50.848  7581  7581 D BtGatt.AdvertiseManager: advertise manager created
08-17 14:01:50.855  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.855  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.856  7581  7581 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-17 14:01:50.856  7581  7581 V BluetoothMapService: BluetoothMapBinder()
08-17 14:01:50.857  7581  7581 D BluetoothMapService: Received start request. Starting profile...
08-17 14:01:50.857  7581  7581 D BluetoothMapService: start()
08-17 14:01:50.859  7581  7581 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-17 14:01:50.859  7581  7581 D BluetoothMapEmailAppObserver: createReceiver()
08-17 14:01:50.860  7581  7581 D BluetoothMapEmailAppObserver: initObservers()
08-17 14:01:50.860  7581  7581 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-17 14:01:50.866  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:50.866  7581  7581 D HeadsetStateMachine: Proxy object connected
08-17 14:01:50.866  7581  7581 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 14:01:50.866  7581  7581 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-17 14:01:50.867  7581  7632 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 14:01:50.868  7581  7632 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 14:01:50.868  7581  7632 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-17 14:01:50.869  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:01:50.869  7581  7581 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:01:50.869  7581  7581 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:01:50.869  7581  7581 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:01:50.869  7581  7581 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:50.869  7581  7581 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-17 14:01:50.873  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 14:01:50.875  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:01:50.876  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:01:50.876  7581  7581 V PanService: [BTUI] SIM Extra State :ABSENT
08-17 14:01:50.878  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 14:01:50.880  7581  7581 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-17 14:01:50.880  7581  7581 V BluetoothMapService: Handler(): got msg=1
08-17 14:01:50.881  7581  7609 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-17 14:01:50.881  7581  7609 I bluedroid-qcom: enable
08-17 14:01:50.881  7581  7648 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 14:01:50.882  7581  7648 I bt-btu  : btu_task pending for preload complete event
08-17 14:01:50.882  7581  7609 I bt_hci_bdroid: init
08-17 14:01:50.882  7581  7609 I bt_vendor: bt-vendor : init
08-17 14:01:50.882  7581  7609 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 14:01:50.882  7581  7609 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 14:01:50.882  7581  7609 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 14:01:50.882  7581  7609 D bt_userial_mct: userial_init
08-17 14:01:50.882  7581  7609 D bt_hci_bdroid: set_power 1
08-17 14:01:50.882  7581  7609 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 14:01:50.882  7581  7609 I bt_vendor: Starting hciattach daemon
08-17 14:01:50.882  7581  7609 I bt_vendor: try to set true
08-17 14:01:50.876  7651  7651 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:50.876  7651  7651 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:50.896  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 14:01:50.950  7658  7658 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 14:01:50.972  7659  7659 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 14:01:51.009  7661  7661 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 14:01:51.033  7662  7662 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-17 14:01:51.045  7663  7663 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-17 14:01:51.068  7664  7664 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-17 14:01:51.092  7666  7666 I libmdmdetect: ESOC framework not supported
08-17 14:01:51.094  7666  7666 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-17 14:01:51.105  7666  7666 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-17 14:01:51.106  7666  7666 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-17 14:01:51.106  7666  7666 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-17 14:01:51.106  7666  7666 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-17 14:01:51.106  7666  7666 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-17 14:01:51.106  7666  7666 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-17 14:01:51.106  7666  7666 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-17 14:01:51.154  7666  7667 E QC-QMI  : qmi_client [7666] 15: failed to locate client data
08-17 14:01:51.155   483   483 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-17 14:01:51.155   483   483 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-17 14:01:51.217  7672  7672 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-17 14:01:51.232  7673  7673 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 14:01:51.284  7581  7609 I bt_vendor: bluetooth satus is on
08-17 14:01:51.285  7581  7609 D bt_hci_bdroid: preload
08-17 14:01:51.285  7581  7650 D bt_userial_mct: userial_open(port:0)
08-17 14:01:51.285  7581  7650 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 14:01:51.290  7581  7650 I bt_vendor: Done intiailizing UART
08-17 14:01:51.293  7581  7650 I bt_vendor: Done intiailizing UART
08-17 14:01:51.293  7581  7650 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 14:01:51.293  7581  7650 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 14:01:51.294  7581  7648 I bt-btu  : btu_task received preload complete event
08-17 14:01:51.294  7581  7648 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 14:01:51.294  7581  7648 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-17 14:01:51.296  7581  7648 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-17 14:01:51.299  7581  7678 D bt_userial_mct: Entering userial_read_thread()
,08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 14:01:51.305  7581  7648 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 14:01:51.404  7581  7648 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-17 14:01:51.404  7581  7648 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a2061 
08-17 14:01:51.404  7581  7648 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a2061 
,08-17 14:01:51.434  7581  7613 E bt-btif : Calling BTA_HhEnable
08-17 14:01:51.434  7581  7613 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-17 14:01:51.434  7581  7613 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-17 14:01:51.438  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 14:01:51.438  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 14:01:51.438  7581  7613 D BluetoothAdapterProperties: Name is: G3
08-17 14:01:51.440  7581  7613 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:01:51.440  7581  7613 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:01:51.440  7581  7613 D bt_hci_bdroid: postload
08-17 14:01:51.441  7581  7613 D bte_conf: Device ID record 1 : primary
08-17 14:01:51.441  7581  7613 D bte_conf:   vendorId            = 00c4
08-17 14:01:51.441  7581  7613 D bte_conf:   vendorIdSource      = 0001
08-17 14:01:51.441  7581  7613 D bte_conf:   product             = 13a1
08-17 14:01:51.441  7581  7613 D bte_conf:   version             = 1000
08-17 14:01:51.441  7581  7613 D bte_conf:   clientExecutableURL = 
08-17 14:01:51.441  7581  7613 D bte_conf:   serviceDescription  = 
08-17 14:01:51.441  7581  7613 D bte_conf:   documentationURL    = 
08-17 14:01:51.442  7581  7650 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 14:01:51.442  7581  7613 D bte_conf: bte_load_did_conf no section named DID2.
08-17 14:01:51.445  7581  7609 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 14:01:51.445  7581  7609 D BluetoothAdapterProperties: ScanMode =  20
08-17 14:01:51.445  7581  7609 D BluetoothAdapterProperties: State =  11
08-17 14:01:51.445  7581  7609 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 14:01:51.446  7581  7609 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 14:01:51.446  7581  7609 D BluetoothAdapterProperties: Setting state to 12
08-17 14:01:51.446  7581  7609 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 14:01:51.447  7581  7613 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 14:01:51.446  7680  7680 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:51.456  1035  1111 D BluetoothManagerService: Message: 60
08-17 14:01:51.456  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 14:01:51.456  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-17 14:01:51.446  7680  7680 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:51.465  7581  7650 D bt_hci_bdroid: Used up Tx Cmd credits
,08-17 14:01:51.476  7581  7678 E bt_mct  : hci lib postload completed
08-17 14:01:51.477  7581  7609 I BluetoothAdapterState: Entering On State
08-17 14:01:51.477  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:51.480  7581  7613 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:01:51.480  7581  7613 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-17 14:01:51.497  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:51.497  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:51.497  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:51.497  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:51.497  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:51.497  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:51.497  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:51.497  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:01:51.512  7581  7609 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 14:01:51.512  7581  7609 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 14:01:51.512  7581  7609 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-17 14:01:51.521  7581  7609 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-17 14:01:51.522  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:51.523  1853  1853 D BluetoothHeadset: Proxy object connected
08-17 14:01:51.524  7581  7648 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-17 14:01:51.524  7581  7648 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-17 14:01:51.524  7581  7648 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-17 14:01:51.526  7581  7609 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-17 14:01:51.527  7581  7648 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 14:01:51.527  7581  7648 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-17 14:01:51.527  7581  7648 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-17 14:01:51.528  7581  7613 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 14:01:51.549  7581  7648 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:51.549  7581  7648 W bt-smp  : Plain text(LSB ~ MSB) = c3 97 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:01:51.549  7581  7648 W bt-smp  : Encrypted text(LSB ~ MSB) = 7b ad fe ba cb 3c c6 12 08 ca 51 92 fb ac d9 47 
08-17 14:01:51.549  7581  7648 W bt-btm  : Stopping oneshot timer
,08-17 14:01:51.552  6889  6906 D BluetoothPan: onBluetoothStateChange on: true
08-17 14:01:51.552  6889  6906 D BluetoothPan: onBluetoothStateChange call bindService
08-17 14:01:51.568  7685  7685 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-17 14:01:51.582  6889  7499 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 14:01:51.582  6889  6889 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:01:51.583  6889  6889 D PanProfile: Bluetooth service connected
,08-17 14:01:51.587  1853  3528 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:51.591  7581  7648 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:51.591  7581  7648 W bt-smp  : Plain text(LSB ~ MSB) = ea d1 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:01:51.591  7581  7648 W bt-smp  : Encrypted text(LSB ~ MSB) = e4 ff d2 29 83 fc ec 89 a1 21 a4 ec 72 d5 9b e5 
08-17 14:01:51.591  7581  7648 W bt-btm  : Stopping oneshot timer
08-17 14:01:51.592  1853  1853 D BluetoothHeadset: Proxy object connected
08-17 14:01:51.592  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:01:51.593  6889  6906 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 14:01:51.594  1035  1035 D BluetoothA2dp: Proxy object connected
08-17 14:01:51.600  6889  6905 D BluetoothMap: onBluetoothStateChange: up=true
08-17 14:01:51.600  6889  6889 D BluetoothInputDevice: Proxy object connected
08-17 14:01:51.600  6889  6889 D HidProfile: Bluetooth service connected
,08-17 14:01:51.604  7581  7648 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:51.604  7581  7648 W bt-smp  : Plain text(LSB ~ MSB) = f9 36 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:01:51.604  7581  7648 W bt-smp  : Encrypted text(LSB ~ MSB) = 65 17 4e ff 55 1c 00 7a 46 d9 48 de b4 cb e3 3b 
08-17 14:01:51.604  7581  7648 W bt-btm  : Stopping oneshot timer
,08-17 14:01:51.606  6889  7499 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:51.606  6889  6889 D BluetoothMap: Proxy object connected
08-17 14:01:51.607  6889  6889 D MapProfile: Bluetooth service connected
08-17 14:01:51.607  6889  6889 D BluetoothMap: getConnectedDevices()
08-17 14:01:51.608  7581  7699 V BluetoothMapService: getConnectedDevices()
08-17 14:01:51.611  6889  6889 D BluetoothHeadset: Proxy object connected
08-17 14:01:51.612  6889  6889 D HeadsetProfile: Bluetooth service connected
08-17 14:01:51.613  1853  2461 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:51.615  7581  7648 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:51.615  7581  7648 W bt-smp  : Plain text(LSB ~ MSB) = 1f 16 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:01:51.615  7581  7648 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a de 2d ee 37 91 f0 12 db f7 8e cd ca 38 89 13 
08-17 14:01:51.615  7581  7648 W bt-btm  : Stopping oneshot timer
08-17 14:01:51.616  1853  1853 D BluetoothHeadset: Proxy object connected
08-17 14:01:51.617  6889  6906 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:01:51.621  6889  6889 D BluetoothA2dp: Proxy object connected
08-17 14:01:51.621  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:01:51.621  6889  6889 D A2dpProfile: Bluetooth service connected
08-17 14:01:51.622  1035  1035 D BluetoothHeadset: Proxy object connected
08-17 14:01:51.625  1035  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 14:01:51.625  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-17 14:01:51.625  7581  7648 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 14:01:51.625  7581  7648 W bt-smp  : Plain text(LSB ~ MSB) = be b8 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 14:01:51.625  7581  7648 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 0d 0b 39 38 6b ed 70 28 cc 8a 4c 57 d0 9b a7 
08-17 14:01:51.626  7581  7648 W bt-btm  : Stopping oneshot timer
08-17 14:01:51.627  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-17 14:01:51.627  1035  1111 D BluetoothManagerService: Message: 40
08-17 14:01:51.627  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 14:01:51.629  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:51.630  1941  2104 D LGBluetoothAPIService: Message: 1
,08-17 14:01:51.630  1941  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-17 14:01:51.630  1941  2104 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-17 14:01:51.630  1941  2104 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-17 14:01:51.634  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-17 14:01:51.638  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:51.639  7581  7581 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:51.639  7581  7581 D BluetoothMapService: STATE_ON
08-17 14:01:51.646  6889  6889 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-17 14:01:51.649  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-17 14:01:51.656  6889  6889 D DockEventReceiver: finishStartingService: stopping service
08-17 14:01:51.662  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:51.662  7581  7581 V BluetoothPbapService: Pbap Service onCreate
08-17 14:01:51.663  7581  7581 V BluetoothPbapService: Starting PBAP service
08-17 14:01:51.665  7581  7581 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-17 14:01:51.665  7581  7581 V BluetoothPbapService: Pbap Service onBind
,08-17 14:01:51.666  7581  7581 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:51.666  6889  6889 D BluetoothPbap: Proxy object connected
08-17 14:01:51.666  7581  7581 V BluetoothPbapService: state: 12
08-17 14:01:51.666  6889  6889 D PbapServerProfile: Bluetooth service connected
08-17 14:01:51.666  7581  7581 V BluetoothMapService: Handler(): got msg=1
08-17 14:01:51.667  7581  7581 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-17 14:01:51.668  7581  7581 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 14:01:51.668  7581  7581 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:51.668  7581  7581 V BluetoothPbapReceiver: ***********state = 12
08-17 14:01:51.668  7581  7704 D BluetoothMapMasInstance: MAS initSocket()
08-17 14:01:51.669  7581  7704 D BluetoothMapMasInstance:   masId = 00
08-17 14:01:51.669  7581  7704 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 14:01:51.669  7581  7704 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 14:01:51.669  7581  7704 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-17 14:01:51.669  7581  7581 V BluetoothPbapService: Handler(): got msg=1
08-17 14:01:51.670  7581  7581 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-17 14:01:51.671  1035  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:51.671  7581  7705 V BluetoothPbapService: Pbap Service initSocket
08-17 14:01:51.672  2198  2198 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 14:01:51.672  1035  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:51.672  2198  2198 D c       : Getting all permits...
08-17 14:01:51.672  2198  2198 D a       : Opening database...
08-17 14:01:51.675  7581  7704 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:51.675  7581  7705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:51.677  7581  7704 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 14:01:51.677  7581  7705 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 14:01:51.677  7581  7704 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 14:01:51.677  7581  7704 D BluetoothMapMasInstance: Accepting socket connection...
08-17 14:01:51.677  7581  7613 D BluetoothAdapterProperties: Scan Mode:21
08-17 14:01:51.678  7581  7613 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 14:01:51.678  2198  2198 D a       : Opening database auth.proximity.permit_store...
,08-17 14:01:51.679  7581  7705 V BluetoothPbapService: Succeed to create listening socket 
08-17 14:01:51.679  7581  7705 V BluetoothPbapService: Accepting socket connection...
08-17 14:01:51.680  2198  2198 D a       : Closing database...
08-17 14:01:51.683  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:51.693  6889  6889 D BluetoothPermissionRequest: onReceive
,08-17 14:01:51.695  6889  6889 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 14:01:51.696  6889  6889 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 14:01:51.700  7581  7581 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 14:01:51.701  7581  7581 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-17 14:01:51.707  7581  7581 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-17 14:01:51.734  7581  7581 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 14:01:51.734  7581  7581 V BtOppService: onCreate
,08-17 14:01:51.739  7581  7581 V BluetoothOppNotification: send message
,08-17 14:01:51.762  7581  7710 V BtOppService: Deleted complete outbound shares, number =  0
,08-17 14:01:51.764  7581  7710 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 14:01:51.765  7581  7710 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 14:01:51.873  1035  2027 I art     : Explicit concurrent mark sweep GC freed 42245(2037KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.370ms total 133.047ms
,08-17 14:01:51.875  7581  7581 V BtOppService: Starting RfcommListener
08-17 14:01:51.876  7581  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10c42b70 on behalf of 
08-17 14:01:51.885  7581  7581 D BluetoothOppPreference: Dumping Names:  
08-17 14:01:51.885  7581  7581 D BluetoothOppPreference: {}
08-17 14:01:51.885  7581  7581 D BluetoothOppPreference: Dumping Channels:  
08-17 14:01:51.885  7581  7581 D BluetoothOppPreference: {}
08-17 14:01:51.885  7581  7581 V BtOppService: onStartCommand
08-17 14:01:51.888  7581  7713 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 14:01:51.888  7581  7713 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 14:01:51.890  7581  7713 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1353476e on behalf of 
08-17 14:01:51.890  7581  7713 V BluetoothOppNotification: update too frequent, put in queue
08-17 14:01:51.891  7581  7581 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:51.891  7581  7713 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 14:01:51.891  7581  7581 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-17 14:01:51.894  7581  7581 V BluetoothOppNotification: new notify threadi!
08-17 14:01:51.894  7581  7581 V BluetoothOppNotification: send delay message
08-17 14:01:51.895  7581  7581 V BtOppService: ContentObserver received notification
08-17 14:01:51.895  7581  7581 V BtOppService: ContentObserver received notification
08-17 14:01:51.895  7581  7581 V BtOppService: start RfcommListener
08-17 14:01:51.897  7581  7715 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 14:01:51.897  7581  7715 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 14:01:51.899  7581  7581 V BtOppService: RfcommListener started
08-17 14:01:51.900  7581  7714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 14:01:51.903  7581  7716 V BtOppRfcommListener: Starting RFCOMM listener....
08-17 14:01:51.904  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:01:51.905  7581  7715 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@74d1e0f on behalf of 
08-17 14:01:51.905  7581  7714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29988e9c on behalf of 
08-17 14:01:51.908  7581  7714 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 14:01:51.909  7581  7716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:51.909  7581  7715 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 14:01:51.909  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:51.910  7581  7581 V BluetoothFtpService: Ftp Service onCreate
08-17 14:01:51.910  7581  7581 I BluetoothFtpService: Ftp Service onCreate
08-17 14:01:51.910  7581  7581 V BluetoothFtpService: Ftp Service onStartCommand
08-17 14:01:51.911  7581  7581 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:51.911  7581  7581 V BluetoothFtpService: Starting Listening on sockets
08-17 14:01:51.911  7581  7581 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 14:01:51.911  7581  7581 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 14:01:51.911  7581  7581 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 14:01:51.911  7581  7581 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:51.911  7581  7581 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 14:01:51.911  7581  7581 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 14:01:51.911  7581  7716 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-17 14:01:51.911  7581  7716 V BtOppRfcommListener: Started RFCOMM listener....
08-17 14:01:51.912  7581  7716 I BtOppRfcommListener: Accept thread started.
08-17 14:01:51.912  7581  7714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 14:01:51.912  7581  7716 V BtOppRfcommListener: Accepting connection...
08-17 14:01:51.912  7581  7581 V BluetoothFtpService: Handler(): got msg=1
08-17 14:01:51.913  7581  7581 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 14:01:51.913  7581  7581 V BluetoothFtpService: Ftp Service initSocket
08-17 14:01:51.914  7581  7714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ff06c7a on behalf of 
08-17 14:01:51.915  7581  7714 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 14:01:51.916  1035  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:51.916  7581  7581 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:51.917  7581  7581 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-17 14:01:51.918  7581  7581 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 14:01:51.918  7581  7714 V BluetoothOppNotification: outbound notification was removed.
08-17 14:01:51.918  7581  7714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-17 14:01:51.919  7581  7714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ac78c2b on behalf of 
08-17 14:01:51.919  7581  7714 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 14:01:51.924  7581  7717 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-17 14:01:51.924  7581  7714 V BluetoothOppNotification: inbound notification was removed.
08-17 14:01:51.925  7581  7714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 14:01:51.926  7581  7714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27edf888 on behalf of 
08-17 14:01:51.929  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c91fd9d
08-17 14:01:51.929  7581  7581 V BluetoothSapService: Sap Service onCreate
,08-17 14:01:51.930  7581  7581 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:01:51.930  7581  7581 V BluetoothSapService: state: 12
,08-17 14:01:51.930  7581  7581 V BluetoothSapService: Starting SAP server process
08-17 14:01:51.932  7581  7581 V BluetoothSapService: SAP Service startRfcommListenerThread
08-17 14:01:51.926  7719  7719 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 14:01:51.926  7719  7719 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:51.936  7581  7718 V BluetoothSapService: Sap Service initRfcommSocket
08-17 14:01:51.937  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:51.939  7581  7718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:01:51.941  7719  7719 V BT_SAP  : Event pipe created
08-17 14:01:51.941  7719  7719 V BT_SAP  : create_server_socket qcom.sap.server
08-17 14:01:51.941  7719  7719 V BT_SAP  : created socket fd 6
08-17 14:01:51.941  7581  7718 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-17 14:01:51.942  7581  7718 V BluetoothSapService: Succeed to create listening socket 
08-17 14:01:51.942  7581  7718 V BluetoothSapService: Accepting socket connection...
,08-17 14:01:52.377  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:52.377  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:52.377  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:52.377  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:01:52.377  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:52.377  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:52.377  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:52.377  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:01:52.389  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:52.393  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:52.393  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12dc62c4 added. We now have 8 listener(s)
08-17 14:01:52.393  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:52.402  1035  1922 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-17 14:01:52.404  1035  1922 D WifiService: setWifiEnabled: false pid=6708, uid=10118
08-17 14:01:52.404  1035  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 14:01:52.409  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:52.411  1035  1933 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 14:01:52.412  1035  1933 D WifiService: setWifiEnabled: true pid=6708, uid=10118
08-17 14:01:52.412  1035  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:01:52.433  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-17 14:01:52.433  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 14:01:52.433  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-17 14:01:52.435  1035  1435 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-17 14:01:52.435  1035  1435 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-17 14:01:52.437  1035  1435 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-17 14:01:52.438  1035  1435 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 14:01:52.438  1035  1435 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 14:01:52.438  1035  1435 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 14:01:52.438  1035  1435 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 14:01:52.438  1035  1435 E WifiHW  : unknown target_country: EU , set to default
,08-17 14:01:52.438  1035  1435 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
08-17 14:01:52.438  1035  1435 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
,08-17 14:01:52.438  1035  1435 I WifiUtil: gEnableBmps=1
,08-17 14:01:52.897  7581  7581 V BluetoothOppNotification: new notify threadi!
,08-17 14:01:52.897  7581  7581 V BluetoothOppNotification: send delay message,
,08-17 14:01:52.922  7581  7738 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-17 14:01:52.926  7581  7738 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@eae1534 on behalf of 
08-17 14:01:52.926  7581  7738 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 14:01:52.928  7581  7738 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 14:01:52.929  7581  7738 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24cd0f5d on behalf of 
08-17 14:01:52.930  7581  7738 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 14:01:52.931  7581  7738 V BluetoothOppNotification: outbound notification was removed.
08-17 14:01:52.932  7581  7738 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 14:01:52.932  7581  7738 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24ec10d2 on behalf of 
08-17 14:01:52.933  7581  7738 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 14:01:52.936  7581  7738 V BluetoothOppNotification: inbound notification was removed.
08-17 14:01:52.936  7581  7738 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-17 14:01:52.939  7581  7738 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a0f55a3 on behalf of 
08-17 14:01:53.008   314   880 D SoftapController: Softap fwReload - Ok
,08-17 14:01:53.083  1035  1435 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (641ms)
,08-17 14:01:53.088  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:01:53.088  1035  1111 D Tethering: InitialState.processMessage what=4
08-17 14:01:53.089  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 14:01:53.106   314   880 D CommandListener: Setting iface cfg
08-17 14:01:53.106   314   880 D CommandListener: Trying to bring down wlan0
08-17 14:01:53.125   314   880 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:01:53.135  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:01:53.135  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 14:01:53.136  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:01:53.136  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-17 14:01:53.139  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 14:01:53.141  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 14:01:53.141  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 14:01:53.141  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:01:53.142  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:01:53.142  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:01:53.142  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 14:01:53.144  1035  1435 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-17 14:01:53.152  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:01:53.152  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 14:01:53.152  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:01:53.152  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 14:01:53.153  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 14:01:53.146  7753  7753 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:53.146  7753  7753 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:53.154  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 14:01:53.155  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 14:01:53.155  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:01:53.155  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:01:53.155  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:01:53.155  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-17 14:01:53.213  7753  7753 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 14:01:53.246  1035  1435 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:01:53.246  1035  1435 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:01:53.246  1035  1435 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-17 14:01:53.250  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:53.251  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-17 14:01:53.251  1035  1435 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 14:01:53.251  1035  1435 D WifiMonitor: connecting to supplicant
08-17 14:01:53.253  7753  7753 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 14:01:53.253  7753  7753 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-17 14:01:53.259  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:53.262  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-17 14:01:53.269  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:53.275  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:01:53.280  6995  7759 W FormManager: Network not available. Please check & try again.
08-17 14:01:53.285  6995  7760 V FormManager: Network unavailable.
08-17 14:01:53.286  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:53.295  6995  7760 V FormManager: Network unavailable.
,08-17 14:01:53.301  7753  7753 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 14:01:53.324  7753  7753 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-17 14:01:53.332  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-17 14:01:53.332  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 14:01:53.333  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-17 14:01:53.334  1035  1435 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 14:01:53.334  1035  1435 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:53.334  1035  1435 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:53.335  1035  1435 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 14:01:53.335  1035  1435 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 14:01:53.336  1035  1435 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-17 14:01:53.336  1035  1435 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 14:01:53.336  1035  1435 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 14:01:53.337  1035  1435 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 14:01:53.337  1035  1435 E WifiStateMachine: useWiFiOffloading() : false
08-17 14:01:53.337  1035  1435 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 14:01:53.337  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:53.337  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:53.337  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:53.338  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:53.338  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 14:01:53.340  1941  1941 D WfdService: Waiting for WifiP2p enabling
,08-17 14:01:53.342  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:53.345  1035  1435 D WifiNative-wlan0: doBoolean: SET update_config 1
08-17 14:01:53.346  1035  1435 D WifiNative-wlan0: SET update_config 1: returned true
08-17 14:01:53.346  1035  1435 D WifiConfigStore: Loading config and enabling all networks 
08-17 14:01:53.346  1035  1435 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 14:01:53.346  1035  1435 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-17 14:01:53.349  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-17 14:01:53.349  1035  1446 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 14:01:53.351  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:53.351  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:53.351  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:53.351  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:53.351  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:53.351  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:53.351  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:53.351  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:53.353  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:01:53.359  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 14:01:53.361  1035  1435 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-17 14:01:53.367  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 14:01:53.372  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 14:01:53.372  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 14:01:53.372  7753  7753 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-17 14:01:53.372  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 14:01:53.372  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 14:01:53.372  1035  7762 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 14:01:53.372  1035  7762 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-17 14:01:53.377  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:53.378  1035  1435 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-17 14:01:53.378  1035  1435 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 14:01:53.379  6995  7764 W FormManager: Network not available. Please check & try again.
,08-17 14:01:53.385  1035  1435 D WifiStateMachine: enableVerboseLogging : level 2
08-17 14:01:53.385  1035  1435 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 14:01:53.385  1035  1435 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 14:01:53.386  1035  1435 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-17 14:01:53.386  1035  1435 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 14:01:53.386  1035  1435 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-17 14:01:53.386  1035  1435 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-17 14:01:53.386  1035  1435 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,08-17 14:01:53.387  1035  1435 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 14:01:53.387  1035  1435 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 14:01:53.387  1035  1435 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 14:01:53.387  1035  1435 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 14:01:53.388  1035  1435 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 14:01:53.388  1035  1435 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-17 14:01:53.388  1035  1435 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-17 14:01:53.389  1035  1435 D WifiStateMachine: Setting OUI to DA-A1-19
,08-17 14:01:53.390  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-17 14:01:53.391  1941  2265 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 14:01:53.391  1941  2265 D WfdsService: Set the WFDS Monitor: true
08-17 14:01:53.391  1035  1435 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-17 14:01:53.391  1941  2265 D WfdsMonitor: WfdsMonitorThread create
08-17 14:01:53.391  1941  2265 D WfdsMonitor: WFDS Monitor is created and started
08-17 14:01:53.391  1941  2265 D WfdsService: WiFi: Supplicant connection re-established
08-17 14:01:53.391  1035  1435 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 14:01:53.391  1035  1435 D WifiNative-HAL: Setting external_sim to 1
08-17 14:01:53.391  1035  1435 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 14:01:53.392  1035  1435 D WifiNative-wlan0: SET external_sim 1: returned true
08-17 14:01:53.392  1035  1435 I WifiNative-HAL: startHal
08-17 14:01:53.392  1035  1435 D wifi    : setting scan oui 0xaf7075e0
08-17 14:01:53.392  1941  7766 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 14:01:53.392  1035  1435 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 14:01:53.393  1035  1435 I WifiNative-HAL: startHal
08-17 14:01:53.393  1941  7766 E CtrlSupplicant: Succeed to open control connection
08-17 14:01:53.393  1035  1435 D wifi    : setting scan oui 0xaf7075e0
08-17 14:01:53.393  1941  7766 E CtrlSupplicant: Succeed to open monitor connection
08-17 14:01:53.393  1035  1435 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 14:01:53.393  1035  1435 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 14:01:53.393  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 14:01:53.394  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-17 14:01:53.394  1035  1435 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-17 14:01:53.394  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 14:01:53.394  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 14:01:53.394  1941  7766 D WfdsMonitor: Supplicant connection established
08-17 14:01:53.395  1941  2265 D WfdsService: Connected to the supplicant for wfds
08-17 14:01:53.395  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 14:01:53.395  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-17 14:01:53.395  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 14:01:53.395  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-17 14:01:53.395  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 14:01:53.395  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 14:01:53.396  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 14:01:53.396  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 14:01:53.396  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 14:01:53.396  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 14:01:53.396  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 14:01:53.396  7753  7753 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-17 14:01:53.397  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,08-17 14:01:53.397  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 14:01:53.397  6995  7765 V FormManager: Network unavailable.
08-17 14:01:53.397  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 14:01:53.398  1035  1435 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 14:01:53.400  1035  1435 E WifiNative: : [147,664,825 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 14:01:53.401  1035  1435 D WifiNative-wlan0: doBoolean: RECONNECT
,08-17 14:01:53.401  1035  1435 D WifiNative-wlan0: RECONNECT: returned true
08-17 14:01:53.401  1035  1435 D WifiNative-wlan0: doString: [STATUS]
08-17 14:01:53.402  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 14:01:53.402  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 14:01:53.402  1035  1435 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 14:01:53.402  1035  1435 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:01:53.403  6995  7765 V FormManager: Network unavailable.
08-17 14:01:53.403  1035  1435 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:01:53.404  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.404  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:01:53.404  4371  4371 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 14:01:53.406   314   880 D CommandListener: Setting iface cfg
08-17 14:01:53.406   314   880 D CommandListener: Trying to bring up p2p0
08-17 14:01:53.406  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:01:53.406  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 14:01:53.406  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 14:01:53.406  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-17 14:01:53.406  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.406  1035  1390 D LGWifiP2pService: P2pEnablingState
08-17 14:01:53.406  1035  1556 I WifiNative-HAL: startHal
08-17 14:01:53.406  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.406  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf7075e0
08-17 14:01:53.406  1035  1390 D LGWifiP2pService: P2p socket connection successful
08-17 14:01:53.406  1035  1556 D wifi    : failed to get capabilities : -3
08-17 14:01:53.407  1035  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.407  1035  1556 E WifiScanningService: could not get scan capabilities
08-17 14:01:53.407  1035  1390 D LGWifiP2pService: P2pEnabledState
08-17 14:01:53.407  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 14:01:53.408  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 14:01:53.408  1941  1941 D WfdsService: WifiP2pState is changed : true
08-17 14:01:53.409  1941  2265 D WfdsService: Receive the WFDS_ENABLE Method
08-17 14:01:53.409  1941  2265 D WfdsService: Set the WFDS Monitor: true
08-17 14:01:53.409  1941  2265 D WfdsService: Connected to the supplicant for wfds
08-17 14:01:53.409  1941  2265 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 14:01:53.409  7753  7753 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-17 14:01:53.409  1941  2265 D WfdsService: selectPreferredScanChannel [36]
,08-17 14:01:53.409  1941  2265 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-17 14:01:53.410  1035  1435 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 14:01:53.411  1035  1435 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-17 14:01:53.411  1035  1435 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 14:01:53.412  1035  1435 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 14:01:53.412  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 14:01:53.412  1035  1435 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-17 14:01:53.412  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-17 14:01:53.413  1035  1435 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 14:01:53.413  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 14:01:53.413  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-17 14:01:53.413  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 14:01:53.413  1035  1390 D LGWifiP2pService: before postfix = G3
08-17 14:01:53.413  1035  1390 D WifiServerServiceExt: postfix byte check : 2
08-17 14:01:53.413  1035  1390 D LGWifiP2pService: after postfix = G3
08-17 14:01:53.413  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 14:01:53.414  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 14:01:53.414  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 14:01:53.414  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 14:01:53.414  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 14:01:53.414  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-17 14:01:53.415  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 14:01:53.415  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 14:01:53.415  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 14:01:53.415  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-17 14:01:53.416  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-17 14:01:53.416  1941  1941 D WfdsService: isConnected: false
,08-17 14:01:53.418  1035  1435 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 14:01:53.418  1035  1435 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-17 14:01:53.418  4371  4371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 14:01:53.418  7753  7753 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-17 14:01:53.418  1035  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 14:01:53.418  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 14:01:53.419  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 14:01:53.419  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 14:01:53.419  1941  1941 D WfdsService: Update P2p Interface State: 3
08-17 14:01:53.419  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-17 14:01:53.419  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 14:01:53.419  1035  1435 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 14:01:53.419  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 14:01:53.420  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-17 14:01:53.420  1035  1435 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-17 14:01:53.420  1035  1435 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-17 14:01:53.420  1035  1435 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-17 14:01:53.420  7753  7753 E wpa_supplicant: disconnect_rssi_lvl: -100
08-17 14:01:53.420  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-17 14:01:53.420  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-17 14:01:53.422  1035  1435 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=147688  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 14:01:53.422  7370  7370 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 14:01:53.422  7370  7370 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-17 14:01:53.423  1035  1435 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=147689  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 14:01:53.423  7370  7370 V [BNRBootReceiver]: Boot Receiver Return
08-17 14:01:53.423  1035  1435 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 14:01:53.423  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:53.423  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:53.425  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:53.425  1035  1435 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 14:01:53.425  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:53.425  1035  1435 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 14:01:53.425  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:53.425  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-17 14:01:53.425  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 14:01:53.428  4371  7767 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 14:01:53.431  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:53.431  4371  7768 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 14:01:53.431  4371  7768 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 14:01:53.432  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-17 14:01:53.432  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 14:01:53.433  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 14:01:53.433  1035  1390 D LGWifiP2pService: InactiveState
08-17 14:01:53.433  1035  1390 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.433  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.433  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-17 14:01:53.433  7753  7753 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:53.434  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:01:53.434  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:53.434  1035  7762 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:53.434  1035  7762 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:53.434  7753  7753 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 14:01:53.434  7753  7753 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.435  1941  7766 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:53.435  1035  7762 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:53.435  1035  7762 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.435  1035  7762 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.435  1035  7762 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.435  7753  7753 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.435  1941  7766 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:53.435  1035  7762 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:53.435  1035  7762 E WifiMonitor: WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.435  1035  7762 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.435  1035  7762 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.436  1035  1435 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 14:01:53.437  1035  1435 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:01:53.437  1035  1435 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:01:53.438  1035  1435 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 14:01:53.438  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-17 14:01:53.438  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 14:01:53.438  7753  7753 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:01:53.438  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 14:01:53.438  1035  7762 ,E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:01:53.438  1035  7762 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:01:53.438  1035  7762 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 14:01:53.439  1035  1435 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-17 14:01:53.439  1035  1435 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-17 14:01:53.440  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 14:01:53.440  7753  7753 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:53.440  1035  7762 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:01:53.440  1035  7762 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:53.441  1035  7762 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:53.441  1035  7762 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 14:01:53.441  7753  7753 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 14:01:53.441  7753  7753 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.442  7753  7753 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.442  1941  7766 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 14:01:53.442  1941  7766 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:53.442  1941  7766 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-17 14:01:53.442  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 14:01:53.443  1035  1390 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.443  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.443  1035  1390 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.443  1035  1390 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.443  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.443  1035  1390 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.443  1035  1390 D LGWifiP2pService: InactiveState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.443  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.443  1035  1390 D LGWifiP2pService: DefaultState{ when=-11ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.444  1035  1390 D LGWifiP2pService: InactiveState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.444  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.444  1035  1390 D LGWifiP2pService: DefaultState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.444  1035  1035 E WifiServerServiceExt: No p2p device connected
08-17 14:01:53.444  1035  1390 D LGWifiP2pService: InactiveState{ when=-7ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.444  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:53.445  1941  2265 W WfdsService: DefaultState - msg [9441285] is not handled
08-17 14:01:53.445  1035  7762 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:53.445  1035  7762 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.445  1035  7762 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.445  1035  7762 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.445  1035  7762 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 14:01:53.445  1035  7762 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.446  1035  7762 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.446  1035  7762 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 14:01:53.446  1035  1435 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-17 14:01:53.446  1035  1435 D WifiNative-wlan0: doBoolean: SCAN
08-17 14:01:53.447  1035  1435 D WifiNative-wlan0: SCAN: returned false
08-17 14:01:53.447  1035  1435 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=147713  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 14:01:53.449  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:53.449  1602  1602 I StatusBar.NetworkController: mWifi,Connected = false, mWifiLevel = 0
08-17 14:01:53.450  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:53.450  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:53.451  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 14:01:53.451  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:53.451  1035  1435 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=147717  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 14:01:53.451  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:01:53.451  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:53.451  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:53.451  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:53.451  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:53.451  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:01:53.451  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:01:53.451  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:01:53.451  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:53.452  1035  1435 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:53.452  1035  1435 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:53.452  1035  1435 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:53.453  1035  1435 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:53.453  1035  1435 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 14:01:53.453  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:01:53.458  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-17 14:01:53.458  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 14:01:53.458  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:53.458  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 14:01:53.460  6708  6833 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-17 14:01:53.461  6708  6833 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-17 14:01:53.463  6708  6833 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@26db2ef8 Bundle[{}]
08-17 14:01:53.464  6708  6833 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 14:01:53.464  6708  6833 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 14:01:53.465  6708  6833 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 14:01:53.465  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:53.466  6708  6833 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 14:01:53.467  6708  6833 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 14:01:53.468  6708  6833 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-17 14:01:53.475  6708  6833 I System.out: Running OutgoingSocketThread
08-17 14:01:53.476  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:53.476  6708  7769 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 845)
,08-17 14:01:53.477  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:53.478  6708  7769 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46499
08-17 14:01:53.478  6708  7769 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-17 14:01:53.478  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:01:53.482  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:53.489  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:01:53.494  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:01:53.500  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:53.501  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:01:53.502  6952  6952 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 14:01:54.067  7753  7753 E wpa_supplicant: USIM:  scard_init function
08-17 14:01:54.068  7753  7753 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-17 14:01:54.079  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-17 14:01:54.079  1035  7762 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-17 14:01:54.080  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-17 14:01:54.080  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: WPS-AP-AVAILABLE 
08-17 14:01:54.080  1035  7762 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-17 14:01:54.083  1035  1435 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:01:54.083  1035  1435 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:01:54.084  1035  1435 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:01:54.084  1035  1435 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 14:01:54.084  1035  1435 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-17 14:01:54.085  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-17 14:01:54.085  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-17 14:01:54.105  1035  1435 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=148371  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-17 14:01:54.112  1035  1435 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=148378  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 14:01:54.114  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.114  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.114  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 14:01:54.116  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:54.116  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:54.120  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:01:54.126  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:54.126  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-17 14:01:54.130  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-17 14:01:54.135  6889  6889 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-17 14:01:54.147  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 14:01:54.158  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:01:54.167  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:54.174  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:54.174  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:54.175  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:01:54.212  7753  7753 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 14:01:54.222  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-17 14:01:54.222  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-17 14:01:54.222  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-17 14:01:54.222  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-17 14:01:54.222  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:01:54.222  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:01:54.228  1035  1435 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=148495  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 14:01:54.229  1035  1435 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=148495  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 14:01:54.230  1035  1435 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=148496
08-17 14:01:54.230  1035  1435 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=148496
,08-17 14:01:54.235  7753  7753 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:01:54.235  7753  7753 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:01:54.238  1035  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 14:01:54.244  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:01:54.244  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:01:54.245  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-17 14:01:54.245  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:01:54.245  1035  7762 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:01:54.245  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-17 14:01:54.245  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:01:54.245  1035  7762 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 14:01:54.245  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:01:54.245  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-17 14:01:54.255  1035  1435 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=148522
08-17 14:01:54.256  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=148522
08-17 14:01:54.256  1035  1435 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 47 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=148522
08-17 14:01:54.257  1035  1435 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=148523  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 14:01:54.262  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.262  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.262  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-17 14:01:54.267  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:54.267  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:54.269  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 14:01:54.280  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.281  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.281  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-17 14:01:54.282  1035  1435 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=148548  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 14:01:54.283  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:54.283  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-17 14:01:54.284  1035  1435 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:54.284  1035  1435 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:54.285  1035  1435 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:54.285  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:54.285  1035  1435 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 14:01:54.286  1035  1435 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=148552  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 14:01:54.286  1035  1435 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=148553  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 14:01:54.290  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 14:01:54.293  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:54.295  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.297  1035  1435 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=148564
08-17 14:01:54.298  1035  1435 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=148564
08-17 14:01:54.298  1035  1435 D WifiNative-wlan0: doString: [STATUS]
08-17 14:01:54.299  1035  7762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 14:01:54.299  1035  7762 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 14:01:54.300  1035  1435 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 14:01:54.301  1035  1435 I WifiServiceExtension: setVHTCapabilityType  : false
08-17 14:01:54.303  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 14:01:54.303  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 14:01:54.303  6889  6889 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 14:01:54.303  6889  6889 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-17 14:01:54.310  1035  1435 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-17 14:01:54.310  1035  1435 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-17 14:01:54.324  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.324  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.324  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-17 14:01:54.330  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.331  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.331  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 14:01:54.332  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:54.332  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:54.335  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.338  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:54.338  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 14:01:54.343  1035  1435 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-17 14:01:54.343  1035  1483 D ConnectivityService: Got NetworkAgent Messenger
08-17 14:01:54.343  1035  1483 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-17 14:01:54.343  1035  1483 D ConnectivityService: NetworkAgent connected
08-17 14:01:54.343  1035  1435 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:01:54.344  1035  1435 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 14:01:54.344  1035  1435 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 14:01:54.344  1035  1435 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 14:01:54.346  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.348  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 14:01:54.350  6889  6889 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 14:01:54.350  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-17 14:01:54.350  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 14:01:54.350  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 14:01:54.350  6889  6889 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 14:01:54.350  6889  6889 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
,08-17 14:01:54.354  1035  1435 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 14:01:54.354  1035  1435 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:01:54.354  1035  1435 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 14:01:54.358  1035  1435 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 14:01:54.358  1035  1435 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 14:01:54.360  6889  6889 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 14:01:54.364  1035  1435 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-17 14:01:54.368   314   880 D CommandListener: Setting iface cfg
08-17 14:01:54.371  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:54.373  1035  1435 E WifiStateMachine: Start Dhcp Watchdog 2
08-17 14:01:54.374  1035  1435 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=148640  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:01:54.374  1035  1435 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=148641  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:01:54.375  1035  1435 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=148641  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:01:54.376  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:54.376  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-17 14:01:54.378  1035  7780 D DhcpStateMachine: StoppedState
08-17 14:01:54.378  1035  7780 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:54.378  1035  7780 D DhcpStateMachine: WaitBeforeStartState
,08-17 14:01:54.386  1035  1435 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=148651  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 14:01:54.387  1035  1435 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=148653  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-17 14:01:54.388  1035  1435 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=148654  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-17 14:01:54.396  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:54.396  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-17 14:01:54.398  1035  1435 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:102634] from screen [on:0 period:-1738468130] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 14:01:54.399  1035  1435 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1738468129] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-17 14:01:54.399  1035  1435 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-17 14:01:54.404  1035  1435 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.404  1035  1435 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.404  1035  1435 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.405  1035  1435 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 14:01:54.405  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.405  1035  1435 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.406  1035  1435 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=100,0,0
08-17 14:01:54.406  1035  1435 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=100,0,0
08-17 14:01:54.406  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-17 14:01:54.407  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-17 14:01:54.407  1035  1483 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-17 14:01:54.407  1035  1483 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 14:01:54.408  1035  1435 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-17 14:01:54.408  1035  1435 D WifiNative-wlan0: doBoolean: SET ps 0
08-17 14:01:54.409  1035  1435 D WifiNative-wlan0: SET ps 0: returned true
08-17 14:01:54.409  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-17 14:01:54.409  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-17 14:01:54.409  1035  1435 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-17 14:01:54.410  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@201c310 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:54.410  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@201c310 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:01:54.411  1035  7780 D DhcpStateMachine: WaitBeforeStartState{ when=-2ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:54.411  1035  7780 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-17 14:01:54.412  1035  1435 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-17 14:01:54.412  1035  1435 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 14:01:54.412  1035  1435 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 14:01:54.413  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.413   314   880 D CommandListener: Setting iface cfg
08-17 14:01:54.413   314   880 D CommandListener: Trying to bring up wlan0
08-17 14:01:54.414  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:54.414  1035  1435 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-17 14:01:54.414  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 14:01:54.419  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:54.420  1035  1435 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.421  1035  1435 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 14:01:54.421  1035  1435 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.421  1035  1435 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.422  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.422  1035  1435 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 14:01:54.422  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 14:01:54.422  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 14:01:54.423  1035  1483 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 14:01:54.423  1035  1435 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-17 14:01:54.423  1035  1435 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-17 14:01:54.423  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 14:01:54.423  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:54.423  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 14:01:54.424  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:54.425  1035  1435 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 14:01:54.425  1035  1435 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-17 14:01:54.425  7753  7753 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-17 14:01:54.425  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:54.425  1035  1435 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-17 14:01:54.425  1035  1435 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 14:01:54.432  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:54.432  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:54.433  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 14:01:54.436  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:54.442  1035  1435 D WifiNative-wlan0: SET ps 1: returned true
08-17 14:01:54.443  1035  1483 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-17 14:01:54.443  1035  1435 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 14:01:54.443  1035  1435 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 14:01:54.443  1035  1435 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 14:01:54.444  1035  1483 D ConnectivityService: ignoring duplicate network state non-change
08-17 14:01:54.446  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:54.446  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:54.447  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:54.447  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.450  1035  1483 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 14:01:54.450  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.451  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.451  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 14:01:54.451  1035  1483 D ConnectivityService: Adding iface wlan0 to network 101
08-17 14:01:54.451  1035  1435 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 14:01:54.461  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.461  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.461  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 14:01:54.462  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 14:01:54.466  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:54.469  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:54.469  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 14:01:54.469  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-17 14:01:54.471  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.472  1035  1483 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 14:01:54.472  1035  1483 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-17 14:01:54.473  1035  1483 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-17 14:01:54.473   314   880 E Netd    : netlink response contains error (File exists)
08-17 14:01:54.473  1035  1483 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-17 14:01:54.474  1035  1483 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-17 14:01:54.474  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.474  1035  1483 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-17 14:01:54.474  1035  1483 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-17 14:01:54.474  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.474  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 14:01:54.474  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:54.474  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 14:01:54.475  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.475  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 14:01:54.476  6708  6833 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 846)
08-17 14:01:54.476  6708  6833 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 846)
08-17 14:01:54.479  6708  6833 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 851)
08-17 14:01:54.480  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.480  6708  6833 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 14:01:54.480  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:01:54.480  6708  6833 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 852)
08-17 14:01:54.480  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 14:01:54.480  1035  1483 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 14:01:54.481  1035  1483 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 14:01:54.481  1035  1483 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-17 14:01:54.481  1035  1483 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 14:01:54.481  1035  1483 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:01:54.481  1035  1483 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:54.481  1035  1483 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-17 14:01:54.481  1035  7779 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:54.481  1035  7779 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-17 14:01:54.481  1035  1483 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:54.481  1035  7779 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:01:54.481  1035  1483 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-17 14:01:54.481  1035  1483 D ConnectivityService: currentScore = 0, newScore = 20
08-17 14:01:54.481  1035  1483 D ConnectivityService:    accepting network in place of null
08-17 14:01:54.481  1035  7779 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 14:01:54.481  1035  1483 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:54.482  1035  1435 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:54.482  1035  1435 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:01:54.482  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:54.482  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 14:01:54.482  1035  1483 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 14:01:54.482  1035  1483 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 14:01:54.483  1035  1483 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 14:01:54.483  1035  1483 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:01:54.483  1035  1483 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-17 14:01:54.483  1035  1483 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&,TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-17 14:01:54.483  1035  1483 D ConnectivityService: validation of new default Network = false
08-17 14:01:54.484  1035  1483 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-17 14:01:54.484  1035  1483 D DSQN    : enableDataServiceNotify 
08-17 14:01:54.484  1035  1483 D DSQN    : start dsqn bin
08-17 14:01:54.484   314  7801 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-17 14:01:54.487  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.487  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1585f5ad added. We now have 2 listener(s)
08-17 14:01:54.489  1035  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.490  1035  1483 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 14:01:54.490  1035  1483 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:54.490  1035  1483 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:54.491  1035  1483 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:54.491  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.491  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.491  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.491  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.491  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb280e2 added. We now have 9 listener(s)
08-17 14:01:54.491  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:54.492  1602  1815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 14:01:54.492  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-17 14:01:54.486  7802  7802 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:54.486  7802  7802 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 14:01:54.496  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 14:01:54.496  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 14:01:54.496  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 14:01:54.496  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:01:54.496  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 14:01:54.497  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.501  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:54.501  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:54.501  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 14:01:54.503  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:54.504  7802  7802 E DSQN    : DSQN ssw
,08-17 14:01:54.507  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:54.507  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:54.507  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:54.507  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:54.507  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:54.507  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.507  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:54.507  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:54.508  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.508  6708  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:54.509  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.509  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@349ee730 added. We now have 3 listener(s)
08-17 14:01:54.509  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:54.510  1035  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.510  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:54.511  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:54.514  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.514  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.514  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.514  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.514  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11393fa9 added. We now have 10 listener(s)
08-17 14:01:54.514  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:01:54.514  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:54.515  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:54.515  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:54.515  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.515  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.515  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:54.515  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.515  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1585f5ad removed from the list
08-17 14:01:54.515  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.515  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb280e2 removed from the list
08-17 14:01:54.515  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:54.515  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.516  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:54.517  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.517  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.517  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.517  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.518  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.518  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb280e2 not in the list
08-17 14:01:54.518  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.518  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.518  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-17 14:01:54.519  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.519  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.519  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.519  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11393fa9 removed from the list
08-17 14:01:54.519  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.519  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.519  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.519  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.519  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@349ee730 removed from the list
08-17 14:01:54.519  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.519  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c7bc92e added. We now have 2 listener(s)
08-17 14:01:54.520  1035  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.523  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.523  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.523  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.523  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.523  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f94dccf added. We now have 9 listener(s)
08-17 14:01:54.523  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:54.524  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:01:54.525  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:54.529  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:01:54.534  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:54.534  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:54.534  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:54.534  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:54.534  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:54.534  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.534  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:54.534  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:54.536  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.536  6708  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:54.536  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.536  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dbd2d65 added. We now have 3 listener(s)
08-17 14:01:54.536  1035  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.537   314  7801 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-17 14:01:54.537  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 14:01:54.537  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:54.538  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:54.538  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 14:01:54.538  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.538  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 14:01:54.538  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.540  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.540  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.540  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.540  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.540  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7f4a3a added. We now have 10 listener(s)
08-17 14:01:54.540  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:54.540  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:54.540  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:54.540  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:54.540  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:54.540  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:01:54.541  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:54.542  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:54.542  1818  7807 I CheckinService: active receiver: enabled
,08-17 14:01:54.551  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:01:54.551  1035  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.551  1818  7807 I CheckinService: Preparing to send checkin request
08-17 14:01:54.551  1818  7807 I EventLogService: Accumulating logs since 1471435224891
08-17 14:01:54.554  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:01:54.554  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:01:54.555  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:54.555  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:01:54.556  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:01:54.557  6708  6833 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:01:54.558  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:54.558  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:54.559  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:54.559  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:54.559  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:54.560  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.560  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.560  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:54.560  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.560  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c7bc92e removed from the list
08-17 14:01:54.560  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.560  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f94dccf removed from the list
08-17 14:01:54.560  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:54.560  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.560  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:54.560  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.560  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.561  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.561  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.561  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.561  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f94dccf not in the list
08-17 14:01:54.561  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.561  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.562  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.562  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:54.562  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:54.562  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.562  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispos,e
08-17 14:01:54.562  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7f4a3a removed from the list
08-17 14:01:54.562  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.562  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.562  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.562  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.562  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dbd2d65 removed from the list
08-17 14:01:54.563  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.563  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd83ae1 added. We now have 2 listener(s)
08-17 14:01:54.563  1035  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.564  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.564  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.564  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.564  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.565  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c07d006 added. We now have 9 listener(s)
08-17 14:01:54.565  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:54.566  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:01:54.567  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:54.567  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:54.567  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 14:01:54.569   314  7801 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-17 14:01:54.572  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:54.574  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:54.574  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:54.574  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:54.574  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:54.574  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:54.574  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.574  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:54.574  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:54.575  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.575  6708  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:54.575  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.575  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@160004f4 added. We now have 3 listener(s)
08-17 14:01:54.575  1035  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.575  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:54.576  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:54.579  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:01:54.579  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.579  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.579  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.579  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.579  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@283ca41d added. We now have 10 listener(s)
08-17 14:01:54.579  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:54.580  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:54.580  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:54.580  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:54.580  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:54.580  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:54.580  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:01:54.584  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:01:54.584  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.586  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 14:01:54.587  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:01:54.588  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:01:54.589  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:01:54.590  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:54.590  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:54.592  6708  6833 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:01:54.595  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:54.595  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:54.592  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:54.595  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:54.595  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:54.595  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.595  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.595  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:54.595  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.595  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd83ae1 removed from the list
,08-17 14:01:54.595  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.595  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c07d006 removed from the list
08-17 14:01:54.595  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:54.595  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.597  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.597  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.597  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.597  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.597  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.598  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c07d006 not in the list
08-17 14:01:54.598  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.598  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.598  1818  7807 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-17 14:01:54.598  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.599  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:54.599  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:54.599  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.599  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.599  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 14:01:54.599  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@283ca41d removed from the list
08-17 14:01:54.599  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.599  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.599  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.599  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.599  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@160004f4 removed from the list
08-17 14:01:54.599  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.600  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4927c60 added. We now have 2 listener(s)
08-17 14:01:54.602  1035  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.602  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:54.604  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothC,onnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.604  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.604  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.604  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.604  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26846519 added. We now have 9 listener(s)
08-17 14:01:54.604  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:54.605   314   879 D LGDataListener: argv[0]=dsqncommand
08-17 14:01:54.605   314   879 D LGDataListener: argv[1]=wlan0
08-17 14:01:54.605   314   879 D LGDataListener: argv[2]=1
08-17 14:01:54.605   314   879 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-17 14:01:54.606  1035  1109 D DSQN    : DSQM DsqnNotification wlan0  1
08-17 14:01:54.606  1035  1109 D DSQN    : start to monitor internet connection
08-17 14:01:54.608  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:54.608  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:01:54.610  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:54.613  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:54.613  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:54.613  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:54.613  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:54.613  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:54.613  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.613  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:54.613  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:54.614  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.614  6708  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:54.614  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.614  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30cc97bf added. We now have 3 listener(s)
08-17 14:01:54.615  1035  7780 D DhcpStateMachine: DHCPV4 request on wlan0
08-17 14:01:54.615  1035  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.616  1035  7780 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-17 14:01:54.616  1035  7780 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-17 14:01:54.616  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:54.606  7811  7811 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:54.606  7811  7811 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 14:01:54.618  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:54.618  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:54.619  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.619  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.619  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.619  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.619  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a12fe8c added. We now have 10 listener(s)
08-17 14:01:54.619  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:54.619  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start oper,ation: Should affect listening to advertisements only
08-17 14:01:54.619  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:01:54.620  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:01:54.620  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:54.620  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:01:54.623  7811  7811 I dhcpcd  : version 5.5.6 starting
,08-17 14:01:54.624  7811  7811 E dhcpcd  : get_duid: m
08-17 14:01:54.624  7811  7811 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-17 14:01:54.624  7811  7811 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-17 14:01:54.625  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:01:54.625  1035  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.627  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:54.628  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:54.628  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 14:01:54.628  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 14:01:54.629  6952  6952 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 14:01:54.630  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:01:54.631  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:54.632  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:54.632  6708  6833 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 14:01:54.633  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:54.634  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:54.634  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:54.634  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.634  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.634  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:54.634  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.634  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4927c60 removed from the list
08-17 14:01:54.634  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.634  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26846519 removed from the list
08-17 14:01:54.634  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:54.634  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.635  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.635  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.635  6708  6833 I org.thaliproject.p2p.bt,connectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.635  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.635  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.635  6907  6907 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 14:01:54.635  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26846519 not in the list
08-17 14:01:54.635  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.635  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:54.636  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.637  6708  6833 D BluetoothLeScanner: could not find callback wrapper
08-17 14:01:54.637  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:01:54.637  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.637  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.637  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a12fe8c removed from the list
08-17 14:01:54.637  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.637  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.637  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:01:54.637  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.637  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30cc97bf removed from the list
08-17 14:01:54.638  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.638  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bcf0db added. We now have 2 listener(s)
08-17 14:01:54.638  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 14:01:54.640  1035  7779 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 12:01:54 GMT], X-Android-Received-Millis=[1471435314639], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471435314604]}
08-17 14:01:54.640  1035  7779 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 14:01:54.640  1035  7779 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-17 14:01:54.640  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.640  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.640  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.640  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.640  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d377778 added. We now have 9 listener(s)
08-17 14:01:54.640  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:54.640  1035  1483 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-17 14:01:54.640  1035  1483 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 14:01:54.640  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:01:54.640  1035  1483 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:01:54.640  1035  1483 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:54.640  1035  1483 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 14:01:54.641  1035  1483 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-17 14:01:54.641  1035  1483 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 14:01:54.641  1035  1483 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:54.641  1035  1483 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:54.641  1035  1483 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:54.641  1035  1483 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabili,ties: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:54.641  1035  1435 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:54.641  1035  1435 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:01:54.641  1035  1483 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 14:01:54.641  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:01:54.642  1602  1815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 14:01:54.642  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:54.643  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 14:01:54.644  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:54.645  6708  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:01:54.645  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:01:54.645  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 14:01:54.645  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:01:54.645  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:01:54.645  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.645  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:01:54.645  6708  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:01:54.647  6708  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:01:54.647  6708  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:01:54.647  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:01:54.647  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@176a46b6 added. We now have 3 listener(s)
08-17 14:01:54.647  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 14:01:54.650  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:54.652  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:01:54.653  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 14:01:54.653  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:01:54.653  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:01:54.653  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:01:54.653  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fbfb7 added. We now have 10 listener(s)
08-17 14:01:54.653  6708  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:01:54.653  6708  6833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:01:54.653  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:01:54.654  6708  6833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:01:54.654  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.654  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.654  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:01:54.654  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.654  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33bcf0db removed from the list
08-17 14:01:54.654  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.654  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d377778 removed from the list
08-17 14:01:54.654  6708  6833 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:01:54.654  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.654  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.654  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.655  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:54.655  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.655  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.655  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.655  6708  6833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d377778 not in the list
08-17 14:01:54.655  6708,  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.655  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.656  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:01:54.656  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:01:54.656  6708  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:01:54.656  6708  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fbfb7 removed from the list
08-17 14:01:54.656  6708  6833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:01:54.656  6708  6833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:01:54.656  6708  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:01:54.656  6708  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:01:54.657  6708  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@176a46b6 removed from the list
08-17 14:01:54.657  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 14:01:54.657  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 14:01:54.658  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 14:01:54.658  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:01:54.658  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 14:01:54.658  6708  6833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:01:54.664  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 14:01:54.665  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.665  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 14:01:54.667  6708  7817 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 859, name: My test thread name)
08-17 14:01:54.667  6708  7817 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 859, thread name: My test thread name)
08-17 14:01:54.668  6708  7817 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 859, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 14:01:54.669  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 14:01:54.670  6708  7818 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 861, name: My test thread name)
08-17 14:01:54.670  6708  7818 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 861, thread name: My test thread name)
08-17 14:01:54.670  6708  7818 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 861, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 14:01:54.672  6708  6833 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 14:01:54.672  6708  6833 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 14:01:54.672  6708  6833 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 14:01:54.672  6708  6833 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 14:01:54.672  6708  6833 D com.test.thalitest.ThaliTestRunner: Total duration: 23064 ms
08-17 14:01:54.673  6708  6833 I jxcore-log: Total number of executed tests:  80
08-17 14:01:54.673  6708  6833 I jxcore-log: 
08-17 14:01:54.673  6708  6833 I jxcore-log: Number of passed tests:  80
08-17 14:01:54.673  6708  6833 I jxcore-log: 
08-17 14:01:54.673  6708  6833 I jxcore-log: Number of failed tests:  0
08-17 14:01:54.673  6708  6833 I jxcore-log: 
08-17 14:01:54.673  6708  6833 I jxcore-log: Number of ignored tests:  0
08-17 14:01:54.673  6708  6833 I jxcore-log: 
08-17 14:01:54.674  6708  6833 I jxcore-log: Total duration:  23064
08-17 14:01:54.674  6708  6833 I jxcore-log: 
08-17 14:01:54.674  6708  6833 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 14:01:54.674  6708  6833 I jxcore-log: 
08-17 14:01:54.674  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:54.674  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:54.674  6952  6952 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 14:01:54.675  6952  6952 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 14:01:54.675  6952  6952 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-17 14:01:54.681  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 14:01:54.682  7811  7811 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 14:01:54.682  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.682  6708  6833 I jxcore-log: 
08-17 14:01:54.682  7811  7811 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 14:01:54.682  7811  7811 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 14:01:54.682  7811  7811 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-17 14:01:54.683  7811  7811 D dhcpcd  : wlan0: sending REQUEST (xid 0x4c3a4420), next in 4.66 seconds
08-17 14:01:54.685  6907  6907 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 14:01:54.685  6708  6708 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 14:01:54.685  6907  6907 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-17 14:01:54.687  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.687  6708  6833 I jxcore-log: 
08-17 14:01:54.688  6889  6889 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 14:01:54.688  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.688  6708  6833 I jxcore-log: 
08-17 14:01:54.689  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.689  6708  6833 I jxcore-log: 
08-17 14:01:54.690  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.690  6708  6833 I jxcore-log: 
,08-17 14:01:54.691  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:01:54.691  6708  6833 I jxcore-log: 
08-17 14:01:54.691  6889  6889 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 14:01:54.693  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.693  6708  6833 I jxcore-log: 
08-17 14:01:54.694  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.694  6708  6833 I jxcore-log: 
08-17 14:01:54.695  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:01:54.695  6708  6833 I jxcore-log: 
08-17 14:01:54.695  6952  6952 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 14:01:54.695  6952  6952 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 14:01:54.696  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:01:54.696  6708  6833 I jxcore-log: 
08-17 14:01:54.696  6952  6952 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 14:01:54.696  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:01:54.696  6708  6833 I jxcore-log: 
08-17 14:01:54.696  6952  6952 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 14:01:54.696  6952  6952 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 14:01:54.697  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.697  6708  6833 I jxcore-log: 
08-17 14:01:54.697  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.697  6708  6833 I jxcore-log: 
08-17 14:01:54.698  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.698  6708  6833 I jxcore-log: 
08-17 14:01:54.698  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.698  6708  6833 I jxcore-log: 
08-17 14:01:54.699  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.699  6708  6833 I jxcore-log: 
08-17 14:01:54.699  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.699  6708  6833 I jxcore-log: 
08-17 14:01:54.700  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.700  6708  6833 I jxcore-log: 
08-17 14:01:54.700  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:01:54.700  6708  6833 I jxcore-log: 
08-17 14:01:54.701  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:01:54.701  6708  6833 I ,jxcore-log: 
08-17 14:01:54.701  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:01:54.701  6708  6833 I jxcore-log: 
08-17 14:01:54.702  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.702  6708  6833 I jxcore-log: 
08-17 14:01:54.702  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.702  6708  6833 I jxcore-log: 
08-17 14:01:54.703  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.703  6708  6833 I jxcore-log: 
08-17 14:01:54.703  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.703  6708  6833 I jxcore-log: 
08-17 14:01:54.704  6708  6833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:01:54.704  6708  6833 I jxcore-log: 
,08-17 14:01:54.711  7811  7811 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-17 14:01:54.712  7811  7811 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-17 14:01:54.712  7811  7811 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-17 14:01:54.712  7811  7811 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-17 14:01:54.712  7811  7811 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-17 14:01:54.712  7811  7811 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 14:01:54.712  7811  7811 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 14:01:54.712  7811  7811 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 14:01:54.712  7811  7811 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-17 14:01:54.733  1035  2027 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7823 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-17 14:01:54.782  7823  7823 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 14:01:54.782  7823  7823 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 14:01:54.804  7823  7823 I MultiDex: VM with version 2.1.0 has multidex support
,08-17 14:01:54.804  7823  7823 I MultiDex: install
08-17 14:01:54.804  7823  7823 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-17 14:01:54.813  7823  7823 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-17 14:01:54.817  2198  2198 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-17 14:01:54.826  2198  2198 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-17 14:01:54.827  2198  2198 D c       : Getting all permits...
,08-17 14:01:54.827  2198  2198 D a       : Opening database...
08-17 14:01:54.830  2198  2198 D a       : Opening database auth.proximity.permit_store...
08-17 14:01:54.832  2198  2198 D a       : Closing database...
08-17 14:01:54.876  7843  7843 D AndroidRuntime: 
08-17 14:01:54.876  7843  7843 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 14:01:54.879  7843  7843 D AndroidRuntime: CheckJNI is OFF
08-17 14:01:54.990  7843  7843 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 14:01:55.001  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-17 14:01:55.001  1035  1092 I ActivityManager: Killing 6708:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-17 14:01:55.017  1035  7780 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-17 14:01:55.018  1035  7780 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-17 14:01:55.019  1035  7780 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 14:01:55.019  1035  7780 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-17 14:01:55.019  1035  7780 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-17 14:01:55.019  1035  7780 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 14:01:55.019  1035  7780 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-17 14:01:55.019  1035  7780 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-17 14:01:55.020  1035  7780 D DhcpStateMachine: RunningState
08-17 14:01:55.057  1035  1575 I WindowState: WIN DEATH: Window{1bf6e351 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-17 14:01:55.058  1035  1473 D WifiService: Client connection lost with reason: 4
,08-17 14:01:55.068  1035  1575 D InputDispatcher: Window went away: Window{1bf6e351 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 14:01:55.233  7823  7842 D LgDataFeature: LgDataFeature() Constructor: none
08-17 14:01:55.233  7823  7842 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 14:01:55.239  1035  1092 I ActivityManager:   Force finishing activity ActivityRecord{3727eadf u0 com.test.thalitest/.MainActivity t6}
,08-17 14:01:55.261   342   351 E GBMv2   : DFP En is all cleared set to be enabled
,08-17 14:01:55.262  1035  1890 W ActivityManager: Spurious death for ProcessRecord{354054e9 6708:com.test.thalitest/u0a118}, curProc for 6708: null
08-17 14:01:55.263  1035  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-17 14:01:55.266  1035  1124 I ActivityManager:   Force finishing activity ActivityRecord{3727eadf u0 com.test.thalitest/.MainActivity t6 f}
08-17 14:01:55.266  1035  1124 W ActivityManager: Duplicate finish request for ActivityRecord{3727eadf u0 com.test.thalitest/.MainActivity t6 f}
,08-17 14:01:55.294  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-17 14:01:55.294  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-17 14:01:55.295  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2800fed7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-17 14:01:55.295  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-17 14:01:55.295  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{75c33c4 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-17 14:01:55.296  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-17 14:01:55.302  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-17 14:01:55.303  4660  4660 I art     : Explicit concurrent mark sweep GC freed 720(42KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 318us total 25.796ms
08-17 14:01:55.303  2033  2108 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-17 14:01:55.311  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-17 14:01:55.324  2488  2687 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 14:01:55.325  1035  1378 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-17 14:01:55.325  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-17 14:01:55.327  3823  3823 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-17 14:01:55.331  4552  4552 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-17 14:01:55.331  4552  4552 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-17 14:01:55.331  4552  4552 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-17 14:01:55.331  4552  4552 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
,08-17 14:01:55.331  4552  4552 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:01:55.331  4552  4552 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:01:55.331  4552  4552 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:01:55.332  4552  4552 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:01:55.332  4552  4552 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:55.333  7581  7581 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-17 14:01:55.333  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 14:01:55.333  4552  4552 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:01:55.333  4552  4552 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:01:55.333  4552  4552 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:01:55.357  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-17 14:01:55.372  1035  1994 V SIM_STK : Menu title from STK is T-Mobile
,08-17 14:01:55.401  1035  1035 D administrator: Handling package changes for user 0
,08-17 14:01:55.409  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-17 14:01:55.411  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-17 14:01:55.413  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-17 14:01:55.414  3823  4544 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-17 14:01:55.414  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-17 14:01:55.464  1035  1970 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7875 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-17 14:01:55.469  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-17 14:01:55.474  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:01:55.474  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
08-17 14:01:55.477  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-17 14:01:55.497  1035  1647 V SIM_STK : Menu title from STK is T-Mobile
,08-17 14:01:55.502  1035  1435 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:01:55.503  1035  1435 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:01:55.504  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-17 14:01:55.510  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-17 14:01:55.512  1035  1435 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:01:55.512  1035  1435 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:01:55.513  1035  1435 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:01:55.513  1035  1435 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 14:01:55.514  1035  1483 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-17 14:01:55.514  1035  1483 D ConnectivityService: identical MTU - not setting
08-17 14:01:55.514  1035  1483 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 14:01:55.514  1035  1483 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 14:01:55.514  1035  1483 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:01:55.514  1035  1483 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:55.515  1035  1483 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 14:01:55.515  1602  1815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-17 14:01:55.526  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-17 14:01:55.526  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-17 14:01:55.527  1035  1575 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 14:01:55.527  7581  7581 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-17 14:01:55.539  2198  2198 I ConfigService: onCreate
08-17 14:01:55.539  2198  2198 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-17 14:01:55.545  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-17 14:01:55.545  1870  1870 D SplitUIManager: split_name #11 / not available #0
,08-17 14:01:55.546  1870  1870 D SplitUIService: removed split : 
08-17 14:01:55.547  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-17 14:01:55.548  3823  3839 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 14:01:55.548  3823  4544 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-17 14:01:55.548  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , display: false
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , animation: false }
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , display: false
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , animation: false }
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , create_time: 1471007226523
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , display: false
08-17 14:01:55.552  2033  2033 I GBoardWebViewUtils: , animation: false }
08-17 14:01:55.553  2198  2198 I ConfigService: onBind returning update interface
08-17 14:01:55.554  2198  2198 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-17 14:01:55.554  2198  2198 I ConfigService: onBind returning config service
08-17 14:01:55.560  2033  7894 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-17 14:01:55.566  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-17 14:01:55.566  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 14:01:55.566  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-17 14:01:55.568  2198  2198 I ConfigService: onDestroy
08-17 14:01:55.570  1035  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-17 14:01:55.581  1818  7895 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-17 14:01:55.585  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 14:01:55.586  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-17 14:01:55.588  7875  7875 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-17 14:01:55.592  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-17 14:01:55.592  1870  1870 I SplitUIService: split app #11
08-17 14:01:55.619  1035  1050 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7899 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-17 14:01:55.629  1602  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 14:01:55.629  1602  1656 D KeyguardModel: createShortcutInfo...
08-17 14:01:55.630  1602  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 14:01:55.630  1602  1656 D KeyguardModel: createShortcutInfo...
08-17 14:01:55.633  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-17 14:01:55.633  1602  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:01:55.634  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-17 14:01:55.634  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-17 14:01:55.642  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:01:55.642  1602  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-17 14:01:55.651  2033  2047 I art     : Background sticky concurrent mark sweep GC freed 1827(107KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 79MB/79MB, paused 9.790ms total 15.632ms
08-17 14:01:55.651  1602  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-17 14:01:55.651  1602  1656 D KeyguardModel: createShortcutInfo...
,08-17 14:01:55.657  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-17 14:01:55.658  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-17 14:01:55.658  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:01:55.658  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:01:55.659  1602  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-17 14:01:55.659  1602  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 14:01:55.659  1602  1656 D KeyguardModel: createShortcutInfo...
08-17 14:01:55.670  1602  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:01:55.670  1602  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 14:01:55.670  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-17 14:01:55.670  1602  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 14:01:55.671  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:01:55.671  1602  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-17 14:01:55.672  1818  7920 I PeopleContactsSync: CP2 sync disabled
,08-17 14:01:55.673  1602  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-17 14:01:55.673  1602  1656 D KeyguardModel: createShortcutInfo...
08-17 14:01:55.679  1818  4811 I Icing   : doRemovePackageData com.test.thalitest
08-17 14:01:55.682  1035  1994 I ActivityManager: Killing 7119:com.lge.email/u0a23 (adj 15): empty #17
,08-17 14:01:55.684   332   413 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-17 14:01:55.685  6036  7917 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-17 14:01:55.685  3228  7923 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-17 14:01:55.714  7899  7899 I AppUp4:AppBoxCP: onCreate
08-17 14:01:55.714  7899  7899 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-17 14:01:55.718  7922  7922 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-17 14:01:55.720  7899  7899 I AppUp4:DB:  setFingerPrint start
08-17 14:01:55.720  7899  7899 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-17 14:01:55.727  7899  7899 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-17 14:01:55.727  7899  7899 I AppUp4:DB:  SDK version = 21
08-17 14:01:55.727  7899  7899 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-17 14:01:55.737  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-17 14:01:55.740  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:01:55.742  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-17 14:01:55.743  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-17 14:01:55.745  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-17 14:01:55.746  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-17 14:01:55.764  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-17 14:01:55.764  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-17 14:01:55.765  2033  5889 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-17 14:01:55.765  2033  5889 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-17 14:01:55.768  7922  7922 I dex2oat : dex2oat took 48.953ms (threads: 4)
08-17 14:01:55.776  7823  7842 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:01:55.776  7823  7842 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:01:55.776  7823  7842 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:01:55.776  7823  7842 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:01:55.776  7823  7842 I Adreno-EGL: Remote Branch: 
08-17 14:01:55.776  7823  7842 I Adreno-EGL: Local Patches: 
08-17 14:01:55.776  7823  7842 I Adreno-EGL: Reconstruct Branch: 
,08-17 14:01:55.779  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-17 14:01:55.780  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-17 14:01:55.780  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:01:55.787  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-17 14:01:55.791  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-17 14:01:55.791  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-17 14:01:55.798  1035  1647 W libprocessgroup: failed to open /acct/uid_10023/pid_7119/cgroup.procs: No such file or directory
08-17 14:01:55.802  7899  7899 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-17 14:01:55.804  1602  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 14:01:55.804  1602  1656 D KeyguardModel: createShortcutInfo...
,08-17 14:01:55.804  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{67adbc u0 com.lge.launcher2/.Launcher t5} time:150084
08-17 14:01:55.805  2584  2584 D [Concierge]Service: onStartCommand(). Type : 8
08-17 14:01:55.805  2584  2584 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-17 14:01:55.807  2033  2033 D [Concierge]WidgetView: change position of spinner
08-17 14:01:55.808  2584  2584 D [Concierge]Service: Update widget ID : 11
08-17 14:01:55.808  1602  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 14:01:55.808  1602  1656 D KeyguardModel: createShortcutInfo...
08-17 14:01:55.808  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1471435315808
08-17 14:01:55.809  2584  2584 D [Concierge]Service: onStartCommand(). Type : 0
08-17 14:01:55.810  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:01:55.810  1602  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-17 14:01:55.812  1602  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-17 14:01:55.812  1602  1656 D KeyguardModel: createShortcutInfo...
08-17 14:01:55.814  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:01:55.814  1602  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-17 14:01:55.817  1602  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 14:01:55.817  1602  1656 D KeyguardModel: createShortcutInfo...
,08-17 14:01:55.818  1602  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 14:01:55.818  1602  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-17 14:01:55.820  1818  7919 W GmsApplication: Using Auth Proxy for data requests.
08-17 14:01:55.820  1602  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-17 14:01:55.820  1602  1656 D KeyguardModel: createShortcutInfo...
08-17 14:01:55.821  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 45148757
08-17 14:01:55.821  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-17 14:01:55.822  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-17 14:01:55.824  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3250bb30
08-17 14:01:55.824  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-17 14:01:55.825  1818  7919 W GmsApplication: Using Auth Proxy for data requests.
08-17 14:01:55.825  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-17 14:01:55.826  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:01:55.829  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-17 14:01:55.829  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-17 14:01:55.832  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-17 14:01:55.832  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-17 14:01:55.832  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-17 14:01:55.833  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471435193988, New one : 1471435315808
08-17 14:01:55.833  2033  2033 D [Concierge]WidgetView: Unregister all receivers
08-17 14:01:55.833  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-17 14:01:55.834  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:01:55.835  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-17 14:01:55.836  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-17 14:01:55.837  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-17 14:01:55.838  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-17 14:01:55.839  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-17 14:01:55.844  1035  1124 I art     : Explicit concurrent mark sweep GC freed 85000(4MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 43MB/65MB, paused 1.895ms total 360.650ms
,08-17 14:01:55.845  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:01:55.845  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:01:55.854  7899  7899 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-17 14:01:55.872  1035  2027 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7933 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-17 14:01:55.878  1035  2027 I ActivityManager: Killing 7168:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-17 14:01:55.891  7823  7842 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:01:55.891  7823  7842 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:01:55.891  7823  7842 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:01:55.891  7823  7842 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:01:55.891  7823  7842 I Adreno-EGL: Remote Branch: 
08-17 14:01:55.891  7823  7842 I Adreno-EGL: Local Patches: 
08-17 14:01:55.891  7823  7842 I Adreno-EGL: Reconstruct Branch: 
,08-17 14:01:55.903  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:01:55.905  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-17 14:01:55.912  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-17 14:01:55.912  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-17 14:01:55.914  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 14:01:55.931  7843  7843 D AndroidRuntime: Shutting down VM
,08-17 14:01:55.941  7823  7842 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 14:01:55.941  7823  7842 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 14:01:55.941  7823  7842 I Adreno-EGL: Build Date: 12/12/14 금
08-17 14:01:55.941  7823  7842 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 14:01:55.941  7823  7842 I Adreno-EGL: Remote Branch: 
08-17 14:01:55.941  7823  7842 I Adreno-EGL: Local Patches: 
08-17 14:01:55.941  7823  7842 I Adreno-EGL: Reconstruct Branch: 
08-17 14:01:55.958  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-17 14:01:55.960  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@27d95cf6 time:150239
,08-17 14:01:56.044  1035  1958 W libprocessgroup: failed to open /acct/uid_10046/pid_7168/cgroup.procs: No such file or directory
08-17 14:01:56.052  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-17 14:01:56.056  7933  7933 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:01:56.056  7933  7933 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:01:56.056  7933  7933 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-17 14:01:56.057  7933  7933 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-17 14:01:56.057  7933  7933 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 14:01:56.073  1035  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7950 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-17 14:01:56.080  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-17 14:01:56.095  2033  2871 I GBoardtInterface: onReloaded()
,08-17 14:01:56.101  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-17 14:01:56.103  3823  3839 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 14:01:56.105  3823  3838 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 14:01:56.110   314  7969 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 14:01:56.110   314  7969 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-17 14:01:56.110  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-17 14:01:56.111  3823  4544 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-17 14:01:56.111  3823  4544 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-17 14:01:56.114  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-17 14:01:56.115  3823  4544 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-17 14:01:56.115  3823  4544 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-17 14:01:56.115  3823  4544 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-17 14:01:56.116  3823  4544 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-17 14:01:56.116  3823  3839 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 14:01:56.118  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-17 14:01:56.118  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-17 14:01:56.120  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-17 14:01:56.120  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-17 14:01:56.122  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-17 14:01:56.122  1035  1778 I ActivityManager: Killing 7188:com.android.chrome/u0a57 (adj 15): empty #17
08-17 14:01:56.122  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-17 14:01:56.144  7933  7933 I SystemConfig: BUILD Country: EU
08-17 14:01:56.144  7933  7933 I SystemConfig: BUILD Operator: OPEN
,08-17 14:01:56.167   314  7969 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-17 14:01:56.171  1035  2003 W libprocessgroup: failed to open /acct/uid_10057/pid_7188/cgroup.procs: No such file or directory
08-17 14:01:56.184  1035  1994 I ActivityManager: Killing 7212:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-17 14:01:56.262  1035  1575 W libprocessgroup: failed to open /acct/uid_10062/pid_7212/cgroup.procs: No such file or directory
,08-17 14:01:56.267  7933  7971 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-17 14:01:56.267  7933  7971 I SystemConfig: existFile = false
08-17 14:01:56.267  7933  7971 I SystemConfig: canReadFile = false
08-17 14:01:56.268  7933  7971 I SystemConfig: systemFeature RCS result false
08-17 14:01:56.268  7933  7971 D SystemConfig: refreshRcsSupport() :false
08-17 14:01:56.270  2352  7974 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-17 14:01:56.300  1035  1050 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7975 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-17 14:01:56.308  1818  7807 I CheckinTask: Sending checkin request (7850 bytes)
,08-17 14:01:56.332  7975  7975 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:01:56.332  7975  7975 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 14:01:56.333  7975  7975 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 14:01:56.333  7975  7975 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:01:56.370  7975  7975 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:0,1:56.370  7975  7975 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-17 14:01:56.370  7975  7975 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:01:56.371  7975  7975 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:01:56.371  7975  7975 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:01:56.371  7975  7975 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:56.371  7975  7975 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:01:56.371  7975  7975 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:01:56.371  7975  7975 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-17 14:01:56.378  7975  7975 E SQLi,teDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:01:56.378  7975  7975 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:01:56.378  7975  7975 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-17 14:01:56.379  7975  7975 E AndroidRuntime: FATAL EXCEPTION: main
08-17 14:01:56.379  7975  7975 E AndroidRuntime: Process: com.lge.email, PID: 7975
08-17 14:01:56.379  7975  7975 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 14:01:56.,379  7975  7975 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-17 14:01:56.379  7975  7975 E AndroidRuntime: 	... 11 more
,08-17 14:01:56.383  7975  7975 I Process : Sending signal. PID: 7975 SIG: 9
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: Can't write: system_app_crash
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 14:01:56.384  1035  7993 E DropBoxManagerService: 	... 5 more
08-17 14:01:56.431  2033  2871 I GBoardtInterface: exportHTML()

```
